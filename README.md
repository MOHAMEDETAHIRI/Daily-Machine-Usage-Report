# Daily Machine Usage Report

## Situation Problem
I am working at an IT company that requires the creation of a **daily report** to track **machine usage**. The report needs to identify which users are logged into which machines at any given time.

### Problem Statement
The company’s network logs user activity, including **login** and **logout** events for different machines. However, there is currently no system in place to analyze these logs and produce a concise, readable report of current users per machine.

## Resources Available
The company provides event logs with the following information:
- **Date**: The date and time when the event occurred.
- **User**: The name of the user who logged in or out.
- **Machine**: The machine where the event took place.
- **Event Type**: Specifies whether the event was a login or a logout.

## Brainstorming
- **Event Chronology**: Events should be sorted by time to ensure the system processes them in order.
- **User Tracking**: For each machine, track which users are currently logged in and remove users when they log out.
- **Report Generation**: Create a readable summary of the current status of each machine, showing the users that are still logged in.

## Solution
I developed a Python script that processes a list of login/logout events and produces a report showing the current users for each machine. Here’s how the solution works:
1. **Sorting Events**: Events are sorted chronologically to ensure correct processing.
2. **Tracking Machine Usage**: The script updates the list of logged-in users for each machine.
3. **Generating Report**: The output lists each machine and its currently logged-in users.

## What Things I Used
- **Python Programming**: Core concepts such as classes, functions, lists, dictionaries, and control flow.
- **Sorting Algorithms**: Built-in sorting to order events by date.
- **Custom Classes**: Used a class structure to represent events.

## What I Learned So Far
- **Event-Driven Programming**: How to handle sequential event logs and track states over time.
- **Data Structures**: Using dictionaries and sets to manage and manipulate user data efficiently.
- **Problem-Solving**: Breaking down the problem into smaller tasks like sorting, tracking, and reporting.
- **Python Class Usage**: Improved understanding of object-oriented programming.
