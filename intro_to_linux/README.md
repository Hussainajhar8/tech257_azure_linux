# Linux Basics

Linux is an operating system that powers a wide range of devices, from personal computers to servers and embedded systems. Here are some fundamental concepts and commands to get you started:

## What is Linux?

Linux is an open-source operating system kernel originally developed by Linus Torvalds in 1991. It is based on Unix and provides a powerful and customizable environment for computing.

## Shell and Terminal

In Linux, the shell is a command-line interpreter that allows users to interact with the operating system by typing commands. The terminal is the interface through which the shell operates, providing a text-based environment for running commands.

GitBash, a terminal emulator for Windows, provides a Linux shell environment, enabling users to run Linux commands on a Windows system.

## Why Learn Linux?

- **Open Source**: Linux is open-source software, meaning its source code is freely available for modification and distribution. There are various distributions (distros) tailored for different use-cases, offering flexibility and choice.
- **Remote Communication**: Linux is commonly used to communicate with remote servers and virtual machines (VMs) through secure shell (SSH), enabling remote administration and management.
- **Scripting**: Linux provides powerful scripting capabilities, allowing users to automate tasks, manipulate data, and configure systems through shell scripts.
- **Monitoring**: Linux offers robust monitoring and debugging tools, making it ideal for system administration and performance optimization.

## Common Linux Commands

- **cd**: Changes the current directory. Example: `cd /path/to/directory`.
- **ls**: Lists files and directories in the current directory.
  - `-l`: Displays detailed information about files and directories, including permissions, ownership, size, and modification date. Example: `ls -l`.
  - `-a`: Shows hidden files and directories (those starting with a dot). Example: `ls -a`.
- **tree**: Displays the directory structure in a tree-like format. Example: `tree`.
![alt text](img/image.png)
- **history**: Displays a list of previously executed commands. Use `history -c` to clear the command history. Use `!<number>` to reuse a command from history.
- **curl**: Used to download files or data from the internet. Example: `curl https://example.com/file.txt`.
- **sudo**: Stands for "superuser do." It allows users to execute commands with elevated privileges.
- **apt install/update**: Package management commands used to install or update software packages on Debian-based Linux distributions. Be cautious when upgrading packages (`apt upgrade`), as it may affect the stability of the system.

   - `apt install`: Installs a package. Example: `sudo apt install <package_name>`.
   - `apt update`: Updates the package index to ensure the latest version of packages is available. Example: `sudo apt update`.

   Be careful with `apt upgrade` as upgrading packages may introduce compatibility issues if the server relies on specific package versions.
- **mv**: Moves or renames files and directories. Example: `mv file1.txt directory/`.
- **cp**: Copies files and directories. Example: `cp file1.txt file2.txt`.


- **ps**: Displays information about active processes.
   - `-s $$`: Shows system processes for the current shell session. Example: `ps -s $$`.

- **systemctl**: Manages system services.
   - `status`: Displays the status of a service. Example: `sudo systemctl status nginx`.
   - `stop`: Stops a service. Example: `sudo systemctl stop nginx`.
   - `restart`: Restarts a service. Example: `sudo systemctl restart nginx`.
   - `enable`: Enables a service to start automatically at boot. Example: `sudo systemctl enable nginx`.

- **sudo systemctl is-enabled**: Checks if a service is enabled (returns a boolean).

- **chmod**: Changes file permissions.
  
  ## Variables and environment variables
- **printenv**: Prints environment variables.
- To create a variable: `<define_variable>=<variable_value>`.
  ![alt text](img/image-6.png)
- To create an environment variable: `export <DEFINE_VARIABLE>=<VARIABLE_VALUE>`. 
  ![alt text](img/image-5.png) 
- Environment variables created manually will be lost after exiting and SSHing back in unless you modify a configuration file (e.g., .bashrc) to load them upon startup.
![alt text](img/image-4.png)
![alt text](img/image-3.png)
- Use `source .bashrc` to reload the configuration file and apply the changes.
![alt text](img/image-7.png)

## Scripting:

- To start scripts, create a file with a .sh extension and use the shebang `#!/bin/bash` at the beginning.
  - Use `chmod` command to change file permissions to make the script executable.
- `-y`: Subprompt to auto-approve without requiring user input. Example: `sudo apt update -y`.
- Nginx script we created:<br>
  ![alt text](img/image-12.png)

## Processes 

- `ps aux`: Displays information about all processes running on the system.
  
- **Daemon Processes**: Processes with a 'd' on the end, commonly indicating they are daemons.

- `top`: Interactive process viewer that displays processes sorted by various criteria like CPU usage and memory.
   - Press `Capital P` to sort by CPU usage.
   - Press `Capital M` to sort by memory usage.

- **Running and Controlling Processes**:
   - `sleep <time(s)>`: Makes the terminal or process sleep for the specified time.
   - To run a process in the background, use `&` at the end of the command. Example: `sleep 5000 &`.
   - `jobs`: Shows running jobs and their status. <br>
  
  ![alt text](img/image-13.png)

- **Zombie Processes**: Child processes left behind when a parent process is killed, consuming memory unnecessarily. <br>

![alt text](img/image-16.png)

- **Kill Command**: Used to terminate processes.
   - `kill`: Attempts to terminate processes, including child processes.<br>
  ![alt text](img/image-14.png)
   - `kill -9`: Performs a forceful termination, useful for stubborn processes.<br>
  ![alt text](img/image-15.png)
  
- **Process Managers**:
   - **PM2**: A process manager for managing Node.js applications running in the background. It ensures that applications remain running and restarts them if necessary.
   - If a process under PM2 is killed, PM2 will automatically restart it. To stop the process permanently, it must be killed using PM2 commands.
