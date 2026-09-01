# CS 180 Portfolio

Programming projects for UC Berkeley's CS 180: Introduction to Computer Vision and Computational Photography, Fall 2026.

## Structure

```text
.
├── css/styles.css   # Shared visual system
├── index.html       # Portfolio landing page
└── project0/        # Add each project as its own directory over time
```

Future project pages should live in `project0/` through `project4/` and `final/`, each with its own `index.html`. Use relative paths so the site works at `zszeto.github.io/cs180/`.

## Run locally

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Publish with GitHub Pages

In the repository's **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save. The published site will be available at <https://zszeto.github.io/cs180/>.
