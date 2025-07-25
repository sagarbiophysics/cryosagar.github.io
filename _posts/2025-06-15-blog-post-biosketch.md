---
title: 'Tracing an Unconventional Path: My Journey in Science...<em>So Far</em>'
date: 2025-06-15
permalink: /posts/2025/06/blog-post-biosketch/
tags:
  - biosketch
  - journey
  - about
---

<em>This is a reflection on my scientific journey, how a physicist turned structural biologist came to pioneer large-scale in situ visual proteomics. It traces the path, methods, and ideas that shaped my scientific approach and led to [RNAcartography](/initiatives/1-RNAcartography).


{% include toc %}
----

Early Days: Foundations in Biophysics and Structural Biology
----
My academic training began as an undegraduate in physics which turned towards structural biology driven by curiosity of the complexity of biology. During my formative research years in Mumbai, I used macromolecular X-ray crystallograohy and molecular dynamics (MD) simulations to study urea-induced protein unfolding. Following which we also probed the conformational dynamics of folding chaperones like PEB4. In parallel, I investigated DNA–protein assembly of the Bacillus RecU Holliday junction resolvase system. Using a complementary approach combing macromolecular X-ray crystallography, SAXS, and MD simulations, we revealed how RecU’s flexible N-terminal region engages DNA. These early research projects deepened my appreciation for biomolecular structure and dynamics, providing strong foundations in both computational and experimental structural biology. 

Supported by a Swiss Government Excellence Fellowship, I next worked in Geneva on structural biology of chromatin architecture. Here I combined biochemistry and molecular biology with X-ray crystallography and cryo-EM in order to dissect the architecture of chromatin-associated machinery. 

These early research projects deepened my appreciation for biomolecular structure and dynamics, providing a strong grounding in both computational and experimental structural biology. During these foundational years, I cultivated a rigorously quantitative and interdisciplinary approach that I have carried into all my future work. It was during this period that I became convinced that to truly understand gene-regulation machinary consisting of nucleic acid-protein complexes, one must observe them in their native cellular environment. This conviction led me to cryo-electron tomography (cryo-ET), which has since become the cornerstone of my scientific path.

Advancing Cryo-ET: Methodological Innovation for In Situ Discovery
----
At the Max Planck Institute of Biochemistry, supported by a competitive IMPRS-LS Ph.D. fellowship, I focused on advancing cryo-ET to visualize gene-expression machinery in situ. My first major project was on ribosome assembly in the nucleolus. I joined this work at a critical late stage, when the project required robust data processing to reach biological conclusions. I implemented and extended quantitative classification workflow within our inhouse subtomofram averaging package STOPGAP. Ths allowed us to uncover a radial gradient of assembly states progressing outward from the nucleolar core. This spatial maturation gradient, which emerged only after robust and quantitative classification, provided in situ molecular evidence for phase-separated ribosome biogenesis. This taught me how powerful it is to pair cryo-ET with rigourous computational analysis, and how enabling technology often makes new biology visible.

Driven by this early impact, I continued to make cryo-ET more accessible. I co-developed TOMOMAN, a modular pipeline for cryo-ET data preprocessing, and STOPGAP, a open-source software for template matching, subtomogram averaging, and classification. In addition, I pioneered tilt-series refinment approach within the TOMOMAN-STOPGAP framework for improving subtomogram averaging resolution. These tools, built to serve the scale and demands of our own projects, are now widely used to streamline cryo-ET analysis across labs. 

Building on this expertise in computational cryo-ET, I led timely efforts to integrate AI into cryo-ET. My contributions involved translating insights from developments of TOMOMAN-STOPGAP framework into the AI framework and helping bridge domains. In early efforts, I collaborated on deep-learning-based particle picking methods, applying our template matching expetise to help design AI framework. Building on this experience, I initiated and led a collaboration to adapt the cryoDRGN framework for single particle cryo-EM to cryo-ET and subtomogram averaging. This resulted in cryoDRGN-ET, a deep recosntructing generative network for analyzing continuous conformational heterogeneity. In early applications, it recovered known ribosome elongation states and revealed continuous motions of complexes such as fatty acid synthase, directly in native context. These projects strengthened my ability to navigate between traditional image processing and modern machine learning, an intersection that I believe will be central to tackling transient and rare macromolecular machines in their native context.

In parallel with computational advances, I developed experimental methods to push the limits of cellular cryo-ET. I focused on challenges in sample preparation and data acquisition. I optimized cryo-focused ion beam (cryo-FIB) milling of frozen vitrified cells to mitigate specimen charging allowing  sub-nanometer resolution subtomogram averaging from a single lamella. I also pioneered a ‘multishot tomography’ scheme to record multiple tilt-series in parallel, dramatically boosting data acquisition throughput without compromising the data quality. 

