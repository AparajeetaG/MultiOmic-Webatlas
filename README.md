# MultiOmic-Webatlas
Interactive web atlas for spinal cord single-nucleus and spatial transcriptomic data, built as static HTML/JS pages deployable via GitHub Pages.



# Spinal Cord Single-nucleus & Spatial Transcriptomic WebAtlas

This repository hosts a lightweight, browser-based web atlas for a spinal cord dataset combining single-nucleus RNA-seq and spatial transcriptomics.  
All views are generated from `AnnData` objects in Python and exported as standalone HTML files that can be served directly via GitHub Pages.

The atlas provides interactive UMAP and tissue-level maps that allow visitors to:
- Explore broad cell classes, timepoints, spinal regions, and sample-level structure.
- Inspect gene expression patterns across nuclei and spatial spots via dropdown-selectable genes.
- Navigate between single-nucleus and spatial views from simple landing pages, without needing to install any analysis environment.

The pages are implemented using Scanpy, Plotly, and pure HTML/JavaScript exports, so they remain fully static while supporting rich, exploratory visualization in the browser.


## Copyright

© 2025 Aparajeeta Guha. All rights reserved.

This repository and its contents (code, configuration files, and HTML visualizations) are provided for viewing and academic reference.  
Re-use, modification, or redistribution are not permitted without explicit written permission from the author.
