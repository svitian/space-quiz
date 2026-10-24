# Space Exploration Quiz

Space Exploration Quiz is a lightweight browser quiz focused on space science and exploration trivia. It is designed as a single-page experience with no external dependencies and no build setup.

## Features

- 10-question space-themed quiz flow
- Progress tracking during gameplay
- Live score counter
- Animated correct/incorrect feedback
- Final results screen with emoji reaction
- Responsive narrow-column layout for comfortable reading

## Dependency-free single-file design

The app is intentionally implemented as one static `index.html` file with inline HTML, CSS, and JavaScript. No package manager, build pipeline, framework, or runtime dependencies are required.

## Run locally

You can run the quiz locally in either of these ways:

1. Open `/home/runner/work/space-quiz/space-quiz/index.html` directly in a browser.
2. Or serve the folder with a tiny local server, for example:

   ```bash
   cd /home/runner/work/space-quiz/space-quiz
   python3 -m http.server 8000
   ```

   Then open `http://localhost:8000`.

## GitHub Pages deployment target

When GitHub Pages is enabled for this repository and the deployment workflow runs successfully from `main`, the site URL is expected to follow:

`https://svitian.github.io/space-quiz/`