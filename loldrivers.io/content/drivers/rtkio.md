+++

description = ""
title = "rtkio.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# rtkio.sys ![:inline](/images/twitter_verified.png) 


### Description

rtkio.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

### Commands

```
sc.exe create rtkio.sys binPath=C:\windows\temp\rtkio.sys type=kernel
sc.exe start rtkio.sys
```

| Use Case | Privilages | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

### Resources
<br>
<li><a href=" https://github.com/elastic/protections-artifacts/search?q=VulnDriver"> https://github.com/elastic/protections-artifacts/search?q=VulnDriver</a></li>
<li><a href="https://github.com/elastic/protections-artifacts/search?q=VulnDriver">https://github.com/elastic/protections-artifacts/search?q=VulnDriver</a></li>
<br>

### Known Vulnerable Samples

| Filename | rtkio.sys |
|:---- | ---- | 
| MD5 | <a href="https://www.virustotal.com/gui/file/daf800da15b33bf1a84ee7afc59f0656">daf800da15b33bf1a84ee7afc59f0656</a> |
| SHA1 | <a href="https://www.virustotal.com/gui/file/166759fd511613414d3213942fe2575b926a6226">166759fd511613414d3213942fe2575b926a6226</a> |
| SHA256 | <a href="https://www.virustotal.com/gui/file/478917514be37b32d5ccf76e4009f6f952f39f5553953544f1b0688befd95e82">478917514be37b32d5ccf76e4009f6f952f39f5553953544f1b0688befd95e82</a> |
| Signature | Realtek Semiconductor Corp., DigiCert EV Code Signing CA, DigiCert   |


[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/rtkio.sys.yml)

*last_updated:* 2023-04-05








{{< /column >}}
{{< /block >}}
