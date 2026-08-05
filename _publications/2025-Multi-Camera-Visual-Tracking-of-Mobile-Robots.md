---
title: "Surveillance Using Intelligent Agents: Multi-Camera Visual Tracking of Mobile Robots"
collection: publications
category: technical-project
permalink: /projects/2025-Multi-Camera-Visual-Tracking-of-Mobile-Robots
excerpt: >
        University of Minnesota - Twin Cities, Fall 2025<br>
        Introduction to Intelligent Robotic Systems (CSCI 5551) Final Project<br>
        Instructor: Nikolaos Papanikolopoulos<br>
        Co-authors: Max LaLonde, Alexandra Postolaki
---

University of Minnesota - Twin Cities, Fall 2025

Introduction to Intelligent Robotic Systems (CSCI 5551) Final Project

Instructor: Nikolaos Papanikolopoulos

Co-authors: Max LaLonde, Alexandra Postolaki

# Project Summary

A multi-camera surveillance system was developed to seamlessly track a mobile agent throughout a complex 3D environment. A Unity simulation was created, in which a mobile agent traveled random paths, while camera units dispersed throughout the environment identified and tracked the mobile agent, using the YOLOv8 algorithm. Each camera agent communicates with a central control system, coordinating tracking between camera units, allowing seamless transition of primary tracking responsibilities between nearby camera units. This system proved functional in certain conditions, but had many limitations due to lack of time and data for further training of the object detection model, and a need for further optimizations to the central control system. With these additional improvements, this system may prove useful in real-world surveillance applications, where targets may need to be tracked throughout a complex environment and across multiple fields of view.

# Personal Contributions
* Led development of Unity simulation environment and agent behavior systems
    * Selected a pre-made urban Unity environment
    * Added a node-based network to the environment, including a developer system to quickly expand and edit the network
    * Implemented an algorithm for a mobile robot to randomly move between connected nodes.
    * Created Unity cameras that took shots of the environment and displayed camera frames when detecting the mobile robot.
    * Wrote code to create and read from JSON files, allowing the Unity program to communicate with the Python script that performed object detection on individual camera frames
* Wrote the Abstract, Introduction, Previous Literature, Simulation, Future Work, Problems Encountered, & Conclusions sections.

# Skills Demonstrated:
* Robotic systems
* Computer vision
* Object detection and tracking

# Technologies Used
* Unity
* C#
* Python
* YOLO

# [Download Full Report](https://asbmeyers.github.io/files/Surveillance_Using_Intelligent_Agents_Multi-Camera_Visual_Tracking_of_Mobile_Robots.pdf)

