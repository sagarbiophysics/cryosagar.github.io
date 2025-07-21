---
title: "An approach for coherent periodogram averaging of tilt-series data for improved contrast transfer function estimation"
collection: publications
category: manuscripts
permalink: /publication/2025-05-01-An-approach-for-coherent-periodogram-averaging-of-tilt-series-data-for-improved-contrast-transfer-function-estimation
date: 2025-05-01
venue: 'FEBS Open Bio'
paperurl: 'https://onlinelibrary.wiley.com/doi/abs/10.1002/2211-5463.70050'
citation: ' Sagar Khavnekar,  William Wan, &quot;An approach for coherent periodogram averaging of tilt-series data for improved contrast transfer function estimation.&quot; FEBS Open Bio, 2025.'
excerpt: 'Here we describe the underlying algorithm and methods for tiltCTF'
---
Cryo-electron microscopy (cryo-EM) has become an indispensable technique for determining three-dimensional structures of biological macromolecules. A critical aspect of achieving high-resolution cryo-EM reconstructions is accurately determining and correcting for the microscope&apos;s contrast transfer function (CTF). The CTF introduces defocus-dependent distortions during imaging; if not properly accounted for, the CTF can distort features in and limit the resolution of 3D reconstructions. For tilt-series data used in cryo-electron tomography (cryo-ET), CTF estimation becomes even more challenging due to the tilt of the specimen, which introduces a defocus gradient across the field of view, as well as the low dose and signal in individual tilt images. Here, we describe a simple algorithm to improve the accuracy of CTF estimation of tilted images by leveraging the tilt-series alignment parameters determined for tomographic reconstruction to explicitly account for the tilted specimen geometry. In brief, each tilt image is divided into patches, each of which are then stretched according to their defocus shift. These are then summed to provide a coherent power spectrum at the tilt axis, which can then be used in standard CTF estimation algorithms. This uses all the data in each image to enhance the visibility of Thon rings, thereby improving high-resolution CTF estimation and subsequent enhancements in the resolution of subtomogram averages.

[Access paper here](https://onlinelibrary.wiley.com/doi/abs/10.1002/2211-5463.70050){:target="_blank"}
