# Data-Analysis-Portfolio

## About me
Hello everyone! My name is Virinchi, and this is my portfolio.<br>
I am a Business Analytics Major at Isenberg School of Management. I honed my cloud infrastructure skills as a DevOps Engineer over 2 years. Simultaneously, I led the marketing of a nationwide NGO dedicated to empowering underprivileged students in India. During my tenure there, I achieved a groundbreaking increase in newsletter signups by 62% to reach 9000 subscribers in just one year. an experience that emphasized the power of data-driven decisions. My Academic journey has fortified my knowledge of data-driven strategy, marketing analytics, and optimization techniques. Furthermore, I am proficient in advanced Excel, Google Analytics, and visualization tools.<br>
I am both a team player and a decisive leader.<br>

You can see more information in my [**CV**](https://github.com/almostoutlier/Data-Analysis-Portfolio/blob/main/Virinchi%20Alahari%20Resume.pdf).

This repository was created to showcase my analytical and technical skills (Excel, Python, R, SQL, Tableau, Power BI, PowerPoint, and others).
## Contents
* [About me](#about-me)
* [Portfolio Projects](#portfolio-projects)
  - [Sonar (Rocks vs. Mines)](#sonar) 
  - [Social Distancing Monitor](#social-distancing-monitor) 
  - [Humanoid Robot](#robot)
  - [Pokémon EDA](#pokemon-analysis)
* [Study projects](#study-projects)
  - [Movie Over Time Analysis](#movie-analysis)
  - [Excel Exercises](#excel-exercises)
  - [SQL Exercises](#sql-exercises)
* [Certificates](#certificates)
* [Contacts](#contacts)
## Portfolio Projects
This section contains a list of projects with brief descriptions.
### Sonar (Rocks vs. Mines) 
**Description:** The dataset, sourced from the XYZ website, encompasses two files: "sonar.mines" and "sonar.rocks." It contains a total of 111 patterns from sonar signals bounced off metal cylinders and 97 patterns from rocks, gathered under similar conditions. Each pattern comprises 60 numbers indicating energy within frequency bands over time, with labels "R" for rocks and "M" for mines, sorted by aspect angles. These files are consolidated into one dataset named "sonar.all-data." After meticulous data preprocessing and feature engineering, the logistic regression model was fine-tuned to optimize its predictive capabilities. With an R-squared value of 0.81, indicating the proportion of variance in the target variable explained by the model, and an accuracy rate of 88%, the logistic regression model demonstrated robustness in distinguishing between rocks and mines based on the sonar data patterns.<br>
**Dataset:** <a href = "https://archive.ics.uci.edu/dataset/151/connectionist+bench+sonar+mines+vs+rocks"> 
<code>Connectionist Bench Sonar Mines vs Rocks</code></a> <br>
**Code:** <a href = "https://github.com/almostoutlier/Projects/blob/main/Rocks_vs_Mines.ipynb">
<code>Code</code></a> <br>

### Social Distancing Monitor
**Description:** We will employ YOLOv3, pretrained on the COCO dataset, for object detection. While single-stage detectors like YOLO may be less accurate than two-stage detectors, they offer significant speed advantages. YOLO treats object detection as a regression problem, predicting bounding box coordinates and class label probabilities simultaneously. It returns person prediction probabilities, bounding box coordinates, and centroids. Non-maxima suppression (NMS) is applied to reduce overlapping bounding boxes. Centroids of the detections are computed, and pairwise distances are analyzed to identify people within a certain pixel distance threshold.<br>
**Colab:** <a href = "https://colab.research.google.com/drive/1UNRqDZCyqYc1Z4txhDqVNLER_0PNgpbX?usp=sharing"> 
<code>Colab Link</code></a> <br>
![alt text](image.png)

## Acadamic Projects
This section contains a list of projects which are a part of my acadamics with brief descriptions.

### Flight Delay Prediction 
**Description:** This dataset contains information about flights in three modules; Airlines, Airports and Flights.
All the required data is present in "Flights" module. This includes flight details, departure and arrival airports, flight delays, cancellations and reasons for the same.
Using this data we will predict the status of the flight and the corresponding reason. 
Objectives:

If a flight will be on time/ delayed/ cancelled? (Multiclass Classification Model)
Confusion Matrix on Test Data
 precision    recall  f1-score   support

           C       1.00      1.00      1.00        99
           D       0.94      0.95      0.94      1789
           N       0.99      0.99      0.99      8125

    accuracy                           0.98     10013
   macro avg       0.97      0.98      0.98     10013
weighted avg       0.98      0.98      0.98     10013
![alt text](image-1.png)

If the Flight is being delayed, what could be the reason for it? (Multilabel Classification Model)
Confusion Matrix on Test Data
Accuracy Score:  0.8561869569559573
Hamming Loss:  0.05
[[[8947  265]    [[9997    0]   [[9156  208]     [[8918  275]      [[9666   47]
  [ 442  359]]    [  16    0]]    [ 482  167]]     [ 355  465]]     [ 261   39]]]


If the flight is being delayed, by how many minutes it is going to get delayed? (Regression Model)
    Data       RMSE        MAE      MAPE
0  Train  32.210859  24.042234  0.444889
1    Val  32.409667  24.199183  0.449289
2   Test  32.224404  24.060442  0.441072
Based on these observations:

The model performs consistently across different datasets (training, validation, and test) based on RMSE, MAE, and MAPE metrics.
The RMSE and MAE values suggest that the model's predictions are, on average, around 32 units away from the true values.
The MAPE values indicate that the model's predictions have a very low average percentage difference from the true values, suggesting good accuracy.
<br>
**Dataset:** <a href = "https://www.kaggle.com/datasets/usdot/flight-delays?select=flights.csv"> 
<code>2015 Flight Delays and Cancellations</code></a> <br>
**Link:** <a href = "https://github.com/almostoutlier/Projects/blob/main/Flights_Delay.ipynb">
<code>Github Link</code></a> <br>

### Movie Performance Overtime 
**Description:** The TMDB dataset, encompassing over 700,000 movies up to July 2023, provides a comprehensive array of data points including cast, crew, plot keywords, budget, revenue, and more. To enhance usability, the dataset underwent meticulous cleaning, refining the initial .csv format by eliminating blank fields in key metrics. This refinement resulted in a condensed dataset of 9,678 movies. Additionally, calculated fields for gross profit and profit percentage were introduced. Leveraging Tableau, filters were implemented to distinguish between animated and conventional genres, while data integration techniques were applied to enhance insights, particularly focusing on the highest-grossing actors. This curated dataset serves as a versatile tool for researchers, analysts, and industry professionals, facilitating various applications from historical analysis to predictive modeling of box office revenue.<br>
**Dataset:** <a href = "https://www.kaggle.com/datasets/akshaypawar7/millions-of-movies"> 
<code>Movies Daily Update Dataset</code></a> <br>
**Powerpoint & Dashboard:** <a href = "https://docs.google.com/presentation/d/1ZDyQ4bzW7ycv3ulfHb307G-25ZoXJPkw/edit?usp=sharing&ouid=100940698311259880524&rtpof=true&sd=true">
<code>Slides</code></a> <br>

## Certificates
* [Introduction to Airflow in Python Certificate](https://github.com/almostoutlier/Certificates/blob/main/airflow%20in%20python.pdf) - Datacamp, 2024
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
