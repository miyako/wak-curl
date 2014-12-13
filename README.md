wak-curl
========

Wakanda module to use [cURL](http://curl.haxx.se).

About
-----
**Mac OS X**

* libcurl/7.39.0
* OpenSSL/1.0.1j 
* zlib/1.2.8 
* libidn/1.29 
* libssh2/1.4.3
 
**Windows**

* libcurl/7.39.0
* OpenSSL/1.0.1j
* zlib/1.2.8
* libidn/1.29
* libssh2/1.4.3

**Linux**

* libcurl/7.39.0
* OpenSSL/1.0.1j
* zlib/1.2.8
* libidn/1.29
* libssh2/1.4.3 

|Protocol|Mac OS X|Linux|Windows|
|:-------:|:-:|:---:|:-----:|
|dict|⭕️|⭕️|⭕️|
|file|⭕️|⭕️|⭕️|
|ftp|⭕️|⭕️|⭕️|
|ftps|⭕️|⭕️|⭕️|
|gopher|⭕️|⭕️|⭕️|
|http|⭕️|⭕️|⭕️|
|https|⭕️|⭕️|⭕️|
|imap|⭕️|⭕️|⭕️|
|imaps|⭕️|⭕️|⭕️|
|ldap|⭕️|⭕️|⭕️|
|ldaps|⭕️|⭕️|⭕️|
|pop3|⭕️|⭕️|⭕️|
|pop3s|⭕️|⭕️|⭕️|
|rtsp|⭕️|⭕️|⭕️|
|scp|⭕️|⭕️|⭕️|
|sftp|⭕️|⭕️|⭕️|
|smtp|⭕️|⭕️|⭕️|
|smtps|⭕️|⭕️|⭕️|
|telnet|⭕️|⭕️|⭕️|
|tftp|⭕️|⭕️|⭕️|

|Feature|Mac OS X|Linux|Windows|
|:-----:|:-:|:---:|:-----:|
|IDN|⭕️|⭕️|⭕️|
|IPv6|⭕️|⭕️||
|Largefile|⭕️|⭕️|⭕️|
|NTLM|⭕️|⭕️|⭕️|
|SSL|⭕️|⭕️|⭕️|
|libz|⭕️|⭕️|⭕️|

Example
-------
```js
var modulesFolder = FileSystemSync('Modules');
var curl = require(modulesFolder.path + 'curl');

curl.curl('-V').console.stdOut.toString();
```
