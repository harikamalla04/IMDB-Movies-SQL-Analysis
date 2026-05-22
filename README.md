# 🎬 IMDB Movies SQL Analysis Project

## 📌 Project Objective

The objective of this project is to analyze the IMDB Movies Database using SQL queries and generate meaningful insights about movies, directors, ratings, popularity, revenue, and audience engagement. This project helps in understanding real-world database operations, SQL querying techniques, and analytical problem-solving using relational databases.

---

# 📂 Dataset Used

The dataset consists of two relational tables:

* Directors Table
* Movies Table

The dataset contains information related to:

* Movie titles
* Budgets
* Revenue
* Popularity
* Ratings
* Vote counts
* Directors
* Release dates

---

# ❓ Questions (KPIs)

* Retrieve all movie details
* Retrieve all director details
* Count total number of movies in IMDB
* Find directors:

  * James Cameron
  * Luc Besson
  * John Woo
* Find directors whose names start with “S”
* Count female directors
* Find the 10th female director
* Find the top 3 most popular movies
* Find the top 3 most bankable movies
* Find the highest rated movie after January 1st, 2000
* Find movies directed by Brenda Chapman
* Find the director who made the most movies
* Find the most bankable director

---

# ⚙️ Process

* Connected MySQL database using Python and SQL Connector
* Imported and explored movie and director datasets
* Verified data consistency and checked for missing values
* Performed table merging using Primary Key and Foreign Key relationships
* Executed SQL queries for movie and director analysis
* Applied filtering, sorting, aggregation, and JOIN operations
* Extracted insights based on movie popularity, ratings, and revenue
* Documented all outputs and analysis in Jupyter Notebook

---

# 🛠️ Tools & Technologies Used

* SQL
* MySQL
* Python
* Pandas
* Jupyter Notebook
* MySQL Connector
* VS Code

---

# 🔍 SQL Concepts Used

* SELECT Statements
* WHERE Clause
* ORDER BY
* GROUP BY
* Aggregate Functions
* INNER JOIN
* LIMIT
* LIKE Operator
* COUNT()
* AVG()
* SUM()
* MAX()

---

# 📚 Python Libraries Used

* pandas
* mysql-connector-python
* jupyter

---

# 🔗 Data Relationship

## Directors Table

| Column     | Description        |
| ---------- | ------------------ |
| id         | Unique director ID |
| name       | Director Name      |
| gender     | Gender of director |
| department | Department         |

## Movies Table

| Column         | Description           |
| -------------- | --------------------- |
| id             | Unique movie ID       |
| original_title | Movie Name            |
| budget         | Movie Budget          |
| popularity     | Popularity Score      |
| release_date   | Release Date          |
| revenue        | Revenue Generated     |
| vote_average   | Average IMDB Rating   |
| vote_count     | Total Votes           |
| overview       | Movie Description     |
| tagline        | Movie Tagline         |
| uid            | Unique Movie ID       |
| director_id    | Director Reference ID |

---

# 📊 Project Insights

* Identified the most popular movies based on popularity score
* Found the highest revenue-generating movies
* Analyzed directors with maximum movie contributions
* Explored female director representation in the dataset
* Determined highly rated movies released after the year 2000
* Understood relationships between movie ratings, popularity, and revenue

---

# 📈 Key Findings

* Popular movies generally received higher vote counts
* Revenue and popularity are major indicators of movie success
* Some directors consistently produced high-revenue movies
* Female directors represented a smaller percentage compared to male directors
* Movies released after 2000 showed strong audience engagement

---

# 🚀 Learning Outcomes

Through this project, I learned:

* Writing efficient SQL queries
* Using aggregate functions in SQL
* Applying JOIN operations between tables
* Working with relational databases
* Connecting SQL databases with Python
* Performing real-world movie data analysis
* Extracting insights from structured data

---

# ▶️ How to Run the Project

## Step 1: Install Required Libraries

```bash id="4xv5f0"
pip install pandas mysql-connector-python
```

## Step 2: Open Jupyter Notebook

```bash id="q9q6di"
jupyter notebook
```

## Step 3: Run the Project File

```bash id="vtlycu"
IMDB_movies_project.ipynb
```

Run all cells sequentially to view outputs and analysis.

---

# 📷 Project File

* IMDB_movies_project.ipynb

The notebook contains:

* Database connection setup
* SQL queries
* Data analysis
* Query outputs
* Insights and findings

---

# 🔮 Future Improvements

* Build interactive dashboards using Power BI or Tableau
* Add data visualization using Matplotlib and Seaborn
* Perform predictive analysis on movie success
* Develop movie recommendation systems

---

# 👩‍💻 Author

**Malla Harika**
Aspiring Data Analyst | SQL Enthusiast | Python Learner

---

# ✅ Final Conclusion

This project demonstrates practical SQL and analytical skills using a real-world IMDB movie dataset. It highlights the ability to work with relational databases, perform complex SQL queries, analyze movie industry trends, and generate meaningful business insights through structured data analysis.
