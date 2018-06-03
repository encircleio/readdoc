|image0|

**Content**

`Report Management 1 <#report-management>`__

`Introduction to Reports 2 <#introduction-to-reports>`__

`Types of Reports 4 <#types-of-reports>`__

`Create a Report 5 <#create-a-report>`__

`New Custom Report 5 <#new-custom-report>`__

`Add Name and Description 6 <#add-name-and-description>`__

`Selecting a Module 6 <#selecting-a-module>`__

`Selecting Report Type 7 <#selecting-report-type>`__

`Report Layout 7 <#report-layout>`__

`Report Visibility 7 <#report-visibility>`__

`Filter Data with Time 8 <#filter-data-with-time>`__

`Setting Conditions to Filter Data
8 <#setting-conditions-to-filter-data>`__

`Grouping of data 9 <#grouping-of-data>`__

`Selecting Columns 10 <#selecting-columns>`__

`Create a Tabular Report 13 <#create-a-tabular-report>`__

`Create a Matrix Report 16 <#create-a-matrix-report>`__

`Create a Summary Report 20 <#create-a-summary-report>`__

`Creating Multi-Module Report 23 <#creating-multi-module-report>`__

`Editing a Report 26 <#editing-a-report>`__

`Add and Rearrange Columns 27 <#add-and-rearrange-columns>`__

`Report List View 29 <#report-list-view>`__

`Change Report View 30 <#_Toc511169836>`__

`Search a Report 32 <#search-a-report>`__

`Preview a Report 34 <#preview-a-report>`__

`Open Custom Reports 34 <#open-custom-reports>`__

`Preview and Download 34 <#preview-and-download>`__

`Share a Report 36 <#share-a-report>`__

`Schedule a Report 37 <#schedule-a-report>`__

`Creating a Schedule 37 <#creating-a-schedule>`__

Report Management
=================

Introduction to Reports
-----------------------

The {Product} generates a lot of data which you can convert into
meaningful information using Reports. The reporting feature allows you
to generate an organized representation of system data. The result is
printable reports that you can share with others.

You get to choose the filter parameters and data columns and using those
you can generate n numbers of permutations, each resulting in a
different report. You can automate the report generation process using a
feature called scheduling; once set, you get periodic emails with a
report based on your set conditions.

You can generate reports across the following modules:

-  Request

-  Problem

-  Change

-  Asset

-  Remote Deployment

-  Software License

-  Project

**Benefits of Report**

Some of the benefits of having the reporting feature are as follows:

1. There is a better understanding of opportunities for optimization.
   For example, you can generate a report highlighting the average time
   taken for each technician to close a Request over a period. Armed
   with this information, you can map the efficiency of your
   technicians.

2. Generate reports to influence the short and long-term management
   strategies and policies.

3. Cost reduction and streamline of processes. For example, using
   Reports, you can understand the utilization of your IT Assets; thus
   you can plan your future IT purchases or justify an existing
   purchase.

4. Helps in benchmarking and setting goals. For example, you can monitor
   the overall performance of your technicians and know whether they are
   meeting the set benchmark. Similarly, you can track different KPIs in
   other modules using different parameters.

Types of Reports
----------------

There are four types of Reports that you can generate:

-  **Tabular Report**: This type of Reports list items in columns
   grouped by either time or product properties. For example, you can
   create a Tabular Report that lists Assets grouped by Technicians who
   manage them. Learn how to create a `Tabular
   Report <#create-a-tabular-report>`__.

-  **Matrix Report**: This type of Reports generate cumulative counts of
   items in a grid grouped by either time or a product property. For
   example, you can generate a report that lists the average resolution
   time of each Technician. Here average resolution time accounts for
   all the Reports that a Technician has resolved. Learn how to create a
   `Matrix Report <#create-a-matrix-report>`__.

-  **Summary Report**: This type of Reports can summarize properties,
   details, milestones, and components of items in Asset, Projects,
   Patches, and Software License. Learn how to create a `Summary
   Report <#create-a-summary-report>`__.

-  **Multi-Module Report**: You can combine two or more Reports into a
   single Report. This is called a Multi-Module Report. Learn how to
   create a `Multi-Module Report <#creating-multi-module-report>`__.

Create a Report
---------------

We have a standard interface to create reports across different modules.

