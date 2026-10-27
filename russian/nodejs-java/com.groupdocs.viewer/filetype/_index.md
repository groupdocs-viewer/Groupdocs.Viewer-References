---
title: "FileType"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Представляет тип файла."
type: docs
weight: 14
url: /ru/nodejs-java/com.groupdocs.viewer/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, com.groupdocs.viewer.caching.Cacheable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>, Cacheable
```

Представляет тип файла. Предоставляет методы для получения списка всех типов файлов, поддерживаемых компонентом GroupDocs.Viewer.

Перечисление FileType предоставляет константы, представляющие различные типы файлов, поддерживаемые компонентом GroupDocs.Viewer. Вы можете использовать методы этого перечисления для получения списка всех поддерживаемых типов файлов или проверки, поддерживается ли конкретный тип файла.

Пример использования:

```

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
 
```
## Поля

| Поле | Описание |
| --- | --- |
| [UNKNOWN](#UNKNOWN) | Представляет неизвестный тип файла. |
| [ZIP](#ZIP) | Представляет zip‑файл (.zip), который может содержать один или несколько файлов или каталогов. |
| [TAR](#TAR) | Представляет объединённый Unix‑архив (.tar), созданный для сбора одного или нескольких файлов. |
| [XZ](#XZ) | Представляет XZ‑файл (.xz), сжатый с использованием высокоэффективного алгоритма сжатия, основанного на алгоритме LZMA. |
| [TXZ](#TXZ) | Представляет объединённый Unix‑архив (.txz, .tar.xz), созданный для сбора одного или нескольких файлов. |
| [TARXZ](#TARXZ) | Представляет объединённый Unix‑архив (.txz, .tar.xz), созданный для сбора одного или нескольких файлов. |
| [TGZ](#TGZ) | Представляет объединённый Unix‑архив (.tgz, .tar.gz), созданный для сбора одного или нескольких файлов. |
| [TARGZ](#TARGZ) | Представляет объединённый Unix‑архив (.tgz, .tar.gz), созданный для сбора одного или нескольких файлов. |
| [BZ_2](#BZ-2) | Представляет Bzip2‑сжатый файл (.bz2), созданный с использованием открытого метода сжатия BZIP2. |
| [RAR](#RAR) | Представляет файл архива Roshal (.rar), сжатый с использованием метода сжатия RAR (WINRAR версии 4). |
| [GZ](#GZ) | Представляет Gnu Zipped File (.gz), сжатый файл, созданный с помощью приложения gzip. |
| [GZIP](#GZIP) | Представляет сжатый файл Gnu Zipped File (.gzip), введённый как бесплатная утилита для замены программы Compress, используемой в системах Unix. |
| [SEVEN_ZIP](#SEVEN-ZIP) | Представляет файл 7Zip (.7z, .7zip), который является бесплатным открытым архиватором с сжатием LZMA и LZMA2. |
| [CPIO](#CPIO) | Cpio — это общая утилита архивирования файлов и связанный с ней формат файлов. |
| [ZSTANDARD](#ZSTANDARD) | Файл ZST — это сжатый файл, созданный с помощью алгоритма сжатия Zstandard (zstd). |
| [TZST](#TZST) | Файлы TZST (.tar.zst, .tzst) являются архивами Zstandard (ZST), которые внутри содержат объединённый Unix‑архив (Tar), созданный с помощью утилиты Unix для сбора одного или нескольких файлов. |
| [TAR_ZST](#TAR-ZST) | Файлы TZST (.tar.zst, .tzst) являются архивами Zstandard (ZST), которые внутри содержат объединённый Unix‑архив (Tar), созданный с помощью утилиты Unix для сбора одного или нескольких файлов. |
| [ISO](#ISO) | ISO‑образ оптического диска — это не сжатый образ диска‑архива, представляющий содержимое всех данных на оптическом диске, таком как CD или DVD, основанный на стандарте ISO‑9660. |
| [LHA](#LHA) | LHA или LZH — это бесплатная утилита сжатия и связанный с ней формат файлов. |
| [CAB](#CAB) | Cabinet (или CAB) — это формат архивных файлов для Microsoft Windows. |
| [DXF](#DXF) | Представляет файл Drawing Exchange Format (.dxf), который является тегированным представлением данных файла чертежа AutoCAD. |
| [DWG](#DWG) | Представляет файл AutoCAD Drawing Database (.dwg), который представляет собой проприетарные бинарные файлы, используемые для хранения 2D и 3D данных проектирования. |
| [DWT](#DWT) | Представляет шаблон чертежа AutoCAD (.dwt), который является файлом шаблона чертежа AutoCAD, используемым в качестве основы для создания чертежей, сохраняемых как файлы DWG. |
| [STL](#STL) | Представляет файл Stereolithography (.stl), который является взаимозаменяемым форматом файлов, представляющим трёхмерную геометрию поверхности. |
| [IFC](#IFC) | Представляет файл Industry Foundation Classes (.ifc), который является форматом файлов, устанавливающим международные стандарты импорта и экспорта строительных объектов и их свойств. |
| [DWF](#DWF) | Представляет файл Design Web Format (.dwf), который является сжатым форматом файлов для просмотра, рецензирования или печати 2D/3D чертежей. |
| [FBX](#FBX) | Представляет файл Autodesk FBX Interchange (FilmBoX) (.fbx), который является форматом 3D‑моделей. |
| [DWFX](#DWFX) | Представляет файл Design Web Format XPS (.dwfx), который является сжатым форматом для просмотра, рецензирования или печати 2D/3D чертежей в виде документа XPS. |
| [DGN](#DGN) | Представляет файл MicroStation Design (.dgn), который представляет собой чертежи, созданные и поддерживаемые CAD‑приложениями, такими как MicroStation и Intergraph Interactive Graphics Design System. |
| [PLT](#PLT) | Представляет файл PLT (HPGL) (.plt), который является векторным файлом плоттера, разработанным Autodesk, Inc. |
| [CF2](#CF2) | Представляет файл Common File Format (.cf2). |
| [OBJ](#OBJ) | Представляет файл Wavefront 3D Object (.obj), который является 3D‑изображением, разработанным Wavefront Technologies. |
| [HPG](#HPG) | Представляет файл PLT (HPGL) (.hpg). |
| [IGS](#IGS) | Представляет файл Initial Graphics Exchange Specification (IGES) (.igs). |
| [VSD](#VSD) | Представляет файл Visio Drawing (.vsd), который представляет собой чертежи, созданные с помощью приложения Microsoft Visio для представления различных графических объектов и их взаимосвязей. |
| [VSDX](#VSDX) | Представляет файл Visio Drawing (.vsdx), который представляет формат файлов Microsoft Visio, введённый, начиная с Microsoft Office 2013. |
| [VSS](#VSS) | Представляет файл Visio Stencil (.vss), который представляет собой шаблоны, созданные в Microsoft Visio 2007 и более ранних версиях. |
| [VSSX](#VSSX) | Представляет файл шаблона Visio (.vssx), который является шаблоном чертежей, созданным в Microsoft Visio 2013 и более новых версиях. |
| [VSDM](#VSDM) | Представляет файл Visio с поддержкой макросов (.vsdm), который является файлом чертежа, созданным в приложении Microsoft Visio и поддерживающим макросы. |
| [VST](#VST) | Представляет шаблон чертежа Visio (.vst), который является векторным файлом изображения, созданным в Microsoft Visio. |
| [VSTX](#VSTX) | Представляет шаблон чертежа Visio (.vstx), который является файлом шаблона чертежа, созданным в Microsoft Visio 2013 и более новых версиях. |
| [VSTM](#VSTM) | Представляет шаблон чертежа Visio с поддержкой макросов (.vstm), который является файлом шаблона, созданным в Microsoft Visio и поддерживающим макросы. |
| [VSSM](#VSSM) | Представляет файл шаблона Visio с поддержкой макросов (.vssm), который является файлом шаблона Microsoft Visio, поддерживающим макросы. |
| [VSX](#VSX) | Представляет XML‑файл шаблона Visio (.vsx), который относится к шаблонам, состоящим из чертежей и фигур, используемых для создания диаграмм в Microsoft Visio. |
| [VTX](#VTX) | Представляет XML‑файл шаблона Visio (.vtx), который является шаблоном чертежа Microsoft Visio, сохранённым на диск в формате XML. |
| [VDW](#VDW) | Представляет веб‑чертеж Visio (.vdw), который определяет потоки и хранилища, необходимые для отображения веб‑чертежа. |
| [VDX](#VDX) | Представляет XML‑файл чертежа Visio (.vdx), который представляет любой чертеж или диаграмму, созданные в Microsoft Visio, но сохранённые в формате XML с расширением .VDX. |
| [EPUB](#EPUB) | Представляет файл электронных книг Open eBook (.epub), который является форматом файлов электронных книг, предоставляющим стандартный цифровой формат публикаций для издателей и потребителей. |
| [MOBI](#MOBI) | Представляет электронную книгу Mobipocket (.mobi), который является одним из наиболее широко используемых форматов файлов электронных книг. |
| [AZW_3](#AZW-3) | Формат Amazon Kindle 8 (KF8) — это цифровой файловый формат, разработанный для устройств Amazon Kindle. |
| [MSG](#MSG) | Представляет сообщение Outlook Mail (.msg), который является форматом файла, используемым Microsoft Outlook и Exchange для хранения электронных сообщений, контактов, встреч или других задач. |
| [EML](#EML) | Представляет сообщение электронной почты (.eml), которое представляет электронные сообщения, сохранённые с помощью Outlook и других соответствующих приложений. |
| [EMLX](#EMLX) | Представляет сообщение Apple Mail (.emlx), которое реализовано и разработано компанией Apple. |
| [PST](#PST) | Представляет файл хранилища личной информации Outlook (.pst), который представляет файлы личного хранилища Outlook (также называемые таблицей личного хранилища), содержащие разнообразную пользовательскую информацию. |
| [OST](#OST) | Представляет автономный файл данных Outlook (.ost), который представляет данные почтового ящика пользователя в автономном режиме на локальном компьютере после регистрации на сервере Exchange с использованием Microsoft Outlook. |
| [TIF](#TIF) | Представляет файл Tagged Image File (.tif), который представляет растровые изображения, предназначенные для использования на различных устройствах, соответствующих данному стандарту формата файлов. |
| [TIFF](#TIFF) | Представляет файл Tagged Image File Format (.tiff), который представляет растровые изображения, предназначенные для использования на различных устройствах, соответствующих данному стандарту формата файлов. |
| [JPG](#JPG) | Представляет JPEG‑изображение (.jpg), которое является типом формата изображения, сохраняемого методом сжатия с потерями. |
| [JPEG](#JPEG) | Представляет JPEG‑изображение (.jpeg), которое является типом формата изображения, сохраняемого методом сжатия с потерями. |
| [JFIF](#JFIF) | Формат обмена JPEG‑файлами (.jfif) — это изображение, разработанное для быстрой передачи между платформами. |
| [PNG](#PNG) | Представляет Portable Network Graphic (.png), который является типом формата растрового изображения, использующего безпотерьное сжатие. |
| [GIF](#GIF) | Представляет файл Graphical Interchange Format (.gif), который является типом сильно сжатого изображения. |
| [APNG](#APNG) | Представляет Animated Portable Network Graphic (.apng), который является расширением формата PNG и поддерживает анимацию. |
| [BMP](#BMP) | Представляет Bitmap Image File (.bmp), который используется для хранения растровых цифровых изображений. |
| [ICO](#ICO) | Представляет Icon File (.ico), тип графического файла, используемый в качестве значка для представления приложения в Microsoft Windows. |
| [TGA](#TGA) | Представляет Truevision TGA (TARGA) файл, который используется для хранения растровых цифровых изображений, разработанных компанией TRUEVISION. |
| [JP_2](#JP-2) | Представляет JPEG 2000 Core Image File (.jp2), который является системой кодирования изображений и передовым стандартом сжатия изображений. |
| [JPF](#JPF) | Представляет JPEG 2000 Image File (.jpf). |
| [JPX](#JPX) | Представляет JPEG 2000 Image File (.jpx). |
| [JPM](#JPM) | Представляет JPEG 2000 Image File (.jpm). |
| [J2C](#J2C) | Представляет JPEG 2000 Code InputStream (.j2c). |
| [J2K](#J2K) | Представляет JPEG 2000 Code Stream (.j2k), который представляет собой изображение, сжатое с помощью вейвлетного сжатия вместо DCT‑сжатия. |
| [JPC](#JPC) | Представляет JPEG 2000 Code Stream (.jpc). |
| [JLS](#JLS) | Представляет JPEG-LS (JLS) файл (.jls). |
| [DIB](#DIB) | Представляет Device Independent Bitmap File (.dib). |
| [WMF](#WMF) | Представляет Windows Metafile (.wmf), который представляет Microsoft Windows Metafile (WMF) для хранения как векторных, так и растровых изображений. |
| [WMZ](#WMZ) | Представляет Compressed Windows Metafile (.wmz), который представляет Microsoft Windows Metafile (WMF), сжатый в архиве GZIP, для хранения как векторных, так и растровых изображений. |
| [EMF](#EMF) | Представляет Enhanced Windows Metafile (.emf), который представляет графические изображения независимо от устройства. |
| [EMZ](#EMZ) | Представляет Windows Compressed Enhanced Metafile (.emz), который представляет графические изображения, независимо от устройства, сжатые GZIP. |
| [WEBP](#WEBP) | Представляет WebP Image (.webp), который является современным растровым веб‑форматом изображений, основанным на без потерь и с потерями сжатии. |
| [DNG](#DNG) | Представляет Digital Negative Specification (.dng), который является форматом изображений цифровой камеры, используемым для хранения RAW‑файлов. |
| [CDR](#CDR) | Представляет CorelDraw Vector Graphic Drawing (.cdr), который является векторным файлом рисунка, изначально созданным в CorelDRAW для хранения цифрово закодированных и сжатых изображений. |
| [CMX](#CMX) | Представляет Corel Exchange (.cmx), который является файлом рисунка, содержащим как векторную, так и растровую графику. |
| [DJVU](#DJVU) | Представляет DjVu Image (.djvu), который является графическим форматом файлов, предназначенным для отсканированных документов и книг, особенно содержащих комбинацию текста, рисунков, изображений и фотографий. |
| [CGM](#CGM) | Представляет Computer Graphics Metafile (.cgm), который является бесплатным, независимым от платформы, международным стандартным форматом метафайла для хранения и обмена векторной графикой (2D), растровой графикой и текстом. |
| [PCL](#PCL) | Представляет Printer Command Language Document (.pcl). |
| [PSD](#PSD) | Представляет Adobe Photoshop Document (.psd), который является родным форматом файла Adobe Photoshop, используемым для разработки и проектирования графики. |
| [PSB](#PSB) | Представляет формат Photoshop Large Document Format (.psb), который используется для графического дизайна и разработки в Adobe Photoshop. |
| [DCM](#DCM) | Представляет изображение DICOM (.dcm), которое представляет цифровое изображение, хранящее медицинскую информацию пациентов, такую как МРТ, КТ‑сканирование и ультразвуковые изображения. |
| [PS](#PS) | Представляет файл PostScript (.ps). |
| [EPS](#EPS) | Представляет файл Encapsulated PostScript (.eps), который описывает программу языка Encapsulated PostScript, определяющую внешний вид одной страницы. |
| [ODG](#ODG) | Представляет графический файл OpenDocument (.odg), который используется приложением Draw из Apache OpenOffice для хранения элементов рисунка в виде векторного изображения. |
| [FODG](#FODG) | Представляет шаблон Flat XML ODF (.fodg), который используется приложением Draw из Apache OpenOffice для хранения элементов рисунка в виде векторного изображения. |
| [SVG](#SVG) | Представляет файл Scalable Vector Graphics (.svg), который является файлом Scalable Vector Graphics и использует основанный на XML текстовый формат для описания внешнего вида изображения. |
| [SVGZ](#SVGZ) | Представляет сжатый файл Scalable Vector Graphics (.svgz), который является файлом Scalable Vector Graphics, использующим основанный на XML текстовый формат, сжатый с помощью GZIP, для описания внешнего вида изображения. |
| [OTG](#OTG) | Представляет шаблон OpenDocument Graphic (.otg). |
| [HTM](#HTM) | Представляет файл Hypertext Markup Language (.htm), который является расширением веб‑страниц, созданных для отображения в браузерах. |
| [HTML](#HTML) | Представляет файл Hypertext Markup Language (.html), который является расширением веб‑страниц, созданных для отображения в браузерах. |
| [MHT](#MHT) | Представляет веб‑архив MHTML (.mht). |
| [NSF](#NSF) | Представляет базу данных Lotus Notes (.nsf). |
| [MBOX](#MBOX) | Представляет файл почтового ящика Email (.mbox). |
| [MHTML](#MHTML) | Представляет файл MIME HTML (.mhtml). |
| [XML](#XML) | Представляет файл XML (.xml). |
| [ONE](#ONE) | Представляет документ OneNote (.one), созданный приложением Microsoft OneNote. |
| [PDF](#PDF) | Представляет файл Portable Document Format (.pdf), который является типом документа, созданного Adobe в 1990‑х годах. |
| [XPS](#XPS) | Представляет файл XML Paper Specification (.xps), который представляет файлы разметки страниц, основанные на спецификациях XML Paper, созданных Microsoft. |
| [OXPS](#OXPS) | Представляет файл OpenXPS (.oxps). |
| [TEX](#TEX) | Представляет исходный документ LaTeX (.tex), который является языком, включающим возможности программирования и разметки, используемые для наборa документов. |
| [PPT](#PPT) | Представляет презентацию PowerPoint (.ppt), которая представляет файл PowerPoint, состоящий из набора слайдов для отображения в виде слайд-шоу. |
| [PPTX](#PPTX) | Представляет презентацию PowerPoint Open XML (.pptx), которая является файлом презентации, созданным с помощью популярного приложения Microsoft PowerPoint. |
| [PPS](#PPS) | Представляет слайд-шоу PowerPoint (.pps), которое создаётся с помощью Microsoft PowerPoint для целей показа слайдов. |
| [PPSX](#PPSX) | Представляет файлы слайд-шоу PowerPoint Open XML (.ppsx), которые создаются с помощью Microsoft PowerPoint 2007 и новее для целей показа слайдов. |
| [ODP](#ODP) | Представляет OpenDocument Presentation (.odp), который представляет формат файла презентации, используемый OpenOffice.org в стандарте OASISOpen. |
| [FODP](#FODP) | Представляет OpenDocument Presentation (.fodp), который представляет OpenDocument Flat XML Presentation. |
| [POT](#POT) | Представляет шаблон PowerPoint (.pot), который представляет файлы шаблонов Microsoft PowerPoint, созданные версиями PowerPoint 97‑2003. |
| [PPTM](#PPTM) | Представляет презентацию PowerPoint Open XML с поддержкой макросов (.pptm), которые являются файлами презентаций с поддержкой макросов, созданными в Microsoft PowerPoint 2007 и более новых версиях. |
| [POTX](#POTX) | Представляет шаблон презентации PowerPoint Open XML (.potx), который представляет шаблоны презентаций Microsoft PowerPoint, созданные в Microsoft PowerPoint 2007 и более новых версиях. |
| [POTM](#POTM) | Представляет шаблон презентации PowerPoint Open XML с поддержкой макросов (.potm), которые являются файлами шаблонов Microsoft PowerPoint с поддержкой макросов. |
| [PPSM](#PPSM) | Представляет слайд PowerPoint Open XML с поддержкой макросов (.ppsm), который представляет формат файла слайд-шоу с поддержкой макросов, созданный в Microsoft PowerPoint 2007 и более новых версиях. |
| [OTP](#OTP) | Представляет шаблон OpenDocument Presentation (.otp), который представляет файлы шаблонов презентаций, созданные приложениями в формате стандарта OASIS OpenDocument. |
| [XLS](#XLS) | Представляет электронную таблицу Excel (.xls), которая представляет двоичный формат файлов Excel. |
| [EXCEL_2003_XML](#EXCEL-2003-XML) | Представляет Excel 2003 XML (SpreadsheetML) (.xml), который представляет двоичный формат файлов Excel. |
| [NUMBERS](#NUMBERS) | Представляет Apple Numbers (.numbers), который представляет двоичный формат файлов, похожий на Excel. |
| [XLSX](#XLSX) | Представляет электронную таблицу Microsoft Excel Open XML (.xlsx), которая является широко известным форматом документов Microsoft Excel, представленного Microsoft в выпуске Microsoft Office 2007. |
| [XLSM](#XLSM) | Представляет электронную таблицу Excel Open XML с поддержкой макросов (.xlsm), которая является типом файла таблицы, поддерживающего макросы. |
| [XLSB](#XLSB) | Представляет двоичную электронную таблицу Excel (.xlsb), которая определяет двоичный формат файлов Excel. |
| [CSV](#CSV) | Представляет файл значений, разделённых запятыми (.csv), который представляет простые текстовые файлы, содержащие записи данных со значениями, разделёнными запятыми. |
| [TSV](#TSV) | Представляет файл значений, разделённых табуляцией (.tsv), который представляет данные, разделённые табуляцией, в простом текстовом формате. |
| [ODS](#ODS) | Представляет электронную таблицу OpenDocument (.ods), которая обозначает формат документа OpenDocument Spreadsheet, редактируемый пользователем. |
| [FODS](#FODS) | Представляет электронную таблицу OpenDocument Flat XML (.fods). |
| [OTS](#OTS) | Представляет шаблон электронной таблицы OpenDocument (.ots). |
| [XLAM](#XLAM) | Представляет надстройку Microsoft Excel (.xlam). |
| [XLTM](#XLTM) | Представляет шаблон Microsoft Excel с поддержкой макросов (.xltm), который представляет файлы, генерируемые Microsoft Excel как шаблоны с поддержкой макросов. |
| [XLT](#XLT) | Представляет шаблон Microsoft Excel (.xlt), который является файлом шаблона, созданным в Microsoft Excel, приложении для работы с электронными таблицами, входящем в состав пакета Microsoft Office. |
| [XLTX](#XLTX) | Представляет шаблон электронной таблицы Excel Open XML (.xltx), который представляет шаблоны Microsoft Excel, основанные на спецификациях формата файлов Office OpenXML. |
| [SXC](#SXC) | Представляет электронную таблицу StarOffice Calc (.sxc). |
| [MPP](#MPP) | Представляет файл Microsoft Project (.mpp), который является файлом данных Microsoft Project, хранящим информацию, связанную с управлением проектами, в интегрированном виде. |
| [MPT](#MPT) | Представляет шаблон Microsoft Project (.mpt), который содержит базовую информацию и структуру, а также настройки документа для создания файлов .MPP. |
| [MPX](#MPX) | Представляет файл Microsoft Project Exchange (.mpx), который является форматом ASCII-файла для передачи информации о проекте между Microsoft Project (MSP) и другими приложениями, поддерживающими формат MPX, такими как Primavera Project Planner, Sciforma и Timerline Precision Estimating. |
| [AS](#AS) | Представляет файл ActionScript (.as). |
| [AS_3](#AS-3) | Представляет файл ActionScript (.as3). |
| [ASM](#ASM) | Представляет файл исходного кода на ассемблере (.asm). |
| [BAT](#BAT) | Представляет пакетный файл DOS (.bat). |
| [C](#C) | Представляет файл исходного кода C/C++ (.c). |
| [CC](#CC) | Представляет файл исходного кода C++ (.cc). |
| [CMAKE](#CMAKE) | Представляет файл CMake (.cmake). |
| [CPP](#CPP) | Представляет файл исходного кода C++ (.cpp). |
| [CS](#CS) | Представляет файл исходного кода C\# (.cs), который является файлом исходного кода для языка программирования C\#. |
| [VB](#VB) | Представляет файл элемента проекта Visual Basic (.vb), который является файлом исходного кода, созданным на языке Visual Basic. |
| [CSS](#CSS) | Представляет файл каскадных таблиц стилей (.css). |
| [CXX](#CXX) | Представляет файл исходного кода C++ (.cxx). |
| [DIFF](#DIFF) | Представляет файл патча (.diff). |
| [ERB](#ERB) | Представляет скрипт Ruby ERB (.erb). |
| [GROOVY](#GROOVY) | Представляет файл исходного кода Groovy (.groovy). |
| [H](#H) | Представляет заголовочный файл C/C++/Objective-C (.h). |
| [HAML](#HAML) | Представляет файл исходного кода Haml (.haml). |
| [HH](#HH) | Представляет заголовочный файл C++ (.hh). |
| [JAVA](#JAVA) | Представляет файл исходного кода Java (.java). |
| [JS](#JS) | Представляет файл JavaScript (.js). |
| [JSON](#JSON) | Представляет файл JavaScript Object Notation (.json). |
| [LESS](#LESS) | Представляет файл таблицы стилей LESS (.less). |
| [LOG](#LOG) | Представляет файл журнала (.log). |
| [M](#M) | Представляет файл реализации Objective-C (.m). |
| [MAKE](#MAKE) | Представляет скрипт Xcode Makefile (.make). |
| [MD](#MD) | Представляет файл документации в формате Markdown (.md). |
| [ML](#ML) | Представляет файл исходного кода ML (.ml). |
| [MM](#MM) | Представляет файл исходного кода Objective-C++ (.mm). |
| [PHP](#PHP) | Представляет файл исходного кода PHP (.php). |
| [PL](#PL) | Представляет скрипт Perl (.pl). |
| [PROPERTIES](#PROPERTIES) | Представляет файл свойств Java (.properties). |
| [PY](#PY) | Представляет скрипт Python (.py). |
| [RB](#RB) | Представляет файл исходного кода Ruby (.rb). |
| [RST](#RST) | Представляет файл reStructuredText (.rst). |
| [SASS](#SASS) | Представляет файл Syntactically Awesome StyleSheets (.sass). |
| [SCALA](#SCALA) | Представляет файл исходного кода Scala (.scala). |
| [SCM](#SCM) | Представляет файл исходного кода Scheme (.scm). |
| [SCRIPT](#SCRIPT) | Представляет файл общего скрипта (.script). |
| [SH](#SH) | Представляет скрипт оболочки Bash (.sh). |
| [SML](#SML) | Представляет файл исходного кода Standard ML (.sml). |
| [SQL](#SQL) | Представляет файл данных Structured Query Language (.sql). |
| [VIM](#VIM) | Представляет файл настроек Vim (.vim). |
| [YAML](#YAML) | Представляет документ YAML (.yaml). |
| [DOC](#DOC) | Представляет документ Microsoft Word (.doc). |
| [DOCX](#DOCX) | Представляет документ Microsoft Word Open XML (.docx). |
| [CHM](#CHM) | Представляет файл Microsoft Compiled HTML Help (.chm). |
| [DOCM](#DOCM) | Представляет документ Word Open XML с поддержкой макросов (.docm). |
| [DOT](#DOT) | Представляет шаблон документа Word (.dot). |
| [DOTX](#DOTX) | Представляет файл шаблона документа Word Open XML (.dotx). |
| [DOTM](#DOTM) | Представляет файл шаблона документа Word Open XML с поддержкой макросов (.dotm). |
| [RTF](#RTF) | Представляет файл в формате Rich Text Format (.rtf). |
| [TXT](#TXT) | Представляет простой текстовый файл (.txt). |
| [ODT](#ODT) | Представляет текстовый документ OpenDocument (.odt). |
| [OTT](#OTT) | Представляет шаблон документа OpenDocument (.ott). |
| [VCF](#VCF) | Представляет файл vCard (.vcf), который является цифровым форматом файлов для хранения контактной информации. |
| [AI](#AI) | Представляет файл Adobe Illustrator (.ai), который является форматом файлов для рисунков Adobe Illustrator. |
| [PSM1](#PSM1) | Представляет файл модуля скриптов PowerShell (.psm1). |
| [PS1](#PS1) | Представляет файл скрипта PowerShell (.ps1). |
| [PSD1](#PSD1) | Представляет файл манифеста модуля скриптов PowerShell (.psd1). |
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Сопоставляет расширение файла с типом файла. |
| [fromFilePath(String filePath)](#fromFilePath-java.lang.String-) | Извлекает расширение файла из имени файла или пути к файлу и сопоставляет его с типом файла. |
| [fromMediaType(String mediaType)](#fromMediaType-java.lang.String-) | Сопоставляет тип медиа‑файла с типом файла. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Определяет тип файла, читая сигнатуру файла. |
| [fromStream(InputStream stream, String password)](#fromStream-java.io.InputStream-java.lang.String-) | Определяет тип файла, читая сигнатуру файла. |
| [fromStream(InputStream stream, ILogger logger)](#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-) | Определяет тип файла, читая сигнатуру файла. |
| [fromStream(InputStream stream, String password, ILogger logger)](#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-) | Определяет тип файла, читая сигнатуру файла. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | Получает поддерживаемые типы файлов. |
| [detectCharset(String filePath)](#detectCharset-java.lang.String-) | Пытается определить кодировку текстовых файлов [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) и [CSV](../../com.groupdocs.viewer/filetype\#CSV) по пути. |
| [detectCharset(InputStream stream)](#detectCharset-java.io.InputStream-) | Пытается определить кодировку текстового файла [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) и [CSV](../../com.groupdocs.viewer/filetype\#CSV) по потоку. |
| [getFileFormat()](#getFileFormat--) | Получает название формата файла, например, "Microsoft Word Document". |
| [getExtension()](#getExtension--) | Получает суффикс расширения файла (включая точку "."), например, ".doc". |
| [toString()](#toString--) | Возвращает строковое представление текущего объекта. |
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Представляет неизвестный тип файла.

### ZIP {#ZIP}
```
public static final FileType ZIP
```


Представляет zip‑файл (.zip), который может содержать один или несколько файлов или каталогов. Узнайте больше о этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/compression/zip

### TAR {#TAR}
```
public static final FileType TAR
```


Представляет объединённый архив Unix‑файлов (.tar), созданный для сбора одного или нескольких файлов. Узнайте больше о этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/compression/tar

### XZ {#XZ}
```
public static final FileType XZ
```


Представляет файл XZ (.xz), сжатый с использованием алгоритма высокоэффективного сжатия на основе LZMA. Узнайте больше о этом формате файла [здесь][].


[here]: https://fileinfo.com/extension/xz

### TXZ {#TXZ}
```
public static final FileType TXZ
```


Представляет объединённый архив Unix‑файлов (.txz, .tar.xz), созданный для сбора одного или нескольких файлов. Узнайте больше о этом формате файла [здесь][].


[here]: https://fileinfo.com/extension/txz

### TARXZ {#TARXZ}
```
public static final FileType TARXZ
```


Представляет объединённый архив Unix‑файлов (.txz, .tar.xz), созданный для сбора одного или нескольких файлов. Узнайте больше о этом формате файла [здесь][].


[here]: https://fileinfo.com/extension/txz

### TGZ {#TGZ}
```
public static final FileType TGZ
```


Представляет объединённый архив Unix‑файлов (.tgz, .tar.gz), созданный для сбора одного или нескольких файлов. Узнайте больше о этом формате файла [здесь][].


[here]: https://fileinfo.com/extension/tgz

### TARGZ {#TARGZ}
```
public static final FileType TARGZ
```


Представляет объединённый архив Unix‑файлов (.tgz, .tar.gz), созданный для сбора одного или нескольких файлов. Узнайте больше о этом формате файла [здесь][].


[here]: https://fileinfo.com/extension/tgz

### BZ_2 {#BZ-2}
```
public static final FileType BZ_2
```


Представляет сжатый файл Bzip2 (.bz2), созданный с использованием открытого метода сжатия BZIP2. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/compression/bz2

### RAR {#RAR}
```
public static final FileType RAR
```


Представляет сжатый файл Roshal Archive (.rar), созданный с использованием метода сжатия RAR (WINRAR версия 4). Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/compression/rar

### GZ {#GZ}
```
public static final FileType GZ
```


Представляет сжатый файл Gnu Zipped File (.gz), созданный с помощью приложения gzip. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/compression/gz

### GZIP {#GZIP}
```
public static final FileType GZIP
```


Представляет сжатый файл Gnu Zipped File (.gzip), представленный как бесплатная утилита, заменяющая программу Compress, используемую в системах Unix. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/compression/gz

### SEVEN_ZIP {#SEVEN-ZIP}
```
public static final FileType SEVEN_ZIP
```


Представляет файл 7Zip (.7z, .7zip), который является бесплатным открытым архиватором с сжатием LZMA и LZMA2. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/compression/7z/

### CPIO {#CPIO}
```
public static final FileType CPIO
```


Cpio — это универсальная утилита архивирования файлов и связанный с ней формат файлов. Она в основном устанавливается в операционных системах, похожих на Unix. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/compression/cpio

### ZSTANDARD {#ZSTANDARD}
```
public static final FileType ZSTANDARD
```


Файл ZST — это сжатый файл, генерируемый с помощью алгоритма сжатия Zstandard (zstd). Это сжатый файл, созданный без потерь алгоритмом. Файлы ZST могут использоваться для сжатия различных типов файлов, таких как базы данных, файловые системы, сети и игры. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/compression/zst/

### TZST {#TZST}
```
public static final FileType TZST
```


Файлы TZST (.tar.zst, .tzst) являются архивами Zstandard (ZST), которые внутри содержат объединённый Unix‑архив (Tar), созданный с помощью утилиты Unix для сбора одного или нескольких файлов.

### TAR_ZST {#TAR-ZST}
```
public static final FileType TAR_ZST
```


Файлы TZST (.tar.zst, .tzst) являются архивами Zstandard (ZST), которые внутри содержат объединённый Unix‑архив (Tar), созданный с помощью утилиты Unix для сбора одного или нескольких файлов.

### ISO {#ISO}
```
public static final FileType ISO
```


ISO‑образ оптического диска — это несжатый архивный образ диска, представляющий содержимое всех данных на оптическом диске, таком как CD или DVD, основанный на стандарте ISO‑9660. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/compression/iso/

### LHA {#LHA}
```
public static final FileType LHA
```


LHA или LZH — это бесплатная утилита сжатия и связанный с ней формат файлов. Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/compression/lzh/

### CAB {#CAB}
```
public static final FileType CAB
```


Cabinet (или CAB) — это формат архивных файлов для Microsoft Windows. Узнайте больше об этом формате файла [here][].


[here]: https://en.wikipedia.org/wiki/Cabinet_%28file_format%29

### DXF {#DXF}
```
public static final FileType DXF
```


Представляет файл Drawing Exchange Format (.dxf), который является тегированным представлением данных файла чертежа AutoCAD. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/cad/dxf

### DWG {#DWG}
```
public static final FileType DWG
```


Представляет файл базы данных чертежей AutoCAD (.dwg), который представляет проприетарные бинарные файлы, используемые для хранения 2D и 3D данных дизайна. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/cad/dwg

### DWT {#DWT}
```
public static final FileType DWT
```


Представляет шаблон чертежа AutoCAD (.dwt), который является файлом шаблона чертежа AutoCAD, используемым в качестве основы для создания чертежей, которые могут быть сохранены как файлы DWG. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/cad/dwt

### STL {#STL}
```
public static final FileType STL
```


Представляет файл стереолитографии (.stl), который является взаимозаменяемым форматом файлов, представляющим трехмерную поверхностную геометрию. Он обычно используется в быстром прототипировании, 3D‑печати и компьютерном производстве. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/cad/stl

### IFC {#IFC}
```
public static final FileType IFC
```


Представляет файл Industry Foundation Classes (.ifc), который является форматом файлов, устанавливающим международные стандарты импорта и экспорта строительных объектов и их свойств. Он обеспечивает совместимость между различными программными приложениями. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/cad/ifc

### DWF {#DWF}
```
public static final FileType DWF
```


Представляет файл Design Web Format (.dwf), который является сжатым форматом файлов для просмотра, рецензирования или печати 2D/3D чертежей. Он содержит графику и текст как часть данных дизайна и уменьшает размер файла за счет сжатия. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/cad/dwf

### FBX {#FBX}
```
public static final FileType FBX
```


Представляет файл Autodesk FBX Interchange (FilmBoX) (.fbx), который является форматом 3D‑модели. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/cad/fbx

### DWFX {#DWFX}
```
public static final FileType DWFX
```


Представляет файл Design Web Format XPS (.dwfx), который является сжатым форматом для просмотра, рецензирования или печати 2D/3D чертежей в виде документа XPS. Он содержит графику и текст как часть данных дизайна и уменьшает размер файла за счет сжатия. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/cad/dwfx

### DGN {#DGN}
```
public static final FileType DGN
```


Представляет файл дизайна MicroStation (.dgn), который представляет собой чертежи, создаваемые и поддерживаемые CAD‑приложениями, такими как MicroStation и Intergraph Interactive Graphics Design System. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/cad/dgn

### PLT {#PLT}
```
public static final FileType PLT
```


Представляет файл PLT (HPGL) (.plt), который является векторным файлом плоттера, разработанным Autodesk, Inc. Он содержит информацию для определённого CAD‑файла, и все изображения печатаются линиями вместо точек, обеспечивая точность и прецизионность в производстве. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/cad/plt

### CF2 {#CF2}
```
public static final FileType CF2
```


Представляет файл Common File Format (.cf2). Узнайте больше об этом формате файла [here][].


[here]: https://fileinfo.com/extension/cf2

### OBJ {#OBJ}
```
public static final FileType OBJ
```


Представляет файл Wavefront 3D Object (.obj), который является 3D‑изображением, разработанным Wavefront Technologies. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/3d/obj/

### HPG {#HPG}
```
public static final FileType HPG
```


Представляет файл PLT (HPGL) (.hpg). Это формат файлов, используемый для файлов плоттера в HP Graphics Language (HPGL). Узнайте больше об этом формате файла [here][].


[here]: https://fileinfo.com/extension/hpg

### IGS {#IGS}
```
public static final FileType IGS
```


Представляет файл Initial Graphics Exchange Specification (IGES) (.igs).

### VSD {#VSD}
```
public static final FileType VSD
```


Представляет файл Visio Drawing (.vsd), который представляет чертежи, созданные в приложении Microsoft Visio для отображения различных графических объектов и их взаимосвязей. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/image/vsd

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Представляет файл Visio Drawing (.vsdx), который представляет формат файлов Microsoft Visio, введённый, начиная с Microsoft Office 2013. Он заменил бинарный формат (.VSD), поддерживаемый более ранними версиями Microsoft Visio. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/image/vsdx

### VSS {#VSS}
```
public static final FileType VSS
```


Представляет файл Visio Stencil (.vss), который является шаблонным файлом, созданным в Microsoft Visio 2007 и более ранних версиях. Шаблонные файлы предоставляют объекты чертежа, которые можно включать в Visio‑чертеж (.VSD). Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/image/vss

### VSSX {#VSSX}
```
public static final FileType VSSX
```


Представляет файл Visio Stencil (.vssx), который представляет чертежные шаблоны, созданные в Microsoft Visio 2013 и более новых версиях. Формат VSSX можно открыть в Visio 2013 и выше. Файлы Visio известны тем, что представляют различные элементы чертежа, такие как фигуры, соединители, блок‑схемы, сетевые схемы, UML‑диаграммы и т.д. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/image/vssx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Представляет файл Visio Macro-Enabled Drawing (.vsdm), который представляет чертежи, созданные в Microsoft Visio и поддерживающие макросы. Файлы VSDM — это OPC/XML‑чертежи, похожие на VSDX, но также позволяющие выполнять макросы при открытии файла. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/image/vsdm

### VST {#VST}
```
public static final FileType VST
```


Представляет шаблон Visio Drawing (.vst), который представляет векторные изображения, созданные в Microsoft Visio. Они служат шаблонами для создания последующих файлов и содержат макет и настройки по умолчанию, используемые при создании новых чертежей Visio. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/image/vst

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Представляет шаблон Visio Drawing (.vstx), который представляет файлы шаблонов чертежей, созданные в Microsoft Visio 2013 и более новых версиях. Эти файлы VSTX предоставляют отправную точку для создания чертежей Visio, сохраняемых как .VSDX, с макетом и настройками по умолчанию. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Представляет шаблон Visio Macro-Enabled Drawing (.vstm), который представляет файлы шаблонов, созданные в Microsoft Visio и поддерживающие макросы. Файлы, созданные из шаблонов VSTM, могут выполнять макросы, разработанные на языке Visual Basic for Applications (VBA). Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Представляет файл Visio Macro-Enabled Stencil (.vssm), который представляет шаблоны Microsoft Visio, поддерживающие макросы. При открытии файла VSSM можно выполнять макросы для получения требуемого форматирования и размещения фигур в диаграмме. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Представляет файл Visio Stencil XML (.vsx), который относится к шаблонам, состоящим из чертежей и фигур, используемых для создания диаграмм в Microsoft Visio. Файлы VSX сохраняются в формате XML и поддерживались до Visio 2013. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


Представляет файл Visio Template XML (.vtx), который представляет шаблон чертежа Microsoft Visio, сохранённый на диск в формате XML. Шаблон предоставляет базовые настройки для создания нескольких файлов Visio с одинаковыми параметрами. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/image/vtx

### VDW {#VDW}
```
public static final FileType VDW
```


Представляет веб‑чертеж Visio (.vdw), который определяет потоки и хранилища, необходимые для отображения веб‑чертежа. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/web/vdw

### VDX {#VDX}
```
public static final FileType VDX
```


Представляет файл Visio Drawing XML (.vdx), который представляет любой чертеж или диаграмму, созданные в Microsoft Visio, но сохранённые в формате XML с расширением .VDX. Файл Visio Drawing XML создаётся в программном обеспечении Visio, разработанном Microsoft. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Представляет файл Open eBook (.epub), который является форматом электронных книг, предоставляющим стандартный цифровой формат публикаций для издателей и потребителей. Формат поддерживается многими электронными читалками и программными приложениями. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/ebook/epub

### MOBI {#MOBI}
```
public static final FileType MOBI
```


Представляет электронную книгу Mobipocket (.mobi), который является одним из самых широко используемых форматов файлов электронных книг. Формат является улучшением старого формата OEB (Open Ebook Format) и использовался как проприетарный формат для Mobipocket Reader. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/ebook/mobi

### AZW_3 {#AZW-3}
```
public static final FileType AZW_3
```


Электронная книга Amazon Kindle Format 8 (KF8) — это цифровой формат файла, разработанный для устройств Amazon Kindle. Формат является улучшением более старых файлов AZW и используется только на устройствах Kindle Fire с обратной совместимостью с предшествующими форматами, то есть MOBI и AZW. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/ebook/azw3

### MSG {#MSG}
```
public static final FileType MSG
```


Представляет сообщение Outlook Mail (.msg), которое является форматом файла, используемым Microsoft Outlook и Exchange для хранения электронных сообщений, контактов, встреч или других задач. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/email/msg

### EML {#EML}
```
public static final FileType EML
```


Представляет электронное сообщение (.eml), которое представляет электронные письма, сохранённые с помощью Outlook и других соответствующих приложений. Практически все почтовые клиенты поддерживают этот формат файла благодаря соответствию стандарту RFC‑822 Internet Message Format. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/email/eml

### EMLX {#EMLX}
```
public static final FileType EMLX
```


Представляет сообщение Apple Mail (.emlx), которое реализовано и разработано Apple. Приложение Apple Mail использует формат файла EMLX для экспорта электронных писем. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/email/emlx

### PST {#PST}
```
public static final FileType PST
```


Представляет файл Outlook Personal Information Store (.pst), который представляет файлы личного хранилища Outlook (также называемые Personal Storage Table), содержащие разнообразную пользовательскую информацию. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/email/pst

### OST {#OST}
```
public static final FileType OST
```


Представляет файл Outlook Offline Data (.ost), который представляет данные почтового ящика пользователя в автономном режиме на локальном компьютере после регистрации на сервере Exchange с использованием Microsoft Outlook. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/email/ost

### TIF {#TIF}
```
public static final FileType TIF
```


Представляет файл Tagged Image (.tif), который представляет растровые изображения, предназначенные для использования на различных устройствах, соответствующих этому стандарту формата файла. Он способен описывать двууровневые, градации серого, палитровые и полноцветные данные изображения в нескольких цветовых пространствах. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/tiff

### TIFF {#TIFF}
```
public static final FileType TIFF
```


Представляет формат Tagged Image File (.tiff), который представляет растровые изображения, предназначенные для использования на различных устройствах, соответствующих этому стандарту формата файла. Он способен описывать двууровневые, градации серого, палитровые и полноцветные данные изображения в нескольких цветовых пространствах. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/tiff

### JPG {#JPG}
```
public static final FileType JPG
```


Представляет изображение JPEG (.jpg), которое является типом формата изображения, сохраняемого с помощью метода сжатия с потерями. Получаемое изображение в результате сжатия представляет собой компромисс между размером хранения и качеством изображения. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/jpeg

### JPEG {#JPEG}
```
public static final FileType JPEG
```


Представляет изображение JPEG (.jpeg), которое является типом формата изображения, сохраняемого с помощью метода сжатия с потерями. Получаемое изображение в результате сжатия представляет собой компромисс между размером хранения и качеством изображения. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/jpeg

### JFIF {#JFIF}
```
public static final FileType JFIF
```


JPEG File Interchange Format (.jfif) — это изображение, разработанное для быстрого обмена между платформами. Этот формат использует JPEG‑сжатие. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/jfif

### PNG {#PNG}
```
public static final FileType PNG
```


Представляет графический файл Portable Network Graphic (.png), который является типом формата растрового изображения, использующего без потерь сжатие. Этот формат файла был создан как замена Graphics Interchange Format (GIF) и не имеет ограничений по авторским правам. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/png

### GIF {#GIF}
```
public static final FileType GIF
```


Представляет файл формата Graphical Interchange Format (.gif), который является типом сильно сжатого изображения. Для каждого изображения GIF обычно допускает до 8 бит на пиксель, и в изображении допускается до 256 цветов. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/gif

### APNG {#APNG}
```
public static final FileType APNG
```


Представляет анимированный формат Portable Network Graphic (.apng), который является расширением формата PNG и поддерживает анимацию. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/apng

### BMP {#BMP}
```
public static final FileType BMP
```


Представляет файл растрового изображения (.bmp), который используется для хранения цифровых растровых изображений. Эти изображения независимы от графического адаптера и также называются форматом device independent bitmap (DIB). Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/bmp

### ICO {#ICO}
```
public static final FileType ICO
```


Представляет файл значка (.ico), который является типом графического файла, используемого в качестве значка для представления приложения в Microsoft Windows. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/ico

### TGA {#TGA}
```
public static final FileType TGA
```


Представляет файл Truevision TGA (TARGA), который используется для хранения цифровых растровых изображений, разработанных компанией TRUEVISION. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/tga

### JP_2 {#JP-2}
```
public static final FileType JP_2
```


Представляет основной файл изображения JPEG 2000 (.jp2), который является системой кодирования изображений и передовым стандартом сжатия изображений. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/jp2

### JPF {#JPF}
```
public static final FileType JPF
```


Представляет файл изображения JPEG 2000 (.jpf). Узнайте больше об этом формате файла [здесь][].


[here]: https://docs.fileformat.com/image/jpf

### JPX {#JPX}
```
public static final FileType JPX
```


Представляет файл изображения JPEG 2000 (.jpx). Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/jpx

### JPM {#JPM}
```
public static final FileType JPM
```


Представляет файл изображения JPEG 2000 (.jpm). Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/jpm

### J2C {#J2C}
```
public static final FileType J2C
```


Представляет поток ввода кода JPEG 2000 (.j2c). Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/j2c

### J2K {#J2K}
```
public static final FileType J2K
```


Представляет поток кода JPEG 2000 (.j2k), который представляет собой изображение, сжатое с использованием вейвлет‑сжатия вместо DCT‑сжатия. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/j2k

### JPC {#JPC}
```
public static final FileType JPC
```


Представляет поток кода JPEG 2000 (.jpc). Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/jpc

### JLS {#JLS}
```
public static final FileType JLS
```


Представляет файл JPEG‑LS (JLS) (.jls). Узнайте больше об этом формате файла [здесь][].


[here]: https://fileinfo.com/extension/jls

### DIB {#DIB}
```
public static final FileType DIB
```


Представляет файл Device Independent Bitmap (.dib). Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/dib

### WMF {#WMF}
```
public static final FileType WMF
```


Представляет метафайл Windows (.wmf), который представляет Microsoft Windows Metafile (WMF) для хранения как векторных, так и растровых данных изображений. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/wmf

### WMZ {#WMZ}
```
public static final FileType WMZ
```


Представляет сжатый метафайл Windows (.wmz), который представляет Microsoft Windows Metafile (WMF), сжатый в архиве GZIP, для хранения как векторных, так и растровых данных изображений. Узнайте больше об этом формате файла [здесь][].


[here]: https://fileinfo.com/extension/wmz#compressed_windows_metafile

### EMF {#EMF}
```
public static final FileType EMF
```


Представляет расширенный метафайл Windows (.emf), который представляет графические изображения независимо от устройства. Метафайлы EMF состоят из записей переменной длины в хронологическом порядке, которые могут отобразить сохранённое изображение после разбора на любом выходном устройстве. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/emf

### EMZ {#EMZ}
```
public static final FileType EMZ
```


Представляет сжатый расширенный метафайл Windows (.emz), который представляет графические изображения, независимо от устройства, сжатые с помощью GZIP. Метафайлы EMF состоят из записей переменной длины в хронологическом порядке, которые могут отобразить сохранённое изображение после разбора на любом выходном устройстве. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/emz

### WEBP {#WEBP}
```
public static final FileType WEBP
```


Представляет изображение WebP (.webp), который является современным растровым веб‑форматом изображения, основанным на без потерь и с потерями сжатии. Он обеспечивает такое же качество изображения при значительном уменьшении размера файла. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/webp

### DNG {#DNG}
```
public static final FileType DNG
```


Представляет спецификацию Digital Negative (.dng), которая является форматом изображений цифровой камеры, используемым для хранения RAW‑файлов. Она была разработана Adobe в сентябре 2004 года и в основном используется в цифровой фотографии. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/dng

### CDR {#CDR}
```
public static final FileType CDR
```


Представляет векторный графический рисунок CorelDraw (.cdr), который является файлом векторного рисунка, изначально созданным в CorelDRAW для хранения цифрово закодированных и сжатых изображений. Файл рисунка CDR содержит текст, линии, формы, изображения, цвета и эффекты для векторного представления содержимого изображения. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/cdr

### CMX {#CMX}
```
public static final FileType CMX
```


Представляет файл обмена Corel (.cmx), который является файлом рисунка и может содержать как векторную графику, так и растровую графику. Узнайте больше об этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/image/cmx

### DJVU {#DJVU}
```
public static final FileType DJVU
```


Представляет изображение DjVu (.djvu), которое является графическим файловым форматом, предназначенным для отсканированных документов и книг, особенно содержащих комбинацию текста, рисунков, изображений и фотографий. Узнайте больше об этом файловом формате [здесь][].


[here]: https://wiki.fileformat.com/image/djvu

### CGM {#CGM}
```
public static final FileType CGM
```


Представляет компьютерный графический метафайл (.cgm), который является бесплатным, независимым от платформы, международным стандартным форматом метафайла для хранения и обмена векторной графикой (2D), растровой графикой и текстом. CGM использует объектно-ориентированный подход и предоставляет множество функций для создания изображений. Узнайте больше об этом файловом формате [здесь][].


[here]: https://wiki.fileformat.com/page-description-language/cgm

### PCL {#PCL}
```
public static final FileType PCL
```


Представляет документ Printer Command Language (.pcl). Узнайте больше об этом файловом формате [здесь][].


[here]: https://wiki.fileformat.com/page-description-language/pcl

### PSD {#PSD}
```
public static final FileType PSD
```


Представляет документ Adobe Photoshop (.psd), который является родным форматом Adobe Photoshop, используемым для разработки и дизайна графики. Узнайте больше об этом файловом формате [здесь][].


[here]: https://wiki.fileformat.com/image/psd

### PSB {#PSB}
```
public static final FileType PSB
```


Представляет формат большого документа Photoshop (.psb), который используется для разработки и дизайна графики в Adobe Photoshop. Узнайте больше об этом файловом формате [здесь][].


[here]: https://wiki.fileformat.com/image/psb

### DCM {#DCM}
```
public static final FileType DCM
```


Представляет изображение DICOM (.dcm), которое представляет цифровое изображение, хранящее медицинскую информацию о пациентах, такую как МРТ, КТ‑сканирование и ультразвуковые изображения. Узнайте больше об этом файловом формате [здесь][].


[here]: https://wiki.fileformat.com/image/dcm

### PS {#PS}
```
public static final FileType PS
```


Представляет файл PostScript (.ps). Узнайте больше об этом файловом формате [здесь][].


[here]: https://wiki.fileformat.com/page-description-language/ps

### EPS {#EPS}
```
public static final FileType EPS
```


Представляет файл Encapsulated PostScript (.eps), который описывает программу языка Encapsulated PostScript, определяющую внешний вид одной страницы. Узнайте больше об этом файловом формате [здесь][].


[here]: https://wiki.fileformat.com/page-description-language/eps

### ODG {#ODG}
```
public static final FileType ODG
```


Представляет графический файл OpenDocument (.odg), который используется приложением Draw из Apache OpenOffice для хранения элементов рисунка в виде векторного изображения. Узнайте больше об этом файловом формате [здесь][].


[here]: https://wiki.fileformat.com/image/odg

### FODG {#FODG}
```
public static final FileType FODG
```


Представляет шаблон Flat XML ODF (.fodg), который используется приложением Draw из Apache OpenOffice для хранения элементов рисунка в виде векторного изображения. Узнайте больше об этом файловом формате [здесь][].


[here]: https://wiki.fileformat.com/image/fodg

### SVG {#SVG}
```
public static final FileType SVG
```


Представляет файл Scalable Vector Graphics (.svg), который является файлом Scalable Vector Graphics, использующим текстовый формат XML для описания внешнего вида изображения. Узнайте больше об этом файловом формате [здесь][].


[here]: https://wiki.fileformat.com/page-description-language/svg

### SVGZ {#SVGZ}
```
public static final FileType SVGZ
```


Представляет сжатый файл Scalable Vector Graphics (.svgz), который является файлом Scalable Vector Graphics, использующим текстовый формат XML, сжатый с помощью GZIP, для описания внешнего вида изображения. Узнайте больше об этом файловом формате [здесь][].


[here]: https://fileinfo.com/extension/svgz

### OTG {#OTG}
```
public static final FileType OTG
```


Представляет шаблон графики OpenDocument (.otg). Узнайте больше об этом файловом формате [здесь][].


[here]: https://docs.fileformat.com/image/otg

### HTM {#HTM}
```
public static final FileType HTM
```


Представляет файл Hypertext Markup Language (.htm), который является расширением для веб-страниц, созданных для отображения в браузерах. Узнайте больше об этом файловом формате [здесь][].


[here]: https://wiki.fileformat.com/web/html

### HTML {#HTML}
```
public static final FileType HTML
```


Представляет файл Hypertext Markup Language (.html), который является расширением для веб-страниц, созданных для отображения в браузерах. Узнайте больше об этом файловом формате [здесь][].


[here]: https://wiki.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


Представляет веб-архив MHTML (.mht). Узнайте больше об этом файловом формате [здесь][].


[here]: https://wiki.fileformat.com/web/mht

### NSF {#NSF}
```
public static final FileType NSF
```


Представляет базу данных Lotus Notes (.nsf). Узнайте больше об этом файловом формате [здесь][].


[here]: https://fileinfo.com/extension/nsf

### MBOX {#MBOX}
```
public static final FileType MBOX
```


Представляет файл почтового ящика Email (.mbox). Узнайте больше об этом файловом формате [здесь][].


[here]: https://fileinfo.com/extension/mbox

### MHTML {#MHTML}
```
public static final FileType MHTML
```


Представляет файл MIME HTML (.mhtml). Узнайте больше об этом файловом формате [здесь][].


[here]: https://wiki.fileformat.com/web/mhtml

### XML {#XML}
```
public static final FileType XML
```


Представляет файл XML (.xml). Узнайте больше об этом файловом формате [здесь][].


[here]: https://docs.fileformat.com/web/xml

### ONE {#ONE}
```
public static final FileType ONE
```


Представляет документ OneNote (.one), созданный приложением Microsoft OneNote. OneNote позволяет собирать информацию с помощью приложения, как если бы вы использовали черновик для записи заметок. Узнайте больше об этом файловом формате [здесь][].


[here]: https://wiki.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


Представляет файл Portable Document Format (.pdf), который является типом документа, созданного Adobe в 1990‑х годах. Цель этого формата файлов заключалась в введении стандарта представления документов и других справочных материалов в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционных систем. Узнайте больше об этом файловом формате [здесь][].


[here]: https://wiki.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


Представляет файл спецификации XML Paper (.xps), который представляет файлы разметки страниц на основе спецификаций XML Paper, созданных Microsoft. Этот формат был разработан Microsoft в качестве замены формата EMF и похож на формат PDF, но использует XML в разметке, внешнем виде и информации о печати документа. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/page-description-language/xps

### OXPS {#OXPS}
```
public static final FileType OXPS
```


Представляет файл OpenXPS (.oxps). Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/page-description-language/oxps

### TEX {#TEX}
```
public static final FileType TEX
```


Представляет исходный документ LaTeX (.tex), который является языком, включающим возможности программирования и разметки, используемыми для наборa документов. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


Представляет презентацию PowerPoint (.ppt), которая представляет файл PowerPoint, состоящий из набора слайдов для показа в виде слайд-шоу. Он определяет двоичный формат файла, используемый Microsoft PowerPoint 97-2003. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


Представляет презентацию PowerPoint Open XML (.pptx), которая является файлом презентации, созданным с помощью популярного приложения Microsoft PowerPoint. В отличие от предыдущей версии формата файла презентации PPT, который был двоичным, формат PPTX основан на формате файла презентации Microsoft PowerPoint Open XML. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


Представляет слайд-шоу PowerPoint (.pps), которое создаётся с помощью Microsoft PowerPoint для целей слайд-шоу. Чтение и создание файлов PPS поддерживается Microsoft PowerPoint 97-2003. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


Представляет слайд-шоу PowerPoint Open XML (.ppsx), которое создаётся с помощью Microsoft PowerPoint 2007 и более новых версий для целей слайд-шоу. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


Представляет презентацию OpenDocument (.odp), которая представляет формат файла презентации, используемый OpenOffice.org в стандарте OASISOpen. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/presentation/odp

### FODP {#FODP}
```
public static final FileType FODP
```


Представляет презентацию OpenDocument (.fodp), которая представляет OpenDocument Flat XML Presentation. Узнайте больше об этом формате файла [here][].


[here]: https://fileinfo.com/extension/fodp

### POT {#POT}
```
public static final FileType POT
```


Представляет шаблон PowerPoint (.pot), который представляет файлы шаблонов Microsoft PowerPoint, созданные версиями PowerPoint 97-2003. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/presentation/pot

### PPTM {#PPTM}
```
public static final FileType PPTM
```


Представляет презентацию PowerPoint Open XML с поддержкой макросов (.pptm), которая является презентацией с включёнными макросами, созданной в Microsoft PowerPoint 2007 или более новых версиях. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/presentation/pptm

### POTX {#POTX}
```
public static final FileType POTX
```


Представляет шаблон презентации PowerPoint Open XML (.potx), который представляет шаблоны презентаций Microsoft PowerPoint, созданные в Microsoft PowerPoint 2007 и более новых версиях. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/presentation/potx

### POTM {#POTM}
```
public static final FileType POTM
```


Представляет шаблон презентации PowerPoint Open XML с поддержкой макросов (.potm), который является файлом шаблона Microsoft PowerPoint с поддержкой макросов. Файлы POTM создаются в PowerPoint 2007 или более новых версиях и содержат настройки по умолчанию, которые можно использовать для создания дальнейших файлов презентаций. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/presentation/potm

### PPSM {#PPSM}
```
public static final FileType PPSM
```


Представляет слайд PowerPoint Open XML с поддержкой макросов (.ppsm), который представляет формат файла слайд-шоу с включёнными макросами, созданный в Microsoft PowerPoint 2007 или более новых версиях. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/presentation/ppsm

### OTP {#OTP}
```
public static final FileType OTP
```


Представляет шаблон презентации OpenDocument (.otp), который представляет файлы шаблонов презентаций, созданные приложениями в формате стандарта OASIS OpenDocument. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


Представляет электронную таблицу Excel (.xls), которая представляет двоичный формат файла Excel. Такие файлы могут быть созданы Microsoft Excel, а также другими аналогичными программами для работы с таблицами, такими как OpenOffice Calc или Apple Numbers. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### EXCEL_2003_XML {#EXCEL-2003-XML}
```
public static final FileType EXCEL_2003_XML
```


Представляет файл Excel 2003 XML (SpreadsheetML) (.xml), который представляет двоичный формат файла Excel. Такие файлы могут быть созданы Microsoft Excel, а также другими аналогичными программами для работы с таблицами, такими как OpenOffice Calc или Apple Numbers. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### NUMBERS {#NUMBERS}
```
public static final FileType NUMBERS
```


Представляет Apple Numbers (.numbers), который представляет двоичный файловый формат, похожий на Excel. Такие файлы могут быть созданы приложением Apple Numbers. Узнайте больше об этом файловом формате [here][].


[here]: https://fileinfo.com/extension/numbers

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Представляет Microsoft Excel Open XML Spreadsheet (.xlsx), который является широко известным форматом документов Microsoft Excel, представленным Microsoft в выпуске Microsoft Office 2007. Узнайте больше об этом файловом формате [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Представляет Excel Open XML Macro-Enabled Spreadsheet (.xlsm), который является типом файлов таблиц, поддерживающих макросы. Узнайте больше об этом файловом формате [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Представляет Excel Binary Spreadsheet (.xlsb), который определяет двоичный файловый формат Excel. Это набор записей и структур, описывающих содержимое рабочей книги Excel. Узнайте больше об этом файловом формате [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


Представляет файл значений, разделённых запятыми (.csv), который представляет собой обычные текстовые файлы, содержащие записи данных со значениями, разделёнными запятыми. Узнайте больше об этом файловом формате [here][].


[here]: https://wiki.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


Представляет файл значений, разделённых табуляцией (.tsv), который представляет данные, разделённые табуляциями, в обычном текстовом формате. Узнайте больше об этом файловом формате [here][].


[here]: https://wiki.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


Представляет OpenDocument Spreadsheet (.ods), что означает формат документа электронной таблицы OpenDocument, редактируемый пользователем. Данные хранятся в файлах ODF в виде строк и столбцов. Узнайте больше об этом файловом формате [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ods

### FODS {#FODS}
```
public static final FileType FODS
```


Представляет OpenDocument Flat XML Spreadsheet (.fods). Это формат документа электронной таблицы, основанный на XML и используемый в OpenOffice и LibreOffice. Узнайте больше об этом файловом формате [here][].


[here]: https://wiki.fileformat.com/spreadsheet/fods

### OTS {#OTS}
```
public static final FileType OTS
```


Представляет OpenDocument Spreadsheet Template (.ots). Это шаблонный формат документа, используемый в OpenOffice и LibreOffice для электронных таблиц. Узнайте больше об этом файловом формате [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ots

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Представляет Microsoft Excel Add-in (.xlam). Это файловый формат, используемый Microsoft Excel для создания надстроек с пользовательской функциональностью. Узнайте больше об этом файловом формате [here][].


[here]: https://fileinfo.com/extension/xlam

### XLTM {#XLTM}
```
public static final FileType XLTM
```


Представляет Microsoft Excel Macro-Enabled Template (.xltm), который представляет файлы, создаваемые Microsoft Excel как шаблоны с поддержкой макросов. Файлы XLTM похожи на XLTX по структуре, за исключением того, что последние не поддерживают создание шаблонов с макросами. Узнайте больше об этом файловом формате [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltm

### XLT {#XLT}
```
public static final FileType XLT
```


Представляет Microsoft Excel Template (.xlt), который представляет собой шаблонные файлы, созданные в Microsoft Excel — приложении для электронных таблиц, входящем в состав пакета Microsoft Office. Microsoft Office 97‑2003 поддерживал создание новых файлов XLT, а также их открытие. Узнайте больше об этом файловом формате [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlt

### XLTX {#XLTX}
```
public static final FileType XLTX
```


Представляет Excel Open XML Spreadsheet Template (.xltx), который представляет шаблоны Microsoft Excel, основанные на спецификациях файлового формата Office OpenXML. Он используется для создания стандартного шаблонного файла, который может быть использован для генерации файлов XLSX с теми же настройками, указанными в файле XLTX. Узнайте больше об этом файловом формате [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltx

### SXC {#SXC}
```
public static final FileType SXC
```


Представляет StarOffice Calc Spreadsheet (.sxc). Это документ электронной таблицы, созданный в StarOffice Calc, программе для работы с таблицами. Узнайте больше об этом файловом формате [here][].


[here]: https://wiki.fileformat.com/spreadsheet/sxc

### MPP {#MPP}
```
public static final FileType MPP
```


Представляет Microsoft Project File (.mpp), который является файлом данных Microsoft Project, хранящим информацию, связанную с управлением проектами, в интегрированном виде. Узнайте больше об этом файловом формате [here][].


[here]: https://wiki.fileformat.com/project-management/mpp

### MPT {#MPT}
```
public static final FileType MPT
```


Представляет Microsoft Project Template (.mpt), который содержит базовую информацию и структуру, а также настройки документа для создания файлов .MPP. Узнайте больше об этом файловом формате [here][].


[here]: https://wiki.fileformat.com/project-management/mpt

### MPX {#MPX}
```
public static final FileType MPX
```


Представляет Microsoft Project Exchange file (.mpx), который является ASCII‑форматом файла для передачи проектной информации между Microsoft Project (MSP) и другими приложениями, поддерживающими формат MPX, такими как Primavera Project Planner, Sciforma и Timerline Precision Estimating. Узнайте больше об этом файловом формате [here][].


[here]: https://wiki.fileformat.com/project-management/mpx

### AS {#AS}
```
public static final FileType AS
```


Представляет файл ActionScript (.as). Узнайте больше об этом файловом формате [here][].


[here]: https://docs.fileformat.com/programming/as

### AS_3 {#AS-3}
```
public static final FileType AS_3
```


Представляет файл ActionScript (.as3). Узнайте больше об этом файловом формате [here][].


[here]: https://datatypes.net/open-as3-files

### ASM {#ASM}
```
public static final FileType ASM
```


Представляет файл исходного кода на ассемблере (.asm). Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/cad/asm

### BAT {#BAT}
```
public static final FileType BAT
```


Представляет файл пакетных команд DOS (.bat). Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/executable/bat

### C {#C}
```
public static final FileType C
```


Представляет файл исходного кода C/C++ (.c). Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/programming/c

### CC {#CC}
```
public static final FileType CC
```


Представляет файл исходного кода C++ (.cc). Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/programming/cc

### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Представляет файл CMake (.cmake). Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/programming/cmake

### CPP {#CPP}
```
public static final FileType CPP
```


Представляет файл исходного кода C++ (.cpp). Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/programming/cpp

### CS {#CS}
```
public static final FileType CS
```


Представляет файл исходного кода C# (.cs), который является файлом исходного кода для языка программирования C#. Он был введён Microsoft для использования с .NET Framework. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/programming/cs

### VB {#VB}
```
public static final FileType VB
```


Представляет файл элемента проекта Visual Basic (.vb), который является файлом исходного кода, созданным на языке Visual Basic. Он был создан Microsoft для разработки приложений .NET. Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/programming/vb

### CSS {#CSS}
```
public static final FileType CSS
```


Представляет файл таблицы стилей CSS (.css). Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/web/css

### CXX {#CXX}
```
public static final FileType CXX
```


Представляет файл исходного кода C++ (.cxx). Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/programming/cxx

### DIFF {#DIFF}
```
public static final FileType DIFF
```


Представляет файл патча (.diff). Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/programming/diff

### ERB {#ERB}
```
public static final FileType ERB
```


Представляет скрипт Ruby ERB (.erb). Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/programming/erb

### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Представляет файл исходного кода Groovy (.groovy). Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/programming/groovy

### H {#H}
```
public static final FileType H
```


Представляет заголовочный файл C/C++/Objective-C (.h). Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/programming/h

### HAML {#HAML}
```
public static final FileType HAML
```


Представляет файл исходного кода Haml (.haml). Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/programming/haml

### HH {#HH}
```
public static final FileType HH
```


Представляет заголовочный файл C++ (.hh). Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/programming/hh

### JAVA {#JAVA}
```
public static final FileType JAVA
```


Представляет файл исходного кода Java (.java). Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/programming/java

### JS {#JS}
```
public static final FileType JS
```


Представляет файл JavaScript (.js). Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/web/js

### JSON {#JSON}
```
public static final FileType JSON
```


Представляет файл JavaScript Object Notation (.json). Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/web/json

### LESS {#LESS}
```
public static final FileType LESS
```


Представляет файл таблицы стилей LESS (.less). Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/web/less

### LOG {#LOG}
```
public static final FileType LOG
```


Представляет файл журнала (.log). Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/database/log

### M {#M}
```
public static final FileType M
```


Представляет файл реализации Objective-C (.m). Узнайте больше об этом формате файла [here][].


[here]: https://fileinfo.com/extension/m

### MAKE {#MAKE}
```
public static final FileType MAKE
```


Представляет скрипт Makefile Xcode (.make). Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/programming/make

### MD {#MD}
```
public static final FileType MD
```


Представляет файл документации в формате Markdown (.md). Узнайте больше об этом формате файла [here][].


[here]: https://docs.fileformat.com/word-processing/md

### ML {#ML}
```
public static final FileType ML
```


Представляет файл исходного кода ML (.ml). Узнайте больше об этом формате файла [here][].


[here]: https://wiki.fileformat.com/programming/ml

### MM {#MM}
```
public static final FileType MM
```


Представляет файл исходного кода Objective-C++ (.mm). Узнайте больше о этом формате файла [here][].


[here]: https://docs.fileformat.com/programming/mm

### PHP {#PHP}
```
public static final FileType PHP
```


Представляет файл исходного кода PHP (.php). Узнайте больше о этом формате файла [here][].


[here]: https://wiki.fileformat.com/programming/php

### PL {#PL}
```
public static final FileType PL
```


Представляет скрипт Perl (.pl). Узнайте больше о этом формате файла [here][].


[here]: https://docs.fileformat.com/programming/pl

### PROPERTIES {#PROPERTIES}
```
public static final FileType PROPERTIES
```


Представляет файл свойств Java (.properties). Узнайте больше о этом формате файла [here][].


[here]: https://fileinfo.com/extension/properties

### PY {#PY}
```
public static final FileType PY
```


Представляет скрипт Python (.py). Узнайте больше о этом формате файла [here][].


[here]: https://docs.fileformat.com/programming/py

### RB {#RB}
```
public static final FileType RB
```


Представляет файл исходного кода Ruby (.rb). Узнайте больше о этом формате файла [here][].


[here]: https://docs.fileformat.com/programming/rb

### RST {#RST}
```
public static final FileType RST
```


Представляет файл reStructuredText (.rst). Узнайте больше о этом формате файла [here][].


[here]: https://docs.fileformat.com/programming/rst

### SASS {#SASS}
```
public static final FileType SASS
```


Представляет файл Syntactically Awesome StyleSheets (.sass). Узнайте больше о этом формате файла [here][].


[here]: https://docs.fileformat.com/web/sass

### SCALA {#SCALA}
```
public static final FileType SCALA
```


Представляет файл исходного кода Scala (.scala). Узнайте больше о этом формате файла [here][].


[here]: https://docs.fileformat.com/programming/scala

### SCM {#SCM}
```
public static final FileType SCM
```


Представляет файл исходного кода Scheme (.scm). Узнайте больше о этом формате файла [here][].


[here]: https://docs.fileformat.com/programming/scm

### SCRIPT {#SCRIPT}
```
public static final FileType SCRIPT
```


Представляет файл общего скрипта (.script). Узнайте больше о этом формате файла [here][].


[here]: https://docs.fileformat.com/programming/script

### SH {#SH}
```
public static final FileType SH
```


Представляет скрипт Bash Shell (.sh). Узнайте больше о этом формате файла [here][].


[here]: https://docs.fileformat.com/cs/programming/sh

### SML {#SML}
```
public static final FileType SML
```


Представляет файл исходного кода Standard ML (.sml). Узнайте больше о этом формате файла [here][].


[here]: https://fileinfo.com/extension/sml

### SQL {#SQL}
```
public static final FileType SQL
```


Представляет файл данных Structured Query Language (.sql). Узнайте больше о этом формате файла [here][].


[here]: https://wiki.fileformat.com/database/sql

### VIM {#VIM}
```
public static final FileType VIM
```


Представляет файл настроек Vim (.vim). Узнайте больше о этом формате файла [here][].


[here]: https://fileinfo.com/extension/vim

### YAML {#YAML}
```
public static final FileType YAML
```


Представляет документ YAML (.yaml). Узнайте больше о этом формате файла [here][].


[here]: https://docs.fileformat.com/programming/yaml

### DOC {#DOC}
```
public static final FileType DOC
```


Представляет документ Microsoft Word (.doc). Узнайте больше о этом формате файла [here][].


[here]: https://wiki.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Представляет документ Microsoft Word Open XML (.docx). Узнайте больше о этом формате файла [here][].


[here]: https://wiki.fileformat.com/word-processing/docx

### CHM {#CHM}
```
public static final FileType CHM
```


Представляет файл Microsoft Compiled HTML Help (.chm). Узнайте больше о этом формате файла [here][].


[here]: https://docs.fileformat.com/web/chm

### DOCM {#DOCM}
```
public static final FileType DOCM
```


Представляет документ Word Open XML с поддержкой макросов (.docm). Узнайте больше о этом формате файла [here][].


[here]: https://wiki.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


Представляет шаблон документа Word (.dot). Узнайте больше о этом формате файла [here][].


[here]: https://wiki.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Представляет шаблон документа Word Open XML (.dotx). Узнайте больше о этом формате файла [here][].


[here]: https://wiki.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Представляет шаблон документа Word Open XML с поддержкой макросов (.dotm). Узнайте больше о этом формате файла [here][].


[here]: https://wiki.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


Представляет файл Rich Text Format (.rtf). Узнайте больше о этом формате файла [here][].


[here]: https://wiki.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


Представляет файл обычного текста (.txt). Узнайте больше о этом формате файла [here][].


[here]: https://wiki.fileformat.com/word-processing/txt

### ODT {#ODT}
```
public static final FileType ODT
```


Представляет текстовый документ OpenDocument (.odt). Узнайте больше о этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


Представляет шаблон документа OpenDocument (.ott). Это шаблонный документ, созданный в соответствии со стандартным форматом OpenDocument от OASIS. Узнайте больше о этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/word-processing/ott

### VCF {#VCF}
```
public static final FileType VCF
```


Представляет файл vCard (.vcf), который является цифровым форматом для хранения контактной информации. Он широко используется для обмена данными между популярными приложениями обмена информацией. Узнайте больше о этом формате файла [здесь][].


[here]: https://wiki.fileformat.com/email/vcf

### AI {#AI}
```
public static final FileType AI
```


Представляет файл Adobe Illustrator (.ai), который является форматом файлов для рисунков Adobe Illustrator. Узнайте больше о этом формате файла [здесь][].


[here]: https://docs.fileformat.com/image/ai

### PSM1 {#PSM1}
```
public static final FileType PSM1
```


Представляет файл модуля скриптов PowerShell (.psm1). Это формат файлов для скриптов модулей PowerShell. Узнайте больше о этом формате файла [здесь][].


[here]: https://fileinfo.com/extension/psm1

### PS1 {#PS1}
```
public static final FileType PS1
```


Представляет файл скрипта PowerShell (.ps1). Это формат файлов для командлетов Windows PowerShell. Узнайте больше о этом формате файла [здесь][].


[here]: https://fileinfo.com/extension/ps1

### PSD1 {#PSD1}
```
public static final FileType PSD1
```


Представляет файл манифеста модуля скриптов PowerShell (.psd1). Это формат файлов для скриптов манифеста модуля PowerShell. Узнайте больше о этом формате файла [здесь][].


[here]: https://fileinfo.com/extension/psd1

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


Сопоставляет расширение файла с типом файла.

Этот метод принимает расширение файла, с точкой "." или без неё, и возвращает соответствующий тип файла, если он поддерживается. Если тип файла не поддерживается, он возвращает тип файла по умолчанию [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| extension | java.lang.String | Расширение файла с точкой "." или без неё. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromFilePath(String filePath) {#fromFilePath-java.lang.String-}
```
public static FileType fromFilePath(String filePath)
```


Извлекает расширение файла из имени файла или пути к файлу и сопоставляет его с типом файла.

Если тип файла поддерживается, метод возвращает соответствующий  FileType , иначе он возвращает тип файла по умолчанию [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Имя файла или путь к файлу. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromMediaType(String mediaType) {#fromMediaType-java.lang.String-}
```
public static FileType fromMediaType(String mediaType)
```


Отображает медиа‑тип файла на тип файла. Например, 'application/pdf' будет сопоставлен с [PDF](../../com.groupdocs.viewer/filetype\#PDF).

Этот метод принимает медиа‑тип файла в качестве входных данных и сопоставляет его с соответствующим  FileType . Если медиа‑тип поддерживается, метод возвращает соответствующий тип файла. Если медиа‑тип не поддерживается, он возвращает тип файла по умолчанию [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mediaType | java.lang.String | Медиа‑тип файла, например, 'application/pdf'. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if found, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream stream)
```


