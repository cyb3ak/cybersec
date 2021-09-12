# find

for more link : [https://tryhackme.com/room/thefindcommand](https://tryhackme.com/room/thefindcommand)

## Syntax - `find` `where` `what`

1. find
2. where
3. what

* we can use `wildcards` in the names \(`what`\)
* we can avoid `where` if we are finding in our current working directory
* for whole filesystem `where` = `/`

## Important flags

### `-type`

1. `d` = for directories
2. `f` = for files

### `-name`

* specify a name or pattern to look for
* type the whole name, or use wildcards to specify only part\(s\) of the name
* If you use `wildcards`, you need to enclose your pattern in `quotes`

==Note== : It is useful to know that you can also use the `-iname` flag; same as `-name`, but case insensitive.

### `-user`

username of the **owner** of a file is specified with the `-user` flag

### `-size`

syntax =&gt; `-size value*suffix` or `-size [-n | +n | n][c, k, M]` **size** of a file is specified with the `-size` flag

for values -

* `-n` = matches values lesser than n
* `+n` = matches values greater than n
* `n` = matches values exactly n

for suffix -

* `c` = suffix for bytes
* `k` = for KiB’
* `M` = for MiB’s.

### `-perm`

* used to specify **permissions**
* either in octal form \(ex. `644`\) or in symbolic form \(ex. `u=r`\)

can use the `–` or `/` prefix to make your search more inclusive

* `–` = will return files that match **at least** of the permissions
* `/` = will return files that match **any** of the permissions

### time-related searches

The flag consists of a **word** and a **prefix** words are:

* `min` = minutes
* `time` = days prefixes are:
* `a` = was last **accessed**
* `m` = was last **modified**
* `c` = was last **changed**

eg - specify that a file was last accessed more than 30 minutes ago `-amin +30` ==Note== : when you want to specify that a file was modified within the last 24 hours, the option `-mtime 0` is used.

### &gt; operator use

* u can use the redirection operator `>` with the `find` command
* `2> /dev/null` = to suppress any errors for better readable results

## Find SUID & SGID permission

`find directory -user root -perm /permissions` `find directory -perm /permissions` Suid permission = /4000 Sgid permission = /2000

