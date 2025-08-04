Netflix Titles Analysis
📌 Project Overview
This project performs exploratory data analysis (EDA) on a dataset containing information about Netflix titles such as movies and TV shows. The notebook uses Python and Pandas to analyze and visualize key insights like:

Distribution of content by type and country

Trends in content release years

Analysis of genres and durations

Missing values and data cleaning

🗂️ Dataset
The dataset used is a sample of Netflix titles (netflix_titles_sample.csv), which includes the following columns:

show_id

type

title

director

cast

country

date_added

release_year

rating

duration

listed_in

description

⚙️ Libraries Used
pandas

numpy



🧹 Data Cleaning & Preprocessing
Standardized column names

Removed missing values in critical columns

Extracted year, month, and day from date_added

Converted durations into numeric format for analysis

📊 Key Insights
Most content on Netflix is movies (~70%+).

The USA has the highest number of Netflix titles.

TV Shows tend to have shorter durations, while movies vary significantly.

Popular genres include dramas, comedies, and documentaries.



📁 How to Run
Clone the repository

Install required libraries:

bash
Copy
Edit
pip install pandas 
Run the notebook in Jupyter or VS Code

