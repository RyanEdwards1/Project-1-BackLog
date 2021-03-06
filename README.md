# Project-1 Trace Ball

## Introduction
#### The aim of this project was to create a web based game. There are two characters: the player, and the enemy npc. The aim of the game is to keep your character away from the enemy, until a timer concludes. The player has three lives, if the enemy NPC hits the player they lose a life. When the player runs out of lives, the game ends

## Description
#### A non-playing character NPC (that is a character controlled by the computer) targets the users mouse position as the player moves across the screen, the game is over once the NPC touches the players mouse position 3 times

## User Stories
#### As a player I would like to know when I have come in contact with the NPC 
#### As a player I would want my character to follow my mouse 
#### As a player I would want to know when I have lost all 3 lives 
#### As a user I would like to play it in a browser 
#### As a player I'd want the NPC to follow my character 
#### As a user I would like to see both characters 


## Flow Chart
![flowchart](https://user-images.githubusercontent.com/31927415/33268043-9047a1a6-d373-11e7-9032-3bedf0c82ee0.JPG)


## Time Line Of Progress
![cfpture](https://user-images.githubusercontent.com/31927415/33266395-5fdb6db4-d36d-11e7-8043-b6b6ff564e4a.JPG)


### The IDE i used Was NotePad++

#### Notepad ++ was a good option to use as it shows the syntax highlights with colours instead of normal notpad just showing the text so this helped me out alot as i was able to see when i was correcting indenting things and making other syntaxs correctly aswell Notepad++ also aloud us to preview it in many differnt browsers so we could check in real time to see if are code was working or not.

#### I also used a little bit of "Repl.it" as i got closer to the end of my code as this helped with displaying errors and helping me locate them it also saved time as it split the screen into two so i could see what i was changing live instead of tabing in and out of notpad and a web browser. 
![dfffd](https://user-images.githubusercontent.com/31927415/33600567-8984a5f6-d9a1-11e7-9058-aedb64b3f74f.JPG)


### Using A IDE vs Not Using A IDE
#### Notepad is a simple application comes up with windows allows you to write some text and store it in very low file size. it’s a very simple editor. 
#### Notepad++ is a advanced text editor, it supports many extensions, good for coding purposes by this you can validate a text very fast, provide many kinds of extensions by this you can compare , modify , replace and find texts very easy way. high readability and this list is never ending lots and lots of features. Notepad++ supports 50 programming, scripting and markup languages. It also features the automatic detection of the programming language that a given file uses. It is Also Free to use

## Example Code

#### Code For Drawing Player:
     context.beginPath();
     context.fillStyle = "#000000";
     context.fillRect(mouseX - 25, mouseY - 25, 25, 25); 
     context.fill();
        
#### The code above starts with context.beginPath which begings the drawing of retangles it draws too lines on the screen and the next lines of code place it all togethere and make it into a rectangle.

#### Context.fillStyle is the colour that you want your rectangle to be using hex numbers which is made up of 6 differnet number and letter combinations.

#### Context.fillRect is to make the lines that was created earlier into a rectangle, Then in the brakets is numbers which is creating the size that you want your rectangle to be.

## Debugging Process
#### When we first started coding using notepad++, we would do the code line by line so if a error happens then we would know where the error has occurred and this would make it simpler to fix the code when it breaks. Once we started using to 'repl.it' our debugging improved as we were able to see a live preview as well as get valid debugging messages to tell us where we made mistakes.

## Coding Standards
#### During the coding process, I made sure to constantly indent my code often so that I was able to identify the breaks in commands. also this makes it easier to see what code is inside what function or command. making easier to also comment and add notes to the code. I used alot of indenting in my work for this project as i had alot of fuctions that had alot of code in each one. I used Tabs to indent my work as it is quicker and looks more professional as everything is in line. This also makes it easyer for someone else to read and understand my code. 
#### I also added alot of Comments to my code so that when i go back to it i can see what each part of the program does and i can refresh my memory. I can also use it to help me on later projects if i was to forget somthing 

## Evaluation
#### Overall I feel that as this was my first game that i have coded it went pretty good as i meet all the requirements that we needed to. I learnt have to diagnose simple coding errors/mistakes as well as pick up simple terminology whilst being able to implement it into my code. I also commented my code so that if i ever need to look back at it and see what code i used and what it does. This will help later down the road when we code bigger projects.
