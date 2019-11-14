JamfPro Connector overview:

Custom connectors allow to retrieve data by calling APIs, and systems that aren’t available as prebuilt connectors.    The connector retrieves data by calling JAMF’s JSS API and creates a data model from the data retrieved.  This means that customers will have access to their data in Power BI Desktop and Power BI service.  With Power BI desktop and Power BI Service, customers can do powerful analytics and can combine the data from API with their own data sources to create powerful visuals and Dashboards.


JamfPro connector exposes the following entities:

1.	Computers – Information about the computers in your organization, managed by JamfPro
2.	Mobiles – Mobile devices information managed by JamfPro
3.	Computer Device groups – Mapping between mobile computers and device groups in your organization.
4.	Computers – Extension attributes – Details of extension attributes associated with your organization mobile devices.
5.	Computer – Applications – Details about computer applications managed by JamfPro by computer.
6.	Mobile Device groups – Mapping between mobile devices and device groups in your organization
7.	Mobile devices – Extension attributes – Details of extension attributes associated with your organization mobile devices.
8.	Mobile device applications – Information about the applications installed on your mobile devices.

JamfPro – Usage guide:

1.	Use with Power BI Desktop:

Copy the .mez file to the following directory in your desktop:

<<User’s home directory>>\Documents\Power BI Desktop\Custom Connectors

 

If the directory doesn’t exist, please create it.

Open Power BI desktop:

a.	Enable custom connectors:

Click on File  Options and Setting  Options  Security, , select "(Not Recommeded) Allow any extension to load without validation or warning"under Data Extensions section.

 
b.	Click on Get Data  Search for “Jamf”.  The connector shows up:

 

Hovering over the connector name gives you a brief description of the connector.
Click on JamfPro Connector and click on Connect.  

Enter your JamfPro API instance URL:

 


Enter your username and password in the next window:

 

This will display the Jamf connector Navigation tree:

 

Click on any entity to see the data in preview mode.  Note that preview mode displays only a few records.

 

From then on you can use Load or Transform to load this model into your Power BI report.




