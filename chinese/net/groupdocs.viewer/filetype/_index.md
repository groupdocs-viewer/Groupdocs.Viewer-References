---
title: "FileType"
second_title: "GroupDocs.Viewer for .NET API 参考"
description: "表示文件类型。提供获取 GroupDocs.Viewer 支持的所有文件类型列表的方法。"
type: docs
weight: 10
url: /zh/net/groupdocs.viewer/filetype/
---

## FileType class

表示文件类型。提供获取 **GroupDocs.Viewer** 支持的所有文件类型列表的方法。

```csharp
public sealed class FileType : IEquatable<FileType>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [FileType](filetype#constructor)() | 初始化 [`FileType`](../filetype) 类的新实例。 |
| [FileType](filetype#constructor_1)(string, string) | 初始化 [`FileType`](../filetype) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Extension](../../groupdocs.viewer/filetype/extension) { get; set; } | 文件名后缀（包括句点 "."），例如 ".doc"。 |
| [FileFormat](../../groupdocs.viewer/filetype/fileformat) { get; set; } | 文件类型名称，例如 "Microsoft Word Document"。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromExtension](../../groupdocs.viewer/filetype/fromextension)(string) | 将文件扩展名映射到文件类型。 |
| static [FromFilePath](../../groupdocs.viewer/filetype/fromfilepath)(string) | 提取文件扩展名并将其映射到文件类型。 |
| static [FromMediaType](../../groupdocs.viewer/filetype/frommediatype)(string) | 将文件媒体类型映射到文件类型，例如 'application/pdf' 将映射为 [`PDF`](./pdf)。 |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream)(Stream) | 通过读取文件签名来检测文件类型。 |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_1)(Stream, ILogger) | 通过读取文件签名来检测文件类型。 |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_2)(Stream, string) | 通过读取文件签名来检测文件类型。 |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_3)(Stream, string, ILogger) | 通过读取文件签名来检测文件类型。 |
| [Equals](../../groupdocs.viewer/filetype/equals#equals)(FileType) | 确定当前 [`FileType`](../filetype) 是否与指定的 [`FileType`](../filetype) 对象相同。 |
| override [Equals](../../groupdocs.viewer/filetype/equals#equals_1)(object) | 确定当前 [`FileType`](../filetype) 是否与指定的对象相同。 |
| override [GetHashCode](../../groupdocs.viewer/filetype/gethashcode)() | 返回当前 [`FileType`](../filetype) 对象的哈希码。 |
| override [ToString](../../groupdocs.viewer/filetype/tostring)() | 返回表示当前对象的字符串。 |
| static [DetectEncoding](../../groupdocs.viewer/filetype/detectencoding#detectencoding)(Stream) | 尝试通过流检测文本 [`TXT`](./txt)、[`TSV`](./tsv) 和 [`CSV`](./csv) 文件的编码。 |
| static [DetectEncoding](../../groupdocs.viewer/filetype/detectencoding#detectencoding_1)(string) | 尝试通过路径检测文本 [`TXT`](./txt)、[`TSV`](./tsv) 和 [`CSV`](./csv) 文件的编码。 |
| static [GetSupportedFileTypes](../../groupdocs.viewer/filetype/getsupportedfiletypes)() | 检索受支持的文件类型 |
| [operator ==](../../groupdocs.viewer/filetype/op_equality) | 确定两个 [`FileType`](../filetype) 对象是否相同。 |
| [operator !=](../../groupdocs.viewer/filetype/op_inequality) | 确定两个 [`FileType`](../filetype) 对象是否不相同。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| static readonly [APNG](../../groupdocs.viewer/filetype/apng) | Animated Portable Network Graphic（.apng）是支持动画的 PNG 格式的扩展。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/apng)。 |
| static readonly [AS](../../groupdocs.viewer/filetype/as) | ActionScript 文件（.as） |
| static readonly [AS3](../../groupdocs.viewer/filetype/as3) | ActionScript 文件（.as） |
| static readonly [ASM](../../groupdocs.viewer/filetype/asm) | 汇编语言源代码文件（.asm） |
| static readonly [AZW3](../../groupdocs.viewer/filetype/azw3) | Amazon Kindle Format 8 (KF8) 电子书是为 Amazon Kindle 设备开发的数字文件格式。该格式是对旧的 AZW 文件的改进，仅在 Kindle Fire 设备上使用，同时向后兼容其前身文件格式，即 MOBI 和 AZW。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/ebook/azw3)。 |
| static readonly [BAT](../../groupdocs.viewer/filetype/bat) | DOS 批处理文件（.bat） |
| static readonly [BMP](../../groupdocs.viewer/filetype/bmp) | Bitmap 图像文件（.bmp）用于存储位图数字图像。这些图像独立于图形适配器，也称为设备无关位图（DIB）文件格式。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/bmp)。 |
| static readonly [BZ2](../../groupdocs.viewer/filetype/bz2) | Bzip2 压缩文件（.bz2）是使用 BZIP2 开源压缩方法生成的压缩文件，主要在 UNIX 或 Linux 系统上使用。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/compression/bz2)。 |
| static readonly [C](../../groupdocs.viewer/filetype/c) | C/C++ 源代码文件（.c） |
| static readonly [Cab](../../groupdocs.viewer/filetype/cab) | Cabinet（或 CAB）是 Microsoft Windows 的一种归档文件格式。了解更多关于此文件格式的信息，请点击[此处](https://en.wikipedia.org/wiki/Cabinet_(file_format)). |
| static readonly [CC](../../groupdocs.viewer/filetype/cc) | C++ 源代码文件（.cc） |
| static readonly [CDR](../../groupdocs.viewer/filetype/cdr) | CorelDraw 矢量图形绘图文件（.cdr）是一种由 CorelDRAW 原生创建的用于存储已编码和压缩的数字图像的矢量绘图文件。此类绘图文件包含文本、线条、形状、图像、颜色和效果，用于对图像内容进行矢量表示。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/cdr)。 |
| static readonly [CF2](../../groupdocs.viewer/filetype/cf2) | Common File Format 文件 了解更多关于此文件格式的信息，请点击[此处](https://fileinfo.com/extension/cf2)。 |
| static readonly [CGM](../../groupdocs.viewer/filetype/cgm) | Computer Graphics Metafile（.cgm）是一种免费、平台无关的国际标准元文件格式，用于存储和交换矢量图形（2D）、光栅图形和文本。CGM 使用面向对象的方法和许多功能来支持图像生成。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/page-description-language/cgm)。 |
| static readonly [CHM](../../groupdocs.viewer/filetype/chm) | Microsoft 编译的 HTML 帮助文件（.chm）是一种广为人知的 HELP（某些应用程序的文档）文档格式。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/web/chm/)。 |
| static readonly [CMAKE](../../groupdocs.viewer/filetype/cmake) | CMake 文件 (.cmake) |
| static readonly [CMX](../../groupdocs.viewer/filetype/cmx) | Corel Exchange (.cmx) 是一种绘图图像文件，可能包含矢量图形以及位图图形。了解更多关于此文件格式的信息，请访问[这里](https://wiki.fileformat.com/image/cmx)。 |
| static readonly [CPIO](../../groupdocs.viewer/filetype/cpio) | Cpio 是一种通用文件归档工具及其关联的文件格式。它主要安装在类 Unix 计算机操作系统上。了解更多关于此文件格式的信息，请访问[这里](https://wiki.fileformat.com/compression/cpio)。 |
| static readonly [CPP](../../groupdocs.viewer/filetype/cpp) | C++ 源代码文件 (.cpp) |
| static readonly [CS](../../groupdocs.viewer/filetype/cs) | C# 源代码文件 (.cs) 是用于 C# 编程语言的源代码文件。由 Microsoft 引入，用于 .NET 框架。了解更多关于此文件格式的信息，请访问[这里](https://wiki.fileformat.com/programming/cs)。 |
| static readonly [CSS](../../groupdocs.viewer/filetype/css) | 层叠样式表 (.css) |
| static readonly [CSV](../../groupdocs.viewer/filetype/csv) | Comma Separated Values 文件 (.csv) 表示包含逗号分隔值记录的纯文本文件。了解更多关于此文件格式的信息，请访问[这里](https://wiki.fileformat.com/spreadsheet/csv)。 |
| static readonly [CXX](../../groupdocs.viewer/filetype/cxx) | C++ 源代码文件 (.cxx) |
| static readonly [DCM](../../groupdocs.viewer/filetype/dcm) | DICOM 图像 (.dcm) 表示存储患者医学信息（如 MRI、CT 扫描和超声图像）的数字图像。了解更多关于此文件格式的信息，请访问[这里](https://wiki.fileformat.com/image/dcm)。 |
| static readonly [DGN](../../groupdocs.viewer/filetype/dgn) | MicroStation 设计文件 (.dgn) 是由 MicroStation 和 Intergraph Interactive Graphics Design System 等 CAD 应用程序创建并支持的图纸。了解更多关于此文件格式的信息，请访问[这里](https://wiki.fileformat.com/cad/dgn)。 |
| static readonly [DIB](../../groupdocs.viewer/filetype/dib) | 设备无关位图文件 (.dib) |
| static readonly [DIFF](../../groupdocs.viewer/filetype/diff) | 补丁文件 (.diff) |
| static readonly [DJVU](../../groupdocs.viewer/filetype/djvu) | DjVu 图像 (.djvu) 是一种针对扫描文档和书籍（尤其是包含文本、图纸、图像和照片组合）的图形文件格式。了解更多关于此文件格式的信息，请访问[这里](https://wiki.fileformat.com/image/djvu)。 |
| static readonly [DNG](../../groupdocs.viewer/filetype/dng) | Digital Negative 规范 (.dng) 是用于存储原始文件的数码相机图像格式。该格式由 Adobe 于 2004 年 9 月开发，主要用于数码摄影。了解更多关于此文件格式的信息，请访问[这里](https://wiki.fileformat.com/image/dng)。 |
| static readonly [DOC](../../groupdocs.viewer/filetype/doc) | Microsoft Word 文档 (.doc) 表示由 Microsoft Word 或其他文字处理软件生成的二进制文件格式文档。了解更多关于此文件格式的信息，请访问[这里](https://wiki.fileformat.com/word-processing/doc)。 |
| static readonly [DOCM](../../groupdocs.viewer/filetype/docm) | Word Open XML 启用宏的文档 (.docm) 是由 Microsoft Word 2007 或更高版本生成的、具备运行宏功能的文档。了解更多关于此文件格式的信息，请访问[这里](https://wiki.fileformat.com/word-processing/docm)。 |
| static readonly [DOCX](../../groupdocs.viewer/filetype/docx) | Microsoft Word Open XML 文档 (.docx) 是一种广为人知的 Microsoft Word 文档格式。自 2007 年 Microsoft Office 2007 发布起，该文档格式的结构从纯二进制更改为 XML 与二进制文件的组合。了解更多关于此文件格式的信息，请访问[这里](https://wiki.fileformat.com/word-processing/docx)。 |
| static readonly [DOT](../../groupdocs.viewer/filetype/dot) | Word 文档模板 (.dot) 是由 Microsoft Word 创建的模板文件，具有预设格式设置，用于生成后续的 DOC 或 DOCX 文件。了解更多关于此文件格式的信息，请访问[这里](https://wiki.fileformat.com/word-processing/dot)。 |
| static readonly [DOTM](../../groupdocs.viewer/filetype/dotm) | Word Open XML 启用宏的文档模板 (.dotm) 表示由 Microsoft Word 2007 或更高版本创建的模板文件。了解更多关于此文件格式的信息，请访问[这里](https://wiki.fileformat.com/word-processing/dotm)。 |
| static readonly [DOTX](../../groupdocs.viewer/filetype/dotx) | Word Open XML 文档模板 (.dotx) 是由 Microsoft Word 创建的模板文件，具有预设格式设置，用于生成后续的 DOCX 文件。了解更多关于此文件格式的信息，请访问[这里](https://wiki.fileformat.com/word-processing/dotx)。 |
| static readonly [DWF](../../groupdocs.viewer/filetype/dwf) | Design Web Format 文件 (.dwf) 以压缩格式表示用于查看、审阅或打印的 2D/3D 图纸。它包含作为设计数据一部分的图形和文本，并因压缩格式而减小文件大小。了解更多关于此文件格式的信息，请访问[这里](https://wiki.fileformat.com/cad/dwf)。 |
| static readonly [DWFX](../../groupdocs.viewer/filetype/dwfx) | Design Web Format 文件 XPS (.dwfx) 以压缩的 XPS 文档形式表示用于查看、审阅或打印的 2D/3D 图纸。它包含作为设计数据一部分的图形和文本，并因压缩格式而减小文件大小。了解更多关于此文件格式的信息，请访问[这里](https://wiki.fileformat.com/cad/dwfx)。 |
| static readonly [DWG](../../groupdocs.viewer/filetype/dwg) | AutoCAD 绘图数据库文件 (.dwg) 表示用于存储 2D 和 3D 设计数据的专有二进制文件。与 ASCII 文件的 DXF 类似，DWG 代表 CAD（计算机辅助设计）图纸的二进制文件格式。了解更多关于此文件格式的信息，请访问[这里](https://wiki.fileformat.com/cad/dwg)。 |
| static readonly [DWT](../../groupdocs.viewer/filetype/dwt) | AutoCAD 绘图模板 (.dwt) 是一种 AutoCAD 绘图模板文件，用作创建可保存为 DWG 文件的图纸的起始模板。了解更多关于此文件格式的信息，请访问[这里](https://wiki.fileformat.com/cad/dwt)。 |
| static readonly [DXF](../../groupdocs.viewer/filetype/dxf) | Drawing Exchange Format 文件 (.dxf) 是 AutoCAD 绘图文件的标记数据表示。了解更多关于此文件格式的信息，请访问[这里](https://wiki.fileformat.com/cad/dxf)。 |
| static readonly [EMF](../../groupdocs.viewer/filetype/emf) | 增强型 Windows 元文件 (.emf) 以设备无关的方式表示图形图像。EMF 元文件由按时间顺序排列的可变长度记录组成，能够在任何输出设备上解析后渲染存储的图像。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/emf)。 |
| static readonly [EML](../../groupdocs.viewer/filetype/eml) | 电子邮件消息 (.eml) 表示使用 Outlook 等相关应用程序保存的电子邮件。几乎所有邮件客户端都支持此文件格式，因为它符合 RFC-822 互联网消息格式标准。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/email/eml)。 |
| static readonly [EMLX](../../groupdocs.viewer/filetype/emlx) | Apple Mail 消息 (.emlx) 由 Apple 实现和开发。Apple Mail 应用程序使用 EMLX 文件格式导出电子邮件。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/email/emlx)。 |
| static readonly [EMZ](../../groupdocs.viewer/filetype/emz) | 压缩的增强型 Windows 元文件 (.emz) 以设备无关的方式表示经 GZIP 压缩的图形图像。EMF 元文件由按时间顺序排列的可变长度记录组成，能够在任何输出设备上解析后渲染存储的图像。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/emz)。 |
| static readonly [EPS](../../groupdocs.viewer/filetype/eps) | 封装的 PostScript 文件 (.eps) 描述一个封装的 PostScript 语言程序，用于描述单页的外观。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/page-description-language/eps)。 |
| static readonly [EPUB](../../groupdocs.viewer/filetype/epub) | Open eBook 文件 (.epub) 是一种电子书文件格式，为出版商和用户提供标准的数字出版格式。该格式现已非常普及，受到众多电子阅读器和软件应用的支持。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/ebook/epub)。 |
| static readonly [ERB](../../groupdocs.viewer/filetype/erb) | Ruby ERB 脚本 (.erb) |
| static readonly [Excel2003XML](../../groupdocs.viewer/filetype/excel2003xml) | Excel 2003 XML (SpreadsheetML) 表示 Excel 二进制文件格式。这类文件可以由 Microsoft Excel 以及其他类似的电子表格程序（如 OpenOffice Calc 或 Apple Numbers）创建。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/spreadsheet/xls)。 |
| static readonly [FBX](../../groupdocs.viewer/filetype/fbx) | Autodesk FBX 交换文件 (FilmBoX) (.fbx) 表示 3D 模型格式。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/cad/fbx)。 |
| static readonly [FODG](../../groupdocs.viewer/filetype/fodg) | Flat XML ODF 模板 (.fodg) 被 Apache OpenOffice 的 Draw 应用程序用于将绘图元素存储为矢量图像。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/fodg)。 |
| static readonly [FODP](../../groupdocs.viewer/filetype/fodp) | OpenDocument 演示文稿 (.fodp) 表示 OpenDocument 平面 XML 演示文稿。了解更多关于此文件格式的信息，请点击[here](https://fileinfo.com/extension/fodp)。 |
| static readonly [FODS](../../groupdocs.viewer/filetype/fods) | OpenDocument 平面 XML 电子表格 (.fods) |
| static readonly [GIF](../../groupdocs.viewer/filetype/gif) | 图形交换格式文件 (.gif) 是一种高度压缩的图像。对于每张 GIF 图像，通常允许每像素最多 8 位，并且整个图像最多支持 256 种颜色。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/gif)。 |
| static readonly [GROOVY](../../groupdocs.viewer/filetype/groovy) | Groovy 源代码文件 (.groovy) |
| static readonly [GZ](../../groupdocs.viewer/filetype/gz) | Gnu 压缩文件 (.gz) 是使用 gzip 压缩程序创建的压缩文件。它可以包含多个压缩文件，且常用于 UNIX 和 Linux 系统。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/compression/gz)。 |
| static readonly [GZIP](../../groupdocs.viewer/filetype/gzip) | Gnu 压缩文件 (.gzip) 作为一种免费工具推出，用于取代 Unix 系统中使用的 Compress 程序。这类文件可以使用多种应用程序打开和解压，例如在 Windows 和 macOS 上均可使用的 WinZip。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/compression/gz)。 |
| static readonly [H](../../groupdocs.viewer/filetype/h) | C/C++/Objective-C 头文件 (.h) |
| static readonly [HAML](../../groupdocs.viewer/filetype/haml) | Haml 源代码文件 (.haml) |
| static readonly [HH](../../groupdocs.viewer/filetype/hh) | C++ 头文件 (.hh) |
| static readonly [HPG](../../groupdocs.viewer/filetype/hpg) | PLT (HPGL) (.hpg) |
| static readonly [HTM](../../groupdocs.viewer/filetype/htm) | 超文本标记语言文件 (.htm) 是用于在浏览器中显示的网页的扩展名。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/web/html)。 |
| static readonly [HTML](../../groupdocs.viewer/filetype/html) | 超文本标记语言文件 (.html) 是用于在浏览器中显示的网页的扩展名。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/web/html)。 |
| static readonly [ICO](../../groupdocs.viewer/filetype/ico) | 图标文件 (.ico) 是用于在 Microsoft Windows 上表示应用程序图标的图像文件类型。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/image/ico)。 |
| static readonly [IFC](../../groupdocs.viewer/filetype/ifc) | Industry Foundation Classes 文件 (.ifc) 是一种建立国际标准以导入和导出建筑对象及其属性的文件格式。该文件格式提供了不同软件应用之间的互操作性。了解更多关于此文件格式的信息，请点击[here](https://wiki.fileformat.com/cad/ifc)。 |
| static readonly [IGS](../../groupdocs.viewer/filetype/igs) | 初始图形交换规范 (IGES) (.igs) |
| static readonly [Iso](../../groupdocs.viewer/filetype/iso) | ISO光盘映像是一种未压缩的归档磁盘映像文件，表示光盘（如CD或DVD）上全部数据的内容，基于ISO-9660标准。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/compression/iso/)。 |
| static readonly [J2C](../../groupdocs.viewer/filetype/j2c) | JPEG 2000代码流 (.j2c) |
| static readonly [J2K](../../groupdocs.viewer/filetype/j2k) | JPEG 2000代码流 (.j2k) 是一种使用小波压缩而非DCT压缩的图像。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/j2k)。 |
| static readonly [JAVA](../../groupdocs.viewer/filetype/java) | Java源代码文件 (.java) |
| static readonly [JFIF](../../groupdocs.viewer/filetype/jfif) | JPEG文件互换格式 (.jfif) 是为平台间快速交换而开发的图像。此格式使用JPEG压缩。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/jfif)。 |
| static readonly [JLS](../../groupdocs.viewer/filetype/jls) | JPEG-LS (JLS) (.jls) |
| static readonly [JP2](../../groupdocs.viewer/filetype/jp2) | JPEG 2000核心图像文件 (.jp2) 是一种图像编码系统和最先进的图像压缩标准。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/jp2)。 |
| static readonly [JPC](../../groupdocs.viewer/filetype/jpc) | JPEG 2000代码流 (.jpc) |
| static readonly [JPEG](../../groupdocs.viewer/filetype/jpeg) | JPEG图像 (.jpeg) 是一种使用有损压缩方式保存的图像格式。压缩后的输出图像在存储大小和图像质量之间进行权衡。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/jpeg)。 |
| static readonly [JPF](../../groupdocs.viewer/filetype/jpf) | JPEG 2000图像文件 (.jpf) |
| static readonly [JPG](../../groupdocs.viewer/filetype/jpg) | JPEG图像 (.jpg) 是一种使用有损压缩方式保存的图像格式。压缩后的输出图像在存储大小和图像质量之间进行权衡。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/jpeg)。 |
| static readonly [JPM](../../groupdocs.viewer/filetype/jpm) | JPEG 2000图像文件 (.jpm) |
| static readonly [JPX](../../groupdocs.viewer/filetype/jpx) | JPEG 2000图像文件 (.jpx) |
| static readonly [JS](../../groupdocs.viewer/filetype/js) | JavaScript文件 (.js) |
| static readonly [JSON](../../groupdocs.viewer/filetype/json) | JavaScript对象表示法文件 (.json) |
| static readonly [LESS](../../groupdocs.viewer/filetype/less) | LESS样式表 (.less) |
| static readonly [Lha](../../groupdocs.viewer/filetype/lha) | LHA或LZH是一款免费压缩工具及其关联的文件格式。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/compression/lzh/)。 |
| static readonly [LOG](../../groupdocs.viewer/filetype/log) | 日志文件 (.log) |
| static readonly [M](../../groupdocs.viewer/filetype/m) | Objective-C实现文件 (.m) |
| static readonly [MAKE](../../groupdocs.viewer/filetype/make) | Xcode Makefile脚本 (.make) |
| static readonly [MBOX](../../groupdocs.viewer/filetype/mbox) | 电子邮件邮箱文件 (.mbox) 了解更多关于此文件格式的信息，请点击[此处](https://fileinfo.com/extension/mbox)。 |
| static readonly [MD](../../groupdocs.viewer/filetype/md) | Markdown文档文件 (.md) |
| static readonly [MHT](../../groupdocs.viewer/filetype/mht) | MHTML网页存档 (.mht) |
| static readonly [MHTML](../../groupdocs.viewer/filetype/mhtml) | MIME HTML文件 (.mhtml) |
| static readonly [ML](../../groupdocs.viewer/filetype/ml) | ML源代码文件 (.ml) |
| static readonly [MM](../../groupdocs.viewer/filetype/mm) | Objective-C++ 源文件 (.mm) |
| static readonly [MOBI](../../groupdocs.viewer/filetype/mobi) | Mobipocket eBook (.mobi) 是最广泛使用的电子书文件格式之一。该格式是对旧的 OEB（Open Ebook Format）格式的增强，并被用作 Mobipocket Reader 的专有格式。了解更多关于此文件格式的信息，请点击[这里](https://wiki.fileformat.com/ebook/mobi)。 |
| static readonly [MPP](../../groupdocs.viewer/filetype/mpp) | Microsoft Project 文件 (.mpp) 是 Microsoft Project 数据文件，可以集成方式存储与项目管理相关的信息。了解更多关于此文件格式的信息，请点击[这里](https://wiki.fileformat.com/project-management/mpp)。 |
| static readonly [MPT](../../groupdocs.viewer/filetype/mpt) | Microsoft Project 模板 (.mpt) 包含用于创建 .MPP 文件的基本信息、结构以及文档设置。了解更多关于此文件格式的信息，请点击[这里](https://wiki.fileformat.com/project-management/mpt)。 |
| static readonly [MPX](../../groupdocs.viewer/filetype/mpx) | Microsoft Project Exchange 文件 (.mpx) 是一种 ASCII 文件格式，用于在 Microsoft Project（MSP）与其他支持 MPX 文件格式的应用程序（如 Primavera Project Planner、Sciforma 和 Timerline Precision Estimating）之间传输项目信息。了解更多关于此文件格式的信息，请点击[这里](https://wiki.fileformat.com/project-management/mpx)。 |
| static readonly [MSG](../../groupdocs.viewer/filetype/msg) | Outlook 邮件信息 (.msg) 是 Microsoft Outlook 和 Exchange 用于存储电子邮件、联系人、约会或其他任务的文件格式。了解更多关于此文件格式的信息，请点击[这里](https://wiki.fileformat.com/email/msg)。 |
| static readonly [NSF](../../groupdocs.viewer/filetype/nsf) | Lotus Notes 数据库 (.nsf) 了解更多关于此文件格式的信息，请点击[这里](https://fileinfo.com/extension/nsf)。 |
| static readonly [NUMBERS](../../groupdocs.viewer/filetype/numbers) | Apple Numbers 代表类似 Excel 的二进制文件格式。这类文件可以通过 Apple Numbers 应用程序创建。了解更多关于此文件格式的信息，请点击[这里](https://fileinfo.com/extension/numbers)。 |
| static readonly [OBJ](../../groupdocs.viewer/filetype/obj) | Wavefront 3D 对象文件 (.obj) 是由 Wavefront Technologies 推出的 3D 图像文件。了解更多关于此文件格式的信息，请点击[这里](https://wiki.fileformat.com/3d/obj/)。 |
| static readonly [ODG](../../groupdocs.viewer/filetype/odg) | OpenDocument 图形文件 (.odg) 被 Apache OpenOffice 的 Draw 应用程序用于将绘图元素存储为矢量图像。了解更多关于此文件格式的信息，请点击[这里](https://wiki.fileformat.com/image/odg)。 |
| static readonly [ODP](../../groupdocs.viewer/filetype/odp) | OpenDocument 演示文稿 (.odp) 代表 OpenOffice.org 在 OASIS Open 标准中使用的演示文件格式。了解更多关于此文件格式的信息，请点击[这里](https://wiki.fileformat.com/presentation/odp)。 |
| static readonly [ODS](../../groupdocs.viewer/filetype/ods) | OpenDocument 电子表格 (.ods) 指可供用户编辑的 OpenDocument 电子表格文档格式。数据以行列的形式存储在 ODF 文件中。了解更多关于此文件格式的信息，请点击[这里](https://wiki.fileformat.com/spreadsheet/ods)。 |
| static readonly [ODT](../../groupdocs.viewer/filetype/odt) | OpenDocument 文本文档 (.odt) 是基于 OpenDocument 文本文件格式的文字处理应用程序创建的文档类型。了解更多关于此文件格式的信息，请点击[这里](https://wiki.fileformat.com/word-processing/odt)。 |
| static readonly [OFD](../../groupdocs.viewer/filetype/ofd) | Open Fixed-layout 文档（OFD）格式由 GB/T 33190-2016 定义，旨在取代中国公共机构中的 PDF。 |
| static readonly [OST](../../groupdocs.viewer/filetype/ost) | Outlook 离线数据文件 (.ost) 表示用户在使用 Microsoft Outlook 注册 Exchange Server 后，在本地机器上离线模式下的邮箱数据。了解更多关于此文件格式的信息，请点击[这里](https://wiki.fileformat.com/email/ost)。 |
| static readonly [OTG](../../groupdocs.viewer/filetype/otg) | OpenDocument 图形模板 (.otg) |
| static readonly [OTP](../../groupdocs.viewer/filetype/otp) | OpenDocument 演示模板 (.otp) 代表使用 OASIS OpenDocument 标准格式创建的演示模板文件。了解更多关于此文件格式的信息，请点击[这里](https://wiki.fileformat.com/presentation/otp)。 |
| static readonly [OTS](../../groupdocs.viewer/filetype/ots) | OpenDocument 电子表格模板 (.ots) |
| static readonly [OTT](../../groupdocs.viewer/filetype/ott) | OpenDocument 文档模板 (.ott) 代表符合 OASIS OpenDocument 标准格式的应用程序生成的模板文档。了解更多关于此文件格式的信息，请点击[这里](https://wiki.fileformat.com/word-processing/ott)。 |
| static readonly [OXPS](../../groupdocs.viewer/filetype/oxps) | OpenXPS 文件 (.oxps) |
| static readonly [PCL](../../groupdocs.viewer/filetype/pcl) | Printer Command Language 文档 (.pcl) |
| static readonly [PDF](../../groupdocs.viewer/filetype/pdf) | Portable Document Format 文件 (.pdf) 是 Adobe 在 1990 年代创建的一种文档类型。该文件格式的目的是引入一种标准，以在独立于应用软件、硬件以及操作系统的格式中表示文档和其他参考资料。了解更多关于此文件格式的信息，请点击[这里](https://wiki.fileformat.com/view/pdf)。 |
| static readonly [PHP](../../groupdocs.viewer/filetype/php) | PHP 源代码文件 (.php) |
| static readonly [PL](../../groupdocs.viewer/filetype/pl) | Perl 脚本 (.pl) |
| static readonly [PLT](../../groupdocs.viewer/filetype/plt) | PLT (HPGL) (.plt) 是 Autodesk, Inc. 推出的基于矢量的绘图仪文件，包含特定 CAD 文件的信息。绘图细节在生产中需要精确和准确，使用 PLT 文件能够保证这一点，因为所有图像都是用线而非点进行打印。了解更多关于此文件格式的信息，请点击[这里](https://wiki.fileformat.com/cad/plt)。 |
| static readonly [PNG](../../groupdocs.viewer/filetype/png) | Portable Network Graphic (.png) 是一种使用无损压缩的光栅图像文件格式。该文件格式是为取代图形交换格式 (GIF) 而创建的，并且没有版权限制。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/png)。 |
| static readonly [POT](../../groupdocs.viewer/filetype/pot) | PowerPoint Template (.pot) 表示由 PowerPoint 97-2003 版本创建的 Microsoft PowerPoint 模板文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/presentation/pot)。 |
| static readonly [POTM](../../groupdocs.viewer/filetype/potm) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) 是支持宏的 Microsoft PowerPoint 模板文件。POTM 文件由 PowerPoint 2007 或更高版本创建，包含可用于创建后续演示文件的默认设置。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/presentation/potm)。 |
| static readonly [POTX](../../groupdocs.viewer/filetype/potx) | PowerPoint Open XML Presentation Template (.potx) 表示由 Microsoft PowerPoint 2007 及以上版本创建的 Microsoft PowerPoint 模板演示文稿。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/presentation/potx)。 |
| static readonly [PPS](../../groupdocs.viewer/filetype/pps) | PowerPoint Slide Show (.pps) 是使用 Microsoft PowerPoint 用于幻灯片放映的文件。Microsoft PowerPoint 97-2003 支持对 PPS 文件的读取和创建。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/presentation/pps)。 |
| static readonly [PPSM](../../groupdocs.viewer/filetype/ppsm) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) 表示由 Microsoft PowerPoint 2007 或更高版本创建的支持宏的幻灯片放映文件格式。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/presentation/ppsm)。 |
| static readonly [PPSX](../../groupdocs.viewer/filetype/ppsx) | PowerPoint Open XML Slide Show (.ppsx) 文件是使用 Microsoft PowerPoint 2007 及以上版本为幻灯片放映目的创建的。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/presentation/ppsx)。 |
| static readonly [PPT](../../groupdocs.viewer/filetype/ppt) | PowerPoint Presentation (.ppt) 表示包含一系列幻灯片用于幻灯片放映的 PowerPoint 文件。它指定了 Microsoft PowerPoint 97-2003 使用的二进制文件格式。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/presentation/ppt)。 |
| static readonly [PPTM](../../groupdocs.viewer/filetype/pptm) | PowerPoint Open XML Macro-Enabled Presentation 是由 Microsoft PowerPoint 2007 或更高版本创建的支持宏的演示文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/presentation/pptm)。 |
| static readonly [PPTX](../../groupdocs.viewer/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) 是使用流行的 Microsoft PowerPoint 应用程序创建的演示文件。不同于之前的二进制 PPT 演示文件格式，PPTX 格式基于 Microsoft PowerPoint 开放 XML 演示文件格式。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/presentation/pptx)。 |
| static readonly [PROPERTIES](../../groupdocs.viewer/filetype/properties) | Java 属性文件 (.properties) |
| static readonly [PS](../../groupdocs.viewer/filetype/ps) | PostScript 文件 (.ps) |
| static readonly [PS1](../../groupdocs.viewer/filetype/ps1) | PowerShell 脚本文件 (.ps1) 是用于 Windows PowerShell Cmdlet 文件的文件格式。了解更多关于此文件格式的信息，请点击[此处](https://fileinfo.com/extension/ps1)。 |
| static readonly [PSD1](../../groupdocs.viewer/filetype/psd1) | PowerShell 脚本模块清单 (.psd1) 是用于 PowerShell 模块清单脚本的文件格式。了解更多关于此文件格式的信息，请点击[此处](https://fileinfo.com/extension/psd1)。 |
| static readonly [PSM1](../../groupdocs.viewer/filetype/psm1) | PowerShell 脚本模块 (.psm1) 是用于 PowerShell 模块脚本的文件格式。了解更多关于此文件格式的信息，请点击[此处](https://fileinfo.com/extension/psm1)。 |
| static readonly [PST](../../groupdocs.viewer/filetype/pst) | Outlook Personal Information Store File (.pst) 表示 Outlook 个人存储文件（也称为个人存储表），用于存储各种用户信息。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/email/pst)。 |
| static readonly [PY](../../groupdocs.viewer/filetype/py) | Python 脚本 (.py) |
| static readonly [RAR](../../groupdocs.viewer/filetype/rar) | Roshal ARchive (.rar) 是使用 RAR（WINRAR）压缩方法生成的压缩文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/compression/rar)。 |
| static readonly [RB](../../groupdocs.viewer/filetype/rb) | Ruby 源代码 (.rb) |
| static readonly [RST](../../groupdocs.viewer/filetype/rst) | reStructuredText 文件 (.rst) |
| static readonly [RTF](../../groupdocs.viewer/filetype/rtf) | Rich Text Format File (.rtf) 表示一种用于在应用程序中编码格式化文本和图形的方法。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/word-processing/rtf)。 |
| static readonly [SASS](../../groupdocs.viewer/filetype/sass) | Syntactically Awesome StyleSheets 文件 (.sass) |
| static readonly [SCALA](../../groupdocs.viewer/filetype/scala) | Scala 源代码文件 (.scala) |
| static readonly [SCM](../../groupdocs.viewer/filetype/scm) | Scheme 源代码文件 (.scm) |
| static readonly [SCRIPT](../../groupdocs.viewer/filetype/script) | 通用脚本文件 (.script) |
| static readonly [SevenZip](../../groupdocs.viewer/filetype/sevenzip) | 7Zip (.7z, .7zip) 是免费开源的压缩工具，使用 LZMA 和 LZMA2 压缩。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/compression/7z/)。 |
| static readonly [SH](../../groupdocs.viewer/filetype/sh) | Bash Shell 脚本 (.sh) |
| static readonly [SML](../../groupdocs.viewer/filetype/sml) | Standard ML 源代码文件 (.sml) |
| static readonly [SQL](../../groupdocs.viewer/filetype/sql) | 结构化查询语言数据文件 (.sql) |
| static readonly [STL](../../groupdocs.viewer/filetype/stl) | Stereolithography 文件 (.stl) 是一种可互换的文件格式，用于表示三维表面几何。该文件格式在快速原型、3D 打印和计算机辅助制造等多个领域中得到使用。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/cad/stl)。 |
| static readonly [SVG](../../groupdocs.viewer/filetype/svg) | Scalable Vector Graphics 文件 (.svg) 是一种可缩放矢量图形文件，使用基于 XML 的文本格式来描述图像的外观。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/page-description-language/svg)。 |
| static readonly [SVGZ](../../groupdocs.viewer/filetype/svgz) | Scalable Vector Graphics 文件 (.svgz) 是一种可缩放矢量图形文件，使用基于 XML 的文本格式，并通过 GZIP 压缩，以描述图像的外观。了解更多关于此文件格式的信息，请点击[此处](https://fileinfo.com/extension/svgz)。 |
| static readonly [SXC](../../groupdocs.viewer/filetype/sxc) | StarOffice Calc 电子表格 (.sxc) |
| static readonly [TAR](../../groupdocs.viewer/filetype/tar) | Consolidated Unix 文件归档 (.tar) 是使用基于 Unix 的工具创建的归档，用于收集一个或多个文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/compression/tar)。 |
| static readonly [TARGZ](../../groupdocs.viewer/filetype/targz) | Consolidated Unix 文件归档 (.tgz, .tar.gz) 是使用基于 Unix 的工具创建的归档，用于收集一个或多个文件。了解更多关于此文件格式的信息，请点击[此处](https://fileinfo.com/extension/tgz)。 |
| static readonly [TARXZ](../../groupdocs.viewer/filetype/tarxz) | Consolidated Unix 文件归档 (.txz, .tar.xz) 是使用基于 Unix 的工具创建的归档，用于收集一个或多个文件。了解更多关于此文件格式的信息，请点击[此处](https://fileinfo.com/extension/txz)。 |
| static readonly [TarZst](../../groupdocs.viewer/filetype/tarzst) | TZST 文件 (.tar.zst, .tzst) 是 Zstandard（ZST）归档，内部包含 Consolidated Unix 文件归档（Tar），由基于 Unix 的工具创建，用于收集一个或多个文件。 |
| static readonly [TEX](../../groupdocs.viewer/filetype/tex) | LaTeX 源文档 (.tex) 是一种既包含编程又包含标记功能的语言，用于排版文档。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/page-description-language/tex)。 |
| static readonly [TGA](../../groupdocs.viewer/filetype/tga) | Truevision TGA（Truevision Advanced Raster Adapter - TARGA）用于存储由 TRUEVISION 开发的位图数字图像。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/tga)。 |
| static readonly [TGZ](../../groupdocs.viewer/filetype/tgz) | Consolidated Unix 文件归档 (.tgz, .tar.gz) 是使用基于 Unix 的工具创建的归档，用于收集一个或多个文件。了解更多关于此文件格式的信息，请点击[此处](https://fileinfo.com/extension/tgz)。 |
| static readonly [TIF](../../groupdocs.viewer/filetype/tif) | Tagged Image File (.tif) 表示用于各种符合此文件格式标准的设备的栅格图像。它能够在多种色彩空间中描述二值、灰度、调色板颜色和全彩图像数据。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/tiff)。 |
| static readonly [TIFF](../../groupdocs.viewer/filetype/tiff) | Tagged Image File Format (.tiff) 表示用于各种符合此文件格式标准的设备的栅格图像。它能够在多种色彩空间中描述二值、灰度、调色板颜色和全彩图像数据。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/tiff)。 |
| static readonly [TSV](../../groupdocs.viewer/filetype/tsv) | Tab Separated Values 文件 (.tsv) 表示以制表符分隔的纯文本格式数据。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/tsv)。 |
| static readonly [TXT](../../groupdocs.viewer/filetype/txt) | Plain Text 文件 (.txt) 表示包含按行排列的纯文本的文档。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/word-processing/txt)。 |
| static readonly [TXZ](../../groupdocs.viewer/filetype/txz) | Consolidated Unix 文件归档 (.txz, .tar.xz) 是使用基于 Unix 的工具创建的归档，用于收集一个或多个文件。了解更多关于此文件格式的信息，请点击[此处](https://fileinfo.com/extension/txz)。 |
| static readonly [Tzst](../../groupdocs.viewer/filetype/tzst) | TZST 文件 (.tar.zst, .tzst) 是 Zstandard（ZST）归档，内部包含 Consolidated Unix 文件归档（Tar），由基于 Unix 的工具创建，用于收集一个或多个文件。 |
| static readonly [Unknown](../../groupdocs.viewer/filetype/unknown) | 表示未知文件类型。 |
| static readonly [VB](../../groupdocs.viewer/filetype/vb) | Visual Basic 项目项文件 (.vb) 是使用 Microsoft 为 .NET 应用程序开发而创建的 Visual Basic 语言的源代码文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/programming/vb)。 |
| static readonly [VCF](../../groupdocs.viewer/filetype/vcf) | vCard 文件 (.vcf) 是一种用于存储联系信息的数字文件格式。该格式被广泛用于流行信息交换应用之间的数据互通。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/email/vcf)。 |
| static readonly [VDW](../../groupdocs.viewer/filetype/vdw) | Visio Web 绘图 (.vdw) 表示一种指定渲染 Web 绘图所需流和存储的文件格式。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/web/vdw)。 |
| static readonly [VDX](../../groupdocs.viewer/filetype/vdx) | Visio 绘图 XML 文件 (.vdx) 代表在 Microsoft Visio 中创建的任何绘图或图表，但以 XML 格式保存，扩展名为 .VDX。Visio 绘图 XML 文件是在 Microsoft 开发的 Visio 软件中创建的。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vdx)。 |
| static readonly [VIM](../../groupdocs.viewer/filetype/vim) | Vim 设置文件 (.vim) |
| static readonly [VSD](../../groupdocs.viewer/filetype/vsd) | Visio 绘图文件 (.vsd) 是使用 Microsoft Visio 应用程序创建的绘图，用于表示各种图形对象及其相互连接。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vsd)。 |
| static readonly [VSDM](../../groupdocs.viewer/filetype/vsdm) | Visio 宏启用绘图 (.vsdm) 是使用支持宏的 Microsoft Visio 应用程序创建的绘图文件。VSDM 文件是类似于 VSDX 的 OPC/XML 绘图，但还提供在打开文件时运行宏的功能。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vsdm)。 |
| static readonly [VSDX](../../groupdocs.viewer/filetype/vsdx) | Visio 绘图 (.vsdx) 代表自 Microsoft Office 2013 起引入的 Microsoft Visio 文件格式。它旨在取代早期 Microsoft Visio 支持的二进制文件格式 .VSD。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vsdx)。 |
| static readonly [VSS](../../groupdocs.viewer/filetype/vss) | Visio 模板文件 (.vss) 是使用 Microsoft Visio 2007 及更早版本创建的模板文件。模板文件提供可包含在 .VSD Visio 绘图中的绘图对象。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vss)。 |
| static readonly [VSSM](../../groupdocs.viewer/filetype/vssm) | Visio 宏启用模板文件 (.vssm) 是支持宏的 Microsoft Visio 模板文件。打开 VSSM 文件时可运行宏，以实现图表中形状的所需格式化和放置。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vssm)。 |
| static readonly [VSSX](../../groupdocs.viewer/filetype/vssx) | Visio 模板文件 (.vssx) 是使用 Microsoft Visio 2013 及以上版本创建的绘图模板。VSSX 文件格式可在 Visio 2013 及以上版本中打开。Visio 文件以表示各种绘图元素而闻名，例如形状集合、连接线、流程图、网络布局、UML 图等。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vssx)。 |
| static readonly [VST](../../groupdocs.viewer/filetype/vst) | Visio 绘图模板 (.vst) 是使用 Microsoft Visio 创建的矢量图像文件，充当创建其他文件的模板。这些模板文件采用二进制格式，包含用于创建新 Visio 绘图的默认布局和设置。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vst)。 |
| static readonly [VSTM](../../groupdocs.viewer/filetype/vstm) | Visio 宏启用绘图模板 (.vstm) 是使用 Microsoft Visio 创建的支持宏的模板文件。与 VSDX 文件不同，基于 VSTM 模板创建的文件可以运行使用 Visual Basic for Applications (VBA) 代码编写的宏。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vstm)。 |
| static readonly [VSTX](../../groupdocs.viewer/filetype/vstx) | Visio 绘图模板 (.vstx) 是使用 Microsoft Visio 2013 及以上版本创建的绘图模板文件。这些 VSTX 文件提供创建 Visio 绘图的起始点，保存为 .VSDX 文件，并包含默认布局和设置。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vstx)。 |
| static readonly [VSX](../../groupdocs.viewer/filetype/vsx) | Visio 模板 XML 文件 (.vsx) 指用于在 Microsoft Visio 中创建图表的绘图和形状模板。VSX 文件以 XML 格式保存，支持至 Visio 2013。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vsx)。 |
| static readonly [VTX](../../groupdocs.viewer/filetype/vtx) | Visio 模板 XML 文件 (.vtx) 是以 XML 格式保存到磁盘的 Microsoft Visio 绘图模板。该模板旨在提供具有基本设置的文件，可用于创建多个具有相同设置的 Visio 文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/vtx)。 |
| static readonly [WEBP](../../groupdocs.viewer/filetype/webp) | WebP 图像 (.webp) 是一种基于无损和有损压缩的现代光栅网络图像文件格式。它在显著减小图像尺寸的同时提供相同的图像质量。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/webp)。 |
| static readonly [WMF](../../groupdocs.viewer/filetype/wmf) | Windows 元文件 (.wmf) 代表用于存储矢量和位图格式图像数据的 Microsoft Windows Metafile (WMF)。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/image/wmf)。 |
| static readonly [WMZ](../../groupdocs.viewer/filetype/wmz) | 压缩 Windows 元文件 (.wmz) 代表以 GZIP 压缩的 Microsoft Windows Metafile (WMF)，用于存储矢量和位图格式的图像数据。了解更多关于此文件格式的信息，请点击[此处](https://fileinfo.com/extension/wmz#compressed_windows_metafile)。 |
| static readonly [XLAM](../../groupdocs.viewer/filetype/xlam) | Microsoft Excel 加载项 (.xlam) |
| static readonly [XLS](../../groupdocs.viewer/filetype/xls) | Excel 电子表格 (.xls) 代表 Excel 二进制文件格式。这类文件可由 Microsoft Excel 以及其他类似的电子表格程序如 OpenOffice Calc 或 Apple Numbers 创建。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xls)。 |
| static readonly [XLSB](../../groupdocs.viewer/filetype/xlsb) | Excel 二进制电子表格 (.xlsb) 指定 Excel 二进制文件格式，它是一组记录和结构，用于描述 Excel 工作簿的内容。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xlsb)。 |
| static readonly [XLSM](../../groupdocs.viewer/filetype/xlsm) | Excel Open XML 宏启用电子表格 (.xlsm) 是一种支持宏的电子表格文件类型。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xlsm)。 |
| static readonly [XLSX](../../groupdocs.viewer/filetype/xlsx) | Microsoft Excel Open XML 电子表格 (.xlsx) 是一种广为人知的 Microsoft Excel 文档格式，由 Microsoft 在 Microsoft Office 2007 发布时引入。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xlsx)。 |
| static readonly [XLT](../../groupdocs.viewer/filetype/xlt) | Microsoft Excel 模板 (.xlt) 是使用 Microsoft Excel（Microsoft Office 套件中的电子表格应用）创建的模板文件。Microsoft Office 97-2003 支持创建和打开 XLT 文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xlt)。 |
| static readonly [XLTM](../../groupdocs.viewer/filetype/xltm) | Microsoft Excel 宏启用模板 (.xltm) 代表由 Microsoft Excel 生成的宏启用模板文件。XLTM 文件在结构上与 XLTX 类似，唯一区别是后者不支持创建带宏的模板文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xltm)。 |
| static readonly [XLTX](../../groupdocs.viewer/filetype/xltx) | Excel Open XML Spreadsheet Template (.xltx) 表示基于 Office OpenXML 文件格式规范的 Microsoft Excel 模板。它用于创建一个标准模板文件，可用于生成具有 XLTX 文件中指定的相同设置的 XLSX 文件。了解更多关于此文件格式的信息，请访问[此处](https://wiki.fileformat.com/spreadsheet/xltx)。 |
| static readonly [XML](../../groupdocs.viewer/filetype/xml) | XML File (.xml)。GroupDocs.Viewer 拥有用于处理 XML 文件的专用处理器，参见[文档](https://docs.groupdocs.com/viewer/net/render-xml-documents/)。 |
| static readonly [XPS](../../groupdocs.viewer/filetype/xps) | XML Paper Specification File (.xps) 表示基于 Microsoft 创建的 XML Paper Specification 的页面布局文件。此格式由 Microsoft 开发，用于取代 EMF 文件格式，类似于 PDF 文件格式，但在文档的布局、外观和打印信息中使用 XML。了解更多关于此文件格式的信息，请访问[此处](https://wiki.fileformat.com/page-description-language/xps)。 |
| static readonly [XZ](../../groupdocs.viewer/filetype/xz) | XZ file (.xz) 是一种基于 LZMA 算法的高压缩比归档压缩算法。了解更多关于此文件格式的信息，请访问[此处](https://fileinfo.com/extension/xz)。 |
| static readonly [YAML](../../groupdocs.viewer/filetype/yaml) | YAML 文档 (.yaml) |
| static readonly [ZIP](../../groupdocs.viewer/filetype/zip) | Zipped File (.zip) 表示可以容纳一个或多个文件或目录的归档。了解更多关于此文件格式的信息，请访问[此处](https://wiki.fileformat.com/compression/zip)。 |
| static readonly [Zstandard](../../groupdocs.viewer/filetype/zstandard) | ZST file 是使用 Zstandard (zstd) 压缩算法生成的压缩文件。它是通过该算法进行无损压缩创建的压缩文件。ZST 文件可用于压缩各种类型的文件，如数据库、文件系统、网络和游戏。了解更多关于此文件格式的信息，请访问[此处](https://docs.fileformat.com/compression/zst/)。 |

### 另见

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