We give twenty-three Reports out of the box, referred as Pre-defined
Reports. These Reports are standard Reports commonly used by most of our
users.

All Reports are created using the New Custom Reports page. To access the
page follow the below steps.

New Custom Report
~~~~~~~~~~~~~~~~~

-  Log in to the Dashboard using the Technician Portal.

-  Click on **Report** from the Navigation Tabs.

-  The Report List View opens. Click on **Create a Report** button
   situated in the top right corner of the page. The New Custom Report
   page opens.

|image1|

Figure 1

Creating a Report involves nine stages which have been described below:

Add Name and Description
^^^^^^^^^^^^^^^^^^^^^^^^

Section-A (Figure 1) is where you enter the name of the Report. The best
practice is having a name which is descriptive and concise.

Section-B is where you enter the description of the Report. Write a
suitable description because it is used as a body when the Report is
sent via email.

Selecting a Module
^^^^^^^^^^^^^^^^^^

Section-C (Figure 1) is where you select the module for which you are
making the Report. You are allowed to select one module from the
following modules:

-  **Request**: Refers to the Request Management module.

-  **Problem**: Refers to the Problem Management module.

-  **Change**: Refers to the Change Management module.

-  **Asset**: Refers to the Asset Management module. You can drill down
   to an Asset Type with this selection in section-E (Figure 1). Reports
   are generated based on Asset and the type you select.

   |image2|

Figure 2

-  **Project**: Refers to the Project Management module.

-  **Remote Deployment**-**Patch**: Refers to the Patch Management
   module.

-  **Remoter Deployment**-**Agent**: Refers to the {Product} Agent used
   for Asset discovery and remote deployment of patches and packages.

-  **Multi-Module**: This module helps you to combine two or more
   existing Reports into one Report. This module is visible when the
   Report Type is set to Summary Report.

Depending on the module selected, the Criteria parameters, data columns
and group by properties are updated.

*Note: This is a onetime selection meaning that you cannot change it
later.*

Selecting Report Type
^^^^^^^^^^^^^^^^^^^^^

Section-D (Figure 1) lets you select the Report type. There are three
types shown which are as follows:

-  **Tabular Report**: These are simple reports that allow you list
   items in columns grouped by criteria in section-J.

-  **Matrix Report**: This type of Reports show cumulative item counts
   in a grid format (C X R). The counts are group based on criteria in
   section-J.

-  **Summary Report**: This type of Reports can summarize properties,
   details, milestones, and components of items in Asset, Projects,
   Patches, and Software License.

*Note: This is a onetime selection meaning that you cannot change it
later.*

Report Layout
^^^^^^^^^^^^^

Section-F (Figure 1) houses the layout options that decide the
orientation of the final Report. You can see the orientation when the
Report is opened either in PDF or Excel format. There are two
orientations to choose from:

-  Portrait

-  Landscape

Report Visibility
^^^^^^^^^^^^^^^^^

Section-G (Figure 1) houses the visibility options. There are two
options to choose from:

-  **Public**: The Report is visible to anyone having access to the
   Technician Portal. But the right to edit and delete still lies with
   the creator of the Report.

-  **Private**: The Report is visible only to the creator.

*Note: This option is non-changeable if the visibility is set to Public;
changeable, if set to Private.*

Filter Data with Time
^^^^^^^^^^^^^^^^^^^^^

Section-H (Figure 1) allows you to filter data using time. When
filtering tickets and CIs three times are considered; which one to use
depends on your selection?

-  **Create Time**: Whenever data is fetched, by {Product}, from a
   module, the Create Time is considered in checking conditions, if any.
   For example, in a Report that shows total Requests with the Urgency
   set to High and group by Technicians for last 60 days, the {Product}
   checks the Create Time of all the Requests to see eligibility for the
   period.

-  **Update Time**: Instead of Create Time, the product uses the Update
   Time in checking data.

-  **Closed Time**: Here the product uses the Closed Time in checking
   data.

Closed Time is not applicable to the Asset module and its Types, and
Remote Deployment.

Setting Conditions to Filter Data
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Section-I (Figure 1) is where you set conditions to filter data before
it is used for generating Reports

The condition parameters are different for each module, but the way they
work is same for all.

You can add multiple condition groups with the **Add Condition Group**
option. Within each group, you can add multiple condition statements.

