# less

`🏷️ Tags:` **\#less**

**\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_**

_displays the contents of a file or a command output,_ **one page at a time.** It also **allows** you **to navigate** both forward and backward through the file.

 **💡** mostly used to open large files

### View Content

```text
less filename
```

#### Redirect the output

 redirect the output from a command to **`less`** using a **`pipe`** operator. eg-

```text
ps aux | less
```

### Navigating Through the File Content 

* **`q`** -  quit out of less
* **`g`** - Moves to the beginning of the text file.
* **`G`** - Moves to the end of the text file.
* **`/pattern`** - search forward for a pattern
* **`?pattern`** - search backward for a pattern

#### navigate in the same page:

* **`Down arrow key`** - scroll downwards / forward
* **`Up arrow key`** - scroll upwards / backward
* move some line downwards - type number of lines followed by **`f`**
* move some lines upwards -  type number of lines followed by **`b`**

#### navigate between pages:

* **`f`** - to go forward / next page
* **`b`** - to go back / previous page

### Commands

| Command | Action |
| :--- | :--- |
| `Down arrow`, `Enter`, `e`, or `j` | Move forward one line. |
| `Up arrow`,`y` or `k` | Move backward one line. |
| `Space bar` or `f` | Move Forward one page. |
| `b` | Move Backward one page. |
| `/pattern` | Search forward for matching patterns. |
| `?pattern` | Search backward for matching patterns. |
| `n` | Repeat previous search. |
| `N` | Repeat previous search in reverse direction. |
| `g` | Go to the first line in the file. |
| `Ng` | Go to the N-th line in the file. |
| `G` | Go to the last line in the file. |
| `p` | Go to the beginning of fthe ile. |
| `Np` | Go to N percent into file. |
| `h` | Display help. |
| `q` | Exit `less`. |



