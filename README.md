[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Kyle Hubbard
### Student number: 47435356


## 1. Player Experience (~700 words)

in my first section there are greated with 2 pathways one to the right and one to the left, if the player tries to go the the left they will see that the pathway has been blocked, however if they go to the right then encounter the cave area, the learning here is structure in a way that it first focuses on movement making sure the player is confortable this is done through the acid pit, next the player is greated by a pressure plat which upon steeping on causes the door ahead of them to open, this explains the concept behind what is an interactive element and what is not this is also followed through as once the player enter the new room open to them, the acquire a gun and pistol and are able to choose 2 pathways one is under the swarm of enemy, where there is a destructable pillar and above there are a few spikes and 5 chompers, the split was introduced as a way for the player to disover both pathways, and at the end of the cave is a switch that once shoot open the bridge that has been blocking the other pathway.

the other pathway requires the player to climb up a cliff and then jump across onto the floating island where they then discover the other type of enemy the spitter, the part isn't diffcult as to introduce the player to what the new encounter does, the only test one this path is at the end where there is a moving platform and a spitter at the goal.


![Acid pit](DocImages/acid_stage1.png)
![2 pathways](DocImages/stage1_alterateFight.png)
![spitters](DocImages/stage1_rangedFight.png)

in the second section is follows a spiral discovery pattern, whereby the player is restricted to move in that pattern, the focus of this level is more geared towards the drama and challenge of having to dodge and move around while attacking, the level achieves this why first setting the players expecations in the first ecounter where they have to time there jumps to navigate over the acid pit, then by they can drop down to the next part where they are greated by a checkpoint and a moving platform over a large spike pit and several obstacle such as a floating spike island and spitters placed along the plath of the moving platform. the challenge in this part is greatly increased as the player has to now focus on how to target the spitters while avoding all the obstacles that may harm him, the final part is the center area, this contains two pathways the user has to take to complete the level, they can be complete in any order but must be both completed to allow the pushable box to fall down and hit the pressure plate opening up the door to allow the player to progress to the next stage. this part has a decrease in drama as it more focused on discovery hover it is still challanging as the level still requires the player to be quick with how they responed to threats.

![2_1](DocImages/2_1.png)
![2_2](DocImages/2_2.png)
![2_3](DocImages/2_3.png)

the final sections is rather simple when the player enters it nothing to the left and and platform and an empty door, this is the level lowest tension as the player moves to the right they are stopped this is when they are greated by a cutscene and it then reveals that the door was containing a boss [* part of the 2d game kit *], the point of highest tension would be when the boss bar appears and the player is confronted with the fact they must kill the boss to pass, the boss has 3 stages where it the challenge increase on each one, the fist stage is an introduction of a moving spike platform that insure the player cannot hog the floating platform given for there aid, the next stage adds ads (chompers) to start spawning in requiring the player to now focus on both the chompers and the boss, on the final stage the player is given more health regens but is now greated with spitters on floating platforms.

![3_1](DocImages/3_1.png)
![3_2](DocImages/3_2.png)
![3_3](DocImages/3_3.png)


## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

(DocImages/stage1.png)

### 2.2. Checkpoints

### 2.1. Acid

### 2.3. Chompers

### 2.4. Health Pickups

### 2.10. Weapon Pickup (Gun)

### 2.11. Weapon Pickup (Staff)

### 2.7. Passthrough Platforms

### 2.6. Moving Platforms

### 2.5. Keys

### 2.9. Spitters

### 2.8. Spikes


## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram

### 3.2. Level Map – Section 1

### 3.3.	Level Map – Section 2

### 3.4.	Level Map – Section 3

## 4. Iterative Design (~400 words)

I employed an iterative design approach to significantly rework elements of the 2nd and 3rd stages in my game. Here's how the process unfolded:

Stage 2 Adjustments

Initial playtesting of stage 2 revealed that spitters positioned in the center section could fire through the tilemap, drastically altering gameplay and making the section unfairly difficult. My first iterative change was to adjust the spitters' lines of sight to prevent them from seeing the player within the corridor.  However, further playtesting showed that the spitters were reluctant to move along the flat central area. To address this, I removed the spitters and increased the number of chompers.

Stage 3 Revisions

Stage 3 underwent the most extensive iterative changes, primarily focused on the boss fight. Initially, the moving spike trap hovered too far over the platform, negating its intended purpose. Additionally, the platform could damage the player during health retreats. My initial design hadn't anticipated the obstructive nature of the platform, leading to a frustrating rather than challenging experience. I decreased the platform's range and size to prevent unintended player hits.

Next, I originally had chompers spawning on the right, but they became stuck on the boss and didn't meaningfully contribute to the fight.  Moving their spawn point to the left created a new issue where they could immediately hit the player upon appearing. To mitigate this, I carved a section out of the map, forcing them to travel further. This gives the player crucial reaction time and signals the chomper spawn.

Finally, stage 3 featured spitter enemies that added difficulty. I had platforms on both the left and right of the boss, but playtesting revealed that the right platform was impossible to hit. I relocated it above the health crates on the left, allowing players to target spitters more effectively and creating a more balanced level.

Conclusion and Future Refinements

These changes significantly improved playability, but there's always room for refinement. One notable issue in the stage 3 boss fight is that the confined space prevents the boss from using its third attack. Addressing this would enhance the challenge and excitement of the final stage.

