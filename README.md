# NAZR

A daily riddle game that turns a Mumbai auto-rickshaw commute into a way of noticing the city.

Built by a team of three in the **Play It Forward creator residency (Kulfi Collective x Maker's Asylum), Mumbai, 15 Aug to 18 Oct 2026**. Showcased at the Kulfi Collective HQ on 16 October 2026.

**Live app:** [https://www.nazarit.in/]
**Instagram documentation (Kulfi Collective):** [https://www.instagram.com/reel/DfXCkF8tEoX/?utm_source=ig_web_copy_link&jplx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==)]
**Full case study (design portfolio):** [PORTFOLIO LINK]

## The idea
Commuters in Mumbai autos are overstimulated by traffic noise and rarely look up. NAZR gives them one prompt a day for the whole city, for example "an object wearing a disguise", and asks them to answer it with a photo from the street. Riders can then see how other people interpreted the same prompt.

## How it works
1. A mascot installation inside the auto, inspired by Nazar Battu demon masks, uses an **ultrasonic sensor** to detect a rider.
2. A **servo** sweeps the mascot's eyes to catch attention, and a **display** (the mascot's tongue) shows the daily riddle.
3. A **QR sticker** takes the rider to the **web app**, where they get an auto-generated username, can build their own mascot avatar, post a photo with a short description and location, and browse other people's finds.

## Hardware and tools
ESP32 (CrowPanel 3.5" HMI display), HC-SR04 ultrasonic sensor, SG90 servo, 5 V power bank; Arduino IDE; enclosure modelled in FreeCAD and Blender (with Meshy AI for final touches), 3D printed, drilled and spray-painted; UI designed in Figma; branding in Adobe CC.

## My part
Confirmed by the residency letter:
- Field research (interviews and observation) and identifying the key themes.
- Brand identity, and the concept of the physical component and user journey.
- Wiring, and AI-assisted coding and testing, of the sensor, display and servo (about 80 h of firmware and hardware prototyping).
- AI-assisted coding and testing of the web app, together with my teammates (about 56 h).
- 3D modelling, printing and final assembly of the enclosure.
- Figma UI design of the web app.

## Code
The source code is private because this is a live commericial project.
