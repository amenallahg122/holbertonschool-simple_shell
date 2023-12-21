# Simple Shell

## Description ##

**hsh** is a simple UNIX command language interpreter that reads commands from either a file or standard input and executes them.
It also checks to see if the user’s command inputs are correct.

<h3>Usage</h3>

After compilation, the resulting program can run stand-alone, either in interactive or non-interactive mode.

<h4>Interactive Mode</h4>

In interactive mode, simply run the program and wait for the prompt to appear. 

From there, you can type commands freely, exiting with either the "exit" command or ctrl-D.

<h5>Non-Interactive Mode</h5>

In non-interactive mode, echo your desired command and pipe it into the program like this:

```echo "cd" | ./shell```

In non-interactive mode, the program will exit after finishing your desired command(s).

<h2>Installation</h2>
https://github.com/amenallah122/holbertonschool-simple_shell.git

### Compilation

`gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh`

## Functions we used
```
   - exit
   - execve
   - fork
   - free
   - getline
   - isatty
   - malloc
   - perror
   - snprintf
   - strcmp
   - strdup
   - strtok
   - waitpid
```


# flowchart
![387513799_3540172309565679_1158508219524781890_n](https://github.com/amenallah122/holbertonschool-simple_shell/assets/146720071/862f883d-80cc-4aa6-ae97-d6303659efdb)
