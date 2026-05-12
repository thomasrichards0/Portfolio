---
title: "Dog Rehabilitation Wheelchair"
date: 2026-05-12
weight: 2
image: "/images/projects/dog-wheelchair-prototype.jpeg"
---

Designed crankshaft mechanism for canine rehabilitation wheelchair and analyzed IMU gait data comparing passive exercise patterns to healthy dog locomotion.

<div style="text-align: center; margin: 30px 0;">
  <img src="{{ '/images/projects/dog-wheelchair-prototype.jpeg' | relative_url }}" alt="Critter Catcher Device" style="max-width: 600px; width: 100%; border-radius: 8px;">
  <p style="font-style: italic; margin-top: 10px;">Final prototype of the dog rehabilitation wheelchair</p>
</div>

## Summary

Dogs with partial hind leg paralysis require regular physical therapy to regain muscle function. The common rehabilitation method is for vets to manually move the dog's legs in water therapy which poses limitations on the duration of the process. My group modified a commerical dog wheelchair with a crankshaft-driven mechanism that passively exercises the hind legs as the dog walks with its front legs, automating the rehabilitation process. I led the mechanical design of the crankshaft integration system and conducted data analysis comparing a dog's gait patterns while using the modified wheelchair against a standard dog wheelchair and healthy dog reference data.

## Design Challenge

The design needed to retrofit a crankshaft system onto the existing frame while maintaining its structural integrity and ensuring smooth rotation of the pedals. Additionally, the mechanism needed to be robust enough for dynamic loads during walking and running while remaining lightweight and non-restrictive for the animal.

## Mechanical Design

**Crankshaft Mounting System**

I designed custom brackets that extend below the wheelchair frame to create space for the crankshaft assembly to attach to the frame. The brackets incorporate press-fit bearings to ensure smooth rotation of the crankshaft as the wheels turn. To prevent the bearings spinning freely within the brackets, I created 3D-printed TPU sleeves that grip the bearing's outer surface circumferentially while also featuring a keyed interface with the bracket to prevent rotation—creating a more secure mounting system.

<div style="text-align: center; margin: 30px 0;">
  <img src="{{ '/images/projects/dog-wheelchair-frame-bracket-cad.png' | relative_url }}" alt="Bearing Sleeve CAD" style="max-width: 600px; width: 50%; border-radius: 8px;">
  <p style="font-style: italic; margin-top: 10px;">The bearing sleeve used to hold the bearing in place and prevent spinning</p>
</div>

**Pedal Design**

I designed pedals that clamp around the crankshaft and connect to the dog's hind legs, transfering the rotational wheel motion into the dog's legs to mimic a more natural walking gait. Exact constraint principles were applied to the pedal design to ensure that when clamping around the crankshaft rod, the two pieces were not misaligned that could add friction or binding during rotation. Due to the thinness of the pedals and slight variability in the hand-made crankshaft, we opted to not utilize bearings or bushings. Instead, the pedals are free spinning on the crankshaft due to a loose fit between the pedals and crankshaft. To further reduce friction between the two, I added cutout features along the inner surface.

<div style="text-align: center; margin: 30px 0;">
  <img src="{{ '/images/projects/dog-wheelchair-pedal-cad.png' | relative_url }}" alt="Pedal CAD" style="max-width: 600px; width: 70%; border-radius: 8px;">
  <p style="font-style: italic; margin-top: 10px;">The inner surfaces and features of the pedals</p>
</div>

**CAD Development**

To be able to design the crankshaft brackets, I reverse-engineered and modeled the entire original dog wheelchair frame in Solidworks, using measurements I took as well as pictures. This allowed me to ensure that the brackets accounted for the angle tilt that was originally incorporated into the dog wheelchair.

<div style="text-align: center; margin: 30px 0;">
  <img src="{{ '/images/projects/dog-wheelchair-cad.png' | relative_url }}" alt="Modified Dog Wheelchair CAD" style="max-width: 600px; width: 100%; border-radius: 8px;">
  <p style="font-style: italic; margin-top: 10px;">The recreated CAD model of the modified dog wheelchair</p>
</div>

## Data Analysis

**Real World Testing**

We conducted live testing at an animal hospital with a dog suffering from hind leg paralysis. Four Actigraph Link IMUs were attached to the dog to capture 3-axis acceleration and angular velocity. The dog then trotted down the hall using both our crankshaft-assisted wheelchair and the unmodified dog wheelchair.

**Data Analysis in MATLAB**

I led the analysis of the IMU data. This involved several steps:

- Data synchronization and cropping: Aligned the IMU timestamps and cropped the data to isolate the test runs
- Heel strike detection: Identified the start of each gait cycle using knee acceleration peaks in z-axis
- Gait cycle averaging - Segmented the continuous motion data into individual stride cycles and found the average
- Comparative analysis - Compared the average gait between the modified wheelchair, standard wheelchair, and reference data from a healthy dog of a similar weight

This analysis shows that our modified wheelchair allowed the dog to have a gait that was more similar to a healthy dog's gait.

<div style="text-align: center; margin: 30px 0;">
  <img src="{{ '/images/projects/dog-wheelchair-results.png' | relative_url }}" alt="Modified Dog Wheelchair Results" style="max-width: 600px; width: 100%; border-radius: 8px;">
  <p style="font-style: italic; margin-top: 10px;">The results showing the modified dog wheelchair behaves more similarly to a healthy dog's gait</p>
</div>

## Results

Successfully designed and fabricated a functional crankshaft-driven dog wheelchair that passively exercises paralyzed hind legs during front-leg locomotion. Live animal testing demonstrated the mechanism's ability to produce cyclic leg motion synchronized with the dog's gait. Biomechanical data analysis showed gait characteristics more closely resembling healthy dog locomotion compared to standard wheelchairs with suspended hind legs, validating the rehabilitation potential of the passive exercise mechanism.
The single-iteration design success—achieving proper alignment, smooth rotation, and functional kinematics without requiring adjustments—demonstrated effective application of exact constraint design principles and thorough CAD-based design validation.

<div style="margin: 30px 0; text-align: center;">
  <a href="https://www.youtube.com/watch?v=W_suEdvzoY4" target="_blank">
    <img src="{{ '/images/projects/dog-wheelchair-journey.jpeg' | relative_url }}" 
         alt="Dog Wheelchair Demo Video" 
         style="max-width: 600px; width: 80%; border-radius: 8px; cursor: pointer; transition: transform 0.2s ease, box-shadow 0.2s ease;"
         onmouseover="this.style.transform='scale(1.02)'; this.style.boxShadow='0 8px 16px rgba(0,0,0,0.2)';"
         onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='none';">
  </a>
  <p style="font-style: italic; margin-top: 10px; color: #666;">Click to watch Journey testing our wheelchair!</p>
</div>

## Skills Applied

- SolidWorks (assemblies, design for manufacturing)
- Exact Constraint
- 3D Printing
- MATLAB (signal processing, data analysis)
- Component Sourcing