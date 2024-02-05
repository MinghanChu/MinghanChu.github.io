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
    description: 
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

Simulation of SD7003 airfoil using the same code and transition model, comparison with our test data and/or literature.
 Comparison of location and size of LSB, laminar to turbulence transition, and other related parameters with literature.
 Use of OpenFOAM in conjunction with Wei et al transition model for flat plate, results validated



<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

=begin
The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
=end
{% endraw %}
