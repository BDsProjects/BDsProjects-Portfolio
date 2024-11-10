---
layout: single
title: "JetOp"
date: 2024-08-18
permalink: /projects/jetop/
header:
  teaser: /assets/images/projects/jetop-thumb.jpg    # Thumbnail in grid
  overlay_image: /assets/images/projects/jetop-banner.jpg  # Optional banner image
  overlay_filter: 0.5  # Darken the banner image
  actions:
    - label: "View on GitHub"
      url: "your-github-repo-url"


# Project-specific metadata
# project_type: Software Development
# status: In Progress  # or In Progress, Maintenance, etc.
# technologies:
#   - Python
#   - PyQt5
#   - JetCat V12.0 ECU
#   - Arduino
#   - C++
#   - ImGui
#   - Visual Studio Community 2022
#   - Visual Studio Code
# timeline:
#   start_date: 2024-05-30
#   end_date: 2025-03-05

#   # Optional sidebar info
# sidebar:
#   - title: "Role"
#     text: "Lead Developer"
#   - title: "Technologies"
#     text: "Python, PyQt5, JetCat V12.0 ECU,  C++,  ImGui"
#   - title: "Duration"
#     text: "10 months"
#   - title: "Status"
#     text: "Ongoing"
---

## Project Overview
During the Air Force Research Labs Aerospace Propulsion Out Reach Program senior design, I realized that the apps provided by JetCat were antiquated. These apps, written in visual basic 6, or similar, did not have a quick response time and were prone to glitches/faults. After my graduation, I began work on redesigning the app from the ground up. I based the app fully in python as that is my current primary language outside of Matlab. The goal of building a new app from the ground up was to modernize it while allowing for new features to be added. This was done by using JetCat serial communication, documentation and PyQt5 documentation.  

I completed the backend and successfully tested for functionality with it. This was done by testing the button commands for the fuel pumps, health checks, and additional commands. Operational testing was also conducted for the RPM increases, start up and shutdown functionality, etc. 

I however struggled with the development of the UI. Python is not the best tool to use for development of complex UI. I underestimated the difficulty of the UI development and began testing with differnt Python frameworks, HTML, C++, and will be looking into using GTK4. PyQt5 provided a good basis and was quick, but continued issues with the graphics solutions avaliable has shown that a change of frameworks may be necessary.

This python version of this project will will be undertaken by UD's Computer Science Department as a senior design capstone project. I have and will continue to move to a C++ developed App. This is currently within my  Jet-Go-Kart project, but may be moved to its own repository. 


