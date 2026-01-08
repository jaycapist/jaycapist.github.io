---
layout: essay
type: essay
title: "Kimoriya: A thematic Pokemon team builder"
date: 2024-12-30
published: false
category: "projectideas"
labels:
 - Personal Project
 - Project Management
 - Software Engineering
 - Web Application
---

Originally, the idea of this web-based tool was posted to r/Pokemon. A user was recruiting people to work on a thematic Pokemon team builder called DreamDex. We had scraped most of the relevant data at the time and had some work finished on the developer's side, but the project was ultimately abandoned. I joined that team because this genuinely seemed like a tool that I would personally make lots of use of. With it being abandoned, it seemed to be a sad conclusion. I am now on winter break in my junior year and decided to start reviving this project on my own under the name Kimoriya.

Honestly, I had no idea what to call the application. Kimoriya primarily comes from the Japanese name of Treecko, my favourite Pokemon. The ya comes from 屋, meaning house or shop. So, Treecko's house, but honestly it was mostly added to make it sound better.

# Overview

**Kimoriya** is a thematic Pokemon team builder. It will be a web-based tool that allows users to filter Pokémon based on various attributes, including type, stats, abilities, creature type, and more. After the basics of a Pokemon filter site are accomplished, the type of filters will be built upon.

# Page Ideas

**Home Page**: A clean and minimalistic design. List of current features and ones to be implemented. A basic rundown for basic usage.

**Pokemon Filter Page**: Displays a list and or grid of Pokémon with the capabiliyt for infinite scrolling. Include a search bar and dropdowns for filters. Filters with checkboxes, sliders, and dropdowns. An option to clear or reset filters.

**Game Page (Future)**: Wordle-like game interface where users try to guess a Pokémon based on selected attributes. It returns a user's guess with visual feedback on which attributes do or do not match. Include customisable options for selecting which Pokémon attributes will be used to help guess. Eg. egg group, game availability, etc.

# Use Case Ideas

**Casual Users**: A user that will use the site to browse Pokémon by type, stats, or generation and to filter out Pokémon quickly.

**Pokémon Fans**: Users who are interested in seeing all the Pokémon of a specific type or a certain theme.

# Advanced Features and Solutions

**Advanced Search Filters**:
Feature: Allow users to apply advanced filters like move compatibility, egg groups, creature type, etc.
Solution: Implement additional filtering options to make searching more granular.
- e.g. filtering Pokémon with multiple filter types
Challenges: Ensure all filters work seamlessly and return accurate results.

**Pokémon Guessing Game**:
Feature: Allow users to play a Wordle Pokémon guessing game
Solution: Use custom filters to help guess the Pokémon based on their selections.
Challenges: Ensure dynamic, and real-time feedback based on user guesses. Implement the game logic to check guesses against Pokémon data.

# Key Design Goals

**Usability**: Create a user-friendly and intuitive interface that allows for easy navigation. The filters and data should be easy to understand for new users.

**Responsiveness**: Ensure the site works well on desktop devices, adjusting the layout and elements accordingly. Look into ensuring similar functionality on mobile devices.

**Performance**: Ensure the site loads quickly and efficiently, especially when filtering large datasets. Implement lazy loading to handle Pokémon data without compromising speed.

**Data Accuracy**: Make sure that all Pokémon data is accurate and up-to-date. Regularly check and update the Pokémon data, like when new Pokémon games are released.

**Aesthetic Design**: The site should have an appealing, modern look. Utilise Pokémon art and icons to keep it visually engaging while maintaining readability.

# Plans for Implementation

### Stage 1: Non-coded Mockups

- plan basic layouts and ideas using Figma

### Stage 2: Basic Setup

- set up the project structure using HTML, CSS, and React
- integrate the Pokémon API (PokeAPI) to retrieve data
- develop a basic homepage
- develop a basic Pokemon filter page
  - search bar
  - grid/list to display Pokemon
  - simple filters

### Stage 3: Pokémon Filter Page

Enhance the filtering system to support more advanced filter criteria. Display a dynamic list and/or grid of Pokémon matching the selected filters. Implement sorting types for the list of Pokemon, also switch between grid or list changes.

### Stage 4: User Interface Enhancements

Improve the UI/UX design with better styling and interactivity. Implement a clean and visually appealing layout for the filter page.

### Stage 5: Testing and Optimisation

Implement a feedback system and conduct user testing to get feedback on usability and design. Optimise performance, particularly when displaying large datasets of Pokémon.

# What I'll Need to Learn

**Web Development Frameworks**: Consolidate knowledge in React for dynamic filtering and interactivity. Improve HTML, CSS, and JavaScript skills.

**API Integration**: Learn to work with the PokeAPI to fetch and manage Pokémon data. Understand how to handle and optimise large datasets and data retrieval.

**UX/UI Design**: Learn principles of user experience and interface design for a smooth and intuitive layout. Explore Figma to mock up designs and prototypes.

**Performance Optimisation**: Learn techniques for optimising the performance of web applications, including lazy loading for large datasets.

**Game Logic**: Understand how to implement game logic, specifically in providing real-time feedback based on user input.

# Goals I Hope to Achieve in Completing the Project

**Technical Mastery**: Gain experience with integrating APIs into dynamic, data-driven web applications. Master React to create more complex web applications with interactivity

**Portfolio Piece**: Create a polished, interactive, and fully functional Pokémon site to showcase in my portfolio.

**Problem-Solving & Project Management**: One thing I struggled with on my ICS 314 final project is breaking down tasks into smaller and more manageable tasks. Thus, I want to improve my ability to break down large projects into manageable stages and tackle each challenge step-by-step. I also want to learn how to test and optimise an application for performance and user experience.

**User-Focused Design**: Gain experience by creating websites that prioritise the user's experience and usability.
