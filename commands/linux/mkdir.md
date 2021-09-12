# mkdir

The command that allows you to create directories or folders

### Syntax

```text
mkdir [OPTION] [DIRECTORY]
```

### Create a New Directory <a id="how-to-create-a-new-directory"></a>

```text
mkdir newdir
```

### New directory in another location

```text
mkdir /tmp/newdir
```

### If parent directory doesn't exist

```text
mkdir -p /home/cyb3ak/Tools/privsec/
```

* here **`Tools`** directory doesn't exist & **`-p`** option ensures to create one before attempting to create **`privsec`** directory

### Set Permissions when Creating a Directory <a id="how-to-set-permissions-when-creating-a-directory"></a>

```text
mkdir -m 700 newdir
```

### Create Multiple Directories <a id="how-to-create-multiple-directories"></a>

```text
mkdir dir1 dir2 dir3
```

### Useful Links

* [https://linuxize.com/post/how-to-create-directories-in-linux-with-the-mkdir-command/](https://linuxize.com/post/how-to-create-directories-in-linux-with-the-mkdir-command/)

