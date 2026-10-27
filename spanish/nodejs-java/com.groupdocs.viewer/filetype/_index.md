---
title: "FileType"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Representa el tipo de archivo."
type: docs
weight: 14
url: /es/nodejs-java/com.groupdocs.viewer/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, com.groupdocs.viewer.caching.Cacheable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>, Cacheable
```

Representa el tipo de archivo. Proporciona métodos para obtener una lista de todos los tipos de archivo compatibles con el componente GroupDocs.Viewer.

El enum FileType proporciona constantes que representan diferentes tipos de archivo compatibles con el componente GroupDocs.Viewer. Puedes usar los métodos de este enum para obtener una lista de todos los tipos de archivo compatibles o verificar si un tipo de archivo específico es compatible.

Ejemplo de uso:

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

| Field | Descripción |
| --- | --- |
| [UNKNOWN](#UNKNOWN) | Representa un tipo de archivo desconocido. |
| [ZIP](#ZIP) | Representa un archivo comprimido (.zip) que puede contener uno o más archivos o directorios. |
| [TAR](#TAR) | Representa un archivo Unix consolidado (.tar) creado para recopilar uno o más archivos. |
| [XZ](#XZ) | Representa un archivo XZ (.xz) comprimido usando un algoritmo de compresión de alta relación basado en el algoritmo LZMA. |
| [TXZ](#TXZ) | Representa un archivo Unix consolidado (.txz, .tar.xz) creado para recopilar uno o más archivos. |
| [TARXZ](#TARXZ) | Representa un archivo Unix consolidado (.txz, .tar.xz) creado para recopilar uno o más archivos. |
| [TGZ](#TGZ) | Representa un archivo Unix consolidado (.tgz, .tar.gz) creado para recopilar uno o más archivos. |
| [TARGZ](#TARGZ) | Representa un archivo Unix consolidado (.tgz, .tar.gz) creado para recopilar uno o más archivos. |
| [BZ_2](#BZ-2) | Representa un archivo comprimido Bzip2 (.bz2) generado usando el método de compresión de código abierto BZIP2. |
| [RAR](#RAR) | Representa un archivo comprimido Roshal Archive (.rar) generado usando el método de compresión RAR (WINRAR versión 4). |
| [GZ](#GZ) | Representa un archivo comprimido Gnu Zipped File (.gz) creado con la aplicación de compresión gzip. |
| [GZIP](#GZIP) | Representa un archivo comprimido Gnu Zipped (.gzip) introducido como una utilidad gratuita para reemplazar el programa Compress utilizado en sistemas Unix. |
| [SEVEN_ZIP](#SEVEN-ZIP) | Representa un archivo 7Zip (.7z, .7zip), que es un archivador gratuito de código abierto con compresión LZMA y LZMA2. |
| [CPIO](#CPIO) | Cpio es una utilidad general de archivado de archivos y su formato de archivo asociado. |
| [ZSTANDARD](#ZSTANDARD) | El archivo ZST es un archivo comprimido que se genera con el algoritmo de compresión Zstandard (zstd). |
| [TZST](#TZST) | Los archivos TZST (.tar.zst, .tzst) son archivos Zstandard (ZST), que internamente contienen un Archivo Consolidado de Archivos Unix (Tar), creado con una utilidad basada en Unix para recopilar uno o más archivos. |
| [TAR_ZST](#TAR-ZST) | Los archivos TZST (.tar.zst, .tzst) son archivos Zstandard (ZST), que internamente contienen un Archivo Consolidado de Archivos Unix (Tar), creado con una utilidad basada en Unix para recopilar uno o más archivos. |
| [ISO](#ISO) | La imagen de disco óptico ISO es un archivo de imagen de disco sin comprimir que representa el contenido de todos los datos en un disco óptico como CD o DVD, basado en la norma ISO-9660. |
| [LHA](#LHA) | LHA o LZH es una utilidad de compresión freeware y su formato de archivo asociado. |
| [CAB](#CAB) | Cabinet (o CAB) es un formato de archivo de archivo para Microsoft Windows. |
| [DXF](#DXF) | Representa un archivo Drawing Exchange Format (.dxf), que es una representación de datos etiquetados de un archivo de dibujo AutoCAD. |
| [DWG](#DWG) | Representa un archivo de base de datos de dibujo AutoCAD (.dwg), que representa archivos binarios propietarios utilizados para contener datos de diseño 2D y 3D. |
| [DWT](#DWT) | Representa una plantilla de dibujo AutoCAD (.dwt), que es un archivo de plantilla de dibujo AutoCAD usado como punto de partida para crear dibujos que pueden guardarse como archivos DWG. |
| [STL](#STL) | Representa un archivo de estereolitografía (.stl), que es un formato de archivo intercambiable que representa la geometría de superficies tridimensionales. |
| [IFC](#IFC) | Representa un archivo Industry Foundation Classes (.ifc), que es un formato de archivo que establece normas internacionales para la importación y exportación de objetos de construcción y sus propiedades. |
| [DWF](#DWF) | Representa un archivo Design Web Format (.dwf), que es un formato de archivo comprimido para visualizar, revisar o imprimir dibujos 2D/3D. |
| [FBX](#FBX) | Representa un archivo Autodesk FBX Interchange (FilmBoX) (.fbx), que es un formato de modelo 3D. |
| [DWFX](#DWFX) | Representa un archivo Design Web Format XPS (.dwfx), que es un formato comprimido para visualizar, revisar o imprimir dibujos 2D/3D como documento XPS. |
| [DGN](#DGN) | Representa un archivo de diseño MicroStation (.dgn), que son dibujos creados y soportados por aplicaciones CAD como MicroStation e Intergraph Interactive Graphics Design System. |
| [PLT](#PLT) | Representa un archivo PLT (HPGL) (.plt), que es un archivo de trazador vectorial introducido por Autodesk, Inc. |
| [CF2](#CF2) | Representa un archivo Common File Format (.cf2). |
| [OBJ](#OBJ) | Representa un archivo Wavefront 3D Object (.obj), que es un archivo de imagen 3D introducido por Wavefront Technologies. |
| [HPG](#HPG) | Representa un archivo PLT (HPGL) (.hpg). |
| [IGS](#IGS) | Representa un archivo Initial Graphics Exchange Specification (IGES) (.igs). |
| [VSD](#VSD) | Representa un archivo de dibujo Visio (.vsd), que son dibujos creados con la aplicación Microsoft Visio para representar una variedad de objetos gráficos y sus interconexiones. |
| [VSDX](#VSDX) | Representa un archivo de dibujo Visio (.vsdx), que representa el formato de archivo Microsoft Visio introducido a partir de Microsoft Office 2013. |
| [VSS](#VSS) | Representa un archivo de plantilla Visio (.vss), que son archivos de plantilla creados con Microsoft Visio 2007 y versiones anteriores. |
| [VSSX](#VSSX) | Representa un archivo de plantilla Visio (.vssx), que son plantillas de dibujo creadas con Microsoft Visio 2013 y versiones posteriores. |
| [VSDM](#VSDM) | Representa un archivo de dibujo Visio con macros habilitadas (.vsdm), que son archivos de dibujo creados con la aplicación Microsoft Visio que soportan macros. |
| [VST](#VST) | Representa una plantilla de dibujo Visio (.vst), que son archivos de imagen vectorial creados con Microsoft Visio. |
| [VSTX](#VSTX) | Representa una plantilla de dibujo Visio (.vstx), que son archivos de plantilla de dibujo creados con Microsoft Visio 2013 y versiones posteriores. |
| [VSTM](#VSTM) | Representa una plantilla de dibujo Visio con macros habilitadas (.vstm), que son archivos de plantilla creados con Microsoft Visio que soportan macros. |
| [VSSM](#VSSM) | Representa un archivo de plantilla Visio con macros habilitadas (.vssm), que son archivos de plantilla Visio que soportan macros. |
| [VSX](#VSX) | Representa un archivo XML de plantilla Visio (.vsx), que se refiere a plantillas compuestas de dibujos y formas utilizadas para crear diagramas en Microsoft Visio. |
| [VTX](#VTX) | Representa un archivo XML de plantilla Visio (.vtx), que es una plantilla de dibujo Microsoft Visio guardada en disco en formato de archivo XML. |
| [VDW](#VDW) | Representa un dibujo web Visio (.vdw), que especifica los flujos y almacenes requeridos para renderizar un dibujo web. |
| [VDX](#VDX) | Representa un archivo XML de dibujo Visio (.vdx), que representa cualquier dibujo o gráfico creado en Microsoft Visio pero guardado en formato XML con la extensión .VDX. |
| [EPUB](#EPUB) | Representa un archivo Open eBook (.epub), que es un formato de archivo de libro electrónico que proporciona un estándar de publicación digital para editores y consumidores. |
| [MOBI](#MOBI) | Representa un libro electrónico Mobipocket (.mobi), que es uno de los formatos de libro electrónico más ampliamente utilizados. |
| [AZW_3](#AZW-3) | El formato de libro electrónico Amazon Kindle Format 8 (KF8) es el formato de archivo digital desarrollado para dispositivos Amazon Kindle. |
| [MSG](#MSG) | Representa un mensaje de correo Outlook (.msg), que es un formato de archivo usado por Microsoft Outlook y Exchange para almacenar mensajes de correo electrónico, contactos, citas u otras tareas. |
| [EML](#EML) | Representa un mensaje de correo electrónico (.eml), que representa mensajes de correo guardados usando Outlook y otras aplicaciones relevantes. |
| [EMLX](#EMLX) | Representa un mensaje de correo Apple Mail (.emlx), que es implementado y desarrollado por Apple. |
| [PST](#PST) | Representa un archivo de almacén de información personal de Outlook (.pst), que representa los archivos de almacenamiento personal de Outlook (también llamados Tabla de Almacenamiento Personal) que guardan una variedad de información del usuario. |
| [OST](#OST) | Representa un archivo de datos sin conexión de Outlook (.ost), que representa los datos del buzón de un usuario en modo sin conexión en una máquina local tras el registro con Exchange Server usando Microsoft Outlook. |
| [TIF](#TIF) | Representa un archivo de imagen etiquetada (.tif), que representa imágenes raster que están destinadas al uso en una variedad de dispositivos que cumplen con este estándar de formato de archivo. |
| [TIFF](#TIFF) | Representa un archivo de formato de imagen etiquetada (.tiff), que representa imágenes raster que están destinadas al uso en una variedad de dispositivos que cumplen con este estándar de formato de archivo. |
| [JPG](#JPG) | Representa una imagen JPEG (.jpg), que es un tipo de formato de imagen que se guarda mediante el método de compresión con pérdida. |
| [JPEG](#JPEG) | Representa una imagen JPEG (.jpeg), que es un tipo de formato de imagen que se guarda mediante el método de compresión con pérdida. |
| [JFIF](#JFIF) | El formato JPEG File Interchange Format (.jfif) es una imagen que fue desarrollada para el intercambio rápido entre plataformas. |
| [PNG](#PNG) | Representa un gráfico de red portátil (.png), que es un tipo de formato de archivo de imagen raster que utiliza compresión sin pérdida. |
| [GIF](#GIF) | Representa un archivo de formato de intercambio gráfico (.gif), que es un tipo de imagen altamente comprimida. |
| [APNG](#APNG) | Representa un Gráfico de Red Portátil Animado (.apng), que es una extensión del formato PNG que admite animación. |
| [BMP](#BMP) | Representa un archivo de imagen bitmap (.bmp), que se utiliza para almacenar imágenes digitales bitmap. |
| [ICO](#ICO) | Representa un archivo de ícono (.ico), que es un tipo de archivo de imagen usado como ícono para la representación de una aplicación en Microsoft Windows. |
| [TGA](#TGA) | Representa un archivo Truevision TGA (TARGA), que se utiliza para almacenar imágenes digitales bitmap desarrolladas por TRUEVISION. |
| [JP_2](#JP-2) | Representa un archivo de imagen central JPEG 2000 (.jp2), que es un sistema de codificación de imágenes y un estándar de compresión de imágenes de última generación. |
| [JPF](#JPF) | Representa un archivo de imagen JPEG 2000 (.jpf). |
| [JPX](#JPX) | Representa un archivo de imagen JPEG 2000 (.jpx). |
| [JPM](#JPM) | Representa un archivo de imagen JPEG 2000 (.jpm). |
| [J2C](#J2C) | Representa un flujo de entrada de código JPEG 2000 (.j2c). |
| [J2K](#J2K) | Representa un flujo de código JPEG 2000 (.j2k), que es una imagen comprimida usando compresión por ondas en lugar de compresión DCT. |
| [JPC](#JPC) | Representa un flujo de código JPEG 2000 (.jpc). |
| [JLS](#JLS) | Representa un archivo JPEG-LS (JLS) (.jls). |
| [DIB](#DIB) | Representa un archivo bitmap independiente del dispositivo (.dib). |
| [WMF](#WMF) | Representa un Metarchivo de Windows (.wmf), que representa el Metarchivo de Microsoft Windows (WMF) para almacenar datos de imagen en formato vectorial así como bitmap. |
| [WMZ](#WMZ) | Representa un Metarchivo de Windows comprimido (.wmz), que representa el Metarchivo de Microsoft Windows (WMF) comprimido en un archivo GZIP para almacenar datos de imagen vectoriales y en formato bitmap. |
| [EMF](#EMF) | Representa un Metarchivo de Windows Mejorado (.emf), que representa imágenes gráficas de forma independiente del dispositivo. |
| [EMZ](#EMZ) | Representa un Metarchivo Mejorado de Windows comprimido (.emz), que representa imágenes gráficas independientes del dispositivo comprimidas con GZIP. |
| [WEBP](#WEBP) | Representa una imagen WebP (.webp), que es un formato de archivo de imagen raster web moderno basado en compresión sin pérdida y con pérdida. |
| [DNG](#DNG) | Representa una especificación Digital Negative (.dng), que es un formato de imagen de cámara digital usado para el almacenamiento de archivos RAW. |
| [CDR](#CDR) | Representa un dibujo gráfico vectorial CorelDraw (.cdr), que es un archivo de imagen de dibujo vectorial creado de forma nativa con CorelDRAW para almacenar imágenes codificadas y comprimidas digitalmente. |
| [CMX](#CMX) | Representa un intercambio Corel (.cmx), que es un archivo de imagen de dibujo que puede contener gráficos vectoriales así como gráficos bitmap. |
| [DJVU](#DJVU) | Representa una imagen DjVu (.djvu), que es un formato de archivo gráfico destinado a documentos y libros escaneados, especialmente aquellos que contienen una combinación de texto, dibujos, imágenes y fotografías. |
| [CGM](#CGM) | Representa un Metarchivo de Gráficos por Computadora (.cgm), que es un formato de metarchivo gratuito, independiente de la plataforma, estándar internacional para almacenar e intercambiar gráficos vectoriales (2D), gráficos raster y texto. |
| [PCL](#PCL) | Representa un documento Printer Command Language (.pcl). |
| [PSD](#PSD) | Representa un documento Adobe Photoshop (.psd), que es el formato de archivo nativo de Adobe Photoshop usado para el diseño y desarrollo de gráficos. |
| [PSB](#PSB) | Representa un formato de documento grande de Photoshop (.psb), que se utiliza para el diseño y desarrollo gráfico en Adobe Photoshop. |
| [DCM](#DCM) | Representa una imagen DICOM (.dcm), que representa una imagen digital que almacena información médica de los pacientes, como resonancias magnéticas, tomografías computarizadas y imágenes de ultrasonido. |
| [PS](#PS) | Representa un archivo PostScript (.ps). |
| [EPS](#EPS) | Representa un archivo Encapsulated PostScript (.eps), que describe un programa en lenguaje Encapsulated PostScript que define la apariencia de una sola página. |
| [ODG](#ODG) | Representa un archivo OpenDocument Graphic (.odg), que es utilizado por la aplicación Draw de Apache OpenOffice para almacenar elementos de dibujo como una imagen vectorial. |
| [FODG](#FODG) | Representa una plantilla Flat XML ODF (.fodg), que es utilizada por la aplicación Draw de Apache OpenOffice para almacenar elementos de dibujo como una imagen vectorial. |
| [SVG](#SVG) | Representa un archivo Scalable Vector Graphics (.svg), que es un archivo Scalar Vector Graphics que utiliza un formato de texto basado en XML para describir la apariencia de una imagen. |
| [SVGZ](#SVGZ) | Representa un archivo Compressed Scalable Vector Graphics (.svgz), que es un archivo Scalar Vector Graphics que utiliza un formato de texto basado en XML, comprimido con GZIP, para describir la apariencia de una imagen. |
| [OTG](#OTG) | Representa una plantilla OpenDocument Graphic (.otg). |
| [HTM](#HTM) | Representa un archivo Hypertext Markup Language (.htm), que es la extensión para páginas web creadas para mostrarse en navegadores. |
| [HTML](#HTML) | Representa un archivo Hypertext Markup Language (.html), que es la extensión para páginas web creadas para mostrarse en navegadores. |
| [MHT](#MHT) | Representa un archivo de archivo web MHTML (.mht). |
| [NSF](#NSF) | Representa una base de datos Lotus Notes (.nsf). |
| [MBOX](#MBOX) | Representa un archivo de buzón de correo electrónico (.mbox). |
| [MHTML](#MHTML) | Representa un archivo MIME HTML (.mhtml). |
| [XML](#XML) | Representa un archivo XML (.xml). |
| [ONE](#ONE) | Representa un documento OneNote (.one) creado por la aplicación Microsoft OneNote. |
| [PDF](#PDF) | Representa un archivo Portable Document Format (.pdf), que es un tipo de documento creado por Adobe en la década de 1990. |
| [XPS](#XPS) | Representa un archivo XML Paper Specification (.xps), que representa archivos de diseño de página basados en XML Paper Specifications creados por Microsoft. |
| [OXPS](#OXPS) | Representa un archivo OpenXPS (.oxps). |
| [TEX](#TEX) | Representa un documento fuente LaTeX (.tex), que es un lenguaje que comprende características de programación y de marcado utilizadas para componer documentos. |
| [PPT](#PPT) | Representa una presentación PowerPoint (.ppt), que representa un archivo PowerPoint que consiste en una colección de diapositivas para mostrarse como una presentación de diapositivas. |
| [PPTX](#PPTX) | Representa una presentación PowerPoint Open XML (.pptx), que son archivos de presentación creados con la popular aplicación Microsoft PowerPoint. |
| [PPS](#PPS) | Representa una presentación de diapositivas PowerPoint (.pps), que se crean usando Microsoft PowerPoint con fines de presentación de diapositivas. |
| [PPSX](#PPSX) | Representa archivos de presentación de diapositivas PowerPoint Open XML (.ppsx), que se crean usando Microsoft PowerPoint 2007 y versiones posteriores con fines de presentación de diapositivas. |
| [ODP](#ODP) | Representa una presentación OpenDocument (.odp), que representa un formato de archivo de presentación utilizado por OpenOffice.org en el estándar OASISOpen. |
| [FODP](#FODP) | Representa una presentación OpenDocument (.fodp), que representa la presentación OpenDocument Flat XML. |
| [POT](#POT) | Representa una plantilla de PowerPoint (.pot), que representa archivos de plantilla de Microsoft PowerPoint creados por las versiones PowerPoint 97-2003. |
| [PPTM](#PPTM) | Representa una presentación PowerPoint Open XML con macros habilitados (.pptm), que son archivos de presentación con macros creados con Microsoft PowerPoint 2007 o versiones superiores. |
| [POTX](#POTX) | Representa una plantilla de presentación PowerPoint Open XML (.potx), que representa presentaciones de plantilla de Microsoft PowerPoint creadas con Microsoft PowerPoint 2007 y posteriores. |
| [POTM](#POTM) | Representa una plantilla de presentación PowerPoint Open XML con macros habilitados (.potm), que son archivos de plantilla de Microsoft PowerPoint con soporte para macros. |
| [PPSM](#PPSM) | Representa una diapositiva PowerPoint Open XML con macros habilitados (.ppsm), que representa un formato de archivo de presentación de diapositivas con macros creado con Microsoft PowerPoint 2007 o superior. |
| [OTP](#OTP) | Representa una plantilla de presentación OpenDocument (.otp), que representa archivos de plantilla de presentación creados por aplicaciones en el formato estándar OASIS OpenDocument. |
| [XLS](#XLS) | Representa una hoja de cálculo Excel (.xls), que representa el formato de archivo binario de Excel. |
| [EXCEL_2003_XML](#EXCEL-2003-XML) | Representa un XML de Excel 2003 (SpreadsheetML) (.xml), que representa el formato de archivo binario de Excel. |
| [NUMBERS](#NUMBERS) | Representa Apple Numbers (.numbers), que representa un formato de archivo binario similar a Excel. |
| [XLSX](#XLSX) | Representa una hoja de cálculo Microsoft Excel Open XML (.xlsx), que es un formato bien conocido para documentos de Microsoft Excel que fue introducido por Microsoft con el lanzamiento de Microsoft Office 2007. |
| [XLSM](#XLSM) | Representa una hoja de cálculo Excel Open XML con macros habilitados (.xlsm), que es un tipo de archivo de hoja de cálculo que admite macros. |
| [XLSB](#XLSB) | Representa una hoja de cálculo binaria de Excel (.xlsb), que especifica el formato de archivo binario de Excel. |
| [CSV](#CSV) | Representa un archivo de valores separados por comas (.csv), que representa archivos de texto plano que contienen registros de datos con valores separados por comas. |
| [TSV](#TSV) | Representa un archivo de valores separados por tabulaciones (.tsv), que representa datos separados por tabulaciones en formato de texto plano. |
| [ODS](#ODS) | Representa una hoja de cálculo OpenDocument (.ods), que corresponde al formato de documento de hoja de cálculo OpenDocument que es editable por el usuario. |
| [FODS](#FODS) | Representa una hoja de cálculo OpenDocument Flat XML (.fods). |
| [OTS](#OTS) | Representa una plantilla de hoja de cálculo OpenDocument (.ots). |
| [XLAM](#XLAM) | Representa un complemento de Microsoft Excel (.xlam). |
| [XLTM](#XLTM) | Representa una plantilla de Microsoft Excel con macros habilitados (.xltm), que representa archivos generados por Microsoft Excel como plantillas con macros. |
| [XLT](#XLT) | Representa una plantilla de Microsoft Excel (.xlt), que son archivos de plantilla creados con Microsoft Excel, una aplicación de hoja de cálculo que forma parte del conjunto Microsoft Office. |
| [XLTX](#XLTX) | Representa una plantilla de hoja de cálculo Excel Open XML (.xltx), que representa plantillas de Microsoft Excel basadas en las especificaciones del formato de archivo Office OpenXML. |
| [SXC](#SXC) | Representa una hoja de cálculo StarOffice Calc (.sxc). |
| [MPP](#MPP) | Representa un archivo de Microsoft Project (.mpp), que es un archivo de datos de Microsoft Project que almacena información relacionada con la gestión de proyectos de manera integrada. |
| [MPT](#MPT) | Representa una plantilla de Microsoft Project (.mpt), que contiene información básica y estructura junto con la configuración de documentos para crear archivos .MPP. |
| [MPX](#MPX) | Representa un archivo de intercambio de Microsoft Project (.mpx), que es un formato de archivo ASCII para transferir información de proyectos entre Microsoft Project (MSP) y otras aplicaciones que admiten el formato de archivo MPX, como Primavera Project Planner, Sciforma y Timerline Precision Estimating. |
| [AS](#AS) | Representa un archivo ActionScript (.as). |
| [AS_3](#AS-3) | Representa un archivo ActionScript (.as3). |
| [ASM](#ASM) | Representa un archivo de código fuente en lenguaje ensamblador (.asm). |
| [BAT](#BAT) | Representa un archivo por lotes DOS (.bat). |
| [C](#C) | Representa un archivo de código fuente C/C++ (.c). |
| [CC](#CC) | Representa un archivo de código fuente C++ (.cc). |
| [CMAKE](#CMAKE) | Representa un archivo CMake (.cmake). |
| [CPP](#CPP) | Representa un archivo de código fuente C++ (.cpp). |
| [CS](#CS) | Representa un archivo de código fuente C\# (.cs), que es un archivo de código fuente para el lenguaje de programación C\#. |
| [VB](#VB) | Representa un archivo de elemento de proyecto Visual Basic (.vb), que es un archivo de código fuente creado en el lenguaje Visual Basic. |
| [CSS](#CSS) | Representa un archivo de hoja de estilo en cascada (.css). |
| [CXX](#CXX) | Representa un archivo de código fuente C++ (.cxx). |
| [DIFF](#DIFF) | Representa un archivo de parche (.diff). |
| [ERB](#ERB) | Representa un script Ruby ERB (.erb). |
| [GROOVY](#GROOVY) | Representa un archivo de código fuente Groovy (.groovy). |
| [H](#H) | Representa un archivo de encabezado C/C++/Objective-C (.h). |
| [HAML](#HAML) | Representa un archivo de código fuente Haml (.haml). |
| [HH](#HH) | Representa un archivo de encabezado C++ (.hh). |
| [JAVA](#JAVA) | Representa un archivo de código fuente Java (.java). |
| [JS](#JS) | Representa un archivo JavaScript (.js). |
| [JSON](#JSON) | Representa un archivo de notación de objetos JavaScript (.json). |
| [LESS](#LESS) | Representa un archivo de hoja de estilo LESS (.less). |
| [LOG](#LOG) | Representa un archivo de registro (.log). |
| [M](#M) | Representa un archivo de implementación Objective‑C (.m). |
| [MAKE](#MAKE) | Representa un script Makefile de Xcode (.make). |
| [MD](#MD) | Representa un archivo de documentación Markdown (.md). |
| [ML](#ML) | Representa un archivo de código fuente ML (.ml). |
| [MM](#MM) | Representa un archivo de código fuente Objective‑C++ (.mm). |
| [PHP](#PHP) | Representa un archivo de código fuente PHP (.php). |
| [PL](#PL) | Representa un script Perl (.pl). |
| [PROPERTIES](#PROPERTIES) | Representa un archivo de propiedades Java (.properties). |
| [PY](#PY) | Representa un script Python (.py). |
| [RB](#RB) | Representa un archivo de código fuente Ruby (.rb). |
| [RST](#RST) | Representa un archivo reStructuredText (.rst). |
| [SASS](#SASS) | Representa un archivo Syntactically Awesome StyleSheets (.sass). |
| [SCALA](#SCALA) | Representa un archivo de código fuente Scala (.scala). |
| [SCM](#SCM) | Representa un archivo de código fuente Scheme (.scm). |
| [SCRIPT](#SCRIPT) | Representa un archivo de script genérico (.script). |
| [SH](#SH) | Representa un script Bash Shell (.sh). |
| [SML](#SML) | Representa un archivo de código fuente Standard ML (.sml). |
| [SQL](#SQL) | Representa un archivo de datos Structured Query Language (.sql). |
| [VIM](#VIM) | Representa un archivo de configuración Vim (.vim). |
| [YAML](#YAML) | Representa un documento YAML (.yaml). |
| [DOC](#DOC) | Representa un archivo de documento Microsoft Word (.doc). |
| [DOCX](#DOCX) | Representa un archivo de documento Microsoft Word Open XML (.docx). |
| [CHM](#CHM) | Representa un archivo de ayuda HTML compilado de Microsoft (.chm). |
| [DOCM](#DOCM) | Representa un archivo Word Open XML Macro-Enabled Document (.docm). |
| [DOT](#DOT) | Representa un archivo de plantilla de documento Word (.dot). |
| [DOTX](#DOTX) | Representa un archivo de plantilla de documento Word Open XML (.dotx). |
| [DOTM](#DOTM) | Representa un archivo de plantilla de documento Word Open XML con macros habilitadas (.dotm). |
| [RTF](#RTF) | Representa un archivo Rich Text Format (.rtf). |
| [TXT](#TXT) | Representa un archivo de texto plano (.txt). |
| [ODT](#ODT) | Representa un documento de texto OpenDocument (.odt). |
| [OTT](#OTT) | Representa una plantilla de documento OpenDocument (.ott). |
| [VCF](#VCF) | Representa un archivo vCard (.vcf), que es un formato de archivo digital para almacenar información de contactos. |
| [AI](#AI) | Representa un archivo de Adobe Illustrator (.ai), que es un formato de archivo para dibujos de Adobe Illustrator. |
| [PSM1](#PSM1) | Representa un archivo de módulo de script PowerShell (.psm1). |
| [PS1](#PS1) | Representa un archivo de script PowerShell (.ps1). |
| [PSD1](#PSD1) | Representa un archivo de manifiesto de módulo de script PowerShell (.psd1). |
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Asocia una extensión de archivo con un tipo de archivo. |
| [fromFilePath(String filePath)](#fromFilePath-java.lang.String-) | Extrae la extensión del archivo de un nombre de archivo o ruta de archivo y la asocia con un tipo de archivo. |
| [fromMediaType(String mediaType)](#fromMediaType-java.lang.String-) | Asocia un tipo de medio de archivo con un tipo de archivo. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Detecta el tipo de archivo leyendo la firma del archivo. |
| [fromStream(InputStream stream, String password)](#fromStream-java.io.InputStream-java.lang.String-) | Detecta el tipo de archivo leyendo la firma del archivo. |
| [fromStream(InputStream stream, ILogger logger)](#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-) | Detecta el tipo de archivo leyendo la firma del archivo. |
| [fromStream(InputStream stream, String password, ILogger logger)](#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-) | Detecta el tipo de archivo leyendo la firma del archivo. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | Recupera los tipos de archivo compatibles. |
| [detectCharset(String filePath)](#detectCharset-java.lang.String-) | Intenta detectar la codificación de archivos de texto [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) y [CSV](../../com.groupdocs.viewer/filetype\#CSV) por ruta. |
| [detectCharset(InputStream stream)](#detectCharset-java.io.InputStream-) | Intenta detectar la codificación de archivos de texto [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) y [CSV](../../com.groupdocs.viewer/filetype\#CSV) por flujo. |
| [getFileFormat()](#getFileFormat--) | Obtiene el nombre del formato de archivo, p. ej., "Microsoft Word Document". |
| [getExtension()](#getExtension--) | Obtiene el sufijo de la extensión del archivo (incluyendo el punto "."), p. ej., ".doc". |
| [toString()](#toString--) | Devuelve una representación en forma de cadena del objeto actual. |
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Representa un tipo de archivo desconocido.

### ZIP {#ZIP}
```
public static final FileType ZIP
```


Representa un archivo comprimido (.zip) que puede contener uno o más archivos o directorios. Obtén más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/compression/zip

### TAR {#TAR}
```
public static final FileType TAR
```


Representa un archivo Unix consolidado (.tar) creado para recopilar uno o más archivos. Obtén más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/compression/tar

### XZ {#XZ}
```
public static final FileType XZ
```


Representa un archivo XZ (.xz) comprimido usando un algoritmo de compresión de alta relación basado en el algoritmo LZMA. Obtén más información sobre este formato de archivo [aquí][].


[here]: https://fileinfo.com/extension/xz

### TXZ {#TXZ}
```
public static final FileType TXZ
```


Representa un archivo Unix consolidado (.txz, .tar.xz) creado para recopilar uno o más archivos. Obtén más información sobre este formato de archivo [aquí][].


[here]: https://fileinfo.com/extension/txz

### TARXZ {#TARXZ}
```
public static final FileType TARXZ
```


Representa un archivo Unix consolidado (.txz, .tar.xz) creado para recopilar uno o más archivos. Obtén más información sobre este formato de archivo [aquí][].


[here]: https://fileinfo.com/extension/txz

### TGZ {#TGZ}
```
public static final FileType TGZ
```


Representa un archivo Unix consolidado (.tgz, .tar.gz) creado para recopilar uno o más archivos. Obtén más información sobre este formato de archivo [aquí][].


[here]: https://fileinfo.com/extension/tgz

### TARGZ {#TARGZ}
```
public static final FileType TARGZ
```


Representa un archivo Unix consolidado (.tgz, .tar.gz) creado para recopilar uno o más archivos. Obtén más información sobre este formato de archivo [aquí][].


[here]: https://fileinfo.com/extension/tgz

### BZ_2 {#BZ-2}
```
public static final FileType BZ_2
```


Representa un archivo comprimido Bzip2 (.bz2) generado usando el método de compresión de código abierto BZIP2. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/compression/bz2

### RAR {#RAR}
```
public static final FileType RAR
```


Representa un archivo comprimido Roshal Archive (.rar) generado usando el método de compresión RAR (versión 4 de WINRAR). Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/compression/rar

### GZ {#GZ}
```
public static final FileType GZ
```


Representa un archivo comprimido Gnu Zipped File (.gz) creado con la aplicación de compresión gzip. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/compression/gz

### GZIP {#GZIP}
```
public static final FileType GZIP
```


Representa un archivo comprimido Gnu Zipped File (.gzip) introducido como una utilidad gratuita para reemplazar el programa Compress usado en sistemas Unix. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/compression/gz

### SEVEN_ZIP {#SEVEN-ZIP}
```
public static final FileType SEVEN_ZIP
```


Representa un archivo 7Zip (.7z, .7zip), que es un archivador de código abierto gratuito con compresión LZMA y LZMA2. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/compression/7z/

### CPIO {#CPIO}
```
public static final FileType CPIO
```


Cpio es una utilidad de archivado de archivos general y su formato de archivo asociado. Se instala principalmente en sistemas operativos de computadora tipo Unix. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/compression/cpio

### ZSTANDARD {#ZSTANDARD}
```
public static final FileType ZSTANDARD
```


El archivo ZST es un archivo comprimido que se genera con el algoritmo de compresión Zstandard (zstd). Es un archivo comprimido creado con compresión sin pérdida mediante el algoritmo. Los archivos ZST pueden usarse para comprimir diferentes tipos de archivos como bases de datos, sistemas de archivos, redes y juegos. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/compression/zst/

### TZST {#TZST}
```
public static final FileType TZST
```


Los archivos TZST (.tar.zst, .tzst) son archivos Zstandard (ZST), que internamente contienen un Archivo Consolidado de Archivos Unix (Tar), creado con una utilidad basada en Unix para recopilar uno o más archivos.

### TAR_ZST {#TAR-ZST}
```
public static final FileType TAR_ZST
```


Los archivos TZST (.tar.zst, .tzst) son archivos Zstandard (ZST), que internamente contienen un Archivo Consolidado de Archivos Unix (Tar), creado con una utilidad basada en Unix para recopilar uno o más archivos.

### ISO {#ISO}
```
public static final FileType ISO
```


La imagen de disco óptico ISO es un archivo de imagen de disco de archivo sin comprimir que representa el contenido de todos los datos en un disco óptico como CD o DVD, basado en la norma ISO-9660. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/compression/iso/

### LHA {#LHA}
```
public static final FileType LHA
```


LHA o LZH es una utilidad de compresión freeware y su formato de archivo asociado. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/compression/lzh/

### CAB {#CAB}
```
public static final FileType CAB
```


Cabinet (o CAB) es un formato de archivo de archivo para Microsoft Windows. Obtenga más información sobre este formato de archivo [here][].


[here]: https://en.wikipedia.org/wiki/Cabinet_%28file_format%29

### DXF {#DXF}
```
public static final FileType DXF
```


Representa un archivo Drawing Exchange Format (.dxf), que es una representación de datos etiquetados de un archivo de dibujo AutoCAD. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/cad/dxf

### DWG {#DWG}
```
public static final FileType DWG
```


Representa un archivo AutoCAD Drawing Database (.dwg), que son archivos binarios propietarios usados para contener datos de diseño 2D y 3D. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/cad/dwg

### DWT {#DWT}
```
public static final FileType DWT
```


Representa una plantilla de dibujo AutoCAD (.dwt), que es un archivo de plantilla de dibujo AutoCAD usado como punto de partida para crear dibujos que pueden guardarse como archivos DWG. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/cad/dwt

### STL {#STL}
```
public static final FileType STL
```


Representa un archivo Stereolithography (.stl), que es un formato de archivo intercambiable que representa la geometría de superficie tridimensional. Se usa comúnmente en prototipado rápido, impresión 3D y fabricación asistida por computadora. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/cad/stl

### IFC {#IFC}
```
public static final FileType IFC
```


Representa un archivo Industry Foundation Classes (.ifc), que es un formato de archivo que establece normas internacionales para la importación y exportación de objetos de construcción y sus propiedades. Permite la interoperabilidad entre diferentes aplicaciones de software. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/cad/ifc

### DWF {#DWF}
```
public static final FileType DWF
```


Representa un archivo Design Web Format (.dwf), que es un formato de archivo comprimido para ver, revisar o imprimir dibujos 2D/3D. Contiene gráficos y texto como parte de los datos de diseño y reduce el tamaño del archivo gracias a la compresión. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/cad/dwf

### FBX {#FBX}
```
public static final FileType FBX
```


Representa un archivo Autodesk FBX Interchange (FilmBoX) (.fbx), que es un formato de modelo 3D. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/cad/fbx

### DWFX {#DWFX}
```
public static final FileType DWFX
```


Representa un archivo Design Web Format XPS (.dwfx), que es un formato comprimido para ver, revisar o imprimir dibujos 2D/3D como documento XPS. Contiene gráficos y texto como parte de los datos de diseño y reduce el tamaño del archivo gracias a la compresión. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/cad/dwfx

### DGN {#DGN}
```
public static final FileType DGN
```


Representa un archivo MicroStation Design (.dgn), que son dibujos creados y soportados por aplicaciones CAD como MicroStation e Intergraph Interactive Graphics Design System. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/cad/dgn

### PLT {#PLT}
```
public static final FileType PLT
```


Representa un archivo PLT (HPGL) (.plt), que es un archivo de trazador vectorial introducido por Autodesk, Inc. Contiene información para un determinado archivo CAD, y todas las imágenes se imprimen usando líneas en lugar de puntos, garantizando precisión y exactitud en la producción. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/cad/plt

### CF2 {#CF2}
```
public static final FileType CF2
```


Representa un archivo Common File Format (.cf2). Obtenga más información sobre este formato de archivo [here][].


[here]: https://fileinfo.com/extension/cf2

### OBJ {#OBJ}
```
public static final FileType OBJ
```


Representa un archivo Wavefront 3D Object (.obj), que es un archivo de imagen 3D introducido por Wavefront Technologies. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/3d/obj/

### HPG {#HPG}
```
public static final FileType HPG
```


Representa un archivo PLT (HPGL) (.hpg). Es un formato de archivo utilizado para archivos de trazador en el HP Graphics Language (HPGL). Obtenga más información sobre este formato de archivo [here][].


[here]: https://fileinfo.com/extension/hpg

### IGS {#IGS}
```
public static final FileType IGS
```


Representa un archivo Initial Graphics Exchange Specification (IGES) (.igs).

### VSD {#VSD}
```
public static final FileType VSD
```


Representa un archivo de dibujo Visio (.vsd), que son dibujos creados con la aplicación Microsoft Visio para representar una variedad de objetos gráficos y sus interconexiones. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/vsd

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Representa un archivo de dibujo Visio (.vsdx), que representa el formato de archivo Microsoft Visio introducido a partir de Microsoft Office 2013. Reemplazó el formato de archivo binario (.VSD) soportado por versiones anteriores de Microsoft Visio. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/vsdx

### VSS {#VSS}
```
public static final FileType VSS
```


Representa un archivo Stencil Visio (.vss), que son archivos Stencil creados con Microsoft Visio 2007 y versiones anteriores. Los archivos Stencil proporcionan objetos de dibujo que pueden incluirse en un dibujo Visio .VSD. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/vss

### VSSX {#VSSX}
```
public static final FileType VSSX
```


Representa un archivo Stencil Visio (.vssx), que son plantillas de dibujo creadas con Microsoft Visio 2013 y versiones posteriores. El formato de archivo VSSX puede abrirse con Visio 2013 y versiones posteriores. Los archivos Visio son conocidos por representar una variedad de elementos de dibujo como formas, conectores, diagramas de flujo, diseños de red, diagramas UML, etc. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/vssx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Representa un dibujo Visio con macros habilitadas (.vsdm), que son archivos de dibujo creados con la aplicación Microsoft Visio que soportan macros. Los archivos VSDM son dibujos OPC/XML similares a VSDX, pero también ofrecen la capacidad de ejecutar macros al abrir el archivo. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/vsdm

### VST {#VST}
```
public static final FileType VST
```


Representa una plantilla de dibujo Visio (.vst), que son archivos de imagen vectorial creados con Microsoft Visio. Actúan como plantillas para crear más archivos y contienen el diseño y la configuración predeterminados utilizados para crear nuevos dibujos Visio. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/vst

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Representa una plantilla de dibujo Visio (.vstx), que son archivos de plantilla de dibujo creados con Microsoft Visio 2013 y versiones posteriores. Estos archivos VSTX proporcionan un punto de partida para crear dibujos Visio guardados como archivos .VSDX, con diseño y configuración predeterminados. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Representa una plantilla de dibujo Visio con macros habilitadas (.vstm), que son archivos de plantilla creados con Microsoft Visio que soportan macros. Los archivos creados a partir de plantillas VSTM pueden ejecutar macros desarrollados en código Visual Basic for Applications (VBA). Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Representa un archivo Stencil Visio con macros habilitadas (.vssm), que son archivos Stencil de Microsoft Visio que soportan macros. Cuando se abre un archivo VSSM, se pueden ejecutar macros para lograr el formato y la ubicación deseados de las formas en un diagrama. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Representa un archivo Stencil XML Visio (.vsx), que se refiere a plantillas que consisten en dibujos y formas utilizados para crear diagramas en Microsoft Visio. Los archivos VSX se guardan en formato XML y fueron compatibles hasta Visio 2013. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


Representa un archivo XML de plantilla Visio (.vtx), que es una plantilla de dibujo Microsoft Visio guardada en disco en formato XML. La plantilla proporciona configuraciones básicas para crear múltiples archivos Visio con los mismos ajustes. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/vtx

### VDW {#VDW}
```
public static final FileType VDW
```


Representa un dibujo web Visio (.vdw), que especifica los flujos y almacenamientos requeridos para renderizar un dibujo web. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/web/vdw

### VDX {#VDX}
```
public static final FileType VDX
```


Representa un archivo XML de dibujo de Visio (.vdx), que representa cualquier dibujo o diagrama creado en Microsoft Visio pero guardado en formato XML con la extensión .VDX. Un archivo XML de dibujo de Visio se crea en el software Visio desarrollado por Microsoft. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Representa un archivo Open eBook (.epub), que es un formato de archivo de libro electrónico que proporciona un formato de publicación digital estándar para editores y consumidores. El formato es compatible con muchos lectores electrónicos y aplicaciones de software. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/ebook/epub

### MOBI {#MOBI}
```
public static final FileType MOBI
```


Representa un libro electrónico Mobipocket (.mobi), que es uno de los formatos de archivo de libro electrónico más utilizados. El formato es una mejora del antiguo formato OEB (Open Ebook Format) y se utilizó como formato propietario para Mobipocket Reader. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/ebook/mobi

### AZW_3 {#AZW-3}
```
public static final FileType AZW_3
```


El libro electrónico Amazon Kindle Format 8 (KF8) es el formato de archivo digital desarrollado para dispositivos Amazon Kindle. El formato es una mejora de los archivos AZW más antiguos y se usa en dispositivos Kindle Fire únicamente con compatibilidad retroactiva para los formatos de archivo ancestros, es decir, MOBI y AZW. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/ebook/azw3

### MSG {#MSG}
```
public static final FileType MSG
```


Representa un mensaje de correo de Outlook (.msg), que es un formato de archivo utilizado por Microsoft Outlook y Exchange para almacenar mensajes de correo electrónico, contactos, citas u otras tareas. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/email/msg

### EML {#EML}
```
public static final FileType EML
```


Representa un mensaje de correo electrónico (.eml), que representa mensajes de correo guardados usando Outlook y otras aplicaciones relevantes. Casi todos los clientes de correo electrónico admiten este formato de archivo debido a su cumplimiento con el estándar RFC-822 Internet Message Format. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/email/eml

### EMLX {#EMLX}
```
public static final FileType EMLX
```


Representa un mensaje de Apple Mail (.emlx), que es implementado y desarrollado por Apple. La aplicación Apple Mail utiliza el formato de archivo EMLX para exportar correos electrónicos. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/email/emlx

### PST {#PST}
```
public static final FileType PST
```


Representa un archivo Outlook Personal Information Store (.pst), que representa los archivos de almacenamiento personal de Outlook (también llamados Personal Storage Table) que almacenan una variedad de información del usuario. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/email/pst

### OST {#OST}
```
public static final FileType OST
```


Representa un archivo de datos sin conexión de Outlook (.ost), que representa los datos del buzón de un usuario en modo offline en una máquina local tras registrarse en Exchange Server usando Microsoft Outlook. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/email/ost

### TIF {#TIF}
```
public static final FileType TIF
```


Representa un archivo de imagen etiquetada (.tif), que representa imágenes rasterizadas destinadas a usarse en una variedad de dispositivos que cumplen con este estándar de formato de archivo. Es capaz de describir datos de imagen binaria, en escala de grises, con paleta de colores y a color completo en varios espacios de color. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/tiff

### TIFF {#TIFF}
```
public static final FileType TIFF
```


Representa un formato de archivo de imagen etiquetada (.tiff), que representa imágenes rasterizadas destinadas a usarse en una variedad de dispositivos que cumplen con este estándar de formato de archivo. Es capaz de describir datos de imagen binaria, en escala de grises, con paleta de colores y a color completo en varios espacios de color. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/tiff

### JPG {#JPG}
```
public static final FileType JPG
```


Representa una imagen JPEG (.jpg), que es un tipo de formato de imagen que se guarda mediante el método de compresión con pérdida. La imagen resultante, como consecuencia de la compresión, es un compromiso entre el tamaño de almacenamiento y la calidad de la imagen. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/jpeg

### JPEG {#JPEG}
```
public static final FileType JPEG
```


Representa una imagen JPEG (.jpeg), que es un tipo de formato de imagen que se guarda mediante el método de compresión con pérdida. La imagen resultante, como consecuencia de la compresión, es un compromiso entre el tamaño de almacenamiento y la calidad de la imagen. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/jpeg

### JFIF {#JFIF}
```
public static final FileType JFIF
```


El formato JPEG File Interchange Format (.jfif) es una imagen que se desarrolló para el intercambio rápido entre plataformas. Este formato utiliza compresión JPEG. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/jfif

### PNG {#PNG}
```
public static final FileType PNG
```


Representa un gráfico de red portátil (.png), que es un tipo de formato de archivo de imagen rasterizada que utiliza compresión sin pérdida. Este formato de archivo se creó como reemplazo del Graphics Interchange Format (GIF) y no tiene limitaciones de derechos de autor. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/png

### GIF {#GIF}
```
public static final FileType GIF
```


Representa un archivo Graphical Interchange Format (.gif), que es un tipo de imagen altamente comprimida. Para cada imagen, GIF típicamente permite hasta 8 bits por píxel, y se permiten hasta 256 colores en toda la imagen. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/gif

### APNG {#APNG}
```
public static final FileType APNG
```


Representa un archivo Animated Portable Network Graphic (.apng), que es una extensión del formato PNG que admite animación. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/apng

### BMP {#BMP}
```
public static final FileType BMP
```


Representa un archivo Bitmap Image File (.bmp), que se utiliza para almacenar imágenes digitales bitmap. Estas imágenes son independientes del adaptador gráfico y también se denominan formato de archivo bitmap independiente del dispositivo (DIB). Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/bmp

### ICO {#ICO}
```
public static final FileType ICO
```


Representa un archivo Icon File (.ico), que es un tipo de archivo de imagen utilizado como ícono para la representación de una aplicación en Microsoft Windows. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/ico

### TGA {#TGA}
```
public static final FileType TGA
```


Representa un archivo Truevision TGA (TARGA), que se utiliza para almacenar imágenes digitales bitmap desarrolladas por TRUEVISION. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/tga

### JP_2 {#JP-2}
```
public static final FileType JP_2
```


Representa un archivo JPEG 2000 Core Image File (.jp2), que es un sistema de codificación de imágenes y un estándar de compresión de imágenes de última generación. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/jp2

### JPF {#JPF}
```
public static final FileType JPF
```


Representa un archivo JPEG 2000 Image File (.jpf). Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/image/jpf

### JPX {#JPX}
```
public static final FileType JPX
```


Representa un archivo JPEG 2000 Image File (.jpx). Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/jpx

### JPM {#JPM}
```
public static final FileType JPM
```


Representa un archivo JPEG 2000 Image File (.jpm). Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/jpm

### J2C {#J2C}
```
public static final FileType J2C
```


Representa un archivo JPEG 2000 Code InputStream (.j2c). Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/j2c

### J2K {#J2K}
```
public static final FileType J2K
```


Representa un archivo JPEG 2000 Code Stream (.j2k), que es una imagen comprimida usando compresión wavelet en lugar de compresión DCT. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/j2k

### JPC {#JPC}
```
public static final FileType JPC
```


Representa un archivo JPEG 2000 Code Stream (.jpc). Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/jpc

### JLS {#JLS}
```
public static final FileType JLS
```


Representa un archivo JPEG-LS (JLS) (.jls). Obtenga más información sobre este formato de archivo [here][].


[here]: https://fileinfo.com/extension/jls

### DIB {#DIB}
```
public static final FileType DIB
```


Representa un archivo Device Independent Bitmap (.dib). Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/dib

### WMF {#WMF}
```
public static final FileType WMF
```


Representa un archivo Windows Metafile (.wmf), que representa Microsoft Windows Metafile (WMF) para almacenar datos de imagen en formato vectorial así como bitmap. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/wmf

### WMZ {#WMZ}
```
public static final FileType WMZ
```


Representa un archivo Compressed Windows Metafile (.wmz), que representa Microsoft Windows Metafile (WMF) comprimido en un archivo GZIP para almacenar datos de imagen en formato vectorial así como bitmap. Obtenga más información sobre este formato de archivo [here][].


[here]: https://fileinfo.com/extension/wmz#compressed_windows_metafile

### EMF {#EMF}
```
public static final FileType EMF
```


Representa un archivo Enhanced Windows Metafile (.emf), que representa imágenes gráficas de forma independiente del dispositivo. Los metafiles EMF comprenden registros de longitud variable en orden cronológico que pueden renderizar la imagen almacenada después de analizarla en cualquier dispositivo de salida. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/emf

### EMZ {#EMZ}
```
public static final FileType EMZ
```


Representa un archivo Windows Compressed Enhanced Metafile (.emz), que representa imágenes gráficas de forma independiente del dispositivo comprimidas con GZIP. Los metafiles EMF comprenden registros de longitud variable en orden cronológico que pueden renderizar la imagen almacenada después de analizarla en cualquier dispositivo de salida. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/emz

### WEBP {#WEBP}
```
public static final FileType WEBP
```


Representa un archivo WebP Image (.webp), que es un formato de archivo de imagen web raster moderno basado en compresión sin pérdida y con pérdida. Proporciona la misma calidad de imagen mientras reduce considerablemente el tamaño del archivo. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/webp

### DNG {#DNG}
```
public static final FileType DNG
```


Representa un archivo Digital Negative Specification (.dng), que es un formato de imagen de cámara digital utilizado para el almacenamiento de archivos RAW. Fue desarrollado por Adobe en septiembre de 2004 y se utiliza principalmente para fotografía digital. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/dng

### CDR {#CDR}
```
public static final FileType CDR
```


Representa un archivo CorelDraw Vector Graphic Drawing (.cdr), que es un archivo de dibujo vectorial creado nativamente con CorelDRAW para almacenar imágenes codificadas y comprimidas digitalmente. Un archivo de dibujo CDR contiene texto, líneas, formas, imágenes, colores y efectos para la representación vectorial del contenido de la imagen. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/cdr

### CMX {#CMX}
```
public static final FileType CMX
```


Representa un archivo Corel Exchange (.cmx), que es un archivo de dibujo que puede contener gráficos vectoriales así como gráficos bitmap. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/cmx

### DJVU {#DJVU}
```
public static final FileType DJVU
```


Representa una imagen DjVu (.djvu), que es un formato de archivo gráfico destinado a documentos escaneados y libros, especialmente aquellos que contienen una combinación de texto, dibujos, imágenes y fotografías. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/djvu

### CGM {#CGM}
```
public static final FileType CGM
```


Representa un Metarchivo de Gráficos por Computadora (.cgm), que es un formato de metarchivo estándar internacional, gratuito e independiente de la plataforma, para almacenar e intercambiar gráficos vectoriales (2D), gráficos rasterizados y texto. CGM utiliza un enfoque orientado a objetos y proporciona muchas funciones para la producción de imágenes. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/page-description-language/cgm

### PCL {#PCL}
```
public static final FileType PCL
```


Representa un documento Printer Command Language (.pcl). Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/page-description-language/pcl

### PSD {#PSD}
```
public static final FileType PSD
```


Representa un documento Adobe Photoshop (.psd), que es el formato de archivo nativo de Adobe Photoshop utilizado para el diseño y desarrollo gráfico. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/psd

### PSB {#PSB}
```
public static final FileType PSB
```


Representa un formato Photoshop Large Document (.psb), que se utiliza para el diseño y desarrollo gráfico en Adobe Photoshop. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/psb

### DCM {#DCM}
```
public static final FileType DCM
```


Representa una imagen DICOM (.dcm), que es una imagen digital que almacena información médica de pacientes, como resonancias magnéticas, tomografías computarizadas y ecografías. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/dcm

### PS {#PS}
```
public static final FileType PS
```


Representa un archivo PostScript (.ps). Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/page-description-language/ps

### EPS {#EPS}
```
public static final FileType EPS
```


Representa un archivo Encapsulated PostScript (.eps), que describe un programa en lenguaje Encapsulated PostScript que define la apariencia de una sola página. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/page-description-language/eps

### ODG {#ODG}
```
public static final FileType ODG
```


Representa un archivo OpenDocument Graphic (.odg), que es utilizado por la aplicación Draw de Apache OpenOffice para almacenar elementos de dibujo como una imagen vectorial. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/odg

### FODG {#FODG}
```
public static final FileType FODG
```


Representa una plantilla Flat XML ODF (.fodg), que es utilizada por la aplicación Draw de Apache OpenOffice para almacenar elementos de dibujo como una imagen vectorial. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/image/fodg

### SVG {#SVG}
```
public static final FileType SVG
```


Representa un archivo Scalable Vector Graphics (.svg), que es un archivo Scalable Vector Graphics que utiliza un formato de texto basado en XML para describir la apariencia de una imagen. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/page-description-language/svg

### SVGZ {#SVGZ}
```
public static final FileType SVGZ
```


Representa un archivo Compressed Scalable Vector Graphics (.svgz), que es un archivo Scalable Vector Graphics que utiliza un formato de texto basado en XML, comprimido con GZIP, para describir la apariencia de una imagen. Obtenga más información sobre este formato de archivo [here][].


[here]: https://fileinfo.com/extension/svgz

### OTG {#OTG}
```
public static final FileType OTG
```


Representa una plantilla OpenDocument Graphic (.otg). Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/image/otg

### HTM {#HTM}
```
public static final FileType HTM
```


Representa un archivo Hypertext Markup Language (.htm), que es la extensión para páginas web creadas para mostrarse en navegadores. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/web/html

### HTML {#HTML}
```
public static final FileType HTML
```


Representa un archivo Hypertext Markup Language (.html), que es la extensión para páginas web creadas para mostrarse en navegadores. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


Representa un archivo MHTML Web Archive (.mht). Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/web/mht

### NSF {#NSF}
```
public static final FileType NSF
```


Representa una base de datos Lotus Notes (.nsf). Obtenga más información sobre este formato de archivo [here][].


[here]: https://fileinfo.com/extension/nsf

### MBOX {#MBOX}
```
public static final FileType MBOX
```


Representa un archivo de buzón de correo electrónico (.mbox). Obtenga más información sobre este formato de archivo [here][].


[here]: https://fileinfo.com/extension/mbox

### MHTML {#MHTML}
```
public static final FileType MHTML
```


Representa un archivo MIME HTML (.mhtml). Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/web/mhtml

### XML {#XML}
```
public static final FileType XML
```


Representa un archivo XML (.xml). Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/web/xml

### ONE {#ONE}
```
public static final FileType ONE
```


Representa un documento OneNote (.one) creado por la aplicación Microsoft OneNote. OneNote le permite recopilar información usando la aplicación como si estuviera usando su cuaderno de borradores para tomar notas. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


Representa un archivo Portable Document Format (.pdf), que es un tipo de documento creado por Adobe a principios de los años 90. El propósito de este formato de archivo era introducir un estándar para la representación de documentos y otros materiales de referencia en un formato independiente del software de aplicación, hardware y sistemas operativos. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


Representa un archivo de especificación de papel XML (.xps), que representa archivos de diseño de página basados en especificaciones de papel XML creadas por Microsoft. Este formato fue desarrollado por Microsoft como reemplazo del formato de archivo EMF y es similar al formato de archivo PDF, pero utiliza XML en el diseño, la apariencia y la información de impresión de un documento. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/page-description-language/xps

### OXPS {#OXPS}
```
public static final FileType OXPS
```


Representa un archivo OpenXPS (.oxps). Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/page-description-language/oxps

### TEX {#TEX}
```
public static final FileType TEX
```


Representa un documento fuente LaTeX (.tex), que es un lenguaje que comprende programación así como características de marcado utilizadas para componer documentos. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


Representa una presentación de PowerPoint (.ppt), que representa un archivo de PowerPoint que consiste en una colección de diapositivas para mostrarse como una presentación de diapositivas. Especifica el formato de archivo binario utilizado por Microsoft PowerPoint 97-2003. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


Representa una presentación PowerPoint Open XML (.pptx), que son archivos de presentación creados con la popular aplicación Microsoft PowerPoint. A diferencia de la versión anterior del formato de archivo de presentación PPT, que era binario, el formato PPTX se basa en el formato de archivo de presentación Microsoft PowerPoint Open XML. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


Representa una presentación de diapositivas de PowerPoint (.pps), que se crean usando Microsoft PowerPoint con fines de presentación de diapositivas. La lectura y creación de archivos PPS son compatibles con Microsoft PowerPoint 97-2003. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


Representa archivos de presentación de diapositivas PowerPoint Open XML (.ppsx), que se crean usando Microsoft PowerPoint 2007 y versiones posteriores con fines de presentación de diapositivas. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


Representa una presentación OpenDocument (.odp), que representa un formato de archivo de presentación utilizado por OpenOffice.org en el estándar OASISOpen. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/presentation/odp

### FODP {#FODP}
```
public static final FileType FODP
```


Representa una presentación OpenDocument (.fodp), que representa una presentación OpenDocument Flat XML. Obtenga más información sobre este formato de archivo [here][].


[here]: https://fileinfo.com/extension/fodp

### POT {#POT}
```
public static final FileType POT
```


Representa una plantilla de PowerPoint (.pot), que representa archivos de plantilla de Microsoft PowerPoint creados por versiones de PowerPoint 97-2003. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/presentation/pot

### PPTM {#PPTM}
```
public static final FileType PPTM
```


Representa una presentación PowerPoint Open XML con macros habilitados (.pptm), que son archivos de presentación con macros creados con Microsoft PowerPoint 2007 o versiones superiores. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/presentation/pptm

### POTX {#POTX}
```
public static final FileType POTX
```


Representa una plantilla de presentación PowerPoint Open XML (.potx), que representa presentaciones de plantilla de Microsoft PowerPoint creadas con Microsoft PowerPoint 2007 y versiones posteriores. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/presentation/potx

### POTM {#POTM}
```
public static final FileType POTM
```


Representa una plantilla de presentación PowerPoint Open XML con macros habilitados (.potm), que son archivos de plantilla de Microsoft PowerPoint con soporte para macros. Los archivos POTM se crean con PowerPoint 2007 o versiones posteriores y contienen configuraciones predeterminadas que pueden usarse para crear más archivos de presentación. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/presentation/potm

### PPSM {#PPSM}
```
public static final FileType PPSM
```


Representa una diapositiva PowerPoint Open XML con macros habilitados (.ppsm), que representa un formato de archivo de presentación de diapositivas con macros creado con Microsoft PowerPoint 2007 o superior. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/presentation/ppsm

### OTP {#OTP}
```
public static final FileType OTP
```


Representa una plantilla de presentación OpenDocument (.otp), que representa archivos de plantilla de presentación creados por aplicaciones en el formato estándar OASIS OpenDocument. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


Representa una hoja de cálculo de Excel (.xls), que representa el formato de archivo binario de Excel. Estos archivos pueden ser creados por Microsoft Excel así como por otros programas de hoja de cálculo similares como OpenOffice Calc o Apple Numbers. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### EXCEL_2003_XML {#EXCEL-2003-XML}
```
public static final FileType EXCEL_2003_XML
```


Representa un XML de Excel 2003 (SpreadsheetML) (.xml), que representa el formato de archivo binario de Excel. Estos archivos pueden ser creados por Microsoft Excel así como por otros programas de hoja de cálculo similares como OpenOffice Calc o Apple Numbers. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### NUMBERS {#NUMBERS}
```
public static final FileType NUMBERS
```


Representa Apple Numbers (.numbers), que representa un formato de archivo binario similar a Excel. Estos archivos pueden ser creados por la aplicación Apple Numbers. Obtenga más información sobre este formato de archivo [here][].


[here]: https://fileinfo.com/extension/numbers

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Representa una hoja de cálculo Microsoft Excel Open XML (.xlsx), que es un formato bien conocido para documentos de Microsoft Excel que fue introducido por Microsoft con el lanzamiento de Microsoft Office 2007. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Representa una hoja de cálculo Excel Open XML con macros habilitados (.xlsm), que es un tipo de archivo de hoja de cálculo que admite macros. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Representa una hoja de cálculo Excel binaria (.xlsb), que especifica el formato de archivo binario de Excel. Es una colección de registros y estructuras que especifican el contenido del libro de trabajo de Excel. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


Representa un archivo de valores separados por comas (.csv), que son archivos de texto plano que contienen registros de datos con valores separados por comas. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


Representa un archivo de valores separados por tabulaciones (.tsv), que contiene datos separados por tabulaciones en formato de texto plano. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


Representa una hoja de cálculo OpenDocument (.ods), que corresponde al formato de documento de hoja de cálculo OpenDocument editable por el usuario. Los datos se almacenan dentro de archivos ODF en filas y columnas. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ods

### FODS {#FODS}
```
public static final FileType FODS
```


Representa una hoja de cálculo OpenDocument Flat XML (.fods). Es un formato de documento de hoja de cálculo basado en XML utilizado por OpenOffice y LibreOffice. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/spreadsheet/fods

### OTS {#OTS}
```
public static final FileType OTS
```


Representa una plantilla de hoja de cálculo OpenDocument (.ots). Es un formato de documento plantilla utilizado por OpenOffice y LibreOffice para hojas de cálculo. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ots

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Representa un complemento de Microsoft Excel (.xlam). Es un formato de archivo utilizado por Microsoft Excel para crear complementos con funcionalidad personalizada. Obtenga más información sobre este formato de archivo [here][].


[here]: https://fileinfo.com/extension/xlam

### XLTM {#XLTM}
```
public static final FileType XLTM
```


Representa una plantilla de Microsoft Excel con macros habilitados (.xltm), que son archivos generados por Microsoft Excel como plantillas con macros. Los archivos XLTM son similares a los XLTX en estructura, excepto que estos últimos no admiten crear plantillas con macros. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltm

### XLT {#XLT}
```
public static final FileType XLT
```


Representa una plantilla de Microsoft Excel (.xlt), que son archivos plantilla creados con Microsoft Excel, una aplicación de hoja de cálculo que forma parte del conjunto Microsoft Office. Microsoft Office 97-2003 permitía crear nuevos archivos XLT así como abrirlos. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlt

### XLTX {#XLTX}
```
public static final FileType XLTX
```


Representa una plantilla de hoja de cálculo Excel Open XML (.xltx), que son plantillas de Microsoft Excel basadas en las especificaciones del formato de archivo Office OpenXML. Se utiliza para crear un archivo plantilla estándar que puede emplearse para generar archivos XLSX con la misma configuración especificada en el archivo XLTX. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltx

### SXC {#SXC}
```
public static final FileType SXC
```


Representa una hoja de cálculo StarOffice Calc (.sxc). Es un documento de hoja de cálculo creado con StarOffice Calc, un programa de hojas de cálculo. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/spreadsheet/sxc

### MPP {#MPP}
```
public static final FileType MPP
```


Representa un archivo de Microsoft Project (.mpp), que es un archivo de datos de Microsoft Project que almacena información relacionada con la gestión de proyectos de forma integrada. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/project-management/mpp

### MPT {#MPT}
```
public static final FileType MPT
```


Representa una plantilla de Microsoft Project (.mpt), que contiene información y estructura básicas junto con la configuración del documento para crear archivos .MPP. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/project-management/mpt

### MPX {#MPX}
```
public static final FileType MPX
```


Representa un archivo de intercambio de Microsoft Project (.mpx), que es un formato de archivo ASCII para transferir información de proyectos entre Microsoft Project (MSP) y otras aplicaciones que admiten el formato MPX, como Primavera Project Planner, Sciforma y Timerline Precision Estimating. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/project-management/mpx

### AS {#AS}
```
public static final FileType AS
```


Representa un archivo ActionScript (.as). Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/programming/as

### AS_3 {#AS-3}
```
public static final FileType AS_3
```


Representa un archivo ActionScript (.as3). Obtenga más información sobre este formato de archivo [here][].


[here]: https://datatypes.net/open-as3-files

### ASM {#ASM}
```
public static final FileType ASM
```


Representa un archivo de código fuente de lenguaje ensamblador (.asm). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/cad/asm

### BAT {#BAT}
```
public static final FileType BAT
```


Representa un archivo por lotes DOS (.bat). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/executable/bat

### C {#C}
```
public static final FileType C
```


Representa un archivo de código fuente C/C++ (.c). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/programming/c

### CC {#CC}
```
public static final FileType CC
```


Representa un archivo de código fuente C++ (.cc). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/programming/cc

### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Representa un archivo CMake (.cmake). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/programming/cmake

### CPP {#CPP}
```
public static final FileType CPP
```


Representa un archivo de código fuente C++ (.cpp). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/programming/cpp

### CS {#CS}
```
public static final FileType CS
```


Representa un archivo de código fuente C\# (.cs), que es un archivo de código fuente para el lenguaje de programación C\#. Fue introducido por Microsoft para su uso con el .NET Framework. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/programming/cs

### VB {#VB}
```
public static final FileType VB
```


Representa un archivo de elemento de proyecto Visual Basic (.vb), que es un archivo de código fuente creado en el lenguaje Visual Basic. Fue creado por Microsoft para el desarrollo de aplicaciones .NET. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/programming/vb

### CSS {#CSS}
```
public static final FileType CSS
```


Representa un archivo de hoja de estilo en cascada (.css). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/web/css

### CXX {#CXX}
```
public static final FileType CXX
```


Representa un archivo de código fuente C++ (.cxx). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/programming/cxx

### DIFF {#DIFF}
```
public static final FileType DIFF
```


Representa un archivo de parche (.diff). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/programming/diff

### ERB {#ERB}
```
public static final FileType ERB
```


Representa un script Ruby ERB (.erb). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/programming/erb

### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Representa un archivo de código fuente Groovy (.groovy). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/programming/groovy

### H {#H}
```
public static final FileType H
```


Representa un archivo de encabezado C/C++/Objective-C (.h). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/programming/h

### HAML {#HAML}
```
public static final FileType HAML
```


Representa un archivo de código fuente Haml (.haml). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/programming/haml

### HH {#HH}
```
public static final FileType HH
```


Representa un archivo de encabezado C++ (.hh). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/programming/hh

### JAVA {#JAVA}
```
public static final FileType JAVA
```


Representa un archivo de código fuente Java (.java). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/programming/java

### JS {#JS}
```
public static final FileType JS
```


Representa un archivo JavaScript (.js). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/web/js

### JSON {#JSON}
```
public static final FileType JSON
```


Representa un archivo de notación de objetos JavaScript (.json). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/web/json

### LESS {#LESS}
```
public static final FileType LESS
```


Representa un archivo de hoja de estilo LESS (.less). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/web/less

### LOG {#LOG}
```
public static final FileType LOG
```


Representa un archivo de registro (.log). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/database/log

### M {#M}
```
public static final FileType M
```


Representa un archivo de implementación Objective-C (.m). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://fileinfo.com/extension/m

### MAKE {#MAKE}
```
public static final FileType MAKE
```


Representa un script Makefile de Xcode (.make). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/programming/make

### MD {#MD}
```
public static final FileType MD
```


Representa un archivo de documentación Markdown (.md). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/word-processing/md

### ML {#ML}
```
public static final FileType ML
```


Representa un archivo de código fuente ML (.ml). Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/programming/ml

### MM {#MM}
```
public static final FileType MM
```


Representa un archivo fuente Objective-C++ (.mm). Obtén más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/programming/mm

### PHP {#PHP}
```
public static final FileType PHP
```


Representa un archivo de código fuente PHP (.php). Obtén más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/programming/php

### PL {#PL}
```
public static final FileType PL
```


Representa un script Perl (.pl). Obtén más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/programming/pl

### PROPERTIES {#PROPERTIES}
```
public static final FileType PROPERTIES
```


Representa un archivo de propiedades Java (.properties). Obtén más información sobre este formato de archivo [here][].


[here]: https://fileinfo.com/extension/properties

### PY {#PY}
```
public static final FileType PY
```


Representa un script Python (.py). Obtén más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/programming/py

### RB {#RB}
```
public static final FileType RB
```


Representa un archivo de código fuente Ruby (.rb). Obtén más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/programming/rb

### RST {#RST}
```
public static final FileType RST
```


Representa un archivo reStructuredText (.rst). Obtén más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/programming/rst

### SASS {#SASS}
```
public static final FileType SASS
```


Representa un archivo Syntactically Awesome StyleSheets (.sass). Obtén más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/web/sass

### SCALA {#SCALA}
```
public static final FileType SCALA
```


Representa un archivo de código fuente Scala (.scala). Obtén más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/programming/scala

### SCM {#SCM}
```
public static final FileType SCM
```


Representa un archivo de código fuente Scheme (.scm). Obtén más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/programming/scm

### SCRIPT {#SCRIPT}
```
public static final FileType SCRIPT
```


Representa un archivo de script genérico (.script). Obtén más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/programming/script

### SH {#SH}
```
public static final FileType SH
```


Representa un script de Bash Shell (.sh). Obtén más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/cs/programming/sh

### SML {#SML}
```
public static final FileType SML
```


Representa un archivo de código fuente Standard ML (.sml). Obtén más información sobre este formato de archivo [here][].


[here]: https://fileinfo.com/extension/sml

### SQL {#SQL}
```
public static final FileType SQL
```


Representa un archivo de datos Structured Query Language (.sql). Obtén más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/database/sql

### VIM {#VIM}
```
public static final FileType VIM
```


Representa un archivo de configuración Vim (.vim). Obtén más información sobre este formato de archivo [here][].


[here]: https://fileinfo.com/extension/vim

### YAML {#YAML}
```
public static final FileType YAML
```


Representa un documento YAML (.yaml). Obtén más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/programming/yaml

### DOC {#DOC}
```
public static final FileType DOC
```


Representa un documento Microsoft Word (.doc). Obtén más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Representa un documento Microsoft Word Open XML (.docx). Obtén más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/word-processing/docx

### CHM {#CHM}
```
public static final FileType CHM
```


Representa un archivo Microsoft Compiled HTML Help (.chm). Obtén más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/web/chm

### DOCM {#DOCM}
```
public static final FileType DOCM
```


Representa un documento Microsoft Word Open XML con macros habilitadas (.docm). Obtén más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


Representa una plantilla de documento Word (.dot). Obtén más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Representa una plantilla de documento Microsoft Word Open XML (.dotx). Obtén más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Representa una plantilla de documento Microsoft Word Open XML con macros habilitadas (.dotm). Obtén más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


Representa un archivo Rich Text Format (.rtf). Obtén más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


Representa un archivo de texto plano (.txt). Obtén más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/word-processing/txt

### ODT {#ODT}
```
public static final FileType ODT
```


Representa un documento de texto OpenDocument (.odt). Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


Representa una plantilla de documento OpenDocument (.ott). Es un documento plantilla generado en cumplimiento con el formato estándar OpenDocument de OASIS. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/word-processing/ott

### VCF {#VCF}
```
public static final FileType VCF
```


Representa un archivo vCard (.vcf), que es un formato de archivo digital para almacenar información de contactos. Se utiliza ampliamente para el intercambio de datos entre aplicaciones populares de intercambio de información. Obtenga más información sobre este formato de archivo [here][].


[here]: https://wiki.fileformat.com/email/vcf

### AI {#AI}
```
public static final FileType AI
```


Representa un archivo de Adobe Illustrator (.ai), que es un formato de archivo para dibujos de Adobe Illustrator. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/image/ai

### PSM1 {#PSM1}
```
public static final FileType PSM1
```


Representa un archivo de módulo de script PowerShell (.psm1). Es un formato de archivo para scripts de módulos PowerShell. Obtenga más información sobre este formato de archivo [here][].


[here]: https://fileinfo.com/extension/psm1

### PS1 {#PS1}
```
public static final FileType PS1
```


Representa un archivo de script PowerShell (.ps1). Es un formato de archivo para archivos Cmdlet de Windows PowerShell. Obtenga más información sobre este formato de archivo [here][].


[here]: https://fileinfo.com/extension/ps1

### PSD1 {#PSD1}
```
public static final FileType PSD1
```


Representa un archivo de manifiesto de módulo de script PowerShell (.psd1). Es un formato de archivo para scripts de manifiesto de módulos PowerShell. Obtenga más información sobre este formato de archivo [here][].


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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


Asocia una extensión de archivo con un tipo de archivo.

Este método recibe una extensión de archivo, con o sin el punto ".", y devuelve el tipo de archivo correspondiente si está soportado. Si el tipo de archivo no está soportado, devuelve el tipo de archivo predeterminado [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| extension | java.lang.String | La extensión del archivo con o sin el punto ".". |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromFilePath(String filePath) {#fromFilePath-java.lang.String-}
```
public static FileType fromFilePath(String filePath)
```


Extrae la extensión del archivo de un nombre de archivo o ruta de archivo y la asocia con un tipo de archivo.

Si el tipo de archivo está soportado, el método devuelve el FileType correspondiente, de lo contrario devuelve el tipo de archivo predeterminado [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | El nombre del archivo o la ruta del archivo. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromMediaType(String mediaType) {#fromMediaType-java.lang.String-}
```
public static FileType fromMediaType(String mediaType)
```


Mapea un tipo de medio de archivo a un tipo de archivo. Por ejemplo, 'application/pdf' se mapeará a [PDF](../../com.groupdocs.viewer/filetype\#PDF).

Este método recibe un tipo de medio de archivo como entrada y lo mapea al FileType correspondiente. Si el tipo de medio está soportado, el método devuelve el tipo de archivo correspondiente. Si el tipo de medio no está soportado, devuelve el tipo de archivo predeterminado [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mediaType | java.lang.String | El tipo de medio del archivo, p. ej., 'application/pdf'. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if found, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream stream)
```


