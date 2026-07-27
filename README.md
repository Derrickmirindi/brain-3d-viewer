# Brain Anatomy & Regions - A Modular Atlas

<img width="1009" height="1109" alt="image" src="https://github.com/user-attachments/assets/81610ec7-4ab5-481a-b9f0-38d4c3f834fb" />


An interactive, single-page web atlas of the human brain. It pairs an interactive **BioDigital Human** 3D model with a structured neuroanatomy reference table covering 20 core brain regions.

**Live site:** https://derrickmirindi.github.io/brain-3d-viewer/

## Overview

This project presents thoracic-style editorial anatomy content for the brain in two sections:

- **Section 01 - 3D Model:** An embedded BioDigital Human viewer (model `BE=4IX9`) that lets users rotate, zoom, and dissect the brain directly in 3D. Includes `Reload Model` and `Fullscreen` controls.
- **Section 02 - Regions:** A reference table of 20 core brain regions, each with its major subparts, core functional role, and links to supporting references (YouTube / Wikipedia).

## Regions Covered

Cerebrum, Frontal lobe, Parietal lobe, Temporal lobe, Occipital lobe, Insula, Limbic system, Basal ganglia, Diencephalon, Thalamus, Hypothalamus, Pineal region / Epithalamus, Brainstem, Midbrain, Pons, Medulla oblongata, Cerebellum, Ventricular system, White matter systems, and Cranial nerve nuclei / origins.

## Tech Stack

- Static HTML + CSS (no build step, no dependencies)
- Google Fonts: Inter and Space Mono
- BioDigital Human embedded viewer (iframe)
- Vanilla JavaScript for the reload/fullscreen controls
- Swiss modular 12-column grid layout

## Project Structure

```
brain-3d-viewer/
|-- index.html   # Entire single-page atlas (markup, styles, script)
|-- README.md    # This file
```

## Running Locally

Because the site is fully static, just open `index.html` in a browser, or serve the folder:

```bash
# Clone the repository
git clone https://github.com/Derrickmirindi/brain-3d-viewer.git
cd brain-3d-viewer

# Option A: open directly
open index.html

# Option B: serve with a local web server
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

The site is deployed with **GitHub Pages** from the `main` branch (root folder). Any commit to `main` republishes the site automatically.

## Authors

By Derrick Mirindi, David Sinkhonde and Frederic Mirindi.

