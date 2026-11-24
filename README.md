V.BHUVANESH VENKATA SAI MANIKANTA 
N26V01A0416
SECTION-5
# Tamil Notes

A responsive, single-page Tamil music discovery website made with HTML5 and CSS3. It highlights Anirudh Ravichander and Sai Abhyankkar with artist profiles, albums and singles, playlists, recently played songs, popular tracks, and a fixed audio player.

## Features

- Dark theme with a bright accent color and responsive layouts.
- Sidebar navigation on desktop and a horizontal top navigation on mobile.
- Artist, album, playlist, recently played, and popular track sections.
- Flexbox-only page layout; no JavaScript, frameworks, or CSS Grid.
- A fixed player with native HTML audio controls and a royalty-free sample.
- Placeholder photography from Unsplash; replace images with properly licensed artwork before public use.

## How the layout works

- `display: flex` makes a container line up its child elements.
- `flex-direction` chooses a row or column; the sidebar navigation switches between these as the screen changes.
- `justify-content` distributes items along the main axis, while `align-items` lines them up across the other axis.
- `flex-wrap: wrap` moves cards onto another line when they no longer fit.
- `gap` adds consistent space between flex items without extra margins.
- `flex: 1` lets artist cards share the available row space.

## Project structure

```text
music-streaming-website/
├── index.html
├── style.css
└── README.md
```

## Run locally

Open `index.html` in a browser. The Google Fonts, placeholder photos, and audio sample need an internet connection.

## Upload to GitHub

1. Sign in to GitHub and create a new repository, for example `tamil-notes`.
2. In the repository page, choose **Add file → Upload files**.
3. Upload `index.html`, `style.css`, and `README.md` (keep them together in the repository root).
4. Enter a commit message and choose **Commit changes**.

## Publish with GitHub Pages

1. Open the repository's **Settings** tab.
2. In the left sidebar, choose **Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose the `main` branch and `/ (root)` folder, then select **Save**.
5. Wait for the Pages deployment to finish. Open the published URL shown in the Pages settings.

If you update the site later, commit the changes to the selected branch and GitHub Pages will deploy them.
