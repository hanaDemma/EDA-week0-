Streamlit Dashboard for Solar and Wind Data Analysis

This project is a Streamlit dashboard designed to analyze and visualize data related to solar radiation, temperature, wind direction, and wind speed. The app allows users to upload CSV files, explore data trends, and visualize various components such as hourly and monthly averages, wind direction distributions, and correlation matrices for solar and temperature data.

Features
Data Upload: Upload your CSV files containing solar and wind data.
Monthly Trends: Visualize monthly trends for solar radiation components (GHI, DNI, DHI) and temperature (Tamb).
Hourly Averages: Explore hourly trends for solar radiation and temperature.
Sensor Readings: Compare sensor readings for cleaned and not-cleaned data.
Correlation Matrix: Display a heatmap showing the correlation between solar radiation components and temperature.
Wind Direction Distribution: Analyze wind direction using a polar bar chart.
Wind Speed Distribution: Visualize the distribution of wind speed using a radial bar chart.

1. Installation

git clone https://github.com/hanaDemma/EDA-week0-.git

2. Install Required Dependencies: The dependencies required for this project are listed in the requirements.txt file. Install them using:

    pip install -r requirements.txt
3. Run the Streamlit App: After installing the dependencies, you can run the app locally:
     streamlit run app.py

Here's a sample GitHub README template for your Streamlit dashboard project, including key sections to describe the project, installation instructions, and usage details:

Streamlit Dashboard for Solar and Wind Data Analysis
This project is a Streamlit dashboard designed to analyze and visualize data related to solar radiation, temperature, wind direction, and wind speed. The app allows users to upload CSV files, explore data trends, and visualize various components such as hourly and monthly averages, wind direction distributions, and correlation matrices for solar and temperature data.

Table of Contents
Features
Installation
Usage
CSV Data Requirements
Screenshots
Contributing
License
Features
Data Upload: Upload your CSV files containing solar and wind data.
Monthly Trends: Visualize monthly trends for solar radiation components (GHI, DNI, DHI) and temperature (Tamb).
Hourly Averages: Explore hourly trends for solar radiation and temperature.
Sensor Readings: Compare sensor readings for cleaned and not-cleaned data.
Correlation Matrix: Display a heatmap showing the correlation between solar radiation components and temperature.
Wind Direction Distribution: Analyze wind direction using a polar bar chart.
Wind Speed Distribution: Visualize the distribution of wind speed using a radial bar chart.
Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
Create a Virtual Environment (optional but recommended):

bash
Copy code
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate  # For Windows
Install Required Dependencies: The dependencies required for this project are listed in the requirements.txt file. Install them using:

bash
Copy code
pip install -r requirements.txt
Run the Streamlit App: After installing the dependencies, you can run the app locally:

bash
Copy code
streamlit run app.py
Usage
Upload a CSV file with the required columns (see CSV Data Requirements).
Choose one of the available options from the sidebar to visualize trends:
Data Upload: Upload and preview the first few rows of your CSV file.
Monthly Trends: View monthly averages for solar radiation and temperature.
Hourly Averages: Display hourly averages of solar radiation components and temperature.
Sensor Readings: Compare cleaned and not-cleaned sensor readings.
Correlation Matrix: Display a heatmap for solar radiation and temperature correlation.
Wind Direction Distribution: View the wind direction distribution using a polar plot.
Wind Speed Distribution: Explore the wind speed distribution using a radial bar plot.
CSV Data Requirements
Your CSV file should contain the following columns for accurate analysis and visualization:

Timestamp: A column named Timestamp with time data in a recognizable format.
Solar Data: Columns like GHI, DNI, DHI for solar radiation data.
Temperature: Columns like Tamb, TModA, TModB for temperature data.
Wind Data: Columns like WD (Wind Direction), WS (Wind Speed).
Sensor Data: Columns like ModA, ModB, Cleaning for sensor readings.
Example CSV Format:
Timestamp	GHI	DNI	DHI	Tamb	TModA	TModB	WD	WS	ModA	ModB	Cleaning
2024-01-01 00:00:00	500	200	150	25	23	24	180	10	200	210	1
2024-01-01 01:00:00	550	220	160	26	24	25	190	12	210	220	0
Screenshots
Monthly Trends:

Wind Direction Distribution:

Add any additional screenshots or GIFs showing the app in action.

Contributing
If you’d like to contribute to this project, feel free to open a pull request or submit issues for bug fixes or improvements. Contributions are welcome!

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Commit your changes and push them to the new branch.
4. Open a pull request and explain your changes.