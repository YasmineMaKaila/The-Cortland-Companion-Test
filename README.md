# The Cortland Companion (mockup)

A clickable mockup of the Cortland Companion: role-based dashboards, the Daily Report, Down to the Details, onboarding checklists, My Goals, My Tool Box, and Our Culture.

Use **Preview as** in the top bar to switch between roles.

## What's in this folder

| Path | What it is |
|---|---|
| `index.html` | The whole Companion in one page |
| `assets/pdf/` | The PDFs the page opens: Down to the Details (`dtd-*`), onboarding guides (`onb-*`), and other guides (`gd-*`) |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Put it on GitHub Pages

1. Create a new repository on GitHub and upload everything in this folder (keep the `assets` folder as is).
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then **Save**.
4. After a minute or two, GitHub shows the link to the site at the top of the Pages settings.

## Before you share

- A site on GitHub Pages can be seen by anyone who has the link, and a public repository shows the files to anyone. This mockup includes internal Cortland guides and sample community data, so check with IT about where it should live. A private repository in Cortland's GitHub organization, or SharePoint, may be the better home.
- Numbers, names in brackets, and schedules are sample data.
- Progress and checkmarks are kept only while the page is open.

## Run it on your computer

Open `index.html` in a browser. PDFs open best when the folder is served, for example with `python3 -m http.server` from inside the folder, then visit `http://localhost:8000`.
