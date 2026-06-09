#  Netflix Cinema in the 1990s: Comprehensive Exploratory Data Analysis

A deep-dive data science portfolio project exploring historical entertainment trends on Netflix, focusing specifically on the 1990s decade (1990–1999). This project scales past baseline statistics to map out the genre landscape, geographical production hubs, demographic targeting, and structural runtime shifts across a 10-year timeline.

---

##  Core Questions Answered

### **Section 1: Base Tasks**
1. **The Duration Peak:** What was the most frequent movie runtime in the 1990s? (Identified the approximate modal runtime).
2. **Niche Filtering:** How many Short Action Movies (< 90 mins) were released during this decade? (Calculated via conditional row iteration).

### **Section 2: Advanced Portfolio Expansions**
3. **Genre Dominance:** What were the Top 5 most prominent genres of the 1990s?
4. **Chronological Trends:** Did average movie runtimes lengthen or shorten year-over-year from 1990 to 1999?
5. **Content Split:** What percentage of total 90s entertainment content consisted of Movies versus episodic TV Shows?
6. **Global Output:** Which 5 countries produced the highest volume of cinema during this era?
7. **Genre vs. Runtime Spread:** Does a movie's genre heavily impact its structural duration? (Analyzed variance and outliers via boxplots).
8. **Target Audiences:** What was the dominant maturity rating profile (e.g., R, PG-13, TV-14) for 90s releases?
9. **Creative Leaders:** Which 5 directors were responsible for the highest output of 90s cinematic content?
10. **Runtime Outliers:** What were the top 5 absolute longest films produced during this decade?

---

## Environment & Technical Stack

* **Language:** Python
* **Environment:** Jupyter Notebook / DataCamp DataLab
* **Core Libraries:**
  * **Pandas:** Utilized for multi-criteria boolean indexing, string data cleansing (`.dropna()`), group aggregation (`.groupby()`), and index sorting.
  * **Matplotlib & Seaborn:** Used to design publication-ready data visualizations including histograms, trend lines, pie charts, horizontal/vertical bar plots, and boxplots.

---

##  Key Analytical Insights

* **The 100-Minute Benchmark:** Distribution analysis via histograms reveals a sharp peak right at **100 minutes**, proving a heavy industry preference for standard 1.5 to 2-hour theatrical windows.
* **Format Concentration:** The 1990s ecosystem on the platform is overwhelmingly dominated by **Feature Movies (over 85%)** compared to TV formats, capturing an era before high-budget streaming serialization took off.
* **Genre Patterns:** Boxplot spreads indicate that while Comedies maintain a tight, fast-paced runtime layout, Action and Drama films display much wider interquartile ranges and higher median durations.
* **Geographical Dominance:** The United States commands the largest production footprint of the decade, followed by strong international distribution pipelines out of India and the United Kingdom.

---

## Repository Structure

```text
├── netflix_data.csv       # Raw historical Netflix dataset
├── netflix_eda.ipynb      # Complete 10-question Jupyter Notebook
└── README.md              # Project documentation and insights
