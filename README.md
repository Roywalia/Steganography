# Steganography
#### This project provides a simple Python-based steganography tool that allows users to encode and decode secret messages within image files. It features a graphical user interface (GUI) built with Tkinter


## Features
1. Encode Messages in Images
   * Upload an image, type a secret message, and embed it into the image using the "Encode" functionality.
   * Save the new image with the hidden message.
2. Decode Messages from Images
   * Upload an image with a hidden message, and reveal the message using the "Decode" functionality.


## How It Works
### Encoding Process:
  1. Click the Encode button.
  2. Select an image file (.png, .jpeg, or .jpg).
  3. Enter the secret message you want to hide.
  4. Press Encode.  
    The program will create a new image file with the message embedded.



## Requirements
#### A C compiler (e.g., GCC)

## How to run
1. Clone the repository:
  ```bash
    git clone https://github.com/yourusername/Arrange-Puzzle-Game.git
    cd Arrange-Puzzle-Game
  ```

2. Compile the program:
  ```bash
    gcc -o arrange-puzzle-game main.c
  ```

3. Run the game:
   ```bash
   ./arrange-puzzle-game
   ```

## Controls
* `W` - To move the tile down
* `A` - To move the tile right
* `S` - To move the tile up
* `D` - To move the tile left
