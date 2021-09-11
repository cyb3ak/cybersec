# cp

to copy files and directories, you must have at least **`read`** permissions on the **`source`** file and **`write`** permission on the **`destination`** directory

[🧠](https://emojipedia.org/brain/) When copying a file, the `new file` is owned by the `user` running the command.

### 3 types of copy operations

### file to file \(usually for bkp in same directory\)

```text
cp file file_backup
```

```text
cp file{,_backup}
```

```text
cp file destination/newfile.txt
```

if **`newfile.txt`** exist before, it will be overwritten by default

### multiple files & folders to folder

```text
cp file.txt dir file1.txt  dir1
```

### folder to folder including all subdirectories & files

```text
cp -R Pictures Pictures_backup
```

To copy only the files and subdirectories but not the source directory \(**`-T`**\)

```text
cp -RT Pictures Pictures_backup
```

