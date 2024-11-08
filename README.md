# Escape_ROOM.py 

**Hello there!** 🚂🚂  I'm Gerardo Jiménez (www.linkedin.com/in/gerardo-jiménez-islas-9487b1227), a mining and metallurgy engineer exploring the coding world.

This post presents Escape_ROOM.py, a game developed in Python as a project for the Ironhack Data Analyst bootcamp.

In collaboration with @Esteban Cristos, we have modified a base code, and we created and added new game features. As a result, we introduce Escape_ROOM.py. In the following lines, you will find a brief explanation of the game code, with the main challenges faced during development, the functions of the game, and the libraries included.

##  Overview

### 👾 The game

This game allows players to go through a series of spaces within a house, while exploring and examining objects that can be interacted with. The goal is to find hidden keys among the objects to unlock the doors of the rooms inside the house, until finally making an escape.

--> Image of the game and gif of scape

### 💻 Game functions

- Two game modes: (Easy / Hard)
- Temporizer added in hard mode to make a it more interesting .
- New push action over the objects, to interact with all items within rooms.

--> Image of the game and gif of scape

### 💡 Experience during development

- Functions optimization: Without a doubt, the lengthiest task was arranging the game's functions. All the functions used global variables as arguments, which necessitated a restructuring that allowed separating the game's functions and the general startup data into different files.

- Adding temporizer: To correctly add the timer during the game sequence, the sys, time, and threading libraries were consulted and used. Thus, a stopwatch is displayed in real-time throughout the entire game process. Of course, coupling this function with the rest of the program was quite a challenge, as it had to be integrated into the existing logical sequence. After many errors and unwanted loops, the goal was achieved.

- Documentation code: Finally, worked to improve the documentation of the game functions and the program in general. The base code did not have comprehensive documentation, so a considerable amount of time had to be invested in fully understanding the code. Now, for a future update, it is expected to be easier.

---

## 🎮🎮 DEMO 🎮🎮

📔 **Try the game:** Go to the following link and try it online. 

Link main.pynb: (https://drive.google.com/file/d/1bGiKOkujnZh_G6ojAE34h1gbPRzOwEiU/view?usp=sharing)

Link functions.py: (https://drive.google.com/file/d/1J0v-U6DfjkcHY32RGG9ZqmKfKeSikIwh/view?usp=sharing)
