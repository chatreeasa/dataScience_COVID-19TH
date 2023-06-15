# dataScience_COVID-19TH

<!DOCTYPE html>
<html>
<head>
  <title>Data Visualization in Healthcare: COVID-19 Cases</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 30px;
    }
    
    h1, h2, h3 {
      color: #333;
    }
    
    p {
      margin-bottom: 20px;
    }
  </style>
</head>
<body>
  <h1>Data Visualization in Healthcare: COVID-19 Cases</h1>
  
  <p>This project demonstrates data visualization techniques using Python for analyzing and visualizing COVID-19 cases in the healthcare domain.</p>
  
  <h2>Dataset</h2>
  
  <p>The dataset used for this project contains information about confirmed COVID-19 cases, including province of onset, sex, notified date, and age. It can be sourced from <a href="https://data.go.th/dataset/8a956917-436d-4afd-a2d4-59e4dd8e906e/resource/4688036a-cd89-45f7-a0c3-a34dbe35a50c/download/confirmed-cases-since-120465.xlsx">data.go.th</a>.</p>
  
  <h2>Getting Started</h2>
  
  <ol>
    <li>Clone the repository:</li>
    <code>git clone https://github.com/your-username/your-repo.git</code>
    
    <li>Install the required libraries:</li>
    <code>pip install pandas matplotlib seaborn</code>
    
    <li>Run the script:</li>
    <code>python data_visualization.py</code>
  </ol>
  
  <h2>Exploratory Data Analysis (EDA)</h2>
  
  <p>The script performs the following steps for exploratory data analysis:</p>
  
  <ol>
    <li><strong>Data Preparation:</strong> The dataset is loaded from the provided URL using Pandas.</li>
    <li><strong>Data Cleaning:</strong> Any missing values are dropped from the dataset.</li>
    <li><strong>Visualization:</strong> The script presents various visualizations to analyze the COVID-19 cases, including:</li>
  </ol>
  
  <h3>Relation between province_of_onset and sex</h3>
  <pre><code>... Python code for plotting the relation between province_of_onset and sex ...</code></pre>
  
  <h3>Relation between province_of_onset and Notified date</h3>
  <pre><code>... Python code for plotting the relation between province_of_onset and Notified date ...</code></pre>
  
  <h3>Relation between province_of_onset and age</h3>
  <pre><code>... Python code for plotting the relation between province_of_onset and age ...</code></pre>
  
  <ol start="4">
    <li><strong>Additional Analysis:</strong> The script also includes additional visualizations, such as:</li>
  </ol>
  
  <h3>Daily Inflection of Cases over Time</h3>
  <pre><code>... Python code for plotting the daily inflection of cases over time ...</code></pre>
  
  <h3>Sex Distribution over Time</h3>
  <pre><code>... Python code for plotting the sex distribution over time ...</code></pre
