# Pig Game
Pig Game based on a tutorial by Jonas Schmedtmann.

To use:
- Clone or download to a local folder
- Change directory to newly created folder
- In the terminal run 'npm install' and then 'npm run dev'

GAME RULES:

- The game has 2 players, playing in rounds
- Set winning score
- In each turn, a player rolls 2 dices as many times as he whishes. Each result gets added to his ROUND score
- BUT, if the player rolls a 1, all his ROUND score gets lost. After that, it's the next player's turn
- The player can choose to 'Hold', which means that his ROUND score gets added to his GLOBAL score. After that, it's the next player's turn
- Player loses GLOBAL score if double 6 dice is thrown
- The first player to reach winning score points on GLOBAL score wins the game