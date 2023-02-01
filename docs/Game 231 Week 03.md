- [[index|Home]]
- [[Game 231 Week 02|Previous Week]]
- [[Game 231 Week 04|Next Week]]

# Week 3 - 2/1/23
- [slides](slides/week3.html)
- [Exercise 2](https://github.com/APUGames/Game-220-Exercise-2/tree/main) due

## Catch up
- Everyone have Books?
- Reading?
- Headphones?
- Assignment 2?

## Lecture Notes
Sound Design for User Interfaces (file formats; editing techniques; menu interface sound design; unified soundscapes; synthesized interface sounds) 

### Reading 
_25 minutes_

- [[The Essential Guide to Game Audio Book Notes#Intro]]
- [[The Essential Guide to Game Audio Book Notes#Level 1 - Animation Art Audio]]
- [[The Essential Guide to Game Audio Book Notes#Level 2 - Brief History of Games]]
- [[The Essential Guide to Game Audio Book Notes#Level 3 - Audio for Interactive Evironments]]
- [[The Essential Guide to Game Audio Book Notes#Level 5 - Sound Design in Games]]

### Cover Missed EQ section
- [[Game 231 Week 02#EQ]]

### Advanced Sound Editing Concepts
8:00
#### Speed and Pitch
- related by default
	- dropping both results in lower EQ range
- can be separated with digital algorithms
	- time stretch: slowed without changing pitch
	- pitch effect: raise pitch without speed
	
#### Reverse
- reverses

#### Reverb / Delay aka "time based"
- delay is repition of sound
	- usually at decresing volume
	- sometimes decreasing EQ
	- simple delay is one regular repeat over fixed time
	- "spacey" 
- reverb
	- many delays all so close together they "blur"
	- "breathy"
	- "wet"
	- "cold"

#### Compression / Gate
- Gate more important

#### Noise Reduction
- complex algorithm

#### Distortion
- complex harmonic interaction

#### Effects order matters	
This will sound different
```mermaid
graph LR;
source(Source signal) -- Dry singal --> EQ;
EQ -- EQ'd signal --> Reverb;
Reverb -- Reverb'd signal --> Output(Output);
```
Than this	
```mermaid
graph LR;
source(Source signal) -- Dry singal --> Reverb;
Reverb -- Reverb'd signal --> EQ;
EQ -- EQ'd signal --> Output(Output);
```

### Creative sound techniques
- slow it down
- speed it up
- creative EQ
- reverse it
- put attack of one sound to decay of another
- put lots of reverb on it
- distort it

### Sound Design Inspirations
[Article on Ben Burtt](https://www.popularmechanics.com/culture/movies/news/g2486/how-6-of-star-wars-iconic-sounds-were-conceived/)
- Ben Burtt hitting high tension wire
[99% Invisible Episode on UI Sounds](https://99percentinvisible.org/episode/episode-15-the-sound-of-the-artificial-world/)


### Help and Questions about Using Audition

### Explain Assignment

## Assignments
### Exercise 3: UI Sound Library  - due week 5
[Exercise 3](https://canvas.apu.edu/courses/45722/assignments/798501)
> You are tasked with creating User Interface sounds for the menu page and inventory screen of an adventure/survival game. These sounds are _non diagetic_, but they should fit the overall theme of the game, which is "outdoor survival". The client requested that the sounds "sound organic" and "not electronic".

### Reading
- Catch up from last week: [[The Essential Guide to Game Audio Book Notes#Level 5 - Sound Design in Games]]
- [[The Essential Guide to Game Audio Book Notes#Level 4 - Styles and Genres]]

## Optional Additional Reading
- [Video: Differences between Sample Rates](https://www.youtube.com/watch?v=fZzMXdxbOes)
- [Video: Differences between Bit Depths](https://www.youtube.com/watch?v=ubCMI3Jq6e4)
- [99% Invisible Episode on UI Sounds](https://99percentinvisible.org/episode/episode-15-the-sound-of-the-artificial-world/)
- [Article on Ben Burtt](https://www.popularmechanics.com/culture/movies/news/g2486/how-6-of-star-wars-iconic-sounds-were-conceived/)
