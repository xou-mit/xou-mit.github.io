---
layout: page
title: Synthetic Gaia DR3 surveys from the FIRE cosmological simulations of Milky-Way-mass galaxies
description: Updated synthetic surveys based on the high-resolution cosmological simulations, providing a crucial tool for validating observational results and exploring dark matter distribution in the Milky Way
img: assets/img/synthetic_survey_m12i.png
importance: 2
category: Dynamics
related_publications: true
---

The Gaia mission has dramatically transformed our understanding of the Milky Way by providing unprecedented kinematic data for over a billion stars. 
This data allowed for groundbreaking discoveries, such as the identification of major galactic merger events like the Gaia-Sausage/Enceladus and Kraken, the creation of a 3D dust map of the Milky Way, and detailed studies of the Galactic disk's history and dynamics. 
These advances have provided deeper insights into the dynamics of the Galaxy, including extending measurements of its circular velocity to greater distances.

To complement these rich observational data sets, synthetic catalogs generated from cosmological simulations have become invaluable for testing analysis tools and verifying our ability to recover the true properties of the Milky Way. For instance, the Ananke framework, introduced by Sanderson+2020, produces synthetic surveys based on the Latte suite of simulations. 
These surveys have been widely used to study the dynamics of the Milky Way, estimate the detectability of stellar streams, and even train machine learning models to create stellar catalogs, helping discover structures like the Nyx stream. 
Synthetic surveys provide a crucial link between the theoretical predictions of galaxy formation and the actual data collected by missions like Gaia.

In this work, we present an updated set of synthetic Gaia DR3 surveys based on the Feedback in Realistic Environments (FIRE) project. 
These simulations model Milky Way analogs with high precision, capturing key baryonic processes such as star formation and metal enrichment, as well as the galaxy’s merger history in a cosmological context. 
The new synthetic surveys build upon the previous Gaia DR2 versions by incorporating improved stellar isochrones, enhanced error models for radial velocity and proper motion, and a larger sample of stars with radial velocity measurements. 
By offering more accurate representations of the observational uncertainties present in DR3, these updated synthetic surveys provide a more reliable comparison for studies of the Milky Way’s structure and kinematics.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/synthetic_survey_m12i.png" title="Image of the FIRE simulation in the synthetic survey" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Synthetic survey image from the FIRE simulation of the Milky Way analog galaxy m12i, showing the distribution of stars in the disk and halo.
</div>

The synthetic DR3 surveys are made available to the community, allowing researchers to test their analysis pipelines before applying them to real Gaia data. 
This is particularly useful for studies involving the dynamic properties of the Milky Way, such as investigations of the Galaxy’s rotation curve, which have revealed potential discrepancies in the dark matter distribution. 
By comparing synthetic and observational data, researchers can quantify how Gaia's selection effects might impact their measurements, improving the accuracy of their findings.

The FIRE simulations provide publicly available data on star particles, satellite galaxies, and halos, offering a comprehensive framework for understanding the Milky Way as a whole. 
With these tools, the community can explore not only the stellar components visible through Gaia, but also the underlying dark matter structures that govern the motion and evolution of the stars. 
The availability of such detailed synthetic data enhances our ability to interpret real observations and pushes the boundaries of what we can learn about the formation and evolution of the Milky Way.

