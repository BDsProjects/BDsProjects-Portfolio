---
layout: single
title: "Air Force Research Laboratory's Aerospace Propulsion Outreach Program Competition"
date: 2024-08-18n of the project."
permalink: /projects/project-apop
header:
  teaser: /assets/images/projects/jetop-thumb.jpg    # Thumbnail in grid
  overlay_image: /assets/images/projects/jetop-banner.jpg  # Optional banner image
  overlay_filter: 0.5  # Darken the banner image

---

## Project Details
The AFRL APOP Competition is given as a senior design project spanning the fall and spring semesters for UDayton's MEE 431L and MEE 432L 'capstone' classes.  This competition centers around research and design of small turbine technology. For the 2023-2024 competition,  the topic is researching, designing, and creating a thrust reverser on a JetCat P100-RX. As this project is worked into the senior design classes, the full length of the project included designs reviews and milestone meetings with both UD and the AFRL mentor team, midterm and final presentations for both semesters, and a final report covering all work done in the first semester, and all work to date including testing results from the testing completed at AFRL's facility. 

I had many diverse roles within the project but was primarily responsible for mathematical models of the thrust reverser, cycle analysis of the turbine, CFD modeling of the stock nozzle and thrust reversers, documentation creation/upkeep, and data integrity. 

I am currently reverse engineering and redesigning of the turbine software to provide a better and more detailed interface. This will contain more features than the standard app, while also being built in modern languages, Python and Arduino. This will be completed by the next APOP project, starting at the end of August 2024. I am also working on data-integrity and handoff measures for the future competition teams at UD.

## Technical Details 
I was responsible and shared responsibility for many different components of this project including but not limited to, turbine operation, electronics configuration, software versus basic controller use for turbine control, cycle analysis, thrust reverser performance calculations, Computational Fluid Dynamics (CFD) of thrust reverser and stock nozzle models, technical documentation, and data integrity measures. 

Due to data loss from prior years, we started nearly from scratch with turbine operation. There is essentially no documentation on the JetCat software, so I set out to get it working, while also figuring out standard operation with their provided software, drivers, and manual controllers. I developed the directions and procedures for the software and manual controller method, along with safety procedures before, during, and after operation. I also wrote and performed the processes for updating the ECU to the newest versions. 

For the calculations, I completed the non-ideal cycle analysis for the P100-RX using its datasheet, its operation output, and measured forces from our 5 axis sensor. I then used efficiencies typically used in UD's AEE 513, Air Breathing Propulsion class. I used this model to aid in the thrust reverser performance calculations as well, which were done using the conservation of momentum for flow hitting and being redirected by angled plates. 

I performed CFD analysis on the thrust reverser designs, along with the stock nozzles for performance comparisons. I used SolidWorks as it was the tool I had experience with, and the time needed to run the simulations. These analyses were used to assist in determining which design(s) would be best to move into the manufacturing and testing stage with. The manual claculations were used as the basis and in the end, we chose a pneumatically actuated clamshell design. In the future I would like to further develop my skills with CFD in Ansys, or Converge CFD. Using SolidWorks, I also created some models of the P100-RX components. Included below is a picture of the secondary turbine shaft and nozzle. 
![alt text](assets\images\SecondaryShaft.png "Secondary Shaft")

loading nozzle image test

![alt text](/assets/images/nozzle.png)


## Non-Technical Details
As I previously mentioned, we completed design reviews for the typical stages in the product realization process. This included meetings covering the Initial Design Ideas and Constraints, Preliminary and Detailed Design Review (PDR), and a Final Design Review and Production, all conducted with UD professors, and AFRL/AFLCMC/AFRL-RQT mentors. 