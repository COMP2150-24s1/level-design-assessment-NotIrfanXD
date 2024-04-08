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
The player discovers the mechanics of the game one step at a time in various ways,
the first thing they learn is how spikes damage you when they walk into them and the boxes heal you when the character recoils from the spike into the health pickup.
This feedback loop of failure and success teaches the player throughout the first section of the game.
Other examples would include the chomper,spitter, acid pits and checkpoints.
Obstacles like the wall blocking the way also teach the player how to learn, an example would be how the transparent floors can be jumped through when blocked by the wall, 
the first chomper also acts as an obstacle forcing the player to learn how to attack it as they cant avoid it in the cramped space.
The game also encourages the player to discover more when it draws the players attention with the door glowing underground when the key is picked up, 
or when they see space on the other side of the wall when they encounter the first passthrough platform, as well as how the gun works when faced with the spitter out of reach.
This sort of level design makes the player learn game mechanics from the level itself.

### 1.2. Drama
The first section of the game is not so intense and encourages the player to learn the mechanics of the game, rewarding the player each step as they learn something new.(new items like the staff and gun can be considered rewarding)
From Section 2 however the difficulty increases slightly where the player will be forced to go at a slightly faster pace to be able to keep up with the moving platforms above an acid pit while avoiding the spitters attacking.
additionally the player can jump and shoot the spitters in section 2, when they are past the acid pit they can relax before dropping down to section 3.
Section 3 forces the player to go even faster as there are more spitters constantly throwing acid, they also have less space to jump over the spikes forcing the player to be more precise with the movement,
the player is forced to melee the chompers while moving fast due to the constricted space and the threat of acid being thrown at them(basically not be able to crouch and shoot the chompers).
The part with the moving platforms and acid still forces the player to go faster as the platforms only move a small distance and they must quickly and skillfully dispatch the chompers and spitters to progress to the door.
(note the cramped space makes it difficult to avoid the enemies, the chomper also forces u to kill it on the platform above the acid as it will knock u into the acid if u try getting on that platform without killing it.)
Reaching the door and getting out of the really intense section 3 feels really relieving, rewarding and satisfying as the player.

### 1.3. Challenge
Spikes, Acid pits, chompers and spitters are the main challenges in this level. Navigating on the moving platforms and finding keys can also be seen as another challenge.
The first section makes the players face the challenges seperately one by one letting the players get used to how to play this game.
The 2nd Section combines multiple challenges like the acid, moving platform and spitters to increase the challenge slightly for the player.
The jump from 2nd to 3rd section has the chompers and spikes in the cramped underground area where the player is once again forced to overcome multiple challenges at a faster pace with precise movement, all the while there is a threat from spitters below.
The last half of the 3rd section has all the challenges at a really fast pace, with moving platforms moving a tiny distance, spitters throwing acids constantly and chompers with a spike in a cramped space. 
The gradual increase in difficulty keeps the player from being overwhelmed and the big challenge in the end like that should feel satisfying as the player to overcome.

### 1.4. Exploration
Being able to see space behind the wall on the first passthrough platform encounter entices the player to try and get there.
Being able to see the door light up underground when picking up the first key gets the player to want to find out how to get there and figure out more about the door.
If the player skips the 2nd key and goes to the door after picking up the 3rd one, the player will be able to see the 2nd key from where they are standing at the door, 
this encourages them to backtrack and explore the part of the map they skipped to get the last key.

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
The player will have to jump to their max height and shoot it to kill it.
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




