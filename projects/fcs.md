---
layout: project
type: project
image: img/fcs/fcslogo.png
title: Enterprise File & Client Classification System
date: January 2026
published: true
labels: [data hygiene, system design, enterprise tooling, error handling, operational reliability]
summary: Designed an internal file and client-classification system to manage thousands of unstructured financial documents in SharePoint. Built validation logic, naming heuristics, and review workflows to resolve ambiguous client identities, enforce consistency, and prevent downstream audit and retrieval failures. Focused on data hygiene, operational reliability, and human-error mitigation under real enterprise constraints.
---

## Overview

In a real production environment, most failures do not come from broken code—they come from messy data and human inconsistency.

At work, I encountered a growing SharePoint repository containing thousands of folders with financial documents tied to client work. Folder names were inconsistent, client identities were ambiguous, and folders often mixed multiple entities. This created real operational risk: misfiled documents, retrieval failures, and audit exposure.

I designed FCS, an internal file and client classification system, to bring structure, validation, and accountability to an otherwise ungovernable document space.

## Problem

The core challenge was not storage—it was identity.
- Clients appeared under multiple naming conventions
- Folder names mixed individuals, entities, and engagements
- Files contained partial or conflicting client references
- SharePoint provided no enforced schema or validation
- Manual cleanup did not scale and introduced more errors

There was no single source of truth—and yet the system had to remain usable by non-technical staff.

## Solution

I designed a classification and validation pipeline that worked with human workflows rather than against them.

**Key components included**:
Heuristic-based client name matching and normalisation
- Explicit Match, No Match, or Needs Review classification states
- Validation columns to surface ambiguity instead of hiding it
- Structured naming conventions enforced through review steps
- Separation between automated detection and human confirmation

Rather than attempting brittle full automation, the system focused on data hygiene and error visibility, ensuring problems were caught early and intentionally resolved.

## Engineering & Design Considerations

- Designed for ambiguity, not ideal inputs
- Avoided destructive operations or silent overwrites
- Prioritised traceability and reviewability over cleverness
- Balanced automation with human-in-the-loop safeguards
- Operated entirely within enterprise tool constraints (SharePoint + Excel)

This was a systems design problem, not a UI or scripting task.

## Impact

- Identified and formalised inconsistencies in client and file naming across an existing SharePoint repository
- Created a structured way to distinguish valid, ambiguous, and invalid client associations
- Made document organisation issues visible rather than implicit or silently ignored
- Provided a clear foundation for IT to design a more robust long-term document management solution
- Reduced reliance on ad-hoc tribal knowledge for locating client files

The primary value of this work was not immediate automation, but clarity: turning an unstructured problem into a defined system that could be reasoned about, reviewed, and improved.

## What I Learnt

- Real systems fail at boundaries, not cores
- Data hygiene is an engineering problem
- Full automation is not always the correct solution
- Designing for humans is part of system design
- Constraints often matter more than tools

## Status

This system remains internal and cannot be shared publicly due to confidentiality constraints.
Its design principles continue to inform how I approach data validation, operational tooling, and system reliability in larger projects.