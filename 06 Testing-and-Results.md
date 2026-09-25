# Project Testing

## Test Case 1 - Mandatory Enforcement

### Steps

1. Open Incident → Create New.
2. Set Impact to High.
3. Leave Assigned To empty.
4. Click Submit.

### Expected Result

- Incident should not be saved.
- Error message should be displayed.
- Assigned To should be required.

---

## Test Case 2 - Successful Save

### Steps

1. Open an Incident.
2. Set Impact to High.
3. Fill Assigned To.
4. Click Submit.

### Expected Result

- Incident should save successfully.
- Urgency should be automatically set to High.
- Configured UI Policy actions should work.

---

## Test Case 3 - Reverse Condition

### Steps

1. Open an Incident with Impact = High.
2. Change Impact to Medium.

### Expected Result

- Assignment Group should no longer be mandatory.
- Urgency should become editable.

---

## Test Case 4 - List Edit Blocking

### Steps

1. Navigate to Incident → All.
2. Double-click the State field.
3. Try to change the value.

### Expected Result

- Alert message should appear.
- State should remain unchanged.

---

## Test Case 5 - Form Based Update

### Steps

1. Open an Incident.
2. Change State from the Incident form.
3. Click Update.

### Expected Result

- State change should be saved successfully.
