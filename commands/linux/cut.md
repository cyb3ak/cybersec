# cut

**`cut`** command extracts portions of text from a file or piped data.

[🧠](https://emojipedia.org/brain/) `cut` command operates **line by line** for any input

**Cons:** It doesn’t support specifying more than one character as a delimiter and it doesn’t support multiple delimiters

### Syntax

```text
cut OPTION... [FILE]...
```

 `OPTION` that tell `cut` whether to use a **delimiter**, **byte position**, or **character** when cutting

* **`-f`** \(`--fields=LIST`\) - Select by specifying **a field**, a **set of fields\(x,y,z...\)**, or a **range of fields\(x-y\)**. This is the most commonly used option.
* **`-b`** \(`--bytes=LIST`\) - Select by specifying **a byte**, a **set of bytes**, or a **range of bytes**.
* **`-c`** \(`--characters=LIST`\) - Select by specifying **a character**, **a set of characters**, or a **range of characters**.  **`Tabs` and `backspaces`** are treated as a character

### Useful Links:

* [https://www.geeksforgeeks.org/cut-command-linux-examples/](https://www.geeksforgeeks.org/cut-command-linux-examples/)

