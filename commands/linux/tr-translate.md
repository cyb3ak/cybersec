# tr \(translate\)

* **`Used for`** - **removing repeated characters**, converting **uppercase to lowercase**, and basic **character replacing and removing**.

### `tr` Command <a id="how-to-use-the-tr-command"></a>

```text
tr <OPTION> '<SET1>' '<SET2>'
```

accepts two sets of characters, usually with the same length, **replaces** characters of the `first sets` with the **corresponding** characters from the `second set`.

* **ranges** can also be passed instead of sets

### Refer for character classes

{% page-ref page="../../topics/character-classes-and-bracket-ops.md" %}

### Useful flags

* **`-c`** : **complements** the set of characters in string.i.e., operations apply to characters not in the given set 
* **`-d`** : **delete** characters in the first set from the output.
* **`-s`** : **replaces** repeated characters listed in the set1 with single occurrence 
* **`-t`** : **truncates** `set1`

### Convert lower to upper case

```text
echo 'cyberseclogs' | tr 'a-z' 'A-Z'
```

###  **How to squeeze repetition of characters \(-s\)**

```text
echo "Welcome    To    cybersecLogs" | tr -s [:space:] ' '
```

### Print `$PATH` directories on a separate line

```text
echo $PATH | tr ':' '\n'
```



