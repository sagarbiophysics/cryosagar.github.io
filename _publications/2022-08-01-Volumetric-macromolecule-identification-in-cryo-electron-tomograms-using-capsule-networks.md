---
title: "Volumetric macromolecule identification in cryo-electron tomograms using capsule networks"
collection: publications
category: manuscripts
permalink: /publication/2022-08-01-Volumetric-macromolecule-identification-in-cryo-electron-tomograms-using-capsule-networks
date: 2022-08-01
venue: 'BMC Bioinformatics'
paperurl: 'https://doi.org/10.1186/s12859-022-04901-w'
citation: ' Noushin Hajarolasvadi,  Vikram Sunkara,  Sagar Khavnekar,  Florian Beck,  Robert Brandt,  Daniel Baum, &quot;Volumetric macromolecule identification in cryo-electron tomograms using capsule networks.&quot; BMC Bioinformatics, 2022.'
---
Despite recent advances in cellular cryo-electron tomography (CET), developing automated tools for macromolecule identification in submolecular resolution remains challenging due to the lack of annotated data and high structural complexities. To date, the extent of the deep learning methods constructed for this problem is limited to conventional Convolutional Neural Networks (CNNs). Identifying macromolecules of different types and sizes is a tedious and time-consuming task. In this paper, we employ a capsule-based architecture to automate the task of macromolecule identification, that we refer to as 3D-UCaps. In particular, the architecture is composed of three components: feature extractor, capsule encoder, and CNN decoder. The feature extractor converts voxel intensities of input sub-tomograms to activities of local features. The encoder is a 3D Capsule Network (CapsNet) that takes local features to generate a low-dimensional representation of the input. Then, a 3D CNN decoder reconstructs the sub-tomograms from the given representation by upsampling.

[Access paper here](https://doi.org/10.1186/s12859-022-04901-w){:target="_blank"}
