---
layout: page
title: Senior Design
permalink: /sd/
---

## Overview
Partnering with the ISU Electric Power Research Center, our team had been tasked to create a mobile application to retrieve and present solar microgrid energy data from a dynamic array of measurement devices to serve as an efficient way for users to analyze the efficiency of power collection remotely. This application's primary objective was to serve as a intuitive way to store data collected, as well as present live data of the current readings at a solar microgrid site.

<div style="display:flex;align-items:center;">
  <div style="flex:50%;padding:5px;">
    <img src="/images/crate_pic.png" style="width:100%;">
  </div>
  <div style="flex:50%;padding:5px;">
    <img src="/images/crateVisit3.jpg" style="width:100%;">
  </div>
</div>

The application serves as an efficient way for public users and site maintainers to analyze efficiency of power collection and distribution of the microgrid from data presented through the application. Microgrid maintainers will be able to gain a better understanding of how a site collects energy over time. Site users will know what the crate could be used to power given how much power is stored in the microgrid's battery storage.

The main components our team had designed and were tasked to create are as follows:
* A data aggregator to collect all the data from the data sources. This will function to access and process the operational data of the microgrid into the form that the rest of the application needs.
* A database to store the collected data. This will store all the collected data from the data aggregator and will make the data readily available to the rest of the application. This database contains normalized data from the past and an indepentent table for recent, "live" data.
* A mobile app to display and interact with this data. This will be an iOS and Android mobile application. It will allow users to see not just current data readings from the microgrid, but also query and view ranges of previous data for the microgrid.
* A server to manage the data between the aggregator, database, and mobile app. This will allow the different pieces of the application to communicate between each other and maintain the integrity of the system.

### My Role
Team Lead, Backend Engineer

#### Big Picture Contribution
Help design backend components, establishing connections to crate, database, and frontend users. Facilate advisor and team meetings, ensuring team members are doing their part well mantaining healthy communication of ideas and hurdles with advisor team

### Skills Gained
Spring Boot, Leadership skills in engineering setting, project management

Documents:

Below you will find a video demostration of our finalized live version of our application :)

<div style="text-align:center;">
  <video width="560" height="315" controls>
    <source src="/videos/DemoV2 _com.mp4" type="video/mp4">
  </video>
</div>

<a href="/documents/sd-design_document.pdf">Project Design Document</a>

<a href="/documents/sddec21-21_poster.pdf">Project Poster</a>
