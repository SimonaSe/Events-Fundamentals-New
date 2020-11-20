
# Module 4: Event Data Analysis

## 4.0 - Create your DHIS2 account on ANALYSIS & Introduction to Module 4

### Introduction to Module 4

#### WELCOME TO MODULE 4!

This module focuses on showing you how you can use event data to create
event data outputs in the form of tables, charts and maps.

In module 4, there are 4 subsections that you will be reviewing:

  - 4.1 - Event Reports. This subsection is divided into 6 units.
  - 4.2 - Event Visualizer. This subsection is divided into 5 units.
  - 4.3 - Maps. This subsection is divided into 6 units
  - 4.4 - Joint Analysis of Event & Aggregate Data. This subsection is
    divided into 5 units.

#### OBJECTIVES

By the end of this module, you should be able to:

  - Describe the features of the event reports, event visualizer and
    maps apps as they relate to outputting event data
  - Use the event reports, event visualizer and maps app to create event
    data outputs in DHIS2
  - Describe how event and aggregate data can be reviewed together
  - Use the data visualizer and maps app to create joint event and
    aggregate data outputs

#### ACTIVITIES & ASSIGNMENTS

#### Activities

You will be performing ungraded activities **for each unit labelled as a demonstration** within the 4 subsections of this module. Activities will be identified within the subsection themselves. There is therefore a total of **20 activities** that you will perform within this module. Don't worry, we try not to make any single activity to long!

#### Assignments

You will have **4 graded assignments** in the form of hands-on exercises
that you must answer, one for each subsection. Each graded assignment
will contribute to 10% of your overall grade. This module therefore
contributes to 40% of your grade overall.

#### Training Environment

You will be using the ANALYSIS training environment to perform your
activities and assignments. If you have not done so, please sign up for
this training environment by following the instructions in the unit
Account Creation - Analysis.

#### TIME COMMITMENT

There is a significant amount of content to cover in this module! This
module should take you approximately **8 hours** in total to review all of the content, perform the ungraded activities and finish the graded
assignments as identified in the course outline. This is our longest
module, but will likely be very useful to many of you!

### Account Creation - ANALYSIS

Instructions - Account Creation on Analysis

In order to perform the exercises and assignments within Module 4, you
will be accessing the **ANALYSIS** DHIS2 system. The **ANALYSIS** system will grant you access to different apps within DHIS2 when compared to **CAPTURE**. You can see the apps you will have available in the screenshot below. In this system, you will not have access to any of the apps used to capture data. If modification of the data was allowed, this could potentially affect any of the values associated with the outputs used in this module.

![Analysis apps](images/image225.png)

Please create an account for ANALYSIS by following the available
instructions.

-----

Click the "Request account" button below to request an account on the
DHIS2 Analysis system.

You will receive an invitation by email with instructions on how to
complete the registration in DHIS2.

Note: the email address you use with OpenEDX will be sent to the DHIS2
database to create an account.

Give it a couple of seconds to think; DO NOT keep clicking the “Request
account” button several times in a row! It will send your email details
that you used when you registered in OpenEdX to the DHIS2 Analysis
system to begin the registration process. After 5-10 seconds you should
receive the following notification in your browser window.

![Account Invitation Sent](images/image2.png)

Click on OK to close this notification.

Login to to your e-mail. You should receive an e-mail subject that looks
like the following:

![Email Subject](images/image276.png)

We can see in the email subject that the DHIS2 system that has been
identified is the Analysis system that you should be signing up for.

Note that this e-mail may be in your junk folder. If you do not see it
in one of your primary inboxes, please check your junk folder in case it
was filtered out.

The e-mail itself should look like this

![Received Email](images/image22.png)

In order to continue, either click on the highlighted link or copy and
paste it into a new tab in your browser. This link will take you to the
following page:

![Account Details](images/image145.png)

Your email-details have already been filled in from OpenEdX. You will
need to fill in the remaining fields however.

Take note of the restrictions on the password. It must:

  - Be at least 8 characters long
  - Include an uppercase letter
  - Include 1 number/digit
  - Include a special character

After filling in all the fields select “Create” to proceed

![Account Details Filled](images/image152.png)

This should log you in to the DHIS2 Analysis system where you can view
the dashboard.

![Dashboard](images/image30.png)

From here, please follow instructions for any activities or assignments
that are referring you to the DHIS2 Analysis system.

## 4.1 - Event Reports

### Demonstration - Interface Description

#### Introduction - Subsection 4.1

In Subsection 4.1 we review how to enter event data into DHIS2 using the
capture app on the web.

Subsection 4.1 has 6 units for you to review. We recommend that you
review these units in order.

1.  Demonstration - Interface Description
2.  Demonstration - Creating a Line List Event Report
3.  Demonstration - Filtering Data Items
4.  Demonstration - Creating a Pivot Table Event Report
5.  Demonstration - Updating the Table Layout
6.  Demonstration - Aggregated Data Using an Average

##### Ungraded Activities

There is an activity associated with each unit in this subsection.
Scroll below the video demonstration in each unit in order to view the
activity.

##### Graded Assignment

After you have completed reviewing all the material within this
subsection, please attempt the graded quiz for this subsection. This
quiz will contribute to 10% of your overall grade.

#### Video - Event Reports Demonstration Part 1 of 6

#### Part 1 Activity: Interface Description

This activity will be completed in DHIS2 Analysis.

Clicking on the DHIS2 symbol below, located in the upper left of the
page, navigate to the main Dashboard page.

![4.1.1.1.DHIS2_symbol](images/image102.png)

Next, select the **action ellipses** within the 4.1 Pivot Table, and click  “Open in Event Reports app.”

![4.1.1.2.Dashboard_Pivot_table](images/image231.png)

![4.1.1.3.Open_Event_Reports_app](images/image166.png)

Using the **Data** tab on the left, add the data item “Condition of
Patient”.

![4.1.1.4.MCM](images/image141.png)

**Update** the table to see the changes reflected on the screen.

![4.1.1.5.Malaria_Case_Management_Results](images/image347.png)

Add the year “2020” to the **period** and then **update** the table.

![4.1.1.6.MCM_Period_2019___2020](images/image130.png)

![4.1.1.7.Results_table_1](images/image117.png)

Change the Organisation unit to “Animal Region” and update the table.

![4.1.1.8.Org_Unit_change](images/image279.png)

![4.1.1.9.Results_table_2](images/image283.png)

### Demonstration - Creating a Line List Event Report

#### Video - Event Reports Demonstration Part 2 of 6

#### Part 2 Activity: Creating Line List Event Report

Create a new table by selecting **Favorites > New**.

Select the **Table style** “Line list” and the **Output type** “Event.”

In the **Data** tab, select:

  - The **Program** and **Stage** “Malaria Case Management”
  - The data elements “Age", "Sex" and "MCM Treatment Outcome”

![4.1.2.1_Line_list_overview](images/image229.png)

  - In the **Periods** tab select:
  - “Fixed and relative periods”
  - The period type “Yearly”
  - “2019”
  - Make sure to remove the checkmark next to “Last 12 months”

![4.1.2.2_Periods](images/image80.png)

In the **Organisation units** tab select “Trainingland” and then click on **Update**.

![4.1.2.3_Org_units](images/image222.png)

![4.1.2.4_Results](images/image164.png)

### Demonstration - Filtering Data Items

#### Video - Event Reports Demonstration Part 3 of 6

#### Part 3 Activity: Filtering Data Items

Edit the data item “Sex” to filter the cases to show “Females” only.

![4.1.3.1_Filtering_data_items](images/image183.png)

Click **Update** and view the table.

![4.1.3.2_Results_after_filtering](images/image69.png)

Change the “Age” filter, set the option to “No range set” and the
operator to “=”.

![4.1.3.3_Filtering_data_items](images/image309.png)

Click **Update** and view the table.

![4.1.3.4_Results](images/image253.png)

### Demonstration - Creating a Pivot Table Event Report

#### Video - Event Reports Demonstration Part 4 of 6

#### Part 4 Activity: Creating a Pivot Table Event Report

Clear the current table. Select **Favorites> New**.

![4.1.4.1_Pivot_Table_Favorites](images/image115.png)

![4.1.4.2_Table_Style](images/image197.png)

In the **Data** tab select:

  - The **Program** and **Stage** “Malaria Case Management”
  - The data elements “Age", "MCM | Condition of Patient" and
    "MCM|Malaria species Type”

