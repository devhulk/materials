# Accelerate University - Introduction to VI

## What is VI?
  * VI is a command line code editor that you navigate using the keyboard instead of a mouse.
  * VI takes commands from the keyboard and executes them.
  * VI is modal meaning that depending on the mode you are in the commands will behave differently.

## Command Mode
  * Moving around - H,J,K,L = (Left,Down,Up,Right)
  * If you are not in Command Mode you enter it by pressing ESC.
  
- Basic Commands
    * yy - copy line
    * p - print line
    * dd - delete line

## How to Enter and Exit a File
  * vi **file** - open a file using vi
  * :q - quit out of a file
  * :wq - quit out of a file and save changes
  * :q! - don't save changes and quit out of the file

## Insert Mode
  * Press 'i' to enter Insert Mode and begin typing
  * Press ESC to go back to Command Mode which is the default
  * A
  * I

## Visual Mode
  * Press 'v' to enter Visual Mode.
  * Visual mode will execute a command over the selected text.
  * v(nav) y
  * v(nav) d

