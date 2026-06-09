#  Netflix Movies in the 1990s: Exploratory Data Analysis

A data science project focused on performing Exploratory Data Analysis (EDA) on historical Netflix data. The goal is to uncover trends regarding movie runtimes and specific genre distributions throughout the 1990s decade.

---

## Project Objectives
1. **Filter and Clean:** Isolate movie entries specifically released between 1990 and 1999.
2. **Analyze Durations:** Visualize the distribution of 1990s movie runtimes to identify the most frequent (modal) duration.
3. **Targeted Counting:** Isolate and count the number of short action movies (under 90 minutes) released during this decade.

---

##  Tech Stack & Methods
* **Language:** Python
* **Libraries:** Pandas (Data manipulation), Matplotlib (Data visualization)
* **Techniques Used:** Multi-criteria boolean indexing, data visualization (histograms), row iteration with `.iterrows()`.

---

## Insights & Findings

### 1. Most Frequent Movie Duration
By analyzing the distribution peak in the movie runtime histogram, the most frequent movie duration during the 1990s was approximately **100 minutes**.

### 2. Short Action Movies Count
* **Criteria:** Genre set to "Action", release year between 1990–1999, and duration strictly less than 90 minutes.
* **Result:** Total count computed via row iteration loops (and verified using fast pandas vectorization methods). 
*( Note: Type your final printed number here!)*

---

##  Repository Structure
```text
├── netflix_data.csv       # The raw Netflix dataset
├── netflix_eda.ipynb      # Jupyter Notebook containing the analysis code
└── README.md              # Project documentation

