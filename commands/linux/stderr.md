# stderr

A `file descriptor` is a non-negative number that is used to access a file or stream.

File descriptor for `stdin=0`, `stdout=1` and **`stderr=2`**

### **redirect** our **`stderr`** to the `file` :

```text
error_cmd_here 2> peanuts.txt
```

* error\_cmd\_here = can be `find`, `ls` or some command that throws any sort of error.

### get rid of stderr messages completely

```text
error_cmd_here 2> /dev/null
```

### redirect stderr & stdout to a file

```text
error_cmd_here > peanuts.txt 2>&1
```

