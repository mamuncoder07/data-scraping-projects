# 🏢 AmbitionBox Companies Dataset (Web Scraping Project)

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge\&logo=python)
![Web Scraping](https://img.shields.io/badge/Web-Scraping-BeautifulSoup-green?style=for-the-badge)
![Dataset](https://img.shields.io/badge/Dataset-CSV-orange?style=for-the-badge)
![Data Science](https://img.shields.io/badge/Data-Analysis-purple?style=for-the-badge)

🚀 This project demonstrates **web scraping using Python** to collect company data from **AmbitionBox** and convert it into a structured dataset.

The scraped data is stored in a **CSV file** that can be used for **Data Analysis, Machine Learning projects, and research**.

---

# 📊 Dataset Overview

The dataset contains information about companies listed on AmbitionBox.

Each row represents a **company with ratings, reviews, and location information**.

---

# 📂 Dataset File

```
ambitionbox_companies_dataset.csv
```

---

# 🧾 Dataset Columns

| Column            | Description                        |
| ----------------- | ---------------------------------- |
| name              | Company name                       |
| rating            | Company rating                     |
| reviews           | Total number of reviews            |
| type_and_location | Company industry type and location |

---

# 📊 Example Dataset

| name      | rating | reviews | type_and_location                    |
| --------- | ------ | ------- | ------------------------------------ |
| TCS       | 3.3    | 1.1L    | IT Services & Consulting | Bengaluru |
| Accenture | 3.7    | 72.1k   | IT Services & Consulting | Bengaluru |

---

# 🛠 Technologies Used

* 🐍 Python
* 🌐 Requests
* 🍲 BeautifulSoup
* 📊 Pandas

---

# ⚙ How the Scraper Works

1️⃣ Send request to AmbitionBox website
2️⃣ Parse HTML using **BeautifulSoup**
3️⃣ Extract company information
4️⃣ Store data in **Pandas DataFrame**
5️⃣ Export dataset as **CSV file**

---

# 🚀 How to Run

### 1️⃣ Install required libraries

```bash
pip install requests beautifulsoup4 pandas
```

### 2️⃣ Run the scraping script

```bash
python scraper.py
```

### 3️⃣ Dataset will be generated

```
ambitionbox_companies_dataset.csv
```

---

# 📈 Possible Use Cases

✔ Company rating analysis
✔ Job market research
✔ Data visualization projects
✔ Machine learning experiments
✔ Web scraping practice

---

# ⚠ Disclaimer

This project is created **for educational purposes only**.
Please respect the **website's terms of service** when collecting data.

---

# ⭐ Support

If you found this project useful, consider giving it a **⭐ star** on GitHub!

---

💡 Built for learning **Web Scraping, Data Science, and Python automation**.

