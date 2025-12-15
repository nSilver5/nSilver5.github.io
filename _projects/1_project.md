---
layout: page
title: Drivetrain
description: Brown Formula Racing Lead Mechanical Engineer – Drivetrain
img: assets/img/drivetrain_render.png
importance: 1
category: Student Design Team
related_publications: false
---

Design Requirements: 
- Minimize weight
- Optimize torque and speed tradeoff (for faster lap times)
Outcomes: 
- 30% mounting weight reduction
- 12% higher finishes in acceleration and endurance events
Technical Skills:
- CAD
- FEA
- CAM & CNC


To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/drivetrain_render.png" title="Drivetrain CAD render" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Drivetrain_assembly.jpg" title="Drivetrain physical assembly photo" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/drivetrain_onCar.png" title="drivetrain on car photo" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Drivetrain SolidWorks render (left) and removable portion of physical assembly (middle) and mounted assembly (right).
</div>

{% comment %}
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>
{% endcomment %}

Gear Ratio Selection:

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SpeedVsGear.png" title="Speed vs Gear for different gear ratios plot" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Accel_SpeedVsTime.png" title="Speed vs time accel data" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Accel_EngineSpeedVsTime.png" title="Engine Speed vs time accel data" class="img-fluid rounded z-depth-1" %}
    </div>
<div class="caption">
    Max speed per gear for a range of tooth numbers on the rear sprocket. The selected 40/11 gear ratio is highlighted with 70 MPH top speed. (left)
    Acceleration event race data, aligning with theoretical 70 MPH top speed. (middle)
    Acceleration event race data showing redline is reached at the completion of the event. (right)
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/TorqueVsRPM.png" title="Torque Vs RPM plot" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Engine torque curve plotted with torques calculated to reach traction limit in 1st & 2nd gear – showing effective gear ratio for engine to reach the traction limit torque.
</div>

Structural Analysis:

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/VonMisesFEA.png" title="von Mises FEA visual" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/DisplacementFEA.png" title="Displacement FEA visual" class="img-fluid rounded z-depth-1" %}
    </div>
<div class="caption">
    Static structural FEA on Left Differential Mount, with von Mises stress and deformed displacement visualizations. Forces are resolved from max engine torque. Boundary conditions are pinned mounts and eccentric disk contact.
</div>

Manufacturing:
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/EDiskDrawing.png" title="Eccentric Disk Drawing" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Machined_pillowblock.jpg" title="Machined pillowblock and eccentric disk" class="img-fluid rounded z-depth-1" %}
    </div>
<div class="caption">
    Critical to function dimensioned drawing of the eccentric disk. (left)
    In house CNC milled differential mounting and eccentric disk. (right)
</div>

{% comment %}
The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
{% endcomment %}