![4.1.4.3__Programs_and_data_elements](images/image236.png)

In the **period** tab select:

  - “Fixed and relative periods”
  - The period “Yearly”
  - “2019”
  - Make sure to uncheck the “Last 12 months” box

![4.1.4.4_Periods](images/image59.png)

Select the **Organisation Unit** “Animal Region.”

![](images/image340.png)

Click **Update**.

Edit the table **Options**

  - Remove the checks next to “Show row totals” and “Show row
    sub-totals”
  - Check the box next to “Hide n/a data”

![4.1.4.6_Table_options](images/image345.png)

Click Update.

![4.1.4.7_Results](images/image203.png)

### Demonstration - Updating the Table Layout

#### Video - Event Reports Demonstration Part 5 of 6

#### Part 5 Activity: Updating Table Layouts

Change the table layout by clicking on the **Layout** button

  - Put “Periods” under **Report filter**
  - Put “Age” under **Column dimensions**
  - Leave “MCM l Condition of Patient” and “MCM l Malaria species Type"
    in **Row dimensions**

![4.1.5.1_Table_layout](images/image45.png)

Click Update.

![4.1.5.2_Results](images/image33.png)

Under the Data items change the “Age” legend to “CoD: Age group
(broad)”.

![4.1.5.3_Data_elements_and_filters](images/image155.png)

Click **Update**.

![4.1.5.4_Results](images/image334.png)

### Demonstration - Aggregated Data Using an Average

#### Video - Event Reports Demonstration Part 6 of 6

#### Part 6 Activity: Aggregated Data Using an Average

Click **Layout**.

Under Aggregation select “Age” instead of “Number of events”. Select the
aggregation operator as “Average”.

![Table layout](images/image304.png)

Click **Update**.

![Pivot table as the output](images/image327.png)

If you would like, you can save the table as a favorite. Click
**Favorites > Save**.

![Save the output](images/image171.png)

  - Please provide the favorite name and description using a unique
    naming convention that begins with your initials
  - A useful convention is: **your initials_program_what_where_when**
  - Next, select **Download**.

  - Click on the format you prefer

![Download options of the output](images/image248.png)

## 4.1 - Graded Assignment - Event Reports

### Graded Assignment - Event Reports

This is a **graded assignment** and it is worth **10%** of your final grade.

You have **2 attempts** to pass each question.

If you are not sure about the steps you followed in the assignment to
get to the correct answer, click on the "**hint**" button to see some tips.

If you want to save your current response without submitting it for
grading yet, select the "**save**" button. This allows you to come back
later and resume the attempt.

Select the "**check**" button to submit your answers.

#### Assignment Links

#### Instructions

1. For this assignment, answer questions using the **Event Reports** app
2. Use the “Malaria Case Management” **program** and **stage**
3. You will be marked based on the answers selected through multiple
    choice. To determine the answers, you must create the associated
    table described in the details section.
4. Save all tables as Favorites, using the convention:
    **username_program_what, where, when**

##### Question 1: Details

**Table style**: “Line list”

**Output type**: “Event”

**Program**: “Malaria Case Management”

**Stage**: “Malaria Case Management”

**Data elements**: “MCM | Malaria method of detection,” “MCM | Malaria species Type,” “MCM | Confirmation Method”

Period: “2020”

**Organisation Unit**: “Food Region”; “Select levels” as the mode and then “Facility”

![4.1.1.Assign_-_Part_1_Results](images/image333.png)

The eighth event listed is from the “Ice Cream Dispensary.” What was
the “Malaria Species Type” for this event?

( ) Mix {{Mix is incorrect, it was not the Malaria Species Type for the
eighth event listed }}

( ) Po {{Po is incorrect, it was not the Malaria Species Type for the
eighth event listed}}

(x) Pk {{Pk is the Malaria Species Type for the eighth event listed}}

( ) Pf {{Pf is incorrect, it was not the Malaria Species Type for the
eighth event listed .}}

||(A) Make sure for the Period you chose “Fixed and relative periods,”
then''Yearly” before selecting “2020.”||

||(B) Make sure you unchecked the “Last 12 months” box in the Periods
section.||

||(C) In the Layout tab, make sure the “Longitude” and “Latitude” are
“Excluded dimensions.”||

##### Question 2: Details

**Table style**: “Pivot table”

**Output type**: “Event”

**Program**: “Malaria Case Management”

**Stage**: “Malaria Case Management”

**Data elements**: “Sex,” “MCM|Treatment Outcome”

**Period**: “Start/end dates,” from “15th August 2019” to “15th June 2020"

**Organisation unit**: “Trainingland”

**Tip**: Hide “n/a data” as well as “row totals.”

**What is the most common “MCM Treatment Outcome” for “Females?”**

(x) Recovered {{Recovered. ‘Recovered’ is the most common Treatment
Outcome for Females.}}

( ) Drop out {{Drop out - is not the most common Treatment Outcome for
Females. Double check you have entered all of the input details
correctly and disaggregated the number of malaria cases by “Sex.” }}

( ) Failed due to medication {{Failed due to medication - is not the
most common Treatment Outcome for Females. Double check you have entered
all of the input details correctly and disaggregated the number of
malaria cases by “Sex.”}}

( ) Dead {{Dead - is not the most common Treatment Outcome for Females.
Double check you have entered all of the input details correctly and
disaggregated the number of malaria cases by “Sex.”}}

( ) Follow up {{Follow up -  is not the most common Treatment Outcome
for Female. Double check you have entered all of the input details
correctly and disaggregated the number of malaria cases by “Sex.”}}

||(A) Make sure to disaggregate the number of malaria cases by gender by
going to the Data tab and selecting “Male” and “Female” within the data
item “Sex.”||

||(B) Use the Options menu to hide “n/a data” as well as “row totals.”
||

**What is the most common “MCM Treatment Outcome” for “Females?”**

(x) Recovered {{Recovered. ‘Recovered’ is the most common Treatment
Outcome for Females.}}

( ) Drop out {{Drop out - is not the most common Treatment Outcome for
Females. Double check you have entered all of the input details
correctly and disaggregated the number of malaria cases by “Sex.” }}

( ) Failed due to medication {{Failed due to medication - is not the
most common Treatment Outcome for Females. Double check you have entered
all of the input details correctly and disaggregated the number of
malaria cases by “Sex.”}}

( ) Dead {{Dead - is not the most common Treatment Outcome for Females.
Double check you have entered all of the input details correctly and
disaggregated the number of malaria cases by “Sex.”}}

( ) Follow up {{Follow up -  is not the most common Treatment Outcome
for Female. Double check you have entered all of the input details
correctly and disaggregated the number of malaria cases by “Sex.”}}

||(A) Make sure to disaggregate the number of malaria cases by gender by
going to the Data tab and selecting “Male” and “Female” within the data
item “Sex.”||

||(B) Use the Options menu to hide “n/a data” as well as “row totals.”
||

##### Question 3: Details

**Table style**: “Pivot table”

**Output type**: “Event”

**Program**: Malaria Case Management”

**Stage**: “Malaria Case Management”

**Data elements**: “Age,” “MCM l Condition of Patient”

**Periods**: “Fixed and relative periods” “Quarterly”   the following
quarters:

  - “July - September 2019”
  - “October - December 2019”
  - “January - March 2020”
  - “April - June 2020”

Organisation unit: “Trainingland”

***Tip**: Filter the number of cases in the Age Range 5-9

**Which quarter has the highest number of people aged, “5-9” with a “Severe” condition?**

( ) “Jul - Sep 2019” {{“Jul - Sep 2019” does not have the  highest
number of people aged 5-9 with a "Severe" condition. Double check you
have entered all of the input details correctly and that you are
reporting the number of patients within the “5-9” age range
disaggregated by “Condition of patient.”}}

(x) “Oct - Dec 2019” {{“Oct-Dec 2019” has the highest number of people
aged, 5-9 with a "Severe" condition.}}

( ) “Jan - Mar 2020” {{Jan - Mar 2020” does not have the  highest number
of people aged 5-9 with a "Severe" condition. Double check you have
entered all of the input details correctly and that you are reporting
the number of patients within the “5-9” age range disaggregated by
“Condition of patient.”}}

