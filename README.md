# 📌 Project:- PageRank Web Crawler & Visualization

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

## 🔹 Screenshots
*Screenshots of terminal execution and graph visualization are included below:*

### 1. Python Data Crawl & Rank
<img width="835" height="691" alt="Screenshot 1" src="https://github.com/user-attachments/assets/e700baec-6fcf-4f65-8280-d88320d66d62" />

### 2. Python Data Visualization
<img width="1236" height="708" alt="Screenshot 2" src="https://github.com/user-attachments/assets/03929250-b3e0-4caa-ad97-f58edc501e2c" />

### 3. Daring Fireball Crawl
<img width="941" height="682" alt="Screenshot 3" src="https://github.com/user-attachments/assets/53c75884-4270-479e-8906-f826a0d152b2" />

### 4. Daring Fireball Visualization
<img width="1223" height="703" alt="Screenshot 4" src="https://github.com/user-attachments/assets/937aa78a-0480-4e97-989e-5577e37d368e" />

## 🔹 What I Learned
* How **web crawling** works in practice.
* How **PageRank** distributes importance across nodes.
* Handling real-world crawling issues (timeouts, blocked pages).
* Visualizing graph-based data effectively using **D3.js**.

## 🔹 Notes on Reproducibility
Some original training URLs are no longer consistently accessible. The included screenshots show successful executions and visualizations from my runs.
