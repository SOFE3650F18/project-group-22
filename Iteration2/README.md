# Iteration 2

## Step 1

### Drivers

#### Functional

* UC-1
* UC-2
* UC-5
* UC-7
* UC-8
* UC-10
* QA-3

## Step 2: Iteration Goal

The goal of this iteration is to set up the server and database framework in order to fulfill the remaining use cases that have not yet been addressed

## Step 3

### Elements to refine

In this iteration, we are refining the backend of the CMS system

## Step 4

| Design Decisions and Location | Rationale and Assumptions |
|------------------------------|--------------------------|
| PostgreSQL | PostgreSQL is a powerful database management systems that has an emphasis on extendability and standards compliance, which makes it a good choice for a system that is being used in a regulated environment |
| Amazon Web Services(AWS) | AWS allows us to host a server without having to implement the infastructure into the university. By using AWS, we can have our server set up for us, and we dont have to worry about scaling our database in the future, because we can just pay for more space. |

## Step 5

| Element | Responsibilities |
|---------|------------------|
| Server Connector | Communicates with our AWS server in order to retrieve data via API calls|
| Event Controller | Process events that are received from the user devices |

## Step 6

![](https://github.com/SOFE3650F18/project-group-22/blob/master/Iteration2/Drawing1.png)