( ) “Apr - Jun 2020”  {{ “Apr - Jun 2020” does not have the highest
number of people aged 5-9 with a "Severe" condition. Double check you
have entered all of the input details correctly and that you are
reporting the number of patients within the “5-9” age range
disaggregated by “Condition of patient.”}}

||Think about the objective and the specifics of what you are reporting.
Make sure to correctly adjust the age ranges in the data tab under the
“Age” data item. When choosing the period you may need to make use of
the Prev year and Next year buttons.||

##### Question 4: Details

**Table style**: “Pivot table”

**Output type**: “Event”

**Program**: “Malaria Case Management”

**Stage**: “Malaria Case Management”

**Data elements**: “Age,” “MCM | Condition of Patient”

**Period**: “Fixed and relative periods”; “Yearly”; “2020”

**Organisation unit**: Facilities within Animal Region > Bird District.

***Tip**: Calculate the average of the “Age” data element using the Layout tab

**Which facility in the “Bird District” has the highest average age of
“Severe” malaria cases?**

( ) “Owl Dispensary” {{“Owl Dispensary” does not have the highest
average age of severe malaria cases in Bird District. Double check you
have entered all of the input details correctly and that you are
reporting the average age of “Severe” malaria cases within all “Bird
District” facilities in “2020.”}}

(x) “Robin Primary Health Centre” {{“Robin Primary Health Centre” has
the highest average age of severe malaria cases in Bird District.}}

() “Ostrich Health Centre”  {{“Ostrich Health Centre” does not have the
highest average age of severe malaria cases in Bird District. Double
check you have entered all of the input details correctly and that you
are reporting the average age of “Severe” malaria cases within all “Bird
District” facilities in “2020.”}}

( ) “Parrot District Hospital” {{“Parrot District Hospital” does not
have the highest average age of severe malaria cases in Bird District.
Double check you have entered all of the input details correctly and
that you are reporting the average age of “Severe” malaria cases within
all “Bird District” facilities in “2020.”}}

||(A) Update the layout of the report. Click on Layout and make sure
“Organisation units” is under Row dimensions, and the “Condition of
patient” is in the Report Filter. ||

||(B) Remember you are reporting the “Severe” cases of Malaria and make
sure the "Condition of patient" data item is filtering only "Severe"
cases.||

||(C) In order to calculate the average of the “Age” data element in the
Layout tab, under the Value > Aggregation section, find the “Age” data
element and then, directly below, select the aggregation type as
"Average".||

## 4.2 - Event Visualizer

### Demonstration - Navigating the Event Visualizer Application

#### Introduction - Subsection 4.2

In Subsection 4.2 we review how to create data outputs using the event
visualizer app in DHIS2.

Subsection 4.2 has 5 units for you to review. We recommend that you
review these units in order.

1. Demonstration - Navigating the Event Visualizer Application
2. Demonstration - Visualizing Event Data in a Column Chart
3. Demonstration - Filtering an Age Range
4. Demonstration - Additional Filters for a Visualization
5. Demonstration - Creating a Pie Chart with Event Data

##### Ungraded Activities

There is an activity associated with each unit in this subsection.
Scroll below the video demonstration in each unit in order to view the
activity.

##### Graded Assignment

After you have completed reviewing all the material within this
subsection, please attempt the graded quiz for this subsection. This
quiz will contribute to 10% of your overall grade.

#### Video - Event Visualizer Demonstration Part 1 of 5

#### Part 1 Activity: Navigating the Event Visualizer Application

Navigate to the **Event Visualizer** application. To do so:

a) Use the **search apps** feature OR 

b) Use the **action ellipses** and select “Open in Event Visualizer app”

![4.2.1.1Searchbar](images/image311.png)

![4.2.1.2Actionellipses](images/image208.png)

![4.2.1.3OpenEventVisapp](images/image52.png)

Now that we are in the app, let’s review the interface.

At the very top left corner of the criteria selection column, we can see
the first option to select is the **Type**.

![4.2.1.4_Type](images/image287.png)

Next, we can see the **Data** selection tab where we choose the program, and if the program is a tracker program, we will also have the option to select the program stage too. The available data items are the data elements and program indicators related to the selected program.

![4.2.1.5_Data](images/image84.png)

The next tab is the **Period**, and here, as in the Event Reports app, we
have the option to select either the fixed and relative period, or the
start and end dates.

![4.2.1.6_Periods](images/image249.png)

Lastly the **Organisation Unit** selection tab is where we can select the organisation units we would like to view in the report.

![4.2.1.7_OUs](images/image216.png)

### Demonstration - Visualizing Event Data in a Column Chart

#### Video - Event Visualizer Demonstration Part 2 of 5

#### Part 2 Activity: Visualizing Event Data in a Column Graph

Now let’s proceed with **Task 1** and create a column graph displaying the options for malaria species type in 2019 for Trainingland.

From the **Event Visualizer** app, select **Favorites > New**.

![4.2.2.1_New_graph](images/image121.png)

Click **Ok** to continue and approve the discarding of any changes made to the previous chart.

![4.2.2.2_OK](images/image21.png)

Select the **column graph** type.

![4.2.2.3_Column_chart](images/image39.png)

In the data tab select:

  - The **Program** and **Stage** “Malaria Case Management”
  - The **data element** “MCM l Malaria species Type”
  - Select all “MCM l Malaria species types,” “Mix, Pf, Pk, Pm, Po, Pv”

![4.2.2.4_Malaria_species_type](images/image191.png)

In the Period tab, select:

  - “Fixed and relative periods”
  - The **period type** “Yearly”
  - The period “2019”
  - Ensure “Last 12 months” is deselected in the Relative Periods
    section

![4.2.2.5_Periods](images/image273.png)

In the **Organisation units** tab, use the **Selection mode** “Select
organisation units” and then select “Trainingland.” Next, click **Update**.

![4.2.2.6_Trainingland](images/image9.png)

The graph shows all malaria species types listed across the horizontal
axis. It is showing the aggregate number of cases of malaria in 2019 for
the whole of Trainingland, by species type.

![4.2.2.7_Bar_graph](images/image113.png)

Next, let’s view the species type separately by region.

From the **Organisation Units** tab, select the “Animal” and “Food” regions.

![4.2.2.8_Org_units](images/image5.png)

Click on the **Layout** button:

  - “Organisation units” should be listed under **Category dimensions**
  - “Periods” should be listed under **Report Filter**

![4.2.2.9_Layout](images/image332.png)

Click **Update**.

Now we are able to view the mix of species types of malaria cases
separately for Animal Region and Food Region in the chart.

![4.2.2.10_Food_Animal_region](images/image261.png)

Now let’s see what happens when we drill down even further into the
Organisation Units.

From the **Organisation Units** tab, select all of the districts within the “Animal Region”; then click **Update**.

![4.2.2.11_Animal_Region](images/image56.png)

This gives you separate results for malaria cases by species in each of
the districts within “Animal Region”.

![4.2.2.12_Updated_results](images/image140.png)

Next, from the **Options** menu, above the chart:

  - Select “Hide n/a data”
  - Chose the **Sort order** “Low to high”
  - Leave **Hide chart title** unchecked and add a chart title “Malaria
    Species Type, Animal Region, 2019”

 ![4.2.2.13_Options_menu](images/image196.png)

Then click **Update**.

The chart now displays the results by district from lowest to highest,
and we can see the title at the top.

![4.2.2.14_Different_Districts](images/image146.png)

Save your chart as a favorite.

  - In the menu bar, click on **Favorites > Save**

![4.2.2.15_Save](images/image75.png)

  - Fill in the Name section: “Your initials_Malaria: Species Type,
    Animal Region, 2019”
  - Add a description, “This chart shows the positive malaria cases
    separated by their species type within the Animal Region in 2019”
  - Click **Save**

![4.2.2.16_Description](images/image330.png)

You are able to download this chart in various formats by clicking
**Download** in the menu bar and choosing your preferred download option.

![4.2.2.17_Download](images/image226.png)

### Demonstration - Filtering an Age Range

#### Video - Event Visualizer Demonstration Part 3 of 5

#### Part 3 Activity: Filtering an Age Range

Now, we will move onto **Task 2** , where we will filter out a range of ages
in an event report. Recall that we want to view the conditions of
malaria patients who are between the ages of 15-20, with the time frame
of July - December 2019, by district, in the Food Region.

From the **Event Visualizer** app, click on **Favorites > New**.

Select the **Line chart**.

![4.2.3.1_Line_chart](images/image135.png)

