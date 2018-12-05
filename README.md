# ADD Group 22

project-group-22 created by GitHub Classroom

## Inputs

### Use Cases

**UC-1: Display Course Information**
The system should display static and dynamic course information. Lecturers or Administrators can store, modify or delete the information as needed. Lecturers can also view other courses information.

**UC-2: Collect User Information**
The system should collect information about the students and lecturers. A user may edit their personal information.

**UC-3: Display History**
The system should display the history of a course or an attended course

**UC-4: Collaborative Environment**
Students should be able to collaborate within a course through a variety of methods. They will mostly interact in a Team setting. This includes sharing files, messaging each other and submitting assignments for the team. They can also view the users in the team, or any grades for the team. A Lecturer or Administrator can create, update or remove teams, and can choose rules and govern the team settings.

**UC-5: Submissions**
Faculty should be able to create assignment submission dropboxes. Students can upload submissions either by text or uploading files in the respective dropbox. Maintainers can limit the size of the files uploaded if space is an issue

**UC-6: Messaging**
Lecturers should be able to message students via announcements or private messaging. The system should allow for multiple recipients, and can support mail templates. The lecturer can also message all students at the push of a single button. Students can modify their notification behaviour regarding messages and announcements.

**UC-7: Enrollment**
Lecturers and Administrators should be able to specify the rules and policies of courses based on grade, first-come-first-serve basis and department. Students can subscribe to a course, and if they do not qualify or are over the size limit they can be rejected by the system.

**UC-8: Grades**
Lecturers can upload the grades for a given submission. Students should be able to verify their grades. Administrators and Lecturers can compare and view grades and statistics of a course with other courses.

**UC-9: Login**
Users should be able to sign in with a password. They can also edit, or go through a password recovery process if they forget it

**UC-10: Course Content**
Lecturers should be able to upload and prepare lecture content. They can also prepare schedules and upload course material. Roster information can be imported into the course. Maintainers can limit the space for a given course

**UC-11: Backups**
Maintainers can create backups and restore from a partial backup or a full backup. The system also syncs with secondary university systems.

**UC-12: Administrative Privileges**
Administrators shall be able to create, update, and delete courses, assign principle lecturers, and prerequisites for a course. They are also able to calculate the statistics of a course, and calculate the number of passed students. They can view information of students and lecturers as well

### Quality Attributes

**QA-1: Privacy**
The system shall protect the user’s privacy, and prevent students from viewing grades of other people.

**QA-2: Security**
The system should be secure and only allow authorized users to view and modify data that belongs to them, and modify how much information others can see.

**QA-3: Availability**
The system should almost always be available. Whenever there is planned downtime, it should be during low-intensity hours and cannot be for more than 4 hours/month

**QA-4: User Friendliness**
The system should be friendly, have multiple language support, have a single login for all content, and have a consistent, easy to understand, and descriptive UI

**QA-5: Interoperability**
The system should be highly interoperable, and allow the import of BOZ roster information, export calendars and interoperate with the secondary university systems

### Constraints

**CON-1: Web server**
The system must be accessed using a web server, so that it is easily accessible to everyone

**CON-2: Little Downtime**
There should only be downtime of 4 hours/month

**CON-3: Simple Interface**
There should only be a maximum of 3 clicks

**CON-4: Single Login**
The users should only have to login on a interface

## Step 1: Review Inputs

| Category                         | Description                                                                                                                                                                                            |
| -------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Design Purpose                   | The purpose is to design a functional CMS system                                                                                                                                                       |
| Primary Funcational Requirements | From the use cases above, we have selected: </br> UC-1 - Core functionality </br> UC-5 - Core functionality</br> UC-7 - Core functionality </br> UC-9 - Supports QA-2 </br> UC-10 - Core functionality |
| QA Scenerios                     | QA-1: M, L </br> QA-2: H, L </br> QA-3: H,H </br> QA-4: H,H </br> QA-5: L, M </br> From the above list QA-2, QA-3, and QA-4 are selected                                                               |
| Constraints                      | We have selected all of the constraints as drivers                                                                                                                                                     |
