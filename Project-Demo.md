# Project Demonstration

## Project Name

Implement Client Script & UI Policy (Incident)

## Purpose

The purpose of this project is to improve data integrity
and enforce validation rules on ServiceNow Incident records.

## Project Benefits

- Ensures required information is entered.
- Automatically updates Urgency.
- Prevents invalid Incident submission.
- Controls field behavior dynamically.
- Prevents unwanted State changes through list editing.

## Demo Flow

### Step 1
Open ServiceNow Incident application.

### Step 2
Create a new Incident.

### Step 3
Set Impact = High.

### Step 4
Show that Assignment Group becomes mandatory.

### Step 5
Show that Urgency becomes read-only.

### Step 6
Show that Urgency is automatically set to High.

### Step 7
Leave Assigned To empty and click Submit.

### Step 8
Show the validation error.

### Step 9
Fill Assigned To and submit again.

### Step 10
Show successful save.

### Step 11
Change Impact from High to Medium.

### Step 12
Show that the UI Policy condition is reversed.

### Step 13
Open Incident list.

### Step 14
Try editing State directly from the list.

### Step 15
Show the alert message and blocked update.

## Final Output

The completed ServiceNow Incident configuration
successfully demonstrates UI Policy and Client Script
based validation and field control.
