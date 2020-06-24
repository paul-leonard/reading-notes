# Paul's Reading Notes

## Code 102

### The Coder's Computer: Environment for Writing Code

#### Text Editor
Text Editor is a program the developer can use to write code.  Many different text editors exist and the choice of which one to use depends on personal preference and objective.

  ##### Available Text Editors
  - Notepad
  - Text Edit
  - Gedit
  - Atom by GitHub
  - NotePad++
  - Text Wrangler
  - BB Edit
  - Visual Studio Code by Microsoft
  - Atom
  - Brackets by Adobe
  - Sublime Text

  ##### Considerations for Choosing
  + Code completion - *autocompletes syntax to reduce keystrokes and typos*
  + Syntax highlighting - *greatly improves readability and error recognition*
  + Variety of brightness/contrast themes
  + Selection of extensions/plug-ins - *Example: Emmet increase efficency*
  + References and wikis
  + Zoom features
  + Live preview

##### The Full Integrated Development Environment (IDE)
The text editor is a one segment of what combines with other functional software to form the Integrated Development Environment.  The other suplemental software packages include a file manager, a compiler, and a debugger.

---

#### The Terminal

>Your window into the computer.
>     -Ryan's Tutorial

##### The Command Line
The **Command Line Interface** (CLI) is the textual interface for issuing commands to the computer.  The computer prompts the user for an entry.  The user enters a command.  The command can be further modified by using options or arguments.  Options are usually lead by a '-'.  Often, the computer will return outputs following a command.  Other times, the command simply runs a background process. The return of the computer's prompt to the user signifies the completion of the previous command.

A shell is used and determines the display, format, and behavior of the terminal.  Bash is the most common shell and is short for Bourne again shell.


##### Basic Navigation


Here are some basic commands as an example:
Command   |   Description
---   |   ---
pwd   |   present working directory
ls   |   list
ls   |   list including hidden files
mkdir   |   make directory
touch   |   creates new file (ex.  Touch students.txt)
cd   |   change directory
cd..   |   back one directory
cd../..   |   back two directories
echo   |   use to display a system variable
up arrow   |   get to previous commands
down arrow   |   get to more recent commands
file   |   obtain info about what type of file a file or directory is


##### About Files

**Everything is a file.**

Windows uses extensions (suffixes) to determine the type of a file.  Linux looks within a file to determine what type of file it is.

Linux is case sensitive for file names.  Windows is not.

Spaces in file names can cause complications, but there are ways around it.  One option is quotes around the file name.  The second option is a '\' before the space which nulifies the space's command line meaning.  (If you use tab completion before the space, the computer will automatically nulify the space for you!)

Hidden Files!  Any file name beginning with '.' hides that file or directory.  The command 'ls' lists all un-hidden items.  To modify that command to show the hidden files as well, write 'ls -a'.


[Return to Table of Contents for Paul's Reading Notes](README "Go back to find more notes!")

---

Thank you for visiting my page of notes.  I hope they were helpful to you.  Please also check out [my GitHub portfolio page](https://github.com/paul-leonard "Paul's GitHub Portfolio").
