# wc

 `wc` command allows you to count the number of **lines**, **words**, **characters**, and **bytes** of each given file or standard input and print the result

### Syntax

```text
wc OPTION... [FILE]...
```

#### Output

without any options, the `wc` command will print four columns

1. the number of lines
2. words
3. byte counts
4. name of the file

#### When using the standard input, the file name is not shown:

```text
wc < /proc/cpuinfo
```

### Useful options

* `-l`, `--lines` - Print the number of lines.
* `-w`, `--words` - Print the number of words.
* `-m`, `--chars` - Print the number of characters.
* `-c`, `--bytes` - Print the number of bytes.
* `-L`, `--max-line-length` - Print the length of the longest line.

### Useful Links

* [https://linuxize.com/post/linux-wc-command/](https://linuxize.com/post/linux-wc-command/)

