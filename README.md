# Mohith Anumula — Portfolio

A dark, cinematic personal portfolio: near-black background, burgundy accents and editorial typography. Short videos of me run through the page: on the right in the top section, on the left in About, then again in Skills, Projects, Experience and Contact.

Plain HTML, CSS and JavaScript. No build step.

## Files

```
index.html          the whole site
resume.pdf          your résumé (add it; the Résumé buttons link here)
images/avatar.png   shown wherever a video is missing
videos/
  hero-right.mp4    you on the RIGHT (top section, Skills, Experience, Contact)
  about-left.mp4    you on the LEFT (About, Projects)
VIDEO-PROMPTS.md    the Google Flow prompts for making the two videos
```

## Make it yours

1. **Videos:** follow `VIDEO-PROMPTS.md`, then put both files in a `videos` folder.
2. **Résumé:** add your résumé as `resume.pdf` next to `index.html`.
3. **Text:** in `index.html`, replace everything in `[brackets]` with details from your résumé: city, intro, bio, skills, projects, experience, education, email and LinkedIn link. Search for `EDIT:` to find each part.

## How the videos behave

- The top-section video loads first. The others load only when you scroll near them, and play only while they're on screen.
- If a video file is missing, the cartoon in `images/avatar.png` is shown instead, so the site never looks broken.
- With "reduce motion" turned on in the visitor's system settings, the videos and animations stay still.

## Run locally

Open `index.html` in a browser, or run `python3 -m http.server 8000` and go to http://localhost:8000.

## Deploy with GitHub Pages

Push to GitHub, then go to **Settings → Pages**. Choose **Deploy from a branch**, then `main` and `/ (root)`, and click **Save**. The site goes live at https://mohithanumula.github.io/Portfolio/