In the **Data tab**, select:

  - The **Program** and **Stage** “Malaria Case Management”
  - The **Data elements** “MCM l Condition of Patient” and “Age”  
    ![4.2.3.2_Data_item](images/image8.png)

To view cases that are in the age range of “15-20”:

  - **Duplicate** the “Age” data item
  - Select “No range set” for both “Age” items
  - one Age item, choose “>=” and “15”
  - the other Age item, choose “<=” and “20”  
    ![4.2.3.3_Age_ranges](images/image349.png)

In the **Period** tab select:

  - “Fixed and relative periods” and “Six - monthly”
  - Select “July - December 2019” as the period
  - Ensure “Last 12 months” is unticked in the **Relative Periods** section  
    ![4.2.3.4_Period](images/image27.png)

In the **Organisation units** tab open the hierarchy for “Food Region”.

  - Select all Districts in “Food Region”  
    ![4.2.3.5_Org_unit](images/image302.png)

Click on the **Layout** tab

  - Set “Age” as the **Report filter**
  - Put “Organisation Units” in **Category dimensions**
  - Put “MCM l Condition of Patient” in **Series dimensions**
  - Click on **Update**  
    ![4.2.3.6_Layout](images/image1.png)  
    The resulting line graph should now depict the number of simple and
    severe malaria cases for people >=15 and <=20 years old by
    district within the Food Region.

![4.2.3.7_Results_1](images/image162.png)

### Demonstration - Additional Filters for a Visualization

#### Video - Event Visualizer Demonstration Part 4 of 5

#### Part 4 Activity: Additional Filters for a Visualization

Continuing on with the line chart from the last activity, now let’s
update the chart to only show female cases in the line graph. We’ll need
to add more filters to this visualization.

In the **Data** tab select:

  - “Sex” as a **data element**
  - “Female” as the **filter**

![4.2.4.1_Data](images/image331.png)

In the **Layout** menu organise the following:

  - Put “Age” and “Sex” under **Report filter**
  - Put “MCM l Condition of Patient” under **Series dimensions**
  - Put “Organisation units” under **Category dimensions**
  - Click **Update**

![4.2.4.2_Chart_layout](images/image4.png)

The line graph should now depict the number of “Simple” and “Severe”
malaria cases for females aged between 15 -20 years old by district in
the “Food Region”.

![4.2.4.3_Results_2](images/image175.png)

Let’s add another filter to your **Line chart**.

In the **Data** tab, select:

- “Pregnant” as the **data element**
  - Filter this element by selecting “Yes”

![4.2.4.4_Selected_data_items](images/image190.png)

Click on the **Layout** menu and organise the following:

  - “Pregnant” under **Report filter**
  - “Organisation Units” under **Category dimensions**
  - “Condition of Patient” under **Series dimensions**

![4.2.4.5_Chart_layout](images/image154.png)

Then click on **Update**.

![4.2.4.6.Results](images/image325.png)

The graph type is no longer appropriate for this data. Change the graph
type to a **bar graph** and click **Update**.

![4.2.4.7.Bar_chart](images/image16.png)

![4.2.4.8.Bar_chart_results](images/image194.png)

  - Click on **Favorites > Save**
  - Provide the chart with a name and description using the recommended
    naming convention “Your intials_program, data elements, location,
    period”

### Demonstration - Creating a Pie Chart with Event Data

#### Video - Event Visualizer Demonstration Part 5 of 5

#### Part 5 Activity: Creating a Pie Chart with Event Data

From the **Event Visualizer** app, click on **Favorites > New**.

Please create a pie chart that follows the example in the demo.

Choose **pie chart** as the chart type.

![4.2.5.1.Pie_chart](images/image322.png)

In the Data tab, select

  - The **Program** and **Stage** “Malaria case management”
  - The **data element** “MCM l Treatment Outcome”

![4.2.5.2.Data](images/image19.png)

In the **Periods** tab, select

  - “Fixed and relative periods”
  - The period type “Yearly”
  - “2020” as the available period
  - Ensure “Last 12 months” is unticked in the Relative Periods section

![4.2.5.3.Periods](images/image201.png)

In the **Organisation units** tab, select “Trainingland.”

![4.2.5.4.Org_units](images/image88.png)

From the **Layout** menu organize the following:

  - “Periods” under the **Report filter**
  - “Organisation units” under the **Series dimensions**
  - “MCM l Treatment Outcome” under the **Category dimensions**

![4.2.5.5.Chart_layout](images/image57.png)

Then click on **Update**.

![4.2.5.6.Pie_chart_results](images/image172.png)

  - Click on **Favorites > Save**
  - Provide the chart with a name and description using the recommended
    naming convention “Your intials_program, data elements, location,
    period"

## 4.2 - Graded Assignment - Event Visualizer

#### GRADED ASSIGNMENT - EVENT VISUALIZER

This is a **graded assignment** and it is worth **10%** of your final grade.

You have **2 attempts** to pass each question.

If you are not sure about the steps you followed in the assignment to
get to the correct answer, click on the "**hint**" button to see some tips.

If you want to save your current response without submitting it for
grading yet, select the "**save**" button. This allows you to come back
later and resume the attempt.

Select the "**check**" button to submit your answers.

#### INSTRUCTIONS

1. For this assignment, answer questions using the **Event Visualizer** app
2. Use the “Malaria Case Management” **program** and **stage**
3. You will be marked based on the answers selected through multiple
  choice. To determine the answers, you must create the associated
  table described in the details section.
4. Save all tables as Favorites, using the convention:
  **username_program_what, where, when**

#### QUESTION 1: DETAILS

  - **Visualization Type**: Pie Chart
  - **Program**: “Malaria Case Management”
  - **Data Element**: “MCM|Malaria method of detection”
  - **Period**: “2020”
  - **Organisation Unit**: “Trainingland”

In 2020, what is the most common method for detecting malaria?

( ) MFS {{“MFS”; in 2020 MSF was not the most common method for malaria
detection at 12.1% Double check you have entered all of the input
details correctly, including the program, data elements, org unit and
period }}

(x ) FUP {{In 2020 FUP was the most common method for malaria detection
at 13.8%}}

( ) Kader {{“Kader”; in 2020 Kader was not the most common method for
malaria detection at 12.4% Double check you have entered all of the
input details correctly, including the program, data elements, org unit
and period}}

( ) SK {{“SK”; in 2020 SK was not the most common method for malaria
detection at 11.3%

Double check you have entered all of the input details correctly,
including the program, data elements, org unit and period}}

|| You may need to update the Layout of this chart. Click on Layout to
make sure “Periods” is under Report filter, “Organisation units” is
under Series dimensions, and “Malaria method of detection” is under
Category dimensions.||

#### Question 2: Details

**Visualization Type**: Line Chart

**Program**: “Malaria Case Management”

**Data Elements**:

“Sex”

“Age" >= 30

**Period**: “July to December 2019”

**Organisation Units**: Districts in “Trainingland”

In which Districts do women (aged >=30) have more malaria cases
than men (aged >=30)?

( ) “Cat District, Dinner District, Fruit District” {{“Cat District,
Dinner District, Fruit District” - Dinner District is the only District
where more women have malaria cases. Double check you have entered all
of the input details correctly, including the program, data elements,
org unit and period.}}

(x) “Dessert District, Dinner District, Sweet District” {{in “Dessert
District, Dinner District, Sweet District” women have more malaria cases
than men.}}

( ) “Dessert District, Bird District, Insect District” {{ “Dessert
District, Dinner District, Insect District”  In Bird District there are
ten more male case of malaria than there are female cases. Double check
you have entered all of the input details correctly, including the
program, data elements, org unit and period. }}

( ) “Dinner District, Game District, Staple District” {{“Dinner
District, Game District, Staple District”  In Game District, men have
more malaria cases than women. Double check you have entered all of the
input details correctly, including the program, data elements, org unit
and period

.}}

||Make sure that when you’re entering “Age >= 30” you use “No range
set” so that you are able to enter the number 30 manually||

||Review the layout of the chart by clicking the layout tab: “Age” and
"Periods" should be under Report filter; “Sex” should be under Series
dimensions; Organisation units should be under Category dimensions.||

#### QUESTION 3: DETAILS

**Visualization Type**: Bar Chart

**Program**: "Malaria Case Management"

**Data Elements**:

“Age” Range: 20-59

