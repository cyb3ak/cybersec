# rm

### `unlink` command

* removes a single file at a time

### `rmdir` command

* can delete empty directories only

### `remove` command

* can remove **multiple files** at once
* can remove **directories and their contents** `recursively`.

### Use Cases

delete a single file

```text
rm filename
```

```text
unlink filename
```

remove  an empty directory

```text
rm -d dirname
```

```text
rmdir dirname
```

remove non-empty directories and all the files within them  
[💡](https://emojipedia.org/light-bulb/#:~:text=%F0%9F%92%A1%20Light%20Bulb&text=May%20also%20represent%20various%20senses,to%20Emoji%201.0%20in%202015.) avoid the remove confirmation prompt by **`-f`** flag \[**`rm -rf dirname`**\]

```text
rm -r dirname
```

emove multiple directories at once

```text
rm -r dirname1 dirname2 dirname3
```

### References & Links

* [https://linuxize.com/post/how-to-remove-files-and-directories-using-linux-command-line/](https://linuxize.com/post/how-to-remove-files-and-directories-using-linux-command-line/)

