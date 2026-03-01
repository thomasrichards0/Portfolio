---
title: "Outdoor Oven Smoke Handle Design"
date: 2026-02-23
weight: 5
image: "/images/projects/oohandle-initial-testing.jpeg"
---

Redesigned an outdoor grill/oven smoke box handle to reduce surface temperatures, successfully shipping on both the Ninja Outdoor Oven and Ninja Outdoor Grill XL appliances.

<div style="text-align: center; margin: 30px 0;">
  <img src="{{ '/images/projects/oohandle-prototype.jpeg' | relative_url }}" alt="Outdoor Oven Smoke Handle Design" style="max-width: 600px; width: 50%; border-radius: 8px;">
  <p style="font-style: italic; margin-top: 10px;">Smoke box handle prototype</p>
</div>

## Summary

The Ninja Outdoor Oven features a smoke box with a door that allows the user to add wood pellets for smoke flavor. During testing, excesssive heat transfer from the smoke box raised the door handle's touchpoint temperature above the limit set for user safety. I redesigned the handle and mounting bracket to reduce the touchpoint temperature and tested in the lab to verify prototype.

## Design Challenges

The original handle design conducted excessive heat, either during long usages of the smoke box or repeated ignitions of the wood pellets caused by the user, creating a safety concern. The redesigned handle needed to fix this thermal issue while not compromising on the visual aesthetic of the oven, or add significant manufacturing complexity.

## Approach

**Handle Geometry**

I raised the height of the upper handle surface and added a slotted hole feature. This increased the distance between the user's fingers and the metal bracket. The slotted hole also minimizes heat transfer through the handle itself.

**Mounting Bracket**

The mounting bracket connecting the handle to the smoke box was also extended. This positioned the handle farther from the heat source, reducing the radiative and conductive heat transfer.

## Validation Testing

I led the validation testing of this redesigned handle using 3D printed nylon handles with the updated geometry, and by modifying the mounting bracket with sheet metal and rivets to emulate a longer mounting bracket. I created a standard operating procedure to perform repeatable temperature tests of the handle.

Thermocouples and a DAQ were used for data acquisition, where the TCs were placed at set locations along the handle.

<div style="text-align: center; margin: 30px 0;">
  <img src="{{ '/images/projects/oohandle-testing.jpeg' | relative_url }}" alt="Prototype Validation" style="max-width: 600px; width: 50%; border-radius: 8px;">
  <p style="font-style: italic; margin-top: 10px;">Testing prototype handle and bracket</p>
</div>

## Results

The redesigned handle successfully reduced touchpoint temperature below the safety limit. Both the Ninja Outdoor Oven and Ninja Outdoor Grill XL shipped with this improved handle design.

## Skills Applied

- SolidWorks
- Rapid Prototyping and Fabrication
- Product Testing
- Data Acquisition
- Data Analysis
