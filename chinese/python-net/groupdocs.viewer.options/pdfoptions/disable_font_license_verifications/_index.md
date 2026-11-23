---
title: "disable_font_license_verifications 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "此属性禁用当前 XPS/OXPS 文档中所有字体的任何许可证限制。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/
is_root: false
weight: 2030
---


## disable_font_license_verifications property

此属性禁用当前 XPS/OXPS 文档中所有字体的任何许可证限制。

如果字体的许可证禁止某些操作，则许多与字体相关的操作无法执行。例如，如果许可证规则禁止嵌入某些字体，则这些字体无法嵌入到 PDF 文档中。此选项允许您跳过对这些规则的验证。

使用此标志时请谨慎。设置后，意味着设置此标志的人要对可能的许可证或法律违规承担全部责任。强烈建议仅在您完全确信未侵犯版权法时才使用此标志。默认值为 `False`。

代码示例请参见文档：https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

### Definition:
```python
@property
def disable_font_license_verifications(self):
    ...
@disable_font_license_verifications.setter
def disable_font_license_verifications(self, value):
    ...
```

### 另见
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
