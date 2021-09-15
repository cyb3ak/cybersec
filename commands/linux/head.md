# head

* prints the top N number of data of the given input.
* By default, prints first 10 lines

### **Syntax:** 

```text
head [OPTION]... [FILE]..
```

![](../../.gitbook/assets/head.png)

## Usecases

### Display a Specific Number of Lines <a id="display-a-specific-number-of-lines"></a>

```text
head -n 5 file.txt
```

### Display a Specific Number of Bytes  <a id="display-a-specific-number-of-bytes"></a>

```text
head -c 5 file.txt
```

### Display Multiple Files  <a id="display-multiple-files"></a>

```text
head filename1.txt filename2.txt
```

### Use with pipe operator

```text
ls /etc | head -n 5
```

### Useful Links

* [https://linuxize.com/post/linux-head-command/](https://linuxize.com/post/linux-head-command/)

