# Weekend assignment - dice game
## Basic planning

___
### Features :
- component reusabillity
- good practice : props and state

___
### Components :
Base Container
- Background

Login container (Main)
- Login container
- Btn (new game, total wins balance)

Game container (Main)
- Game container
- Game score&players board
- Btn (exit, roll dice, bank)
- Current player & Current score Sign (Utilities - sign)
- Show Dice
- display delay* message ( on 6/6)
- display Win message (posibble different main component)

Utilities* 
- btn
- sign 

---
### Principles :
- tree priority is first functionality than Modularity
- attention for props : some is not changing, only on mounting. if change: should I render, and what?
- possible send data through "father" without render anything
- Use local storage

---
### Game actions :
- btn design:
    - functions in game container, btn is only reused with new designed input
    - dice function : random image, show dice component. possible random number(1-12), then create show of right sum dice images.... cool!!!
    - dice component is child of game container 
    
---

###start
- make sketch
- setup all components, and basic presentation
- game action functions


