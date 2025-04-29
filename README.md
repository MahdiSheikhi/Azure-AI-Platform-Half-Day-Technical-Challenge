# Azure AI Platform Challenge: HR Survey Analytics

Welcome to the **Azure AI Half-Day Technical Challenge**. This challenge is designed to evaluate your practical skills with Azure OpenAI, Azure AI Language, and Azure Document Intelligence through the lens of HR analytics.

---

## 📘 Scenario
You are assisting an HR analytics team by automating the analysis of employee survey feedback using Azure AI services. You'll generate synthetic survey data, analyze it for sentiment and key insights, and use AI-powered document processing for semi-structured formats.

---

## ⏱ Duration
**Total Time:** 3–4 hours

---

## 🧩 Tasks Overview

### 🔹 Task 1: HR Survey Generation + Sentiment Analysis
- Use **Azure OpenAI** to generate up to 30 fictional HR survey responses with fields:
  - `EmployeeID`
  - `Department`
  - `Comment`
  - `SatisfactionRating` (1–5)
- Use **Azure AI Language (Text Analytics)** to analyze sentiment of each comment.
- Add columns `Sentiment` and `SentimentScore` to your final dataset.
- Output as CSV or JSON.

### 🔹 Task 2: Document Intelligence Extraction
- Convert 3–5 survey responses into PDFs or scanned form-like documents.
- Use **Azure Document Intelligence** to extract:
  - `EmployeeID`, `Department`, `Comment`, `SatisfactionRating`
- Output as structured JSON or table.

### 🔹 Task 3: Summarization with Azure OpenAI
- Use **Azure OpenAI** to summarize each `Comment` into 1–2 HR-friendly sentences.
- Add `CommentSummary` column to your dataset.

### 🔹 Bonus Task: Key Phrase Extraction (Optional)
- Use Azure AI Language to extract `KeyPhrases` from comments.
- Add results as a new column.

---

## ✅ Deliverables
- `generated_survey_data.csv` or `.json` with added sentiment and summaries
- `document_extraction_output.json` from Azure Document Intelligence
- `summary_script.py` or notebook showing summarization logic
- Code/scripts used for API calls and transformations
- A `README.md` explaining how to run your scripts and what each file does

---

## 🧪 Evaluation Criteria

| Category | Weight | Description |
|----------|--------|-------------|
| Prompt Engineering | 20% | Control and clarity of generated survey data |
| Sentiment Analysis | 20% | Accurate, structured sentiment extraction |
| Document Intelligence | 20% | Proper field extraction from forms or PDFs |
| Summarization | 20% | Clarity and usefulness of summaries |
| Code Quality | 15% | Readable, modular code with proper API usage |
| Documentation & Output | 5% | Clean output files and documentation |

---

## 📦 Suggested Repo Structure
```
azure-ai-hr-challenge/
├── data/
│   ├── generated_survey_data.csv
│   └── document_samples/
├── scripts/
│   ├── generate_surveys.py
│   ├── analyze_sentiment.py
│   ├── summarize_comments.py
│   └── extract_documents.py
├── outputs/
│   └── final_results.csv
├── README.md
└── requirements.txt
```

---

## 🔧 Tools & Services
- Azure OpenAI (GPT-4 or GPT-3.5)
- Azure AI Language (Text Analytics)
- Azure AI Document Intelligence
- Python SDKs or C# SDK or REST APIs

---

## 📌 Notes
- Keep prompts and sample outputs well-documented.
- You may mock data if needed, but document your approach.

---

Happy building! 🚀
