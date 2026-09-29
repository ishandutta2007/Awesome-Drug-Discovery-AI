# Awesome-Drug-Discovery-AI

## Top Drug Discovery AI Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Computational Drug Design, Virtual Screening & AI-Driven Lead Optimization*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI-Driven Drug Discovery**. These tools apply machine learning, physics-based modeling, and generative algorithms to accelerate the identification of novel therapeutic candidates — from target validation through lead optimization — reducing the time and cost of traditional R&D cycles.



**Examples** include Schrödinger, Atomwise, Insilico Medicine, Recursion, Exscientia, BenevolentAI, XtalPi, Relay Therapeutics, Valo Health, and Owkin (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom virtual screening, and transparent cheminformatics — ideal for academic researchers, biotech startups, and developers building vendor-independent drug discovery pipelines. The open-source ecosystem offers ligand-based screening tools, structural bioinformatics platforms, and molecular docking engines, though full end-to-end AI drug discovery platforms remain largely commercial.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Schrödinger](https://www.schrodinger.com/)**  

  Computational platform built on 30+ years of physics-based R&D, licensed by biotech, pharma, and academic institutions worldwide. Launched **Bunsen**, an agentic AI co-scientist for molecular discovery, and **RetroSynth**, an AI-driven synthesis planning platform using distributed Monte Carlo tree search to predict optimal synthetic pathways . BMS deployed Bunsen at scale in August 2026 .



- **[Atomwise](https://www.atomwise.com/)**  

  Deep learning virtual screening pioneer with AtomNet. Published results from 318 prospective experiments showing 6.7% internal hit rate and 91% of experiments producing reconfirmed single-dose hits . Screened a 16-billion synthesis-on-demand chemical space for internal programs .



- **[Insilico Medicine](https://insilico.com/)**  

  Clinical-stage generative AI drug discovery company with **Pharma.AI** platform spanning target validation, generative chemistry, and molecule optimization. Signed a landmark $2.5B neuroimmune alliance with SK Biopharmaceuticals and a ~$600M collaboration with Takeda in 2026 . Pharma.AI reduces target-to-PCC timelines to an average of 12–18 months .



- **[Recursion](https://www.recursion.com/)**  

  TechBio company operating **Recursion OS**, an AI-native drug discovery engine integrating phenomics, transcriptomics, and patient data. Runs up to 2 million weekly experiments building a 50+ petabyte proprietary dataset . Achieved first clinical validation with REC-4881 for familial adenomatous polyposis (FAP) .



- **[Exscientia](https://www.exscientia.ai/)**  

  AI-driven precision medicine platform incorporating human tissue samples into early target and drug discovery. Signed a $100M upfront deal with Sanofi covering 15 small-molecule candidates for oncology and immunology . Trains on pharmacology data and patient multi-omics to iteratively design targeted compounds .



- **[BenevolentAI](https://www.benevolent.com/)**  

  Proprietary **Benevolent Platform™** integrating AI and science to uncover new biology and predict novel targets. Features **R2E (Retrieve to Explain)** system for explainable AI in drug target identification, demonstrating higher relative success rates than industry-leading genetics-based methods when using all data modalities .



- **[XtalPi](https://www.xtalpi.com/)**  

  AI and robotics-driven R&D platform with **PepiX™** for peptide drug discovery and dynamic conformation precision modeling using quantum physics algorithms . Partnered with Gan & Lee Pharmaceuticals for metabolic disease peptide drugs . Collaboration with DoveTree valued at up to $5.99B with second payment received in May 2026 . Synthesizes 3,000–4,000 novel molecules in 2–3 months with >80% success rate .



- **[Relay Therapeutics](https://www.relaytx.com/)**  

  Clinical-stage precision medicine company with **Dynamo®** platform pioneering **Motion-Based Drug Design®** — insights into protein motion rather than static structures . Focused on precision oncology and genetic diseases, including PI3Kα franchise for breast cancer and vascular malformations .



- **[Valo Health](https://www.valohealth.com/)**  

  AI-enabled **human causal biology** platform leveraging access to 17 million+ de-identified patient records spanning 20–30 years, combined with biobank samples . **Closed loop chemistry** platform generates small molecules from trillions of starting points. Collaboration with Merck KGaA valued at over $3B for Parkinson's disease .



- **[Owkin](https://www.owkin.com/)**  

  Agentic AI company with **K Pro**, the first agentic AI co-pilot for biopharma powered by biological reasoning models . Built on **Owkin Zero**, a fine-tuned biological LLM. Accelerated internal drug target identification by 70% (12+ months to 3 months) and built an IND-ready asset positioning strategy in hours . Licensed to Boehringer Ingelheim for oncology and immunology in September 2026 .



## Open-Source GitHub Projects



- **[PyRMD Studio](https://github.com/sandrocosconati/PyRMD-Studio)**  

  Major update to the open-source virtual screening software with comprehensive GUI compatible with Linux and Windows, democratizing access to AI workflows for non-expert users. Supports both ligand-based and structure-based virtual screening without coding expertise. Implements rigorous validation strategy based on Butina clustering to separate structural clusters between training and test sets, mitigating data leakage and preventing overoptimistic benchmarking. Achieves ~3.3-fold increase in screening speed compared to previous release. Freely available and actively maintained .



- **[DeepChem](https://github.com/deepchem/deepchem)**  

  The most widely adopted open-source deep learning library for drug discovery, materials science, and quantum chemistry. Provides featurizers, models, and datasets for molecular property prediction, virtual screening, and generative chemistry. Supports TensorFlow, PyTorch, and JAX backends. Used in academic research and industrial pipelines worldwide.



- **[RDKit](https://github.com/rdkit/rdkit)**  

  The de-facto open-source cheminformatics toolkit, essential for any drug discovery pipeline. Provides molecular parsing, descriptor calculation, fingerprinting, substructure searching, and 2D/3D coordinate generation. BSD licensed and integrated into virtually every open-source drug discovery project.



- **[Open Babel](https://github.com/openbabel/openbabel)**  

  Open-source chemical toolbox for interconverting molecular file formats, generating 3D coordinates, and performing cheminformatics operations. Supports 110+ file formats and is a standard component in computational chemistry workflows.



- **[AutoDock Vina](https://github.com/ccsb-scripps/AutoDock-Vina)**  

  The most widely used open-source molecular docking engine, developed at Scripps. Achieves high accuracy and speed for protein-ligand docking, with support for flexible ligands and rigid receptors. Apache 2.0 licensed and actively maintained. Essential for structure-based virtual screening campaigns.



- **[GNINA](https://github.com/gnina/gnina)**  

  Open-source molecular docking with deep learning scoring, built on AutoDock Vina. Uses convolutional neural networks to improve binding pose prediction and affinity ranking compared to classical scoring functions. Developed by the Computational Structural Biology group at UCSF.



- **[DeepPurpose](https://github.com/kexinhuang12345/DeepPurpose)**  

  Deep learning library for drug-target interaction prediction with 15+ model architectures (DeepDTA, DeepPurpose, MPNN, etc.) and 15+ encoders for molecules and proteins. PyTorch-based, designed for both binding affinity prediction and drug repurposing applications. MIT licensed.



- **[Chemprop](https://github.com/chemprop/chemprop)**  

  Message passing neural network for molecular property prediction, developed at MIT. Achieves state-of-the-art results on MoleculeNet benchmarks. Supports directed message passing, reaction prediction, and uncertainty quantification. Actively maintained by the Chemprop community.



- **[Open Drug Discovery Toolkit (ODDT)](https://github.com/oddt/oddt)**  

  Modular open-source toolkit for drug discovery, providing machine learning scoring functions, consensus scoring, and virtual screening pipelines. Integrates with RDKit and Open Babel. BSD licensed.



- **[PLIP (Protein-Ligand Interaction Profiler)](https://github.com/pharmai/plip)**  

  Open-source tool for analyzing and visualizing protein-ligand interactions from 3D structures. Detects hydrogen bonds, hydrophobic contacts, pi-stacking, salt bridges, and water bridges. Widely used for post-docking analysis and binding mode characterization.



### Additional Strong Open-Source Options



- **OpenMM** — High-performance toolkit for molecular simulation, enabling physics-based drug discovery workflows with GPU acceleration.

- **PyMOL (Open-Source Build)** — Molecular visualization system for structural biology, widely used for analyzing protein-ligand complexes.

- **MDTraj** — Modern, open-source library for analyzing molecular dynamics trajectories with fast, vectorized operations.

- **MDAnalysis** — Python library for analyzing molecular dynamics simulations, supporting many trajectory formats and providing a rich API.

- **Open Force Field Initiative** — Open-source force fields for molecular simulation, providing reproducible and extensible parameters for drug discovery.



**Frameworks for building custom AI drug discovery pipelines**: Combine **RDKit** for cheminformatics foundations, **DeepChem** or **Chemprop** for molecular property prediction, **AutoDock Vina** or **GNINA** for structure-based virtual screening, and **PLIP** for interaction analysis. For ligand-based screening with GUI accessibility, **PyRMD Studio** provides a validated, user-friendly foundation . Note that true end-to-end AI drug discovery platforms with proprietary biological datasets, closed-loop wet-lab automation, and clinical-stage pipelines remain fundamentally commercial. Open-source stacks excel at molecular representation, property prediction, and docking, but cannot replicate the massive proprietary data and automated experimentation of Recursion, Insilico, or XtalPi.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Drug discovery tools must comply with applicable regulations (FDA, EMA, ICH guidelines) and institutional review requirements. Computational predictions require experimental validation before clinical application.

- Self-hosted open-source solutions require proper infrastructure, domain expertise in cheminformatics and structural biology, and ongoing maintenance. Model validation and benchmark methodology are critical for reliable results.

- The open-source ecosystem provides strong molecular representation, property prediction, and docking foundations, but proprietary biological datasets and automated wet-lab validation remain primarily a commercial offering.



---



**Made for computational chemists, drug discovery researchers, structural biologists, and AI/ML engineers in pharma.**  

Let's make drug discovery AI more open, transparent, and reproducible.
