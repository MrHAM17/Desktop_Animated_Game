# Bricks Breaker Game

This is "master" branch(main) of this repo; And presenting latest version (i.e, version no. 1.0) of the app.

It is the basic Desktop Game Application.It’s a GUI-based project used with the Opengl library to organize all the elements that work under the Brick Breaker game. Below, point by point complete detailed information is discussed.

## Chapter 1: Introduction

### 1.1 Motivation : 
Games are a fundamental way that humans interact and learn. They provide so many advantages for 
people of all interests and abilities. 
 
The main benefits of using computer games as learning tools, is related with problem solving, 
21stcentury skills, integration of learning and assessment, collaboratives and interactivity, 
addressing cognitive as well as affective learning issues, and motivation for learning. Gaming is 
gaining a different level of attention not only from the youngsters but also from different age people. 
 
It is creating a virtual world where we can virtually live our life. Gaming has gained importance in 
Desktop application as well as in Android Application.
 
### 1.2 Need Of The Problem : 

As a computer science student, we’ve to learn game development because this field 
requires some skills that already we’ve and at the same time we can enhance them. 
 
For a ‘game design’ it can mean “emotional engineering” or “largely communication” 
whilst for the other “everything that goes into a game is more or less game design”. On a 
more formal matter, many designers have gone extra miles to explicate their conceptions on 
game design. 
 
Game development can considerably improve our imagination skills, designing skills and 
the ability to produce new things. For a game to attract attention, it should also be unique. 
The more the game is realistic, the more appealing and charming it !

## Chapter 2: Problem Statement 

### Tech Stack :

-  **Developer:**

          1. OS- Windows 11. 
          2. Processor– Any Pentium Version. 
          3. Hard Disk- 32 GB (64 GB recommended). 
          4. Memory- 4GB RAM for 64 bit. 
          5. C/C++ Compiler. 
          6. Code Blocks IDE 
          7. Open GL Libraries 
          8. Some Graphics Files.     

-  **Client:**

          1. Desktop with minimum 2 GB RAM. 




## Chapter 3: Flowchart

Process of the program in detail:

