# AI-Powered Business Brochure Generator

This project provides a **full business solution** to automatically generate professional brochures for companies.  
The system takes a company’s **name** and **website URL**, scrapes relevant information, and then leverages **Llama 3.2** to generate marketing content, making it useful for prospective clients, investors, and potential recruits.

---

## 🚀 Features
- Scrapes and parses company websites to extract text and links
- Identifies **relevant sections** (About, Services, Careers, etc.)
- Automatically assembles content into a **brochure-style output**
- Demonstrates **real-world business applications** of LLMs
- Modular design for customization in other industries

---

## 📂 Project Structure
- `brochure.ipynb` → Main Jupyter Notebook (end-to-end workflow)
- `business.jpg` → Example image used for demo
- `Website` class → Utility for web scraping and parsing
- LLM integration (Llama 3.2) for content generation

---

## 🛠️ Requirements
Make sure you have Python 3.9+ installed.  

Install dependencies:
```bash
pip install requests beautifulsoup4 ollama
