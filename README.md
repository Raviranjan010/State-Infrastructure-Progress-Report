🛣️ Project Overview: Road Construction Analysis under PMGSY
This project provides an in-depth analysis of road construction initiatives under the Pradhan Mantri Gram Sadak Yojana (PMGSY). The aim is to explore patterns in project distribution, assess completion rates, and evaluate the length of roadwork sanctioned and completed across different Indian states.

🎯 Objectives
✅ Analyze the average road length sanctioned per project and per state
✅ Identify states with the highest number of sanctioned projects
✅ Visualize insights using Pivot Tables and Charts
✅ Provide actionable insights to monitor the progress of PMGSY implementation



📂 Dataset Overview
File: roadconstruction.csv

Key Columns:

STATE_NAME: Name of the state

LENGTH_OF_ROAD_WORK_SANCTIONED_KM: Sanctioned road length (in km)

LENGTH_OF_ROAD_WORK_COMPLETED_KM: Completed road length (in km)

PROJECT_ID or UNIQUE_ID: Unique identifier for each project

road_completion_: Completion status (1 = completed, 0 = not completed)

📈 Pivot Table Analysis
1️⃣ Average Road Length per Project
Setup:

Rows: STATE_NAME

Values: LENGTH_OF_ROAD_WORK_SANCTIONED_KM → Set to Average

2️⃣ Road Completion Rate (%) by State
Setup:

Rows: STATE_NAME

Values:

LENGTH_OF_ROAD_WORK_SANCTIONED_KM → Sum

LENGTH_OF_ROAD_WORK_COMPLETED_KM → Sum

Calculated Field:

Completion Rate (%) = (Completed Length ÷ Sanctioned Length) × 100

📊 Visualizations
🔘 Donut Chart – Share of sanctioned projects by state
📏 Bar Chart – Road completion rate per state
📐 Table View – Average road length per project

🛠️ Tools Used
Microsoft Excel – Pivot Tables, Charts, and Calculated Fields

GitHub – Version control and code sharing

