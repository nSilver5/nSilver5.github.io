---
layout: page
title: Aerodynamics
description: Brown Formula Racing – Lead Aerodynamics Engineer
img: assets/img/AeroPackageRender.png
importance: 2
category: Student Design Team
related_publications: false
---
###### May 2024 - May 2025

---

### Overview:

##### Design Requirements:
- Minimize weight
- Tune downforce, drag & aero balance (for improved lap times)


##### Outcomes:
- 24.5% weight reduction while remaining durable
- 22.7% downforce increase, 7.2% drag reduction
- Adjustable wing to tune aero balance from 45-55% front


##### Technical Skills:
- STAR-CCM+ CFD
- SolidWorks CAD
- Composites Manufacturing


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/AeroPackageRender.png" title="Drivetrain CAD render"
        caption="SolidWorks render of aerodynamics components."
        class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/StarCCM_cadRender.png" title="Drivetrain physical assembly photo" 
        caption="STAR-CCM+ CAD render for CFD simulations."
        class="img-fluid rounded z-depth-1" %}
    </div>
</div>

---

### Simulation:

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/CorneringStreamlines.png"
      title="Speed vs Gear for different gear ratios plot"
      caption="Pressure coefficient streamlines in cornering simulations."
      class="img-fluid rounded z-depth-1"
    %}
  </div>

  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/TotalPressureScene.jpeg"
      title="Speed vs time accel data"
      caption="Total pressure coefficient front view of left diffuser, observing vortex generation and effects of inwashing from wheels."
      class="img-fluid rounded z-depth-1"
    %}
  </div>
</div>


<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/OutboardRWvelocityStreamlines.png"
      title="Speed vs Gear for different gear ratios plot"
      class="img-fluid rounded z-depth-1"
    %}
  </div>

  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/InboardRWvelocityStreamlines.png"
      title="Speed vs time accel data"
      class="img-fluid rounded z-depth-1"
    %}
  </div>
</div>
<div class="caption">
    Outboard (left) and inboard (right) velocity streamline scenes of the rear wing assisting in tuning rear wing elements. 
</div>

<div class="row justify-content-center">
  <div class="col-md-6 mt-3 mt-md-0">
    {% include figure.liquid
       loading="eager"
       path="assets/img/dmprj_example.png"
       caption="Design manager project iterating rear wing third flap angle of attack in STAR-CCM+ for CLA optimization."
       title="Torque Vs RPM plot"
       class="img-fluid rounded z-depth-1 mx-auto d-block"
    %}
  </div>
</div>

---

### Manufacturing:

<div class="row">
  <div class="col-md-6 mt-3 mt-md-0 text-center">
    {% include figure.liquid
       loading="eager"
       path="assets/img/FoamMold.jpeg"
       title="von Mises FEA visual"
       caption="High density CNC cut foam mold of rear wing main element bottom surface."
       class="img-fluid rounded z-depth-1 equal-size"
    %}
  </div>

  <div class="col-md-6 mt-3 mt-md-0 text-center">
    {% include figure.liquid
       loading="eager"
       path="assets/img/VacuumBag.jpeg"
       title="Displacement FEA visual"
       caption="Vacuum bagging diffusers."
       class="img-fluid rounded z-depth-1 equal-size-cropped"
    %}
  </div>
</div>

<div class="row justify-content-center">
  <div class="col-md-6 mt-3 mt-md-0">
        {% include figure.liquid
           loading="eager"
           path="assets/img/AeroPackageCrop.jpeg"
           title="Eccentric Disk Drawing"
           caption="Finished front and rear wing elements."
           class="img-fluid rounded z-depth-1"
        %}
    </div>
</div>

---

### Testing:

<div class="row justify-content-center">
  <div class="col-md-6 mt-3 mt-md-0">
        {% include figure.liquid
           loading="eager"
           path="assets/img/dmprj_meshStudy.png"
           title="Eccentric Disk Drawing"
           caption="CLA vs. base mesh size, one of the metrics examined in the mesh independence study."
           class="img-fluid rounded z-depth-1"
        %}
    </div>
</div>

<div class="row justify-content-center">
  <div class="col-md-6 mt-3 mt-md-0">
        {% include figure.liquid
           loading="eager"
           path="assets/img/Airfoil_Instron.png"
           title="Machined pillowblock and eccentric disk"
           caption="Intron three point bend test of hollow composite airfoil. Assessed stiffness and determined a carbon fiber weight for manufacturing."
           class="img-fluid rounded z-depth-1 img-crop-center"
        %}
    </div>
</div>

<div class="row">
<div class="col-md-6 mt-3 mt-md-0 text-center">
    {% include figure.liquid
       loading="eager"
       path="assets/img/AeroLapTimeChart.png"
       title="Displacement FEA visual"
       caption="Average lap time graph with aero on and off the vehicle."
       class="img-fluid rounded z-depth-1 equal-size-cropped"
    %}
  </div>
  <div class="col-md-6 mt-3 mt-md-0 text-center">
    {% include figure.liquid
       loading="eager"
       path="assets/img/TuftTest_Image.png"
       title="von Mises FEA visual"
       caption="Rear wing tuft testing captured by a mounted video camera."
       class="img-fluid rounded z-depth-1 equal-size"
    %}
  </div>
</div>
