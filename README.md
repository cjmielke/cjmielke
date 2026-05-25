### Hi, I'm Cosmo 👋

I build and deploy AI systems for high-stakes clinical and scientific environments. My focus is at the intersection of foundation models, high-performance computing, and beneficial deployments in life sciences.

Currently, I'm a Senior AI Engineer at Genentech training foundation models for digital pathology. Previously, I built the algorithm for the first FDA-cleared AI to run directly on a bedside medical device at UCSF, and spent a decade running a computational biology nonprofit.

#### 🚀 Featured Tooling
* **[NeuroAnswer](https://github.com/cjmielke/NeuroAnswer)**: An AI copilot for exploring the MICrONs Minnie65 connectome dataset. Uses an MCP (Model Context Protocol) server to let researchers query 200k+ neurons and 500 million synapses via natural language, rendering the results directly into a 3D Neuroglancer scene.
* [useful-transformers (RK3566 NPU Port)](https://github.com/cjmielke/useful-transformers/tree/RK3566): A low-level C++ optimization enabling transformer inference (Whisper) on highly constrained edge silicon. Engineered a fundamental rewrite of the library's matrix logic and ARM NEON intrinsics, refactoring the fp16 processing pipeline from an 8-wide to a 4-wide architecture to resolve hardware-level memory alignment crashes on the Rockchip RK3566 NPU. This port allows near-realtime whisper speech to text transcription on chips that [cost as little as $15](https://www.lcsc.com/product-detail/C2943786.html)

#### 📌 Applied Machine Learning & Systems
* **Bedside AI for Critical Care (UCSF & GE Healthcare)**: Designed and trained the deep learning architecture for the first FDA-cleared AI algorithm fully integrated into a mobile medical device (detecting collapsed lungs on bedside X-rays). 
  * 📄 [Read the Publication (PLOS Medicine)](https://pubmed.ncbi.nlm.nih.gov/30457991/)
  * 📰 [Read the Press Release (GE Healthcare)](https://investor.gehealthcare.com/news-releases/news-release-details/ge-healthcare-expands-device-triage-capabilities-critical-care)
* **[synominous](https://github.com/cjmielke/synominous)**: An in-browser vector search engine and interactive UMAP viewer for clustering ~100k fruitfly brain synapses, utilizing PGVector and off-the-shelf vision transformers.
* **[quarantine@Home](https://github.com/cjmielke/quarantineAtHome)**: A distributed computing architecture I built to crowd-source small-molecule docking against COVID-19 viral proteins using AutoDock and GPU-optimized Docker containers.
* **[rsna-mammography](https://github.com/cjmielke/rsna-mammography)**: Implementations of Attention-based Multiple Instance Learning (MIL) applied to digital mammography screening.

#### 📚 Archive & Writing
* **[Project Infinome / Research Blog](https://blog.infino.me/bpa/)**: Research, writing, and history from my decade running Infinome, a self-funded computational biology nonprofit.

#### Ancient projects
* [QuarantineAtHome](https://quarantine.infino.me/) was an emergency project that was [rapidly built during the first two months](https://covidglobalhackathon.com/projects/quarantinehome) of the covid pandemic. I lead the development of a "Seti@Home" and "FoldingAtHome" inspired drug docking experiment to find compounds that would target the spike protein and the Sars-Cov2 main protease. This project eventually got me a job working at Vir biotech where I developed a more refined internal docking pipeline.
* [Hungrybot](https://www.infino.me/hungrybot) was [arguably the first](https://news.ycombinator.com/item?id=11712751) ever released AI food recognition app, a year before [NotHotdog](https://www.youtube.com/watch?v=ACmydtFDTGs), and unlike NotHotdog, HungryBot also provided genomics analysis! This is probably the most insanely ambitious thing I ever built.
