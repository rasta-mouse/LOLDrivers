+++

description = ""
title = "BS_RCIO.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# BS_RCIO.sys 


{{< tip "warning" >}}
We were not able to verify the hash of this driver successfully, it has not been confirmed.
{{< /tip >}}


### Description

BS_RCIO.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

### Commands

```
sc.exe create BS_RCIO.sys binPath=C:\windows\temp\BS_RCIO.sys type=kernel
sc.exe start BS_RCIO.sys
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

| Filename | BS_RCIO.sys |
|:---- | ---- | 
| MD5 | <a href="https://www.virustotal.com/gui/file/ab53d07f18a9697139ddc825b466f696">ab53d07f18a9697139ddc825b466f696</a> |
| SHA1 | <a href="https://www.virustotal.com/gui/file/213ba055863d4226da26a759e8a254062ea77814">213ba055863d4226da26a759e8a254062ea77814</a> |
| SHA256 | <a href="https://www.virustotal.com/gui/file/362c4f3dadc9c393682664a139d65d80e32caa2a97b6e0361dfd713a73267ecc">362c4f3dadc9c393682664a139d65d80e32caa2a97b6e0361dfd713a73267ecc</a> |
| Signature | Biostar Microtech Int&#39;l Corp, DigiCert EV Code Signing CA, DigiCert   |


[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/bs_rcio.sys.yml)

*last_updated:* 2023-04-05








{{< /column >}}
{{< /block >}}
