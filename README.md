<p align="center">
  <img src="2 Assets/Banner.png" width="100%">
</p>

# 🔍 Personalized Job Search Engine for 'Data Scientist' Roles

*Solving real-life job discovery with semantic search, intelligent matching, and GenAI reasoning—built from the ground up during the Google x Kaggle GenAI Capstone.*

* Dataset timing: **Real Time**
* Topics covered: **Job Scraping, Embedding & Matching, JSON Output, HTML Rendering**
* Models used: **Text Embedding + Gemini LLM Reasoning**
* Skills demonstrated:

  * **Google Gemini API (text-embedding-004, flash)**
  * **BeautifulSoup Scraping**
  * **ChromaDB Vector Search**
  * **Structured JSON Output + HTML Export**
* Expected outcome:

  * **Daily personalized job match using GenAI embeddings**
  * **Click-and-apply smart dashboard**

---

## 👥 Authors

**Sam Hossain**

---

## 🔗 Live Notebook

Check it out on Kaggle:
<p align="center">
  <img src="2 Assets/Company2.png" width="80%">
</p>

https://www.kaggle.com/code/hossainsam/data-scientist-job-search-engine

As part of <img src="2 Assets/Company3.png" width="80%"> </p>


---

## 🔍 Problem Statement

**Goal:**

Build a personalized job search engine that identifies the best Data Scientist opportunities based on a candidate profile.

**Challenges Addressed:**

* Scraping valid, rich job information from LinkedIn HTML endpoints
* Understanding match between user profile and job descriptions
* Ranking based on location & time priority heuristics
* Generating clean, explainable recommendations using Gemini LLM
* Exporting results as dynamic, reusable HTML output

---

## 🔧 Workflow

### ✅ Data Scraping & Collection

* 3-page job parsing from LinkedIn using requests + BeautifulSoup
* Key fields extracted: Title, Company, Location, Post Date, Salary, Link
* Priority tagging by location (North York → Toronto → Remote → Ontario → Canada)
* Timeliness tagging by post date (1 Day → 7 Days → Older)

### ⚛️ Embedding & Matching

* Use of Google Gemini API `text-embedding-004` for semantic matching
* Vector database (ChromaDB) to store and search job embeddings
* Profile-driven matching based on candidate embedding

### ✨ GenAI Reasoning

* Use Gemini Flash model to explain each match in one short sentence
* JSON schema enforced via response parsing
* Rank and return top 10 matches

**Model Verdict:**
Gemini performed fast, accurate, and extremely context-aware matching + reasoning

### 📊 Visualization & Output

* HTML table rendered using Pandas + CSS
* Color-coded, clickable job links
* Sorted by location and recency
* Dark themed and responsive
* Saved as external HTML for portfolio use

<p align="center">
  <img src="2 Assets/Process1.png" width="80%">
  <img src="2 Assets/Process2.png" width="80%">
  <img src="2 Assets/Process3.png" width="80%">
  <img src="2 Assets/Process4.png" width="80%">
  <img src="2 Assets/Process5.png" width="80%">
  <img src="2 Assets/Process6.png" width="80%">
</p>


---

## 🌟 Key Findings

* Semantic embedding boosts matching relevance beyond just keyword search
* Structured GenAI output helps generate concise, contextual match reasoning
* Vector DB makes this pipeline scalable for frequent daily usage

---

## 💡 Key Recommendations

* Extend the job parser to more job boards like Indeed, Workopolis, etc.
* Run the search pipeline daily via scheduled Lambda or Colab Cron
* Integrate apply buttons + email forwarding to automate applications


---

## 📊 Output Dashboard

<p align="center">
  <img src="2 Assets/Dashboard1.png" width="80%">
</p>

---

## 🚀 How to Run This Project

1. **Clone the repository**

   ```bash
   git clone https://github.com/SamHossain2025/Job-Search-Engine.git
   cd Job-Search-Engine
   ```

2. **Install dependencies**

   ```bash
   pip install -qU google-genai chromadb requests beautifulsoup4 pandas
   ```

3. **Run the notebook**

   * `2 Codes/Data Scientist Job Search Engine.ipynb`

4. **Set your Gemini API Key**

   Use environment variable or input box to securely provide your API key.

---

## 🧬 Data Sources

* 📌 [LinkedIn Job Listings (Scraped HTML Pages)](https://ca.linkedin.com/jobs)
* 🔹 Google Gemini API (Embedding + Flash models)
* 🔹 Real-world job search experience from author's profile

---

## 🔓 License

This project is licensed under the [MIT License](LICENSE)



