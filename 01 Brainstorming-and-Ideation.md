# Brainstorming & Ideation

## Project Title
Implement Client Script & UI Policy (Incident)

## Problem Identification

Incident records require accurate and complete information.
Manual data entry can result in incomplete or incorrect information.

This project uses ServiceNow Client Scripts and UI Policies
to control Incident form behavior and improve data integrity.

## Proposed Solution

The proposed solution is to use:

1. UI Policy
2. UI Policy Action
3. onChange Client Script
4. onSubmit Client Script
5. onCellEdit Client Script

## Main Idea

When an Incident has High Impact:

- Assignment Group should be mandatory.
- Urgency should become read-only.
- Urgency should automatically be set to High.
- Assigned To should be mandatory before saving.
- State should not be changed through list editing.

## Expected Benefits

- Improved data accuracy
- Better Incident validation
- Reduced incorrect submissions
- Consistent Incident management
- Better user experience
