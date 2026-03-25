# EdgeLog GitHub Pages Setup

This project is ready to upload to GitHub and host with GitHub Pages.

## What is included
- `index.html` — your full EdgeLog app

## How to publish it free with GitHub Pages

1. Create a GitHub account if you do not already have one.
2. Create a new repository. A good name is `edgelog`.
3. Upload the files from this folder to the repository.
4. In GitHub, open **Settings** for the repository.
5. Open **Pages** in the left sidebar.
6. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
7. Save.
8. Wait a minute or two. GitHub will give you a live link.

Your site will usually be at:
`https://YOUR-USERNAME.github.io/REPO-NAME/`

## Important note about storage
Right now the app saves to local browser storage on the same device/browser.
That means:
- data stays when the user closes the site
- but it does not sync across devices yet

To get true cloud sync later, connect Firebase or Supabase.

## Updating later
Once the site is on GitHub Pages:
- edit `index.html`
- upload the new version to the same repo
- GitHub Pages updates the live site automatically

That means you will not need to hand out a new file every time.
