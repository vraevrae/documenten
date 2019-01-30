# documenten
# VraeVrae

## Description
Aim of our webapplication is to allow users to play trivia quiz against each other. By using our website, the players will be able to expand their miscellaneous knowledge while playing live against other users.

## Installation

To install the project locally, run:
```
pip install -r requirements.txt
```
If you want to run the program in development mode run: 
```
flask run
```
To test the project, 35 tests have been written. To run those tests, run:
```
pytest
```

## Usage
When opening the program, the user can choose to make a new game or join an already existing game. When making a new game, the user has to fill in a username and is able to pick a difficulty and a category, when joining an existing game, the user also has to fill in a gamecode. After that, all users arrive in a lobby where they can see the gamecode. The user who made the game will also see a button which can start the game. When the game starts, a timer will start and every 10 seconds all users will see a new question. After 10 questions a scoreboard will appear. Here you can also see the correct answers to all questions.

## Credits
Yunus Demir
Robert-Jan Korteschiel
Deniz Seyfeli
Rachel de Haan

## Licensing

Copyright (c)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.