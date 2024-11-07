# Alex's Portfolio

# Identifying and Defining
## PMI

| Existing Idea | Plus | Minus | Implication |
|:------------- |:---- |:----- |:----------- |
| Soul Knight ![alt text](image.png)| Soul Knight has extremely fast-paced action which includes very easy-to-use controls (only available on mobile, but you can emulate it), making it very engaging for new players. The graphics are very simple but nice, making it a pleasing experience. | Although there is a lot of fun in the levels, it may get a bit boring for some people, as the gameplay is pretty repetitive. There also isn't much of a storyline, just beating the game while unlocking new characters and things, where some people enjoy more of a narrative plot. | For my game, I could use Soul Knight's simple controls and use it for inspiration for my game, and I could implement a more fun storyline so that it is more engaging to play, and not repetitive. |
| Hollow Knight ![alt text](image-1.png)| Unlike Soul Knight, Hollow Knight is extremely well known for its plentiful and deep lore. It also has a very mechanical and strategic playstyle, making the game appealing to players who enjoy that playstyle. | Because of the playstyle, new players may find it hard to learn the game and its mechanics. It is also a little slow-paced (unlike Soul Knight), making it not fit for people who want action immediately. | I could use some elements from Hollow Knight's storytelling and lore in my game, possibly making a story of how the main character's best friend got trapped. I will make sure to introduce new players to the game using a tutorial so they know how to play. |
| Dead Cells ![alt text](image-2.png)| Dead Cells is mainly known for its smooth combat system and roguelike style, making it fun to fight. There are also randomly generated levels, making it interesting to play, as well as the game's visual style being unique and appealing. | As a result of its random level generation, the difficulty may be inconsistent, leading to unstable difficulties, as well as some players feeling a lack of a real story. | To improve my game using Dead Cell's features, I could make a fluid combat system as well as a roguelike style, and maybe possibly randomly generated levels (will be hard), but I need to make sure if I implement one, that it can't spike in difficulty much and it needs to be consistent. |

### Need
To improve young teen's hand-eye coordination and cognitive abilities while developing their motor skills, as well as offering a fun and entertaining way to improve essential developmental skills, such as reaction times, problem-solving skills.

### Problem Statement
Lots of teenagers struggle with concentrating due to their short attention spans, which is caused by short-form videos such as Tiktok, Youtube Shorts and WeChat Channels. By making a very interesting game, users will want to interact with the challenges within the game, resulting in a repaired attention span, allowing them to focus on other aspects of life, like school.

### Skill Development
To develop the skills in Unity required to create the game, I would complete the 2D Roguelike tutorial, which can teach me the basics of the game, allowing me to expand further and explore better game features.

## Requirements Outline
### Inputs
- Movement Keys: WASD, Arrows
There will be an "8 directional" player movement system which allows people to move whenever they want (up, down, left, right, diagonals).
- Ability Keys: Designated keys for abilities (shooting, punches, e.g.)
- GUI Keys: Buttons to open inventory, interact, and more.

### Processing
The game will detect the user for when an enemy is defeated, which will then update the score accordingly. Also, when the user loses a life, they will also lose some of their score, and when they lose all of their lives, they will lose and enter the lose screen.

### Outputs
The player's avatar with their location and health will be displayed, along with their inventory (like weapons and tools). When the user kills an enemy, there will be a death sound as well as when the user loses a life or dies.

### Transmission
There will not be any online transmissions as the 2D Roguelike game is going to be single player, meaning everything will be stored on the computer. There may be a leaderboard system to see who can reach the highest score in the game.

### Storage
The game will have all of the assets in different categorised folders (e.g. sprites, scripts, and prefabs), just like in the 2D platformer game that everyone designed last term. The whole game will be tried to be optimised, ensuring that users with low/slow storage can run it without it being laggy.

## Functional Requirements
### User Interaction
The user will interact with the game using the keyboard and mouse inputs. They can move their character, select their weapon, etc. They can press a button for their inventory, which will be able to switch weapons or tools (like Soul Knight), and buttons to use their abilities,

### Scoring and Feedback
Every time the user defeats a monster and unlocks the next level, they get a specific amount of points. They get even more when they rescue the main character's best friend, which results in beating the game, ending up in the win screen, which will show their score and high score. This will be the same for if they lose all their lives, but with a "GAME OVER" text and a different background.

### Level Progression or Simulation Stages
There will be multiple levels of the dungeon, allowing players to have a fulfilling amount of gameplay, so that the main character is defeating monsters and enemies until they save their best friend and then beating the game.

### Saving and Loading Data
The game will store all of the game data locally on the computer, so that it is able to be played offline whenever the user pleases, even without wifi, unlike some games. There will be an auto-saving feature everytime the player enters a new level so that they do not lose any progress.

