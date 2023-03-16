# Speak Number Guess

Number guessing game where you speak your guess into the microphone using the speech recognition API

## Description

This a number guessing game that uses speech recognition to capture the user's guess.

It initializes a constant variable `msgEl` to store the HTML element with ID `msg`, which will be used to display messages to the user.

It generates a random number between 1 and 100 using the `getRandomNumber()` function.

It sets up a speech recognition object using the `SpeechRecognition()` constructor.

It starts the speech recognition service using the `start()` method.

When the user speaks, the `onSpeak()` function is called. It captures the user's speech and passes it to the `writeMessage()` and `checkNumber()` functions.

The `writeMessage()` function displays the user's speech in the HTML element stored in `msgEl`.

The `checkNumber()` function checks if the user's speech is a valid number between 1 and 100. If the speech is not a valid number, an error message is displayed. If the speech is valid, the function checks if the number is equal to the randomly generated number. If the numbers match, a congratulatory message is displayed and a "Play Again" button is added to the page. If the user's guess is too high or too low, a message is displayed indicating which direction the user should go.

The `getRandomNumber()` function generates a random number between 1 and 100 using the `Math.random()` and `Math.floor()` methods.

It sets up event listeners for the speech recognition service, the end of the speech recognition service, and a click event for the "Play Again" button. If the "Play Again" button is clicked, the page is reloaded.

Overall, this code implements a simple number guessing game using speech recognition to capture the user's guess.

## License

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Technologies Used

![HTML 5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

![CSS 3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

![Javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 😂 Here is a random joke that'll make you laugh!

![Jokes Card](https://readme-jokes.vercel.app/api)

https://mdb.pushkaryadav.in/generate
