# Milestone 80 — Public README Screenshot Integration

## Purpose

This milestone updates the public showcase README so screenshots display directly on the GitHub repository page.

---

## Files Included

```text
README.md
VISIONREVIEW_MILESTONE80_SUMMARY.md
```

---

## Where to place README.md

Replace the README in your public showcase repo:

```text
C:\Users\might\OneDrive\Desktop\visionreview-ai-showcase\README.md
```

---

## Required Screenshot Paths

The README expects screenshots at these paths:

```text
docs/screenshots/dashboard.png
docs/screenshots/report-overview.png
docs/screenshots/segment-review.png
docs/screenshots/review-mode.png
docs/screenshots/reel-builder-plan.png
docs/screenshots/reel-builder-order.png
docs/screenshots/reel-builder-presets.png
docs/screenshots/client-review.png
docs/screenshots/qc-approval.png
docs/screenshots/project-package-export.png
```

If a screenshot file is missing, GitHub will show a broken image icon. Either add the matching screenshot or remove that screenshot section from README.md.

---

## Git Commands

From the public showcase repo folder:

```powershell
cd C:\Users\might\OneDrive\Desktop\visionreview-ai-showcase
git add README.md docs/screenshots
git commit -m "Add screenshots to public showcase README"
git push
```

---

## Verification

Open:

```text
https://github.com/ReeseMoe73/visionreview-ai-showcase
```

Confirm:

- README loads correctly.
- Screenshots display.
- No broken image icons appear.
- No private source code appears.
- No private video footage, local file paths, email, token, or credentials are visible.
