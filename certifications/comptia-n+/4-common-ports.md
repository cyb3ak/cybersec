# 4 - Common ports

`🏷️ Tags:` **\#telnet \#port23 \#ssh**

**\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_**

### Port 20/21 TCP - FTP \(File Transfer Protocol\)

* Port 20 - Active mode data
* Port 21 - control
* Non - encrypted
* Auth with user-pass
* Fully featured functionality \(list, add, delete\)

### Port 22 `TCP` - SSH \(Secure Shell\)

* same as telnet but with encryption

### Port 22 TCP - SFTP \(Secure FTP\)

* uses **`ssh`** file transfer protocol
* provides basic file system functionality
* encrypted communication - using ssh

### Port 23 `TCP` - Telnet \(Telecommunication Network\)

* Login devices remotely
* Clear-text communication protocol
* Not the best choice for production systems

### Port 25 `TCP` - SMTP \(Simple Mail Transfer Protocol\)

* server-to-server mail transfer
* device to the mail server

`Note: Other protocols are used for incoming mail -` **`IMAP, POP3`**

### Port 53 `UDP` - DNS \(Domain Name System\)

* Converts web address to IP address

