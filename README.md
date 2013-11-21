#Library for Moving the Robot
Library for moving the issued robot through the MSP430.
Example code included in example.c

## General Notes
Configures with internal pull_up resistors. To be used in future implementation with the library
for interacting with the sensors.

## Functions

- `void initTimer()`
    - Initializes TimerA to be used for controlling the motors

- `void moveForward()`
    - Moves both wheels forwards

- `void moveBackward()`
    - Moves both wheels backwards

- `void shortLeft()`
    - Moves left wheel backwards and right wheel forwards
    
- `void longLeft()`
    - Moves right wheel forwards

- `void shortRight()`
    - Moves right wheel backwards and left wheel forwards
    
- `void longLeft()`
    - Moves left wheel forwards

- `void fullStop()`
    - Stops both wheels
    
## License
Anyone is free to use and modify this for any purpose, provided they pay three easy payments of $15,000




