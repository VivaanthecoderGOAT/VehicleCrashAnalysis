# VehicleCrashAnalysis
This project provides a comprehensive analysis of Texas traffic crash data, combining exploratory data analysis (EDA), predictive modeling, and clustering to uncover key insights and identify high-risk areas. The primary goals are to understand the underlying patterns in traffic incidents, predict the severity of crashes, and pinpoint crash hotspots.

Key Features:
In-Depth Exploratory Data Analysis (EDA): The project begins by cleaning the dataset and creating new features, such as categorizing crash times into intuitive periods (e.g., Morning, Afternoon, Evening). It then generates a series of visualizations to explore trends, including:

Crash distribution by time of day.

Annual crash trends from 2017-2023.

The top 10 most dangerous streets by crash frequency.

The most common types of collisions.

Crash Severity Prediction: A machine learning model is developed to predict the severity of a crash.

Model: A RandomForestClassifier is used for its robustness and interpretability.

Feature Experimentation: The script systematically tests multiple combinations of features (e.g., location only, time only, all features combined) to identify the most predictive set.

Hyperparameter Tuning: GridSearchCV is employed to find the optimal parameters for the Random Forest model, ensuring the best possible performance.

Evaluation: The model's effectiveness is thoroughly assessed using a classification report, accuracy score, and a confusion matrix to visualize its predictive power.

Crash Hotspot Identification:

Clustering: KMeans clustering is applied to location-based features to group crashes into distinct geographical hotspots.

Heatmap Visualization: The analysis identifies the top 10 crash-prone streets and generates a heatmap showing crash frequency on these streets across different times of day, making it easy to see when and where crashes are most likely to occur.

Technologies Used:
Python

Pandas: For data manipulation and analysis.

Matplotlib & Seaborn: For data visualization.

Scikit-learn: For machine learning, including LabelEncoder, RandomForestClassifier, GridSearchCV, and KMeans.