“MCM|Treatment Outcome = Dead”

“MCM|Condition of Patient" = "Severe”

**Periods**: “2020”

**Organisation Units**: Districts in “Animal Region”

In 2020, which District has the least amount of people who passed
away from “Severe” malaria for the age range “20-59?”

( ) Game District {{“Game District” does not have the least amount of
cases; it has 27. Double check you have entered all of the input details
correctly, including the program, data elements, org unit and period .}}

(x) Insect District {{“Insect District” has the least amount of people
who passed away from “Severe” malaria cases for the age range “20-59,”
with 8 “dead” cases registered.}}

( ) Dog District {{“Dog District”  does not have the least amount of
cases; it has 20. Double check you have entered all of the input details
correctly, including the program, data elements, org unit and period.}}

( ) Fish District {{“Fish District” does not have the least amount of
cases; it has 49. Double check you have entered all of the input details
correctly, including the program, data elements, org unit and period

.}}

||Click on Layout and make sure  (A) “MCM | Condition of Patient,” “Age”
and “Periods” are under Report Filter (B) “MCM | Treatment Outcome” is
under Series dimensions and (C) “Organisation units” is under Category
dimensions. ||

## 4.3 - Maps

### Presentation - Introduction to Maps

#### Introduction : Subsection 4.3 - Maps

In Subsection 4.3 we review how to create data outputs using the maps
app in DHIS2.

Subsection 4.3 has 6 units for you to review. We recommend that you
review these units in order.

1. Presentation - Introduction to Maps
2. Demonstration - Coordinates in Capture App & Maps Interface
    Description
3. Demonstration -  Adding Layers to Maps
4. Demonstration - Styling Layers & Adding Filters
5. Demonstration - Style by Data Element & Donut Clusters
6. Demonstration - Creating a Dashboard

##### Ungraded Activities

There is an activity associated with each unit in this subsection
labelled as "demonstration." Scroll below the video demonstration in
each of these units in order to view the activity.

##### Graded Assignment

After you have completed reviewing all the material within this
subsection, please attempt the graded quiz for this subsection. This
quiz will contribute to 10% of your overall grade.

#### Video - Maps Presentation Part 1 of 6

### Demonstration - Coordinates in Capture App & Maps Interface Description

#### Video - Maps Demonstration Part 2 of 6

#### Part 2 Activity: Coordinates in Capture App & Maps Interface Description

Now let’s see how coordinates can be visualized in the maps app. We can
do so by using an existing map.

Navigate to the dashboard by clicking on the **Dashboard** app in the **Search apps** menu.

![4.3.2.8_Dashboard](images/image328.png)

Find the particular map of interest within the dashboard and click on
the **action ellipses**.

![4.3.2.9_Action_Ellipses](images/image92.png)

Then click on “Open in Maps app.”

![4.3.2.10_Action_Ellipses_Open](images/image185.png)

Note the criteria selection column is on the left.

![4.3.2.11_Criteria_Column](images/image126.png)

Click on the **pencil symbol** at the bottom left of the layer box to edit
the layer.

![4.3.2.12_Pencil_Symbol](images/image24.png)

Click on the **Org Units** tab, then deselect “Trainingland” and select
“Animal Region.” Then click **Update Layer**.

![4.3.2.13_Event_Layer_Edit](images/image299.png)

Next, let’s add a boundary layer. Click on the **Add layer** button in the
top left corner.

![4.3.2.14_Add_Layer](images/image293.png)

Next, select a “Boundaries” layer.

![4.3.2.15_Boundary_Layer_copy](images/image218.png)

In the **Organisation Units** tab, ensure “Trainingland” is selected. Make
sure the **level** “Region” is selected.

![4.3.2.16_Org_Units](images/image38.png)

Under the **Style** tab, make sure the **Labels** box is ticked.

![4.3.2.17_Style](images/image35.png)

Then select **Add Layer**.

Example of what the result should look like:

![4.3.2.18_Results](images/image285.png)

### Demonstration - Adding Layers to Maps

#### Video - Maps Demonstration Part 3 of 6

#### Part 3 Activity: Adding Layers to Maps

Under the **File** button, click on “New” to open a new map.

![4.3.3.1_New](images/image247.png)

In the left corner, you can see the default layer, the **Basemap** layer. It
allows you to choose the basemap. Let’s choose **Bing Road** as the **Basemap**.

![4.3.3.2_Bing_Road](images/image82.png)

Click on the **Add layer** button.

![4.3.3.3_Add_Layer_Button](images/image29.png)

Choose Boundaries.

![4.3.3.4_Second_Boundary_Layer](images/image12.png)

From the Organisation Unit tree, select “Trainingland”.

From the **Select levels** drop down list choose “Region” and “District”.

![4.3.3.5_Boundary_Layer_Details](images/image176.png)

Click on **Add Layer**.

You can now see the region and district boundaries of “Trainingland”.

![4.3.3.6_District_Boundaries](images/image116.png)

Add another new layer by clicking on the **Add layer** button.

![4.3.3.7SecondAddLayerButton](images/image109.png)

As a layer type, choose Events.

![4.3.3.8_Layer_Types](images/image284.png)

The **Add new event layer** box opens.

Under the **Data** tab, choose “Malaria Case Management” as the **Program** and
as the **Stage**.

Leave the Coordinate field as “Event location”.

![4.3.3.9_Add_New_Event_Layer](images/image15.png)

Select the **Period** tab.

In the period tab, choose a “Start/end date”.

Select “January 1, 2020 - March 31, 2020” as the period.

![4.3.3.10_Period_Tab](images/image238.png)

Go to the **Org Units** tab and select “Trainingland”.

![4.3.3.11_Org_Units](images/image38.png)

  - Choose the **Filter tab** and click on **Add Filter**
  - This tab allows you to apply criteria to the events being displayed
    on the map
  - In our case, we have two criteria:
  - Choose “Pregnant” under **Data item**, “one of” as the **Operator** and
    “Yes” as the **option**
  - Add a second filter by selecting **Add Filter**
  - Choose the **Data item** “MCM|Condition of Patient,” **the Operator** “one
    of,” and “Severe” under the **Options**

![4.3.3.12_Filter](images/image263.png)

Before adding the layer, we want to ensure that the clustering is on.

Go to the **Style** tab and select “Group events”. By doing so, you will
regroup events and make the map easier to read if there are a large
number of events.

![4.3.3.13_Style](images/image163.png)

Click on **Add Layer**.

**N.B. The filter that you have applied to the map will appear along with
the legend on the left side of the maps app. You can edit the layer by
clicking on the pen icon.**

![4.3.3.14_Two_Layer_Results](images/image41.png)

Zoom in until you get to point data and click one point. A box opens
that shows the attributes of the selected event.

  - You can verify the condition of the patient is “Severe”. You will
    also be able to determine what kind of treatment the woman has
    received (ACT, Non-ACT…)

![4.3.3.15_Analyzing_the_Map](images/image98.png)

Go to **File > Save**.

Enter the name of the map and a short description and save it.

![4.3.3.16_Save_Map](images/image298.png)

### Demonstration - Styling Layers & Adding Filters

#### Video - Maps Demonstration Part 4 of 6

#### Part 4 Activity: Styling Layers & Adding Filters

Click on **File > New**.

First choose **Bing Road** as the base map.

Click on **Add layer** on the top left side of the interface and choose
**Boundaries** as a layer type.

![4.3.4.1_Second_Boundaries](images/image337.png)

From the Organization unit tree, select **Animal Region > Cat District**.

![4.3.4.2__Adding_Boundary_Layer](images/image40.png)

Go to the **Style tab** and select **Labels** to display the name of the
district on the map. You can change the size of the font.

![4.3.4.3_Style_Items](images/image151.png)

Click on Add Layer.

We now only see the boundaries of the “Cat District”.

![4.3.4.4_Cat_District](images/image78.png)

The second step is to add an event layer to display all malaria cases
that have resulted in death from “July 31 2019 to December 31 2019”.

Click on **Add Layer** and select **Events**.

![4.3.4.5_Add_Layer_Button](images/image343.png)

Under the **Data** tab, choose “Malaria Case Management” as the **Program** and
the **Stage**.

Leave the **Coordinate field** as “Event location”.

![4.3.4.6_MCM_Edit_Layer](images/image55.png)

Go to the **Period tab** and specify the **period** type as “Start/end dates”.

