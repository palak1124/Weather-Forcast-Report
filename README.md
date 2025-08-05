### ☀️ Dynamic Weather Dashboard with Power BI

This repository contains the files for my Power BI project: a dynamic weather dashboard that visualizes current and forecasted weather conditions. This project was developed to showcase my skills in data extraction, transformation, and visualization using Power BI.

#### 📊 Dashboard Overview

The dashboard provides a comprehensive view of weather data, updated live from a web source. It is designed to be intuitive and informative, offering insights into various meteorological parameters.
<img width="1427" height="807" alt="image" src="https://github.com/user-attachments/assets/8c7044c2-6004-4448-82fd-d3eb07334205" />



**Key Features:**

* **7-Day Weather Forecast:** A detailed forecast for the next seven days, including daily high and low temperatures.
* **Real-Time Metrics:** Displays current temperature, humidity, wind speed, pressure, visibility, UV index, and precipitation.
* **Air Quality Index (AQI):** A dedicated section for air quality, showing the overall AQI status and individual levels for pollutants like PM10, CO, PM2.5, SO2, and NO2.
* **Time-Based Insights:** Includes sunrise and sunset times for the current day.
* **Chance of Rain:** A clear visualization of the probability of rain for each day of the week.

#### 🛠️ Technologies Used

* **Power BI Desktop:** The primary tool for data modeling, visualization, and dashboard creation.
* **Web Data Connector:** Used to scrape live weather data from a publicly available web source.
* **Power Query (M Language):** Utilized for data cleaning, transformation, and shaping the raw data into a usable format for analysis.
* **DAX (Data Analysis Expressions):** Employed to create custom measures and calculated columns for advanced insights.

#### 📁 Repository Structure

* `Weather_Dashboard.pbix`: The main Power BI project file. You can open this file in Power BI Desktop to view the data model, queries, and visualizations.
* `README.md`: This file, providing an overview of the project.
* `[Optional: Screenshots/]`: A folder with high-quality images of the dashboard for quick viewing.

#### 📈 How It Works

1.  **Data Source:** The project uses Power BI's web connector to pull data from a specific weather website.
2.  **Data Transformation:** Power Query scripts are used to parse the HTML table, extract relevant data points, and transform them into a structured table. This includes splitting columns, changing data types, and handling null values.
3.  **Data Model:** A simple star schema is used, with a main fact table containing all the weather data.
4.  **Visualizations:** The transformed data is then used to create various charts and cards, including line charts for temperature trends, bar charts for rain probability, and gauge charts for AQI.

#### 🚀 Getting Started

To explore this project:

1.  Clone this repository to your local machine.
2.  Ensure you have **Power BI Desktop** installed.
3.  Open the `Weather_Dashboard.pbix` file.
4.  Power BI may prompt you to refresh the data. You can click "Refresh" to fetch the latest weather information from the web source.

#### 💡 Learnings & Challenges

* **Web Scraping with Power Query:** I learned how to navigate and extract data from complex HTML structures using Power Query's `Table.FromRows` and other functions.
* **Dynamic Data Handling:** I implemented a solution to handle dynamic data that changes daily, ensuring the dashboard remains up-to-date without manual intervention.
* **UI/UX Design:** I focused on creating a visually appealing and easy-to-read dashboard, using custom colors and layouts to enhance the user experience.
