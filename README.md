# platanosverdes.com

Static site served by GitHub Pages at [platanosverdes.com](https://platanosverdes.com). No build step.

| File | What it is |
| :--- | :--- |
| `index.html` | The home page: the Watcher, its console, whoami and the project lists |
| `projects.json` | Every project shown on the home page and in the console |
| `homelab.html` | What the Homelab sign-in is; the home page of the Google OAuth app |
| `privacy.html` | Privacy policy, linked from the Google OAuth app |
| `logo.svg` | The Watcher |

## Adding or changing a project

Edit `projects.json` and push. `services` are the things anyone can use, each with its link. Each project is a name (the GitHub repository under PlatanosVerdes),
a one-line description and a language. `groups` are the sections under *projects*; `archived` and
`university` are the two lists at the bottom.

Pages publishes a push to `main` in about a minute.