![](https://github.com/MrHAM17/Desktop_Animated_Game/blob/master/2.%20Rough%20Work%20&%20Data/Used%20Images/Fig%203.1.1.png?raw=true)

![](https://github.com/MrHAM17/Desktop_Animated_Game/blob/master/2.%20Rough%20Work%20&%20Data/Used%20Images/Fig%203.1.2.png?raw=true)

## Chapter 4: Functions Used

All the Computer Graphics concepts that are implemented are listed below: 
### ● Translation: 
      Concept of translation is used in our game while moving the paddle as 
      well as while the ball is in motion rebounding from the different surfaces. 

### ● Scaling: 
      Concept of scaling can be seen in our game when the difficulty changes, the 
      scaling of the paddle differs. When the level is easy we scale the paddle smaller and 
      when the level is hard we scale the paddle longer 

### ● Drawing Polygons: 
      Different shapes were drawn using the inbuilt polygon function 
      and defining the appropriate vertices which matches the shape of the polygon. 

### ● Game Concept: 
      Brick Breaker is a famous retro game where we have to destroy all 
      the bricks and the ball should not fall. If the ball falls the game will restart. The main 
      player of the game is paddle, we have to save the ball from going below by the paddle 
      and at the same time try to hit as many bricks as possible. 

### ● Keyboard Inputs: 
      Now for playing the game the user needs some kind of input to 
      give. This can be done very easily by using a glut function ‘keyboard’ and then by 
      specifying the role of the keys in the switch case. In each switch case you need to 
      define what that key will do. 

### ● Hitting the Brick: 
      This is the concept which comes into play when the ball hits the 
      brick. This function defines the trajectory of the ball after hitting. We used the concept 
      by applying the if else conditions and accordingly changing the direction of the ball. 

### ● Trajectory of the Ball: 
      The concept used for this particular feature of our game which handles 
      the motion of the ball along with the rebounding from various surfaces. Here one condition is 
      for increasing the rate after some successive collisions and another condition is to make the 
      changes for the different directions of the ball after rebounding.


![](https://github.com/MrHAM17/Bricks_Breaker_Game/blob/master/2.%20Rough%20Work%20&%20Data/Used%20Images/Fig%202.1.jpg?raw=true)


##

## Chapter 4: Output Primitives And Transformations

### Output Primitives:

Output Primitives are simple geometric functions that are used to generate various 
Computer Graphics required by the user. Some most basic Output Primitives include 
pixels (points) and straight lines. For this project, we have used the following Output 
Primitives:

![]( )

### Filled Area Primitive:

Filled area primitives are used to give color to a specific region of the graphics scene. 
For this project, the flood-fill approach was used to give color to various components 
of game. Then four connected approaches or eight connected approaches are used to fill 
with specified color. 
The flood fill algorithm has many characters similar to boundary fill. But this flood fill 
method is  more suitable for filling multiple color boundaries of brick. When boundary is 
of all bricks is to be filled with one color we use this algorithm i.e. Blue.

### 3D Transformations:

Transformation means changing some graphics into something else by applying rules. 
We can have various types of transformations such as translation, scaling up or down, 
rotation, shearing, etc. When a transformation takes place on a 3D plane, it is called 3D 
transformation. 
For this project, we have used concepts of : 
Translation : To move the paddle on ground level. 
Scaling :         To move a ball up or down

1) Initial view of Game:
   
![](https://github.com/MrHAM17/Desktop_Animated_Game/blob/master/2.%20Rough%20Work%20&%20Data/Used%20Images/Fig%207.1.jpg?raw=true)

2) When user tap to start:
   
![](https://github.com/MrHAM17/Desktop_Animated_Game/blob/master/2.%20Rough%20Work%20&%20Data/Used%20Images/Fig%207.2.png?raw=true)

3) When user playing:
   
![](https://github.com/MrHAM17/Desktop_Animated_Game/blob/master/2.%20Rough%20Work%20&%20Data/Used%20Images/Fig%207.3.png?raw=true)

4) When user missed the ball first time:
   
![](https://github.com/MrHAM17/Desktop_Animated_Game/blob/master/2.%20Rough%20Work%20&%20Data/Used%20Images/Fig%207.4.png?raw=true)

![](https://github.com/MrHAM17/Desktop_Animated_Game/blob/master/2.%20Rough%20Work%20&%20Data/Used%20Images/Fig%207.5.png?raw=true)

5)  When user used all his life chances:
   
![](https://github.com/MrHAM17/Desktop_Animated_Game/blob/master/2.%20Rough%20Work%20&%20Data/Used%20Images/Fig%207.6.png?raw=true)


##

## Conclusion:

 
Thus, we were able to implement the code of Animated 2D game using C++ language 
(with graphics.h, dos.h and process.h header files).
 
The project is well suited for designing 2D objects, as well as for carrying out basic 
graphics functionalities.
 
However, if implemented on professional level with sufficient resources, it has the 
potential to become a standard stand-alone GUI based application for fun for Operating 
System.
 
The major aim of this project is to increase the problem-solving skills. The project aims to 
create a 2D game in pc is successful . Where users can access the game with ease. In this we 
learned how computer graphics is used in game development and in other applications. We 
have discussed about how brick breakout game is developed in C++.
 
So, concluding our project, the Brick Breaker Game demonstrated our learning and new found 
expertise in Verilog coding, the understanding of basic CodeBlocks IDE, basic C++ 
Programming Language, Teamwork & all, How to handle a real life project, And many more 
things; Also last but not the least i.e. solution for our aim of the project.

## Documents

Project Report

![PDF](https://github.com/MrHAM17/Bricks_Breaker_Game/tree/master/1.%20Project%20All%20IMP%20Docs)

For more details,
Kindly Check the 1st folder of this repo i.e, "Prject All IMP Docs"

## Installation

Install my-project with:
- Code Blocks IDE
- Opengl Library
- C/C++ Compiler



## Reference:

- TEC, University of Mumbai, Mumbai, India 
  “PC Based 2D Game Design”, May-June-2021

- Stanley College of Engineering and Technology for Women, Hyderabad, 
  “GLOBAL JOURNAL OF ENGINEERING SCIENCE AND RESEARCHES, BRICK 
  BREAKOUT”, 2018


- http://www.cs.columbia.edu/~sedwards/classes/2019/4840-spring/designs/BrickBreaker.pdf

- http://web.mit.edu/6.111/www/f2013/projects/jabbott_Project_Final_Report.pdf


- Youtube
   - https://youtu.be/T4TJKlZKATM
   - https://www.youtube.com/watch?v=KED9ZTO4mhg
   - https://www.youtube.com/watch?v=gPiahyf70ds
  
- LinkedIn 

- Github 
