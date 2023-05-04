---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
<style>body {text-align: justify}</style>
My research centers around applying data science and AI concepts in health & life sciences. I'm developing bioinformatics tools and prediction model for studying biological systems.

{% include base_path %}

AI for Structural Biology and Protein Design
------
Within the Laboratory of Biomolecular Modeling (EPFL, Group Leader: Matteo Dal Peraro), I am starting a PhD on AI models and computational methods for structural biology, with diverse applications in protein and drug design. I am especially interested by Graph Neural Networks applications and Diffusion Models to evaluate protein-protein and protein-ligand interactions, notably for antigen-specific antibody design.

Computational Drug Discovery
------
At Roche (F.Hoffmann - LaRoche), I worked within the division pRED Pharma Research and Early Development (Supervisor: Jitao David Zhang) on interpretable Graph Neural Networks to predict drug-target interactions. We built an heterogeneous GNN to predict compound-protein activities from a macro perspective with features directly compilable from compound SMILES and public protein sequences, and infered some biological understanding from causal inference.
The position has been sponsored by the internship programme “Think Tank in Innovation and Sustainability #IP2TIS”, founded by André Hoffmann.

Computational Virology
------
At the Institute of Biodiversity, Animal Health and Comparative Medicine (University of Glasgow, Group Leader: Simon Babayan), I worked on a viral host predictor in Julia. Using large genomic and ecological datasets, Babayan et al. ([Science, 2018](https://dx.doi.org/10.1126/science.aap9072)) demonstrate the possibility of predicting animal reservoirs as well as the existence and identity of arthropod vectors from viral genome sequences alone, via machine learning. Together, we rewrote the entire pipeline from the ground up in the high-performance programming language Julia, extended the scope of our models to DNA viruses and new reservoir groups and/or vector groups, added structural data, and now offer better usability with an all-in-one feature engineering and model training user interface.

Precision Medicine & Computational Virology
------
At the Department of of Biosystems Science and Engineering (ETH Zurich, Group Leader: Niko Beerenwinkel), I worked on computational methods to predict HIV mutational pathways and induced drug resistance to antiretrovirals, aiming to design optimal treatment combinations. We were especially interested on treatment change episode and how to design effective and safe treatments for patients developping drug resistance due to mutations accumulated under selective pressure.

Computational Structural Biology
------
With the Laboratory of Computational and Quantitative Biology (Sorbonne University, Group Leader: Alessandra Carbone), I worked on an evaluation of docking conformations based on graph representation learning. From a database of complete cross-docking (CC-D), and integrating extra features such as regional classification of the interface residues or non-intrinsic properties of protein chains, we evaluate and identify near-native protein-protein docking models thanks to an end-to-end deep learning architecture, using graph convolutional and attention networks.
Publication: Yasser Mohseni Behbahani, Simon Crouzet, Élodie Laine, Alessandra Carbone, Deep Local Analysis evaluates protein docking conformations with Locally oriented Cubes ([Bioinformatics 2022](https://doi.org/10.1093/bioinformatics/btac551))


Genomics
------
At the Wellcome Sanger Institute (University of Cambridge, Group Leader: Mara Lawniczak), I worked on a pangenomics exploration of Anopheles Funestus (mosquito, major vector of malaria). By building a pipeline to call short and long-range structural variation events (SVs) using several bioinformatics tools (Minimap2, Svim-asm) from high-quality assemblies, we characterized, crossed and analyzed SVs from several specimen of the species.
