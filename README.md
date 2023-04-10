# Tic-Tac-Toe

Tic-tac-toe is a game where two players X and O fill the hash (#) shaped box (consist of two vertical lines
crossing two horizontal lines) with their alternate turns.Created a two-player Tic Tac Toe game in C++
language using Array, Function, and True-False condition.



Tic-Tac-Toe game  is a simple two-player game played on a 3x3 grid, where each player takes turns to mark a cell in the grid with their designated symbol ('X' or 'O'). The objective is to get three of their symbols in a row, either horizontally, vertically, or diagonally, before the other player does. If all the cells are filled and none of the players have achieved a winning combination, then the game ends in a draw.

The basic structure of the Tic Tac Toe game contains two vertical lines and two horizontal lines passing through each other at an angle of 90 degrees and creating nine empty spaces.

So we have created the board using the c++.

![image](https://user-images.githubusercontent.com/103095458/230978880-a738f491-2576-499d-8c1b-d3a9f9637eea.png)

In the main function, you have made the tic tac toe game structure with the help of cout for printing and used multiple vertical slashes for vertical lines and multiple underscores for horizontal lines.


Now you have to add the digits at these empty spaces inside the structure to make use of these spaces for filling up X or 0’s.

So you will need to create a two-dimensional array of 3x3 matrix of character type, and store the elements of the array in these empty spaces.

Now, you must declare some global variables, and declare the array outside the function.

![image](https://user-images.githubusercontent.com/103095458/230979121-c4647b1c-63d6-4a59-8ddf-93311108d542.png)

Inside another  function, write two if statements stating that if the token's value is x, then player1 will enter the digit or number. Similarly, if the token’s value is 0, then player2 will enter the digit.

Once the player enters the digit, that number needs to be replaced by the symbol.

To replace it, you should use multiple if conditions and an else if condition.

One by one, using the if statements, you must check for each digit from 0 to 9, and whichever matches with the player’s input, that particular block will execute. If the user enters any other value that is less than 1 and more than 9, it will display Invalid.

![image](https://user-images.githubusercontent.com/103095458/230979440-82417698-a99d-4b33-a662-8f9189970682.png)
![image](https://user-images.githubusercontent.com/103095458/230979515-e26ff014-bb6b-452b-b9d0-11cd85e8489a.png)
![image](https://user-images.githubusercontent.com/103095458/230979622-e6c912ce-bc7f-459d-9393-f6d4169cb01c.png)

If the  player1 turn is there and if the position in which the player enters is vacant, there is no x and 0, then x would be assigned to that place. 

Similarly, if player2 turn is there, and the position entered by the user is vacant, then 0 would be assigned to that position; else, “There is no empty space” gets displayed.


For Checking if It’s a Win or Draw,


Use a for loop which is iterating from 0 to 3. Inside the loop, there is an if condition that checks for three pairs of x’s or 0’s both horizontally and vertically. And if there is a pair, it will return true, which means somebody won the game.Similarly, you must check for diagonal pairs.

![image](https://user-images.githubusercontent.com/103095458/230979771-81e52904-ad32-4de1-89cf-badafd7c8e8e.png)

Inside the main function, you must take the input of the names of both the players n1 and n2 and also, you have to declare these n1 and n2 strings as global variables.

Inside the While loop all the three functions are getting called one by one, and there’s a condition that the loop will keep on iterating till functionThree() is returning false. This function will keep on returning false until anyone wins the game among the two players. So these functions will keep on repeating one by one until the game is won.

![image](https://user-images.githubusercontent.com/103095458/230979946-d8e614b3-1a57-4b39-a93a-68d26fee6159.png)

Inside the if statement there’s a condition stating that if the token’s value is x and tie is false, then n2 or player2 will be the winner. It means the last turn was played by player2; that is why now the value of turn is x, and it is also not a tie as the value of tie is false. So it means player2 wins the game.

Similarly, there’s a condition for token 0, where player1 would be the winner. 

At last, if both the conditions are not met, then the game would be a tie.’






























