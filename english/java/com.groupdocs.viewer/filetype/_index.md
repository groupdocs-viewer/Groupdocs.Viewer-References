---
title: FileType
second_title: GroupDocs.Viewer for Java API Reference
description: Represents file type.
type: docs
weight: 14
url: /java/com.groupdocs.viewer/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, com.groupdocs.viewer.caching.Cacheable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>, Cacheable
```

Represents file type. Provides methods to obtain list of all file types supported by **GroupDocs.Viewer**.
## Fields

| Field | Description |
| --- | --- |
| [UNKNOWN](#UNKNOWN) | Represents unknown file type. |
| [ZIP](#ZIP) | Zipped File (.zip) represents archives that can hold one or more files or directories. |
| [TAR](#TAR) | Consolidated Unix File Archive (.tar) are archives created with Unix-based utility for collecting one or more files. |
| [XZ](#XZ) | XZ file (.xz) is archive compressed a high-ratio compression algorithm based on the LZMA algorithm. |
| [TXZ](#TXZ) | Consolidated Unix File Archive (.txz, .tar.xz) are archives created with Unix-based utility for collecting one or more files. |
| [TARXZ](#TARXZ) | Consolidated Unix File Archive (.txz, .tar.xz) are archives created with Unix-based utility for collecting one or more files. |
| [TGZ](#TGZ) | Consolidated Unix File Archive (.tgz, .tar.gz) are archives created with Unix-based utility for collecting one or more files. |
| [TARGZ](#TARGZ) | Consolidated Unix File Archive (.tgz, .tar.gz) are archives created with Unix-based utility for collecting one or more files. |
| [BZ_2](#BZ-2) | Bzip2 Compressed File (.bz2) are compressed files generated using the BZIP2 open source compression method, mostly on UNIX or Linux system. |
| [RAR](#RAR) | Roshal ARchive (.rar) are compressed files generated using the RAR (WINRAR version 4) compression method. |
| [GZ](#GZ) | Gnu Zipped File (.gz) are compressed files created with gzip compression application. |
| [GZIP](#GZIP) | Gnu Zipped File (.gzip) was introduced as a free utility for replacing the Compress program used in Unix systems. |
| [SEVEN_ZIP](#SEVEN-ZIP) | 7Zip (.7z, .7zip) is free open source archiver with LZMA and LZMA2 compression. |
| [DXF](#DXF) | Drawing Exchange Format File (.dxf) is a tagged data representation of AutoCAD drawing file. |
| [DWG](#DWG) | AutoCAD Drawing Database File (.dwg) represents proprietary binary files used for containing 2D and 3D design data. |
| [DWT](#DWT) | AutoCAD Drawing Template (.dwt) is an AutoCAD drawing template file that is used as starter for creating drawings that can be saved as DWG files. |
| [STL](#STL) | Stereolithography File (.stl) is an interchangeable file format that represents 3-dimensional surface geometry. |
| [IFC](#IFC) | Industry Foundation Classes File (.ifc) is a file format that establishes international standards to import and export building objects and their properties. |
| [DWF](#DWF) | Design Web Format File (.dwf) represents 2D/3D drawing in compressed format for viewing, reviewing or printing design files. |
| [FBX](#FBX) | Autodesk FBX Interchange File (FilmBoX) (.fbx) represents 3D model format. |
| [DWFX](#DWFX) | Design Web Format File XPS (.dwfx) represents 2D/3D drawing as XPS document in compressed format for viewing, reviewing or printing design files. |
| [DGN](#DGN) | MicroStation Design File (.dgn) are drawings created by and supported by CAD applications such as MicroStation and Intergraph Interactive Graphics Design System. |
| [PLT](#PLT) | PLT (HPGL) (.plt) is a vector-based plotter file introduced by Autodesk, Inc. |
| [CF2](#CF2) | Common File Format File. |
| [OBJ](#OBJ) | Wavefront 3D Object File (.obj) is 3D image file introduced by Wavefront Technologies. |
| [HPG](#HPG) | PLT (HPGL) (.hpg). |
| [IGS](#IGS) | Initial Graphics Exchange Specification (IGES) (.igs). |
| [VSD](#VSD) | Visio Drawing File (.vsd) are drawings created with Microsoft Visio application to represent variety of graphical objects and the interconnection between these. |
| [VSDX](#VSDX) | Visio Drawing (.vsdx) represents Microsoft Visio file format introduced from Microsoft Office 2013 onwards. |
| [VSS](#VSS) | Visio Stencil File(.vss) are stencil files created with Microsoft Visio 2007 and earlier. |
| [VSSX](#VSSX) | Visio Stencil File (.vssx) are drawing stencils created with Microsoft Visio 2013 and above. |
| [VSDM](#VSDM) | Visio Macro-Enabled Drawing (.vsdm) are drawing files created with Microsoft Visio application that supports macros. |
| [VST](#VST) | Visio Drawing Template (.vst) are vector image files created with Microsoft Visio and act as template for creating further files. |
| [VSTX](#VSTX) | Visio Drawing Template (.vstx) are drawing template files created with Microsoft Visio 2013 and above. |
| [VSTM](#VSTM) | Visio Macro-Enabled Drawing Template (.vstm) are template files created with Microsoft Visio that support macros. |
| [VSSM](#VSSM) | Visio Macro-Enabled Stencil File (.vssm) are Microsoft Visio Stencil files that support provide support for macros. |
| [VSX](#VSX) | Visio Stencil XML File (.vsx) refers to stencils that consist of drawings and shapes that are used for creating diagrams in Microsoft Visio. |
| [VTX](#VTX) | Visio Template XML File (.vtx) is a Microsoft Visio drawing template that is saved to disc in XML file format. |
| [VDW](#VDW) | Visio Web Drawing (.vdw) represents file format that specifies the streams and storages required for rendering a Web drawing. |
| [VDX](#VDX) | Visio Drawing XML File (.vdx) represents any drawing or chart created in Microsoft Visio, but saved in XML format have .VDX extension. |
| [EPUB](#EPUB) | Open eBook File (.epub) is an e-book file format that provide a standard digital publication format for publishers and consumers. |
| [MOBI](#MOBI) | Mobipocket eBook (.mobi) is one of the most widely used ebook file format. |
| [MSG](#MSG) | Outlook Mail Message (.msg) is a file format used by Microsoft Outlook and Exchange to store email messages, contact, appointment, or other tasks. |
| [EML](#EML) | E-Mail Message (.eml) represents email messages saved using Outlook and other relevant applications. |
| [EMLX](#EMLX) | Apple Mail Message (.emlx) is implemented and developed by Apple. |
| [PST](#PST) | Outlook Personal Information Store File (.pst) represents Outlook Personal Storage Files (also called Personal Storage Table) that store variety of user information. |
| [OST](#OST) | Outlook Offline Data File (.ost) represents user's mailbox data in offline mode on local machine upon registration with Exchange Server using Microsoft Outlook. |
| [TIF](#TIF) | Tagged Image File (.tif) represents raster images that are meant for usage on a variety of devices that comply with this file format standard. |
| [TIFF](#TIFF) | Tagged Image File Format (.tiff) represents raster images that are meant for usage on a variety of devices that comply with this file format standard. |
| [JPG](#JPG) | JPEG Image (.jpg) is a type of image format that is saved using the method of lossy compression. |
| [JPEG](#JPEG) | JPEG Image (.jpeg) is a type of image format that is saved using the method of lossy compression. |
| [PNG](#PNG) | Portable Network Graphic (.png) is a type of raster image file format that use loseless compression. |
| [GIF](#GIF) | Graphical Interchange Format File (.gif) is a type of highly compressed image. |
| [APNG](#APNG) | Animated Portable Network Graphic (.apng) is extension of PNG format that support animation. |
| [BMP](#BMP) | Bitmap Image File (.bmp) is used to store bitmap digital images. |
| [ICO](#ICO) | Icon File (.ico) are image file types used as icon for representation of an application on Microsoft Windows. |
| [TGA](#TGA) | Truevision TGA (Truevision Advanced Raster Adapter - TARGA) is used to store bitmap digital images developed by TRUEVISION. |
| [JP_2](#JP-2) | JPEG 2000 Core Image File (.jp2) is an image coding system and state-of-the-art image compression standard. |
| [JPF](#JPF) | JPEG 2000 Image File (.jpf) |
| [JPX](#JPX) | JPEG 2000 Image File (.jpx) |
| [JPM](#JPM) | JPEG 2000 Image File (.jpm) |
| [J2C](#J2C) | JPEG 2000 Code InputStream (.j2c) |
| [J2K](#J2K) | JPEG 2000 Code Stream (.j2k) is an image that is compressed using the wavelet compression instead of DCT compression. |
| [JPC](#JPC) | JPEG 2000 Code InputStream (.jpc) |
| [JLS](#JLS) | JPEG-LS (JLS) (.jls) |
| [DIB](#DIB) | Device Independent Bitmap File (.dib) |
| [WMF](#WMF) | Windows Metafile (.wmf) represents Microsoft Windows Metafile (WMF) for storing vector as well as bitmap-format images data. |
| [WMZ](#WMZ) | ompressed Windows Metafile (.wmz) represents Microsoft Windows Metafile (WMF) compressed in GZIP archvive - for storing vector as well as bitmap-format images data. |
| [EMF](#EMF) | Enhanced Windows Metafile (.emf) represents graphical images device-independently. |
| [EMZ](#EMZ) | Enhanced Windows Metafile compressed (.emz) represents graphical images device-independently compressed by GZIP. |
| [WEBP](#WEBP) | WebP Image (.webp) is a modern raster web image file format that is based on lossless and lossy compression. |
| [DNG](#DNG) | Digital Negative Specification (.dng) is a digital camera image format used for the storage of raw files. |
| [CDR](#CDR) | CorelDraw Vector Graphic Drawing (.cdr) is a vector drawing image file that is natively created with CorelDRAW for storing digital image encoded and compressed. |
| [CMX](#CMX) | Corel Exchange (.cmx) is a drawing image file that may contain vector graphics as well as bitmap graphics. |
| [DJVU](#DJVU) | DjVu Image (.djvu) is a graphics file format intended for scanned documents and books especially those which contain the combination of text, drawings, images and photographs. |
| [CGM](#CGM) | Computer Graphics Metafile (.cgm) is a free, platform-independent, international standard metafile format for storing and exchanging of vector graphics (2D), raster graphics, and text. |
| [PCL](#PCL) | Printer Command Language Document (.pcl) |
| [PSD](#PSD) | Adobe Photoshop Document (.psd) represents Adobe Photoshop's native file format used for graphics designing and development. |
| [PSB](#PSB) | Photoshop Large Document Format (.psb) represents Photoshop Large Document Format used for graphics designing and development. |
| [DCM](#DCM) | DICOM Image (.dcm) represents digital image which stores medical information of patients such as MRIs, CT scans and ultrasound images. |
| [PS](#PS) | PostScript File (.ps) |
| [EPS](#EPS) | Encapsulated PostScript File (.eps) describes an Encapsulated PostScript language program that describes the appearance of a single page. |
| [ODG](#ODG) | OpenDocument Graphic File (.odg) is used by Apache OpenOffice's Draw application to store drawing elements as a vector image. |
| [FODG](#FODG) | Flat XML ODF Template (.fodg) is used by Apache OpenOffice's Draw application to store drawing elements as a vector image. |
| [SVG](#SVG) | Scalable Vector Graphics File (.svg) is a Scalar Vector Graphics file that uses XML based text format for describing the appearance of an image. |
| [SVGZ](#SVGZ) | Scalable Vector Graphics File (.svgz) is a Scalar Vector Graphics file that uses XML based text format, compressed by GZIP for describing the appearance of an image. |
| [OTG](#OTG) | OpenDocument Graphic Template (.otg) |
| [HTM](#HTM) | Hypertext Markup Language File (.htm) is the extension for web pages created for display in browsers. |
| [HTML](#HTML) | Hypertext Markup Language File (.html) is the extension for web pages created for display in browsers. |
| [MHT](#MHT) | MHTML Web Archive (.mht) |
| [NSF](#NSF) | Lotus Notes Database (.nsf) Learn more about this file format https://fileinfo.com/extension/nsf |
| [MBOX](#MBOX) | Email Mailbox File (.mbox). |
| [MHTML](#MHTML) | MIME HTML File (.mhtml) |
| [XML](#XML) | XML File (.xml) |
| [ONE](#ONE) | OneNote Document (.one) is created by Microsoft OneNote application. |
| [PDF](#PDF) | Portable Document Format File (.pdf) is a type of document created by Adobe back in 1990s. |
| [XPS](#XPS) | XML Paper Specification File (.xps) represents page layout files that are based on XML Paper Specifications created by Microsoft. |
| [OXPS](#OXPS) | OpenXPS File (.oxps) |
| [TEX](#TEX) | LaTeX Source Document (.tex) is a language that comprises of programming as well as mark-up features, used to typeset documents. |
| [PPT](#PPT) | PowerPoint Presentation (.ppt) represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. |
| [PPTX](#PPTX) | PowerPoint Open XML Presentation (.pptx) are presentation files created with popular Microsoft PowerPoint application. |
| [PPS](#PPS) | PowerPoint Slide Show (.pps) are created using Microsoft PowerPoint for Slide Show purpose. |
| [PPSX](#PPSX) | PowerPoint Open XML Slide Show (.ppsx) files are created using Microsoft PowerPoint 2007 and above for Slide Show purpose. |
| [ODP](#ODP) | OpenDocument Presentation (.odp) represents presentation file format used by OpenOffice.org in the OASISOpen standard. |
| [FODP](#FODP) | OpenDocument Presentation (.fodp) represents OpenDocument Flat XML Presentation. |
| [POT](#POT) | PowerPoint Template (.pot) represents Microsoft PowerPoint template files created by PowerPoint 97-2003 versions. |
| [PPTM](#PPTM) | PowerPoint Open XML Macro-Enabled Presentation are Macro-enabled Presentation files that are created with Microsoft PowerPoint 2007 or higher versions. |
| [POTX](#POTX) | PowerPoint Open XML Presentation Template (.potx) represents Microsoft PowerPoint template presentations that are created with Microsoft PowerPoint 2007 and above. |
| [POTM](#POTM) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) are Microsoft PowerPoint template files with support for Macros. |
| [PPSM](#PPSM) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) represents Macro-enabled Slide Show file format created with Microsoft PowerPoint 2007 or higher. |
| [OTP](#OTP) | OpenDocument Presentation Template (.otp) represents presentation template files created by applications in OASIS OpenDocument standard format. |
| [XLS](#XLS) | Excel Spreadsheet (.xls) represents Excel Binary File Format. |
| [EXCEL_2003_XML](#EXCEL-2003-XML) | Excel 2003 XML (SpreadsheetML) represents Excel Binary File Format. |
| [NUMBERS](#NUMBERS) | Apple numbers represents Excel like Binary File Format. |
| [XLSX](#XLSX) | Microsoft Excel Open XML Spreadsheet (.xlsx) is a well-known format for Microsoft Excel documents that was introduced by Microsoft with the release of Microsoft Office 2007. |
| [XLSM](#XLSM) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) is a type of Spreasheet files that support macros. |
| [XLSB](#XLSB) | Excel Binary Spreadsheet (.xlsb) specifies the Excel Binary File Format, which is a collection of records and structures that specify Excel workbook content. |
| [CSV](#CSV) | Comma Separated Values File (.csv) represents plain text files that contain records of data with comma separated values. |
| [TSV](#TSV) | Tab Separated Values File (.tsv) represents data separated with tabs in plain text format. |
| [ODS](#ODS) | OpenDocument Spreadsheet (.ods) stands for OpenDocument Spreadsheet Document format that are editable by user. |
| [FODS](#FODS) | OpenDocument Flat XML Spreadsheet (.fods) |
| [OTS](#OTS) | OpenDocument Spreadsheet Template (.ots) |
| [XLAM](#XLAM) | Microsoft Excel Add-in (.xlam) |
| [XLTM](#XLTM) | Microsoft Excel Macro-Enabled Template (.xltm) represents files that are generated by Microsoft Excel as Macro-enabled template files. |
| [XLT](#XLT) | Microsoft Excel Template (.xlt) are template files created with Microsoft Excel which is a spreadsheet application which comes as part of Microsoft Office suite. |
| [XLTX](#XLTX) | Excel Open XML Spreadsheet Template (.xltx) represents Microsoft Excel Template that are based on the Office OpenXML file format specifications. |
| [SXC](#SXC) | StarOffice Calc Spreadsheet (.sxc) |
| [MPP](#MPP) | Microsoft Project File (.mpp) is Microsoft Project data file that stores information related to project management in an integrated manner. |
| [MPT](#MPT) | Microsoft Project Template (.mpt) contains basic information and structure along with document settings for creating .MPP files. |
| [MPX](#MPX) | Microsoft Project Exchange file (.mpx) is an ASCII file format for transferring of project information between Microsoft Project (MSP) and other applications that support the MPX file format such as Primavera Project Planner, Sciforma and Timerline Precision Estimating. |
| [AS](#AS) | ActionScript File (.as) |
| [AS_3](#AS-3) | ActionScript File (.as) |
| [ASM](#ASM) | Assembly Language Source Code File (.asm) |
| [BAT](#BAT) | DOS Batch File (.bat) |
| [C](#C) | C/C++ Source Code File (.c) |
| [CC](#CC) | C++ Source Code File (.cc) |
| [CMAKE](#CMAKE) | CMake File (.cmake) |
| [CPP](#CPP) | C++ Source Code File (.cpp) |
| [CS](#CS) | C\# Source Code File (.cs) is a source code file for C\# programming language. |
| [VB](#VB) | Visual Basic Project Item File (.vb) is a source code file created in Visual Basic language that was created by Microsoft for development of .NET applications. |
| [CSS](#CSS) | Cascading Style Sheet (.css) |
| [CXX](#CXX) | C++ Source Code File (.cxx) |
| [DIFF](#DIFF) | Patch File (.diff) |
| [ERB](#ERB) | Ruby ERB Script (.erb) |
| [GROOVY](#GROOVY) | Groovy Source Code File (.groovy) |
| [H](#H) | C/C++/Objective-C Header File (.h) |
| [HAML](#HAML) | Haml Source Code File (.haml) |
| [HH](#HH) | C++ Header File (.hh) |
| [JAVA](#JAVA) | Java Source Code File (.java) |
| [JS](#JS) | JavaScript File (.js) |
| [JSON](#JSON) | JavaScript Object Notation File (.json) |
| [LESS](#LESS) | LESS Style Sheet (.less) |
| [LOG](#LOG) | Log File (.log) |
| [M](#M) | Objective-C Implementation File (.m) |
| [MAKE](#MAKE) | Xcode Makefile Script (.make) |
| [MD](#MD) | Markdown Documentation File (.md) |
| [ML](#ML) | ML Source Code File (.ml) |
| [MM](#MM) | Objective-C++ Source File (.mm) |
| [PHP](#PHP) | PHP Source Code File (.php) |
| [PL](#PL) | Perl Script (.pl) |
| [PROPERTIES](#PROPERTIES) | Java Properties File (.properties) |
| [PY](#PY) | Python Script (.py) |
| [RB](#RB) | Ruby Source Code (.rb) |
| [RST](#RST) | reStructuredText File (.rst) |
| [SASS](#SASS) | Syntactically Awesome StyleSheets File (.sass) |
| [SCALA](#SCALA) | Scala Source Code File (.scala) |
| [SCM](#SCM) | Scheme Source Code File (.scm) |
| [SCRIPT](#SCRIPT) | Generic Script File (.script) |
| [SH](#SH) | Bash Shell Script (.sh) |
| [SML](#SML) | Standard ML Source Code File (.sml) |
| [SQL](#SQL) | Structured Query Language Data File (.sql) |
| [VIM](#VIM) | Vim Settings File (.vim) |
| [YAML](#YAML) | YAML Document (.yaml) |
| [DOC](#DOC) | Microsoft Word Document (.doc) represents documents generated by Microsoft Word or other word processing documents in binary file format. |
| [DOCX](#DOCX) | Microsoft Word Open XML Document (.docx) is a well-known format for Microsoft Word documents. |
| [CHM](#CHM) | Microsoft Compiled HTML Help File (.chm) is a well-known format for HELP (documentation to some application) documents. |
| [DOCM](#DOCM) | Word Open XML Macro-Enabled Document (.docm) is a Microsoft Word 2007 or higher generated documents with the ability to run macros. |
| [DOT](#DOT) | Word Document Template (.dot) are template files created by Microsoft Word to have pre-formatted settings for generation of further DOC or DOCX files. |
| [DOTX](#DOTX) | Word Open XML Document Template (.dotx) are template files created by Microsoft Word to have pre-formatted settings for generation of further DOCX files. |
| [DOTM](#DOTM) | Word Open XML Macro-Enabled Document Template (.dotm) represents template file created with Microsoft Word 2007 or higher. |
| [RTF](#RTF) | Rich Text Format File (.rtf) represents a method of encoding formatted text and graphics for use within applications. |
| [TXT](#TXT) | Plain Text File (.txt) represents a text document that contains plain text in the form of lines. |
| [ODT](#ODT) | OpenDocument Text Document (.odt) are type of documents created with word processing applications that are based on OpenDocument Text File format. |
| [OTT](#OTT) | OpenDocument Document Template (.ott) represents template documents generated by applications in compliance with the OASIS' OpenDocument standard format. |
| [VCF](#VCF) | vCard File (.vcf) is a digital file format for storing contact information. |
| [AI](#AI) | Adobe Illustrator (.ai) is a file format for Adobe Illustrator drawings. |
| [PSM1](#PSM1) | PowerShell script module (.psm1) a file format for PowerShell module scripts. |
| [PS1](#PS1) | PowerShell script file (.ps1) a file format for Windows PowerShell Cmdlet files. |
| [PSD1](#PSD1) | PowerShell script module manifest (.psd1) a file format for PowerShell module manifest scripts. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Maps file extension to file type. |
| [fromFilePath(String filePath)](#fromFilePath-java.lang.String-) | Extracts file extension and maps it to file type. |
| [fromMediaType(String mediaType)](#fromMediaType-java.lang.String-) | Maps file media type to file type e.g. 'application/pdf' will be mapped to [FileType](../../com.groupdocs.viewer/filetype).PDF. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Detects file type by reading the file signature. |
| [fromStream(InputStream stream, String password)](#fromStream-java.io.InputStream-java.lang.String-) | Detects file type by reading the file signature. |
| [fromStream(InputStream stream, ILogger logger)](#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-) | Detects file type by reading the file signature. |
| [fromStream(InputStream stream, String password, ILogger logger)](#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-) | Detects file type by reading the file signature. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | Retrieves supported file types |
| [getFileFormat()](#getFileFormat--) | File type name e.g. "Microsoft Word Document". |
| [getExtension()](#getExtension--) | Filename suffix (including the period ".") e.g. ".doc". |
| [toString()](#toString--) | Returns a String that represents the current object. |
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Represents unknown file type.

### ZIP {#ZIP}
```
public static final FileType ZIP
```


Zipped File (.zip) represents archives that can hold one or more files or directories. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/compression/zip

### TAR {#TAR}
```
public static final FileType TAR
```


Consolidated Unix File Archive (.tar) are archives created with Unix-based utility for collecting one or more files. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/compression/tar

### XZ {#XZ}
```
public static final FileType XZ
```


XZ file (.xz) is archive compressed a high-ratio compression algorithm based on the LZMA algorithm. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/xz

### TXZ {#TXZ}
```
public static final FileType TXZ
```


Consolidated Unix File Archive (.txz, .tar.xz) are archives created with Unix-based utility for collecting one or more files. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/txz

### TARXZ {#TARXZ}
```
public static final FileType TARXZ
```


Consolidated Unix File Archive (.txz, .tar.xz) are archives created with Unix-based utility for collecting one or more files. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/txz

### TGZ {#TGZ}
```
public static final FileType TGZ
```


Consolidated Unix File Archive (.tgz, .tar.gz) are archives created with Unix-based utility for collecting one or more files. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/tgz

### TARGZ {#TARGZ}
```
public static final FileType TARGZ
```


Consolidated Unix File Archive (.tgz, .tar.gz) are archives created with Unix-based utility for collecting one or more files. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/tgz

### BZ_2 {#BZ-2}
```
public static final FileType BZ_2
```


Bzip2 Compressed File (.bz2) are compressed files generated using the BZIP2 open source compression method, mostly on UNIX or Linux system. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/compression/bz2

### RAR {#RAR}
```
public static final FileType RAR
```


Roshal ARchive (.rar) are compressed files generated using the RAR (WINRAR version 4) compression method. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/compression/rar

### GZ {#GZ}
```
public static final FileType GZ
```


Gnu Zipped File (.gz) are compressed files created with gzip compression application. It can contain multiple compressed files and is commonly used on UNIX and Linux systems. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/compression/gz

### GZIP {#GZIP}
```
public static final FileType GZIP
```


Gnu Zipped File (.gzip) was introduced as a free utility for replacing the Compress program used in Unix systems. Such files can be opened and extracted with a several applications such as WinZip which is available on both Windows and MacOS. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/compression/gz

### SEVEN_ZIP {#SEVEN-ZIP}
```
public static final FileType SEVEN_ZIP
```


7Zip (.7z, .7zip) is free open source archiver with LZMA and LZMA2 compression. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/compression/7z/

### DXF {#DXF}
```
public static final FileType DXF
```


Drawing Exchange Format File (.dxf) is a tagged data representation of AutoCAD drawing file. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/dxf

### DWG {#DWG}
```
public static final FileType DWG
```


AutoCAD Drawing Database File (.dwg) represents proprietary binary files used for containing 2D and 3D design data. Like DXF, which are ASCII files, DWG represent the binary file format for CAD (Computer Aided Design) drawings. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/dwg

### DWT {#DWT}
```
public static final FileType DWT
```


AutoCAD Drawing Template (.dwt) is an AutoCAD drawing template file that is used as starter for creating drawings that can be saved as DWG files. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/dwt

### STL {#STL}
```
public static final FileType STL
```


Stereolithography File (.stl) is an interchangeable file format that represents 3-dimensional surface geometry. The file format finds its usage in several fields such as rapid prototyping, 3D printing and computer-aided manufacturing. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/stl

### IFC {#IFC}
```
public static final FileType IFC
```


Industry Foundation Classes File (.ifc) is a file format that establishes international standards to import and export building objects and their properties. This file format provides interoperability between different software applications. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/ifc

### DWF {#DWF}
```
public static final FileType DWF
```


Design Web Format File (.dwf) represents 2D/3D drawing in compressed format for viewing, reviewing or printing design files. It contains graphics and text as part of design data and reduce the size of the file due to its compressed format. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/dwf

### FBX {#FBX}
```
public static final FileType FBX
```


Autodesk FBX Interchange File (FilmBoX) (.fbx) represents 3D model format.

Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/fbx

### DWFX {#DWFX}
```
public static final FileType DWFX
```


Design Web Format File XPS (.dwfx) represents 2D/3D drawing as XPS document in compressed format for viewing, reviewing or printing design files. It contains graphics and text as part of design data and reduce the size of the file due to its compressed format. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/dwfx

### DGN {#DGN}
```
public static final FileType DGN
```


MicroStation Design File (.dgn) are drawings created by and supported by CAD applications such as MicroStation and Intergraph Interactive Graphics Design System. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/dgn

### PLT {#PLT}
```
public static final FileType PLT
```


PLT (HPGL) (.plt) is a vector-based plotter file introduced by Autodesk, Inc. and contains information for a certain CAD file. Plotting details require accuracy and precision in production, and usage of PLT file guarantee this as all images are printed using lines instead of dots. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/plt

### CF2 {#CF2}
```
public static final FileType CF2
```


Common File Format File. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/cf2

### OBJ {#OBJ}
```
public static final FileType OBJ
```


Wavefront 3D Object File (.obj) is 3D image file introduced by Wavefront Technologies. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/3d/obj/

### HPG {#HPG}
```
public static final FileType HPG
```


PLT (HPGL) (.hpg).

### IGS {#IGS}
```
public static final FileType IGS
```


Initial Graphics Exchange Specification (IGES) (.igs).

### VSD {#VSD}
```
public static final FileType VSD
```


Visio Drawing File (.vsd) are drawings created with Microsoft Visio application to represent variety of graphical objects and the interconnection between these. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vsd

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Visio Drawing (.vsdx) represents Microsoft Visio file format introduced from Microsoft Office 2013 onwards. It was developed to replace the binary file format, .VSD, which is supported by earlier versions of Microsoft Visio. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vsdx

### VSS {#VSS}
```
public static final FileType VSS
```


Visio Stencil File(.vss) are stencil files created with Microsoft Visio 2007 and earlier. Stencil files provide drawing objects that can be included in a .VSD Visio drawing. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vss

### VSSX {#VSSX}
```
public static final FileType VSSX
```


Visio Stencil File (.vssx) are drawing stencils created with Microsoft Visio 2013 and above. The VSSX file format can be opened with Visio 2013 and above. Visio files are known for representation of a variety of drawing elements such as collection of shapes, connectors, flowcharts, network layout, UML diagrams, Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vssx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Visio Macro-Enabled Drawing (.vsdm) are drawing files created with Microsoft Visio application that supports macros. VSDM files are OPC/XML drawings that are similar to VSDX, but also provide the capability to run macros when the file is opened. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vsdm

### VST {#VST}
```
public static final FileType VST
```


Visio Drawing Template (.vst) are vector image files created with Microsoft Visio and act as template for creating further files. These template files are in binary file format and contain the default layout and settings that are utilized for creation of new Visio drawings. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vst

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Visio Drawing Template (.vstx) are drawing template files created with Microsoft Visio 2013 and above. These VSTX files provide starting point for creating Visio drawings, saved as .VSDX files, with default layout and settings. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Visio Macro-Enabled Drawing Template (.vstm) are template files created with Microsoft Visio that support macros. Unlike VSDX files, files created from VSTM templates can run macros that are developed in Visual Basic for Applications (VBA) code. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Visio Macro-Enabled Stencil File (.vssm) are Microsoft Visio Stencil files that support provide support for macros. A VSSM file when opened allows to run the macros to achieve desired formatting and placement of shapes in a diagram. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Visio Stencil XML File (.vsx) refers to stencils that consist of drawings and shapes that are used for creating diagrams in Microsoft Visio. VSX files are saved in XML file format and was supported till Visio 2013. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


Visio Template XML File (.vtx) is a Microsoft Visio drawing template that is saved to disc in XML file format. The template is aimed to provide a file with basic settings that can be used to create multiple Visio files of the same settings. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vtx

### VDW {#VDW}
```
public static final FileType VDW
```


Visio Web Drawing (.vdw) represents file format that specifies the streams and storages required for rendering a Web drawing. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/vdw

### VDX {#VDX}
```
public static final FileType VDX
```


Visio Drawing XML File (.vdx) represents any drawing or chart created in Microsoft Visio, but saved in XML format have .VDX extension. A Visio drawing XML file is created in Visio software, which is developed by Microsoft. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Open eBook File (.epub) is an e-book file format that provide a standard digital publication format for publishers and consumers. The format has been so common by now that it is supported by many e-readers and software applications. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/ebook/epub

### MOBI {#MOBI}
```
public static final FileType MOBI
```


Mobipocket eBook (.mobi) is one of the most widely used ebook file format. The format is an enhancement to the old OEB (Open Ebook Format) format and was used as proprietary format for Mobipocket Reader. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/ebook/mobi

### MSG {#MSG}
```
public static final FileType MSG
```


Outlook Mail Message (.msg) is a file format used by Microsoft Outlook and Exchange to store email messages, contact, appointment, or other tasks. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/email/msg

### EML {#EML}
```
public static final FileType EML
```


E-Mail Message (.eml) represents email messages saved using Outlook and other relevant applications. Almost all emailing clients support this file format for its compliance with RFC-822 Internet Message Format Standard. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/email/eml

### EMLX {#EMLX}
```
public static final FileType EMLX
```


Apple Mail Message (.emlx) is implemented and developed by Apple. The Apple Mail application uses the EMLX file format for exporting the emails. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/email/emlx

### PST {#PST}
```
public static final FileType PST
```


Outlook Personal Information Store File (.pst) represents Outlook Personal Storage Files (also called Personal Storage Table) that store variety of user information. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/email/pst

### OST {#OST}
```
public static final FileType OST
```


Outlook Offline Data File (.ost) represents user's mailbox data in offline mode on local machine upon registration with Exchange Server using Microsoft Outlook. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/email/ost

### TIF {#TIF}
```
public static final FileType TIF
```


Tagged Image File (.tif) represents raster images that are meant for usage on a variety of devices that comply with this file format standard. It is capable of describing bilevel, grayscale, palette-color and full-color image data in several color spaces. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/tiff

### TIFF {#TIFF}
```
public static final FileType TIFF
```


Tagged Image File Format (.tiff) represents raster images that are meant for usage on a variety of devices that comply with this file format standard. It is capable of describing bilevel, grayscale, palette-color and full-color image data in several color spaces. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/tiff

### JPG {#JPG}
```
public static final FileType JPG
```


JPEG Image (.jpg) is a type of image format that is saved using the method of lossy compression. The output image, as result of compression, is a trade-off between storage size and image quality. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/jpeg

### JPEG {#JPEG}
```
public static final FileType JPEG
```


JPEG Image (.jpeg) is a type of image format that is saved using the method of lossy compression. The output image, as result of compression, is a trade-off between storage size and image quality. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/jpeg

### PNG {#PNG}
```
public static final FileType PNG
```


Portable Network Graphic (.png) is a type of raster image file format that use loseless compression. This file format was created as a replacement of Graphics Interchange Format (GIF) and has no copyright limitations. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/png

### GIF {#GIF}
```
public static final FileType GIF
```


Graphical Interchange Format File (.gif) is a type of highly compressed image. For each image GIF typically allow up to 8 bits per pixel and up to 256 colours are allowed across the image. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/gif

### APNG {#APNG}
```
public static final FileType APNG
```


Animated Portable Network Graphic (.apng) is extension of PNG format that support animation. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/apng

### BMP {#BMP}
```
public static final FileType BMP
```


Bitmap Image File (.bmp) is used to store bitmap digital images. These images are independent of graphics adapter and are also called device independent bitmap (DIB) file format. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/bmp

### ICO {#ICO}
```
public static final FileType ICO
```


Icon File (.ico) are image file types used as icon for representation of an application on Microsoft Windows. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/ico

### TGA {#TGA}
```
public static final FileType TGA
```


Truevision TGA (Truevision Advanced Raster Adapter - TARGA) is used to store bitmap digital images developed by TRUEVISION. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/tga

### JP_2 {#JP-2}
```
public static final FileType JP_2
```


JPEG 2000 Core Image File (.jp2) is an image coding system and state-of-the-art image compression standard. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/jp2

### JPF {#JPF}
```
public static final FileType JPF
```


JPEG 2000 Image File (.jpf)

### JPX {#JPX}
```
public static final FileType JPX
```


JPEG 2000 Image File (.jpx)

### JPM {#JPM}
```
public static final FileType JPM
```


JPEG 2000 Image File (.jpm)

### J2C {#J2C}
```
public static final FileType J2C
```


JPEG 2000 Code InputStream (.j2c)

### J2K {#J2K}
```
public static final FileType J2K
```


JPEG 2000 Code Stream (.j2k) is an image that is compressed using the wavelet compression instead of DCT compression. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/j2k

### JPC {#JPC}
```
public static final FileType JPC
```


JPEG 2000 Code InputStream (.jpc)

### JLS {#JLS}
```
public static final FileType JLS
```


JPEG-LS (JLS) (.jls)

### DIB {#DIB}
```
public static final FileType DIB
```


Device Independent Bitmap File (.dib)

### WMF {#WMF}
```
public static final FileType WMF
```


Windows Metafile (.wmf) represents Microsoft Windows Metafile (WMF) for storing vector as well as bitmap-format images data. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/wmf

### WMZ {#WMZ}
```
public static final FileType WMZ
```


ompressed Windows Metafile (.wmz) represents Microsoft Windows Metafile (WMF) compressed in GZIP archvive - for storing vector as well as bitmap-format images data. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/wmz#compressed_windows_metafile

### EMF {#EMF}
```
public static final FileType EMF
```


Enhanced Windows Metafile (.emf) represents graphical images device-independently. Metafiles of EMF comprises of variable-length records in chronological order that can render the stored image after parsing on any output device. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/emf

### EMZ {#EMZ}
```
public static final FileType EMZ
```


Enhanced Windows Metafile compressed (.emz) represents graphical images device-independently compressed by GZIP. Metafiles of EMF comprises of variable-length records in chronological order that can render the stored image after parsing on any output device. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/emz

### WEBP {#WEBP}
```
public static final FileType WEBP
```


WebP Image (.webp) is a modern raster web image file format that is based on lossless and lossy compression. It provides same image quality while considerably reducing the image size. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/webp

### DNG {#DNG}
```
public static final FileType DNG
```


Digital Negative Specification (.dng) is a digital camera image format used for the storage of raw files. It has been developed by Adobe in September 2004. It was basically developed for digital photography. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/dng

### CDR {#CDR}
```
public static final FileType CDR
```


CorelDraw Vector Graphic Drawing (.cdr) is a vector drawing image file that is natively created with CorelDRAW for storing digital image encoded and compressed. Such a drawing file contains text, lines, shapes, images, colours and effects for vector representation of image contents. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/cdr

### CMX {#CMX}
```
public static final FileType CMX
```


Corel Exchange (.cmx) is a drawing image file that may contain vector graphics as well as bitmap graphics. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/cmx

### DJVU {#DJVU}
```
public static final FileType DJVU
```


DjVu Image (.djvu) is a graphics file format intended for scanned documents and books especially those which contain the combination of text, drawings, images and photographs. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/djvu

### CGM {#CGM}
```
public static final FileType CGM
```


Computer Graphics Metafile (.cgm) is a free, platform-independent, international standard metafile format for storing and exchanging of vector graphics (2D), raster graphics, and text. CGM uses object-oriented approach and many function provisions for image production. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/cgm

### PCL {#PCL}
```
public static final FileType PCL
```


Printer Command Language Document (.pcl)

### PSD {#PSD}
```
public static final FileType PSD
```


Adobe Photoshop Document (.psd) represents Adobe Photoshop's native file format used for graphics designing and development. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/psd

### PSB {#PSB}
```
public static final FileType PSB
```


Photoshop Large Document Format (.psb) represents Photoshop Large Document Format used for graphics designing and development. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/psb

### DCM {#DCM}
```
public static final FileType DCM
```


DICOM Image (.dcm) represents digital image which stores medical information of patients such as MRIs, CT scans and ultrasound images. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/dcm

### PS {#PS}
```
public static final FileType PS
```


PostScript File (.ps)

### EPS {#EPS}
```
public static final FileType EPS
```


Encapsulated PostScript File (.eps) describes an Encapsulated PostScript language program that describes the appearance of a single page. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/eps

### ODG {#ODG}
```
public static final FileType ODG
```


OpenDocument Graphic File (.odg) is used by Apache OpenOffice's Draw application to store drawing elements as a vector image. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/odg

### FODG {#FODG}
```
public static final FileType FODG
```


Flat XML ODF Template (.fodg) is used by Apache OpenOffice's Draw application to store drawing elements as a vector image. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/fodg

### SVG {#SVG}
```
public static final FileType SVG
```


Scalable Vector Graphics File (.svg) is a Scalar Vector Graphics file that uses XML based text format for describing the appearance of an image. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/svg

### SVGZ {#SVGZ}
```
public static final FileType SVGZ
```


Scalable Vector Graphics File (.svgz) is a Scalar Vector Graphics file that uses XML based text format, compressed by GZIP for describing the appearance of an image. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/svgz

### OTG {#OTG}
```
public static final FileType OTG
```


OpenDocument Graphic Template (.otg)

### HTM {#HTM}
```
public static final FileType HTM
```


Hypertext Markup Language File (.htm) is the extension for web pages created for display in browsers. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/html

### HTML {#HTML}
```
public static final FileType HTML
```


Hypertext Markup Language File (.html) is the extension for web pages created for display in browsers. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


MHTML Web Archive (.mht)

### NSF {#NSF}
```
public static final FileType NSF
```


Lotus Notes Database (.nsf) Learn more about this file format https://fileinfo.com/extension/nsf

### MBOX {#MBOX}
```
public static final FileType MBOX
```


Email Mailbox File (.mbox). Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/mbox

### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML File (.mhtml)

### XML {#XML}
```
public static final FileType XML
```


XML File (.xml)

### ONE {#ONE}
```
public static final FileType ONE
```


OneNote Document (.one) is created by Microsoft OneNote application. OneNote lets you gather information using the application as if you are using your draftpad for taking notes. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


Portable Document Format File (.pdf) is a type of document created by Adobe back in 1990s. The purpose of this file format was to introduce a standard for representation of documents and other reference material in a format that is independent of application software, hardware as well as Operating System. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


XML Paper Specification File (.xps) represents page layout files that are based on XML Paper Specifications created by Microsoft. This format was developed by Microsoft as a replacement of EMF file format and is similar to PDF file format, but uses XML in layout, appearance, and printing information of a document. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/xps

### OXPS {#OXPS}
```
public static final FileType OXPS
```


OpenXPS File (.oxps)

### TEX {#TEX}
```
public static final FileType TEX
```


LaTeX Source Document (.tex) is a language that comprises of programming as well as mark-up features, used to typeset documents. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


PowerPoint Presentation (.ppt) represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


PowerPoint Open XML Presentation (.pptx) are presentation files created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


PowerPoint Slide Show (.pps) are created using Microsoft PowerPoint for Slide Show purpose. PPS file reading and creation is supported by Microsoft PowerPoint 97-2003. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


PowerPoint Open XML Slide Show (.ppsx) files are created using Microsoft PowerPoint 2007 and above for Slide Show purpose. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument Presentation (.odp) represents presentation file format used by OpenOffice.org in the OASISOpen standard. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/presentation/odp

### FODP {#FODP}
```
public static final FileType FODP
```


OpenDocument Presentation (.fodp) represents OpenDocument Flat XML Presentation. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/fodp

### POT {#POT}
```
public static final FileType POT
```


PowerPoint Template (.pot) represents Microsoft PowerPoint template files created by PowerPoint 97-2003 versions. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/presentation/pot

### PPTM {#PPTM}
```
public static final FileType PPTM
```


PowerPoint Open XML Macro-Enabled Presentation are Macro-enabled Presentation files that are created with Microsoft PowerPoint 2007 or higher versions. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/presentation/pptm

### POTX {#POTX}
```
public static final FileType POTX
```


PowerPoint Open XML Presentation Template (.potx) represents Microsoft PowerPoint template presentations that are created with Microsoft PowerPoint 2007 and above. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/presentation/potx

### POTM {#POTM}
```
public static final FileType POTM
```


PowerPoint Open XML Macro-Enabled Presentation Template (.potm) are Microsoft PowerPoint template files with support for Macros. POTM files are created with PowerPoint 2007 or above and contains default settings that can be used to create further presentation files. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/presentation/potm

### PPSM {#PPSM}
```
public static final FileType PPSM
```


PowerPoint Open XML Macro-Enabled Slide (.ppsm) represents Macro-enabled Slide Show file format created with Microsoft PowerPoint 2007 or higher. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/presentation/ppsm

### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument Presentation Template (.otp) represents presentation template files created by applications in OASIS OpenDocument standard format. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


Excel Spreadsheet (.xls) represents Excel Binary File Format. Such files can be created by Microsoft Excel as well as other similar spreadsheet programs such as OpenOffice Calc or Apple Numbers. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### EXCEL_2003_XML {#EXCEL-2003-XML}
```
public static final FileType EXCEL_2003_XML
```


Excel 2003 XML (SpreadsheetML) represents Excel Binary File Format. Such files can be created by Microsoft Excel as well as other similar spreadsheet programs such as OpenOffice Calc or Apple Numbers. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### NUMBERS {#NUMBERS}
```
public static final FileType NUMBERS
```


Apple numbers represents Excel like Binary File Format. Such files can be created by Apple numbers application. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/numbers

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel Open XML Spreadsheet (.xlsx) is a well-known format for Microsoft Excel documents that was introduced by Microsoft with the release of Microsoft Office 2007. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Excel Open XML Macro-Enabled Spreadsheet (.xlsm) is a type of Spreasheet files that support macros. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Excel Binary Spreadsheet (.xlsb) specifies the Excel Binary File Format, which is a collection of records and structures that specify Excel workbook content. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


Comma Separated Values File (.csv) represents plain text files that contain records of data with comma separated values. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


Tab Separated Values File (.tsv) represents data separated with tabs in plain text format. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument Spreadsheet (.ods) stands for OpenDocument Spreadsheet Document format that are editable by user. Data is stored inside ODF file into rows and columns. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ods

### FODS {#FODS}
```
public static final FileType FODS
```


OpenDocument Flat XML Spreadsheet (.fods)

### OTS {#OTS}
```
public static final FileType OTS
```


OpenDocument Spreadsheet Template (.ots)

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Microsoft Excel Add-in (.xlam)

### XLTM {#XLTM}
```
public static final FileType XLTM
```


Microsoft Excel Macro-Enabled Template (.xltm) represents files that are generated by Microsoft Excel as Macro-enabled template files. XLTM files are similar to XLTX in structure other than that the later doesn't support creating template files with macros. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltm

### XLT {#XLT}
```
public static final FileType XLT
```


Microsoft Excel Template (.xlt) are template files created with Microsoft Excel which is a spreadsheet application which comes as part of Microsoft Office suite. Microsoft Office 97-2003 supported creating new XLT files as well as opening these. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlt

### XLTX {#XLTX}
```
public static final FileType XLTX
```


Excel Open XML Spreadsheet Template (.xltx) represents Microsoft Excel Template that are based on the Office OpenXML file format specifications. It is used to create a standard template file that can be utilized to generate XLSX files that exhibit the same settings as specified in the XLTX file. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltx

### SXC {#SXC}
```
public static final FileType SXC
```


StarOffice Calc Spreadsheet (.sxc)

### MPP {#MPP}
```
public static final FileType MPP
```


Microsoft Project File (.mpp) is Microsoft Project data file that stores information related to project management in an integrated manner. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/project-management/mpp

### MPT {#MPT}
```
public static final FileType MPT
```


Microsoft Project Template (.mpt) contains basic information and structure along with document settings for creating .MPP files. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/project-management/mpt

### MPX {#MPX}
```
public static final FileType MPX
```


Microsoft Project Exchange file (.mpx) is an ASCII file format for transferring of project information between Microsoft Project (MSP) and other applications that support the MPX file format such as Primavera Project Planner, Sciforma and Timerline Precision Estimating. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/project-management/mpx

### AS {#AS}
```
public static final FileType AS
```


ActionScript File (.as)

### AS_3 {#AS-3}
```
public static final FileType AS_3
```


ActionScript File (.as)

### ASM {#ASM}
```
public static final FileType ASM
```


Assembly Language Source Code File (.asm)

### BAT {#BAT}
```
public static final FileType BAT
```


DOS Batch File (.bat)

### C {#C}
```
public static final FileType C
```


C/C++ Source Code File (.c)

### CC {#CC}
```
public static final FileType CC
```


C++ Source Code File (.cc)

### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


CMake File (.cmake)

### CPP {#CPP}
```
public static final FileType CPP
```


C++ Source Code File (.cpp)

### CS {#CS}
```
public static final FileType CS
```


C\# Source Code File (.cs) is a source code file for C\# programming language. Introduced by Microsoft for use with the .NET Framework. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/programming/cs

### VB {#VB}
```
public static final FileType VB
```


Visual Basic Project Item File (.vb) is a source code file created in Visual Basic language that was created by Microsoft for development of .NET applications. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/programming/vb

### CSS {#CSS}
```
public static final FileType CSS
```


Cascading Style Sheet (.css)

### CXX {#CXX}
```
public static final FileType CXX
```


C++ Source Code File (.cxx)

### DIFF {#DIFF}
```
public static final FileType DIFF
```


Patch File (.diff)

### ERB {#ERB}
```
public static final FileType ERB
```


Ruby ERB Script (.erb)

### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Groovy Source Code File (.groovy)

### H {#H}
```
public static final FileType H
```


C/C++/Objective-C Header File (.h)

### HAML {#HAML}
```
public static final FileType HAML
```


Haml Source Code File (.haml)

### HH {#HH}
```
public static final FileType HH
```


C++ Header File (.hh)

### JAVA {#JAVA}
```
public static final FileType JAVA
```


Java Source Code File (.java)

### JS {#JS}
```
public static final FileType JS
```


JavaScript File (.js)

### JSON {#JSON}
```
public static final FileType JSON
```


JavaScript Object Notation File (.json)

### LESS {#LESS}
```
public static final FileType LESS
```


LESS Style Sheet (.less)

### LOG {#LOG}
```
public static final FileType LOG
```


Log File (.log)

### M {#M}
```
public static final FileType M
```


Objective-C Implementation File (.m)

### MAKE {#MAKE}
```
public static final FileType MAKE
```


Xcode Makefile Script (.make)

### MD {#MD}
```
public static final FileType MD
```


Markdown Documentation File (.md)

### ML {#ML}
```
public static final FileType ML
```


ML Source Code File (.ml)

### MM {#MM}
```
public static final FileType MM
```


Objective-C++ Source File (.mm)

### PHP {#PHP}
```
public static final FileType PHP
```


PHP Source Code File (.php)

### PL {#PL}
```
public static final FileType PL
```


Perl Script (.pl)

### PROPERTIES {#PROPERTIES}
```
public static final FileType PROPERTIES
```


Java Properties File (.properties)

### PY {#PY}
```
public static final FileType PY
```


Python Script (.py)

### RB {#RB}
```
public static final FileType RB
```


Ruby Source Code (.rb)

### RST {#RST}
```
public static final FileType RST
```


reStructuredText File (.rst)

### SASS {#SASS}
```
public static final FileType SASS
```


Syntactically Awesome StyleSheets File (.sass)

### SCALA {#SCALA}
```
public static final FileType SCALA
```


Scala Source Code File (.scala)

### SCM {#SCM}
```
public static final FileType SCM
```


Scheme Source Code File (.scm)

### SCRIPT {#SCRIPT}
```
public static final FileType SCRIPT
```


Generic Script File (.script)

### SH {#SH}
```
public static final FileType SH
```


Bash Shell Script (.sh)

### SML {#SML}
```
public static final FileType SML
```


Standard ML Source Code File (.sml)

### SQL {#SQL}
```
public static final FileType SQL
```


Structured Query Language Data File (.sql)

### VIM {#VIM}
```
public static final FileType VIM
```


Vim Settings File (.vim)

### YAML {#YAML}
```
public static final FileType YAML
```


YAML Document (.yaml)

### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word Document (.doc) represents documents generated by Microsoft Word or other word processing documents in binary file format. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word Open XML Document (.docx) is a well-known format for Microsoft Word documents. Introduced from 2007 with the release of Microsoft Office 2007, the structure of this new Document format was changed from plain binary to a combination of XML and binary files. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/word-processing/docx

### CHM {#CHM}
```
public static final FileType CHM
```


Microsoft Compiled HTML Help File (.chm) is a well-known format for HELP (documentation to some application) documents. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/web/chm/

### DOCM {#DOCM}
```
public static final FileType DOCM
```


Word Open XML Macro-Enabled Document (.docm) is a Microsoft Word 2007 or higher generated documents with the ability to run macros. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


Word Document Template (.dot) are template files created by Microsoft Word to have pre-formatted settings for generation of further DOC or DOCX files. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Word Open XML Document Template (.dotx) are template files created by Microsoft Word to have pre-formatted settings for generation of further DOCX files. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Word Open XML Macro-Enabled Document Template (.dotm) represents template file created with Microsoft Word 2007 or higher. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


Rich Text Format File (.rtf) represents a method of encoding formatted text and graphics for use within applications. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


Plain Text File (.txt) represents a text document that contains plain text in the form of lines. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/word-processing/txt

### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument Text Document (.odt) are type of documents created with word processing applications that are based on OpenDocument Text File format. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument Document Template (.ott) represents template documents generated by applications in compliance with the OASIS' OpenDocument standard format. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/word-processing/ott

### VCF {#VCF}
```
public static final FileType VCF
```


vCard File (.vcf) is a digital file format for storing contact information. The format is widely used for data interchange among popular information exchange applications. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/email/vcf

### AI {#AI}
```
public static final FileType AI
```


Adobe Illustrator (.ai) is a file format for Adobe Illustrator drawings. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/ai#adobe_illustrator_file

### PSM1 {#PSM1}
```
public static final FileType PSM1
```


PowerShell script module (.psm1) a file format for PowerShell module scripts.

Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/psm1

### PS1 {#PS1}
```
public static final FileType PS1
```


PowerShell script file (.ps1) a file format for Windows PowerShell Cmdlet files.

Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/ps1

### PSD1 {#PSD1}
```
public static final FileType PSD1
```


PowerShell script module manifest (.psd1) a file format for PowerShell module manifest scripts.

Learn more about this file format [here][].


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
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


Maps file extension to file type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | File extension with or without the period "." |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - When file type is supported returns it, otherwise returns default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromFilePath(String filePath) {#fromFilePath-java.lang.String-}
```
public static FileType fromFilePath(String filePath)
```


Extracts file extension and maps it to file type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file name or file path. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - When file type is supported returns it, otherwise returns default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromMediaType(String mediaType) {#fromMediaType-java.lang.String-}
```
public static FileType fromMediaType(String mediaType)
```


Maps file media type to file type e.g. 'application/pdf' will be mapped to [FileType](../../com.groupdocs.viewer/filetype).PDF.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mediaType | java.lang.String | File media type e.g. application/pdf. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - Returns corresponding media type when found, otherwise returns default Unknown file type.
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream stream)
```


