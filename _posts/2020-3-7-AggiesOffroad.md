---
layout: post
title: Aggies Offroad Racing and Development
author: Kevin Schroeder
date: '2020-03-07 13:50:00 +0530'
category: engineering
summary: CSU's group for gearheads and Baja SAE followers
thumbnail: AORD/aord_logo.jpg
permalink: /engineering/aggiesoffroad
---

<link rel="stylesheet" href="/assets/css/custom-style.css">
<img class="blog-img" src="/assets/img/posts/AORD/buggy.jpg" />

## What is AORD?
Aggies Offroad Racing and Development (AORD) is a Registered Student Organization (RSO) at CSU for students interested in the engineering process behind offroad vehicles. It was reintroduced to CSU in the fall of 2016 (when I first came to CSU) by a group of motorheads in engineering who wanted to design and race an offroad buggy for their senior design project.

## Engine Workshop
This model is based off of drawings for <a href="/assets/files/SoumardTwin.pdf">Soumard’s Moteur Vapeur Bicylindre Modele</a>. It's a small tabletop design made for machine hobbyists to be able to manufacture. One of the challenges I faced in modeling it was that the drawings are in french, and many dimensions had to be inferred based on the processes used for machining. I took a couple of liberties in modifying the model to make it better suited for my taste. One of the things I changed was putting my first name initial and birth year on the plate covering the steam box. I also changed the flywheel to be sleeker looking. The reverse mechanism was omitted as well since the project already took a very long time to model without it.

<img class="blog-gif" src="/assets/img/posts/CADShowcase_SteamEngine/SteamEngineFront.gif"/>

## Competition
One of the headaches in making this model was the sheer part count associated with the assembly. I had to save constantly to avoid losing my changes whenever the program would crash due to the computational burden. This was especially true whenever trying to create a high resolution render. The program also crashed whenever a material change was made, so a lot of time was wasted without gain. There were
also geometries that required offsets from angled planes, which requires a lot of setup to perform in PTC Creo.

<img class="blog-gif" src="/assets/img/posts/CADShowcase_SteamEngine/SteamEnginePerspective.gif"/>

## Retrospective
I really liked the idea of making an engine, because it incorporates so much of what makes up the field of mechanical engineering. It's neat to be able to look back at this project after taking classes like dynamics of machines, machine shop, and thermodynamics. It's important for an engineer to know when designing an engine that the piston, connecting rod, chassis, and crank make up a four-bar slider-crank linkage, that the engine converts the enthalpy of the steam into work, and that the parts should be easily manufactured at reasonable tolerances. This project really challenged me in new ways, and I learned a lot from it because of that.
