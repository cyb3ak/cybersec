# Character classes & Bracket ops

### **`‘[:alnum:]’`**

Alphanumeric characters: ‘\[:alpha:\]’ and ‘\[:digit:\]’; in the ‘C’ locale and ASCII character encoding, this is the same as ‘\[0-9A-Za-z\]’.

### **`‘[:alpha:]’`**

Alphabetic characters: ‘\[:lower:\]’ and ‘\[:upper:\]’; in the ‘C’ locale and ASCII character encoding, this is the same as ‘\[A-Za-z\]’.

### **`‘[:blank:]’`**

Blank characters: space and tab.‘\[:cntrl:\]’

Control characters. In ASCII, these characters have octal codes 000 through 037, and 177 \(DEL\). In other character sets, these are the equivalent characters, if any.

### **`‘[:digit:]’`**

Digits: `0 1 2 3 4 5 6 7 8 9`.

### **`‘[:graph:]’`**

Graphical characters: ‘\[:alnum:\]’ and ‘\[:punct:\]’.

### **`‘[:lower:]’`**

Lower-case letters; in the ‘C’ locale and ASCII character encoding, this is `a b c d e f g h i j k l m n o p q r s t u v w x y z`.

### **`‘[:print:]’`**

Printable characters: ‘\[:alnum:\]’, ‘\[:punct:\]’, and space.

### **`‘[:punct:]’`**

Punctuation characters; in the ‘C’ locale and ASCII character encoding, this is ``! " # $ % & ' ( ) * + , - . / : ; < = > ? @ [ \ ] ^ _ ` { | } ~``.

### **`‘[:space:]’`**

Space characters: in the ‘C’ locale, this is tab, newline, vertical tab, form feed, carriage return, and space.‘\[:upper:\]’

Upper-case letters: in the ‘C’ locale and ASCII character encoding, this is `A B C D E F G H I J K L M N O P Q R S T U V W X Y Z`.

### **`‘[:xdigit:]’`**

Hexadecimal digits: `0 1 2 3 4 5 6 7 8 9 A B C D E F a b c d e f`.

Note that the brackets in these class names are part of the symbolic names, and must be included in addition to the brackets delimiting the bracket expression.

### 

### Useful links

* [https://www.gnu.org/software/sed/manual/html\_node/Character-Classes-and-Bracket-Expressions.html](https://www.gnu.org/software/sed/manual/html_node/Character-Classes-and-Bracket-Expressions.html)

