- [[GAME 220 Syllabus|Home]]
- [[Game 231 Week 10|Previous Week]]
- [[Game 231 Week 12|Next Week]]

# Week 11 - 3/29/23

## Lecture Notes
FMOD

### Reading
- [[The Essential Guide to Game Audio Book Notes#Level 8 - Middleware]]

### FMOD

Working along with the Examples FMOD Project that comes with FMOD Studio

#### When we say "FMOD"...
- FMOD Studio: DAW like app for building sound events
- FMOD API: Low level API for integrating with games
- FMOD for Unity: Plugin for integrating Unity with FMOD

#### FMOD Studio

**Events**
An instanceable unit of sound content that can be triggered, controlled and stopped from game code. Everything that _produces_ a sound in a game should have a corresponding event

**Events VS Snapshots**
A snapshot is an instanceable unit of changes to the _project mix_ that can be [triggered](https://fmod.com/resources/documentation-studio?version=2.02&page=glossary.html#trigger), controlled, and stopped from game code

**Instruments**
Instruments are tirggerable elements that route audio content into the tracks of an event. Can be tiggered by parameter sheets or action sheets

- MultiInstruments

**Parameters**
Parameters can be changed with Unity game code. Parameter changes can tweak FMOD in several ways.

- Parameter Sheets

**Banks**
Collection of events. Events need to be assigned to at least one bank in order to be used by Unity.

**Building**
Compiles your FMOD banks/events to usuable packages for Unity to use.

#### Unity Integration
- [FMOD Unity Integration Docs Home](https://www.fmod.com/resources/documentation-unity?version=2.02&page=welcome.html)
- [FMOD Studio Listener](https://www.fmod.com/resources/documentation-unity?version=2.02&page=game-components.html#studio-listener)
	- Usually added to camera
- [FMOD Studio Event Emitter](https://www.fmod.com/resources/documentation-unity?version=2.02&page=game-components.html#studio-event-emitter) 
	- plays and stops an event or snapshot.
- [Live Update](https://www.fmod.com/resources/documentation-unity?version=2.02&page=user-guide.html#connecting-using-live-update)	
	- allows you to adjust mix and content on the fly while working in Unity
	
## Assignment
### Reading
- [FMOD Studio Concepts](https://fmod.com/resources/documentation-studio?version=2.02&page=fmod-studio-concepts.html)
- [FMOD Events](https://fmod.com/resources/documentation-studio?version=2.02&page=authoring-events.html)

### FMOD Example Projects
- In “FMOD Studio” open the “Examples” project 
	- Try playing with “Vehicles -> Car Engine” example 
	- Try playing with the “Character -> Player Footsteps” project. 
- These are great intros to what FMOD will do with parameter values.

### Project 2: Footsteps Project - ~Due week 12~ Due Week 15
[Project 2 Repo](https://github.com/APUGames/Game-220-Project-2-Footsteps)
  - record footsteps on multiple surfaces
  - looping
