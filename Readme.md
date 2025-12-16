# Naukri Data Scientist Job Scraper 🧑‍💻📊

This project scrapes **Data Scientist job listings from Naukri.com** using **Python & Selenium** and saves the collected data into an **Excel file** for analysis.

---

## 📌 Project Overview

The script automatically:

* Opens Naukri job listing pages
* Extracts job details such as:

  * Job Role
  * Company Name
  * Location
  * Experience Required
  * Salary
  * Skills
* Stores the scraped data into a structured **Excel (.xlsx) file**

This project is useful for **job market analysis**, **skill demand analysis**, and **data analytics practice**.

---

## 🛠️ Technologies Used

* Python 3
* Selenium
* WebDriver Manager
* Pandas
* Google Chrome

---

## 📂 Project Structure

```
📁 naukri-job-scraper
│
├── naukri_scraper.py        # Main scraping script
├── naukri_jobs.xlsx        # Output Excel file
├── README.md               # Project documentation
```

---

## ⚙️ Installation & Setup

1. **Clone the repository**

```bash
git clone https://github.com/your-username/naukri-job-scraper.git
cd naukri-job-scraper
```

2. **Install required libraries**

```bash
pip install selenium webdriver-manager pandas
```

3. **Make sure Google Chrome is installed** on your system.

---

## ▶️ How to Run the Script

```bash
python naukri_scraper.py
```

After execution:

* An Excel file `naukri_jobs.xlsx` will be created
* The file will contain all scraped job listings

---

## 📊 Output Fields

| Column Name | Description         |
| ----------- | ------------------- |
| job_no      | Serial number       |
| roles       | Job title           |
| companies   | Company name        |
| locations   | Job location        |
| experience  | Required experience |
| salaries    | Salary range        |
| skills      | Required skills     |

---

## ⚠️ Important Notes

* Scraping speed is controlled using `time.sleep()` to avoid blocking
* Website structure may change, which can affect scraping
* This project is for **educational purposes only**

---

## 🚀 Future Improvements

* Add Headless Chrome for faster scraping
* Add skill frequency analysis
* Create visual dashboards (WordCloud / Charts)
* Use official APIs if available

---

## 👤 Author

**Tamil mani Elangovan**
Aspiring Data Analyst | Python Enthusiast

---

## ⭐ Support

If you find this project useful, please ⭐ star the repository on GitHub!
