---
title: "FileType"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt den Dateityp dar."
type: docs
weight: 14
url: /de/java/com.groupdocs.viewer/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, com.groupdocs.viewer.caching.Cacheable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>, Cacheable
```

Stellt den Dateityp dar. Bietet Methoden, um eine Liste aller von der GroupDocs.Viewer-Komponente unterstützten Dateitypen zu erhalten.


Das FileType‑Enum stellt Konstanten bereit, die verschiedene Dateitypen repräsentieren, die von der GroupDocs.Viewer-Komponente unterstützt werden.
Sie können die Methoden dieses Enums verwenden, um eine Liste aller unterstützten Dateitypen zu erhalten oder zu prüfen, ob ein bestimmter Dateityp unterstützt wird.


Beispielverwendung:

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


## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | Stellt einen unbekannten Dateityp dar. |
|
|  | [ZIP](#ZIP) | Stellt eine gezippte Datei (.zip) dar, die eine oder mehrere Dateien oder Verzeichnisse enthalten kann. |
|
|  | [TAR](#TAR) | Stellt ein konsolidiertes Unix-Dateiarchiv (.tar) dar, das zum Sammeln einer oder mehrerer Dateien erstellt wurde. |
|
|  | [XZ](#XZ) | Stellt eine XZ-Datei (.xz) dar, die mit einem hochkomprimierenden Algorithmus auf Basis des LZMA-Algorithmus komprimiert wurde. |
|
|  | [TXZ](#TXZ) | Stellt ein konsolidiertes Unix-Dateiarchiv (.txz, .tar.xz) dar, das zum Sammeln einer oder mehrerer Dateien erstellt wurde. |
|
|  | [TARXZ](#TARXZ) | Stellt ein konsolidiertes Unix-Dateiarchiv (.txz, .tar.xz) dar, das zum Sammeln einer oder mehrerer Dateien erstellt wurde. |
|
|  | [TGZ](#TGZ) | Stellt ein konsolidiertes Unix-Dateiarchiv (.tgz, .tar.gz) dar, das zum Sammeln einer oder mehrerer Dateien erstellt wurde. |
|
|  | [TARGZ](#TARGZ) | Stellt ein konsolidiertes Unix-Dateiarchiv (.tgz, .tar.gz) dar, das zum Sammeln einer oder mehrerer Dateien erstellt wurde. |
|
|  | [BZ_2](#BZ-2) | Stellt eine Bzip2-komprimierte Datei (.bz2) dar, die mit der Open-Source-Kompressionsmethode BZIP2 erzeugt wurde. |
|
|  | [RAR](#RAR) | Stellt eine Roshal-Archiv (.rar) komprimierte Datei dar, die mit der RAR (WINRAR Version 4) Kompressionsmethode erzeugt wurde. |
|
|  | [GZ](#GZ) | Stellt eine Gnu-Zip-Datei (.gz) dar, die mit der gzip-Kompressionsanwendung erstellt wurde. |
|
|  | [GZIP](#GZIP) | Stellt eine Gnu-Zip-Datei (.gzip) dar, die als kostenloses Dienstprogramm zur Ersetzung des in Unix-Systemen verwendeten Compress-Programms eingeführt wurde. |
|
|  | [SEVEN_ZIP](#SEVEN-ZIP) | Stellt eine 7Zip (.7z, .7zip)-Datei dar, die ein kostenloser Open-Source-Archivierer mit LZMA- und LZMA2-Kompression ist. |
|
|  | [CPIO](#CPIO) | Cpio ist ein allgemeines Dateiarchivierungsprogramm und das zugehörige Dateiformat. |
|
|  | [ZSTANDARD](#ZSTANDARD) | Eine ZST-Datei ist eine komprimierte Datei, die mit dem Zstandard-(zstd)-Kompressionsalgorithmus erzeugt wird. |
|
|  | [TZST](#TZST) | TZST-Dateien (.tar.zst, .tzst) sind Zstandard-Archive (ZST), die intern ein konsolidiertes Unix-Dateiarchiv (Tar) enthalten, erstellt mit einem Unix-basierten Dienstprogramm zum Sammeln einer oder mehrerer Dateien. |
|
|  | [TAR_ZST](#TAR-ZST) | TZST-Dateien (.tar.zst, .tzst) sind Zstandard-Archive (ZST), die intern ein konsolidiertes Unix-Dateiarchiv (Tar) enthalten, erstellt mit einem Unix-basierten Dienstprogramm zum Sammeln einer oder mehrerer Dateien. |
|
|  | [ISO](#ISO) | Ein ISO-Optical-Disc-Image ist eine unkomprimierte Archiv-Disk-Image-Datei, die den gesamten Inhalt einer optischen Disc wie CD oder DVD gemäß dem ISO-9660-Standard darstellt. |
|
|  | [LHA](#LHA) | LHA oder LZH ist ein kostenloses Komprimierungsprogramm und das zugehörige Dateiformat. |
|
|  | [CAB](#CAB) | Cabinet (oder CAB) ist ein Archivdateiformat für Microsoft Windows. |
|
|  | [DXF](#DXF) | Stellt eine Drawing Exchange Format-Datei (.dxf) dar, die eine getaggte Datenrepräsentation einer AutoCAD-Zeichnungsdatei ist. |
|
|  | [DWG](#DWG) | Stellt eine AutoCAD Drawing Database-Datei (.dwg) dar, die proprietäre Binärdateien zur Speicherung von 2D- und 3D-Design-Daten repräsentiert. |
|
|  | [DWT](#DWT) | Stellt eine AutoCAD Drawing Template-Datei (.dwt) dar, die als Ausgangsvorlage für das Erstellen von Zeichnungen dient, die als DWG-Dateien gespeichert werden können. |
|
|  | [STL](#STL) | Stellt eine Stereolithography-Datei (.stl) dar, ein austauschbares Dateiformat, das die 3‑dimensionale Oberflächengeometrie repräsentiert. |
|
|  | [IFC](#IFC) | Stellt eine Industry Foundation Classes-Datei (.ifc) dar, ein Dateiformat, das internationale Standards für den Import und Export von Bauobjekten und deren Eigenschaften festlegt. |
|
|  | [DWF](#DWF) | Stellt eine Design Web Format-Datei (.dwf) dar, ein komprimiertes Dateiformat zum Anzeigen, Überprüfen oder Drucken von 2D/3D-Zeichnungen. |
|
|  | [FBX](#FBX) | Stellt eine Autodesk FBX Interchange-Datei (FilmBoX) (.fbx) dar, ein 3D‑Modellformat. |
|
|  | [DWFX](#DWFX) | Stellt eine Design Web Format XPS-Datei (.dwfx) dar, ein komprimiertes Format zum Anzeigen, Überprüfen oder Drucken von 2D/3D-Zeichnungen als XPS-Dokument. |
|
|  | [DGN](#DGN) | Stellt eine MicroStation Design-Datei (.dgn) dar, die von CAD-Anwendungen wie MicroStation und Intergraph Interactive Graphics Design System erstellte und unterstützte Zeichnungen sind. |
|
|  | [PLT](#PLT) | Stellt eine PLT (HPGL)-Datei (.plt) dar, eine vektorbasierte Plotterdatei, die von Autodesk, Inc. eingeführt wurde. |
|
|  | [CF2](#CF2) | Stellt eine Common File Format-Datei (.cf2) dar. |
|
|  | [OBJ](#OBJ) | Stellt eine Wavefront 3D Object-Datei (.obj) dar, eine von Wavefront Technologies eingeführte 3D‑Bilddatei. |
|
|  | [HPG](#HPG) | Stellt eine PLT (HPGL)-Datei (.hpg) dar. |
|
|  | [IGS](#IGS) | Stellt eine Initial Graphics Exchange Specification (IGES)-Datei (.igs) dar. |
|
|  | [VSD](#VSD) | Stellt eine Visio Drawing-Datei (.vsd) dar, die mit der Microsoft Visio-Anwendung erstellte Zeichnungen zur Darstellung verschiedener grafischer Objekte und deren Verbindungen sind. |
|
|  | [VSDX](#VSDX) | Stellt eine Visio Drawing-Datei (.vsdx) dar, das von Microsoft Office 2013 an eingeführte Microsoft Visio-Dateiformat. |
|
|  | [VSS](#VSS) | Stellt eine Visio Stencil-Datei (.vss) dar, das sind Schablonendateien, die mit Microsoft Visio 2007 und früher erstellt wurden. |
|
|  | [VSSX](#VSSX) | Stellt eine Visio Stencil-Datei (.vssx) dar, das sind Zeichnungsschablonen, die mit Microsoft Visio 2013 und neueren Versionen erstellt wurden. |
|
|  | [VSDM](#VSDM) | Stellt ein Visio-Makro‑aktiviertes Zeichenblatt (.vsdm) dar, das Zeichendateien sind, die mit der Microsoft‑Visio‑Anwendung erstellt wurden und Makros unterstützen. |
|
|  | [VST](#VST) | Stellt eine Visio-Zeichnungsvorlage (.vst) dar, die Vektorbilderdateien sind, die mit Microsoft Visio erstellt wurden. |
|
|  | [VSTX](#VSTX) | Stellt eine Visio-Zeichnungsvorlage (.vstx) dar, die Zeichnungsvorlagendateien sind, die mit Microsoft Visio 2013 und höher erstellt wurden. |
|
|  | [VSTM](#VSTM) | Stellt eine Visio-Makro‑aktivierte Zeichnungsvorlage (.vstm) dar, die Vorlagendateien sind, die mit Microsoft Visio erstellt wurden und Makros unterstützen. |
|
|  | [VSSM](#VSSM) | Stellt eine Visio-Makro‑aktivierte Schablonendatei (.vssm) dar, die Microsoft‑Visio‑Schablonendateien sind, die Makros unterstützen. |
|
|  | [VSX](#VSX) | Stellt eine Visio‑Schablon‑XML‑Datei (.vsx) dar, die sich auf Schablonen bezieht, die aus Zeichnungen und Formen bestehen und zum Erstellen von Diagrammen in Microsoft Visio verwendet werden. |
|
|  | [VTX](#VTX) | Stellt eine Visio‑Vorlagen‑XML‑Datei (.vtx) dar, die eine Microsoft‑Visio‑Zeichnungsvorlage ist, die auf der Festplatte im XML‑Dateiformat gespeichert wird. |
|
|  | [VDW](#VDW) | Stellt ein Visio‑Web‑Zeichnung (.vdw) dar, das die für die Darstellung einer Web‑Zeichnung erforderlichen Streams und Speicher angibt. |
|
|  | [VDX](#VDX) | Stellt eine Visio‑Zeichnungs‑XML‑Datei (.vdx) dar, die jede in Microsoft Visio erstellte Zeichnung oder Grafik repräsentiert, die jedoch im XML‑Format mit der Erweiterung .VDX gespeichert wird. |
|
|  | [EPUB](#EPUB) | Stellt eine Open‑eBook‑Datei (.epub) dar, die ein eBook‑Dateiformat ist, das ein standardisiertes digitales Veröffentlichungsformat für Verlage und Leser bereitstellt. |
|
|  | [MOBI](#MOBI) | Stellt ein Mobipocket‑eBook (.mobi) dar, das zu den am weitesten verbreiteten eBook‑Dateiformaten gehört. |
|
|  | [AZW_3](#AZW-3) | Amazon Kindle Format 8 (KF8) eBook ist das digitale Dateiformat, das für Amazon‑Kindle‑Geräte entwickelt wurde. |
|
|  | [MSG](#MSG) | Stellt eine Outlook‑Mail‑Nachricht (.msg) dar, die ein Dateiformat ist, das von Microsoft Outlook und Exchange zum Speichern von E‑Mail‑Nachrichten, Kontakten, Terminen oder anderen Aufgaben verwendet wird. |
|
|  | [EML](#EML) | Stellt eine E‑Mail‑Nachricht (.eml) dar, die E‑Mail‑Nachrichten repräsentiert, die mit Outlook und anderen relevanten Anwendungen gespeichert wurden. |
|
|  | [EMLX](#EMLX) | Stellt eine Apple‑Mail‑Nachricht (.emlx) dar, die von Apple implementiert und entwickelt wurde. |
|
|  | [PST](#PST) | Stellt eine Outlook‑Personal‑Information‑Store‑Datei (.pst) dar, die Outlook‑Personal‑Storage‑Files (auch Personal‑Storage‑Table genannt) repräsentiert, die eine Vielzahl von Benutzerinformationen speichern. |
|
|  | [OST](#OST) | Stellt eine Outlook‑Offline‑Datendatei (.ost) dar, die die Postfachdaten eines Benutzers im Offline‑Modus auf einem lokalen Rechner bei der Registrierung am Exchange‑Server mit Microsoft Outlook repräsentiert. |
|
|  | [TIF](#TIF) | Stellt eine Tagged‑Image‑File (.tif) dar, die Rasterbilder repräsentiert, die für die Verwendung auf einer Vielzahl von Geräten gedacht sind, die diesem Dateiformatstandard entsprechen. |
|
|  | [TIFF](#TIFF) | Stellt ein Tagged‑Image‑File‑Format (.tiff) dar, das Rasterbilder repräsentiert, die für die Verwendung auf einer Vielzahl von Geräten gedacht sind, die diesem Dateiformatstandard entsprechen. |
|
|  | [JPG](#JPG) | Stellt ein JPEG‑Bild (.jpg) dar, das ein Bildformat ist, das mit verlustbehafteter Kompression gespeichert wird. |
|
|  | [JPEG](#JPEG) | Stellt ein JPEG‑Bild (.jpeg) dar, das ein Bildformat ist, das mit verlustbehafteter Kompression gespeichert wird. |
|
|  | [JFIF](#JFIF) | JPEG File Interchange Format (.jfif) ist ein Bild, das für den schnellen Austausch zwischen Plattformen entwickelt wurde. |
|
|  | [PNG](#PNG) | Stellt ein Portable Network Graphic (.png) dar, das ein Rasterbild-Dateiformat ist, das verlustfreie Kompression verwendet. |
|
|  | [GIF](#GIF) | Stellt eine Graphical Interchange Format Datei (.gif) dar, die eine stark komprimierte Bilddatei ist. |
|
|  | [APNG](#APNG) | Stellt ein Animated Portable Network Graphic (.apng) dar, das eine Erweiterung des PNG-Formats ist und Animation unterstützt. |
|
|  | [BMP](#BMP) | Stellt eine Bitmap Image File (.bmp) dar, die zum Speichern von Bitmap-Digitalbildern verwendet wird. |
|
|  | [ICO](#ICO) | Stellt eine Icon File (.ico) dar, die als Symbol für die Darstellung einer Anwendung unter Microsoft Windows verwendet wird. |
|
|  | [TGA](#TGA) | Stellt eine Truevision TGA (TARGA) Datei dar, die zum Speichern von von TRUEVISION entwickelten Bitmap-Digitalbildern verwendet wird. |
|
|  | [JP_2](#JP-2) | Stellt eine JPEG 2000 Core Image File (.jp2) dar, die ein Bildkodierungssystem und einen hochmodernen Bildkompressionsstandard darstellt. |
|
|  | [JPF](#JPF) | Stellt eine JPEG 2000 Image File (.jpf) dar. |
|
|  | [JPX](#JPX) | Stellt eine JPEG 2000 Image File (.jpx) dar. |
|
|  | [JPM](#JPM) | Stellt eine JPEG 2000 Image File (.jpm) dar. |
|
|  | [J2C](#J2C) | Stellt einen JPEG 2000 Code InputStream (.j2c) dar. |
|
|  | [J2K](#J2K) | Stellt einen JPEG 2000 Code Stream (.j2k) dar, der ein Bild ist, das mittels Wavelet-Kompression statt DCT-Kompression komprimiert wurde. |
|
|  | [JPC](#JPC) | Stellt einen JPEG 2000 Code Stream (.jpc) dar. |
|
|  | [JLS](#JLS) | Stellt eine JPEG-LS (JLS) Datei (.jls) dar. |
|
|  | [DIB](#DIB) | Stellt eine Device Independent Bitmap File (.dib) dar. |
|
|  | [WMF](#WMF) | Stellt ein Windows Metafile (.wmf) dar, das das Microsoft Windows Metafile (WMF) zum Speichern von Vektor- sowie Bitmap-Bilddaten repräsentiert. |
|
|  | [WMZ](#WMZ) | Stellt ein Compressed Windows Metafile (.wmz) dar, das das Microsoft Windows Metafile (WMF) in einem GZIP-Archiv komprimiert zum Speichern von Vektor- und Bitmap-Bilddaten repräsentiert. |
|
|  | [EMF](#EMF) | Stellt ein Enhanced Windows Metafile (.emf) dar, das grafische Bilder geräteunabhängig repräsentiert. |
|
|  | [EMZ](#EMZ) | Stellt ein Windows Compressed Enhanced Metafile (.emz) dar, das grafische Bilder geräteunabhängig durch GZIP komprimiert repräsentiert. |
|
|  | [WEBP](#WEBP) | Stellt ein WebP Image (.webp) dar, das ein modernes Raster-Webbild-Dateiformat ist, das auf verlustfreier und verlustbehafteter Kompression basiert. |
|
|  | [DNG](#DNG) | Stellt eine Digital Negative Specification (.dng) dar, das ein digitales Kamerabildformat ist, das zur Speicherung von Rohdateien verwendet wird. |
|
|  | [CDR](#CDR) | Stellt ein CorelDraw Vector Graphic Drawing (.cdr) dar, das eine Vektorzeichnungs-Bilddatei ist, die nativ mit CorelDRAW erstellt wurde, um digital codierte und komprimierte Bilder zu speichern. |
|
|  | [CMX](#CMX) | Stellt ein Corel Exchange (.cmx) dar, das eine Zeichenbilddatei ist, die sowohl Vektorgrafiken als auch Bitmap-Grafiken enthalten kann. |
|
|  | [DJVU](#DJVU) | Stellt ein DjVu Image (.djvu) dar, das ein Grafikdateiformat für gescannte Dokumente und Bücher ist, insbesondere für solche, die eine Kombination aus Text, Zeichnungen, Bildern und Fotografien enthalten. |
|
|  | [CGM](#CGM) | Stellt ein Computer Graphics Metafile (.cgm) dar, das ein kostenloses, plattformunabhängiges, internationales Standard-Metadateiformat zum Speichern und Austauschen von Vektorgrafiken (2D), Rastergrafiken und Text ist. |
|
|  | [PCL](#PCL) | Stellt ein Printer Command Language-Dokument (.pcl) dar. |
|
|  | [PSD](#PSD) | Stellt ein Adobe Photoshop-Dokument (.psd) dar, das das native Dateiformat von Adobe Photoshop ist und für Grafikdesign und -entwicklung verwendet wird. |
|
|  | [PSB](#PSB) | Stellt ein Photoshop Large Document Format (.psb) dar, das für Grafikdesign und -entwicklung in Adobe Photoshop verwendet wird. |
|
|  | [DCM](#DCM) | Stellt ein DICOM-Bild (.dcm) dar, das ein digitales Bild ist, das medizinische Informationen von Patienten wie MRTs, CT-Scans und Ultraschallbilder speichert. |
|
|  | [PS](#PS) | Stellt eine PostScript-Datei (.ps) dar. |
|
|  | [EPS](#EPS) | Stellt eine Encapsulated PostScript-Datei (.eps) dar, die ein Encapsulated PostScript-Programm beschreibt, das das Aussehen einer einzelnen Seite definiert. |
|
|  | [ODG](#ODG) | Stellt eine OpenDocument-Grafikdatei (.odg) dar, die von der Draw-Anwendung von Apache OpenOffice verwendet wird, um Zeichnungselemente als Vektorbilder zu speichern. |
|
|  | [FODG](#FODG) | Stellt eine Flat XML ODF-Vorlage (.fodg) dar, die von der Draw-Anwendung von Apache OpenOffice verwendet wird, um Zeichnungselemente als Vektorbilder zu speichern. |
|
|  | [SVG](#SVG) | Stellt eine Scalable Vector Graphics-Datei (.svg) dar, die eine Scalable Vector Graphics-Datei ist, die ein XML-basiertes Textformat zur Beschreibung des Aussehens eines Bildes verwendet. |
|
|  | [SVGZ](#SVGZ) | Stellt eine komprimierte Scalable Vector Graphics-Datei (.svgz) dar, die eine Scalable Vector Graphics-Datei ist, die ein XML-basiertes Textformat, komprimiert mit GZIP, zur Beschreibung des Aussehens eines Bildes verwendet. |
|
|  | [OTG](#OTG) | Stellt eine OpenDocument-Grafikvorlage (.otg) dar. |
|
|  | [HTM](#HTM) | Stellt eine Hypertext Markup Language-Datei (.htm) dar, die die Dateierweiterung für Webseiten ist, die zur Anzeige in Browsern erstellt wurden. |
|
|  | [HTML](#HTML) | Stellt eine Hypertext Markup Language-Datei (.html) dar, die die Dateierweiterung für Webseiten ist, die zur Anzeige in Browsern erstellt wurden. |
|
|  | [MHT](#MHT) | Stellt ein MHTML-Webarchiv (.mht) dar. |
|
|  | [NSF](#NSF) | Stellt eine Lotus Notes-Datenbank (.nsf) dar. |
|
|  | [MBOX](#MBOX) | Stellt eine E‑Mail-Postfachdatei (.mbox) dar. |
|
|  | [MHTML](#MHTML) | Stellt eine MIME HTML-Datei (.mhtml) dar. |
|
|  | [XML](#XML) | Stellt eine XML-Datei (.xml) dar. |
|
|  | [ONE](#ONE) | Stellt ein OneNote-Dokument (.one) dar, das von der Microsoft OneNote-Anwendung erstellt wurde. |
|
|  | [PDF](#PDF) | Stellt eine Portable Document Format-Datei (.pdf) dar, die eine Art Dokument ist, das von Adobe in den 1990er‑Jahren erstellt wurde. |
|
|  | [XPS](#XPS) | Stellt eine XML Paper Specification-Datei (.xps) dar, die Seitenlayoutdateien auf Basis von XML Paper Specifications darstellt, die von Microsoft erstellt wurden. |
|
|  | [OXPS](#OXPS) | Stellt eine OpenXPS-Datei (.oxps) dar. |
|
|  | [TEX](#TEX) | Stellt ein LaTeX-Quelltextdokument (.tex) dar, das eine Sprache ist, die Programmierung sowie Markup‑Funktionen umfasst und zum Satz von Dokumenten verwendet wird. |
|
|  | [OFD](#OFD) | Das Open Fixed‑layout Document (OFD)-Format, definiert durch GB/T 33190‑2016, zielt darauf ab, PDF in chinesischen öffentlichen Institutionen zu ersetzen. |
|
|  | [PPT](#PPT) | Stellt eine PowerPoint-Präsentation (.ppt) dar, die eine PowerPoint-Datei ist, die aus einer Sammlung von Folien besteht, die als Diashow angezeigt werden. |
|
|  | [PPTX](#PPTX) | Stellt eine PowerPoint Open XML-Präsentation (.pptx) dar, die Präsentationsdateien sind, die mit der beliebten Microsoft PowerPoint-Anwendung erstellt wurden. |
|
|  | [PPS](#PPS) | Stellt eine PowerPoint-Diashow (.pps) dar, die mit Microsoft PowerPoint für Diashow-Zwecke erstellt wird. |
|
|  | [PPSX](#PPSX) | Stellt PowerPoint Open XML-Diashowdateien (.ppsx) dar, die mit Microsoft PowerPoint 2007 und höher für Diashow-Zwecke erstellt werden. |
|
|  | [ODP](#ODP) | Stellt eine OpenDocument-Präsentation (.odp) dar, die ein Präsentationsdateiformat ist, das von OpenOffice.org im OASISOpen-Standard verwendet wird. |
|
|  | [FODP](#FODP) | Stellt eine OpenDocument-Präsentation (.fodp) dar, die die OpenDocument Flat XML-Präsentation repräsentiert. |
|
|  | [POT](#POT) | Stellt eine PowerPoint-Vorlage (.pot) dar, die Microsoft PowerPoint-Vorlagendateien sind, die von PowerPoint‑Versionen 97‑2003 erstellt wurden. |
|
|  | [PPTM](#PPTM) | Stellt eine PowerPoint Open XML-Makro‑aktivierte Präsentation (.pptm) dar, die makro‑aktivierte Präsentationsdateien sind, die mit Microsoft PowerPoint 2007 oder neueren Versionen erstellt wurden. |
|
|  | [POTX](#POTX) | Stellt eine PowerPoint Open XML-Präsentationsvorlage (.potx) dar, die Microsoft PowerPoint-Vortragsvorlagen sind, die mit Microsoft PowerPoint 2007 und höher erstellt wurden. |
|
|  | [POTM](#POTM) | Stellt eine PowerPoint Open XML-Makro‑aktivierte Präsentationsvorlage (.potm) dar, die Microsoft PowerPoint-Vorlagendateien mit Makrounterstützung sind. |
|
|  | [PPSM](#PPSM) | Stellt eine PowerPoint Open XML-Makro‑aktivierte Folie (.ppsm) dar, die ein makro‑aktiviertes Diashow-Dateiformat ist, das mit Microsoft PowerPoint 2007 oder höher erstellt wurde. |
|
|  | [OTP](#OTP) | Stellt eine OpenDocument-Präsentationsvorlage (.otp) dar, die Präsentationsvorlagendateien sind, die von Anwendungen im OASIS OpenDocument-Standardformat erstellt werden. |
|
|  | [XLS](#XLS) | Stellt eine Excel-Tabelle (.xls) dar, die das Excel-Binärdateiformat repräsentiert. |
|
|  | [EXCEL_2003_XML](#EXCEL-2003-XML) | Stellt ein Excel 2003 XML (SpreadsheetML) (.xml) dar, das das Excel-Binärdateiformat repräsentiert. |
|
|  | [NUMBERS](#NUMBERS) | Stellt Apple Numbers (.numbers) dar, das ein Excel‑ähnliches Binärdateiformat ist. |
|
|  | [XLSX](#XLSX) | Stellt eine Microsoft Excel Open XML-Tabelle (.xlsx) dar, ein bekanntes Format für Microsoft Excel‑Dokumente, das von Microsoft mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde. |
|
|  | [XLSM](#XLSM) | Stellt eine Excel Open XML-Makro‑aktivierte Tabelle (.xlsm) dar, eine Art Tabellendatei, die Makros unterstützt. |
|
|  | [XLSB](#XLSB) | Stellt eine Excel-Binärtabelle (.xlsb) dar, die das Excel-Binärdateiformat spezifiziert. |
|
|  | [CSV](#CSV) | Stellt eine Komma‑separierte Werte‑Datei (.csv) dar, die Klartextdateien sind, die Datensätze mit kommagetrennten Werten enthalten. |
|
|  | [TSV](#TSV) | Stellt eine Tab‑separierte Werte‑Datei (.tsv) dar, die Daten enthält, die in Klartextformat durch Tabs getrennt sind. |
|
|  | [ODS](#ODS) | Stellt eine OpenDocument-Tabelle (.ods) dar, die für das OpenDocument-Tabellendokumentformat steht und vom Benutzer editierbar ist. |
|
|  | [FODS](#FODS) | Stellt eine OpenDocument Flat XML‑Tabelle (.fods) dar. |
|
|  | [OTS](#OTS) | Stellt eine OpenDocument-Tabellenvorlage (.ots) dar. |
|
|  | [XLAM](#XLAM) | Stellt ein Microsoft Excel Add‑In (.xlam) dar. |
|
|  | [XLTM](#XLTM) | Stellt eine Microsoft Excel Makro‑aktivierte Vorlage (.xltm) dar, die von Microsoft Excel als makro‑aktivierte Vorlagendateien erzeugt wird. |
|
|  | [XLT](#XLT) | Stellt eine Microsoft Excel-Vorlage (.xlt) dar, die Vorlagendateien sind, die mit Microsoft Excel erstellt wurden, einer Tabellenkalkulationsanwendung, die Teil der Microsoft Office‑Suite ist. |
|
|  | [XLTX](#XLTX) | Stellt eine Excel Open XML Tabellenkalkulationsvorlage (.xltx) dar, die Microsoft Excel‑Vorlagen basierend auf den Office OpenXML-Dateiformatspezifikationen repräsentiert. |
|
|  | [SXC](#SXC) | Stellt eine StarOffice Calc‑Tabellenkalkulation (.sxc) dar. |
|
|  | [MPP](#MPP) | Stellt eine Microsoft Project‑Datei (.mpp) dar, die eine Microsoft Project‑Datendatei ist, die Informationen zum Projektmanagement integriert speichert. |
|
|  | [MPT](#MPT) | Stellt eine Microsoft Project‑Vorlage (.mpt) dar, die grundlegende Informationen und Struktur sowie Dokumenteinstellungen für die Erstellung von .MPP‑Dateien enthält. |
|
|  | [MPX](#MPX) | Stellt eine Microsoft Project Exchange‑Datei (.mpx) dar, ein ASCII‑Dateiformat zum Übertragen von Projektinformationen zwischen Microsoft Project (MSP) und anderen Anwendungen, die das MPX‑Dateiformat unterstützen, wie Primavera Project Planner, Sciforma und Timerline Precision Estimating. |
|
|  | [AS](#AS) | Stellt eine ActionScript‑Datei (.as) dar. |
|
|  | [AS_3](#AS-3) | Stellt eine ActionScript‑Datei (.as3) dar. |
|
|  | [ASM](#ASM) | Stellt eine Assembler‑Quellcodedatei (.asm) dar. |
|
|  | [BAT](#BAT) | Stellt eine DOS‑Batchdatei (.bat) dar. |
|
|  | [C](#C) | Stellt eine C/C++‑Quellcodedatei (.c) dar. |
|
|  | [CC](#CC) | Stellt eine C++‑Quellcodedatei (.cc) dar. |
|
|  | [CMAKE](#CMAKE) | Stellt eine CMake‑Datei (.cmake) dar. |
|
|  | [CPP](#CPP) | Stellt eine C++‑Quellcodedatei (.cpp) dar. |
|
|  | [CS](#CS) | Stellt eine C#‑Quellcodedatei (.cs) dar, die eine Quellcodedatei für die Programmiersprache C# ist. |
|
|  | [VB](#VB) | Stellt eine Visual‑Basic‑Projektdatei (.vb) dar, die eine Quellcodedatei ist, die in der Visual‑Basic‑Sprache erstellt wurde. |
|
|  | [CSS](#CSS) | Stellt eine Cascading‑Style‑Sheet‑Datei (.css) dar. |
|
|  | [CXX](#CXX) | Stellt eine C++‑Quellcodedatei (.cxx) dar. |
|
|  | [DIFF](#DIFF) | Stellt eine Patch‑Datei (.diff) dar. |
|
|  | [ERB](#ERB) | Stellt ein Ruby‑ERB‑Skript (.erb) dar. |
|
|  | [GROOVY](#GROOVY) | Stellt eine Groovy‑Quellcodedatei (.groovy) dar. |
|
|  | [H](#H) | Stellt eine C/C++/Objective‑C‑Headerdatei (.h) dar. |
|
|  | [HAML](#HAML) | Stellt eine Haml‑Quellcodedatei (.haml) dar. |
|
|  | [HH](#HH) | Stellt eine C++‑Headerdatei (.hh) dar. |
|
|  | [JAVA](#JAVA) | Stellt eine Java‑Quellcodedatei (.java) dar. |
|
|  | [JS](#JS) | Stellt eine JavaScript-Datei (.js) dar. |
|
|  | [JSON](#JSON) | Stellt eine JavaScript Object Notation-Datei (.json) dar. |
|
|  | [LESS](#LESS) | Stellt eine LESS-Stylesheet-Datei (.less) dar. |
|
|  | [LOG](#LOG) | Stellt eine Protokolldatei (.log) dar. |
|
|  | [M](#M) | Stellt eine Objective-C-Implementierungsdatei (.m) dar. |
|
|  | [MAKE](#MAKE) | Stellt ein Xcode-Makefile-Skript (.make) dar. |
|
|  | [MD](#MD) | Stellt eine Markdown-Dokumentationsdatei (.md) dar. |
|
|  | [ML](#ML) | Stellt eine ML-Quellcodedatei (.ml) dar. |
|
|  | [MM](#MM) | Stellt eine Objective-C++-Quelldatei (.mm) dar. |
|
|  | [PHP](#PHP) | Stellt eine PHP-Quellcodedatei (.php) dar. |
|
|  | [PL](#PL) | Stellt ein Perl-Skript (.pl) dar. |
|
|  | [PROPERTIES](#PROPERTIES) | Stellt eine Java-Properties-Datei (.properties) dar. |
|
|  | [PY](#PY) | Stellt ein Python-Skript (.py) dar. |
|
|  | [RB](#RB) | Stellt eine Ruby-Quellcodedatei (.rb) dar. |
|
|  | [RST](#RST) | Stellt eine reStructuredText-Datei (.rst) dar. |
|
|  | [SASS](#SASS) | Stellt eine Syntactically Awesome StyleSheets-Datei (.sass) dar. |
|
|  | [SCALA](#SCALA) | Stellt eine Scala-Quellcodedatei (.scala) dar. |
|
|  | [SCM](#SCM) | Stellt eine Scheme-Quellcodedatei (.scm) dar. |
|
|  | [SCRIPT](#SCRIPT) | Stellt eine generische Skriptdatei (.script) dar. |
|
|  | [SH](#SH) | Stellt ein Bash-Shell-Skript (.sh) dar. |
|
|  | [SML](#SML) | Stellt eine Standard-ML-Quellcodedatei (.sml) dar. |
|
|  | [SQL](#SQL) | Stellt eine Structured Query Language-Datendatei (.sql) dar. |
|
|  | [VIM](#VIM) | Stellt eine Vim-Einstellungsdatei (.vim) dar. |
|
|  | [YAML](#YAML) | Stellt ein YAML-Dokument (.yaml) dar. |
|
|  | [DOC](#DOC) | Stellt ein Microsoft-Word-Dokument (.doc) dar. |
|
|  | [DOCX](#DOCX) | Stellt eine Microsoft Word Open XML Dokument (.docx)-Datei dar. |
|
|  | [CHM](#CHM) | Stellt eine Microsoft Compiled HTML Help-Datei (.chm) dar. |
|
|  | [DOCM](#DOCM) | Stellt eine Word Open XML Makro-aktivierte Dokument (.docm)-Datei dar. |
|
|  | [DOT](#DOT) | Stellt eine Word Dokumentvorlage (.dot)-Datei dar. |
|
|  | [DOTX](#DOTX) | Stellt eine Word Open XML Dokumentvorlage (.dotx)-Datei dar. |
|
|  | [DOTM](#DOTM) | Stellt eine Word Open XML Makro-aktivierte Dokumentvorlage (.dotm)-Datei dar. |
|
|  | [RTF](#RTF) | Stellt eine Rich Text Format Datei (.rtf) dar. |
|
|  | [TXT](#TXT) | Stellt eine Nur-Text-Datei (.txt) dar. |
|
|  | [ODT](#ODT) | Stellt ein OpenDocument Textdokument (.odt) dar. |
|
|  | [OTT](#OTT) | Stellt eine OpenDocument Dokumentvorlage (.ott) dar. |
|
|  | [VCF](#VCF) | Stellt eine vCard-Datei (.vcf) dar, die ein digitales Dateiformat zum Speichern von Kontaktinformationen ist. |
|
|  | [AI](#AI) | Stellt eine Adobe Illustrator-Datei (.ai) dar, die ein Dateiformat für Adobe Illustrator-Zeichnungen ist. |
|
|  | [PSM1](#PSM1) | Stellt eine PowerShell‑Skriptmodul‑Datei (.psm1) dar. |
|
|  | [PS1](#PS1) | Stellt eine PowerShell‑Skript‑Datei (.ps1) dar. |
|
|  | [PSD1](#PSD1) | Stellt eine PowerShell‑Skriptmodul‑Manifest‑Datei (.psd1) dar. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Ordnet eine Dateierweiterung einem Dateityp zu. |
|
|  | [fromFilePath(String filePath)](#fromFilePath-java.lang.String-) | Extrahiert die Dateierweiterung aus einem Dateinamen oder Dateipfad und ordnet sie einem Dateityp zu. |
|
|  | [fromMediaType(String mediaType)](#fromMediaType-java.lang.String-) | Ordnet einen Dateimedientyp einem Dateityp zu. |
|
|  | [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Ermittelt den Dateityp durch Lesen der Dateisignatur. |
|
|  | [fromStream(InputStream stream, String password)](#fromStream-java.io.InputStream-java.lang.String-) | Ermittelt den Dateityp durch Lesen der Dateisignatur. |
|
|  | [fromStream(InputStream stream, ILogger logger)](#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-) | Ermittelt den Dateityp durch Lesen der Dateisignatur. |
|
|  | [fromStream(InputStream stream, String password, ILogger logger)](#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-) | Ermittelt den Dateityp durch Lesen der Dateisignatur. |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | Ruft die unterstützten Dateitypen ab. |
|
|  | [detectCharset(String filePath)](#detectCharset-java.lang.String-) | Versucht, den Zeichensatz von Textdateien [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV) und [CSV](../../com.groupdocs.viewer/filetype#CSV) anhand des Pfads zu erkennen. |
|
|  | [detectCharset(InputStream stream)](#detectCharset-java.io.InputStream-) | Versucht, den Zeichensatz von Textdateien [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV) und [CSV](../../com.groupdocs.viewer/filetype#CSV) anhand des Streams zu erkennen. |
|
|  | [getFileFormat()](#getFileFormat--) | Ermittelt den Namen des Dateiformats, z.\u00a0B. \"Microsoft Word Document\". |
|
|  | [getExtension()](#getExtension--) | Ermittelt das Dateierweiterungs‑Suffix (einschließlich des Punktes \".\"), z.\u00a0B. \".doc\". |
|
|  | [toString()](#toString--) | Gibt eine String-Darstellung des aktuellen Objekts zurück. |
|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Stellt einen unbekannten Dateityp dar.


### ZIP {#ZIP}
```
public static final FileType ZIP
```


Stellt eine gezippte Datei (.zip) dar, die eine oder mehrere Dateien oder Verzeichnisse enthalten kann.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/compression/zip).


### TAR {#TAR}
```
public static final FileType TAR
```


Stellt ein konsolidiertes Unix-Dateiarchiv (.tar) dar, das zum Sammeln einer oder mehrerer Dateien erstellt wurde.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/compression/tar).


### XZ {#XZ}
```
public static final FileType XZ
```


Stellt eine XZ-Datei (.xz) dar, die mit einem hochkomprimierenden Algorithmus auf Basis des LZMA-Algorithmus komprimiert wurde.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://fileinfo.com/extension/xz).


### TXZ {#TXZ}
```
public static final FileType TXZ
```


Stellt ein konsolidiertes Unix-Dateiarchiv (.txz, .tar.xz) dar, das zum Sammeln einer oder mehrerer Dateien erstellt wurde.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://fileinfo.com/extension/txz).


### TARXZ {#TARXZ}
```
public static final FileType TARXZ
```


Stellt ein konsolidiertes Unix-Dateiarchiv (.txz, .tar.xz) dar, das zum Sammeln einer oder mehrerer Dateien erstellt wurde.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://fileinfo.com/extension/txz).


### TGZ {#TGZ}
```
public static final FileType TGZ
```


Stellt ein konsolidiertes Unix-Dateiarchiv (.tgz, .tar.gz) dar, das zum Sammeln einer oder mehrerer Dateien erstellt wurde.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://fileinfo.com/extension/tgz).


### TARGZ {#TARGZ}
```
public static final FileType TARGZ
```


Stellt ein konsolidiertes Unix-Dateiarchiv (.tgz, .tar.gz) dar, das zum Sammeln einer oder mehrerer Dateien erstellt wurde.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://fileinfo.com/extension/tgz).


### BZ_2 {#BZ-2}
```
public static final FileType BZ_2
```


Stellt eine Bzip2-komprimierte Datei (.bz2) dar, die mit der Open-Source-Kompressionsmethode BZIP2 erzeugt wurde.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/compression/bz2).


### RAR {#RAR}
```
public static final FileType RAR
```


Stellt eine Roshal-Archiv (.rar) komprimierte Datei dar, die mit der RAR (WINRAR Version 4) Kompressionsmethode erzeugt wurde.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/compression/rar).


### GZ {#GZ}
```
public static final FileType GZ
```


Stellt eine Gnu-Zip-Datei (.gz) dar, die mit der gzip-Kompressionsanwendung erstellt wurde.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/compression/gz).


### GZIP {#GZIP}
```
public static final FileType GZIP
```


Stellt eine Gnu-Zip-Datei (.gzip) dar, die als kostenloses Dienstprogramm zur Ersetzung des in Unix-Systemen verwendeten Compress-Programms eingeführt wurde.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/compression/gz).


### SEVEN_ZIP {#SEVEN-ZIP}
```
public static final FileType SEVEN_ZIP
```


Stellt eine 7Zip (.7z, .7zip)-Datei dar, die ein kostenloser Open-Source-Archivierer mit LZMA- und LZMA2-Kompression ist.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/compression/7z/).


### CPIO {#CPIO}
```
public static final FileType CPIO
```


Cpio ist ein allgemeines Dateiarchivierungswerkzeug und das zugehörige Dateiformat. Es ist hauptsächlich auf Unix‑ähnlichen Betriebssystemen installiert. Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/compression/cpio).


### ZSTANDARD {#ZSTANDARD}
```
public static final FileType ZSTANDARD
```


Die ZST‑Datei ist eine komprimierte Datei, die mit dem Zstandard‑ (zstd) Kompressionsalgorithmus erzeugt wird. Es ist eine komprimierte Datei, die vom Algorithmus mit verlustfreier Kompression erstellt wird. ZST‑Dateien können verwendet werden, um verschiedene Dateitypen wie Datenbanken, Dateisysteme, Netzwerke und Spiele zu komprimieren.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/compression/zst/).


### TZST {#TZST}
```
public static final FileType TZST
```


TZST-Dateien (.tar.zst, .tzst) sind Zstandard-Archive (ZST), die intern ein konsolidiertes Unix-Dateiarchiv (Tar) enthalten, erstellt mit einem Unix-basierten Dienstprogramm zum Sammeln einer oder mehrerer Dateien.


### TAR_ZST {#TAR-ZST}
```
public static final FileType TAR_ZST
```


TZST-Dateien (.tar.zst, .tzst) sind Zstandard-Archive (ZST), die intern ein konsolidiertes Unix-Dateiarchiv (Tar) enthalten, erstellt mit einem Unix-basierten Dienstprogramm zum Sammeln einer oder mehrerer Dateien.


### ISO {#ISO}
```
public static final FileType ISO
```


Ein ISO-Optical-Disc-Image ist eine unkomprimierte Archiv-Disk-Image-Datei, die den gesamten Inhalt einer optischen Disc wie CD oder DVD gemäß dem ISO-9660-Standard darstellt.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/compression/iso/).


### LHA {#LHA}
```
public static final FileType LHA
```


LHA oder LZH ist ein kostenloses Komprimierungsprogramm und das zugehörige Dateiformat.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/compression/lzh/).


### CAB {#CAB}
```
public static final FileType CAB
```


Cabinet (oder CAB) ist ein Archivdateiformat für Microsoft Windows.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://en.wikipedia.org/wiki/Cabinet_(file_format)).


### DXF {#DXF}
```
public static final FileType DXF
```


Stellt eine Drawing Exchange Format-Datei (.dxf) dar, die eine getaggte Datenrepräsentation einer AutoCAD-Zeichnungsdatei ist.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/cad/dxf).


### DWG {#DWG}
```
public static final FileType DWG
```


Stellt eine AutoCAD Drawing Database-Datei (.dwg) dar, die proprietäre Binärdateien zur Speicherung von 2D- und 3D-Design-Daten repräsentiert.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/cad/dwg).


### DWT {#DWT}
```
public static final FileType DWT
```


Stellt eine AutoCAD Drawing Template-Datei (.dwt) dar, die als Ausgangsvorlage für das Erstellen von Zeichnungen dient, die als DWG-Dateien gespeichert werden können.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/cad/dwt).


### STL {#STL}
```
public static final FileType STL
```


Stellt eine Stereolithografie‑Datei (.stl) dar, ein austauschbares Dateiformat, das die dreidimensionale Oberflächengeometrie repräsentiert. Es wird häufig im Rapid Prototyping, 3D‑Druck und der computergestützten Fertigung verwendet.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/cad/stl).


### IFC {#IFC}
```
public static final FileType IFC
```


Stellt eine Industry Foundation Classes‑Datei (.ifc) dar, ein Dateiformat, das internationale Standards für den Import und Export von Bauobjekten und deren Eigenschaften festlegt. Es ermöglicht die Interoperabilität zwischen verschiedenen Softwareanwendungen.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/cad/ifc).


### DWF {#DWF}
```
public static final FileType DWF
```


Stellt eine Design Web Format‑Datei (.dwf) dar, ein komprimiertes Dateiformat zum Anzeigen, Überprüfen oder Drucken von 2D/3D‑Zeichnungen. Es enthält Grafiken und Text als Teil der Designdaten und reduziert die Dateigröße durch Kompression.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/cad/dwf).


### FBX {#FBX}
```
public static final FileType FBX
```


Stellt eine Autodesk FBX Interchange-Datei (FilmBoX) (.fbx) dar, ein 3D‑Modellformat.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/cad/fbx).


### DWFX {#DWFX}
```
public static final FileType DWFX
```


Stellt eine Design Web Format Datei XPS (.dwfx) dar, die ein komprimiertes Format zum Anzeigen, Überprüfen oder Drucken von 2D/3D-Zeichnungen als XPS-Dokument ist. Sie enthält Grafiken und Text als Teil der Designdaten und reduziert die Dateigröße durch Kompression.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/cad/dwfx).


### DGN {#DGN}
```
public static final FileType DGN
```


Stellt eine MicroStation Design-Datei (.dgn) dar, die von CAD-Anwendungen wie MicroStation und Intergraph Interactive Graphics Design System erstellte und unterstützte Zeichnungen sind.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/cad/dgn).


### PLT {#PLT}
```
public static final FileType PLT
```


Stellt eine PLT (HPGL)-Datei (.plt) dar, die eine vektorbasierte Plotterdatei ist, die von Autodesk, Inc. eingeführt wurde. Sie enthält Informationen für eine bestimmte CAD-Datei, und alle Bilder werden mit Linien statt Punkten gedruckt, was Genauigkeit und Präzision in der Produktion gewährleistet.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/cad/plt).


### CF2 {#CF2}
```
public static final FileType CF2
```


Stellt eine Common File Format-Datei (.cf2) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://fileinfo.com/extension/cf2).


### OBJ {#OBJ}
```
public static final FileType OBJ
```


Stellt eine Wavefront 3D Object-Datei (.obj) dar, eine von Wavefront Technologies eingeführte 3D‑Bilddatei.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/3d/obj/).


### HPG {#HPG}
```
public static final FileType HPG
```


Stellt eine PLT (HPGL)-Datei (.hpg) dar.
Es ist ein Dateiformat, das für Plotterdateien in der HP Graphics Language (HPGL) verwendet wird.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://fileinfo.com/extension/hpg).


### IGS {#IGS}
```
public static final FileType IGS
```


Stellt eine Initial Graphics Exchange Specification (IGES)-Datei (.igs) dar.


### VSD {#VSD}
```
public static final FileType VSD
```


Stellt eine Visio Drawing-Datei (.vsd) dar, die mit der Microsoft Visio-Anwendung erstellte Zeichnungen zur Darstellung verschiedener grafischer Objekte und deren Verbindungen sind.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vsd).


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Stellt eine Visio-Zeichnungsdatei (.vsdx) dar, die das Microsoft Visio-Dateiformat darstellt, das ab Microsoft Office 2013 eingeführt wurde. Sie ersetzte das binäre Dateiformat (.VSD), das von früheren Versionen von Microsoft Visio unterstützt wurde.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vsdx).


### VSS {#VSS}
```
public static final FileType VSS
```


Stellt eine Visio-Stencil-Datei (.vss) dar, die Stencil-Dateien sind, die mit Microsoft Visio 2007 und früher erstellt wurden. Stencil-Dateien bieten Zeichenobjekte, die in einer .VSD Visio-Zeichnung eingebunden werden können.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vss).


### VSSX {#VSSX}
```
public static final FileType VSSX
```


Stellt eine Visio-Stencil-Datei (.vssx) dar, die Zeichenstencils sind, die mit Microsoft Visio 2013 und höher erstellt wurden. Das VSSX-Dateiformat kann mit Visio 2013 und höher geöffnet werden. Visio-Dateien sind dafür bekannt, eine Vielzahl von Zeichenobjekten wie Formen, Verbinder, Flussdiagramme, Netzwerklayouts, UML-Diagramme usw. darzustellen.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vssx).


### VSDM {#VSDM}
```
public static final FileType VSDM
```


Stellt eine Visio-Makro-unterstützte Zeichnung (.vsdm) dar, die Zeichendateien sind, die mit der Microsoft Visio-Anwendung erstellt wurden und Makros unterstützen. VSDM-Dateien sind OPC/XML-Zeichnungen, die VSDX ähneln, aber zudem die Möglichkeit bieten, Makros beim Öffnen der Datei auszuführen.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vsdm).


### VST {#VST}
```
public static final FileType VST
```


Stellt eine Visio-Zeichnungsvorlage (.vst) dar, die Vektor-Bilddateien sind, die mit Microsoft Visio erstellt wurden. Sie dienen als Vorlagen für die Erstellung weiterer Dateien und enthalten das Standard-Layout und die Einstellungen, die für die Erstellung neuer Visio-Zeichnungen verwendet werden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vst).


### VSTX {#VSTX}
```
public static final FileType VSTX
```


Stellt eine Visio-Zeichnungsvorlage (.vstx) dar, die Zeichenvorlagendateien sind, die mit Microsoft Visio 2013 und höher erstellt wurden. Diese VSTX‑Dateien bieten einen Ausgangspunkt für die Erstellung von Visio‑Zeichnungen, die als .VSDX‑Dateien gespeichert werden, mit Standardlayout und -einstellungen.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vstx).


### VSTM {#VSTM}
```
public static final FileType VSTM
```


Stellt eine Visio-Makro‑unterstützte Zeichnungsvorlage (.vstm) dar, die Vorlagendateien sind, die mit Microsoft Visio erstellt wurden und Makros unterstützen. Aus VSTM‑Vorlagen erstellte Dateien können Makros ausführen, die in Visual Basic for Applications (VBA)-Code entwickelt wurden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vstm).


### VSSM {#VSSM}
```
public static final FileType VSSM
```


Stellt eine Visio-Makro‑unterstützte Stencil‑Datei (.vssm) dar, die Microsoft Visio Stencil‑Dateien sind, die Makros unterstützen. Wenn eine VSSM‑Datei geöffnet wird, können Makros ausgeführt werden, um die gewünschte Formatierung und Platzierung von Formen in einem Diagramm zu erreichen.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vssm).


### VSX {#VSX}
```
public static final FileType VSX
```


Stellt eine Visio-Stencil‑XML‑Datei (.vsx) dar, die sich auf Stencils bezieht, die aus Zeichnungen und Formen bestehen und zum Erstellen von Diagrammen in Microsoft Visio verwendet werden. VSX‑Dateien werden im XML‑Dateiformat gespeichert und wurden bis Visio 2013 unterstützt.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vsx).


### VTX {#VTX}
```
public static final FileType VTX
```


Stellt eine Visio‑Template‑XML‑Datei (.vtx) dar, die eine Microsoft Visio‑Zeichnungsvorlage ist, die auf der Festplatte im XML‑Dateiformat gespeichert wird. Die Vorlage bietet Grundeinstellungen für die Erstellung mehrerer Visio‑Dateien mit denselben Einstellungen.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vtx).


### VDW {#VDW}
```
public static final FileType VDW
```


Stellt ein Visio‑Web‑Zeichnung (.vdw) dar, das die für die Darstellung einer Web‑Zeichnung erforderlichen Streams und Speicher angibt.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/web/vdw).


### VDX {#VDX}
```
public static final FileType VDX
```


Stellt eine Visio‑Zeichnungs‑XML‑Datei (.vdx) dar, die jede in Microsoft Visio erstellte Zeichnung oder Grafik repräsentiert, die jedoch im XML‑Format mit der Erweiterung .VDX gespeichert wird. Eine Visio‑Zeichnungs‑XML‑Datei wird in der von Microsoft entwickelten Visio‑Software erstellt.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/vdx).


### EPUB {#EPUB}
```
public static final FileType EPUB
```


Stellt eine Open‑eBook‑Datei (.epub) dar, die ein eBook‑Dateiformat ist, das ein standardisiertes digitales Veröffentlichungsformat für Verlage und Leser bereitstellt. Das Format wird von vielen eReadern und Softwareanwendungen unterstützt.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/ebook/epub).


### MOBI {#MOBI}
```
public static final FileType MOBI
```


Stellt ein Mobipocket‑eBook (.mobi) dar, das zu den am weitesten verbreiteten eBook‑Dateiformaten gehört. Das Format ist eine Weiterentwicklung des alten OEB (Open Ebook Format) und wurde als proprietäres Format für den Mobipocket Reader verwendet.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/ebook/mobi).


### AZW_3 {#AZW-3}
```
public static final FileType AZW_3
```


Das Amazon Kindle Format 8 (KF8) eBook ist das digitale Dateiformat, das für Amazon‑Kindle‑Geräte entwickelt wurde. Das Format ist eine Weiterentwicklung älterer AZW‑Dateien und wird ausschließlich auf Kindle‑Fire‑Geräten verwendet, wobei es abwärtskompatibel zum Vorgänger‑Dateiformat, d. h. MOBI und AZW, ist.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/ebook/azw3).


### MSG {#MSG}
```
public static final FileType MSG
```


Stellt eine Outlook‑Mail‑Nachricht (.msg) dar, die ein Dateiformat ist, das von Microsoft Outlook und Exchange zum Speichern von E‑Mail‑Nachrichten, Kontakten, Terminen oder anderen Aufgaben verwendet wird.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/email/msg).


### EML {#EML}
```
public static final FileType EML
```


Stellt eine E‑Mail‑Nachricht (.eml) dar, die E‑Mail‑Nachrichten repräsentiert, die mit Outlook und anderen relevanten Anwendungen gespeichert wurden. Fast alle E‑Mail‑Clients unterstützen dieses Dateiformat, da es dem RFC‑822‑Internet‑Message‑Format‑Standard entspricht.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/email/eml).


### EMLX {#EMLX}
```
public static final FileType EMLX
```


Stellt eine Apple‑Mail‑Nachricht (.emlx) dar, die von Apple implementiert und entwickelt wurde. Die Apple‑Mail‑Anwendung verwendet das EMLX‑Dateiformat zum Exportieren von E‑Mails.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/email/emlx).


### PST {#PST}
```
public static final FileType PST
```


Stellt eine Outlook‑Personal‑Information‑Store‑Datei (.pst) dar, die Outlook‑Personal‑Storage‑Files (auch Personal‑Storage‑Table genannt) repräsentiert, die eine Vielzahl von Benutzerinformationen speichern.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/email/pst).


### OST {#OST}
```
public static final FileType OST
```


Stellt eine Outlook‑Offline‑Datendatei (.ost) dar, die die Postfachdaten eines Benutzers im Offline‑Modus auf einem lokalen Rechner bei der Registrierung am Exchange‑Server mit Microsoft Outlook repräsentiert.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/email/ost).


### TIF {#TIF}
```
public static final FileType TIF
```


Stellt eine Tagged Image File (.tif) dar, die Rasterbilder repräsentiert, die für die Verwendung auf einer Vielzahl von Geräten gedacht sind, die diesem Dateiformatstandard entsprechen. Sie kann bilevel-, Graustufen-, Palettenfarb- und Vollfarbbilddaten in mehreren Farbräumen beschreiben.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/tiff).


### TIFF {#TIFF}
```
public static final FileType TIFF
```


Stellt ein Tagged Image File Format (.tiff) dar, das Rasterbilder repräsentiert, die für die Verwendung auf einer Vielzahl von Geräten gedacht sind, die diesem Dateiformatstandard entsprechen. Es kann bilevel-, Graustufen-, Palettenfarb- und Vollfarbbilddaten in mehreren Farbräumen beschreiben.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/tiff).


### JPG {#JPG}
```
public static final FileType JPG
```


Stellt ein JPEG‑Bild (.jpg) dar, das ein Bildformat ist, das mit verlustbehafteter Kompression gespeichert wird. Das Ergebnisbild ist dabei ein Kompromiss zwischen Speichergröße und Bildqualität.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/jpeg).


### JPEG {#JPEG}
```
public static final FileType JPEG
```


Stellt ein JPEG‑Bild (.jpeg) dar, das ein Bildformat ist, das mit verlustbehafteter Kompression gespeichert wird. Das Ergebnisbild ist dabei ein Kompromiss zwischen Speichergröße und Bildqualität.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/jpeg).


### JFIF {#JFIF}
```
public static final FileType JFIF
```


Das JPEG File Interchange Format (.jfif) ist ein Bild, das für den schnellen Austausch zwischen Plattformen entwickelt wurde. Dieses Format verwendet JPEG‑Kompression. Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/jfif).


### PNG {#PNG}
```
public static final FileType PNG
```


Stellt ein Portable Network Graphic (.png) dar, das ein Rasterbilddateiformat ist, das verlustfreie Kompression verwendet. Dieses Dateiformat wurde als Ersatz für das Graphics Interchange Format (GIF) erstellt und hat keine urheberrechtlichen Beschränkungen.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/png).


### GIF {#GIF}
```
public static final FileType GIF
```


Stellt eine Graphical Interchange Format File (.gif) dar, die ein stark komprimiertes Bild ist. Für jedes Bild erlaubt GIF typischerweise bis zu 8 Bit pro Pixel, und bis zu 256 Farben sind im Bild zulässig.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/gif).


### APNG {#APNG}
```
public static final FileType APNG
```


Stellt ein Animated Portable Network Graphic (.apng) dar, das eine Erweiterung des PNG-Formats ist und Animation unterstützt.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/apng).


### BMP {#BMP}
```
public static final FileType BMP
```


Stellt eine Bitmap-Bilddatei (.bmp) dar, die zum Speichern von bitmap‑digitalen Bildern verwendet wird. Diese Bilder sind unabhängig vom Grafikadapter und werden auch als device independent bitmap (DIB)-Dateiformat bezeichnet.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/bmp).


### ICO {#ICO}
```
public static final FileType ICO
```


Stellt eine Icon File (.ico) dar, die als Symbol für die Darstellung einer Anwendung unter Microsoft Windows verwendet wird.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/ico).


### TGA {#TGA}
```
public static final FileType TGA
```


Stellt eine Truevision TGA (TARGA) Datei dar, die zum Speichern von von TRUEVISION entwickelten Bitmap-Digitalbildern verwendet wird.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/tga).


### JP_2 {#JP-2}
```
public static final FileType JP_2
```


Stellt eine JPEG 2000 Core Image File (.jp2) dar, die ein Bildkodierungssystem und einen hochmodernen Bildkompressionsstandard darstellt.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/jp2).


### JPF {#JPF}
```
public static final FileType JPF
```


Stellt eine JPEG 2000 Image File (.jpf) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/image/jpf).


### JPX {#JPX}
```
public static final FileType JPX
```


Stellt eine JPEG 2000 Image File (.jpx) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/jpx).


### JPM {#JPM}
```
public static final FileType JPM
```


Stellt eine JPEG 2000 Image File (.jpm) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/jpm).


### J2C {#J2C}
```
public static final FileType J2C
```


Stellt einen JPEG 2000 Code InputStream (.j2c) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/j2c).


### J2K {#J2K}
```
public static final FileType J2K
```


Stellt einen JPEG 2000 Code Stream (.j2k) dar, der ein Bild ist, das mittels Wavelet-Kompression statt DCT-Kompression komprimiert wurde.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/j2k).


### JPC {#JPC}
```
public static final FileType JPC
```


Stellt einen JPEG 2000 Code Stream (.jpc) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/jpc).


### JLS {#JLS}
```
public static final FileType JLS
```


Stellt eine JPEG-LS (JLS) Datei (.jls) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://fileinfo.com/extension/jls).


### DIB {#DIB}
```
public static final FileType DIB
```


Stellt eine Device Independent Bitmap File (.dib) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/dib).


### WMF {#WMF}
```
public static final FileType WMF
```


Stellt ein Windows Metafile (.wmf) dar, das das Microsoft Windows Metafile (WMF) zum Speichern von Vektor- sowie Bitmap-Bilddaten repräsentiert.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/wmf).


### WMZ {#WMZ}
```
public static final FileType WMZ
```


Stellt ein Compressed Windows Metafile (.wmz) dar, das das Microsoft Windows Metafile (WMF) in einem GZIP-Archiv komprimiert zum Speichern von Vektor- und Bitmap-Bilddaten repräsentiert.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://fileinfo.com/extension/wmz#compressed_windows_metafile).


### EMF {#EMF}
```
public static final FileType EMF
```


Stellt ein Enhanced Windows Metafile (.emf) dar, das grafische Bilder geräteunabhängig repräsentiert. Metadateien von EMF bestehen aus Datensätzen variabler Länge in chronologischer Reihenfolge, die das gespeicherte Bild nach dem Parsen auf jedem Ausgabegerät rendern können.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/emf).


### EMZ {#EMZ}
```
public static final FileType EMZ
```


Stellt ein Windows Compressed Enhanced Metafile (.emz) dar, das grafische Bilder geräteunabhängig durch GZIP komprimiert repräsentiert. Metadateien von EMF bestehen aus Datensätzen variabler Länge in chronologischer Reihenfolge, die das gespeicherte Bild nach dem Parsen auf jedem Ausgabegerät rendern können.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/emz).


### WEBP {#WEBP}
```
public static final FileType WEBP
```


Stellt ein WebP-Bild (.webp) dar, ein modernes rasterbasiertes Web‑Bilddateiformat, das auf verlustfreier und verlustbehafteter Kompression basiert. Es liefert die gleiche Bildqualität, reduziert jedoch die Dateigröße erheblich.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/webp).


### DNG {#DNG}
```
public static final FileType DNG
```


Stellt eine Digital Negative Specification (.dng) dar, ein digitales Kamerabildformat, das zur Speicherung von Rohdateien verwendet wird. Es wurde von Adobe im September 2004 entwickelt und wird hauptsächlich für die digitale Fotografie eingesetzt.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/dng).


### CDR {#CDR}
```
public static final FileType CDR
```


Stellt ein CorelDraw-Vektor‑Grafik‑Zeichnung (.cdr) dar, eine Vektor‑Zeichnungsdatei, die nativ mit CorelDRAW erstellt wird, um digital codierte und komprimierte Bilder zu speichern. Eine CDR‑Zeichnungsdatei enthält Text, Linien, Formen, Bilder, Farben und Effekte zur Vektorrepräsentation des Bildinhalts.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/cdr).


### CMX {#CMX}
```
public static final FileType CMX
```


Stellt ein Corel Exchange (.cmx) dar, das eine Zeichenbilddatei ist, die sowohl Vektorgrafiken als auch Bitmap-Grafiken enthalten kann.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/cmx).


### DJVU {#DJVU}
```
public static final FileType DJVU
```


Stellt ein DjVu Image (.djvu) dar, das ein Grafikdateiformat für gescannte Dokumente und Bücher ist, insbesondere für solche, die eine Kombination aus Text, Zeichnungen, Bildern und Fotografien enthalten.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/djvu).


### CGM {#CGM}
```
public static final FileType CGM
```


Stellt ein Computer Graphics Metafile (.cgm) dar, das ein kostenloses, plattformunabhängiges, internationales Standard-Metadateiformat zum Speichern und Austauschen von Vektorgrafiken (2D), Rastergrafiken und Text ist. CGM verwendet einen objektorientierten Ansatz und bietet viele Funktionen für die Bildproduktion.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/page-description-language/cgm).


### PCL {#PCL}
```
public static final FileType PCL
```


Stellt ein Printer Command Language-Dokument (.pcl) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/page-description-language/pcl).


### PSD {#PSD}
```
public static final FileType PSD
```


Stellt ein Adobe Photoshop-Dokument (.psd) dar, das das native Dateiformat von Adobe Photoshop ist und für Grafikdesign und -entwicklung verwendet wird.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/psd).


### PSB {#PSB}
```
public static final FileType PSB
```


Stellt ein Photoshop Large Document Format (.psb) dar, das für Grafikdesign und -entwicklung in Adobe Photoshop verwendet wird.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/psb).


### DCM {#DCM}
```
public static final FileType DCM
```


Stellt ein DICOM-Bild (.dcm) dar, das ein digitales Bild ist, das medizinische Informationen von Patienten wie MRTs, CT-Scans und Ultraschallbilder speichert.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/dcm).


### PS {#PS}
```
public static final FileType PS
```


Stellt eine PostScript-Datei (.ps) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/page-description-language/ps).


### EPS {#EPS}
```
public static final FileType EPS
```


Stellt eine Encapsulated PostScript-Datei (.eps) dar, die ein Encapsulated PostScript-Programm beschreibt, das das Aussehen einer einzelnen Seite definiert.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/page-description-language/eps).


### ODG {#ODG}
```
public static final FileType ODG
```


Stellt eine OpenDocument-Grafikdatei (.odg) dar, die von der Draw-Anwendung von Apache OpenOffice verwendet wird, um Zeichnungselemente als Vektorbilder zu speichern.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/odg).


### FODG {#FODG}
```
public static final FileType FODG
```


Stellt eine Flat XML ODF-Vorlage (.fodg) dar, die von der Draw-Anwendung von Apache OpenOffice verwendet wird, um Zeichnungselemente als Vektorbilder zu speichern.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/image/fodg).


### SVG {#SVG}
```
public static final FileType SVG
```


Stellt eine Scalable Vector Graphics-Datei (.svg) dar, die eine Scalable Vector Graphics-Datei ist, die ein XML-basiertes Textformat zur Beschreibung des Aussehens eines Bildes verwendet.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/page-description-language/svg).


### SVGZ {#SVGZ}
```
public static final FileType SVGZ
```


Stellt eine komprimierte Scalable Vector Graphics-Datei (.svgz) dar, die eine Scalable Vector Graphics-Datei ist, die ein XML-basiertes Textformat, komprimiert mit GZIP, zur Beschreibung des Aussehens eines Bildes verwendet.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://fileinfo.com/extension/svgz).


### OTG {#OTG}
```
public static final FileType OTG
```


Stellt eine OpenDocument-Grafikvorlage (.otg) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/image/otg).


### HTM {#HTM}
```
public static final FileType HTM
```


Stellt eine Hypertext Markup Language-Datei (.htm) dar, die die Dateierweiterung für Webseiten ist, die zur Anzeige in Browsern erstellt wurden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/web/html).


### HTML {#HTML}
```
public static final FileType HTML
```


Stellt eine Hypertext Markup Language-Datei (.html) dar, die die Dateierweiterung für Webseiten ist, die zur Anzeige in Browsern erstellt wurden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/web/html).


### MHT {#MHT}
```
public static final FileType MHT
```


Stellt ein MHTML-Webarchiv (.mht) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/web/mht).


### NSF {#NSF}
```
public static final FileType NSF
```


Stellt eine Lotus Notes-Datenbank (.nsf) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://fileinfo.com/extension/nsf).


### MBOX {#MBOX}
```
public static final FileType MBOX
```


Stellt eine E‑Mail-Postfachdatei (.mbox) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://fileinfo.com/extension/mbox).


### MHTML {#MHTML}
```
public static final FileType MHTML
```


Stellt eine MIME HTML-Datei (.mhtml) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/web/mhtml).


### XML {#XML}
```
public static final FileType XML
```


Stellt eine XML-Datei (.xml) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/web/xml).


### ONE {#ONE}
```
public static final FileType ONE
```


Stellt ein OneNote-Dokument (.one) dar, das von der Microsoft OneNote-Anwendung erstellt wurde. OneNote ermöglicht es Ihnen, Informationen zu sammeln, indem Sie die Anwendung wie ein Notizblock zum Aufnehmen von Notizen verwenden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/note-taking/one).


### PDF {#PDF}
```
public static final FileType PDF
```


Stellt eine Portable Document Format Datei (.pdf) dar, die in den 1990er Jahren von Adobe erstellt wurde. Der Zweck dieses Dateiformats war es, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einem Format einzuführen, das unabhängig von Anwendungssoftware, Hardware und Betriebssystemen ist.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/view/pdf).


### XPS {#XPS}
```
public static final FileType XPS
```


Stellt eine XML Paper Specification-Datei (.xps) dar, die Seitenlayoutdateien basierend auf von Microsoft erstellten XML Paper Specifications repräsentiert. Dieses Format wurde von Microsoft als Ersatz für das EMF-Dateiformat entwickelt und ist dem PDF-Dateiformat ähnlich, verwendet jedoch XML für das Layout, das Erscheinungsbild und die Druckinformationen eines Dokuments.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/page-description-language/xps).


### OXPS {#OXPS}
```
public static final FileType OXPS
```


Stellt eine OpenXPS-Datei (.oxps) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/page-description-language/oxps).


### TEX {#TEX}
```
public static final FileType TEX
```


Stellt ein LaTeX-Quelltextdokument (.tex) dar, das eine Sprache ist, die Programmierung sowie Markup‑Funktionen umfasst und zum Satz von Dokumenten verwendet wird.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/page-description-language/tex).


### OFD {#OFD}
```
public static final FileType OFD
```


Das Open Fixed‑layout Document (OFD)-Format, definiert durch GB/T 33190‑2016, zielt darauf ab, PDF in chinesischen öffentlichen Institutionen zu ersetzen.


### PPT {#PPT}
```
public static final FileType PPT
```


Stellt eine PowerPoint-Präsentation (.ppt) dar, die eine PowerPoint-Datei ist, die aus einer Sammlung von Folien für die Anzeige als Diashow besteht. Sie gibt das von Microsoft PowerPoint 97-2003 verwendete Binärdateiformat an.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/presentation/ppt).


### PPTX {#PPTX}
```
public static final FileType PPTX
```


Stellt eine PowerPoint Open XML-Präsentation (.pptx) dar, bei der es sich um Präsentationsdateien handelt, die mit der beliebten Microsoft PowerPoint-Anwendung erstellt wurden. Im Gegensatz zur vorherigen Version des Präsentationsdateiformats PPT, das binär war, basiert das PPTX-Format auf dem Microsoft PowerPoint Open XML-Präsentationsdateiformat.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/presentation/pptx).


### PPS {#PPS}
```
public static final FileType PPS
```


Stellt eine PowerPoint-Diashow (.pps) dar, die mit Microsoft PowerPoint für Diashow-Zwecke erstellt wird. Das Lesen und Erstellen von PPS-Dateien wird von Microsoft PowerPoint 97-2003 unterstützt.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/presentation/pps).


### PPSX {#PPSX}
```
public static final FileType PPSX
```


Stellt PowerPoint Open XML-Diashowdateien (.ppsx) dar, die mit Microsoft PowerPoint 2007 und höher für Diashow-Zwecke erstellt werden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/presentation/ppsx).


### ODP {#ODP}
```
public static final FileType ODP
```


Stellt eine OpenDocument-Präsentation (.odp) dar, die ein Präsentationsdateiformat ist, das von OpenOffice.org im OASISOpen-Standard verwendet wird.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/presentation/odp).


### FODP {#FODP}
```
public static final FileType FODP
```


Stellt eine OpenDocument-Präsentation (.fodp) dar, die die OpenDocument Flat XML-Präsentation repräsentiert.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://fileinfo.com/extension/fodp).


### POT {#POT}
```
public static final FileType POT
```


Stellt eine PowerPoint-Vorlage (.pot) dar, die Microsoft PowerPoint-Vorlagendateien sind, die von PowerPoint‑Versionen 97‑2003 erstellt wurden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/presentation/pot).


### PPTM {#PPTM}
```
public static final FileType PPTM
```


Stellt eine PowerPoint Open XML-Makro‑aktivierte Präsentation (.pptm) dar, die makro‑aktivierte Präsentationsdateien sind, die mit Microsoft PowerPoint 2007 oder neueren Versionen erstellt wurden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/presentation/pptm).


### POTX {#POTX}
```
public static final FileType POTX
```


Stellt eine PowerPoint Open XML-Präsentationsvorlage (.potx) dar, die Microsoft PowerPoint-Vortragsvorlagen sind, die mit Microsoft PowerPoint 2007 und höher erstellt wurden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/presentation/potx).


### POTM {#POTM}
```
public static final FileType POTM
```


Stellt eine PowerPoint Open XML-Makroaktivierte Präsentationsvorlage (.potm) dar, bei der es sich um Microsoft PowerPoint-Vorlagendateien mit Makrounterstützung handelt. POTM-Dateien werden mit PowerPoint 2007 oder höher erstellt und enthalten Standardeinstellungen, die zur Erstellung weiterer Präsentationsdateien verwendet werden können.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/presentation/potm).


### PPSM {#PPSM}
```
public static final FileType PPSM
```


Stellt eine PowerPoint Open XML-Makro‑aktivierte Folie (.ppsm) dar, die ein makro‑aktiviertes Diashow-Dateiformat ist, das mit Microsoft PowerPoint 2007 oder höher erstellt wurde.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/presentation/ppsm).


### OTP {#OTP}
```
public static final FileType OTP
```


Stellt eine OpenDocument-Präsentationsvorlage (.otp) dar, die Präsentationsvorlagendateien sind, die von Anwendungen im OASIS OpenDocument-Standardformat erstellt werden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/presentation/otp).


### XLS {#XLS}
```
public static final FileType XLS
```


Stellt eine Excel‑Tabelle (.xls) dar, die das Excel‑Binärdateiformat repräsentiert. Solche Dateien können mit Microsoft Excel sowie anderen ähnlichen Tabellenkalkulationsprogrammen wie OpenOffice Calc oder Apple Numbers erstellt werden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/xls).


### EXCEL_2003_XML {#EXCEL-2003-XML}
```
public static final FileType EXCEL_2003_XML
```


Stellt ein Excel 2003 XML (SpreadsheetML) (.xml) dar, das das Excel‑Binärdateiformat repräsentiert. Solche Dateien können mit Microsoft Excel sowie anderen ähnlichen Tabellenkalkulationsprogrammen wie OpenOffice Calc oder Apple Numbers erstellt werden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/xls).


### NUMBERS {#NUMBERS}
```
public static final FileType NUMBERS
```


Stellt Apple Numbers (.numbers) dar, das ein Excel‑ähnliches Binärdateiformat repräsentiert. Solche Dateien können mit der Apple Numbers‑Anwendung erstellt werden.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://fileinfo.com/extension/numbers).


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Stellt eine Microsoft Excel Open XML-Tabelle (.xlsx) dar, ein bekanntes Format für Microsoft Excel‑Dokumente, das von Microsoft mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/xlsx).


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Stellt eine Excel Open XML-Makro‑aktivierte Tabelle (.xlsm) dar, eine Art Tabellendatei, die Makros unterstützt.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/xlsm).


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Stellt eine Excel‑Binär‑Tabelle (.xlsb) dar, die das Excel‑Binärdateiformat spezifiziert. Es ist eine Sammlung von Datensätzen und Strukturen, die den Inhalt einer Excel‑Arbeitsmappe festlegen.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/xlsb).


### CSV {#CSV}
```
public static final FileType CSV
```


Stellt eine Komma‑separierte Werte‑Datei (.csv) dar, die Klartextdateien sind, die Datensätze mit kommagetrennten Werten enthalten.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/csv).


### TSV {#TSV}
```
public static final FileType TSV
```


Stellt eine Tab‑separierte Werte‑Datei (.tsv) dar, die Daten enthält, die in Klartextformat durch Tabs getrennt sind.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/tsv).


### ODS {#ODS}
```
public static final FileType ODS
```


Stellt ein OpenDocument‑Tabellenkalkulationsdokument (.ods) dar, das für das OpenDocument‑Tabellenkalkulationsformat steht und vom Benutzer editierbar ist. Daten werden in ODF‑Dateien in Zeilen und Spalten gespeichert.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/ods).


### FODS {#FODS}
```
public static final FileType FODS
```


Stellt eine OpenDocument Flat XML‑Tabelle (.fods) dar.
Es ist ein auf XML basierendes Tabellenkalkulationsdokumentformat, das von OpenOffice und LibreOffice verwendet wird.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/fods).


### OTS {#OTS}
```
public static final FileType OTS
```


Stellt eine OpenDocument-Tabellenvorlage (.ots) dar.
Es ist ein Vorlagendokumentformat, das von OpenOffice und LibreOffice für Tabellenkalkulationen verwendet wird.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/ots).


### XLAM {#XLAM}
```
public static final FileType XLAM
```


Stellt ein Microsoft Excel Add‑In (.xlam) dar.
Es ist ein Dateiformat, das von Microsoft Excel verwendet wird, um Add‑Ins mit benutzerdefinierter Funktionalität zu erstellen.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://fileinfo.com/extension/xlam).


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Stellt eine Microsoft Excel Makro‑aktivierte Vorlage (.xltm) dar, die von Microsoft Excel als makroaktivierte Vorlagendateien erzeugt wird. XLTM‑Dateien ähneln XLTX in ihrer Struktur, wobei letztere keine Erstellung von Vorlagendateien mit Makros unterstützt.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/xltm).


### XLT {#XLT}
```
public static final FileType XLT
```


Stellt eine Microsoft Excel Vorlage (.xlt) dar, das sind Vorlagendateien, die mit Microsoft Excel, einer Tabellenkalkulationsanwendung, die Teil der Microsoft Office‑Suite ist, erstellt werden. Microsoft Office 97‑2003 unterstützte das Erstellen neuer XLT‑Dateien sowie das Öffnen dieser.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/xlt).


### XLTX {#XLTX}
```
public static final FileType XLTX
```


Stellt eine Excel Open XML Spreadsheet Template (.xltx) dar, die Microsoft Excel Templates basierend auf den Office OpenXML file format specifications repräsentiert. Sie wird verwendet, um eine Standardvorlagendatei zu erstellen, die genutzt werden kann, um XLSX-Dateien mit denselben im XLTX-File angegebenen Einstellungen zu erzeugen.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/xltx).


### SXC {#SXC}
```
public static final FileType SXC
```


Stellt eine StarOffice Calc‑Tabellenkalkulation (.sxc) dar.
Es ist ein Tabellendokument, das mit StarOffice Calc, einem Tabellenkalkulationsprogramm, erstellt wurde.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/spreadsheet/sxc).


### MPP {#MPP}
```
public static final FileType MPP
```


Stellt eine Microsoft Project‑Datei (.mpp) dar, die eine Microsoft Project‑Datendatei ist, die Informationen zum Projektmanagement integriert speichert.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/project-management/mpp).


### MPT {#MPT}
```
public static final FileType MPT
```


Stellt eine Microsoft Project‑Vorlage (.mpt) dar, die grundlegende Informationen und Struktur sowie Dokumenteinstellungen für die Erstellung von .MPP‑Dateien enthält.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/project-management/mpt).


### MPX {#MPX}
```
public static final FileType MPX
```


Stellt eine Microsoft Project Exchange‑Datei (.mpx) dar, ein ASCII‑Dateiformat zum Übertragen von Projektinformationen zwischen Microsoft Project (MSP) und anderen Anwendungen, die das MPX‑Dateiformat unterstützen, wie Primavera Project Planner, Sciforma und Timerline Precision Estimating.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/project-management/mpx).


### AS {#AS}
```
public static final FileType AS
```


Stellt eine ActionScript‑Datei (.as) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/programming/as).


### AS_3 {#AS-3}
```
public static final FileType AS_3
```


Stellt eine ActionScript‑Datei (.as3) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://datatypes.net/open-as3-files).


### ASM {#ASM}
```
public static final FileType ASM
```


Stellt eine Assembler‑Quellcodedatei (.asm) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/cad/asm).


### BAT {#BAT}
```
public static final FileType BAT
```


Stellt eine DOS‑Batchdatei (.bat) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/executable/bat).


### C {#C}
```
public static final FileType C
```


Stellt eine C/C++‑Quellcodedatei (.c) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/programming/c).


### CC {#CC}
```
public static final FileType CC
```


Stellt eine C++‑Quellcodedatei (.cc) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/programming/cc).


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Stellt eine CMake‑Datei (.cmake) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/programming/cmake).


### CPP {#CPP}
```
public static final FileType CPP
```


Stellt eine C++‑Quellcodedatei (.cpp) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/programming/cpp).


### CS {#CS}
```
public static final FileType CS
```


Stellt eine C# Quellcodedatei (.cs) dar, die eine Quellcodedatei für die Programmiersprache C# ist. Sie wurde von Microsoft für die Verwendung mit dem .NET Framework eingeführt.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/programming/cs).


### VB {#VB}
```
public static final FileType VB
```


Stellt eine Visual Basic Projekt-Item-Datei (.vb) dar, die eine Quellcodedatei ist, die in der Visual Basic Sprache erstellt wurde. Sie wurde von Microsoft für die Entwicklung von .NET-Anwendungen erstellt.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/programming/vb).


### CSS {#CSS}
```
public static final FileType CSS
```


Stellt eine Cascading‑Style‑Sheet‑Datei (.css) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/web/css).


### CXX {#CXX}
```
public static final FileType CXX
```


Stellt eine C++‑Quellcodedatei (.cxx) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/programming/cxx).


### DIFF {#DIFF}
```
public static final FileType DIFF
```


Stellt eine Patch‑Datei (.diff) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/programming/diff).


### ERB {#ERB}
```
public static final FileType ERB
```


Stellt ein Ruby‑ERB‑Skript (.erb) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/programming/erb).


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Stellt eine Groovy‑Quellcodedatei (.groovy) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/programming/groovy).


### H {#H}
```
public static final FileType H
```


Stellt eine C/C++/Objective‑C‑Headerdatei (.h) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/programming/h).


### HAML {#HAML}
```
public static final FileType HAML
```


Stellt eine Haml‑Quellcodedatei (.haml) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/programming/haml).


### HH {#HH}
```
public static final FileType HH
```


Stellt eine C++‑Headerdatei (.hh) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/programming/hh).


### JAVA {#JAVA}
```
public static final FileType JAVA
```


Stellt eine Java‑Quellcodedatei (.java) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/programming/java).


### JS {#JS}
```
public static final FileType JS
```


Stellt eine JavaScript-Datei (.js) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/web/js).


### JSON {#JSON}
```
public static final FileType JSON
```


Stellt eine JavaScript Object Notation-Datei (.json) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/web/json).


### LESS {#LESS}
```
public static final FileType LESS
```


Stellt eine LESS-Stylesheet-Datei (.less) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/web/less).


### LOG {#LOG}
```
public static final FileType LOG
```


Stellt eine Protokolldatei (.log) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/database/log).


### M {#M}
```
public static final FileType M
```


Stellt eine Objective-C-Implementierungsdatei (.m) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://fileinfo.com/extension/m).


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Stellt ein Xcode-Makefile-Skript (.make) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/programming/make).


### MD {#MD}
```
public static final FileType MD
```


Stellt eine Markdown-Dokumentationsdatei (.md) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/word-processing/md).


### ML {#ML}
```
public static final FileType ML
```


Stellt eine ML-Quellcodedatei (.ml) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/programming/ml).


### MM {#MM}
```
public static final FileType MM
```


Stellt eine Objective-C++-Quelldatei (.mm) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/programming/mm).


### PHP {#PHP}
```
public static final FileType PHP
```


Stellt eine PHP-Quellcodedatei (.php) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/programming/php).


### PL {#PL}
```
public static final FileType PL
```


Stellt ein Perl-Skript (.pl) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/programming/pl).


### PROPERTIES {#PROPERTIES}
```
public static final FileType PROPERTIES
```


Stellt eine Java-Properties-Datei (.properties) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://fileinfo.com/extension/properties).


### PY {#PY}
```
public static final FileType PY
```


Stellt ein Python-Skript (.py) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/programming/py).


### RB {#RB}
```
public static final FileType RB
```


Stellt eine Ruby-Quellcodedatei (.rb) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/programming/rb).


### RST {#RST}
```
public static final FileType RST
```


Stellt eine reStructuredText-Datei (.rst) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/programming/rst).


### SASS {#SASS}
```
public static final FileType SASS
```


Stellt eine Syntactically Awesome StyleSheets-Datei (.sass) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/web/sass).


### SCALA {#SCALA}
```
public static final FileType SCALA
```


Stellt eine Scala-Quellcodedatei (.scala) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/programming/scala).


### SCM {#SCM}
```
public static final FileType SCM
```


Stellt eine Scheme-Quellcodedatei (.scm) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/programming/scm).


### SCRIPT {#SCRIPT}
```
public static final FileType SCRIPT
```


Stellt eine generische Skriptdatei (.script) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/programming/script).


### SH {#SH}
```
public static final FileType SH
```


Stellt ein Bash-Shell-Skript (.sh) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/cs/programming/sh).


### SML {#SML}
```
public static final FileType SML
```


Stellt eine Standard-ML-Quellcodedatei (.sml) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://fileinfo.com/extension/sml).


### SQL {#SQL}
```
public static final FileType SQL
```


Stellt eine Structured Query Language-Datendatei (.sql) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/database/sql).


### VIM {#VIM}
```
public static final FileType VIM
```


Stellt eine Vim-Einstellungsdatei (.vim) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://fileinfo.com/extension/vim).


### YAML {#YAML}
```
public static final FileType YAML
```


Stellt ein YAML-Dokument (.yaml) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/programming/yaml).


### DOC {#DOC}
```
public static final FileType DOC
```


Stellt ein Microsoft-Word-Dokument (.doc) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/word-processing/doc).


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Stellt eine Microsoft Word Open XML Dokument (.docx)-Datei dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/word-processing/docx).


### CHM {#CHM}
```
public static final FileType CHM
```


Stellt eine Microsoft Compiled HTML Help-Datei (.chm) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/web/chm).


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Stellt eine Word Open XML Makro-aktivierte Dokument (.docm)-Datei dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/word-processing/docm).


### DOT {#DOT}
```
public static final FileType DOT
```


Stellt eine Word Dokumentvorlage (.dot)-Datei dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/word-processing/dot).


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Stellt eine Word Open XML Dokumentvorlage (.dotx)-Datei dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/word-processing/dotx).


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Stellt eine Word Open XML Makro-aktivierte Dokumentvorlage (.dotm)-Datei dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/word-processing/dotm).


### RTF {#RTF}
```
public static final FileType RTF
```


Stellt eine Rich Text Format Datei (.rtf) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/word-processing/rtf).


### TXT {#TXT}
```
public static final FileType TXT
```


Stellt eine Nur-Text-Datei (.txt) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/word-processing/txt).


### ODT {#ODT}
```
public static final FileType ODT
```


Stellt ein OpenDocument Textdokument (.odt) dar.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/word-processing/odt).


### OTT {#OTT}
```
public static final FileType OTT
```


Stellt eine OpenDocument Dokumentvorlage (.ott) dar.
Es ist ein Vorlagendokument, das in Übereinstimmung mit dem OpenDocument‑Standardformat von OASIS erstellt wurde.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/word-processing/ott).


### VCF {#VCF}
```
public static final FileType VCF
```


Stellt eine vCard-Datei (.vcf) dar, die ein digitales Dateiformat zum Speichern von Kontaktinformationen ist.
Es wird häufig für den Datenaustausch zwischen beliebten Informationsaustausch‑Anwendungen verwendet.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/email/vcf).


### AI {#AI}
```
public static final FileType AI
```


Stellt eine Adobe Illustrator-Datei (.ai) dar, die ein Dateiformat für Adobe Illustrator-Zeichnungen ist.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/image/ai).


### PSM1 {#PSM1}
```
public static final FileType PSM1
```


Stellt eine PowerShell‑Skriptmodul‑Datei (.psm1) dar.
Es ist ein Dateiformat für PowerShell‑Modul‑Skripte.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://fileinfo.com/extension/psm1).


### PS1 {#PS1}
```
public static final FileType PS1
```


Stellt eine PowerShell‑Skript‑Datei (.ps1) dar.
Es ist ein Dateiformat für Windows‑PowerShell‑Cmdlet‑Dateien.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://fileinfo.com/extension/ps1).


### PSD1 {#PSD1}
```
public static final FileType PSD1
```


Stellt eine PowerShell‑Skriptmodul‑Manifest‑Datei (.psd1) dar.
Es ist ein Dateiformat für PowerShell‑Modul‑Manifest‑Skripte.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://fileinfo.com/extension/psd1).


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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


Ordnet eine Dateierweiterung einem Dateityp zu.


Diese Methode nimmt eine Dateierweiterung, mit oder ohne den Punkt \".\", und gibt den entsprechenden Dateityp zurück, falls er unterstützt wird.
Wenn der Dateityp nicht unterstützt wird, gibt er den Standard-[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN)-Dateityp zurück.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | extension | java.lang.String | Die Dateierweiterung mit oder ohne den Punkt ".". |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromFilePath(String filePath) {#fromFilePath-java.lang.String-}
```
public static FileType fromFilePath(String filePath)
```


Extrahiert die Dateierweiterung aus einem Dateinamen oder Dateipfad und ordnet sie einem Dateityp zu.


Wenn der Dateityp unterstützt wird, gibt die Methode den entsprechenden zurück
FileType
,
ansonsten gibt sie den Standard-[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN)-Dateityp zurück.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Dateiname oder der Dateipfad. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromMediaType(String mediaType) {#fromMediaType-java.lang.String-}
```
public static FileType fromMediaType(String mediaType)
```


Ordnet einen Dateimedientyp einem Dateityp zu. Zum Beispiel wird 'application/pdf' dem [PDF](../../com.groupdocs.viewer/filetype#PDF) zugeordnet.


Diese Methode nimmt einen Dateimedientyp als Eingabe und ordnet ihn dem entsprechenden zu
FileType
. Wenn der Medientyp
unterstützt, gibt die Methode den entsprechenden Dateityp zurück. Wenn der Medientyp nicht unterstützt wird, gibt sie den Standard zurück
[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | mediaType | java.lang.String | Der Dateimedientyp, z. B. 'application/pdf'. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if found, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream stream)
```


