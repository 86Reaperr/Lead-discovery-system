# Lead Discovery & Qualification System

An AI-powered B2B Lead Discovery & Qualification System that automates the discovery, validation, and classification of companies using web scraping, rule-based filtering, and Large Language Models (LLMs).

## Overview

This project collects company information from Clutch.co, extracts business details, and identifies technology-focused companies. It applies ICP-based qualification rules and uses Anthropic Claude to verify and classify each company, producing structured outputs for further analysis.

## Features

- Automated company data collection from Clutch.co
- Company profile extraction using Playwright and BeautifulSoup
- AI-assisted lead qualification using Anthropic Claude
- ICP rule-based company classification
- Technology keyword analysis
- Structured CSV and JSON export
- Progress tracking with interactive widgets

## Workflow

1. Scrape company information from Clutch.co.
2. Extract company descriptions, services, and website details.
3. Apply ICOP qualification rules.
4. Verify and classify companies using Claude AI.
5. Export qualified leads in CSV/JSON format.

## Technologies Used

- Python
- Playwright
- BeautifulSoup (bs4)
- Pandas
- Anthropic Claude API
- Google Cloud Secret Manager
- asyncio
- ipywidgets
- tqdm

## Project Structure

```
Lead-discovery-system/
│
├── LEAD_DISCOVERY_AND_QUALIFICATION_SYSTEM.ipynb
└── README.md
```

## Output

The system generates structured lead data containing:

- Company Name
- Website
- Company Description
- Services
- Technology Classification
- Qualification Status
- AI Verification Result

## Author

**Pranav Sharma**
