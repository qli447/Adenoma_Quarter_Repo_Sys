# 🧾 Quarterly Adenoma Report Generator

## 📌 Description

A lightweight web-based tool to generate and download quarterly adenoma case reports as PowerPoint files by facility.

---

## 📌 Overview

This project provides a simple automated system for generating **quarterly adenoma reports**. Users can select a medical facility from a dropdown menu and instantly download a PowerPoint report that summarizes adenoma cases by physician and gender.

### Key Features
- 📊 Query quarterly case data from a MySQL database
- 📑 Populate a PowerPoint template with dynamic statistics
- 👩‍⚕️ Group data by attending physician and gender
- 🌐 Simple web interface (Streamlit or Flask)
- 📥 One-click download of formatted `.pptx` reports

---

## 🛠️ Tech Stack

- Python
- pandas, mysql-connector
- python-pptx
- Streamlit or Flask (web framework)
- MySQL (data source)

---

## 📂 Project Structure

├── app.py # Main app interface (Streamlit/Flask)
├── report_generator.py # Core logic for DB query & PPT creation
├── Gopath template.pptx # PowerPoint slide template
├── requirements.txt # Python dependencies
└── README.md # Project documentation



