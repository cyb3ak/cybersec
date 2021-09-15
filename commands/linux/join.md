# join

* to join the two files based on a **key field present in both the files**
* The input file can be separated by white space or any delimiter

**Syntax:**

```text
join [OPTION] FILE1 FILE2
```

**`NOTE :`** When using `join` command, both the input files should be sorted on the `KEY` on which we are going to join the files.

```text
join file1.txt file2.txt
```

* by default `join` command takes **first column** as `key` to join files

### Useful Links

* [https://www.geeksforgeeks.org/join-command-linux/](https://www.geeksforgeeks.org/join-command-linux/)

