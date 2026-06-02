# AI-Fee-Reminder-Agent
Built an automated fee reminder agent using n8n workflow automation. Integrated Google Sheets and Gmail to fetch student records, track pending payments, and send scheduled reminder emails, streamlining fee collection and reducing administrative effort.
# AI Fee Reminder Agent

## 📌 Overview

AI Fee Reminder Agent is an automated workflow built using **n8n**, **Google Sheets**, and **Gmail** to streamline fee payment reminders. The system automatically retrieves student fee records, identifies pending payments, and sends personalized reminder emails without manual intervention.

## 🚀 Features

* Automated scheduled execution
* Google Sheets integration
* Pending fee detection
* Personalized email reminders
* Gmail automation
* Real-time workflow monitoring
* No-code workflow design using n8n

## 🛠️ Technologies Used

* n8n
* Google Sheets
* Gmail API
* OAuth Authentication

## 📊 Workflow Architecture

Schedule Trigger → Google Sheets → Filter Pending Fees → Generate Reminder → Gmail → Student

## ⚙️ How It Works

1. The workflow runs automatically at scheduled intervals.
2. Student fee records are fetched from Google Sheets.
3. Records with pending payments are identified.
4. Personalized reminder emails are generated.
5. Emails are sent automatically through Gmail.
6. The process repeats based on the configured schedule.

## 📂 Project Structure

```text
AI-Fee-Reminder-Agent/
│
├── workflow.json
├── README.md
├── screenshots/
│   ├── workflow.png
│   ├── google-sheet.png
│   └── email-output.png
```

## 🎯 Benefits

* Reduces manual follow-up efforts
* Improves communication efficiency
* Ensures timely fee reminders
* Scalable for multiple student records

## 📸 Screenshots

Add screenshots of:

* Complete n8n workflow
* Google Sheets dataset
* Email reminder output

## 👨‍💻 Author

Praveen Raj N

LinkedIn: https://www.linkedin.com/in/pravrj12
