# NovaSphere Logistics Analysis & AI Assistant  
### 🏆 UConn Huskies – Iowa Graduate Business Analytics Case Competition 2025

This repository showcases our submission for the **2025 Iowa Graduate Business Analytics Case Competition**, where we analyzed data for **NovaSphere Logistics** and built an LLM-based AI assistant for insight generation and strategy planning.

---

## 📊 Project Overview

- Conducted in-depth demographic and dual-eligibility analysis across Iowa and South Dakota.
- Used ZIP-level data (income, poverty, age, education) to forecast Medicaid risk zones.
- Delivered actionable insights for underserved populations.
- Built a conversational **AI Data Analyst** assistant using OpenAI's API.

---

## 📁 Repository Structure

```
📂 IOWA_UconnHuskies--main/
├── 📄 IOWA Case Study Competition.pdf      → Original competition prompt
├── 📄 LICENSE                             → Open-source license
├── 📄 README.md                           → Project overview (this file)

📁 Analysis_Using _Python/
├── 📄 Case for NovaSphere Logistics.pdf   → Business case document
├── 📊 IOWA Competition.ipynb              → Main analysis notebook
├── 📊 NovaSphere_logistics_raw_data.csv   → Raw data
├── 📈 cleanFile.xlsx / cleanFileUpdated.xlsx → Cleaned datasets

📁 LLM_IMPLEMENTATION/
├── 🧠 ai_data_analyst.py                   → AI-powered assistant script
├── 📦 requirements.txt                     → Python dependencies
```

---

## 💻 Technologies Used

- **Python** – pandas, matplotlib, seaborn
- **Jupyter Notebook**
- **Excel** – data cleaning and preprocessing
- **OpenAI API** – LLM integration
- **LangChain** – AI response pipelines

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/UConn_NovaSphere_Logistics_Analysis.git
cd UConn_NovaSphere_Logistics_Analysis
```

### 2. Set Up the Environment
```bash
pip install -r LLM_IMPLEMENTATION/requirements.txt
```

### 3. Launch the Notebook
Open the notebook from `Analysis_Using _Python/IOWA Competition.ipynb` and run the cells.

### 4. Run the AI Assistant
```bash
python LLM_IMPLEMENTATION/ai_data_analyst.py
```

---

## 📈 Business Impact

- Identified counties with high Medicaid pressure
- Visualized post-COVID dual eligibility shifts
- Created executive-ready visual reports
- Built an AI interface for analyst-level queries

---

## 👨‍💼 Team Credits

Developed by the **UConn Huskies** – Master’s in Business Analytics students  
University of Connecticut, Spring 2025

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
