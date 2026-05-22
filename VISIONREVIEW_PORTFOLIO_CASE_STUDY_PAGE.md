# VisionReview AI — Portfolio Case Study

## AI-Assisted Video Review and Editorial Workflow

VisionReview AI is a local AI-assisted video review and editorial workflow application designed to help editors, creators, and production teams move from raw footage to reviewed selects, structured reel drafts, QC notes, and export-ready handoff packages.

## Project Snapshot

| Category | Details |
|---|---|
| Project Type | Full-stack AI/video workflow application |
| Status | Local Beta v1.0 |
| Role | Full-stack developer, AI workflow designer, product builder |
| Backend | FastAPI, SQLite, SQLAlchemy, OpenCV, FFmpeg, Whisper |
| Frontend | React, Vite, CSS, jsPDF |
| Focus Area | Applied AI, video analysis, editorial workflow, media automation |
| Public Showcase | https://github.com/ReeseMoe73/visionreview-ai-showcase |
| Source Code | Private while commercial direction is evaluated |

## One-Line Summary

VisionReview AI helps transform uploaded footage into reviewed clips, reel drafts, client summaries, QC checks, and project handoff exports.

## The Problem

Video editors, creators, and production teams often spend significant time manually scrubbing footage, finding strong moments, organizing usable clips, writing review notes, tagging content types, preparing short-form reels, creating client review summaries, building editor handoff documents, and exporting deliverables.

These tasks are usually spread across multiple tools, such as video editors, spreadsheets, notes apps, caption tools, project folders, and messaging platforms.

## The Solution

VisionReview AI brings the editorial review process into one guided workflow:

```text
Upload → Analyze → Review → Build Reel → QC → Approve → Export
```

The app combines AI-assisted media analysis with human editorial control. The goal is not to replace the editor. The goal is to help the editor move faster from raw footage to usable selects and structured deliverables.

## Product Workflow

### 1. Upload

The user uploads an MP4 file into the local application.

### 2. Analyze

The app extracts metadata, creates segments, generates thumbnails, performs visual analysis, processes audio, generates transcripts, and calculates highlight scores.

### 3. Review

The user reviews each segment and marks it as Favorite, Keep, Reject, or Unreviewed. The user can also add review notes and tags.

### 4. Build Reel

The Reel Builder helps convert reviewed clips into structured draft options.

```text
Plan | Order | Presets | Client | Timeline | Copy | Handoff | Compare | QC
```

### 5. QC and Approval

The QC workflow checks readiness, review completeness, runtime, clip count, visual warnings, and export approval status.

### 6. Export

The app supports clip exports, reel exports, review CSV, summary TXT, JSON report, and full Project Package ZIP export.

## Key Features

### Dashboard

- Upload new footage
- Reopen recent reports
- Search projects
- Filter by review status
- Sort project list
- Delete local test projects
- Refresh-safe report loading

### Editorial Report

- Main video player
- Segment map
- Segment browser
- Transcript excerpts
- Highlight scores
- Quality labels
- Review decisions
- Notes and tags
- Export tools

### Review Mode

- Focused review workspace
- Sticky review action bar
- Quick decisions
- Quick tags
- Quick notes
- Review queue
- Completion panel

### Reel Builder

| Tab | Purpose |
|---|---|
| Plan | Recommended draft, structure, readiness, next steps |
| Order | Rearrange clips before export |
| Presets | Delivery guidance for social, client, or handoff use |
| Client | Client-facing review summary |
| Timeline | Editor-facing sequence notes |
| Copy | Caption and posting copy support |
| Handoff | Editor brief and delivery notes |
| Compare | Compare possible reel candidate pools |
| QC | Final readiness and approval workflow |

### Export System

Supported exports include single clip export, selected reel export, Favorite reel export, Keep reel export, ordered reel export, client draft export, review CSV, review summary TXT, JSON report, and Project Package ZIP.

The Project Package ZIP includes:

```text
manifest.json
report.json
review_segments.csv
project_summary.txt
transcript.txt
media_inventory.txt
```

## Technical Architecture

```text
React + Vite Frontend
        ↓
FastAPI Backend
        ↓
SQLite / SQLAlchemy
        ↓
OpenCV + FFmpeg + Whisper
        ↓
Reports, Review Data, Clips, Reels, Project Packages
```

## Applied AI and Media Processing

VisionReview AI demonstrates applied AI/media workflow design through video segmentation, computer vision analysis, speech transcription, highlight scoring, human-in-the-loop review, AI-assisted editorial prioritization, and structured export generation.

## Human-in-the-Loop Design

A major design goal was keeping the editor in control. AI-generated scoring helps prioritize footage, but the user decides what becomes usable through decisions, manual tags, review notes, clip ordering, client review selection, and QC approval.

## UI/UX Approach

The interface uses a dark cinematic editor-style layout to match the video production domain. UX improvements added during development include a guided workflow panel, compact Recommended Draft layout, dashboard search/filter/sort, clear Reel Builder tabs, error recovery, loading and empty states, and refresh-safe report loading.

## Challenges Solved

### Preventing undefined report loads

The app previously risked requesting `/videos/undefined/report`. This was resolved with safer report loading, localStorage handling, and back-to-upload recovery.

### Preserving review state

Review decisions, notes, and tags persist across refreshes and report sessions.

### Managing UI complexity

The app uses tabs, guided workflow cues, and compact cards to reduce visual overload.

### Export handoff design

The app evolved from basic report display into a workflow that supports structured exports and project package delivery.

## Outcome

VisionReview AI reached Local Beta v1.0 with a working private source repository, public showcase repository, README documentation, screenshot integration, demo video plan, and portfolio case study draft.

## What I Learned

This project strengthened practical skills in full-stack product development, FastAPI backend design, React state management, video processing workflows, database-backed review systems, media export workflows, applied AI product design, UX refinement for complex tools, Git/GitHub workflow, and public/private repository strategy.

## Future Roadmap

Possible future directions include desktop app packaging, cloud storage, hosted database, background processing, client review portal, authentication, multi-user project workspaces, SaaS deployment, billing and usage controls, and improved captioning/export presets.

## Commercial Note

The full working source code remains private while the project is evaluated for possible commercial development. The public GitHub repository is a showcase version containing documentation, screenshots, architecture overview, and sample schema only.

## Public Showcase

```text
https://github.com/ReeseMoe73/visionreview-ai-showcase
```
