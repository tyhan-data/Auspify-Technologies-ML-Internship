# 🎬 Netflix Machine Learning Internship Projects

### From Recommendation Systems to Time-Series Forecasting

Welcome to my machine learning internship project repository! This repository showcases the practical work I completed during my internship at **Auspify Technologies**, where I explored different machine learning techniques using the Netflix Movies and TV Shows dataset.

Throughout this journey, I worked on recommendation systems, classification, unsupervised learning, and time-series forecasting. Each task helped me strengthen my understanding of data preprocessing, feature engineering, model training, evaluation, and practical machine learning applications.

I also explored a final challenge focused on content success analytics, where I identified an important limitation of the available dataset: it lacked the performance metrics needed to reliably measure actual content success.

---

## 📌 Project Overview

The internship consisted of six tasks covering different machine learning concepts.

| Task | Project                               | Approach                               | Status                                                        |
| ---- | ------------------------------------- | -------------------------------------- | ------------------------------------------------------------- |
| 01   | Netflix Content Recommendation System | Recommendation System                  | ✅ Completed                                                   |
| 02   | Movie vs. TV Show Classification      | Supervised Learning                    | ✅ Completed                                                   |
| 03   | Content Rating Classification         | Supervised Learning                    | ✅ Completed                                                   |
| 04   | Netflix Content Segmentation          | Unsupervised Learning — K-Means        | ✅ Completed                                                   |
| 05   | Netflix Content Trend Forecasting     | Time-Series Forecasting                | ✅ Completed                                                   |
| 06   | Netflix Content Success Analytics     | Data Analysis & Feasibility Assessment | ⚠️ Explored; prediction not completed due to data limitations |

---

# 🚀 Tasks and Implementation

## 🎯 Task 01: Netflix Content Recommendation System

**Objective:** Build a recommendation system that suggests relevant Netflix titles based on content similarities.

### What I did

* Explored and prepared the Netflix dataset.
* Worked with content metadata, including titles and genres.
* Applied **TF-IDF vectorization** to represent textual information numerically.
* Used **cosine similarity** to measure the similarity between titles.
* Built a recommendation function to retrieve similar titles.
* Tested the system using new title inputs to examine its recommendation behavior.

### Key learning

I learned how recommendation systems can use content similarities to generate suggestions without requiring user watch histories or ratings.

**Machine learning concepts:** Text preprocessing, TF-IDF, vectorization, cosine similarity, recommendation systems.

---

## 🎬 Task 02: Movie vs. TV Show Classification

**Objective:** Develop a classification model to distinguish between movies and TV shows using available metadata.

### What I did

* Explored the dataset's features and target variable.
* Prepared the data for machine learning.
* Applied preprocessing and feature engineering where appropriate.
* Trained and evaluated classification models.
* Examined how content metadata can help distinguish between the two categories.

### Key learning

I gained practical experience with supervised classification, feature preparation, model training, and evaluation.

**Machine learning concepts:** Data preprocessing, feature engineering, supervised learning, classification, model evaluation.

---

## ⭐ Task 03: Content Rating Classification

**Objective:** Predict a title's content maturity rating using available metadata.

### What I did

* Examined the distribution of content ratings.
* Investigated class imbalance and the presence of less frequent rating categories.
* Prepared relevant features for classification.
* Compared multiple classification algorithms, including Logistic Regression, Decision Tree, Random Forest, and XGBoost.

### Key learning

I learned why class imbalance matters, why accuracy alone may not be sufficient, and how model evaluation metrics can provide a more meaningful comparison.

**Machine learning concepts:** Multiclass classification, class imbalance, model comparison, model tuning.

> **Note:** Here, content rating refers to maturity classifications such as TV-MA and TV-PG, not audience satisfaction or a title's commercial success.

---

## 🔍 Task 04: Netflix Content Segmentation

**Objective:** Discover groups of similar Netflix titles without relying on predefined target labels.

### What I did

* Explored similarities and differences among titles.
* Prepared genre information for clustering.
* Used **MultiLabelBinarizer** to represent titles with multiple genres.
* Applied the K-Means clustering algorithm.
* Investigated different cluster configurations using the elbow method and silhouette score.
* Examined the characteristics of the resulting clusters.

### Key learning

I learned how unsupervised learning can reveal patterns and similarities in a dataset without requiring a labeled target variable.

**Machine learning concepts:** Unsupervised learning, K-Means clustering, multi-label encoding, elbow method, silhouette score.

---

## 📈 Task 05: Netflix Content Trend Forecasting

**Objective:** Analyze historical Netflix catalog additions and use past observations to forecast future trends.

### What I did

* Processed date information to create time-based features.
* Aggregated title additions over time.
* Visualized historical content addition patterns.
* Built a baseline forecasting approach for comparison.
* Engineered lag features to represent previous observations.
* Trained a Random Forest regression model using historical information.
* Applied walk-forward validation to evaluate predictions over successive time periods.
* Examined forecasting performance using MAE, MSE, RMSE, and R².
* Generated future predictions and visualized the forecast.

### Key learning

