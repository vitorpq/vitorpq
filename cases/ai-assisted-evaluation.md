# AI-Assisted Evaluation Platform

## Problem

Manual review of handwritten assessments is time-consuming and difficult to scale while preserving consistency, traceability and the professor's final authority.

## Solution

I built a full-stack platform where educators upload handwritten PDF assessments and an approved answer reference. A multimodal AI model produces structured suggestions, while the professor can review and override individual decisions.

## Architecture

```text
Web frontend
   ↓
FastAPI
   ↓
Job queue
   ↓
PDF → images
   ↓
Multimodal LLM
   ↓
Structured evaluation
   ↓
Human review
   ↓
Database / reports
```

## Stack

- Python
- FastAPI
- Next.js
- TypeScript
- PostgreSQL
- SQLModel
- Redis
- Celery
- PyMuPDF
- OpenRouter / multimodal LLM
- Docker Compose
- pytest

## Engineering aspects

- authentication and role isolation;
- asynchronous processing;
- persistent relational data model;
- human-in-the-loop review;
- rate limiting;
- test coverage;
- CSV export;
- production-oriented containerization.

## Skills demonstrated

- applied AI product development;
- backend architecture;
- asynchronous workloads;
- relational modeling;
- AI + human review workflows;
- production deployment.

## Confidentiality

This public case describes the architecture at a high level. Private prompts, proprietary business logic and private source code are not included.
