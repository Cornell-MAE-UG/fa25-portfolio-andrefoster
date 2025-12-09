---
layout: project
title: Torque Wrench
description: MAE 3270 Final Homework Assignment
technologies: [Fusion, Ansys]
image: /assets/images/cover.png
---


For the MAE 3270 Final Homework assignment, we have been instructred to design a torque wrench able to withstand a moment of 600in-lbf. Here are the results:

5.2.1 Results

A - Image(s) of CAD model. Must show all key dimensions.

![Figure 1: Dimensioned CAD Model]({{ "/assets/images/CAD.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}


B - Describe material used and its relevant mechanical properties.

The material I have decided to use is a Titanium alloy, Ti-6Al-4V. The relevant properties are as follows:
Modulus of Elasticity: E = 16.7+E6 psi
Poisson’s Ratio: v = 0.349
Tensile Yield Strength: y = 126+E6 psi
Fracture Toughness: KIC = 94.2+E3 psi-in^.05
Fatigue Strength for 10+E7 Cycles: f' = 92+E3 psi


C - Diagram communicating how loads and boundary conditions were applied to your FEM model.

![Figure 2: FEM Model Loading and Boundary Conditions]({{ "/assets/images/force.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}


D - Normal strain contours (in the strain gauge direction) from FEM

![Figure 3: FEM Normal Strain Contours]({{ "/assets/images/ns-contour.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}


E - Contour plot of maximum principal stress from FEM

![Figure 4: FEM Principal Stress Contour Plot]({{ "/assets/images/ps-contour.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}


F - Summarize results from FEM calculation showing maximum normal stress (anywhere), load point deflection, strains at the strain gauge locations

The results from FEM calculation are as follows:
Smax = 142,690 psi
Strain @ Gauge = 1,064 micro-strain
Load Point  = 0.074 in


G - Torque wrench sensitivity in mV/V using strains from the FEM analysis

According to the FEM analysis, the torque wrenche’s sensitivity is 1.06 mV/V.


H - Strain gauge selected (give type and dimensions). Note that design must physically have enough space to bond the gauges.





