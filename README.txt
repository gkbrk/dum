dum
===

1. What is dum?

  dum is a Version Control System (VCS).

2. TODO list

2.1. internal-generate-commit line numbers

  Currently internal-generate-commit outputs a lot of unnecessary line numbers.
  It is possible to get rid of them by keeping track of the line number that
  the tools reading the log would have, and only outputting it if they are
  different.
