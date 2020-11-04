# LINO GLOBULINO
## The Game
This game is inspired by the Google Blockly Game Maze (https://blockly.games/maze) and by the character Lino Globulino (https://www.aip-it.org/index.php/le-avventure-di-lino-globulino), created by Associazione Immunodeficienze Primitive – AIP. Help the protagonist to achieve his goal: a Space Hospital, to which Lino carries transfusion bags, thus helping patients.

## Get the Code

First, download the source code.  Git is the easiest:

    git clone https://github.com/LucaCellamare/LinoGlobulino.git

## Get the Dependencies

Enter the Blockly Games directory, and get/build
the dependencies:

    cd blockly-games/
    make deps

## Build English

The next step is to build the English versions of the game:
    make maze-en

There shouldn't be any errors.

## Build all Languages

Optionally, you might wish to build all 50+ languages, not just English. Be
warned that this takes approximately *2 hours*, so this may be something you
should do overnight.

    make languages

## Test Locally

Point a browser at `blockly-games/trunk/appengine/maze.html?lang=en` and you should
see the game.
