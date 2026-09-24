# React-Tic-Tac-Toe-5
1. Overview: What does your project do?

Allows a user to play tic-tac-toe on a 5x5 board and return to previous states of the game. For a player to win they must connect 5 in a row.

2. How to run it: What installation and start commands should we use?

npm install 

npm start

3. Your contribution: What did you build or change?

I changed the board from a 3x3 board to a 5x5 board. 

For the current move only, I changed the page to show “You are at move #…” instead of a button.

I rewrote Board to use two loops to make the squares instead of hardcoding them.

The message now says "Draw" if the board is full and no one has won.

4. What you learned: Briefly describe one challenge and how you approached it.

I had some trouble changing the code from hard-coding the board to using a loop to create the squares because I did not realize that this would require assigning unique key props to the squares and the board. I approached this by looking at the errors in the console when running the page and then looking implementation of unique key props for the move buttons to assign key props for the board items.

5. References: Credit any tutorials, starters, or other resources you used.

I used the React Tic-Tac-Toe tutorial at https://react.dev/learn/tutorial-tic-tac-toe
