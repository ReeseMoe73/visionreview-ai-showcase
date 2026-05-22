# VisionReview AI — Optional Public Repo Cleanup Plan

## Purpose

This is an optional cleanup plan if you want the public showcase repo root to look less crowded.

The current public repo is acceptable, but moving support documents into `docs/` can make it feel more polished.

---

## Current Issue

The public repo root may contain many files like:

```text
VISIONREVIEW_DEMO_VIDEO_RECORDING_PLAN.md
VISIONREVIEW_DEMO_VIDEO_SHOT_LIST.md
VISIONREVIEW_LINKEDIN_POST_DRAFT.md
VISIONREVIEW_PORTFOLIO_CASE_STUDY_PAGE.md
VISIONREVIEW_PRODUCT_ROADMAP_COMMERCIALIZATION.md
```

This is not unsafe, but it can feel busy.

---

## Recommended Cleaner Structure

```text
visionreview-ai-showcase/
├── README.md
├── .gitignore
├── docs/
│   ├── architecture-overview.md
│   ├── product-walkthrough.md
│   ├── api-contract-summary.md
│   ├── roadmap.md
│   ├── screenshots/
│   ├── portfolio-case-study.md
│   ├── demo-video-recording-plan.md
│   ├── demo-video-shot-list.md
│   ├── voiceover-script.md
│   ├── linkedin-post-draft.md
│   ├── resume-project-section.md
│   ├── interview-pitch.md
│   ├── commercialization-roadmap.md
│   └── final-public-showcase-review-checklist.md
└── examples/
    └── sample-report-schema.json
```

---

## Suggested Move Commands

Run from:

```powershell
cd C:\Users\might\OneDrive\Desktop\visionreview-ai-showcase
```

Create folders:

```powershell
mkdir docs\portfolio
mkdir docs\demo
mkdir docs\career
mkdir docs\strategy
```

Move files:

```powershell
move VISIONREVIEW_PORTFOLIO_CASE_STUDY_PAGE.md docs\portfolio\portfolio-case-study.md
move VISIONREVIEW_PORTFOLIO_CASE_STUDY_PAGE.html docs\portfolio\portfolio-case-study.html
move VISIONREVIEW_DEMO_VIDEO_RECORDING_PLAN.md docs\demo\demo-video-recording-plan.md
move VISIONREVIEW_DEMO_VIDEO_SHOT_LIST.md docs\demo\demo-video-shot-list.md
move VISIONREVIEW_VOICEOVER_SCRIPT.md docs\demo\voiceover-script.md
move VISIONREVIEW_LINKEDIN_POST_DRAFT.md docs\career\linkedin-post-draft.md
move VISIONREVIEW_RESUME_PROJECT_SECTION.md docs\career\resume-project-section.md
move VISIONREVIEW_RESUME_BULLETS_BY_ROLE.md docs\career\resume-bullets-by-role.md
move VISIONREVIEW_INTERVIEW_PITCH.md docs\career\interview-pitch.md
move VISIONREVIEW_PRODUCT_ROADMAP_COMMERCIALIZATION.md docs\strategy\product-roadmap-commercialization.md
move VISIONREVIEW_COMMERCIALIZATION_DECISION_MATRIX.md docs\strategy\commercialization-decision-matrix.md
move VISIONREVIEW_FEATURE_ROADMAP.md docs\strategy\feature-roadmap.md
move VISIONREVIEW_FINAL_PUBLIC_SHOWCASE_REVIEW_CHECKLIST.md docs\final-public-showcase-review-checklist.md
```

---

## Commit Cleanup

After moving files:

```powershell
git add .
git commit -m "Organize public showcase documentation"
git push
```

---

## Important

If you move files, update README links if it references any of those moved documents.

Screenshots should remain at:

```text
docs/screenshots/
```

Examples should remain at:

```text
examples/
```

---

## Recommendation

This cleanup is optional.

If the current public repo looks acceptable and safe, you can leave it as-is.
