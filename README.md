# Automated Job Search & Cover Letter Generator

## Project Overview

An automation workflow built using n8n to collect Data Scientist job listings and generate personalised cover letters using AI.

## Technologies Used

* n8n
* SerpApi / Google Jobs
* Google Gemini API
* Google Sheets

## Workflow

1. Schedule Trigger starts the workflow.
2. Fetches job listings for the selected role and location.
3. Processes job listings individually.
4. Uses Gemini AI to generate cover letter content.
5. Stores job details and generated content in Google Sheets.

## Key Features

* Automated job search
* AI-assisted cover letter generation
* Job data organisation in Google Sheets
* Scheduled workflow execution

## Setup Instructions

1. Import the workflow JSON file into n8n.
2. Configure your own SerpApi, Gemini and Google Sheets credentials.
3. Set your preferred job role and location.
4. Activate the workflow and test the scheduled execution.

## Security

API keys and credentials should be stored securely in n8n Credentials and must not be committed to this repository.
