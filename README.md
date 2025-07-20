# AI Promotion Finder

An end-to-end machine learning project to automatically detect **promotional content** from popular e-commerce websites using homepage text. Built using Python, Selenium, TF-IDF, and Logistic Regression.

---

## Project Overview

This project scrapes short texts from websites like **Amazon**, **Ajio**, and **Nykaa**, then classifies them into:

- `Promotion`
- `Non-Promotion`
---

##  Tools & Technologies

- Python
- Selenium + ChromeDriver
- TF-IDF Vectorization
- Logistic Regression (sklearn)
- Pandas, NumPy, scikit-learn

---


##  Folder Structure
AI_Promotion_Finder/
├── AI_Promotion_Finder.ipynb ← all steps in one notebook
├── AI_Promotion_Finder_Report_Updated.docx
├── chromedriver.exe ← Selenium browser driver
├── models/
│ ├── promotion_classifier.pkl
│ └── tfidf_vectorizer.pkl
├── data/
│ ├── raw/
│ │ ├── amazon_raw.csv
│ │ ├── ajio_raw.csv
│ │ └── nykaa_raw.csv
│ ├── labeled/
│ │ ├── amazon_labeled.csv
│ │ ├── ajio_labeled.csv
│ │ └── nykaa_labeled.csv
│ └── predicted/
│ ├── amazon_predicted.csv
│ ├── ajio_predicted.csv
│ └── nykaa_predicted.csv


---


##  How to Run

1. Clone the repo
2. Install dependencies:  
   `pip install -r requirements.txt`
3. Download compatible `chromedriver.exe` and place it in the root folder
4. Run `AI_Promotion_Finder.ipynb` step-by-step

---





