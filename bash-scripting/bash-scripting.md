# Bash Scripting

## Create a Bash script

```bash
nano hello.sh
```

## First line (Shebang)

```bash
#!/bin/bash
```

## Print text

```bash
echo "Hello, World!"
```

## Variables

```bash
name="Ben"
echo "Hello, $name"
```

## Read user input

```bash
read -p "Enter your name: " name
echo "Welcome, $name"
```

## If statement

```bash
if [ "$name" = "Ben" ]; then
    echo "Welcome back!"
fi
```

## For loop

```bash
for i in 1 2 3 4 5
do
    echo $i
done
```

## While loop

```bash
count=1
while [ $count -le 5 ]
do
    echo $count
    count=$((count+1))
done
```

## Make a script executable

```bash
chmod +x hello.sh
```

## Run a script

```bash
./hello.sh
```
