🔥 Australia Wildfire Dashboard

An interactive dashboard built with Python, Dash, Plotly, and Pandas to analyze historical wildfire activity in Australia.

The dashboard allows users to explore wildfire data by Australian region and year, providing visualizations of the estimated fire area and the number of pixels associated with presumed vegetation fires.

📊 Dashboard LINK VIRTUAL (http://127.0.0.1:8050/)

The dashboard provides two interactive visualizations:

🥧 Monthly Average Estimated Fire Area — A pie chart showing the average estimated fire area by month. 📊 Monthly Average Count of Pixels for Presumed Vegetation Fires — A bar chart showing the average number of pixels associated with presumed vegetation fires by month.

Users can interact with the dashboard by selecting:

Region New South Wales (NSW) Northern Territory (NT) Queensland (QL) South Australia (SA) Tasmania (TA) Victoria (VI) Western Australia (WA) Year — Select a year from the available historical wildfire data. 🛠️ Technologies Used Python Pandas — Data manipulation and analysis Plotly — Interactive data visualization Dash — Interactive web dashboard HTML/CSS — Dashboard layout and styling 📁 Project Structure Australia-Wildfire-Dashboard/ │ ├── app.py ├── README.md └── requirements.txt 📋 Dataset

The dashboard uses the Historical Wildfires dataset provided as part of the IBM Developer Skills Network Data Visualization course.

The dataset contains historical wildfire observations in Australia, including information such as:

Date Region Estimated fire area Count of pixels associated with presumed vegetation fires

The Date column is converted into:

Month Year

These variables are then used to filter and aggregate the data for the dashboard visualizations. 📈 Visualizations Monthly Average Estimated Fire Area

The pie chart provides a monthly comparison of the average estimated wildfire area for the selected region and year.

Average Count of Pixels

The bar chart shows the average number of pixels associated with presumed vegetation fires for each month.

Together, these visualizations help identify seasonal patterns and differences in wildfire activity across Australian regions.

🎯 Project Objective

The main objective of this project is to demonstrate the use of Python and Dash to create an interactive data visualization dashboard.

This project demonstrates skills in:

Data cleaning and transformation Exploratory data analysis Data aggregation with Pandas Interactive visualization with Plotly Dashboard development with Dash Python application development Git and GitHub project management 👨‍💻 Author

Julian Daniel Lopez Cano

Economist | Data Analyst

Interested in:

Data Analysis Business Intelligence Python SQL Data Visualization Machine Learning
