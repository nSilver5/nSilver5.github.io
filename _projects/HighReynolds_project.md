---
layout: page
title: Airfoil Analysis and Testing
description: High Reynolds Number Flows
img: assets/img/RE_cr001sm.png
importance: 3
category: Course Projects
related_publications: false
---
###### Jan 2024 - May 2024

---

### Overview:

##### Design Requirements:
- Use theory to align simulation and experimental data
- Maximizes aerodynamic efficiency
- Maximize lift at max efficiency


##### Outcomes:
- Used finite airfoil adjustments to improve simulation and experiment agreement
- 2.4282 coefficient of lift at 3.4927 efficiency (2nd best in class)


##### Technical Skills:
- XFLR5 (GUI wrapper of XFOIL) 
- Wind tunnel testing
- Matlab
- SolidWorks CAD


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/RE_S1210.png" title="Drivetrain CAD render"
        caption="S1210 airfoil profile under study (from <a href='http://airfoiltools.com/'>AirfoilTools.com</a>)."
        class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/RE_cr001sm.png" title="Drivetrain physical assembly photo" 
        caption="CR001SM airfoil profile under study (from <a href='http://airfoiltools.com/'>AirfoilTools.com</a>)."
        class="img-fluid rounded z-depth-1" %}
    </div>
</div>

---

### Simulation:

<div class="row justify-content-center">
  <div class="col-md-6 mt-3 mt-md-0">
    {% include figure.liquid
       loading="eager"
       path="assets/img/RE_XFLR5_plot.png"
       caption="Image of XFLR5 interface, comparing lift coefficient vs. angle of attack for different airfoil profiles."
       title="Torque Vs RPM plot"
       class="img-fluid rounded z-depth-1 mx-auto d-block"
    %}
  </div>
</div>

---

### Experiments and Analysis:

<div class="row justify-content-center">
  <div class="col-md-6 mt-3 mt-md-0">
    {% include figure.liquid
       loading="eager"
       path="assets/img/RE_WindTunnel.jpg"
       caption="CR001SM airfoil during wind tunnel testing, using a strain gauge and angle gauge to measure axial and normal forces over a range of angles of attack."
       title="Wind Tunnel Photo"
       class="img-fluid rounded z-depth-1 mx-auto d-block"
    %}
  </div>
</div>

<div class="row justify-content-center">
  <div class="col-md-6 mt-3 mt-md-0">
    {% include figure.liquid
       loading="eager"
       path="assets/img/RE_SimVExperiment.png"
       caption="Comparison of experimental and simulation data of the infinite airfoil S1210 profile and with an adjustment for finite airfoils. Agreement discrepancies coming from infinite approximations in simulations and errors from airfoil mounting brackets and possible wind tunnel wall effects."
       title="Torque Vs RPM plot"
       class="img-fluid rounded z-depth-1 mx-auto d-block"
    %}
  </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/RE_efficiencyPlot.png" title="Drivetrain CAD render"
        caption="Airfoil efficiency plots from wind tunnel data from S1210 airfoil."
        class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/RE_airfoil_efficiencyPlotCR.png" title="Drivetrain physical assembly photo" 
        caption="Airfoil efficiency plots from wind tunnel data from CR001SM airfoil."
        class="img-fluid rounded z-depth-1" %}
    </div>
</div>