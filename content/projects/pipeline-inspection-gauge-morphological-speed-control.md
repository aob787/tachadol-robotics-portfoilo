+++
title = "Morphological Adaptation for Speed Control of Pipeline Inspection Gauges"
date = 2025-01-21
summary = "An add-on adaptive speed control module for pipeline inspection gauges, using morphological adaptation via a rotary valve unit and closed-loop PD control — demonstrated in a real industrial pipeline."
association = "ARV / VISTEC"
project_folder = "pig-speed-control"
image_file = "cover.jpg"
gallery = [
  # "/images/projects/pig-speed-control/slide-01.jpg",
  # "/images/projects/pig-speed-control/slide-02.jpg",
]
+++

## Project Overview

Pipeline inspection gauges (PIGs) are devices used for in-pipe inspection and maintenance. Controlling their speed is critical for safe operation, but passive PIGs lack any speed regulation capability.

This project develops a modular, external add-on speed control module for PIGs — called MC-PIG (Morphological Computation PIG) — using the principle of morphological adaptation. By adjusting the angle of a rotary valve unit integrated with the PIG body, the module modulates bypass flow and thereby regulates the device's moving speed inside the pipeline.

The full system integrates multiple sensors, a rotary valve with an actuator, and an embedded controller with sensor fusion via an Extended Kalman Filter (EKF). Closed-loop Proportional-Derivative (PD) control automatically adjusts the valve morphology to match the desired speed.

## Research Context

This project spans two publications and progressed from simulation-based concept validation to real-world industrial demonstration.

**Paper 1 — Concept and Simulation (2021)**
Morphological Adaptation for Speed Control of Pipeline Inspection Gauges: MC-PIG
SPE Abu Dhabi International Petroleum Exhibition and Conference (ADIPEC), 2021
Authors: S. Phodapol, T. Suthisomboon et al.

This earlier work introduced the MC-PIG (Morphological Computation PIG) concept, validated valve-based speed modulation via CFD numerical simulation, and performed small-scale mock testing. The focus was on establishing feasibility of the modular rotary valve approach.

**Paper 2 — System Integration and Real-World Demo (2025)**
Morphological Adaptation for Speed Control of Pipeline Inspection Gauges: From System Integration to Real-world Demonstration
IEEE/SICE International Symposium on System Integration (SII), 2025 — Pages 155–156
Authors: T. Suthisomboon, S. Phodapol et al.

Achievement highlights:
- SIYA-SII2025 (SIYA-SII Winners)
- Award-winning paper presenter: Thipawan Pairam
- Reference: [Past SIYA-SII Winners](https://sice-si.org/en/past_siya-sii_winners/)

The 2025 paper presents the full integrated system evaluated and demonstrated in an actual industrial pipeline environment under various fluid flow rates.

## Objectives

- Design a modular, retrofit-compatible speed control module that requires minimal changes to existing passive PIGs.
- Implement morphological adaptation by using valve angle adjustment to control bypass flow and speed.
- Achieve reliable closed-loop speed regulation using sensor fusion and PD control.
- Validate system performance in a real industrial pipeline under varying flow conditions.

## My Contribution

I was a key contributor across the project lifecycle, from early feasibility to hardware integration and real-world testing:

- Spearheaded the feasibility prototype and defined the initial project scope.
- Led valve design and optimization, developing the rotary valve unit that enables morphological adaptation.
- Contributed to mechanical design of the module architecture and system integration.
- Involved in hardware development throughout both phases of the project, from bench testing to industrial pipeline demonstration.

## Key Results

- The valve-angle-based morphological adaptation successfully modulated PIG speed in real pipeline conditions.
- EKF-based sensor fusion provided accurate speed estimation under varying flow dynamics.
- Closed-loop PD control maintained speed regulation across different fluid flow rates in the industrial test environment.
- Demonstrated practical viability of a modular external add-on approach, requiring minimal modification to existing PIGs.

## Links

- Paper (SII 2025): [IEEE](https://ieeexplore.ieee.org/document/10890021)
- Paper (ADIPEC 2021): [SPE](https://onepetro.org/SPEADIP/proceedings-abstract/21ADIP/3-21ADIP/D011S025R004/473540)
- Video Demo: [Google Drive](https://drive.google.com/file/d/1PPuNLwX_M4ojAeKmKQL5N-xAInn1TiwQ/view?usp=sharing)

## Concept Overview Video

{{< gdrive-video id="1PPuNLwX_M4ojAeKmKQL5N-xAInn1TiwQ" >}}
