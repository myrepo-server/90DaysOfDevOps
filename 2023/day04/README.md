# Day 4 Task: Basic Linux Shell Scripting for DevOps Engineers.

## What is Kernel

The kernel is a computer program that is the core of a computer’s operating system, with complete control over everything in the system.

## What is Shell

A shell is special user program which provide an interface to user to use operating system services. Shell accept human readable commands from user and convert them into something which kernel can understand. It is a command language interpreter that execute commands read from input devices such as keyboards or from files. The shell gets started when the user logs in or start the terminal.

## What is Linux Shell Scripting?

A shell script is a computer program designed to be run by a linux shell, a command-line interpreter. The various dialects of shell scripts are considered to be scripting languages. Typical operations performed by shell scripts include file manipulation, program execution, and printing text.

**Tasks**

- Explain in your own words and examples, what is Shell Scripting for DevOps.
= so shell scripts are helpful for executing some bunch on command ex like as devops enginner i create as script for doing something related to free disk like every day at morning automatically delete the temp file so i add this script on cron tab so cron tab will execute this script every day at morning and alos shell script help us into automation

- What is `#!/bin/bash?` can we write `#!/bin/sh` as well?
so #!/bin/bash is broune again shell so its a standerd for linux script without this we can't write script 
and we can write script #!/bin/sh in its simple and lightwait shell that available in linux 

- Write a Shell Script which prints `I will complete #90DaysOofDevOps challenge`
create file file with .sh syntax and go inside that file add add 
#!/bin/bash
echo "I will complete #90DaysOofDevOps challenge"
save adn exit

and now give execute permission that file using chmod
that all

- Write a Shell Script to take user input, input from arguments and print the variables.

Bash
#!/bin/bash

# Get user input
read -p "Enter a message: " message

# Get input from arguments
if [[ $# -gt 0 ]]; then
  for arg in "$@"; do
    echo "Argument: $arg"
  done
fi

# Print all variables
echo "Message: $message"
echo "Arguments: $@"

- Write an Example of If else in Shell Scripting by comparing 2 numbers

#!/bin/bash

# Get two numbers from the user
read -p "Enter the first number: " num1
read -p "Enter the second number: " num2

# Compare the two numbers
if [ $num1 -gt $num2 ]; then
  echo "The first number ($num1) is greater than the second number ($num2)."
elif [ $num1 -lt $num2 ]; then
  echo "The first number ($num1) is less than the second number ($num2)."
else
  echo "The two numbers are equal."
fi
Was it difficult?
its little hard that python because shell scripting have complex syntax compering to python and javascript

- Post about it on LinkedIn and Let me know :)

Article Reference: [Click here to read basic Linux Shell Scripting](https://devopscube.com/linux-shell-scripting-for-devops/)

YouTube Vedio: [EASIEST Shell Scripting Tutorial for DevOps Engineers](https://www.youtube.com/watch?v=_-D6gkRj7xc&list=PLlfy9GnSVerQr-Se9JRE_tZJk3OUoHCkh&index=3)

[← Previous Day](../day03/README.md) | [Next Day →](../day05/README.md)
