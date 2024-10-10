# Rock_Paper_Scissors-Game

Description : Rock paper scissors is a hand game usually played between two people, in which each player simultaneously forms one of three shapes with an outstretched hand. These shapes are "rock", "paper", and "scissors". This Python Program Project is aimed at automating one of the player called as Computerized Player and the taking rock, paper or scissor as an input from the used.

**Introduction**

Rock paper scissors (also known by other orderings of the three items, with "rock" sometimes being called "stone", roshambo or ro-sham-bo) is a hand game usually played between two people, in which each player simultaneously forms one of three shapes with an outstretched hand. These shapes are "rock" (a closed fist), "paper" (a flat hand), and "scissors" (a fist with the index finger and middle finger extended, forming a V). "Scissors" is identical to the two-fingered V sign (also indicating "victory" or "peace") except that it is pointed horizontally instead of being held upright in the air.

A simultaneous, zero-sum game, it has only two possible outcomes: a draw, or a win for one player and a loss for the other. A player who decides to play rock will beat another player who has chosen scissors ("rock crushes scissors" or sometimes "blunts scissors"), but will lose to one who has played paper ("paper covers rock"); a play of paper will lose to a play of scissors ("scissors cuts paper"). If both players choose the same shape, the game is tied and is usually immediately replayed to break the tie. Read More on Wiki Pedia.
_____________________________________________________________________________________________________________________________________________________________________________________________________________________

**Game Play**

The players may count aloud to three, or speak the name of the game (e.g. "Rock! Paper! Scissors!"), either raising one hand in a fist and swinging it down with each syllable or holding it behind their back. They then "throw" by extending it towards their opponent. Variations include a version where players throw immediately on the third count (thus throwing on the count of "Scissors!"), or a version where they shake their hands three times before "throwing". We are going to computerize this game play, so that computer will choose some random choice while the player will have the choice to choose one [Rock! Paper! or Scissors! ]
_____________________________________________________________________________________________________________________________________________________________________________________________________________________

**Rules**

A player who decides to play rock will beat another player who has chosen scissors ("rock crushes scissors" or sometimes "blunts scissors"), but will lose to one who has played paper ("paper covers rock"); a play of paper will lose to a play of scissors ("scissors cuts paper"). If both players choose the same shape, the game is tied and is usually immediately replayed to break the tie.

![RPC Game](https://github.com/user-attachments/assets/936ee401-55ba-4660-a7f1-6b58c12d3df9)
_____________________________________________________________________________________________________________________________________________________________________________________________________________________

**Possible cases** -

if (player == rock) and (computer == paper); computer wins

if (player == paper) and (computer == paper); tie

if (player == scissors) and (computer == paper); player wins

if (player == rock) and (computer == rock); tie

if (player == paper) and (computer == rock); player wins

if (player == scissors) and (computer == rock); computer wins

if (player == rock) and (computer == scissors); player wins

if (player == paper) and (computer == scissors); computer wins

if (player == scissors) and (computer == scissors); tie
_____________________________________________________________________________________________________________________________________________________________________________________________________________________

**Algorithm**

**Initialize Timer**: Start a timer that counts up to 100 seconds.

**Countdown Phase**:

If the timer is less than 20 seconds: Display "Ready!"
If the timer is less than 30 seconds: Display "Count: 3"
If the timer is less than 40 seconds: Display "Count: 2"
If the timer is less than 50 seconds: Display "Count: 1"
If the timer is less than 60 seconds: Display "GO!"
Start the Game: When the timer reaches 60 seconds, both players make their choices (rock, paper, or scissors).

**Evaluate Winner**:

If the timer is less than 100 seconds, check the players' choices:
Rock beats Scissors
Scissors beats Paper
Paper beats Rock
Determine the winner based on the rules above and display the result.
**End Game**: The game concludes after announcing the winner, and the timer can reset for a new game if desired.
_____________________________________________________________________________________________________________________________________________________________________________________________________________________

**Dependencies**

Python Language
_____________________________________________________________________________________________________________________________________________________________________________________________________________________

**Requirements**
64 Bit Windows / Open Source Linux & its derivatives.
Open Source Programming Tools like PyCharm/Python IDE (Visual Studio Code or any other).
_____________________________________________________________________________________________________________________________________________________________________________________________________________________
