# MathNotesAI
![MathNotesAI](https://github.com/parthbhangla/MathNotesAI/blob/main/assests/MathNotes.gif)

Math Notes AI is a basic interactive drawing application that allows users to draw mathematical equations on a canvas. Once an equation is drawn, the application uses a multimodal LLM to calculate and display the result next to the equals sign.

This application is built using Python with the Tkinter library for the GUI and PIL for image processing. This was inspired by Apple's ["Math Notes" demo](https://www.youtube.com/live/RXeOiIDNNek?si=zsfLkfVtCoCqk1ie&t=2806) from WWDC 2024.

This has been my introduction to the Tkinter and PIL.

## Setup & Installation
- Install libraries: `pip install -r requirements.txt`
- Setup OpenAI API as enviorment variable


## Usage
- Run the application: `python main.py`

### Application Interface

The app works by placing the answer next to an equation that has not been solved (AKA has an equals sign with nothing to the right of it). An equals sign has to be the last thing you write before clicking calculate (or pressing the enter key) as it is what determines the position where the result will be printed on the canvas.

- Canvas: Draw equations using your mouse.
- Clear Button:  Clears the canvas.
- Undo Button (Ctrl/Cmd Z): Undoes the last drawing action.
- Calculate Button (Enter/Return): Calculates the drawn equation and prints the result next to the equals sign.

Also, a huge shoutout to [Ayush Pai](https://github.com/ayushpai) who's github I took reference and inspiration from for this.
