
# Class 2 notes - The Coder's Computer

## Choosing a text editor

**Classifications**

- Text Editors are used to edit and manage files and folders
- IDE(Integrated Developement Environment) combines text editor, file manager, compiler, and debugger

The best text editor is the one that offers services you use and like to code with


## Basic Terminal Usage

**Cheat Sheet**

- `pwd` - Print Working Directory. Shows current directory
- `ls` - list. Shows what is in current directory
>- `ls [options] [location]`
>- `-l` is for long list
>- `/etc` list the contents of the directory

Absolute paths specify a location in relation to the root directory - always begin with `/`.
Relative paths specify a location in relation to where we currently are.

- `~` is a shortcut for home directory example: /home/user
- `.` is a reference to current directory
- `..` is a reference to parent directory
- `cd [location]` change directory. `cd` ran by itself will take you to home directory
- `file [path]` tells us what type of file something is

Navigating to a folder that contains a space can be accomplished by wrapping in quotes `'Holiday Photos'` or with an escape character (`\`) `Holiday\ Photos` or by using tab completion - typing Holiday`TAB` and letting it auto complete

Hidden files are shown using `ls -a` and begin with `.` example: .hidden

