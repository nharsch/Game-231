---
aliases: Horowitz and Looney
---

## Intro

## Level 1 - Animation, Art, Audio
- What is a platform
- Story vs Interactivity

## Level 2 - Brief History of Games
- Video Game History
	- Primitive synths to PCM
	
## Level 3 - Audio for Interactive Evironments
- Non linearity
- Digital Sound Basics
	- Sample Rate
	- Bit Depth
- File Compression
	- not to be confused with "Dynamic Compression", which deals with volume
- MIDI
- Synthesis
	- analog synthesis
		- [NES Sounds](https://www.youtube.com/watch?v=la3coK5pq5w)
	- FM
- Digital Audio
- Middleware
- Though much more resources available on PC & Platform, eesources now constrained by mobile device capacity, internet speed for online

## Level 4 - Styles and Genres
- Gameplay Mechanics
- Types of Games

## Level 5 - Sound Design in Games
- Sound changes perception of events
	- collision or pass through example
- Practical sound effects played live
- Foley
- Diagetic vs Non Diagetic
	- Diagetic = In reality of world
	- Non Diagetic = Music, voice over, flashback audio
- Dynamic Audio
	- Audio designed to change in responses to changes in game
- Interactive Audio
	- Specifically responds to user player directly
		- Sword swoosh sound
- Adaptive Audio
	- Reaction to gameplay rather than user directly
		- Music changes from level to level
- Sound Effects Layers	
	- Background Ambience
	- Foreground sounds
	- Interface sounds
- Sound Formats
	- Open, uncompressed
		- wav
		- aiff
	- Open, compressed
		- mp3
		- ogg
		- FLAC
		- AAC
	- Others
- Birth of Sound Design
	- Kind of Game
	- Target Audience
	- Game pace
	- Platform
	- Audio budget
	- Hardware space
- Asset List
	- List of every sound that occurs in the game
	- Name of sound broken out by type (music, sfx, voice over)
	- filename
	- description
	- one shot / looping
- Where do sounds come from?
- Editing techniques
	- One shots
	- Looping
	- EQ
	- Compression
	- Delay
	- Reverb
	- Sound Layering
	- 3D Sound
		- mostly handled by game engine
- Creating sounds
	- Sound synonyms
	- creative reuse
		- wilhelm scream
- Audio Team Roles
	- Audio Director
		- Owns audio
	- Audio Lead
		- Coordinates sounds
	- Sound Designer
		- Sources / creates sounds
	- Audio Programmer
		- Integrates into game engine
- job types

## Level 6 - Composing
- New "hybrid" composers
- Thinking about music for a game
	- overall mood and tone
	- time and place within game
	- Locations within game
	- Characters in game
	- Pace of Game
	- Increase immersion
- Form and structure
	- Cinematics
	- Interactive
	- Looping and branching
	- stem mixes
	- transitions
		- fade out
	- Stinger
		- cover transitions
	- cross fade
	- cue to cue
		- with music, needs to happen intelligently
	- Interactive vs Adaptive music
		- Interactive - user makes changes based on music
			- DDR, RockBand
		- Adaptive - music responds to changes in game
			- cue changes during battle
	- Elements of Music
		- Tempo
		- Key
		- Instrumentation
		- Volume/dynamics
	- Music Team
		- Music director - oversees creative direction
		- producer - oversees creative direction of recording and "production" of music
		- composer - writes music
			- composer is often producer these days
		- Orchestrator - writes music for individual players in orchestral recordings
		- recording engineer - handles technical aspects of recording
			- often composer
		- mix engineer - handles balance of recording
			- often composer
		- mastering engineer - produces final tracks
			- often composer
- composing techniques
- interactive vs adaptive

## Level 7 - Voice Over
- Functions of voice over in games
	- game feedback
	- narrative
	- dialogue
- Roles in VO production
	- Producer 
	- Writer
	- Talent Agent
	- VO Actor
	- Union vs Non Union
	- Voice Director
	- Recording Engineer
- Scripts
	- many shapes sizes
	- will often look different than plays/screenplays, important to communicate the overall character to Actor
- Tools
	- Mics
		- Dynamic
			- good for loud sounds
		- Condenser
			- Need phantom power
			- good for clarity
		- Cardiod/ unidirectional
			- spotlight audio source
			- good for VO
		- omnidirectional
			- flood light audio source
			- good for environments, moving targets
- Formats usually PCM 48/44.1k 16/24 bit
- Preparing space
	- quiet
	- dead, not many reflections
- Editing engineer
	- edit and balances each take
	
## Level 8 - Middleware
- Pre middleware
	- bespoke solutions based on game
- Middlware
	- creates a standard tool for audio implementation
	- allows integration with game state using events, parameters and hooks
- Middleware lets you
	- Develoop basic sound functions like when where are how loud a sound plays
    - Create dynamic scores
	- Mix and master game audio in real time
	- Profile audio in real time
	- Create 3D environments
	- Generate sound banks
	- deploy sound for multiple platforms and markets
		- internationalization
	- Compress audio
	- work with several game engines
- 3D sound in games
	- Volume and Distance
	- Occlusion
		- sound filtered by environment
	- Obstruction
		- Direct path is muffled but not enlosed
	- Environment morphing
		- changing reverb based on space
	- Audio Middleware Structure
		- GUI
			- where the audio work is done
		- API
			- what the audio programmer uses
	- Current tools
		- FMOD Studio
		- Wwise
		- Others
		
## Level 9 - Preparing Audio
- Mixing for Games
	- Bounce sounds out of DAW
	- Trim sounds
	- Balance all sounds
	- create seamless loops
	- provide asset list
	- note on reverb - usually handled by middleware, so "dry" cues often best
- Uses of Looping
	- sound effects
		- walking, machine gun
	- ambient backgrounds
		- long storm cue
	- music
- Making perfect Loops	
	- loop at zero crossing
		- center point of no volume
	- if no good zero crossing exists at desires loop point, use fades
	- clicks cause by abrupt, sharp changes
- Audio format choices
	- uncompressed audio usually better, unless resource constrained
	
## Level 10 - Game Engines
- Emergence of Game Engines
- What Game Engines Do
	- render images and 3D models
	- import and arrange sound files
	- render light 
	- physics engine
	- animation of objects
	- AI
	- Scripting
	- Asset control
- Current Engines
	- Unity
	- Unreal
	- CryEngine
	- Stencyl
	- Cocos2d-iPhone
	- Codea
- How Game Engines think about sound
	- sounds are assets, no different thatn any other piece of game

## Level 11 - Intro to Unity
- Unity Free/Basic vs Pro
- Platform Development Support
- Unity's Audio Engine based on FMOD
- Filtering/Effects
	- HiPass
	- LowPass
	- Echo
	- Distortion
	- Chorus
	- Reverb
	- Reverb Zone
- How sound works in Unity
	- Audio Listener and Audio Source
	- Triggering audio sources
		- mostly need to be in code

## Level 12 - Basic Audio in Unity 3D
- Importing Sound
- Import Settings
	- Native vs Compressed modes
		- decompress on load
		- compressed in memory
		- stream from disc
	- 3D vs 2D
	- Convert to Mono
- Putting a Sound into Gamespace
	- add AudioSource to objects
- AudioSource component settings
	- Mute
	- Bypass
	- Play on awake
	- loop
	- priority
	- volume
	- pitch
- 3D sound settings
	- min distance
	- max distance
	- volume curve
		- linear 
		- logorithmic
	- doppler level
	- pan
	- spread
		- used for surround
- Triggering a sound in Unity
	- add AudioSource to Box Collider "Is Trigger" option
- Scripting example

## Level 13 - Web and Mobile Games
- Structure of iOS
	- Core OS - containe Darwin kernel and vital system extensions
	- Core Services - handles services suck as in-App purchasing and XML support
	- Media Layer - modeia-oriented frameworks such as Core Audio and Core Display
	- Cocoa Touch - multitasking, touch-based imput, high level system services
- iOS Audio Specifics
	- 32 simultaneous streams available
	- standard format is .CAF
- Sound on Android
	- runs on Linux Kernel, needs OpenSL ES to run
- Mixing Audio for Small Format Delivery
	- Use harmonicly rich tones
		- not sine waves
	- Make sure Low EQ sounds have high EQ components
		- Like, kick fundemental vs beater head
	- HTML Audio

## Level 14 - Jobs in Game Audio
- Grand Theory of Adaptaion
	1. Quality
	2. Perseverance
	3. Parallel Movement
	4. Conceptual Continuity
	5. Tell the world
	6. Critical Mass
- Questions
	- Music or Sound?
	- Programming experience or interest?
	- Interested in evolving sound?
	- Good at networking?
- Marketing Yourself 
	- How to create website