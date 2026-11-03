# Srijita Saha – Academic Website

A simple, fast academic site built with plain HTML and CSS. No build tools needed.

## Files
- `index.html` – all page content
- `style.css` – all styling (colors are at the top under `:root`)
- `cv.pdf` – your CV (add this yourself)
- `photo.jpg` – optional profile photo (add this yourself)

## Publish on GitHub Pages
1. Create a public repo named `YOUR-USERNAME.github.io`
2. Upload all the files to the repo root
3. Go to **Settings → Pages**, set source to the `main` branch and `/ (root)`
4. Open `https://YOUR-USERNAME.github.io` after a minute or two

## Edit your content
- Replace everything in `[square brackets]` in `index.html`
- Change `your.email@university.edu` to your real email
- Fill in the Google Scholar and ORCID links, or delete those lines
- Add a photo: replace the `SS` initials in the `.avatar` div with `<img src="photo.jpg" alt="Srijita Saha">`
- Add a new publication or course by copying an `<div class="entry">` block

## Change the look
- Edit the color variables at the top of `style.css`
- Dark mode switches on automatically based on the visitor's device

## Test locally
Open `index.html` in your browser, or run `python3 -m http.server` in the folder and visit `http://localhost:8000`.

## Links
- LinkedIn: https://www.linkedin.com/in/srijita-saha-125a47448
