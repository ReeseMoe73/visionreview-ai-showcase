# VisionReview AI — Public Showcase

## AI-Assisted Editorial Review and Client Handoff Workflow

VisionReview AI is a local beta full-stack application for AI-assisted video review, editorial decision-making, quality control, and client handoff package generation.

The project was built to explore how AI, computer vision, transcription, and human editorial review can work together to help creators, editors, and production teams move from raw footage to organized selects and client-ready deliverables.

---
## Demo Video

Watch the VisionReview AI local beta demo:

https://drive.google.com/file/d/1FSOujpqpnOwJ49ciRKDRFNj_mfgv3YgT/view?usp=sharing

This demo shows VisionReview AI as an AI-assisted editorial review and client handoff workflow.

The walkthrough includes:

- Video report review
- Segment-level analysis
- Review Mode
- Tags and notes
- Reel Builder
- Compare workflow
- Export Quality Control
- Client/project metadata
- Client review HTML
- Client package ZIP
- Send-ready handoff summary


## Product Positioning

```text
From raw footage to client-ready review packages.
```

VisionReview AI is not positioned as a simple viral clip generator. It is an AI-assisted review-to-handoff workflow system.

The app helps users:

- Analyze uploaded video
- Break footage into reviewable segments
- Score segment quality and highlight potential
- Review clips manually
- Add notes and editorial tags
- Build draft reel structures
- Run export quality control
- Generate client review HTML
- Generate client package ZIP files
- Save client/project metadata
- Copy send-ready handoff summaries

---

## Why This Project Matters

Many AI video tools focus on instantly generating clips.

VisionReview AI focuses on the professional workflow around video review:

```text
Analyze → Review → Tag → Organize → QC → Package → Handoff
```

This is designed for editors and production teams that need more than a quick clipping tool. The goal is to support better editorial decisions and cleaner client communication.

---

## Current Version

```text
Local Beta v1.1.2
```

This version includes:

- Database-backed client/project metadata
- Manual metadata save workflow
- Last saved timestamp
- Client review HTML export
- Client package ZIP export
- Review tags and notes
- Reel Builder workflow
- Export Quality Control
- Send-ready client handoff summary
- Layout polish and regression fixes

---

## Core Workflow

```text
Upload footage
↓
Generate report
↓
Review video segments
↓
Add status, notes, and tags
↓
Build reel candidates
↓
Run QC checks
↓
Enter client/project metadata
↓
Generate client review HTML
↓
Download client package ZIP
↓
Send or archive handoff package
```

---

## Feature Overview

### Video Analysis

VisionReview AI processes video into structured segments and extracts useful review information such as:

- Duration
- Segment timestamps
- Transcript excerpts
- Highlight scoring
- Visual quality indicators
- Speech scoring

### Review Workflow

Users can mark segments as:

- Favorite
- Keep
- Reject
- Unreviewed

Users can also add notes and tags to explain why a segment matters.

### Tagging System

Tags help turn raw segments into editorial building blocks.

Example tags include:

- Hook
- B-roll
- Interview
- Cutaway
- CTA
- Strong Speech
- Client Ready
- Needs Review

### Reel Builder

The Reel Builder helps organize selected clips into draft structures and review possible reel candidates.

### Export Quality Control

The QC workflow helps flag export readiness issues such as:

- Too few clips
- Runtime concerns
- Missing opening hook
- Missing ending / CTA
- Quality warnings

### Client Handoff

The Client tab allows users to prepare polished delivery context, including:

- Project name
- Client name
- Prepared by
- Delivery brand
- Review purpose
- Target review date
- Project notes

These details can be saved and included in client-facing deliverables.

---

## Client Deliverables

VisionReview AI can generate:

- Client review HTML
- Client review summary
- Selected clips CSV
- Quality check summary
- Client next steps
- Project metadata file
- Full structured report JSON
- ZIP handoff package

---

## Technology Stack

```text
Backend: FastAPI
Database: SQLite + SQLAlchemy
Frontend: React + Vite
Video processing: OpenCV
Transcription: Whisper
Media utilities: FFmpeg
```

---

## Development Status

```text
Status: Working local beta
Version: Local Beta v1.1.2
Repository type: Public showcase only
Private source code: Not included
```

This repository is intended as a portfolio and product showcase. It does not include private implementation files, source code, database files, uploaded videos, generated media, API keys, or credentials.

---

## Competitive Position

VisionReview AI is best understood as an:

```text
AI-assisted editorial review and client handoff workflow system
```

It is adjacent to AI clipping tools, but the stronger differentiation is review, organization, QC, and handoff.

The product is designed to support the human editor instead of replacing the editorial decision process.

---

## Suggested Demo Narrative

A strong demo should show:

1. Uploading or opening a video report
2. Reviewing segments
3. Applying review status and tags
4. Building a reel candidate
5. Running QC
6. Entering client metadata
7. Opening client review HTML
8. Downloading the client package ZIP
9. Copying the send-ready handoff message

---

## Note

This is a public showcase repository. The private development repository contains the implementation code and local development history.
