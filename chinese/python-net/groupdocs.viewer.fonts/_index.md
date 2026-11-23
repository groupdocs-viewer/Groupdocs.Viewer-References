---
title: "groupdocs.viewer.fonts"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "字体加载和替换配置。"
type: docs
url: /zh/python-net/groupdocs.viewer.fonts/
is_root: false
weight: 40
---


字体加载和替换配置。

### 类
| 类 | 描述 |
| :- | :- |
| [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) | 表示包含 TrueType 字体的文件夹。 |
| [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/) | 提供用于查找 TrueType 字体来源的方法。 |
| [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) | 表示文档中使用的字体的四种可能样式：Regular、Bold、Italic 或 Bold Italic。 |
| [`IFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/) | 表示所有可从所有受支持的文档格式系列（PDF、WordProcessing、Spreadsheet 和 Presentation）中提取的字体的通用接口。 |
| [`PdfFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/) | 封装加载到 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 实例中的 PDF 字体的元数据和二进制数据，该字体可能嵌入在文档中或安装在运行 GroupDocs.Viewer 的操作系统上。 |
| [`PresentationFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/) | 表示从 Presentation 文档加载到 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 实例中的字体的元信息和二进制数据。该字体用于文档内容，可能嵌入在文档中或安装在运行查看器的操作系统上。 |
| [`SpreadsheetFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/) | 封装从电子表格文档加载到 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 实例中的字体的元信息和二进制数据。电子表格文档无法嵌入字体，因此由 [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) 返回的字体会安装在运行查看器的操作系统上。 |
| [`WordProcessingFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/) | 封装从 WordProcessing 文档加载到 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 实例中的字体的元信息和二进制数据。 |
| [`WordProcessingSubstitutedFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/) | 封装从 WordProcessing 文档中获取的单个字体的元信息和二进制数据，该字体最初未在已加载的 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 实例文档中使用，但作为目标机器上未找到的字体的替代字体。替代字体仅存在于 WordProcessing 格式系列中。 |

### 枚举
| 枚举 | 描述 |
| :- | :- |
| [`FontFormat`](/viewer/python-net/groupdocs.viewer.fonts/fontformat/) |  |
| [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) | 表示用于字体来源的标记接口。 |
| [`SearchOption`](/viewer/python-net/groupdocs.viewer.fonts/searchoption/) |  |
