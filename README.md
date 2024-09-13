# C ++ Snake Game
# Snake Game

This is a simple Snake game implemented in C++. The game runs in the terminal and offers a classic gameplay experience where the player controls a snake that grows longer as it eats food while avoiding collisions with itself. Additionally, the walls feature a wrap-around mechanic, adding a new twist to the gameplay by allowing the snake to appear on the opposite side of the screen when it crosses the boundary.

## Files

- **`Food.cpp`** / **`Food.h`**: Contains the food generation class and functions.
- **`GameMechs.cpp`** / **`GameMechs.h`**: Implements the main game mechanics.
- **`MacUILib.c`** / **`MacUILib.h`**: Contains the main game mechanics for UI (Platform-specific).
- **`Player.cpp`** / **`Player.h`**: Defines the player class and functions.
- **`Project.cpp`**: The main file that ties everything together and runs the game.
- **`objPos.cpp`** / **`objPos.h`**: Implements object position classes and functions.
- **`objPosArrayList.cpp`** / **`objPosArrayList.h`**: Manages the object position array list.

## How to Compile and Run

1. **Organize the Files**  
   Ensure all `.cpp`, `.h`, and `.c` files are in the same directory.

2. **Open Terminal or Command Prompt**  
   - On **Windows**, open Command Prompt.  
   - On **macOS/Linux**, open Terminal.

4. **Compile the Project**  
   Run the following command to compile the project using g++
   ```bash
   g++ -o snake_game Project.cpp Food.cpp GameMechs.cpp MacUILib.c Player.cpp objPos.cpp objPosArrayList.cpp
   ```

5. **Run the Executable**  
   Finally, run the executable:
   ```bash
   snake_game.exe
   ```
   

