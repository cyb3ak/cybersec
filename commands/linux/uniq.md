# uniq

to detect the **adjacent** duplicate lines and also deletes the duplicate lines

if duplicates are not adjacent the command won't work as expected. In that case, use **`sort`** command first & then use **`uniq`**

**`Syntax`**

```text
uniq [OPTIONS] [INPUT] [OUTPUTFILE]
```

* If **`[OUTPUTFILE]`** is not specified. it outputs to **`stdout`**

### Useful commands

###  **1. Using -c option :** It tells the number of times a line was repeated. 

```text
uniq -c file.txt
```

###  2. **Using -u option :** It prints only the unique lines. 

```text
uniq -u file.txt
```

### Useful Links:

[https://www.geeksforgeeks.org/uniq-command-in-linux-with-examples/](https://www.geeksforgeeks.org/uniq-command-in-linux-with-examples/)

