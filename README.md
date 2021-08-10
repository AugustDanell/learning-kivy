# learning-kivy
A repo designed for learning and maintaining knowledge in the kiwy library for Python. Kivy is a library that is used to develop for instance mobile applications. Much like the library pygame one can use it to write games as well (See pygame repo). Here are some kivy implementations to follow:

## text_game.py (Blueberries)
This is my first kivy project, a small text game where the player plays by pressing different buttons. The goal of the game is to avoid the bear and to collect the blueberries. It is simple in nature consisting of one python file extended via kivy. The entire game is controlled by which state it is in, an update function updates all the buttons and scenario text in accordance with the state. The player can change the state by pressing different buttons, and so it is like a graph in which the player can traverse to different nodes where each node is a game state. One state is a losing state and one state is a winning state. 

## kivy_calculator.py
A simple application where the user inputs two numbers a,b and gets an answer based on what operation the user wants to perform. Some error handling is done to make sure that the user inputs integers, and not something else, as well as to avoid division with zero. A standard calculator. 


# Images
## text_game.py (Blueberries):
<img src="https://user-images.githubusercontent.com/70810124/128862428-69ed0d4f-3f33-49e7-9226-b5b964f77dcc.png" width = "400" height = "300" />
<img src="https://user-images.githubusercontent.com/70810124/128862457-9399dc3a-2fe5-466e-bf64-4de1aa162c34.png" width = "400" height = "300" />

## kivy_calculator.py
<img src="https://user-images.githubusercontent.com/70810124/128889661-2a4b6685-ddae-4c01-86de-9fb4994e75fc.png" width = "400" height = "300" />
<img src="https://user-images.githubusercontent.com/70810124/128889665-b14157c4-8c21-4a41-b5e4-4bede05cfb0e.png" width = "400" height = "300" />
