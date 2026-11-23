---
title: "FileType 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "表示一种文件类型，并提供获取 GroupDocs.Viewer 支持的所有文件类型列表的方法。"
type: docs
url: /zh/python-net/groupdocs.viewer/filetype/
is_root: false
weight: 10
---


## FileType class

表示一种文件类型，并提供获取 GroupDocs.Viewer 支持的所有文件类型列表的方法。

FileType 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/) | 初始化一个新的 [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) 实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/#file_format-extension) | 初始化一个新的 FileType 实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#file_path) | 通过路径检测文本 TXT、TSV 和 CSV 文件的编码。 |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#stream) | 尝试从流中检测文本文件（TXT、TSV、CSV）的编码。 |
| [detect_encoding_file](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_file/) |  |
| [detect_encoding_stream](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_stream/) |  |
| [detect_encoding_streams](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_streams/) |  |
| [detect_encoding_string](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_string/) |  |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#other) | 确定当前的 [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) 是否与指定的 [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) 相同。 |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#obj) | 确定当前的 [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) 是否与指定的对象相同。 |
| [equals_file_type](/viewer/python-net/groupdocs.viewer/filetype/equals_file_type/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer/filetype/equals_object/) |  |
| [from_extension](/viewer/python-net/groupdocs.viewer/filetype/from_extension/#extension) | 将文件扩展名映射到文件类型。 |
| [from_file_path](/viewer/python-net/groupdocs.viewer/filetype/from_file_path/#file_path) | 提取文件扩展名并将其映射到文件类型。 |
| [from_media_type](/viewer/python-net/groupdocs.viewer/filetype/from_media_type/#media_type) | 将文件媒体类型映射到 [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)（例如，'application/pdf' 映射到 [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)）。 |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream) | 通过读取文件签名检测文件类型。 |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password) | 通过读取文件签名检测文件类型。 |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-logger) | 通过读取文件签名检测文件类型。 |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password-logger) | 通过读取文件签名检测文件类型。 |
| [from_stream_file](/viewer/python-net/groupdocs.viewer/filetype/from_stream_file/) |  |
| [from_stream_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream_stream/) |  |
| [from_stream_streams](/viewer/python-net/groupdocs.viewer/filetype/from_stream_streams/) |  |
| [from_stream_string](/viewer/python-net/groupdocs.viewer/filetype/from_stream_string/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer/filetype/get_hash_code/) | 返回当前 [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) 对象的哈希码。 |
| [get_supported_file_types](/viewer/python-net/groupdocs.viewer/filetype/get_supported_file_types/) | 检索受支持的文件类型。 |
| [to_string](/viewer/python-net/groupdocs.viewer/filetype/to_string/) | 返回表示当前对象的字符串。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [extension](/viewer/python-net/groupdocs.viewer/filetype/extension/) | 文件名后缀（包括句点 "."），例如 ".doc"。 |
| [file_format](/viewer/python-net/groupdocs.viewer/filetype/file_format/) | 文件类型名称，例如 "Microsoft Word Document"。 |

### 字段
| 字段 | 描述 |
| :- | :- |
| [UNKNOWN](/viewer/python-net/groupdocs.viewer/filetype/unknown/) | 表示未知的文件类型。 |
| [ZIP](/viewer/python-net/groupdocs.viewer/filetype/zip/) | 压缩文件（.zip）表示可以容纳一个或多个文件或目录的归档。了解此文件格式的更多信息，请点击此处。 |
| [TAR](/viewer/python-net/groupdocs.viewer/filetype/tar/) | 统一 Unix 文件归档（.tar）是使用基于 Unix 的工具创建的，用于收集一个或多个文件的归档。了解此文件格式的更多信息，请点击此处。 |
| [XZ](/viewer/python-net/groupdocs.viewer/filetype/xz/) | XZ 文件（.xz）是一种使用基于 LZMA 算法的高压缩比算法压缩的归档。了解此文件格式的更多信息，请点击此处。 |
| [TXZ](/viewer/python-net/groupdocs.viewer/filetype/txz/) | 统一 Unix 文件归档（.txz、.tar.xz）是使用基于 Unix 的工具创建的，用于收集一个或多个文件的归档。了解此文件格式的更多信息，请点击此处。 |
| [TARXZ](/viewer/python-net/groupdocs.viewer/filetype/tarxz/) | 统一 Unix 文件归档（.txz、.tar.xz）是使用基于 Unix 的工具创建的，用于收集一个或多个文件的归档。了解此文件格式的更多信息，请点击此处。 |
| [TGZ](/viewer/python-net/groupdocs.viewer/filetype/tgz/) | 统一 Unix 文件归档（.tgz、.tar.gz）是使用基于 Unix 的工具创建的，用于收集一个或多个文件的归档。了解此文件格式的更多信息，请点击此处。 |
| [TARGZ](/viewer/python-net/groupdocs.viewer/filetype/targz/) | 统一 Unix 文件归档（.tgz、.tar.gz）是使用基于 Unix 的工具创建的，用于收集一个或多个文件的归档。了解此文件格式的更多信息，请点击此处。 |
| [BZ2](/viewer/python-net/groupdocs.viewer/filetype/bz2/) | Bzip2 压缩文件（.bz2）是使用 BZIP2 开源压缩方法生成的压缩文件，主要在 UNIX 或 Linux 系统上使用。了解此文件格式的更多信息，请点击此处。 |
| [RAR](/viewer/python-net/groupdocs.viewer/filetype/rar/) | Roshal ARchive（.rar）是使用 RAR（WINRAR）压缩方法生成的压缩文件。了解更多关于此文件格式的信息。 |
| [GZ](/viewer/python-net/groupdocs.viewer/filetype/gz/) | Gnu Zipped File（.gz）是使用 gzip 压缩应用程序创建的压缩文件。它可以包含多个压缩文件，且常用于 UNIX 和 Linux 系统。了解更多关于此文件格式的信息。 |
| [GZIP](/viewer/python-net/groupdocs.viewer/filetype/gzip/) | Gnu Zipped File（.gzip）作为一种免费工具推出，用于替代 Unix 系统中使用的 Compress 程序。这类文件可以通过多种应用程序打开和解压，例如在 Windows 和 macOS 上均可使用的 WinZip。了解更多关于此文件格式的信息。 |
| [SEVEN_ZIP](/viewer/python-net/groupdocs.viewer/filetype/seven_zip/) | 7Zip（.7z、.7zip）是一款使用 LZMA 和 LZMA2 压缩的免费开源归档工具。了解更多关于此文件格式的信息。 |
| [CPIO](/viewer/python-net/groupdocs.viewer/filetype/cpio/) | Cpio 是一种通用文件归档实用程序及其关联的文件格式，主要安装在类 Unix 操作系统上。了解更多关于此文件格式的信息。 |
| [ZSTANDARD](/viewer/python-net/groupdocs.viewer/filetype/zstandard/) | ZST 文件是使用 Zstandard（zstd）压缩算法生成的压缩文件，采用无损压缩。ZST 文件可用于压缩数据库、文件系统、网络和游戏等多种类型的文件。了解更多关于此文件格式的信息。 |
| [TZST](/viewer/python-net/groupdocs.viewer/filetype/tzst/) | TZST 文件（.tar.zst、.tzst）是 Zstandard（ZST）归档，其中内部包含由 Unix 工具创建的合并 Unix 文件归档（Tar），用于收集一个或多个文件。 |
| [TAR_ZST](/viewer/python-net/groupdocs.viewer/filetype/tar_zst/) | TZST 文件（.tar.zst、.tzst）是 Zstandard（ZST）归档，其中内部包含由 Unix 工具创建的合并 Unix 文件归档（Tar），用于收集一个或多个文件。 |
| [ISO](/viewer/python-net/groupdocs.viewer/filetype/iso/) | ISO 光盘映像是一种未压缩的归档磁盘映像文件，基于 ISO-9660 标准，表示光盘（如 CD 或 DVD）上完整数据的内容。了解更多关于此文件格式的信息。 |
| [LHA](/viewer/python-net/groupdocs.viewer/filetype/lha/) | LHA 或 LZH 是一种免费压缩实用程序及其关联的文件格式。了解更多关于此文件格式的信息。 |
| [CAB](/viewer/python-net/groupdocs.viewer/filetype/cab/) | Cabinet（或 CAB）是 Microsoft Windows 使用的归档文件格式。了解更多关于此文件格式的信息。 |
| [DXF](/viewer/python-net/groupdocs.viewer/filetype/dxf/) | Drawing Exchange Format 文件（.dxf）是 AutoCAD 绘图文件的标记数据表示。了解更多关于此文件格式的信息。 |
| [DWG](/viewer/python-net/groupdocs.viewer/filetype/dwg/) | AutoCAD 绘图数据库文件（.dwg）是用于存储 2D 和 3D 设计数据的专有二进制文件。与 ASCII 格式的 DXF 不同，DWG 代表 CAD（计算机辅助设计）绘图的二进制文件格式。了解更多关于此文件格式的信息。 |
| [DWT](/viewer/python-net/groupdocs.viewer/filetype/dwt/) | AutoCAD 绘图模板（.dwt）是用于创建可保存为 DWG 文件的绘图的起始模板文件。了解更多关于此文件格式的信息。 |
| [STL](/viewer/python-net/groupdocs.viewer/filetype/stl/) | 立体光刻文件（.stl）是一种可互换的文件格式，表示三维表面几何形状。该格式在快速原型、3D 打印和计算机辅助制造等多个领域中使用。了解更多关于此文件格式的信息。 |
| [IFC](/viewer/python-net/groupdocs.viewer/filetype/ifc/) | Industry Foundation Classes 文件（.ifc）是一种建立了国际标准的文件格式，用于导入和导出建筑对象及其属性。该格式实现了不同软件应用之间的互操作性。了解更多关于此文件格式的信息。 |
| [DWF](/viewer/python-net/groupdocs.viewer/filetype/dwf/) | Design Web Format 文件（.dwf）以压缩格式表示用于查看、审阅或打印设计文件的 2D/3D 绘图。它包含作为设计数据一部分的图形和文本，并因压缩而减小文件大小。了解更多关于此文件格式的信息。 |
| [FBX](/viewer/python-net/groupdocs.viewer/filetype/fbx/) | Autodesk FBX 交换文件（FilmBoX）（.fbx）是一种 3D 模型格式。了解更多关于此文件格式的信息。 |
| [DWFX](/viewer/python-net/groupdocs.viewer/filetype/dwfx/) | Design Web Format 文件 XPS（.dwfx）以压缩的 XPS 文档形式表示用于查看、审阅或打印设计文件的 2D/3D 绘图。它包含作为设计数据一部分的图形和文本，并因压缩而减小文件大小。了解更多关于此文件格式的信息。 |
| [DGN](/viewer/python-net/groupdocs.viewer/filetype/dgn/) | MicroStation 设计文件（.dgn）是由 MicroStation、Intergraph Interactive Graphics Design System 等 CAD 应用创建并支持的绘图。了解更多关于此文件格式的信息。 |
| [PLT](/viewer/python-net/groupdocs.viewer/filetype/plt/) | PLT（HPGL）（.plt）是 Autodesk, Inc. 推出的基于矢量的绘图仪文件，包含特定 CAD 文件的信息。绘图细节在生产中需要精确和精准，使用 PLT 文件可保证所有图像以线条而非点的方式打印。了解更多关于此文件格式的信息。 |
| [CF2](/viewer/python-net/groupdocs.viewer/filetype/cf2/) | 通用文件格式文件。了解更多关于此文件格式的信息。 |
| [OBJ](/viewer/python-net/groupdocs.viewer/filetype/obj/) | Wavefront 3D 对象文件（.obj）是由 Wavefront Technologies 推出的 3D 图像文件。了解更多关于此文件格式的信息。 |
| [HPG](/viewer/python-net/groupdocs.viewer/filetype/hpg/) | PLT（HPGL）（.hpg） |
| [IGS](/viewer/python-net/groupdocs.viewer/filetype/igs/) | 初始图形交换规范（IGES）（.igs） |
| [VSD](/viewer/python-net/groupdocs.viewer/filetype/vsd/) | Visio 绘图文件（.vsd）是使用 Microsoft Visio 应用创建的绘图，用于表示各种图形对象及其相互连接。了解更多关于此文件格式的信息。 |
| [VSDX](/viewer/python-net/groupdocs.viewer/filetype/vsdx/) | Visio Drawing (.vsdx) 表示自 Microsoft Office 2013 起引入的 Microsoft Visio 文件格式。它是为取代早期版本 Microsoft Visio 支持的二进制文件格式 .VSD 而开发的。了解更多关于此文件格式的信息。 |
| [VSS](/viewer/python-net/groupdocs.viewer/filetype/vss/) | Visio Stencil File(.vss) 是使用 Microsoft Visio 2007 及更早版本创建的模板文件。模板文件提供可包含在 .VSD Visio 绘图中的绘图对象。了解更多关于此文件格式的信息。 |
| [VSSX](/viewer/python-net/groupdocs.viewer/filetype/vssx/) | Visio Stencil File (.vssx) 是使用 Microsoft Visio 2013 及以上版本创建的绘图模板。VSSX 文件格式可在 Visio 2013 及以上版本中打开。Visio 文件以表示各种绘图元素而闻名，例如形状集合、连接器、流程图、网络布局、UML 图表。了解更多关于此文件格式的信息。 |
| [VSDM](/viewer/python-net/groupdocs.viewer/filetype/vsdm/) | Visio Macro-Enabled Drawing (.vsdm) 是由支持宏的 Microsoft Visio 应用程序创建的绘图文件。VSDM 文件是类似于 VSDX 的 OPC/XML 绘图，但还具备在打开文件时运行宏的能力。了解更多关于此文件格式的信息。 |
| [VST](/viewer/python-net/groupdocs.viewer/filetype/vst/) | Visio Drawing Template (.vst) 是使用 Microsoft Visio 创建的矢量图像文件，充当创建后续文件的模板。这些模板文件采用二进制文件格式，包含用于创建新 Visio 绘图的默认布局和设置。了解更多关于此文件格式的信息。 |
| [VSTX](/viewer/python-net/groupdocs.viewer/filetype/vstx/) | Visio Drawing Template (.vstx) 是使用 Microsoft Visio 2013 及以上版本创建的绘图模板文件。这些 VSTX 文件提供了创建 Visio 绘图（保存为 .VSDX 文件）的起始点，并包含默认布局和设置。了解更多关于此文件格式的信息。 |
| [VSTM](/viewer/python-net/groupdocs.viewer/filetype/vstm/) | Visio Macro-Enabled Drawing Template (.vstm) 是由支持宏的 Microsoft Visio 创建的模板文件。与 VSDX 文件不同，使用 VSTM 模板创建的文件可以运行在 Visual Basic for Applications (VBA) 代码中开发的宏。了解更多关于此文件格式的信息。 |
| [VSSM](/viewer/python-net/groupdocs.viewer/filetype/vssm/) | Visio Macro-Enabled Stencil File (.vssm) 是支持宏的 Microsoft Visio 模板文件。打开 VSSM 文件后即可运行宏，以实现对图表中形状的所需格式化和放置。了解更多关于此文件格式的信息。 |
| [VSX](/viewer/python-net/groupdocs.viewer/filetype/vsx/) | Visio Stencil XML File (.vsx) 指用于在 Microsoft Visio 中创建图表的包含绘图和形状的模板。VSX 文件以 XML 文件格式保存，并在 Visio 2013 之前受支持。了解更多关于此文件格式的信息。 |
| [VTX](/viewer/python-net/groupdocs.viewer/filetype/vtx/) | Visio Template XML File (.vtx) 是以 XML 文件格式保存到磁盘的 Microsoft Visio 绘图模板。该模板旨在提供一个具有基本设置的文件，可用于创建多个具有相同设置的 Visio 文件。了解更多关于此文件格式的信息。 |
| [VDW](/viewer/python-net/groupdocs.viewer/filetype/vdw/) | Visio Web Drawing (.vdw) 表示用于渲染 Web 绘图所需的流和存储的文件格式。了解更多关于此文件格式的信息。 |
| [VDX](/viewer/python-net/groupdocs.viewer/filetype/vdx/) | Visio Drawing XML File (.vdx) 表示在 Microsoft Visio 中创建的任何绘图或图表，但以 XML 格式保存，扩展名为 .VDX。Visio 绘图 XML 文件是在 Microsoft 开发的 Visio 软件中创建的。了解更多关于此文件格式的信息。 |
| [EPUB](/viewer/python-net/groupdocs.viewer/filetype/epub/) | Open eBook File (.epub) 是一种为出版商和消费者提供标准数字出版格式的电子书文件格式。该格式已相当普及，受到众多电子阅读器和软件应用的支持。了解更多关于此文件格式的信息。 |
| [MOBI](/viewer/python-net/groupdocs.viewer/filetype/mobi/) | Mobipocket eBook (.mobi) 是最广泛使用的电子书文件格式之一。该格式是对旧的 OEB（Open Ebook Format）格式的改进，并曾作为 Mobipocket Reader 的专有格式。了解更多关于此文件格式的信息。 |
| [AZW3](/viewer/python-net/groupdocs.viewer/filetype/azw3/) | Amazon Kindle Format 8 (KF8) 电子书是为 Amazon Kindle 设备开发的数字文件格式。该格式是对旧的 AZW 文件的改进，仅在 Kindle Fire 设备上使用，并向后兼容其前身文件格式，即 MOBI 和 AZW。了解更多关于此文件格式的信息。 |
| [MSG](/viewer/python-net/groupdocs.viewer/filetype/msg/) | Outlook Mail Message (.msg) 是 Microsoft Outlook 和 Exchange 用于存储电子邮件、联系人、约会或其他任务的文件格式。了解更多关于此文件格式的信息。 |
| [EML](/viewer/python-net/groupdocs.viewer/filetype/eml/) | E-Mail Message (.eml) 表示使用 Outlook 等相关应用程序保存的电子邮件。几乎所有电子邮件客户端都支持此文件格式，因为它符合 RFC-822 Internet Message Format 标准。了解更多关于此文件格式的信息。 |
| [NSF](/viewer/python-net/groupdocs.viewer/filetype/nsf/) | Lotus Notes Database (.nsf) 了解更多关于此文件格式的信息。 |
| [MBOX](/viewer/python-net/groupdocs.viewer/filetype/mbox/) | Email Mailbox File (.mbox) 了解更多关于此文件格式的信息。 |
| [EMLX](/viewer/python-net/groupdocs.viewer/filetype/emlx/) | Apple Mail Message (.emlx) 由 Apple 实现和开发。Apple Mail 应用程序使用 EMLX 文件格式导出电子邮件。了解更多关于此文件格式的信息。 |
| [PST](/viewer/python-net/groupdocs.viewer/filetype/pst/) | Outlook Personal Information Store File (.pst) 表示 Outlook 个人存储文件（亦称个人存储表），用于存储各种用户信息。了解更多关于此文件格式的信息。 |
| [OST](/viewer/python-net/groupdocs.viewer/filetype/ost/) | Outlook Offline Data File (.ost) 表示用户在使用 Microsoft Outlook 注册 Exchange Server 后，在本地机器上离线模式下的邮箱数据。了解更多关于此文件格式的信息。 |
| [TIF](/viewer/python-net/groupdocs.viewer/filetype/tif/) | Tagged Image File (.tif) 表示用于各种符合此文件格式标准的设备的光栅图像。它能够在多种色彩空间中描述二值、灰度、调色板颜色和全彩图像数据。了解更多关于此文件格式的信息。 |
| [TIFF](/viewer/python-net/groupdocs.viewer/filetype/tiff/) | Tagged Image File Format (.tiff) 表示用于各种符合此文件格式标准的设备的光栅图像。它能够在多种色彩空间中描述二值、灰度、调色板颜色和全彩图像数据。了解更多关于此文件格式的信息。 |
| [JPG](/viewer/python-net/groupdocs.viewer/filetype/jpg/) | JPEG 图像（.jpg）是一种使用有损压缩方式保存的图像格式。压缩后的输出图像在存储大小和图像质量之间需要权衡。了解更多关于此文件格式的信息，请点击这里。 |
| [JPEG](/viewer/python-net/groupdocs.viewer/filetype/jpeg/) | JPEG 图像（.jpeg）是一种使用有损压缩方式保存的图像格式。压缩后的输出图像在存储大小和图像质量之间需要权衡。了解更多关于此文件格式的信息，请点击这里。 |
| [JFIF](/viewer/python-net/groupdocs.viewer/filetype/jfif/) | JPEG 文件交换格式（.jfif）是一种为在平台之间快速交换而开发的图像。此格式使用 JPEG 压缩。了解更多关于此文件格式的信息，请点击这里。 |
| [PNG](/viewer/python-net/groupdocs.viewer/filetype/png/) | 便携式网络图形（.png）是一种使用无损压缩的栅格图像文件格式。该文件格式被创建为图形交换格式（GIF）的替代品，并且没有版权限制。了解更多关于此文件格式的信息，请点击这里。 |
| [GIF](/viewer/python-net/groupdocs.viewer/filetype/gif/) | 图形交换格式文件（.gif）是一种高度压缩的图像。对于每张图像，GIF 通常支持每像素最多 8 位，并且整个图像最多允许 256 种颜色。了解更多关于此文件格式的信息，请点击这里。 |
| [APNG](/viewer/python-net/groupdocs.viewer/filetype/apng/) | 动画便携式网络图形（.apng）是 PNG 格式的扩展，支持动画。了解更多关于此文件格式的信息，请点击这里。 |
| [BMP](/viewer/python-net/groupdocs.viewer/filetype/bmp/) | 位图图像文件（.bmp）用于存储位图数字图像。这些图像独立于图形适配器，也称为设备无关位图（DIB）文件格式。了解更多关于此文件格式的信息，请点击这里。 |
| [TGA](/viewer/python-net/groupdocs.viewer/filetype/tga/) | Truevision TGA（Truevision 高级光栅适配器 - TARGA）用于存储由 TRUEVISION 开发的位图数字图像。了解更多关于此文件格式的信息，请点击这里。 |
| [ICO](/viewer/python-net/groupdocs.viewer/filetype/ico/) | 图标文件（.ico）是一种用于在 Microsoft Windows 上表示应用程序图标的图像文件类型。了解更多关于此文件格式的信息，请点击这里。 |
| [JP2](/viewer/python-net/groupdocs.viewer/filetype/jp2/) | JPEG 2000 核心图像文件（.jp2）是一种图像编码系统和最先进的图像压缩标准。了解更多关于此文件格式的信息，请点击这里。 |
| [JPF](/viewer/python-net/groupdocs.viewer/filetype/jpf/) | JPEG 2000 图像文件（.jpf） |
| [JPX](/viewer/python-net/groupdocs.viewer/filetype/jpx/) | JPEG 2000 图像文件（.jpx） |
| [JPM](/viewer/python-net/groupdocs.viewer/filetype/jpm/) | JPEG 2000 图像文件（.jpm） |
| [J2C](/viewer/python-net/groupdocs.viewer/filetype/j2c/) | JPEG 2000 代码流（.j2c） |
| [J2K](/viewer/python-net/groupdocs.viewer/filetype/j2k/) | JPEG 2000 代码流（.j2k）是一种使用小波压缩而非 DCT 压缩的图像。了解更多关于此文件格式的信息，请点击这里。 |
| [JPC](/viewer/python-net/groupdocs.viewer/filetype/jpc/) | JPEG 2000 代码流（.jpc） |
| [JLS](/viewer/python-net/groupdocs.viewer/filetype/jls/) | JPEG-LS（JLS）（.jls） |
| [DIB](/viewer/python-net/groupdocs.viewer/filetype/dib/) | 设备无关位图文件（.dib） |
| [WMF](/viewer/python-net/groupdocs.viewer/filetype/wmf/) | Windows 元文件（.wmf）是用于存储矢量和位图格式图像数据的 Microsoft Windows 元文件（WMF）。了解更多关于此文件格式的信息，请点击这里。 |
| [WMZ](/viewer/python-net/groupdocs.viewer/filetype/wmz/) | 压缩的 Windows 元文件（.wmz）是使用 GZIP 压缩的 Microsoft Windows 元文件（WMF），用于存储矢量和位图格式图像数据。了解更多关于此文件格式的信息，请点击这里。 |
| [EMF](/viewer/python-net/groupdocs.viewer/filetype/emf/) | 增强型 Windows 元文件（.emf）以设备无关方式表示图形图像。EMF 元文件由按时间顺序排列的可变长度记录组成，可在任何输出设备上解析后渲染存储的图像。了解更多关于此文件格式的信息，请点击这里。 |
| [EMZ](/viewer/python-net/groupdocs.viewer/filetype/emz/) | 压缩的增强型 Windows 元文件（.emz）以设备无关方式表示经 GZIP 压缩的图形图像。EMF 元文件由按时间顺序排列的可变长度记录组成，可在任何输出设备上解析后渲染存储的图像。了解更多关于此文件格式的信息，请点击这里。 |
| [WEBP](/viewer/python-net/groupdocs.viewer/filetype/webp/) | WebP 图像（.webp）是一种基于无损和有损压缩的现代栅格网络图像文件格式。它在显著减小图像尺寸的同时提供相同的图像质量。了解更多关于此文件格式的信息，请点击这里。 |
| [DNG](/viewer/python-net/groupdocs.viewer/filetype/dng/) | 数字负片规范（.dng）是一种用于存储原始文件的数码相机图像格式。该格式由 Adobe 于 2004 年 9 月开发，主要用于数字摄影。了解更多关于此文件格式的信息，请点击这里。 |
| [CDR](/viewer/python-net/groupdocs.viewer/filetype/cdr/) | CorelDraw 矢量图形绘图文件（.cdr）是一种由 CorelDRAW 原生创建的用于存储已编码和压缩的数字图像的矢量绘图文件。此类绘图文件包含文本、线条、形状、图像、颜色和效果，用于矢量表示图像内容。了解更多关于此文件格式的信息，请点击这里。 |
| [CMX](/viewer/python-net/groupdocs.viewer/filetype/cmx/) | Corel Exchange (.cmx) 是一种绘图图像文件，可能包含矢量图形以及位图图形。了解更多关于此文件格式的信息。 |
| [DJVU](/viewer/python-net/groupdocs.viewer/filetype/djvu/) | DjVu Image (.djvu) 是一种图形文件格式，旨在用于扫描文档和书籍，尤其是包含文本、图纸、图像和照片组合的文档。了解更多关于此文件格式的信息。 |
| [CGM](/viewer/python-net/groupdocs.viewer/filetype/cgm/) | Computer Graphics Metafile (.cgm) 是一种免费、平台无关的国际标准元文件格式，用于存储和交换矢量图形（2D）、光栅图形和文本。CGM 使用面向对象的方法并提供许多用于图像生成的功能。了解更多关于此文件格式的信息。 |
| [PCL](/viewer/python-net/groupdocs.viewer/filetype/pcl/) | Printer Command Language 文档 (.pcl) |
| [PSD](/viewer/python-net/groupdocs.viewer/filetype/psd/) | Adobe Photoshop Document (.psd) 表示 Adobe Photoshop 的原生文件格式，用于图形设计和开发。了解更多关于此文件格式的信息。 |
| [PSB](/viewer/python-net/groupdocs.viewer/filetype/psb/) | Photoshop Large Document Format (.psb) 表示用于图形设计和开发的 Photoshop 大文档格式。了解更多关于此文件格式的信息。 |
| [DCM](/viewer/python-net/groupdocs.viewer/filetype/dcm/) | DICOM Image (.dcm) 表示存储患者医学信息（如 MRI、CT 扫描和超声图像）的数字图像。了解更多关于此文件格式的信息。 |
| [PS](/viewer/python-net/groupdocs.viewer/filetype/ps/) | PostScript 文件 (.ps) |
| [EPS](/viewer/python-net/groupdocs.viewer/filetype/eps/) | Encapsulated PostScript File (.eps) 描述一个封装的 PostScript 语言程序，用于描述单页的外观。了解更多关于此文件格式的信息。 |
| [ODG](/viewer/python-net/groupdocs.viewer/filetype/odg/) | OpenDocument Graphic File (.odg) 被 Apache OpenOffice 的 Draw 应用程序用于将绘图元素存储为矢量图像。了解更多关于此文件格式的信息。 |
| [FODG](/viewer/python-net/groupdocs.viewer/filetype/fodg/) | Flat XML ODF Template (.fodg) 被 Apache OpenOffice 的 Draw 应用程序用于将绘图元素存储为矢量图像。了解更多关于此文件格式的信息。 |
| [SVG](/viewer/python-net/groupdocs.viewer/filetype/svg/) | Scalable Vector Graphics File (.svg) 是一种可缩放矢量图形文件，使用基于 XML 的文本格式来描述图像的外观。了解更多关于此文件格式的信息。 |
| [SVGZ](/viewer/python-net/groupdocs.viewer/filetype/svgz/) | Scalable Vector Graphics File (.svgz) 是一种可缩放矢量图形文件，使用基于 XML 的文本格式，并通过 GZIP 压缩，以描述图像的外观。了解更多关于此文件格式的信息。 |
| [OTG](/viewer/python-net/groupdocs.viewer/filetype/otg/) | OpenDocument Graphic 模板 (.otg) |
| [HTM](/viewer/python-net/groupdocs.viewer/filetype/htm/) | Hypertext Markup Language File (.htm) 是用于在浏览器中显示的网页的扩展名。了解更多关于此文件格式的信息。 |
| [HTML](/viewer/python-net/groupdocs.viewer/filetype/html/) | Hypertext Markup Language File (.html) 是用于在浏览器中显示的网页的扩展名。了解更多关于此文件格式的信息。 |
| [MHT](/viewer/python-net/groupdocs.viewer/filetype/mht/) | MHTML Web 存档 (.mht) |
| [MHTML](/viewer/python-net/groupdocs.viewer/filetype/mhtml/) | MIME HTML 文件 (.mhtml) |
| [XML](/viewer/python-net/groupdocs.viewer/filetype/xml/) | XML File (.xml)。GroupDocs.Viewer 拥有用于处理 XML 文件的专用处理器，详见文档。 |
| [ONE](/viewer/python-net/groupdocs.viewer/filetype/one/) | OneNote Document (.one) 由 Microsoft OneNote 应用程序创建。OneNote 让您可以像使用草稿本记笔记一样收集信息。了解更多关于此文件格式的信息。 |
| [PDF](/viewer/python-net/groupdocs.viewer/filetype/pdf/) | Portable Document Format File (.pdf) 是 Adobe 在 1990 年代创建的一种文档类型。此文件格式的目的是引入一种独立于应用软件、硬件以及操作系统的文档和其他参考材料的表示标准。了解更多关于此文件格式的信息。 |
| [XPS](/viewer/python-net/groupdocs.viewer/filetype/xps/) | XML Paper Specification File (.xps) 表示基于 Microsoft 创建的 XML 纸张规范的页面布局文件。该格式由 Microsoft 开发，以取代 EMF 文件格式，类似于 PDF 文件格式，但在文档的布局、外观和打印信息中使用 XML。了解更多关于此文件格式的信息。 |
| [OXPS](/viewer/python-net/groupdocs.viewer/filetype/oxps/) | OpenXPS 文件 (.oxps) |
| [TEX](/viewer/python-net/groupdocs.viewer/filetype/tex/) | LaTeX Source Document (.tex) 是一种包含编程和标记特性的语言，用于排版文档。了解更多关于此文件格式的信息。 |
| [OFD](/viewer/python-net/groupdocs.viewer/filetype/ofd/) | Open Fixed-layout Document (OFD) 格式由 GB/T 33190-2016 定义，旨在取代中国公共机构中的 PDF。 |
| [PPT](/viewer/python-net/groupdocs.viewer/filetype/ppt/) | PowerPoint Presentation (.ppt) 表示 PowerPoint 文件，它由一系列幻灯片组成，用于以幻灯片放映方式显示。它指定了 Microsoft PowerPoint 97-2003 使用的二进制文件格式。了解更多关于此文件格式的信息。 |
| [PPTX](/viewer/python-net/groupdocs.viewer/filetype/pptx/) | PowerPoint Open XML Presentation (.pptx) 是使用流行的 Microsoft PowerPoint 应用程序创建的演示文稿文件。不同于之前的二进制 PPT 演示文稿格式，PPTX 基于 Microsoft PowerPoint 开放 XML 演示文稿文件格式。了解更多关于此文件格式的信息。 |
| [PPS](/viewer/python-net/groupdocs.viewer/filetype/pps/) | PowerPoint Slide Show (.pps) 是使用 Microsoft PowerPoint 为幻灯片放映目的创建的文件。PPS 文件的读取和创建受 Microsoft PowerPoint 97-2003 支持。了解更多关于此文件格式的信息。 |
| [PPSX](/viewer/python-net/groupdocs.viewer/filetype/ppsx/) | PowerPoint Open XML Slide Show (.ppsx) 文件是使用 Microsoft PowerPoint 2007 及以上版本为幻灯片放映目的创建的。了解更多关于此文件格式的信息。 |
| [ODP](/viewer/python-net/groupdocs.viewer/filetype/odp/) | OpenDocument Presentation (.odp) 表示 OpenOffice.org 在 OASIS Open 标准中使用的演示文稿文件格式。了解更多关于此文件格式的信息。 |
| [FODP](/viewer/python-net/groupdocs.viewer/filetype/fodp/) | OpenDocument Presentation (.fodp) 表示 OpenDocument 平面 XML 演示文稿。了解更多关于此文件格式的信息。 |
| [POT](/viewer/python-net/groupdocs.viewer/filetype/pot/) | PowerPoint Template (.pot) 表示由 PowerPoint 97-2003 版本创建的 Microsoft PowerPoint 模板文件。了解更多关于此文件格式的信息。 |
| [PPTM](/viewer/python-net/groupdocs.viewer/filetype/pptm/) | PowerPoint Open XML Macro-Enabled Presentation 是使用 Microsoft PowerPoint 2007 或更高版本创建的支持宏的演示文稿文件。了解更多关于此文件格式的信息。 |
| [POTX](/viewer/python-net/groupdocs.viewer/filetype/potx/) | PowerPoint Open XML Presentation Template (.potx) 表示使用 Microsoft PowerPoint 2007 及以上版本创建的 Microsoft PowerPoint 模板演示文稿。了解更多关于此文件格式的信息。 |
| [POTM](/viewer/python-net/groupdocs.viewer/filetype/potm/) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) 是支持宏的 Microsoft PowerPoint 模板文件。POTM 文件由 PowerPoint 2007 或以上版本创建，包含可用于创建进一步演示文稿的默认设置。了解更多关于此文件格式的信息。 |
| [PPSM](/viewer/python-net/groupdocs.viewer/filetype/ppsm/) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) 表示使用 Microsoft PowerPoint 2007 或更高版本创建的支持宏的幻灯片放映文件格式。了解更多关于此文件格式的信息。 |
| [OTP](/viewer/python-net/groupdocs.viewer/filetype/otp/) | OpenDocument Presentation Template (.otp) 表示由符合 OASIS OpenDocument 标准的应用程序创建的演示文稿模板文件。了解更多关于此文件格式的信息。 |
| [XLS](/viewer/python-net/groupdocs.viewer/filetype/xls/) | Excel Spreadsheet (.xls) 表示 Excel 二进制文件格式。这类文件可以由 Microsoft Excel 以及其他类似的电子表格程序（如 OpenOffice Calc 或 Apple Numbers）创建。了解更多关于此文件格式的信息。 |
| [EXCEL_2003XML](/viewer/python-net/groupdocs.viewer/filetype/excel_2003xml/) | Excel 2003 XML (SpreadsheetML) 表示 Excel 二进制文件格式。这类文件可以由 Microsoft Excel 以及其他类似的电子表格程序（如 OpenOffice Calc 或 Apple Numbers）创建。了解更多关于此文件格式的信息。 |
| [NUMBERS](/viewer/python-net/groupdocs.viewer/filetype/numbers/) | Apple numbers 表示类似 Excel 的二进制文件格式。这类文件可以由 Apple Numbers 应用程序创建。了解更多关于此文件格式的信息。 |
| [XLSX](/viewer/python-net/groupdocs.viewer/filetype/xlsx/) | Microsoft Excel Open XML Spreadsheet (.xlsx) 是一种广为人知的 Microsoft Excel 文档格式，随 Microsoft Office 2007 的发布而推出。了解更多关于此文件格式的信息。 |
| [XLSM](/viewer/python-net/groupdocs.viewer/filetype/xlsm/) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) 是一种支持宏的电子表格文件类型。了解更多关于此文件格式的信息。 |
| [XLSB](/viewer/python-net/groupdocs.viewer/filetype/xlsb/) | Excel Binary Spreadsheet (.xlsb) 指定了 Excel 二进制文件格式，它是一组记录和结构，用于定义 Excel 工作簿的内容。了解更多关于此文件格式的信息。 |
| [CSV](/viewer/python-net/groupdocs.viewer/filetype/csv/) | Comma Separated Values File (.csv) 表示包含以逗号分隔值的数据记录的纯文本文件。了解更多关于此文件格式的信息。 |
| [TSV](/viewer/python-net/groupdocs.viewer/filetype/tsv/) | Tab Separated Values File (.tsv) 表示以制表符分隔的数据的纯文本格式文件。了解更多关于此文件格式的信息。 |
| [ODS](/viewer/python-net/groupdocs.viewer/filetype/ods/) | OpenDocument Spreadsheet (.ods) 代表可由用户编辑的 OpenDocument 电子表格文档格式。数据以行列的形式存储在 ODF 文件中。了解更多关于此文件格式的信息。 |
| [FODS](/viewer/python-net/groupdocs.viewer/filetype/fods/) | OpenDocument Flat XML Spreadsheet (.fods) |
| [OTS](/viewer/python-net/groupdocs.viewer/filetype/ots/) | OpenDocument Spreadsheet Template (.ots) |
| [XLAM](/viewer/python-net/groupdocs.viewer/filetype/xlam/) | Microsoft Excel Add-in (.xlam) |
| [XLTM](/viewer/python-net/groupdocs.viewer/filetype/xltm/) | Microsoft Excel Macro-Enabled Template (.xltm) 表示由 Microsoft Excel 生成的支持宏的模板文件。XLTM 文件在结构上类似于 XLTX，但后者不支持创建带宏的模板文件。了解更多关于此文件格式的信息。 |
| [XLT](/viewer/python-net/groupdocs.viewer/filetype/xlt/) | Microsoft Excel 模板 (.xlt) 是使用 Microsoft Excel 创建的模板文件，Microsoft Excel 是 Microsoft Office 套件中的电子表格应用程序。Microsoft Office 97-2003 支持创建新的 XLT 文件以及打开这些文件。了解更多关于此文件格式的信息，请点击此处。 |
| [XLTX](/viewer/python-net/groupdocs.viewer/filetype/xltx/) | Excel Open XML 电子表格模板 (.xltx) 表示基于 Office OpenXML 文件格式规范的 Microsoft Excel 模板。它用于创建标准模板文件，可用于生成具有与 XLTX 文件中指定的相同设置的 XLSX 文件。了解更多关于此文件格式的信息，请点击此处。 |
| [SXC](/viewer/python-net/groupdocs.viewer/filetype/sxc/) | StarOffice Calc 电子表格 (.sxc) |
| [MPP](/viewer/python-net/groupdocs.viewer/filetype/mpp/) | Microsoft Project 文件 (.mpp) 是用于存储项目管理相关信息的 Microsoft Project 数据文件，采用集成方式。了解更多关于此文件格式的信息，请点击此处。 |
| [MPT](/viewer/python-net/groupdocs.viewer/filetype/mpt/) | Microsoft Project 模板 (.mpt) 包含用于创建 .MPP 文件的基本信息、结构以及文档设置。了解更多关于此文件格式的信息，请点击此处。 |
| [MPX](/viewer/python-net/groupdocs.viewer/filetype/mpx/) | Microsoft Project Exchange 文件 (.mpx) 是一种 ASCII 文件格式，用于在 Microsoft Project (MSP) 与其他支持 MPX 文件格式的应用程序（如 Primavera Project Planner、Sciforma 和 Timerline Precision Estimating）之间传输项目信息。了解更多关于此文件格式的信息，请点击此处。 |
| [AS_](/viewer/python-net/groupdocs.viewer/filetype/as_/) | ActionScript 文件 (.as) |
| [AS3](/viewer/python-net/groupdocs.viewer/filetype/as3/) | ActionScript 文件 (.as) |
| [ASM](/viewer/python-net/groupdocs.viewer/filetype/asm/) | 汇编语言源代码文件 (.asm) |
| [BAT](/viewer/python-net/groupdocs.viewer/filetype/bat/) | DOS 批处理文件 (.bat) |
| [C](/viewer/python-net/groupdocs.viewer/filetype/c/) | C/C++ 源代码文件 (.c) |
| [CC](/viewer/python-net/groupdocs.viewer/filetype/cc/) | C++ 源代码文件 (.cc) |
| [CMAKE](/viewer/python-net/groupdocs.viewer/filetype/cmake/) | CMake 文件 (.cmake) |
| [CPP](/viewer/python-net/groupdocs.viewer/filetype/cpp/) | C++ 源代码文件 (.cpp) |
| [CS](/viewer/python-net/groupdocs.viewer/filetype/cs/) | C# 源代码文件 (.cs) 是用于 C# 编程语言的源代码文件，由 Microsoft 引入以配合 .NET 框架使用。了解更多关于此文件格式的信息，请点击此处。 |
| [VB](/viewer/python-net/groupdocs.viewer/filetype/vb/) | Visual Basic 项目项文件 (.vb) 是使用 Visual Basic 语言创建的源代码文件，由 Microsoft 为 .NET 应用程序开发而创建。了解更多关于此文件格式的信息，请点击此处。 |
| [CSS](/viewer/python-net/groupdocs.viewer/filetype/css/) | 层叠样式表 (.css) |
| [CXX](/viewer/python-net/groupdocs.viewer/filetype/cxx/) | C++ 源代码文件 (.cxx) |
| [DIFF](/viewer/python-net/groupdocs.viewer/filetype/diff/) | 补丁文件 (.diff) |
| [ERB](/viewer/python-net/groupdocs.viewer/filetype/erb/) | Ruby ERB 脚本 (.erb) |
| [GROOVY](/viewer/python-net/groupdocs.viewer/filetype/groovy/) | Groovy 源代码文件 (.groovy) |
| [H](/viewer/python-net/groupdocs.viewer/filetype/h/) | C/C++/Objective-C 头文件 (.h) |
| [HAML](/viewer/python-net/groupdocs.viewer/filetype/haml/) | Haml 源代码文件 (.haml) |
| [HH](/viewer/python-net/groupdocs.viewer/filetype/hh/) | C++ 头文件 (.hh) |
| [JAVA](/viewer/python-net/groupdocs.viewer/filetype/java/) | Java 源代码文件 (.java) |
| [JS](/viewer/python-net/groupdocs.viewer/filetype/js/) | JavaScript 文件 (.js) |
| [JSON](/viewer/python-net/groupdocs.viewer/filetype/json/) | JavaScript 对象表示法文件 (.json) |
| [LESS](/viewer/python-net/groupdocs.viewer/filetype/less/) | LESS 样式表 (.less) |
| [LOG](/viewer/python-net/groupdocs.viewer/filetype/log/) | 日志文件 (.log) |
| [M](/viewer/python-net/groupdocs.viewer/filetype/m/) | Objective-C 实现文件 (.m) |
| [MAKE](/viewer/python-net/groupdocs.viewer/filetype/make/) | Xcode Makefile 脚本 (.make) |
| [MD](/viewer/python-net/groupdocs.viewer/filetype/md/) | Markdown 文档文件 (.md) |
| [ML](/viewer/python-net/groupdocs.viewer/filetype/ml/) | ML 源代码文件 (.ml) |
| [MM](/viewer/python-net/groupdocs.viewer/filetype/mm/) | Objective‑C++ 源文件 (.mm) |
| [PHP](/viewer/python-net/groupdocs.viewer/filetype/php/) | PHP 源代码文件 (.php) |
| [PL](/viewer/python-net/groupdocs.viewer/filetype/pl/) | Perl 脚本 (.pl) |
| [PROPERTIES](/viewer/python-net/groupdocs.viewer/filetype/properties/) | Java 属性文件 (.properties) |
| [PY](/viewer/python-net/groupdocs.viewer/filetype/py/) | Python 脚本 (.py) |
| [RB](/viewer/python-net/groupdocs.viewer/filetype/rb/) | Ruby 源代码 (.rb) |
| [RST](/viewer/python-net/groupdocs.viewer/filetype/rst/) | reStructuredText 文件 (.rst) |
| [SASS](/viewer/python-net/groupdocs.viewer/filetype/sass/) | Syntactically Awesome StyleSheets 文件 (.sass) |
| [SCALA](/viewer/python-net/groupdocs.viewer/filetype/scala/) | Scala 源代码文件 (.scala) |
| [SCM](/viewer/python-net/groupdocs.viewer/filetype/scm/) | Scheme 源代码文件 (.scm) |
| [SCRIPT](/viewer/python-net/groupdocs.viewer/filetype/script/) | 通用脚本文件 (.script) |
| [SH](/viewer/python-net/groupdocs.viewer/filetype/sh/) | Bash Shell 脚本 (.sh) |
| [SML](/viewer/python-net/groupdocs.viewer/filetype/sml/) | Standard ML 源代码文件 (.sml) |
| [SQL](/viewer/python-net/groupdocs.viewer/filetype/sql/) | 结构化查询语言数据文件 (.sql) |
| [VIM](/viewer/python-net/groupdocs.viewer/filetype/vim/) | Vim 设置文件 (.vim) |
| [YAML](/viewer/python-net/groupdocs.viewer/filetype/yaml/) | YAML 文档 (.yaml) |
| [DOC](/viewer/python-net/groupdocs.viewer/filetype/doc/) | Microsoft Word 文档 (.doc) 表示由 Microsoft Word 或其他文字处理程序生成的二进制文件格式文档。了解更多关于此文件格式的信息，请访问此处。 |
| [DOCX](/viewer/python-net/groupdocs.viewer/filetype/docx/) | Microsoft Word Open XML 文档 (.docx) 是一种广为人知的 Microsoft Word 文档格式。自 2007 年 Microsoft Office 2007 发布起，该文档格式的结构由纯二进制更改为 XML 与二进制文件的组合。了解更多关于此文件格式的信息，请访问此处。 |
| [CHM](/viewer/python-net/groupdocs.viewer/filetype/chm/) | Microsoft 编译 HTML 帮助文件 (.chm) 是一种广为人知的 HELP（某些应用程序的文档）文档格式。了解更多关于此文件格式的信息。 |
| [DOCM](/viewer/python-net/groupdocs.viewer/filetype/docm/) | Word Open XML 宏启用文档 (.docm) 是由 Microsoft Word 2007 或更高版本生成的文档，具备运行宏的能力。了解更多关于此文件格式的信息。 |
| [DOT](/viewer/python-net/groupdocs.viewer/filetype/dot/) | Word 文档模板 (.dot) 是由 Microsoft Word 创建的模板文件，具有预设格式设置，用于生成后续的 DOC 或 DOCX 文件。了解更多关于此文件格式的信息。 |
| [DOTX](/viewer/python-net/groupdocs.viewer/filetype/dotx/) | Word Open XML 文档模板 (.dotx) 是由 Microsoft Word 创建的模板文件，具有预设格式设置，用于生成后续的 DOCX 文件。了解更多关于此文件格式的信息。 |
| [DOTM](/viewer/python-net/groupdocs.viewer/filetype/dotm/) | Word Open XML 宏启用文档模板 (.dotm) 表示使用 Microsoft Word 2007 或更高版本创建的模板文件。了解更多关于此文件格式的信息。 |
| [RTF](/viewer/python-net/groupdocs.viewer/filetype/rtf/) | 富文本格式文件 (.rtf) 表示一种用于在应用程序中编码格式化文本和图形的方法。了解更多关于此文件格式的信息。 |
| [TXT](/viewer/python-net/groupdocs.viewer/filetype/txt/) | 纯文本文件 (.txt) 表示一种包含按行排列的纯文本的文档。了解更多关于此文件格式的信息。 |
| [ODT](/viewer/python-net/groupdocs.viewer/filetype/odt/) | OpenDocument 文本文件 (.odt) 是基于 OpenDocument 文本文件格式的文字处理应用程序创建的文档类型。了解更多关于此文件格式的信息。 |
| [OTT](/viewer/python-net/groupdocs.viewer/filetype/ott/) | OpenDocument 文档模板 (.ott) 表示符合 OASIS OpenDocument 标准格式的应用程序生成的模板文档。了解更多关于此文件格式的信息。 |
| [VCF](/viewer/python-net/groupdocs.viewer/filetype/vcf/) | vCard 文件 (.vcf) 是一种用于存储联系信息的数字文件格式。该格式被广泛用于流行的信息交换应用程序之间的数据互通。了解更多关于此文件格式的信息。 |
| [AI](/viewer/python-net/groupdocs.viewer/filetype/ai/) | Adobe Illustrator (.ai) 是一种用于 Adobe Illustrator 绘图的文件格式。了解更多关于此文件格式的信息。 |
| [PSM1](/viewer/python-net/groupdocs.viewer/filetype/psm1/) | PowerShell 脚本模块 (.psm1) 是一种用于 PowerShell 模块脚本的文件格式。了解更多关于此文件格式的信息。 |
| [PS1](/viewer/python-net/groupdocs.viewer/filetype/ps1/) | PowerShell 脚本文件 (.ps1) 是一种用于 Windows PowerShell Cmdlet 文件的文件格式。了解更多关于此文件格式的信息。 |
| [PSD1](/viewer/python-net/groupdocs.viewer/filetype/psd1/) | PowerShell 脚本模块清单 (.psd1) 是一种用于 PowerShell 模块清单脚本的文件格式。了解更多关于此文件格式的信息。 |

### 示例

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

# 加载文档时指定文件类型（例如，Markdown）
load_options = LoadOptions(FileType.MD)

# 将文档渲染为 PDF
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### 另见
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
