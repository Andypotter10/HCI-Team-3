# First functional version of the digital prototype
<img src="assets/First Digital version.png" width="1800px">

## Requirements Met in this Version
### Functional Requirements

| **ID**     | **Name**                  | **Description** |
|------------|---------------------------|-----------------|
| **FR-01**  | Dice Rolling Mechanics    | The game must allow players to roll dice with faces proportional to their educational level.|
| **FR-02**  | Result Validation         | If a player rolls the dice and moves incorrectly, the opposing player can challenge the move. The student who made the mistake will be penalized, and the other rewarded.|
| **FR-03**  | Movement Tracking         | Penguins must move one tile at a time, visually tracking their progress.|
| **FR-04**  | Error Handling            | If an incorrect result is validated by mistake, movement penalties must be applied accordingly.|
| **FR-07**  | Turn-Based Gameplay       | Players must take turns rolling the dice and moving their penguin.|
| **FR-09**  | Subtraction Rule          | When performing a subtraction, the larger number must always be positive.|
| **FR-11**  | Addition and Subtraction Rules | If both dice show the same color, players must add the values; if the colors are different, they must subtract.|
| **FR-12**  | Third-Party Intervention | If there is a calculation or accounting error, a third party (such as a virtual teacher) must intervene to correct it.|

### Non-Functional Requirements

| **ID**     | **Name**                  | **Description** |
|------------|---------------------------|-----------------|
| **NFR-01** | System Performance        | The game must load each scenario in less than three seconds to ensure a smooth experience. |
| **NFR-05** | Multi-Device Support      | The game should be compatible across multiple screen sizes and resolutions. |
