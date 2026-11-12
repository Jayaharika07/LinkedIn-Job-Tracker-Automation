# LinkedIn Job Tracker Automation

## Project Overview

LinkedIn Job Tracker is an AI-powered job tracking automation built using n8n, Google Gemini, RSS feeds, and Google Sheets.

It automatically collects job postings, uses AI to extract technical skills and generate personalized cover letters, and stores the structured information in Google Sheets.

## Problem Statement

Manually searching for job opportunities and maintaining job records can be time-consuming. This project automates job collection and organization to reduce manual effort.

## Technologies Used

- n8n
- Google Gemini
- RSS Feed
- LangChain Basic LLM Chain (n8n node)
- Structured Output Parser
- Google Sheets

## Workflow Explanation

1. **Schedule Trigger:** Starts the workflow at the scheduled time.
2. **RSS Feed:** Fetches job postings.
3. **Basic LLM Chain:** Processes job information using AI.
4. **Google Gemini:** Extracts technical skills and generates personalized cover letters.
5. **Structured Output Parser:** Organizes the generated information into a structured format.
6. **Google Sheets:** Appends or updates job records in the spreadsheet.

## Key Features

- Automated job posting collection.
- AI-powered technical skill extraction.
- Personalized cover letter generation.
- Structured job information.
- Automated Google Sheets updates.
- Scheduled workflow execution.

## Project Structure

```text
LinkedIn-Job-Tracker-Automation/
├── workflow/
│   └── job_tracker.json
├── screenshots/
│   ├── workflow.png
│   └── google_sheets_output.png
├── README.md
└── .gitignore
```

## How to Use

1. Import the workflow JSON file into n8n.
2. Configure your RSS feed URL.
3. Connect your own Google Gemini credentials.
4. Connect your Google Sheets account.
5. Select your spreadsheet and worksheet.
6. Configure the schedule trigger.
7. Execute the workflow and check the Google Sheets output.

## Screenshots

### n8n Workflow
![Workflow](screenshots/workflow.png)

### Google Sheets Output
![Google Sheets Output](screenshots/google_sheets_output.png)