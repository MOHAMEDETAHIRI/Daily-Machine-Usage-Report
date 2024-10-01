# Daily Machine Usage Report

## Problem Statement
I am working at an IT company that requires the creation of a daily report to track machine usage. The report should identify which users are connected to which machines.

## Note
The company has a system that stores all events occurring in the network. This system logs any user login or logout activity, including timestamps for each event.

## Class Materials
The event logs will contain the following information:
- **Date**: When the user logged in
- **Machine**: The name of the machine used
- **User**: The name of the user involved
- **Event Type**: Indicates whether the event is a login or logout

## Event Structure
Each event is represented with the following attributes:
```plaintext
events_type {
    date
    user
    machine
    type
}

