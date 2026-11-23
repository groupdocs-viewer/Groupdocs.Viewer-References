---
title: "FileType"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Представляет тип файла."
type: docs
weight: 14
url: /ru/java/com.groupdocs.viewer/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, com.groupdocs.viewer.caching.Cacheable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>, Cacheable
```

Представляет тип файла. Предоставляет методы для получения списка всех типов файлов, поддерживаемых компонентом GroupDocs.Viewer.


Перечисление FileType предоставляет константы, представляющие различные типы файлов, поддерживаемые компонентом GroupDocs.Viewer.
Вы можете использовать методы этого перечисления для получения списка всех поддерживаемых типов файлов или проверки, поддерживается ли конкретный тип файла.


Пример использования:

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


## Поля

| Поле | Описание |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | Представляет неизвестный тип файла. |
|
|  | [ZIP](#ZIP) | Представляет zip‑файл (.zip), который может содержать один или несколько файлов или каталогов. |
|
|  | [TAR](#TAR) | Представляет объединённый Unix‑архив (.tar), созданный для сбора одного или нескольких файлов. |
|
|  | [XZ](#XZ) | Представляет XZ‑файл (.xz), сжатый с использованием алгоритма высокого коэффициента сжатия, основанного на алгоритме LZMA. |
|
|  | [TXZ](#TXZ) | Представляет собой консолидированный Unix-архив файлов (.txz, .tar.xz), созданный для сбора одного или нескольких файлов. |
|
|  | [TARXZ](#TARXZ) | Представляет собой консолидированный Unix-архив файлов (.txz, .tar.xz), созданный для сбора одного или нескольких файлов. |
|
|  | [TGZ](#TGZ) | Представляет собой консолидированный Unix-архив файлов (.tgz, .tar.gz), созданный для сбора одного или нескольких файлов. |
|
|  | [TARGZ](#TARGZ) | Представляет собой консолидированный Unix-архив файлов (.tgz, .tar.gz), созданный для сбора одного или нескольких файлов. |
|
|  | [BZ_2](#BZ-2) | Представляет собой файл, сжатый Bzip2 (.bz2), созданный с использованием открытого метода сжатия BZIP2. |
|
|  | [RAR](#RAR) | Представляет собой файл, сжатый в архив Roshal (.rar), созданный с использованием метода сжатия RAR (WINRAR версии 4). |
|
|  | [GZ](#GZ) | Представляет собой файл Gnu Zipped (.gz), сжатый с помощью приложения gzip. |
|
|  | [GZIP](#GZIP) | Представляет собой файл Gnu Zipped (.gzip), сжатый, представленный как бесплатная утилита для замены программы Compress, используемой в системах Unix. |
|
|  | [SEVEN_ZIP](#SEVEN-ZIP) | Представляет собой файл 7Zip (.7z, .7zip), который является бесплатным открытым архиватором с сжатием LZMA и LZMA2. |
|
|  | [CPIO](#CPIO) | Cpio — это общая утилита архивирования файлов и связанный с ней формат файлов. |
|
|  | [ZSTANDARD](#ZSTANDARD) | Файл ZST — это сжатый файл, созданный с помощью алгоритма сжатия Zstandard (zstd). |
|
|  | [TZST](#TZST) | Файлы TZST (.tar.zst, .tzst) являются архивами Zstandard (ZST), которые внутри содержат консолидированный Unix-архив файлов (Tar), созданный с помощью утилиты Unix для сбора одного или нескольких файлов. |
|
|  | [TAR_ZST](#TAR-ZST) | Файлы TZST (.tar.zst, .tzst) являются архивами Zstandard (ZST), которые внутри содержат консолидированный Unix-архив файлов (Tar), созданный с помощью утилиты Unix для сбора одного или нескольких файлов. |
|
|  | [ISO](#ISO) | Образ оптического диска ISO — это несжатый образ диска-архива, представляющий содержимое всех данных на оптическом диске, таком как CD или DVD, основанный на стандарте ISO-9660. |
|
|  | [LHA](#LHA) | LHA или LZH — это бесплатная утилита сжатия и связанный с ней формат файлов. |
|
|  | [CAB](#CAB) | Cabinet (или CAB) — это формат архивных файлов для Microsoft Windows. |
|
|  | [DXF](#DXF) | Представляет собой файл Drawing Exchange Format (.dxf), который является тегированным представлением данных файла чертежа AutoCAD. |
|
|  | [DWG](#DWG) | Представляет собой файл базы данных чертежей AutoCAD (.dwg), который представляет собой проприетарные бинарные файлы, используемые для хранения 2D и 3D данных дизайна. |
|
|  | [DWT](#DWT) | Представляет собой шаблон чертежа AutoCAD (.dwt), который является файлом шаблона чертежа AutoCAD, используемым в качестве основы для создания чертежей, которые могут быть сохранены как файлы DWG. |
|
|  | [STL](#STL) | Представляет собой файл стереолитографии (.stl), который является взаимозаменяемым форматом файлов, представляющим трехмерную поверхность. |
|
|  | [IFC](#IFC) | Представляет собой файл Industry Foundation Classes (.ifc), который является форматом файлов, устанавливающим международные стандарты импорта и экспорта строительных объектов и их свойств. |
|
|  | [DWF](#DWF) | Представляет собой файл Design Web Format (.dwf), который является сжатым форматом файлов для просмотра, рецензирования или печати 2D/3D чертежей. |
|
|  | [FBX](#FBX) | Представляет собой файл Autodesk FBX Interchange (FilmBoX) (.fbx), который является форматом 3D‑модели. |
|
|  | [DWFX](#DWFX) | Представляет собой файл Design Web Format XPS (.dwfx), который является сжатым форматом для просмотра, рецензирования или печати 2D/3D чертежей в виде документа XPS. |
|
|  | [DGN](#DGN) | Представляет собой файл дизайна MicroStation (.dgn), который представляет собой чертежи, созданные и поддерживаемые CAD‑приложениями, такими как MicroStation и Intergraph Interactive Graphics Design System. |
|
|  | [PLT](#PLT) | Представляет собой файл PLT (HPGL) (.plt), который является векторным файлом плоттера, представленным компанией Autodesk, Inc. |
|
|  | [CF2](#CF2) | Представляет собой файл Common File Format (.cf2). |
|
|  | [OBJ](#OBJ) | Представляет собой файл Wavefront 3D Object (.obj), который является 3D‑изображением, представленным компанией Wavefront Technologies. |
|
|  | [HPG](#HPG) | Представляет файл PLT (HPGL) (.hpg). |
|
|  | [IGS](#IGS) | Представляет файл Initial Graphics Exchange Specification (IGES) (.igs). |
|
|  | [VSD](#VSD) | Представляет файл Visio Drawing (.vsd), которые являются чертежами, созданными в приложении Microsoft Visio для представления разнообразных графических объектов и их взаимосвязей. |
|
|  | [VSDX](#VSDX) | Представляет файл Visio Drawing (.vsdx), который представляет формат файлов Microsoft Visio, введённый, начиная с Microsoft Office 2013. |
|
|  | [VSS](#VSS) | Представляет файл Visio Stencil (.vss), который является шаблонными файлами, созданными в Microsoft Visio 2007 и более ранних версиях. |
|
|  | [VSSX](#VSSX) | Представляет файл Visio Stencil (.vssx), который является шаблонами чертежей, созданными в Microsoft Visio 2013 и более новых версиях. |
|
|  | [VSDM](#VSDM) | Представляет файл Visio Macro-Enabled Drawing (.vsdm), который является файлами чертежей, созданными в приложении Microsoft Visio и поддерживающими макросы. |
|
|  | [VST](#VST) | Представляет файл Visio Drawing Template (.vst), который является векторными изображениями, созданными в Microsoft Visio. |
|
|  | [VSTX](#VSTX) | Представляет файл Visio Drawing Template (.vstx), который является шаблонами чертежей, созданными в Microsoft Visio 2013 и более новых версиях. |
|
|  | [VSTM](#VSTM) | Представляет файл Visio Macro-Enabled Drawing Template (.vstm), который является шаблонами, созданными в Microsoft Visio и поддерживающими макросы. |
|
|  | [VSSM](#VSSM) | Представляет файл Visio Macro-Enabled Stencil (.vssm), который является шаблонными файлами Microsoft Visio, поддерживающими макросы. |
|
|  | [VSX](#VSX) | Представляет файл Visio Stencil XML (.vsx), который относится к шаблонам, состоящим из чертежей и фигур, используемых для создания диаграмм в Microsoft Visio. |
|
|  | [VTX](#VTX) | Представляет файл Visio Template XML (.vtx), который является шаблоном чертежа Microsoft Visio, сохранённым на диск в формате XML. |
|
|  | [VDW](#VDW) | Представляет файл Visio Web Drawing (.vdw), который определяет потоки и хранилища, необходимые для отображения веб‑чертежа. |
|
|  | [VDX](#VDX) | Представляет файл Visio Drawing XML (.vdx), который представляет любой чертеж или диаграмму, созданные в Microsoft Visio, но сохранённые в формате XML с расширением .VDX. |
|
|  | [EPUB](#EPUB) | Представляет файл Open eBook (.epub), который является форматом электронных книг, предоставляющим стандартный цифровой формат публикаций для издателей и потребителей. |
|
|  | [MOBI](#MOBI) | Представляет файл Mobipocket eBook (.mobi), который является одним из наиболее широко используемых форматов электронных книг. |
|
|  | [AZW_3](#AZW-3) | Электронная книга Amazon Kindle Format 8 (KF8) — это цифровой формат файлов, разработанный для устройств Amazon Kindle. |
|
|  | [MSG](#MSG) | Представляет файл Outlook Mail Message (.msg), который является форматом файлов, используемым Microsoft Outlook и Exchange для хранения электронных сообщений, контактов, встреч или других задач. |
|
|  | [EML](#EML) | Представляет файл E-Mail Message (.eml), который представляет электронные сообщения, сохранённые с помощью Outlook и других соответствующих приложений. |
|
|  | [EMLX](#EMLX) | Представляет файл Apple Mail Message (.emlx), который реализован и разработан компанией Apple. |
|
|  | [PST](#PST) | Представляет файл Outlook Personal Information Store (.pst), который представляет файлы личного хранилища Outlook (также называемые Personal Storage Table), содержащие разнообразную пользовательскую информацию. |
|
|  | [OST](#OST) | Представляет файл Outlook Offline Data (.ost), который представляет данные почтового ящика пользователя в автономном режиме на локальном компьютере после регистрации на сервере Exchange с использованием Microsoft Outlook. |
|
|  | [TIF](#TIF) | Представляет файл Tagged Image File (.tif), который представляет растровые изображения, предназначенные для использования на различных устройствах, соответствующих данному стандарту формата файлов. |
|
|  | [TIFF](#TIFF) | Представляет файл Tagged Image File Format (.tiff), который представляет растровые изображения, предназначенные для использования на различных устройствах, соответствующих данному стандарту формата файлов. |
|
|  | [JPG](#JPG) | Представляет изображение JPEG (.jpg), которое является типом формата изображения, сохраняемого методом сжатия с потерями. |
|
|  | [JPEG](#JPEG) | Представляет изображение JPEG (.jpeg), которое является типом формата изображения, сохраняемого методом сжатия с потерями. |
|
|  | [JFIF](#JFIF) | Формат обмена файлами JPEG (.jfif) — это изображение, разработанное для быстрой передачи между платформами. |
|
|  | [PNG](#PNG) | Представляет графический формат Portable Network Graphic (.png), который является типом растрового формата файлов изображений, использующего без потерь сжатие. |
|
|  | [GIF](#GIF) | Представляет файл Graphical Interchange Format (.gif), который является типом сильно сжатого изображения. |
|
|  | [APNG](#APNG) | Представляет анимированный Portable Network Graphic (.apng), который является расширением формата PNG и поддерживает анимацию. |
|
|  | [BMP](#BMP) | Представляет файл растрового изображения (.bmp), который используется для хранения цифровых растровых изображений. |
|
|  | [ICO](#ICO) | Представляет файл значка (.ico), который является типом файла изображения, используемого в качестве иконки для представления приложения в Microsoft Windows. |
|
|  | [TGA](#TGA) | Представляет файл Truevision TGA (TARGA), который используется для хранения цифровых растровых изображений, разработанных компанией TRUEVISION. |
|
|  | [JP_2](#JP-2) | Представляет основной файл изображения JPEG 2000 (.jp2), который является системой кодирования изображений и передовым стандартом сжатия изображений. |
|
|  | [JPF](#JPF) | Представляет файл изображения JPEG 2000 (.jpf). |
|
|  | [JPX](#JPX) | Представляет файл изображения JPEG 2000 (.jpx). |
|
|  | [JPM](#JPM) | Представляет файл изображения JPEG 2000 (.jpm). |
|
|  | [J2C](#J2C) | Представляет поток ввода кода JPEG 2000 (.j2c). |
|
|  | [J2K](#J2K) | Представляет поток кода JPEG 2000 (.j2k), который представляет изображение, сжатое с использованием вейвлетного сжатия вместо DCT‑сжатия. |
|
|  | [JPC](#JPC) | Представляет поток кода JPEG 2000 (.jpc). |
|
|  | [JLS](#JLS) | Представляет файл JPEG-LS (JLS) (.jls). |
|
|  | [DIB](#DIB) | Представляет файл Device Independent Bitmap (.dib). |
|
|  | [WMF](#WMF) | Представляет Windows Metafile (.wmf), который представляет Microsoft Windows Metafile (WMF) для хранения векторных и растровых данных изображения. |
|
|  | [WMZ](#WMZ) | Представляет сжатый Windows Metafile (.wmz), который представляет Microsoft Windows Metafile (WMF), сжатый в архиве GZIP, для хранения векторных и растровых данных изображения. |
|
|  | [EMF](#EMF) | Представляет Enhanced Windows Metafile (.emf), который представляет графические изображения независимо от устройства. |
|
|  | [EMZ](#EMZ) | Представляет сжатый Windows Enhanced Metafile (.emz), который представляет графические изображения, независимо от устройства, сжатые с помощью GZIP. |
|
|  | [WEBP](#WEBP) | Представляет изображение WebP (.webp), который является современным растровым веб‑форматом файлов изображений, основанным на без потерь и с потерями сжатии. |
|
|  | [DNG](#DNG) | Представляет спецификацию Digital Negative (.dng), которая является форматом изображений цифровой камеры, используемым для хранения RAW‑файлов. |
|
|  | [CDR](#CDR) | Представляет векторный графический рисунок CorelDraw (.cdr), который является файлом векторного рисунка, изначально созданным в CorelDRAW для хранения цифрово закодированных и сжатых изображений. |
|
|  | [CMX](#CMX) | Представляет Corel Exchange (.cmx), который является файлом изображения чертежа и может содержать векторную графику, а также растровую графику. |
|
|  | [DJVU](#DJVU) | Представляет DjVu Image (.djvu), который является графическим форматом файлов, предназначенным для отсканированных документов и книг, особенно содержащих комбинацию текста, чертежей, изображений и фотографий. |
|
|  | [CGM](#CGM) | Представляет Computer Graphics Metafile (.cgm), который является бесплатным, независимым от платформы, международным стандартным форматом метафайлов для хранения и обмена векторной графикой (2D), растровой графикой и текстом. |
|
|  | [PCL](#PCL) | Представляет документ Printer Command Language (.pcl). |
|
|  | [PSD](#PSD) | Представляет Adobe Photoshop Document (.psd), который является родным форматом файла Adobe Photoshop, используемым для разработки и проектирования графики. |
|
|  | [PSB](#PSB) | Представляет Photoshop Large Document Format (.psb), который используется для разработки и проектирования графики в Adobe Photoshop. |
|
|  | [DCM](#DCM) | Представляет DICOM Image (.dcm), который представляет цифровое изображение, хранящее медицинскую информацию пациентов, такую как МРТ, КТ‑сканирование и ультразвуковые изображения. |
|
|  | [PS](#PS) | Представляет файл PostScript (.ps). |
|
|  | [EPS](#EPS) | Представляет Encapsulated PostScript File (.eps), который описывает программу языка Encapsulated PostScript, определяющую внешний вид одной страницы. |
|
|  | [ODG](#ODG) | Представляет OpenDocument Graphic File (.odg), который используется приложением Draw из Apache OpenOffice для хранения элементов чертежа в виде векторного изображения. |
|
|  | [FODG](#FODG) | Представляет Flat XML ODF Template (.fodg), который используется приложением Draw из Apache OpenOffice для хранения элементов чертежа в виде векторного изображения. |
|
|  | [SVG](#SVG) | Представляет Scalable Vector Graphics File (.svg), который является файлом Scalable Vector Graphics и использует текстовый формат на основе XML для описания внешнего вида изображения. |
|
|  | [SVGZ](#SVGZ) | Представляет Compressed Scalable Vector Graphics File (.svgz), который является файлом Scalable Vector Graphics, использующим текстовый формат на основе XML, сжатый с помощью GZIP, для описания внешнего вида изображения. |
|
|  | [OTG](#OTG) | Представляет OpenDocument Graphic Template (.otg). |
|
|  | [HTM](#HTM) | Представляет Hypertext Markup Language File (.htm), который является расширением веб‑страниц, созданных для отображения в браузерах. |
|
|  | [HTML](#HTML) | Представляет Hypertext Markup Language File (.html), который является расширением веб‑страниц, созданных для отображения в браузерах. |
|
|  | [MHT](#MHT) | Представляет MHTML Web Archive (.mht). |
|
|  | [NSF](#NSF) | Представляет Lotus Notes Database (.nsf). |
|
|  | [MBOX](#MBOX) | Представляет Email Mailbox File (.mbox). |
|
|  | [MHTML](#MHTML) | Представляет MIME HTML File (.mhtml). |
|
|  | [XML](#XML) | Представляет XML File (.xml). |
|
|  | [ONE](#ONE) | Представляет OneNote Document (.one), созданный приложением Microsoft OneNote. |
|
|  | [PDF](#PDF) | Представляет Portable Document Format File (.pdf), который является типом документа, созданного Adobe в 1990‑х годах. |
|
|  | [XPS](#XPS) | Представляет XML Paper Specification File (.xps), который представляет файлы макета страниц, основанные на XML Paper Specifications, созданные Microsoft. |
|
|  | [OXPS](#OXPS) | Представляет OpenXPS File (.oxps). |
|
|  | [TEX](#TEX) | Представляет исходный документ LaTeX (.tex), который является языком, включающим программирование, а также возможности разметки, используемые для наборa документов. |
|
|  | [OFD](#OFD) | Формат Open Fixed-layout Document (OFD), определённый стандартом GB/T 33190-2016, направлен на замену PDF в китайских государственных учреждениях. |
|
|  | [PPT](#PPT) | Представляет презентацию PowerPoint (.ppt), которая представляет файл PowerPoint, состоящий из набора слайдов для отображения в виде слайд-шоу. |
|
|  | [PPTX](#PPTX) | Представляет презентацию PowerPoint Open XML (.pptx), которая является файлом презентации, созданным с помощью популярного приложения Microsoft PowerPoint. |
|
|  | [PPS](#PPS) | Представляет слайд-шоу PowerPoint (.pps), которое создаётся с использованием Microsoft PowerPoint для целей слайд-шоу. |
|
|  | [PPSX](#PPSX) | Представляет файлы слайд-шоу PowerPoint Open XML (.ppsx), которые создаются с использованием Microsoft PowerPoint 2007 и более новых версий для целей слайд-шоу. |
|
|  | [ODP](#ODP) | Представляет презентацию OpenDocument (.odp), которая представляет формат файла презентации, используемый OpenOffice.org в стандарте OASIS Open. |
|
|  | [FODP](#FODP) | Представляет презентацию OpenDocument (.fodp), которая представляет OpenDocument Flat XML Presentation. |
|
|  | [POT](#POT) | Представляет шаблон PowerPoint (.pot), который представляет файлы шаблонов Microsoft PowerPoint, созданные в версиях PowerPoint 97–2003. |
|
|  | [PPTM](#PPTM) | Представляет презентацию PowerPoint Open XML с поддержкой макросов (.pptm), которая является файлом презентации с включёнными макросами, созданным в Microsoft PowerPoint 2007 или более новых версиях. |
|
|  | [POTX](#POTX) | Представляет шаблон презентации PowerPoint Open XML (.potx), который представляет шаблоны презентаций Microsoft PowerPoint, созданные в Microsoft PowerPoint 2007 и более новых версиях. |
|
|  | [POTM](#POTM) | Представляет шаблон презентации PowerPoint Open XML с поддержкой макросов (.potm), который является файлом шаблона Microsoft PowerPoint с поддержкой макросов. |
|
|  | [PPSM](#PPSM) | Представляет слайд PowerPoint Open XML с поддержкой макросов (.ppsm), который представляет формат файла слайд-шоу с включёнными макросами, созданный в Microsoft PowerPoint 2007 или более новых версиях. |
|
|  | [OTP](#OTP) | Представляет шаблон презентации OpenDocument (.otp), который представляет файлы шаблонов презентаций, созданные приложениями в формате стандарта OASIS OpenDocument. |
|
|  | [XLS](#XLS) | Представляет электронную таблицу Excel (.xls), которая представляет двоичный формат файлов Excel. |
|
|  | [EXCEL_2003_XML](#EXCEL-2003-XML) | Представляет Excel 2003 XML (SpreadsheetML) (.xml), который представляет двоичный формат файлов Excel. |
|
|  | [NUMBERS](#NUMBERS) | Представляет Apple Numbers (.numbers), который представляет двоичный формат файлов, похожий на Excel. |
|
|  | [XLSX](#XLSX) | Представляет электронную таблицу Microsoft Excel Open XML (.xlsx), которая является широко известным форматом документов Microsoft Excel, представленного Microsoft в выпуске Microsoft Office 2007. |
|
|  | [XLSM](#XLSM) | Представляет электронную таблицу Excel Open XML с поддержкой макросов (.xlsm), которая является типом файла таблицы, поддерживающего макросы. |
|
|  | [XLSB](#XLSB) | Представляет двоичную электронную таблицу Excel (.xlsb), которая определяет двоичный формат файлов Excel. |
|
|  | [CSV](#CSV) | Представляет файл значений, разделённых запятыми (.csv), который представляет текстовые файлы, содержащие записи данных со значениями, разделёнными запятыми. |
|
|  | [TSV](#TSV) | Представляет файл значений, разделённых табуляцией (.tsv), который представляет данные, разделённые табуляцией, в текстовом формате. |
|
|  | [ODS](#ODS) | Представляет электронную таблицу OpenDocument (.ods), которая обозначает формат документа OpenDocument Spreadsheet, редактируемый пользователем. |
|
|  | [FODS](#FODS) | Представляет электронную таблицу OpenDocument Flat XML (.fods). |
|
|  | [OTS](#OTS) | Представляет шаблон электронной таблицы OpenDocument (.ots). |
|
|  | [XLAM](#XLAM) | Представляет надстройку Microsoft Excel (.xlam). |
|
|  | [XLTM](#XLTM) | Представляет шаблон Microsoft Excel с поддержкой макросов (.xltm), который представляет файлы, создаваемые Microsoft Excel как шаблоны с поддержкой макросов. |
|
|  | [XLT](#XLT) | Представляет шаблон Microsoft Excel (.xlt), который является файлом шаблона, созданным с помощью Microsoft Excel, приложения для работы с электронными таблицами, входящего в состав пакета Microsoft Office. |
|
|  | [XLTX](#XLTX) | Представляет шаблон электронных таблиц Excel Open XML (.xltx), который представляет шаблоны Microsoft Excel, основанные на спецификациях формата файлов Office OpenXML. |
|
|  | [SXC](#SXC) | Представляет электронную таблицу StarOffice Calc (.sxc). |
|
|  | [MPP](#MPP) | Представляет файл Microsoft Project (.mpp), который является файлом данных Microsoft Project и хранит информацию, связанную с управлением проектами, в интегрированном виде. |
|
|  | [MPT](#MPT) | Представляет шаблон Microsoft Project (.mpt), который содержит базовую информацию и структуру, а также настройки документа для создания файлов .MPP. |
|
|  | [MPX](#MPX) | Представляет файл обмена Microsoft Project (.mpx), который является форматом ASCII для передачи информации о проектах между Microsoft Project (MSP) и другими приложениями, поддерживающими формат MPX, такими как Primavera Project Planner, Sciforma и Timerline Precision Estimating. |
|
|  | [AS](#AS) | Представляет файл ActionScript (.as). |
|
|  | [AS_3](#AS-3) | Представляет файл ActionScript (.as3). |
|
|  | [ASM](#ASM) | Представляет файл исходного кода на ассемблере (.asm). |
|
|  | [BAT](#BAT) | Представляет пакетный файл DOS (.bat). |
|
|  | [C](#C) | Представляет файл исходного кода C/C++ (.c). |
|
|  | [CC](#CC) | Представляет файл исходного кода C++ (.cc). |
|
|  | [CMAKE](#CMAKE) | Представляет файл CMake (.cmake). |
|
|  | [CPP](#CPP) | Представляет файл исходного кода C++ (.cpp). |
|
|  | [CS](#CS) | Представляет файл исходного кода C# (.cs), который является файлом исходного кода для языка программирования C#. |
|
|  | [VB](#VB) | Представляет файл элемента проекта Visual Basic (.vb), который является файлом исходного кода, созданным на языке Visual Basic. |
|
|  | [CSS](#CSS) | Представляет файл каскадных таблиц стилей (.css). |
|
|  | [CXX](#CXX) | Представляет файл исходного кода C++ (.cxx). |
|
|  | [DIFF](#DIFF) | Представляет файл патча (.diff). |
|
|  | [ERB](#ERB) | Представляет скрипт Ruby ERB (.erb). |
|
|  | [GROOVY](#GROOVY) | Представляет файл исходного кода Groovy (.groovy). |
|
|  | [H](#H) | Представляет заголовочный файл C/C++/Objective-C (.h). |
|
|  | [HAML](#HAML) | Представляет файл исходного кода Haml (.haml). |
|
|  | [HH](#HH) | Представляет файл заголовка C++ (.hh). |
|
|  | [JAVA](#JAVA) | Представляет файл исходного кода Java (.java). |
|
|  | [JS](#JS) | Представляет файл JavaScript (.js). |
|
|  | [JSON](#JSON) | Представляет файл JavaScript Object Notation (.json). |
|
|  | [LESS](#LESS) | Представляет файл таблицы стилей LESS (.less). |
|
|  | [LOG](#LOG) | Представляет файл журнала (.log). |
|
|  | [M](#M) | Представляет файл реализации Objective-C (.m). |
|
|  | [MAKE](#MAKE) | Представляет скрипт Xcode Makefile (.make). |
|
|  | [MD](#MD) | Представляет файл документации Markdown (.md). |
|
|  | [ML](#ML) | Представляет файл исходного кода ML (.ml). |
|
|  | [MM](#MM) | Представляет файл исходного кода Objective-C++ (.mm). |
|
|  | [PHP](#PHP) | Представляет файл исходного кода PHP (.php). |
|
|  | [PL](#PL) | Представляет скрипт Perl (.pl). |
|
|  | [PROPERTIES](#PROPERTIES) | Представляет файл свойств Java (.properties). |
|
|  | [PY](#PY) | Представляет скрипт Python (.py). |
|
|  | [RB](#RB) | Представляет файл исходного кода Ruby (.rb). |
|
|  | [RST](#RST) | Представляет файл reStructuredText (.rst). |
|
|  | [SASS](#SASS) | Представляет файл Syntactically Awesome StyleSheets (.sass). |
|
|  | [SCALA](#SCALA) | Представляет файл исходного кода Scala (.scala). |
|
|  | [SCM](#SCM) | Представляет файл исходного кода Scheme (.scm). |
|
|  | [SCRIPT](#SCRIPT) | Представляет файл универсального скрипта (.script). |
|
|  | [SH](#SH) | Представляет скрипт оболочки Bash (.sh). |
|
|  | [SML](#SML) | Представляет файл исходного кода Standard ML (.sml). |
|
|  | [SQL](#SQL) | Представляет файл данных Structured Query Language (.sql). |
|
|  | [VIM](#VIM) | Представляет файл настроек Vim (.vim). |
|
|  | [YAML](#YAML) | Представляет документ YAML (.yaml). |
|
|  | [DOC](#DOC) | Представляет файл документа Microsoft Word (.doc). |
|
|  | [DOCX](#DOCX) | Представляет файл документа Microsoft Word Open XML (.docx). |
|
|  | [CHM](#CHM) | Представляет файл справки Microsoft Compiled HTML Help (.chm). |
|
|  | [DOCM](#DOCM) | Представляет файл документа Word Open XML с поддержкой макросов (.docm). |
|
|  | [DOT](#DOT) | Представляет файл шаблона документа Word (.dot). |
|
|  | [DOTX](#DOTX) | Представляет файл шаблона документа Word Open XML (.dotx). |
|
|  | [DOTM](#DOTM) | Представляет файл шаблона документа Word Open XML с поддержкой макросов (.dotm). |
|
|  | [RTF](#RTF) | Представляет файл Rich Text Format (.rtf). |
|
|  | [TXT](#TXT) | Представляет файл простого текста (.txt). |
|
|  | [ODT](#ODT) | Представляет документ OpenDocument Text (.odt). |
|
|  | [OTT](#OTT) | Представляет шаблон документа OpenDocument (.ott). |
|
|  | [VCF](#VCF) | Представляет файл vCard (.vcf), который является цифровым форматом для хранения контактной информации. |
|
|  | [AI](#AI) | Представляет файл Adobe Illustrator (.ai), который является форматом файлов для рисунков Adobe Illustrator. |
|
|  | [PSM1](#PSM1) | Представляет файл модуля скрипта PowerShell (.psm1). |
|
|  | [PS1](#PS1) | Представляет файл скрипта PowerShell (.ps1). |
|
|  | [PSD1](#PSD1) | Представляет файл манифеста модуля скрипта PowerShell (.psd1). |
|
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Сопоставляет расширение файла с типом файла. |
|
|  | [fromFilePath(String filePath)](#fromFilePath-java.lang.String-) | Извлекает расширение файла из имени файла или пути к файлу и сопоставляет его с типом файла. |
|
|  | [fromMediaType(String mediaType)](#fromMediaType-java.lang.String-) | Сопоставляет тип медиа-файла с типом файла. |
|
|  | [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Определяет тип файла, читая сигнатуру файла. |
|
|  | [fromStream(InputStream stream, String password)](#fromStream-java.io.InputStream-java.lang.String-) | Определяет тип файла, читая сигнатуру файла. |
|
|  | [fromStream(InputStream stream, ILogger logger)](#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-) | Определяет тип файла, читая сигнатуру файла. |
|
|  | [fromStream(InputStream stream, String password, ILogger logger)](#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-) | Определяет тип файла, читая сигнатуру файла. |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | Получает поддерживаемые типы файлов. |
|
|  | [detectCharset(String filePath)](#detectCharset-java.lang.String-) | Пытается определить кодировку текстовых файлов [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV) и [CSV](../../com.groupdocs.viewer/filetype#CSV) по пути. |
|
|  | [detectCharset(InputStream stream)](#detectCharset-java.io.InputStream-) | Пытается определить кодировку текстовых файлов [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV) и [CSV](../../com.groupdocs.viewer/filetype#CSV) по потоку. |
|
|  | [getFileFormat()](#getFileFormat--) | Получает название формата файла, например, "Microsoft Word Document". |
|
|  | [getExtension()](#getExtension--) | Получает суффикс расширения файла (включая точку "."), например, ".doc". |
|
|  | [toString()](#toString--) | Возвращает строковое представление текущего объекта. |
|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Представляет неизвестный тип файла.


### ZIP {#ZIP}
```
public static final FileType ZIP
```


Представляет zip‑файл (.zip), который может содержать один или несколько файлов или каталогов.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/compression/zip).


### TAR {#TAR}
```
public static final FileType TAR
```


Представляет объединённый Unix‑архив (.tar), созданный для сбора одного или нескольких файлов.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/compression/tar).


### XZ {#XZ}
```
public static final FileType XZ
```


Представляет XZ‑файл (.xz), сжатый с использованием алгоритма высокого коэффициента сжатия, основанного на алгоритме LZMA.
Узнайте больше об этом формате файла [здесь](../https://fileinfo.com/extension/xz).


### TXZ {#TXZ}
```
public static final FileType TXZ
```


Представляет собой консолидированный Unix-архив файлов (.txz, .tar.xz), созданный для сбора одного или нескольких файлов.
Узнайте больше об этом формате файла [здесь](../https://fileinfo.com/extension/txz).


### TARXZ {#TARXZ}
```
public static final FileType TARXZ
```


Представляет собой консолидированный Unix-архив файлов (.txz, .tar.xz), созданный для сбора одного или нескольких файлов.
Узнайте больше об этом формате файла [здесь](../https://fileinfo.com/extension/txz).


### TGZ {#TGZ}
```
public static final FileType TGZ
```


Представляет собой консолидированный Unix-архив файлов (.tgz, .tar.gz), созданный для сбора одного или нескольких файлов.
Узнайте больше об этом формате файла [здесь](../https://fileinfo.com/extension/tgz).


### TARGZ {#TARGZ}
```
public static final FileType TARGZ
```


Представляет собой консолидированный Unix-архив файлов (.tgz, .tar.gz), созданный для сбора одного или нескольких файлов.
Узнайте больше об этом формате файла [здесь](../https://fileinfo.com/extension/tgz).


### BZ_2 {#BZ-2}
```
public static final FileType BZ_2
```


Представляет собой файл, сжатый Bzip2 (.bz2), созданный с использованием открытого метода сжатия BZIP2.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/compression/bz2).


### RAR {#RAR}
```
public static final FileType RAR
```


Представляет собой файл, сжатый в архив Roshal (.rar), созданный с использованием метода сжатия RAR (WINRAR версии 4).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/compression/rar).


### GZ {#GZ}
```
public static final FileType GZ
```


Представляет собой файл Gnu Zipped (.gz), сжатый с помощью приложения gzip.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/compression/gz).


### GZIP {#GZIP}
```
public static final FileType GZIP
```


Представляет собой файл Gnu Zipped (.gzip), сжатый, представленный как бесплатная утилита для замены программы Compress, используемой в системах Unix.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/compression/gz).


### SEVEN_ZIP {#SEVEN-ZIP}
```
public static final FileType SEVEN_ZIP
```


Представляет собой файл 7Zip (.7z, .7zip), который является бесплатным открытым архиватором с сжатием LZMA и LZMA2.
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/compression/7z/).


### CPIO {#CPIO}
```
public static final FileType CPIO
```


Cpio — это общая утилита архивирования файлов и связанный с ней формат файла. Она в основном установлена в Unix‑подобных операционных системах. Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/compression/cpio).


### ZSTANDARD {#ZSTANDARD}
```
public static final FileType ZSTANDARD
```


Файл ZST — это сжатый файл, созданный с помощью алгоритма сжатия Zstandard (zstd). Это сжатый файл, полученный без потерь с помощью данного алгоритма. Файлы ZST могут использоваться для сжатия различных типов файлов, таких как базы данных, файловые системы, сети и игры.
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/compression/zst/).


### TZST {#TZST}
```
public static final FileType TZST
```


Файлы TZST (.tar.zst, .tzst) являются архивами Zstandard (ZST), которые внутри содержат консолидированный Unix-архив файлов (Tar), созданный с помощью утилиты Unix для сбора одного или нескольких файлов.


### TAR_ZST {#TAR-ZST}
```
public static final FileType TAR_ZST
```


Файлы TZST (.tar.zst, .tzst) являются архивами Zstandard (ZST), которые внутри содержат консолидированный Unix-архив файлов (Tar), созданный с помощью утилиты Unix для сбора одного или нескольких файлов.


### ISO {#ISO}
```
public static final FileType ISO
```


Образ оптического диска ISO — это несжатый образ диска-архива, представляющий содержимое всех данных на оптическом диске, таком как CD или DVD, основанный на стандарте ISO-9660.
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/compression/iso/).


### LHA {#LHA}
```
public static final FileType LHA
```


LHA или LZH — это бесплатная утилита сжатия и связанный с ней формат файлов.
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/compression/lzh/).


### CAB {#CAB}
```
public static final FileType CAB
```


Cabinet (или CAB) — это формат архивных файлов для Microsoft Windows.
Узнайте больше об этом формате файла [здесь](../https://en.wikipedia.org/wiki/Cabinet_(file_format)).


### DXF {#DXF}
```
public static final FileType DXF
```


Представляет собой файл Drawing Exchange Format (.dxf), который является тегированным представлением данных файла чертежа AutoCAD.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/cad/dxf).


### DWG {#DWG}
```
public static final FileType DWG
```


Представляет собой файл базы данных чертежей AutoCAD (.dwg), который представляет собой проприетарные бинарные файлы, используемые для хранения 2D и 3D данных дизайна.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/cad/dwg).


### DWT {#DWT}
```
public static final FileType DWT
```


Представляет собой шаблон чертежа AutoCAD (.dwt), который является файлом шаблона чертежа AutoCAD, используемым в качестве основы для создания чертежей, которые могут быть сохранены как файлы DWG.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/cad/dwt).


### STL {#STL}
```
public static final FileType STL
```


Представляет файл стереолитографии (.stl), который является взаимозаменяемым форматом файла, описывающим трехмерную поверхность. Он обычно используется в быстром прототипировании, 3D‑печати и компьютерном производстве.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/cad/stl).


### IFC {#IFC}
```
public static final FileType IFC
```


Представляет файл Industry Foundation Classes (.ifc), который является форматом файла, устанавливающим международные стандарты импорта и экспорта строительных объектов и их свойств. Он обеспечивает совместимость между различными программными приложениями.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/cad/ifc).


### DWF {#DWF}
```
public static final FileType DWF
```


Представляет файл Design Web Format (.dwf), который является сжатым форматом файла для просмотра, проверки или печати 2D/3D чертежей. Он содержит графику и текст как часть данных проекта и уменьшает размер файла за счёт сжатия.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/cad/dwf).


### FBX {#FBX}
```
public static final FileType FBX
```


Представляет собой файл Autodesk FBX Interchange (FilmBoX) (.fbx), который является форматом 3D‑модели.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/cad/fbx).


### DWFX {#DWFX}
```
public static final FileType DWFX
```


Представляет файл Design Web Format XPS (.dwfx), который является сжатым форматом для просмотра, проверки или печати 2D/3D чертежей в виде XPS‑документа. Он содержит графику и текст как часть данных дизайна и уменьшает размер файла за счёт сжатия.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/cad/dwfx).


### DGN {#DGN}
```
public static final FileType DGN
```


Представляет собой файл дизайна MicroStation (.dgn), который представляет собой чертежи, созданные и поддерживаемые CAD‑приложениями, такими как MicroStation и Intergraph Interactive Graphics Design System.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/cad/dgn).


### PLT {#PLT}
```
public static final FileType PLT
```


Представляет файл PLT (HPGL) (.plt), который является векторным файлом плоттера, разработанным компанией Autodesk, Inc. Он содержит информацию для определённого CAD‑файла, и все изображения печатаются линиями вместо точек, обеспечивая точность и прецизионность производства.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/cad/plt).


### CF2 {#CF2}
```
public static final FileType CF2
```


Представляет собой файл Common File Format (.cf2).
Узнайте больше об этом формате файла [здесь](../https://fileinfo.com/extension/cf2).


### OBJ {#OBJ}
```
public static final FileType OBJ
```


Представляет собой файл Wavefront 3D Object (.obj), который является 3D‑изображением, представленным компанией Wavefront Technologies.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/3d/obj/).


### HPG {#HPG}
```
public static final FileType HPG
```


Представляет файл PLT (HPGL) (.hpg).
Это формат файла, используемый для файлов плоттера в HP Graphics Language (HPGL).
Узнайте больше об этом формате файла [здесь](../https://fileinfo.com/extension/hpg).


### IGS {#IGS}
```
public static final FileType IGS
```


Представляет файл Initial Graphics Exchange Specification (IGES) (.igs).


### VSD {#VSD}
```
public static final FileType VSD
```


Представляет файл Visio Drawing (.vsd), которые являются чертежами, созданными в приложении Microsoft Visio для представления разнообразных графических объектов и их взаимосвязей.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/vsd).


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Представляет файл Visio Drawing (.vsdx), который представляет формат файлов Microsoft Visio, введённый, начиная с Microsoft Office 2013. Он заменил бинарный формат (.VSD), поддерживаемый более ранними версиями Microsoft Visio.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/vsdx).


### VSS {#VSS}
```
public static final FileType VSS
```


Представляет файл шаблона Visio (.vss), который является шаблонным файлом, созданным в Microsoft Visio 2007 и более ранних версиях. Шаблонные файлы предоставляют объекты чертежа, которые могут быть включены в Visio‑чертёж .VSD.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/vss).


### VSSX {#VSSX}
```
public static final FileType VSSX
```


Представляет файл шаблона Visio (.vssx), который является набором шаблонов чертежей, созданных в Microsoft Visio 2013 и более новых версиях. Формат VSSX можно открыть в Visio 2013 и выше. Файлы Visio известны тем, что представляют разнообразные элементы чертежа, такие как фигуры, соединители, блок‑схемы, сетевые схемы, UML‑диаграммы и т.д.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/vssx).


### VSDM {#VSDM}
```
public static final FileType VSDM
```


Представляет файл Visio с поддержкой макросов (.vsdm), который является чертёжным файлом, созданным в приложении Microsoft Visio и поддерживающим макросы. Файлы VSDM — это чертежи OPC/XML, похожие на VSDX, но также предоставляющие возможность выполнения макросов при открытии файла.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/vsdm).


### VST {#VST}
```
public static final FileType VST
```


Представляет шаблон чертежа Visio (.vst), который является векторным файлом, созданным в Microsoft Visio. Он служит шаблоном для создания последующих файлов и содержит макет и настройки по умолчанию, используемые при создании новых чертежей Visio.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/vst).


### VSTX {#VSTX}
```
public static final FileType VSTX
```


Представляет шаблон чертежа Visio (.vstx), который является файлом шаблона чертежа, созданным в Microsoft Visio 2013 и более новых версиях. Эти файлы VSTX предоставляют отправную точку для создания чертежей Visio, сохраняемых как файлы .VSDX, с макетом и настройками по умолчанию.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/vstx).


### VSTM {#VSTM}
```
public static final FileType VSTM
```


Представляет шаблон чертежа Visio с поддержкой макросов (.vstm), который является шаблонным файлом, созданным в Microsoft Visio и поддерживающим макросы. Файлы, созданные на основе шаблонов VSTM, могут выполнять макросы, разработанные в коде Visual Basic for Applications (VBA).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/vstm).


### VSSM {#VSSM}
```
public static final FileType VSSM
```


Представляет файл шаблона Visio с поддержкой макросов (.vssm), который является файлом шаблона Microsoft Visio, поддерживающим макросы. При открытии файла VSSM можно выполнять макросы для получения требуемого форматирования и размещения фигур в диаграмме.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/vssm).


### VSX {#VSX}
```
public static final FileType VSX
```


Представляет XML‑файл шаблона Visio (.vsx), который относится к шаблонам, содержащим чертежи и фигуры, используемые для создания диаграмм в Microsoft Visio. Файлы VSX сохраняются в формате XML и поддерживались до Visio 2013.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/vsx).


### VTX {#VTX}
```
public static final FileType VTX
```


Представляет XML‑файл шаблона Visio (.vtx), который является шаблоном чертежа Microsoft Visio, сохранённым на диск в формате XML. Шаблон предоставляет базовые настройки для создания нескольких файлов Visio с одинаковыми параметрами.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/vtx).


### VDW {#VDW}
```
public static final FileType VDW
```


Представляет файл Visio Web Drawing (.vdw), который определяет потоки и хранилища, необходимые для отображения веб‑чертежа.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/web/vdw).


### VDX {#VDX}
```
public static final FileType VDX
```


Представляет XML‑файл чертежа Visio (.vdx), который представляет любой чертеж или схему, созданные в Microsoft Visio, но сохранённые в формате XML с расширением .VDX. XML‑файл чертежа Visio создаётся в программном обеспечении Visio, разработанном Microsoft.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/vdx).


### EPUB {#EPUB}
```
public static final FileType EPUB
```


Представляет файл Open eBook (.epub), который является форматом электронных книг, предоставляющим стандартный цифровой формат публикаций для издателей и читателей. Формат поддерживается многими электронными ридерами и программными приложениями.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/ebook/epub).


### MOBI {#MOBI}
```
public static final FileType MOBI
```


Представляет электронную книгу Mobipocket (.mobi), которая является одним из наиболее широко используемых форматов файлов электронных книг. Формат является улучшением старого формата OEB (Open Ebook Format) и использовался как проприетарный формат для Mobipocket Reader.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/ebook/mobi).


### AZW_3 {#AZW-3}
```
public static final FileType AZW_3
```


Электронная книга Amazon Kindle Format 8 (KF8) — это цифровой формат файла, разработанный для устройств Amazon Kindle. Формат является улучшением более старых файлов AZW и используется только на устройствах Kindle Fire с обратной совместимостью с предшествующими форматами, т.е. MOBI и AZW.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/ebook/azw3).


### MSG {#MSG}
```
public static final FileType MSG
```


Представляет файл Outlook Mail Message (.msg), который является форматом файлов, используемым Microsoft Outlook и Exchange для хранения электронных сообщений, контактов, встреч или других задач.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/email/msg).


### EML {#EML}
```
public static final FileType EML
```


Представляет сообщение электронной почты (.eml), которое представляет электронные письма, сохранённые с помощью Outlook и других соответствующих приложений. Практически все почтовые клиенты поддерживают этот формат файла благодаря его соответствию стандарту RFC‑822 Internet Message Format.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/email/eml).


### EMLX {#EMLX}
```
public static final FileType EMLX
```


Представляет сообщение Apple Mail (.emlx), которое реализовано и разработано компанией Apple. Приложение Apple Mail использует формат файла EMLX для экспорта электронных писем.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/email/emlx).


### PST {#PST}
```
public static final FileType PST
```


Представляет файл Outlook Personal Information Store (.pst), который представляет файлы личного хранилища Outlook (также называемые Personal Storage Table), содержащие разнообразную пользовательскую информацию.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/email/pst).


### OST {#OST}
```
public static final FileType OST
```


Представляет файл Outlook Offline Data (.ost), который представляет данные почтового ящика пользователя в автономном режиме на локальном компьютере после регистрации на сервере Exchange с использованием Microsoft Outlook.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/email/ost).


### TIF {#TIF}
```
public static final FileType TIF
```


Представляет файл Tagged Image File (.tif), который представляет растровые изображения, предназначенные для использования на различных устройствах, соответствующих этому стандарту формата файла. Он способен описывать двууровневые, градационные, палитровые и полноцветные данные изображения в нескольких цветовых пространствах.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/tiff).


### TIFF {#TIFF}
```
public static final FileType TIFF
```


Представляет формат Tagged Image File Format (.tiff), который представляет растровые изображения, предназначенные для использования на различных устройствах, соответствующих этому стандарту формата файла. Он способен описывать двууровневые, градационные, палитровые и полноцветные данные изображения в нескольких цветовых пространствах.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/tiff).


### JPG {#JPG}
```
public static final FileType JPG
```


Представляет изображение JPEG (.jpg), которое является типом формата изображения, сохраняемого методом сжатия с потерями. Выходное изображение, в результате сжатия, представляет собой компромисс между размером хранения и качеством изображения.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/image/jpeg).


### JPEG {#JPEG}
```
public static final FileType JPEG
```


Представляет изображение JPEG (.jpeg), которое является типом формата изображения, сохраняемого методом сжатия с потерями. Выходное изображение, в результате сжатия, представляет собой компромисс между размером хранения и качеством изображения.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/image/jpeg).


### JFIF {#JFIF}
```
public static final FileType JFIF
```


JPEG File Interchange Format (.jfif) — это изображение, разработанное для быстрой передачи между платформами. Этот формат использует сжатие JPEG. Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/image/jfif).


### PNG {#PNG}
```
public static final FileType PNG
```


Представляет графический файл Portable Network Graphic (.png), который является типом растрового формата изображения, использующего безпотерьное сжатие. Этот формат был создан как замена формата Graphics Interchange Format (GIF) и не имеет ограничений по авторским правам.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/image/png).


### GIF {#GIF}
```
public static final FileType GIF
```


Представляет файл Graphical Interchange Format (.gif), который является типом сильно сжатого изображения. Для каждого изображения GIF обычно допускает до 8 бит на пиксель, а всего допускается до 256 цветов.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/image/gif).


### APNG {#APNG}
```
public static final FileType APNG
```


Представляет анимированный Portable Network Graphic (.apng), который является расширением формата PNG и поддерживает анимацию.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/image/apng).


### BMP {#BMP}
```
public static final FileType BMP
```


Представляет файл Bitmap Image (.bmp), который используется для хранения растровых цифровых изображений. Эти изображения независимы от графического адаптера и также называются форматом device independent bitmap (DIB).
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/image/bmp).


### ICO {#ICO}
```
public static final FileType ICO
```


Представляет файл значка (.ico), который является типом файла изображения, используемого в качестве иконки для представления приложения в Microsoft Windows.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/image/ico).


### TGA {#TGA}
```
public static final FileType TGA
```


Представляет файл Truevision TGA (TARGA), который используется для хранения цифровых растровых изображений, разработанных компанией TRUEVISION.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/image/tga).


### JP_2 {#JP-2}
```
public static final FileType JP_2
```


Представляет основной файл изображения JPEG 2000 (.jp2), который является системой кодирования изображений и передовым стандартом сжатия изображений.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/image/jp2).


### JPF {#JPF}
```
public static final FileType JPF
```


Представляет файл изображения JPEG 2000 (.jpf).
Узнайте больше о этом формате файла [здесь](../https://docs.fileformat.com/image/jpf).


### JPX {#JPX}
```
public static final FileType JPX
```


Представляет файл изображения JPEG 2000 (.jpx).
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/image/jpx).


### JPM {#JPM}
```
public static final FileType JPM
```


Представляет файл изображения JPEG 2000 (.jpm).
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/image/jpm).


### J2C {#J2C}
```
public static final FileType J2C
```


Представляет поток ввода кода JPEG 2000 (.j2c).
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/image/j2c).


### J2K {#J2K}
```
public static final FileType J2K
```


Представляет поток кода JPEG 2000 (.j2k), который представляет изображение, сжатое с использованием вейвлетного сжатия вместо DCT‑сжатия.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/image/j2k).


### JPC {#JPC}
```
public static final FileType JPC
```


Представляет поток кода JPEG 2000 (.jpc).
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/image/jpc).


### JLS {#JLS}
```
public static final FileType JLS
```


Представляет файл JPEG-LS (JLS) (.jls).
Узнайте больше о этом формате файла [здесь](../https://fileinfo.com/extension/jls).


### DIB {#DIB}
```
public static final FileType DIB
```


Представляет файл Device Independent Bitmap (.dib).
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/image/dib).


### WMF {#WMF}
```
public static final FileType WMF
```


Представляет Windows Metafile (.wmf), который представляет Microsoft Windows Metafile (WMF) для хранения векторных и растровых данных изображения.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/image/wmf).


### WMZ {#WMZ}
```
public static final FileType WMZ
```


Представляет сжатый Windows Metafile (.wmz), который представляет Microsoft Windows Metafile (WMF), сжатый в архиве GZIP, для хранения векторных и растровых данных изображения.
Узнайте больше о этом формате файла [здесь](../https://fileinfo.com/extension/wmz#compressed_windows_metafile).


### EMF {#EMF}
```
public static final FileType EMF
```


Представляет расширенный Windows Metafile (.emf), который представляет графические изображения независимо от устройства. Метафайлы EMF состоят из записей переменной длины в хронологическом порядке, которые могут отобразить сохранённое изображение после разбора на любом выводном устройстве.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/emf).


### EMZ {#EMZ}
```
public static final FileType EMZ
```


Представляет собой Windows Compressed Enhanced Metafile (.emz), который содержит графические изображения, сжатые независимо от устройства с помощью GZIP. Метафайлы EMF состоят из записей переменной длины в хронологическом порядке, которые могут отобразить сохранённое изображение после разбора на любом выходном устройстве.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/emz).


### WEBP {#WEBP}
```
public static final FileType WEBP
```


Представляет собой изображение WebP (.webp), современный растровый веб‑формат файлов изображений, основанный на без потерь и с потерями сжатии. Он обеспечивает такое же качество изображения, значительно уменьшая размер файла.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/webp).


### DNG {#DNG}
```
public static final FileType DNG
```


Представляет собой спецификацию Digital Negative (.dng), формат изображения цифровой камеры, используемый для хранения RAW‑файлов. Он был разработан компанией Adobe в сентябре 2004 года и в основном применяется в цифровой фотографии.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/dng).


### CDR {#CDR}
```
public static final FileType CDR
```


Представляет собой CorelDraw Vector Graphic Drawing (.cdr), векторный графический файл, изначально созданный в CorelDRAW для хранения цифрово закодированных и сжатых изображений. Файл рисунка CDR содержит текст, линии, формы, изображения, цвета и эффекты для векторного представления содержимого изображения.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/cdr).


### CMX {#CMX}
```
public static final FileType CMX
```


Представляет Corel Exchange (.cmx), который является файлом изображения чертежа и может содержать векторную графику, а также растровую графику.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/cmx).


### DJVU {#DJVU}
```
public static final FileType DJVU
```


Представляет DjVu Image (.djvu), который является графическим форматом файлов, предназначенным для отсканированных документов и книг, особенно содержащих комбинацию текста, чертежей, изображений и фотографий.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/djvu).


### CGM {#CGM}
```
public static final FileType CGM
```


Представляет собой Computer Graphics Metafile (.cgm), свободный, независимый от платформы, международный стандартный формат метафайла для хранения и обмена векторной графикой (2D), растровой графикой и текстом. CGM использует объектно‑ориентированный подход и предоставляет множество функций для создания изображений.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/page-description-language/cgm).


### PCL {#PCL}
```
public static final FileType PCL
```


Представляет документ Printer Command Language (.pcl).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/page-description-language/pcl).


### PSD {#PSD}
```
public static final FileType PSD
```


Представляет Adobe Photoshop Document (.psd), который является родным форматом файла Adobe Photoshop, используемым для разработки и проектирования графики.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/psd).


### PSB {#PSB}
```
public static final FileType PSB
```


Представляет Photoshop Large Document Format (.psb), который используется для разработки и проектирования графики в Adobe Photoshop.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/psb).


### DCM {#DCM}
```
public static final FileType DCM
```


Представляет DICOM Image (.dcm), который представляет цифровое изображение, хранящее медицинскую информацию пациентов, такую как МРТ, КТ‑сканирование и ультразвуковые изображения.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/dcm).


### PS {#PS}
```
public static final FileType PS
```


Представляет файл PostScript (.ps).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/page-description-language/ps).


### EPS {#EPS}
```
public static final FileType EPS
```


Представляет Encapsulated PostScript File (.eps), который описывает программу языка Encapsulated PostScript, определяющую внешний вид одной страницы.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/page-description-language/eps).


### ODG {#ODG}
```
public static final FileType ODG
```


Представляет OpenDocument Graphic File (.odg), который используется приложением Draw из Apache OpenOffice для хранения элементов чертежа в виде векторного изображения.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/odg).


### FODG {#FODG}
```
public static final FileType FODG
```


Представляет Flat XML ODF Template (.fodg), который используется приложением Draw из Apache OpenOffice для хранения элементов чертежа в виде векторного изображения.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/image/fodg).


### SVG {#SVG}
```
public static final FileType SVG
```


Представляет Scalable Vector Graphics File (.svg), который является файлом Scalable Vector Graphics и использует текстовый формат на основе XML для описания внешнего вида изображения.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/page-description-language/svg).


### SVGZ {#SVGZ}
```
public static final FileType SVGZ
```


Представляет Compressed Scalable Vector Graphics File (.svgz), который является файлом Scalable Vector Graphics, использующим текстовый формат на основе XML, сжатый с помощью GZIP, для описания внешнего вида изображения.
Узнайте больше об этом формате файла [здесь](../https://fileinfo.com/extension/svgz).


### OTG {#OTG}
```
public static final FileType OTG
```


Представляет OpenDocument Graphic Template (.otg).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/image/otg).


### HTM {#HTM}
```
public static final FileType HTM
```


Представляет Hypertext Markup Language File (.htm), который является расширением веб‑страниц, созданных для отображения в браузерах.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/web/html).


### HTML {#HTML}
```
public static final FileType HTML
```


Представляет Hypertext Markup Language File (.html), который является расширением веб‑страниц, созданных для отображения в браузерах.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/web/html).


### MHT {#MHT}
```
public static final FileType MHT
```


Представляет MHTML Web Archive (.mht).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/web/mht).


### NSF {#NSF}
```
public static final FileType NSF
```


Представляет Lotus Notes Database (.nsf).
Узнайте больше об этом формате файла [здесь](../https://fileinfo.com/extension/nsf).


### MBOX {#MBOX}
```
public static final FileType MBOX
```


Представляет Email Mailbox File (.mbox).
Узнайте больше об этом формате файла [здесь](../https://fileinfo.com/extension/mbox).


### MHTML {#MHTML}
```
public static final FileType MHTML
```


Представляет MIME HTML File (.mhtml).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/web/mhtml).


### XML {#XML}
```
public static final FileType XML
```


Представляет XML File (.xml).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/web/xml).


### ONE {#ONE}
```
public static final FileType ONE
```


Представляет документ OneNote (.one), созданный приложением Microsoft OneNote. OneNote позволяет собирать информацию, используя приложение, как если бы вы использовали черновик для записи заметок.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/note-taking/one).


### PDF {#PDF}
```
public static final FileType PDF
```


Представляет файл формата Portable Document Format (.pdf), который является типом документа, созданного Adobe еще в 1990-х годах. Цель этого формата файлов — ввести стандарт представления документов и другого справочного материала в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционных систем.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/view/pdf).


### XPS {#XPS}
```
public static final FileType XPS
```


Представляет файл спецификации XML Paper (.xps), который представляет файлы разметки страниц на основе спецификаций XML Paper, созданных Microsoft. Этот формат был разработан Microsoft как замена формата EMF и похож на формат PDF, но использует XML для описания разметки, внешнего вида и информации о печати документа.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/page-description-language/xps).


### OXPS {#OXPS}
```
public static final FileType OXPS
```


Представляет OpenXPS File (.oxps).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/page-description-language/oxps).


### TEX {#TEX}
```
public static final FileType TEX
```


Представляет исходный документ LaTeX (.tex), который является языком, включающим программирование, а также возможности разметки, используемые для наборa документов.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/page-description-language/tex).


### OFD {#OFD}
```
public static final FileType OFD
```


Формат Open Fixed-layout Document (OFD), определённый стандартом GB/T 33190-2016, направлен на замену PDF в китайских государственных учреждениях.


### PPT {#PPT}
```
public static final FileType PPT
```


Представляет презентацию PowerPoint (.ppt), которая представляет файл PowerPoint, состоящий из набора слайдов для отображения в виде слайд-шоу. Он определяет бинарный формат файла, используемый Microsoft PowerPoint 97-2003.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/presentation/ppt).


### PPTX {#PPTX}
```
public static final FileType PPTX
```


Представляет презентацию PowerPoint Open XML (.pptx), которая представляет файлы презентаций, созданные популярным приложением Microsoft PowerPoint. В отличие от предыдущей версии формата файлов презентаций PPT, который был бинарным, формат PPTX основан на формате презентаций Microsoft PowerPoint Open XML.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/presentation/pptx).


### PPS {#PPS}
```
public static final FileType PPS
```


Представляет слайд-шоу PowerPoint (.pps), которое создаётся с помощью Microsoft PowerPoint для целей слайд-шоу. Чтение и создание файлов PPS поддерживается Microsoft PowerPoint 97-2003.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/presentation/pps).


### PPSX {#PPSX}
```
public static final FileType PPSX
```


Представляет файлы слайд-шоу PowerPoint Open XML (.ppsx), которые создаются с использованием Microsoft PowerPoint 2007 и более новых версий для целей слайд-шоу.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/presentation/ppsx).


### ODP {#ODP}
```
public static final FileType ODP
```


Представляет презентацию OpenDocument (.odp), которая представляет формат файла презентации, используемый OpenOffice.org в стандарте OASIS Open.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/presentation/odp).


### FODP {#FODP}
```
public static final FileType FODP
```


Представляет презентацию OpenDocument (.fodp), которая представляет OpenDocument Flat XML Presentation.
Узнайте больше об этом формате файла [здесь](../https://fileinfo.com/extension/fodp).


### POT {#POT}
```
public static final FileType POT
```


Представляет шаблон PowerPoint (.pot), который представляет файлы шаблонов Microsoft PowerPoint, созданные в версиях PowerPoint 97–2003.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/presentation/pot).


### PPTM {#PPTM}
```
public static final FileType PPTM
```


Представляет презентацию PowerPoint Open XML с поддержкой макросов (.pptm), которая является файлом презентации с включёнными макросами, созданным в Microsoft PowerPoint 2007 или более новых версиях.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/presentation/pptm).


### POTX {#POTX}
```
public static final FileType POTX
```


Представляет шаблон презентации PowerPoint Open XML (.potx), который представляет шаблоны презентаций Microsoft PowerPoint, созданные в Microsoft PowerPoint 2007 и более новых версиях.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/presentation/potx).


### POTM {#POTM}
```
public static final FileType POTM
```


Представляет шаблон презентации PowerPoint Open XML с поддержкой макросов (.potm), который является файлом шаблона Microsoft PowerPoint с поддержкой макросов. Файлы POTM создаются в PowerPoint 2007 и более новых версиях и содержат настройки по умолчанию, которые можно использовать для создания последующих файлов презентаций.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/presentation/potm).


### PPSM {#PPSM}
```
public static final FileType PPSM
```


Представляет слайд PowerPoint Open XML с поддержкой макросов (.ppsm), который представляет формат файла слайд-шоу с включёнными макросами, созданный в Microsoft PowerPoint 2007 или более новых версиях.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/presentation/ppsm).


### OTP {#OTP}
```
public static final FileType OTP
```


Представляет шаблон презентации OpenDocument (.otp), который представляет файлы шаблонов презентаций, созданные приложениями в формате стандарта OASIS OpenDocument.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/presentation/otp).


### XLS {#XLS}
```
public static final FileType XLS
```


Представляет электронную таблицу Excel (.xls), которая использует двоичный формат файлов Excel. Такие файлы могут быть созданы Microsoft Excel, а также другими аналогичными программами для работы с таблицами, такими как OpenOffice Calc или Apple Numbers.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/xls).


### EXCEL_2003_XML {#EXCEL-2003-XML}
```
public static final FileType EXCEL_2003_XML
```


Представляет XML Excel 2003 (SpreadsheetML) (.xml), который представляет двоичный формат файлов Excel. Такие файлы могут быть созданы Microsoft Excel, а также другими аналогичными программами для работы с таблицами, такими как OpenOffice Calc или Apple Numbers.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/xls).


### NUMBERS {#NUMBERS}
```
public static final FileType NUMBERS
```


Представляет Apple Numbers (.numbers), который использует двоичный формат файлов, похожий на Excel. Такие файлы могут быть созданы приложением Apple Numbers.
Узнайте больше о этом формате файла [здесь](../https://fileinfo.com/extension/numbers).


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Представляет электронную таблицу Microsoft Excel Open XML (.xlsx), которая является широко известным форматом документов Microsoft Excel, представленного Microsoft в выпуске Microsoft Office 2007.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/xlsx).


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Представляет электронную таблицу Excel Open XML с поддержкой макросов (.xlsm), которая является типом файла таблицы, поддерживающего макросы.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/xlsm).


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Представляет двоичную электронную таблицу Excel (.xlsb), который определяет двоичный формат файлов Excel. Это набор записей и структур, определяющих содержимое книги Excel.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/xlsb).


### CSV {#CSV}
```
public static final FileType CSV
```


Представляет файл значений, разделённых запятыми (.csv), который представляет текстовые файлы, содержащие записи данных со значениями, разделёнными запятыми.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/csv).


### TSV {#TSV}
```
public static final FileType TSV
```


Представляет файл значений, разделённых табуляцией (.tsv), который представляет данные, разделённые табуляцией, в текстовом формате.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/tsv).


### ODS {#ODS}
```
public static final FileType ODS
```


Представляет электронную таблицу OpenDocument (.ods), что означает формат документа электронных таблиц OpenDocument, редактируемый пользователем. Данные хранятся в ODF‑файлах в виде строк и столбцов.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/ods).


### FODS {#FODS}
```
public static final FileType FODS
```


Представляет электронную таблицу OpenDocument Flat XML (.fods).
Это формат документа электронных таблиц, основанный на XML, используемый в OpenOffice и LibreOffice.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/fods).


### OTS {#OTS}
```
public static final FileType OTS
```


Представляет шаблон электронной таблицы OpenDocument (.ots).
Это формат шаблона документа, используемый в OpenOffice и LibreOffice для электронных таблиц.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/ots).


### XLAM {#XLAM}
```
public static final FileType XLAM
```


Представляет надстройку Microsoft Excel (.xlam).
Это формат файла, используемый Microsoft Excel для создания надстроек с пользовательской функциональностью.
Узнайте больше о этом формате файла [здесь](../https://fileinfo.com/extension/xlam).


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Представляет шаблон Microsoft Excel с поддержкой макросов (.xltm), который представляет файлы, генерируемые Microsoft Excel как шаблоны с поддержкой макросов. Файлы XLTM похожи на XLTX по структуре, за исключением того, что последние не поддерживают создание шаблонов с макросами.
Узнайте больше о этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/xltm).


### XLT {#XLT}
```
public static final FileType XLT
```


Представляет шаблон Microsoft Excel (.xlt), который является файлом шаблона, созданным с помощью Microsoft Excel, приложения для работы с электронными таблицами, входящего в состав пакета Microsoft Office. Microsoft Office 97‑2003 поддерживал создание новых файлов XLT, а также их открытие.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/xlt).


### XLTX {#XLTX}
```
public static final FileType XLTX
```


Представляет шаблон электронной таблицы Excel Open XML (.xltx), который представляет шаблоны Microsoft Excel, основанные на спецификациях формата файлов Office OpenXML. Он используется для создания стандартного файла шаблона, который может быть использован для генерации файлов XLSX с теми же настройками, указанными в файле XLTX.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/xltx).


### SXC {#SXC}
```
public static final FileType SXC
```


Представляет электронную таблицу StarOffice Calc (.sxc).
Это документ электронной таблицы, созданный с помощью StarOffice Calc, программы для работы с электронными таблицами.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/spreadsheet/sxc).


### MPP {#MPP}
```
public static final FileType MPP
```


Представляет файл Microsoft Project (.mpp), который является файлом данных Microsoft Project и хранит информацию, связанную с управлением проектами, в интегрированном виде.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/project-management/mpp).


### MPT {#MPT}
```
public static final FileType MPT
```


Представляет шаблон Microsoft Project (.mpt), который содержит базовую информацию и структуру, а также настройки документа для создания файлов .MPP.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/project-management/mpt).


### MPX {#MPX}
```
public static final FileType MPX
```


Представляет файл обмена Microsoft Project (.mpx), который является форматом ASCII для передачи информации о проектах между Microsoft Project (MSP) и другими приложениями, поддерживающими формат MPX, такими как Primavera Project Planner, Sciforma и Timerline Precision Estimating.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/project-management/mpx).


### AS {#AS}
```
public static final FileType AS
```


Представляет файл ActionScript (.as).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/programming/as).


### AS_3 {#AS-3}
```
public static final FileType AS_3
```


Представляет файл ActionScript (.as3).
Узнайте больше об этом формате файла [здесь](../https://datatypes.net/open-as3-files).


### ASM {#ASM}
```
public static final FileType ASM
```


Представляет файл исходного кода на ассемблере (.asm).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/cad/asm).


### BAT {#BAT}
```
public static final FileType BAT
```


Представляет пакетный файл DOS (.bat).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/executable/bat).


### C {#C}
```
public static final FileType C
```


Представляет файл исходного кода C/C++ (.c).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/programming/c).


### CC {#CC}
```
public static final FileType CC
```


Представляет файл исходного кода C++ (.cc).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/programming/cc).


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Представляет файл CMake (.cmake).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/programming/cmake).


### CPP {#CPP}
```
public static final FileType CPP
```


Представляет файл исходного кода C++ (.cpp).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/programming/cpp).


### CS {#CS}
```
public static final FileType CS
```


Представляет файл исходного кода C# (.cs), который является файлом исходного кода для языка программирования C#. Он был представлен компанией Microsoft для использования с .NET Framework.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/programming/cs).


### VB {#VB}
```
public static final FileType VB
```


Представляет файл элемента проекта Visual Basic (.vb), который является файлом исходного кода, созданным на языке Visual Basic. Он был создан компанией Microsoft для разработки приложений .NET.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/programming/vb).


### CSS {#CSS}
```
public static final FileType CSS
```


Представляет файл каскадных таблиц стилей (.css).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/web/css).


### CXX {#CXX}
```
public static final FileType CXX
```


Представляет файл исходного кода C++ (.cxx).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/programming/cxx).


### DIFF {#DIFF}
```
public static final FileType DIFF
```


Представляет файл патча (.diff).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/programming/diff).


### ERB {#ERB}
```
public static final FileType ERB
```


Представляет скрипт Ruby ERB (.erb).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/programming/erb).


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Представляет файл исходного кода Groovy (.groovy).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/programming/groovy).


### H {#H}
```
public static final FileType H
```


Представляет заголовочный файл C/C++/Objective-C (.h).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/programming/h).


### HAML {#HAML}
```
public static final FileType HAML
```


Представляет файл исходного кода Haml (.haml).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/programming/haml).


### HH {#HH}
```
public static final FileType HH
```


Представляет файл заголовка C++ (.hh).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/programming/hh).


### JAVA {#JAVA}
```
public static final FileType JAVA
```


Представляет файл исходного кода Java (.java).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/programming/java).


### JS {#JS}
```
public static final FileType JS
```


Представляет файл JavaScript (.js).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/web/js).


### JSON {#JSON}
```
public static final FileType JSON
```


Представляет файл JavaScript Object Notation (.json).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/web/json).


### LESS {#LESS}
```
public static final FileType LESS
```


Представляет файл таблицы стилей LESS (.less).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/web/less).


### LOG {#LOG}
```
public static final FileType LOG
```


Представляет файл журнала (.log).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/database/log).


### M {#M}
```
public static final FileType M
```


Представляет файл реализации Objective-C (.m).
Узнайте больше об этом формате файла [здесь](../https://fileinfo.com/extension/m).


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Представляет скрипт Xcode Makefile (.make).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/programming/make).


### MD {#MD}
```
public static final FileType MD
```


Представляет файл документации Markdown (.md).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/word-processing/md).


### ML {#ML}
```
public static final FileType ML
```


Представляет файл исходного кода ML (.ml).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/programming/ml).


### MM {#MM}
```
public static final FileType MM
```


Представляет файл исходного кода Objective-C++ (.mm).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/programming/mm).


### PHP {#PHP}
```
public static final FileType PHP
```


Представляет файл исходного кода PHP (.php).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/programming/php).


### PL {#PL}
```
public static final FileType PL
```


Представляет скрипт Perl (.pl).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/programming/pl).


### PROPERTIES {#PROPERTIES}
```
public static final FileType PROPERTIES
```


Представляет файл свойств Java (.properties).
Узнайте больше об этом формате файла [здесь](../https://fileinfo.com/extension/properties).


### PY {#PY}
```
public static final FileType PY
```


Представляет скрипт Python (.py).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/programming/py).


### RB {#RB}
```
public static final FileType RB
```


Представляет файл исходного кода Ruby (.rb).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/programming/rb).


### RST {#RST}
```
public static final FileType RST
```


Представляет файл reStructuredText (.rst).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/programming/rst).


### SASS {#SASS}
```
public static final FileType SASS
```


Представляет файл Syntactically Awesome StyleSheets (.sass).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/web/sass).


### SCALA {#SCALA}
```
public static final FileType SCALA
```


Представляет файл исходного кода Scala (.scala).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/programming/scala).


### SCM {#SCM}
```
public static final FileType SCM
```


Представляет файл исходного кода Scheme (.scm).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/programming/scm).


### SCRIPT {#SCRIPT}
```
public static final FileType SCRIPT
```


Представляет файл универсального скрипта (.script).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/programming/script).


### SH {#SH}
```
public static final FileType SH
```


Представляет скрипт оболочки Bash (.sh).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/cs/programming/sh).


### SML {#SML}
```
public static final FileType SML
```


Представляет файл исходного кода Standard ML (.sml).
Узнайте больше об этом формате файла [здесь](../https://fileinfo.com/extension/sml).


### SQL {#SQL}
```
public static final FileType SQL
```


Представляет файл данных Structured Query Language (.sql).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/database/sql).


### VIM {#VIM}
```
public static final FileType VIM
```


Представляет файл настроек Vim (.vim).
Узнайте больше об этом формате файла [здесь](../https://fileinfo.com/extension/vim).


### YAML {#YAML}
```
public static final FileType YAML
```


Представляет документ YAML (.yaml).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/programming/yaml).


### DOC {#DOC}
```
public static final FileType DOC
```


Представляет файл документа Microsoft Word (.doc).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/word-processing/doc).


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Представляет файл документа Microsoft Word Open XML (.docx).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/word-processing/docx).


### CHM {#CHM}
```
public static final FileType CHM
```


Представляет файл справки Microsoft Compiled HTML Help (.chm).
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/web/chm).


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Представляет файл документа Word Open XML с поддержкой макросов (.docm).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/word-processing/docm).


### DOT {#DOT}
```
public static final FileType DOT
```


Представляет файл шаблона документа Word (.dot).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/word-processing/dot).


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Представляет файл шаблона документа Word Open XML (.dotx).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/word-processing/dotx).


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Представляет файл шаблона документа Word Open XML с поддержкой макросов (.dotm).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/word-processing/dotm).


### RTF {#RTF}
```
public static final FileType RTF
```


Представляет файл Rich Text Format (.rtf).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/word-processing/rtf).


### TXT {#TXT}
```
public static final FileType TXT
```


Представляет файл простого текста (.txt).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/word-processing/txt).


### ODT {#ODT}
```
public static final FileType ODT
```


Представляет документ OpenDocument Text (.odt).
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/word-processing/odt).


### OTT {#OTT}
```
public static final FileType OTT
```


Представляет шаблон документа OpenDocument (.ott).
Это шаблонный документ, созданный в соответствии со стандартным форматом OpenDocument от OASIS.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/word-processing/ott).


### VCF {#VCF}
```
public static final FileType VCF
```


Представляет файл vCard (.vcf), который является цифровым форматом для хранения контактной информации.
Он широко используется для обмена данными между популярными приложениями для обмена информацией.
Узнайте больше об этом формате файла [здесь](../https://wiki.fileformat.com/email/vcf).


### AI {#AI}
```
public static final FileType AI
```


Представляет файл Adobe Illustrator (.ai), который является форматом файлов для рисунков Adobe Illustrator.
Узнайте больше об этом формате файла [здесь](../https://docs.fileformat.com/image/ai).


### PSM1 {#PSM1}
```
public static final FileType PSM1
```


Представляет файл модуля скрипта PowerShell (.psm1).
Это формат файла для скриптов модулей PowerShell.
Узнайте больше об этом формате файла [здесь](../https://fileinfo.com/extension/psm1).


### PS1 {#PS1}
```
public static final FileType PS1
```


Представляет файл скрипта PowerShell (.ps1).
Это формат файла для файлов Cmdlet Windows PowerShell.
Узнайте больше об этом формате файла [здесь](../https://fileinfo.com/extension/ps1).


### PSD1 {#PSD1}
```
public static final FileType PSD1
```


Представляет файл манифеста модуля скрипта PowerShell (.psd1).
Это формат файла для скриптов манифеста модуля PowerShell.
Узнайте больше об этом формате файла [здесь](../https://fileinfo.com/extension/psd1).


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


Этот метод принимает расширение файла, с точкой или без неё ".", и возвращает соответствующий тип файла, если он поддерживается.
Если тип файла не поддерживается, он возвращает тип файла по умолчанию [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | расширение | java.lang.String | Расширение файла с точкой или без неё ".". |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromFilePath(String filePath) {#fromFilePath-java.lang.String-}
```
public static FileType fromFilePath(String filePath)
```


Извлекает расширение файла из имени файла или пути к файлу и сопоставляет его с типом файла.


Если тип файла поддерживается, метод возвращает соответствующий
FileType
,
в противном случае он возвращает тип файла по умолчанию [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Имя файла или путь к файлу. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromMediaType(String mediaType) {#fromMediaType-java.lang.String-}
```
public static FileType fromMediaType(String mediaType)
```


Отображает тип медиа файла на тип файла. Например, 'application/pdf' будет сопоставлен с [PDF](../../com.groupdocs.viewer/filetype#PDF).


Этот метод принимает тип медиа файла в качестве входных данных и сопоставляет его с соответствующим
FileType
. Если тип медиа
поддерживается, метод возвращает соответствующий тип файла. Если тип медиа не поддерживается, он возвращает тип файла по умолчанию
[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | mediaType | java.lang.String | Тип медиа файла, например, 'application/pdf'. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if found, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream stream)
```


