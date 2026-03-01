---
title: "Critter Catcher - Capstone Project"
date: 2026-02-22
weight: 1
image: "/images/projects/capstone-final-prototype.jpg"
---

Led the mechanical design, CAD development, and system integration of an insect capturing device, creating creative solutions, and validated with professional beekeeper field testing.

<div style="text-align: center; margin: 30px 0;">
  <img src="{{ '/images/projects/capstone-final-prototype.jpg' | relative_url }}" alt="Critter Catcher Device" style="max-width: 600px; width: 100%; border-radius: 8px;">
  <p style="font-style: italic; margin-top: 10px;">Final prototype of the Critter Catcher</p>
</div>

## Summary

Existing insect capture devices largely focus on trapping the insect through any means, rather than insect safety. I led the mechanical design of the Critter Catcher, a handheld vacuum-like device that humanely captures insects using an innovative reversible fan system. The device won "Best Iterative Design" at Northeastern University's 2024 Fall Capstone Showcase and received positive feedback from beekeepers during live bee testing.

## Creative Solutions

Throughout this project, I developed several innovative solutions to overcome mechanical, manufacturing, and aesthetic challenges that couldn't be solved with off-the-shelf components, or conventional approaches. Here are some of my favorites!

**Rotating Fan Mechanism**

To enable the capture and release functionality of the Critter Catcher without needing to directly interact with the insects, I came up with the idea of being able to rotate the fan 180°. This would allow the device to seamlessly switch between "vacuum" and "blower" modes. The mechanism used a keyed shaft that interfaces with a silicone overmolded t-handle. Magnets on either side of the fan provided tactile feedback and ensured the fan stayed at the set mode. Ball bearings above and below the fan ensured smooth rotation while a slip ring was implemented below the fan to prevent wires from tangling.

<div style="text-align: center; margin: 30px 0;">
  <img src="{{ '/images/projects/capstone-fan-mechanism.jpg' | relative_url }}" alt="Rotating Fan Mechanism" style="max-width: 600px; width: 100%; border-radius: 8px;">
  <p style="font-style: italic; margin-top: 10px;">The rotating fan mechanism installed in the Critter Catcher</p>
</div>

**Spring-Loaded Containment Door Mechanism**

One of the more challenging aspects of the containment system was creating a hinge mechanism for the transparent door. This doubled as a window for the user to view inside, while allowing for an alternative approach to removing insects. The casing geometry severely restricted the directions the door could swing open, and off-the-shelf hinges from McMaster-Carr were too bulky for my aesthetic vision.

I developed a custom spring-loaded pin mechanism that solved both problems. Pins were added to either side of the door within the casing. When compressed, they sat flush with the casing surface, allowing the door to be installed. Once the door was properly situated, the spring-loaded pins extended outwards and engaged with hole features incorporated into the SLA 3D printed door. To latch the door in place, ball plungers were added on the opposite side to add resistance when opening the door. This solution allowed me to fully incorporate the hinge mechanism inside the door.

<div style="text-align: center; margin: 30px 0;">
  <img src="{{ '/images/projects/capstone-door-mechanism.jpg' | relative_url }}" alt="Door Hinge Mechanism" style="max-width: 600px; width: 60%; border-radius: 8px;">
  <p style="font-style: italic; margin-top: 10px;">The spring-loaded hinge mechanism in the Critter Catcher</p>
</div>

**Hidden Fasteners**

From the beginning of this project, one of my biggest goals was to achieve a consumer-ready aesthetic in the device design. If you take a close look at the Critter Catcher, one thing you might notice is that there is no visible screws. This constraint required creative problem-solving throughout the entire assembly to ensure the device was still structurally sound.

To pull back the curtains of how I achieved this, I developed several integrated solutions to hide necessary screws. For instance, the silicone handle grip attaches to the handle sub-assembly by stretching over internal pins, creating a tool-free fit that naturally covers the screws connecting the handle to the main body. Furthermore, fasteners joining the two casing halves are concealed within the battery compartment, accessible only through the containment area and behind the containment door, which hides the screws when in its closed state. The fan speed control knob also serves two purposes. Before it's installation, its mounting hole provides screwdriver access to the rear assembly. Once installed, the potentiometer and knob fill this access point completely.

<div style="text-align: center; margin: 30px 0;">
  <img src="{{ '/images/projects/capstone-hidden-fastener-1.jpg' | relative_url }}" alt="Hidden screws" style="max-width: 600px; width: 40%; border-radius: 8px;">
  <p style="font-style: italic; margin-top: 10px;">The screws hidden using the potentiometer and knob</p>
</div>

<div style="text-align: center; margin: 30px 0;">
  <img src="{{ '/images/projects/capstone-hidden-fastener-2.jpg' | relative_url }}" alt="Hidden screws" style="max-width: 600px; width: 40%; border-radius: 8px;">
  <p style="font-style: italic; margin-top: 10px;">The screws hidden using the handle grip</p>
</div>

**Silicone Handle**

We identified ergonomics as another source of differentiation compared to existing insect capture devices. To ensure we made the most comfortable handle as possible, we conducted three rounds of user testing with over 60 participants to refine the handle geometry. Between testing stages, I iterated on parameters such as grip diameter, grip length, finger contours, and grip material. The final handle design features a molded 60A silicone grip attached to a rigid handle base. The handle is ambidexterous so both left and right-handed people can use the device.

## Validation Testing

Working with New England Beekeeping, we conducted validation testing at an apiary with a prototype of the Critter Catcher. The beekeeper tested the device on live bees, evaluating the capture and release functionality, adjustable vacuum fan speed, and insect safeness. All captured bees were successfully caught, and subsequently released unharmed. The beekeepers provided positive feedback on the device's features, with a particular interest in its ability to separate and transport queen bees and checking beehives for mites.

<div style="text-align: center; margin: 30px 0;">
  <img src="{{ '/images/projects/capstone-prototype-testing.JPG' | relative_url }}" alt="Validation Testing at apiary" style="max-width: 600px; width: 100%; border-radius: 8px;">
  <p style="font-style: italic; margin-top: 10px;">Validation testing of an early prototype with live bees at a local apiary</p>
</div>

## Results

The Critter Catcher successfully captured and released live bees in our field testing, with no injuries observed. During the Fall 2024 Capstone Showcase, our group was awarded the "Best Iterative Design".

## Skills Applied

- SolidWorks (assemblies, design for manufacturing, and PDM)
- 3D Printing (FDM and SLA)
- Silicone Molding and Mold Design
- Component Sourcing
- Fast-paced Design Iterations
