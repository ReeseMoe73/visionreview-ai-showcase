# VisionReview AI — Architecture Overview

## System Overview

VisionReview AI is structured as a local full-stack application.

```text
User Browser
    ↓
React + Vite Frontend
    ↓
FastAPI REST API
    ↓
SQLite Database
    ↓
Video Processing Services
```

## Frontend Layer

The frontend handles:
- Upload workflow
- Dashboard
- Report display
- Video preview
- Segment browsing
- Human review controls
- Reel Builder UI
- QC and approval UI
- Export actions

## Backend Layer

The backend handles:
- Receiving video uploads
- Saving media files locally
- Extracting video metadata
- Segmenting footage
- Running analysis
- Managing review data
- Serving reports
- Exporting clips and reels
- Creating project packages

## Processing Pipeline

```text
Uploaded MP4
    ↓
Metadata extraction
    ↓
Segment generation
    ↓
Visual analysis
    ↓
Audio extraction
    ↓
Transcription
    ↓
Highlight scoring
    ↓
Structured report
```

## Local Beta Limitation

A public SaaS version would require authentication, cloud storage, a hosted database, background jobs, secure file access, monitoring, usage limits, and deployment infrastructure.
