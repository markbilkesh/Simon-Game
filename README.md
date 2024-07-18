# Simon Game

This is a simple implementation of the classic Simon Game using HTML, CSS, and JavaScript (with jQuery).

## How to Play

- The game will start when you press any key.
- Follow the pattern of lights and sounds for as long as you can by pressing the same color buttons.
- After each correct sequence, the pattern will become longer.
- If you press the wrong button, the game will end and you can start over by pressing any key.

## Files

- `index.html`: The main HTML file that sets up the structure of the game.
- `styles.css`: The CSS file that styles the game.
- `game.js`: The JavaScript file that contains the game logic.

Key JavaScript Functions
• nextSequence(): Generates the next color in the sequence.
• checkAnswer(currentLevel): Checks the user's answer against the game sequence.
• playSound(name): Plays the corresponding sound for a given color.
• animatePress(currentColor): Animates the button press.
• startOver(): Resets the game.
