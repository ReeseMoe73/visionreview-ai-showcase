# VisionReview AI — Architecture Overview

## Purpose

This document gives a public-safe overview of VisionReview AI's architecture without exposing private implementation details.

---

## High-Level Architecture

```text
Frontend UI
   ↓
FastAPI Backend
   ↓
SQLite Database
   ↓
Video / Audio Processing Utilities
```

---

## Frontend

The frontend is built with React and Vite.

It provides screens and workflows for:

- Video report review
- Segment cards
- Review status updates
- Notes and tags
- Reel Builder
- Timeline/compare/QC views
- Client metadata
- Export/download actions

---

## Backend

The backend is built with FastAPI.

It provides routes for:

- Upload
- Report retrieval
- Segment review updates
- Thumbnail access
- Export package generation
- Client metadata persistence
- Client review HTML
- Client package ZIP

---

## Database

SQLite is used for local beta development.

Data includes:

- Video metadata
- Segment metadata
- Review status
- Review notes
- Review tags
- Client/project metadata

---

## Media Processing

The local beta uses media processing utilities for:

- Video metadata extraction
- Segment analysis
- Audio extraction
- Transcript generation
- Export packaging

---

## Client Handoff System

The client handoff system connects review decisions and metadata to deliverable files such as:

- HTML report
- Project details
- Review summary
- QC summary
- Next steps
- Structured JSON

---

## Local Beta Scope

VisionReview AI is currently a local beta application.

Not included in the public showcase:

- Private source code
- Local database
- Uploaded media
- Generated private packages
- API keys
- Credentials