Detecta el tipo de archivo leyendo la firma del archivo.

Este método recibe un flujo de entrada que representa un archivo e intenta detectar su tipo de archivo analizando la firma del archivo. La firma del archivo es una secuencia única de bytes al inicio del archivo que indica su tipo de archivo. El método lee la firma del archivo del flujo de entrada y la compara con firmas de archivo conocidas de los tipos de archivo soportados. Si se encuentra una coincidencia, el método devuelve el tipo de archivo correspondiente. Si no se encuentra ninguna coincidencia, devuelve el tipo de archivo predeterminado [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | El flujo de entrada que representa el archivo. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password) {#fromStream-java.io.InputStream-java.lang.String-}
```
public static FileType fromStream(InputStream stream, String password)
```


Detecta el tipo de archivo leyendo la firma del archivo.

Este método analiza la firma del archivo, que es una secuencia única de bytes al inicio del archivo, para determinar el tipo de archivo. Lee la firma del archivo del flujo de entrada proporcionado y la compara con firmas de archivo conocidas de los tipos de archivo soportados. Si se encuentra una coincidencia, el método devuelve el tipo de archivo correspondiente. Si no se encuentra ninguna coincidencia, devuelve el tipo de archivo predeterminado [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

Si el archivo está cifrado y requiere una contraseña para abrirse, la contraseña debe proporcionarse como parámetro a este método. La contraseña se utilizará para descifrar el archivo y analizar su firma para determinar el tipo de archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | El flujo de entrada que representa el archivo. |
| password | java.lang.String | La contraseña para abrir el archivo. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, ILogger logger) {#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, ILogger logger)
```


Detecta el tipo de archivo leyendo la firma del archivo.

Este método analiza la firma del archivo, que es una secuencia única de bytes al inicio del archivo, para determinar el tipo de archivo. Lee la firma del archivo del flujo de entrada proporcionado y la compara con firmas de archivo conocidas de los tipos de archivo soportados. Si se encuentra una coincidencia, el método devuelve el tipo de archivo correspondiente. Si no se encuentra ninguna coincidencia, devuelve el tipo de archivo predeterminado [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

Se puede proporcionar un registrador para registrar cualquier información relevante o errores durante el proceso de detección del tipo de archivo. El registrador debe implementar la interfaz ILogger. Si no se proporciona un registrador, el proceso de detección no generará salida de registro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | El flujo de entrada que representa el archivo. |
| registrador | com.groupdocs.foundation.logging.ILogger | El registrador para registrar información o errores. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password, ILogger logger) {#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, String password, ILogger logger)
```


Detecta el tipo de archivo leyendo la firma del archivo.

Este método analiza la firma del archivo, que es una secuencia única de bytes al inicio del archivo, para determinar el tipo de archivo. Lee la firma del archivo del flujo de entrada proporcionado y la compara con firmas de archivo conocidas de los tipos de archivo soportados. Si se encuentra una coincidencia, el método devuelve el tipo de archivo correspondiente. Si no se encuentra ninguna coincidencia, devuelve el tipo de archivo predeterminado [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

Se puede proporcionar una contraseña si el archivo está cifrado o protegido. La contraseña se utilizará para abrir el archivo antes de analizar la firma del archivo. Si el archivo no requiere una contraseña, este parámetro puede establecerse en null.

Se puede proporcionar un registrador para registrar cualquier información relevante o errores durante el proceso de detección del tipo de archivo. El registrador debe implementar la interfaz ILogger. Si no se proporciona un registrador, el proceso de detección no generará salida de registro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | El flujo de entrada que representa el archivo. |
| password | java.lang.String | La contraseña para abrir el archivo. |
| registrador | com.groupdocs.foundation.logging.ILogger | El registrador para registrar información o errores. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Recupera los tipos de archivo compatibles.

Este método devuelve una secuencia de todos los tipos de archivo compatibles con el sistema. Los tipos de archivo representan varios formatos de documento que pueden ser procesados o reconocidos por el sistema.

 **Learn more**

 *  Learn more about the supported document formats: [Full list of supported file formats][]


[Full list of supported file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/

**Returns:**
java.util.List<com.groupdocs.viewer.FileType> - una secuencia de tipos de archivo compatibles.
### detectCharset(String filePath) {#detectCharset-java.lang.String-}
```
public static Charset detectCharset(String filePath)
```


Intenta detectar la codificación de archivos de texto [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) y [CSV](../../com.groupdocs.viewer/filetype\#CSV) por ruta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | El nombre del archivo o la ruta del archivo. |

**Returns:**
java.nio.charset.Charset - Charset o null cuando falla la detección del conjunto de caracteres del archivo.

**Example:**

```
Charset charset = FileType.detectCharset("message.txt");
```
### detectCharset(InputStream stream) {#detectCharset-java.io.InputStream-}
```
public static Charset detectCharset(InputStream stream)
```


Intenta detectar la codificación de archivos de texto [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) y [CSV](../../com.groupdocs.viewer/filetype\#CSV) por flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | El flujo de archivo. |

**Returns:**
java.nio.charset.Charset - Charset o null cuando falla la detección del conjunto de caracteres del archivo.

**Example:**

```
InputStream stream = new FileInputStream("message.txt");
 Charset charset = FileType.detectCharset(stream);
```
### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Obtiene el nombre del formato de archivo, p. ej., "Microsoft Word Document".

**Returns:**
java.lang.String - el nombre del formato de archivo.
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Obtiene el sufijo de la extensión del archivo (incluyendo el punto "."), p. ej., ".doc".

**Returns:**
java.lang.String - el sufijo de la extensión del archivo.
### toString() {#toString--}
```
public String toString()
```


Devuelve una representación en forma de cadena del objeto actual.

**Returns:**
java.lang.String - una representación en forma de cadena del objeto actual.
