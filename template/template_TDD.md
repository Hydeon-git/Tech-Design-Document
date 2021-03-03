# TECH DESIGN DOCUMENT
## GAMENAME

### 1. GAME OVERVIEW
#### GAME SUMMARY
What is your game about? You have to give a very short and general summary of what happens in your game.

#### PLATFORM TARGET
What platform your game will be releasing? Is it PC, or maybe Consoles?

What will you use to control the game? Keyboard or Gamepad, or both? Answer all this questions in this section!

What are the minimum requirements of your game in order to play it in a solid 60 fps in a computer? What hardware should that computer have to be able to play it?


### 2. DEVELOPMENT OVERVIEW
#### DEVELOPMENT TEAM
Every person in the team must be here. It has to be recorded which role every coworker has.

It is encouraged to give a short description in one line of what exactly this person will do in the project.


#### DEVELOPMENT ENVIRONMENT
In which library and language will be written all the game?

**Development Hardware**: What are the requirements of the software you are using?

**Development Software**: Which software will be using the team for the development?

#### GITHUB BRANCHING
How your team will manage the branches on GitHub? Here’s a tip: Use 3 different branches. Master branch: Only for release purpose. Merging from the dev branch.

Development branch: One main branch + temporal branch for each new feature.

Bug Fixing branch: Only for fixing bugs.

### 3. TECHNICAL FEATURES
#### TECHNICAL REQUIREMENTS
List all the main technical features of your game.

#### MODULE ARCHITECTURE
What module structure do we have in our project?

What happens in that module in particular?

Do not provide a scheme, what we want here is to list what each module does.

#### GAME FLOW
Explain everything that happens in a game loop. Think of it like a guided tour of your game.

A scheme might be really useful here too.

#### GRAPHICS
The screen resolution, tile size and camera view should be documented here in a few lines specifying its characteristics.

What visual style the game will have? Describe the visual techniques what will be used. Which particles will be used on the game?

#### AUDIO
Specify what music or sound will be heard in what moment on the game.

#### ARTIFICIAL INTELLIGENCE
What enemies in your game do have intelligence?

Do they attack trying to discover your weaknesses?

Write how every enemy works.

Example: When you kill an enemy, it drops an item.

Explain how the AI you implemented manages an item pool checking your current level.

#### PHYSICS
Explain what object in your game has collisions and the reason for it.

Useful for explaining specific functionalities that may be difficult to remember.

#### DATA MANAGEMENT
How the data will be managed? Saved on an XML?

When will it Save or Load? Checkpoints?

### 4 CODE STYLE
#### NAMING CONVENTIONS
General guideline on how your code should be written. Essential section for your team to be able to read and understand code from other coworkers.

Take a look at Ray’s code conventions for a good reference on how it’s done.

#### XML
Structure of your game xml. Useful guideline while developing.

Here you can visualize all the structure your xml should have, in case you don’t remember it.

You can use the xml we used in Video Game Development class last semester as a reference.

#### UML
Structure of all the modules in the game. The scheme should be very simple to be able to understand the module structure in seconds.

You have lots of references on the internet. A useful reference I found for you is this UML from this CITM students project.

### 5 TECHNICAL RISK
Analyze the any lack the team might have in this project. This is useful to be able to see which part will be more difficult than another and strengthen it for the sake of making a solid project.

Is the library new to us? We didn’t work yet with this type of game? All this questions can be answered here.