|image3|

Figure 3

Each condition statement talks about a parameter being equal/not equal
to something. You can form a condition statement by clicking on the
three components marked by red boxes in Figure 3. Condition statements
exist within a group, and you can add multiple conditions by clicking on
the plus sign.

The conditions are checked following a hierarchy: first conditions are
checked within a group, and then within groups. The outcome of a
condition statement or a group of statements, or groups of statements is
either true or false. The word AND & OR helps in deriving an outcome
when there are multiple statements or groups, or both.

Multiple condition statements can be evaluated using two basic
operators: AND & OR. These two operators describe the relationship
between two statements, and the outcome is always either true or false.

Grouping of data
^^^^^^^^^^^^^^^^

Section-J (Figure 1) houses the Group By feature that groups the data
rows in a Report by:

*Note: This is a required field when the Report type is Matrix*

-  **Time Unit**: You can group the data row either Daily, Weekly or
   Monthly.

-  **Property**: Each module has a list of properties that you can use
   to group the data rows in the Report.

   |image4|

Figure 4

The above figure shows the properties of the module Request Management.

Selecting Columns
^^^^^^^^^^^^^^^^^

The last step in creating a Report is selecting the columns. What
columns are available depends on the Report type and module selected.

|image5|

|image6|

Figure 5

-  **Tabular Report**:

   a. You add columns by selecting them and clicking on **Done**.

   b. You can search a column by its name.

-  **Matrix Report**:

   a. You select a column from a drop-down list (Figure 5). Each column
      is accompanied by the count function which tells of giving a
      cumulative count of items grouped by either time or a product
      property.

   b. Some columns have sub-columns which you can access by clicking the
      down icon next to a column name.

      |image7|

Figure 6

You can choose what sun-columns to include in the dialog box.

c. You add more columns using the plus icon (Figure 5).

-  **Summary Report**:

   a. You add properties/details by selecting them and clicking on
      **Done**.

   b. Some properties/details have sub-items which you can access by
      clicking the arrow icon next to a name.

      |image8|

Figure 7

You can choose what sun-columns to include in the dialog box.

-  **Multi-Module Report**:

   You search and select Reports that you want to merge into one Report.

   |image9|

Figure 8

Create a Tabular Report
~~~~~~~~~~~~~~~~~~~~~~~

-  Open the `New Custom Report <#_Accessing_New_Custom>`__ page.

-  We are going to create a Tabular Report called Computer Asset List
   that lists all computers managed by a particular Technician, group by
   Product.

-  Following is our selections for the sections in New Custom Reports:

