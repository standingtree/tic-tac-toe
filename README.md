# Tic-Tac-Toe in React
A simple tic-tac-toe game in React. The game passes React component state between parent and child elements in the DOM, and displays a winner when 3 X's or O's are marked in a row by the same player.

### How to run: 
<ol>
  <li>Default player is Player X. Click a square to claim for Player X. Game play then turns to Player O. 
</ol>

### Roadmap for future improvements: 
<ol>
  <li>Highlight winning set of 3 squares by changing the border color: This can be done by adding a setting a className property for Square, which is either "winner" or "not-winner". If checkForWinner(gameState) returns "Player X" or "Player O", pass "winner" to the className property of the Square component. Add a new CSS element for .winner, and set the border color to a new one</li>
  <li>Add a button to reset the game to initial state: Add a button to the game-board element and set its onClick property to call window.location.reload()</li>
</ol>

License: MIT 2021

Contact: Viren // standingtreetechnologies@gmail.com
