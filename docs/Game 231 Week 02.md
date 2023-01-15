- [[GAME 220 Syllabus|Home]]
- [[Game 231 Week 01|Previous Week]]
- [[Game 231 Week 03|Next Week]]

# Week 2 - 1/25/23
- Exercise 1 Due

## Lecture Notes
Game Audio Technology (sampling; MIDI; audio compression, middleware)

### Week 1 Lecture Quick Review
_5 minutes_

- Quick [[Game 231 Week 01]] review
	- what is sound?
	- what is amplitude?
	- what is frequency?
	
### Exercise 1 Review
- how to describe first 3 sounds
- what's the difference between the 2 EQ'd sounds
- answers for last section
- github issues?
- everyone have a decent text editor?
	- Quick note on what [Markdown](https://www.markdownguide.org/) is
		- human readable markup language
		- Are simple text files
		- Can be rendered in different ways
		- Becoming industry standard
				- Build into github and slack, as well as other tools
	- markdown preview is nice
	- [VSCode](https://code.visualstudio.com/)
	- [Atom](https://atom.io/)

### Reading Review
_15 minutes_

- [[The Essential Guide to Game Audio Book Notes#Intro]]
- [[The Essential Guide to Game Audio Book Notes#Level 1 - Animation Art Audio]]
- [[The Essential Guide to Game Audio Book Notes#Level 2 - Brief History of Games]]
- [[The Essential Guide to Game Audio Book Notes#Level 3 - Audio for Interactive Evironments]]

### Introduction to DAWs
- Digital Audio Workstation
- Destructive editing vs non destructive
	- Audition waveform view vs multitrack
	- Concept of splicing tape
	- Multiple lanes, mixing
	- "printing" effects vs effects racks and channel flow
		- "printing" effects
		- signal flow
		
### Hands on with destructive audio editing - Audition
- Let's clean up this file [[luxury car commercial raw take.wav]]
	- [ ] class: download file
	- trim silences
	- normalize
	- EQ
		- sounds like there's room resonance
		- something sounds "nasally"
- [ ] class: open file in audition
- waveform view
	- top left
	- multitrack view
		- not using audition multitrack in this class
- transport controls
	- pro tip, `space` is play/pause
- saving
	- careful when saving changes to original sound file

### Editing
- how to trim sound
- tape splice analogy
- cut at silences if possible
- cut at zero crossing
	- to avoid pops
- [ ] Class: clean up silences

### Volume, Fades
- volume aka gain aka level
- Measured in Decibles (dB)
- A quick, but complicated explanation about Decibels
	- Quick Video to explain: https://www.youtube.com/watch?v=WZLQoP6CM0k
	- is a relative measure of volume
	- db is measured against some standard
		- db SPL - relative to threshold of human hearing
		- we measure in dBFS - decibels reltative to full scale
			- 0 is maximum loudness capable
	- 6db-10db increase is about twice as loud
		- as perceived
	- 10 decibels = a bel = one order of magnitude greater
	- [handy wikipedia chart](https://en.wikipedia.org/wiki/Sound_pressure)
		-  Near total silence - 0 dB
		-  A whisper - 15 dB
		-  Normal conversation - 60 dB
		-  A lawnmower - 90 dB
		-  A car horn - 110 dB
		-  A rock concert or a jet engine - 120 dB
		-  A gunshot or firecracker - 140 dB
- Normalization
	- Peak normalizaiton
		- bring highest volume up to target level, usuually 0dBfs 
		- helpful to normalize clips to avoid adding volume elsewhere to compensate
	- Loudness normalization
		- bring average aplitude to target level
		- useful for broadcast, radio
		- useful if we want several similar audio files to play at consistent volume
			- dialogue
		- need to use dynamic compression to avoid clipping
			- more on this later
- Fades: changing volume over time
	- good for avoiding zero crossing clicks when looping or cutting
	- good for hiding edits
	- Audition will insert fades automatically when cutting into sounds
	- Two ways to create fades
		- Using envelopes add beginning and end of file
		- Effects -> Amplitude and Compression -> Fade Evelope
- Pan : balance of volume between left and right
- [ ] Class: peak normalize clip to -0.5 db

### EQ 
- Stands for "Equalization"
- Human hearing 20hz-20khz
- [Video on Identifying EQ bands](https://www.youtube.com/watch?v=0Ls7ZGH1PAk&t=34s)
- sub bass 
	- felt more than heard
	- often lost in reproduction
	  - need subs
- bass
	- complex waves sound muddy
	- travel farther
    - associated with larger objects
- lower midrange
	- "warmth"
	- chesty
- higher midrange
	- nasal
	- we're especially sensitive
- high
	- texture
	- enunciatrion and articulation
	- crispy
	- old people lose it 
- Styles of EQs
	- graphic
		- you may have seem this on devices or software
			- fixed EQ bands
			- fixed widths
	- parametric
		- adjustable bands and curves
		- frequency
		- gain
		- Q/width
- Different EQ curves
	- Peak
		- amplify or attenuate frequencies around some center frequency
		- using Q / width for finer / broader control
	- Highpass
		- cuts off low frequencies below a point
		- "passes" frequencies above that point
	- Lowpass
		- cuts off high frequencies above a point
		- "passes" low frequencies below that point
	- high shelf
		- amplify or attenuate all frequencies above a freq
	- low shelf
		- amplify or attenuate all frequencies below a freq
- Let's clean up this file [[luxury car commercial raw take.wav]]
	- [X] class: download file
	- [X] trim silences
	- [X] normalize
	- EQ
		- sounds like there's room resonance
		- something sounds "nasally"
- [ ] class: open file in audition
- [ ] Class: using Parametric EQ, find low frequency room resonance and attenuate
- [ ] Class: using Parametric EQ, find "nasally" midrage frequency and attenuate
- [ ] Class: using high shelf, raise higher frequencies for more articulation
- [ ] Class: using high pass, cut off all frequencies below performers range

### Saving / Rendering
- File types
	- We'll be working with .wav (PCM)
	- Be mindful of Frequency and Bitrate

### Intro assignment
_8:40_

[Exercise 2 Repo](https://github.com/APUGames/Game-220-Exercise-2/tree/main)
- will be given an asset list with sound names, descriptions and notes
- you'll find sounds and clean them up to spec

### Where to source sounds
#### Free
- [FreeSound.org](https://freesound.org/)
- [Open Game Art](https://opengameart.org/art-search-advanced?keys=&field_art_type_tid%5B%5D=13&sort_by=count&sort_order=DESC)
- [Loader.to](https://loader.to/en52/youtube-wav-converter.html)
	- Use this responsibly!
		- May be copywritten material
		- These sites often have fake "download" buttons
		
#### Paid
- [A Sound Effect](https://www.asoundeffect.com/)
- [StoryBlocks](https://www.storyblocks.com/audio)
- [Boom Library](https://www.boomlibrary.com/original-boom-library-sound-fx/)

## Additional Resources
- [What is a Decibel](https://www.youtube.com/watch?v=F4r3WI-JXlc)
- [Video on Identifying EQ bands](https://www.youtube.com/watch?v=0Ls7ZGH1PAk&t=34s)

## Assignments
### Lecture Addendum Videos
- [Fades in Audition](https://youtu.be/o2sn0A5ooUo)
- [Where to Source Sounds](https://www.youtube.com/watch?v=PTTc-c9SmiA)

### Exercise 2: Stand Alone Game SFX
- [Exercise 2 Repo](https://github.com/APUGames/Game-220-Exercise-2/tree/main)

### Reading
- Reassigned from last week:
	- [[The Essential Guide to Game Audio Book Notes#Intro|Intro]]
	- [[The Essential Guide to Game Audio Book Notes#Level 1 - Animation Art Audio|Level 1]]
	- [[The Essential Guide to Game Audio Book Notes#Level 2 - Brief History of Games|Level 2]]
	- [[The Essential Guide to Game Audio Book Notes#Level 3 - Audio for Interactive Evironments|Level 3]]
- [[The Essential Guide to Game Audio Book Notes#Level 5 - Sound Design in Games]]