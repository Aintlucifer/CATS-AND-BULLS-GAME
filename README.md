## <span style="color: pink;">PROBLEM STATEMENT</span>
Design and implement a virtual Mastermind game (also called cows and bulls game): The computer generates a 4 digit random number M that is not shown to the player (end user). The player guesses the number. If a guessed digit is present in M and is in the correct position, it is a 'bull' or 'B'. If a guessed digit is present in M but not in the correct position, it is a 'cow' or 'C'. Nothing is mentioned for the guessed digit that is not present in M. When the player guesses the number, system responds with the number of bulls and cows. Example, suppose the random generated number is 2345, and the player has guessed 2468, then the system responds with 1 bull and 1 cow or 1B & 1C. Player makes a second guess 1234, system responds with 3C or 3 cows. The game finishes when the player guesses the number correctly (that is, 4 bulls or 4B) or number of tries reaches 10. If player isn't able to guess within 10 tries, then the system responds with - Sorry, you lose! If the player guesses the number correctly within 10 tries, system responds with - Yeah, you are a champ!

## <span style="color: pink;">RULES TO FOLLOW</span>
HOW TO PLAY?</br>
#USER thinks of a secret code, and attempts to guess the code within a limited number of attempts.</br>
#GAME selects a secret code, which consists of a sequence of 4 digits.</br>
#USER makes an initial guess at the secret code.</br>
#GAME provides feedback using the terms "Cows" and "Bulls" based on the guess.</br>

</br>FEEDBACK DEFINATIONS:</br>
#A "Cow" represents a correct digit in the wrong position.</br>
#A "Bull" represents a correct digit in the correct position.</br>

EXAMPLE:</br>
If the secret code is "1234" and the guess is "1350":</br>
One "Cow" because the digit "1" is correct but in the wrong position.</br>
One "Bull" because the digit "3" is correct and in the correct position.</br>
