# Iteration 3

## Step 2: Iteration Goal and Select Drivers

The goal of this iteration is to refine the security of our system

The selected drivers are:

* UC-9
* QA-2
* CON-3
* CON-4

## Step 3: Elements to Decompose

The element that we want to decompose is the security of our system.

## Step 4: Design Concept

| Design Decision              | Rationale                                                                                                                                                                                                                  |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Authentication | We will be using the school's authentication system for this application. It allows the users to be tied to the school's secondary database, as well as ensuring that new users can access the CMS application. Storage of the user will still be done in the CMS database for collection of information (i.e. grades).  |
|

## Step 5: Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces

| Design Decisions | Rationale   |
| ---------------- | ----------- |
| Regular Backups | Using the AWS platform we can create regularly scheduled backups of the data. This ensures that we never lose information in case of hardware failure or corruption |

## Step 6: Sketch Design Decisions

![](https://github.com/SOFE3650F18/project-group-22/blob/redo/Iteration%203/Untitled%20Diagram.png)

An updated deployment diagram with our new design decisions


## Step 7: Update Kanban
