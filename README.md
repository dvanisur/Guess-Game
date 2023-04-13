# Guess-Game.

This is an interesting game. Lets play!...

      from random import randint

      guessNumber = int(input("Please enter your guess numbeer between 1 to 5: "))

      randomNumber= randint(1,5)

      if guessNumber == randomNumber:
          print ("You have won")
      else:
          print("You have lose")
          print("random number is: ", randomNumber)
      print(f'You chose : {guessNumber}')
