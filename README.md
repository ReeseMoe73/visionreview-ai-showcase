# VisionReview AI — Public Showcase

## AI-Assisted Video Review and Editorial Workflow

VisionReview AI is an AI-assisted video review and editorial workflow system designed to help editors, creators, and production teams move from raw footage to reviewed selects, structured reel drafts, quality-control notes, and export-ready handoff packages.

This public repository is a **showcase version** of the project. The full working source code is kept private while the project is evaluated for commercial development.

## Project Summary

Video editors, content creators, and production teams often spend significant time scrubbing raw footage, finding usable moments, taking review notes, organizing selects, creating reel drafts, preparing client review summaries, and exporting handoff documents.

VisionReview AI explores how AI-assisted media analysis can support that workflow by combining video processing, transcription, highlight scoring, human review, reel planning, and export packaging into one local application.

## Core Workflow

```text
Upload → Analyze → Review → Build Reel → QC → Approve → Export
```

## Current Status

```text
Status: Local Beta v1.0
Full Source: Private
Public Repo Type: Showcase / Portfolio
```

## Technology Stack

Backend:
- FastAPI
- SQLite
- SQLAlchemy
- OpenCV
- FFmpeg
- Whisper transcription

Frontend:
- React
- Vite
- CSS
- jsPDF

## Feature Overview

VisionReview AI includes:
- MP4 upload
- Video analysis and segmentation
- Transcript generation
- Highlight scoring
- Human review decisions
- Notes and tags
- Review Mode
- Reel Builder
- Client Review View
- QC and approval workflow
- Project package export
- Recent Videos dashboard

## Reel Builder

The Reel Builder includes:

```text
Plan | Order | Presets | Client | Timeline | Copy | Handoff | Compare | QC
```

## Public Showcase Note

This repository does **not** include the full working backend or frontend source code.

The full implementation is kept private to protect:
- Product implementation
- Backend architecture
- UI workflow
- Highlight scoring logic
- Reel Builder workflow
- QC and approval logic
- Export pipeline
- Commercial roadmap

## Demo Video

```text
Coming soon
```

## Screenshots

Suggested screenshot folder:

```text
docs/screenshots/
```

Recommended screenshots:
- dashboard.png
- report-overview.png
- segment-review.png
- reel-builder-plan.png
- reel-builder-order.png
- reel-builder-presets.png
- client-review.png
- qc-approval.png
- project-package-export.png

## Architecture Overview

See:

```text
docs/architecture-overview.md
```

## Roadmap

Potential future directions include:
- Desktop app packaging
- Cloud storage
- Hosted database
- Authenticated user workspaces
- Background video processing
- Client review portal
- Export presets
- Billing and usage limits
- SaaS deployment

## Repository Notice

Copyright © 2026 M Henning. All rights reserved.

This repository is provided for portfolio and demonstration purposes only. No permission is granted to copy, modify, distribute, sublicense, or use this project commercially.

The full working source code is not included in this public showcase repository.
