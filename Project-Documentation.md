# Project Documentation

## Project Title

Implement Client Script & UI Policy (Incident)

## Introduction

This project demonstrates the implementation of UI Policies
and Client Scripts in ServiceNow Incident Management.

## Objective

The objective is to enforce data integrity on Incident records
using client-side controls.

## Technologies Used

- ServiceNow
- JavaScript
- UI Policies
- UI Policy Actions
- Client Scripts
- Incident Management

## Implemented Features

### 1. High Impact Control

Assignment Group becomes mandatory when Impact is High.

### 2. Urgency Control

Urgency becomes read-only when Impact is High.

### 3. Automatic Urgency

Urgency is automatically set to High.

### 4. Save Validation

Incident cannot be saved when Assigned To is empty
for a High Impact Incident.

### 5. List Edit Restriction

State cannot be changed directly using list editing.

## Conclusion

The project demonstrates how UI Policies and Client Scripts
can be used together to enforce dynamic field behavior,
automate updates, and prevent incorrect data submission.

The implementation improves data consistency and
Incident form usability.
