# SmartPitch Demo (Static)

This is a **static** (no backend) demo build of the SmartPitch GUI.

## How it works
- The UI is unchanged visually.
- A **DEMO / Simulation** layer intercepts `/api/*` calls and returns realistic mock data.
- Use the floating **DEMO** control dock (bottom-right) to switch scenarios.

## Free hosting (recommended)
### GitHub Pages (phone-friendly)
1. Create a new GitHub repository (e.g. `smartpitch-demo`)
2. Upload these files to the repo root:
   - `index.html`
   - `logoforhtml.svg`
3. GitHub repo → **Settings** → **Pages**
4. Source: `Deploy from a branch` → Branch: `main` → Folder: `/ (root)` → Save
5. Your demo URL appears on the Pages screen.

## Local test
Just open `index.html` in a browser.