Ermittelt den Dateityp durch Lesen der Dateisignatur.


Diese Methode nimmt einen Eingabestream, der eine Datei darstellt, und versucht, den Dateityp zu erkennen, indem sie die Dateisignatur analysiert. Der
Die Dateisignatur ist eine eindeutige Byte-Sequenz am Anfang der Datei, die ihren Dateityp angibt. Die Methode
liest die Dateisignatur aus dem Eingabestream und vergleicht sie mit bekannten Dateisignaturen unterstützter Dateitypen.
Wenn eine Übereinstimmung gefunden wird, gibt die Methode den entsprechenden Dateityp zurück. Wenn keine Übereinstimmung gefunden wird, gibt sie den Standard zurück
[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | stream | java.io.InputStream | Der Eingabestream, der die Datei darstellt. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, String password) {#fromStream-java.io.InputStream-java.lang.String-}
```
public static FileType fromStream(InputStream stream, String password)
```


Ermittelt den Dateityp durch Lesen der Dateisignatur.


Diese Methode analysiert die Dateisignatur, die eine eindeutige Byte-Sequenz am Anfang der Datei ist, um zu bestimmen
den Dateityp. Sie liest die Dateisignatur aus dem bereitgestellten Eingabestream und vergleicht sie mit bekannten Dateisignaturen
unterstützter Dateitypen. Wenn eine Übereinstimmung gefunden wird, gibt die Methode den entsprechenden Dateityp zurück. Wenn keine Übereinstimmung gefunden wird, gibt sie
gibt den Standard-[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN)-Dateityp zurück.


Wenn die Datei verschlüsselt ist und ein Passwort zum Öffnen benötigt, sollte das Passwort als Parameter an diese
Methode übergeben werden. Das Passwort wird verwendet, um die Datei zu entschlüsseln und ihre Signatur zur Bestimmung des Dateityps zu analysieren.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | stream | java.io.InputStream | Der Eingabestream, der die Datei darstellt. |
|
|  | Passwort | java.lang.String | Das Passwort, um die Datei zu öffnen. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, ILogger logger) {#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, ILogger logger)
```


Ermittelt den Dateityp durch Lesen der Dateisignatur.


Diese Methode analysiert die Dateisignatur, die eine eindeutige Byte-Sequenz am Anfang der Datei ist, um zu bestimmen
den Dateityp. Sie liest die Dateisignatur aus dem bereitgestellten Eingabestream und vergleicht sie mit bekannten Dateisignaturen
unterstützter Dateitypen. Wenn eine Übereinstimmung gefunden wird, gibt die Methode den entsprechenden Dateityp zurück. Wenn keine Übereinstimmung gefunden wird, gibt sie
gibt den Standard-[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN)-Dateityp zurück.


Ein Logger kann bereitgestellt werden, um relevante Informationen oder Fehler während des Dateityp-Erkennungsprozesses zu protokollieren. Der Logger
sollte das ILogger-Interface implementieren. Wenn kein Logger bereitgestellt wird, erzeugt der Erkennungsprozess keine
Logausgabe.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | stream | java.io.InputStream | Der Eingabestream, der die Datei darstellt. |
|
|  | Logger | com.groupdocs.foundation.logging.ILogger | Der Logger zum Protokollieren von Informationen oder Fehlern. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, String password, ILogger logger) {#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, String password, ILogger logger)
```


Ermittelt den Dateityp durch Lesen der Dateisignatur.


Diese Methode analysiert die Dateisignatur, die eine eindeutige Byte-Sequenz am Anfang der Datei ist, um zu bestimmen
den Dateityp. Sie liest die Dateisignatur aus dem bereitgestellten Eingabestream und vergleicht sie mit bekannten Dateisignaturen
unterstützter Dateitypen. Wenn eine Übereinstimmung gefunden wird, gibt die Methode den entsprechenden Dateityp zurück. Wenn keine Übereinstimmung gefunden wird, gibt sie
gibt den Standard-[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN)-Dateityp zurück.


Ein Passwort kann angegeben werden, wenn die Datei verschlüsselt oder geschützt ist. Das Passwort wird verwendet, um die Datei vor
der Analyse der Dateisignatur zu öffnen. Wenn die Datei kein Passwort benötigt, kann dieser Parameter auf null gesetzt werden.


Ein Logger kann bereitgestellt werden, um relevante Informationen oder Fehler während des Dateityp-Erkennungsprozesses zu protokollieren. Der Logger
sollte das ILogger-Interface implementieren. Wenn kein Logger bereitgestellt wird, erzeugt der Erkennungsprozess keine
Logausgabe.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | stream | java.io.InputStream | Der Eingabestream, der die Datei darstellt. |
|
|  | Passwort | java.lang.String | Das Passwort, um die Datei zu öffnen. |
|
|  | Logger | com.groupdocs.foundation.logging.ILogger | Der Logger zum Protokollieren von Informationen oder Fehlern. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Ruft die unterstützten Dateitypen ab.


Diese Methode gibt eine Sequenz aller vom System unterstützten Dateitypen zurück. Die Dateitypen repräsentieren verschiedene
Dokumentenformate, die vom System verarbeitet oder erkannt werden können.
***Learn more**
* Learn more about the supported document formats: [Full list of supported file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/)*


**Returns:**
java.util.List<com.groupdocs.viewer.FileType> - eine Sequenz unterstützter Dateitypen.

### detectCharset(String filePath) {#detectCharset-java.lang.String-}
```
public static Charset detectCharset(String filePath)
```


Versucht, den Zeichensatz von Textdateien [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV) und [CSV](../../com.groupdocs.viewer/filetype#CSV) anhand des Pfads zu erkennen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Dateiname oder der Dateipfad. |
|

**Returns:**
java.nio.charset.Charset - Charset oder null, wenn die Erkennung eines Dateicharsets fehlschlägt.

**Example:**


Charset charset = FileType.detectCharset(\"message.txt\");
     

### detectCharset(InputStream stream) {#detectCharset-java.io.InputStream-}
```
public static Charset detectCharset(InputStream stream)
```


Versucht, den Zeichensatz von Textdateien [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV) und [CSV](../../com.groupdocs.viewer/filetype#CSV) anhand des Streams zu erkennen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | stream | java.io.InputStream | Der Dateistream. |
|

**Returns:**
java.nio.charset.Charset - Charset oder null, wenn die Erkennung eines Dateicharsets fehlschlägt.

**Example:**


InputStream stream = new FileInputStream(\"message.txt\");
Charset charset = FileType.detectCharset(stream);
     

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Ermittelt den Namen des Dateiformats, z.\u00a0B. \"Microsoft Word Document\".


**Returns:**
java.lang.String - der Name des Dateiformats.

### getExtension() {#getExtension--}
```
public final String getExtension()
```


Ermittelt das Dateierweiterungs‑Suffix (einschließlich des Punktes \".\"), z.\u00a0B. \".doc\".


**Returns:**
java.lang.String - die Dateierweiterungsendung.

### toString() {#toString--}
```
public String toString()
```


Gibt eine String-Darstellung des aktuellen Objekts zurück.


**Returns:**
java.lang.String – eine String-Darstellung des aktuellen Objekts.

