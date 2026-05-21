# VisionReview AI — API Contract Summary

This public document provides a high-level API summary only. The full backend implementation is private.

## Example API Areas

```text
Health check
Upload
Video listing
Video report
Thumbnail generation
Segment review
Segment tagging
Clip export
Reel export
Project package export
```

## Example Endpoints

```text
GET    /health
POST   /upload
GET    /videos
GET    /videos/{video_id}/report
GET    /videos/{video_id}/thumbnail
PUT    /segments/{segment_id}/review
PUT    /segments/{segment_id}/tags
POST   /videos/{video_id}/export-clip
POST   /videos/{video_id}/export-reel
GET    /videos/{video_id}/project-package
```
