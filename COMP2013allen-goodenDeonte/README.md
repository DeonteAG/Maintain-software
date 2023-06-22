# Breakout Coursework 
By Deonte Allen-Gooden 20166502
Tested on Windows, Maven Build Script Java version "17.0.1", JavaFX "17.0.0.1"

# Contents
1. [How To Compile Code How To Compile Code](#how-to-compile-code)
2. [Javadoc Location](#javadoc-location)
3. [Working Features](#working-features)
4. [Non-Implemented Features](#non-implemented-features)
5. [New Classes](#new-classes)
6. [Modified Classes](#modified-classes)
7. [Code Conventions](#code-conventions)
8. [Controls](#controls)
9. [Breakout Home Screen](#breakout-home-screen)

## How To Compile Code
`~$ shift+f10 or gameStart.java run`

## Javadoc Location
* My Javadoc can be found in the directory breakMain\\src\\main\\java\\javadoc\\index.html

## Working Features
* Meaningful packages for the gamer files
* HomeScreen works PlayButton, HowToPlay and QuitButton
* Score Display Works
* Colour schemes ball, game paddle and background
* Cautions and advisories in the code removed
* Music Feature for main game and home screen
* High score saved displayed and updated when beaten
* Coin sound when user breaks a block and receives points
* Game ball progressively speeds up as the game continues
* Crack sound when the brick cracks 
* Javadocs implemented with comments on methods
* User can choose the background colour of the game
* Constants used through code to follow the singleton design pattern

## Non-implemented Features
* Player Login players only enter name for high score
* Did not covert the whole game in javafx just the home screen GUI was substantial enough
* Did non include method naming convention as I am working in java

## New classes
* **HomeScreen** includes the javafx home screen launcher which adhere to the 
  MVC design pattern
* **HomeController** includes the javafx home screen logic 
* **HowToPlayController** includes the javafx How To Play Screen logic
* **Crack** class which is extended from the brick class contains the method to 
  crack the cement
* **Test Folder** has meaningful Junit tests

## Modified classes
* **Wall** class includes score which adds 10 to score after each broken 
  brick class also includes method to get, check and amend the high score as 
  well as another level added in this class
* **gameStart** class modified to start the HomeScreen class
* **gamePaddle** class modified paddle colours and speed changed to game 
  theme includes m_trace flags
* **gameGUI** class modified the title of the application and icon to have a 
  picture on the left corner
* **gameBoard** class modified colours, buttons and icon changed also exit 
  button fixed, present message of score and high score using get methods from 
  wall
* **CementBrick** class modified colours of the brick changed uses the newly 
  extracted crack class from brick
* **ClayBrick** class modified colours of the brick changed
* **SteelBrick** class modified colours of the brick changed
* **Brick** class unused variables discarded nested crack class broken down 
  into separate class
* **DebugConsole** Javadocs and warnings complete as well as colour theme
* **DebugPanel** Javadocs and warnings complete as well as colour theme
* **Ball** Javadocs and warnings complete as well as colour theme and 
  m_trace flags
* **newBall** Javadocs and warnings complete as well as colour theme and
  m_trace flags

## Code Conventions
* All lines where possible follow the 80-character limit guideline
* Magic Numbers Have Been erased
* Method Lengths are all 75 or less
* Indentation are not more than five levels
* Most of the methods Parameters are not more than 5 apart from the odd few
* Getters and setters applied where needed and smaller methods change into 
  getters and setters

## Controls
![Alt text](https://github.com/DeonteAG/images/blob/main/HowToPlay.PNG?raw=true)

## Breakout Home screen
![Alt text](https://github.com/DeonteAG/images/blob/main/homeScreen.png?raw=true)


