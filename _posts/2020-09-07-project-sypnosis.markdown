---
layout: post
title:  "Project Synopsis"
date:   2020-09-07 18:00:00 -0400
categories: synopsis
---

The goal of the Turtle Tower project is to create a tool for monitoring turtle nests, alerting caretakers of any risks and allowing nest sponsors to view video feeds of turtle emergence events. 

The primary users for Turtle Tower are scientists, caretakers, and nest sponsors. Users will interface with a cross-platform mobile-first application. Scientists will use the application to consume full access of data collected by the sensors. Caretakers will have access to the current data as well as alerts based on that data, and will be allowed to change their alert preferences to receive specific alerts. Nest sponsors will be given a video feed of the nest as well as an alert when the eggs are hatching.

Devices containing a temperature sensor, a usb camera, a radar sensor, and IMU sensor will be placed in beaches to monitor turtle nests. Each device will send sensor data to the Turtle Tower REST API on a timer, and listen to server events through a real-time queue.