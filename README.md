# University Residency Recommendation System

This project aims to recommend the residency that best suits students at the university based on their survey responses. The recommendation system utilizes various machine learning algorithms to analyze survey data and suggest the most suitable residency option for each student.

# Dataset
The dataset used in this project is surveyResponses.csv, which contains the survey responses of students. Additionally, parsedSurveyData.csv is created as a preprocessed version of the survey data to facilitate the analysis.

# Methods and Libraries
The project explores different machine learning methods and libraries to determine the most effective model for residency recommendation. The following methods and libraries are utilized:

**Decision Trees:** Each node in the tree represents a choice based on student characteristics, leading to a leaf that designates their best-fit residence.  <br />
**Linear Regression:** Ridge is used to shrink personality coefficients to near zero, reduce overfitting, but does not perform feature selection so forward selection methods were used with cross validation.  <br />
**Logistic Regression:** Returns probability for each class, allowing clear understanding of likelihood of features given to a student.  <br />
**Neural Network:** Complex non-linear relationships between personality traits can be determined through a neural network.  <br />
**Support Vector Machines (SVM):** The SVM's hyperplane acts as a decision boundary to segregate students into distinct residence categories based on their profiles.  <br />
**K-Means Clustering + K-nearest Neighbor:** It then looks at all residences that each user in a specific group has been too, assigns that entire cluster as a “user”, to create a user-residence matrix, where a row is a user cluster, and the columns are the ratings of what residences the users in that cluster have rated. 


By: Sneh, Ben, Sher, and Shailleze

Presentation: https://docs.google.com/presentation/d/1nDgpNrZwOl35--tjuxm0ywR6OkhNQ-3UBR4bYnW80C4/edit?usp=sharing 
