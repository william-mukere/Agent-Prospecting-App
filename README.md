## Agent-Prospecting-App ##
*This App is created using Microsoft Power platform tools*

## Use Case Description 

*The app is suitable for an insurance company seeking to know the number of potential clients that its agents interact with at a certain point in time.*

## App functionality ## 

a.	The app allows the agents to collect the details of potential and store it in database linked to the app.

b.	The app allows agents to access stored information for their specific potential clients and leads in order to make follow up calls.

c.	It has dashboard that allow the management team to get real time visualization of what is happening in the market.

d.	The app has a feature of status of client, whether a client has decided to purchase a plan.

 ## Components & Services ##
1.	Power Apps
-	Mobile Application

2.	Sharepoint
-	Sharepoint list

3.	Power BI
-	To show dashboards for performance to the management

4.	Power Automate
-	Send email notifications to the agent when a client accept a plan


## Inspiration 
Agents struggle with managing large amounts of data or keeping track of leads. There is a need for an app that is easy to use and intuitive which delivers real value and solves agents' pain points. 
Need to make organized client follow ups

## What it does
This app addresses these challenges by providing tools for organizing and analyzing data, and provide management with upto date information of what is happening on the market including performance of different products.

## How we built it

We first created sharepoint list,which we then use to create power app.The sharepoint list acts as our datasource and also act as our backend,we then modify and customize user interface of our app.We tried to create design using figma but the implementation was not what we expected so we instead did the customization using tools already provided under power app studio.
We then connected our sharepoint list to power Bi for management access to data.We started by connecting sharepoint list through power Bi desktop,then loaded and transform data using power query inbuild in power Bi desktop,after that we created a visuals and published the report on powerBi online services for access by the management.

<img src="Agent Prospecting App Project/agent prospecting app flowchart (1).png" alt="Flowchart" style="height: 300px; width:300px;"/>

## How the App works

1. <img src="Agent Prospecting App Project/Agent PROSPECTING.png" alt="Landing Page" style="height:400px; width:800px;"/>
2. <img src="Agent Prospecting App Project/List_Agent_Propecting_App.png" alt="Landing Page" style="height:400px; width:800px;"/>
3. <img src="Agent Prospecting App Project/Edit_Titlecolum_Name_client.png" alt=" Editing sharepoint" style="height: 400px; width:8000px;"/>
4. <img src="Agent Prospecting App Project/Integrate_with_PowerApp.png" alt=" Creating Power App" style="height: 400px; width:8000px;"/>
5. <img src="Agent Prospecting App Project/Editing_Power_app_agent_p_app.png" alt=" Editing Power App" style="height: 400px; width:800px;"/>
6. <img src="Agent Prospecting App Project/getting_data.png" alt=" Import Data to Power BI" style="height: 400px; width:800px;"/>
7. <img src="Agent Prospecting App Project/data_navigator.png" alt=" Data Navigator" style="height: 400px; width:800px;"/>
8. <img src="Agent Prospecting App Project/Importing_data_TO_PowerBI.png" alt=" Import Data to Power BI 2" style="height: 400px; width:800px;"/>
9. <img src="Agent Prospecting App Project/Loading Data.png" alt=" Loading Data" style="height: 400px; width:800px;"/>
10. <img src="Agent Prospecting App Project/publishing report.png" alt=" Publishing Report" style="height: 400px; width:800px;"/>
11. <img src="Agent Prospecting App Project/visualization.png" alt=" Data Visualization" style="height: 400px; width:800px;"/>
12. <img src="Agent Prospecting App Project/report published.png" alt=" Report Published - Now Available on Power BI services" style="height: 400px; width:800px;"/>

## Challenges we ran into
We had challenges of integrating data from sharepoint to Power BI but after reading several documentation published online and watching youtube tutorials we were able to integrate the power Bi,power app and sharepoint list.
Also due to time we not able to add power automate features,but we have set the same for phase 2 of the project.

## Accomplishments that we're proud of

The app can automate many of the time-consuming and repetitive tasks involved in identifying and contacting new prospects, such as data entry, lead scoring, and follow-up reminders. This can free up agents' time and allow them to focus on higher-value activities, such as building relationships and closing deals.

## What we learned

Through building the app we have developed skills in user research and data management.We understood the importance of data,data integration,security features.
We were able to learn how to integrate power Bi and also create visualization.
We learn that sometimes refresh of data in power BI may fail due to changes in credential of data sources.

## What's next for Agent Prospecting App
We are planning to add power automate to be able to send notification to business users of leads that are being closed,that will lead to speed up of activation process.
Also in subsequent update we are planning to add feature that will allow agents to be notified once policy is active and at renewal.
