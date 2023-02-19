Details:

- View this project demo on <a href="https://www.youtube.com/watch?v=1TV3vUGNr-o&list=PLbkOKmQRnCn45kDUhMIgzyGSAj7u0v4xU">Youtube</a>.



https://user-images.githubusercontent.com/55496113/219962220-89d63a90-639e-437a-a44d-0ad6dcda5c02.mp4


- <a href="https://en.wikipedia.org/wiki/FastAPI">FastAPI</a> is a Web framework for developing RESTful APIs in Python. FastAPI is based on Pydantic and type hints to validate, serialize, and deserialize data, and automatically auto-generate OpenAPI documents.
- Github <a href="https://github.com/tiangolo/fastapi">link</a> to FastAPI.
- About this project:

  - This project consists of the implementation of a few games and apps using NestJS, and deployed onto Vercel.

  - Following apps have been implemented:

    - Calculator: A calculator covering the fundamental operations - Addition, Subtraction, Multiplication, Division, and Clear Screen.

    - Maze: A maze for navigating the object to the destination. It exists in four levels of difficulty: Easy, Medium, Hard, Extreme.

    - Tic tac toe: The first symbol (X/O) to get 3 consecutive boxes filled upon alternative turns of filling the boxes in the grid (we have implemented for 3X3 grid) would be the winner. After one game is over, the user is allowed to Restart the game.

    - Analogue clock: Analogue clock showing the current time.

    - Hangman: User will have to guess the phrase with 5 guesses. The user can reset the phrase at anytime during the game.

    - Puzzles: User will have to rearrange the pieces to form the picture that is shown on the screen. The steps and time taken are counted.

      - There are a sample of 5 images in this app (Harju-Madis Church, Kakumäe Harbor, Kohila mill, Rahumäe train station, Neeruti manor).
      - This game has 4 levels of difficulty:
        - Easy (3x3)
        - Medium (4x4)
        - Hard (5x5)
        - Very hard (6x6)

    - Sudoku:

      - This is an implementation of the game of Sudoku, and it demonstrates how developers can use HTML5 and JavaScript to create an efficient algorithm to solve these puzzles. The algorithms draw heavily on the Chakra engine’s support for ECMAScript 5 standard array operations to rapidly solve many Sudoku games. We can also manually solve Sudoku puzzles.
      - Courtesy: https://github.com/MicrosoftEdge/Sudoku

    - Virtual Keyboard: Implementation of keyboard with fundamental functionality.

    - Solitaire: Implementation of <a href="https://en.wikipedia.org/wiki/Patience_(game)">Solitaire</a> (stacking cards of alternating colors (red and black) one below the other). Here, we have the following features:

      - The ability to undo moves
      - Switch between light and dark themes
      - Start a new game in the middle of another game

    - Chess: Implementation of <a href="https://en.wikipedia.org/wiki/Chess">Chess</a>

    - Dino:

      - Implementation of the <a href="https://en.wikipedia.org/wiki/Dinosaur_Game">Dinosaur game</a>
      - Courtesy: https://codepen.io/MysticReborn/pen/rygqao

    - Sass:

      - Styling using SASS/SCSS

    - Tilted maze:

      - Four dots are supposed to be combined into one,and should be directed into the dotted circle in between. This movement should be done with the help of a virtual joystick. This game is there in 2 modes:
        - Easy: Plain version, as mentioned above
        - Hard: There are "potholes" in the maze. The game will stop when any of the dots falls into a pothole. Toggling between easy and hard mode is by pressing on keyboard (E/e) and (H/h).
        - Courtesy: https://youtu.be/bTk6dcAckuI

    - Codepen:
      - Simulation of <a href="https://codepen.io/">Codepen</a>, wherein we can code and see the browser result simultaneously.

---

# FastAPI Notes Application

Repository containing code for "Deploying FastAPI applications to Vercel".
Reference: https://blog.logrocket.com/deploying-fastapi-applications-to-vercel/

## Running the application

To run the application on your machine, clone this repository and install the dependencies:

```
$ git clone https://github.com/Youngestdev/fastapi-notes-app && cd fastapi-notes-app
```

Setup a virtual environment:

```
$ virtualenv --python=python3.8 venv
$ source venv/bin/activate
$ deactivate
```

Install dependencies:

```
$ pip3 install -r requirements.txt
```

Run the application:

```
python3 main.py
git add . && git commit -m "C" && git push origin main && vercel --prod

```

## Error?

If it's an error with regards to path, run the command:

```
export PYTHONPATH=$PWD
```

Any other one? Please raise an issue.
