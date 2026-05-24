# AI-Powered ATS Resume Optimizer using n8n

An end-to-end AI-powered resume optimization workflow built using n8n, Groq LLM APIs, Docker, JavaScript, and LaTeX automation.

This project automatically extracts resume content from PDF files, tailors resumes according to job descriptions using AI, and generates ATS-friendly resume outputs through an automated workflow pipeline.

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

# Architecture Workflow

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
