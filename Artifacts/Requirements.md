# Digital Prototype Requirements for "Más o menos pinguinos"

## Functional Requirements

| **ID**     | **Name**                  | **Description** |
|------------|---------------------------|-----------------|
| **FR-01**  | Dice Rolling Mechanics    | The game must allow players to roll dice with faces proportional to their educational level. |
| **FR-02**  | Result Validation         | Both players must validate the result before the penguin moves. |
| **FR-03**  | Movement Tracking         | Penguins must move one tile at a time, visually tracking their progress. |
| **FR-04**  | Error Handling            | If an incorrect result is validated by mistake, movement penalties must be applied accordingly. |
| **FR-05**  | Dynamic Backgrounds       | Background scenery must change when a penguin moves to a new tile. |
| **FR-06**  | Tile Arrangement          | Players must be able to arrange tiles before starting the game to form the path. |
| **FR-07**  | Turn-Based Gameplay       | Players must take turns rolling the dice and moving their penguin. |
| **FR-08**  | Reverse Order Mechanic    | Every X turns, previously rolled dice values should repeat in reverse order. |
| **FR-09**  | Subtraction Rule          | When performing a subtraction, the larger number must always be positive. |
| **FR-10**  | Time Tracking             | The game should track relevant values, such as time between turns and movement patterns. |
| **FR-11**  | Addition and Subtraction Rules | If both dice show the same color, players must add the values; if the colors are different, they must subtract.|
| **FR-12**  | Third-Party Intervention | If there is a calculation or accounting error, a third party (such as a virtual teacher) must intervene to correct it. |

## Non-Functional Requirements

| **ID**     | **Name**                  | **Description** |
|------------|---------------------------|-----------------|
| **NFR-01** | System Performance        | The game must load each scenario in less than three seconds to ensure a smooth experience. |
| **NFR-02** | Usability                 | The interface must be intuitive and accessible for primary school children. |
| **NFR-03** | Data Security             | User progress and game data must be securely stored to prevent loss or corruption. |
| **NFR-04** | Mobile Optimization       | The game must run efficiently on both low-end and high-end mobile devices. |
| **NFR-05** | Multi-Device Support      | The game should be compatible across multiple screen sizes and resolutions. |