## Non-Functional Requirements Instructions
### Performance Requirements
The game will definitely need some optimization (just like the storage mentioned above) to make the game able to run for devices with slow parts like the CPU and memory. This can be done by optimising things in the game, including textures or the render distance, if the level is going to be very big, and out of the character's camera.

### Security Requirements
Once the game is more advanced, you can access your settings and game info through a login screen, which then decrypts the sensitive data and allows the player to access their own personal game files.

### Reliability and Availability
Since the game is locally played, it should be available basically 100% of the time, and with crash reports sent to the owner (me), allowing new bugs and features the be fixed. The game will then be updated/fixed ASAP and released to whatever platform the game is on.

## Consideration of Social and Ethical Issues
### Define the following terms:
- Equity

Equity is the fairness of a judgement to things. Basically, equity is given based on whatever someone/something needs, which is different to evenly distributing things to people/things, which is called equality. For example, if 3 people needed to see over their fence (one tall, one medium and one short), 'equity' would give them different sized blocks which would each help them see over the fence at the same height, but equality would give them the same sized block, meaning not everyone can see over the fence.
- Accessibility

How easy something is to be reached. If something has low accessibility, then it would be hard to get. If it has high accessibility, then it would be easy to get. For example, the new RTX 5090, which is scheduled to release next year, would have low accessibility as there is a high demand with limited stock. Something with high accessibility would be water, as you can basically get it anywhere, such as from your taps and at a public water dispenser.

### Accessibility
My project will mostly be able to support intermediate and experienced gamers over 13, as there are a lot of mechanics that new players may need to learn and practice, which will take some time, but will get some help. To help these new players, there will be things such as a tutorial level, which gets them to know the game and to know the controls and everything, so that they can actually know how to play the game. Younger players under 13 may not be mature enough to handle the graphics.

### Privacy and Data Protection
Because the game is very new and is not big, there will be no need to collect any of the user's personal information like where they live. The program will definitely need to collect the user's game data like the score and other files, but it will definitely be encrypted and stored securely, so that no cybercriminals can access it and use it for malicious intent.

### Fairness and Representation
The game will not be stereotypical or discriminatory, it will only include monsters and a main character, along with their best friend. If the game further develops in the future, there may be some character customization.

### Mental and Emotional Well-Being
It will be pretty hard for the game to affect the player's mental health, as it is not too hard to play and there is a tutorial level to get them started. The monsters and the deaths are not too gorey or gruesome, so that everyone can enjoy and not get affected by the game in terms of its maturity. There will be an age rating of 13+, to make sure everyone is suitable for the game.

### Cultural Sensitivities
The content is not offensive to cultures, as it is just about someone killing monsters and rescuing their best friend. There will not be anything related to any relgions that offend it, including satanic symbols, etc. The game is supposed to be friendly (apart from the monsters) and playable, and not made to be offending cultures.

# Researching and Planning
## Flowchart and Pseudocode
### User Interaction
![alt text](<User Interaction.drawio.png>)

&nbsp; START

&nbsp; Input from User

&nbsp; IF 'W' pressed THEN

&nbsp; &nbsp; Move up

&nbsp; ELSE IF 'A' pressed THEN

&nbsp; &nbsp; Move left

&nbsp; ELSE IF 'S' pressed THEN

&nbsp; &nbsp; Move down

&nbsp; ELSE IF 'D' pressed THEN

&nbsp; &nbsp; Move right

&nbsp; END

### Scoring and Feedback (if applicable)
![alt text](<Scoring and Feedback.drawio.png>)

&nbsp; START

&nbsp; Event Happening

&nbsp; IF 'Monster Defeated' THEN

&nbsp; &nbsp; Give 1 Point

&nbsp; ELSE IF 'Level Cleared' THEN

&nbsp; &nbsp; Give 50 Points

&nbsp; ELSE IF 'Friend Saved' THEN

&nbsp; &nbsp; Give 100 Points

&nbsp; Save Score

&nbsp; END

### Level Progression or Simulation Stages (if applicable)
![alt text](<Level Progression.drawio.png>)

&nbsp; START

&nbsp; User beats level

&nbsp; &nbsp; Enter current level + 1

&nbsp; IF 'Last level' THEN

&nbsp; &nbsp; Play winning screen

&nbsp; END

### Saving and Loading Data
![alt text](<Saving and Loading Data.drawio.png>)

&nbsp; START

&nbsp; User beats a level

&nbsp; &nbsp; Save score and items

&nbsp; User manually saves level

&nbsp; &nbsp; Save score, items and position

&nbsp; END

## Storyboards
### Flowchart
![alt text](<Whole Game Storyboard.drawio-1.png>)

## Gantt Chart
![alt text](<Copy of Gantt Chart Example - Sheet1-1.png>)

