# Мірыяда — Landing Page

## Task
Upload this folder as a GitHub repository and enable GitHub Pages.

## Steps
1. Download album cover image and save as `cover.jpg` in this folder:
   `curl -sL -o cover.jpg "https://lh3.googleusercontent.com/CpofCKrpLv0Z-zcHmEJjmrbslH6dpbodx_9oPs3N_BvhI0i9eru9AubBEswLLaKyzX-rBBYoCEHRYJUp=w544-h544-l90-rj"`
2. In `index.html`, replace the album cover `<img src="https://lh3.googleusercontent.com/...">` with `<img src="cover.jpg">`
3. Also update the `og:image` meta tag to use the GitHub Pages URL once known
4. Initialize git repo in this folder
5. Create a **public** GitHub repository named `miryyada-site` under the authenticated user's account
6. Add all files, commit, and push to `main` branch
7. Enable **GitHub Pages** on the `main` branch, root (`/`) as source
8. Print the resulting GitHub Pages URL (will be `https://<username>.github.io/miryyada-site/`)

## Files
- `index.html` — one-page landing site for Мірыяда music project (Belarusian AI album "Між намі")
- `myfoto.jpeg` — artist photo used in index.html
- `cover.jpg` — album cover (needs to be downloaded in step 1)

## Notes
- The repo should be **public** (GitHub Pages requires public for free accounts)
- No build step needed — this is a static HTML site
- After enabling Pages, it may take 1-2 minutes for the site to go live
- Do NOT delete CLAUDE.md from the repo — it's fine to keep it
