# iFocusFlow Landing

A tiny, stylish static site for the iFocusFlow iOS app. Built with plain HTML/CSS/JS and ready for GitHub Pages + your custom domain `iFocusFlow.cc`.

## Quick start

1. **Create a new GitHub repo** (e.g., `ifocusflow-site`) and push these files.
2. In the repo, go to **Settings → Pages**:
   - Source: **Deploy from a branch**.
   - Branch: `main` → `/ (root)`.
3. Add a `CNAME` file (already included) with `iFocusFlow.cc`.
4. In your DNS, create a **CNAME** record for `www` → `<your-username>.github.io`. Then, in GitHub Pages, set the custom domain to `iFocusFlow.cc` and follow the exact DNS records GitHub provides (these change occasionally).
5. (Optional) Redirect the apex `iFocusFlow.cc` to `www.iFocusFlow.cc` using your DNS provider’s ALIAS/ANAME if supported (or follow GitHub’s given A/AAAA records).

> Tip: After DNS propagates, enforce HTTPS in Pages settings.

## Replace images / copy

- Replace `assets/img/hero-placeholder.svg` with real artwork (aim ~1600×900).
- Drop iPhone/iPad screenshots into the gallery grid or swap the SVG mocks.
- Update copy in `index.html` and the App Store link in the hero button.

## Contact form

The included form uses a `mailto:` action so it works without a backend. For a better UX, use a form service:
- Formspree, Basin, Tally, or Netlify Forms.
Change the `<form action="...">` endpoint and keep the inputs as-is.

## Local dev

Just open `index.html` in a browser. No build tools needed.

---

© 2025 iFocusFlow. All rights reserved.
