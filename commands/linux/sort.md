# sort

* for sorting lines of text files. It supports sorting **alphabetically**, in **reverse order**, **by number**, **by month**, and can also **remove duplicates**.
* sort command sorts file assuming the contents are ASCII

### sort a normal text file

```text
sort file.txt
```

* the command does not actually change the input file
* to output to a new file use **`>`** operator

#### if the text file contains UPPER & lowercase letters

* output = first UPPERCASE than lowercase

### **Sorting In Reverse Order \(-r\)**

```text
sort -r file.txt
```

### Sort files with numbers \(-n\)

```text
sort -n file.txt
```

###  **sort and remove duplicates \(-u\)**

```text
sort -u file.txt
```

### **Check if the file is sorted or not \(-c\)**

```text
sort -c file.txt
```

* if no output -&gt; file is already sorted

