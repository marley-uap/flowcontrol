# Hands On
## OBJECTIVE:
The goal of this activity is to create an application that allows a user to play a number guessing game with a computer. Through this exercise, you will gain hands-on experience using different flow control statements.

## INSTRUCTIONS:

1. Create a new Java file named following the format YourLastNameNumbersGuessingGame.java.
2. Import the Scanner and Random classes:
  
<details>
  <summary>Solution</summary>
  <img width="248" alt="image" src="https://github.com/user-attachments/assets/da256b08-ceaa-4f2c-bde1-9b5efa913dd6">
</details>
3. Create a method named getRandomNumber that returns a whole number from 1 to 5000:

<details>
  <summary>Solution</summary>
  <img alt="image" src="https://github.com/user-attachments/assets/89bb8ea6-c818-46cd-b6a2-37229b628215">
</details>

4.Inside your main method, call the getRandomNumber method and store the result in an int variable named randomNumber. Print its value.

  <img alt="image" src="https://github.com/user-attachments/assets/76558fd7-88ab-4235-8c78-9d76d14262b5">

5.Create a method named guessNumber. This method should not return any value but should accept a whole number as the single parameter. This parameter will hold the value of our randomly generated number that the user needs to guess.

6.Inside the guessNumber method, create a Boolean variable named isGuessCorrect with an initial value of false. This will contain the result of the validation to check if the entered value matches the generated random value.


7. Create a logic that accepts a guess from the user as long as the guess is not yet correct. Create a while block that continues checking while isGuessCorrect is false.


8. Inside the while block, ask for a guess. Validate if the value matches the number we are looking for and update the value of isGuessCorrect based on the evaluation result. If the guess is correct, print “You Won!”.
<img alt="image" src="https://github.com/user-attachments/assets/d045d184-c0fd-464a-9217-ada32a2918a8"/>

9.Build and execute your code. Enter values that do not match the random number a few times. Notice how the program keeps asking for a guess as long as the guess is incorrect. This happens because the while statement re-executes the code block as long as the condition is satisfied.

10. Delete the print statement in the main method to keep the random number hidden from the user.

  
