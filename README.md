# Project 02 – Artificial Intelligence (IA25_P02_G04)

## Group Members
- **Pedro Ribeiro** — 27960  
- **Ricardo Fernandes** — 27961  
- **Carolina Branco** — 27983  
- **João Barbosa** — 27964  
- **Diogo Abreu** — 27975  

---

## Project Overview
This project explores the application of **Artificial Intelligence (AI)** techniques on sports datasets, using **two separate datasets** for different machine learning tasks:

1. **Olympic Athletes Dataset (120 Years of Athlete History)**  
   - Used for **Automatic Classification**.  
   - The goal is to predict athlete outcomes (Medal: Gold, Silver, Bronze, or None) based on features such as Age, Height, Weight, Sport, Team, and Event.

2. **NFL Super Bowl Dataset (1967–2020)**  
   - Used for **Clustering** and **Association Rules** analysis.  
   - The goal is to discover patterns, group similar games, and identify frequent relationships between game attributes (e.g., teams, points, MVPs, locations).

This project combines **data exploration**, **feature engineering**, and **machine learning analysis** to provide actionable insights for sports analysts, commentators, and enthusiasts across both datasets.

---

## Repository
The full project repository is available at:

[https://github.com/diogooaabreu/IA25_P02_G4.git](https://github.com/diogooaabreu/IA25_P02_G4.git)

---

## Project Structure & Deliverables

### 1. Olympic Athletes Dataset Overview & EDA Notebook
- Provides an introduction to the Olympic Athletes dataset and its attributes.  
- Performs **exploratory data analysis (EDA)** including descriptive statistics, visualizations, and feature investigation.  

### 2. Superbowl Dataset Overview & EDA Notebook
- Provides an introduction to the dataset and its attributes.  
- Performs **exploratory data analysis (EDA)** including descriptive statistics, visualizations, and feature investigation.  

### 3. Notebook 1 – Automatic Classification
- Defines business goals and target variables.  
- Prepares the data with **cleaning, feature engineering, and encoding**.  
- Implements machine learning algorithms for classification

### 4. Notebook 2 – Clustering
- Prepares the superbowl dataset for unsupervised learning.  
- Applies clustering algorithms (e.g., **K-Means**) and analyzes the characteristics of each cluster.  
- Provides visualizations and interpretations of clusters to uncover patterns in the games.

### 5. Notebook 3 – Association Rules
- Prepares the superbowl dataset for frequent pattern mining.  
- Applies the **Apriori algorithm** to extract association rules between game features.  
- Interprets rules to reveal interesting relationships among teams, points, locations, and MVPs.

### 6. Additional Files
- **Superbowl Dataset:** `superbowl.csv`  
- **Olympic Athletes Dataset** `athlete_events.csv`
---

## How to Run the Project
To run the notebooks and reproduce the analysis, follow these steps:

1. **Clone the repository**  
   ```bash
   git clone https://github.com/diogooaabreu/IA25_P02_G4.git
   cd IA25_P02_G4
   ```
   
2. **Install required Python libraries**

   Make sure you have Python installed (preferably version 3.8+). Then install the required libraries using pip:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn mlxtend
   ```

3. **Download the datasets**

   Place the CSV files in the root folder of the project (same level as the notebooks). Use the links below to download them:

   - Olympic Athletes Dataset (`athlete_events.csv`)
   https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results

   - NFL Super Bowl Dataset (`superbowl.csv`)
   https://www.kaggle.com/datasets/maxhorowitz/nfl-super-bowl-history

4. **Open and run the notebooks**

   You can use VS Code or Jupyter Notebook to open the .ipynb files. Execute the cells in order to reproduce the analyses.

