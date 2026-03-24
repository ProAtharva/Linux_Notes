# Linux Basics Notes

## 1. echo

Prints text to the terminal.

```
echo "Hello World"
```

## 2. whoami

Displays the current logged-in user.

```
whoami
```

## 3. id

Shows user ID (UID), group ID (GID), and groups.

```
id
```

### id -un

Displays only the username.

```
id -un
```

## 4. ls

Lists files and directories.

```
ls
```

### Options:

* ls -a : Show hidden files
* ls -r : Reverse order
* ls -l : Detailed information
* ls -la : Detailed + hidden files

## 5. touch

Creates a new empty file.

```
touch file.txt
```

## 6. pwd

Prints the current working directory.

```
pwd
```

## 7. cd

Changes directory.

```
cd folder_name
```

## 8. file

Displays the type of a file.

```
file filename.txt
```

## 9. cat

Used to view, create, append, and combine files.

### View file

```
cat file.txt
```

### Create file

```
cat > file.txt
```

### Append content

```
cat >> file.txt
```

### Merge files

```
cat file1.txt file2.txt > merged.txt
```

### View multiple files

```
cat file1.txt file2.txt
```

## 10. clear

Clears the terminal screen.

```
clear
```

## 11. mv

Moves or renames files.

```
mv oldname.txt newname.txt
mv file.txt /path/to/destination/
```

## 12. mkdir

Creates a new directory.

```
mkdir folder_name
```

## 13. rm

Removes files or directories.

```
rm file.txt
```

Note: This action is permanent.

## 14. exit

Closes the terminal session.

```
exit
```

## Quick Tips

* Use Tab for auto-completion
* Use Up Arrow to reuse previous commands
* Be careful with rm (no undo)

16. man - manual of any command if not understanding.
