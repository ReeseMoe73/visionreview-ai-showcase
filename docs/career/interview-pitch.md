# VisionReview AI — Interview Pitch

## 30-Second Version

VisionReview AI is a local full-stack AI/video workflow application I built to help move from raw footage to reviewed selects, reel drafts, QC notes, and export-ready handoff packages. The backend uses FastAPI, SQLite, SQLAlchemy, OpenCV, FFmpeg, and Whisper-based transcription workflows, while the frontend uses React and Vite. The project demonstrates applied AI, computer vision, media processing, API design, database-backed review workflows, and product-focused UI development.

---

## 60-Second Version

VisionReview AI is a Local Beta v1.0 application I built to combine AI-assisted video analysis with human editorial review. The app lets a user upload an MP4, generate segment-level reports, review clips, add notes and tags, build reel drafts, run QC checks, and export project handoff packages.

The backend is built with FastAPI, SQLite, SQLAlchemy, OpenCV, FFmpeg, and Whisper-based transcription workflows. The frontend is built with React and Vite and includes a dashboard, report page, Review Mode, Reel Builder, client review summaries, QC approval, and export tools.

The project is meaningful because it connects my AI/ML background with my film and video production background. It is more than a model demo; it is a practical workflow system with backend processing, frontend state management, database persistence, media export, and product-oriented UX.

---

## Technical Explanation

The upload pipeline receives an MP4 through FastAPI, stores it locally, extracts video metadata, creates fixed-length segments, generates analysis data, processes transcription, and returns a structured report. The React frontend displays the report with video playback, segment cards, timeline information, transcript excerpts, review decisions, tags, notes, and export actions.

A major design decision was keeping the human editor in control. AI-assisted scoring helps prioritize clips, but the user makes final decisions through Favorite, Keep, Reject, tags, notes, ordering, QC approval, and export choices.

---

## Why It Matters

VisionReview AI shows I can build applied AI systems that connect model-assisted analysis with real user workflows. It demonstrates backend engineering, frontend product design, database persistence, media processing, AI workflow design, and practical product thinking.
