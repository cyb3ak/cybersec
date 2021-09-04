# 4 - Common ports

`🏷️ Tags:` **\#ftp \#port20 \#port21 \#ssh \#sftp \#port22 \#telnet \#port23 \#smtp \#port25 \#dns \#port53 \#tftp \#port69 \#dhcp \#port67 \#port68**

**\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_**

### Port 20/21 `TCP` - FTP \(File Transfer Protocol\)

* Port 20 - Active mode data
* Port 21 - control mode
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

### Port 69 `UDP` - TFTP \(Trivial File Transfer System\)

* Very Simple FTP
* Read-write files
* No Auth
* Not useful in a production environment 

### Port 67/68 `UDP` - DHCP \(Dynamic Host Configuration Protocol\)



