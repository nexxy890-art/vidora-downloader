# Vidora Downloader

A responsive static video helper website.

## Run locally
Open `index.html` in a modern browser, or serve this folder with any static web server.

## Deploy on GitHub Pages
1. Create a GitHub repository named `vidora-downloader`.
2. Upload `index.html`, `style.css`, `app.js`, and this README to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for the Pages URL to appear in that section.

## Important behavior
- YouTube URLs are detected and offered as links to open on YouTube. This project does not bypass YouTube's restrictions or extract protected streams.
- Direct video URLs are inspected using a browser `HEAD` request. The host must allow CORS and expose the content type/length for metadata to be available.
- The local-file tab previews a video selected from the user's device. Files are not uploaded to a server.
- Browser download behavior depends on the source server and browser. Cross-origin hosts may ignore the `download` attribute.

Use this site only for content you own or are authorized to download.
