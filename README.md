# Portfolio

A personal portfolio site for a software engineer, built from scratch with plain HTML, CSS and JavaScript. No build step and no dependencies.

**Sections:** glassy futuristic design: aurora background, starfield, cursor spotlight, 3D-tilt glass cards · hero with typing effect and an animated 3D cartoon of me that stands, breathes, blinks, looks at your cursor and says "Hi!" with a head tilt and a waving hand · tech-stack marquee · about · services · stacked project cards · testimonials · contact form · footer

## Make it yours

Search `index.html` for `EDIT:` comments and `[brackets]`, then replace:

- your name (hero, footer, page title), city, role and intro
- the rotating roles in the hero (the `ROLES` list in the script at the bottom)
- the tech-stack chips in the marquee
- the three project cards: name, description, stack, links and a screenshot
- testimonials (real quotes only — LinkedIn recommendations work well)
- email and social links
- add your CV as `resume.pdf` in the repo root

To use a real screenshot in a project card, replace the `<span class="placeholder">` with:

```html
<img src="images/project-1.png" alt="Screenshot of Project name" style="width:100%;height:100%;object-fit:cover;position:absolute;inset:0">
```

### Contact form

The form posts to [Formspree](https://formspree.io). Create a free form there and replace `YOUR_FORM_ID` in `index.html`.

## Run locally

Open `index.html` in a browser, or run:

```bash
python3 -m http.server 8000
```

## Deploy with GitHub Pages

1. Push to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**, then `main` and `/ (root)`.
4. Your site will go live at `https://<username>.github.io/<repo>/`.

### The animated avatar

The character comes from `images/avatar.png`, cut into layers (`leg-l`, `leg-r`, `torso`, `head`) so the body can breathe and shift its weight and the head can tilt and nod. Every few seconds it says "Hi!" with a waving hand in the speech bubble. The timing is set in the last `<script>` in `index.html`.
