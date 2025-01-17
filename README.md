# CW_Quizzer



![](https://github.com/busysteve/CW_Quizzer/blob/main/CW_Quizzer.jpg)


![](https://github.com/busysteve/CW_Quizzer/blob/main/CW_Quizzer_Diagram.png)


## The CW_Quizzer is a device project that is based on an Instructables project from Scott Baker that allows for keying practice.  It has since been modified to support CW reciving practice.  It includes a varity of training methods as well.  Koch, LICW, and ESTONIA are the currently supported training sets.  By default the unit currently starts in keying mode, to enter the menu options tap the menu switch.  To enter training mode hold and release the menu switch, and let the quizzing begin.  press both paddles of your keyer to quiz again.  Just look away, listen, decode, and look back to see if you were correct.  The menu options are:

### Learning Method
### Lesson Level
### Lession Size (greater than 6 will include spaces)
### Lesson Window Width
### WPM
### Farns worth spacing difference
### Tone Frequency

The code supports LCD 4x20 and OLED 128x64 with some #define adjustments at the top.  The LCD version works great, the OLED version had a minor timing issue with keying that I will be working on.  The code is currently set to build for LCD by default.

