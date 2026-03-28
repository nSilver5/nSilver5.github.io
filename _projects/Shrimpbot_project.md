---
layout: page
title: Shrimpbot
description: Vibrations Course & Wilhelmus Lab
img: assets/img/Shrimpbot_sketch.png
importance: 1
category: Course Projects # Research
related_publications: false
---
###### Sept. 2024 - Dec. 2024

---

### Overview:

##### Design Requirements:
- Constrain leg movement besides pivot axis with an easy to assemble, exchangeable design in fixed form factor.
- Represent shrimp leg movement with a voice coil style actuator.



##### Outcomes:
- Modular design assembled without adhesives.
- Mathematical model of system following shrimp movement.
- Implemented PID control to follow and correct swimming motion.


##### Technical Skills:
- SolidWorks CAD
- SLA 3D Printing
- Arduino IDE for microcontrollers
- Basic PID Implementation


<div class="row justify-content-center">
  <div class="col-md-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Shrimpbot_sketch.png" title="Shrimpbot labeled sketch"
        caption="Labeled sketch of system components."
        class="img-fluid rounded z-depth-1" %}
    </div>
</div>

---

### Design:

<div class="row justify-content-center">
  <div class="col-md-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ShrimpbotLabeledLegAssem.png" title="Shrimpbot Labeled CAD Assembly"
        caption="Labeled SolidWorks renders of the designed system. Includes solenoid frame, magnet housings, arms for secure pivoting, magnets for actuation and angle sensing, and a tail."
        class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/Shrimpbot_LegDWG.jpg"
      title="Shrimpbot leg drawing"
      class="img-fluid rounded z-depth-1"
    %}
  </div>

  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/Shrimpbot_MagnetPost.jpg"
      title="Shrimpbot Magnet Post Drawing"
      class="img-fluid rounded z-depth-1"
    %}
  </div>
</div>
<div class="caption">
    Keyed leg (left) and keyed post (right) SolidWorks drawings.
</div>

<div class="row justify-content-center">
  <div class="col-md-6 mt-3 mt-md-0">
    {% include figure.liquid
       loading="eager"
       path="assets/img/ShrimpbotODEmodel.png"
       caption="Schematic to determine ODE model for the system."
       title="Shrimpbot ODE model schematic"
       class="img-fluid rounded z-depth-1 mx-auto d-block"
    %}
  </div>
</div>

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/ShrimpbotSwimmingFunction.png"
      title="Shrimpbot swimming function plot"
      class="img-fluid rounded z-depth-1"
    %}
  </div>

  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/ShrimpbotCurrentFunction.png"
      title="Shrimpbot current input function"
      class="img-fluid rounded z-depth-1"
    %}
  </div>
</div>
<div class="caption">
    Metachronal swimming function (left) and necessary output current for metachronal swimming (right), as determined from the system ODE.
</div>

---

### Results:

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/PIDvideo_constantSetpoint.gif"
      title="PID video constant setpoint"
      class="img-fluid rounded z-depth-1"
    %}
  </div>

  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/PIDplot_constantSetpoint.jpg"
      title="PID video constant setpoint"
      class="img-fluid rounded z-depth-1"
    %}
  </div>
</div>
<div class="caption">
    Constant setpoint PID implementation. The measured output angle graphed above input signal, corresponding to the video above.
</div>


<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/PIDvideo_changingSetpoint.gif"
      title="PID video changing setpoint"
      class="img-fluid rounded z-depth-1"
    %}
  </div>

  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/PIDplot_changingSetpoint.jpg"
      title="PID plot changing setpoint"
      class="img-fluid rounded z-depth-1"
    %}
  </div>
</div>
<div class="caption">
    Changing setpoint PID implementation. 
</div>


<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/PIDvideo_functionSetpoint.gif"
      title="PID video function setpoint"
      class="img-fluid rounded z-depth-1"
    %}
  </div>

  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/PIDplot_functionSetpoint.jpg"
      title="PID plot function setpoint"
      class="img-fluid rounded z-depth-1"
    %}
  </div>
</div>
<div class="caption">
     Setpoint determined from the metachronal swimming function. The PID corrections are applied on top of the calculated necessary current output. 
</div>