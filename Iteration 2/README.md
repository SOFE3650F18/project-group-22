# Iteration 2

## Step 2: Iteration Goal and Select Drivers

The goal of this iteration is to refine the user interface

The selected drivers are:

* QA-4
* CON-3
* CON-4

## Step 3: Elements to Decompose

The elements that we want to decompose is the entire front-end. We want to make sure that we have a simple, but functional design.

## Step 4: Design Concept

| Design Decisions          | Rationale                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Use an MVC design pattern | Using this design pattern was decided since it allows us to update the UI if something in the database changes. For this we decided to use Angular as our web framework. This also means that we can help support other browsers using its built-in tools such as polyfills </br> **Discarded Alternatives**: Another option was using React.js, but we wanted to make sure that we would minimize the time ensuring that this application works on other browsers |

## Step 5: Instantiate Architectural Elements, Allocate Responsibilities, and Define Interfaces

| Design Decision     | Rationale                                                                                                                                                                                          |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Login Page          | The users (students and lecturers) will have to sign into a login page before they can access the rest of the application.                                                                         |
| Course organization | The homepage after logging in will require a single click to access the course, a second click to access a subfolder containg content such as lectures, and then a final click to open the lecture |

## Step 6: Sketch Design Decisions

* Login sequence diagram
* Component Diagram for frontend
* Deployment Diagram

## Step 7: Update Kanban
