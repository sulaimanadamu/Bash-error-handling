# Error Handling 

Error Handling is a deliberate effort of anticipating and managing errors that may arise in script execution
There are alot of things that could bring about error in bash, some of this errors might arise due to incorrect syntax,
system version, or dependencies not installed. 
Error Handling is important for reliability, robustness and usability of the shell script.
Some steps you might consider taking to Handling errors are
- Identify potential Error: this is the part where you sit back and look at your program for what could possibly go wrong.
questions like. this is a calculator what if the user enters a string what should the system do. e.t.c

- use conditional statements(if elif else): use this to execute another part of the code if the program falls into an error
category. this conditionals can really come in handy if properly used ofcourse.

Don't forget to provide users with a descriptive message if their input is what is generating the error.