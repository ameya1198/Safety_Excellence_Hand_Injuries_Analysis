# Safety_Excellence_Hand_Injuries_Analysis
Problem Statement:
The Safety Excellence Group (S.E.G.) aims to reduce workplace injuries. A major focus for their clients is hand injury prevention, particularly within the manufacturing sector.
Using data from OSHA’s Severe Injury Reports, we were tasked with analyzing how most hand injuries occur and extracting meaningful insights.

Objectives:
Manipulate and filter OSHA data to isolate hand-related injuries in manufacturing (based on NAICS codes). The codes are provided in another csv. 
Analyze common causes and patterns in these injuries.

BONUS PROBLEM STATEMENT: Apply AI/NLP techniques to extract keywords from the “Final Narrative” field to enhance understanding of injury causes.
Present insights using a dashboard for intuitive exploration.

Our Solution
Data Preprocessing – Cleaned and filtered the OSHA Severe Injury dataset to focus on manufacturing industry and hand-related incidents.
Exploratory Data Analysis – Identified top causes, tools, and machinery involved in hand injuries.
NLP Keyword Extraction – Used a Large Language Model (LLM) to extract key injury descriptors from incident narratives.
Interactive Dashboard – Built a dashboard to visually explore the patterns, keywords, and trends across injury types, locations, and narratives.

Deliverables
data/ – Cleaned and processed datasets.
notebooks/ – Jupyter notebooks for data analysis and NLP keyword extraction.
dashboard/ – Interactive visual dashboard with filters and insights.

How to Use
Clone the repo
Open the notebook or dashboard folder
Launch the dashboard or explore the insights through code/notebooks
