# Brain Explorer 3D

An interactive, single-file, browser-based brain explorer for learning. Rotate a schematic 3D brain, switch between ways of viewing it, and read short summaries of regions, functions, networks — and now also conditions, substances, medications, famous case studies, how the brain changes across life, and which popular claims do not survive the evidence.

> **Educational use only.** This is a simplified teaching aid, not clinical guidance. Shapes, sizes and positions are schematic and approximate, cortical regions use simple boundaries, and the right hemisphere is a mirror image of the left. Do not use it for diagnosis or treatment decisions. Condition, substance and medication summaries describe population-level research findings; they are never medical advice — never start, stop or change medication without a qualified clinician.

## Features

### The 3D model
- Rotatable 3D brain with procedurally generated gyri/sulci folding, a visible Sylvian fissure and central sulcus, and an internal view (cutaway and adjustable opacity)
- Shaped deep structures rather than plain blobs: a seahorse-curved hippocampus, almond amygdala, bulging pons, folia-striped cerebellum, C-shaped caudate and putamen, and midbrain dopamine nuclei
- 21 selectable structures, including the ventral tegmental area, substantia nigra, nucleus accumbens, locus coeruleus and raphe nuclei
- Floating 3D labels that track structures as you rotate (toggle: **Labels**)
- A **Pathways** overlay drawing the major neuromodulator routes — dopamine (VTA and substantia nigra), serotonin (raphe), noradrenaline (locus coeruleus) and acetylcholine — with animated signal pulses and a colour legend
- Both-hemispheres toggle and three slice planes (sagittal, coronal, axial) with adjustable position

### Ways of exploring
- **By region**, **by function** and **by network** lenses (as before)
- **Conditions** lens: 19 entries across neurological, psychiatric, injury & sleep and addiction groups. Each highlights the regions and networks most consistently implicated and cites its sources — Parkinson's, Alzheimer's, epilepsy, stroke, multiple sclerosis, Huntington's, depression, anxiety, PTSD, OCD, ADHD, schizophrenia, bipolar disorder, autism, TBI, CTE, insomnia, narcolepsy and substance use disorder
- **Substances & meds** lens: 15 entries — alcohol, caffeine, nicotine, cannabis, cocaine, amphetamine, MDMA, opioids, LSD/psilocybin, ketamine, SSRIs/SNRIs, antipsychotics, mood stabilisers, benzodiazepines and ADHD medications. Each names the neurotransmitter systems it acts on (highlighting the matching pathways on the model), plus short- and longer-term effects
- **Case studies** lens: H.M., Phineas Gage, Broca's patient "Tan", S.M. and the split-brain patients, with what each did — and didn't — prove
- **Across life** lens: seven stages from before birth to later life — what is being built (neurogenesis, synapse bursts, pruning, myelination), the vulnerabilities of each window, and what supports it, with the Lancet Commission's preventable-dementia findings in the later stages
- **Myths & hype** lens: eight popular claims — "we only use 10% of our brain", "left-brained people", "the brain is finished at 25", "dopamine detox", brain-training, "every drink kills brain cells", "chemical imbalance", learning styles — each with the claim as it circulates, what the evidence says, why it spreads, and its sources
- Two-way cross-links: every region panel lists the conditions and substances that involve it, every condition/substance panel links back to the brain and (where relevant) to the life stages it typically touches
- **Print this view / Copy as text**: a clean, print-formatted summary of whatever you are looking at — including your own notes and bookmarks — for handouts and revision
- Search across structures, functions, networks, conditions, substances, case studies, life stages, myths and the glossary
- Compare mode, a quiz (structures, conditions, neurotransmitter systems *and* a true-or-false round mixing myth claims with true statements), personal notes and bookmarks
- A tap-to-expand **Glossary** of ~38 terms, an in-app **References** list (58 sources), and an expanded "Reading this critically" panel
- A **Guided tour**: a 9-step walkthrough that moves the camera and highlights structures as it introduces each lens
- **Shareable links**: the URL updates as you explore, so you can link straight to a condition, region or substance (also supports the browser's back button)

## Running it

Open `index.html` in a browser. No build step is required. To host a live demo, enable GitHub Pages for the repository (Settings, then Pages, then deploy from the `main` branch, root folder).

**Needs an internet connection** because it loads two things from external servers:

- three.js (r128) from cdnjs
- the Figtree and Bitter fonts from Google Fonts

Visitors' browsers therefore contact those services when the page loads. If you need a fully offline or more privacy-preserving version, download those files and serve them from the repository.

## Data and privacy

Nothing is sent to any server by the app itself. Notes and bookmarks are stored in the browser's local storage on the visitor's device only. Note that all GitHub Pages sites under one account share a browser origin, so local storage is shared across them.

## Known limitations

- Anatomy is schematic and simplified for teaching, so it will not match imaging or an atlas. The gyri pattern is procedurally generated decoration, not real anatomy.
- Condition–region links are group-level research associations, often contested; substance mechanisms are simplified pharmacology. None of it diagnoses anyone.
- Many findings about brain function are contested, and region-function mappings are approximate; see the in-app references.
- Not systematically tested across devices or with assistive technology.

## AI-assistance statement

This project was developed in conversation with Claude (Anthropic), expanded in a second pass with Z.ai (GLM) — that pass added the improved 3D geometry, pathways overlay, conditions, substances, case studies, glossary, tour and link sharing — and extended in a third pass with Z.ai (GLM), which added the life-span and myth lenses, the true-or-false quiz round, print/copy summaries and four new references. The content and code have not been independently reviewed by a neuroscientist, a pharmacologist or an accessibility auditor. Please check the references and claims before relying on them.

## References

The in-app **References** panel lists the sources used. Please verify each DOI resolves and that the cited work supports the statement it is attached to.

## Licence

MIT. See `LICENSE`.
