# pybricks-stub-file
For use with the LEGO Mindstorms EV3 Micropython extension in Visual Studio Code. This repository contains a single file called "pybricks" that acts as a stub file of the real pybricks (located on micropython SD card image) so you can use intellisense with pybricks, even when it's not currently in your program directory when coding.

--Instructions--
* To use, simply place the "pybricks" folder in the same directory as your main script.

* Then when your ready to import your code to your ev3 robot, remove the "pybricks" file from the directory (or else the script will confuse the pybricks stub with the real pybricks folder, which ACTUALLY contains the code inside the methods & functions of each script).


Note: I'm sure there are more professional/efficient ways to accomplish the same thing without needing to add/remove a script for every configuration, but this is a very simple & straightfoward way of accomplishing the same thing. No pip installs or anything like that required.
