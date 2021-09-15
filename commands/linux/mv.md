# mv

 The `mv` command is used to **`rename`** and **`move`** and files

 _To move a file or directory, you need to have_ **`write`** _permissions on both_ `SOURCE` _and_ `DESTINATION`

Syntax

```text
mv [OPTIONS] SOURCE DESTINATION
```

| Source | Destination | Action |
| :--- | :--- | :--- |
| multiple files or directories | directory | move |
| single file | existing directory | move |
| single file | single file | rename |
| directory | doesn’t exist | rename |

#### Prompt before overwriting  <a id="prompt-before-overwriting"></a>

By default, if the destination file exists, it will be overwritten

```text
mv -i file1 /tmp
```

#### Force overwriting <a id="force-overwriting"></a>

 If you try to overwrite a read-only file, the `mv` command will prompt you whether you want to overwrite the file

To avoid being prompted

```text
mv -f file1 /tmp
```

### Useful Links

* [https://linuxize.com/post/how-to-move-files-in-linux-with-mv-command/](https://linuxize.com/post/how-to-move-files-in-linux-with-mv-command/)

