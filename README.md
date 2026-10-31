# platanosverdes.com

Static site served by GitHub Pages at [platanosverdes.com](https://platanosverdes.com). No build step.

| File | What it is |
| :--- | :--- |
| `index.html` | The home page: the Watcher, its console, whoami and the project lists |
| `projects.json` | Every project shown on the home page and in the console |
| `privacy.html` | Privacy policy of the Google OAuth app (PlatanosVerdes): the private services and Apex |
| `logo.svg` | The Watcher |
| `apple-touch-icon.png` | The Watcher for the iOS home screen, which ignores SVG icons: `rsvg-convert --width 180 --height 180 logo.svg -o apple-touch-icon.png` after changing the logo |

## Adding or changing a project

Edit `projects.json` and push. Each project is a name (the GitHub repository under PlatanosVerdes),
a one-line description and a language. `groups` are the sections under *projects*; `archived` and
`university` are the two lists at the bottom. A project anyone can use gets `links` (a label and a URL each), shown under its description.

Pages publishes a push to `main` in about a minute.

