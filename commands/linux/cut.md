# cut

**`cut`** command extracts portions of text from a file or piped data.

**Cons:** It doesn’t support specifying more than one character as a delimiter and it doesn’t support multiple delimiters

### Syntax

```text
cut OPTION... [FILE]...
```

 `OPTION` that tell `cut` whether to use a **delimiter**, **byte position**, or **character** when cutting

* **`-f`** \(`--fields=LIST`\) - Select by specifying **a field**, a **set of fields**, or a **range of fields**. This is the most commonly used option.
* **`-b`** \(`--bytes=LIST`\) - Select by specifying **a byte**, a **set of bytes**, or a **range of bytes**.
* **`-c`** \(`--characters=LIST`\) - Select by specifying **a character**, **a set of characters**, or a **range of characters**.

### Useful Links:

* [https://linuxize.com/post/linux-cut-command/](https://linuxize.com/post/linux-cut-command/)

