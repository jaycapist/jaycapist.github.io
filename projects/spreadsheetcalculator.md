---
layout: project
type: project
image: img/spreadsheetcalculator/spreadsheet-thumbnail.png
title: Modular Spell Damage Modelling System
date:  May 18 - July 19 2024
published: true
labels: [data modelling, modular design, error handling, spreadsheets]
summary: A modular spreadsheet tool built to model complex spell damage systems in a mobile game. The calculator translates layered game mechanics—items, traits, spell paths, and passives—into accurate, decision-ready outputs, with real-time validation to prevent invalid configurations. Designed for scalability and maintainability as the game’s systems evolve.

---

<div class="text-center p-4">
  <img width="1000px" src="../img/spreadsheetcalculator/spreadsheet-main.png" class="img-thumbnail" >
</div>

## Overview

Designed and built an advanced spreadsheet-based calculator to compute spell damage and related statistics for a mobile game. The tool allows users to configure mage types, spells, spell paths, items, traits, and passives, then dynamically calculates outcomes based on those selections. The goal was to support highly optimised gameplay by turning complex stat interactions into auditable, user-driven calculations.

## Responsibilities

- Sole developer responsible for system design, implementation, and interface layout.
- Designed modular calculation systems for spells, items, and traits
- Built structured data models to support scalable stat interactions
- Integrated backend logic with a clear, user-facing input interface
- Implemented constraint validation and error handling (e.g., item limits)
- Designed visual structure and colour-coded inputs to improve clarity and usability

## Technical Highlights

<div class="text-center p-4">
  <img width="1000px" src="../img/spreadsheetcalculator/spreadsheet-thunderstrike-damage-formulae.png" class="img-thumbnail" >
</div>

**Modular Architecture**: Independent modules for items, spells, and traits to support maintainability and future expansion
**Dynamic Calculations**: Real-time stat computation based on user configuration
**Input Validation**: Guardrails and feedback to prevent invalid or conflicting configurations
**Data Organisation**: Categorised and structured data to reduce complexity and improve auditability

## Outcome

The project demonstrated how modular design and structured data handling can simplify complex calculation logic while remaining extensible. Although currently paused due to changes in the game’s item system, the architecture was intentionally designed to support future updates with minimal refactoring.

---

Spreadsheet available [here](https://docs.google.com/spreadsheets/d/19tHauHYIDEdJ4v4bz1OhWK5OPHvkaEYyTbK8K9yhvp0/edit?usp=sharing).
