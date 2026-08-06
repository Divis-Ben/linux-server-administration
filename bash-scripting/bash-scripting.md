# Bash Scripting

## Overview

This section demonstrates the basics of Bash scripting in Linux. Bash scripts help automate repetitive tasks, making system administration more efficient and reducing manual work.

## Objectives

- Understand the structure of a Bash script
- Create executable Bash scripts
- Use variables
- Display output with `echo`
- Execute Linux commands inside a script
- Run scripts from the terminal

## Scripts Included

### 1. hello.sh

Prints a simple welcome message.

```bash
#!/bin/bash

echo "Hello, World!"
echo "Welcome to Linux Server Administration"
```

### 2. system-info.sh

Displays basic system information.

```bash
#!/bin/bash

echo "Current User: $(whoami)"
echo "Hostname: $(hostname)"
```

### 3. system-status.sh

Displays useful system information.

```bash
#!/bin/bash

echo "Disk Usage:"
df -h

echo "Current Directory:"
pwd
```

## How to Run a Script

Make the script executable:

```bash
chmod +x hello.sh
```

Run the script:

```bash
./hello.sh
```

## Skills Demonstrated

- Creating Bash scripts
- Executing scripts
- Using variables
- Using Linux commands inside scripts
- Basic automation

## Conclusion

Bash scripting is an essential skill for Linux system administrators and DevOps engineers. It enables automation of repetitive tasks and improves efficiency in managing Linux systems.
