---
layout: project
title: "JetOp"
categories:
  - Projects
date: 2024-08-18
description: "A short description of the project."
# image: /path/to/image.jpg
permalink: /projects/JetOp/


---

## Project Overview
During the Air Force Research Labs Aerospace Propulsion Out Reach Program senior design, I realized that the apps provided by JetCat were antiquated. These apps, written in visual basic 6, or similar, did not have a quick response time and were prone to glitches/faults. After my graduation, I began work on redesigning the app from the ground up. I based the app fully in python as that is my current primary language outside of Matlab. The goal of building a new app from the ground up was to modernize it while allowing for new features to be added. This was done by using JetCat serial communication, documentation and PyQt5 documentation.  

I completed the backend and successfully tested for functionality with it. This was done by testing the button commands for the fuel pumps, health checks, and additional commands. Operational testing was also conducted for the RPM increases, start up and shutdown functionality, etc. 

I however struggled with the development of the UI. Python is not the best tool to use for development of complex UI. I underestimated the difficulty of the UI development and began testing with differnt Python frameworks, HTML, C++, and will be looking into using GTK4. PyQt5 provided a good basis and was quick, but continued issues with the graphics solutions avaliable has shown that a change of frameworks may be necessary. 
##