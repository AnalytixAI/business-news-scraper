# 📊 Automated Business News Scraper using Python

This project is a lightweight and effective tool for **automated extraction of live business news headlines** from a public news website. It is designed to assist in **business research**, **market monitoring**, and **competitive intelligence** by compiling current headlines into a neatly formatted, clickable Word document.

---

## 💼 Use Case

- Business Intelligence and Market Research
- Secondary Research for Analysts and Consultants
- News Monitoring for Decision-Makers
- Automating Manual Data Collection Processes

---

## 🚀 Features

- Scrapes live business headlines from [Moneycontrol Business News](https://www.moneycontrol.com/news/business/)
- Extracts and formats each headline with a clickable hyperlink
- Saves results in a clean, professional `.docx` Word document
- Minimal dependencies, fast execution

---

## 🛠️ Tech Stack

| Technology     | Purpose                          |
|----------------|----------------------------------|
| Python         | Core Programming Language        |
| Requests       | Fetching webpage data            |
| BeautifulSoup  | Parsing HTML content             |
| python-docx    | Generating Word document output  |

---

## 📂 Output Example

1. Market opens flat amid global cues 
https://www.moneycontrol.com/news/business/...

2. Rupee gains 15 paise against USD 
https://www.moneycontrol.com/news/business/...

---

## ✅ How to Run

1. **Install dependencies** (first time only):
   ```bash
   pip install requests beautifulsoup4 python-docx

## Run
python scraper.py
