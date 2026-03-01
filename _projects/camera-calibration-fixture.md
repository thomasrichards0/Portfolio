---
title: "Camera Calibration Fixture"
date: 2026-02-23
weight: 4
image: "/images/projects/calibration-fixture-cad.jpg"
---

Designed a magnetic mounting fixture for calibration of a machine vision camera, enabling tool-free installation while maintaining positional repeatability.

<div style="text-align: center; margin: 30px 0;">
  <img src="{{ '/images/projects/calibration-fixture-cad.jpg' | relative_url }}" alt="Camera Calibration Fixture" style="max-width: 600px; width: 40%; border-radius: 8px;">
  <p style="font-style: italic; margin-top: 10px;">Machine vision camera calibration fixture design</p>
</div>

## Summary

I designed a fixture to enable accurate calibration of the autoinjector test system's machine vision camera. The fixture positions a glass calibration square at a precise, repeatable distance from the camera, which measures critical autoinjector parameters, such as needle length and medicine ejection timing.

## Design Challenges

The calibration square needed to be mounted in a location that was difficult to access within the autoinjector test system assembly. The initial approach using threaded fasteners required removing two pneumatic fittings for each calibration, creating an inconvenient, time-consuming process that would discourage more regular calibration.

## Approach

**Magnets!**

I proposed using magnets instead of mechanical fasteners, enabling tool-free installation and removal of the calibration fixture. I considered an alternative approach using extended shoulder screws that would allow the fixture to slide onto the existing pneumatic fitting screws, but this would add another different component to the test system assembly, adding unnecessary complexity to its product line.

**Exact Constraint and GD&T**

I applied exact constraint principles to ensure the calibration square was positioned consistently between calibrations, despite attaching using magnets, instead of fasteners. I designed the fixture for CNC manufacturing with GD&T to maintain repeatable positioning.

## Results

I designed a fixture that simplified calibration from a multi-step procedure requiring tools to a single-handed magnetic attachment. The design improves calibration workflow efficiency while maintaining the positional repeatability for calibration.

## Skills Applied

- SolidWorks (configurations, assemblies, exploded views)
- GD&T
- Exact Constraint
- Design for Manufacturing