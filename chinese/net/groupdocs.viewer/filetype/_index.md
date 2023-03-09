---
title: FileType
second_title: GroupDocs.Viewer for .NET API 参考
description: 表示文件类型提供获取所有支持的文件类型列表的方法GroupDocs.查看器.
type: docs
weight: 70
url: /zh/net/groupdocs.viewer/filetype/
---
## FileType class

表示文件类型。提供获取所有支持的文件类型列表的方法**GroupDocs.查看器**.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [FileType](filetype#constructor)() | 初始化新实例[`FileType`](../filetype)类. |
| [FileType](filetype#constructor_1)(string, string) | 初始化新实例[`FileType`](../filetype)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Extension](../../groupdocs.viewer/filetype/extension) { get; set; } | 文件名后缀（包括句点“.”）例如“.doc”. |
| [FileFormat](../../groupdocs.viewer/filetype/fileformat) { get; set; } | 文件类型名称，例如“Microsoft Word 文档”. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [FromExtension](../../groupdocs.viewer/filetype/fromextension)(string) | 将文件扩展名映射到文件类型。 |
| static [FromFilePath](../../groupdocs.viewer/filetype/fromfilepath)(string) | 提取文件扩展名并将其映射到文件类型。 |
| static [FromMediaType](../../groupdocs.viewer/filetype/frommediatype)(string) | 将文件媒体类型映射到文件类型，例如“应用程序/pdf”将映射到[`PDF`](./pdf). |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream)(Stream) | 通过读取文件签名来检测文件类型。 |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_1)(Stream, ILogger) | 通过读取文件签名来检测文件类型。 |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_2)(Stream, string) | 通过读取文件签名来检测文件类型。 |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_3)(Stream, string, ILogger) | 通过读取文件签名来检测文件类型。 |
| [Equals](../../groupdocs.viewer/filetype/equals#equals)(FileType) | 判断当前是否[`FileType`](../filetype)与指定的相同[`FileType`](../filetype)对象. |
| override [Equals](../../groupdocs.viewer/filetype/equals#equals_1)(object) | 判断当前是否[`FileType`](../filetype)与指定对象相同。 |
| override [GetHashCode](../../groupdocs.viewer/filetype/gethashcode)() | 返回当前的哈希码[`FileType`](../filetype)对象. |
| override [ToString](../../groupdocs.viewer/filetype/tostring)() | 返回表示当前对象的字符串。 |
| static [DetectEncoding](../../groupdocs.viewer/filetype/detectencoding#detectencoding)(Stream) | 尝试检测文本[`TXT`](./txt),[`TSV`](./tsv) ， 和[`CSV`](./csv) stream. 文件编码 |
| static [DetectEncoding](../../groupdocs.viewer/filetype/detectencoding#detectencoding_1)(string) | 尝试检测文本[`TXT`](./txt),[`TSV`](./tsv) ， 和[`CSV`](./csv)按路径编码的文件. |
| static [GetSupportedFileTypes](../../groupdocs.viewer/filetype/getsupportedfiletypes)() | 检索支持的文件类型 |
| [operator ==](../../groupdocs.viewer/filetype/op_equality) | 判断是否两个[`FileType`](../filetype)对象是相同的。 |
| [operator !=](../../groupdocs.viewer/filetype/op_inequality) | 判断是否两个[`FileType`](../filetype)对象不一样. |

## 字段

| 姓名 | 描述 |
| --- | --- |
| static readonly [AI](../../groupdocs.viewer/filetype/ai) | Adobe Illustrator (.ai) 是一种用于 Adobe Illustrator 绘图的文件格式。 了解有关此文件格式的更多信息[这里](https://fileinfo.com/extension/ai#adobe_illustrator_file) |
| static readonly [APNG](../../groupdocs.viewer/filetype/apng) | 动画便携式网络图形 (.apng) 是支持动画的 PNG 格式的扩展。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/apng) |
| static readonly [AS](../../groupdocs.viewer/filetype/as) | 动作脚本文件 (.as) |
| static readonly [AS3](../../groupdocs.viewer/filetype/as3) | 动作脚本文件 (.as) |
| static readonly [ASM](../../groupdocs.viewer/filetype/asm) | 汇编语言源代码文件 (.asm) |
| static readonly [BAT](../../groupdocs.viewer/filetype/bat) | DOS 批处理文件 (.bat) |
| static readonly [BMP](../../groupdocs.viewer/filetype/bmp) | 位图图像文件 (.bmp) 用于存储位图数字图像。这些图像独立于图形适配器，也称为设备独立位图 (DIB) 文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/bmp) |
| static readonly [BZ2](../../groupdocs.viewer/filetype/bz2) | Bzip2 Compressed File (.bz2) 是使用BZIP2开源压缩方式生成的压缩文件，多用于UNIX或Linux系统。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/compression/bz2) |
| static readonly [C](../../groupdocs.viewer/filetype/c) | C/C++ 源代码文件 (.c) |
| static readonly [CC](../../groupdocs.viewer/filetype/cc) | C++ 源代码文件 (.cc) |
| static readonly [CDR](../../groupdocs.viewer/filetype/cdr) | CorelDraw Vector Graphic Drawing (.cdr) 是使用 CorelDRAW 原生创建的矢量绘图图像文件，用于存储编码和压缩的数字图像。这样的绘图文件包含用于图像内容的矢量表示的文本、线条、形状、图像、颜色和效果。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/cdr) |
| static readonly [CF2](../../groupdocs.viewer/filetype/cf2) | 通用文件格式 File 了解有关此文件格式的更多信息[这里](https://fileinfo.com/extension/cf2). |
| static readonly [CGM](../../groupdocs.viewer/filetype/cgm) | 计算机图形图元文件 (.cgm) 是一种免费的、独立于平台的国际标准图元文件格式，用于存储和交换矢量图形 (2D)、光栅图形和文本。 CGM 使用面向对象的方法和许多图像制作功能规定。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/page-description-language/cgm) |
| static readonly [CHM](../../groupdocs.viewer/filetype/chm) | Microsoft 编译的 HTML 帮助文件 (.chm) 是一种众所周知的 HELP（某些应用程序的文档）文档格式。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/web/chm/) |
| static readonly [CMAKE](../../groupdocs.viewer/filetype/cmake) | CMake 文件 (.cmake) |
| static readonly [CMX](../../groupdocs.viewer/filetype/cmx) | Corel Exchange (.cmx) 是一种绘图图像文件，可能包含矢量图形和位图图形。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/cmx) |
| static readonly [CPIO](../../groupdocs.viewer/filetype/cpio) | Cpio 是一个通用的文件归档实用程序及其相关文件格式。它主要安装在类 Unix 计算机操作系统上。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/compression/cpio). |
| static readonly [CPP](../../groupdocs.viewer/filetype/cpp) | C++ 源代码文件 (.cpp) |
| static readonly [CS](../../groupdocs.viewer/filetype/cs) | C# 源代码文件 (.cs) 是 C# 编程语言的源代码文件。由 Microsoft 引入，用于 .NET Framework。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/programming/cs) |
| static readonly [CSS](../../groupdocs.viewer/filetype/css) | 级联样式表 (.css) |
| static readonly [CSV](../../groupdocs.viewer/filetype/csv) | 逗号分隔值文件 (.csv) 表示纯文本文件，其中包含以逗号分隔值的数据记录。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/csv) |
| static readonly [CXX](../../groupdocs.viewer/filetype/cxx) | C++ 源代码文件 (.cxx) |
| static readonly [DCM](../../groupdocs.viewer/filetype/dcm) | DICOM 图像 (.dcm) 表示存储患者医疗信息的数字图像，例如 MRI、CT 扫描和超声图像。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/dcm) |
| static readonly [DGN](../../groupdocs.viewer/filetype/dgn) | MicroStation 设计文件 (.dgn) 是由 CAD 应用程序（例如 MicroStation 和鹰图交互式图形设计系统）创建并受其支持的绘图。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/cad/dgn) |
| static readonly [DIB](../../groupdocs.viewer/filetype/dib) | 设备独立位图文件 (.dib) |
| static readonly [DIFF](../../groupdocs.viewer/filetype/diff) | 补丁文件 (.diff) |
| static readonly [DJVU](../../groupdocs.viewer/filetype/djvu) | DjVu 图像 (.djvu) 是一种图形文件格式，适用于扫描的文档和书籍，尤其是那些包含文本、绘图、图像和照片的组合。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/djvu) |
| static readonly [DNG](../../groupdocs.viewer/filetype/dng) | Digital Negative Specification (.dng) 是一种用于存储原始文件的数码相机图像格式。它由Adobe于2004年9月开发。它基本上是为数码摄影而开发的。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/dng) |
| static readonly [DOC](../../groupdocs.viewer/filetype/doc) | Microsoft Word 文档 (.doc) 表示由 Microsoft Word 或其他文字处理文档以二进制文件格式生成的文档。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/doc) |
| static readonly [DOCM](../../groupdocs.viewer/filetype/docm) | Word Open XML Macro-Enabled Document (.docm) 是 Microsoft Word 2007 或更高版本生成的文档，能够运行宏。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/docm) |
| static readonly [DOCX](../../groupdocs.viewer/filetype/docx) | Microsoft Word Open XML 文档 (.docx) 是一种众所周知的 Microsoft Word 文档格式。随着 Microsoft Office 2007 的发布从 2007 年引入，这种新文档格式的结构从普通二进制文件更改为 XML 和二进制文件的组合。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/docx) |
| static readonly [DOT](../../groupdocs.viewer/filetype/dot) | Word 文档模板 (.dot) 是由 Microsoft Word 创建的模板文件，具有用于生成更多 DOC 或 DOCX 文件的预格式化设置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/dot) |
| static readonly [DOTM](../../groupdocs.viewer/filetype/dotm) | Word Open XML 启用宏的文档模板 (.dotm) 表示使用 Microsoft Word 2007 或更高版本创建的模板文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/dotm) |
| static readonly [DOTX](../../groupdocs.viewer/filetype/dotx) | Word Open XML 文档模板 (.dotx) 是由 Microsoft Word 创建的模板文件，具有用于生成更多 DOCX 文件的预格式化设置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/dotx) |
| static readonly [DWF](../../groupdocs.viewer/filetype/dwf) | 设计 Web 格式文件 (.dwf) 表示压缩格式的 2D/3D 绘图，用于查看、审阅或打印设计文件。它包含图形和文本作为设计数据的一部分，并由于其压缩格式而减小了文件的大小。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/cad/dwf). |
| static readonly [DWFX](../../groupdocs.viewer/filetype/dwfx) | 设计 Web 格式文件 XPS (.dwfx) 将 2D/3D 绘图表示为压缩格式的 XPS 文档，用于查看、审阅或打印设计文件。它包含图形和文本作为设计数据的一部分，并由于其压缩格式而减小了文件的大小。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/cad/dwfx). |
| static readonly [DWG](../../groupdocs.viewer/filetype/dwg) | AutoCAD 绘图数据库文件 (.dwg) 表示用于包含 2D 和 3D 设计数据的专有二进制文件。与作为 ASCII 文件的 DXF 一样，DWG 代表 CAD（计算机辅助设计）图纸的二进制文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/cad/dwg). |
| static readonly [DWT](../../groupdocs.viewer/filetype/dwt) | AutoCAD 绘图模板 (.dwt) 是一种 AutoCAD 绘图模板文件，用作创建可另存为 DWG 文件的绘图的起始文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/cad/dwt) |
| static readonly [DXF](../../groupdocs.viewer/filetype/dxf) | 绘图交换格式文件 (.dxf) 是 AutoCAD 绘图文件的标记数据表示。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/cad/dxf) |
| static readonly [EMF](../../groupdocs.viewer/filetype/emf) | 增强型 Windows 图元文件 (.emf) 独立于设备表示图形图像。 EMF 图元文件由按时间顺序排列的可变长度记录组成，可以在任何输出设备上解析后呈现存储的图像。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/emf) |
| static readonly [EML](../../groupdocs.viewer/filetype/eml) | 电子邮件消息 (.eml) 表示使用 Outlook 和其他相关应用程序保存的电子邮件消息。几乎所有电子邮件客户端都支持此文件格式，因为它符合 RFC-822 Internet 消息格式标准。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/email/eml) |
| static readonly [EMLX](../../groupdocs.viewer/filetype/emlx) | Apple Mail Message (.emlx) 由 Apple 实施和开发。 Apple Mail 应用程序使用 EMLX 文件格式导出电子邮件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/email/emlx) |
| static readonly [EMZ](../../groupdocs.viewer/filetype/emz) | 增强型 Windows 图元文件压缩 (.emz) 表示由 GZIP 独立于设备压缩的图形图像。 EMF 图元文件由按时间顺序排列的可变长度记录组成，可以在任何输出设备上解析后呈现存储的图像。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/emz) |
| static readonly [EPS](../../groupdocs.viewer/filetype/eps) | 封装的 PostScript 文件 (.eps) 描述了一个封装的 PostScript 语言程序，它描述了单个页面的外观。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/page-description-language/eps) |
| static readonly [EPUB](../../groupdocs.viewer/filetype/epub) | 打开电子书文件 (.epub) 是一种电子书文件格式，可为出版商和消费者提供标准的数字出版格式。该格式现在非常普遍，许多电子阅读器和软件应用程序都支持它。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/ebook/epub) |
| static readonly [ERB](../../groupdocs.viewer/filetype/erb) | Ruby ERB 脚本 (.erb) |
| static readonly [Excel2003XML](../../groupdocs.viewer/filetype/excel2003xml) | Excel 2003 XML (SpreadsheetML) 表示 Excel 二进制文件格式。此类文件可以由 Microsoft Excel 以及其他类似的电子表格程序（例如 OpenOffice Calc 或 Apple Numbers）创建。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xls) |
| static readonly [FBX](../../groupdocs.viewer/filetype/fbx) | Autodesk FBX 交换文件 (FilmBoX) (.fbx) 表示 3D 模型格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/cad/fbx). |
| static readonly [FODG](../../groupdocs.viewer/filetype/fodg) | Apache OpenOffice 的 Draw 应用程序使用平面 XML ODF 模板 (.fodg) 将绘图元素存储为矢量图像。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/fodg) |
| static readonly [FODP](../../groupdocs.viewer/filetype/fodp) | OpenDocument Presentation (.fodp) 表示 OpenDocument Flat XML Presentation。 了解有关此文件格式的更多信息[这里](https://fileinfo.com/extension/fodp) |
| static readonly [FODS](../../groupdocs.viewer/filetype/fods) | OpenDocument 平面 XML 电子表格 (.fods) |
| static readonly [GIF](../../groupdocs.viewer/filetype/gif) | 图形交换格式文件 (.gif) 是一种高度压缩的图像。对于每个图像，GIF 通常允许每个像素最多 8 位，并且整个图像最多允许 256 种颜色。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/gif) |
| static readonly [GROOVY](../../groupdocs.viewer/filetype/groovy) | Groovy 源代码文件 (.groovy) |
| static readonly [GZ](../../groupdocs.viewer/filetype/gz) | Gnu 压缩文件 (.gz) 是使用 gzip 压缩应用程序创建的压缩文件。它可以包含多个压缩文件，常用于 UNIX 和 Linux 系统。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/compression/gz) |
| static readonly [GZIP](../../groupdocs.viewer/filetype/gzip) | Gnu Zipped File (.gzip) 是作为免费实用程序引入的，用于替换 Unix 系统中使用的 Compress 程序。此类文件可以使用多种应用程序打开和提取，例如在 Windows 和 MacOS 上都可用的 WinZip。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/compression/gz). |
| static readonly [H](../../groupdocs.viewer/filetype/h) | C/C++/Objective-C 头文件 (.h) |
| static readonly [HAML](../../groupdocs.viewer/filetype/haml) | Haml 源代码文件 (.haml) |
| static readonly [HH](../../groupdocs.viewer/filetype/hh) | C++ 头文件 (.hh) |
| static readonly [HPG](../../groupdocs.viewer/filetype/hpg) | PLT (HPGL) (.hpg) |
| static readonly [HTM](../../groupdocs.viewer/filetype/htm) | 超文本标记语言文件 (.htm) 是为在浏览器中显示而创建的网页的扩展名。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/web/html) |
| static readonly [HTML](../../groupdocs.viewer/filetype/html) | 超文本标记语言文件 (.html) 是为在浏览器中显示而创建的网页的扩展名。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/web/html) |
| static readonly [ICO](../../groupdocs.viewer/filetype/ico) | 图标文件 (.ico) 是用作图标的图像文件类型，用于表示 Microsoft Windows 上的应用程序。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/ico) |
| static readonly [IFC](../../groupdocs.viewer/filetype/ifc) | 行业基础类文件 (.ifc) 是一种文件格式，它建立了导入和导出建筑对象及其属性的国际标准。此文件格式提供不同软件应用程序之间的互操作性。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/cad/ifc). |
| static readonly [IGS](../../groupdocs.viewer/filetype/igs) | 初始图形交换规范 (IGES) (.igs) |
| static readonly [J2C](../../groupdocs.viewer/filetype/j2c) | JPEG 2000 代码流 (.j2c) |
| static readonly [J2K](../../groupdocs.viewer/filetype/j2k) | JPEG 2000 代码流 (.j2k) 是使用小波压缩而非 DCT 压缩进行压缩的图像。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/j2k) |
| static readonly [JAVA](../../groupdocs.viewer/filetype/java) | Java 源代码文件 (.java) |
| static readonly [JLS](../../groupdocs.viewer/filetype/jls) | JPEG-LS (JLS) (.jls) |
| static readonly [JP2](../../groupdocs.viewer/filetype/jp2) | JPEG 2000 核心图像文件 (.jp2) 是图像编码系统和最先进的图像压缩标准。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/jp2) |
| static readonly [JPC](../../groupdocs.viewer/filetype/jpc) | JPEG 2000 代码流 (.jpc) |
| static readonly [JPEG](../../groupdocs.viewer/filetype/jpeg) | JPEG 图像 (.jpeg) 是一种使用有损压缩方法保存的图像格式。作为压缩的结果，输出图像是存储大小和图像质量之间的权衡。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/jpeg) |
| static readonly [JPF](../../groupdocs.viewer/filetype/jpf) | JPEG 2000 图像文件 (.jpf) |
| static readonly [JPG](../../groupdocs.viewer/filetype/jpg) | JPEG 图像 (.jpg) 是一种使用有损压缩方法保存的图像格式。作为压缩的结果，输出图像是存储大小和图像质量之间的权衡。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/jpeg) |
| static readonly [JPM](../../groupdocs.viewer/filetype/jpm) | JPEG 2000 图像文件 (.jpm) |
| static readonly [JPX](../../groupdocs.viewer/filetype/jpx) | JPEG 2000 图像文件 (.jpx) |
| static readonly [JS](../../groupdocs.viewer/filetype/js) | JavaScript 文件 (.js) |
| static readonly [JSON](../../groupdocs.viewer/filetype/json) | JavaScript 对象表示法文件 (.json) |
| static readonly [LESS](../../groupdocs.viewer/filetype/less) | LESS 样式表 (.less) |
| static readonly [LOG](../../groupdocs.viewer/filetype/log) | 日志文件 (.log) |
| static readonly [M](../../groupdocs.viewer/filetype/m) | Objective-C 实现文件 (.m) |
| static readonly [MAKE](../../groupdocs.viewer/filetype/make) | Xcode Makefile 脚本 (.make) |
| static readonly [MBOX](../../groupdocs.viewer/filetype/mbox) | 电子邮件邮箱文件 (.mbox) 了解有关此文件格式的更多信息[这里](https://fileinfo.com/extension/mbox) |
| static readonly [MD](../../groupdocs.viewer/filetype/md) | Markdown 文档文件 (.md) |
| static readonly [MHT](../../groupdocs.viewer/filetype/mht) | MHTML 网络存档 (.mht) |
| static readonly [MHTML](../../groupdocs.viewer/filetype/mhtml) | MIME HTML 文件 (.mhtml) |
| static readonly [ML](../../groupdocs.viewer/filetype/ml) | 机器学习源代码文件 (.ml) |
| static readonly [MM](../../groupdocs.viewer/filetype/mm) | Objective-C++ 源文件 (.mm) |
| static readonly [MOBI](../../groupdocs.viewer/filetype/mobi) | Mobipocket 电子书 (.mobi) 是使用最广泛的电子书文件格式之一。该格式是对旧 OEB（开放电子书格式）格式的增强，并用作 Mobipocket Reader 的专有格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/ebook/mobi) |
| static readonly [MPP](../../groupdocs.viewer/filetype/mpp) | Microsoft Project 文件 (.mpp) 是 Microsoft Project 数据文件，以集成方式存储与项目管理相关的信息。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/project-management/mpp) |
| static readonly [MPT](../../groupdocs.viewer/filetype/mpt) | Microsoft 项目模板 (.mpt) 包含基本信息和结构以及用于创建 .MPP 文件的文档设置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/project-management/mpt) |
| static readonly [MPX](../../groupdocs.viewer/filetype/mpx) | Microsoft Project Exchange 文件 (.mpx) 是一种 ASCII 文件格式，用于在 Microsoft Project (MSP) 和其他支持 MPX 文件格式的应用程序（例如 Primavera Project Planner、Sciforma 和 Timerline Precision Estimating）之间传输项目信息。 了解更多信息这种文件格式[这里](https://wiki.fileformat.com/project-management/mpx) |
| static readonly [MSG](../../groupdocs.viewer/filetype/msg) | Outlook 邮件消息 (.msg) 是 Microsoft Outlook 和 Exchange 用于存储电子邮件、联系人、约会或其他任务的文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/email/msg) |
| static readonly [NSF](../../groupdocs.viewer/filetype/nsf) | Lotus Notes 数据库 (.nsf) 了解有关此文件格式的更多信息[这里](https://fileinfo.com/extension/nsf) |
| static readonly [NUMBERS](../../groupdocs.viewer/filetype/numbers) | Apple 数字表示像二进制文件格式一样的 Excel。此类文件可以由 Apple 号码应用程序创建。 了解有关此文件格式的更多信息[这里](https://fileinfo.com/extension/numbers) |
| static readonly [OBJ](../../groupdocs.viewer/filetype/obj) | Wavefront 3D Object File (.obj) 是 Wavefront Technologies 推出的 3D 图像文件 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/3d/obj/). |
| static readonly [ODG](../../groupdocs.viewer/filetype/odg) | OpenDocument 图形文件 (.odg) 由 Apache OpenOffice 的 Draw 应用程序用于将绘图元素存储为矢量图像。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/odg) |
| static readonly [ODP](../../groupdocs.viewer/filetype/odp) | OpenDocument Presentation (.odp) 表示 OpenOffice.org 在 OASISOpen 标准中使用的演示文稿文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/odp) |
| static readonly [ODS](../../groupdocs.viewer/filetype/ods) | OpenDocument 电子表格 (.ods) 代表用户可编辑的 OpenDocument 电子表格文档格式。数据以行和列的形式存储在 ODF 文件中。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/ods) |
| static readonly [ODT](../../groupdocs.viewer/filetype/odt) | OpenDocument 文本文档 (.odt) 是使用基于 OpenDocument 文本文件格式的文字处理应用程序创建的文档类型。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/odt) |
| static readonly [ONE](../../groupdocs.viewer/filetype/one) | OneNote 文档 (.one) 由 Microsoft OneNote 应用程序创建。 OneNote 让您可以使用该应用程序收集信息，就像您使用草稿本做笔记一样。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/note-taking/one) |
| static readonly [OST](../../groupdocs.viewer/filetype/ost) | Outlook 脱机数据文件 (.ost) 表示在使用 Microsoft Outlook 向 Exchange Server 注册后，用户在本地计算机上处于脱机模式的邮箱数据。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/email/ost) |
| static readonly [OTG](../../groupdocs.viewer/filetype/otg) | OpenDocument 图形模板 (.otg) |
| static readonly [OTP](../../groupdocs.viewer/filetype/otp) | OpenDocument 演示模板 (.otp) 表示应用程序以 OASIS OpenDocument 标准格式创建的演示模板文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/otp) |
| static readonly [OTS](../../groupdocs.viewer/filetype/ots) | OpenDocument 电子表格模板 (.ots) |
| static readonly [OTT](../../groupdocs.viewer/filetype/ott) | OpenDocument 文档模板 (.ott) 表示由应用程序生成的符合 OASIS 的 OpenDocument 标准格式的模板文档。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/ott) |
| static readonly [OXPS](../../groupdocs.viewer/filetype/oxps) | OpenXPS 文件 (.oxps) |
| static readonly [PCL](../../groupdocs.viewer/filetype/pcl) | 打印机命令语言文档 (.pcl) |
| static readonly [PDF](../../groupdocs.viewer/filetype/pdf) | 便携式文档格式文件 (.pdf) 是 Adobe 在 1990 年代创建的一种文档。这种文件格式的目的是引入一种标准，以一种独立于应用程序软件、硬件和操作系统的格式来表示文档和其他参考资料。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/view/pdf) |
| static readonly [PHP](../../groupdocs.viewer/filetype/php) | PHP 源代码文件 (.php) |
| static readonly [PL](../../groupdocs.viewer/filetype/pl) | Perl 脚本 (.pl) |
| static readonly [PLT](../../groupdocs.viewer/filetype/plt) | PLT (HPGL) (.plt) 是 Autodesk, Inc. 推出的基于矢量的绘图仪文件，包含特定 CAD 文件的信息。绘图细节需要生产的准确性和精度，PLT 文件的使用保证了这一点，因为所有图像都是使用线而不是点打印的。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/cad/plt). |
| static readonly [PNG](../../groupdocs.viewer/filetype/png) | 便携式网络图形 (.png) 是一种使用无损压缩的光栅图像文件格式。此文件格式是为替代图形交换格式 (GIF) 而创建的，没有版权限制。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/png) |
| static readonly [POT](../../groupdocs.viewer/filetype/pot) | PowerPoint 模板 (.pot) 表示由 PowerPoint 97-2003 版本创建的 Microsoft PowerPoint 模板文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/pot) |
| static readonly [POTM](../../groupdocs.viewer/filetype/potm) | PowerPoint Open XML 启用宏的演示模板 (.potm) 是支持宏的 Microsoft PowerPoint 模板文件。 POTM 文件是使用 PowerPoint 2007 或更高版本创建的，包含可用于创建更多演示文稿文件的默认设置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/potm) |
| static readonly [POTX](../../groupdocs.viewer/filetype/potx) | PowerPoint Open XML 演示文稿模板 (.potx) 表示使用 Microsoft PowerPoint 2007 及更高版本创建的 Microsoft PowerPoint 模板演示文稿。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/potx) |
| static readonly [PPS](../../groupdocs.viewer/filetype/pps) | PowerPoint 幻灯片放映 (.pps) 是使用 Microsoft PowerPoint 创建的，用于放映幻灯片。 Microsoft PowerPoint 97-2003 支持 PPS 文件读取和创建。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/pps) |
| static readonly [PPSM](../../groupdocs.viewer/filetype/ppsm) | PowerPoint Open XML 启用宏的幻灯片 (.ppsm) 表示使用 Microsoft PowerPoint 2007 或更高版本创建的启用宏的幻灯片放映文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/ppsm) |
| static readonly [PPSX](../../groupdocs.viewer/filetype/ppsx) | PowerPoint Open XML 幻灯片放映 (.ppsx) 文件是使用 Microsoft PowerPoint 2007 及更高版本创建的，用于放映幻灯片。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/ppsx) |
| static readonly [PPT](../../groupdocs.viewer/filetype/ppt) | PowerPoint 演示文稿 (.ppt) 代表 PowerPoint 文件，该文件由一组幻灯片组成，用于显示为 SlideShow。它指定 Microsoft PowerPoint 97-2003 使用的二进制文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/ppt) |
| static readonly [PPTM](../../groupdocs.viewer/filetype/pptm) | PowerPoint Open XML 启用宏的演示文稿是使用 Microsoft PowerPoint 2007 或更高版本创建的启用宏的演示文稿文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/pptm) |
| static readonly [PPTX](../../groupdocs.viewer/filetype/pptx) | PowerPoint Open XML 演示文稿 (.pptx) 是使用流行的 Microsoft PowerPoint 应用程序创建的演示文稿文件。与以前版本的二进制演示文稿文件格式 PPT 不同，PPTX 格式基于 Microsoft PowerPoint 开放 XML 演示文稿文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/pptx) |
| static readonly [PROPERTIES](../../groupdocs.viewer/filetype/properties) | Java 属性文件 (.properties) |
| static readonly [PS](../../groupdocs.viewer/filetype/ps) | PostScript 文件 (.ps) |
| static readonly [PS1](../../groupdocs.viewer/filetype/ps1) | PowerShell 脚本文件 (.ps1) Windows PowerShell Cmdlet 文件的一种文件格式。 了解有关此文件格式的更多信息[这里](https://fileinfo.com/extension/ps1) |
| static readonly [PSB](../../groupdocs.viewer/filetype/psb) | Photoshop 大型文档格式 (.psb) 表示用于图形设计和开发的 Photoshop 大型文档格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/psb) |
| static readonly [PSD](../../groupdocs.viewer/filetype/psd) | Adobe Photoshop 文档 (.psd) 代表 Adobe Photoshop 用于图形设计和开发的本机文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/psd) |
| static readonly [PSD1](../../groupdocs.viewer/filetype/psd1) | PowerShell 脚本模块清单 (.psd1) PowerShell 模块清单脚本的文件格式。 了解有关此文件格式的更多信息[这里](https://fileinfo.com/extension/psd1) |
| static readonly [PSM1](../../groupdocs.viewer/filetype/psm1) | PowerShell 脚本模块 (.psm1) PowerShell 模块脚本的文件格式。 了解有关此文件格式的更多信息[这里](https://fileinfo.com/extension/psm1) |
| static readonly [PST](../../groupdocs.viewer/filetype/pst) | Outlook 个人信息存储文件 (.pst) 表示存储各种用户信息的 Outlook 个人存储文件（也称为个人存储表）。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/email/pst) |
| static readonly [PY](../../groupdocs.viewer/filetype/py) | Python 脚本 (.py) |
| static readonly [RAR](../../groupdocs.viewer/filetype/rar) | Roshal ARchive (.rar) 是使用 RAR (WINRAR) 压缩方法生成的压缩文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/compression/rar) |
| static readonly [RB](../../groupdocs.viewer/filetype/rb) | Ruby 源代码 (.rb) |
| static readonly [RST](../../groupdocs.viewer/filetype/rst) | 重组文本文件 (.rst) |
| static readonly [RTF](../../groupdocs.viewer/filetype/rtf) | Rich Text Format File (.rtf) 表示一种编码格式化文本和图形以在应用程序中使用的方法。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/rtf) |
| static readonly [SASS](../../groupdocs.viewer/filetype/sass) | 语法上很棒的样式表文件 (.sass) |
| static readonly [SCALA](../../groupdocs.viewer/filetype/scala) | Scala 源代码文件 (.scala) |
| static readonly [SCM](../../groupdocs.viewer/filetype/scm) | 方案源代码文件 (.scm) |
| static readonly [SCRIPT](../../groupdocs.viewer/filetype/script) | 通用脚本文件 (.script) |
| static readonly [SevenZip](../../groupdocs.viewer/filetype/sevenzip) | 7Zip (.7z, .7zip) 是免费的开源压缩器，采用 LZMA 和 LZMA2 压缩。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/compression/7z/). |
| static readonly [SH](../../groupdocs.viewer/filetype/sh) | Bash Shell 脚本 (.sh) |
| static readonly [SML](../../groupdocs.viewer/filetype/sml) | 标准 ML 源代码文件 (.sml) |
| static readonly [SQL](../../groupdocs.viewer/filetype/sql) | 结构化查询语言数据文件 (.sql) |
| static readonly [STL](../../groupdocs.viewer/filetype/stl) | Stereolithography 文件 (.stl) 是一种可互换的文件格式，表示 3 维表面几何形状。该文件格式可用于多个领域，例如快速原型制作、3D 打印和计算机辅助制造。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/cad/stl). |
| static readonly [SVG](../../groupdocs.viewer/filetype/svg) | 可缩放矢量图形文件 (.svg) 是一种标量矢量图形文件，它使用基于 XML 的文本格式来描述图像的外观。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/page-description-language/svg) |
| static readonly [SVGZ](../../groupdocs.viewer/filetype/svgz) | 可缩放矢量图形文件 (.svgz) 是一种标量矢量图形文件，它使用基于 XML 的文本格式，由 GZIP 压缩以描述图像的外观。 了解有关此文件格式的更多信息[这里](https://fileinfo.com/extension/svgz) |
| static readonly [SXC](../../groupdocs.viewer/filetype/sxc) | StarSuite Calc 电子表格 (.sxc) |
| static readonly [TAR](../../groupdocs.viewer/filetype/tar) | 统一 Unix 文件存档 (.tar) 是使用基于 Unix 的实用程序创建的存档，用于收集一个或多个文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/compression/tar) |
| static readonly [TARGZ](../../groupdocs.viewer/filetype/targz) | 统一 Unix 文件存档（.tgz、.tar.gz）是使用基于 Unix 的实用程序创建的存档，用于收集一个或多个文件。 了解有关此文件格式的更多信息[这里](https://fileinfo.com/extension/tgz) |
| static readonly [TARXZ](../../groupdocs.viewer/filetype/tarxz) | 统一 Unix 文件存档（.txz、.tar.xz）是使用基于 Unix 的实用程序创建的存档，用于收集一个或多个文件。 了解有关此文件格式的更多信息[这里](https://fileinfo.com/extension/txz) |
| static readonly [TEX](../../groupdocs.viewer/filetype/tex) | LaTeX 源文档 (.tex) 是一种包含编程和标记功能的语言，用于排版文档。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/page-description-language/tex) |
| static readonly [TGA](../../groupdocs.viewer/filetype/tga) | Truevision TGA（Truevision Advanced Raster Adapter - TARGA）用于存储由 TRUEVISION 开发的位图数字图像。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/tga) |
| static readonly [TGZ](../../groupdocs.viewer/filetype/tgz) | 统一 Unix 文件存档（.tgz、.tar.gz）是使用基于 Unix 的实用程序创建的存档，用于收集一个或多个文件。 了解有关此文件格式的更多信息[这里](https://fileinfo.com/extension/tgz) |
| static readonly [TIF](../../groupdocs.viewer/filetype/tif) | 标记图像文件 (.tif) 表示适用于符合此文件格式标准的各种设备的光栅图像。它能够在多个颜色空间中描述二值、灰度、调色板颜色和全色图像数据。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/tiff) |
| static readonly [TIFF](../../groupdocs.viewer/filetype/tiff) | 标记图像文件格式 (.tiff) 表示适用于符合此文件格式标准的各种设备的光栅图像。它能够在多个颜色空间中描述二值、灰度、调色板颜色和全色图像数据。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/tiff) |
| static readonly [TSV](../../groupdocs.viewer/filetype/tsv) | 制表符分隔值文件 (.tsv) 表示以纯文本格式的制表符分隔的数据。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/tsv) |
| static readonly [TXT](../../groupdocs.viewer/filetype/txt) | 纯文本文件 (.txt) 表示包含行形式的纯文本的文本文档。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/txt) |
| static readonly [TXZ](../../groupdocs.viewer/filetype/txz) | 统一 Unix 文件存档（.txz、.tar.xz）是使用基于 Unix 的实用程序创建的存档，用于收集一个或多个文件。 了解有关此文件格式的更多信息[这里](https://fileinfo.com/extension/txz) |
| static readonly [Unknown](../../groupdocs.viewer/filetype/unknown) | 代表未知文件类型。 |
| static readonly [VB](../../groupdocs.viewer/filetype/vb) | Visual Basic 项目项文件 (.vb) 是用 Visual Basic 语言创建的源代码文件，由 Microsoft 创建用于开发 .NET 应用程序。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/programming/vb) |
| static readonly [VCF](../../groupdocs.viewer/filetype/vcf) | vCard 文件 (.vcf) 是一种用于存储联系人信息的数字文件格式。该格式广泛用于流行信息交换应用程序之间的数据交换。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/email/vcf) |
| static readonly [VDW](../../groupdocs.viewer/filetype/vdw) | Visio Web 绘图 (.vdw) 表示指定呈现 Web 绘图所需的流和存储的文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/web/vdw). |
| static readonly [VDX](../../groupdocs.viewer/filetype/vdx) | Visio 绘图 XML 文件 (.vdx) 表示在 Microsoft Visio 中创建的任何绘图或图表，但以 XML 格式保存并具有 .VDX 扩展名。 Visio 绘图 XML 文件是在 Microsoft 开发的 Visio 软件中创建的。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vdx). |
| static readonly [VIM](../../groupdocs.viewer/filetype/vim) | Vim 设置文件 (.vim) |
| static readonly [VSD](../../groupdocs.viewer/filetype/vsd) | Visio 绘图文件 (.vsd) 是使用 Microsoft Visio 应用程序创建的绘图，用于表示各种图形对象以及这些对象之间的互连。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vsd). |
| static readonly [VSDM](../../groupdocs.viewer/filetype/vsdm) | Visio 宏启用绘图 (.vsdm) 是使用支持宏的 Microsoft Visio 应用程序创建的绘图文件。 VSDM 文件是类似于 VSDX 的 OPC/XML 绘图，但也提供了在文件打开时运行宏的功能。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vsdm). |
| static readonly [VSDX](../../groupdocs.viewer/filetype/vsdx) | Visio 绘图 (.vsdx) 表示从 Microsoft Office 2013 开始引入的 Microsoft Visio 文件格式。开发它是为了替换二进制文件格式 .VSD，它受早期版本的 Microsoft Visio 支持。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vsdx). |
| static readonly [VSS](../../groupdocs.viewer/filetype/vss) | Visio 模板文件 (.vss) 是使用 Microsoft Visio 2007 及更早版本创建的模板文件。模板文件提供可包含在 .VSD Visio 绘图中的绘图对象。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vss). |
| static readonly [VSSM](../../groupdocs.viewer/filetype/vssm) | Visio 启用宏的模板文件 (.vssm) 是支持宏的 Microsoft Visio 模板文件。 VSSM 文件打开后允许运行宏以在图表中实现所需的格式设置和形状放置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vssm). |
| static readonly [VSSX](../../groupdocs.viewer/filetype/vssx) | Visio 模板文件 (.vssx) 是使用 Microsoft Visio 2013 及更高版本创建的绘图模板。 VSSX 文件格式可以用 Visio 2013 及更高版本打开。 Visio 文件以表示各种绘图元素而闻名，例如形状集合、连接器、流程图、网络布局、UML 图、 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vssx). |
| static readonly [VST](../../groupdocs.viewer/filetype/vst) | Visio 绘图模板 (.vst) 是使用 Microsoft Visio 创建的矢量图像文件，可作为创建更多文件的模板。这些模板文件采用二进制文件格式，包含用于创建新 Visio 绘图的默认布局和设置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vst). |
| static readonly [VSTM](../../groupdocs.viewer/filetype/vstm) | Visio 启用宏的绘图模板 (.vstm) 是使用支持宏的 Microsoft Visio 创建的模板文件。与 VSDX 文件不同，从 VSTM 模板创建的文件可以运行在 Visual Basic for Applications (VBA) 代码中开发的宏。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vstm). |
| static readonly [VSTX](../../groupdocs.viewer/filetype/vstx) | Visio 绘图模板 (.vstx) 是使用 Microsoft Visio 2013 及更高版本创建的绘图模板文件。这些 VSTX 文件为创建 Visio 绘图提供起点，保存为 .VSDX 文件，具有默认布局和设置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vstx). |
| static readonly [VSX](../../groupdocs.viewer/filetype/vsx) | Visio Stencil XML 文件 (.vsx) 是指由绘图和形状组成的模板，用于在 Microsoft Visio 中创建图表。 VSX 文件以 XML 文件格式保存并在 Visio 2013 之前一直受支持。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vsx). |
| static readonly [VTX](../../groupdocs.viewer/filetype/vtx) | Visio 模板 XML 文件 (.vtx) 是一种以 XML 文件格式保存到光盘的 Microsoft Visio 绘图模板。该模板旨在提供具有基本设置的文件，可用于创建具有相同设置的多个 Visio 文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/vtx). |
| static readonly [WEBP](../../groupdocs.viewer/filetype/webp) | WebP 图像 (.webp) 是一种基于无损和有损压缩的现代光栅网络图像文件格式。它提供相同的图像质量，同时显着减小图像尺寸。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/webp) |
| static readonly [WMF](../../groupdocs.viewer/filetype/wmf) | Windows 图元文件 (.wmf) 表示用于存储矢量和位图格式图像数据的 Microsoft Windows 图元文件 (WMF)。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/wmf) |
| static readonly [WMZ](../../groupdocs.viewer/filetype/wmz) | Compressed Windows Metafile (.wmz) 表示在 GZIP archvive 中压缩的 Microsoft Windows 图元文件 (WMF) - 用于存储矢量和位图格式图像数据。 了解有关此文件格式的更多信息[这里](https://fileinfo.com/extension/wmz#compressed_windows_metafile) |
| static readonly [XLAM](../../groupdocs.viewer/filetype/xlam) | Microsoft Excel 加载项 (.xlam) |
| static readonly [XLS](../../groupdocs.viewer/filetype/xls) | Excel 电子表格 (.xls) 表示 Excel 二进制文件格式。此类文件可以由 Microsoft Excel 以及其他类似的电子表格程序（例如 OpenOffice Calc 或 Apple Numbers）创建。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xls) |
| static readonly [XLSB](../../groupdocs.viewer/filetype/xlsb) | Excel 二进制电子表格 (.xlsb) 指定 Excel 二进制文件格式，它是指定 Excel 工作簿内容的记录和结构的集合。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xlsb) |
| static readonly [XLSM](../../groupdocs.viewer/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) 是一种支持宏的 Spreasheet 文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xlsm) |
| static readonly [XLSX](../../groupdocs.viewer/filetype/xlsx) | Microsoft Excel Open XML 电子表格 (.xlsx) 是 Microsoft 随 Microsoft Office 2007 发布而引入的一种众所周知的 Microsoft Excel 文档格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xlsx) |
| static readonly [XLT](../../groupdocs.viewer/filetype/xlt) | Microsoft Excel 模板 (.xlt) 是使用 Microsoft Excel 创建的模板文件，Microsoft Excel 是一个电子表格应用程序，是 Microsoft Office 套件的一部分。 Microsoft Office 97-2003 支持创建新的 XLT 文件以及打开这些文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xlt) |
| static readonly [XLTM](../../groupdocs.viewer/filetype/xltm) | Microsoft Excel 启用宏的模板 (.xltm) 表示由 Microsoft Excel 作为启用宏的模板文件生成的文件。 XLTM 文件在结构上类似于 XLTX，只是后者不支持使用宏创建模板文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xltm) |
| static readonly [XLTX](../../groupdocs.viewer/filetype/xltx) | Excel Open XML 电子表格模板 (.xltx) 表示基于 Office OpenXML 文件格式规范的 Microsoft Excel 模板。它用于创建标准模板文件，该文件可用于生成 XLSX 文件，这些文件显示与 XLTX 文件中指定的设置相同的设置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xltx) |
| static readonly [XML](../../groupdocs.viewer/filetype/xml) | XML 文件 (.xml) |
| static readonly [XPS](../../groupdocs.viewer/filetype/xps) | XML 纸张规格文件 (.xps) 表示基于 Microsoft 创建的 XML 纸张规格的页面布局文件。此格式由 Microsoft 开发，用于替代 EMF 文件格式，类似于 PDF 文件格式，但在文档的布局、外观和打印信息中使用 XML。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/page-description-language/xps) |
| static readonly [XZ](../../groupdocs.viewer/filetype/xz) | XZ 文件 (.xz) 是基于 LZMA 算法的高比率压缩算法压缩的存档。 了解有关此文件格式的更多信息[这里](https://fileinfo.com/extension/xz) |
| static readonly [YAML](../../groupdocs.viewer/filetype/yaml) | YAML 文档 (.yaml) |
| static readonly [ZIP](../../groupdocs.viewer/filetype/zip) | Zipped File (.zip) 表示可以保存一个或多个文件或目录的档案。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/compression/zip) |

### 也可以看看

* 命名空间 [GroupDocs.Viewer](../../groupdocs.viewer)
* 部件 [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
