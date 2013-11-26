run-group
=========

Run a command (as a child process) and timeout if the command doesn't finish
within a specified amount of time.  If the command launches any children of
its own, track those children (using process groups) to make sure those
children all finish when the parent finishes, too.
