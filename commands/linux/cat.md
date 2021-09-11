# cat

`🏷️ Tags:` **\#cat**

**\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_**

 _It can **read**, **concatenate**, and **write** file contents to the **standard output**. If no file is specified or the input file name is specified as a single hyphen_ **`(-)`**_, it **reads** from the **standard input**._

### Display file content

```text
cat filename
```

#### Redirect Contents of File <a id="redirect-contents-of-file"></a>

 Instead of displaying the output to `stdout` \(on the screen\), you can redirect it to a file.

```text
cat file1.txt > file2.txt
```

*  If the `file2.txt` file doesn’t exist, the command will create it. Otherwise, it will overwrite the file.
*  Use the \(`>>`\) operator to append the contents of `file1.txt` to `file2.txt`

\`\`

