---
title: 'SimRev module for learning reservoir simulation in Spanish with OPM Flow'
authors:
  - name: Daniela Navarro-Perez
    orcid: 0000-0001-5775-3300
    affiliation: 1
    corresponding: true
  - name: Diego Cepeda Mansilla
    orcid: 0009-0002-0062-5054
    affiliation: 1
  - name: Sergio Pollak Mayorga
    orcid: 0009-0004-7911-6803
    affiliation: 1
  - name: Pedro Simeone Barrientos
    orcid: 0000-0003-4745-5240
    affiliation: 1
  - name: Diego Glasinovich Mansilla
    orcid: 0009-0001-5338-6723
    affiliation: 1
affiliations:
  - name: Departamento de Ingeniería Química, Universidad de Magallanes, Punta Arenas 6210427, Chile
    index: 1
date: 22 December 2025
bibliography: paper.bib
---

# Summary

SimRev is a Spanish-language learning module designed for undergraduate students and young professionals to introduce reservoir simulation using the open-source software OPM Flow and ResInsight. The module consists of five hands-on tutorials with a progressive learning curve, ranging from simple two-phase reservoir models to applied case studies involving CO₂ storage and tight gas reservoirs. The tutorials are compiled in a structured manual that explains script organization, modeling workflow, and key simulation keywords. Each tutorial includes the corresponding `.DATA` and `.RSM` files, allowing users to reproduce results, compare outputs, and gain practical experience. SimRev is freely available through an open GitHub repository, promoting accessibility, reuse, and continuous improvement.

# Statement of Need

Reservoir simulation has been a fundamental tool in reservoir exploration and development since the early expansion of the oil and gas industry [@Breitenbach1991]. Advances in computational power have enabled increasingly complex representations of geological and petrophysical systems, based on mass conservation principles and numerical methods. Today, reservoir simulation is also a critical tool for emerging energy applications, including CO₂ storage for carbon capture and storage (CCS) [@Bonto2021], underground hydrogen storage [@Huang2023], nuclear waste containment [@Kneafsey2002], and geothermal energy production [@OSullivan2001].

A typical reservoir simulation workflow involves: (1) conceptual and static modeling of geometry, layering, and rock and fluid properties; (2) numerical simulation to predict reservoir behavior under different operational scenarios; and (3) history matching of production data to refine dynamic models [@Ertekin2019]. From a thermodynamic perspective, reservoir models are commonly categorized as black-oil or compositional. Black-oil models describe oil, gas, and water phases with simplified PVT behavior, while compositional models explicitly track fluid composition as a function of pressure, temperature, and depth [@Trangenstein1989].

Despite its importance, reservoir simulation remains challenging for inexperienced users, particularly those without formal training or access to structured learning materials. Moreover, English dominates scientific and technical communication [@Tonkin2011], creating a language barrier for many learners. Existing educational resources are often limited, fragmented, or unavailable in Spanish. SimRev addresses this gap by providing a coherent, open-source, Spanish-language learning module that enables users to learn reservoir simulation concepts using free and widely adopted tools. Although the tutorials are written in Spanish, the structured input data and example files are accessible and reusable by non-Spanish speakers, facilitating future adaptations to other languages and contexts.

# SimRev Learning Module

## Story

The SimRev learning module originated from a research project led by one of the co-authors, Daniela Navarro-Perez, at the Universidad de Magallanes. The project, titled *"SimRev: explorando la multifuncionalidad en reservorios para la transición energética en Magallanes"*, aimed to establish a research and teaching line in reservoir simulation within the Chemical Engineering Department. Among its objectives, the project sought to develop simulation-based learning materials targeted at undergraduate students and other disciplines interested in reservoir simulation using open and free software tools.

## Software Selected

Two open-source software packages were selected for the module: OPM Flow and ResInsight. OPM Flow is a black-oil reservoir simulator developed by the Open Porous Media Initiative since 2009, with major contributions from SINTEF, NORCE, Equinor, TNO, and OPM-OP [@Rasmussen2021]. A key advantage of OPM Flow is its compatibility with ECLIPSE-style input files, enabling learners to acquire transferable skills applicable to both open-source and commercial simulators. Recent developments, such as Python-based benchmarking frameworks [@LandaMarban2025] and GPU-accelerated linear solvers [@Lye2025], further demonstrate the robustness and active development of the OPM ecosystem.

ResInsight is a cross-platform visualization tool developed by Ceetron Solutions in collaboration with Equinor. It enables interactive 3D visualization and post-processing of reservoir simulation results using `.EGRID` and related output files. Both OPM Flow and ResInsight are openly developed on GitHub, ensuring transparency and long-term sustainability.

## Tutorials

The SimRev module is organized into five Spanish-language tutorials that integrate theoretical concepts with practical applications. The tutorials progressively introduce users to reservoir simulation workflows, script structure, and essential modeling keywords. Each tutorial corresponds to a specific simulation scenario and is accompanied by executable input files and reference outputs. The learning objectives of the tutorials are summarized in Table 1.

During development, the tutorials were piloted by Diego Glasinovich Mansilla, an undergraduate student with a geology background currently studying chemical engineering. Through guided self-study, his feedback contributed to refining the clarity, structure, and pedagogical effectiveness of the materials. Hosting the complete module on GitHub supports open access, version control, and community-driven improvements.

# Acknowledgments

Parts of the tutorials were adapted into Spanish from teaching materials by Dr. Piroska Lorinczi, with her consent. The authors thank Antonella Ritorto and Markus Blatt for their feedback as internal reviewers. This work was financially supported by the Vicerrectoría de Investigación, Innovación y Postgrado and coordinated with the Dirección de Investigación y Creación of the Universidad de Magallanes, Chile.

# References

References are provided in the accompanying `paper.bib` file.
