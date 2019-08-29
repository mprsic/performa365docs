.. _enroll_learner_to_course:

Enroll Learners to Courses
==========================

There are two ways to enroll learners to courses:

* Self enrollment
* Administrative enrollment

.. _self_enrollment:

Self enrollment
^^^^^^^^^^^^^^^^

.. 
This action can be performed by 
:ref:`learner <learner>`.

..
Learners can self-enroll to the public courses. Public courses are all those with :ref:`visibility <courses>` set to "Public" which means all learners can see them in the **Catalog** and self-enroll to them.

..
To self-enroll to the course a learner must perform the following steps:

#. Go to **Catalog** > **Courses**. Specific courses can be found using search and filtering options on the **Catalog** page.
#. Click the tile of the course you wish to self-enroll to.
#. You will be redirected to the course page. 
#. In the right sidebar there is some general information about the course (rating, status) and action button **Enroll**. All public courses have this action button. Courses which have their visibility set to *read-only* can be viewed but do not have **Enroll** button and learners cannot self-enroll to them.
#. Click on **Enroll** to self-enroll to the course.
#. You will be asked to confirm your action.
#. Click **Yes**.

.. _administrative_enrollment:

Administrative enrollment
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. 
This action can be performed by 
:ref:`Enrollment Admin <enrollment_administrator>`.

#. Click on **Administrative enrollment** in the main navigation menu.
#. You will be redirected to the new page with a list of all created assignments. 
#. The assignments table has following columns: **Learning period**, **Description**, **Display name**, **Number of enrolled learners**, **Creation date**; **Last update**, **Due date**, **Status**, **Assignmnet procedure** and **Actions**. 
#. At the bottom of the page there are two buttons: **Add static assignment** and **Add dynamic assignment**. 


Add static assignment
***************************

#. Click on the action button **Add static assignment** below the list of assignments.
#. The first step of Add/Edit wizard opens up below.
#. Assignments can be created for courses or programs. Check the appropriate radio button in the **Assignment for** section.
#. **Enrollment reason** is required. Text entered into this field is sent to the learner as a part of the email message informing them they've been enrolled into the course/program.
#. **Summary** is an optional field. It contains additional information about assignment in text format. This field has a limit of 500 characters.
#. **Course/program** is selected from the dropdown menu. Only active courses and programs will be shown in this list.
#. Enter **Finish** using datetime picker control. All learners enrolled to this course must complete it before this date.
#. When all required fields have been filled in, click **Next** to continue to the second step (assignment query builder) which will be the same for both static and dynamic assignments.

Dynamic assignments
***************************

#. Click on the action button **Add dynamic assignment**.
#. The first step of Add/Edit wizard opens up below.
#. Assignments can be created for courses and programs. Check the appropriate radio button in the **Assignment for** section.
#. **Enrollment reason** is required. Text entered into this field is sent to the learner as a part of the email message informing them they've been enrolled into the course/program.
#. **Summary** is an optional field. It contains additional information about assignment in text format. This field has a limit of 500 characters.
#. **Course/program** is selected from the dropdown menu. Only active courses and programs will be shown in this list.
#. **Number of days to finish** will tell the learner how much time they've got to complete the course/program after they've been enrolled into it.
#. Enter **Valid until** using datetime picker control. Service will be automatically adding eligible learners until this date.
#. When all required fields have been filled in, click **Next** to continue to the second step (assignment query builder) which will be the same for both static and dynamic assignments.

Assignment query builder (assignment's second step)
*****************************************************

This is the second step of Add/Edit assignment wizard. In this step, a tool called query builder is used to select learners based on specific criteria.
When you first get to this step, a single tile will be displayed. This tile represents *query group*. Query groups are used to combine search criteria. There is a maximum of three query groups in this tool. 

To create a query follow these steps:

#. **Choose a logical operator.** In the upper right corner of the query builder tile, click on either **AND** or **OR**. 

Choosing a logical operator **AND** means that all conditions must be true for the complex expression to be true. 

.. tip:: For example, you need to assign a task to John Smith from Sales Department. If you search by name and type in "John Smith" you will get three results because there are three people in the organization called "John Smith". If you choose **AND**, then add another search criteria and type "Sales" to search by department,  the results will be reduced to two people, because those two fulfill both requirements - they are both called John Smith and work in the sales department. You can add another criteria and type in "Sales representative" because you know that this is the job title of the John Smith you are looking for. This will narrow your search even more and show only one result because there is only one John Smith who fullfils all requirements.  

If you choose **OR**, if either requirement is true, the complex expression is true.

.. tip:: For example, 

#. **Enter at least three characters to search by keyword.** You can search by anything: name, organization, group, job title, etc. Just start typing at three characters and you will be shown all the options in the dropdown menu.
Let's say an assignment admin needs to make sure all office assistants within sales department must complete a specific course. The admin can search by job title, but this will result in showing all candidates with this job title from all departments, not just sales. To get more specific result, they can do the following:


**Learners to enroll** displays a list of users eligible for enrollment. Choose users you want to enroll by clicking **Enroll** from the **Actions** column of each user. If a user has finished that course or is already enrolled to it, an information icon will be displayed in this column informing you of user's status.

#. As you pick users from the list, they are displayed in **Selected learners** panel.
#. When you are done selecting learners, click **Add** to finish the enrollment.
