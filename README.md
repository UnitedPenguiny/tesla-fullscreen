# Tesla Fullscreen Launcher

A self-contained static website to launch links using the Tesla browser's YouTube/Theater redirect workaround.

## Deploy using GitHub Pages

1. Create a new **public** GitHub repository named `tesla-fullscreen`.
2. Upload `index.html` and `.nojekyll` to the root of the new repository (or push them using Git).
3. Open the repository's **Settings → Pages**.
4. Select **Deploy from a branch**, **main**, **/(root)**, and save.
5. Visit `https://<your-username>.github.io/tesla-fullscreen/` in the parked Tesla browser.
6. Bookmark the site. Tap **Enter Tesla Fullscreen**, then **Go to site** on the YouTube redirect screen if offered.

The technique depends on Tesla's software and YouTube redirect handling, so it may stop working. It does not bypass built-in video safety limits.

## Features

- One-button YouTube redirect of the launcher itself, allowing a possible fullscreen Theater view.
- Type any HTTP/HTTPS URL and open it via the same redirect.
- Built-in quick links and locally saved shortcuts.
- No external libraries, no trackers, no required backend.

## Security

No credentials or URLs are uploaded to the site operator. Shortcuts are stored in the vehicle browser's `localStorage`. Destination sites handle their own login and traffic. Don't open untrusted URLs.