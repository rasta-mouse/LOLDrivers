+++

description = ""
title = "PanMonFlt.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# PanMonFlt.sys 


{{< tip "warning" >}}
We were not able to verify the hash of this driver successfully, it has not been confirmed.
{{< /tip >}}


### Description

PanMonFlt.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

### Commands

```
sc.exe create PanMonFlt.sys binPath=C:\windows\temp\PanMonFlt.sys type=kernel
sc.exe start PanMonFlt.sys
```

| Use Case | Privilages | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

### Resources
<br>
<li><a href=" https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-defender-application-control/microsoft-recommended-driver-block-rules"> https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-defender-application-control/microsoft-recommended-driver-block-rules</a></li>
<li><a href="https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-defender-application-control/microsoft-recommended-driver-block-rules">https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-defender-application-control/microsoft-recommended-driver-block-rules</a></li>
<br>

### Known Vulnerable Samples

| Filename | PanMonFlt.sys |
|:---- | ---- | 
| MD5 | <a href="https://www.virustotal.com/gui/file/2850608430dd089f24386f3336c84729">2850608430dd089f24386f3336c84729</a> |
| SHA1 | <a href="https://www.virustotal.com/gui/file/a6816949cd469b6e5c35858d19273936fab1bef6">a6816949cd469b6e5c35858d19273936fab1bef6</a> |
| SHA256 | <a href="https://www.virustotal.com/gui/file/7e0124fcc7c95fdc34408cf154cb41e654dade8b898c71ad587b2090b1da30d7">7e0124fcc7c95fdc34408cf154cb41e654dade8b898c71ad587b2090b1da30d7</a> |
| Signature | PAN YAZILIM BILISIM TEKNOLOJILERI TICARET LTD. STI., GlobalSign CodeSigning CA - G2, GlobalSign   |


[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/panmonflt.sys.yml)

*last_updated:* 2023-04-05








{{< /column >}}
{{< /block >}}
