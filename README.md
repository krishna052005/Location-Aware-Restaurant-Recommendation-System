#Location-Aware Restaurant Recommendation System

A real-world machine learning recommender system that suggests restaurants based on user location, cuisine preference, and budget using distance-based similarity models.\
This project is inspired by food discovery platforms like Zomato and Yelp.
---

# 📌 Problem Statement

With thousands of restaurants available in food delivery and review platforms, users often struggle to find places that match their location, food preferences, and budget.\
Objective:\
Build a location-aware restaurant recommendation system that:\
Accepts user preferences (city, cuisine, budget)\
Uses geographical and restaurant metadata\
Recommends the most relevant restaurants using ML similarity techniques
---

# 🚀 Features

Real-world restaurant dataset\
Location-aware recommendations using latitude & longitude\
Cuisine and budget-based filtering\
Distance-based KNN recommendation model\
Exploratory Data Analysis (EDA) with insights\
User input–driven recommendations\
---

# 🧠 Real-World Challenges Addressed

Sparse and uneven restaurant ratings
Geographical constraints (distance matters)
Popularity bias (ratings vs votes)
Cold-start users (no past history)
---

# 📊 Dataset

Source: Kaggle
Dataset: Zomato Global Restaurant Dataset
Size: ~9,500 restaurants
Type: Static CSV dataset

Key Attributes Used:
Restaurant Name
City
Latitude & Longitude
Cuisines
Average Cost for Two
Aggregate Rating
Votes
---

# Tech Stack

| Category            | Tools                            |
| ------------------- | -------------------------------- |
| Language            | Python                           |
| Data Processing     | Pandas, NumPy                    |
| Visualization       | Matplotlib, Seaborn              |
| Machine Learning    | K-Nearest Neighbors (KNN)        |
| Feature Engineering | Label Encoding, Standard Scaling |
| Platform            | Jupyter Notebook                 |

---
# 🔍 Exploratory Data Analysis (EDA)

The EDA phase focuses on:

Identifying top restaurant cities
Analyzing popular cuisines
Understanding cost vs rating trends
Observing restaurant density patterns

Key Insights:
Metro cities dominate restaurant availability
Mid-range restaurants often receive higher ratings
Cuisine popularity varies significantly by location
High vote count improves trust in ratings
---

# 🤖 Model Used
🔹 K-Nearest Neighbors (KNN)

Uses Euclidean distance
Works well for similarity-based recommendations
Naturally supports location-aware filtering
Ideal for cold-start users

🔹Features Used for Similarity
Latitude & Longitude
Encoded City
Encoded Cuisine
Average Cost for Two
Aggregate Rating
---

#🎯 How Recommendations Work

User provides:
City
Preferred cuisine
Budget for two
Input is encoded and scaled
KNN finds nearest restaurants based on similarity
Top matching restaurants are returned
