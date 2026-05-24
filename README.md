# AI-Powered ATS Resume Optimizer using n8n

An end-to-end AI-powered resume optimization workflow built using n8n, Groq LLM APIs, Docker, JavaScript, and LaTeX automation.

This project automatically extracts resume content from PDF files, tailors resumes according to job descriptions using AI, and generates ATS-friendly resume outputs through an automated workflow pipeline.

---

# Table of Contents

- Project Overview
- Workflow Architecture
- Features
- Tech Stack
- Folder Structure
- Installation & Setup
- Running the Workflow
- Example Workflow Execution
- AI Workflow Logic
- Challenges Faced
- Future Improvements
- Learning Outcomes
- Screenshots
- Author
- License

---

# Project Overview

The goal of this project is to automate the process of resume customization for different job applications.

The workflow:
1. Accepts a resume PDF and job description
2. Extracts resume text from PDF
3. Uses AI to tailor the resume
4. Generates ATS-friendly structured content
5. Converts the generated content into LaTeX format
6. Produces a professional resume output automatically

This project demonstrates:
- AI workflow automation
- LLM integration
- PDF processing
- Structured JSON handling
- Resume optimization
- API integration
- Workflow orchestration using n8n

---

# Workflow Architecture

## Current Workflow Pipeline

```text
On Form Submission
        ↓
Extract Resume from PDF
        ↓
Count Original Pages
        ↓
AI Resume Generator
        ↓
LaTeX Resume Converter
        ↓
JavaScript Processing
        ↓
HTTP Request (PDF Generation)
```

---

# Features

- AI-powered resume tailoring
- ATS-friendly resume optimization
- Resume PDF extraction
- Structured JSON generation
- Automated LaTeX resume formatting
- HTTP API integration
- Workflow automation using n8n
- Local Docker-based execution
- Groq LLM integration
- Conditional workflow logic
- Automated resume generation pipeline

---

# Tech Stack

## Workflow Automation
- n8n

## AI Models
- Groq API
- Llama 3.1 8B Instant

## Backend / Processing
- JavaScript
- JSON Processing

## Resume Processing
- PDF Extraction
- LaTeX Conversion

## Infrastructure
- Docker
- Docker Desktop

## APIs
- Groq API
- LaTeX Rendering API

---

# Folder Structure

```text
AI-Resume-Generator/
│
├── workflow/
│   └── resume-generator-workflow.json
│
├── screenshots/
│   ├── architecture.png
│   ├── workflow-execution.png
│   ├── resume-generator-node.png
│   └── generated-output.png
│
└── README.md
```

---

# Example Workflow Execution

## Step 1 — Resume Upload

User uploads:
- Resume PDF
- Job Description

---

## Step 2 — PDF Extraction

The workflow extracts:
- Skills
- Experience
- Projects
- Education
- Certifications

from the uploaded resume.

---

## Step 3 — AI Resume Tailoring

Anthropic LLM:
- analyzes the job description
- optimizes resume keywords
- rewrites bullet points
- improves ATS compatibility

---

## Step 4 — JSON Formatting

The tailored resume is converted into:
- structured JSON
- clean formatting
- reusable data structure

---

## Step 5 — LaTeX Conversion

Structured JSON is converted into:
- professional LaTeX resume template
- ATS-friendly formatting
- clean resume layout

---

## Step 6 — PDF Generation

The final resume PDF is generated automatically through HTTP API integration.

---

# AI Workflow Logic

## Resume Generator Node

Purpose:
- Tailor resume based on job description
- Optimize keywords
- Improve ATS compatibility

Input:
- Resume content
- Job description

Output:
- Tailored resume JSON

---

## LaTeX Converter Node

Purpose:
- Convert structured JSON into LaTeX format

Input:
- Tailored JSON resume

Output:
- ATS-friendly LaTeX resume

---

## HTTP Request Node

Purpose:
- Send LaTeX content to PDF rendering service

Input:
- LaTeX code

Output:
- Final generated PDF

---

# Challenges Faced

- Managing Groq free-tier token limitations
- Optimizing prompt sizes
- Handling large resume JSON payloads
- Maintaining structured JSON consistency
- Workflow execution optimization
- AI response formatting consistency
- Managing multiple AI node executions

---

# Future Improvements

- Multi-template resume support
- Real-time ATS score evaluation
- Resume keyword analytics
- Multi-model AI integration
- Cloud deployment support
- Public web application
- User authentication system
- Resume version history
- Multiple export formats
- LinkedIn profile integration

---

# Learning Outcomes

Through this project, I learned:

- Workflow automation using n8n
- AI model integration using APIs
- Prompt engineering
- JSON parsing and transformation
- Docker containerization
- LaTeX automation
- ATS optimization strategies
- End-to-end AI pipeline development
- API integration
- Workflow orchestration
- AI automation architecture

---

# Screenshots

## Workflow Architecture

Add:
```text
screenshots/architecture.png
```

---

## Workflow Execution

Add:
```text
screenshots/workflow-execution.png
```

---

## Generated Resume Output

Add:
```text
screenshots/generated-output.png
```

---

# Example Resume Use Cases

- Software Engineering roles
- Machine Learning Engineer roles
- Data Science positions
- Cloud Engineering roles
- AI Engineering positions
- ATS optimization for job applications

---

# Why This Project Matters

Modern job applications heavily depend on ATS (Applicant Tracking Systems).

This project helps automate:
- resume optimization
- keyword tailoring
- formatting consistency
- professional resume generation

using AI workflow automation.

---

# Author

## Raj Patel


# License

This project is created for:
- educational purposes
- portfolio demonstration
- learning AI workflow automation

---

# Acknowledgements

- n8n
- Groq API
- Docker
- Open-source AI community
- LaTeX ecosystem

---
