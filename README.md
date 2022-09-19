## UE4 Plugin: HotPatcher
Chinese Document：[README_Chinese.md](https://github.com/hxhb/HotPatcher/blob/master/README_Chinese.md).

[HotPatcher](https://github.com/hxhb/HotPatcher) is a tool for managing hot update versions and resource packaging. It is used to track changes in the original resources of the project version to create patches. Support resource version management, difference comparison and packaging between versions, support exporting basic package information for multiple platforms, easily cook and package multi-platform Patches, support iterative packaging, rich configuration options, full-featured commandlet support, can be combined with ci/cd platform is integrated.

>The currently supported engine version is UE4.21-UE5 (UE5.0.3 is supported). I created a group to discuss UE4 hot update and HotPatcher plug-in issues (QQ group 958363331).

Plug-in documentation: [UE4 resource hot update packaging tool HotPatcher](https://imzlp.com/posts/17590/)

Video tutorial: [UE4 hot update: HotPatcher plug-in tutorial](https://www.bilibili.com/video/BV1Tz4y197tR/)

My UOD Hot Update Keynote Speech: [Unreal Open Day2020 Unreal Engine 4 Full Platform Hot Update Solution | lipengzha](https://www.bilibili.com/video/BV1ir4y1c76g)

The series of UE4 hot update articles I wrote can be used as a reference for engineering practice:

- [UE4 Hot Update: Demand Analysis and Scheme Design](https://imzlp.com/posts/17371)
- [UE4 resource packaging tool HotPatcher](https://imzlp.com/posts/17590/)
- [UE4 Hot Update: Automated Process Based on HotPatcher](https://imzlp.com/posts/10938/)
- [2020 Unreal Open Day](https://imzlp.com/posts/11043/)
- [UE4 Hot Update: Split the basic package](https://imzlp.com/posts/13765/)
- [UE4 Hot Update: Asset Management and Audit Tool](https://imzlp.com/posts/3675)
- [UE4 Hot Update: Create Shader Patch](https://imzlp.com/posts/5867/)
- [UE4 Hot Update: Questions & Answers](https://imzlp.com/posts/16895/)
- [UE Hot Update: Binary Patch Solution for Resources](https://imzlp.com/posts/25136/)
- [UE Hot Update: Shader Update Strategy](https://imzlp.com/posts/15810/)
- [UE Hot Update: Reload and Reapply of Config](https://imzlp.com/posts/9028/)
- [Resource Inspection Automation Practice Based on ResScannerUE](https://imzlp.com/posts/20376/)
- [UE5: Game Feature Pre-Research](https://imzlp.com/posts/17658/)
- [UE Resource Management: Engine Packaging Resource Analysis](https://imzlp.com/posts/22570/)
- [Shader compression scheme based on ZSTD dictionary](https://imzlp.com/posts/24725/)
- [Runtime reorganization scheme for Pak in Unreal Engine](https://imzlp.com/posts/12188/)

**Resource management framework based on HotPatcher**

![](https://img.imzlp.com/imgs/zlp/picgo/2021/20220526194731.png)

**Application project**
|                              QQ                              |                     Apex Legends Mobile                      | MOSSAI|
| :----------------------------------------------------------: | :----------------------------------------------------------: | :-------------: |
| <img src="https://img.imzlp.com/imgs/zlp/picgo/2022/202207280953994.png" height="160" width="160" /> | <img src="https://img.imzlp.com/imgs/zlp/picgo/2022/202207280956642.webp" height="160" width="160" /> | <img src="https://img.imzlp.com/imgs/zlp/picgo/2021/20220607171033.png" height="160" width="160" /> |

HotPatcher is used in a large number of UE projects and is currently the most popular hot update tool in the UE community.