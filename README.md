# Calls Metrics Automation

**Streamline daily call center reporting by converting Xencall/ReadyMode raw metrics into ready-to-upload report format in seconds.**

This simple yet powerful Jupyter-based automation processes the "Project Metric" CSV export from Xencall/ReadyMode, transforms the awkward time strings (e.g., "1 hour, 3 min., 21 s.") into standard HH:MM:SS format, and generates a clean output file ready for your company's "Metrics" report.

**Main benefit**: What used to take 1–2 hours of manual copy-paste and formatting now happens in just a few clicks — saving time every single day.

## ✨ Features

- Automatic time format conversion from verbose strings to standard `HH:MM:SS`
- Handles daily "Project Metric" CSV exports directly
- Produces consistently named output files: `Formatted Metrics - YYYY-MM-DD.csv`
- Clean, reproducible processing with Jupyter Notebooks
- Minimal setup — just Python + pandas

## 📊 Before vs After

| Task                        | Manual Process          | With This Automation    |
|-----------------------------|--------------------------|--------------------------|
| Time to prepare report      | 1–2 hours               | ~1–5 minutes            |
| Error-prone copy-pasting    | High                    | Eliminated              |
| Daily repetition            | Tedious & frustrating   | One-click execution     |
| Output consistency          | Varies                  | Always perfect          |

## 🛠️ Technologies Used

- **Language**: Python 3
- **Core library**: pandas (data manipulation & CSV handling)
- **Environment**: Jupyter Notebook
- **No external APIs** or complex dependencies

## 📁 Project Structure

Calls-Metrics/
├── Daily_metrics.ipynb       ← Main notebook for processing & formatting metrics
├── Project Metrics.csv       ← Example input file (Project Metric export)
├── Requirements              ← List of required packages (or use requirements.txt)
└── README.md


## 🚀 Quick Start / Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/Rich-AlFa/Calls-Metrics.git
   cd Calls-Metrics

2. **Install dependencies (if not already set up)**
   pip install pandas jupyter

3. **Prepare your data**
   Download the daily "Project Metric" report from Xencall/ReadyMode as CSV and save it into the same folder where the Jupyter notebook 'Daily_metrics.ipynb' is located.

4. **Run the notebook**
   -Open Daily_metrics.ipynb in Jupyter:Bashjupyter notebook
   -Execute all cells (or just run the processing section)
   -The script will generate Formatted Metrics - YYYY-MM-DD.csv in the same folder

## 📈 Business Value

This small automation tool frees up valuable time for call center / operations teams every working day. Multiply the saved hours across weeks and months.
