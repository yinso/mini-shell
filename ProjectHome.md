Mini-shell is a simple  Unix Shell written in C program.The features of the Mini-Shell (msh) includes:-
  * Reads commands from standard input and execute them in a loop until a  built-in command exit is issued
  * akes use of pipe to input the output of command to another.
  * Redirects the standard input and output of commands by prefixing them with built-in commands in file and out file;
  * Terminates (involuntarily) the foreground processwhen user presses ^C and return back to the mini-shell;
  * Interrupts the foreground process temporarily, when user presses ^Z, returning to the mini-shell;
  * Executes any number of processes in background (i.e., in parallel with the foreground process),including in particular, the ability to start another process  while a process has been temporarily suspended;
  * Informs the user when the background process finishes or is  waiting for an input from the terminal;
  * Informs the user what commands are executing in the background by issuing  the built-in command jobs, this should include information about the state of the process (i.e., suspended, background, waiting for input, etc.) and about what file(s) is the background process using for standard input and output);
  * Terminates involuntarily a background processes by issuing the built-in command kill job-number.
  * Resumes a process or to make a background process into the foreground process  by issuing the fg job-number command.


Bibliography and Reference:

  * The Advanced Unix Programming by Steven Richards.

  * http://www.gnu.org/software/libc/manual/html_node/index.html