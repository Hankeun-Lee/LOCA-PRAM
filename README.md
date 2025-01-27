# LOCA-PRAM

LOCA-PRAM utilizes a single-frame DECODE network to localize gold nanoparticles (AuNPs) from photonic resonator absorption microscope (PRAM) images, significantly enhancing the sensitivity and dynamic range of assays used in single-molecule diagnostics.

The approach is physically grounded, as the point spread function (PSF) of PC-AuNP resonant coupled signals is empirically analyzed through direct registration of scanning electron microscope (SEM) images with PRAM images. This analysis enables the modeling of the PSF, which is then used to generate realistic training images.

The developed code guides users through the entire process, including the creation of background noise, simulation of PC-AuNP resonant coupled signals on background images, and the training and testing of the model.

This self-supervised method, built on a robust physical foundation, provides a reliable framework for validating and verifying methodologies in localizing and counting AuNPs in the context of nanoparticle-based assays.

