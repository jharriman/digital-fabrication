# py2gcode
Running `python run.py` will output G-Code to the standard output for creating a 2cm diameter half-sphere on a PrintrBot Simple Maker.

If you store this G-Code from the standard output to a file (using the command `python run.py > sphere.gcode` for example), you can open it in Repetir and print it out using the Printrbot.

I decided to create G-Code that would print a hemisphere following a suggestion from Professor Stevens, since a full sphere would have to have supports that are difficult to render in G-Code by hand. I argue that printing a half-sphere is equivalent to being able to print the whole sphere, since we can just glue together two copies of the half-sphere to get the whole one.

## Differences between Slic3r G-Code and my own programmatically created G-Code