Use “July 31 2019” as a **Start date** and “December 31 2019” as an **End
date**.

![4.3.4.7_Period](images/image97.png)

Under the **Org Units** tab, select **Animal Region > Cat District**. Make sure
the box next to Trainingland is unchecked.

Under the **Filter** tab, click **Add filter**.

Choose the **Data item** “MCM|Treatment Outcome”, **the Operator** “one of,” and
“Dead” under the **Options**.

![/4.3.4.8_Add_Filter](images/image101.png)

Go to the **Style** tab.

Select “View all events”.

Pick a color on the color scale.

![4.3.4.9_Blue_color](images/image167.png)

Change the Radius size to “4”.

![4.3.4.10_Radius_Size](images/image61.png)

Click on **Add Layer**.

As the map shows, unfortunately, there are some deaths from malaria in
the “Cat District,” between “July 31, 2019 and December 31, 2019”.

![4.3.4.11_Malaria_Deaths_Cat_District](images/image149.png)

Note that you can view the filter that has been applied on the left side
panel. It indicates that the “Treatment outcome” is “Dead” under the
filter heading.

Do not forget to save your map as a favorite!

Select **File > Save**. Add a name that includes your initials and a
description.

### Demonstration - Style by Data Element & Donut Clusters

#### Video - Maps Demonstration Part 5 of 6

#### Part 5 Activity: Style by Data Element & Donut Clusters

The last task is to create a map that filters the data by “Female” and
“PF” malaria and that applies a data element style using the
confirmation method.

Click on **File > New**.

Choose “Bing Road” as the base map.

Click on **Add layer** and choose “Boundaries”.

![4.3.5.1_Third_boundary_layer](images/image12.png)

From the org units tree choose the **Insect District** under the **Animal
Region**.

![4.3.5.2_Insect_District](images/image124.png)

Click on **Add Layer**. The app shows the boundaries of the **Insect District**.

![4.3.5.3_Insect_District_Boundaries](images/image209.png)

Add an Event layer to our map.

Click on **Add layer** and choose “Events”.

![4.3.5.4_Add_Events_Layer](images/image315.png)

Under the **Data** tab, choose “Malaria Case Management” as the **Program** and
**Stage**.

Leave the coordinate field as “Event Location”.

![4.3.5.5_Data_MCM](images/image314.png)

In the **Period** tab, select “Start/End dates.”

  - **Start date** is “July 1st 2019”
  - **End date** is “December 31 2019”

![4.3.5.6_Period_July_Dec](images/image239.png)

In the **Org Units** tab, select the “Insect District” from the organization
unit tree.

![4.3.5.7_Insect_District_Org_Units](images/image286.png)

Under the **Filter** tab, click **Add filter**.

Choose the **Data item** “Sex”, the Operator “one of”, and the Option
"Female".

Click on Add filter to add the second filter to specify the Malaria
species type. Choose the Data item “Malaria species Type,” the
Operator “one of,” and “Pf” as the Option.

![4.3.5.8_Adding_Filter](images/image305.png)

With these options, the map will only display events that show where
women are infected with the Pf species of malaria. These filters will
appear under this layer’s heading in the column on the left.

  each event we would like to know what type of confirmation method
has been used. To do this, we need to apply a data element style.

In the Style tab, click on the Style by data element drop down list and
choose “Confirmation Method.”

Notice that all of the options for confirmation method appear: “RDT,
Microscopy and Both.”

The colors that appear next to each option can be customized by clicking
on the color and adjusting to the color of your choice.

Change the colors as follows:

  - “RDT = purple”
  - “Microscopy = blue”
  - “Both = red”

![4.3.5.9_Style_MCM](images/image120.png)

Click on Add Layer.

The map now displays the “female” cases of malaria infected with the
“Pf” species that occurred in the “Insect District” between “July
and December” of 2019. Using donut clusters the map shows these cases by
the confirmation method.

![4.3.5.10_Confirmation_Method](images/image177.png)

The number displayed in the middle of the cluster represents the total
number of cases by cluster, and the different colored rings represent
the percentage of each confirmation method. The number displayed in the
middle of the cluster represents the total number of cases by cluster,
and the different colored rings represent the percentage of each
confirmation method.

Click on the File > Save. Give the map a name with your initials and a
description.

An example is shown below.

![4.3.5.11_Saving_Map](images/image70.png)

### Demonstration - Creating a Dashboard

#### Video - Maps Demonstration Part 6 of 6

#### Part 6 Activity: Creating a Dashboard

Now that we have all of the maps from the 3 tasks in this demonstration
saved, let’s add them to a dashboard.

Search for the Dashboard app in the apps menu then select it.

![4.3.6.1__Dashboard_app](images/image44.png)

Let’s create a new dashboard. Do so but clicking on the green plus
button.

![4.3.6.2_Green_Plus_Button](images/image234.png)

Provide the new dashboard with a name. See an example below.

![4.3.6.3_Malaria_Case_Management_Maps](images/image165.png)

Now in the Search for items to add to this dashboard tab, type in the
individual names of the maps you just created and click on the
insert button at the right of the name.

![4.3.6.5_Search_Dashboard](images/image294.png)

Once you have clicked “insert” for all of the relevant maps, click on
Save changes at the top of the page.

![4.3.6.6_Save_Changes](images/image134.png)

The maps you’ve just added are now available on your dashboard.

![4.3.6.7_Maps_on_Dashboard](images/image160.png)

  - The dashboards are interactive, the +, - buttons allow you to zoom
    in or out on the map
  - The button with 4 arrows allows you to view the map in fullscreen
    mode
  - The list icon allows you to easily view the layers on the map

## 4.3 - Graded Assignment - Maps

#### GRADED ASSIGNMENT - MAPS

This is a graded assignment and it is worth 10% of your final grade.

You have 2 attempts to pass each question.

If you are not sure about the steps you followed in the assignment to
get to the correct answer, click on the "hint" button to see some tips.

If you want to save your current response without submitting it for
grading yet, select the "save" button. This allows you to come back
later and resume the attempt.

Select the "check" button to submit your answers.

#### 

#### INSTRUCTIONS

1.    this assignment, answer questions using the Maps app
2.  Use the “Malaria Case Management” program and stage
3.  You will be marked based on the answers selected through multiple
    choice. To determine the answers, you must create the associated
    table described in the details section.
4.  Save all tables as Favorites, using the convention:
    username_program_what, where, when

 Click here for a printable version of this assignment.

##### Question 1: Details

Create an event layer map for all of Trainingland that shows pregnant
women with severe malaria. Make sure that the district boundary layer is
present along with the labels for the district layer.

  - Basemap: Bing Road
  - Program/Program Stage: “Malaria Case Management”
  - Period: “January 1 2019 - December 31 2019”
  - Organisation Unit: “Trainingland”
  - Data Element Filters:



  - “Pregnant = Yes”
  - “MCM|Condition of Patient = Severe”

How many cases of severe malaria in pregnant women are there in the
"Insect District"?

( ) 10 {{10 is the total for Sweet District. Make sure: (a) you have
entered all of the inputs correctly in the Event Layer, including the
program, period and org unit (b) the additional Boundaries Layer has
been established with the district borders outlined using labels}}

( ) 24 {{24 is the total for Game District. Make sure: (a) you have
entered all of the inputs correctly in the Event Layer, including the
program, period and org unit (b) the additional Boundaries Layer has
been established with the district borders outlined using labels}}

(x) 15 {{15; During this period, 12 pregnant women had severe cases of
malaria within “Insect District.”}}

||Remember to set up the additional district boundary layer to  view
where the events are allocated. This means clicking on Add layer, then
“Boundaries.” Afterwards, select the “Insect District” as the Org
Unit, and check the “Labels” box under Style.||

##### Question 2: Details

Create a map for "Cat District" showing all the malaria medicine types
from January 31 2019 to Dec 31 2019. The map will be more meaningful if
you add the district boundary for Cat District.

  - Basemap: Bing Road
  - Program/Program Stage: “Malaria Case Management”
  - Period: “January 31 2019 - December 31 2019”
  - Organisation Unit: “Cat District”
  - Data Element Filters: “MCM|Malaria medicine Type”

![4.3.2.1_Quiz](images/image211.png)

What is the medicine type that has been provided to the highlighted
case?

