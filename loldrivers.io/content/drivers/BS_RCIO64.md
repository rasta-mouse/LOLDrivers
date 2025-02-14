+++

description = ""
title = "BS_RCIO64.sys"
weight = 10

+++


{{< block "grid-1" >}}
{{< column "mt-2 pt-1">}}


# BS_RCIO64.sys ![:inline](/images/twitter_verified.png) 


### Description

BS_RCIO64.sys is a vulnerable driver and more information will be added as found.

- **Created**: 2023-01-09
- **Author**: Michael Haag
- **Acknowledgement**:  | [](https://twitter.com/)

### Commands

```
sc.exe create BS_RCIO64.sys binPath=C:\windows\temp\BS_RCIO64.sys type=kernel
sc.exe start BS_RCIO64.sys
```

| Use Case | Privilages | Operating System | 
|:---- | ---- | ---- |
| Elevate privileges | kernel | Windows 10 |

### Resources
<br>
<li><a href=" https://github.com/jbaines-r7/dellicious"> https://github.com/jbaines-r7/dellicious</a></li>
<li><a href=" https://www.rapid7.com/blog/post/2021/12/13/driver-based-attacks-past-and-present/"> https://www.rapid7.com/blog/post/2021/12/13/driver-based-attacks-past-and-present/</a></li>
<li><a href="https://github.com/elastic/protections-artifacts/blob/932baf346cc8a743f1963ad3d4565b42ed17bebe/yara/rules/Windows_VulnDriver_Biostar.yar#L54">https://github.com/elastic/protections-artifacts/blob/932baf346cc8a743f1963ad3d4565b42ed17bebe/yara/rules/Windows_VulnDriver_Biostar.yar#L54</a></li>
<li><a href="https://github.com/jbaines-r7/dellicious and https://www.rapid7.com/blog/post/2021/12/13/driver-based-attacks-past-and-present/">https://github.com/jbaines-r7/dellicious and https://www.rapid7.com/blog/post/2021/12/13/driver-based-attacks-past-and-present/</a></li>
<br>

### Known Vulnerable Samples

| Filename | BS_RCIO64.sys |
|:---- | ---- | 
| MD5 | <a href="https://www.virustotal.com/gui/file/b10b210c5944965d0dc85e70a0b19a42">b10b210c5944965d0dc85e70a0b19a42</a> |
| SHA1 | <a href="https://www.virustotal.com/gui/file/5db61d00a001fd493591dc919f69b14713889fc5">5db61d00a001fd493591dc919f69b14713889fc5</a> |
| SHA256 | <a href="https://www.virustotal.com/gui/file/d205286bffdf09bc033c09e95c519c1c267b40c2ee8bab703c6a2d86741ccd3e">d205286bffdf09bc033c09e95c519c1c267b40c2ee8bab703c6a2d86741ccd3e</a> |
| Signature | Microsoft Windows Hardware Compatibility Publisher, Microsoft Windows Third Party Component CA 2014, Microsoft Root Certificate Authority 2010   |


[*source*](https://github.com/magicsword-io/LOLDrivers/tree/main/yaml/bs_rcio64.sys.yml)

*last_updated:* 2023-04-05








{{< /column >}}
{{< /block >}}
