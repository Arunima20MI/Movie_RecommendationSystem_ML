# 🎬 Movie Recommendation System using Machine Learning

## 📌 Project Overview

This project is a **Movie Recommendation System** built using **Python**, **Machine Learning**, and **Natural Language Processing (NLP)** techniques.
The system recommends movies similar to a user’s favorite movie based on genres, directors, and actors.

It also predicts movie ratings using a **Ridge Regression model** and provides visual insights through **Exploratory Data Analysis (EDA)**.

---

# 🚀 Features

* 📂 Dataset loading and preprocessing
* 🧹 Data cleaning and handling missing values
* 📊 Exploratory Data Analysis (EDA)
* 🔠 TF-IDF feature extraction
* 🤖 Movie rating prediction using Ridge Regression
* 🎯 Content-based movie recommendation system
* 📈 Visualization of model performance
* 🔍 Smart movie search with partial matching support

---

# 🛠️ Technologies Used

## Programming Language

* Python

## Libraries

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

---

# 📁 Dataset Information

The dataset file used is:

```bash id="0v0sxj"
movies_data.csv
```

### Expected Columns

* Name
* Genre
* Director
* Actor 1
* Actor 2
* Actor 3
* Year
* Duration
* Rating
* Votes

---

# ⚙️ Installation

## Step 1: Clone the Repository

```bash id="71qk3n"
git clone https://github.com/your-username/movie-recommendation-system.git
```

## Step 2: Navigate to Project Folder

```bash id="2x1y4m"
cd movie-recommendation-system
```

## Step 3: Install Required Libraries

```bash id="gwqax4"
pip install pandas numpy matplotlib seaborn scikit-learn notebook
```

---

# ▶️ Running the Project

## Start Jupyter Notebook

```bash id="a0sm9m"
jupyter notebook
```

## Open the Notebook File

```bash id="6z7j7r"
MoviePrediction.ipynb
```

Run all cells sequentially to execute the complete project.

---

# 📊 Exploratory Data Analysis

The project generates:

* Distribution of movie ratings
* Top 10 movie genres
* Movies released per decade

Saved as:

```bash id="y8g7y4"
eda_plots.png
```

---

# 🧠 Machine Learning Workflow

## 1. Data Cleaning

* Removes duplicates
* Handles missing values
* Converts numeric columns

## 2. Feature Engineering

Combines:

* Genre
* Director
* Actor names

into a single text feature.

## 3. TF-IDF Vectorization

Converts textual movie information into numerical vectors.

## 4. Model Training

Uses:

```python id="f5ep3f"
Ridge Regression
```

for movie rating prediction.

## 5. Model Evaluation

Metrics used:

* RMSE (Root Mean Squared Error)
* R² Score

---

# 🎯 Recommendation System

The recommendation system uses:

```python id="3xgqka"
Cosine Similarity
```

to find movies similar to the selected movie.

### Recommendation Logic

* Exact movie match
* Partial title match
* Substring search fallback
* Genre-based recommendation if movie not found

---

# 📸 Output Screenshots

## EDA Visualization

* Rating Distribution
* Genre Analysis
* Movies per Decade

## Prediction Plot

Saved as:

```bash id="b4a0px"
actual_vs_predicted.png
```

---

# 📂 Project Structure

```bash id="km7u8o"
movie-recommendation-system/
│
├── movies_data.csv
├── MoviePrediction.ipynb
├── eda_plots.png
├── actual_vs_predicted.png
README.md
```

---

# 📈 Sample Output

```bash id="qlq2g3"
Enter a movie you like: PK

✔ Found : 'PK'
Genre  : Comedy, Drama, Sci-Fi
Rating : 8.1

Top 5 Recommended Movies

1. 3 Idiots
2. Munna Bhai M.B.B.S.
3. Lage Raho Munna Bhai
4. OMG: Oh My God!
5. Taare Zameen Par
```

---

