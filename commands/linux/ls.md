# ls

lists directory contents of files and directories.

```text
ls
```

```text
ls [dir-path]
```

### Output

#### understanding 1st charater of output

* **`-`** in the 1st character = **`file`**
* **`d`** in the 1st character = **`directory`**
* **`s`** in the 1st character = **`socket file`**
* **`l`** in the first charater =  **`link file`**

#### understanding rest of the fields of output

1. **Field 1 – File Permissions**: Next 9 character specifies the file's permission. The format looks like **`rwx`** **`rwx`** **`rwx`**

   Every 3 characters specify **`read (r)`**, **`write (w)`**, **`execute (x)`** permissions for `user(root)`, `group` and `others` respectively in order.

2. **Field 2 –** Number of links
3. **Field 4 –** File Group
4. **Field 5 –** Size in bytes
5. **Field 6 –** Last modified date and time
6. **Field 7 –** Filename

### Useful Usecases

 Display One File Per Line

```text
ls -1
```

 Display All Information About Files/Directories

```text
ls -l
```

  ****Display File Size in Human Readable Format

```text
ls -lh
```

 Order Files Based on Last Modified Time

```text
ls -lt
```

 Display Hidden Files

```text
ls -la
```

 Display File UID and GID - shows the **`UID`** and **`GID`** in numeric format instead of names.

```text
ls -n [filepath]
```

### References & links

* [https://www.geeksforgeeks.org/practical-applications-ls-command-linux/](https://www.geeksforgeeks.org/practical-applications-ls-command-linux/)
