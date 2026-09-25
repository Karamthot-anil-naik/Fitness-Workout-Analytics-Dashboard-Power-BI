🏋️ Fitness & Workout Analytics Dashboard — Power BI

📊 Dashboard Preview

🏋️ Work Type Analysis



👥 Gender Analysis



📈 Experience Level Analysis



📊 Work Type Analysis — Detailed View



🎯 Project Objectives

Analyze workout patterns across different exercise types

Compare fitness metrics between male and female participants

Analyze fitness performance by experience level

Track calories burned and workout frequency

Analyze BMI and body-fat percentage

Compare heart-rate metrics

Analyze water intake and workout duration

Build an interactive Power BI dashboard for data exploration

📌 Key Metrics

The dashboard includes analysis of:

Average BPM

Average BMI

Average Calories Burned

Average Max BPM

Average Fat Percentage

Average Resting BPM

Workout Frequency

Session Duration

Water Intake

Workout Type

Gender

Experience Level

📊 Dashboard Analysis

Gender Analysis

The gender analysis page compares fitness metrics across male and female participants, including:

Calories Burned

BMI

Fat Percentage

Workout Type Distribution

Max BPM

Average BPM

Resting BPM

Water Intake

Experience Analysis

The experience-level analysis allows fitness metrics to be explored across different experience levels.

Workout Type Analysis

The dashboard compares major workout categories:

Strength

Cardio

HIIT

Yoga

Metrics can be filtered interactively to explore differences between workout types.

🛠️ Tools & Technologies

Power BI Desktop

Power Query

DAX

Data Cleaning

Data Transformation

Data Modeling

Data Visualization

CSV Dataset

🔄 Data Analysis Workflow

Raw Gym Member Dataset
        ↓
Data Cleaning
        ↓
Data Transformation
        ↓
Data Modeling
        ↓
DAX Measures
        ↓
KPI Development
        ↓
Interactive Visualizations
        ↓
Power BI Dashboard

📂 Repository Structure

PowerBI-Fitness-Workout-Dashboard/
│
├── README.md
├── my.work.pbix
├── gym_members_exercise_tracking.csv
│
├── gender-analysis.png
├── experience-analysis.png
├── work-type analysis.png
└── work-type analysis - Copy.png

📁 Project Files

File

Description

my.work.pbix

Power BI dashboard source file

gym_members_exercise_tracking.csv

Dataset used for analysis

gender-analysis.png

Gender analysis dashboard

experience-analysis.png

Experience-level analysis

work-type analysis.png

Workout type analysis

work-type analysis - Copy.png

Additional workout analysis screenshot

🧮 DAX & Power BI

The dashboard uses DAX measures for analytical KPIs such as averages of:

Calories Burned

BMI

Fat Percentage

Max BPM

Resting BPM

Workout Frequency

Example:

Average Calories Burned =
AVERAGE('gym_members_exercise_tracking'[Calories_Burned])

Average BMI =
AVERAGE('gym_members_exercise_tracking'[BMI])

Average Fat Percentage =
AVERAGE('gym_members_exercise_tracking'[Fat_Percentage])

The exact DAX measure names may differ depending on the final Power BI data model.

💡 Skills Demonstrated

Power BI Dashboard Development

DAX

Power Query

Data Cleaning

Data Transformation

Data Modeling

KPI Development

Exploratory Data Analysis

Data Visualization

Interactive Reporting

Business Intelligence

🚀 How to Use

Download or clone this repository.

Open my.work.pbix using Power BI Desktop.

If Power BI asks for the dataset location, select gym_members_exercise_tracking.csv.

Refresh the data if required.

Use the slicers and visual interactions to explore the dashboard.

👨‍💻 Author

Karamthot Anil Naik

Aspiring Data Scientist | Machine Learning | NLP | Power BI

GitHub: Karamthot-anil-naik

📌 Project Purpose

This project demonstrates practical experience in data analysis, Power BI, DAX, data visualization, and interactive business intelligence dashboard development using a fitness and workout dataset.
