# The Grief That Doesn't Look Like Grief
### An UnBroken Reflection Guide | Places to Thrive

---

## Overview

This is a single-file interactive HTML reflection guide, part of the UnBroken curriculum. It is deployed via Netlify directly from this GitHub repository.

**Live URL:** *(add your Netlify URL here once deployed)*

---

## Video Setup — Important

The module includes a video on Step 4 ("Name It"). The video file is **not** stored in this repository. You need to upload it manually.

### Steps to get the video working:

1. **Name your file exactly:** `name-it-video.mp4`
2. **Upload it to the root of this repository** — the same folder as `module-1b-grief-loss-is-real.html`
3. Once pushed to GitHub and deployed via Netlify, the video will load automatically

> **Note:** GitHub has a 100MB file size limit. If your video exceeds this, use [Git Large File Storage (LFS)](https://git-lfs.github.com/) or host the video externally (e.g. Vimeo, Cloudflare Stream) and update the `src` attribute in the HTML.

### If hosting externally:

Find this line in the HTML (around line 377):
```html
<source src="name-it-video.mp4" type="video/mp4">
```
Replace `name-it-video.mp4` with the direct URL to your hosted video file, e.g.:
```html
<source src="https://your-video-host.com/name-it-video.mp4" type="video/mp4">
```

---

## Files in This Repo

| File | Description |
|------|-------------|
| `module-1b-grief-loss-is-real.html` | The complete interactive reflection guide |
| `name-it-video.mp4` | Video for Step 4 — upload separately (see above) |
| `README.md` | This file |

---

## Deployment

This site deploys automatically via Netlify on every push to `main`.

- No build step required — it's a static HTML file
- Netlify publish directory: `/` (root)

---

## Part of the UnBroken Project

Created with care by Places to Thrive, Inc. © 2025
[unbrokenpathways.org](https://unbrokenpathways.org)
