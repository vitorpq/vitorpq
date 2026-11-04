# Business Knowledge & Versioning Platform

## Problem

Teams need a simple way to edit, search and maintain shared knowledge while avoiding accidental overwrites and preserving change history.

## Solution

I built a web application for governed Markdown knowledge management with a Python API and modern frontend.

## Architecture

```text
React frontend
   ↓
FastAPI
   ↓
Knowledge files + metadata
   ├── Version control
   ├── Change monitoring
   └── Concurrency protection
```

## Stack

- Python
- FastAPI
- SQLModel
- React
- Vite
- TypeScript
- GitPython
- Watchdog
- SQLite
- Docker
- Nginx Proxy Manager

## Engineering aspects

- automatic Git-based versioning;
- external file change monitoring;
- optimistic concurrency using ETags / hashes;
- separation of application data and knowledge files;
- containerized production deployment.

## Skills demonstrated

- internal tools;
- API design;
- concurrency control;
- filesystem synchronization;
- versioning automation;
- frontend/backend integration;
- VPS deployment.

## Confidentiality

This case describes only reusable engineering concepts. Private source code, data and deployment details remain private.
