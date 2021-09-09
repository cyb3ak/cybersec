# locate

### ⌨️ updatedb

`Note:` Before using locate command use this command

```text
updatedb
```

 **updatedb** creates or updates a database used by **locate**

[✍️](https://emojipedia.org/writing-hand/#:~:text=A%20right%20hand%20holding%20a,to%20Emoji%201.0%20in%202015.) **`SECURITY`** Databases built with `--require-visibility` ****`no` allow users to find names of files and directories of other users, which they would not otherwise be able to do.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

### ⌨️ locate

 The **`locate`** command works better and faster than **`find`** __command, because **`locate`** search through a database whereas **`find`** searches the file system.

```text
man locate
```

```text
locate  [options]  [pattern]
```

**Exit Status**

* 0 = if match found
* 1 = error /  no match

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

### Installation if not present

```text
sudo apt install mlocate
```

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

### Use cases

#### Search a file with a specific name

```text
locate filename.txt 
```

#### Limit Search Queries to a Specific Number

```text
locate "*.html" -n 20
```

#### Display number of specific file type \(output = no of .txt file\)

```text
locate -c “*.txt*”
```

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

### Useful Links

1. [https://linuxhint.com/linux-locate-command/](https://linuxhint.com/linux-locate-command/)
2. [https://www.geeksforgeeks.org/locate-command-in-linux-with-examples/](https://www.geeksforgeeks.org/locate-command-in-linux-with-examples/)

