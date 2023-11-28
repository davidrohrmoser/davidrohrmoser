# GENERAL KNOWLEDGE QUIZ
## CS50P final project
#### Video Demo: URL


# Introduction

The program is a general knowledge quiz which will test you in the fields of
history, biology, geography and others.
You have 60 seconds to answer as many questions as possible.
The program will record your performance and keep track of your score.
After finishing your questions it will tell you your points, as well as the previous highscore.


# Motivation

The main aim of this project was to finish the CS50 Python Course by Harvard University.
Though, I also somehow wanted to implement my own interest in the project I was about to create.
Therefore, I decided to create a general knowledge quiz
as I was always interested in having a broad understanding about a plethora of topics.
The inspiration behind this program is the show "Who wants to be a millionaire?" because it also revolves about answering multiple-choice
questions in order to increase your score.

# Project

#### Features

1. take your name as input
2. print out the rules to play this game
3. asks you if you want to start
4. start a 60 second timer
5. asks you a random question and gives you 4 different answers
6. asks for your answer
7. prints out wheter your answer was correct or incorrect
8. repeats from 4
9. if time expired prints your score and previous highscore


#### Files

- 'main directory'

    - 'project.py' - contains code for the main program
    - 'questions.py' - contains all the questions and answers in a list of dictionaries
    - 'requirements.txt' - lists all the used libraries
    - 'test_project.py' - contains 3 test functions for the main program
    - 'highscores.csv' - contains all the score of the players with their respective names

### Libraries used

- 'csv' in order to manage csv files
- 'os' in order to exit while threading
- 'pandas' in order to work with data
- 'random' in order to get random questions
- 'sys' in order to exit
- 'termcolor' in order to print with color
- 'threading' in order to do two things at the same time in your code
- 'time' in order to add a timer to the quiz


# Project structure

After running the project you will be asked to enter your name in order to play.
Your name will then be formatted and you will be able to read all the rules to continue.
If you want to continue, you have to input "s" into the terminal window.
If you input anything except for an 's' or 'S', the program will stop automatically.
After starting, you will be asked questions randomly chosen from a list written by me.
The list contains questions about different subjects such as geography, history and biology.
One of these questions will be displayed on your screen with 4 different answers.
You have to choose the one answer, you assume to be correct, by inputting either A, B, C or D in either upper- or lowercase into the terminal window.
The program will decide whether the answer is true or false and print 'Correct' or 'Incorrect' in color on the screen.
The process repeats and the next question is shown.
After one minute of answering you will still be able to input your last answer before the program stops.
Your score out of the displayed questions will now be shown as well as the previous highscore read from a csv-file.


<!--
**davidrohrmoser/davidrohrmoser** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
