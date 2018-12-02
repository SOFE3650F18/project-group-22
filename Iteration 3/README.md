# Iteration 3

## Step 1

* UC-2
* UC-9
* UC-12
* QA-2
* QA-4

## Step 2

Our goal for this iteration is to increase the security, relalibilty, and user friendliness of the CMS

## Step 3

### Elements to refine

The elements we need to refine for this iteration are the security of the frontend, as well as the user friendiness of the user interface.

The elements we will refine are the login pages, the handling of sensitive data and user permissions

## Step 4
| Design Decisions and Location | Rationale and Assumptions                                                                                                                                                                                                                                                                                                                               |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Authentification              | By using a school login or a third party authentification service, we can assign each student and instructor their own account with permissions set for each of them so they can access the services they need without affecting anyone else's data when doing so. This also protects against non students accessing the database and changing anything |
| Permissons                    | By using a permissions system, we can make it so that students are only bale to view their own grades, while instructors can view the whole class, as well and change grades as they wish                                                                                                                                                               |
| Backup web server             | By hosting a backup server that pulls data from the AWS server periodically, we can have a snapshot of the server in the case it goes down. Any changes would have to be queued, but the server would still be able to be checked for data if the server goes down at an important juncture during the school year                                      |

## Step 5

| Element               | Responsibilities                                                                                       |
| --------------------- | ------------------------------------------------------------------------------------------------------ |
| Authentication Portal | Checks to see to if the username and password combination is correct, and to see if the account exists |

## Step 6
![](https://github.com/SOFE3650F18/project-group-22/blob/master/Iteration%203/Drawing2.png)
