# Django_test(class management API)

Don't bother about UIs, we're here for APIs,
Here you need to identify the schema/model fields by observing the UIs, The goal of this assignment is to build **_API_** for a **Class Management** site in which you are free to play with as much as possible your sample data.

<img src="class_mng1.png" />
<img src="classmng2.png" />

---

<hr>

### API Features:

1. User login for student and class teacher.

- A student can see only his assignments and announcements.(use permissions and authentication)
- A class teacher can create class and add students in that class.

2. Assignment

- A teacher can Create, Delete and Get all assignments that are assigned by him.
- If a teacher add assignment in a class then it must be accessible for all students of same class.
- students can solve assignement and upload that in pdf/jpg format.
- Teacher can check assignment and mark them as completed.

3. Announcements <br>

- A teacher can add announcement(e.g: holidays, events etc).
- That announcement will be shown for every student of a class.

4. Authentication

- Login (mandatory)
- Logout(optional)
- Signup (optional)

<hr>

### Coding Guidelines

- Please fork current problem repository or use it as template and, add [@divyansh420](https://github.com/divyansh420) ,[@nitesh5695smilebots](https://github.com/nitesh5695smilebots) as collaborator while intializing repository in github. And follow the given timeline instructions from your mail.
- The changes/commits will not be considered after timeline mentioned in your mail.
- Please avoid any frameworks and libraries except **_Django REST framework_**.
- Focus more on the **_Django REST framework_** side of the problem.
- You need to add requirements.txt file in project
- Add a readme.md file and add all details about your APIs.
- You will be evaluated on a **WORKING PROJECT** for:
  - Modularity of Code
  - Security
  - Data Structures used
  - Model serialization
  - Database designing
  - Logic and cleanliness of code.
  - Completeness.
- Please ask us for any hurdle in your problem assignment.

<b>Note: <b> please use sqlite database and tables should be related to other tables.
