- Lecture notes [[Game 220 Week 02#Hands on with destructive audio editing - Audition]] [[Game 220 Week 04#Advanced Sound Editing Concepts]]

## Sound Not Playing?
The media lab machines have a known issue where Audition will not play back sound. No sound will play, and the playback head won't move. If you run into this problem, try this:

- Go to `Edit -> Preferences -> Audio Hardware`
- Change the input device to `No Device`

## Effects Order of Operations
When applying effects in a non destructive DAW, be aware of the order you apply effects, as applying effects in a different order will yield different results.

For example, normalizing a clip to 0 db _then_ adding 3db of EQ on some frequency will likely **clip the audio**

_In general_, it's best to use this rule of thumb for ordering edits / effects:

0. `Save As` a safety copy if you don't want to lose your original
	- IE `audio_track__original.wav`
1. Clean up track
	- remove unwanted silences
	- increase gain (or normalize) to an audible level 
2. Apply non time based effects
	- EQ
	- compression
	- distortion
3. Apply time based effects
	- Reverb
	- Delay
4. Prep for delivery
	- add any final eq or compression 
	- add fade ins or fade outs
	- Normalize to delivery spec volume
	- `Save As` and choose your desired file type and bit rate / depth