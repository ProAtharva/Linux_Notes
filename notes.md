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

## 11. mv and cp

Moves or renames files.

```
mv oldname.txt newname.txt
mv file.txt /path/to/destination/
```

```
cp file_name folder_path/
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
rm -rf folder_name
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

# User Management (Linux)

## 1. useradd

Creates a new user.


sudo useradd username


---

## 2. passwd

Sets or changes password of a user.


sudo passwd username


---

## 3. usermod

Modifies an existing user.


sudo usermod username


---

## 4. userdel

Deletes a user.


sudo userdel username


---

## 5. groupadd

Creates a new group.


sudo groupadd groupname


---

## 6. groupdel

Deletes a group.


sudo groupdel groupname


---

## 7. usermod -aG

Adds a user to a group.


sudo usermod -aG groupname username


---

## 8. whoami

Displays current logged-in user.


whoami


---

## 9. id

Shows user ID (UID), group ID (GID), and groups.


id


---

## 10. groups

Shows groups of a user.


groups username


---

## 11. su

Switches to another user.


su username


---

## 12. sudo

Runs command as root.


sudo command
