---
layout: project
type: project
image: images/Checkers3.png
title: Checkers Game
permalink: projects/checkers
date: 2016
labels:
  - Java
  - Eclipse
  - Programming
  - Game Development
summary: A checkers game for 2 players I developed in a team of 2 for ICS111.
---

<img class="ui medium right floated rounded image" src="../images/Checkers1.png">

## Introduction

In ICS111, I, along with my partner Grace Jung, created a game of checkers with help from [EZ](http://www2.hawaii.edu/~dylank/ics111/), provided to us. Our game follows the rules of Checkers to the letter, and is playable with 2 players only. Players move pieces by clicking a piece with the mouse, and then clicking an empty space that the piece can go to, taking turns until the game is over. This project helped me learn how to collaborate in a development environment, the basics of programming in Java, and how to design, develop, and debug games. Our project was selected as one of the best projects out of our ICS111 class.

## Responsibilities

My responsibility was primarily the game logic (regarding the valid movement of pieces, capturing logic, etc.) and debugging the code. It was particularly challenging to debug, as there were many fringe case bugs caused by incorrect logic. 

Our algorithm mostly involved using a 2d array to hold the pieces, and checking each piece's valid moves by comparing its position to other pieces' positions on the board, and making sure the pieces could not exit the boundaries of the checkers board. This approach ended up having a lot of specific cases for few specific scenarios, which most likely means the algorithm could have been improved; as it stands, there was most likely a lot of spaghetti code in the program. Nevertheless, we managed to get the game working and debugged it as best we could, but there were possibly some other fringe cases that we did not encounter in our testing.

## Reflections

I think it's possible that we could've developed a better algorithm for our board logic rather than having to run checks on each piece to see what valid squares it could move to, possibly something that could cut down on the fringe case bugs and have been more simpler to implement. I also would've liked to have had some more features, particularly displaying possible moves on the board, or an AI opponent. Overall, I learned a lot about game development, programming in Java, and collaboration with teammates on a software development project.

### Links below
  
[Github](https://github.com/blaine-wataru/ICS111Checkers)  

[Dropbox](https://www.dropbox.com/s/9m2owgbckxr6d91/CheckersICS111.zip?dl=0) (May need [Eclipse](http://www.eclipse.org/downloads/packages/eclipse-ide-java-developers/keplersr1) to run)

Youtube Demo: 
<div class="ui embed" data-source="youtube" data-id="UQ0Owort4oQ" >
</div>
