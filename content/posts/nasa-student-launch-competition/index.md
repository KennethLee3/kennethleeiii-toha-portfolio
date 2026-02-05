---
title: "NASA Student Launch Competition"
date: 2025-05-02T18:00:00-04:00
description: CFO of Payload Team for 2024-2025 NASA Student Launch competition for Senior Design Project
menu:
  sidebar:
    name: NASA Student Launch Competition
    identifier: academic
    weight: 10
tags: ["Academic", "Mechanical", "Electrical", "Software"]
categories: ["Basic"]
---

## Formal Proposal

The [NASA Student Launch](https://www.nasa.gov/learning-resources/nasa-student-launch) competition is an annual event organized and hosted by NASA in which teams of engineers from universities around the United States compete to design, construct, and launch high-powered rockets. Teams submit a project proposal which must be accepted by NASA to be allowed to enter the competition. Each team must then provide comprehensive reports to NASA during the competition outlining their engineering progress to be allowed to remain in the competition, including a Preliminary Design Review, Critical Design Review, Flight Readiness Review, and Post-Launch Assessment Review. All of the details regarding the competition are provided in the handbook as shown below. 

{{< embed-pdf src="/files/NASA Student Launch Handbook 2025.pdf" >}}
{{< vs 2>}}

Part of the requirements for achieving the [Computer Engineering degree at Cedarville University](https://www.cedarville.edu/academics/programs/computer-engineering) include completing a senior design project. Successful completion of the project is evaluated by department faculty, who review our reports and presentations at the end of both semesters. My senior design project was working alongside two other electrical and computer engineering seniors to design, build, and test the payload for the Cedarville Student Launch (CSL) competition team. The full CSL team included eight mechanical engineers, one electrical engineer, and two computer engineers, along with faculty advisors. 

{{< img src="/posts/nasa-student-launch-competition/group-photo-EPL.jpg" title="Group Photo EPL" >}}
{{< vs 1>}}

To start the project, we had several meetings to determine important project parameters such as division of responsibility and reporting procedures. This included both full CSL team meetings and payload team meetings. Another important part of these meetings was decifering NASA's guidelines for our design and brainstorming how to meet these requirements completely but efficiently. The summary of NASA's payload requirements is as follows:

> Teams are tasked with designing, building, and flying a STEMnaut flight capsule capable of safely retaining four STEMnauts and transmitting, via radio frequency, relevant rocket and STEMnaut landing site data to a NASA-owned receiver located at the launch site.

My team and I began by brainstorming and researching what electronic components could be used in the payload, including microcontrollers, sensors, and radio transmitters. For each component we researched, we collected the product's cost, specifications, power consumption, mass, and a link to access it in the future. This spreadsheet allowed us to have a bill of materials for the payload which could be quickly altered if the team decided to change what components we were using. This spreadsheet also became the basis for other tables including the payload's mass budget, financial budget, and power consumption allowance to calculate battery life. 

{{< img src="/posts/nasa-student-launch-competition/components-list.png" title="Components List" >}}
{{< vs 1>}}

Since the project also required the payload to transmit data packets over the two meter band, my team and I needed to get our [FCC Amateur Radio Licenses](https://www.fcc.gov/wireless/bureau-divisions/mobility-division/amateur-radio-service). To do so, I studied for and passed the test to obtain my [Amateur Radio Technician License](https://www.arrl.org/ham-radio-licenses), callsign KF8CDC. 

After completing this initial research, we submitted our senior design proposal to our faculty advisor. A copy is provided below. 

{{< embed-pdf src="/files/ECE NASA Team Cedarville Proposal.pdf" >}}
{{< vs 2>}}

This same research along with significantly more details regarding operational and safety procedures was submitted to NASA, as shown below. Both proposals were accepted. 

{{< embed-pdf src="/files/CSL - Proposal.pdf" >}}
{{< vs 2>}}


## Preliminary Design Review

After our proposals were accepted, CSL began to work on what our design for the rocket and payloads would look like. This process requires that for each portion of the overall rocket design, multiple competing designs be proposed then evaluated using applicable analysis tools; this culminates in one design being chosen and formally proposed to NASA in the Preliminary Design Review. 

### Radio Transmitter Research

One of the core design decisions for the primary payload was the method of radio transmission and reception. NASA's requirements specified that the payload send data as packets over radio, which is typically accomplished using the [APRS](https://how.aprs.works) protocol. 

Our initial design plan was to use the *Friendcom* [FC-302](https://fcc.report/FCC-ID/UU3FC302U2F/2920489.pdf) transmitter on board the payload and the *Yaesu* [FTM-300DR](https://www.yaesu.com/product-detail.aspx?Model=FTM-300DR&CatName=Legacy) transceiver to receive the payload's data transmissions, both of which have APRS encoding/decoding functionality built in. Because both of these options were more expensive and had less thorough documentation, our faculty advisors recommended that we begin by using *Baofeng* [UV-5R](https://www.baofengradio.com/products/uv-5r) handheld transceivers for both sending and receiving transmissions. 

The cheaper price of the UV-5R handheld radios meant that we could maintain a reasonable budget even in the event of rocket recovery failure during testing which could destroy the payload. In fact, all of the planning and budgeting regarding rocket payloads was done in such a way that the system could quickly be rebuilt from scratch in the event of testing-induced destruction. 

### First PCB Implementation

### First CAD Implementation

{{< embed-pdf src="/files/CSL - PDR Report.pdf" >}}
{{< vs 2>}}

## Semester Report

{{< embed-pdf src="/files/ECE NASA Team Cedarville Semester Report.pdf" >}}
{{< vs 2>}}

## Critical Design Review

{{< embed-pdf src="/files/CSL - CDR Report.pdf" >}}
{{< vs 2>}}

## Flight Readiness Review

{{< embed-pdf src="/files/CSL - FRR Report.pdf" >}}
{{< vs 2>}}

## Flight Readiness Review Addendum

{{< embed-pdf src="/files/CSL - FRR Addendum.pdf" >}}
{{< vs 2>}}

## Final Report

{{< embed-pdf src="/files/ECE NASA Team Cedarville Final Report.pdf" >}}
{{< vs 2>}}

{{< embed-pdf src="/files/ECE NASA Team Cedarville User Manual.pdf" >}}
{{< vs 2>}}

## Post-Launch Assessment Review

{{< embed-pdf src="/files/CSL - PLAR Report.pdf" >}}
{{< vs 2>}}

## Project Summary Video

{{< vs 1>}}
<div style="display: flex; justify-content: center;">
    <iframe 
        width="600" 
        height="350" 
        src="https://www.youtube.com/embed/GDAyKgWNy-U" 
        title="YouTube video player" 
        frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
        allowfullscreen>
    </iframe>
</div>
{{< vs 1>}}
