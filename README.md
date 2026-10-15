# SiteAspect website

Support page (`index.html`) and privacy policy (`privacy.html`) for the SiteAspect iPhone app, published with GitHub Pages.

## Publish (about five minutes, no command line needed)

1. Sign in at github.com and choose **New repository**.
   - Repository name: `siteaspect`
   - Visibility: **Public** (GitHub Pages on a free account needs a public repository)
   - Leave "Add a README" unticked.
   - Choose **Create repository**.
2. On the new repository page, choose **uploading an existing file**. Drag in all the files from this folder: `index.html`, `privacy.html`, `style.css`, `README.md` and `.nojekyll`.
   - `.nojekyll` is hidden in Finder. Press **Cmd + Shift + .** in Finder to show hidden files. It is optional; the site works without it.
3. Choose **Commit changes**.
4. Open **Settings > Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**, then **Save**.
5. Wait a minute or two, then refresh the Pages settings. It shows the site address:
   - Support URL: `https://YOUR-USERNAME.github.io/siteaspect/`
   - Privacy policy URL: `https://YOUR-USERNAME.github.io/siteaspect/privacy.html`
6. Open both links in a private browser window to check they load.

## Updating

Edit a file on github.com (pencil icon) or upload a replacement, then commit. The site updates within a minute or two. If the app's data handling ever changes, update `privacy.html` and its effective date before releasing that version.
