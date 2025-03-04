# Digital Prototype Requirements for "Más o menos pinguinos"

## Functional Requirements

| ID  | Requirement           | Description                                                                                                                                                                           |
|-----|-----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| FR1 | Digital Board         | Display a board composed of 25 square spaces (each equivalent to 6 × 6 cm pieces) with a variable layout simulating a jigsaw puzzle.                                                  |
| FR2 | Digital Tokens        | Include six digital tokens (penguins), each with a distinct color to represent a player, with the ability to move on the board following the game rules.                          |
| FR3 | Digital Dice          | Simulate two dodecahedral dice with 12 faces numbered from 1 to 12; each die has 6 green faces and 6 red faces.                                                                     |
| FR4 | Dice Roll Logic       | On each roll: if both dice show the same color, add the numbers; if they show different colors, subtract the smaller number from the larger. Sum results must be between 3–22, and subtraction results between 0–10. |
| FR5 | Movement Rule         | Compare the result with the number 12: if the result is greater than or equal to 12, move the token two spaces; if it is less than 12, move one space.                          |
| FR6 | Turn Management       | Determine turn order by having the player with the highest initial dice roll start first, and update each player's token position accordingly.                                     |
| FR7 | Game Objective        | The objective is to reach the final "ice floe" (last board space) to win the game.                                                                                                  |

## Non-Functional Requirements

| ID   | Requirement | Description                                                                                                                                                          |
|------|-------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| NFR1 | Usability   | The interface should be intuitive and child-friendly, suitable for children aged 6 to 7, with visuals that align with the penguin and ice floe theme.              |
| NFR2 | Performance | The application should respond immediately during dice rolls and token movements, updating the board state smoothly on each turn.                                  |
| NFR3 | Reliability | The system must consistently and accurately enforce arithmetic (addition and subtraction) and movement rules, ensuring stable operation throughout the game.   |
| NFR4 | Adaptability| The system should allow simulation of various board configurations, maintaining the variability of the jigsaw-like board layout.                                    |
