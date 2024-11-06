
---
layout: essay
type: essay
title: "Final Project Idea"
date: 2024-11-04
labels:
  - Software Engineering
  - Nextjs
---

# Overview

## The Problem:

Many students in the ICS (Information and Computer Science) department face challenges when seeking academic help from peers due to social inhibition, time constraints, and limited engagement with fellow students. Additionally, organizing and scheduling study sessions, especially for specific topics or urgent needs, can be disorganized and inconvenient. Students also feel overwhelmed by constant notifications, leading to frustration and disengagement.

## The Solution:

PerchPals is a student support system designed to encourage collaboration, spontaneous study group formation, and peer assistance among ICS students. By providing a structured, gamified environment that rewards helpfulness and participation, PerchPals aims to make academic support more accessible and enjoyable. The system incorporates scheduling tools, an online calendar, and customizable notifications to facilitate collaboration while addressing common barriers such as time constraints and social inhibition.

# Mockup Page Ideas
Possible mockup pages for PerchPals include:

    - Landing Page: Overview of the app, call to action for new users to sign up or log in.
    - User Home Page: A personalized dashboard showing upcoming study sessions, notifications, and a quick way to join or propose new sessions.
    - Admin Home Page: Admin tools for overseeing activity, monitoring reports, and managing content.
    - User Profile Page: Allows users to input their course information, headshot, and optional availability for other commitments. Display earned points and badges.
    - Calendar Page: Displays upcoming and past study sessions. Users can filter by course, topic, and time. Shows both group study sessions and solo sessions.
    - Create Study Session Page: A page where Grasshoppers (students seeking help) can propose study sessions on specific topics and schedule a time.
    - Study Session Page: Details of a specific study session, including participants, topic, time, and a status tracker (e.g., ongoing, completed).
    - Game Mechanics Page(s): Displays the point or level system, solo and group rankings, and details of available rewards.
    - Notification Page: Where users can configure their notification preferences, including the option to mute notifications based on course commitments or personal time.

# Use Case Ideas

These are scenarios where the system is used from start to finish:

    - New User Signs Up:
        A new student visits the PerchPals landing page, signs up, and is prompted to complete their profile.
        During profile setup, the user inputs their current courses (Pueo), their upcoming courses (Mynah), and optionally their class and other commitment times.
        The user is given a tutorial on how the system works, how to propose study sessions, and how to participate.

    - Admin Managing the Site:
        An admin logs into the admin page, reviews the general activity feed, handles reports, and monitors user behavior.
        Admin can adjust settings or temporarily suspend users who violate guidelines.

    - Student Proposes a Study Session:
        A Grasshopper (student requesting help) logs in, selects a course, and creates a study session on a specific topic (e.g., “Write my essay on configuration management”).
        The proposed session includes a time (e.g., 8:30-9:30 pm) and notifies all available Senseis (tutors) and Grasshoppers.
        Students who are available can respond, confirming participation or proposing an alternate time.

    - Scheduling Immediate Help:
        A user can select "Right Now!" for immediate help and set a time (e.g., “ASAP”).
        This triggers a notification to all available Senseis and Grasshoppers, allowing them to form a spontaneous study group.

    - Checking Participation and Attendance:
        Users can view all scheduled sessions in the calendar and check their own attendance or participation status.
        After a session, users can rate their experience and provide feedback on the study session and any Senseis involved.

    - Responding to Notifications:
        Students can mute notifications based on their class schedule or personal time, blocking interruptions during important commitments.
        Notifications for upcoming sessions, feedback requests, or availability of new sessions are streamlined and customizable.

## Advanced Features & Solutions

    Text Message Interface:
        Students can receive and respond to notifications via text, confirming attendance or availability for study sessions.
        Text messages also serve as reminders for upcoming study sessions or events.

    Slack Integration:
        The app can integrate with Slack to send notifications about new study session proposals or changes.
        A Slack Bot could be used to help organize and suggest study groups based on student availability and course commitments.

    Gamified Point System:
        A system where students earn points for proposing or attending study sessions and for helping others.
        Points contribute to a level system that can unlock rewards like gift cards or recognition on the leaderboard.
        The system will prevent gaming by implementing safeguards to discourage fraudulent behavior (e.g., fake session participation or "gaming" the system with friends).

    User Grouping & Matching:
        Grouping mechanisms allow students to form study sessions by course, subject area, or even by skill level.
        Groups could be ranked based on the number of successful study sessions and feedback received.

    Encouraging Engagement:
        Reward active participation through game mechanics, badges, and rankings.
        This creates a motivating, fun environment where social inhibition is overcome by the peer pressure of earning points and leveling up.

# Key Design Goals

    Encourage ICS Student Engagement: Make PerchPals a core part of the ICS student community by encouraging collaboration through social interaction, rewards, and a seamless user experience.
    Minimize Risk of Inappropriate Encounters: By requiring all meetings to occur within ICSpace, the app ensures a controlled, safe environment for students to meet and collaborate.
    Promote Community and Face-to-Face Interactions: While online collaboration tools are available, the system incentivizes in-person interactions by offering points or other rewards for face-to-face study sessions.