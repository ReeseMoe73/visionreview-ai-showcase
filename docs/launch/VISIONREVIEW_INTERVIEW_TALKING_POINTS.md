# VisionReview AI — Interview Talking Points

## 30-Second Elevator Pitch

VisionReview AI is a local beta full-stack application I built to support AI-assisted video review and client handoff workflows. It analyzes uploaded video into segments, supports transcript and quality-based review, lets users mark clips as Favorite, Keep, or Reject, add notes and tags, build reel candidates, run export QC, and generate client-ready handoff packages.

## Technical Talking Points

- FastAPI backend with REST API endpoints
- SQLite/SQLAlchemy database models for videos, segments, review state, and client metadata
- React/Vite frontend with multi-section review workflow
- OpenCV video metadata extraction
- FFmpeg media handling
- Whisper transcription integration
- Human-in-the-loop review design
- Client-facing HTML and ZIP package generation

## Product Talking Points

- Focuses on review-to-handoff instead of just clip generation
- Supports editors, creators, and production teams
- Bridges AI/ML and real post-production workflow needs
- Helps communicate editorial decisions to clients
- Creates more professional handoff deliverables

## Why I Built It

Many AI video tools focus only on generating clips, but professional video work also needs review, selection, notes, tags, QC, and client communication. I wanted to build a tool that supports the full editorial handoff workflow while keeping the human editor in control.
