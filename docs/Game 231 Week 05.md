- [[index|Home]]
- [[Game 231 Week 04|Previous Week]]
- [[Game 231 Week 06|Next Week]]

# Week 5 - 2/15/23
- Exercise 3 Due

## [slides](slides/week5.html)

## Lecture Notes
Foley and recording on location (recording equipment; signal flow; microphone techniques; recording on location)

### Announcements
- I retooled the syllabus
	- cointinuing audio work
	- will get to Unity integration post spring break
- Does anyone care about the Trello board?
	- I might delete it
- Everyone should get their assignments submitted
	- I need to start submitting grades

### Reading Review
- [Level 4 - Styles and Genres]
- [Level 5 - Sound Design in Games]


### Some more useful Sound Effects
- Example audio file: [[noisy_VO.wav]]

#### Compression
- reduces volume over a certain point

##### Threshold
The db level at which the volume reduction will kick in. 

##### Ratio
The amount of gain reduction applied to signal over threshold.

For instance, with a 2:1 ratio, the gain is reduced by half. For 2 db over threshold, output gain will be 1, for 10db over, 5db out, etc. For 10:1, gain will be reduced by 90%, for 10db over threshold, 1db will go out.

##### Attack
Time, usually in milliseconds, that the compression will start one the level has gone over the threshold. This is useful if you want to keep _some_ of the attack of a signal.

##### Release
Time, usually in milliseconds, that the gain reduction will stop after the signal has dropped below the threshold. If compression sounds "choppy", often slowing the release time will make the effect sound smoother.

#### Noise Gate
- reduces volume under a certain point

#### Noise Reduction
- complex algorithm
- DeNoiser is the most user friendly

#### Distortion
- complex harmonic interaction

### Recording Audio
Introduction to Signal Path
- What a microphone is
- Signal Flow
- Mic techniques

- Room problems
	- https://www.youtube.com/watch?v=JPYt10zrclQ

- Common Voice Over fixes
	- Sibilance
		- Pop filter
		- De-esser
	- Room resonance
		- Use EQ notch
	- Mouth sounds
		- Give actor some water
		- use judicious editing
	- Even volume
		- use checkerboard edits to increse quiet levels
			- can result in uneven noise floors
		- compression and limiting

### Voice Over Assignment
- follow instructions, update tsv file
- are you familar with renting equipment?
  - [Equipment Rental Site](https://www.apu.edu/vpa/cinematicarts/equipmentfacilities/)


## Assignment
### Voice Over
https://github.com/APUGames/Game-220-Exercise-4
- Due Week 7

### Reading
- [[The Essential Guide to Game Audio Book Notes#Level 7 - Voice Over|Level 7 - Voice Over]]
