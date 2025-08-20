# Improving French Synthetic Speech Quality via SSML Prosody Control — Demo

A lightweight, static demo webpage that showcases example SSML, side-by-side audio comparisons (baseline vs. enhanced), architecture and preprocessing diagrams, and links to project resources for the research project "Improving French Synthetic Speech Quality via SSML Prosody Control."

## Contents
- `index.html` — main demo page
- `style.css` — visual styles
- `script.js` — client-side behavior (navigation, audio handling, animations)
- `architecture.png`, `PreprocessingPipeline.png` — illustrative diagrams
- `audio/` — example audio files (`*_baseline.wav`, `*_enhanced.wav`)

## Quick start
1. Clone or download this repository.
2. Open the demo in your browser:
   - Option A (double-click): open `index.html` in your browser.
   - Option B (recommended): run a simple local server to avoid media/CORS quirks.

```bash
# Python 3
python3 -m http.server 8000
# then open http://localhost:8000

# or using npx http-server
npx http-server -p 8000
# then open http://localhost:8000
```

## How to update demo assets
- Replace the diagrams: overwrite `architecture.png` and `PreprocessingPipeline.png`.
- Swap example audio: put new files into the `audio/` folder and update the `<audio>` elements in `index.html`.
- Edit text/SSML: update the text blocks and `<pre>` elements in `index.html`.
- Optional: enable the lazy-loading behavior in `script.js` by uncommenting the audio lazy-load observer lines.

## Authors & Contact
Maintained by Hi! PARIS, Tim Luka Horstmann — tim.horstmann@ip-paris.fr

If you find issues or want to contribute improvements (content fixes, accessibility tweaks, better examples), please open a PR or an issue.

## License
This repository is licensed under the Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0). See `LICENSE` for full terms.

Short summary: you are free to share and adapt the material for non-commercial purposes as long as you provide appropriate credit to the authors and indicate if changes were made. For any commercial use or separate licensing of code, please contact the maintainer.

## Citation
If you use this demo in a publication, please mention the demo in your acknowledgements.

---

Last updated: August 20, 2025
