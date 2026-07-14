# Git Repo Link
https://github.com/Aditya-Ujjwal/Customer_Feeback_Analysis.git

# Customer Feedback Analysis and Automated Response

## Imarticus Data Science Internship Assessment
**Python Foundations & Generative AI**

---

## Project Overview

This project automates the process of identifying critical customer feedback and generating personalized response emails using Generative AI. It demonstrates how Python, Pandas, rule-based text analysis, and Google Gemini API can be combined to improve customer support workflows.

Instead of manually reviewing thousands of customer reviews, the system automatically filters negative reviews, identifies the most common customer complaints, and generates empathetic response emails for the most urgent cases.

---

## Problem Statement

A retail company receives thousands of customer reviews every week. The support team currently spends significant time manually reading negative reviews and drafting apology emails.

The objective is to:
- Clean customer review data
- Identify critical reviews (1–2 stars)
- Extract common complaint keywords
- Generate personalized apology emails using Google Gemini AI

---

## Dataset

**Amazon Product Reviews Dataset**

| Column | Description |
|---------|-------------|
| `overall` | Customer Rating (1–5 Stars) |
| `reviewText` | Customer Review |
| `summary` | Review Title |

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Google Gemini API
- Collections (`Counter`)
- Jupyter Notebook

---

## Project Workflow

1. Load the dataset using Pandas.
2. Clean and preprocess customer reviews.
3. Filter critical reviews (ratings ≤ 2).
4. Extract common complaint keywords.
5. Visualize insights.
6. Generate AI-powered apology emails using Google Gemini.
7. Export processed outputs.

---

## Project Structure

```text
Customer-Feedback-Analysis/
│
├── customer_feedback_analysis.ipynb
├── reviews.csv
├── requirements.txt
├── README.md
├── .env
├── critical_reviews.csv
├── top_keywords.csv
└── generated_emails.txt
```

---

## Installation

```bash
git clone <your-repository-link>

cd Customer-Feedback-Analysis

pip install -r requirements.txt
```

---

## Google Gemini API Setup

Create a `.env` file:

```text
GOOGLE_API_KEY=YOUR_API_KEY
```

Get your API key from:
https://aistudio.google.com/app/apikey

---

## Running the Project

```bash
jupyter notebook
```

Run every notebook cell from top to bottom.

---

## Outputs

- `critical_reviews.csv`
- `top_keywords.csv`
- `generated_emails.txt`

---

## Future Improvements

- Sentiment Analysis
- Complaint Categorization
- Streamlit Web App
- Customer Support Dashboard
- Email Automation

---

## Author

**Aditya Ujjwal**

Aspiring Data Analyst | Data Science Enthusiast

---

## License

Created for educational purposes as part of the **Imarticus Data Science Internship Assessment**.