These experimental and computational advances were foundational to conception of a large scale cryo-ET effort with an ambition to bring big data approach to visual proteomics with cryo-ET. I initiated and led multi-institution, multi-lab visual proteomics efforts with Chlamydomonas reinhardtii, resulting in a dataset of ~1800 curated tomograms. This resource has yielded subnanometer resolution averages of Ribosomes, Nucleosomes, Rubisco, and numerous other complexes including one of the first in situ structural systems biology view of respiratory chain. In addition, in collaboration with the EMPIAR and the Chaz Zuckerberg Initiative this data is readily available for downstream analysis, pioneering open data and collaborative inititives in cryo-ET. This ‘one-of-its-kind’ effort has shown collaborative big data approach in cryo-ET no only advances development of new methods but also offers new and rare biological insights. Coordinating this collaborative effort honed my leadership skills and reinforced my belief that open and community-driven science accelerates discovery.

Bridging Academia and Industry
----
During my tenure at the Max Planck institute of Biochemistry, I collaborated closely with Thermo Fisher Scintific to co-develop next-generation cryo-ET instrumentation. Working directly with engineers, I helped integrate advanced energy filter into cryo-TEM, optimize next-generation direct electron detectors for tomography, and implement cryo-FIB milling workflows to optimise lamellae preparation using both galium and plasma sources. These co-development efforts directly improved data quality and consistency and enabled cryo-ET on more challenging cell types and subcellular regions. This hands-on experience with microscope design not only advanced our projects but also broadened my technical expertise beyond the standard academic toolkit, including emerging techniques like 4D-STEM imaging and automated microscope control through SerialEM scripting.

In late 2023, I formally joined Thermo Fisher as a Research Scientist in their Electron Microscopy division, continuing and expanding upon the collaborations from the Max Plack Institute of Biochemistry. This industry experience has sharpened my ability to translate between academic research needs and engineering solutions. Far from being a detour, it has deepened my understanding of the technology underpinning high-end microscopy and reinforced my collaborative instincts. Working at the interface of academia and industry has further prepared me to lead an independent lab that thrives on both innovation and practical impact.

Teaching and Mentoring
----
Throughout my career, teaching and mentorship have been natural extensions of my passion for science. I have taught and mentored at many levels, from co-instructing an undergraduate molecular biology practical course at the University of Geneva to serving as an instructor in international cryo-ET training programs. In 2022, I taught at an EMBO practical course on cryo-electron microscopy at EMBL Heidelberg. The following year, I led a subtomogram averaging workshop at the SPACET cryo-EM course in Prague and delivered a lecture on cryo-ET fundamentals for the Human Technopole graduate program in Milan. I am now co-organizing the inaugural Rio School of CryoET in 2025, reflecting my ongoing commitment to training the next generation. These engagements have allowed me to support and inspire young scientists beyond my host institutions.

Within my host institutions, I have prioritized mentoring junior scientists by organizing regular in-house cryo-ET workshops during my Ph.D. and training new researchers in advanced cryo-ET techniques and computational analysis at Thermo Fisher. I have also taken on leadership roles beyond the lab, such as serving on organizing committees for student retreats and symposia, and engaging in science outreach. These experiences have strengthened my ability to communicate and lead, preparing me to cultivate a culture of learning in my own lab.

Towards Independence
----
My scientific path has been far from linear. This breadth of experience has fostered a deep scientific maturity, strong leadership skills, and an innovative mindset that prepare me well to establish and lead my own research group. I have grown from a student captivated by molecular structures into a scientist who develops tools, drives large-scale collaborations to understand biology at a systems level. 

My diverse contributions from impactful peer-reviewed studies to leading multi-institution projects, developing open-source software, and creating community data resources reflect a combination of technical depth across advanced experimental and computational methods, interdisciplinary agility, and a sustained commitment to open, team-driven science. Along the way, my work has also earned broad peer recognition. I have been invited to present at leading institutes, at international conferences, and at specialized cryo-ET workshops, which underscore my standing in the field. Far from a drawback, the unconventional nature of my journey has been a key strength, equipping me to adapt and innovate at each step. Each project has been anchored in the belief that new tools make new biology possible. I am now eager to investigate RNA-centered assemblies in their full in situ complexity as an independent group leader and to build a research program that embodies the spirit of innovation and collaboration that has defined my path.

_Epilogue_
----
<em>
As I reflect on this journey, I’m reminded that a scientific path need not follow a straight line to have an impact. Mine has been shaped by curiosity, collaboration, and conviction more than by convention. What holds it all together is not a tidy structure, but a clear and evolving vision; one that bridges disciplines, adapts to new challenges, and seeks to understand RNA biology in its native context.

<em>
I share this as encouragement for those navigating nonlinear or unconventional routes in science, your story matters. Coherence can emerge from vision, resilience, and the courage to build something new. If this reflection resonates, I hope it inspires you to explore bold questions, take creative risks, and carve your own paths, just as I continue to carve mine through [RNAcartography](/initiatives/1-RNAcartography) and [beyond](/initiatives/2-openemage).