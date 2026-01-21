# 📌 Project: PageRank Web Crawler & Visualization

## 🔹 Overview
This project implements a simplified **PageRank algorithm** by crawling web pages, building a link graph, and visualizing the results using a force-directed layout.

This project is based on a **peer-graded assignment** from **“Capstone: Retrieving, Processing, and Visualizing Data with Python”** by **Dr. Charles Severance (Python for Everybody specialization)**.

## 🔹 What I Did
* **Crawled ~100 pages** from two different websites:
  * `python-data.dr-chuck.net` (Test Data)
  * `daringfireball.net` (Real World Data)
* **Stored link relationships** in an SQLite database.
* **Computed PageRank scores** iteratively until convergence.
* **Generated a force-directed network visualization** using D3.js.
* **Analyzed** how highly connected pages dominate link structure.

## 🔹 My Contributions / Customization
* Cleaned the project structure (removed unnecessary cache/backup files).
* Re-ran and verified the pipeline end-to-end.
* Organized outputs and screenshots clearly.
* Added documentation explaining the workflow and learnings.

## 🔹 Technologies Used
* **Python** (Logic & Crawling)
* **SQLite** (Data Storage)
* **BeautifulSoup** (HTML Parsing)
* **D3.js** (Visualization)
* **HTML / CSS** (Frontend)

## 🔹 Screenshots
*Screenshots of terminal execution and graph visualization are included below:*

### 1. Python Data Crawl & Rank


### 2. Python Data Visualization


### 3. Daring Fireball Crawl


### 4. Daring Fireball Visualization


## 🔹 What I Learned
* How **web crawling** works in practice.
* How **PageRank** distributes importance across nodes.
* Handling real-world crawling issues (timeouts, blocked pages).
* Visualizing graph-based data effectively using **D3.js**.

## 🔹 Notes on Reproducibility
Some original training URLs are no longer consistently accessible. The included screenshots show successful executions and visualizations from my runs.