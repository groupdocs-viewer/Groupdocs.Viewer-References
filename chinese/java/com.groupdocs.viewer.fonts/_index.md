---
title: "com.groupdocs.viewer.fonts"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "该包提供用于管理渲染过程中使用的字体的类和枚举。"
type: docs
weight: 16
url: /zh/java/com.groupdocs.viewer.fonts/
---

该包提供用于管理渲染过程中使用的字体的类和枚举。

此包中的主要类和接口有：

* [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) - Represents a folder that contains TrueType fonts.
* [FontSettings](../../com.groupdocs.viewer.fonts/fontsettings) - Provides methods for working with sources to look for TrueType fonts.
* [FontSource](../../com.groupdocs.viewer.fonts/fontsource) - Marker interface for the font sources.


有关在 GroupDocs.Viewer 中使用字体的更多详细信息，请参阅
[GroupDocs.Viewer Documentation](../https://docs.groupdocs.com/viewer/java/).



## 类

| 类 | 描述 |
| --- | --- |
| [FolderFontSource](../com.groupdocs.viewer.fonts/folderfontsource) | 表示包含 TrueType 字体的文件夹。 |
| [FontFormat](../com.groupdocs.viewer.fonts/fontformat) | 表示所有可能出现在 UsedFontInfo 类中的字体格式。 |
| [FontSettings](../com.groupdocs.viewer.fonts/fontsettings) | 提供用于查找 TrueType 字体来源的方法。 |
| [FontStyles](../com.groupdocs.viewer.fonts/fontstyles) | 表示文档中使用的四种可能的字体样式：常规、粗体、斜体或粗斜体。 |
| [PdfFontInfo](../com.groupdocs.viewer.fonts/pdffontinfo) | 封装来自 PDF 文档的单个字体的元信息和二进制数据，已加载到 Viewer 实例中。 |
| [PresentationFontInfo](../com.groupdocs.viewer.fonts/presentationfontinfo) | 封装在演示文稿文档中使用的字体的元数据和二进制数据，已加载到 Viewer 实例中。 |
| [SpreadsheetFontInfo](../com.groupdocs.viewer.fonts/spreadsheetfontinfo) | 封装来自电子表格文档的单个字体的元信息和二进制数据，已加载到 Viewer 实例中。 |
| [WordProcessingFontInfo](../com.groupdocs.viewer.fonts/wordprocessingfontinfo) | 封装来自文字处理文档的单个字体的元信息和二进制数据，已加载到 Viewer 实例中。 |
| [WordProcessingSubstitutedFontInfo](../com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo) | 封装通过 GroupDocs.Viewer 在文字处理文档中使用的一个替代字体的元数据和二进制数据。 |

## 接口

| 接口 | 描述 |
| --- | --- |
| [FontSource](../com.groupdocs.viewer.fonts/fontsource) | 用于字体来源的标记接口。 |
| [IFontInfo](../com.groupdocs.viewer.fonts/ifontinfo) | 可从文档格式（PDF、WordProcessing、Spreadsheet 和 Presentation）中提取的所有字体的通用接口。 |

## 枚举

| 枚举类型 | 描述 |
| --- | --- |
| [SearchOption](../com.groupdocs.viewer.fonts/searchoption) | 指定是仅搜索当前文件夹，还是搜索当前文件夹及所有子文件夹。 |
