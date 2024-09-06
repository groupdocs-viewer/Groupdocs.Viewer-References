---
title: FileType
second_title: GroupDocs.Viewer for Python via .NET API Reference
description: 
type: docs
weight: 10
url: /python-net/groupdocs.viewer/filetype/
---

## FileType class

Represents file type. Provides methods to obtain list of all file types supported by GroupDocs.Viewer.

The FileType type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|FileType()|Initializes new instance of [FileType](/viewer/python-net/groupdocs.viewer/filetype/) class.|
|FileType(file_format, extension)|Initializes a new instance of the FileType class|
## Properties
| Name | Description |
| :- | :- |
|file_format|File type name e.g. "Microsoft Word Document".|
|extension|Filename suffix (including the period ".") e.g. ".doc".|
|UNKNOWN|Represents unknown file type.|
|ZIP|Zipped File (.zip) represents archives that can hold one or more files or directories. <br/>            Learn more about this file format|
|TAR|Consolidated Unix File Archive (.tar) are archives created with Unix-based utility for collecting one or more files. <br/>            Learn more about this file format|
|XZ|XZ file (.xz) is archive compressed a high-ratio compression algorithm based on the LZMA algorithm. <br/>            Learn more about this file format|
|TXZ|Consolidated Unix File Archive (.txz, .tar.xz) are archives created with Unix-based utility for collecting one or more files. <br/>            Learn more about this file format|
|TARXZ|Consolidated Unix File Archive (.txz, .tar.xz) are archives created with Unix-based utility for collecting one or more files. <br/>            Learn more about this file format|
|TGZ|Consolidated Unix File Archive (.tgz, .tar.gz) are archives created with Unix-based utility for collecting one or more files. <br/>            Learn more about this file format|
|TARGZ|Consolidated Unix File Archive (.tgz, .tar.gz) are archives created with Unix-based utility for collecting one or more files. <br/>            Learn more about this file format|
|BZ2|Bzip2 Compressed File (.bz2) are compressed files generated using the BZIP2 open source compression method, mostly on UNIX or Linux system. <br/>            Learn more about this file format|
|RAR|Roshal ARchive (.rar) are compressed files generated using the RAR (WINRAR) compression method. <br/>            Learn more about this file format|
|GZ|Gnu Zipped File (.gz) are compressed files created with gzip compression application. It can contain multiple compressed files and is commonly used on UNIX and Linux systems.<br/>            Learn more about this file format|
|GZIP|Gnu Zipped File (.gzip) was introduced as a free utility for replacing the Compress program used in Unix systems. Such files can be opened and extracted with a several applications such as WinZip which is available on both Windows and MacOS. <br/>            Learn more about this file format|
|SEVEN_ZIP|7Zip (.7z, .7zip) is free open source archiver with LZMA and LZMA2 compression.<br/>            Learn more about this file format|
|CPIO|Cpio is a general file archiver utility and its associated file format. It is primarily installed on Unix-like computer operating systems.<br/>            Learn more about this file format|
|DXF|Drawing Exchange Format File (.dxf) is a tagged data representation of AutoCAD drawing file.<br/>            Learn more about this file format|
|DWG|AutoCAD Drawing Database File (.dwg) represents proprietary binary files used for containing 2D and 3D design data. Like DXF, which are ASCII files, DWG represent the binary file format for CAD (Computer Aided Design) drawings. <br/>            Learn more about this file format|
|DWT|AutoCAD Drawing Template (.dwt) is an AutoCAD drawing template file that is used as starter for creating drawings that can be saved as DWG files.<br/>            Learn more about this file format|
|STL|Stereolithography File (.stl) is an interchangeable file format that represents 3-dimensional surface geometry. The file format finds its usage in several fields such as rapid prototyping, 3D printing and computer-aided manufacturing.<br/>            Learn more about this file format|
|IFC|Industry Foundation Classes File (.ifc) is a file format that establishes international standards to import and export building objects and their properties. This file format provides interoperability between different software applications. <br/>            Learn more about this file format|
|DWF|Design Web Format File (.dwf) represents 2D/3D drawing in compressed format for viewing, reviewing or printing design files. It contains graphics and text as part of design data and reduce the size of the file due to its compressed format.<br/>            Learn more about this file format|
|FBX|Autodesk FBX Interchange File (FilmBoX) (.fbx) represents 3D model format.<br/>            Learn more about this file format|
|DWFX|Design Web Format File XPS (.dwfx) represents 2D/3D drawing as XPS document in compressed format for viewing, reviewing or printing design files. It contains graphics and text as part of design data and reduce the size of the file due to its compressed format.<br/>            Learn more about this file format|
|DGN|MicroStation Design File (.dgn) are drawings created by and supported by CAD applications such as MicroStation and Intergraph Interactive Graphics Design System.<br/>            Learn more about this file format|
|PLT|PLT (HPGL) (.plt) is a vector-based plotter file introduced by Autodesk, Inc. and contains information for a certain CAD file. Plotting details require accuracy and precision in production, and usage of PLT file guarantee this as all images are printed using lines instead of dots. <br/>            Learn more about this file format|
|CF2|Common File Format File<br/>            Learn more about this file format|
|OBJ|Wavefront 3D Object File (.obj) is 3D image file introduced by Wavefront Technologies<br/>            Learn more about this file format|
|HPG|PLT (HPGL) (.hpg)|
|IGS|Initial Graphics Exchange Specification (IGES) (.igs)|
|VSD|Visio Drawing File (.vsd) are drawings created with Microsoft Visio application to represent variety of graphical objects and the interconnection between these.<br/>            Learn more about this file format|
|VSDX|Visio Drawing (.vsdx) represents Microsoft Visio file format introduced from Microsoft Office 2013 onwards. It was developed to replace the binary file format, .VSD, which is supported by earlier versions of Microsoft Visio.<br/>            Learn more about this file format|
|VSS|Visio Stencil File(.vss) are stencil files created with Microsoft Visio 2007 and earlier. Stencil files provide drawing objects that can be included in a .VSD Visio drawing.<br/>            Learn more about this file format|
|VSSX|Visio Stencil File (.vssx) are drawing stencils created with Microsoft Visio 2013 and above. The VSSX file format can be opened with Visio 2013 and above. Visio files are known for representation of a variety of drawing elements such as collection of shapes, connectors, flowcharts, network layout, UML diagrams, <br/>            Learn more about this file format|
|VSDM|Visio Macro-Enabled Drawing (.vsdm) are drawing files created with Microsoft Visio application that supports macros. VSDM files are OPC/XML drawings that are similar to VSDX, but also provide the capability to run macros when the file is opened. <br/>            Learn more about this file format|
|VST|Visio Drawing Template (.vst) are vector image files created with Microsoft Visio and act as template for creating further files. These template files are in binary file format and contain the default layout and settings that are utilized for creation of new Visio drawings.<br/>            Learn more about this file format|
|VSTX|Visio Drawing Template (.vstx) are drawing template files created with Microsoft Visio 2013 and above. These VSTX files provide starting point for creating Visio drawings, saved as .VSDX files, with default layout and settings. <br/>            Learn more about this file format|
|VSTM|Visio Macro-Enabled Drawing Template (.vstm) are template files created with Microsoft Visio that support macros. Unlike VSDX files, files created from VSTM templates can run macros that are developed in Visual Basic for Applications (VBA)  code. <br/>            Learn more about this file format|
|VSSM|Visio Macro-Enabled Stencil File (.vssm) are Microsoft Visio Stencil files that support provide support for macros. A VSSM file when opened allows to run the macros to achieve desired formatting and placement of shapes in a diagram.<br/>            Learn more about this file format|
|VSX|Visio Stencil XML File (.vsx) refers to stencils that consist of drawings and shapes that are used for creating diagrams in Microsoft Visio. VSX files are saved in XML file format and was supported till Visio 2013.<br/>            Learn more about this file format|
|VTX|Visio Template XML File (.vtx) is a Microsoft Visio drawing template that is saved to disc in XML file format. The template is aimed to provide a file with basic settings that can be used to create multiple Visio files of the same settings.<br/>            Learn more about this file format|
|VDW|Visio Web Drawing (.vdw) represents file format that specifies the streams and storages required for rendering a Web drawing. <br/>            Learn more about this file format|
|VDX|Visio Drawing XML File (.vdx) represents any drawing or chart created in Microsoft Visio, but saved in XML format have .VDX extension. A Visio drawing XML file is created in Visio software, which is developed by Microsoft.<br/>            Learn more about this file format|
|EPUB|Open eBook File (.epub) is an e-book file format that provide a standard digital publication format for publishers and consumers. The format has been so common by now that it is supported by many e-readers and software applications.<br/>            Learn more about this file format|
|MOBI|Mobipocket eBook (.mobi) is one of the most widely used ebook file format. The format is an enhancement to the old OEB (Open Ebook Format) format and was used as proprietary format for Mobipocket Reader.<br/>            Learn more about this file format|
|AZW3|Amazon Kindle Format 8 (KF8) ebook is the digital file format developed for Amazon Kindle devices. The format is an enhancement to older AZW files and is used on Kindle Fire devices only with backward compatibility for the ancestor file format i.e. MOBI and AZW.<br/>            Learn more about this file format|
|MSG|Outlook Mail Message (.msg) is a file format used by Microsoft Outlook and Exchange to store email messages, contact, appointment, or other tasks.<br/>            Learn more about this file format|
|EML|E-Mail Message (.eml) represents email messages saved using Outlook and other relevant applications. Almost all emailing clients support this file format for its compliance with RFC-822 Internet Message Format Standard. <br/>            Learn more about this file format|
|NSF|Lotus Notes Database (.nsf)<br/>            Learn more about this file format|
|MBOX|Email Mailbox File (.mbox)<br/>            Learn more about this file format|
|EMLX|Apple Mail Message (.emlx) is implemented and developed by Apple. The Apple Mail application uses the EMLX file format for exporting the emails.<br/>            Learn more about this file format|
|PST|Outlook Personal Information Store File (.pst) represents Outlook Personal Storage Files (also called Personal Storage Table) that store variety of user information.<br/>            Learn more about this file format|
|OST|Outlook Offline Data File (.ost) represents user's mailbox data in offline mode on local machine upon registration with Exchange Server using Microsoft Outlook. <br/>            Learn more about this file format|
|TIF|Tagged Image File (.tif) represents raster images that are meant for usage on a variety of devices that comply with this file format standard. It is capable of describing bilevel, grayscale, palette-color and full-color image data in several color spaces. <br/>            Learn more about this file format|
|TIFF|Tagged Image File Format (.tiff) represents raster images that are meant for usage on a variety of devices that comply with this file format standard. It is capable of describing bilevel, grayscale, palette-color and full-color image data in several color spaces. <br/>            Learn more about this file format|
|JPG|JPEG Image (.jpg) is a type of image format that is saved using the method of lossy compression. The output image, as result of compression, is a trade-off between storage size and image quality.<br/>            Learn more about this file format|
|JPEG|JPEG Image (.jpeg) is a type of image format that is saved using the method of lossy compression. The output image, as result of compression, is a trade-off between storage size and image quality.<br/>            Learn more about this file format|
|PNG|Portable Network Graphic (.png) is a type of raster image file format that use loseless compression. This file format was created as a replacement of Graphics Interchange Format (GIF) and has no copyright limitations.<br/>            Learn more about this file format|
|GIF|Graphical Interchange Format File (.gif) is a type of highly compressed image. For each image GIF typically allow up to 8 bits per pixel and up to 256 colours are allowed across the image. <br/>            Learn more about this file format|
|APNG|Animated Portable Network Graphic (.apng) is extension of  PNG format that support animation.<br/>            Learn more about this file format|
|BMP|Bitmap Image File (.bmp) is used to store bitmap digital images. These images are independent of graphics adapter and are also called device independent bitmap (DIB) file format.<br/>            Learn more about this file format|
|TGA|Truevision TGA (Truevision Advanced Raster Adapter - TARGA) is used to store bitmap digital images developed by TRUEVISION.<br/>            Learn more about this file format|
|ICO|Icon File (.ico) are image file types used as icon for representation of an application on Microsoft Windows.<br/>            Learn more about this file format|
|JP2|JPEG 2000 Core Image File (.jp2) is an image coding system and state-of-the-art image compression standard. <br/>            Learn more about this file format|
|JPF|JPEG 2000 Image File (.jpf)|
|JPX|JPEG 2000 Image File (.jpx)|
|JPM|JPEG 2000 Image File (.jpm)|
|J2C|JPEG 2000 Code Stream (.j2c)|
|J2K|JPEG 2000 Code Stream (.j2k) is an image that is compressed using the wavelet compression instead of DCT compression.<br/>            Learn more about this file format|
|JPC|JPEG 2000 Code Stream (.jpc)|
|JLS|JPEG-LS (JLS) (.jls)|
|DIB|Device Independent Bitmap File (.dib)|
|WMF|Windows Metafile (.wmf) represents Microsoft Windows Metafile (WMF) for storing vector as well as bitmap-format images data.<br/>            Learn more about this file format|
|WMZ|Compressed Windows Metafile (.wmz) represents Microsoft Windows Metafile (WMF) compressed in GZIP archvive - for storing vector as well as bitmap-format images data.<br/>            Learn more about this file format|
|EMF|Enhanced Windows Metafile (.emf) represents graphical images device-independently. Metafiles of EMF comprises of variable-length records in chronological order that can render the stored image after parsing on any output device.<br/>            Learn more about this file format|
|EMZ|Enhanced Windows Metafile compressed (.emz) represents graphical images device-independently compressed by GZIP. Metafiles of EMF comprises of variable-length records in chronological order that can render the stored image after parsing on any output device.<br/>            Learn more about this file format|
|WEBP|WebP Image (.webp) is a modern raster web image file format that is based on lossless and lossy compression. It provides same image quality while considerably reducing the image size. <br/>            Learn more about this file format|
|DNG|Digital Negative Specification (.dng) is a digital camera image format used for the storage of raw files. It has been developed by Adobe in September 2004. It was basically developed for digital photography. <br/>            Learn more about this file format|
|CDR|CorelDraw Vector Graphic Drawing (.cdr) is a vector drawing image file that is natively created with CorelDRAW for storing digital image encoded and compressed. Such a drawing file contains text, lines, shapes, images, colours and effects for vector representation of image contents. <br/>            Learn more about this file format|
|CMX|Corel Exchange (.cmx) is a drawing image file that may contain vector graphics as well as bitmap graphics. <br/>            Learn more about this file format|
|DJVU|DjVu Image (.djvu) is a graphics file format intended for scanned documents and books especially those which contain the combination of text, drawings, images and photographs.<br/>            Learn more about this file format|
|CGM|Computer Graphics Metafile (.cgm) is a free, platform-independent, international standard metafile format for storing and exchanging of vector graphics (2D), raster graphics, and text. CGM uses object-oriented approach and many function provisions for image production. <br/>            Learn more about this file format|
|PCL|Printer Command Language Document (.pcl)|
|PSD|Adobe Photoshop Document (.psd) represents Adobe Photoshop's native file format used for graphics designing and development. <br/>            Learn more about this file format|
|PSB|Photoshop Large Document Format (.psb) represents Photoshop Large Document Format used for graphics designing and development. <br/>            Learn more about this file format|
|DCM|DICOM Image (.dcm) represents digital image which stores medical information of patients such as MRIs, CT scans and ultrasound images. <br/>            Learn more about this file format|
|PS|PostScript File (.ps)|
|EPS|Encapsulated PostScript File (.eps) describes an Encapsulated PostScript language program that describes the appearance of a single page. <br/>            Learn more about this file format|
|ODG|OpenDocument Graphic File (.odg) is used by Apache OpenOffice's Draw application to store drawing elements as a vector image.<br/>            Learn more about this file format|
|FODG|Flat XML ODF Template (.fodg) is used by Apache OpenOffice's Draw application to store drawing elements as a vector image.<br/>            Learn more about this file format|
|SVG|Scalable Vector Graphics File (.svg) is a Scalar Vector Graphics file that uses XML based text format for describing the appearance of an image. <br/>            Learn more about this file format|
|SVGZ|Scalable Vector Graphics File (.svgz) is a Scalar Vector Graphics file that uses XML based text format, compressed by GZIP for describing the appearance of an image. <br/>            Learn more about this file format|
|OTG|OpenDocument Graphic Template (.otg)|
|HTM|Hypertext Markup Language File (.htm) is the extension for web pages created for display in browsers. <br/>            Learn more about this file format|
|HTML|Hypertext Markup Language File (.html) is the extension for web pages created for display in browsers. <br/>            Learn more about this file format|
|MHT|MHTML Web Archive (.mht)|
|MHTML|MIME HTML File (.mhtml)|
|XML|XML File (.xml)|
|ONE|OneNote Document (.one) is created by Microsoft OneNote application. OneNote lets you gather information using the application as if you are using your draftpad for taking notes.<br/>            Learn more about this file format|
|PDF|Portable Document Format File (.pdf) is a type of document created by Adobe back in 1990s. The purpose of this file format was to introduce a standard for representation of documents and other reference material in a format that is independent of application software, hardware as well as Operating System. <br/>            Learn more about this file format|
|XPS|XML Paper Specification File (.xps) represents page layout files that are based on XML Paper Specifications created by Microsoft. This format was developed by Microsoft as a replacement of EMF file format and is similar to PDF file format, but uses XML in layout, appearance, and printing information of a document.<br/>            Learn more about this file format|
|OXPS|OpenXPS File (.oxps)|
|TEX|LaTeX Source Document (.tex) is a language that comprises of programming as well as mark-up features, used to typeset documents. <br/>            Learn more about this file format|
|PPT|PowerPoint Presentation (.ppt) represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003.<br/>            Learn more about this file format|
|PPTX|PowerPoint Open XML Presentation (.pptx) are presentation files created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. <br/>            Learn more about this file format|
|PPS|PowerPoint Slide Show (.pps) are created using Microsoft PowerPoint for Slide Show purpose. PPS file reading and creation is supported by Microsoft PowerPoint 97-2003.<br/>            Learn more about this file format|
|PPSX|PowerPoint Open XML Slide Show (.ppsx) files are created using Microsoft PowerPoint 2007 and above for Slide Show purpose.<br/>            Learn more about this file format|
|ODP|OpenDocument Presentation (.odp) represents presentation file format used by OpenOffice.org in the OASISOpen standard.<br/>            Learn more about this file format|
|FODP|OpenDocument Presentation (.fodp) represents OpenDocument Flat XML Presentation.<br/>            Learn more about this file format|
|POT|PowerPoint Template (.pot) represents Microsoft PowerPoint template files created by PowerPoint 97-2003 versions. <br/>            Learn more about this file format|
|PPTM|PowerPoint Open XML Macro-Enabled Presentation are Macro-enabled Presentation files that are created with Microsoft PowerPoint 2007 or higher versions.<br/>            Learn more about this file format|
|POTX|PowerPoint Open XML Presentation Template (.potx) represents Microsoft PowerPoint template presentations that are created with Microsoft PowerPoint 2007 and above.<br/>            Learn more about this file format|
|POTM|PowerPoint Open XML Macro-Enabled Presentation Template (.potm) are Microsoft PowerPoint template files with support for Macros. POTM files are created with PowerPoint 2007 or above and contains default settings that can be used to create further presentation files.<br/>            Learn more about this file format|
|PPSM|PowerPoint Open XML Macro-Enabled Slide (.ppsm) represents Macro-enabled Slide Show file format created with Microsoft PowerPoint 2007 or higher.<br/>            Learn more about this file format|
|OTP|OpenDocument Presentation Template (.otp) represents presentation template files created by applications in OASIS OpenDocument standard format.<br/>            Learn more about this file format|
|XLS|Excel Spreadsheet (.xls) represents Excel Binary File Format. Such files can be created by Microsoft Excel as well as other similar spreadsheet programs such as OpenOffice Calc or Apple Numbers. <br/>            Learn more about this file format|
|EXCEL_2003XML|Excel 2003 XML (SpreadsheetML) represents Excel Binary File Format. Such files can be created by Microsoft Excel as well as other similar spreadsheet programs such as OpenOffice Calc or Apple Numbers. <br/>            Learn more about this file format|
|NUMBERS|Apple numbers represents Excel like Binary File Format. Such files can be created by Apple numbers application. <br/>            Learn more about this file format|
|XLSX|Microsoft Excel Open XML Spreadsheet (.xlsx) is a well-known format for Microsoft Excel documents that was introduced by Microsoft with the release of Microsoft Office 2007. <br/>            Learn more about this file format|
|XLSM|Excel Open XML Macro-Enabled Spreadsheet (.xlsm) is a type of Spreasheet files that support macros.<br/>            Learn more about this file format|
|XLSB|Excel Binary Spreadsheet (.xlsb) specifies the Excel Binary File Format, which is a collection of records and structures that specify Excel workbook content. <br/>            Learn more about this file format|
|CSV|Comma Separated Values File (.csv) represents plain text files that contain records of data with comma separated values.<br/>            Learn more about this file format|
|TSV|Tab Separated Values File (.tsv) represents data separated with tabs in plain text format. <br/>            Learn more about this file format|
|ODS|OpenDocument Spreadsheet (.ods) stands for OpenDocument Spreadsheet Document format that are editable by user. Data is stored inside ODF file into rows and columns.<br/>            Learn more about this file format|
|FODS|OpenDocument Flat XML Spreadsheet (.fods)|
|OTS|OpenDocument Spreadsheet Template (.ots)|
|XLAM|Microsoft Excel Add-in (.xlam)|
|XLTM|Microsoft Excel Macro-Enabled Template (.xltm) represents files that are generated by Microsoft Excel as Macro-enabled template files. XLTM files are similar to XLTX in structure other than that the later doesn't support creating template files with macros. <br/>            Learn more about this file format|
|XLT|Microsoft Excel Template (.xlt) are template files created with Microsoft Excel which is a spreadsheet application which comes as part of Microsoft Office suite.  Microsoft Office 97-2003 supported creating new XLT files as well as opening these. <br/>            Learn more about this file format|
|XLTX|Excel Open XML Spreadsheet Template	(.xltx) represents Microsoft Excel Template that are based on the Office OpenXML file format specifications. It is used to create a standard template file that can be utilized to generate XLSX files that exhibit the same settings as specified in the XLTX file.<br/>            Learn more about this file format|
|SXC|StarOffice Calc Spreadsheet (.sxc)|
|MPP|Microsoft Project File (.mpp) is Microsoft Project data file that stores information related to project management in an integrated manner.<br/>            Learn more about this file format|
|MPT|Microsoft Project Template (.mpt) contains basic information and structure along with document settings for creating .MPP files.<br/>            Learn more about this file format|
|MPX|Microsoft Project Exchange file (.mpx) is an ASCII file format for transferring of project information between Microsoft Project (MSP) and other applications that support the MPX file format such as Primavera Project Planner, Sciforma and Timerline Precision Estimating.<br/>            Learn more about this file format|
|AS|ActionScript File (.as)|
|AS3|ActionScript File (.as)|
|ASM|Assembly Language Source Code File (.asm)|
|BAT|DOS Batch File (.bat)|
|C|C/C++ Source Code File (.c)|
|CC|C++ Source Code File (.cc)|
|CMAKE|CMake File (.cmake)|
|CPP|C++ Source Code File (.cpp)|
|CS|C# Source Code File (.cs) is a source code file for C# programming language. Introduced by Microsoft for use with the .NET Framework.<br/>            Learn more about this file format|
|VB|Visual Basic Project Item File (.vb) is a source code file created in Visual Basic language that was created by Microsoft for development of .NET applications.<br/>            Learn more about this file format|
|CSS|Cascading Style Sheet (.css)|
|CXX|C++ Source Code File (.cxx)|
|DIFF|Patch File (.diff)|
|ERB|Ruby ERB Script (.erb)|
|GROOVY|Groovy Source Code File (.groovy)|
|H|C/C++/Objective-C Header File (.h)|
|HAML|Haml Source Code File (.haml)|
|HH|C++ Header File (.hh)|
|JAVA|Java Source Code File (.java)|
|JS|JavaScript File (.js)|
|JSON|JavaScript Object Notation File (.json)|
|LESS|LESS Style Sheet (.less)|
|LOG|Log File (.log)|
|M|Objective-C Implementation File (.m)|
|MAKE|Xcode Makefile Script (.make)|
|MD|Markdown Documentation File (.md)|
|ML|ML Source Code File (.ml)|
|MM|Objective-C++ Source File (.mm)|
|PHP|PHP Source Code File (.php)|
|PL|Perl Script (.pl)|
|PROPERTIES|Java Properties File (.properties)|
|PY|Python Script (.py)|
|RB|Ruby Source Code (.rb)|
|RST|reStructuredText File (.rst)|
|SASS|Syntactically Awesome StyleSheets File (.sass)|
|SCALA|Scala Source Code File (.scala)|
|SCM|Scheme Source Code File (.scm)|
|SCRIPT|Generic Script File (.script)|
|SH|Bash Shell Script (.sh)|
|SML|Standard ML Source Code File (.sml)|
|SQL|Structured Query Language Data File (.sql)|
|VIM|Vim Settings File (.vim)|
|YAML|YAML Document (.yaml)|
|DOC|Microsoft Word Document (.doc) represents documents generated by Microsoft Word or other word processing documents in binary file format.<br/>            Learn more about this file format|
|DOCX|Microsoft Word Open XML Document (.docx) is a well-known format for Microsoft Word documents. Introduced from 2007 with the release of Microsoft Office 2007, the structure of this new Document format was changed from plain binary to a combination of XML and binary files. <br/>            Learn more about this file format|
|CHM|Microsoft Compiled HTML Help File (.chm) is a well-known format for HELP (documentation to some application) documents.<br/>            Learn more about this file format|
|DOCM|Word Open XML Macro-Enabled Document (.docm) is a Microsoft Word 2007 or higher generated documents with the ability to run macros.<br/>            Learn more about this file format|
|DOT|Word Document Template (.dot) are template files created by Microsoft Word to have pre-formatted settings for generation of further DOC or DOCX files. <br/>            Learn more about this file format|
|DOTX|Word Open XML Document Template (.dotx) are template files created by Microsoft Word to have pre-formatted settings for generation of further DOCX files. <br/>            Learn more about this file format|
|DOTM|Word Open XML Macro-Enabled Document Template (.dotm) represents template file created with Microsoft Word 2007 or higher.<br/>            Learn more about this file format|
|RTF|Rich Text Format File (.rtf) represents a method of encoding formatted text and graphics for use within applications. <br/>            Learn more about this file format|
|TXT|Plain Text File (.txt) represents a text document that contains plain text in the form of lines. <br/>            Learn more about this file format|
|ODT|OpenDocument Text Document (.odt) are type of documents created with word processing applications that are based on OpenDocument Text File format. <br/>            Learn more about this file format|
|OTT|OpenDocument Document Template (.ott) represents template documents generated by applications in compliance with the OASIS' OpenDocument standard format. <br/>            Learn more about this file format|
|VCF|vCard File (.vcf) is a digital file format for storing contact information. The format is widely used for data interchange among popular information exchange applications.<br/>            Learn more about this file format|
|AI|Adobe Illustrator (.ai) is a file format for Adobe Illustrator drawings.<br/>            Learn more about this file format|
|PSM1|PowerShell script module (.psm1) a file format for PowerShell module scripts.<br/>            Learn more about this file format|
|PS1|PowerShell script file (.ps1) a file format for Windows PowerShell Cmdlet files.<br/>            Learn more about this file format|
|PSD1|PowerShell script module manifest (.psd1) a file format for PowerShell module manifest scripts.<br/>            Learn more about this file format|
## Methods
| Name | Description |
| :- | :- |
|from_stream(stream)|Detects file type by reading the file signature.|
|from_stream(stream, password)|Detects file type by reading the file signature.|
|from_stream(stream, logger)|Detects file type by reading the file signature.|
|from_stream(stream, password, logger)|Detects file type by reading the file signature.|
|detect_encoding(file_path)|Attempts to detect text [None](/viewer/python-net/groupdocs.viewer/filetype/), [None](/viewer/python-net/groupdocs.viewer/filetype/), and [None](/viewer/python-net/groupdocs.viewer/filetype/) files encoding by path.|
|detect_encoding(stream)|Attempts to detect text [None](/viewer/python-net/groupdocs.viewer/filetype/), [None](/viewer/python-net/groupdocs.viewer/filetype/), and [None](/viewer/python-net/groupdocs.viewer/filetype/) file encoding by stream.|
|from_extension(extension)|Maps file extension to file type.|
|from_file_path(file_path)|Extracts file extension and maps it to file type.|
|from_media_type(media_type)|Maps file media type to file type e.g. 'application/pdf' will be mapped to [None](/viewer/python-net/groupdocs.viewer/filetype/).|
|get_supported_file_types()|Retrieves supported file types|
|equals(other)|Determines whether the current [FileType](/viewer/python-net/groupdocs.viewer/filetype/) is the same as specified [FileType](/viewer/python-net/groupdocs.viewer/filetype/) object.|

### See Also

* namespace [groupdocs.viewer](/viewer/python-net/groupdocs.viewer/)
* assembly [GroupDocs.Viewer](/viewer/python-net/)

