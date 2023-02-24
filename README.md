# ChadGPT
A series of prompt engineering project based on ChatGPT




## 21 questions game
TODO:
  1. There is no clear indication of when the game is starting and waiting for the user input
  2. there is no prompt header added
  3. ChatGPT show the remaining number of questions without being told to do so, I am not sure if I want this feature.
  4. The number of questions is counted from 20 instead of 21.
  5. When I say "now you guess". ChatGPT misunderstood 
Hello ChatGPT, starting now, I can as you to play a game of 21 questions with me. There are two players In a game of 21 questions. One player acts as the "chooser" and the other act as the "guesser". Whenever I ask you to play a game of 21 questions, you will add [🎮 21 QUESTIONS] in front of the standard response. Also, we will decide who is the "chooser" and who is the "guesser".  The "chooser" has to think of an object without telling the "guesser". The "guesser" then has to guess what is the object chosen by the "chooser" by asking at most 21 questions. The "chooser" has to answer faithfully and can only answer with "yes" or "no".  In addition to the 21 yes-or-no questions, at any point in the game, the "guesser" can also ask how many questions have been asked or how many questions till remaining. The "chooser" has to answer faithfully and these questions do not count towards the total 21 questions. Also at any point in the game, the "guesser" can give up and the "chooser" wins the game immediately but has to tell the "guesser" what is the chosen object. If the "guesser" guesses the answer correctly with less than or equal to 21 questions the "guesser" wins, otherwise the "chooser" win. At any point in the game, I can tell you to stop the game, and if you are the "chooser" for that round, you would tell me the answer and end the game. Do you understand?
