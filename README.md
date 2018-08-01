## Hangman-Game at Coffee Shop

https://flyingunicornsf.github.io/Hangman-Game/

Organize the game code as an object, except for the key events to get the letter guessed.
functions are in the wrapped in `var hangcaffeine = {` 

Game is initialized by 
`var initializeed = false;

    document.onkeyup = function(event) {
    
        hangcaffeine.guessedLetter = event.key;
        
        if (!initializeed) {
        
            var computerPickedWord = hangcaffeine.initialize()`
            
            
### functions in hangcaffeine object

- initialize
- playGame
- didYouAlreadyGuess
- didYouAlreadyGuess (great names... Can't even think what else it could possibly do....) 
- youGuessedRight
- guessLeftCounter
- isItGameOver
- youWon
- resetGame
- playVid


