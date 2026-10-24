---
title: "FileType"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "表示文件类型。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.viewer/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, com.groupdocs.viewer.caching.Cacheable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>, Cacheable
```

表示文件类型。提供获取 GroupDocs.Viewer 组件支持的所有文件类型列表的方法。


FileType 枚举提供表示 GroupDocs.Viewer 组件支持的不同文件类型的常量。
您可以使用此枚举中的方法获取所有支持的文件类型列表，或检查特定文件类型是否受支持。


示例用法：

````

 // Try to detect file type using stream
 final FileType fileTypeFromStream = FileType.fromStream(new FileInputStream("document.pdf"));
 // Detect file type by extension
 final FileType fileTypeFromExtension = FileType.fromExtension(".png");
 // Iterate all supported file types
 for (FileType supportedFileType : FileType.getSupportedFileTypes()) {
     System.out.println("File type: " + supportedFileType);
 }
 final LoadOptions loadOptions = new LoadOptions(fileTypeFromExtension);
 // Usage of loadOptions
 
````


## 字段

| 字段 | 描述 |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | 表示未知的文件类型。 |
|
|  | [ZIP](#ZIP) | 表示可容纳一个或多个文件或目录的压缩文件（.zip）。 |
|
|  | [TAR](#TAR) | 表示用于收集一个或多个文件的合并 Unix 文件归档（.tar）。 |
|
|  | [XZ](#XZ) | 表示使用基于 LZMA 算法的高比率压缩算法压缩的 XZ 文件（.xz）。 |
|
|  | [TXZ](#TXZ) | 表示一个为收集一个或多个文件而创建的合并 Unix 文件归档（.txz，.tar.xz）。 |
|
|  | [TARXZ](#TARXZ) | 表示一个为收集一个或多个文件而创建的合并 Unix 文件归档（.txz，.tar.xz）。 |
|
|  | [TGZ](#TGZ) | 表示一个为收集一个或多个文件而创建的合并 Unix 文件归档（.tgz，.tar.gz）。 |
|
|  | [TARGZ](#TARGZ) | 表示一个为收集一个或多个文件而创建的合并 Unix 文件归档（.tgz，.tar.gz）。 |
|
|  | [BZ_2](#BZ-2) | 表示使用 BZIP2 开源压缩方法生成的 Bzip2 压缩文件（.bz2）。 |
|
|  | [RAR](#RAR) | 表示使用 RAR（WINRAR 版本 4）压缩方法生成的 Roshal Archive（.rar）压缩文件。 |
|
|  | [GZ](#GZ) | 表示使用 gzip 压缩应用程序创建的 Gnu Zipped File（.gz）压缩文件。 |
|
|  | [GZIP](#GZIP) | 表示作为替代 Unix 系统中 Compress 程序的免费工具引入的 Gnu Zipped File（.gzip）压缩文件。 |
|
|  | [SEVEN_ZIP](#SEVEN-ZIP) | 表示 7Zip（.7z，.7zip）文件，它是一种具有 LZMA 和 LZMA2 压缩的免费开源归档工具。 |
|
|  | [CPIO](#CPIO) | Cpio 是一种通用文件归档实用程序及其关联的文件格式。 |
|
|  | [ZSTANDARD](#ZSTANDARD) | ZST 文件是一种使用 Zstandard（zstd）压缩算法生成的压缩文件。 |
|
|  | [TZST](#TZST) | TZST 文件（.tar.zst，.tzst）是 Zstandard 归档（ZST），内部包含使用 Unix 基础实用程序为收集一个或多个文件而创建的合并 Unix 文件归档（Tar）。 |
|
|  | [TAR_ZST](#TAR-ZST) | TZST 文件（.tar.zst，.tzst）是 Zstandard 归档（ZST），内部包含使用 Unix 基础实用程序为收集一个或多个文件而创建的合并 Unix 文件归档（Tar）。 |
|
|  | [ISO](#ISO) | ISO 光盘映像是一种未压缩的归档磁盘映像文件，基于 ISO-9660 标准，表示光盘（如 CD 或 DVD）上完整数据的内容。 |
|
|  | [LHA](#LHA) | LHA 或 LZH 是一种免费压缩实用程序及其关联的文件格式。 |
|
|  | [CAB](#CAB) | Cabinet（或 CAB）是 Microsoft Windows 的归档文件格式。 |
|
|  | [DXF](#DXF) | 表示一种绘图交换格式文件（.dxf），它是 AutoCAD 绘图文件的标记数据表示。 |
|
|  | [DWG](#DWG) | 表示一种 AutoCAD 绘图数据库文件（.dwg），它是用于存储 2D 和 3D 设计数据的专有二进制文件。 |
|
|  | [DWT](#DWT) | 表示一种 AutoCAD 绘图模板（.dwt），它是用于创建可保存为 DWG 文件的绘图的起始模板文件。 |
|
|  | [STL](#STL) | 表示一种立体光刻文件（.stl），它是一种可互换的文件格式，用于表示三维表面几何形状。 |
|
|  | [IFC](#IFC) | 表示一种行业基础类文件（.ifc），它是一种建立建筑对象及其属性进出口国际标准的文件格式。 |
|
|  | [DWF](#DWF) | 表示一种设计网络格式文件（.dwf），它是一种用于查看、审阅或打印 2D/3D 绘图的压缩文件格式。 |
|
|  | [FBX](#FBX) | 表示一种 Autodesk FBX 交换文件（FilmBoX）（.fbx），它是一种 3D 模型格式。 |
|
|  | [DWFX](#DWFX) | 表示一种设计网络格式文件 XPS（.dwfx），它是一种用于将 2D/3D 绘图以 XPS 文档形式查看、审阅或打印的压缩格式。 |
|
|  | [DGN](#DGN) | 表示一种 MicroStation 设计文件（.dgn），它是由 MicroStation、Intergraph Interactive Graphics Design System 等 CAD 应用程序创建和支持的绘图。 |
|
|  | [PLT](#PLT) | 表示一种 PLT（HPGL）文件（.plt），它是 Autodesk, Inc. 推出的基于矢量的绘图仪文件。 |
|
|  | [CF2](#CF2) | 表示一种通用文件格式文件（.cf2）。 |
|
|  | [OBJ](#OBJ) | 表示一种 Wavefront 3D 对象文件（.obj），它是 Wavefront Technologies 推出的 3D 图像文件。 |
|
|  | [HPG](#HPG) | 表示一个 PLT (HPGL) 文件 (.hpg)。 |
|
|  | [IGS](#IGS) | 表示一个初始图形交换规范 (IGES) 文件 (.igs)。 |
|
|  | [VSD](#VSD) | 表示一个 Visio 绘图文件 (.vsd)，这些绘图是使用 Microsoft Visio 应用程序创建的，用于表示各种图形对象及其相互连接。 |
|
|  | [VSDX](#VSDX) | 表示一个 Visio 绘图文件 (.vsdx)，它代表自 Microsoft Office 2013 起引入的 Microsoft Visio 文件格式。 |
|
|  | [VSS](#VSS) | 表示一个 Visio 模板文件 (.vss)，这些模板文件是使用 Microsoft Visio 2007 及更早版本创建的。 |
|
|  | [VSSX](#VSSX) | 表示一个 Visio 模板文件 (.vssx)，这些绘图模板是使用 Microsoft Visio 2013 及以上版本创建的。 |
|
|  | [VSDM](#VSDM) | 表示一个 Visio 启用宏的绘图 (.vsdm)，这些绘图文件是使用支持宏的 Microsoft Visio 应用程序创建的。 |
|
|  | [VST](#VST) | 表示一个 Visio 绘图模板 (.vst)，这些是使用 Microsoft Visio 创建的矢量图像文件。 |
|
|  | [VSTX](#VSTX) | 表示一个 Visio 绘图模板 (.vstx)，这些绘图模板文件是使用 Microsoft Visio 2013 及以上版本创建的。 |
|
|  | [VSTM](#VSTM) | 表示一个 Visio 启用宏的绘图模板 (.vstm)，这些模板文件是使用支持宏的 Microsoft Visio 创建的。 |
|
|  | [VSSM](#VSSM) | 表示一个 Visio 启用宏的模板文件 (.vssm)，这些是支持宏的 Microsoft Visio 模板文件。 |
|
|  | [VSX](#VSX) | 表示一个 Visio 模板 XML 文件 (.vsx)，它指的是用于在 Microsoft Visio 中创建图表的包含绘图和形状的模板。 |
|
|  | [VTX](#VTX) | 表示一个 Visio 模板 XML 文件 (.vtx)，它是以 XML 文件格式保存到磁盘的 Microsoft Visio 绘图模板。 |
|
|  | [VDW](#VDW) | 表示一个 Visio Web 绘图 (.vdw)，它指定了渲染 Web 绘图所需的流和存储。 |
|
|  | [VDX](#VDX) | 表示一个 Visio 绘图 XML 文件 (.vdx)，它代表任何在 Microsoft Visio 中创建但以 .VDX 扩展名的 XML 格式保存的绘图或图表。 |
|
|  | [EPUB](#EPUB) | 表示一个 Open eBook 文件 (.epub)，它是一种为出版商和消费者提供标准数字出版格式的电子书文件格式。 |
|
|  | [MOBI](#MOBI) | 表示一个 Mobipocket 电子书 (.mobi)，它是最广泛使用的电子书文件格式之一。 |
|
|  | [AZW_3](#AZW-3) | Amazon Kindle Format 8 (KF8) 电子书是为 Amazon Kindle 设备开发的数字文件格式。 |
|
|  | [MSG](#MSG) | 表示一个 Outlook 邮件信息 (.msg)，它是 Microsoft Outlook 和 Exchange 用于存储电子邮件、联系人、约会或其他任务的文件格式。 |
|
|  | [EML](#EML) | 表示一个电子邮件信息 (.eml)，它代表使用 Outlook 和其他相关应用程序保存的电子邮件。 |
|
|  | [EMLX](#EMLX) | 表示一个 Apple 邮件信息 (.emlx)，它由 Apple 实现和开发。 |
|
|  | [PST](#PST) | 表示一个 Outlook 个人信息存储文件 (.pst)，它代表 Outlook 个人存储文件（亦称个人存储表），用于存储各种用户信息。 |
|
|  | [OST](#OST) | 表示一个 Outlook 离线数据文件 (.ost)，它代表用户在使用 Microsoft Outlook 注册 Exchange Server 后，在本地机器上离线模式下的邮箱数据。 |
|
|  | [TIF](#TIF) | 表示一个 Tagged Image 文件 (.tif)，它代表用于符合此文件格式标准的各种设备上的光栅图像。 |
|
|  | [TIFF](#TIFF) | 表示一个 Tagged Image 文件格式 (.tiff)，它代表用于符合此文件格式标准的各种设备上的光栅图像。 |
|
|  | [JPG](#JPG) | 表示 JPEG 图像（.jpg），这是一种使用有损压缩方法保存的图像格式。 |
|
|  | [JPEG](#JPEG) | 表示 JPEG 图像（.jpeg），这是一种使用有损压缩方法保存的图像格式。 |
|
|  | [JFIF](#JFIF) | JPEG 文件交换格式（.jfif）是一种为在平台之间快速交换而开发的图像。 |
|
|  | [PNG](#PNG) | 表示便携式网络图形（.png），这是一种使用无损压缩的栅格图像文件格式。 |
|
|  | [GIF](#GIF) | 表示图形交换格式文件（.gif），这是一种高度压缩的图像。 |
|
|  | [APNG](#APNG) | 表示动画便携式网络图形（.apng），这是 PNG 格式的扩展，支持动画。 |
|
|  | [BMP](#BMP) | 表示位图图像文件（.bmp），用于存储位图数字图像。 |
|
|  | [ICO](#ICO) | 表示图标文件（.ico），这是一种在 Microsoft Windows 上用作应用程序图标的图像文件类型。 |
|
|  | [TGA](#TGA) | 表示 Truevision TGA（TARGA）文件，这是一种由 TRUEVISION 开发用于存储位图数字图像的文件。 |
|
|  | [JP_2](#JP-2) | 表示 JPEG 2000 核心图像文件（.jp2），这是一种图像编码系统和最先进的图像压缩标准。 |
|
|  | [JPF](#JPF) | 表示 JPEG 2000 图像文件（.jpf）。 |
|
|  | [JPX](#JPX) | 表示 JPEG 2000 图像文件（.jpx）。 |
|
|  | [JPM](#JPM) | 表示 JPEG 2000 图像文件（.jpm）。 |
|
|  | [J2C](#J2C) | 表示 JPEG 2000 代码输入流（.j2c）。 |
|
|  | [J2K](#J2K) | 表示 JPEG 2000 代码流（.j2k），这是一种使用小波压缩而非 DCT 压缩的图像。 |
|
|  | [JPC](#JPC) | 表示 JPEG 2000 代码流（.jpc）。 |
|
|  | [JLS](#JLS) | 表示 JPEG-LS（JLS）文件（.jls）。 |
|
|  | [DIB](#DIB) | 表示设备无关位图文件（.dib）。 |
|
|  | [WMF](#WMF) | 表示 Windows 元文件（.wmf），用于存储矢量以及位图格式图像数据的 Microsoft Windows 元文件（WMF）。 |
|
|  | [WMZ](#WMZ) | 表示压缩的 Windows 元文件（.wmz），这是经过 GZIP 压缩的 Microsoft Windows 元文件（WMF），用于存储矢量以及位图格式图像数据。 |
|
|  | [EMF](#EMF) | 表示增强型 Windows 元文件（.emf），用于设备无关地表示图形图像。 |
|
|  | [EMZ](#EMZ) | 表示 Windows 压缩的增强型元文件（.emz），这是通过 GZIP 压缩的设备无关图形图像。 |
|
|  | [WEBP](#WEBP) | 表示 WebP 图像（.webp），这是一种基于无损和有损压缩的现代栅格网络图像文件格式。 |
|
|  | [DNG](#DNG) | 表示 Digital Negative 规范（.dng），这是一种用于存储原始文件的数码相机图像格式。 |
|
|  | [CDR](#CDR) | 表示 CorelDraw 矢量图形绘图（.cdr），这是一种使用 CorelDRAW 原生创建的矢量绘图图像文件，用于存储数字编码和压缩的图像。 |
|
|  | [CMX](#CMX) | 表示 Corel Exchange (.cmx)，它是一种可能包含矢量图形以及位图图形的绘图图像文件。 |
|
|  | [DJVU](#DJVU) | 表示 DjVu Image (.djvu)，它是一种用于扫描文档和书籍的图形文件格式，尤其适用于包含文本、图纸、图像和照片组合的文档。 |
|
|  | [CGM](#CGM) | 表示 Computer Graphics Metafile (.cgm)，它是一种免费、平台无关的国际标准元文件格式，用于存储和交换矢量图形（2D）、光栅图形和文本。 |
|
|  | [PCL](#PCL) | 表示 Printer Command Language 文档 (.pcl)。 |
|
|  | [PSD](#PSD) | 表示 Adobe Photoshop Document (.psd)，它是 Adobe Photoshop 的原生文件格式，用于图形设计和开发。 |
|
|  | [PSB](#PSB) | 表示 Photoshop Large Document Format (.psb)，它用于 Adobe Photoshop 中的图形设计和开发。 |
|
|  | [DCM](#DCM) | 表示 DICOM Image (.dcm)，它是一种存储患者医学信息（如 MRI、CT 扫描和超声图像）的数字图像。 |
|
|  | [PS](#PS) | 表示 PostScript 文件 (.ps)。 |
|
|  | [EPS](#EPS) | 表示 Encapsulated PostScript 文件 (.eps)，它描述了一个定义单页外观的 Encapsulated PostScript 语言程序。 |
|
|  | [ODG](#ODG) | 表示 OpenDocument Graphic 文件 (.odg)，它被 Apache OpenOffice 的 Draw 应用程序用于将绘图元素存储为矢量图像。 |
|
|  | [FODG](#FODG) | 表示 Flat XML ODF 模板 (.fodg)，它被 Apache OpenOffice 的 Draw 应用程序用于将绘图元素存储为矢量图像。 |
|
|  | [SVG](#SVG) | 表示 Scalable Vector Graphics 文件 (.svg)，它是一种使用基于 XML 的文本格式来描述图像外观的可缩放矢量图形文件。 |
|
|  | [SVGZ](#SVGZ) | 表示 Compressed Scalable Vector Graphics 文件 (.svgz)，它是一种使用基于 XML 的文本格式并经 GZIP 压缩的可缩放矢量图形文件，用于描述图像的外观。 |
|
|  | [OTG](#OTG) | 表示 OpenDocument Graphic 模板 (.otg)。 |
|
|  | [HTM](#HTM) | 表示 Hypertext Markup Language 文件 (.htm)，它是用于在浏览器中显示的网页的扩展名。 |
|
|  | [HTML](#HTML) | 表示 Hypertext Markup Language 文件 (.html)，它是用于在浏览器中显示的网页的扩展名。 |
|
|  | [MHT](#MHT) | 表示 MHTML Web 存档 (.mht)。 |
|
|  | [NSF](#NSF) | 表示 Lotus Notes 数据库 (.nsf)。 |
|
|  | [MBOX](#MBOX) | 表示 Email Mailbox 文件 (.mbox)。 |
|
|  | [MHTML](#MHTML) | 表示 MIME HTML 文件 (.mhtml)。 |
|
|  | [XML](#XML) | 表示 XML 文件 (.xml)。 |
|
|  | [ONE](#ONE) | 表示 OneNote 文档 (.one)，由 Microsoft OneNote 应用程序创建。 |
|
|  | [PDF](#PDF) | 表示 Portable Document Format 文件 (.pdf)，它是一种由 Adobe 在 1990 年代创建的文档类型。 |
|
|  | [XPS](#XPS) | 表示 XML Paper Specification 文件 (.xps)，它是基于 Microsoft 创建的 XML Paper Specification 的页面布局文件。 |
|
|  | [OXPS](#OXPS) | 表示 OpenXPS 文件 (.oxps)。 |
|
|  | [TEX](#TEX) | 表示一个 LaTeX 源文档 (.tex)，这是一种包含编程和标记功能的语言，用于排版文档。 |
|
|  | [OFD](#OFD) | 开放式固定布局文档（OFD）格式由 GB/T 33190-2016 定义，旨在取代中国公共机构中的 PDF。 |
|
|  | [PPT](#PPT) | 表示一个 PowerPoint 演示文稿 (.ppt)，它是一个包含一系列幻灯片用于放映的 PowerPoint 文件。 |
|
|  | [PPTX](#PPTX) | 表示一个 PowerPoint Open XML 演示文稿 (.pptx)，这些演示文件由流行的 Microsoft PowerPoint 应用程序创建。 |
|
|  | [PPS](#PPS) | 表示一个 PowerPoint 幻灯片放映文件 (.pps)，它是使用 Microsoft PowerPoint 为放映目的创建的。 |
|
|  | [PPSX](#PPSX) | 表示 PowerPoint Open XML 幻灯片放映文件 (.ppsx)，它们是使用 Microsoft PowerPoint 2007 及以上版本为放映目的创建的。 |
|
|  | [ODP](#ODP) | 表示一个 OpenDocument 演示文稿 (.odp)，它是一种在 OASIS Open 标准中由 OpenOffice.org 使用的演示文件格式。 |
|
|  | [FODP](#FODP) | 表示一个 OpenDocument 演示文稿 (.fodp)，它是 OpenDocument 平面 XML 演示文稿。 |
|
|  | [POT](#POT) | 表示一个 PowerPoint 模板 (.pot)，它是由 PowerPoint 97-2003 版本创建的 Microsoft PowerPoint 模板文件。 |
|
|  | [PPTM](#PPTM) | 表示一个 PowerPoint Open XML 启用宏的演示文稿 (.pptm)，它是使用 Microsoft PowerPoint 2007 或更高版本创建的启用宏的演示文件。 |
|
|  | [POTX](#POTX) | 表示一个 PowerPoint Open XML 演示模板 (.potx)，它是使用 Microsoft PowerPoint 2007 及以上版本创建的 Microsoft PowerPoint 模板演示文稿。 |
|
|  | [POTM](#POTM) | 表示一个 PowerPoint Open XML 启用宏的演示模板 (.potm)，它是支持宏的 Microsoft PowerPoint 模板文件。 |
|
|  | [PPSM](#PPSM) | 表示一个 PowerPoint Open XML 启用宏的幻灯片 (.ppsm)，它是使用 Microsoft PowerPoint 2007 或更高版本创建的启用宏的幻灯片放映文件格式。 |
|
|  | [OTP](#OTP) | 表示一个 OpenDocument 演示模板 (.otp)，它是按照 OASIS OpenDocument 标准格式由应用程序创建的演示模板文件。 |
|
|  | [XLS](#XLS) | 表示一个 Excel 电子表格 (.xls)，它采用 Excel 二进制文件格式。 |
|
|  | [EXCEL_2003_XML](#EXCEL-2003-XML) | 表示一个 Excel 2003 XML（SpreadsheetML） (.xml)，它采用 Excel 二进制文件格式。 |
|
|  | [NUMBERS](#NUMBERS) | 表示 Apple Numbers (.numbers)，它是一种类似 Excel 的二进制文件格式。 |
|
|  | [XLSX](#XLSX) | 表示一个 Microsoft Excel Open XML 电子表格 (.xlsx)，它是 Microsoft 在发布 Microsoft Office 2007 时推出的广为人知的 Excel 文档格式。 |
|
|  | [XLSM](#XLSM) | 表示一个 Excel Open XML 启用宏的电子表格 (.xlsm)，它是一种支持宏的电子表格文件。 |
|
|  | [XLSB](#XLSB) | 表示一个 Excel 二进制电子表格 (.xlsb)，它指定了 Excel 二进制文件格式。 |
|
|  | [CSV](#CSV) | 表示一个逗号分隔值文件 (.csv)，它是包含以逗号分隔的数据记录的纯文本文件。 |
|
|  | [TSV](#TSV) | 表示一个制表符分隔值文件 (.tsv)，它是以制表符分隔数据的纯文本格式文件。 |
|
|  | [ODS](#ODS) | 表示一个 OpenDocument 电子表格 (.ods)，它代表一种用户可编辑的 OpenDocument 电子表格文档格式。 |
|
|  | [FODS](#FODS) | 表示一个 OpenDocument 平面 XML 电子表格 (.fods)。 |
|
|  | [OTS](#OTS) | 表示一个 OpenDocument 电子表格模板 (.ots)。 |
|
|  | [XLAM](#XLAM) | 表示 Microsoft Excel 加载项 (.xlam)。 |
|
|  | [XLTM](#XLTM) | 表示 Microsoft Excel 宏启用模板 (.xltm)，它表示由 Microsoft Excel 生成的宏启用模板文件。 |
|
|  | [XLT](#XLT) | 表示 Microsoft Excel 模板 (.xlt)，它是使用 Microsoft Excel（Microsoft Office 套件中的电子表格应用程序）创建的模板文件。 |
|
|  | [XLTX](#XLTX) | 表示 Excel Open XML 电子表格模板 (.xltx)，它表示基于 Office OpenXML 文件格式规范的 Microsoft Excel 模板。 |
|
|  | [SXC](#SXC) | 表示 StarOffice Calc 电子表格 (.sxc)。 |
|
|  | [MPP](#MPP) | 表示 Microsoft Project 文件 (.mpp)，它是以集成方式存储项目管理相关信息的 Microsoft Project 数据文件。 |
|
|  | [MPT](#MPT) | 表示 Microsoft Project 模板 (.mpt)，它包含用于创建 .MPP 文件的基本信息、结构以及文档设置。 |
|
|  | [MPX](#MPX) | 表示 Microsoft Project Exchange 文件 (.mpx)，它是一种 ASCII 文件格式，用于在 Microsoft Project (MSP) 与其他支持 MPX 文件格式的应用程序之间传输项目信息，例如 Primavera Project Planner、Sciforma 和 Timerline Precision Estimating。 |
|
|  | [AS](#AS) | 表示 ActionScript 文件 (.as)。 |
|
|  | [AS_3](#AS-3) | 表示 ActionScript 文件 (.as3)。 |
|
|  | [ASM](#ASM) | 表示汇编语言源代码文件 (.asm)。 |
|
|  | [BAT](#BAT) | 表示 DOS 批处理文件 (.bat)。 |
|
|  | [C](#C) | 表示 C/C++ 源代码文件 (.c)。 |
|
|  | [CC](#CC) | 表示 C++ 源代码文件 (.cc)。 |
|
|  | [CMAKE](#CMAKE) | 表示 CMake 文件 (.cmake)。 |
|
|  | [CPP](#CPP) | 表示 C++ 源代码文件 (.cpp)。 |
|
|  | [CS](#CS) | 表示 C# 源代码文件 (.cs)，它是 C# 编程语言的源代码文件。 |
|
|  | [VB](#VB) | 表示 Visual Basic 项目项文件 (.vb)，它是使用 Visual Basic 语言创建的源代码文件。 |
|
|  | [CSS](#CSS) | 表示层叠样式表 (.css) 文件。 |
|
|  | [CXX](#CXX) | 表示 C++ 源代码文件 (.cxx)。 |
|
|  | [DIFF](#DIFF) | 表示补丁文件 (.diff)。 |
|
|  | [ERB](#ERB) | 表示 Ruby ERB 脚本 (.erb)。 |
|
|  | [GROOVY](#GROOVY) | 表示 Groovy 源代码文件 (.groovy)。 |
|
|  | [H](#H) | 表示 C/C++/Objective-C 头文件 (.h)。 |
|
|  | [HAML](#HAML) | 表示 Haml 源代码文件 (.haml)。 |
|
|  | [HH](#HH) | 表示一个 C++ 头文件 (.hh)。 |
|
|  | [JAVA](#JAVA) | 表示一个 Java 源代码文件 (.java)。 |
|
|  | [JS](#JS) | 表示一个 JavaScript 文件 (.js)。 |
|
|  | [JSON](#JSON) | 表示一个 JavaScript 对象表示法文件 (.json)。 |
|
|  | [LESS](#LESS) | 表示一个 LESS 样式表 (.less) 文件。 |
|
|  | [LOG](#LOG) | 表示一个日志文件 (.log)。 |
|
|  | [M](#M) | 表示一个 Objective-C 实现文件 (.m)。 |
|
|  | [MAKE](#MAKE) | 表示一个 Xcode Makefile 脚本 (.make)。 |
|
|  | [MD](#MD) | 表示一个 Markdown 文档文件 (.md)。 |
|
|  | [ML](#ML) | 表示一个 ML 源代码文件 (.ml)。 |
|
|  | [MM](#MM) | 表示一个 Objective-C++ 源文件 (.mm)。 |
|
|  | [PHP](#PHP) | 表示一个 PHP 源代码文件 (.php)。 |
|
|  | [PL](#PL) | 表示一个 Perl 脚本 (.pl)。 |
|
|  | [PROPERTIES](#PROPERTIES) | 表示一个 Java 属性文件 (.properties)。 |
|
|  | [PY](#PY) | 表示一个 Python 脚本 (.py)。 |
|
|  | [RB](#RB) | 表示一个 Ruby 源代码 (.rb) 文件。 |
|
|  | [RST](#RST) | 表示一个 reStructuredText 文件 (.rst)。 |
|
|  | [SASS](#SASS) | 表示一个 Syntactically Awesome StyleSheets 文件 (.sass)。 |
|
|  | [SCALA](#SCALA) | 表示一个 Scala 源代码文件 (.scala)。 |
|
|  | [SCM](#SCM) | 表示一个 Scheme 源代码文件 (.scm)。 |
|
|  | [SCRIPT](#SCRIPT) | 表示一个通用脚本文件 (.script)。 |
|
|  | [SH](#SH) | 表示一个 Bash Shell 脚本 (.sh)。 |
|
|  | [SML](#SML) | 表示一个 Standard ML 源代码文件 (.sml)。 |
|
|  | [SQL](#SQL) | 表示一个结构化查询语言数据文件 (.sql)。 |
|
|  | [VIM](#VIM) | 表示一个 Vim 设置文件 (.vim)。 |
|
|  | [YAML](#YAML) | 表示一个 YAML 文档 (.yaml)。 |
|
|  | [DOC](#DOC) | 表示一个 Microsoft Word 文档 (.doc) 文件。 |
|
|  | [DOCX](#DOCX) | 表示一个 Microsoft Word Open XML 文档 (.docx) 文件。 |
|
|  | [CHM](#CHM) | 表示一个 Microsoft 编译的 HTML 帮助文件 (.chm)。 |
|
|  | [DOCM](#DOCM) | 表示一个 Word Open XML 宏启用文档 (.docm) 文件。 |
|
|  | [DOT](#DOT) | 表示一个 Word 文档模板 (.dot) 文件。 |
|
|  | [DOTX](#DOTX) | 表示一个 Word Open XML 文档模板 (.dotx) 文件。 |
|
|  | [DOTM](#DOTM) | 表示一个 Word Open XML 宏启用文档模板 (.dotm) 文件。 |
|
|  | [RTF](#RTF) | 表示一个富文本格式文件 (.rtf)。 |
|
|  | [TXT](#TXT) | 表示一个纯文本文件 (.txt)。 |
|
|  | [ODT](#ODT) | 表示一个 OpenDocument 文本文档 (.odt)。 |
|
|  | [OTT](#OTT) | 表示一个 OpenDocument 文档模板 (.ott)。 |
|
|  | [VCF](#VCF) | 表示一个 vCard 文件 (.vcf)，它是一种用于存储联系信息的数字文件格式。 |
|
|  | [AI](#AI) | 表示一个 Adobe Illustrator 文件 (.ai)，它是一种用于 Adobe Illustrator 绘图的文件格式。 |
|
|  | [PSM1](#PSM1) | 表示一个 PowerShell 脚本模块文件 (.psm1)。 |
|
|  | [PS1](#PS1) | 表示一个 PowerShell 脚本文件 (.ps1)。 |
|
|  | [PSD1](#PSD1) | 表示一个 PowerShell 脚本模块清单文件 (.psd1)。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 将文件扩展名映射到文件类型。 |
|
|  | [fromFilePath(String filePath)](#fromFilePath-java.lang.String-) | 从文件名或文件路径中提取文件扩展名并将其映射到文件类型。 |
|
|  | [fromMediaType(String mediaType)](#fromMediaType-java.lang.String-) | 将文件媒体类型映射到文件类型。 |
|
|  | [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | 通过读取文件签名检测文件类型。 |
|
|  | [fromStream(InputStream stream, String password)](#fromStream-java.io.InputStream-java.lang.String-) | 通过读取文件签名检测文件类型。 |
|
|  | [fromStream(InputStream stream, ILogger logger)](#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-) | 通过读取文件签名检测文件类型。 |
|
|  | [fromStream(InputStream stream, String password, ILogger logger)](#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-) | 通过读取文件签名检测文件类型。 |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | 检索受支持的文件类型。 |
|
|  | [detectCharset(String filePath)](#detectCharset-java.lang.String-) | 尝试通过路径检测文本 [TXT](../../com.groupdocs.viewer/filetype#TXT)、[TSV](../../com.groupdocs.viewer/filetype#TSV) 和 [CSV](../../com.groupdocs.viewer/filetype#CSV) 文件的字符集。 |
|
|  | [detectCharset(InputStream stream)](#detectCharset-java.io.InputStream-) | 尝试通过流检测文本 [TXT](../../com.groupdocs.viewer/filetype#TXT)、[TSV](../../com.groupdocs.viewer/filetype#TSV) 和 [CSV](../../com.groupdocs.viewer/filetype#CSV) 文件的字符集。 |
|
|  | [getFileFormat()](#getFileFormat--) | 获取文件格式的名称，例如 "Microsoft Word Document"。 |
|
|  | [getExtension()](#getExtension--) | 获取文件扩展名后缀（包括句点 "."），例如 ".doc"。 |
|
|  | [toString()](#toString--) | 返回当前对象的字符串表示。 |
|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


表示未知的文件类型。


### ZIP {#ZIP}
```
public static final FileType ZIP
```


表示可容纳一个或多个文件或目录的压缩文件（.zip）。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/compression/zip)。


### TAR {#TAR}
```
public static final FileType TAR
```


表示用于收集一个或多个文件的合并 Unix 文件归档（.tar）。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/compression/tar)。


### XZ {#XZ}
```
public static final FileType XZ
```


表示使用基于 LZMA 算法的高比率压缩算法压缩的 XZ 文件（.xz）。
了解更多关于此文件格式的信息，请点击[此处](../https://fileinfo.com/extension/xz)。


### TXZ {#TXZ}
```
public static final FileType TXZ
```


表示一个为收集一个或多个文件而创建的合并 Unix 文件归档（.txz，.tar.xz）。
了解更多关于此文件格式的信息，请点击[此处](../https://fileinfo.com/extension/txz)。


### TARXZ {#TARXZ}
```
public static final FileType TARXZ
```


表示一个为收集一个或多个文件而创建的合并 Unix 文件归档（.txz，.tar.xz）。
了解更多关于此文件格式的信息，请点击[此处](../https://fileinfo.com/extension/txz)。


### TGZ {#TGZ}
```
public static final FileType TGZ
```


表示一个为收集一个或多个文件而创建的合并 Unix 文件归档（.tgz，.tar.gz）。
了解更多关于此文件格式的信息，请点击[此处](../https://fileinfo.com/extension/tgz)。


### TARGZ {#TARGZ}
```
public static final FileType TARGZ
```


表示一个为收集一个或多个文件而创建的合并 Unix 文件归档（.tgz，.tar.gz）。
了解更多关于此文件格式的信息，请点击[此处](../https://fileinfo.com/extension/tgz)。


### BZ_2 {#BZ-2}
```
public static final FileType BZ_2
```


表示使用 BZIP2 开源压缩方法生成的 Bzip2 压缩文件（.bz2）。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/compression/bz2)。


### RAR {#RAR}
```
public static final FileType RAR
```


表示使用 RAR（WINRAR 版本 4）压缩方法生成的 Roshal Archive（.rar）压缩文件。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/compression/rar)。


### GZ {#GZ}
```
public static final FileType GZ
```


表示使用 gzip 压缩应用程序创建的 Gnu Zipped File（.gz）压缩文件。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/compression/gz)。


### GZIP {#GZIP}
```
public static final FileType GZIP
```


表示作为替代 Unix 系统中 Compress 程序的免费工具引入的 Gnu Zipped File（.gzip）压缩文件。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/compression/gz)。


### SEVEN_ZIP {#SEVEN-ZIP}
```
public static final FileType SEVEN_ZIP
```


表示 7Zip（.7z，.7zip）文件，它是一种具有 LZMA 和 LZMA2 压缩的免费开源归档工具。
了解更多关于此文件格式的信息，请点击[此处](../https://docs.fileformat.com/compression/7z/)。


### CPIO {#CPIO}
```
public static final FileType CPIO
```


Cpio 是一种通用文件归档工具及其关联的文件格式。它主要安装在类 Unix 的计算机操作系统上。了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/compression/cpio)。


### ZSTANDARD {#ZSTANDARD}
```
public static final FileType ZSTANDARD
```


ZST 文件是一种使用 Zstandard（zstd）压缩算法生成的压缩文件。它是通过该算法进行无损压缩创建的压缩文件。ZST 文件可用于压缩各种类型的文件，如数据库、文件系统、网络和游戏。
了解更多关于此文件格式的信息，请点击[此处](../https://docs.fileformat.com/compression/zst/)。


### TZST {#TZST}
```
public static final FileType TZST
```


TZST 文件（.tar.zst，.tzst）是 Zstandard 归档（ZST），内部包含使用 Unix 基础实用程序为收集一个或多个文件而创建的合并 Unix 文件归档（Tar）。


### TAR_ZST {#TAR-ZST}
```
public static final FileType TAR_ZST
```


TZST 文件（.tar.zst，.tzst）是 Zstandard 归档（ZST），内部包含使用 Unix 基础实用程序为收集一个或多个文件而创建的合并 Unix 文件归档（Tar）。


### ISO {#ISO}
```
public static final FileType ISO
```


ISO 光盘映像是一种未压缩的归档磁盘映像文件，基于 ISO-9660 标准，表示光盘（如 CD 或 DVD）上完整数据的内容。
了解更多关于此文件格式的信息，请点击[此处](../https://docs.fileformat.com/compression/iso/)。


### LHA {#LHA}
```
public static final FileType LHA
```


LHA 或 LZH 是一种免费压缩实用程序及其关联的文件格式。
了解更多关于此文件格式的信息，请点击[此处](../https://docs.fileformat.com/compression/lzh/)。


### CAB {#CAB}
```
public static final FileType CAB
```


Cabinet（或 CAB）是 Microsoft Windows 的归档文件格式。
了解更多关于此文件格式的信息，请点击[此处](../https://en.wikipedia.org/wiki/Cabinet_(file_format))。


### DXF {#DXF}
```
public static final FileType DXF
```


表示一种绘图交换格式文件（.dxf），它是 AutoCAD 绘图文件的标记数据表示。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/cad/dxf)。


### DWG {#DWG}
```
public static final FileType DWG
```


表示一种 AutoCAD 绘图数据库文件（.dwg），它是用于存储 2D 和 3D 设计数据的专有二进制文件。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/cad/dwg)。


### DWT {#DWT}
```
public static final FileType DWT
```


表示一种 AutoCAD 绘图模板（.dwt），它是用于创建可保存为 DWG 文件的绘图的起始模板文件。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/cad/dwt)。


### STL {#STL}
```
public static final FileType STL
```


表示立体光刻文件（.stl），这是一种可互换的文件格式，用于表示三维表面几何。它常用于快速原型制作、3D 打印和计算机辅助制造。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/cad/stl)。


### IFC {#IFC}
```
public static final FileType IFC
```


表示行业基础类文件（.ifc），这是一种建立了建筑对象及其属性进出口国际标准的文件格式。它实现了不同软件应用之间的互操作性。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/cad/ifc)。


### DWF {#DWF}
```
public static final FileType DWF
```


表示设计网络格式文件（.dwf），这是一种用于查看、审阅或打印 2D/3D 图纸的压缩文件格式。它包含作为设计数据一部分的图形和文本，并通过压缩降低文件大小。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/cad/dwf)。


### FBX {#FBX}
```
public static final FileType FBX
```


表示一种 Autodesk FBX 交换文件（FilmBoX）（.fbx），它是一种 3D 模型格式。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/cad/fbx).


### DWFX {#DWFX}
```
public static final FileType DWFX
```


表示一种 Design Web Format 文件 XPS (.dwfx)，它是一种用于查看、审阅或打印 2D/3D 图纸为 XPS 文档的压缩格式。它包含作为设计数据一部分的图形和文本，并通过压缩降低文件大小。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/cad/dwfx).


### DGN {#DGN}
```
public static final FileType DGN
```


表示一种 MicroStation 设计文件（.dgn），它是由 MicroStation、Intergraph Interactive Graphics Design System 等 CAD 应用程序创建和支持的绘图。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/cad/dgn).


### PLT {#PLT}
```
public static final FileType PLT
```


表示一种 PLT (HPGL) 文件 (.plt)，它是 Autodesk, Inc. 推出的基于矢量的绘图仪文件。它包含特定 CAD 文件的信息，所有图像均使用线条而非点进行打印，确保生产中的准确性和精度。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/cad/plt).


### CF2 {#CF2}
```
public static final FileType CF2
```


表示一种通用文件格式文件（.cf2）。
了解更多关于此文件格式的信息 [这里](../https://fileinfo.com/extension/cf2).


### OBJ {#OBJ}
```
public static final FileType OBJ
```


表示一种 Wavefront 3D 对象文件（.obj），它是 Wavefront Technologies 推出的 3D 图像文件。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/3d/obj/).


### HPG {#HPG}
```
public static final FileType HPG
```


表示一个 PLT (HPGL) 文件 (.hpg)。
它是一种用于 HP Graphics Language (HPGL) 绘图仪文件的文件格式。
了解更多关于此文件格式的信息 [这里](../https://fileinfo.com/extension/hpg).


### IGS {#IGS}
```
public static final FileType IGS
```


表示一个初始图形交换规范 (IGES) 文件 (.igs)。


### VSD {#VSD}
```
public static final FileType VSD
```


表示一个 Visio 绘图文件 (.vsd)，这些绘图是使用 Microsoft Visio 应用程序创建的，用于表示各种图形对象及其相互连接。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/image/vsd).


### VSDX {#VSDX}
```
public static final FileType VSDX
```


表示一种 Visio 绘图文件 (.vsdx)，它是自 Microsoft Office 2013 起引入的 Microsoft Visio 文件格式。它取代了早期 Microsoft Visio 支持的二进制文件格式 (.VSD)。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/image/vsdx).


### VSS {#VSS}
```
public static final FileType VSS
```


表示一种 Visio 模板文件 (.vss)，它是使用 Microsoft Visio 2007 及更早版本创建的模板文件。模板文件提供可包含在 .VSD Visio 绘图中的绘图对象。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/image/vss).


### VSSX {#VSSX}
```
public static final FileType VSSX
```


表示一种 Visio 模板文件 (.vssx)，它是使用 Microsoft Visio 2013 及以上版本创建的绘图模板。VSSX 文件格式可在 Visio 2013 及以上版本中打开。Visio 文件以表示各种绘图元素而闻名，如形状、连接线、流程图、网络布局、UML 图等。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/image/vssx).


### VSDM {#VSDM}
```
public static final FileType VSDM
```


表示一种 Visio 启用宏的绘图文件 (.vsdm)，它是由支持宏的 Microsoft Visio 应用程序创建的绘图文件。VSDM 文件是类似于 VSDX 的 OPC/XML 绘图，但还提供在打开文件时运行宏的功能。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/image/vsdm).


### VST {#VST}
```
public static final FileType VST
```


表示一种 Visio 绘图模板 (.vst)，它是使用 Microsoft Visio 创建的矢量图像文件。它们充当创建其他文件的模板，并包含用于创建新 Visio 绘图的默认布局和设置。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/image/vst).


### VSTX {#VSTX}
```
public static final FileType VSTX
```


表示一种 Visio 绘图模板 (.vstx)，它是使用 Microsoft Visio 2013 及以上版本创建的绘图模板文件。这些 VSTX 文件为创建保存为 .VSDX 文件的 Visio 绘图提供了起始点，并带有默认布局和设置。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/image/vstx).


### VSTM {#VSTM}
```
public static final FileType VSTM
```


表示一种 Visio 启用宏的绘图模板 (.vstm)，它是由支持宏的 Microsoft Visio 创建的模板文件。基于 VSTM 模板创建的文件可以运行使用 Visual Basic for Applications (VBA) 代码开发的宏。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/image/vstm).


### VSSM {#VSSM}
```
public static final FileType VSSM
```


表示一个 Visio 宏启用模板文件 (.vssm)，它是支持宏的 Microsoft Visio 模板文件。当打开 VSSM 文件时，可以运行宏以实现所需的形状格式化和放置。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/image/vssm)。


### VSX {#VSX}
```
public static final FileType VSX
```


表示一个 Visio 模板 XML 文件 (.vsx)，它指的是用于在 Microsoft Visio 中创建图表的绘图和形状模板。VSX 文件以 XML 格式保存，并在 Visio 2013 之前受支持。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/image/vsx)。


### VTX {#VTX}
```
public static final FileType VTX
```


表示一个 Visio 模板 XML 文件 (.vtx)，它是以 XML 格式保存到磁盘的 Microsoft Visio 绘图模板。该模板提供基本设置，以创建具有相同设置的多个 Visio 文件。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/image/vtx)。


### VDW {#VDW}
```
public static final FileType VDW
```


表示一个 Visio Web 绘图 (.vdw)，它指定了渲染 Web 绘图所需的流和存储。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/web/vdw)。


### VDX {#VDX}
```
public static final FileType VDX
```


表示一个 Visio 绘图 XML 文件 (.vdx)，它表示在 Microsoft Visio 中创建的任何绘图或图表，但以 .VDX 扩展名的 XML 格式保存。Visio 绘图 XML 文件由 Microsoft 开发的 Visio 软件创建。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/image/vdx)。


### EPUB {#EPUB}
```
public static final FileType EPUB
```


表示一个 Open eBook 文件 (.epub)，它是一种为出版商和消费者提供标准数字出版格式的电子书文件格式。该格式受到许多电子阅读器和软件应用的支持。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/ebook/epub)。


### MOBI {#MOBI}
```
public static final FileType MOBI
```


表示一个 Mobipocket 电子书 (.mobi)，它是最广泛使用的电子书文件格式之一。该格式是对旧的 OEB（Open Ebook Format）格式的增强，并曾作为 Mobipocket Reader 的专有格式使用。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/ebook/mobi)。


### AZW_3 {#AZW-3}
```
public static final FileType AZW_3
```


Amazon Kindle Format 8 (KF8) 电子书是为 Amazon Kindle 设备开发的数字文件格式。该格式是对旧的 AZW 文件的增强，仅在 Kindle Fire 设备上使用，并向后兼容其祖先文件格式，即 MOBI 和 AZW。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/ebook/azw3)。


### MSG {#MSG}
```
public static final FileType MSG
```


表示一个 Outlook 邮件信息 (.msg)，它是 Microsoft Outlook 和 Exchange 用于存储电子邮件、联系人、约会或其他任务的文件格式。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/email/msg)。


### EML {#EML}
```
public static final FileType EML
```


表示一个电子邮件消息 (.eml)，它代表使用 Outlook 等相关应用程序保存的电子邮件。几乎所有电子邮件客户端都支持此文件格式，因为它符合 RFC-822 Internet Message Format 标准。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/email/eml)。


### EMLX {#EMLX}
```
public static final FileType EMLX
```


表示一个 Apple Mail 消息 (.emlx)，它由 Apple 实现和开发。Apple Mail 应用程序使用 EMLX 文件格式导出电子邮件。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/email/emlx)。


### PST {#PST}
```
public static final FileType PST
```


表示一个 Outlook 个人信息存储文件 (.pst)，它代表 Outlook 个人存储文件（亦称个人存储表），用于存储各种用户信息。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/email/pst)。


### OST {#OST}
```
public static final FileType OST
```


表示一个 Outlook 离线数据文件 (.ost)，它代表用户在使用 Microsoft Outlook 注册 Exchange Server 后，在本地机器上离线模式下的邮箱数据。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/email/ost)。


### TIF {#TIF}
```
public static final FileType TIF
```


表示一个标记图像文件 (.tif)，它代表用于各种符合此文件格式标准的设备的光栅图像。它能够在多种色彩空间中描述二值、灰度、调色板颜色和全彩图像数据。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/image/tiff)。


### TIFF {#TIFF}
```
public static final FileType TIFF
```


表示一个标记图像文件格式 (.tiff)，它代表用于各种符合此文件格式标准的设备的光栅图像。它能够在多种色彩空间中描述二值、灰度、调色板颜色和全彩图像数据。
了解更多关于此文件格式的信息，请点击[这里](../https://wiki.fileformat.com/image/tiff)。


### JPG {#JPG}
```
public static final FileType JPG
```


表示 JPEG 图像（.jpg），这是一种使用有损压缩方法保存的图像格式。压缩后得到的输出图像在存储大小和图像质量之间需要权衡。
了解更多关于此文件格式的信息 [此处](../https://wiki.fileformat.com/image/jpeg)。


### JPEG {#JPEG}
```
public static final FileType JPEG
```


表示 JPEG 图像（.jpeg），这是一种使用有损压缩方法保存的图像格式。压缩后得到的输出图像在存储大小和图像质量之间需要权衡。
了解更多关于此文件格式的信息 [此处](../https://wiki.fileformat.com/image/jpeg)。


### JFIF {#JFIF}
```
public static final FileType JFIF
```


JPEG 文件交换格式（.jfif）是一种为平台之间快速交换而开发的图像。此格式使用 JPEG 压缩。了解更多关于此文件格式的信息 [此处](../https://wiki.fileformat.com/image/jfif)。


### PNG {#PNG}
```
public static final FileType PNG
```


表示可移植网络图形（.png），这是一种使用无损压缩的光栅图像文件格式。该文件格式是为取代图形交换格式（GIF）而创建的，并且没有版权限制。
了解更多关于此文件格式的信息 [此处](../https://wiki.fileformat.com/image/png)。


### GIF {#GIF}
```
public static final FileType GIF
```


表示图形交换格式文件（.gif），这是一种高度压缩的图像。对于每个图像，GIF 通常允许每像素最多 8 位，并且整个图像最多允许 256 种颜色。
了解更多关于此文件格式的信息 [此处](../https://wiki.fileformat.com/image/gif)。


### APNG {#APNG}
```
public static final FileType APNG
```


表示动画便携式网络图形（.apng），这是 PNG 格式的扩展，支持动画。
了解更多关于此文件格式的信息 [此处](../https://wiki.fileformat.com/image/apng)。


### BMP {#BMP}
```
public static final FileType BMP
```


表示位图图像文件（.bmp），用于存储位图数字图像。这些图像独立于图形适配器，也称为设备无关位图（DIB）文件格式。
了解更多关于此文件格式的信息 [此处](../https://wiki.fileformat.com/image/bmp)。


### ICO {#ICO}
```
public static final FileType ICO
```


表示图标文件（.ico），这是一种在 Microsoft Windows 上用作应用程序图标的图像文件类型。
了解更多关于此文件格式的信息 [此处](../https://wiki.fileformat.com/image/ico)。


### TGA {#TGA}
```
public static final FileType TGA
```


表示 Truevision TGA（TARGA）文件，这是一种由 TRUEVISION 开发用于存储位图数字图像的文件。
了解更多关于此文件格式的信息 [此处](../https://wiki.fileformat.com/image/tga)。


### JP_2 {#JP-2}
```
public static final FileType JP_2
```


表示 JPEG 2000 核心图像文件（.jp2），这是一种图像编码系统和最先进的图像压缩标准。
了解更多关于此文件格式的信息 [此处](../https://wiki.fileformat.com/image/jp2)。


### JPF {#JPF}
```
public static final FileType JPF
```


表示 JPEG 2000 图像文件（.jpf）。
了解更多关于此文件格式的信息 [此处](../https://docs.fileformat.com/image/jpf)。


### JPX {#JPX}
```
public static final FileType JPX
```


表示 JPEG 2000 图像文件（.jpx）。
了解更多关于此文件格式的信息 [此处](../https://wiki.fileformat.com/image/jpx)。


### JPM {#JPM}
```
public static final FileType JPM
```


表示 JPEG 2000 图像文件（.jpm）。
了解更多关于此文件格式的信息 [此处](../https://wiki.fileformat.com/image/jpm)。


### J2C {#J2C}
```
public static final FileType J2C
```


表示 JPEG 2000 代码输入流（.j2c）。
了解更多关于此文件格式的信息 [此处](../https://wiki.fileformat.com/image/j2c)。


### J2K {#J2K}
```
public static final FileType J2K
```


表示 JPEG 2000 代码流（.j2k），这是一种使用小波压缩而非 DCT 压缩的图像。
了解更多关于此文件格式的信息 [此处](../https://wiki.fileformat.com/image/j2k)。


### JPC {#JPC}
```
public static final FileType JPC
```


表示 JPEG 2000 代码流（.jpc）。
了解更多关于此文件格式的信息 [此处](../https://wiki.fileformat.com/image/jpc)。


### JLS {#JLS}
```
public static final FileType JLS
```


表示 JPEG-LS（JLS）文件（.jls）。
了解更多关于此文件格式的信息 [此处](../https://fileinfo.com/extension/jls)。


### DIB {#DIB}
```
public static final FileType DIB
```


表示设备无关位图文件（.dib）。
了解更多关于此文件格式的信息 [此处](../https://wiki.fileformat.com/image/dib)。


### WMF {#WMF}
```
public static final FileType WMF
```


表示 Windows 元文件（.wmf），用于存储矢量以及位图格式图像数据的 Microsoft Windows 元文件（WMF）。
了解更多关于此文件格式的信息 [此处](../https://wiki.fileformat.com/image/wmf)。


### WMZ {#WMZ}
```
public static final FileType WMZ
```


表示压缩的 Windows 元文件（.wmz），这是经过 GZIP 压缩的 Microsoft Windows 元文件（WMF），用于存储矢量以及位图格式图像数据。
了解更多关于此文件格式的信息 [此处](../https://fileinfo.com/extension/wmz#compressed_windows_metafile)。


### EMF {#EMF}
```
public static final FileType EMF
```


表示增强型 Windows 元文件（.emf），它以设备无关方式表示图形图像。EMF 元文件由按时间顺序排列的可变长度记录组成，可在任何输出设备上解析后渲染存储的图像。
了解更多关于此文件格式的信息，请访问[此处](../https://wiki.fileformat.com/image/emf)。


### EMZ {#EMZ}
```
public static final FileType EMZ
```


表示 Windows 压缩增强型图元文件 (.emz)，它通过 GZIP 对图形图像进行设备无关压缩。EMF 元文件由按时间顺序排列的可变长度记录组成，能够在任何输出设备上解析后渲染存储的图像。
了解更多关于此文件格式的信息，请访问[此处](../https://wiki.fileformat.com/image/emz)。


### WEBP {#WEBP}
```
public static final FileType WEBP
```


表示 WebP 图像 (.webp)，这是一种基于无损和有损压缩的现代光栅网络图像文件格式。它在显著减小图像体积的同时提供相同的图像质量。
了解更多关于此文件格式的信息，请访问[此处](../https://wiki.fileformat.com/image/webp)。


### DNG {#DNG}
```
public static final FileType DNG
```


表示数字负片规范 (.dng)，这是一种用于存储原始文件的数码相机图像格式。它于 2004 年 9 月由 Adobe 开发，主要用于数字摄影。
了解更多关于此文件格式的信息，请访问[此处](../https://wiki.fileformat.com/image/dng)。


### CDR {#CDR}
```
public static final FileType CDR
```


表示 CorelDraw 矢量图形绘图 (.cdr)，这是一种由 CorelDRAW 原生创建用于存储数字编码和压缩图像的矢量绘图文件。CDR 绘图文件包含文本、线条、形状、图像、颜色和效果，以矢量方式表示图像内容。
了解更多关于此文件格式的信息，请访问[此处](../https://wiki.fileformat.com/image/cdr)。


### CMX {#CMX}
```
public static final FileType CMX
```


表示 Corel Exchange (.cmx)，它是一种可能包含矢量图形以及位图图形的绘图图像文件。
了解更多关于此文件格式的信息，请访问[此处](../https://wiki.fileformat.com/image/cmx)。


### DJVU {#DJVU}
```
public static final FileType DJVU
```


表示 DjVu Image (.djvu)，它是一种用于扫描文档和书籍的图形文件格式，尤其适用于包含文本、图纸、图像和照片组合的文档。
了解更多关于此文件格式的信息，请访问[此处](../https://wiki.fileformat.com/image/djvu)。


### CGM {#CGM}
```
public static final FileType CGM
```


表示计算机图形元文件 (.cgm)，这是一种免费、平台无关的国际标准元文件格式，用于存储和交换矢量图形（2D）、光栅图形和文本。CGM 采用面向对象的方法，提供多种图像生成函数。
了解更多关于此文件格式的信息，请访问[此处](../https://wiki.fileformat.com/page-description-language/cgm)。


### PCL {#PCL}
```
public static final FileType PCL
```


表示 Printer Command Language 文档 (.pcl)。
了解更多关于此文件格式的信息，请访问[此处](../https://wiki.fileformat.com/page-description-language/pcl)。


### PSD {#PSD}
```
public static final FileType PSD
```


表示 Adobe Photoshop Document (.psd)，它是 Adobe Photoshop 的原生文件格式，用于图形设计和开发。
了解更多关于此文件格式的信息，请访问[此处](../https://wiki.fileformat.com/image/psd)。


### PSB {#PSB}
```
public static final FileType PSB
```


表示 Photoshop Large Document Format (.psb)，它用于 Adobe Photoshop 中的图形设计和开发。
了解更多关于此文件格式的信息，请访问[此处](../https://wiki.fileformat.com/image/psb)。


### DCM {#DCM}
```
public static final FileType DCM
```


表示 DICOM Image (.dcm)，它是一种存储患者医学信息（如 MRI、CT 扫描和超声图像）的数字图像。
了解更多关于此文件格式的信息，请访问[此处](../https://wiki.fileformat.com/image/dcm)。


### PS {#PS}
```
public static final FileType PS
```


表示 PostScript 文件 (.ps)。
了解更多关于此文件格式的信息，请访问[此处](../https://wiki.fileformat.com/page-description-language/ps)。


### EPS {#EPS}
```
public static final FileType EPS
```


表示 Encapsulated PostScript 文件 (.eps)，它描述了一个定义单页外观的 Encapsulated PostScript 语言程序。
了解更多关于此文件格式的信息，请访问[此处](../https://wiki.fileformat.com/page-description-language/eps)。


### ODG {#ODG}
```
public static final FileType ODG
```


表示 OpenDocument Graphic 文件 (.odg)，它被 Apache OpenOffice 的 Draw 应用程序用于将绘图元素存储为矢量图像。
了解更多关于此文件格式的信息，请访问[此处](../https://wiki.fileformat.com/image/odg)。


### FODG {#FODG}
```
public static final FileType FODG
```


表示 Flat XML ODF 模板 (.fodg)，它被 Apache OpenOffice 的 Draw 应用程序用于将绘图元素存储为矢量图像。
了解更多关于此文件格式的信息，请访问[此处](../https://wiki.fileformat.com/image/fodg)。


### SVG {#SVG}
```
public static final FileType SVG
```


表示 Scalable Vector Graphics 文件 (.svg)，它是一种使用基于 XML 的文本格式来描述图像外观的可缩放矢量图形文件。
了解更多关于此文件格式的信息，请访问[此处](../https://wiki.fileformat.com/page-description-language/svg)。


### SVGZ {#SVGZ}
```
public static final FileType SVGZ
```


表示 Compressed Scalable Vector Graphics 文件 (.svgz)，它是一种使用基于 XML 的文本格式并经 GZIP 压缩的可缩放矢量图形文件，用于描述图像的外观。
了解更多关于此文件格式的信息，请访问[此处](../https://fileinfo.com/extension/svgz)。


### OTG {#OTG}
```
public static final FileType OTG
```


表示 OpenDocument Graphic 模板 (.otg)。
了解更多关于此文件格式的信息，请访问[此处](../https://docs.fileformat.com/image/otg)。


### HTM {#HTM}
```
public static final FileType HTM
```


表示 Hypertext Markup Language 文件 (.htm)，它是用于在浏览器中显示的网页的扩展名。
了解更多关于此文件格式的信息，请访问[此处](../https://wiki.fileformat.com/web/html)。


### HTML {#HTML}
```
public static final FileType HTML
```


表示 Hypertext Markup Language 文件 (.html)，它是用于在浏览器中显示的网页的扩展名。
了解更多关于此文件格式的信息，请访问[此处](../https://wiki.fileformat.com/web/html)。


### MHT {#MHT}
```
public static final FileType MHT
```


表示 MHTML Web 存档 (.mht)。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/web/mht)。


### NSF {#NSF}
```
public static final FileType NSF
```


表示 Lotus Notes 数据库 (.nsf)。
了解更多关于此文件格式的信息，请点击[此处](../https://fileinfo.com/extension/nsf)。


### MBOX {#MBOX}
```
public static final FileType MBOX
```


表示 Email Mailbox 文件 (.mbox)。
了解更多关于此文件格式的信息，请点击[此处](../https://fileinfo.com/extension/mbox)。


### MHTML {#MHTML}
```
public static final FileType MHTML
```


表示 MIME HTML 文件 (.mhtml)。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/web/mhtml)。


### XML {#XML}
```
public static final FileType XML
```


表示 XML 文件 (.xml)。
了解更多关于此文件格式的信息，请点击[此处](../https://docs.fileformat.com/web/xml)。


### ONE {#ONE}
```
public static final FileType ONE
```


表示由 Microsoft OneNote 应用程序创建的 OneNote 文档 (.one)。OneNote 让您能够使用该应用程序收集信息，就像使用草稿本记笔记一样。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/note-taking/one)。


### PDF {#PDF}
```
public static final FileType PDF
```


表示便携式文档格式文件 (.pdf)，这是一种由 Adobe 在 1990 年代创建的文档类型。此文件格式的目的是引入一种标准，用于以独立于应用软件、硬件和操作系统的格式表示文档和其他参考材料。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/view/pdf)。


### XPS {#XPS}
```
public static final FileType XPS
```


表示 XML 纸张规范文件 (.xps)，它基于 Microsoft 创建的 XML 纸张规范的页面布局文件。此格式由 Microsoft 开发，作为 EMF 文件格式的替代品，类似于 PDF 文件格式，但在文档的布局、外观和打印信息中使用 XML。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/page-description-language/xps)。


### OXPS {#OXPS}
```
public static final FileType OXPS
```


表示 OpenXPS 文件 (.oxps)。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/page-description-language/oxps)。


### TEX {#TEX}
```
public static final FileType TEX
```


表示一个 LaTeX 源文档 (.tex)，这是一种包含编程和标记功能的语言，用于排版文档。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/page-description-language/tex)。


### OFD {#OFD}
```
public static final FileType OFD
```


开放式固定布局文档（OFD）格式由 GB/T 33190-2016 定义，旨在取代中国公共机构中的 PDF。


### PPT {#PPT}
```
public static final FileType PPT
```


表示 PowerPoint 演示文稿 (.ppt)，即包含一系列幻灯片用于放映的 PowerPoint 文件。它指定了 Microsoft PowerPoint 97-2003 使用的二进制文件格式。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/presentation/ppt)。


### PPTX {#PPTX}
```
public static final FileType PPTX
```


表示 PowerPoint Open XML 演示文稿 (.pptx)，即使用流行的 Microsoft PowerPoint 应用程序创建的演示文件。与之前的二进制 PPT 演示文件格式不同，PPTX 基于 Microsoft PowerPoint Open XML 演示文件格式。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/presentation/pptx)。


### PPS {#PPS}
```
public static final FileType PPS
```


表示 PowerPoint 幻灯片放映 (.pps)，即使用 Microsoft PowerPoint 创建用于幻灯片放映的文件。Microsoft PowerPoint 97-2003 支持 PPS 文件的读取和创建。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/presentation/pps)。


### PPSX {#PPSX}
```
public static final FileType PPSX
```


表示 PowerPoint Open XML 幻灯片放映文件 (.ppsx)，它们是使用 Microsoft PowerPoint 2007 及以上版本为放映目的创建的。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/presentation/ppsx)。


### ODP {#ODP}
```
public static final FileType ODP
```


表示一个 OpenDocument 演示文稿 (.odp)，它是一种在 OASIS Open 标准中由 OpenOffice.org 使用的演示文件格式。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/presentation/odp)。


### FODP {#FODP}
```
public static final FileType FODP
```


表示一个 OpenDocument 演示文稿 (.fodp)，它是 OpenDocument 平面 XML 演示文稿。
了解更多关于此文件格式的信息，请点击[此处](../https://fileinfo.com/extension/fodp)。


### POT {#POT}
```
public static final FileType POT
```


表示一个 PowerPoint 模板 (.pot)，它是由 PowerPoint 97-2003 版本创建的 Microsoft PowerPoint 模板文件。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/presentation/pot)。


### PPTM {#PPTM}
```
public static final FileType PPTM
```


表示一个 PowerPoint Open XML 启用宏的演示文稿 (.pptm)，它是使用 Microsoft PowerPoint 2007 或更高版本创建的启用宏的演示文件。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/presentation/pptm)。


### POTX {#POTX}
```
public static final FileType POTX
```


表示一个 PowerPoint Open XML 演示模板 (.potx)，它是使用 Microsoft PowerPoint 2007 及以上版本创建的 Microsoft PowerPoint 模板演示文稿。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/presentation/potx)。


### POTM {#POTM}
```
public static final FileType POTM
```


表示 PowerPoint Open XML 宏启用演示文稿模板 (.potm)，它是支持宏的 Microsoft PowerPoint 模板文件。POTM 文件由 PowerPoint 2007 或更高版本创建，并包含可用于创建其他演示文稿文件的默认设置。
了解有关此文件格式的更多信息 [此处](../https://wiki.fileformat.com/presentation/potm)。


### PPSM {#PPSM}
```
public static final FileType PPSM
```


表示一个 PowerPoint Open XML 启用宏的幻灯片 (.ppsm)，它是使用 Microsoft PowerPoint 2007 或更高版本创建的启用宏的幻灯片放映文件格式。
了解有关此文件格式的更多信息 [此处](../https://wiki.fileformat.com/presentation/ppsm)。


### OTP {#OTP}
```
public static final FileType OTP
```


表示一个 OpenDocument 演示模板 (.otp)，它是按照 OASIS OpenDocument 标准格式由应用程序创建的演示模板文件。
了解有关此文件格式的更多信息 [此处](../https://wiki.fileformat.com/presentation/otp)。


### XLS {#XLS}
```
public static final FileType XLS
```


表示 Excel 电子表格 (.xls)，它使用 Excel 二进制文件格式。这类文件可以由 Microsoft Excel 以及其他类似的电子表格程序（如 OpenOffice Calc 或 Apple Numbers）创建。
了解有关此文件格式的更多信息 [此处](../https://wiki.fileformat.com/spreadsheet/xls)。


### EXCEL_2003_XML {#EXCEL-2003-XML}
```
public static final FileType EXCEL_2003_XML
```


表示 Excel 2003 XML（SpreadsheetML） (.xml)，它使用 Excel 二进制文件格式。这类文件可以由 Microsoft Excel 以及其他类似的电子表格程序（如 OpenOffice Calc 或 Apple Numbers）创建。
了解有关此文件格式的更多信息 [此处](../https://wiki.fileformat.com/spreadsheet/xls)。


### NUMBERS {#NUMBERS}
```
public static final FileType NUMBERS
```


表示 Apple Numbers (.numbers)，它使用类似 Excel 的二进制文件格式。这类文件可以由 Apple Numbers 应用程序创建。
了解有关此文件格式的更多信息 [此处](../https://fileinfo.com/extension/numbers)。


### XLSX {#XLSX}
```
public static final FileType XLSX
```


表示一个 Microsoft Excel Open XML 电子表格 (.xlsx)，它是 Microsoft 在发布 Microsoft Office 2007 时推出的广为人知的 Excel 文档格式。
了解有关此文件格式的更多信息 [此处](../https://wiki.fileformat.com/spreadsheet/xlsx)。


### XLSM {#XLSM}
```
public static final FileType XLSM
```


表示一个 Excel Open XML 启用宏的电子表格 (.xlsm)，它是一种支持宏的电子表格文件。
了解有关此文件格式的更多信息 [此处](../https://wiki.fileformat.com/spreadsheet/xlsm)。


### XLSB {#XLSB}
```
public static final FileType XLSB
```


表示 Excel 二进制电子表格 (.xlsb)，它采用 Excel 二进制文件格式。它是由记录和结构组成的集合，用于指定 Excel 工作簿的内容。
了解有关此文件格式的更多信息 [此处](../https://wiki.fileformat.com/spreadsheet/xlsb)。


### CSV {#CSV}
```
public static final FileType CSV
```


表示一个逗号分隔值文件 (.csv)，它是包含以逗号分隔的数据记录的纯文本文件。
了解有关此文件格式的更多信息 [此处](../https://wiki.fileformat.com/spreadsheet/csv)。


### TSV {#TSV}
```
public static final FileType TSV
```


表示一个制表符分隔值文件 (.tsv)，它是以制表符分隔数据的纯文本格式文件。
了解有关此文件格式的更多信息 [此处](../https://wiki.fileformat.com/spreadsheet/tsv)。


### ODS {#ODS}
```
public static final FileType ODS
```


表示 OpenDocument 电子表格 (.ods)，即用户可编辑的 OpenDocument 电子表格文档格式。数据以行列的形式存储在 ODF 文件中。
了解有关此文件格式的更多信息 [此处](../https://wiki.fileformat.com/spreadsheet/ods)。


### FODS {#FODS}
```
public static final FileType FODS
```


表示一个 OpenDocument 平面 XML 电子表格 (.fods)。
它是一种基于 XML 的电子表格文档格式，供 OpenOffice 和 LibreOffice 使用。
了解有关此文件格式的更多信息 [此处](../https://wiki.fileformat.com/spreadsheet/fods)。


### OTS {#OTS}
```
public static final FileType OTS
```


表示一个 OpenDocument 电子表格模板 (.ots)。
它是 OpenOffice 和 LibreOffice 用于电子表格的模板文档格式。
了解有关此文件格式的更多信息 [此处](../https://wiki.fileformat.com/spreadsheet/ots)。


### XLAM {#XLAM}
```
public static final FileType XLAM
```


表示 Microsoft Excel 加载项 (.xlam)。
它是 Microsoft Excel 用于创建具有自定义功能的加载项的文件格式。
了解有关此文件格式的更多信息 [此处](../https://fileinfo.com/extension/xlam)。


### XLTM {#XLTM}
```
public static final FileType XLTM
```


表示 Microsoft Excel 宏启用模板 (.xltm)，即 Microsoft Excel 生成的宏启用模板文件。XLTM 文件在结构上类似于 XLTX，但后者不支持创建带宏的模板文件。
了解有关此文件格式的更多信息 [此处](../https://wiki.fileformat.com/spreadsheet/xltm)。


### XLT {#XLT}
```
public static final FileType XLT
```


表示 Microsoft Excel 模板 (.xlt)，即使用 Microsoft Excel 创建的模板文件，Microsoft Excel 是 Microsoft Office 套件中的电子表格应用程序。Microsoft Office 97-2003 支持创建新的 XLT 文件以及打开它们。
了解此文件格式的更多信息 [此处](../https://wiki.fileformat.com/spreadsheet/xlt).


### XLTX {#XLTX}
```
public static final FileType XLTX
```


表示 Excel Open XML 电子表格模板 (.xltx)，即基于 Office OpenXML 文件格式规范的 Microsoft Excel 模板。它用于创建标准模板文件，可用于生成具有 XLTX 文件中指定的相同设置的 XLSX 文件。
了解此文件格式的更多信息 [此处](../https://wiki.fileformat.com/spreadsheet/xltx).


### SXC {#SXC}
```
public static final FileType SXC
```


表示 StarOffice Calc 电子表格 (.sxc)。
这是使用 StarOffice Calc（电子表格程序）创建的电子表格文档。
了解此文件格式的更多信息 [此处](../https://wiki.fileformat.com/spreadsheet/sxc).


### MPP {#MPP}
```
public static final FileType MPP
```


表示 Microsoft Project 文件 (.mpp)，它是以集成方式存储项目管理相关信息的 Microsoft Project 数据文件。
了解此文件格式的更多信息 [此处](../https://wiki.fileformat.com/project-management/mpp).


### MPT {#MPT}
```
public static final FileType MPT
```


表示 Microsoft Project 模板 (.mpt)，它包含用于创建 .MPP 文件的基本信息、结构以及文档设置。
了解此文件格式的更多信息 [此处](../https://wiki.fileformat.com/project-management/mpt).


### MPX {#MPX}
```
public static final FileType MPX
```


表示 Microsoft Project Exchange 文件 (.mpx)，它是一种 ASCII 文件格式，用于在 Microsoft Project (MSP) 与其他支持 MPX 文件格式的应用程序之间传输项目信息，例如 Primavera Project Planner、Sciforma 和 Timerline Precision Estimating。
了解此文件格式的更多信息 [此处](../https://wiki.fileformat.com/project-management/mpx).


### AS {#AS}
```
public static final FileType AS
```


表示 ActionScript 文件 (.as)。
了解此文件格式的更多信息 [此处](../https://docs.fileformat.com/programming/as).


### AS_3 {#AS-3}
```
public static final FileType AS_3
```


表示 ActionScript 文件 (.as3)。
了解此文件格式的更多信息 [此处](../https://datatypes.net/open-as3-files).


### ASM {#ASM}
```
public static final FileType ASM
```


表示汇编语言源代码文件 (.asm)。
了解此文件格式的更多信息 [此处](../https://docs.fileformat.com/cad/asm).


### BAT {#BAT}
```
public static final FileType BAT
```


表示 DOS 批处理文件 (.bat)。
了解此文件格式的更多信息 [此处](../https://docs.fileformat.com/executable/bat).


### C {#C}
```
public static final FileType C
```


表示 C/C++ 源代码文件 (.c)。
了解此文件格式的更多信息 [此处](../https://wiki.fileformat.com/programming/c).


### CC {#CC}
```
public static final FileType CC
```


表示 C++ 源代码文件 (.cc)。
了解此文件格式的更多信息 [此处](../https://docs.fileformat.com/programming/cc).


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


表示 CMake 文件 (.cmake)。
了解此文件格式的更多信息 [此处](../https://wiki.fileformat.com/programming/cmake).


### CPP {#CPP}
```
public static final FileType CPP
```


表示 C++ 源代码文件 (.cpp)。
了解此文件格式的更多信息 [此处](../https://wiki.fileformat.com/programming/cpp).


### CS {#CS}
```
public static final FileType CS
```


表示 C# 源代码文件 (.cs)，即 C# 编程语言的源代码文件。它由 Microsoft 为 .NET Framework 引入而提供。
了解此文件格式的更多信息 [此处](../https://wiki.fileformat.com/programming/cs).


### VB {#VB}
```
public static final FileType VB
```


表示 Visual Basic 项目项文件 (.vb)，即在 Visual Basic 语言中创建的源代码文件。它由 Microsoft 为 .NET 应用程序的开发创建。
了解此文件格式的更多信息 [此处](../https://wiki.fileformat.com/programming/vb).


### CSS {#CSS}
```
public static final FileType CSS
```


表示层叠样式表 (.css) 文件。
了解此文件格式的更多信息 [此处](../https://wiki.fileformat.com/web/css).


### CXX {#CXX}
```
public static final FileType CXX
```


表示 C++ 源代码文件 (.cxx)。
了解此文件格式的更多信息 [此处](../https://docs.fileformat.com/programming/cxx).


### DIFF {#DIFF}
```
public static final FileType DIFF
```


表示补丁文件 (.diff)。
了解此文件格式的更多信息 [此处](../https://docs.fileformat.com/programming/diff).


### ERB {#ERB}
```
public static final FileType ERB
```


表示 Ruby ERB 脚本 (.erb)。
了解此文件格式的更多信息 [此处](../https://docs.fileformat.com/programming/erb).


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


表示 Groovy 源代码文件 (.groovy)。
了解有关此文件格式的更多信息 [here](../https://wiki.fileformat.com/programming/groovy).


### H {#H}
```
public static final FileType H
```


表示 C/C++/Objective-C 头文件 (.h)。
了解有关此文件格式的更多信息 [here](../https://docs.fileformat.com/programming/h).


### HAML {#HAML}
```
public static final FileType HAML
```


表示 Haml 源代码文件 (.haml)。
了解有关此文件格式的更多信息 [here](../https://wiki.fileformat.com/programming/haml).


### HH {#HH}
```
public static final FileType HH
```


表示一个 C++ 头文件 (.hh)。
了解有关此文件格式的更多信息 [here](../https://docs.fileformat.com/programming/hh).


### JAVA {#JAVA}
```
public static final FileType JAVA
```


表示一个 Java 源代码文件 (.java)。
了解有关此文件格式的更多信息 [here](../https://wiki.fileformat.com/programming/java).


### JS {#JS}
```
public static final FileType JS
```


表示一个 JavaScript 文件 (.js)。
了解有关此文件格式的更多信息 [here](../https://docs.fileformat.com/web/js).


### JSON {#JSON}
```
public static final FileType JSON
```


表示一个 JavaScript 对象表示法文件 (.json)。
了解有关此文件格式的更多信息 [here](../https://docs.fileformat.com/web/json).


### LESS {#LESS}
```
public static final FileType LESS
```


表示一个 LESS 样式表 (.less) 文件。
了解有关此文件格式的更多信息 [here](../https://wiki.fileformat.com/web/less).


### LOG {#LOG}
```
public static final FileType LOG
```


表示一个日志文件 (.log)。
了解有关此文件格式的更多信息 [here](../https://docs.fileformat.com/database/log).


### M {#M}
```
public static final FileType M
```


表示一个 Objective-C 实现文件 (.m)。
了解有关此文件格式的更多信息 [here](../https://fileinfo.com/extension/m).


### MAKE {#MAKE}
```
public static final FileType MAKE
```


表示一个 Xcode Makefile 脚本 (.make)。
了解有关此文件格式的更多信息 [here](../https://docs.fileformat.com/programming/make).


### MD {#MD}
```
public static final FileType MD
```


表示一个 Markdown 文档文件 (.md)。
了解有关此文件格式的更多信息 [here](../https://docs.fileformat.com/word-processing/md).


### ML {#ML}
```
public static final FileType ML
```


表示一个 ML 源代码文件 (.ml)。
了解有关此文件格式的更多信息 [here](../https://wiki.fileformat.com/programming/ml).


### MM {#MM}
```
public static final FileType MM
```


表示一个 Objective-C++ 源文件 (.mm)。
了解有关此文件格式的更多信息 [here](../https://docs.fileformat.com/programming/mm).


### PHP {#PHP}
```
public static final FileType PHP
```


表示一个 PHP 源代码文件 (.php)。
了解有关此文件格式的更多信息 [here](../https://wiki.fileformat.com/programming/php).


### PL {#PL}
```
public static final FileType PL
```


表示一个 Perl 脚本 (.pl)。
了解有关此文件格式的更多信息 [here](../https://docs.fileformat.com/programming/pl).


### PROPERTIES {#PROPERTIES}
```
public static final FileType PROPERTIES
```


表示一个 Java 属性文件 (.properties)。
了解有关此文件格式的更多信息 [here](../https://fileinfo.com/extension/properties).


### PY {#PY}
```
public static final FileType PY
```


表示一个 Python 脚本 (.py)。
了解有关此文件格式的更多信息 [here](../https://docs.fileformat.com/programming/py).


### RB {#RB}
```
public static final FileType RB
```


表示一个 Ruby 源代码 (.rb) 文件。
了解有关此文件格式的更多信息 [here](../https://docs.fileformat.com/programming/rb).


### RST {#RST}
```
public static final FileType RST
```


表示一个 reStructuredText 文件 (.rst)。
了解有关此文件格式的更多信息 [here](../https://docs.fileformat.com/programming/rst).


### SASS {#SASS}
```
public static final FileType SASS
```


表示一个 Syntactically Awesome StyleSheets 文件 (.sass)。
了解有关此文件格式的更多信息 [here](../https://docs.fileformat.com/web/sass).


### SCALA {#SCALA}
```
public static final FileType SCALA
```


表示一个 Scala 源代码文件 (.scala)。
了解有关此文件格式的更多信息 [here](../https://docs.fileformat.com/programming/scala).


### SCM {#SCM}
```
public static final FileType SCM
```


表示一个 Scheme 源代码文件 (.scm)。
了解有关此文件格式的更多信息 [here](../https://docs.fileformat.com/programming/scm).


### SCRIPT {#SCRIPT}
```
public static final FileType SCRIPT
```


表示一个通用脚本文件 (.script)。
了解有关此文件格式的更多信息 [here](../https://docs.fileformat.com/programming/script).


### SH {#SH}
```
public static final FileType SH
```


表示一个 Bash Shell 脚本 (.sh)。
了解有关此文件格式的更多信息 [here](../https://docs.fileformat.com/cs/programming/sh).


### SML {#SML}
```
public static final FileType SML
```


表示一个 Standard ML 源代码文件 (.sml)。
了解更多关于此文件格式的信息，请点击[此处](../https://fileinfo.com/extension/sml)。


### SQL {#SQL}
```
public static final FileType SQL
```


表示一个结构化查询语言数据文件 (.sql)。
了解更多关于此文件格式的信息，请点击[此处](../https://fileinfo.com/extension/sql)。


### VIM {#VIM}
```
public static final FileType VIM
```


表示一个 Vim 设置文件 (.vim)。
了解更多关于此文件格式的信息，请点击[此处](../https://fileinfo.com/extension/vim)。


### YAML {#YAML}
```
public static final FileType YAML
```


表示一个 YAML 文档 (.yaml)。
了解更多关于此文件格式的信息，请点击[此处](../https://docs.fileformat.com/programming/yaml)。


### DOC {#DOC}
```
public static final FileType DOC
```


表示一个 Microsoft Word 文档 (.doc) 文件。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/word-processing/doc)。


### DOCX {#DOCX}
```
public static final FileType DOCX
```


表示一个 Microsoft Word Open XML 文档 (.docx) 文件。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/word-processing/docx)。


### CHM {#CHM}
```
public static final FileType CHM
```


表示一个 Microsoft 编译的 HTML 帮助文件 (.chm)。
了解更多关于此文件格式的信息，请点击[此处](../https://docs.fileformat.com/web/chm)。


### DOCM {#DOCM}
```
public static final FileType DOCM
```


表示一个 Word Open XML 宏启用文档 (.docm) 文件。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/word-processing/docm)。


### DOT {#DOT}
```
public static final FileType DOT
```


表示一个 Word 文档模板 (.dot) 文件。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/word-processing/dot)。


### DOTX {#DOTX}
```
public static final FileType DOTX
```


表示一个 Word Open XML 文档模板 (.dotx) 文件。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/word-processing/dotx)。


### DOTM {#DOTM}
```
public static final FileType DOTM
```


表示一个 Word Open XML 宏启用文档模板 (.dotm) 文件。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/word-processing/dotm)。


### RTF {#RTF}
```
public static final FileType RTF
```


表示一个富文本格式文件 (.rtf)。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/word-processing/rtf)。


### TXT {#TXT}
```
public static final FileType TXT
```


表示一个纯文本文件 (.txt)。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/word-processing/txt)。


### ODT {#ODT}
```
public static final FileType ODT
```


表示一个 OpenDocument 文本文档 (.odt)。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/word-processing/odt)。


### OTT {#OTT}
```
public static final FileType OTT
```


表示一个 OpenDocument 文档模板 (.ott)。
它是一个符合 OASIS 的 OpenDocument 标准格式生成的模板文档。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/word-processing/ott)。


### VCF {#VCF}
```
public static final FileType VCF
```


表示一个 vCard 文件 (.vcf)，它是一种用于存储联系信息的数字文件格式。
它被广泛用于流行的信息交换应用之间的数据互换。
了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/email/vcf)。


### AI {#AI}
```
public static final FileType AI
```


表示一个 Adobe Illustrator 文件 (.ai)，它是一种用于 Adobe Illustrator 绘图的文件格式。
了解更多关于此文件格式的信息，请点击[此处](../https://docs.fileformat.com/image/ai)。


### PSM1 {#PSM1}
```
public static final FileType PSM1
```


表示一个 PowerShell 脚本模块文件 (.psm1)。
它是一种用于 PowerShell 模块脚本的文件格式。
了解更多关于此文件格式的信息，请点击[此处](../https://fileinfo.com/extension/psm1)。


### PS1 {#PS1}
```
public static final FileType PS1
```


表示一个 PowerShell 脚本文件 (.ps1)。
它是一种用于 Windows PowerShell Cmdlet 文件的文件格式。
了解更多关于此文件格式的信息，请点击[此处](../https://fileinfo.com/extension/ps1)。


### PSD1 {#PSD1}
```
public static final FileType PSD1
```


表示一个 PowerShell 脚本模块清单文件 (.psd1)。
它是一种用于 PowerShell 模块清单脚本的文件格式。
了解更多关于此文件格式的信息，请点击[此处](../https://fileinfo.com/extension/psd1)。


### values() {#values--}
```
public static FileType[] values()
```




**Returns:**
com.groupdocs.viewer.FileType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static FileType valueOf(String name)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


将文件扩展名映射到文件类型。


此方法接受文件扩展名（可带或不带句点 \".\"），如果受支持，则返回相应的文件类型。
如果文件类型不受支持，则返回默认的 [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) 文件类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 扩展名 | java.lang.String | 文件扩展名，可带或不带句点 \".\"。 |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromFilePath(String filePath) {#fromFilePath-java.lang.String-}
```
public static FileType fromFilePath(String filePath)
```


从文件名或文件路径中提取文件扩展名并将其映射到文件类型。


如果文件类型受支持，方法返回相应的
FileType
,
否则返回默认的 [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) 文件类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 文件名或文件路径。 |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromMediaType(String mediaType) {#fromMediaType-java.lang.String-}
```
public static FileType fromMediaType(String mediaType)
```


将文件媒体类型映射到文件类型。例如，'application/pdf' 将映射为 [PDF](../../com.groupdocs.viewer/filetype#PDF)。


此方法接受文件媒体类型作为输入，并将其映射到相应的
FileType
。如果媒体类型是
受支持的，方法返回相应的文件类型。如果媒体类型不受支持，则返回默认的
[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | mediaType | java.lang.String | 文件媒体类型，例如 'application/pdf'。 |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if found, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream stream)
```


