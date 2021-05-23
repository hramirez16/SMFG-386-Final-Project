## SMFG-386 Lab 6-Physical Viepoint of the Semester Project

Team Members: Sean Arend, Hector Ramirez, Aaron Jones, Jose Quintana

Spring 2021,California State University, Chico 

# Table of Contents:
1. Introduction 
2. Brainstorming
3. Bill Of Materials and Legend
4. Physical Viewpoint
5. Arduino Code
6. Backend Flowchart (Detailed)
7. Frontend Flowchart
8. CAD Embed

## 1. Introduction

The goal of this exercise is to finalize many of the details needed to construct an injection molding machine that had previously been conceptualized and discussed. This is the stage where members of the building team are supposed to make sure that parts that will be purchased will all work together flawlessly. This is important because it may cut down on errors that may arise later, when building the physical machine.

## 2. Brainstorming 
In this phase of development, we as the designers of this machine did not know much about the project ahead, or the specifications that we needed for the machine. Nevertheless, we got to work on what we believed to be the basic layout of how the machine should be. We were able to draw from our experiences in the Langdon Polymer Plastics Laboratory, as we had logged extensive hours on the Arbug 55-ton Injection Molder located there. Using this knowledge, we were able to come up with the diagrams you see below. Though our design is not nearly as complex as a commercial injection molding machine such as the Arburg, this was done to cut down on costs and complexity while retaining the basic functionality of the machine’s capability.

Block Diagram
![Brainstorm 1](https://user-images.githubusercontent.com/80607574/118383867-a90fea80-b5b6-11eb-9f77-aadf4e9ce2b8.PNG)

Lgical/functional View point
![Brainstorm 2](https://user-images.githubusercontent.com/80607574/118383949-5682fe00-b5b7-11eb-98d2-d86aa46f03ef.PNG)

Capabiltites Database 
![Brainstorm 3](https://user-images.githubusercontent.com/80607574/118383954-5be04880-b5b7-11eb-980d-6b50e2788e4a.PNG)

## 3. Bill Of Materials and Legend
Shown below are diagrams depicting where parts of the machine are located. Each of the two-digit alphanumeric codes that accompanies each of the pointer lines represents a line in the Bill of Materials that has information about the part and where it may be purchased. Some of the parts in the Bill of Materials are hidden or too small to be shown in the diagram and thus could not be labelled. To make it easier, however, the spreadsheet is divided into different sections that are representative of different areas of the machine. This is done to make it easier to determine which parts belong with which sub-assemblies.

### [Bill_Of_Materials.xlsx](https://github.com/hramirez16/SMFG-386-LAB-6/files/6528607/Bill_Of_Materials.xlsx)

![Balloons1](https://user-images.githubusercontent.com/80607574/113252840-3acacf00-9279-11eb-8532-d6e3d5e5724e.jpg)

![Balloons2](https://user-images.githubusercontent.com/80607574/113252869-43bba080-9279-11eb-8a78-7c5171b7e746.jpg)

## 4. Physical Viewpoint
In the diagram below, there is a physical viewpoint of how the internal electronics should work and be wired. This was done to make it easier to do the actual wiring once the physical parts have been gathered. Perfecting this stage can be quite challenging, however, as there will always be unforeseen problems that will arise as a machine is being built for the first time. Thankfully, tools like this can help cut down on the amount of problems by eliminating some of the more obvious ones that can be found in the virtual representation.

![Physical](https://user-images.githubusercontent.com/80607574/118384722-5ede3780-b5bd-11eb-8d6a-215165b25180.jpg)

## 5. Arduino Code
Note: Github would not allow us to upload individual ".ino" files, so they are in a zipped folder instead.
### [Arduino_Codes.zip](https://github.com/hramirez16/SMFG-386-LAB-6/files/6528602/Arduino_Codes.zip)

## 6. Backend Flowchart
This flowchart was not a requirement of the project, but was made so that all of the members of the design team could understand what the machine needed to be able to do. It is more in-depth than the Front End Flowchart in the next section, but shows more of the logic that will have to go on in the programming of the machine.

![Back](https://user-images.githubusercontent.com/80607574/113253096-a319b080-9279-11eb-860e-8d37ba39dac9.png)

## 7. Frontend Flowchart
This simpler flowchart shows how the user is to interact with the machine. This flowchart also showcases surface-level functionality of the machine, making it an easier diagram to communicate to a given 3rd party.

![Front](https://user-images.githubusercontent.com/80607574/113253150-b593ea00-9279-11eb-8ec6-29aab0a6767b.jpg)

## 8. CAD Embed

<iframe width="800" height="450" src="https://www.youtube.com/embed/UzUNsAMRM2g" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<div class="sketchfab-embed-wrapper">
    <iframe title="Injection Molder Assembly" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="fullscreen; autoplay; vr" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share width="800" height="450" src="https://sketchfab.com/models/a9d2bfdc74574008968b90028a32a86b/embed">
    </iframe>
   <p style="font-size: 13px; font-weight: normal; margin: 5px; color: #4A4A4A;">
        <a href="https://sketchfab.com/3d-models/injection-molder-assembly-a9d2bfdc74574008968b90028a32a86b?utm_medium=embed&utm_campaign=share-popup&utm_content=a9d2bfdc74574008968b90028a32a86b" target="_blank" style="font-weight: bold; color: #1CAAD9;">Injection Molder Assembly</a>
        by <a href="https://sketchfab.com/seanarend?utm_medium=embed&utm_campaign=share-popup&utm_content=a9d2bfdc74574008968b90028a32a86b" target="_blank" style="font-weight: bold; color: #1CAAD9;">seanarend</a>
        on <a href="https://sketchfab.com?utm_medium=embed&utm_campaign=share-popup&utm_content=a9d2bfdc74574008968b90028a32a86b" target="_blank" style="font-weight: bold; color: #1CAAD9;">Sketchfab</a>
    </p>
</div>

 
<iframe src="https://goodiecl.sirv.com/Spins/Extrusion%20Screw/Extrusion%20Screw.spin" width="800" height="450" frameborder="0" allowfullscreen></iframe>

<iframe src="https://goodiecl.sirv.com/Spins/Molding/Molding.spin" width="800" height="450" frameborder="0" allowfullscreen></iframe>
