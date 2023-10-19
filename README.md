# CMPG323_PROJECT_4_34385479
Testing &amp; RPA

# All about how the "AI ROBOT HIRES ITSELF":

![image](https://github.com/kayleeyana/CMPG323_PROJECT_4_34385479/assets/112712495/b9476549-a940-4cfc-b947-1082455a293b)


## What is RPA and Automation all about?

Robotic Process Automation (RPA) is a technology that employs software robots to replicate human tasks, focusing on automating interactions with user interfaces to handle repetitive and time-consuming processes. RPA serves as a catalyst for organizations to optimize operational efficiency by delegating routine, rule-based tasks to these digital assistants, thus enabling human workers to channel their efforts into more strategic and creative endeavors. The merits of RPA are diverse, encompassing cost savings, heightened precision, expedited task execution, and scalable deployment, all with minimal disruption to existing systems. RPA stands as a transformative force in reshaping business operations, elevating productivity, and liberating employees to engage in more strategic and value-driven tasks, thereby streamlining processes and elevating overall performance.

# Why we need Automation in our lives?

SAVE TIME, MONEY AND THERES STILL MORE TO COME...

# HOW TO USE THE AUTOMATION:

This Automation populates the: Customers, Orders, Products, and OrdersDetails using the Excel spreadsheet called "ecopowerlogistics" and displays all the data on the web app called: https://cmpg323-ecopowerlogistics.azurewebsites.net/

# MORE ABOUT RPA AND TESTING.

Instruction Manual
Using the available web app: https://cmpg323-ecopowerlogistics.azurewebsites.net/.

Using FireFox browser and UiPath community studio.

Log-in on the web app.

This web app has four tabs namely: HOME, CUSTOMERS, ORDERS, PRODUCTS AND ORDERS DETAILS tabs. 

Stakeholders would need the above before running the automation.

# Read and Create data from Excel spreadsheet.

    1. Firstly the automation logs into the web app called https://cmpg323-ecopowerlogistics.azurewebsites.net/ with a username and password saved in the automation.
    2. Clicks a tab in this order: Customers, Orders, Products and then Ordersdetails.
3. Clicks on the "Create New" proceeding with entering all the data from the Excel spreadsheet onto the webpage.
4. Automating all records based on the click event from each tab for the: Customers, Orders, Products, OrdersDetails, inserting all corresponding data from the Excel based on the tab clicked by using the click activity called "Create".
5. Each tab called Customers, Orders, Products and OrdersDetails will have a table with all the details captured.
6. Whilst doing this it writes to the Excel spreadsheet and updates the Test Result Column by indicating True/False that the automation was successful. 

# Edit data on the web app and modify the data.

1.Now we have the option of editing the: Customers, Orders, Products, OrdersDetails on the web app to make it a little more meaningful by adding more data to each Customer, Orders, Products, OrdersDetails.

2. The automation captures the data provided on the web app based on a specific tab on the web app: Customers,  Orders, Products, OrdersDetails, loops through each of the data captured on the web- app, and edits respective data, e.g Customer Title.
   
4. Then captures all the edits on the web app.
   
6. Updates the excel spreedsheet that the webapp has captured the editing.

[Stretch Tasks]: Writes to the Excel spreadsheet when the edit was successful or not. 

# Delete data on the web app.

1.Now we also have the option of deleting an entire record based on the tab: Customers, Orders, Product, OrdersDetails.
2.Theres a record of all Customers, Orders, Products and Orders so in each respective tab theres a table with all the details captured at the end theres a "Delete" activity. 
3.Once the "Delete "has been clicked on, the automation deletes the entire record.
4.Updates the excel spreedsheet that the deleting has occurred.

[Stretch Tasks]: Writes to the excel spreedsheet.



