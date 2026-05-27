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
