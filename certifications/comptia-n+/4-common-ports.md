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

* Automated configures IP Address, subnet mask, etc
* Requires a DHCP server:  - Server, Appliances, integrated into a SOHO router
*  Dynamic/Pooled 1. IP Addresses are assigned in real-time from the pool  2. Each device is given a lease & must renew after a certain time
* DHCP reservation - Addresses are assigned on the basis of MAC addresses - Quickly manage addresses from one location

### Port 80 `TCP` - HTTP \(HyperText Transfer Protocol\)

* for web communication

### Port 110 TCP - POP3 \(Post Office Protocol V3\)

* receives emails from an Email server
* Basic mail transfer functionality

### Port 143 TCP - IMAP4 \(Internet Message Access\)

* receives emails from an Email server
* we use this - includes mailbox management, we see the same functionality in mobile as in web

### Port 123 ~~`UDP`~~ - NTP \(Network Time Protocol\)

* Switches, Routers, Firewall, Servers, Workstation, etc all have their own **clock**
* Synchronises the clock
* Automatic updates
* Flexible - you control how often clocks are updated
* Very accurate ~ 1ms on a local network

### Port 161 `UDP` - SNMP \(Simple Network Management Protocol\)

* Gather **Statistics** from Network devices \(Routers, switches, etc\)
* **SNMP V1** - Structured Tables - request & response in clear-text
* **SNMP V2** - Data type enhancement - Bulk transfer - uses clear-text
* **SNMP V3** - a secure Standard - provides Message Integrity, Authentication, Encryption

### Port 389 `TCP` -  LDAP \(Lightweight Directory Access Protocol\)

* Store & Retrieve information in a network directory

### Port 443 `TCP` - HTTPS \(HTTP Secure\)

* for web communication with security

### Port 445 `TCP` - SMB \(Server Message Block\) \| NetBIOS - less

* Used by Windows for file/printer sharing on a network
* Also called CIFS \(Common Internet File System\)
* SMB communication over TCP without using NetBIOS transport

### Port 636`TCP` -  LDAPs \(LDAP Secure\)

* LDAP over SSL

### Port 1720 `TCP` - H.323

* ITU Telecommunication H.23x series
* Setup & manages VOIP sessions - call, ring, hang
* earliest VOIP protocol - still used

### Port 3389 `TCP` - RDP \(Remote Desktop protocol\)

* Share desktop from a remote location
* can connect to an entire desktop or just an application

### Port 5060/5061 `TCP` - SIP \(Session Initiation Protocol\)

* Voice over IP \(**VOIP**\) signaling



