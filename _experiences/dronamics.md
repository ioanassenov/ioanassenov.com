---
title: "Structural Intern at DRONAMICS"
summary: "Intern on the structural engineering team at DRONAMICS, a Bulgaria‑based startup building cargo drones. Worked on dynamical and structural analysis for a new landing gear design."
skills: ["Dynamics", "Statics", "Simulink", "MATLAB"]
hero: "/assets/img/projects/dronamics/dronamics-hero.jpg"
date: 2024-07-01
layout: experience
---

# Modeling Motion: My Internship at DRONAMICS
During the summer of 2024, I joined [DRONAMICS](https://www.dronamics.com/) in Sofia, Bulgaria, as a structural engineering intern on the Stress Team. My task was to help model and analyze the aircraft’s landing gear system—a deceptively simple structure that hides complex dynamics. I began with a static analysis to size a carbon fiber beam for the main landing gear (MLG), but the real challenge started when I moved on to dynamic modeling. Each week brought a new version of the system: first, a three-degree-of-freedom (DOF) model that failed because I had assigned independent motion to the wheels when they were actually coupled to the fuselage; then a corrected model that used small-angle approximations to linearize the equations of motion; and eventually a more advanced five-DOF simulation that captured the elasticity of the landing gear beams themselves. It was in this stage that I developed a love for energy methods in dynamic and static analyses. I learned about Castigliano’s theorem, a clever way to calculate beam deflections through strain energy—a method that completely changed how I thought about structural mechanics. I was also exposed to Lagrangian dynamics, which gave me an elegant way to approach multi-degree of freedom systems and quickly construct models of complicated systems.


<div class="embed" style="width: 100%">
    <img src="{{ '/assets/img/projects/dronamics/bs-first-test.jpg' | relative_url }}" width="100%" alt="DRONAMIC's Black Swan airplane in flight"/>
    <p class="embed__caption">The Black Swan aircraft on its maiden flight.</p>
</div>

Later, my work shifted from the landing gear to the Flight Termination System (FTS): a rapid parachute deployment mechanism designed to save the aircraft during emergencies. My role was to model potential drop-test scenarios to determine what initial heights and velocities would produce the accelerations required for a safe deployment. It sounded simple, but translating those physical events into mathematical models was anything but. I built one- and two-DOF simulations to represent different test setups, wrestling with how to control the deceleration profile so that real-world data could actually be collected. In the end, both proposed tests had impractical height requirements, but the process itself—deriving equations of motion, testing assumptions, and confronting the limits of models—was one of the most rewarding learning experiences I’ve had.

Looking back, those six weeks were a crash course not only in analytical mechanics but also in the rhythm of engineering work. I learned that while I love diving into equations and seeing them come to life in simulation, what excites me even more is connecting those details to the bigger picture—understanding how each component contributes to the success of the whole aircraft. Working in Bulgaria’s most ambitious aerospace startup gave me a sense of what real engineering collaboration feels like, where theory meets manufacturing and innovation must coexist with practicality. More than anything, it clarified the kind of engineer I want to become: someone who bridges deep technical understanding with the ability to guide projects forward at the system level.

## Gallery

<div class="embed__gallery">
    <div class="embed__gallery-item">
        <img src="{{ '/assets/img/projects/dronamics/3DOF.png' | relative_url }}" alt="3 DOF model of aircraft and landing gear"/>
        <p class="embed__caption">3 DOF dynamical model of Black Swan's main landing gear.</p>
    </div>
    <div class="embed__gallery-item">
        <img src="{{ '/assets/img/projects/dronamics/5DOF.png' | relative_url }}" alt="5DOF dynamic model of aircraft and MLG"/>
        <p class="embed__caption">5 DOF dynamical model of the MLG (head on)</p>
    </div>
    <div class="embed__gallery-item">
        <img src="{{ '/assets/img/projects/dronamics/prototype.png' | relative_url }}" alt="Proposed MLG design visualization"/>
        <p class="embed__caption">Rough sketch of proposed MLG design in CAD.</p>
    </div>
</div>