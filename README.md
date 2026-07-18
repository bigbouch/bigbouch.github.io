# BigBouch Website

This is a free, one-page artist website built for GitHub Pages.

## Fastest way to publish it free

1. Create a free GitHub account at github.com.
2. Create a new public repository named `bigbouch`.
3. Upload `index.html` from this folder.
4. Open the repository's **Settings**.
5. Select **Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select the `main` branch and `/root`, then save.
8. Your free address will look like:
   `https://YOUR-USERNAME.github.io/bigbouch/`

## To use the shortest free GitHub address

Name the repository exactly:

`YOUR-USERNAME.github.io`

Then the website address becomes:

`https://YOUR-USERNAME.github.io`

## What to customize

Open `index.html` in any text editor and replace:

- `Your New Single`
- The release description
- Every `href="#"` with your real Spotify, Apple Music, YouTube, Instagram, and TikTok links
- `booking@example.com` with your email
- The placeholder album artwork, if desired

## Add real album artwork

Place your square artwork in the same folder and name it:

`cover.jpg`

Then find this line in the CSS:

`.cover {`

Add this inside that section:

`background: url("cover.jpg") center/cover no-repeat;`

Then delete or comment out the `.cover::after` block if you do not want BIGBOUCH displayed over the artwork.
