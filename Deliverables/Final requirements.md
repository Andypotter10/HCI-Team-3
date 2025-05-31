## Functional Requirements
| **ID**     | **Name**                  | **Description** |
|------------|---------------------------|-----------------|
| **FR-01**  | Dice Rolling Mechanics    | The game must allow players to roll dice with faces proportional to their educational level. |
| **FR-02**  | Result Validation         | If a player rolls the dice and moves incorrectly, the opposing player can challenge the move. The student who made the mistake will be penalized, and the other rewarded.|
| **FR-03**  | Movement Tracking         | Penguins must move one tile at a time, visually tracking their progress. |
| **FR-04**  | Error Handling            | If an incorrect result is validated by mistake, movement penalties must be applied accordingly. |
| **FR-05**  | Tile Arrangement          | Players must be able to arrange tiles before starting the game to form the path. |
| **FR-06**  | Turn-Based Gameplay       | Players must take turns rolling the dice and moving their penguin. |
| **FR-07**  | Subtraction Rule          | When performing a subtraction, the larger number must always be positive. |
| **FR-08**  | Addition and Subtraction Rules | If both dice show the same color, players must add the values; if the colors are different, they must subtract.|

## Non-Functional Requirements
|     **ID**  | **Name**                     | **Description**                                                                                                        |
| ----------- | ---------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| **NFR-U01** | Intuitive User Interface     | The interface must be visually engaging, age-appropriate, and easy to understand for children aged 5–7.                |
| **NFR-U02** | Ease of Navigation           | Players must be able to perform key actions within 2–3 simple steps.                                                   |
| **NFR-U03** | Consistent Interaction       | UI elements and game mechanics must behave consistently across all screens and actions to reduce confusion.            |
| **NFR-U04** | Immediate Feedback           | The system must provide instant visual feedback after each user action.                                                |
| **NFR-U05** | Error Tolerance and Recovery | The game should allow players to easily correct mistakes and provide support through hints.                            |
| **NFR-U06** | Simple Language              | All on-screen text and instructions must use language suitable for primary school students.                            |
| **NFR-U07** | Low Learning Curve           | New users must be able to understand game mechanics within the first 3–5 minutes, with help from an optional tutorial. |
| **NFR-U09** | Platform Adaptability        | The game UI must adapt to various screen sizes without loss of usability.                                              |
