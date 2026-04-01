📚 StudyTrack AI – Student Study Behavior Analysis

StudyTrack AI is a Machine Learning-based system that analyzes student study behavior and provides personalized study recommendations to improve academic performance.

🚀 Project Overview

StudyTrack AI is a Machine Learning-based intelligent system developed as part of the Infosys Springboard Virtual Internship Program.

It analyzes student study behavior and generates personalized study recommendations to improve academic performance and productivity.

The system leverages behavioral data such as:

Study duration
Quiz performance
Distraction levels
Learning patterns

…to transform raw data into actionable insights and optimized study strategies.

🎯 Problem Statement

Students often face challenges in:

Identifying effective study strategies
Maintaining consistency
Managing distractions
Improving academic performance

StudyTrack AI addresses these challenges by:

✔ Analyzing behavioral patterns
✔ Clustering students based on study habits
✔ Predicting performance trends
✔ Recommending personalized study routines

🧠 Key Features
Behavioral Data Analysis – Clean and process study logs to uncover patterns
Student Clustering – Identify student types using K-Means / DBSCAN
Performance Prediction & Risk Analysis – Track and predict academic performance trends
Personalized Study Recommendations – Generate tailored study plans and strategies
Interactive Dashboard – Visualize clusters, insights, and recommendations using Streamlit
Admin Model Retraining – Update ML models with new data seamlessly
🧩 Project Modules
🔹 Module 1: Data Preprocessing & EDA

Objective: Prepare and analyze raw student data.
Key Functionalities:

Data cleaning and preprocessing
Handling missing values
Feature normalization
Exploratory Data Analysis (EDA) and correlation analysis

Output:

Cleaned dataset
Feature insights and trends
🔹 Module 2: Clustering & Pattern Detection

Objective: Identify different types of student behavior.
Key Functionalities:

Apply clustering algorithms (K-Means / DBSCAN)
Group students based on study duration, focus level, and distraction frequency

Identified Clusters:

Focused Studiers
Short Burst Learners
Night Owls
Distracted Learners

Output:

Cluster labels and student grouping
Behavioral pattern insights
🔹 Module 3: Recommendation Engine

Objective: Provide personalized study plans.
Key Functionalities:

Suggest optimal study timings
Recommend break schedules (Pomodoro technique)
Generate weekly study plans
Predict performance improvements

Output:

Personalized study schedule
Recommended study strategies
Performance improvement insights
🔹 Module 4: Student UI & Admin Panel

Objective: Build an interactive application interface.

Student Interface:

Log study sessions
Track performance progress
View personalized recommendations

Admin Panel:

Upload datasets
Monitor system performance
Retrain machine learning models

Output:

Student dashboard
Admin dashboard
Performance tracking system
📊 System Architecture
Student Study Logs
        ↓
Data Collection & Preprocessing
        ↓
Behavior Clustering
        ↓
Performance Analysis
        ↓
Recommendation Engine
        ↓
Interactive Dashboard
📁 Project Structure
Study_Track_AI/
├── app.py                 # Main Streamlit application
├── app1.py                # Module 1 – Data Preprocessing & EDA
├── app2.py                # Module 2 – Clustering & Pattern Detection
├── app3.py                # Module 3 – Recommendation Engine
├── app4.py                # Module 4 – UI & Admin Panel
├── study_logs.csv
├── students_with_clusters.csv
├── requirements.txt
├── styles.css
└── README.md
⚙️ Installation & Setup
# Clone the repository
git clone https://github.com/FutureTechLearners/Study_Track_AI.git

# Navigate to project folder
cd Study_Track_AI

# Install required dependencies
pip install -r requirements.txt

# Run the application
streamlit run app.py
📈 Outcomes
Improved study efficiency
Data-driven decision making
Personalized learning experience
Scalable AI-based education solution
🔐 Future Scope
Mobile application development
Deep learning integration for advanced insights
Real-time study tracking
Integration with Learning Management Systems (LMS)
Advanced analytics and predictive modeling
🎓 Internship Details
Program: Infosys Springboard Virtual Internship
Domain: Artificial Intelligence / Machine Learning
Project Type: Real-world Problem Solving
👨‍💻 Team – FutureTechLearners
Vidya Sagar Kothamasu

🌟 Acknowledgements

We sincerely thank Infosys Springboard for providing this opportunity to work on a real-world AI/ML project and guiding us throughout the internship.
Praneetha Chirakala
Akshaya Thirumala
Aniket Khanderao Lingayat
