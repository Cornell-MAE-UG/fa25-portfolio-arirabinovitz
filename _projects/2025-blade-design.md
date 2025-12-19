---
layout: project
title: Airfoil Blade Project
description: Blade Design Project
technologies: [MATLAB, Autodesk Fusion]
image: /assets/images/git1.png
---

For my class MAE 4272, we were asked to design an airfoil. The goal was to design an airfoil to operate at a fixed rotation rate, while operating in wind conditions told to us according to a Weibull distribution. We were asked to design this to learn how to optimize a design, we chose to optimize our design for power at our chosen rotation rate of 1000 RPM.

Given our Weibull Distribtion, we calculated which wind speed to design for, which was determined to be 5.05 m/s. You can see the peak in the following figure: 

![Shaded rendering of earlier version]({{ "/assets/images/git2.png" | relative_url }}){: .inline-image-r style="width: 400px"}

To optimize our power, we designed to optimize our Cl/Cd ratio, which meant that we designed for a constant angle of attack of about 9.75 degrees. We twisted the pitch angle of the airblade to maintain this angle of attack. Then, we tapered our chord length to both maximize power within our limiting constraints. Here is a image of the power we expected to generate.

We tested the airfoils in a wind tunnel, obtaining power curves for the airfoils from 3.4 m/s to 7.1 m/s, our upper limit of likely wind speeds. Our results showed that our airfoils did generate the most power near 1000 RPM; however, the power generation was an order of magnitude less than expected.

The power curves scaled by probability can be seen here:
![Photo of old radio]({{ "/assets/images/git3.png" | relative_url }}){: .inline-image-l}

My work involved developing the code and main design choices in determing the geometry of the airblade, and also contributing to the analysis of our experimental results, helping show that our optimal rotation rate experimental was 1054 RPM. In the future, we want to design our airblade with less assumptions so that we generate power closer to our expectations.