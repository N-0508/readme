🎬 Movies Data Analysis
This is a data analysis and visualization project based on a cleaned dataset of 9,800+ popular movies. It uses Python libraries such as pandas, matplotlib, and seaborn to explore trends in movie genres, popularity, votes, and more.

📁 Dataset Overview
The dataset contains 9 columns and 9827 original entries, with features like:

Release_Date (Year extracted from full date)

Title

Overview (Dropped in cleaning)

Popularity

Vote_Count

Vote_Average (Categorized into 4 popularity groups)

Original_Language (Dropped in cleaning)

Genre (Exploded into single-genre rows)

Poster_Url (Dropped in cleaning)

After cleaning and exploding the Genre column, the dataset contains 25,552 rows and 6 relevant columns.

🧼 Data Cleaning Steps
Dropped columns not useful for analysis (Overview, Original_Language, Poster_Url)

Converted Release_Date to year only

Categorized Vote_Average into:

not_popular, below_avg, average, popular

Handled genres:

Split multi-genre entries into lists

Exploded into individual rows

Converted to categorical type

Removed NaNs (now dataset is clean!)

📊 Key Visualizations & Insights
Most Frequent Genre: 🎭 Drama (appears in over 14% of entries)

Most Popular Movie: 🕷️ Spider-Man: No Way Home

Least Popular Movie(s): The United States vs. Billie Holiday and Threads

Highest Movie Release Year: 📅 2020 saw the most movie releases

Vote Analysis: Majority of movies fall into the popular or not_popular categories

🛠 Technologies Used
Python 🐍

Pandas 📊

Matplotlib 📈

Seaborn 🎨

Jupyter Notebook / PDF Report









