# alias

_aliases allow you to set a memorable shortcut command for a longer command_

### Creating Bash Aliases <a id="creating-bash-aliases"></a>

```text
alias alias_name="command_to_run"
```

but this is temp & is not persistent

### Make the alias persistent 

find the shell you are using: **`echo $0`**

#### If using `bash` shell

*  declare it in the **`~/.bash_profile`** or **`~/.bashrc`** file
* nano **`~/.bashrc`**
* Once done, save and close the file. Make the aliases available in your current session by typing: **`source ~/.bashrc`**

#### If using `zsh` shell

* nano **`~/.zshrc`**
* Once done, save and close the file. Make the aliases available in your current session by typing: **`source ~/.zshrc`**

## If you want to create `alias` with arguments see

* [https://linuxize.com/post/how-to-create-bash-aliases/](https://linuxize.com/post/how-to-create-bash-aliases/)

