---
layout: page
title: project 3
description: Computational Modeling of tritium transport in the anterior
img: assets/img/EyeProject.png
importance: 3
category: work
---

MODELLING OF AQUEOUS HUMOR CIRCULATION IN THE EYE

    ---
    School: University of Ottawa
    Project: Modeling of aqueous humor circulation in the eye
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/EyeGeo.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/EyeMesh.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
     On the left, two-dimensional geometry for the AH domain. Right, unstructured grid with 27,872 nodes to discretize PA1 geometry.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/AHPA2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/PredictedTriAccumulation.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    One the left, predicted AH velocity for the axisymmetric PA2 geometry. On the right, tritium accumulation dynamics in the anterior eye segments for the iris diameter PA1 = 1.85 mm (left) and PA2 = 5.0 mm (right).
</div>

In the present work, a physics-based model for the prediction of tritium transport due to the AH circulation has been developed. Preliminary computational analyses have been performed to demonstrate the capabilities of the model and to provide insight into the important factors that need to be considered in this problem. The geometry considered for the simulations resembles the typical dimensions encountered in healthy human eyes. It should be recognized however that variations among population characteristics or due to other conditions, some of which are dictated by pure eye physiology (e.g., the size of iris opening), would introduce deviations from the dimensions used and consequently, certain differences in the predicted flow. These aspects would need to be considered when validating Tritiated water (HTO) dispersion.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/AHcirculation.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/AHPA2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
     One the left, predicted AH velocity obtained with the PA1 geometry under planar-flow assumption (left); AH flow speed profile predicted at two cross sections in the narrow gap between the lens and the iris (right). On th right, predicted AH velocity for the axisymmetric PA2 geometry.
</div>





