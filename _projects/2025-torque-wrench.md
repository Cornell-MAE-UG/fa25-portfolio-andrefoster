---
layout: project
title: Torque Wrench
description: MAE 3270 Final Homework Assignment
technologies: [Fusion, Ansys]
image: /assets/images/cover.png

---

For the MAE 3270 Final Homework assignment, we have been instructred to design a torque wrench able to withstand a moment of 600in-lbf. Here are the results:
<br>

5.2.1 Results
<br>
<br>
A - Image(s) of CAD model. Must show all key dimensions.  
<br>
![Figure 1: Dimensioned CAD Model]({{ "/assets/images/CAD.jpg" | relative_url }}){: .inline-image-r style="width: 2400px"}
<br>
<br>
<br>
<br>
<br>
<br>
<br>

Figure 1: Dimensioned CAD Model

B - Describe material used and its relevant mechanical properties.  

The material I have decided to use is a Titanium alloy, Ti-6Al-4V. The relevant properties are as follows:  
Modulus of Elasticity: E = 16.7+E6 psi,  
Poisson’s Ratio: v = 0.349,  
Tensile Yield Strength: y = 126+E6 psi,  
Fracture Toughness: KIC = 94.2+E3 psi-in^.05,  
Fatigue Strength for 10+E7 Cycles: f' = 92+E3 psi.  


C - Diagram communicating how loads and boundary conditions were applied to your FEM model.  
![Figure 2: FEM Model Loading and Boundary Conditions]({{ "/assets/images/force.jpg" | relative_url }}){: .inline-image-r style="width: 2400px"}  
<br>
<br>
<br>
<br>
<br>
<br>
<br>

Figure 2: FEM Model Loading and Boundary Conditions

D - Normal strain contours (in the strain gauge direction) from FEM  
![Figure 3: FEM Normal Strain Contours]({{ "/assets/images/ns-contour.png" | relative_url }}){: .inline-image-r style="width: 2400px"}
<br>
<br>
<br>
<br>
<br>
<br>
<br>

Figure 3: FEM Normal Strain Contours

E - Contour plot of maximum principal stress from FEM  
![Figure 4: FEM Principal Stress Contour Plot]({{ "/assets/images/ps-contour.png" | relative_url }}){: .inline-image-r style="width: 2400px"}
<br>
<br>
<br>
<br>
<br>
<br>
<br>

Figure 4: FEM Principal Stress Contour Plot

F - Summarize results from FEM calculation showing maximum normal stress (anywhere), load point deflection, strains at the strain gauge locations  

The results from FEM calculation are as follows:  
Smax = 142,690 psi,  
Strain @ Gauge = 1,064 micro-strain,  
Load Point  = 0.074 in.

G - Torque wrench sensitivity in mV/V using strains from the FEM analysis  

According to the FEM analysis, the torque wrenche’s sensitivity is 1.06 mV/V.


H - Strain gauge selected (give type and dimensions). Note that design must physically have enough space to bond the gauges.  

Selected strain gauge isn the SGD-LINEAR1-AXIS Linear Strain Gage. This gague comes in 4.7mm long and it is longer than it is wide, so it will certainly fit on the 0.3 inch thick wrench.




