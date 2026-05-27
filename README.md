# AI Job Intelligence Platform

An AI-assisted backend engineering job discovery and application acceleration platform built using n8n automation workflows, Greenhouse APIs, Telegram alerts, and intelligent ranking systems.

## Problem

Finding relevant remote backend engineering jobs is noisy and time-consuming.

Traditional job boards:
- contain too many irrelevant listings
- notify slowly
- lack intelligent filtering
- do not prioritize backend/distributed systems roles well
- provide poor recruiter discovery workflows

This project aims to automate and improve the entire job discovery pipeline for software engineers.

---

## Features

### Multi-Source Job Aggregation
- Fetches jobs from Greenhouse job boards
- Targets engineering-focused product companies

### Intelligent Backend Job Filtering
Filters jobs using:
- Java
- Backend
- Distributed systems
- Platform engineering
- Remote-first signals

Rejects:
- marketing
- design
- sales
- HR
- non-engineering roles

### Job Ranking Engine
Ranks jobs based on:
- backend relevance
- Java ecosystem relevance
- remote friendliness
- seniority
- platform/distributed systems keywords

### Duplicate Prevention
Prevents repeated alerts for already-seen jobs.

### Telegram Job Alerts
Sends ranked engineering opportunities directly to Telegram.

### Recruiter Discovery Links
Generates recruiter and hiring-manager search links automatically.

---

## Architecture

```text
Schedule Trigger
        ↓
Greenhouse APIs
        ↓
Job Extraction + Scoring
        ↓
Duplicate Removal
        ↓
Top Job Ranking
        ↓
Telegram Alerts
```

## Tech Stack

- n8n
- JavaScript
- Greenhouse APIs
- Telegram Bot API
- Node.js
- Automation Workflows

---

## Example Alert

```text
🚀 High Match Backend Job

🏢 Company: Example Inc

💼 Role: Senior Backend Engineer

📍 Location: Remote

⭐ Score: 18

🔗 Apply:
https://example.com/job
```

---

## Current Improvements In Progress

- AI-powered resume tailoring
- recruiter outreach automation
- application tracking system
- AI-based semantic job ranking
- multi-source aggregation (Lever, Ashby)
- remote/APAC filtering improvements

---

## Key Learnings

- Retrieval quality matters more than AI ranking initially
- Good filtering dramatically reduces noise
- Engineering-focused sources outperform generic job boards
- Automation pipelines require strong deduplication logic

---

## Future Vision

Build a complete AI-assisted job acquisition platform:

- intelligent discovery
- resume optimization
- recruiter outreach
- automated application workflows
- interview tracking


---

## Screenshots

- Telegram alerts

<img width="513" height="510" alt="image" src="https://github.com/user-attachments/assets/4e30518e-d761-4cb6-921a-e6348eaa8388" />

- n8n workflows

<img width="1652" height="822" alt="image" src="https://github.com/user-attachments/assets/3ab26b18-f9aa-4640-93aa-a26e8385d5dd" />

- ranking system

<img width="553" height="718" alt="image" src="https://github.com/user-attachments/assets/3798cc04-6e3f-421d-a4bc-4e8934318b70" />

- recruiter discovery pipeline

<img width="666" height="287" alt="image" src="https://github.com/user-attachments/assets/f00ad9b9-1229-4366-8023-747d63548899" />


---

## Author

Backend Engineer focused on:

- Java
- distributed systems
- scalable backend architectures
- AI-assisted automation systems
