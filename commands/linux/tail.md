# tail

* displays the last part \(10 lines by default\) of one or more files or piped data
* It can be also used to monitor the file changes in real-time \(**`-f`**\).

### syntax

```text
tail [OPTION] [FILE]
```

### Usecases

```text
tail file.txt
```

### Display last n Lines \(-n\) <a id="display-a-specific-number-of-lines"></a>

```text
tail -n <NUMBER> file.txt
```

### Display last n Number of Bytes <a id="how-to-display-a-specific-number-of-bytes"></a>

```text
tail -c <NUMBER> filename.txt
```

### Watch a File for Changes \(-f\) <a id="how-to-watch-a-file-for-changes"></a>

```text
tail -f filename.txt
```

* This option is particularly useful for monitoring log files

