---
title: "GiganticNVS: Gigapixel Large-Scale Neural Rendering With Implicit Meta-Deformed Manifold"
collection: publications
category: manuscripts
permalink: /publication/2023-10-gigaticnvs-journal
excerpt: 'This paper is about the 3D vision and 3D reconstruction.'
date: 2023-10-09
venue: 'IEEE Transactions on Pattern Analysis and Machine Intelligence'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10274871'
bibtexurl: 'https://scholar.googleusercontent.com/scholar.bib?q=info:UPNg9odGySwJ:scholar.google.com/&output=citation&scisdr=Cl9MYPLIELfLyxU6RSk:AFtJQiwAAAAAaaA8XSn2mD3X1yK64rU7z0g_WAc&scisig=AFtJQiwAAAAAaaA8XbYsDrJ84HSKPPpsVDc3djg&scisf=4&ct=citation&cd=-1&hl=zh-CN'
citation: 'Wang, G., Zhang, J., Zhang, K., Huang, R., & Fang, L. (2023). Giganticnvs: Gigapixel large-scale neural rendering with implicit meta-deformed manifold. IEEE Transactions on Pattern Analysis and Machine Intelligence, 46(1), 338-353.'
---
## Abstract:

The rapid advances of high-performance sensation empowered gigapixel-level imaging/videography for large-scale scenes, yet the abundant details in gigapixel images were rarely valued in 3d reconstruction solutions. Bridging the gap between the sensation capacity and that of reconstruction requires to attack the large-baseline challenge imposed by the large-scale scenes, while utilizing the high-resolution details provided by the gigapixel images. This paper introduces GiganticNVS for gigapixel large-scale novel view synthesis (NVS). Existing NVS methods suffer from excessively blurred artifacts and fail on the full exploitation of image resolution, due to their inefficacy of recovering a faithful underlying geometry and the dependence on dense observations to accurately interpolate radiance. Our key insight is that, a highly-expressive implicit field with view-consistency is critical for synthesizing high-fidelity details from large-baseline observations. In light of this, we propose meta-deformed manifold, where meta refers to the locally defined surface manifold whose geometry and appearance are embedded into high-dimensional latent space. Technically, meta can be decoded as neural fields using an MLP (i.e., implicit representation). Upon this novel representation, multi-view geometric correspondence can be effectively enforced with featuremetric deformation and the reflectance field can be learned purely on the surface. Experimental results verify that the proposed method outperforms state-of-the-art methods both quantitatively and qualitatively, not only on the standard datasets containing complex real-world scenes with large baseline angles, but also on the challenging gigapixel-level ultra-large-scale benchmarks.
