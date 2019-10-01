
Survey
================

..
Application roles needed to work with activities: 

* :ref:`Catalog Administrators <catalog_administrator>`

* :ref:`Course Owner <education_owner>`



Add a Survey Activity
*********************

#. Go to **Catalog** > **Courses**. Course can be found using search and filter options on the **Catalog** page.
#. Click the tile of the course you wish to add a new activity to.
#. You will be redirected to the course page. 
#. Each course page has a sub-menu with following menu items: **Home**, **Activities**, **Documents** and **Manage**.
#. Click on **Manage** to open a dropdown menu (**Manage** is only visible to Catalog administrators and Course owners).
#. Choose **Activities** from the dropdown menu.
#. **Activities** page is shown on top containing a list of all available activities and action button **Add**.
#. Click **Add** to add a new survey activity.
#. **New activity** wizard opens below.
#. When creating a survey, you need to choose **Survey** from the dropdown menu in the **Type** field. 
#. When all required fields are filled in, action button **Next** is enabled. 
#. Click **Next** to continue on to the next step.
#. In the second step enter **Total points** for this activity. Start and Due dates are optional.
#. In the **SharePoint survey** field choose the survey you wish to add from the drop-down menu. Surveys already used in other activities within the same course cannot be added here and will not be shown in the list. If the list is empty, there are no available surveys yet. Use the **Add new** action to create a new SharePoint survey. Clicking on this button will redirect you to SharePoint where you can create new survey. When done, refresh the survey list in the wizard to see the newly added survey. Select the new survey in the list and click **Next**.
#. In the final step you will be notified how many learners will be added to this activity. New activities will only be added to learners who have not yet completed the course. 
#. Click **Finish** to create the activity.

.. note:: Chosen survey cannot be changed afterwards as it would lead to inconsistent survey results.

Edit a Survey Activity
*********************

#. On the course page's sub-menu click **Manage** to open a dropdown menu. 
#. Choose **Activities** from the dropdown menu.
#. **Activities** page opens containing a list of all available activities. 
#. Select the edit icon in the **Actions** column of the activity you wish to edit.
#. **Edit activity** wizard opens below. 
#. Change data in the fields you wish to update and click **Finish** in the last step.


.. note:: When editing an activity, you will not be able to change its type. 

.. note:: Activity will be updated to all enrolled learners who have not yet finished this course, regardless if they have finished the activity or not. 

.. note:: Changing the status of an activity to *OFF* will only hide it from learners who haven't completed it. All learners who have compleated the activity will still be able to see in their course activity list.

.. note:: When editing a survey activity, you cannot change the SharePoint survey as it would lead to inconsistent survey results.

Create a Global Survey
***********************

.. tip:: If you want to reuse the same survey across multiple courses, you'll need to create a global survey. Global surveys are not associated to a particular course, instead they can be used in activities which are part of different courses.

To create a global survey, follow these steps:

#. In the first step of **New activity** wizard, fill in all required fields making sure you've chosen **Survey** from the dropdown menu in the **Type** field. 
#. Select the desired survey from the dropdown menu in the **SharePoint surveys** field.
#. If you want to create new global survey, click on the action button **New general survey**. 
#. You will be redirected to SharePoint survey page where you can create your survey.
#. In the first step of the wizard there is an option to allow multiple responses. Selecting this option will allow users to respond to the same survey multiple times. 

.. image:: catalog-screenshot.png
   :align: center

.. 

.. tip:: Allowing multiple responses to the same survey is tipically what you want when creating global surveys. This is due to the fact that the same set of questions can be used in different courses, so user should be able to take a survey within each course they are enrolled into. However, you should be aware that general surveys cannot be associated with specific course. For example, if you want to ask learners about their learning experience at the end of the course  you create a general survey for that purpose. This way you will be able to create multiple survey activities within different courses using the same set of questions. But the responses you get from surveys will not be linked to any particular course, you will just end up with a bunch of answers to the same questions gathered from different sources. In that case the better option would be to create a regular survey which will be associated with specific course.



Delete a Survey Activity
************************

#. On the course page's sub-menu click **Manage** to open a dropdown menu. 
#. Choose **Activities** from the dropdown menu.
#. **Activities** page opens containing a list of all available activities. 
#. Select delete icon in the **Actions** column of the survey activity you wish to delete.
#. Confirm window opens informing you that activity will be deleted for all enrolled learners in the current learning period. Learners who have enrolled in the previous learning period(s) will not be affected - they will still have this activity.
#. Click **Yes** to complete the action.
