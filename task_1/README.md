# Task 1: Python, Pandas, Preprocessing, and Git Basics

## Dataset: Student Performance Dataset

This task introduces the basic workflow used in Machine Learning projects:
**loading data → cleaning → exploring → visualizing → preprocessing → saving → version control**

---

## 📊 Task 1.1: Data Exploration & Cleaning

### Steps to perform:

* Load the dataset using **Pandas**.

* Display:

  * first 5 rows
  * column names
  * dataset shape
  * data types

* Handle missing values (drop or fill, explain your choice).

* Standardize column names (lowercase, replace spaces with `_`).

* Convert at least **one categorical/text column** to lowercase.

* Find:

  * top 10 students based on **final score / performance index**
  * average score grouped by **gender OR parental education OR study time**

---

## 📈 Task 1.2: Visualization & Insights

Create at least **two plots**, such as:

* score distribution histogram
* bar chart of average score by category (gender / study time / school support)
* correlation heatmap of numeric columns

Write **2–3 short insights** from your plots.

---

## ⚙️ Task 1.3: Feature Engineering & Preprocessing

* Create a new column such as:

  * **effort_score = study_time / absences**
    OR
  * **total_score = sum of subject scores**
    OR
  * any meaningful derived metric

* Convert any column if needed:

  * yes/no → 1/0
  * category encoding OR unit formatting

* Scale numeric features using:

  * **StandardScaler** OR
  * **MinMaxScaler**

* Save the cleaned dataset as:

  `processed.csv`

---

## 🌿 Task 1.4: Git Practice

* Create a branch named **fun**
* Upload a screenshot of a scene from your favorite movie
* The movie name must **NOT** be visible in the screenshot
* Create a file named **movie.env**
* Add the movie name inside `movie.env`
* Ensure `movie.env` is added to `.gitignore` and **not pushed**

---

## ✅ Submission Instructions

* Fork the repository
* Add your notebook/script inside the task folder
* Include:

  * your code
  * outputs/plots
  * explanation.md describing what you understood

If you have doubts, feel free to ask in the group or DM a mentor 🙂
