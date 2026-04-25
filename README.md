# LinkUp GitHub Pages Marketing Site

This is a static GitHub Pages marketing/listing site for the LinkUp app. It follows Google Play listing guidance without copying the Google Play Store UI.

## How to publish on GitHub Pages

1. Push this folder to your GitHub repository root (keep `index.html`, `style.css`, and `images/` together).
2. In GitHub, open **Settings > Pages**.
3. Under **Build and deployment**, set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main`
   - **Folder**: `/ (root)`
4. Save and wait for deployment to complete.

Your live URL format is:

`https://<your-github-username>.github.io/<repo-name>/`

## Local test steps

Run a local static server from this folder:

```bash
python3 -m http.server 8080
```

Then open:

`http://localhost:8080`

Quick checks:

- The page loads with styling (no plain HTML look).
- Logo and all four screenshot placeholders render.
- Header links jump to page sections and GitHub links open correctly.

## Screenshot replacement notes

Recommended screenshots:

- Login or sign up screen
- Main dashboard / meeting list
- Generated meeting brief screen
- Follow-up email or notes screen

Google Play recommends actual in-app screenshots, at least four screenshots for apps when possible, and 9:16 portrait screenshots at minimum 1080 x 1920 for recommendation eligibility.