( ) ACT + Primaquine {{“ACT + Primaquine”. Make sure: (a) you have
entered all of the inputs correctly in the Event Layer, including the
program, period and org unit (b) the additional Boundaries Layer has
been established with the district borders outlined using labels.}}

( ) Artemeter Injeksi {{ “Artemeter Injeksi”. Make sure: (a) you have
entered all of the inputs correctly in the Event Layer, including the
program, period and org unit (b) the additional Boundaries Layer has
been established with the district borders outlined using labels.}}

(x) Kina+Primaquine+Doksisiclin {{ “Kina+Primaquine+Doksisiclin” is the
medicine type that has been provided to the highlighted case of the
female who is 62 years old.}}

( ) Kina+Primaquine {{“Kina+Primaquine". Make sure: (a) you have entered
all of the inputs correctly in the Event Layer, including the program,
period and org unit (b) the additional Boundaries Layer has been
established with the district borders outlined using labels.}}

||You can access additional details about individual events on the map
by clicking on the event. Review the details for the event using this
feature.||

-----

#### Question 3: Details

Create a map of malaria cases filtering the data by the condition of the
patient, the confirmation method and gender. Also apply a data element
style using the confirmation method data.

  - Basemap: Bing Road
  - Program/Program Stage: “Malaria Case Management”
  - Period: “July 01 2019 - December 31 2019”
  - Organisation Unit: “Fruit District”
  - Data Element Filters:



  - “MCM|Confirmation Method" = "Both", "Microscopy" and "RDT”
  - “MCM|Condition of Patient" = "Simple”
  - “Sex" = "Male”



  - Data element style should be on: “MCM|Confirmation Method”

What is the most common confirmation method used in "Fruit District"
to detect simple malaria cases who are male?

(x) RDT {{ RDT.  This should be easily identifiable via the legend that
has been applied as a result of the data element style that has been
added. Roughly 50% of the simple, male cases have been identified using
an RDT.}}

( ) Microscopy {{Microscopy”. Roughly 25% of male cases with “Simple”
malaria have been confirmed with the “Microscopy” method in Fruit
District. Make sure to: (a) apply a data element style using the style
tab on the event layer in order to easily identify which confirmation
type was the most common (b) group the events in clusters so you can
view the distribution by confirmation method.

}}

( ) Both {{Roughly 25% of male cases with “Simple”  malaria have been
confirmed with “Both” methods in Fruit District. Make sure: (a) to apply
a data element style using the style tab on the event layer in order to
easily identify which confirmation type was the most common (b) group
the events in clusters so you can view the distribution by confirmation
method.

}}

||Ensure that in the MCM Event Layer Style tab, you have the option
“Group events” turned on. To view the donut cluster for the whole
district, zoom out on the map so you only have one cluster for the
district.||

## 4.4 - Joint Analysis of Event & Aggregate Data

### Presentation - Introduction of Joint Analysis

#### Introduction : Subsection 4.4 - Joint Analysis of Event & Aggregate Data

In Subsection 4.4 we will review how you can create data outputs that
combine both aggregate and event data together using the data visualizer
and maps app in DHIS2.

Subsection 4.4 has 6 units for you to review. We recommend that you
review these units in order.

1.  Presentation - Introduction of Joint Analysis
2.  Demonstration - Analysis of Program Indicators Using a Pivot Table
3.  Demonstration - Analysis of Program Indicators Using a Chart
4.  Demonstration - Analysis of Aggregate Data, Program Indicators and
    Combined Indicators
5.  Demonstration - Analysis of Event Data & Combined Indicators using
    Maps

##### Ungraded Activities

There is an activity associated with each unit in this subsection
labelled as "demonstration." Scroll below the video demonstration in
each of these units in order to view the activity.

##### Graded Assignment

After you have completed reviewing all the material within this
subsection, please attempt the graded quiz for this subsection. This
quiz will contribute to 10% of your overall grade.

#### Video - Joint Analysis of Event & Aggregate Data Presentation Part 1 of 5

### Demonstration - Analysis of Program Indicators Using a Pivot Table

#### Video - Joint Analysis of Event & Aggregate Data Demonstration Part 2 of 5

#### Part 2 Activity: Analysis of Program Indicators in Data Visualizer App Using a Pivot Table

Navigate to the Data Visualizer app.

Search for the Data Visualizer app in the search apps field, then click
on the app.

![4.4.2.1DataVisualizer](images/image193.png)

Once you have the Data Visualizer app open, choose the Pivot
table option:

![4.4.2.2Pivottable](images/image297.png)

Then enter the following data:

  - Under the Data tab choose “Program indicators”
  - Select the Program “SARA RCH”
  - Select the Program indicators “SARAFacilities offering ANC” and
    “SARAfacilities offering Family Planning services”



  - Use the arrow pointing to the right to move them over to the
    Selected Data box



  - Then click Hide

![4.4.2.3_Data](images/image195.png)

  - Under the Period dimension, select the period type ”Fixed periods,”
    the period type “Yearly” and the year “2020”. Make sure to move
    “2020” to the Selected Data column using the arrow pointing to the
    right
  - Remove “Last 12 Months” from the Selected Data column
  - Then click Hide

![4.4.2.4_Period](images/image316.png)

  - In the Organization Unit dimension, ensure “Trainingland” is
    selected in the hierarchy
  - Select the Level “District”
  - Then click Hide

![4.4.2.5Organisationunits](images/image187.png)

  - To ensure we can view the facilities by district, change the layout
    around; bring the “Organization Unit” to the Rows dimension, and the
    “Period” into the Filter dimension
  - Click Update

![4.4.2.6_Layout](images/image282.png)

  - If we only want to view rows with data in them, using the
    Options tab we can select the “Hide empty rows” and then select
    “Column totals” to view the total number of facilities that
    provide ANC or family planning services
  - Next, click Update

![4.4.2.7_Options](images/image274.png)

 

![4.4.2.8_Results](images/image227.png)

Click on File > Save.

Provide the pivot table with a name and a description.

![4.4.2.9_Save](images/image182.png)

### Demonstration - Analysis of Program Indicators Using a Chart

#### Video - Joint Analysis of Event & Aggregate Data Demonstration Part 3 of 5

#### Part 3 Activity: Analysis of Program Indicators in Data Visualizer App Using a Chart

Click on File > New. In the chart types drop down menu in the top left
corner of the app, select “Line”

![4.4.3.1Linechart](images/image352.png)

  -   the Data dimension choose “Program indicators”
  - Select the program “Malaria Case Management”
  - Select the Program indicators “Malaria cases male,” “Malaria cases
    female,” and “Malaria cases”
  - Click Hide

![4.4.3.2_Data](images/image186.png)

  -   the Period dimension, select:



  - “Fixed periods”
  - Period type “Monthly”
  - Year “2019”
  - “July - December2019”
  - Deselect “Last 12 months”

![4.4.3.3_Period](images/image32.png)

  - Then choose “Trainingland” as the Organisation Unit dimension
  - Then click Update

![4.4.3.4Organisationunits](images/image138.png)

 

![4.4.3.5Linechart_results](images/image62.png)

Now let’s compare the cases by district:

  - Change the graph type to a “Column” graph

![4.4.3.6Columnchart](images/image6.png)

Next, edit the layout:

  - Move the “Period” dimension to the Filter
  - Move the “Organization Unit” dimension to the Category

![4.4.3.7_Layout](images/image47.png)

  - Edit the Organization unit level to show “District”

![](images/image89.png)

Then click Update.

![4.4.3.9Barchart](images/image179.png)

Save this graph. Click File > Save.

Provide this graph with a name and description.

### 

### Demonstration - Analysis of Aggregate Data, Program Indicators and Combined Indicators

#### Video - Joint Analysis of Event & Aggregate Data Demonstration Part 4 of 5

#### Part 4 Activity: Analysis of Aggregate Data Elements, Program Indicators and Combined Indicators in Data Visualizer App

  - First, File > New
  - Choose the Pivot Table option under graph types

 

  - Under Data Type choose “Program indicators”
  - Select the Program “Malaria Case Management”
  - Select the Program indicator “Malaria cases”

 

  - Second, under Data Type choose “Data elements”
  - Select the data element group “Primary Health Care Yearly”
  - Select “Total Population”

 

  - Third, choose the Data Type “Indicators”
  - Choose the indicator group “Malaria”
  - Select “Malaria case incidence per 10,000”
  - Click Hide.

