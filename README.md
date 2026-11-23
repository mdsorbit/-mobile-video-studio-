# Mobile Video Studio

A free, mobile-first browser video maker. It creates animated vertical scenes and records them locally in your browser.

## Features
- 9:16 vertical preview (720 × 1280)
- Cinematic, Space, and Neon visual styles
- Editable title and subtitle
- 10, 15, 20, or 30 second recording
- Slow, normal, and fast motion
- WebM video export using the browser's MediaRecorder API
- No login, paid API, or external service required

## Run
Open the GitHub Pages site in a recent version of Chrome, customize the scene, tap **Record video**, then **Save video to phone**.

## Enable GitHub Pages
In the repository, open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then save. Wait for GitHub to publish the site.

## Notes
- Export format is WebM. Some gallery apps may not preview WebM; use a compatible video player or convert it to MP4 with a trusted converter.
- This first version creates procedural motion graphics, not photorealistic AI actors or generated movie footage.
- Keep the page open while recording. Browser support for canvas recording is required.
