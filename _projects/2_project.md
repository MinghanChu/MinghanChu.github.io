---
layout: page
title: project 2
description: Model-form uncertainty quantification for an SD7003 airfoil
img: assets/img/Triangle.png
importance: 2
category: work
giscus_comments: true
---

The focus of the study is to advance our understanding of the performance of the physics-based uncertainty quantification approach on two different transitional flow scenarios: a flat plate and a SD7003 airfoil.

    ---
    School: Queen's University
    Project: Model-form uncertainty quantification of Reynolds-averaged Navier–Stokes modeling of flows over an SD7003 airfoil
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/SSTLM_contour.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/SSTLM_cf.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
     On the left, contours of streamwise mean velocity over a flat plate using the RANS-based transition model by Langtry and Menter. Right, distribution of skin friction coefficient over a flat plat.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/AnisotropyStates.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Anisotropy states for x/c = 0.15; 0.2; 0.3; 0.4; 0.5, and 0.6 on both the barycentric and Lumley’s invariant maps. (a) and (c): RANS-based transition model by Langtry and Menter (Tu = 0.03%); (b) and (d): in-house DNS. Note that anisotropy states are painted based on the distance from the wall surface.
</div>

It is well known that the Boussinesq turbulent-viscosity hypothesis can introduce uncertainty in predictions for complex flow features such as separation, reattachment, and laminar-turbulent transition. This study adopts a recent physics-based uncertainty quantification (UQ) approach to address such model-form uncertainty in Reynolds-averaged Naiver–Stokes (RANS)simulations. Thus far, almost all UQ studies have focused on quantifying the model-form uncertainty in turbulent flow scenarios. The focus of the study is to advance our understanding of the performance of the UQ approach on two different transitional flow scenarios: a flat plate and a SD7003 airfoil, to close this gap. For the T3A (flat-plate) flow, most of the model-form uncertainty is concentrated in the laminar-turbulent transition region. For the SD7003 airfoil
flow, the eigenvalue perturbations reveal a decrease as well as an increase in the length of the separation bubble. As a consequence, the uncertainty bounds successfully encompass the reattachment point. Likewise, the region of reverse flow that appears in the separation bubble is either suppressed or bolstered by the eigenvalue perturbations. This is the first successful RANS UQ study for transitional flows.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/Perturb_contour.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/perturb_uv.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, contours of initial transient behavior of instantaneous mean streamwise velocity for baseline and eigenvalue perturbations (1c and 3c) at different times: T0 = 0.1; T1 = 0.13; T2 = 0.15; T3 = 0.17. Streamlines are superimposed on the plot to capture the vortex shedding process. Tu = 0.03%. Right, Profile of normalized Reynolds shear stress along the suction side of the SD7003 airfoil (geometry depicted by gray line): from left to right are a, b, c, d, e, f for x/c = 0.15, 0.2, 0.3, 0.4, 0.5, and 0.6, respectively. Displayed are uncertainty bounds for eigenvalue perturbations with uniform value of &Delta = 1 at Tu = 0:03%. Baseline prediction is provided for reference.
</div>





