---
title: "FPGA Obstacle Course Vehicle"
date: 2024-04-30T18:00:00-04:00
description: FPGA-controlled vehicle to complete obstacle course for Advanced Digital Logic Design class
menu:
  sidebar:
    name: FPGA Obstacle Course Vehicle
    identifier: academic
    weight: 10
tags: ["Academic", "Electrical", "Software"]
categories: ["Basic"]
---

## Assembly

Although the vehicle's design was done by my professor, each student laser cut the body of their vehicle, 3D printed the steering mechanism, and assembled the vehicle. Electrical assembly included soldering of surface-mount and through-hole components as well as wiring of sensors and motors. 


## Programming

All programming of the FPGA was done using the Quartus software. Part of the programming challenge included achieving consistency on the obstacle course while minimizing the amount of logic cells used by the FPGA. 


## Results

Once all of the assembly and programming were complete, I recorded a video of my vehicle completing the run successfully, which is shown below. My final report including more details and schematics regarding implementation and troubleshooting is also provided below. 

<div style="display: flex; justify-content: center;">
    <iframe 
        width="320" 
        height="560" 
        src="https://www.youtube.com/embed/aNrIAICuA0Y" 
        title="YouTube video player" 
        frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
        allowfullscreen>
    </iframe>
</div>
{{< vs 1>}}

{{< embed-pdf src="/files/ADLD-report.pdf" >}}
