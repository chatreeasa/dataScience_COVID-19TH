<!DOCTYPE html>
<html>

<body>
  <h1>Data Visualization in Healthcare: COVID-19 Cases</h1>
  
  <p>This project demonstrates data visualization techniques using Python for analyzing and visualizing COVID-19 cases in the healthcare domain.</p>
  
  <h2>Dataset</h2>
  
  <p>The dataset used for this project contains information about confirmed COVID-19 cases, including province of onset, sex, notified date, and age. It can be sourced from <a href="https://data.go.th/dataset/8a956917-436d-4afd-a2d4-59e4dd8e906e/resource/4688036a-cd89-45f7-a0c3-a34dbe35a50c/download/confirmed-cases-since-120465.xlsx">data.go.th</a>.</p>
  
  <h2>Exploratory Data Analysis (EDA)</h2>
  
  <p>The script performs the following steps for exploratory data analysis:</p>
  
  <ol>
    <li><strong>Data Preparation:</strong> The dataset is loaded from the provided URL using Pandas.</li>
    <li><strong>Data Cleaning:</strong> Any missing values are dropped from the dataset.</li>
    <li><strong>Visualization:</strong> The script presents various visualizations to analyze the COVID-19 cases:</li>
  </ol>
  
  <h3>Relation between province_of_onset and sex</h3>
  <p>This visualization showcases the distribution of cases based on the province of onset and sex. It helps to identify any patterns or differences in COVID-19 cases between different provinces and genders.</p>
  
  <h3>Relation between province_of_onset and Notified date</h3>
  <p>This visualization highlights the cases in each province over time. By plotting the cases based on the province of onset and the notified date, it provides insights into the spread and timeline of COVID-19 infections in different regions.</p>
  
  <h3>Relation between province_of_onset and age</h3>
  <p>This visualization displays the distribution of cases based on the province of onset and age. It helps to identify any age-related patterns or variations in COVID-19 cases across different provinces.</p>
  
  <ol start="4">
    <li><strong>Additional Analysis:</strong> The script also includes additional visualizations:</li>
  </ol>
  
  <h3>Daily Inflection of Cases over Time</h3>
  <p>This visualization shows the daily inflection of COVID-19 cases over time. It helps to identify any trends, spikes, or fluctuations in