This task helped me understand the difference between ordinary machine learning and forecasting, particularly the importance of chronological data, lag features, baseline comparisons, and time-aware validation.

**Machine learning concepts:** Time-series analysis, lag features, regression, Random Forest, baseline forecasting, walk-forward validation, forecasting metrics.

> **Important:** These forecasts estimate catalog addition patterns based on historical data. They do not directly predict audience demand, viewership, or revenue.

---

## 💡 Task 06: Netflix Content Success Analytics

**Objective:** Explore whether the available dataset could support a machine learning system for identifying successful Netflix titles.

### What I investigated

I examined the available features, including:

* Content type
* Title and director
* Country
* Date added
* Release year
* Maturity rating
* Duration
* Listed In

Although these features provide useful information about Netflix's content catalog, the dataset does not contain direct performance indicators such as total hours watched, viewership, revenue, or audience engagement.

### Why I could not complete reliable success prediction

Without an actual success metric, I could not establish a reliable target variable for training and evaluating a supervised model that predicts real content success.

For example, a title's genre, release year, or duration alone does not establish whether it was successful. Creating success labels from arbitrary assumptions could produce misleading results.

### What additional data would help?

A more meaningful success prediction system could be developed using historical performance data, such as:

* Total hours watched
* Number of viewers
* Revenue generated
* Audience engagement
* Popularity metrics
* User ratings and reviews

With suitable historical data and a clearly defined success criterion, it would be possible to investigate whether a machine learning model could predict future content performance.

### Outcome

I documented the dataset's limitations rather than claiming to have built a reliable success prediction model without supporting evidence.

This investigation helped me understand an important principle in machine learning: **the quality and relevance of the data determine which problems a model can meaningfully solve.**

---

# 🛠️ Technologies & Tools

The projects involved the following technologies and machine learning concepts:

| Category                | Technologies / Techniques                                       |
| ----------------------- | --------------------------------------------------------------- |
| Programming Language    | Python                                                          |
| Data Manipulation       | Pandas, NumPy                                                   |
| Data Visualization      | Matplotlib, Seaborn                                             |
| Machine Learning        | Scikit-learn                                                    |
| Gradient Boosting       | XGBoost                                                         |
| Text Processing         | TF-IDF                                                          |
| Recommendation Systems  | Cosine Similarity                                               |
| Classification          | Logistic Regression, Decision Tree, Random Forest, XGBoost      |
| Unsupervised Learning   | K-Means Clustering                                              |
| Forecasting             | Lag Features, Random Forest Regression, Walk-Forward Validation |
| Evaluation              | Weighted F1-score, MAE, MSE, RMSE, R², Silhouette Score         |
| Development Environment | Jupyter Notebook / Python                                       |

*The technologies listed above represent the tools and techniques used across the projects; not every tool was necessarily used in every task.*

---

# 📚 Key Takeaways

Throughout this internship, I strengthened my practical understanding of the machine learning workflow.

* **Data preprocessing:** Preparing real-world datasets for analysis and modeling.
* **Feature engineering:** Transforming existing information into useful model inputs.
* **Recommendation systems:** Using textual features and similarity measures to suggest related content.
* **Supervised learning:** Training and evaluating classification models.
* **Unsupervised learning:** Discovering patterns and groups without predefined labels.
* **Forecasting:** Using historical observations to estimate future trends.
* **Model evaluation:** Comparing algorithms with appropriate metrics and validation strategies.
* **Critical thinking:** Recognizing when a dataset does not contain the information required to answer a business question reliably.

Most importantly, I learned that building a machine learning solution involves more than training a model. It requires understanding the problem, examining the available data, selecting an appropriate methodology, and evaluating whether the results genuinely support the intended objective.

---

# 📂 Repository Structure

The repository is organized by internship task to make the notebooks, implementation details, and results easier to explore.

```text
netflix-ml-internship/
│
├── Task-01-Recommendation-System/
│   ├── task-1.ipynb
│   └── Photos/
│
├── Task-02-Type-Classification/
│   ├── task-2.ipynb
│   └── Photos/
│
├── Task-03-Rating-Classification/
│   ├── task-3.ipynb
│   └── Photos/
│
├── Task-04-Content-Segmentation/
│   ├── task-4.ipynb
│   └── Photos/
│
├── Task-05-Trend-Forecasting/
│   ├── task-5.ipynb
│   └── Photos/
│
├── Task-06-Content-Success-Analytics/
│   └── task-6.ipynb
│
├── Data/
|   |__dataset.csv
|
|__ Instructions/
|   |__Machine Learning Task List.pdf
|
└── README.md
```

*This is a suggested structure. Adjust the filenames and folders to match your actual repository.*

---

# 👨‍💻 About This Project

This repository documents my practical learning journey through six machine learning internship tasks, five of which I completed.

My focus was not only on implementing algorithms but also on understanding their purpose, evaluating their outputs, and recognizing the limitations of the available data.

I hope these projects demonstrate my growing skills in Python, data analysis, machine learning, and problem-solving as I continue developing toward a career in Machine Learning Engineering.

**Thank you for visiting my repository!**

If you find these projects interesting, feel free to explore the notebooks and implementations.