Detects file type by reading the file signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The file stream. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
### fromStream(InputStream stream, String password) {#fromStream-java.io.InputStream-java.lang.String-}
```
public static FileType fromStream(InputStream stream, String password)
```


Detects file type by reading the file signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The file stream. |
| password | java.lang.String | The password to open the file. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
### fromStream(InputStream stream, ILogger logger) {#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, ILogger logger)
```


Detects file type by reading the file signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The file stream. |
| logger | com.groupdocs.foundation.logging.ILogger | The logger. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - Returns file type in case it was detected successfully otherwise returns default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password, ILogger logger) {#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, String password, ILogger logger)
```


Detects file type by reading the file signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The file stream. |
| password | java.lang.String | The password to open the file. |
| logger | com.groupdocs.foundation.logging.ILogger | The logger. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - Returns file type in case it was detected successfully otherwise returns default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Retrieves supported file types

**Returns:**
java.util.List<com.groupdocs.viewer.FileType> - Returns sequence of supported file types **Learn more**Learn more about supported document formats: [Full list of supported file formats][]Learn more about getting supported file types in Java code: [How to get supported file types in code][]


[Full list of supported file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/
[How to get supported file types in code]: https://docs.groupdocs.com/viewer/java/how-to-list-and-print-all-supported-file-types/
### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


File type name e.g. "Microsoft Word Document".

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Filename suffix (including the period ".") e.g. ".doc".

**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Returns a String that represents the current object.

**Returns:**
java.lang.String - A String that represents the current object.
