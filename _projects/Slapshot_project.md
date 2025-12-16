---
layout: page
title: Slapshot Dynamic Analysis
description: Structural Analysis
img: assets/img/Slapshot_still_FEA.jpg
importance: 1
category: Course Projects
related_publications: false
---
###### Jan. 2025 - May 2025
<br><br>

### Overview:

##### Design Requirements:
- Approximate hockey stick material properties for simplified model
- Model slapshot dynamics
- Find velocity vs. stiffness relationship


##### Outcomes:
- Created a model to study parameters of a slapshot for low computational cost
- 28% error in time to peak velocity, 45% error in peak velocity resulting from simplifications.


##### Technical Skills:
- Abaqus FEA


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Slapshot_still_FEA.jpg" title="Drivetrain physical assembly photo" 
        caption="Timestep from a slapshot dynamic simulation, with the beam element visualized as a line."
        class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Slapshot_still.png" title="Drivetrain CAD render"
        caption="Deformation of an actual slapshot for comparison (from <a href='https://www.youtube.com/watch?v=IsCdywftyok'>SmarterEveryDay</a>)."
        class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### Results:

<div class="row">
 <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/BladeStickVelocity.png"
      title="Speed vs time accel data"
      class="img-fluid rounded z-depth-1"
    %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid
      loading="eager"
      path="assets/img/BladeTimeVelocity_litterature.png"
      title="Speed vs Gear for different gear ratios plot"
      class="img-fluid rounded z-depth-1"
    %}
  </div>
</div>
<div class="caption">
    Blade (stick tip) velocity over time (right), showing similar velocity behavior in the impact regime (0.05 - 0.1s) of the <a href='https://www.researchgate.net/figure/elocity-of-the-hand-the-stick-and-the-puck-when-the-stick-struck-the-puck-directly_fig6_322093518'>litterature</a> result (right).
</div>

<div class="row justify-content-center">
  <div class="col-md-6 mt-3 mt-md-0">
    {% include figure.liquid
       loading="eager"
       path="assets/img/BladeVelocityVStiffness.png"
       caption="Stick tip velocity magnitude vs. stick stiffness (represented as Young’s Modulus), showing a faster shot for a more flexible stick under a 100 N max applied load."
       title="Torque Vs RPM plot"
       class="img-fluid rounded z-depth-1 mx-auto d-block"
    %}
  </div>
</div>