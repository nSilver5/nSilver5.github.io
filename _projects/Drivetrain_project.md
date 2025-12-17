---
layout: page
title: Drivetrain
description: Brown Formula Racing – Lead Drivetrain Engineer
img: assets/img/Drivetrain_explodedView.png
importance: 1
category: Student Design Team
related_publications: false
---
###### May 2023 - May 2024

---

### Overview:

##### Design Requirements:
- Minimize weight
- Optimize torque and speed tradeoff (for faster lap times)

##### Outcomes:
- 30% mounting weight reduction
- 12% higher finishes in acceleration and endurance events

##### Technical Skills:
- CAD
- FEA
- CAM & CNC

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/drivetrain_render.png" title="Drivetrain CAD render"
        caption="Drivetrain SolidWorks render."
        class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Drivetrain_assembly.jpg" title="Drivetrain physical assembly photo" 
        caption="Removable portion of physical drivetrain assembly."
        class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row justify-content-center">
  <div class="col-md-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/MountedDrivetrainCloseup.jpg" title="drivetrain on car photo"
        caption="Closeup of mounted drivetrain assembly."
        class="img-fluid rounded z-depth-1" style="transform: rotate(90deg);"%}
    </div>
</div>

---

### Gear Ratio Selection:

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/SpeedVsGear.png"
      title="Speed vs Gear for different gear ratios plot"
      caption="Max speed per gear for a range of rear sprocket tooth counts. The selected 40/11 ratio achieves a 70 MPH top speed."
      class="img-fluid rounded z-depth-1"
    %}
  </div>

  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/Accel_SpeedVsTime.png"
      title="Speed vs time accel data"
      caption="Acceleration event race data aligning with the theoretical 70 MPH top speed."
      class="img-fluid rounded z-depth-1"
    %}
  </div>

  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/Accel_EngineSpeedVsTime.png"
      title="Engine Speed vs time accel data"
      caption="Acceleration event race data showing redline reached at event completion."
      class="img-fluid rounded z-depth-1"
    %}
  </div>
</div>

<div class="row justify-content-center">
  <div class="col-md-6 mt-3 mt-md-0">
    {% include figure.liquid
       loading="eager"
       path="assets/img/TorqueVsRPM.png"
       caption="Engine torque curve plotted with torques calculated to reach traction limit in 1st & 2nd gear – showing effective gear ratio for engine to reach the traction limit torque."
       title="Torque Vs RPM plot"
       class="img-fluid rounded z-depth-1 mx-auto d-block"
    %}
  </div>
</div>

---

### Structural Analysis:

<div class="row">
  <div class="col-md-6 mt-3 mt-md-0 text-center">
    {% include figure.liquid
       loading="eager"
       path="assets/img/VonMisesFEA.png"
       title="von Mises FEA visual"
       caption="von Mises stress distribution from FEA analysis."
       class="img-fluid rounded z-depth-1 equal-size"
    %}
  </div>

  <div class="col-md-6 mt-3 mt-md-0 text-center">
    {% include figure.liquid
       loading="eager"
       path="assets/img/DisplacementFEA_2.jpeg"
       title="Displacement FEA visual"
       caption="Displacement field from FEA analysis."
       class="img-fluid rounded z-depth-1 equal-size-cropped"
    %}
  </div>
</div>

---

### Manufacturing:

<div class="row">
  <div class="col-md-6 mt-3 mt-md-0 text-center">
        {% include figure.liquid
           loading="eager"
           path="assets/img/EDiskDrawing.png"
           title="Eccentric Disk Drawing"
           caption="Critical to function dimensioned drawing of the eccentric disk."
           class="img-fluid rounded z-depth-1"
        %}
    </div>
  <div class="col-md-6 mt-3 mt-md-0 text-center">
        {% include figure.liquid
           loading="eager"
           path="assets/img/Machined_pillowblock_2.jpeg"
           title="Machined pillowblock and eccentric disk"
           caption="In-house CNC-milled differential mount and eccentric disk, designed and manufactured with tight tolerances for a precision press-fit bearing and snap ring."
           class="img-fluid rounded z-depth-1 img-crop-center"
        %}
    </div>
</div>

<div class="row">
  <div class="col-md-6 mt-3 mt-md-0 text-center">
        {% include figure.liquid
           loading="eager"
           path="assets/img/SprocketOnMill.jpg"
           title="Eccentric Disk Drawing"
           class="img-fluid rounded z-depth-1"
        %}
    </div>
  <div class="col-md-6 mt-3 mt-md-0 text-center">
        {% include figure.liquid
           loading="eager"
           path="assets/img/MachinedSprocket.jpg"
           title="Machined pillowblock and eccentric disk"
           class="img-fluid rounded z-depth-1 img-crop-center"
        %}
    </div>
</div>
<div class="caption">
    CNC machined 33 tooth sprocket with manual lathe taper designed for gear ratio testing.
</div>

<div class="row">
  <div class="col-md-6 mt-3 mt-md-0 text-center">
        {% include figure.liquid
           loading="eager"
           path="assets/img/SprocketAdaptor_drawing.png"
           title="Eccentric Disk Drawing"
           caption="Critical to function dimensioned drawing of the sprocket adaptor to splined differential."
           class="img-fluid rounded z-depth-1"
        %}
    </div>
  <div class="col-md-6 mt-3 mt-md-0 text-center">
        {% include figure.liquid
           loading="eager"
           path="assets/img/SprocketAdaptor.jpg"
           title="Machined pillowblock and eccentric disk"
           caption="Sprocket adaptor in house CNC contour and wire EDM spline."
           class="img-fluid rounded z-depth-1 img-crop-center"
        %}
    </div>
</div>

<div class="row">
  <div class="col-md-6 mt-3 mt-md-0 text-center">
        {% include figure.liquid
           loading="eager"
           path="assets/img/Sprocket_w_adaptor.jpg"
           title="Eccentric Disk Drawing"
           class="img-fluid rounded z-depth-1"
        %}
    </div>
  <div class="col-md-6 mt-3 mt-md-0 text-center">
        {% include figure.liquid
           loading="eager"
           path="assets/img/Sprocket_w_adaptor_Back.jpg"
           title="Machined pillowblock and eccentric disk"
           class="img-fluid rounded z-depth-1 img-crop-center"
        %}
    </div>
</div>
<div class="caption">
    Sprocket adaptor fastened in black anodized sprocket.
</div>

<div class="row justify-content-center">
  <div class="col-md-6 mt-3 mt-md-0">
    {% include figure.liquid
       loading="eager"
       path="assets/img/Drivetrain_fullCar.jpeg"
       caption="Full car image showing the finished drivetrain in use, with black anodized aluminum components."
       title="Torque Vs RPM plot"
       class="img-fluid rounded z-depth-1 mx-auto d-block"
    %}
  </div>
</div>