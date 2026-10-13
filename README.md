# Brain Explorer 3D

An interactive, single-file, browser-based brain explorer for learning. Rotate a schematic 3D brain, switch between ways of viewing it, and read short summaries of regions, functions and networks.

> **Educational use only.** This is a simplified teaching aid, not clinical guidance. Shapes, sizes and positions are schematic and approximate, cortical regions use simple boundaries, and the right hemisphere is a mirror image of the left. Do not use it for diagnosis or treatment decisions.

## Features

- Rotatable 3D brain with an internal view (cutaway and adjustable opacity)
- Three lenses: by **region**, by **function** and by **network**
- Search, a compare mode and a quiz
- Personal notes and bookmarks, saved in your own browser
- Both-hemispheres toggle and accessibility options
- A "Reading this critically" panel and an in-app reference list

## Running it

Open `index.html` in a browser. No build step is required. To host a live demo, enable GitHub Pages for the repository (Settings, then Pages, then deploy from the `main` branch, root folder).

**Needs an internet connection** because it loads two things from external servers:

- three.js (r128) from cdnjs
- the Figtree and Bitter fonts from Google Fonts

Visitors' browsers therefore contact those services when the page loads. If you need a fully offline or more privacy-preserving version, download those files and serve them from the repository.

## Data and privacy

Nothing is sent to any server by the app itself. Notes and bookmarks are stored in the browser's local storage on the visitor's device only. Note that all GitHub Pages sites under one account share a browser origin, so local storage is shared across them.

## Known limitations

- Anatomy is schematic and simplified for teaching, so it will not match imaging or an atlas.
- Many findings about brain function are contested, and region-function mappings are approximate; see the in-app references.
- Not systematically tested across devices or with assistive technology.

## AI-assistance statement

This project was developed in conversation with Claude (Anthropic). The content and code have not been independently reviewed by a neuroscientist or an accessibility auditor. Please check the references and claims before relying on them.

## References

The in-app **References** panel lists the sources used. Please verify each DOI resolves and that the cited work supports the statement it is attached to.

## Licence

MIT. See `LICENSE`.
