---
title: "Multicooker Cavity Airflow Improvements"
date: 2023-11-15
weight: 5
image: "/images/projects/sfp-final.jpeg"
---

Minimized uneven cooking in the Ninja Combi multicooker through rapid prototyping and testing, adding cavity geometry and heating element shape changes that shipped in the final product.

<div style="text-align: center; margin: 30px 0;">
  <img src="{{ '/images/projects/sfp-final.jpeg' | relative_url }}" alt="Final Cavity Changes" style="max-width: 600px; width: 80%; border-radius: 8px;">
  <p style="font-style: italic; margin-top: 10px;">The new heating element and cavity geometry changes</p>
</div>

## Summary

The Ninja Combi multicooker showed uneven browning in the front right corner during testing of KPIs. As the product was closely reaching production, I was tasked with implementing desisgn changes to improve cooking performance.

## Design Challenges

The solution needed to fit within the existing cavity geometry, avoid significant cost increases, and maintain cooking performance across the multiple cooking modes. The short timeline added urgency, as this issue was preventing further product development progress before the product's launch.

## Approach

**Airflow Deflectors**

I used various sheet metal vanes positioned above the affected spot to attempt to redirect airflow. Fabrication of these sheet metal parts were fast, and allowed for fast iteration.

<div style="text-align: center; margin: 30px 0;">
  <img src="{{ '/images/projects/sfp-vanes.jpeg' | relative_url }}" alt="Airflow Deflectors" style="max-width: 600px; width: 70%; border-radius: 8px;">
  <p style="font-style: italic; margin-top: 10px;">The different airflow deflectors I fabricated and tested</p>
</div>

**Heating Element Geometry Changes**

I tested a heating element prototype that would increase the amount of heat in the front right corner.

<div style="text-align: center; margin: 30px 0;">
  <img src="{{ '/images/projects/sfp-heating-element.jpeg' | relative_url }}" alt="Heating Element Changes" style="max-width: 600px; width: 70%; border-radius: 8px;">
  <p style="font-style: italic; margin-top: 10px;">Testing more localized heating element shape over the front right corner</p>
</div>

**Cavity Geometry Changes**

Another avenue I tested was by altering the upper cavity geometry to redirect airflow, similar to the vanes, but with improved manufacturability. To quickly test the effectiveness of this idea without having to wait for new sheet metal cavity parts, I 3D printed a negative mold of the new geometry. I then applied layers of aluminum tape over the mold, to create a sturdy, yet representative prototype. 

<div style="text-align: center; margin: 30px 0;">
  <img src="{{ '/images/projects/sfp-cavity-prototype.jpeg' | relative_url }}" alt="Cavity Geometry Prototype" style="max-width: 600px; width: 70%; border-radius: 8px;">
  <p style="font-style: italic; margin-top: 10px;">The prototyped new cavity geometry</p>
</div>

## Validation Testing

To ensure the new cavity geometry would not affect surface temperatures of the cavity, I performed tempertaure testing using thermocouples to ensure the prototype remained below the relative thermal index (RTI). This validated that the new cavity would not create additional problems, such as melting of components outside of the cavity, due to excessive surface temperatures.

<div style="text-align: center; margin: 30px 0;">
  <img src="{{ '/images/projects/sfp-cavity-testing-2.jpeg' | relative_url }}" alt="NTT on New Cavity Geometry" style="max-width: 600px; width: 70%; border-radius: 8px;">
  <p style="font-style: italic; margin-top: 10px;">Performing temperature tests on new cavity geometry</p>
</div>

## Results

The final Ninja Combi product features both the modified heating element geometry and upper cavity shape. These changes minimized the uneven browning, allowing the product to be released.

## Skills Applied
- Rapid Prototyping
- Product Testing
- Data Acquisition
- Data Analysis
- Cross-functional Collaboration
