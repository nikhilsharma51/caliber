# Resume ↔ JD Matcher

An AI-powered resume and job description matching system that analyzes how well a resume aligns with a job description, identifies skill gaps, simulates ATS compatibility, and suggests targeted resume improvements.

## Features

- **Resume Parsing:** Extracts structured information from uploaded resumes.
- **JD Analysis:** Identifies required skills, experience, and keywords from job descriptions.
- **Semantic Matching:** Measures alignment between resume content and job requirements.
- **ATS Simulation:** Evaluates resume formatting and keyword compatibility.
- **Gap Analysis:** Identifies missing skills and highlights strengths.
- **Resume Rewriting:** Suggests optimized resume bullets tailored to specific roles.
- **Job Search Intelligence:** Tracks application scores and recurring skill gaps.

## Tech Stack

| Layer               | Technology                        |
| ------------------- | --------------------------------- |
| Frontend            | Next.js, TypeScript, Tailwind CSS |
| Backend             | FastAPI, Python                   |
| Agent Orchestration | LangGraph                         |
| Database            | PostgreSQL, Supabase, pgvector    |
| LLM                 | GPT-4o-mini                       |
| Embeddings          | text-embedding-3-small            |
| Charts              | Recharts                          |

## Project Structure

```text
resume-jd-matcher/
├── frontend/       # Next.js application
├── backend/        # FastAPI application
├── docs/           # Project documentation
└── README.md
```

## Getting Started

### Frontend

```bash
cd frontend
pnpm install
pnpm dev
```

Frontend runs at `http://localhost:3000`.

### Backend

```bash
cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload
```

Backend runs at `http://localhost:8000`.

## Development Roadmap

- [ ] Project architecture and initial setup
- [ ] Phase 1: Core resume analysis pipeline
- [ ] Phase 2: Resume rewriting and optimization
- [ ] Phase 3: Application tracking dashboard
- [ ] Phase 4: Job search intelligence and skill-gap analytics

## Vision

Build more than a resume scoring tool — create a persistent job-search intelligence system that learns from every application and helps users understand which skills and improvements can increase their chances of landing interviews.
