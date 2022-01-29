#Overview
I programmed a simple shell program in C: can accept many inputs to do a variety of shell tasks in Unix. This project used the knowledge of Unix System: child processes, signal masks/handlers, pipes.

#Details
This project is writing a simple shell. mush2 has the following basic features:
- Both interactive and batch processing. If mush2 is run with no argument it reads commands from stdin until an end of file (^D) is typed. If mush2 is run with an argument, “mush2 file,” it will read its commands from file
- Supports redirection
- Support for quoted strings
- Support for backslash escapes
- A built-in cd command
- Support for SIGINT
