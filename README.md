# Liars-Dice
Liar's Dice is a game involving a minimum of two players rolling five dice each and raising bets on the rolled values, both their own and their opponents. The extended scene can be found here: https://www.youtube.com/watch?v=_tnLYEwZRgU, which shows the game in play during the film Dead Man's Chest.

Features:
- The player can choose the number of bots to play against
- Once the dice are cast, the player is able to see their roll. Bots' rolls are stored but cannot be seen by the player
- The game goes around for each bot and the player, with each able to either raise the bet (through number of dice or change of face) or call another's bluff
- Once bluff is called, the game checks all the dice faces and awards the win to either the caller (if the call was correct), or the callee (if the bet was sound)

Issues:
- Sometimes the bots call bluff simply because the previous bot managed to raise the bet too high
- Probability and bet making needs refinement
