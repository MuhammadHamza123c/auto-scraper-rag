# 🕸️ auto-scraper-rag

**auto-scraper-rag** is an automated web scraping and retrieval-augmented generation (RAG) system.  
It scrapes websites, cleans the data into structured text, and stores it in a vector database for fast, intelligent querying.  
Built with **BeautifulSoup** and **LangChain**, it supports both sequential chains and RAG-based Q&A over scraped content.

---

## 🚀 Features
- 🌐 Automated web scraping with BeautifulSoup  
- 🧹 Cleans & structures text from raw HTML  
- 📦 Stores scraped text in a vector database  
- 🔍 Query pipelines with LangChain (sequential + RAG)  
- 🤖 Intelligent Q&A over website data  

---

## 📂 Repository Structure

├── .gitignore # Ignored files

├── rag_scrap.ipynb # RAG pipeline with LangChain

├── scrap.ipynb # Web scraping + preprocessing

├── requirements.txt # Project dependencies


---

## ⚙️ Installation
Clone the repo and install dependencies:
```bash
git clone https://github.com/MuhammadHamza123c/auto-scraper-rag.git
cd auto-scraper-rag
pip install -r requirements.txt
```

## **Usage**:
Run scraping

```
# Inside scrap.ipynb
# Provide a target URL to scrape & extract text
# Run it
```
Run RAG pipeline

```
# Inside rag_scrap.ipynb
# Load scraped data into vector DB and query with LangChain

```
## **License**

This project is licensed under the MIT License.
