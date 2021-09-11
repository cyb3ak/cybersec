# file

`🏷️ Tags:` **\#file**

**\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_**

_displays the type of a file. It’s helpful when you have to find out the type of file you’ve never seen before or the file does not have a file extension_

### **Syntax**

```text
file [OPTION] [FILE]
```

### Without any option

```text
file filename
```

* displays name & type of file

### Show just the file type

```text
file -b filename
```

### Get multiple file info

```text
file file1 file2 file3
```

* print the type of each file on a separate line

```text
file *.jpg
```

* accepts wildcards, print all file type of jpg in current folder

