# AI Resume Analyzer

An AI-powered Resume Analyzer built with n8n and Google Gemini.

## Features
- Resume Upload
- AI Resume Analysis
- ATS Score
- Resume Strength Score
- Detailed AI Report
- Google Sheets Integration
- PDF Report Generation (External API)

## Tech Stack
- n8n
- Google Gemini AI
- Google Sheets
- HTML/CSS
- JavaScript

## Workflow
1. Upload Resume
2. Extract PDF Text
3. AI Analysis
4. Generate ATS Score
5. Save Results to Google Sheets
6. Generate PDF Report

## Note
PDF generation depends on an external API service. If the API quota is exceeded, the workflow still generates ATS Score, Resume Score, and AI Report successfully.
