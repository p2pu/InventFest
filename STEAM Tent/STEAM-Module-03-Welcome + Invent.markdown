---
title: Intro
published: true
---

# Synth Module Week 3: Video Game Maestro

## Your Weekly Invention: Game Sound Design
We all remember the iconic music of Zelda, Sonic and Tetris (well, maybe some of us were more Pong folks). This module will show you the amazing creative freedom of sound design. 

This module will build upon what you'e learned so far from using the 
the [Synth Kit](http://littlebits.cc/kits/synth-kit) and the [Arduino Kit](http://littlebits.cc/kits/arduino-coding-kit). 

## Design Constraints
1. Your song will need to feature loops for "victory" and "defeat."
2. The sound should last at least 60 seconds. 
3. When you upload your project, say a bit about the game you envisioned accompanying this sound.  

## Inspiration, Examples and Support

1. [Beginner Percussion and Melody Synth](http://www.instructables.com/id/Beginner-Percussion-and-Melody-Synth/)
<iframe width="420" height="315" src="//www.youtube.com/embed/VetxUft4gE4" frameborder="0" allowfullscreen></iframe>

2. [Arduino MIDI Synth with LFO, Portamento, and Pitch Wheel](http://littlebits.cc/projects/arduino-midi-synth-with-lfo-portamento-and-pitch-wheel)
<iframe width="653" height="367" src="//www.youtube.com/embed/7EXh6XY0Fgk" frameborder="0" allowfullscreen></iframe>

3. [Advanced Synth Circuit with Ring Modulation and Keyboard](http://littlebits.cc/projects/ring-modulation)

<iframe width="560" height="315" src="//www.youtube.com/embed/3yz6iNC-xrA" frameborder="0" allowfullscreen></iframe>

4. [Arduino at Heart Music Machine](http://littlebits.cc/projects/arduino-at-heart-music-machine):

<iframe width="560" height="315" src="//www.youtube.com/embed/Cg3JyWSR_dE" frameborder="0" allowfullscreen></iframe>

>STEP 5

>To compose your own music: 
A. Identify the notes you want to play. I don’t read music well, so I go by piano keys, and I got a LOT of help from my musician brother Joe Alvear! (Thanks, Joe! Could not have done it without you!) You can use whatever method works for you. Enter these values as a series of frequencies separated by commas in the int melody[] section. Be very careful with notes that go up or down an octave. 
B. Identify the duration of each note in the int noteDurations[] section. This was very tricky for me. Lower numbers mean the note last longer; higher numbers are shorter duration. Also some songs sound better using multiples of 2 while others are better in multiples of 3; you’ll just have to play with it (or have your musician brother help you). Also, you must have a duration value for every note in the melody section. 
C. Finally, in the line that reads: 
for (int thisNote = 0; thisNote < 8; thisNote++) 
replace the “8” with the total number of notes in the song.


## Your Fellow BitStars
### Ron Millar

Ron has made some amazing sounds that would totally suit a space-themed game:

- http://instagram.com/p/tO-PxprbuL/
- http://instagram.com/p/tPiPFxrbrN/
- http://instagram.com/p/tPkNqGLbtB/

### Andrea / DB605

<iframe width="653" height="489" src="//www.youtube.com/embed/zmQyJA3l3c8" frameborder="0" allowfullscreen></iframe>

>A impro electronic-industrial track testing Korg's LittleBits. DB605 is a solo project by Andrea from My Right of Frost steampunk circuit bending industrial band.

> My Right of Frost draws sound signs from electronic circuits rewired and made unstable up to the feedback’s critical point. The sequences proposed are totally improvised from the point of view of the musical value of the sounds, and tonally unrepeatable. Across and beyond the concept of circuit bending, My Right of Frost operates constantly on the verge of oscillators and filter’s collapse, extemporizing electronic paths that diverge to form a macro-sign, i.e. the artwork.

## Share Your Invent 
Upload your project to littleBits [Maker Hub](http://littlebits.cc/projects) and post the link below. Make sure in your upload, you mention
- which bit you explored in detail in this Invent
- where you might take this project next
- a video of your project working (and booming)

## Next Steps:
- Discuss Module 3
- Re/hack Module 3
- Meetup Module 3