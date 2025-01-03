# Data-Analysis-Portfolio

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&width=435&lines=This+is+Virinchi+Alahari)](https://git.io/typing-svg)

Welcome to my Data Analysis Portfolio! This repository showcases a collection of my data analysis projects, demonstrating my skills and expertise in data analysis, data engineering, visualization, and machine learning.<br>


## Contents
* [About me](#about-me)
* [Portfolio Projects](#portfolio-projects)
  - [Perfume Recommendation System](#Perfume-Recommendation-System)
  - [2021 Olympic Analysis](#2021-Olympic-Analysis)
  - [ATS Optimized Custom Resume Generator](#ATS-Optimized-Custom-Resume-Generator) 
  - [Sonar (Rocks vs. Mines)](#Sonar ) 
  - [Social Distancing Monitor](#social-distancing-monitor) 
  - [Humanoid Robot](#robot)
  - [Pokémon EDA](#pokemon-analysis)
* [Acadamic Projects](#Acadamic-Projects)
  - [Flight Delay Prediction](#flight-delay-prediction)
  - [Movie Over Time Analysis](#movie-performance-overtime)
  - [Excel Exercises](#excel-exercises)
  - [R Exercises](https://github.com/almostoutlier/Main/tree/main/R%20Exercises)
  - [SQL Exercises](#sql-exercises)
* [Certificates](#certificates)
* [Contacts](#contacts)


## About me
I am a witty-minded Data Alchemist with a great passion for connecting the dots and storytelling. I have strong foundation in Python, SQL, Azure, Spark, Data Analytics and Machine Learning.

(Still trying to figure out the rest)

- Programming Languages: Python (NumPy, Pandas, SciKit, Matplotlib), Java, SQL, Bash, VBA
- Data Processing Frameworks: Apache Spark, Hadoop MapReduce
- Big Data & Databases: Hadoop, Hive, HDFS, MongoDB, Cosmos DB, MySQL, PostgreSQL, LLM
- Cloud Platforms: Microsoft Azure (Blob Storage, AKS, Databricks, Data Factory, Synapse), AWS (EC2, S3, RDS, Redshift), GCP (Cloud Dataflow, Cloud Storage, BigQuery, Google Kubernetes Engine (GKE))
- Methodologies: CI/CD, ETL/ELT, A/B Testing, NLP, LLM
- Tools: Apache Airflow, Snowflake, Tableau, Power BI, Excel, Docker, Looker, Visual Studio

Currently, I am a Grad Student at UMass Amherst. I will be graduating in December 2024, and I'm interested in a full-time Data Analyst/ Data Engineer role. Please feel free to get in touch with me via email at alaharivirinchi08@gmail.com<br>
I am both a team player and a decisive leader.<br>

You can see more information in my [**CV**](https://github.com/almostoutlier/Data-Analysis-Portfolio/blob/main/Virinchi%20Alahari%20Resume.pdf).

Here is a link to my [[**personal-website**]](https://almost-outlier.framer.website/)
![Website](/images/website.png)

This repository was created to showcase my analytical and technical skills (Excel, Python, R, SQL, Tableau, Power BI, PowerPoint, and others).


## Portfolio Projects
This section contains a list of projects with brief descriptions.

### [Perfume Recommendation System](https://github.com/almostoutlier/Projects/tree/main/PerfumeRecommendation) 
**End-to-End Web Application using NLP & Docker**
**Description:**
- Implements Flask web framework for building a scalable recommendation system, containerized using Docker for consistent deployment and scalability.
- Utilizes Natural Language Processing (NLP) with TF-IDF vectorization for processing perfume descriptions and user preferences, enabling accurate text-based similarity matching
- Integrates scikit-learn's cosine similarity algorithm to calculate perfume matches, delivering personalized top 5 recommendations based on user inputs including gender, brand, and fragrance preferences.
- Features a responsive web interface with an intuitive input form and detailed results page, displaying comprehensive perfume information including ratings, descriptions, and similarity scores.
- Demonstrates end-to-end data engineering pipeline, from data preprocessing to real-time recommendations, showcasing modern web development practices and machine learning integration in a production environment.
- Implements data cleaning and preprocessing pipeline using pandas for efficient handling of perfume dataset, ensuring accurate and relevant recommendations through structured data management.

**Tech Stack:**
- **Backend Framework**: Flask
- **Data Processing**: Pandas, NumPy
- **Machine Learning**: Scikit-learn (TF-IDF Vectorizer, Cosine Similarity)
- **Frontend**: HTML/CSS
- **Containerization**: Docker
- **Development**: Jupyter Notebook

**Architecture Flow:**
![Architecture](/images/architecture.jpg)

**Sample Output:**
![Perfume Recommendation Output](/images/perfume_output.png)


### [2021 Olympic Analysis](https://github.com/almostoutlier/Projects/tree/main/Olympics) 
**End-to-End Data Engineering Project in Azure**
**Description:**
- Leverages Azure Data Factory for efficient data ingestion from various sources into a centralized data lake.
- Utilizes Azure Databricks for data transformation, cleansing, and feature engineering, ensuring data is analytics-ready.
- Employs Azure Synapse Analytics to perform advanced analytics and generate insightful metrics.
- Creates interactive and dynamic visualizations using Power BI to present key findings.
- Integrates Looker Studio and Tableau for additional visualization and reporting capabilities.
- Implements end-to-end data engineering pipeline, showcasing the use of Azure cloud services in handling large datasets for comprehensive analysis.

**Tech Stack:**
- **Data Ingestion:** Azure Data Factory
- **Data Transformation:** Azure Databricks
- **Data Analytics:** Azure Synapse Analytics
- **Visualization:** Power BI

**Process Flow:**
![Data Process Flow](/images/flow.png)

**Azure Data Factory Pipeline:**
![Data Factory Pipeline](/images/pipeline.png)

### [ATS Optimized Custom Resume Generator](https://github.com/almostoutlier/Projects/tree/main/CustomResumeGenerator)
**Description:** 
- Utilizes the `python-docx` library and the Gemini API to create professional, ATS (Applicant Tracking System) optimized resumes in the Microsoft Word format.
- Analyzes job descriptions with the Gemini API to generate tailored resumes with optimized content and keyword placement, ensuring a high ATS score.
- Takes user inputs for personal information, education, experience, skills, and academic projects to generate well-structured, visually appealing resumes.
- Optimizes resumes for Applicant Tracking Systems using industry-standard formatting, section headings, and keywords extracted from job descriptions.
- Presents education and experience sections in a tabular format with adjustable column widths and appropriate formatting for readability.<br>

**Tech Stack:**
- **Programming Language:** Python
- **Libraries:** python-docx, Gemini API
- **Tools:** Jupyter Notebook

![Output Resume:](/images/resume-image.png)


### [Sonar](https://github.com/almostoutlier/Projects/tree/main/Sonar)
**Description:** 
- Dataset sourced from the Archive ICS UCI  website, encompassing two files: "sonar.mines" and "sonar.rocks."
- Contains 111 patterns from sonar signals bounced off metal cylinders and 97 patterns from rocks, gathered under similar conditions.
- Each pattern comprises 60 numbers indicating energy within frequency bands over time, labeled "R" for rocks and "M" for mines, sorted by aspect angles.
- Files are consolidated into one dataset named "sonar.all-data."
- After meticulous data preprocessing and feature engineering, the logistic regression model was fine-tuned, achieving an R-squared value of 0.81 and an accuracy rate of 88%, demonstrating robustness in distinguishing between rocks and mines based on sonar data patterns.<br>

**Tech Stack:**
- **Programming Language:** Python
- **Libraries:** pandas, numpy, scikit-learn, matplotlib
- **Tools:** Jupyter Notebook

![alt text](/images/sonar-image.png)

### Social Distancing Monitor
**Description:** 
- Employ YOLOv3, pretrained on the COCO dataset, for object detection.
- YOLO offers speed advantages despite being potentially less accurate than two-stage detectors.
- Treats object detection as a regression problem, predicting bounding box coordinates and class label probabilities simultaneously.
- Returns person prediction probabilities, bounding box coordinates, and centroids.
- Applies non-maxima suppression (NMS) to reduce overlapping bounding boxes.
- Computes centroids of detections and analyzes pairwise distances to identify people within a certain pixel distance threshold.<br>

**Tech Stack:**
- **Programming Language:** Python
- **Framework:** YOLOv3
- **Pretrained Model:** COCO dataset
- **Libraries:** OpenCV, NumPy
- **Techniques:** Non-maxima suppression (NMS)

**Colab:** <a href = "https://colab.research.google.com/drive/1UNRqDZCyqYc1Z4txhDqVNLER_0PNgpbX?usp=sharing"> 
<code>Colab Link</code></a> <br>
![alt text](/images/social-distance-image.png)

## Acadamic Projects
This section contains a list of projects which are a part of my acadamics with brief descriptions.

### [Flight Delay Prediction](https://github.com/almostoutlier/Projects/tree/main/FlightDelay) 
**Description:** 
- Dataset includes information about flights in three modules: Airlines, Airports, and Flights.
- All required data is present in the "Flights" module, including flight details, departure and arrival airports, delays, cancellations, and reasons.
- Using this data to predict the status of the flight and the corresponding reason.
- Objectives:
  - Predict if a flight will be on time, delayed, or cancelled.(Multiclass Classification Model)

Confusion Matrix on Test Data

                precision    recall  f1-score   support
           C       1.00      1.00      1.00        99
           D       0.94      0.95      0.94      1789
           N       0.99      0.99      0.99      8125
    accuracy                           0.98     10013

![alt text](/images/image-1.png)

  - If delayed, by how many minutes? (Multilabel Classification Model)

Confusion Matrix on Test Data

**Accuracy Score:**  0.8561869569559573

**Hamming Loss:**  0.05


**Confusion Matrix on Test Data:**
| AIR_SYSTEM_DELAY | SECURITY_DELAY | AIRLINE_DELAY | LATE_AIRCRAFT_DELAY | WEATHER_DELAY |
|------------------|----------------|---------------|---------------------|---------------|
| [8947  265]     | [9997    0]   | [9156  208]  | [8918  275]        | [9666   47]  |
| [ 442  359]]    | [  16    0]   | [ 482  167]  | [ 355  465]        | [ 261   39]  |

  - If cancelled, what could be the reason for cancellation? (Regression Model)

**Model Performance:**

| Data  | RMSE      | MAE       | MAPE     |
|-------|-----------|-----------|----------|
| Train | 32.210859 | 24.042234 | 0.444889 |
| Val   | 32.409667 | 24.199183 | 0.449289 |
| Test  | 32.224404 | 24.060442 | 0.441072 |
<br>

**Tech Stack:**
- **Programming Language:** Python
- **Libraries:** pandas, numpy, scikit-learn, matplotlib
- **Tools:** Jupyter Notebook


### Movie Performance Overtime 
**Description:** 
- The TMDB dataset, initially encompassing over 700,000 movies, was meticulously cleaned and refined to 9,678 movies, including key metrics such as cast, crew, budget, revenue, and calculated fields for gross profit and profit percentage.
- Leveraging Tableau, filters were implemented to distinguish between animated and conventional genres, and data integration techniques enhanced insights, particularly focusing on the highest-grossing actors.
- This curated dataset is a versatile tool for researchers, analysts, and industry professionals, facilitating various applications from historical analysis to predictive modeling of box office revenue.<br>

**Tech Stack:**
- **Programming Language:** Python
- **Libraries:** pandas, numpy, scikit-learn, matplotlib
- **Tools:** Jupyter Notebook

**Dataset:** <a href = "https://www.kaggle.com/datasets/akshaypawar7/millions-of-movies"> 
<code>Movies Daily Update Dataset</code></a> <br>
**Powerpoint & Dashboard:** <a href = "https://docs.google.com/presentation/d/1ZDyQ4bzW7ycv3ulfHb307G-25ZoXJPkw/edit?usp=sharing&ouid=100940698311259880524&rtpof=true&sd=true">
<code>Slides</code></a> <br>

## Certificates
* [Introduction to Airflow in Python Certificate](https://github.com/almostoutlier/Certificates/blob/main/airflow%20in%20python.pdf) - Datacamp, 2024  | <a href = "https://github.com/almostoutlier/Projects/blob/main/Datacamp_Introduction_to_Airflow_Certification_Excersises.ipynb">
<code>Link to Airflow Exercises</code></a> <br>
* [Introduction to Data Pipelines Certificate](https://github.com/almostoutlier/Certificates/blob/main/Introduction_to_Data_Pipelines.pdf) - Datacamp, 2024
* [Supervised Learning with scikit-learn Certificate](https://github.com/almostoutlier/Certificates/blob/main/Supervised_Learning_with_Scikit-learn.pdf) - Datacamp, 2024
* [Introduction to Python Certificate](https://github.com/almostoutlier/Certificates/blob/main/Introduction_to_Python.pdf) - Datacamp, 2024
* [Data Scientist's Toolbox Certificate by John Hopkins University](https://github.com/almostoutlier/Certificates/blob/main/DataScientistToolbox_Coursera.pdf) - Coursera, 2020
* [Data Manipulation with Pandas Certificate](https://github.com/almostoutlier/Certificates/blob/main/Data_Manipulation_with_Pandas.pdf) - Datacamp, 2024
* [Algorithmic Toolbox Certificate by UC San Diego](https://github.com/almostoutlier/Certificates/blob/main/AlgorithmicToolbox_Coursera.pdf) - Coursera, 2020
* [AWS Fundamentals Certificate](https://github.com/almostoutlier/Certificates/blob/main/AWS_Coursera.pdf) - Coursera, 2020
* [Crash Course on Python Certificate by Google](https://github.com/almostoutlier/Certificates/blob/main/PythonCrashCourse_Coursera.pdf) - Coursera, 2020
* [Inspiring and Motivating Individuals Certificate by University of Michigan](https://github.com/almostoutlier/Certificates/blob/main/Inspiring%26Motivating_Coursera.pdf) - Coursera, 2020


## Contact
**Mail:** alaharivirinchi123@gmail.com<br>
**LinkedIn:** <a href = "https://www.linkedin.com/in/alahari-virinchi/"> 
<code>Alahari Virinchi</code></a> <br>
