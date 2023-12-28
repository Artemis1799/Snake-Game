Here's a snake game a friend of mine and I made in mips 32 assembler.

The code will be written in MIPS assembler and executed using the Mars emulator (it's free if you want to download it and try it out).

As a reminder, the principle of this game is based on controlling a snake, similar to a long line, using a scoring system.
The aim is to get the best possible score in each game.
To do this, you need to make the snake grow as big as possible by eating food pellets scattered around the environment.
The game ends when the snake hits an obstacle, the edges of the screen or its own body.

To run the program, you need to load the file "snake.asm".
Next, you need to activate the display and capture of keyboard inputs by going to the "Tools" tab to launch "Bitmap Display & Keyboard" and "Display MMIO Simulator".
In the 'BitMap Display' tool, select a 256x256 pixel square window with a pixel size of 16x16.
Don't forget to link the two widgets to your MIPS code.
Finally, all that's left to do is run your programme and interact using the keyboard inputs.
