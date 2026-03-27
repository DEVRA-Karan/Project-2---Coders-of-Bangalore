# 📊 Coders of Bangalore – Instagram Data Analysis Project

## 🚀 Project Overview

This project is a **real-world data processing and analysis challenge** inspired by a fictional scenario where I was tasked with analyzing Instagram follower data of OpenAI within 24 hours.

The project focuses on:

* Handling raw, unstructured data
* Converting it into structured format
* Performing meaningful analysis

---

## 🧠 Problem Statement

Given raw Instagram follower data (in text format), the objective was to extract and answer:

* 📸 Who has the maximum number of posts?
* 👥 Who has the highest followers?
* 🔁 Who follows the most people?
* 🏷️ How many categories of accounts exist?

---

## 🛠️ Tech Stack

* **Python 🐍**
* **File Handling**
* **JSON Processing**
* **Basic Data Analysis**

---

## 📂 Project Workflow

### 1️⃣ Data Collection

Raw Instagram follower data was collected and stored in a `.txt` file.

---

### 2️⃣ Data Cleaning & Parsing

A custom Python function was built to:

* Extract username
* Convert posts, followers, and following into numbers
* Handle formats like:

  * `1.2K` → 1200
  * `3.4M` → 3400000

---

### 3️⃣ Data Structuring

* Parsed data stored into a list of dictionaries
* Exported into `data.json` for structured access

---

### 4️⃣ Data Analysis

Performed analysis to find:

✔️ User with maximum posts
✔️ User with maximum followers
✔️ User following the most accounts
✔️ Total number of account categories

---

## 📈 Key Features

* 🔄 Converts unstructured text → structured JSON
* 📊 Handles real-world messy data
* ⚡ Fast and efficient parsing logic
* 🧠 Demonstrates problem-solving approach

---

## 📁 Project Structure

```id="x9b3fa"
Coders-of-Bangalore/
│── finaldata.txt       # Raw Instagram data
│── data.json           # Processed structured data
│── analysis.ipynb      # Main notebook
│── README.md           # Documentation
```

---

## ▶️ How to Run

1. Clone the repository:

```id="o1f9c8"
git clone https://github.com/Karan081980/Project-2---Coders-of-Bangalore.git
```

2. Open the notebook:

```id="r4qz2m"
jupyter notebook
```

3. Run all cells to:

* Parse data
* Generate JSON
* Perform analysis

---

## 💡 Key Learnings

* Working with real-world messy data
* String parsing and data extraction
* Converting raw data into structured formats
* Performing basic data analysis using Python

---

## 🚀 Future Improvements

* Add data visualization (charts & graphs)
* Use Pandas for advanced analysis
* Automate Instagram data scraping
* Build a dashboard

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork and improve.

---

## 📬 Contact

GitHub: https://github.com/Karan081980

---

## ⭐ Support

If you like this project, give it a ⭐ and share it!
