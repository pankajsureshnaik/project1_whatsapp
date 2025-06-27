# WhatsApp Group-Based Breakdown Analysis for Beverage Lines

## 📌 Project Overview

This project aims to automate and simplify the collection and analysis of line breakdown issues in a beverage manufacturing setup. Instead of relying on manually filled log sheets or forms, we leverage messages shared in the factory’s WhatsApp group (without media files) to gather real-time data on machine issues and breakdowns. 

By using Excel for cleaning and transformation and Power BI for visualization, this approach saves time, reduces documentation overhead, and provides immediate insights to both maintenance teams and management.

## 🚀 Key Features

- ✅ **No Media Files**: Only message text is extracted from WhatsApp chat exports.
- ✅ **Excel-Based Transformation**: Clean, structure, and tokenize (tag) messages for issue classification.
- ✅ **Tokenization System**: Messages are categorized based on keywords (e.g., mechanical failure, sensor issues, electrical fault).
- ✅ **Maintenance Focused**: Eliminates the need for engineers to stop and fill forms during or after work.
- ✅ **Power BI Dashboard**: Visualizes breakdown trends, common issues, and frequency per machine or line.
- ✅ **Easy Update Process**: Just update the Excel file to refresh the entire dashboard.

## ⚙️ Tools Used

- **Microsoft Excel**: Data cleaning, transformation, and token mapping.
- **Power BI**: Data visualization and dashboard generation.
- **WhatsApp Chat Export**: Raw input data (text-only) from factory group.

## 🎯 Why This Project?

In real-world maintenance, engineers often have to juggle machine recovery with documentation. This project was born out of the need to:
- Make the reporting process easier.
- Use already available informal communication (WhatsApp) as structured data input.
- Empower teams with fast, actionable insights without adding extra workload.

## 📁 Folder Structure
📦 WhatsApp-Line-Breakdown-Tracker
├── 📄 ReadMe.md
├── 📊 BreakdownAnalysis.xlsx # Core Excel file with cleaned and tokenized data
├── 📈 PowerBIReport.pbix # Power BI dashboard linked to Excel
└── 📥 Sample_Chat.txt # Example WhatsApp exported chat (no media)

## 🛠️ How to Use

1. **Export** the WhatsApp chat from your factory group (no media).
2. **Paste** the messages into the Excel file in the provided input sheet.
3. The Excel file will **auto-clean and tokenize** the data.
4. **Open the Power BI report** (.pbix), refresh the data source to load the latest breakdown messages.
5. Analyze and share with your team!

## 📌 Benefits

- Reduces manual reporting burden on maintenance staff.
- Identifies recurring breakdown causes and patterns.
- Keeps management updated with live data insights.

## 📬 Contributions

If you’re using a similar method or want to improve token tagging or visual design, feel free to fork the repo or submit a pull request.

---

> 💡 *"Let the machines talk, while you fix them."*


