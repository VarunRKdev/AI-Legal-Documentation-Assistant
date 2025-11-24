"""
# ⚖️ AI-Legal-Documentation-Assistant

A lightweight, console-based Python tool that helps match user-entered legal case details with relevant statutes using simple NLP techniques. Works fully offline, fast, and beginner-friendly.

## 🚀 Key Features

### 🔎 Law Type Filtering
Filter results by categories such as **Criminal**, **Civil**, or **Corporate** to get more accurate matches.

### 🧩 Semantic Matching
Uses `difflib.SequenceMatcher` to measure similarity between user text and statute descriptions.

### 🧠 Synonym Expansion
Automatically substitutes complex legal jargon with simpler synonyms.

### 🧹 Stop Word Removal
Removes common words like *is, the, and* from both input and statutes.

### 🌍 Jurisdictional Reference Links
Automatically generates Google Search links for matched laws.

### 📄 CSV Export
All match results are saved to **output.csv**.

## ⚙️ Requirements

### Prerequisites
- Python **3.x**

### Dependencies
- **pandas**

Install dependencies:

```bash
pip install pandas
pip install pandas
