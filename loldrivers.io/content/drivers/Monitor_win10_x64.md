+++

description = ""
title = "Monitor_win10_x64.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# Monitor_win10_x64.sys ![:inline](/images/twitter_verified.png) 


### Description

CVE-2018-16712

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

### Commands

```
sc.exe create Monitor_win10_x64.sys binPath=C:\windows\temp\Monitor_win10_x64.sys type=kernel
sc.exe start Monitor_win10_x64.sys
```

| Use Case | Privilages | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

### Resources
<br>
<li><a href="https://www.unknowncheats.me/forum/anti-cheat-bypass/334557-vulnerable-driver-megathread.html">https://www.unknowncheats.me/forum/anti-cheat-bypass/334557-vulnerable-driver-megathread.html</a></li>
<li><a href="https://www.unknowncheats.me/forum/anti-cheat-bypass/244386-mta-fairplaykd-driver-reversed-exploited-rpm.html">https://www.unknowncheats.me/forum/anti-cheat-bypass/244386-mta-fairplaykd-driver-reversed-exploited-rpm.html</a></li>
<li><a href="https://github.com/elastic/protections-artifacts/search?q=VulnDriver">https://github.com/elastic/protections-artifacts/search?q=VulnDriver</a></li>
<br>

### Known Vulnerable Samples

| Filename | Monitor_win10_x64.sys |
|:---- | ---- | 
| MD5 | <a href="https://www.virustotal.com/gui/file/988dabdcf990b134b0ac1e00512c30c4">988dabdcf990b134b0ac1e00512c30c4</a> |
| SHA1 | <a href="https://www.virustotal.com/gui/file/ef80da613442047697bec35ea228cde477c09a3d">ef80da613442047697bec35ea228cde477c09a3d</a> |
| SHA256 | <a href="https://www.virustotal.com/gui/file/e4a7da2cf59a4a21fc42b611df1d59cae75051925a7ddf42bf216cc1a026eadb">e4a7da2cf59a4a21fc42b611df1d59cae75051925a7ddf42bf216cc1a026eadb</a> |
| Signature | IObit Information Technology, Symantec Class 3 SHA256 Code Signing CA, VeriSign   |


[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/monitor_win10_x64.sys.yml)

*last_updated:* 2023-04-05








{{< /column >}}
{{< /block >}}
