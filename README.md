<b> Project Title: </b>
<br> Naval Postgraduate School Emergency Management Improvement

<b> Authors:</b>
<br> David Allen, Marcus Boswell

<b> Project Description:</b>
<br> The Naval Postgraduate School (NPS) is a critical institution for the U.S. Department of Defense (DoD) and must remain operational during crises. Emergency Management (EM) policies and procedures at NPS are designed to ensure the institution continues to function under extreme conditions. This project explores opportunities to improve NPS's EM program through an agent-based stochastic discrete event simulation of a biological outbreak. The biological outbreak emulates the fictitious "Rage Virus" from the cult classic film  series 28 Days/Weeks/Years Later. Overall, the project provides cost-tailorable recommendations that directly improve the NPS's EM program and provide institutional resilience.

This repository includes this ReadMe file, simulation model, technical paper, executive summary and final presentation. Most viewers will not need to look
deeper than the Executive Summary for sufficient detail and the "So What?" aspects of the project. For analysts and students I recommend the products be viewed in the following order as needed:
1. Executive Summary
2. Final Presentation
3. Technical Paper
4. Simulation Model

Descriptions of the products are below.

<br> <b> Executive Summary ("NPS_EM_Executive_Summary_09JUN24.pdf") </b> <br>
 A more concise product for leaders and decision makers. Is only one page long.

<br> <b> Final Presentation ("NPS_EM_Presentation_Final_11JUN24.pdf") </b> <br>
 A light-hearted presentation of the simulation and its results, containing ~29 slides. Intended audience is a classroom of peer students. The Presentation
 discusses the project's objectives, research questions, measures of performance, data collection methodology, and significant findings. The presentation
 also details the simulation model components, how major subsystems function, how agent decisions are made and provides a overview of the total model.

<br> <b> Technical Paper ("NPS_EM_Technical_Paper_11JUN24.pdf") </b> <br>
 Intended for analysts and is ~11 pages in length. Contains detailed analysis and resulting recommendations for improving the NPS's EM program. Discusses 25
 different outbreak scenarios, focusing on infection rates, infrastructure quality, and various human responses. Critical findings include average student
 survival rate of 24%, student density and infection rates are key factors in student survivability, and existing infrastructure would restricts rescue 
 efforts. 

 Recommendations include:
 1. Develop and include specific shelter-in-place and rescue procedures for such biological events in NPS's emergency management plans.
 2. Conduct annual rehearsals of these procedures with all students.
 3. Reduce on-campus student density through virtual classes, staggered schedules and limiting physical class sizes.
 4. Upgrade the campus infrastructure, including more secure doors and shutters, to better handle such emergencies.
 
<br> <b> Simulation Model ("NPS_Model_V3.spfx") </b> <br>
 A model representing a subset of NPS facilities with two agents; students and zombies. Adjustable parameters include the starting number of both agent types,
 infection rate, agent movement speeds and student self defense ability. Students desire to get away from zombies, find shelter with other students and
 reinforce their positions. Zombies seek to pursue students, break through their defenses if present, and spread the infection if able. The standard settings
 feature ~2000 agents, which can cause significant lag for some computers. This is especially noticeable when a large number of agents makes pathfinding
 decisions or a significant defense is assaulted.

 The simulation model was built with Simio software using a free academic license. Simio is simulation modeling software designed to help users create 
 simulate, and analyze complex systems. It is capable of object-oriented modeling, 3D visualization, both discrete event and continuous simulation,
 agent-based modeling, experimentation and has some optimization features.