![4.4.4.1_Data](images/image122.png)

  -   the Period dimension, select the period Fixed periods and the
    Period type as “Yearly”
  - Then choose “2019” from the available list and move it to the
    Selected Data column
  - Remove “Last 12 months” from the Selected Data column
  - Then click Hide

 

![4.4.4.2_Period](images/image13.png)

  - In the Organization Unit dimension, ensure “Trainingland” is
    selected in the hierarchy
  - Select the Level “District”
  - Then click Hide ![4.4.4.3_District](images/image188.png)
  - Change the layout around and esure: “Period” under Filter,
    “Organisation Unit” under Row and “Data” under Columns
  - Click Update

![4.4.4.4_Layout](images/image107.png)

![4.4.4.5Results](images/image31.png)

Click on Favorites > Save. Provide this Pivot table with a name and a
description.

### Demonstration -  Analysis of Event Data & Combined Indicators using Maps

#### Video - Joint Analysis of Event & Aggregate Data Demonstration Part 5 of 5

#### Part 5 Activity: Analysis of Event Data & Combined Indicators using Maps

  the last example in this subsection, we will be using the Maps app.

From within the Data Visualizer app, click on the grid button in the
upper right corner to open the Search apps feature.

Search for and open the Maps app.

![4.4.5.1Mapsapp](images/image348.png)

 

Once within the Maps app, select “Bing Road” as the Basemap.

![4.4.5.2BingRd](images/image81.png)

Next, we’ll add the “Thematic” layer by clicking on Add layer, and then
selecting “Thematic.”

![4.4.5.3Thematiclayer](images/image250.png)

  - In the Data tab, select the Item type “Indicator”
  - Choose the Indicator group “Malaria” and the Indicator “Malaria case
    incidence per 10,000”
  - Leave Aggregation type as “By data element”

![4.4.5.4Datatab](images/image86.png)

  - Within the Period tab select the Period type “Six-monthly”
  - Use the arrows to navigate to the year “2019,” and select the period
    “July - December 2019”

 ![4.4.5.5Periodtab](images/image262.png)

  - In the Org Units tab, ensure “Trainingland” is selected in the
    hierarchy, and use the Select levels option to choose the “District”
    level

![](images/image48.png)

Click Add Layer.

![4.4.5.6Orgunit_tab](images/image48.png)

Next, using the Add layer button, add an Event layer by selecting the
Events option.

![4.4.5.8Eventslayer](images/image329.png)

  - Under the Data tab select the Program and Stage as “Malaria Case
    Management”
  - Under Coordinate field leave the selection “Event location”

![4.4.5.9_Data](images/image37.png)

  - In the Period tab of this layer, select the period “Start and end
    dates”



  - Use the Start date “July 1, 2019” and an End date of “December 31,
    2019”

![4.4.5.10_Period](images/image76.png)

  - Select the Organization Unit “Trainingland”

![4.4.5.11Orgunits](images/image217.png)

  - Click on the Add Layer button to add this “Event Layer” to the Map

![4.4.5.12_Results](images/image79.png)

Click on File > Save.

### Takeaways from Module 4

#### Recap, reflect and share

What new ideas have you come up with in this module? What doubts do you
have?

Even though most of the contents of the course are aimed for you to get
familiar with the DHIS2 features, the end goal is for you to relate what
you learn to your daily work and find new ways to solve data challenges
you face.

Take advantage of this space to recap, reflect, and share your thoughts
with your peers and learn from them.

## 4.4 - Graded Assignment - Joint Analysis of Event & Aggregate Data

#### Graded Assignment - Joint Analysis of Event & Aggregate Data

This is a graded assignment and it is worth 10% of your final grade.

You have 2 attempts to pass each question.

If you are not sure about the steps you followed in the assignment to
get to the correct answer, click on the "hint" button to see some tips.

If you want to save your current response without submitting it for
grading yet, select the "save" button. This allows you to come back
later and resume the attempt.

Select the "check" button to submit your answers.

#### Instructions

1.  You will be marked based on the answers selected through multiple
    choice. To determine the answers, you must create the associated
    table described in the details section.
2.  Save all tables as Favorites, using the convention:
    username_program_what, where, when

 Click here for a printable version of this assignment.

##### Question 1: Details

  - Visualization App: Data Visualizer
  - Visualization Type: Column
  - Data Type: Program indicators
  - Program and Program Stage: “SARA RCH program”
  - Program Indicators: “Staff received adolescent health training”,
    “Staff received ANC training”, “Staff received family planning
    training”, “Staff received IPTp training”
  - Period: “2020”
  - Organization Unit: “Trainingland”

In Trainingland, in 2020, what type of training was delivered to the
greatest number of staff?

(x) IPTp training {{“IPTp training”. Staff at health facilities in
Trainingland in 2020 received the most training in IPTp, with 1,105
staff trained.}}

( ) Family planning training {{“Family planning training”. 435 staff
members at health facilities in Trainingland in 2020 received training
in family planning. This is not the training type that staff have been
trained the most. Make sure you have the data in the series dimension,
so you can compare the staff trained by type of training.}}

( ) ANC training {{“ANC training”. Staff at health facilities in
Trainingland in 2020 received the least training in ANC, with 219 staff
trained. Make sure you have the data in the series dimension, so you can
compare the staff trained by type of training.}}

( ) Adolescent health training {{“Adolescent health training”. 1,024
staff members at health facilities in Trainingland in 2020 received
training in adolescent health. This is not the training type that staff
have been trained in the most. Make sure you have the data in the series
dimension, so you can compare the staff trained by type of training.}}

||"Data" should be in the series, “period” should be in the category,
and “Organization units” should be filtered out of the graph.||

##### Question 2: Details

  - Visualization App: Data Visualizer
  - Visualization Type: Pivot table
  - Data Type: Program indicators
  - Program and Program Stage: “Malaria Case Management”
  - Program Indicators: “Malaria deaths", "Malaria cases severe”
  - Period: “2019”
  - Organization Units: Districts in "Trainingland"

Which district has less than 100 “malaria deaths” and more than 250
 “Malaria cases severe?”

( ) Staple District {{“Staple District” has less than 100 malaria
deaths, but has less than 250 severe malaria cases. Use the up and down
arrows next to the data element names to sort the districts from most
deaths to least deaths.}}

(x) Dog District {{“Dog District” has a total of 90 malaria deaths and
279 severe malaria cases. }}

( ) Dinner District {{“Dinner District” has more than 250 severe malaria
cases, but has more than 100 malaria deaths. Use the up and down arrows
next to the data element names to sort the districts from most deaths to
least deaths.}}

( ) Vegetable District {{“Vegetable District” has less than 100 malaria
deaths, but has less than 250 severe malaria cases.  Use the up and down
arrows next to the data element names to sort the districts from most
deaths to least deaths.}}

||Adjust the layout of the table. “Periods” should be under the Report
Filter, “Organization units” should be under Row dimensions, “Data”
should be under Column dimensions.||

##### Question 3: Details

Visualization App: Maps

Basemap

  - “Bing Road”

Thematic layer

  - Value type: “Indicator”
  - Indicator group: “Malaria”
  - Indicator: “Malaria case incidence per 10,000”
  - Period: “Yearly", "2019”
  - Organization unit: “Trainingland,” “District level”

Event layer

  - Program and Program Stage: “Malaria Case Management”
  - Periods, start and end dates: “1 January 2019 - 31 December 2019”
  - Organization Units: “Trainingland”
  - Filter:
  - Data item: “Condition of patient”
  - Operator: “One of”
  - Option: “Severe”

In the district with the highest incidence of malaria, what was the
treatment outcome of the northern most severe case?

( ) Recovered {{The district with the highest incidence is colored dark
orange. To inspect the case details, find the case that is at the
northern tip of the district, and click on the case for more
information.}}

( ) Failed due to medication {{The district with the highest incidence
is colored dark orange. To inspect the case details, find the case that
is at the northern tip of the district, and click on the case for more
information.}}

( ) Dead {{The district with the highest incidence is colored dark
orange. To inspect the case details, find the case that is at the
northern tip of the district, and click on the case for more
information.}}

(x) Drop out {{“Drop out.” The district with the highest incidence is
Sweet District. The treatment outcome for the northernmost case was
“Drop out.”}}

||Use the zoom feature in the application. Also, clicking on a case will
provide you with information about that case, including the treatment
outcome.||

## Feedback - Data Analysis of Events
