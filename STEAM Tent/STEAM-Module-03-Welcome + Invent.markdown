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
### Dr. Traci Kohler and Lindy George, 
Department of STEM Resources and Instructional Technology, Collier County Public Schools

The culminating district-wide iSTEM Competition is held in late spring on a local college campus. For some students, it is the first time they have visited a college campus, and the visit brings a sense of awe in and of itself. At the same time as the elementary students are competing, middle and high school STEM Competition events are also happening around the campus.

In the elementary area, thirty (30) teams of four (4) students each are gathered in a very large room. In the center of each of the 30 tables is a container full of craft materials, a littleBits Kit, and a set of additional modules. The teacher advisors sit along the outside perimeter of the wall trusting that their students are well prepared for the challenge ahead. You can feel the combined excitement and energy of 120 students as they await the announcement of the theme and are given the go ahead to begin planning, designing and building.

Student teams are given 3 hours to design and build their creation based on the theme. Judges walk around and look for team work, collaboration and cooperation. Points are given for teamwork through the day as well as final project and presentation. All students on a team are expected to be able to answer questions about their project, and a final presentation is shared amongst the team. Points are even given for helping a neighboring team problem-solve. Finally each group presents their project to a team of judges. We include a “lights on” and “lights off” opportunity to each team during the judging. There is an additional 5 minutes allotted for the team to present and answer questions.

![](/Images/istem.jpg)

[Case Study: District-Wide STEM Challenge](http://littlebits.cc/education-case-study-district-wide-stem-challenge)

## Share Your Invent 
Upload your project to littleBits [Maker Hub](http://littlebits.cc/projects) and post the link below. Make sure in your upload, you mention
- which bit you explored in detail in this Invent
- where you might take this project next
- a video of your project working (and booming)

## Next Steps:
- Discuss Module 3
- Re/hack Module 3
- Meetup Module 3