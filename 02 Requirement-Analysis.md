# Requirement Analysis

## Functional Requirements

### FR1 - High Impact UI Policy

When Impact is set to High:

- Assignment Group must be  mandatory.
- The UI Policy must be active.
- Reverse if false must be enabled.

### FR2 - Urgency Control

When Impact is High:

- Urgency field must become read-only.

### FR3 - Automatic Urgency

When Impact changes to High:

- Urgency must automatically become High.
- An informational message should be displayed.

### FR4 - Save Validation

When Impact is High and Assigned To is empty:

- The Incident must not be saved.
- An error message must be displayed.

### FR5 - List Editing Restriction

Users must not be allowed to directly change
the State field from the Incident list.

## Non-Functional Requirements

- The solution should be simple.
- The solution should be easy to maintain.
- The configuration should work only on Incident records.
- The system should provide clear validation messages.

## Technology

Platform: ServiceNow

Main Components:
- UI Policy
- UI Policy Action
- Client Script
- Incident Management
