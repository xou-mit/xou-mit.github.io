---
layout: page
title: Robust Clustering of the Local Milky Way Stellar Kinematic Substructures with Gaia eDR3
description: Identifying Substructures using HDBSCAN with measurement uncertainties factored in
img: assets/img/mw_merger_history.png
importance: 4
category: Dynamics
related_publications: true
---

In the most widely accepted model of galaxy formation, the Milky Way formed through hierarchical mergers with smaller galaxies, many of which were tidally disrupted and contributed to the stellar halo. 
Studying these accreted stars provides insight into the Milky Way's merger history and the properties of the merging galaxies, offering valuable information about galaxy evolution and dark matter distribution. 
Large-scale surveys like Gaia have been instrumental in identifying these stellar structures and streams in the Milky Way.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/mw_vel_clisters.png" title="Robust substructures identified in cylindrical velocity space" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Robust clusters (shown in different colors) identified in the cylindrical velocity space using HDBSCAN with uncertainties factored in.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/mw_iom_clisters.png" title="Robust substructures identified in integrals of motion space" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Robust clusters (shown in different colors) identified in the integrals of motion space using HDBSCAN with uncertainties factored in.
</div>

This study applies an unsupervised machine learning algorithm, Hierarchical Density-Based Spatial Clustering of Applications with Noise (HDBSCAN), to identify substructures in the Milky Way using data from Gaia eDR3. 
By incorporating uncertainties into the clustering process for the first time, we robustly identify known structures like the Gaia-Enceladus/Sausage (GSE), Sequoia, the Helmi Stream, and two globular clusters (NGC 3201 and NGC 104). 
Our approach improves the accuracy of identifying stellar members in these clusters. 
However, some structures, like Nyx, Thamnos, and Arjuna, were not recovered, highlighting the limitations of the method when constrained by the available data and orbital distance cuts. 
Our results emphasize the importance of accounting for uncertainties in machine learning applications to enhance the robustness of substructure identification in the Milky Way.



