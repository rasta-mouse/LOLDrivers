+++

description = ""
title = "segwindrvx64.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# segwindrvx64.sys ![:inline](/images/twitter_verified.png) 


### Description

segwindrvx64.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

### Commands

```
sc.exe create segwindrvx64.sys binPath=C:\windows\temp\segwindrvx64.sys type=kernel
sc.exe start segwindrvx64.sys
```

| Use Case | Privilages | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

### Resources
<br>
<li><a href=" https://github.com/eclypsium/Screwed-Drivers/blob/master/DRIVERS.md"> https://github.com/eclypsium/Screwed-Drivers/blob/master/DRIVERS.md</a></li>
<li><a href="https://github.com/eclypsium/Screwed-Drivers/blob/master/DRIVERS.md">https://github.com/eclypsium/Screwed-Drivers/blob/master/DRIVERS.md</a></li>
<br>

### Known Vulnerable Samples

| Filename | segwindrvx64.sys |
|:---- | ---- | 
| MD5 | <a href="https://www.virustotal.com/gui/file/4ae55080ec8aed49343e40d08370195c">4ae55080ec8aed49343e40d08370195c</a> |
| SHA1 | <a href="https://www.virustotal.com/gui/file/d702d88b12233be9413446c445f22fda4a92a1d9">d702d88b12233be9413446c445f22fda4a92a1d9</a> |
| SHA256 | <a href="https://www.virustotal.com/gui/file/65329dad28e92f4bcc64de15c552b6ef424494028b18875b7dba840053bc0cdd">65329dad28e92f4bcc64de15c552b6ef424494028b18875b7dba840053bc0cdd</a> |
| Signature | Insyde Software Corp., VeriSign Class 3 Code Signing 2010 CA, VeriSign   |


[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/segwindrvx64.sys.yml)

*last_updated:* 2023-04-05








{{< /column >}}
{{< /block >}}
