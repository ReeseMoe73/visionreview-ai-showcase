# VisionReview AI — Portfolio Case Study Draft

## Project Title
VisionReview AI — AI-Assisted Video Review and Editorial Workflow

## One-Line Summary
VisionReview AI is a local full-stack application that helps analyze video footage, review segments, build reel drafts, run QC checks, and export editorial handoff packages.

## Problem
Video editors and content creators spend significant time manually reviewing footage, finding usable moments, organizing selects, writing notes, preparing client summaries, and exporting deliverables.

These steps are often spread across video editors, spreadsheets, documents, captions tools, and file folders.

## Solution
VisionReview AI brings these steps into one local workflow:

```text
Upload → Analyze → Review → Build Reel → QC → Export
```

The app combines AI-assisted analysis with human editorial control.

## My Role
I designed and built the local beta application, including:

- Backend API design
- Database workflow
- Video upload pipeline
- Segment analysis workflow
- Review system
- React UI
- Reel Builder workflow
- Export tools
- Local beta documentation
- Public showcase repository

## Tech Stack

Backend:

```text
FastAPI, SQLite, SQLAlchemy, OpenCV, FFmpeg, Whisper
```

Frontend:

```text
React, Vite, CSS, jsPDF
```

## Key Features

- MP4 upload
- Video metadata extraction
- Segment generation
- Thumbnail generation
- Transcript generation
- Highlight scoring
- Review decisions
- Notes and tags
- Review Mode
- Reel Builder
- Client review summaries
- QC and approval workflow
- Project Package ZIP export
- Dashboard search/filter/sort

## Product Thinking
The app is designed around a practical editorial workflow, not just a model output.

The user remains in control through:

- Favorite / Keep / Reject decisions
- Manual notes
- Tags
- Editable reel order
- QC approval
- Export choices

## Outcome
The current project reached:

```text
VisionReview AI Local Beta v1.0
```

A public showcase repository was created while keeping the full source code private for possible commercial development.

## Public Showcase

```text
https://github.com/ReeseMoe73/visionreview-ai-showcase
```

## Future Direction

Potential future directions include:

- Desktop packaging
- Cloud storage
- Client review portal
- SaaS deployment
- Authenticated workspaces
- Background video processing
- Export preset expansion
