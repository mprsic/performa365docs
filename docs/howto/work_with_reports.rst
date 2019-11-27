Work with reports
==================

Application roles needed to view reports: 

* :ref:`Education Process Admin <education_process_administrator>`
* :ref:`Exam Admin and Exam Creator <exam_admin_exam_creator>`
* :ref:`Tenant Admin <tenant_administrator>`

View reports
**************

If a user has any of the roles required to view reports, they will be able to see and click on **Reports** in the main navigation menu.
Clicking on the **Reports** menu item will redirect the user to the page with all available reports listed within navigation menu on the left. 
Each menu item consists of report's name and short description.
When selected, report will be displayed to the right.

Report toolbar
^^^^^^^^^^^^^^

Apart from view and navigation options, report toolbar on the top of each report offers additional features such as:

* Preview (1) and print (2) of the report directly from the application
* Exporting the report to another file format (3)
* Searching the content of active report by entering the keyword in the search pop-up window (4)


Report parameters
^^^^^^^^^^^^^^^^^^

If a report has parameters, they will be shown to the right of the report in the parameters area. 
Depending on the nature of the parameter, it will be displayed as a control such as checkbox, dropdown menu, datepicker, etc. To run a report with parameter, the parameter needs to be selected first. Clicking on **Preview** button at the bottom of the parameter area will generate the report.
You can toggle the visibility of the parameter area by clicking on filter icon in the toolbar.


Types of reports
*****************

The following reports are currently available on the reports page:

RPT-USR01
^^^^^^^^^^

By default, this report displays all active systems users. Total number of users is shown in the report header. The information shown in the body of the report consists of rows showing name, email, manager, creation date and last update for each user.
To view deactivated users, select the checkbox labeled **Show deactivated users** in the reports section and click **Preview**. The report will show all users, both active and deactivated. Deactivated users will be shown in red.

RPT-USR02
^^^^^^^^^^

By default, this report displays all active system's users grouped by organizational hierarchy. The left side of report shows all company's departments arranged hierarchicaly. Active users (employees) in each department are displayed on the right side of the report. Information on department's employees contains total number of users, as well as name, email, manager and last update for each user within department.
To view deactivated users, select the checkbox labeled **Show deactivated users** in the reports section and click **Preview**. The report will show all users, both active and deactivated. Deactivated users will be shown in red.

RPT-M01
^^^^^^^^^^

This reports shows all system users and their progress in each course they are/were enrolled into. Users are grouped by organizational hierarchy. 
By default, results are shown only for default (current) learning period and for required courses (the courses the learner was assigned to, not self-enrolled into). These parameters can be changed by selecting/unselecting different values in the parameters areas and clicking **Preview**.
Information on department's employees contains names of the courses they are/were attending, as well as their current status (finished, started, not started), success (pass, fail or unknown) and due date.

RPT-M02
^^^^^^^^^^

This report is similar to RPT-M01, the difference being that it will only show courses which have an exam type of activity. 
Users are displayed hierarchicaly by department and the information for each user include name of the course(s) they are/were attending, status in the course and success. However, there are two additional columns specific for an exam type of activity - **Exam result** (pass/fail) and **Percentage points** for each exam attempt.


RPT-M02
^^^^^^^^^^

This report is the same as RPT-M02, showing users and all their exam attempts in courses they are/were attending, but in non-hierarchical display. Instead, users are listed alphabetically.


RPT-ER01
^^^^^^^^^^

This report shows average rating for selected course. To generate the report, you need to select two parameters from the parameter area - **Course** and **Learning period**, both which must be chosen from the corresponding drop-down menu. After clicking the **Preview** action button, the report will be generated showing average rating and all individual ratings with comments and date of creation for each rating.


RPT-EO01
^^^^^^^^^^

This report shows all exam attempts for selected course during specific time period. To generate the report, three parameters need to be selected - **Course** from the list of courses in the dropdown menu, **Start date** and **End date** both from the date-picker controls. When you are done, click on **Preview** to generate the report.
The report will show course name and selected time period in the report header. In the body, a table will be generated showing all users who have taken the exam. 
All user's attempts will be listed showing start time/end time of the attempt, success (pass/fail) and percentage points. Each attempt has an expand button next to it. Clicking on it will open up details of each attempt, showing all exam questions, answer that was given and information wheather it was correct or not, and points scored for that particular question.
