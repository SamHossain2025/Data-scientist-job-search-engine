<p align="center">
  <img src="banner.png" alt="Project Banner" width="100%">
</p>

# 📦 AI-Powered Data Scientist Job Search Engine

Capstone Project for the Google x Kaggle 5-Day GenAI Intensive Course 2025

---

## 👥 Author

Sam Hossain

---

## 🎯 Overview

This project is an AI-powered job search engine designed to intelligently match data science job listings to a candidate profile using GenAI techniques. It was inspired by a personal challenge I faced while approaching graduation from my Master of Management Analytics program at Queen’s University.

---

## 🔗 Live Notebook

Check it out on Kaggle:
https://www.kaggle.com/code/hossainsam/data-scientist-job-search-engine

---

## 🧠 Key Features

✅ Scrapes real-time Data Scientist job listings from LinkedIn guest views
✅ Embeds job descriptions using Google Gemini (text-embedding-004)
✅ Stores and semantically matches listings with ChromaDB
✅ Generates concise, JSON-based match explanations using Gemini
✅ Prioritizes results by location and recency
✅ Outputs a professional dark-mode HTML dashboard with clickable job links

---

## 🧩 Technologies Used

- Google Gemini (Generative AI)
- ChromaDB (Vector Store)
- BeautifulSoup + Requests (Web Scraping)
- Pandas (Data processing)
- HTML export for dashboard display

---

## 🧪 GenAI Capabilities Demonstrated

- Prompt Engineering & Structured Output
- Embeddings & Semantic Search
- Reasoning and explanation generation (JSON mode)
- Production-minded MLOps workflow structure

---

## 📅 Course Learnings Mapped

| Day   | Learning                   | Application                          |
| ----- | -------------------------- | ------------------------------------ |
| Day 1 | Prompt Engineering         | Structured match reasoning           |
| Day 2 | Embeddings & Vector Stores | Matching profile ↔ job               |
| Day 3 | Agents & Modularity        | Pipeline structure                   |
| Day 4 | Domain-Specific LLMs       | Tailoring to data science job search |
| Day 5 | MLOps                      | System workflow, reusable outputs    |


---

<<<<<<< HEAD
=======
## 🖼️ Visual Snapshots:
Note: These slides are for visual summary only. Full details are in the PDF.

---

>>>>>>> origin/main
## 📈 Results

- Personalized recommendations for top 10 jobs
- Clickable links, posting dates, and match reasoning
- Built for high-frequency daily use
- Ready to scale with Gemini’s paid API












<p align="center">
  <img src="2 Assets/Banner.png" width="100%">
</p>

# 🔍 AI-Powered Data Scientist Job Search Engine

*Solving real-life job discovery with semantic search, intelligent matching, and GenAI reasoning—built from the ground up during the Google x Kaggle GenAI Capstone.*

* Dataset timing: **2024 April – 2024 May**
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
Capstone Project for Google x Kaggle 5-Day GenAI Intensive 2025

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

This project is built out of my real-life challenge—I'm graduating from the Queen's MMA program and actively searching for data science roles. With so many listings and few truly relevant ones, I created this engine to automatically surface the jobs that actually fit me.

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

<p align="center">
  <img src="2 Assets/Process1.png" width="80%">
  <img src="2 Assets/Process2.png" width="80%">
</p>

### 📊 Visualization & Output

* HTML table rendered using Pandas + CSS
* Color-coded, clickable job links
* Sorted by location and recency
* Dark themed and responsive
* Saved as external HTML for portfolio use

---

## 🌟 Key Findings

* Semantic embedding boosts matching relevance beyond just keyword search
* Structured GenAI output helps generate concise, contextual match reasoning
* Vector DB makes this pipeline scalable for frequent daily usage

<p align="center">
  <img src="2 Assets/Findings1.png" width="80%">
  <img src="2 Assets/Findings2.png" width="80%">
</p>

---

## 💡 Key Recommendations

* Extend the job parser to more job boards like Indeed, Workopolis, etc.
* Run the search pipeline daily via scheduled Lambda or Colab Cron
* Integrate apply buttons + email forwarding to automate applications

<p align="center">
  <img src="2 Assets/Recommendation1.png" width="80%">
  <img src="2 Assets/Recommendation2.png" width="80%">
</p>

---

## 📊 Output Dashboard

<p align="center">
  <img src="2 Assets/Dashboard1.png" width="80%">
  <img src="2 Assets/Dashboard2.png" width="80%">
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



