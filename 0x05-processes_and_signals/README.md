#Processes and Signals This repository contains Bash scripts that demonstrate various concepts related to processes and signals in Linux. These scripts were developed as part of the ALX Software Engineering program.

Learning Objectives

By completing these projects, you will gain knowledge and understanding of the following topics:

Understanding what a PID (Process ID) is
Knowing how to find the PID of a process
Understanding the concept of a process in Linux
Terminating a process using signals
Understanding different signals and their uses in process management
Project Tasks The repository contains the following Bash scripts:

0-what-is-my-pid: Displays the PID of the current Bash script.

1-list_your_processes: Lists all currently running processes, including process hierarchy and user-oriented format.

2-show_your_bash_pid: Displays lines containing the word "bash," allowing you to identify the PID of your Bash process.

3-show_your_bash_pid_made_easy: Displays the PID and process name of processes containing the word "bash."

Each script has its specific requirements and objectives as described in their respective files.

Usage

To run any of the scripts, navigate to the project directory and execute the desired script using the Bash interpreter. For example:

$ ./0-what-is-my-pid
4120
Requirements

All scripts are intended to be executed on Ubuntu 20.04 LTS.
Scripts should be executed using editors such as vi, vim, or emacs.
Scripts should be executable and include the shebang #!/usr/bin/env bash as the first line.
A README.md file is included at the root of the project directory.
Shellcheck (version 0.7.0 via apt-get) should be used to ensure there are no errors in the scripts.
Each script should have a comment explaining its purpose as the second line.
Please note that all scripts should adhere to the above requirements and pass Shellcheck without any errors.