+-------------------------------+-----------------------------------+
| Values                        | Section Name                      |
+===============================+===================================+
| Asset and Computer (Sub-Asset | `Selecting a                      |
| Type)                         | Module <#selecting-a-module>`__   |
+-------------------------------+-----------------------------------+
| Tabular Report                | `Selecting Report                 |
|                               | Type <#selecting-report-type>`__  |
+-------------------------------+-----------------------------------+
| Portrait                      | `Report                           |
|                               | Layout <#report-layout>`__        |
+-------------------------------+-----------------------------------+
| Public                        | `Report                           |
|                               | Visibility <#report-visibility>`_ |
|                               | _                                 |
+-------------------------------+-----------------------------------+
| Created Time                  | `Filter Data with                 |
|                               | Time <#filter-data-with-time>`__  |
+-------------------------------+-----------------------------------+
| Technician name               | `Setting Conditions to Filter     |
|                               | Data <#setting-conditions-to-filt |
|                               | er-data>`__                       |
+-------------------------------+-----------------------------------+
| Product                       | `Grouping of                      |
|                               | Data <#grouping-of-data>`__       |
+-------------------------------+-----------------------------------+

|image10|

Figure 9

-  Scroll down to the Select Column section of the page.

   |image11|

Figure 10

-  Here you see all the data columns available in a module. Each module
   has different columns to select. In Asset, you get different columns
   for each Asset Type; there could be hidden columns that you have to
   unhide by checking a box highlighted in Figure 10.

   You can also search for a column using the search bar in that
   section.

-  We select three columns for this Report. We can rearrange them using
   drag & drop. We finalize our selections by clicking on **Done**.

   |image12|

Figure 11

-  We save the Report by clicking on **Create**.

The process to create a Report is same for all the modules in the
system. We get the following Report when we
`preview <#preview-a-report>`__ for the past 3 months and group by
Product.

|image13|

Figure 12

Create a Matrix Report
~~~~~~~~~~~~~~~~~~~~~~

-  Open the `New Custom Report <#_Accessing_New_Custom>`__ page.

-  We are going to create a Matrix Report called Average Resolution Time
   that shows the average resolution time of each Technicians along with
   the Request number bifurcated across support levels.

-  Following is our selections for the sections in New Custom Reports:

+-------------------------+-----------------------------------+
| Values                  | Section Name                      |
+=========================+===================================+
| Request                 | `Selecting a                      |
|                         | Module <#selecting-a-module>`__   |
+-------------------------+-----------------------------------+
| Matrix Report           | `Selecting Report                 |
|                         | Type <#selecting-report-type>`__  |
+-------------------------+-----------------------------------+
| Portrait                | `Report                           |
|                         | Layout <#report-layout>`__        |
+-------------------------+-----------------------------------+
| Public                  | `Report                           |
|                         | Visibility <#report-visibility>`_ |
|                         | _                                 |
+-------------------------+-----------------------------------+
| Created Time            | `Filter Data with                 |
|                         | Time <#filter-data-with-time>`__  |
+-------------------------+-----------------------------------+
| Status Equals to Closed | `Setting Conditions to Filter     |
|                         | Data <#setting-conditions-to-filt |
|                         | er-data>`__                       |
+-------------------------+-----------------------------------+
| Technician              | `Grouping of                      |
|                         | Data <#grouping-of-data>`__       |
+-------------------------+-----------------------------------+

|image14|

Figure 13

-  Scroll down to Select Column section of the page.

   |image15|

Figure 14

-  A Matric Report gives you a cumulative count of data; for example,
   the total number of Requests assigned to each Technician. In Figure
   14, Count is the function mentioned in the first box, and the second
   box shows you all the column names available in the module. Each
   module has different column names. You can add more columns using the
   Plus Icon.

   We select two columns and click on **Done** to finalize our decision.

   It may happen a column name may generate additional columns. You can
   control the visibility of those columns.

   |image16|

Figure 15

In the above figure, we have selected a column name Support Level.
Clicking on the arrow icon adjacent to the column name opens a dialog
box where you can check what sub-columns to show.

|image17|

Figure 16

-  We save the Report.by clicking on **Create**.

We get the following Report when we `preview <#preview-a-report>`__ for
the past 3 months and group by Technicians.

|image18|

Figure 17

Create a Summary Report
~~~~~~~~~~~~~~~~~~~~~~~

-  Open the `New Custom Report <#_Accessing_New_Custom>`__ page.

-  We are going to create a Summary Report called Asset Summary that
   summarizes OS name, memory size and hostname of computers managed by
   a Technician.

-  Following is our selections for the sections in New Custom Reports:

+-------------------------------+-----------------------------------+
| Values                        | Section Name                      |
+===============================+===================================+
| Asset and Computer (Sub-Asset | `Selecting a                      |
| Type)                         | Module <#selecting-a-module>`__   |
+-------------------------------+-----------------------------------+
| Summary Report                | `Selecting Report                 |
|                               | Type <#selecting-report-type>`__  |
+-------------------------------+-----------------------------------+
| Portrait                      | `Report                           |
|                               | Layout <#report-layout>`__        |
+-------------------------------+-----------------------------------+
| Public                        | `Report                           |
|                               | Visibility <#report-visibility>`_ |
|                               | _                                 |
+-------------------------------+-----------------------------------+
| Created Time                  | `Filter Data with                 |
|                               | Time <#filter-data-with-time>`__  |
+-------------------------------+-----------------------------------+
| Technician name               | `Setting Conditions to Filter     |
|                               | Data <#setting-conditions-to-filt |
|                               | er-data>`__                       |
+-------------------------------+-----------------------------------+

|image19|

Figure 18

-  Scroll down to the Selection Section.

   |image20|

Figure 19

-  A Summary Report can summarize properties and components of Assets.
   In this Report, we are going to summarize properties which is why we
   have selected **Computer Property Details**. We confirm our column
   selection by clicking **Done**.

   |image21|

Figure 20

-  We only want OS name, memory size and host-name which we select as
   sub-columns (Refer Figure 20).

   |image22|

Figure 21

-  We save the Report.by clicking on **Create**.

We get the following Report when we `preview <#preview-a-report>`__ for
the past 3 months.

|image23|

Figure 22

Creating Multi-Module Report
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can create a Report that summarizes the output of multiple Reports.
The feature that allows you to do this is called multi-module.

-  Open the `New Custom Report <#_Accessing_New_Custom>`__ page.

-  We are going to create a Report called Multi-Module Report that has
   the output of two Reports (Computer Asset List and Average Resolution
   Time).

-  Following is our selections for the sections in New Custom Reports:

+----------------+----------------------------------------------------+
| Values         | Section Name                                       |
+================+====================================================+
| Multi-Module   | `Selecting a Module <#selecting-a-module>`__       |
+----------------+----------------------------------------------------+
| Summary Report | `Selecting Report Type <#selecting-report-type>`__ |
+----------------+----------------------------------------------------+
| Portrait       | `Report Layout <#report-layout>`__                 |
+----------------+----------------------------------------------------+
| Public         | `Report Visibility <#report-visibility>`__         |
+----------------+----------------------------------------------------+
| Created Time   | `Filter Data with Time <#filter-data-with-time>`__ |
+----------------+----------------------------------------------------+

|image24|

Figure 23

-  Scroll down to the Report selection area.

   |image25|

Figure 24

-  We select the Reports that we want to add using the search features.
   We finalize our selection by clicking on **Done**.

   |image26|

Figure 25

-  We can rearrange the order of the Reports by drag and drop.

-  We save the Report.by clicking on **Create**.

We get the following Report when we `preview <#preview-a-report>`__ for
the past 3 months.

|image27|

Figure 26

Editing a Report
----------------

*Note: A user can edit Reports that he creates.*

-  Go to the `Report List View <#_Report_List_View_1>`__.

-  In the list area, click on the **Edit Report** button of the Report
   which you want to edit. The Update Custom Report page opens.

   |image28|

Figure 27

-  The Update Custom Report page is similar to the New Custom Report
   page.

-  You can edit the following things in Update Custom Report page:

   a. The layout of the Report.

   b. You can change the Visibility if it is already set to Private.
      Once set to public, you cannot change Visibility.

   c. The Date filter field.

   d. You can modify existing conditions or add new ones in the Criteria
      section.

   e. You can change the Group by options.

   f. Add and rearrange columns.

-  Once you are over with your editing, click **Update**.

You can also access the Update Custom Report page from `Custom
Reports <#open-custom-reports>`__ page.

Add and Rearrange Columns
~~~~~~~~~~~~~~~~~~~~~~~~~

In the Update Custom Report page, you can change the
Column/Report/Section selection using **Modify Column/Reports/Section
Selection** button. You can rearrange the order using drag and drop.

|image29|

Figure 28

**Deleting a Report**

*Note: A Technician is allowed to delete Reports that he/she has
created.*

-  Go to the `Report List View <#create-a-summary-report>`__.

-  Click on **Delete Report** from the Action Menu of a Report. On
   Confirmation, the Report is deleted.

   |image30|

   |image31|

Figure 29

You can delete a Report from its `Update Custom
Repor <#editing-a-report>`__\ t page and `Custom
Reports <#open-custom-reports>`__ page.

|image32|

Figure 30

|image33|

Figure 31

Report List View
----------------

The Report List View is where you get to see all the existing Reports in
the product.

-  Log in to your Dashboard using the Technician Portal.

-  Click on the **Launcher** from the Navigation Tabs and select
   **Report**.

   |image34|

Figure 32

|image35|

Figure 33

Section-A, B & C houses the `search features <#search-a-report>`__.

Section-D is the list area where you view the available Reports. The
Report Names are shown as a tabular list, and the following information
accompanies each name:

-  Module info.

-  Report type.

-  Creator information.

Section-E is the Glance View of a Report where you can view additional
information and set a `schedule <#schedule-a-report>`__ for report
generation.

Section-F allows you to control the number of Reports visible on a
single page.

Section-G houses the `Create a Report <#create-a-report>`__ button.

Search a Report
---------------

{Product} gives you two ways to search for a Report in the Report List
View:

**Use Search Bar**

The product allows you to search for a Report using a keyword/keywords.
The search bar is at the top of the `Report List
View <#create-a-summary-report>`__.

|image36|

Figure 36

When you type in a keyword in the search bar, the product searches all
the Reports with the keyword in their Name and Description. Reports that
have the keyword are shown in the list area. In case there are multiple
keywords, all keywords need to be present in a Report in order to have a
match.

**Use Filters**

There are two types of filters in the Report List View: one that filters
Reports based on a selected module, and the other that filters Reports
based on whether a Report is pre-defined or custom.

|image37|

Figure 37

Apart from filtering Reports module wise, you can have an overview of
the distribution of Reports across all the modules.

You can quickly toggle between Pre-Defined Reports and Custom Reports:

-  **Pre-Defined Report**: {Product} comes preloaded with 23 predefined
   Reports. These are standard Reports commonly used in the product.

-  **Custom Report**: These are Reports that you create using the `New
   Custom Report <#new-custom-report>`__ page.

Preview a Report
----------------

{Product} allows you to preview a Report of a specific period and
download the output as either PDF or Excel. The Custom Reports page
facilitates the generation of a preview.

Open Custom Reports
~~~~~~~~~~~~~~~~~~~

Each Report has a Custom Report page that is accessed from the Report
List View.

-  Go to the `Report List View <#create-a-summary-report>`__.

-  Scroll down to the list area and click on a Report name that you want
   to preview. The Custom Reports page opens.

Preview and Download
~~~~~~~~~~~~~~~~~~~~

|image38|

Figure 38

**Generating a Preview**

Section-A is where you select a timeframe for the preview. Enter a Start
Date and End Date. Based on this range, data is fetched considering
either Create Time, Update Time or Closed Time. Click **Get Preview** to
generate a preview.

Section-B shows you the condition/conditions based on which data is
filtered.

Section-C is where you get to see a preview of the Report.

**Other options**

Section-D houses four options:

-  Delete the Report.

-  `Edit the Report <#editing-a-report>`__.

-  `Export/Share feature. <#share-a-report>`__

**Downloading Report**

You can download the Report either in PDF or Excel by clicking on
**Download Now**. If the Report is too long, then you cannot download
it. You have to use the `export feature <#share-a-report>`__ and receive
the Report as an email attachment.

Share a Report
--------------

The product allows you to send a Report as an email. To export a Report:

-  Go to the `Report List View <#report-list-view>`__.

-  Click on the name of a Report that you want to share. The Custom
   Reports page opens.

-  Click on Export in the top right. A dialog box opens where you have
   to enter an email/emails and select a format.

   |image39|

Figure 39

Schedule a Report
-----------------

You can periodically receive a generated Report via email using the
Schedule option. You decide the time interval when to receive, and in
what format you want to receive the Report.

In Public Reports, Schedules are user specific meaning that a user can
manage and view Schedules that he creates.

In Private Reports, only the creator of a Report can make and view a
Schedule.

Creating a Schedule
~~~~~~~~~~~~~~~~~~~

-  Go to the `Report List View <#create-a-summary-report>`__.

-  Select the Report for which you want to set a Schedule. Now click on
   **Schedule** from the Glance View.

   |image40|

Figure 40

-  The following fields appear in the Glance View.

   |image41|

Figure 41

a. First, enter for last how many days you want the Report. The time
   range keeps moving with respect to the current data.

b. Then enter the email address/addresses where the report is going to
   be sent.

c. Choose a format for the Report. It is either PDF or Excel.

d. The last thing to do is selecting a frequency. This determines how
   often you get a generated Report. We have the following frequencies:

   i.   **Once**: Get a Report once at a specific date and time.

   ii.  **Daily**: Get a Report daily at a specific time after a
        specific date and time.

   iii. **Weekly**: Get a Report on certain days of a week.

   iv.  **Monthly**: Get a Report on a specific date of certain months
        of a year.

   v.   **Interval**: Get a Report at a specific interval set in
        minutes.

d. There are plenty of options to choose from when selecting a Time
   Zone. Set the Time Zone you want to follow based on which Schedule
   Time is set.

-  When you are done, click on **Save Schedule**.

**Editing a Schedule**

-  In the Report List View, select a Report with a Schedule

-  The Glance View shows the settings of the current Schedule.

   |image42|

Figure 42

You can turn the Schedule off using the **Scheduled** toggle. Click on
**Edit Schedule** to make the fields editable.

-  When you are over with your editing, click on **Save Schedule**.

.. |image0| image:: media/image1.jpeg
   :width: 17.61458in
   :height: 11.75833in
.. |image1| image:: media/image2.png
   :width: 6.51458in
   :height: 3.59061in
.. |image2| image:: media/image3.png
   :width: 3.96514in
   :height: 2.27055in
.. |image3| image:: media/image4.png
   :width: 5.68102in
   :height: 1.45833in
.. |image4| image:: media/image5.png
   :width: 2.90625in
   :height: 3.56908in
.. |image5| image:: media/image6.png
   :width: 5.34097in
   :height: 2.37107in
.. |image6| image:: media/image7.png
   :width: 5.65347in
   :height: 1.51578in
.. |image7| image:: media/image8.png
   :width: 2.69792in
   :height: 1.05285in
.. |image8| image:: media/image9.png
   :width: 3.73681in
   :height: 2.32215in
.. |image9| image:: media/image10.png
   :width: 4.85139in
   :height: 2.30637in
.. |image10| image:: media/image11.png
   :width: 6.07014in
   :height: 3.10434in
.. |image11| image:: media/image12.png
   :width: 5.71597in
   :height: 2.42039in
.. |image12| image:: media/image13.png
   :width: 5.8097in
   :height: 0.80016in
.. |image13| image:: media/image14.png
   :width: 4.27029in
   :height: 3.38512in
.. |image14| image:: media/image15.png
   :width: 6.14306in
   :height: 3.17157in
.. |image15| image:: media/image16.png
   :width: 5.73681in
   :height: 1.09575in
.. |image16| image:: media/image17.png
   :width: 5.97639in
   :height: 1.62818in
.. |image17| image:: media/image18.png
   :width: 5.82014in
   :height: 2.51544in
.. |image18| image:: media/image19.png
   :width: 4.50091in
   :height: 2.98296in
.. |image19| image:: media/image20.png
   :width: 6.15347in
   :height: 2.52793in
.. |image20| image:: media/image21.png
   :width: 5.26319in
   :height: 1.08618in
.. |image21| image:: media/image22.png
   :width: 6.26806in
   :height: 0.94028in
.. |image22| image:: media/image23.png
   :width: 5.12222in
   :height: 2.64056in
.. |image23| image:: media/image24.png
   :width: 6.01806in
   :height: 4.03048in
.. |image24| image:: media/image25.png
   :width: 6.26806in
   :height: 1.77361in
.. |image25| image:: media/image26.png
   :width: 5.99722in
   :height: 2.67171in
.. |image26| image:: media/image27.png
   :width: 6.26806in
   :height: 0.72014in
.. |image27| image:: media/image28.png
   :width: 4.32797in
   :height: 5.19792in
.. |image28| image:: media/image29.png
   :width: 4.19514in
   :height: 1.8517in
.. |image29| image:: media/image30.png
   :width: 5.50519in
   :height: 1.05151in
.. |image30| image:: media/image31.png
   :width: 4.61181in
   :height: 1.62941in
.. |image31| image:: media/image32.png
   :width: 5.71597in
   :height: 0.90432in
.. |image32| image:: media/image33.png
   :width: 6.26806in
   :height: 1.43056in
.. |image33| image:: media/image34.png
   :width: 6.26806in
   :height: 1.54097in
.. |image34| image:: media/image35.png
   :width: 5.27847in
   :height: 2.83983in
.. |image35| image:: media/image36.png
   :width: 6.26806in
   :height: 2.84444in
.. |image36| image:: media/image37.png
   :width: 5.57006in
   :height: 1.54525in
.. |image37| image:: media/image38.png
   :width: 5.52804in
   :height: 1.06384in
.. |image38| image:: media/image39.png
   :width: 5.72335in
   :height: 3.12292in
.. |image39| image:: media/image40.png
   :width: 3.25in
   :height: 2.43082in
.. |image40| image:: media/image41.png
   :width: 6.26806in
   :height: 2.15417in
.. |image41| image:: media/image42.png
   :width: 3.71875in
   :height: 4.22356in
.. |image42| image:: media/image43.png
   :width: 4.57292in
   :height: 3.82292in
