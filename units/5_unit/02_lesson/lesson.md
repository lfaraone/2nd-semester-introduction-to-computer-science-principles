#Lesson 5.02: EarSketch Music

##Learning Objectives
Students will be able to...

* Define and identify: **rhythm**, **beat**, **tempo**, **measures**, `setEffect()`, `makeBeat()`
* Play beats using the functions
* Loop through items in a list
* Be aware of the scope of variables during iteration 

##Materials/Preparation
* [Do Now]
* [Lab] - EarSketch Music
* [EarSketch Editor]
* Associated Reading in EarSketch
*  Read through the do now, lesson, and lab so that you are familiar with the requirements and can assist students

## Pacing Guide
| **Duration**   | **Description** |
| ---------- | ----------- |
| 5 Minutes  | Do Now      |
| 10 Minutes | Lesson      |
| 35 Minutes | Lab         |
| 5 Minutes | Debrief     |

## Instructor's Notes

1. **Do Now**
    * Students should be given time to read unit 2 of the EarSketch documentation.
    * Students should answer the questions included in the do now and be prepared to discuss them as a class.
2. **Lesson**
	* Call on students to discuss the answers to the questions from the Do Now.
	* Recap the following key concepts from the reading:
		* **Rhythm**: describing how the music moves through time.
		* A **beat** is the basic unit of time in music. If you have ever clapped along to a song, you were probably clapping on each beat. So how long does a beat last? The length depends on the overall speed of the song, called the tempo. 
		* **Tempo** is measured in beats per minute (bpm). If we are clapping at 60 bpm, then each beat lasts one second. At 120 bpm, each beat takes half a second. The higher the bpm, the faster the song, the shorter the duration of each beat.
		* Beats are grouped into **measures**. In EarSketch, measures always have four beats.
		* `setEffect()`: add an effect to a track. Takes parameters: track number, effect name, effect parameter, effect value
		* `makeBeat()`: instead of composing at the measure-level, we can work at the note-level. Takes parameters: clip name, track number, measure number, beat string
3. **Lab**
	* Follow the EarSketch instructions in the lab to use the `makeBeat()` function
	* Create a simple song with 2 uses of `fitMedia()`, 2 uses of `makeBeat()` and 1 use of an effect. 
	 
4. **Debrief**
	* Talk about the new functions learned today, and go over any questions about data types and using strings.

###Accommodation/Differentiation
Students can use looping and if statements to their song as an extension activity to make their songs more complex.

Students will likely bring a wide range of background knowledge around music and the related terminology. Offer additional support to those students that are less familiar with the terms being introduced in this lesson.

[Do Now]: do_now.md
[Lab]: lab.md
[EarSketch Editor]: http://earsketch.gatech.edu/earsketch2/