Определяет тип файла, читая сигнатуру файла.


Этот метод принимает поток ввода, представляющий файл, и пытается определить его тип, анализируя сигнатуру файла. Сигнатура
сигнатура — уникальная последовательность байтов в начале файла, указывающая его тип. Метод
читает сигнатуру файла из потока ввода и сравнивает её с известными сигнатурами поддерживаемых типов файлов.
Если совпадение найдено, метод возвращает соответствующий тип файла. Если совпадение не найдено, он возвращает тип файла по умолчанию
[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | stream | java.io.InputStream | Поток ввода, представляющий файл. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, String password) {#fromStream-java.io.InputStream-java.lang.String-}
```
public static FileType fromStream(InputStream stream, String password)
```


Определяет тип файла, читая сигнатуру файла.


Этот метод анализирует сигнатуру файла, которая представляет собой уникальную последовательность байтов в начале файла, чтобы определить
тип файла. Он читает сигнатуру файла из предоставленного потока ввода и сравнивает её с известными сигнатурами
поддерживаемых типов файлов. Если совпадение найдено, метод возвращает соответствующий тип файла. Если совпадение не найдено, он
возвращает тип файла по умолчанию [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN).


Если файл зашифрован и требует пароль для открытия, пароль должен быть передан в качестве параметра к этому
методу. Пароль будет использоваться для расшифровки файла и анализа его подписи с целью определения типа файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | stream | java.io.InputStream | Поток ввода, представляющий файл. |
|
|  | пароль | java.lang.String | Пароль для открытия файла. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, ILogger logger) {#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, ILogger logger)
```


Определяет тип файла, читая сигнатуру файла.


Этот метод анализирует сигнатуру файла, которая представляет собой уникальную последовательность байтов в начале файла, чтобы определить
тип файла. Он читает сигнатуру файла из предоставленного потока ввода и сравнивает её с известными сигнатурами
поддерживаемых типов файлов. Если совпадение найдено, метод возвращает соответствующий тип файла. Если совпадение не найдено, он
возвращает тип файла по умолчанию [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN).


Можно предоставить логгер для записи любой релевантной информации или ошибок во время процесса определения типа файла. Логгер
должен реализовать интерфейс ILogger. Если логгер не предоставлен, процесс определения не будет генерировать никакой
вывод журнала.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | stream | java.io.InputStream | Поток ввода, представляющий файл. |
|
|  | логгер | com.groupdocs.foundation.logging.ILogger | Логгер для записи информации или ошибок. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, String password, ILogger logger) {#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, String password, ILogger logger)
```


Определяет тип файла, читая сигнатуру файла.


Этот метод анализирует сигнатуру файла, которая представляет собой уникальную последовательность байтов в начале файла, чтобы определить
тип файла. Он читает сигнатуру файла из предоставленного потока ввода и сравнивает её с известными сигнатурами
поддерживаемых типов файлов. Если совпадение найдено, метод возвращает соответствующий тип файла. Если совпадение не найдено, он
возвращает тип файла по умолчанию [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN).


Пароль может быть предоставлен, если файл зашифрован или защищён. Пароль будет использоваться для открытия файла перед
анализом подписи файла. Если файл не требует пароля, этот параметр можно установить в null.


Можно предоставить логгер для записи любой релевантной информации или ошибок во время процесса определения типа файла. Логгер
должен реализовать интерфейс ILogger. Если логгер не предоставлен, процесс определения не будет генерировать никакой
вывод журнала.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | stream | java.io.InputStream | Поток ввода, представляющий файл. |
|
|  | пароль | java.lang.String | Пароль для открытия файла. |
|
|  | логгер | com.groupdocs.foundation.logging.ILogger | Логгер для записи информации или ошибок. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Получает поддерживаемые типы файлов.


Этот метод возвращает последовательность всех поддерживаемых системой типов файлов. Типы файлов представляют различные
форматы документов, которые могут быть обработаны или распознаны системой.
***Learn more**
* Learn more about the supported document formats: [Full list of supported file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/)*


**Returns:**
java.util.List<com.groupdocs.viewer.FileType> - последовательность поддерживаемых типов файлов.

### detectCharset(String filePath) {#detectCharset-java.lang.String-}
```
public static Charset detectCharset(String filePath)
```


Пытается определить кодировку текстовых файлов [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV) и [CSV](../../com.groupdocs.viewer/filetype#CSV) по пути.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | filePath | java.lang.String | Имя файла или путь к файлу. |
|

**Returns:**
java.nio.charset.Charset - кодировка или null, если не удалось определить кодировку файла.

**Example:**


Charset charset = FileType.detectCharset(\"message.txt\");
     

### detectCharset(InputStream stream) {#detectCharset-java.io.InputStream-}
```
public static Charset detectCharset(InputStream stream)
```


Пытается определить кодировку текстовых файлов [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV) и [CSV](../../com.groupdocs.viewer/filetype#CSV) по потоку.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | stream | java.io.InputStream | Поток файла. |
|

**Returns:**
java.nio.charset.Charset - кодировка или null, если не удалось определить кодировку файла.

**Example:**


InputStream stream = new FileInputStream(\"message.txt\");
Charset charset = FileType.detectCharset(stream);
     

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Получает название формата файла, например, "Microsoft Word Document".


**Returns:**
java.lang.String - название формата файла.

### getExtension() {#getExtension--}
```
public final String getExtension()
```


Получает суффикс расширения файла (включая точку "."), например, ".doc".


**Returns:**
java.lang.String - суффикс расширения файла.

### toString() {#toString--}
```
public String toString()
```


Возвращает строковое представление текущего объекта.


**Returns:**
java.lang.String - строковое представление текущего объекта.

