---
layout: page
title: project 1
description: Separation-induced transition on an SD7003 airfoil
img: assets/img/SD7003.jpg
importance: 1
category: work
related_publications: einstein1956investigations, einstein1950meaning
---

The objective of this project is to fine-tune the RANS-based transition model, aiming to determine the optimal coefficients for the model to generate precise numerical outcomes.



    ---
    Company: Pratt & Whitney Canada
    title: project
    description: Uncertainty reduction in RANS-based transition model
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/CfCalibration.png" title="Calibration of Skin friction coefficient" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/CpCalibration.png" title="Calibration of pressure coefficient" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, calibration of Skin friction coefficient. Right, calibration of pressure coefficient.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/SD7003Model.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The development of the SD7003 model.
</div>

This project conducts simulations of the SD7003 airfoil utilizing RANS-based transition models. The outcomes, derived from a calibrated model, are compared with our in-house high-fidelity DNS and experimental data, showing a good agreement. Quantities of interest include the identification and dimensions of the laminar separation bubble (LSB), the transition from laminar to turbulent flow, as well as the skin friction coefficient and pressure coefficient.



{% endraw %}
