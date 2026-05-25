# Description

The practical part of my thesis was to build a prediction model to predict if a student will pass or fail a course using non-academic factors. The goal of this project was to see how strongly other factors influence performances of students in their courses so teachers could be able to identify does who need special attention.

## About the Dataset

The Open University Learning Analytics Dataset (OULAD) contains data about courses, students and their interactions with Virtual Learning Environment (VLE) for seven selected courses. 3 out of the Dataset files were merged together for this project.

There were a total of 182,735 entries when they were all merged together.

Dataset archive URL: https://archive.ics.uci.edu/dataset/349/open+university+learning+analytics+dataset

The dataset was in its raw form and contained null values

## Process

* Data exploration and Data cleaning
* Data Visualization to understand the patterns
* Data transformation for both categorical data and numerical data
* Split data into test and training sets
* Trained and compared 4 maching learning algorithms
* Performed feature importance analysis


## Challenges
* Gathering the right dataset, there are tons of data available online and it took a long time to find the suitable dataset.
* The bulk of the work was in the dataset, ensuring it properly clean, understanding the relationships between different variables, and ensuring contains necessary values needed to train the model
* Time was a bit limited as this project, could have dived deeper and tested more algorithms to improve the model.


## Improvements or future work
* Instead of using test/train split, k-fold cross-validation will be used to achieve a more robust model perfomance
* Hyperparameter tuning will be applied to optimize model performance and improve predictive accuracy
* Feature engineering will be explored to enhance model performance and capture more meaningful patterns in the data
* Development of a web application to integrate the model for real-time student performance prediction.
