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

### Decoding Process:
  1. Click the Decode button.
  2. Select an image file that contains a hidden message.
  3. The hidden message will be displayed in the text box.

## Installation and Requirements
### Prerequisites:
* Python 3.x
* Required Libraries:
    * `Pillow`
    * `tkinter`
 
### Steps to Install:
1. Clone the repository:
   ```bash
    git clone https://github.com/yourusername/steganography.git
    cd steganography
   ```
2. Install the dependencies:
   ```bash
    pip install pillow
   ```
### Running the Application:
Run the steganography.py file:
   ```bash
    python steganography.py
   ```


## Project Structure
* `steganography.py`: Main application code with GUI and encoding/decoding logic.
* `README.md`: Documentation for the project.


## Technologies Used
* `Python`: Core programming language.
* `Pillow`: For image processing.
* `Tkinter`: For building the graphical user interface.
