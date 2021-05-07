[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/Paul-Glanville/milestone2)

# milestone2

## Second milestone project
---

## index

#### Wireframes
#### Purpose of project
#### functions
#### User Stories
#### Languages
#### Deployment
#### Testing
#### credit

---

## Wireframes

![Project desktop](/assets/wireframes/project-desktop.pdf)
![Project tablet](/assets/wireframes/project-desktop.pdf)
![Project mobile](/assets/wireframes/project-desktop.pdf)

---

## Purpose of project
The purpose with the creation of the project is to create a memory game with 16 Tiles from 1 - 16 and number as such. 
The finished product should allow the user to view a sequence with increasing difficulty levels as the user succeeds with each win of a round.
after a sequence is played the user will then be required to click on the same tiles in the sequence presented for each round.


---

## Function

### Star Button - when clicked will start the game at level 1 and run a sequnce, once clicked. will also start each round upon success.
### Tiles/ Numbered Boxes - should light up in sequence after a few seconds once the start button has been clicked, and once the sequence to each round has played the user is then to click on each tile in the order in which they have seen and can remember for that specific round/level.
### Round Counter - Displays each level/Round that the user is currently on  but will refresh to 1 if the user does not successfully click the tiles in order.
### dialogue box to display either the success or failure of each round. (in progress for the time being, will be included at later time.)

---

## User Stories

As the user it is important to understand the rules of the game, and the instructions on how to play which are displayed below the game view. 
As the player I can clearly see the game layout, read the instructions and rules when I scroll down passed the game layout and everything is on one page for easy access.

As the levels increase the user is expected to witness an increase in difficulty as well until all rounds are cleared or an incorrect tile is clicked and game is reset.


---

## Languages

Languages used are HTML, CSS and JavaScript.

---

## Deployment
This project was created on GitHub, once selecting new repository and choosing a name for the project click on the green button that says GitPod which opens a new workspace.
using the commit to continuously save progress to Github.

after creating the repository it was given a server address in the settings and providing a link to use for viewing the site/Game without going into gitpod.


---

## Testing
while creating and testing the product there was an ongoing issue where it would not run and could not figure out the issue,
the start button and round display would show on the left side of the screen when viewing the product.

while testing the project, had a continuous problem i had struggled to solve, the first problem was getting the start button to place a sequence, but that now works and runs a random sequnce with increasing tiles on each level.
The second issue I have been facing is the tiles not lighting up upon being clicked therefore no comparison sequnce can be made as the tiles do not light up and it does not recognise the tile is being clicked.

When creating the alert pop-ups they appear for every tile in the sequence instead of just the once at the end of each sequence.
start button so far is required to be clicked to start each round and round display counter is one round ahead that it actually is.


JavaScript has been checked in JSHint
CSS checked in validator and passed with no errors.
HTML checked in validator.

---

### Credit

Excellence mentor - for advice and guidance with the language of javascript and direction of the project, also provided a block of javascript in game.js that i had taken inspiration of and personalised in index.js and helped with javascript for the reset and lighting up of tiles when clicked successfully and in error of sequence.

Code Institute material for refencing and material provided for the learning of functions and content.

https://coolors.co/palettes/trending - I used this site to get an idea on which colours would go well with each other, this had been presented by my mentor as a good way to test which colours would comliment and work well with others.
