# UI Policy - High Impact Control

## Name
High Impact Control

## Table
Incident

## Active
true

## Condition

Impact is 1 - High

## UI Policy Action

Field:
Assignment Group

Mandatory:
true

Reverse if false:
true

## Purpose

When an Incident has High Impact, the Assignment Group
must be provided.function onChange(control, oldValue, newValue, isLoading) {

    if (isLoading || newValue == '') {
        return;
    }

    if (newValue == '1') {
        g_form.setValue('urgency', '1');
        g_form.addInfoMessage(
            'Urgency set to High for High impact incident.'
        );
    }
}function onSubmit() {

    if (g_form.getValue('impact') == '1' &&
        g_form.getValue('assigned_to') == '') {

        g_form.showErrorBox(
            'assigned_to',
            'Assigned To is mandatory for High impact incidents.'
        );

        return false;
    }

    return true;
}function onCellEdit(sysIDs, table, oldValues, newValue, callback) {

    alert(
        'State cannot be updated using list editing. Please open the Incident.'
    );

    callback(false);
}
