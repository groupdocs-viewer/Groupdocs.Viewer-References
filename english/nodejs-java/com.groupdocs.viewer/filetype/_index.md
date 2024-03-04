---
title: FileType
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Represents the file type.
type: docs
weight: 14
url: /nodejs-java/com.groupdocs.viewer/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, com.groupdocs.viewer.caching.Cacheable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>, Cacheable
```

Represents the file type. Provides methods to obtain a list of all file types supported by the GroupDocs.Viewer component.

The FileType enum provides constants representing different file types that are supported by the GroupDocs.Viewer component. You can use the methods in this enum to obtain a list of all supported file types or check if a specific file type is supported.

Example usage:

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
## Fields

| Field | Description |
| --- | --- |
| [UNKNOWN](#UNKNOWN) | Represents an unknown file type. |
| [ZIP](#ZIP) | Represents a zipped file (.zip) that can hold one or more files or directories. |
| [TAR](#TAR) | Represents a consolidated Unix file archive (.tar) created for collecting one or more files. |
| [XZ](#XZ) | Represents an XZ file (.xz) compressed using a high-ratio compression algorithm based on the LZMA algorithm. |
| [TXZ](#TXZ) | Represents a consolidated Unix file archive (.txz, .tar.xz) created for collecting one or more files. |
| [TARXZ](#TARXZ) | Represents a consolidated Unix file archive (.txz, .tar.xz) created for collecting one or more files. |
| [TGZ](#TGZ) | Represents a consolidated Unix file archive (.tgz, .tar.gz) created for collecting one or more files. |
| [TARGZ](#TARGZ) | Represents a consolidated Unix file archive (.tgz, .tar.gz) created for collecting one or more files. |
| [BZ_2](#BZ-2) | Represents a Bzip2 compressed file (.bz2) generated using the BZIP2 open-source compression method. |
| [RAR](#RAR) | Represents a Roshal Archive (.rar) compressed file generated using the RAR (WINRAR version 4) compression method. |
| [GZ](#GZ) | Represents a Gnu Zipped File (.gz) compressed file created with the gzip compression application. |
| [GZIP](#GZIP) | Represents a Gnu Zipped File (.gzip) compressed file introduced as a free utility for replacing the Compress program used in Unix systems. |
| [SEVEN_ZIP](#SEVEN-ZIP) | Represents a 7Zip (.7z, .7zip) file, which is a free open-source archiver with LZMA and LZMA2 compression. |
| [DXF](#DXF) | Represents a Drawing Exchange Format File (.dxf), which is a tagged data representation of an AutoCAD drawing file. |
| [DWG](#DWG) | Represents an AutoCAD Drawing Database File (.dwg), which represents proprietary binary files used for containing 2D and 3D design data. |
| [DWT](#DWT) | Represents an AutoCAD Drawing Template (.dwt), which is an AutoCAD drawing template file used as a starter for creating drawings that can be saved as DWG files. |
| [STL](#STL) | Represents a Stereolithography File (.stl), which is an interchangeable file format that represents 3-dimensional surface geometry. |
| [IFC](#IFC) | Represents an Industry Foundation Classes File (.ifc), which is a file format that establishes international standards for importing and exporting building objects and their properties. |
| [DWF](#DWF) | Represents a Design Web Format File (.dwf), which is a compressed file format for viewing, reviewing, or printing 2D/3D drawings. |
| [FBX](#FBX) | Represents an Autodesk FBX Interchange File (FilmBoX) (.fbx), which is a 3D model format. |
| [DWFX](#DWFX) | Represents a Design Web Format File XPS (.dwfx), which is a compressed format for viewing, reviewing, or printing 2D/3D drawings as an XPS document. |
| [DGN](#DGN) | Represents a MicroStation Design File (.dgn), which are drawings created and supported by CAD applications such as MicroStation and Intergraph Interactive Graphics Design System. |
| [PLT](#PLT) | Represents a PLT (HPGL) File (.plt), which is a vector-based plotter file introduced by Autodesk, Inc. |
| [CF2](#CF2) | Represents a Common File Format File (.cf2). |
| [OBJ](#OBJ) | Represents a Wavefront 3D Object File (.obj), which is a 3D image file introduced by Wavefront Technologies. |
| [HPG](#HPG) | Represents a PLT (HPGL) File (.hpg). |
| [IGS](#IGS) | Represents an Initial Graphics Exchange Specification (IGES) File (.igs). |
| [VSD](#VSD) | Represents a Visio Drawing File (.vsd), which are drawings created with Microsoft Visio application to represent a variety of graphical objects and their interconnections. |
| [VSDX](#VSDX) | Represents a Visio Drawing File (.vsdx), which represents the Microsoft Visio file format introduced from Microsoft Office 2013 onwards. |
| [VSS](#VSS) | Represents a Visio Stencil File (.vss), which are stencil files created with Microsoft Visio 2007 and earlier. |
| [VSSX](#VSSX) | Represents a Visio Stencil File (.vssx), which are drawing stencils created with Microsoft Visio 2013 and above. |
| [VSDM](#VSDM) | Represents a Visio Macro-Enabled Drawing (.vsdm), which are drawing files created with Microsoft Visio application that support macros. |
| [VST](#VST) | Represents a Visio Drawing Template (.vst), which are vector image files created with Microsoft Visio. |
| [VSTX](#VSTX) | Represents a Visio Drawing Template (.vstx), which are drawing template files created with Microsoft Visio 2013 and above. |
| [VSTM](#VSTM) | Represents a Visio Macro-Enabled Drawing Template (.vstm), which are template files created with Microsoft Visio that support macros. |
| [VSSM](#VSSM) | Represents a Visio Macro-Enabled Stencil File (.vssm), which are Microsoft Visio Stencil files that support macros. |
| [VSX](#VSX) | Represents a Visio Stencil XML File (.vsx), which refers to stencils consisting of drawings and shapes used for creating diagrams in Microsoft Visio. |
| [VTX](#VTX) | Represents a Visio Template XML File (.vtx), which is a Microsoft Visio drawing template saved to disk in XML file format. |
| [VDW](#VDW) | Represents a Visio Web Drawing (.vdw), which specifies the streams and storages required for rendering a web drawing. |
| [VDX](#VDX) | Represents a Visio Drawing XML File (.vdx), which represents any drawing or chart created in Microsoft Visio but saved in XML format with the .VDX extension. |
| [EPUB](#EPUB) | Represents an Open eBook File (.epub), which is an e-book file format that provides a standard digital publication format for publishers and consumers. |
| [MOBI](#MOBI) | Represents a Mobipocket eBook (.mobi), which is one of the most widely used ebook file formats. |
| [MSG](#MSG) | Represents an Outlook Mail Message (.msg), which is a file format used by Microsoft Outlook and Exchange to store email messages, contacts, appointments, or other tasks. |
| [EML](#EML) | Represents an E-Mail Message (.eml), which represents email messages saved using Outlook and other relevant applications. |
| [EMLX](#EMLX) | Represents an Apple Mail Message (.emlx), which is implemented and developed by Apple. |
| [PST](#PST) | Represents an Outlook Personal Information Store File (.pst), which represents Outlook Personal Storage Files (also called Personal Storage Table) that store a variety of user information. |
| [OST](#OST) | Represents an Outlook Offline Data File (.ost), which represents a user's mailbox data in offline mode on a local machine upon registration with Exchange Server using Microsoft Outlook. |
| [TIF](#TIF) | Represents a Tagged Image File (.tif), which represents raster images that are meant for usage on a variety of devices that comply with this file format standard. |
| [TIFF](#TIFF) | Represents a Tagged Image File Format (.tiff), which represents raster images that are meant for usage on a variety of devices that comply with this file format standard. |
| [JPG](#JPG) | Represents a JPEG Image (.jpg), which is a type of image format that is saved using the method of lossy compression. |
| [JPEG](#JPEG) | Represents a JPEG Image (.jpeg), which is a type of image format that is saved using the method of lossy compression. |
| [PNG](#PNG) | Represents a Portable Network Graphic (.png), which is a type of raster image file format that uses lossless compression. |
| [GIF](#GIF) | Represents a Graphical Interchange Format File (.gif), which is a type of highly compressed image. |
| [APNG](#APNG) | Represents an Animated Portable Network Graphic (.apng), which is an extension of the PNG format that supports animation. |
| [BMP](#BMP) | Represents a Bitmap Image File (.bmp), which is used to store bitmap digital images. |
| [ICO](#ICO) | Represents an Icon File (.ico), which is an image file type used as an icon for the representation of an application on Microsoft Windows. |
| [TGA](#TGA) | Represents a Truevision TGA (TARGA) file, which is used to store bitmap digital images developed by TRUEVISION. |
| [JP_2](#JP-2) | Represents a JPEG 2000 Core Image File (.jp2), which is an image coding system and state-of-the-art image compression standard. |
| [JPF](#JPF) | Represents a JPEG 2000 Image File (.jpf). |
| [JPX](#JPX) | Represents a JPEG 2000 Image File (.jpx). |
| [JPM](#JPM) | Represents a JPEG 2000 Image File (.jpm). |
| [J2C](#J2C) | Represents a JPEG 2000 Code InputStream (.j2c). |
| [J2K](#J2K) | Represents a JPEG 2000 Code Stream (.j2k), which is an image compressed using wavelet compression instead of DCT compression. |
| [JPC](#JPC) | Represents a JPEG 2000 Code Stream (.jpc). |
| [JLS](#JLS) | Represents a JPEG-LS (JLS) file (.jls). |
| [DIB](#DIB) | Represents a Device Independent Bitmap File (.dib). |
| [WMF](#WMF) | Represents a Windows Metafile (.wmf), which represents Microsoft Windows Metafile (WMF) for storing vector as well as bitmap-format image data. |
| [WMZ](#WMZ) | Represents a Compressed Windows Metafile (.wmz), which represents Microsoft Windows Metafile (WMF) compressed in GZIP archive for storing vector as well as bitmap-format image data. |
| [EMF](#EMF) | Represents an Enhanced Windows Metafile (.emf), which represents graphical images device-independently. |
| [EMZ](#EMZ) | Represents a Windows Compressed Enhanced Metafile (.emz), which represents graphical images device-independently compressed by GZIP. |
| [WEBP](#WEBP) | Represents a WebP Image (.webp), which is a modern raster web image file format based on lossless and lossy compression. |
| [DNG](#DNG) | Represents a Digital Negative Specification (.dng), which is a digital camera image format used for the storage of raw files. |
| [CDR](#CDR) | Represents a CorelDraw Vector Graphic Drawing (.cdr), which is a vector drawing image file natively created with CorelDRAW for storing digitally encoded and compressed images. |
| [CMX](#CMX) | Represents a Corel Exchange (.cmx), which is a drawing image file that may contain vector graphics as well as bitmap graphics. |
| [DJVU](#DJVU) | Represents a DjVu Image (.djvu), which is a graphics file format intended for scanned documents and books, especially those containing a combination of text, drawings, images, and photographs. |
| [CGM](#CGM) | Represents a Computer Graphics Metafile (.cgm), which is a free, platform-independent, international standard metafile format for storing and exchanging vector graphics (2D), raster graphics, and text. |
| [PCL](#PCL) | Represents a Printer Command Language Document (.pcl). |
| [PSD](#PSD) | Represents an Adobe Photoshop Document (.psd), which is Adobe Photoshop's native file format used for graphics designing and development. |
| [PSB](#PSB) | Represents a Photoshop Large Document Format (.psb), which is used for graphics designing and development in Adobe Photoshop. |
| [DCM](#DCM) | Represents a DICOM Image (.dcm), which represents a digital image that stores medical information of patients such as MRIs, CT scans, and ultrasound images. |
| [PS](#PS) | Represents a PostScript File (.ps). |
| [EPS](#EPS) | Represents an Encapsulated PostScript File (.eps), which describes an Encapsulated PostScript language program that defines the appearance of a single page. |
| [ODG](#ODG) | Represents an OpenDocument Graphic File (.odg), which is used by Apache OpenOffice's Draw application to store drawing elements as a vector image. |
| [FODG](#FODG) | Represents a Flat XML ODF Template (.fodg), which is used by Apache OpenOffice's Draw application to store drawing elements as a vector image. |
| [SVG](#SVG) | Represents a Scalable Vector Graphics File (.svg), which is a Scalar Vector Graphics file that uses XML-based text format for describing the appearance of an image. |
| [SVGZ](#SVGZ) | Represents a Compressed Scalable Vector Graphics File (.svgz), which is a Scalar Vector Graphics file that uses XML-based text format, compressed by GZIP, for describing the appearance of an image. |
| [OTG](#OTG) | Represents an OpenDocument Graphic Template (.otg). |
| [HTM](#HTM) | Represents a Hypertext Markup Language File (.htm), which is the extension for web pages created for display in browsers. |
| [HTML](#HTML) | Represents a Hypertext Markup Language File (.html), which is the extension for web pages created for display in browsers. |
| [MHT](#MHT) | Represents an MHTML Web Archive (.mht). |
| [NSF](#NSF) | Represents a Lotus Notes Database (.nsf). |
| [MBOX](#MBOX) | Represents an Email Mailbox File (.mbox). |
| [MHTML](#MHTML) | Represents a MIME HTML File (.mhtml). |
| [XML](#XML) | Represents an XML File (.xml). |
| [ONE](#ONE) | Represents a OneNote Document (.one) created by Microsoft OneNote application. |
| [PDF](#PDF) | Represents a Portable Document Format File (.pdf), which is a type of document created by Adobe back in the 1990s. |
| [XPS](#XPS) | Represents an XML Paper Specification File (.xps), which represents page layout files based on XML Paper Specifications created by Microsoft. |
| [OXPS](#OXPS) | Represents an OpenXPS File (.oxps). |
| [TEX](#TEX) | Represents a LaTeX Source Document (.tex), which is a language that comprises programming as well as mark-up features used to typeset documents. |
| [PPT](#PPT) | Represents a PowerPoint Presentation (.ppt), which represents a PowerPoint file that consists of a collection of slides for displaying as a slideshow. |
| [PPTX](#PPTX) | Represents a PowerPoint Open XML Presentation (.pptx), which are presentation files created with the popular Microsoft PowerPoint application. |
| [PPS](#PPS) | Represents a PowerPoint Slide Show (.pps), which are created using Microsoft PowerPoint for Slide Show purposes. |
| [PPSX](#PPSX) | Represents a PowerPoint Open XML Slide Show (.ppsx) files, which are created using Microsoft PowerPoint 2007 and above for Slide Show purposes. |
| [ODP](#ODP) | Represents an OpenDocument Presentation (.odp), which represents a presentation file format used by OpenOffice.org in the OASISOpen standard. |
| [FODP](#FODP) | Represents an OpenDocument Presentation (.fodp), which represents OpenDocument Flat XML Presentation. |
| [POT](#POT) | Represents a PowerPoint Template (.pot), which represents Microsoft PowerPoint template files created by PowerPoint 97-2003 versions. |
| [PPTM](#PPTM) | Represents a PowerPoint Open XML Macro-Enabled Presentation (.pptm), which are macro-enabled presentation files created with Microsoft PowerPoint 2007 or higher versions. |
| [POTX](#POTX) | Represents a PowerPoint Open XML Presentation Template (.potx), which represents Microsoft PowerPoint template presentations created with Microsoft PowerPoint 2007 and above. |
| [POTM](#POTM) | Represents a PowerPoint Open XML Macro-Enabled Presentation Template (.potm), which are Microsoft PowerPoint template files with support for macros. |
| [PPSM](#PPSM) | Represents a PowerPoint Open XML Macro-Enabled Slide (.ppsm), which represents a macro-enabled slide show file format created with Microsoft PowerPoint 2007 or higher. |
| [OTP](#OTP) | Represents an OpenDocument Presentation Template (.otp), which represents presentation template files created by applications in the OASIS OpenDocument standard format. |
| [XLS](#XLS) | Represents an Excel Spreadsheet (.xls), which represents the Excel Binary File Format. |
| [EXCEL_2003_XML](#EXCEL-2003-XML) | Represents an Excel 2003 XML (SpreadsheetML) (.xml), which represents the Excel Binary File Format. |
| [NUMBERS](#NUMBERS) | Represents Apple Numbers (.numbers), which represents an Excel-like Binary File Format. |
| [XLSX](#XLSX) | Represents a Microsoft Excel Open XML Spreadsheet (.xlsx), which is a well-known format for Microsoft Excel documents that was introduced by Microsoft with the release of Microsoft Office 2007. |
| [XLSM](#XLSM) | Represents an Excel Open XML Macro-Enabled Spreadsheet (.xlsm), which is a type of spreadsheet file that supports macros. |
| [XLSB](#XLSB) | Represents an Excel Binary Spreadsheet (.xlsb), which specifies the Excel Binary File Format. |
| [CSV](#CSV) | Represents a Comma Separated Values File (.csv), which represents plain text files that contain records of data with comma-separated values. |
| [TSV](#TSV) | Represents a Tab Separated Values File (.tsv), which represents data separated with tabs in plain text format. |
| [ODS](#ODS) | Represents an OpenDocument Spreadsheet (.ods), which stands for OpenDocument Spreadsheet Document format that is editable by the user. |
| [FODS](#FODS) | Represents an OpenDocument Flat XML Spreadsheet (.fods). |
| [OTS](#OTS) | Represents an OpenDocument Spreadsheet Template (.ots). |
| [XLAM](#XLAM) | Represents a Microsoft Excel Add-in (.xlam). |
| [XLTM](#XLTM) | Represents a Microsoft Excel Macro-Enabled Template (.xltm), which represents files generated by Microsoft Excel as Macro-enabled template files. |
| [XLT](#XLT) | Represents a Microsoft Excel Template (.xlt), which are template files created with Microsoft Excel, a spreadsheet application that comes as part of the Microsoft Office suite. |
| [XLTX](#XLTX) | Represents an Excel Open XML Spreadsheet Template (.xltx), which represents Microsoft Excel Templates based on the Office OpenXML file format specifications. |
| [SXC](#SXC) | Represents a StarOffice Calc Spreadsheet (.sxc). |
| [MPP](#MPP) | Represents a Microsoft Project File (.mpp), which is a Microsoft Project data file that stores information related to project management in an integrated manner. |
| [MPT](#MPT) | Represents a Microsoft Project Template (.mpt), which contains basic information and structure along with document settings for creating .MPP files. |
| [MPX](#MPX) | Represents a Microsoft Project Exchange file (.mpx), which is an ASCII file format for transferring project information between Microsoft Project (MSP) and other applications that support the MPX file format, such as Primavera Project Planner, Sciforma, and Timerline Precision Estimating. |
| [AS](#AS) | Represents an ActionScript File (.as). |
| [AS_3](#AS-3) | Represents an ActionScript File (.as3). |
| [ASM](#ASM) | Represents an Assembly Language Source Code File (.asm). |
| [BAT](#BAT) | Represents a DOS Batch File (.bat). |
| [C](#C) | Represents a C/C++ Source Code File (.c). |
| [CC](#CC) | Represents a C++ Source Code File (.cc). |
| [CMAKE](#CMAKE) | Represents a CMake File (.cmake). |
| [CPP](#CPP) | Represents a C++ Source Code File (.cpp). |
| [CS](#CS) | Represents a C\# Source Code File (.cs), which is a source code file for the C\# programming language. |
| [VB](#VB) | Represents a Visual Basic Project Item File (.vb), which is a source code file created in the Visual Basic language. |
| [CSS](#CSS) | Represents a Cascading Style Sheet (.css) file. |
| [CXX](#CXX) | Represents a C++ Source Code File (.cxx). |
| [DIFF](#DIFF) | Represents a Patch File (.diff). |
| [ERB](#ERB) | Represents a Ruby ERB Script (.erb). |
| [GROOVY](#GROOVY) | Represents a Groovy Source Code File (.groovy). |
| [H](#H) | Represents a C/C++/Objective-C Header File (.h). |
| [HAML](#HAML) | Represents a Haml Source Code File (.haml). |
| [HH](#HH) | Represents a C++ Header File (.hh). |
| [JAVA](#JAVA) | Represents a Java Source Code File (.java). |
| [JS](#JS) | Represents a JavaScript File (.js). |
| [JSON](#JSON) | Represents a JavaScript Object Notation File (.json). |
| [LESS](#LESS) | Represents a LESS Style Sheet (.less) file. |
| [LOG](#LOG) | Represents a Log File (.log). |
| [M](#M) | Represents an Objective-C Implementation File (.m). |
| [MAKE](#MAKE) | Represents an Xcode Makefile Script (.make). |
| [MD](#MD) | Represents a Markdown Documentation File (.md). |
| [ML](#ML) | Represents an ML Source Code File (.ml). |
| [MM](#MM) | Represents an Objective-C++ Source File (.mm). |
| [PHP](#PHP) | Represents a PHP Source Code File (.php). |
| [PL](#PL) | Represents a Perl Script (.pl). |
| [PROPERTIES](#PROPERTIES) | Represents a Java Properties File (.properties). |
| [PY](#PY) | Represents a Python Script (.py). |
| [RB](#RB) | Represents a Ruby Source Code (.rb) file. |
| [RST](#RST) | Represents a reStructuredText File (.rst). |
| [SASS](#SASS) | Represents a Syntactically Awesome StyleSheets File (.sass). |
| [SCALA](#SCALA) | Represents a Scala Source Code File (.scala). |
| [SCM](#SCM) | Represents a Scheme Source Code File (.scm). |
| [SCRIPT](#SCRIPT) | Represents a Generic Script File (.script). |
| [SH](#SH) | Represents a Bash Shell Script (.sh). |
| [SML](#SML) | Represents a Standard ML Source Code File (.sml). |
| [SQL](#SQL) | Represents a Structured Query Language Data File (.sql). |
| [VIM](#VIM) | Represents a Vim Settings File (.vim). |
| [YAML](#YAML) | Represents a YAML Document (.yaml). |
| [DOC](#DOC) | Represents a Microsoft Word Document (.doc) file. |
| [DOCX](#DOCX) | Represents a Microsoft Word Open XML Document (.docx) file. |
| [CHM](#CHM) | Represents a Microsoft Compiled HTML Help File (.chm). |
| [DOCM](#DOCM) | Represents a Word Open XML Macro-Enabled Document (.docm) file. |
| [DOT](#DOT) | Represents a Word Document Template (.dot) file. |
| [DOTX](#DOTX) | Represents a Word Open XML Document Template (.dotx) file. |
| [DOTM](#DOTM) | Represents a Word Open XML Macro-Enabled Document Template (.dotm) file. |
| [RTF](#RTF) | Represents a Rich Text Format File (.rtf). |
| [TXT](#TXT) | Represents a Plain Text File (.txt). |
| [ODT](#ODT) | Represents an OpenDocument Text Document (.odt). |
| [OTT](#OTT) | Represents an OpenDocument Document Template (.ott). |
| [VCF](#VCF) | Represents a vCard File (.vcf), which is a digital file format for storing contact information. |
| [AI](#AI) | Represents an Adobe Illustrator file (.ai), which is a file format for Adobe Illustrator drawings. |
| [PSM1](#PSM1) | Represents a PowerShell script module file (.psm1). |
| [PS1](#PS1) | Represents a PowerShell script file (.ps1). |
| [PSD1](#PSD1) | Represents a PowerShell script module manifest file (.psd1). |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Maps a file extension to a file type. |
| [fromFilePath(String filePath)](#fromFilePath-java.lang.String-) | Extracts the file extension from a file name or file path and maps it to a file type. |
| [fromMediaType(String mediaType)](#fromMediaType-java.lang.String-) | Maps a file media type to a file type. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Detects the file type by reading the file signature. |
| [fromStream(InputStream stream, String password)](#fromStream-java.io.InputStream-java.lang.String-) | Detects the file type by reading the file signature. |
| [fromStream(InputStream stream, ILogger logger)](#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-) | Detects the file type by reading the file signature. |
| [fromStream(InputStream stream, String password, ILogger logger)](#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-) | Detects the file type by reading the file signature. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | Retrieves the supported file types. |
| [getFileFormat()](#getFileFormat--) | Gets the name of the file format, e.g., "Microsoft Word Document". |
| [getExtension()](#getExtension--) | Gets the file extension suffix (including the period "."), e.g., ".doc". |
| [toString()](#toString--) | Returns a string representation of the current object. |
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Represents an unknown file type.

### ZIP {#ZIP}
```
public static final FileType ZIP
```


Represents a zipped file (.zip) that can hold one or more files or directories. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/compression/zip

### TAR {#TAR}
```
public static final FileType TAR
```


Represents a consolidated Unix file archive (.tar) created for collecting one or more files. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/compression/tar

### XZ {#XZ}
```
public static final FileType XZ
```


Represents an XZ file (.xz) compressed using a high-ratio compression algorithm based on the LZMA algorithm. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/xz

### TXZ {#TXZ}
```
public static final FileType TXZ
```


Represents a consolidated Unix file archive (.txz, .tar.xz) created for collecting one or more files. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/txz

### TARXZ {#TARXZ}
```
public static final FileType TARXZ
```


Represents a consolidated Unix file archive (.txz, .tar.xz) created for collecting one or more files. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/txz

### TGZ {#TGZ}
```
public static final FileType TGZ
```


Represents a consolidated Unix file archive (.tgz, .tar.gz) created for collecting one or more files. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/tgz

### TARGZ {#TARGZ}
```
public static final FileType TARGZ
```


Represents a consolidated Unix file archive (.tgz, .tar.gz) created for collecting one or more files. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/tgz

### BZ_2 {#BZ-2}
```
public static final FileType BZ_2
```


Represents a Bzip2 compressed file (.bz2) generated using the BZIP2 open-source compression method. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/compression/bz2

### RAR {#RAR}
```
public static final FileType RAR
```


Represents a Roshal Archive (.rar) compressed file generated using the RAR (WINRAR version 4) compression method. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/compression/rar

### GZ {#GZ}
```
public static final FileType GZ
```


Represents a Gnu Zipped File (.gz) compressed file created with the gzip compression application. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/compression/gz

### GZIP {#GZIP}
```
public static final FileType GZIP
```


Represents a Gnu Zipped File (.gzip) compressed file introduced as a free utility for replacing the Compress program used in Unix systems. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/compression/gz

### SEVEN_ZIP {#SEVEN-ZIP}
```
public static final FileType SEVEN_ZIP
```


Represents a 7Zip (.7z, .7zip) file, which is a free open-source archiver with LZMA and LZMA2 compression. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/compression/7z/

### DXF {#DXF}
```
public static final FileType DXF
```


Represents a Drawing Exchange Format File (.dxf), which is a tagged data representation of an AutoCAD drawing file. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/dxf

### DWG {#DWG}
```
public static final FileType DWG
```


Represents an AutoCAD Drawing Database File (.dwg), which represents proprietary binary files used for containing 2D and 3D design data. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/dwg

### DWT {#DWT}
```
public static final FileType DWT
```


Represents an AutoCAD Drawing Template (.dwt), which is an AutoCAD drawing template file used as a starter for creating drawings that can be saved as DWG files. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/dwt

### STL {#STL}
```
public static final FileType STL
```


Represents a Stereolithography File (.stl), which is an interchangeable file format that represents 3-dimensional surface geometry. It is commonly used in rapid prototyping, 3D printing, and computer-aided manufacturing. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/stl

### IFC {#IFC}
```
public static final FileType IFC
```


Represents an Industry Foundation Classes File (.ifc), which is a file format that establishes international standards for importing and exporting building objects and their properties. It enables interoperability between different software applications. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/ifc

### DWF {#DWF}
```
public static final FileType DWF
```


Represents a Design Web Format File (.dwf), which is a compressed file format for viewing, reviewing, or printing 2D/3D drawings. It contains graphics and text as part of the design data and reduces the file size due to compression. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/dwf

### FBX {#FBX}
```
public static final FileType FBX
```


Represents an Autodesk FBX Interchange File (FilmBoX) (.fbx), which is a 3D model format. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/fbx

### DWFX {#DWFX}
```
public static final FileType DWFX
```


Represents a Design Web Format File XPS (.dwfx), which is a compressed format for viewing, reviewing, or printing 2D/3D drawings as an XPS document. It contains graphics and text as part of the design data and reduces the file size due to compression. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/dwfx

### DGN {#DGN}
```
public static final FileType DGN
```


Represents a MicroStation Design File (.dgn), which are drawings created and supported by CAD applications such as MicroStation and Intergraph Interactive Graphics Design System. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/dgn

### PLT {#PLT}
```
public static final FileType PLT
```


Represents a PLT (HPGL) File (.plt), which is a vector-based plotter file introduced by Autodesk, Inc. It contains information for a certain CAD file, and all images are printed using lines instead of dots, ensuring accuracy and precision in production. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/cad/plt

### CF2 {#CF2}
```
public static final FileType CF2
```


Represents a Common File Format File (.cf2). Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/cf2

### OBJ {#OBJ}
```
public static final FileType OBJ
```


Represents a Wavefront 3D Object File (.obj), which is a 3D image file introduced by Wavefront Technologies. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/3d/obj/

### HPG {#HPG}
```
public static final FileType HPG
```


Represents a PLT (HPGL) File (.hpg). It is a file format used for plotter files in the HP Graphics Language (HPGL). Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/hpg

### IGS {#IGS}
```
public static final FileType IGS
```


Represents an Initial Graphics Exchange Specification (IGES) File (.igs).

### VSD {#VSD}
```
public static final FileType VSD
```


Represents a Visio Drawing File (.vsd), which are drawings created with Microsoft Visio application to represent a variety of graphical objects and their interconnections. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vsd

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Represents a Visio Drawing File (.vsdx), which represents the Microsoft Visio file format introduced from Microsoft Office 2013 onwards. It replaced the binary file format (.VSD) supported by earlier versions of Microsoft Visio. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vsdx

### VSS {#VSS}
```
public static final FileType VSS
```


Represents a Visio Stencil File (.vss), which are stencil files created with Microsoft Visio 2007 and earlier. Stencil files provide drawing objects that can be included in a .VSD Visio drawing. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vss

### VSSX {#VSSX}
```
public static final FileType VSSX
```


Represents a Visio Stencil File (.vssx), which are drawing stencils created with Microsoft Visio 2013 and above. The VSSX file format can be opened with Visio 2013 and above. Visio files are known for representing a variety of drawing elements such as shapes, connectors, flowcharts, network layout, UML diagrams, etc. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vssx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Represents a Visio Macro-Enabled Drawing (.vsdm), which are drawing files created with Microsoft Visio application that support macros. VSDM files are OPC/XML drawings that are similar to VSDX, but also provide the capability to run macros when the file is opened. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vsdm

### VST {#VST}
```
public static final FileType VST
```


Represents a Visio Drawing Template (.vst), which are vector image files created with Microsoft Visio. They act as templates for creating further files and contain the default layout and settings used for creating new Visio drawings. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vst

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Represents a Visio Drawing Template (.vstx), which are drawing template files created with Microsoft Visio 2013 and above. These VSTX files provide a starting point for creating Visio drawings saved as .VSDX files, with default layout and settings. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Represents a Visio Macro-Enabled Drawing Template (.vstm), which are template files created with Microsoft Visio that support macros. Files created from VSTM templates can run macros developed in Visual Basic for Applications (VBA) code. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Represents a Visio Macro-Enabled Stencil File (.vssm), which are Microsoft Visio Stencil files that support macros. When a VSSM file is opened, macros can be run to achieve desired formatting and placement of shapes in a diagram. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Represents a Visio Stencil XML File (.vsx), which refers to stencils consisting of drawings and shapes used for creating diagrams in Microsoft Visio. VSX files are saved in XML file format and were supported until Visio 2013. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


Represents a Visio Template XML File (.vtx), which is a Microsoft Visio drawing template saved to disk in XML file format. The template provides basic settings for creating multiple Visio files with the same settings. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vtx

### VDW {#VDW}
```
public static final FileType VDW
```


Represents a Visio Web Drawing (.vdw), which specifies the streams and storages required for rendering a web drawing. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/vdw

### VDX {#VDX}
```
public static final FileType VDX
```


Represents a Visio Drawing XML File (.vdx), which represents any drawing or chart created in Microsoft Visio but saved in XML format with the .VDX extension. A Visio drawing XML file is created in the Visio software developed by Microsoft. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Represents an Open eBook File (.epub), which is an e-book file format that provides a standard digital publication format for publishers and consumers. The format is supported by many e-readers and software applications. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/ebook/epub

### MOBI {#MOBI}
```
public static final FileType MOBI
```


Represents a Mobipocket eBook (.mobi), which is one of the most widely used ebook file formats. The format is an enhancement to the old OEB (Open Ebook Format) format and was used as a proprietary format for Mobipocket Reader. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/ebook/mobi

### MSG {#MSG}
```
public static final FileType MSG
```


Represents an Outlook Mail Message (.msg), which is a file format used by Microsoft Outlook and Exchange to store email messages, contacts, appointments, or other tasks. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/email/msg

### EML {#EML}
```
public static final FileType EML
```


Represents an E-Mail Message (.eml), which represents email messages saved using Outlook and other relevant applications. Almost all email clients support this file format due to its compliance with the RFC-822 Internet Message Format Standard. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/email/eml

### EMLX {#EMLX}
```
public static final FileType EMLX
```


Represents an Apple Mail Message (.emlx), which is implemented and developed by Apple. The Apple Mail application uses the EMLX file format for exporting emails. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/email/emlx

### PST {#PST}
```
public static final FileType PST
```


Represents an Outlook Personal Information Store File (.pst), which represents Outlook Personal Storage Files (also called Personal Storage Table) that store a variety of user information. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/email/pst

### OST {#OST}
```
public static final FileType OST
```


Represents an Outlook Offline Data File (.ost), which represents a user's mailbox data in offline mode on a local machine upon registration with Exchange Server using Microsoft Outlook. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/email/ost

### TIF {#TIF}
```
public static final FileType TIF
```


Represents a Tagged Image File (.tif), which represents raster images that are meant for usage on a variety of devices that comply with this file format standard. It is capable of describing bilevel, grayscale, palette-color, and full-color image data in several color spaces. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/tiff

### TIFF {#TIFF}
```
public static final FileType TIFF
```


Represents a Tagged Image File Format (.tiff), which represents raster images that are meant for usage on a variety of devices that comply with this file format standard. It is capable of describing bilevel, grayscale, palette-color, and full-color image data in several color spaces. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/tiff

### JPG {#JPG}
```
public static final FileType JPG
```


Represents a JPEG Image (.jpg), which is a type of image format that is saved using the method of lossy compression. The output image, as a result of compression, is a trade-off between storage size and image quality. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/jpeg

### JPEG {#JPEG}
```
public static final FileType JPEG
```


Represents a JPEG Image (.jpeg), which is a type of image format that is saved using the method of lossy compression. The output image, as a result of compression, is a trade-off between storage size and image quality. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/jpeg

### PNG {#PNG}
```
public static final FileType PNG
```


Represents a Portable Network Graphic (.png), which is a type of raster image file format that uses lossless compression. This file format was created as a replacement for the Graphics Interchange Format (GIF) and has no copyright limitations. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/png

### GIF {#GIF}
```
public static final FileType GIF
```


Represents a Graphical Interchange Format File (.gif), which is a type of highly compressed image. For each image, GIF typically allows up to 8 bits per pixel, and up to 256 colors are allowed across the image. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/gif

### APNG {#APNG}
```
public static final FileType APNG
```


Represents an Animated Portable Network Graphic (.apng), which is an extension of the PNG format that supports animation. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/apng

### BMP {#BMP}
```
public static final FileType BMP
```


Represents a Bitmap Image File (.bmp), which is used to store bitmap digital images. These images are independent of the graphics adapter and are also called device independent bitmap (DIB) file format. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/bmp

### ICO {#ICO}
```
public static final FileType ICO
```


Represents an Icon File (.ico), which is an image file type used as an icon for the representation of an application on Microsoft Windows. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/ico

### TGA {#TGA}
```
public static final FileType TGA
```


Represents a Truevision TGA (TARGA) file, which is used to store bitmap digital images developed by TRUEVISION. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/tga

### JP_2 {#JP-2}
```
public static final FileType JP_2
```


Represents a JPEG 2000 Core Image File (.jp2), which is an image coding system and state-of-the-art image compression standard. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/jp2

### JPF {#JPF}
```
public static final FileType JPF
```


Represents a JPEG 2000 Image File (.jpf). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/image/jpf

### JPX {#JPX}
```
public static final FileType JPX
```


Represents a JPEG 2000 Image File (.jpx). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/jpx

### JPM {#JPM}
```
public static final FileType JPM
```


Represents a JPEG 2000 Image File (.jpm). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/jpm

### J2C {#J2C}
```
public static final FileType J2C
```


Represents a JPEG 2000 Code InputStream (.j2c). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/j2c

### J2K {#J2K}
```
public static final FileType J2K
```


Represents a JPEG 2000 Code Stream (.j2k), which is an image compressed using wavelet compression instead of DCT compression. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/j2k

### JPC {#JPC}
```
public static final FileType JPC
```


Represents a JPEG 2000 Code Stream (.jpc). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/jpc

### JLS {#JLS}
```
public static final FileType JLS
```


Represents a JPEG-LS (JLS) file (.jls). Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/jls

### DIB {#DIB}
```
public static final FileType DIB
```


Represents a Device Independent Bitmap File (.dib). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/dib

### WMF {#WMF}
```
public static final FileType WMF
```


Represents a Windows Metafile (.wmf), which represents Microsoft Windows Metafile (WMF) for storing vector as well as bitmap-format image data. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/wmf

### WMZ {#WMZ}
```
public static final FileType WMZ
```


Represents a Compressed Windows Metafile (.wmz), which represents Microsoft Windows Metafile (WMF) compressed in GZIP archive for storing vector as well as bitmap-format image data. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/wmz#compressed_windows_metafile

### EMF {#EMF}
```
public static final FileType EMF
```


Represents an Enhanced Windows Metafile (.emf), which represents graphical images device-independently. Metafiles of EMF comprise variable-length records in chronological order that can render the stored image after parsing on any output device. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/emf

### EMZ {#EMZ}
```
public static final FileType EMZ
```


Represents a Windows Compressed Enhanced Metafile (.emz), which represents graphical images device-independently compressed by GZIP. Metafiles of EMF comprise variable-length records in chronological order that can render the stored image after parsing on any output device. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/emz

### WEBP {#WEBP}
```
public static final FileType WEBP
```


Represents a WebP Image (.webp), which is a modern raster web image file format based on lossless and lossy compression. It provides the same image quality while considerably reducing the image size. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/webp

### DNG {#DNG}
```
public static final FileType DNG
```


Represents a Digital Negative Specification (.dng), which is a digital camera image format used for the storage of raw files. It was developed by Adobe in September 2004 and is primarily used for digital photography. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/dng

### CDR {#CDR}
```
public static final FileType CDR
```


Represents a CorelDraw Vector Graphic Drawing (.cdr), which is a vector drawing image file natively created with CorelDRAW for storing digitally encoded and compressed images. A CDR drawing file contains text, lines, shapes, images, colors, and effects for vector representation of image contents. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/cdr

### CMX {#CMX}
```
public static final FileType CMX
```


Represents a Corel Exchange (.cmx), which is a drawing image file that may contain vector graphics as well as bitmap graphics. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/cmx

### DJVU {#DJVU}
```
public static final FileType DJVU
```


Represents a DjVu Image (.djvu), which is a graphics file format intended for scanned documents and books, especially those containing a combination of text, drawings, images, and photographs. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/djvu

### CGM {#CGM}
```
public static final FileType CGM
```


Represents a Computer Graphics Metafile (.cgm), which is a free, platform-independent, international standard metafile format for storing and exchanging vector graphics (2D), raster graphics, and text. CGM uses an object-oriented approach and provides many functions for image production. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/cgm

### PCL {#PCL}
```
public static final FileType PCL
```


Represents a Printer Command Language Document (.pcl). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/pcl

### PSD {#PSD}
```
public static final FileType PSD
```


Represents an Adobe Photoshop Document (.psd), which is Adobe Photoshop's native file format used for graphics designing and development. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/psd

### PSB {#PSB}
```
public static final FileType PSB
```


Represents a Photoshop Large Document Format (.psb), which is used for graphics designing and development in Adobe Photoshop. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/psb

### DCM {#DCM}
```
public static final FileType DCM
```


Represents a DICOM Image (.dcm), which represents a digital image that stores medical information of patients such as MRIs, CT scans, and ultrasound images. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/dcm

### PS {#PS}
```
public static final FileType PS
```


Represents a PostScript File (.ps). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/ps

### EPS {#EPS}
```
public static final FileType EPS
```


Represents an Encapsulated PostScript File (.eps), which describes an Encapsulated PostScript language program that defines the appearance of a single page. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/eps

### ODG {#ODG}
```
public static final FileType ODG
```


Represents an OpenDocument Graphic File (.odg), which is used by Apache OpenOffice's Draw application to store drawing elements as a vector image. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/odg

### FODG {#FODG}
```
public static final FileType FODG
```


Represents a Flat XML ODF Template (.fodg), which is used by Apache OpenOffice's Draw application to store drawing elements as a vector image. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/image/fodg

### SVG {#SVG}
```
public static final FileType SVG
```


Represents a Scalable Vector Graphics File (.svg), which is a Scalar Vector Graphics file that uses XML-based text format for describing the appearance of an image. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/svg

### SVGZ {#SVGZ}
```
public static final FileType SVGZ
```


Represents a Compressed Scalable Vector Graphics File (.svgz), which is a Scalar Vector Graphics file that uses XML-based text format, compressed by GZIP, for describing the appearance of an image. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/svgz

### OTG {#OTG}
```
public static final FileType OTG
```


Represents an OpenDocument Graphic Template (.otg). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/image/otg

### HTM {#HTM}
```
public static final FileType HTM
```


Represents a Hypertext Markup Language File (.htm), which is the extension for web pages created for display in browsers. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/html

### HTML {#HTML}
```
public static final FileType HTML
```


Represents a Hypertext Markup Language File (.html), which is the extension for web pages created for display in browsers. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


Represents an MHTML Web Archive (.mht). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/mht

### NSF {#NSF}
```
public static final FileType NSF
```


Represents a Lotus Notes Database (.nsf). Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/nsf

### MBOX {#MBOX}
```
public static final FileType MBOX
```


Represents an Email Mailbox File (.mbox). Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/mbox

### MHTML {#MHTML}
```
public static final FileType MHTML
```


Represents a MIME HTML File (.mhtml). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/mhtml

### XML {#XML}
```
public static final FileType XML
```


Represents an XML File (.xml). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/web/xml

### ONE {#ONE}
```
public static final FileType ONE
```


Represents a OneNote Document (.one) created by Microsoft OneNote application. OneNote lets you gather information using the application as if you are using your draftpad for taking notes. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


Represents a Portable Document Format File (.pdf), which is a type of document created by Adobe back in the 1990s. The purpose of this file format was to introduce a standard for the representation of documents and other reference material in a format that is independent of application software, hardware, and operating systems. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


Represents an XML Paper Specification File (.xps), which represents page layout files based on XML Paper Specifications created by Microsoft. This format was developed by Microsoft as a replacement for the EMF file format and is similar to the PDF file format, but uses XML in the layout, appearance, and printing information of a document. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/xps

### OXPS {#OXPS}
```
public static final FileType OXPS
```


Represents an OpenXPS File (.oxps). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/oxps

### TEX {#TEX}
```
public static final FileType TEX
```


Represents a LaTeX Source Document (.tex), which is a language that comprises programming as well as mark-up features used to typeset documents. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


Represents a PowerPoint Presentation (.ppt), which represents a PowerPoint file that consists of a collection of slides for displaying as a slideshow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


Represents a PowerPoint Open XML Presentation (.pptx), which are presentation files created with the popular Microsoft PowerPoint application. Unlike the previous version of the presentation file format PPT, which was binary, the PPTX format is based on the Microsoft PowerPoint Open XML presentation file format. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


Represents a PowerPoint Slide Show (.pps), which are created using Microsoft PowerPoint for Slide Show purposes. PPS file reading and creation are supported by Microsoft PowerPoint 97-2003. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


Represents a PowerPoint Open XML Slide Show (.ppsx) files, which are created using Microsoft PowerPoint 2007 and above for Slide Show purposes. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


Represents an OpenDocument Presentation (.odp), which represents a presentation file format used by OpenOffice.org in the OASISOpen standard. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/presentation/odp

### FODP {#FODP}
```
public static final FileType FODP
```


Represents an OpenDocument Presentation (.fodp), which represents OpenDocument Flat XML Presentation. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/fodp

### POT {#POT}
```
public static final FileType POT
```


Represents a PowerPoint Template (.pot), which represents Microsoft PowerPoint template files created by PowerPoint 97-2003 versions. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/presentation/pot

### PPTM {#PPTM}
```
public static final FileType PPTM
```


Represents a PowerPoint Open XML Macro-Enabled Presentation (.pptm), which are macro-enabled presentation files created with Microsoft PowerPoint 2007 or higher versions. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/presentation/pptm

### POTX {#POTX}
```
public static final FileType POTX
```


Represents a PowerPoint Open XML Presentation Template (.potx), which represents Microsoft PowerPoint template presentations created with Microsoft PowerPoint 2007 and above. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/presentation/potx

### POTM {#POTM}
```
public static final FileType POTM
```


Represents a PowerPoint Open XML Macro-Enabled Presentation Template (.potm), which are Microsoft PowerPoint template files with support for macros. POTM files are created with PowerPoint 2007 or above and contain default settings that can be used to create further presentation files. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/presentation/potm

### PPSM {#PPSM}
```
public static final FileType PPSM
```


Represents a PowerPoint Open XML Macro-Enabled Slide (.ppsm), which represents a macro-enabled slide show file format created with Microsoft PowerPoint 2007 or higher. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/presentation/ppsm

### OTP {#OTP}
```
public static final FileType OTP
```


Represents an OpenDocument Presentation Template (.otp), which represents presentation template files created by applications in the OASIS OpenDocument standard format. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


Represents an Excel Spreadsheet (.xls), which represents the Excel Binary File Format. Such files can be created by Microsoft Excel as well as other similar spreadsheet programs such as OpenOffice Calc or Apple Numbers. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### EXCEL_2003_XML {#EXCEL-2003-XML}
```
public static final FileType EXCEL_2003_XML
```


Represents an Excel 2003 XML (SpreadsheetML) (.xml), which represents the Excel Binary File Format. Such files can be created by Microsoft Excel as well as other similar spreadsheet programs such as OpenOffice Calc or Apple Numbers. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### NUMBERS {#NUMBERS}
```
public static final FileType NUMBERS
```


Represents Apple Numbers (.numbers), which represents an Excel-like Binary File Format. Such files can be created by Apple Numbers application. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/numbers

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Represents a Microsoft Excel Open XML Spreadsheet (.xlsx), which is a well-known format for Microsoft Excel documents that was introduced by Microsoft with the release of Microsoft Office 2007. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Represents an Excel Open XML Macro-Enabled Spreadsheet (.xlsm), which is a type of spreadsheet file that supports macros. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Represents an Excel Binary Spreadsheet (.xlsb), which specifies the Excel Binary File Format. It is a collection of records and structures that specify Excel workbook content. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


Represents a Comma Separated Values File (.csv), which represents plain text files that contain records of data with comma-separated values. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


Represents a Tab Separated Values File (.tsv), which represents data separated with tabs in plain text format. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


Represents an OpenDocument Spreadsheet (.ods), which stands for OpenDocument Spreadsheet Document format that is editable by the user. Data is stored inside ODF files in rows and columns. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ods

### FODS {#FODS}
```
public static final FileType FODS
```


Represents an OpenDocument Flat XML Spreadsheet (.fods). It is a spreadsheet document format based on XML used by OpenOffice and LibreOffice. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/fods

### OTS {#OTS}
```
public static final FileType OTS
```


Represents an OpenDocument Spreadsheet Template (.ots). It is a template document format used by OpenOffice and LibreOffice for spreadsheets. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ots

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Represents a Microsoft Excel Add-in (.xlam). It is a file format used by Microsoft Excel to create add-ins with custom functionality. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/xlam

### XLTM {#XLTM}
```
public static final FileType XLTM
```


Represents a Microsoft Excel Macro-Enabled Template (.xltm), which represents files generated by Microsoft Excel as Macro-enabled template files. XLTM files are similar to XLTX in structure except that the latter doesn't support creating template files with macros. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltm

### XLT {#XLT}
```
public static final FileType XLT
```


Represents a Microsoft Excel Template (.xlt), which are template files created with Microsoft Excel, a spreadsheet application that comes as part of the Microsoft Office suite. Microsoft Office 97-2003 supported creating new XLT files as well as opening them. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlt

### XLTX {#XLTX}
```
public static final FileType XLTX
```


Represents an Excel Open XML Spreadsheet Template (.xltx), which represents Microsoft Excel Templates based on the Office OpenXML file format specifications. It is used to create a standard template file that can be utilized to generate XLSX files with the same settings specified in the XLTX file. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltx

### SXC {#SXC}
```
public static final FileType SXC
```


Represents a StarOffice Calc Spreadsheet (.sxc). It is a spreadsheet document created with StarOffice Calc, a spreadsheet program. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/spreadsheet/sxc

### MPP {#MPP}
```
public static final FileType MPP
```


Represents a Microsoft Project File (.mpp), which is a Microsoft Project data file that stores information related to project management in an integrated manner. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/project-management/mpp

### MPT {#MPT}
```
public static final FileType MPT
```


Represents a Microsoft Project Template (.mpt), which contains basic information and structure along with document settings for creating .MPP files. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/project-management/mpt

### MPX {#MPX}
```
public static final FileType MPX
```


Represents a Microsoft Project Exchange file (.mpx), which is an ASCII file format for transferring project information between Microsoft Project (MSP) and other applications that support the MPX file format, such as Primavera Project Planner, Sciforma, and Timerline Precision Estimating. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/project-management/mpx

### AS {#AS}
```
public static final FileType AS
```


Represents an ActionScript File (.as). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/programming/as

### AS_3 {#AS-3}
```
public static final FileType AS_3
```


Represents an ActionScript File (.as3). Learn more about this file format [here][].


[here]: https://datatypes.net/open-as3-files

### ASM {#ASM}
```
public static final FileType ASM
```


Represents an Assembly Language Source Code File (.asm). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/cad/asm

### BAT {#BAT}
```
public static final FileType BAT
```


Represents a DOS Batch File (.bat). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/executable/bat

### C {#C}
```
public static final FileType C
```


Represents a C/C++ Source Code File (.c). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/programming/c

### CC {#CC}
```
public static final FileType CC
```


Represents a C++ Source Code File (.cc). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/programming/cc

### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Represents a CMake File (.cmake). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/programming/cmake

### CPP {#CPP}
```
public static final FileType CPP
```


Represents a C++ Source Code File (.cpp). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/programming/cpp

### CS {#CS}
```
public static final FileType CS
```


Represents a C\# Source Code File (.cs), which is a source code file for the C\# programming language. It was introduced by Microsoft for use with the .NET Framework. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/programming/cs

### VB {#VB}
```
public static final FileType VB
```


Represents a Visual Basic Project Item File (.vb), which is a source code file created in the Visual Basic language. It was created by Microsoft for the development of .NET applications. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/programming/vb

### CSS {#CSS}
```
public static final FileType CSS
```


Represents a Cascading Style Sheet (.css) file. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/css

### CXX {#CXX}
```
public static final FileType CXX
```


Represents a C++ Source Code File (.cxx). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/programming/cxx

### DIFF {#DIFF}
```
public static final FileType DIFF
```


Represents a Patch File (.diff). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/programming/diff

### ERB {#ERB}
```
public static final FileType ERB
```


Represents a Ruby ERB Script (.erb). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/programming/erb

### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Represents a Groovy Source Code File (.groovy). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/programming/groovy

### H {#H}
```
public static final FileType H
```


Represents a C/C++/Objective-C Header File (.h). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/programming/h

### HAML {#HAML}
```
public static final FileType HAML
```


Represents a Haml Source Code File (.haml). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/programming/haml

### HH {#HH}
```
public static final FileType HH
```


Represents a C++ Header File (.hh). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/programming/hh

### JAVA {#JAVA}
```
public static final FileType JAVA
```


Represents a Java Source Code File (.java). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/programming/java

### JS {#JS}
```
public static final FileType JS
```


Represents a JavaScript File (.js). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/web/js

### JSON {#JSON}
```
public static final FileType JSON
```


Represents a JavaScript Object Notation File (.json). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/web/json

### LESS {#LESS}
```
public static final FileType LESS
```


Represents a LESS Style Sheet (.less) file. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/web/less

### LOG {#LOG}
```
public static final FileType LOG
```


Represents a Log File (.log). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/database/log

### M {#M}
```
public static final FileType M
```


Represents an Objective-C Implementation File (.m). Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/m

### MAKE {#MAKE}
```
public static final FileType MAKE
```


Represents an Xcode Makefile Script (.make). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/programming/make

### MD {#MD}
```
public static final FileType MD
```


Represents a Markdown Documentation File (.md). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/word-processing/md

### ML {#ML}
```
public static final FileType ML
```


Represents an ML Source Code File (.ml). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/programming/ml

### MM {#MM}
```
public static final FileType MM
```


Represents an Objective-C++ Source File (.mm). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/programming/mm

### PHP {#PHP}
```
public static final FileType PHP
```


Represents a PHP Source Code File (.php). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/programming/php

### PL {#PL}
```
public static final FileType PL
```


Represents a Perl Script (.pl). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/programming/pl

### PROPERTIES {#PROPERTIES}
```
public static final FileType PROPERTIES
```


Represents a Java Properties File (.properties). Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/properties

### PY {#PY}
```
public static final FileType PY
```


Represents a Python Script (.py). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/programming/py

### RB {#RB}
```
public static final FileType RB
```


Represents a Ruby Source Code (.rb) file. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/programming/rb

### RST {#RST}
```
public static final FileType RST
```


Represents a reStructuredText File (.rst). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/programming/rst

### SASS {#SASS}
```
public static final FileType SASS
```


Represents a Syntactically Awesome StyleSheets File (.sass). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/web/sass

### SCALA {#SCALA}
```
public static final FileType SCALA
```


Represents a Scala Source Code File (.scala). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/programming/scala

### SCM {#SCM}
```
public static final FileType SCM
```


Represents a Scheme Source Code File (.scm). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/programming/scm

### SCRIPT {#SCRIPT}
```
public static final FileType SCRIPT
```


Represents a Generic Script File (.script). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/programming/script

### SH {#SH}
```
public static final FileType SH
```


Represents a Bash Shell Script (.sh). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/cs/programming/sh

### SML {#SML}
```
public static final FileType SML
```


Represents a Standard ML Source Code File (.sml). Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/sml

### SQL {#SQL}
```
public static final FileType SQL
```


Represents a Structured Query Language Data File (.sql). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/database/sql

### VIM {#VIM}
```
public static final FileType VIM
```


Represents a Vim Settings File (.vim). Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/vim

### YAML {#YAML}
```
public static final FileType YAML
```


Represents a YAML Document (.yaml). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/programming/yaml

### DOC {#DOC}
```
public static final FileType DOC
```


Represents a Microsoft Word Document (.doc) file. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Represents a Microsoft Word Open XML Document (.docx) file. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/word-processing/docx

### CHM {#CHM}
```
public static final FileType CHM
```


Represents a Microsoft Compiled HTML Help File (.chm). Learn more about this file format [here][].


[here]: https://docs.fileformat.com/web/chm

### DOCM {#DOCM}
```
public static final FileType DOCM
```


Represents a Word Open XML Macro-Enabled Document (.docm) file. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


Represents a Word Document Template (.dot) file. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Represents a Word Open XML Document Template (.dotx) file. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Represents a Word Open XML Macro-Enabled Document Template (.dotm) file. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


Represents a Rich Text Format File (.rtf). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


Represents a Plain Text File (.txt). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/word-processing/txt

### ODT {#ODT}
```
public static final FileType ODT
```


Represents an OpenDocument Text Document (.odt). Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


Represents an OpenDocument Document Template (.ott). It is a template document generated in compliance with the OASIS' OpenDocument standard format. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/word-processing/ott

### VCF {#VCF}
```
public static final FileType VCF
```


Represents a vCard File (.vcf), which is a digital file format for storing contact information. It is widely used for data interchange among popular information exchange applications. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/email/vcf

### AI {#AI}
```
public static final FileType AI
```


Represents an Adobe Illustrator file (.ai), which is a file format for Adobe Illustrator drawings. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/image/ai

### PSM1 {#PSM1}
```
public static final FileType PSM1
```


Represents a PowerShell script module file (.psm1). It is a file format for PowerShell module scripts. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/psm1

### PS1 {#PS1}
```
public static final FileType PS1
```


Represents a PowerShell script file (.ps1). It is a file format for Windows PowerShell Cmdlet files. Learn more about this file format [here][].


[here]: https://fileinfo.com/extension/ps1

### PSD1 {#PSD1}
```
public static final FileType PSD1
```


Represents a PowerShell script module manifest file (.psd1). It is a file format for PowerShell module manifest scripts. Learn more about this file format [here][].


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


Maps a file extension to a file type.

This method takes a file extension, with or without the period ".", and returns the corresponding file type if it is supported. If the file type is not supported, it returns the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | The file extension with or without the period ".". |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromFilePath(String filePath) {#fromFilePath-java.lang.String-}
```
public static FileType fromFilePath(String filePath)
```


Extracts the file extension from a file name or file path and maps it to a file type.

If the file type is supported, the method returns the corresponding  FileType , otherwise it returns the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file name or file path. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromMediaType(String mediaType) {#fromMediaType-java.lang.String-}
```
public static FileType fromMediaType(String mediaType)
```


Maps a file media type to a file type. For example, 'application/pdf' will be mapped to [PDF](../../com.groupdocs.viewer/filetype\#PDF).

This method takes a file media type as input and maps it to the corresponding  FileType . If the media type is supported, the method returns the corresponding file type. If the media type is not supported, it returns the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mediaType | java.lang.String | The file media type, e.g., 'application/pdf'. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if found, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream stream)
```


