# Perineal Suturing Simulation
> A virtual reality application for perineal suturing training in midwifery education

**Kaja Wollebæk Skråmo & Mina Marie Bye Tolfsen**
Master's thesis in Software Engineering – HVL / UiB, June 2026

---

## About

This application is a VR simulation for training second-degree perineal laceration repair, developed as part of the [CompMid](https://www.hvl.no/forsking/prosjekt/compmid/) research project (WP4) at Western Norway University of Applied Sciences (HVL).

The simulation gives midwifery students a safe and realistic environment to practice perineal suturing before clinical placement. It includes an onboarding level with instructions and a simulation level with hands-on suturing using virtual medical instruments.

Developed in **Unreal Engine 5.6** and tested on **Meta Quest 3**.

---

## Architecture

The project uses a subsystem-based architecture where components are organized by functional role.

| Subsystem | Responsibility |
|---|---|
| **Application Scenes** | Onboarding and simulation levels |
| **User Interface** | Onboarding menu, in-game menu, system menu |
| **Virtual Environment** | Clinical room, lighting, furniture |
| **Core** | Runtime state, scene transitions, input handling |
| **Simulation** | VR player, interaction system, suturing logic, anatomical model, visual feedback |
| **Assets** | Characters, props, materials, textures, and shared resources |
| **Movies** | Video demonstrations used in the in-game menu |

---

## Packaging and Deployment

This application was packed as an Android `.apk` file and deployed to the Meta Quest 3 via USB-C. 

The following guide was used for setup and packaging

[Unreal Engine 5.6.x for Meta Quest VR – Epic Games Developer Community](https://dev.epicgames.com/community/learning/tutorials/2KR1/unreal-engine-5-6-x-for-meta-quest-vr)
