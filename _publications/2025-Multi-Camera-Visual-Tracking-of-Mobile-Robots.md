---
title: "Multi-Camera Visual Tracking of Mobile Agents"
collection: publications
category: technical-project
permalink: /projects/2025-Multi-Camera-Visual-Tracking-of-Mobile-Agents
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

We developed a prototype multi-camera monitoring system in Unity that used YOLOv8-based object detection to identify a simulated mobile agent and coordinate observations across multiple virtual cameras. The project successfully demonstrated communication between Unity and Python-based detection pipelines and basic multi-camera coordination. However, the system remained a proof-of-concept. Cameras did not autonomously reorient to maintain visual contact with the target, and limitations in the training of the object detection model prevented reliable tracking performance in complex scenarios.

# Personal Contributions
* Led development of Unity simulation environment and agent behavior systems
    * Set up the Unity project directory
    * Selected a pre-made urban Unity environment, and added cameras, a mobile agent, and a node-based path network to the environment.
    * Implemented multiple developer end systems, including one to quickly expand and edit the node-based path network.
    * Implemented an algorithm for a mobile robot to randomly move between connected nodes.
    * Created Unity cameras that took shots of the environment and displayed camera frames when detecting the mobile robot.
    * Wrote code to create and read from JSON files, allowing the Unity program to communicate with the Python script that performed object detection on individual camera frames

# Skills Demonstrated:
* Robotic systems
* Computer vision
* Object detection and tracking

# Technologies Used
* Unity
* C#
* Python
* YOLO

# [GitHub Repository](https://github.com/asbmeyers/Multi-Camera-Visual-Tracking-of-Mobile-Agents)

