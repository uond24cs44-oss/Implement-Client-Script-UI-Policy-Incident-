# Project Design

## System

ServiceNow Incident Management

## Input

Incident fields:

- Impact
- Assignment Group
- Assigned To
- Urgency
- State

## Processing

### Condition 1

Impact = High

↓

UI Policy is triggered

↓

Assignment Group becomes Mandatory

↓

Urgency becomes Read-only


### Condition 2

Impact = High

↓

onChange Client Script

↓

Urgency = High


### Condition 3

Impact = High AND Assigned To is Empty

↓

onSubmit Client Script

↓

Prevent Save


### Condition 4

User edits State from List

↓

onCellEdit Client Script

↓

Block Update


## Output

The Incident record follows the configured
validation and field behavior rules.
