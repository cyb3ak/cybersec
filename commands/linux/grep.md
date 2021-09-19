# grep

The `grep` filter searches a file for a particular **`pattern`** of characters, and displays all lines that contain that pattern.

**Syntax:** 

```text
grep [options] pattern [files]
```

### Options

```text
-c : This prints only a count of the lines that match a pattern
-h : Display the matched lines, but do not display the filenames.
-i : Ignores, case for matching
-n : Display the matched lines and their line numbers.



-E : Treats pattern as an extended regular expression (ERE)
-w : Match whole word
```

### Usecase

#### Let's use our sample.txt file as an example:

```text
$ grep fox sample.txt
```

* You should see that grep found `fox` in the sample.txt file

#### You can also grep patterns that are case insensitive with the -i flag:

```text
$ grep -i somepattern somefile
```

#### To get even more flexible with grep you can combine it with other commands with \|.

```text
$ env | grep -i User
```

#### As you can see grep is pretty versatile. You can even use regular expressions in your pattern:

```text
$ ls /somedir | grep '.txt$'
```

* Should return all files ending with .txt in somedir.



### Useful Links

* [https://www.geeksforgeeks.org/grep-command-in-unixlinux/](https://www.geeksforgeeks.org/grep-command-in-unixlinux/)

