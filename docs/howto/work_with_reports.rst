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

* Previewing and printing the report directly from the application (1 and 2)
* Exporting the report in different formats (3)
* Searching the content of report by entering the keyword in the search pop-up window (4)


Report parameters
^^^^^^^^^^^^^^^^^^

If a report has parameters, they will be shown to the right of the report in the parameters area. 
Depending on the nature of the parameter, it will be displayed as a control such as checkbox, dropdown menu, datepicker, etc. To run a report with parameter, the parameter needs to be selected first. Clicking on **Preview** button at the bottom of the parameter area will generate the report.
You can toggle the visibility of the parameter area by clicking on filter icon in the toolbar.


Types of reports
*****************

Following reports are currently available on the reports page:

RPT-USR01
^^^^^^^^^^

By default, this report displays all active systems users. Total number of users is shown in the report header. The information shown in the body of the report consists of rows showing name, email, manager, creation date and last update for each user.
To view deactivated users, select the checkbox labeled **Show deactivated users** in the reports section and click **Preview**. The report will show all users, both active and deactivated. Deactivated users will be shown in red.

RPT-USR02
^^^^^^^^^^

By default, this report displays all active system's users grouped by organizational hierarchy. The left side of report shows all company's departments arranged hierarchicaly. Active users (employees) in each department are displayed on the right side of the report. Information on department's employees contains total number of users, as well as name, email, manager and last update for each user within department.
To view deactivated users, select the checkbox labeled **Show deactivated users** in the reports section and click **Preview**. The report will show all users, both active and deactivated. Deactivated users will be shown in red.
