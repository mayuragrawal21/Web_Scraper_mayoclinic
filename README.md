
# 🩺 Web Scraper for Mayo Clinic – Mental Health and Symptoms A–Z

This project is a dual-purpose **web scraping tool** designed to extract structured health information from [MayoClinic.org](https://www.mayoclinic.org). It includes scrapers for both **Mental Health Topics** and **Symptoms A–Z**, enabling data collection for research, educational, or knowledge-graph building purposes.

## 🔍 Project Purpose

- **Mental Health Scraper**: Gathers condition names, descriptions, and related treatments from the mental health section.
- **Symptoms A–Z Scraper**: Extracts symptoms and corresponding medical details alphabetically.

## 📂 Files Included

```
📦Web_Scraper_mayoclinic/
 ┣ 📜Mental_Health_Scraper_mayoclinic.ipynb   # Scrapes mental health info
 ┣ 📜Symptoms_A_Z.ipynb                       # Scrapes symptom data A to Z
 ┗ 📜README.md                                # Project details and usage
```

## 🛠 Technologies Used

- Python
- BeautifulSoup4
- Requests
- pandas
- Jupyter Notebook

## ▶️ How to Use

1. **Install dependencies**:
```bash
pip install requests beautifulsoup4 pandas
```

2. **Run in Jupyter Notebook**:
   - Open either `Mental_Health_Scraper_mayoclinic.ipynb` or `Symptoms_A_Z.ipynb`
   - Execute each cell step-by-step
   - Scraped data will be displayed in structured format (can be exported to CSV/JSON)

## 📌 Example Outputs

- **Mental Health Scraper**:  
  - Condition Name: Anxiety  
  - Description: A mental health disorder characterized by feelings of worry...  
  - Treatment: Therapy, medication, or both.

- **Symptoms A–Z Scraper**:  
  - Symptom: Headache  
  - Possible Causes: Migraine, sinus infection, dehydration, etc.

## ⚠️ Disclaimer

This scraper is for educational or non-commercial research purposes only. Respect the terms of service of [mayoclinic.org](https://www.mayoclinic.org/).

## 👤 Author

**Mayur Agrawal**  
🔗 [GitHub](https://github.com/mayuragrawal21) | [LinkedIn](https://www.linkedin.com/in/mayur-agrawal21/)  
📧 [agrawalmayur2001@gmail.com](mailto:agrawalmayur2001@gmail.com)

---

> 📘 Ideal for building structured health datasets, search tools, or knowledge graphs.
