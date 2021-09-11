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

#### Print Line Numbers <a id="print-line-numbers"></a>

```text
cat -n filename
```

### Concatenating Files  <a id="concatenating-files"></a>

#### Display concatenated output

```text
cat file1 file2
```

#### Combine multiple files to a new file

```text
cat file1.txt file2.txt > combinedfile.txt
```

*  If the `combinedfile.txt` file doesn’t exist, the command will create it. Otherwise, it will overwrite the file.
*  To concatenate the contents of `file1.txt` and `file2.txt` and append the result to `file3.txt` to use the \(`>>`\) operator

### Creating Files <a id="creating-files"></a>

```text
cat > filename.txt
```

* then press **`Enter`**
* type the content of the file
* press **`Ctrl + D`** to save

 If a file named `file1.txt` is present, it will be overwritten. Use the ‘`>>`’ operator to append the output to an existing file.

