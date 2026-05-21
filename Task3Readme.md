🎬 Netflix Exploratory Data Analysis (EDA)

Problem Statement
------------------

With the rapid growth of streaming platforms, understanding content distribution and viewer targeting has become crucial.  
This project aims to analyze Netflix’s content library to identify key patterns such as:

- What type of content dominates Netflix (Movies or TV Shows)?
- Which countries contribute the most content?
- What are the most common genres and ratings?
- How has Netflix content evolved over time?

The goal is to extract meaningful insights using Exploratory Data Analysis (EDA) techniques.

📂 Dataset Details

The dataset used in this project is the **Netflix Titles Dataset**, which contains metadata of movies and TV shows available on Netflix.

Key Features:

- `title` → Name of the movie/TV show  
- `director` → Director of the content  
- `cast` → Actors involved  
- `country` → Country of production  
- `date_added` → Date added to Netflix  
- `release_year` → Year of release  
- `rating` → Audience rating (TV-MA, PG, etc.)  
- `duration` → Duration of movie/show  
- `listed_in` → Genre/category  
- `description` → Content summary  

---

⚙️ Approach

The project follows a structured data analysis workflow:

1. Data Collection
- Loaded dataset using Pandas

2. Data Cleaning
- Handled missing values by replacing categorical nulls with `"Unknown"`
- Converted `date_added` column into datetime format
- Checked and verified data types

3. Exploratory Data Analysis (EDA)
- Analyzed distribution of Movies vs TV Shows
- Studied content trends over the years
- Identified top contributing countries
- Explored most popular genres
- Analyzed rating distribution

4. Data Visualization
- Used Matplotlib and Seaborn for insights visualization
- Applied a Netflix-inspired dark theme for better visual storytelling

📊 Results & Key Insights

The analysis revealed several important insights:

- 🎥 Movies dominate Netflix content compared to TV Shows
- 🌍 **United States is the largest contributor of Netflix content
- 🎭 **International Movies and Dramas are the most common genres**
- ⭐ **TV-MA and TV-14 are the most frequent ratings, indicating focus on mature audiences**
- 📈 **Netflix content has significantly increased after 2015**

🎯 Conclusion

This project demonstrates how raw entertainment data can be transformed into meaningful insights using Python-based data analysis techniques.  

Through visualization and EDA, we successfully identified key trends in Netflix’s content strategy, audience targeting, and global content distribution.

This analysis improves understanding of real-world data handling, cleaning, and storytelling using data.

🛠️ Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

👩‍💻 Author

Varshini Nayak  
B.Sc. Computer Science Student   