通过读取文件签名检测文件类型。


此方法接受表示文件的输入流，并尝试通过分析文件签名来检测其文件类型。该
文件签名是文件开头的唯一字节序列，用于指示其文件类型。该方法
从输入流读取文件签名，并将其与已知的受支持文件类型的文件签名进行匹配。
如果找到匹配，方法返回相应的文件类型。如果未找到匹配，则返回默认的
[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | stream | java.io.InputStream | 表示该文件的输入流。 |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, String password) {#fromStream-java.io.InputStream-java.lang.String-}
```
public static FileType fromStream(InputStream stream, String password)
```


通过读取文件签名检测文件类型。


此方法分析文件签名（文件开头的唯一字节序列），以确定
文件类型。它从提供的输入流读取文件签名，并将其与已知的文件签名进行匹配
受支持的文件类型。如果找到匹配，方法返回相应的文件类型。如果未找到匹配，则
返回默认的 [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) 文件类型。


如果文件已加密并且需要密码打开，则应将密码作为参数提供给此
方法。密码将用于解密文件并分析其签名以确定文件类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | stream | java.io.InputStream | 表示该文件的输入流。 |
|
|  | 密码 | java.lang.String | 用于打开文件的密码。 |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, ILogger logger) {#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, ILogger logger)
```


通过读取文件签名检测文件类型。


此方法分析文件签名（文件开头的唯一字节序列），以确定
文件类型。它从提供的输入流读取文件签名，并将其与已知的文件签名进行匹配
受支持的文件类型。如果找到匹配，方法返回相应的文件类型。如果未找到匹配，则
返回默认的 [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) 文件类型。


可以提供日志记录器以记录文件类型检测过程中的任何相关信息或错误。日志记录器
应实现 ILogger 接口。如果未提供日志记录器，检测过程将不会产生任何
日志输出。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | stream | java.io.InputStream | 表示该文件的输入流。 |
|
|  | 日志记录器 | com.groupdocs.foundation.logging.ILogger | 用于记录信息或错误的日志记录器。 |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, String password, ILogger logger) {#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, String password, ILogger logger)
```


通过读取文件签名检测文件类型。


此方法分析文件签名（文件开头的唯一字节序列），以确定
文件类型。它从提供的输入流读取文件签名，并将其与已知的文件签名进行匹配
受支持的文件类型。如果找到匹配，方法返回相应的文件类型。如果未找到匹配，则
返回默认的 [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) 文件类型。


如果文件已加密或受保护，可以提供密码。密码将在打开文件之前使用
分析文件签名。如果文件不需要密码，此参数可以设为 null。


可以提供日志记录器以记录文件类型检测过程中的任何相关信息或错误。日志记录器
应实现 ILogger 接口。如果未提供日志记录器，检测过程将不会产生任何
日志输出。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | stream | java.io.InputStream | 表示该文件的输入流。 |
|
|  | 密码 | java.lang.String | 用于打开文件的密码。 |
|
|  | 日志记录器 | com.groupdocs.foundation.logging.ILogger | 用于记录信息或错误的日志记录器。 |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


检索受支持的文件类型。


此方法返回系统支持的所有文件类型的序列。文件类型代表各种
系统可以处理或识别的文档格式。
***Learn more**
* Learn more about the supported document formats: [Full list of supported file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/)*


**Returns:**
java.util.List<com.groupdocs.viewer.FileType> - 支持的文件类型序列。

### detectCharset(String filePath) {#detectCharset-java.lang.String-}
```
public static Charset detectCharset(String filePath)
```


尝试通过路径检测文本 [TXT](../../com.groupdocs.viewer/filetype#TXT)、[TSV](../../com.groupdocs.viewer/filetype#TSV) 和 [CSV](../../com.groupdocs.viewer/filetype#CSV) 文件的字符集。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 文件名或文件路径。 |
|

**Returns:**
java.nio.charset.Charset - 当无法检测文件字符集时返回字符集或 null。

**Example:**


Charset charset = FileType.detectCharset("message.txt");
     

### detectCharset(InputStream stream) {#detectCharset-java.io.InputStream-}
```
public static Charset detectCharset(InputStream stream)
```


尝试通过流检测文本 [TXT](../../com.groupdocs.viewer/filetype#TXT)、[TSV](../../com.groupdocs.viewer/filetype#TSV) 和 [CSV](../../com.groupdocs.viewer/filetype#CSV) 文件的字符集。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | stream | java.io.InputStream | 文件流。 |
|

**Returns:**
java.nio.charset.Charset - 当无法检测文件字符集时返回字符集或 null。

**Example:**


InputStream stream = new FileInputStream("message.txt");
Charset charset = FileType.detectCharset(stream);
     

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


获取文件格式的名称，例如 "Microsoft Word Document"。


**Returns:**
java.lang.String - 文件格式的名称。

### getExtension() {#getExtension--}
```
public final String getExtension()
```


获取文件扩展名后缀（包括句点 "."），例如 ".doc"。


**Returns:**
java.lang.String - 文件扩展名后缀。

### toString() {#toString--}
```
public String toString()
```


返回当前对象的字符串表示。


**Returns:**
java.lang.String - 当前对象的字符串表示。

