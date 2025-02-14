+++

description = ""
title = "rtkio64.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# rtkio64.sys ![:inline](/images/twitter_verified.png) 


### Description

rtkio64.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

### Commands

```
sc.exe create rtkio64.sys binPath=C:\windows\temp\rtkio64.sys type=kernel
sc.exe start rtkio64.sys
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

| Filename | rtkio64.sys |
|:---- | ---- | 
| MD5 | <a href="https://www.virustotal.com/gui/file/70dcd07d38017b43f710061f37cb4a91">70dcd07d38017b43f710061f37cb4a91</a> |
| SHA1 | <a href="https://www.virustotal.com/gui/file/99201c9555e5faf6e8d82da793b148311f8aa4b8">99201c9555e5faf6e8d82da793b148311f8aa4b8</a> |
| SHA256 | <a href="https://www.virustotal.com/gui/file/7133a461aeb03b4d69d43f3d26cd1a9e3ee01694e97a0645a3d8aa1a44c39129">7133a461aeb03b4d69d43f3d26cd1a9e3ee01694e97a0645a3d8aa1a44c39129</a> |
| Signature | Realtek Semiconductor Corp., DigiCert EV Code Signing CA, DigiCert   |


[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/rtkio64.sys.yml)

*last_updated:* 2023-04-05








{{< /column >}}
{{< /block >}}
