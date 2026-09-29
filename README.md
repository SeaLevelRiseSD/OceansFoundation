# Sea Level Rise San Diego

A responsive, static website about sea level rise and its local effects in San Diego. This rebuild follows the supplied Airo reference and is ready for GitHub and Netlify.

## Local preview

No build step is required. From the project directory, run:

```bash
python3 -m http.server 4173
```

Then open [http://localhost:4173](http://localhost:4173).

## Pages

- `/` — Home
- `/learn/` — Sea level rise science
- `/impacts/` — Local impacts
- `/about/` — Project background
- `/action/` — Ways to help and contact form

## Deploy to Netlify

Connect the GitHub repository to Netlify and use these settings:

- Build command: leave blank
- Publish directory: `.`

The newsletter and contact forms use Netlify Forms and will be detected when Netlify deploys the site.

## Repository

The configured remote is `https://github.com/rubywhite/sealevelrise.git`.