Detects the file type by reading the file signature.

This method takes an input stream representing a file and tries to detect its file type by analyzing the file signature. The file signature is a unique sequence of bytes at the beginning of the file that indicates its file type. The method reads the file signature from the input stream and matches it against known file signatures of supported file types. If a match is found, the method returns the corresponding file type. If no match is found, it returns the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The input stream representing the file. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password) {#fromStream-java.io.InputStream-java.lang.String-}
```
public static FileType fromStream(InputStream stream, String password)
```


Detects the file type by reading the file signature.

This method analyzes the file signature, which is a unique sequence of bytes at the beginning of the file, to determine the file type. It reads the file signature from the provided input stream and matches it against known file signatures of supported file types. If a match is found, the method returns the corresponding file type. If no match is found, it returns the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.

If the file is encrypted and requires a password to open, the password should be provided as a parameter to this method. The password will be used to decrypt the file and analyze its signature for determining the file type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The input stream representing the file. |
| password | java.lang.String | The password to open the file. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, ILogger logger) {#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, ILogger logger)
```


Detects the file type by reading the file signature.

This method analyzes the file signature, which is a unique sequence of bytes at the beginning of the file, to determine the file type. It reads the file signature from the provided input stream and matches it against known file signatures of supported file types. If a match is found, the method returns the corresponding file type. If no match is found, it returns the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.

A logger can be provided to log any relevant information or errors during the file type detection process. The logger should implement the ILogger interface. If no logger is provided, the detection process will not produce any log output.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The input stream representing the file. |
| logger | com.groupdocs.foundation.logging.ILogger | The logger for logging information or errors. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password, ILogger logger) {#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, String password, ILogger logger)
```


Detects the file type by reading the file signature.

This method analyzes the file signature, which is a unique sequence of bytes at the beginning of the file, to determine the file type. It reads the file signature from the provided input stream and matches it against known file signatures of supported file types. If a match is found, the method returns the corresponding file type. If no match is found, it returns the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.

A password can be provided if the file is encrypted or protected. The password will be used to open the file before analyzing the file signature. If the file does not require a password, this parameter can be set to null.

A logger can be provided to log any relevant information or errors during the file type detection process. The logger should implement the ILogger interface. If no logger is provided, the detection process will not produce any log output.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The input stream representing the file. |
| password | java.lang.String | The password to open the file. |
| logger | com.groupdocs.foundation.logging.ILogger | The logger for logging information or errors. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Retrieves the supported file types.

This method returns a sequence of all the supported file types by the system. The file types represent various document formats that can be processed or recognized by the system.

 **Learn more**

 *  Learn more about the supported document formats: [Full list of supported file formats][]


[Full list of supported file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/

**Returns:**
java.util.List<com.groupdocs.viewer.FileType> - a sequence of supported file types.
### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Gets the name of the file format, e.g., "Microsoft Word Document".

**Returns:**
java.lang.String - the name of the file format.
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Gets the file extension suffix (including the period "."), e.g., ".doc".

**Returns:**
java.lang.String - the file extension suffix.
### toString() {#toString--}
```
public String toString()
```


Returns a string representation of the current object.

**Returns:**
java.lang.String - a string representation of the current object.
