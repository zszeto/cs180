# CS 180 Portfolio

Programming projects for UC Berkeley's CS 180: Introduction to Computer Vision and Computational Photography, Fall 2026.

## Structure

```text
.
├── css/styles.css       # Landing-page styles
├── index.html           # Portfolio landing page
├── project0/
│   ├── images/          # Project 0 images and animation
│   ├── index.html       # Project 0 write-up
│   └── styles.css       # Project 0 styles
├── project1/
    ├── images/          # Project 1 JPEG results
    ├── index.html       # Project 1 write-up
    └── styles.css       # Project 1 styles
└── project2/
    ├── images/          # Project 2 inputs and filtering results
    ├── index.html       # Project 2 write-up
    └── styles.css       # Project 2 styles
```

Future project pages should live in `project0/` through `project4/` and `final/`, each with its own `index.html`. Use relative paths so the site works at `zszeto.github.io/cs180/`.

Each project keeps its page, styles, and publishable images in its own directory.

## Run locally

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Publish with GitHub Pages

In the repository's **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save. The published site will be available at <https://zszeto.github.io/cs180/>.
