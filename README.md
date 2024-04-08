[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Irfan Hassan
### Student number: 47816260

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.

### 1.1. Discovery
What does the player learn? How does your encounter and broader level design facilitate learning in a way that follows good design practice?

### 1.2. Drama
What is the intensity curve? How does your design facilitate increasing yet modulating intensity, with moments of tension and relief? 

### 1.3. Challenge
What are the main challenges? How have you designed and balanced these challenges to control the difficulty curve and keep the player in the flow channel?

### 1.4. Exploration
How does your level design facilitate autonomy and invite the player to explore? How do your aesthetic and layout choices create distinct and memorable spaces and/or places?

## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

### 2.1. Health Pickups
When the player spawns in, they immediately spot a health pickup to their right and a wall to their left. 
The health pick up is placed right behind a spike so if the player walks into the spike he recoils back into the health pick up which restores his health. 
This teaches the player the purpose of the health pickup and how it only restores health if u are not on maximum health.

### 2.2. Spikes
The spike is placed right in front of the first health pickup.
Should a player run into it they quickly realize its purpose as it depletes their hp.
After the player overcomes the first obstacle/spike by jumping over it, 
there are 3 more spikes adjacent to each other to teach the player how far they are able to jump by holding down the jump button.

### 2.3. Weapon Pickup (Staff)
After the spikes, The player can pick up a staff from the remains of a skeleton which can be used to do a melee attack.
This mechanic is used to defeat the chomper which is right below the passthrough platform placed beside the skeleton which the player will progress to afterwards.

### 2.4. Passthrough Platforms
Beside the skeleton the player will face a wall with the first passthrough platform behind it which the player must learn to drop down by moving down and jumping to progress.
After defeating the chomper in the small undergroundarea below the passthrough platform he can move past the wall above by moving underground 
and then progress by jumping up through the next passthrough platform placed on the other side.

### 2.5. Chompers
In the underground area below the passthrough platforms the player meets the first chomper which charges at the player on sight and the player loses health when coming in contact with it.
The player must overcome this challenge by learning to use the staff to attack the chomper to be able to progress as avoiding it in the underground area is not possible.

### 2.6. Weapon Pickup (Gun)
After the passthrough platforms the player can pick up the gun which is used for ranged attacks.
This mechanic is used to defeat the spitter which is encountered after the acid pit beside the skeleton which the player will progress to afterwards.

### 2.7. Checkpoints
A checkpoint is placed before the acid pit which the player will run into.
In case the player falls into the acid pit, they will respawn at that checkpoint.

### 2.8. Acid
An acid pit which covers more distance than the player can jump placed after the first checkpoint and gun pickup.
Players falling into it respawns at the checkpoint with 1 less health.
There is a moving platform which the acid pit forces the player to use to progress as they can't jump past the pit.

### 2.9. Moving Platforms
The first moving platform placed above the acid pit after the first checkpoint and gun pickup.
The platform moves when it first becomes visible, meaning the player is guaranteed to know it exists and how it sort of works as soon as he sees the acid pit.
The player is forced to use the platform to move past the acid pit.

### 2.10. Spitters
Placed out of melee reach of the player in an elevated area after the acid pit.
The player will have to jump and shoot it to kill it.
//(Or the player can avoid it entirely which will just make the game harder but I cant think of any other way to force the player to use the gun except using text in game. 
The switch works but its optional and I dont want to figure out how to make it work in unity right now as I have little time ;-;)//

### 2.11. Keys
Placed underneath the spitter, the keydoor is visible underground by the camera which lights up a bit when the player picks up the key, hinting the player to collect more to open the door.

## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram

### 3.2. Level Map – Section 1

### 3.3.	Level Map – Section 2

### 3.4.	Level Map – Section 3

## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.

## Generative AI Use Acknowledgement

Use the below table to indicate any Generative AI or writing assistance tools used in creating your document. Please be honest and thorough in your reporting, as this will allow us to give you the marks you have earnt. Place any drafts or other evidence inside this repository. This form and related evidence do not count to your word count.
An example has been included. Please replace this with any actual tools, and add more as necessary.


### Tool Used: ChatGPT
**Nature of Use** Finding relevant design theory.

**Evidence Attached?** Screenshot of ChatGPT conversation included in the folder "GenAI" in this repo.

**Additional Notes:** I used ChatGPT to try and find some more relevant design theory that I could apply to my game. After googling them, however, I found most of them were inaccurate, and some didn't exist. One theory mentioned, however, was useful, and I've incorporated it into my work.

### Tool Used: Example
**Nature of Use** Example Text

**Evidence Attached?** Example Text

**Additional Notes:** Example Text


