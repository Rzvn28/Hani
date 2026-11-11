# Hanieh Motamedi — Portfolio

A bilingual (English / فارسی) personal portfolio. Plain HTML, CSS and JavaScript, no frameworks and no external requests.

## Folder structure

```
index.html
css/style.css
js/main.js
assets/images/   profile, about, psychology, mind, reading, painting, design,
                 g-illustration, g-painting, g-books, g-concept, g-workspace (.webp)
assets/fonts/    Vazirmatn (Regular, Medium, Bold), Cormorant Garamond (400, 500, 600, 400 italic) (.woff2)
README.md
.nojekyll
```

## Adding contact details

Open `js/main.js`. At the top is:

```js
var CONTACT = { email: "", instagram: "", linkedin: "" };
```

Fill in any of them, for example `email: "name@example.com"`, and use full `https://` addresses for Instagram and LinkedIn. Only filled values are shown; while all are empty the page says "Contact details coming soon."

## Language

English is the default. The "فارسی" button in the menu switches to Persian (right-to-left). Open the site with `#fa` or `?lang=fa` at the end of the address to start in Persian.

## Publishing on GitHub Pages

1. On GitHub, create a new **public** repository.
2. Click **Add file > Upload files**.
3. Drag in the **contents** of this folder, not the folder itself. `index.html` must be at the repository root; keep the `css/`, `js/` and `assets/` folders as they are. (If `.nojekyll` is hidden on your computer, it is optional.)
4. Click **Commit changes**.
5. Go to **Settings > Pages**. Under **Source** choose **Deploy from a branch**, pick branch **main** and folder **/ (root)**, then **Save**.
6. Wait 1–2 minutes. The site will be at `https://USERNAME.github.io/REPO/`.

**Note:** file names are case-sensitive on GitHub. Keep every file name exactly as it is (for example `Vazirmatn-Regular.woff2` and `profile.webp`), or images and fonts will not load.
