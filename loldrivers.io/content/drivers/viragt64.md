+++

description = ""
title = "viragt64.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# viragt64.sys ![:inline](/images/twitter_verified.png) 


### Description

viragt64.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

### Commands

```
sc.exe create viragt64.sys binPath=C:\windows\temp\viragt64.sys type=kernel
sc.exe start viragt64.sys
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

| Filename | viragt64.sys |
|:---- | ---- | 
| MD5 | <a href="https://www.virustotal.com/gui/file/43830326cd5fae66f5508e27cbec39a0">43830326cd5fae66f5508e27cbec39a0</a> |
| SHA1 | <a href="https://www.virustotal.com/gui/file/05c0c49e8bcf11b883d41441ce87a2ee7a3aba1d">05c0c49e8bcf11b883d41441ce87a2ee7a3aba1d</a> |
| SHA256 | <a href="https://www.virustotal.com/gui/file/58a74dceb2022cd8a358b92acd1b48a5e01c524c3b0195d7033e4bd55eff4495">58a74dceb2022cd8a358b92acd1b48a5e01c524c3b0195d7033e4bd55eff4495</a> |
| Signature | TG Soft S.a.s. Di Tonello Gianfranco e C., VeriSign Class 3 Code Signing 2010 CA, VeriSign   |


[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/viragt64.sys.yml)

*last_updated:* 2023-04-05








{{< /column >}}
{{< /block >}}
