# Saeid Pourmand — Academic Website

A minimalist academic homepage, ready for **GitHub Pages**. No build tools or dependencies are required.

## Publish on GitHub Pages

1. Log in to GitHub as **pourmands**.
2. Create a new **public** repository named **pourmands.github.io** (exact spelling).
3. Extract the ZIP. Upload the **contents of the extracted folder** (not the ZIP or the folder itself) to the root of the repository using **Add file → Upload files**. Make sure `index.html` is at the top level.
4. Commit the changes.
5. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/(root)**. Click **Save**.
6. Your site will appear at **https://pourmands.github.io/** once GitHub Pages finishes publishing.

## Update your portrait

The file `assets/photo-placeholder.svg` is a temporary placeholder. Add your headshot to `assets/` (for example, `photo.jpg`), then in `index.html`, change:

`src="assets/photo-placeholder.svg"` to `src="assets/photo.jpg"`

The portrait is displayed as a circle automatically.

## Update other content

- Edit `index.html` to change bio, research projects, publication entries, or email.
- Edit `styles.css` to change appearance.
- Replace `CurriculumVitae-SaeidPourmand.pdf` with a newer PDF using the same filename to keep links intact.

## Contents

- `index.html` — webpage
- `styles.css` — layout and styling
- `assets/research-visual.svg` — abstract research illustration
- `assets/photo-placeholder.svg` — portrait placeholder
- `assets/favicon.svg` — browser favicon
- `CurriculumVitae-SaeidPourmand.pdf` — your provided Curriculum Vitae

The page is static and does not collect visitor information.
