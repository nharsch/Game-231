- [[GAME 220 Syllabus|Home]]
- [[Game 220 Week 02|Next Week]]

# Week 1 - 1/14/22

## Lecture Notes
### Intro
- Resources
	- Canvas being set up
		- Using this class notes repo instead
	- Book
	- Slack
	- Trello
- How class will work
	- lecture heavy at first
	- more of a workshop toward the end
	- assignments submitted through git
	- exercises count as full credit when full exercise is submitted
		- feedback isn't a markdown
- Student Introductions
	- what's your major?
	- what are you looking to learn in this class?

### About Me
- [nigelharsch.com](https://nigelharsch.com)
- Theatrical Sound Designer and Composer
	- Sometimes films - Sometimes games
- Web Developer
- Sound isn't new to me
- Game design is

### Course Intro
- Main Goals
	- Basics of Sound
		- What it is
		- How to talk about it
		- Sound as a material
	- Working with Sound
		- Sourcing
		- Editing
			- Adobe Audition 
				- To teach destructive editing
			- Pro Tools
				- For multitracking, to teach signal flow
		- Recording
			- Voice Over
			- Foley
	- Sound's role in games
	- Technical implementation
		- Asset Sheets
		- Unity Integration
		- Middleware
	- Git sidequest
		- GIt/github are industry tools
		- nothing too fancy here, just practice using it
		- unfortunately, not great with audio assets
		- but your changes are tracked and documented

### What is sound
- [quick sound intro video](https://www.youtube.com/watch?v=hfzCLClVO8g)
- changes in sound pressure level, detected by the ear
	- varies in different animals
- How we hear	
	- ![[ear-diagram.png]]
	- two ears = stereo
		- volume differences and slight delays in sounds tell us position
	- huge dynamic range of hearing
		- pin drop to jet engine 
	- we don't hear all frequencies equally
		- more sensitive to human voice
	
### Sounds as Waveforms
- what is a waveform, what does it represent?
	- temproal, time based
	- aplitude changes over time
		- ![[wave-graph.png]]
	- relative to zero point
		- negative and positive phase values
		- 0 is quiet
	- Amplitude is distance from 0 point
	- frequency is how many times it crosses zero point
		- one hertz = one oscilation per second
		- we hear from 20hz -> 20khz
			- [Hearing Range](https://en.wikipedia.org/wiki/Hearing_range)
	- when mixed, produce [interference](https://en.wikipedia.org/wiki/Wave_interference)
		- caused by waves amplifying or cancelling each other
- complex waves: many frequencies combined
	- simple waves have one frequency
		- sine wave
		- square wave
	- real sounds are complex
		- piano vs sine
			- ![[sine-wave.png]]
			- [[sine-220hz.wav]]
			- ![[piano-wave.png]]
			- [[piano-220hz.wav]]
		- piano note will have fundemental frequency	
		- will also have high and low "harmonics"
			- string harmonics
				- ![[Harmonic_partials_sm.jpeg]]
			- piano resonance
			- room reflections
		- when these waves are added _one_ new wav is perceived by an ear (or mic)*
			- *2 if stereo
			- ![[adding-waves.gif]]
- attack and decay
	- our piano again
		- ![[piano-attack-decay.png]]
	- a car passing
		- ![[car-passes.png]]
		- [[car-passes.wav]]
	- a drum beat 
		- ![[drum-loop-1.png]]
		- [[drum-loop-1.wav]]
	- a conversation
		- ![[convo.png]]
		- [[convo.wav]]
		
### acoustic sound vs electric vs digital
- acoustic is changes in atmospheric pressure
- how do we capture and store that?
	- phonograph
		- acoustic audio to etchings on a medium
	- analog electrical audio
		- analog electric audio is voltage in wire
			- converted from acoustic using microphones and speakers
		- stored on tape
- digital audio is a stream of numbers representing voltage measured n times a second
- acoustic and analog are continuous, digital is discrete (pixelated)
- ![[microphone-diagram.png]]
- ![[sampling-audio.png]]
- ![[analog-to-digital-conversion.png]]
- what digital sound gets us
	- consistent playblack
	- smaller storage
	- digital tools
	- synthesis
	- portability
	- accessability
	- DAWs
		
### Describing Audio
#### In Subjective Terms
- Common subjective words:
	- quiet
	- loud
	- muddy
	- boomy
	- boxy
	- honky
	- bright
	- warm
	- tinny
	- wet
	- dry
	- fuzzy
	- lofi
	- harsh
- What words do you use?
- Many subjective words are talking about objective properties of sound
- Most are about EQ
	- Muddy
		- lacks definition or articulation
		- could be a lack of high frequency content
		- could be too much low frequency content
		- could be too much reverb (more on that later)
	- boomy, boxy
		- often has to do with something resonating
			- often small rooms
			- if one resonant frequency, sometimes easy to fix
	- bright, tinny
		- too much high end
	- warm
		- has pleasing low mid
		- could describe harmonic distortion or compression
- Some are about reverb and reflections
	- wet
		- lots of reverb
	- dry, direct
		- very little or no reflections
	- honky, boxy
		- too many early reflections
- Some are so vague to be almost useless
	- fuzzy
		- eaxtraneous, non signal noise
			- could be background
			- could be recording artifacts
		- bad EQ
		- distortion
		- signal loss
		- background noise
		- digital compression aritifacts, bitrate
	- Lofi
		- EQ that favors midrange, like phones, phone speakers
		- Low bitrate or digital compression artifacts
		- analog tape hiss, warble
		- vinyl surface noise
		- Genres of music
			- "Lofi beats to study to"
	- Harsh
		- ???
- When being creative, vague is good
	- Shiny wood
	- Dull metal
	- It should sound like dawn
	- Use carefully
	
#### Objective Analysis
- When things sound bad, look for these
- Volume
	- is it too loud or too quiet
	- should the sound fade in or out
	- Are some parts way too loud and some way too quiet
- Frequency
	- Are you hearing too much of one frequency range
		- high
		- mid
		- low
- Reflections, Space
	- Can I hear the room / space where this was recorded
	- Does the content sound too dry as to sound artificial
	- distance from source
		- sounds too far away
- Concept: Signal vs Noise
	- How loud is the content is heard vs non content
	- Recording artifacts
	- Environmental Sounds
	- mouth clicks, clothing ruffling, sniffles

### Additional Resources
- [Video on Describing Audio Objectively](https://www.youtube.com/watch?v=wdkrqiqz5ek)
- Science Experiment on analog vs digital
	- [Mics, Speakers, Electric Audio](https://youtu.be/_xHw-RRc-_U)
- Git resources
	- [Git Branching Video](https://www.youtube.com/watch?v=Ir1KfssniRI)
	- [Git Kraken Video](https://www.youtube.com/watch?v=ub9GfRziCtU&feature=emb_logo)
	
## Assigments
### Exercise 1: 
- [Exercise 1 Repo](https://github.com/APUGames/Game-220-Exercise-1)

### Assigned Reading: 
- [[The Essential Guide to Game Audio Book Notes#Intro|Intro]]
- [[The Essential Guide to Game Audio Book Notes#Level 1 - Animation Art Audio|Level 1]]
- [[The Essential Guide to Game Audio Book Notes#Level 2 - Brief History of Games|Level 2]]
- [[The Essential Guide to Game Audio Book Notes#Level 3 - Audio for Interactive Evironments|Level 3]]