Определяет тип файла, читая сигнатуру файла.

Этот метод принимает входной поток, представляющий файл, и пытается определить его тип, анализируя сигнатуру файла. Сигнатура файла — уникальная последовательность байтов в начале файла, указывающая его тип. Метод считывает сигнатуру файла из входного потока и сравнивает её с известными сигнатурами поддерживаемых типов файлов. Если найдено совпадение, метод возвращает соответствующий тип файла. Если совпадения не найдено, он возвращает тип файла по умолчанию [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток, представляющий файл. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password) {#fromStream-java.io.InputStream-java.lang.String-}
```
public static FileType fromStream(InputStream stream, String password)
```


Определяет тип файла, читая сигнатуру файла.

Этот метод анализирует сигнатуру файла, которая представляет собой уникальную последовательность байтов в начале файла, чтобы определить тип файла. Он считывает сигнатуру файла из предоставленного входного потока и сравнивает её с известными сигнатурами поддерживаемых типов файлов. Если найдено совпадение, метод возвращает соответствующий тип файла. Если совпадения не найдено, он возвращает тип файла по умолчанию [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

Если файл зашифрован и требует пароль для открытия, пароль должен быть передан в качестве параметра этому методу. Пароль будет использован для расшифровки файла и анализа его сигнатуры с целью определения типа файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток, представляющий файл. |
| password | java.lang.String | Пароль для открытия файла. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, ILogger logger) {#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, ILogger logger)
```


Определяет тип файла, читая сигнатуру файла.

Этот метод анализирует сигнатуру файла, которая представляет собой уникальную последовательность байтов в начале файла, чтобы определить тип файла. Он считывает сигнатуру файла из предоставленного входного потока и сравнивает её с известными сигнатурами поддерживаемых типов файлов. Если найдено совпадение, метод возвращает соответствующий тип файла. Если совпадения не найдено, он возвращает тип файла по умолчанию [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

Можно предоставить логгер для записи любой релевантной информации или ошибок во время процесса определения типа файла. Логгер должен реализовывать интерфейс ILogger. Если логгер не предоставлен, процесс определения не будет генерировать вывод в журнал.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток, представляющий файл. |
| logger | com.groupdocs.foundation.logging.ILogger | Логгер для записи информации или ошибок. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password, ILogger logger) {#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, String password, ILogger logger)
```


Определяет тип файла, читая сигнатуру файла.

Этот метод анализирует сигнатуру файла, которая представляет собой уникальную последовательность байтов в начале файла, чтобы определить тип файла. Он считывает сигнатуру файла из предоставленного входного потока и сравнивает её с известными сигнатурами поддерживаемых типов файлов. Если найдено совпадение, метод возвращает соответствующий тип файла. Если совпадения не найдено, он возвращает тип файла по умолчанию [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

Пароль может быть указан, если файл зашифрован или защищён. Пароль будет использован для открытия файла перед анализом сигнатуры файла. Если файл не требует пароля, этот параметр можно установить в null.

Можно предоставить логгер для записи любой релевантной информации или ошибок во время процесса определения типа файла. Логгер должен реализовывать интерфейс ILogger. Если логгер не предоставлен, процесс определения не будет генерировать вывод в журнал.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток, представляющий файл. |
| password | java.lang.String | Пароль для открытия файла. |
| logger | com.groupdocs.foundation.logging.ILogger | Логгер для записи информации или ошибок. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Получает поддерживаемые типы файлов.

Этот метод возвращает последовательность всех поддерживаемых системой типов файлов. Типы файлов представляют различные форматы документов, которые могут быть обработаны или распознаны системой.

 **Learn more**

 *  Learn more about the supported document formats: [Full list of supported file formats][]


[Full list of supported file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/

**Returns:**
java.util.List<com.groupdocs.viewer.FileType> — последовательность поддерживаемых типов файлов.
### detectCharset(String filePath) {#detectCharset-java.lang.String-}
```
public static Charset detectCharset(String filePath)
```


Пытается определить кодировку текстовых файлов [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) и [CSV](../../com.groupdocs.viewer/filetype\#CSV) по пути.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Имя файла или путь к файлу. |

**Returns:**
java.nio.charset.Charset — набор символов или null, если не удалось определить кодировку файла.

**Example:**

```
Charset charset = FileType.detectCharset("message.txt");
```
### detectCharset(InputStream stream) {#detectCharset-java.io.InputStream-}
```
public static Charset detectCharset(InputStream stream)
```


Пытается определить кодировку текстового файла [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) и [CSV](../../com.groupdocs.viewer/filetype\#CSV) по потоку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток файла. |

**Returns:**
java.nio.charset.Charset — набор символов или null, если не удалось определить кодировку файла.

**Example:**

```
InputStream stream = new FileInputStream("message.txt");
 Charset charset = FileType.detectCharset(stream);
```
### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Получает название формата файла, например, "Microsoft Word Document".

**Returns:**
java.lang.String — название формата файла.
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Получает суффикс расширения файла (включая точку "."), например, ".doc".

**Returns:**
java.lang.String — суффикс расширения файла.
### toString() {#toString--}
```
public String toString()
```


Возвращает строковое представление текущего объекта.

**Returns:**
java.lang.String — строковое представление текущего объекта.
