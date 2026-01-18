Shell Scripting for DevOps – Basics
1. Kernel

The kernel is the core component of the operating system.
Written mainly in C
Directly interacts with hardware such as CPU, memory, disk, and network
Users cannot interact with the kernel directly
Acts as a bridge between the operating system and hardware

2. Shell

The shell is a command-line interface that allows users to communicate with the kernel.
Converts user commands into instructions for the kernel
Makes system operations easy and user-friendly
Common types of shells:
bash
sh
zsh
Command Flow
User → Shell → Kernel → Hardware

3. Why Shell Scripting?

Shell scripting is used to:
Automate repetitive tasks
Execute multiple commands together
Manage servers efficiently (DevOps automation)

4. Shebang (#!)
#!/bin/bash

Explanation
#! is called shebang

Tells the operating system which shell should execute the script
/bin/bash is the path of the Bash shell in Linux
Without a shebang, the OS does not know which interpreter to use

5. echo Command
echo "Hello DevOps"
echo is used to print output on the terminal

6. Variables
A variable is used to store a value that can change.
Declare a variable
name="DevOps"
Note: Do not use spaces around =
Use a variable
echo $name

7. Command Substitution
Command substitution allows you to run a command inside another command.
Syntax
$(command)
Example
echo "Today’s date is $(date)"


$(date) executes the date command

The output is inserted inside echo
