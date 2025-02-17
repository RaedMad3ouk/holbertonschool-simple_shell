# SIMPLE SHELL

## Description

Project  - Simple Shell - A simple UNIX command interpreter that executes commands read from the standard input or from a file. Based on the Bourne Shell.

## List of Allowed Functions and System Calls	
    all functions from strings.h
    access (man 2 access)
    chdir (man 2 chdir)
    close (man 2 close)
    closedir (man 3 closedir)
    execve (man 2 execve)
    exit (man 3 exit)
    _exit (man 2 _exit)
    fflush (man 3 fflush)
    fork (man 2 fork)
    free (man 3 free)
    getcwd (man 3 getcwd)
    getline (man 3 getline)
    getpid (man 2 getpid)
    isatty (man 3 isatty)
    kill (man 2 kill)
    malloc (man 3 malloc)
    open (man 2 open)
    opendir (man 3 opendir)
    perror (man 3 perror)
    printf (man 3 printf)
    fprintf (man 3 fprintf)
    vfprintf (man 3 vfprintf)
    sprintf (man 3 sprintf)
    putchar (man 3 putchar)
    read (man 2 read)
    readdir (man 3 readdir)
    signal (man 2 signal)
    stat (__xstat) (man 2 stat)
    lstat (__lxstat) (man 2 lstat)
    fstat (__fxstat) (man 2 fstat)
    strtok (man 3 strtok)
    wait (man 2 wait)
    waitpid (man 2 waitpid)
    wait3 (man 2 wait3)
    wait4 (man 2 wait4)
    write (man 2 write)

## File Structure	
   	0. [main.c] (main.c) - The main function for simple_shell
		* ``void prompt(void)`` - Display the prompt and wait for user input
		*``char *parse_input(char *buffer)`` - Parses the user input to get the command.
		*``void execute_command(char *command)`` - Executes the command entered by the user.
		*``int main(void)`` - Runs the shell loop.



## Authors
	Toukebri Ahmed 
	Bedouihch Raed

