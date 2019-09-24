.. _manage_document_templates:

Manage Document Templates
=========================

Application roles needed to manage document templates: :ref:`Education Process Admin <education_process_administrator>`

About Document Templates
^^^^^^^^^^^^^^^^^^^^^^^^^^^
Document templates are used for auto-generated documents, such as cerificate for completed course. Information like the course name, learner's name, date of completion and total course duration can be displayed in a generated document. The list of variables which can be used in a particular template is shown in the place where template is used. For example, on the course creation form, the creator can see a list of variables to be inserted in the user's certificate and thus choose a template which contains these variables.

Triggers that generate documents
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Document is created when a certain action happens. For example, when a learner completes a course, their status in the course will change to "finished" which will trigger a mechanism that checks if the course is completed successfuly, and if so, it will create a certificate of completion for that particular learner.

How to make a template
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Your template should be a Word 2007 document or newer. Variables which will be used in your template should be inside two sets of curly brackets {{}}. List of variables and explanation what will they look like in generated template can be found :ref:`here <variables_for_documents>`.

Add a Document Template
^^^^^^^^^^^^^^^^^^^^^^^^^^^
#. In the **Education process management** section on the **Manage** page click **Templates** tile.
#. **Templates** form is shown on top of the page containing list of all available templates and action button **Add**. List can be sorted by **Name** column.
#. Click **Add** to add new template.
#. **Add Template** form opens below.
#. Template is added by dropping a file in the drag-and-drop control or clicking the control and choosing the file from the computer.
#. **Save** button is enabled if the selected file is in correct format (.docx, for example) and size (smaller than 10MB).
#. Click **Save**.

Edit a Document Template
^^^^^^^^^^^^^^^^^^^^^^^^^^^
#. Go to **Manage** > **Templates**.
#. In the list of templates select edit icon in the **Actions** column of the template you wish to edit.
#. **Edit Template** form opens below. 
#. You can download and check existing file or upload a new one.
#. To upload, drop the file in drag-and-drop control or click the control to choose the file from your computer.
#. **Save** button is enabled if the selected file is in correct format (.doc or .docx) and size (smaller than 10MB).
#. Click **Save**.
