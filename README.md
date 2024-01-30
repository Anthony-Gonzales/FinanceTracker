<h1 align="center">FinanceTracker</h1>

<p align="center">
The purpose of this application is to organize and categorize different transactions utilizing a bank CSV. The user would be able to see their spending on a daily and monthly basis. They will also be able to see a list of transactions from the CSV and be able to see the transactions in their respective categories.
</p>

<h2>About the Project</h2>

<p align="center">
  <img src="https://github.com/Anthony-Gonzales/FinanceTracker/blob/main/images/main_page.png?raw=true" alt="Application Main Page" style="width: 50%; height: auto;">
</p>

<p>
  <strong>User Story</strong>: As a bank account holder, I want a tool to easily categorize my transactions and tell me how much I'm spending daily/monthly to better handle my finances and savings.
</p>

<br>

<h3>Development Environment</h3>
<ul>
  <li>Eclipse IDE 2023-09 (4.29.0)</li>
  <li>Java Version 1.8.0_381</li>
  <li>JavaFX SDK 21.0.2</li>
  <li>Microsoft Excel</li>
</ul>

<br>

<h2>Getting Started</h2>

<h3>Prerequisites</h3>
<ul>
  <li>Install Eclipse IDE</li>
  <li>Install Java</li>
  <li>Install JavaFX SDK</li>
</ul>

<h3>Installation</h3>
<ol>
  <li>Download project</li>
  <li>Open project in Eclipse IDE</li>
  <li>Add JavaFX path as a User Library</li>
  <li>Add JavaFX User Library into project library</li>
  <li>Edit run configuration by adding the following VM option</li>
  <ul>
    <li>--module-path "\path\to\javafx-sdk-21.0.2\lib" --add-modules javafx.controls,javafx.fxml</li>
  </ul>
  <li>Run the applicatin</li>
</ol>

<h2>Use of Application</h2>

<h3>Total Daily Spending</h3>
<p>
  After uploading a bank CSV file (given in src code), the user will be given a line chart graphing out the total spent in dollars on a daily basis. When looking at the 1 Month option, if money was spent on a day, it will be displayed on the chart.
</p>

<p align="center">
  <img src="https://github.com/Anthony-Gonzales/FinanceTracker/blob/main/images/day_page.png?raw=true" alt="Daily Total Chart" style="width: 50%; height: auto;">
</p>

<h3>Transaction List</h3>
<p>
  The user will also be able to see a list of transactions. The table listing the transactions will display the date, category of transaction, description and amount spent.
</p>

<p align="center">
  <img src="https://github.com/Anthony-Gonzales/FinanceTracker/blob/main/images/list_page.png?raw=true" alt="Transactions List" style="width: 50%; height: auto;">
</p>

<h3>Category Seperation</h3>
<p> The user will be able to see the categories of their expenditures. The user is given two options to view this information: they will be able to see this representation in a pie chart, or be able to see their transactions in an organized file-like list seperated by month and category.</p>

<p align="center">
  <img src="https://github.com/Anthony-Gonzales/FinanceTracker/blob/main/images/pie_page.png?raw=true" alt="Transaction Pie Chart" style="width: 50%; height: auto;">
  <img src="https://github.com/Anthony-Gonzales/FinanceTracker/blob/main/images/category_list_page.png?raw=true" alt="Category List" style="width: 50%; height: auto;">
</p>

<h3>Length of Time</h3>
<p>If the csv has a greater date range, the user can select ranges from 1 month, 3 months, 6 months, or a year of data.</p>

<p align="center">
  <img src="https://github.com/Anthony-Gonzales/FinanceTracker/blob/main/images/date_range.png?raw=true" alt="Date Range Change" style="width: 50%; height: auto;">
</p>

<p>
  This update in date range will be reflected throughout the different pages.
</p>

<p align="center">
  <img src="https://github.com/Anthony-Gonzales/FinanceTracker/blob/main/images/three_day.png?raw=true" alt="Three Month Daily Total" style="width: 50%; height: auto;">
  <img src="https://github.com/Anthony-Gonzales/FinanceTracker/blob/main/images/three_category.png?raw=true" alt="Three Month Category List" style="width: 50%; height: auto;">
</p>

<h2>Roadmap</h2>

<ol>
  <li>Main Page</li>
  <ul>
    <li>Create a template for the main page</li>
    <li>Allow user to upload a CSV file</li>
    <li>Have program be able to read in information and allow it to be easily utilized throuhgout the application</li>
  </ul>
  <li>List Page</li>
  <ul>
    <li>Create graph that will allow the user to see the date, category, description and amount of each transaction</li>
    <li>Connect information gathered from main page to the table on this page</li>
  </ul>
  <li>Category Page</li>
  <ul>
    <li>Be able to switch between a pie view and a category list view</li>
    <li>Connect the information gathered from main page to the pie chart and table view</li>
  </ul>
    <li>Total Application Cohesion</li>
  <ul>
    <li>Allow the user to switch between pages within the application</li>
    <li>Be able to maintain a centralized location for the CSV file location using a Simpleton file so it is not lost when switching between pages</li>
    <li>Allow the user to change the date range on different pages</li>
  </ul>

</ol>

<br>
