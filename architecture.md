## System Architecture
### Overview
The Intelligent Job Application Manager is an Agentic AI-powered full-stack application designed to optimize job application decisions using analytics and LLM-based reasoning.
### Components
- Frontend & Backend:
  - Generated using Lovable (AI full-stack builder)
  - Includes authentication, dashboard, APIs, and UI
- Database:
  - Relational schema
  - Tables:
    - Users
    - JobApplications
    - ResumeAnalysis
- API Layer:
  - RESTful APIs for job application CRUD operations
  - Secure user-specific access control
- AI & Agentic Layer:
  - Resume–Job Description semantic matching using LLMs
  - Job relevance scoring logic
  - Decision-making agents (Apply / Skip / Improve Resume)
### Execution Layer
Lovable acts as the execution layer that converts agent decisions into a real, deployed application with persistent storage and UI workflows.
