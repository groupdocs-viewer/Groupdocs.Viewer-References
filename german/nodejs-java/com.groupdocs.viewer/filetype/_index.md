---
title: "FileType"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt den Dateityp dar."
type: docs
weight: 14
url: /de/nodejs-java/com.groupdocs.viewer/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, com.groupdocs.viewer.caching.Cacheable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>, Cacheable
```

Stellt den Dateityp dar. Bietet Methoden, um eine Liste aller von der GroupDocs.Viewer-Komponente unterstützten Dateitypen zu erhalten.

Das FileType-Enum stellt Konstanten bereit, die verschiedene Dateitypen repräsentieren, die von der GroupDocs.Viewer-Komponente unterstützt werden. Sie können die Methoden dieses Enums verwenden, um eine Liste aller unterstützten Dateitypen zu erhalten oder zu prüfen, ob ein bestimmter Dateityp unterstützt wird.

Beispielhafte Verwendung:

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
## Felder

| Feld | Beschreibung |
| --- | --- |
| [UNKNOWN](#UNKNOWN) | Stellt einen unbekannten Dateityp dar. |
| [ZIP](#ZIP) | Stellt eine gezippte Datei (.zip) dar, die eine oder mehrere Dateien oder Verzeichnisse enthalten kann. |
| [TAR](#TAR) | Stellt ein konsolidiertes Unix-Dateiarchiv (.tar) dar, das zum Sammeln einer oder mehrerer Dateien erstellt wurde. |
| [XZ](#XZ) | Stellt eine XZ-Datei (.xz) dar, die mit einem hochkomprimierenden Algorithmus auf Basis des LZMA-Algorithmus komprimiert wurde. |
| [TXZ](#TXZ) | Stellt ein konsolidiertes Unix-Dateiarchiv (.txz, .tar.xz) dar, das zum Sammeln einer oder mehrerer Dateien erstellt wurde. |
| [TARXZ](#TARXZ) | Stellt ein konsolidiertes Unix-Dateiarchiv (.txz, .tar.xz) dar, das zum Sammeln einer oder mehrerer Dateien erstellt wurde. |
| [TGZ](#TGZ) | Stellt ein konsolidiertes Unix-Dateiarchiv (.tgz, .tar.gz) dar, das zum Sammeln einer oder mehrerer Dateien erstellt wurde. |
| [TARGZ](#TARGZ) | Stellt ein konsolidiertes Unix-Dateiarchiv (.tgz, .tar.gz) dar, das zum Sammeln einer oder mehrerer Dateien erstellt wurde. |
| [BZ_2](#BZ-2) | Stellt eine Bzip2-komprimierte Datei (.bz2) dar, die mit der Open-Source-Kompressionsmethode BZIP2 erzeugt wurde. |
| [RAR](#RAR) | Stellt eine Roshal-Archiv (.rar) komprimierte Datei dar, die mit der RAR (WINRAR Version 4) Kompressionsmethode erzeugt wurde. |
| [GZ](#GZ) | Stellt eine Gnu Zipped File (.gz) komprimierte Datei dar, die mit der gzip-Kompressionsanwendung erstellt wurde. |
| [GZIP](#GZIP) | Stellt eine Gnu Zipped File (.gzip) komprimierte Datei dar, die als kostenloses Dienstprogramm zur Ersetzung des Compress-Programms in Unix-Systemen eingeführt wurde. |
| [SEVEN_ZIP](#SEVEN-ZIP) | Stellt eine 7Zip (.7z, .7zip) Datei dar, die ein kostenloser Open-Source-Archivierer mit LZMA- und LZMA2-Kompression ist. |
| [CPIO](#CPIO) | Cpio ist ein allgemeines Dateiarchivierungswerkzeug und das zugehörige Dateiformat. |
| [ZSTANDARD](#ZSTANDARD) | ZST-Datei ist eine komprimierte Datei, die mit dem Zstandard (zstd)-Kompressionsalgorithmus erzeugt wird. |
| [TZST](#TZST) | TZST-Dateien (.tar.zst, .tzst) sind Zstandard-Archive (ZST), die intern ein Consolidated Unix File Archive (Tar) enthalten und mit einem Unix-basierten Dienstprogramm zum Sammeln von einer oder mehreren Dateien erstellt wurden. |
| [TAR_ZST](#TAR-ZST) | TZST-Dateien (.tar.zst, .tzst) sind Zstandard-Archive (ZST), die intern ein Consolidated Unix File Archive (Tar) enthalten und mit einem Unix-basierten Dienstprogramm zum Sammeln von einer oder mehreren Dateien erstellt wurden. |
| [ISO](#ISO) | ISO-Optical-Disc-Image ist eine unkomprimierte Archiv-Disk-Image-Datei, die den Inhalt der gesamten Daten auf einer optischen Disc wie CD oder DVD gemäß dem ISO-9660-Standard darstellt. |
| [LHA](#LHA) | LHA oder LZH ist ein Freeware-Kompressionswerkzeug und zugehöriges Dateiformat. |
| [CAB](#CAB) | Cabinet (oder CAB) ist ein Archivdateiformat für Microsoft Windows. |
| [DXF](#DXF) | Stellt eine Drawing Exchange Format File (.dxf) dar, die eine getaggte Datenrepräsentation einer AutoCAD-Zeichnungsdatei ist. |
| [DWG](#DWG) | Stellt eine AutoCAD Drawing Database File (.dwg) dar, die proprietäre Binärdateien zur Speicherung von 2D- und 3D-Design-Daten repräsentiert. |
| [DWT](#DWT) | Stellt eine AutoCAD Drawing Template (.dwt) dar, die eine AutoCAD-Zeichnungsvorlage ist, die als Ausgangspunkt für das Erstellen von Zeichnungen dient, die als DWG-Dateien gespeichert werden können. |
| [STL](#STL) | Stellt eine Stereolithography File (.stl) dar, ein austauschbares Dateiformat, das 3‑dimensionale Oberflächengeometrie repräsentiert. |
| [IFC](#IFC) | Stellt eine Industry Foundation Classes File (.ifc) dar, ein Dateiformat, das internationale Standards für den Import und Export von Bauobjekten und deren Eigenschaften etabliert. |
| [DWF](#DWF) | Stellt eine Design Web Format File (.dwf) dar, ein komprimiertes Dateiformat zum Anzeigen, Überprüfen oder Drucken von 2D/3D-Zeichnungen. |
| [FBX](#FBX) | Stellt eine Autodesk FBX Interchange File (FilmBoX) (.fbx) dar, ein 3D‑Modellformat. |
| [DWFX](#DWFX) | Stellt eine Design Web Format File XPS (.dwfx) dar, ein komprimiertes Format zum Anzeigen, Überprüfen oder Drucken von 2D/3D-Zeichnungen als XPS-Dokument. |
| [DGN](#DGN) | Stellt eine MicroStation Design File (.dgn) dar, die Zeichnungen sind, die von CAD-Anwendungen wie MicroStation und Intergraph Interactive Graphics Design System erstellt und unterstützt werden. |
| [PLT](#PLT) | Stellt eine PLT (HPGL) File (.plt) dar, eine vektorbasierte Plotterdatei, die von Autodesk, Inc. eingeführt wurde. |
| [CF2](#CF2) | Stellt eine Common File Format File (.cf2) dar. |
| [OBJ](#OBJ) | Stellt eine Wavefront 3D Object File (.obj) dar, eine 3D‑Bilddatei, die von Wavefront Technologies eingeführt wurde. |
| [HPG](#HPG) | Stellt eine PLT (HPGL) File (.hpg) dar. |
| [IGS](#IGS) | Stellt eine Initial Graphics Exchange Specification (IGES) File (.igs) dar. |
| [VSD](#VSD) | Stellt eine Visio Drawing File (.vsd) dar, die Zeichnungen sind, die mit der Microsoft Visio-Anwendung erstellt wurden, um eine Vielzahl von grafischen Objekten und deren Verbindungen darzustellen. |
| [VSDX](#VSDX) | Stellt eine Visio Drawing File (.vsdx) dar, die das Microsoft Visio-Dateiformat repräsentiert, das ab Microsoft Office 2013 eingeführt wurde. |
| [VSS](#VSS) | Stellt eine Visio-Stencil-Datei (.vss) dar, die Stencil-Dateien sind, die mit Microsoft Visio 2007 und früher erstellt wurden. |
| [VSSX](#VSSX) | Stellt eine Visio-Stencil-Datei (.vssx) dar, die Zeichenstencil-Dateien sind, die mit Microsoft Visio 2013 und neuer erstellt wurden. |
| [VSDM](#VSDM) | Stellt eine Visio-Makro‑aktivierte Zeichnung (.vsdm) dar, die Zeichen‑Dateien sind, die mit der Microsoft Visio‑Anwendung erstellt wurden und Makros unterstützen. |
| [VST](#VST) | Stellt eine Visio-Zeichnungsvorlage (.vst) dar, die Vektorbilder sind, die mit Microsoft Visio erstellt wurden. |
| [VSTX](#VSTX) | Stellt eine Visio-Zeichnungsvorlage (.vstx) dar, die Vorlagendateien für Zeichnungen sind, die mit Microsoft Visio 2013 und neuer erstellt wurden. |
| [VSTM](#VSTM) | Stellt eine Visio-Makro‑aktivierte Zeichnungsvorlage (.vstm) dar, die Vorlagendateien sind, die mit Microsoft Visio erstellt wurden und Makros unterstützen. |
| [VSSM](#VSSM) | Stellt eine Visio-Makro‑aktivierte Stencil-Datei (.vssm) dar, die Microsoft Visio Stencil‑Dateien sind, die Makros unterstützen. |
| [VSX](#VSX) | Stellt eine Visio-Stencil-XML-Datei (.vsx) dar, die sich auf Stencil‑Dateien bezieht, die aus Zeichnungen und Formen bestehen und zum Erstellen von Diagrammen in Microsoft Visio verwendet werden. |
| [VTX](#VTX) | Stellt eine Visio-Vorlagen‑XML-Datei (.vtx) dar, die eine Microsoft Visio‑Zeichnungsvorlage ist, die im XML‑Dateiformat auf dem Datenträger gespeichert wird. |
| [VDW](#VDW) | Stellt eine Visio-Webzeichnung (.vdw) dar, die die für die Darstellung einer Webzeichnung erforderlichen Streams und Speicherbereiche spezifiziert. |
| [VDX](#VDX) | Stellt eine Visio-Zeichnungs‑XML-Datei (.vdx) dar, die jede in Microsoft Visio erstellte Zeichnung oder Diagramm repräsentiert, die jedoch im XML‑Format mit der Erweiterung .VDX gespeichert wird. |
| [EPUB](#EPUB) | Stellt eine Open-eBook-Datei (.epub) dar, die ein eBook‑Dateiformat ist, das ein standardisiertes digitales Publikationsformat für Verlage und Leser bereitstellt. |
| [MOBI](#MOBI) | Stellt ein Mobipocket-eBook (.mobi) dar, das eines der am weitesten verbreiteten eBook‑Dateiformate ist. |
| [AZW_3](#AZW-3) | Amazon Kindle Format 8 (KF8) eBook ist das digitale Dateiformat, das für Amazon Kindle‑Geräte entwickelt wurde. |
| [MSG](#MSG) | Stellt eine Outlook-Mailnachricht (.msg) dar, die ein Dateiformat ist, das von Microsoft Outlook und Exchange zum Speichern von E‑Mail‑Nachrichten, Kontakten, Terminen oder anderen Aufgaben verwendet wird. |
| [EML](#EML) | Stellt eine E‑Mail‑Nachricht (.eml) dar, die E‑Mail‑Nachrichten repräsentiert, die mit Outlook und anderen relevanten Anwendungen gespeichert wurden. |
| [EMLX](#EMLX) | Stellt eine Apple‑Mail‑Nachricht (.emlx) dar, die von Apple implementiert und entwickelt wurde. |
| [PST](#PST) | Stellt eine Outlook-Personal‑Information‑Store‑Datei (.pst) dar, die Outlook-Personal‑Storage‑Files (auch Personal Storage Table genannt) repräsentiert, die eine Vielzahl von Benutzerdaten speichern. |
| [OST](#OST) | Stellt eine Outlook-Offline‑Datendatei (.ost) dar, die die Postfachdaten eines Benutzers im Offline‑Modus auf einem lokalen Rechner nach der Registrierung beim Exchange‑Server mittels Microsoft Outlook repräsentiert. |
| [TIF](#TIF) | Stellt eine Tagged‑Image‑File (.tif) dar, die Rasterbilder repräsentiert, die für die Verwendung auf einer Vielzahl von Geräten gedacht sind, die diesem Dateiformatstandard entsprechen. |
| [TIFF](#TIFF) | Stellt ein Tagged‑Image‑File‑Format (.tiff) dar, das Rasterbilder repräsentiert, die für die Verwendung auf einer Vielzahl von Geräten gedacht sind, die diesem Dateiformatstandard entsprechen. |
| [JPG](#JPG) | Stellt ein JPEG‑Bild (.jpg) dar, das ein Bildformat ist, das mit verlustbehafteter Kompression gespeichert wird. |
| [JPEG](#JPEG) | Stellt ein JPEG-Bild (.jpeg) dar, das ein Bildformat ist, das mittels verlustbehafteter Kompression gespeichert wird. |
| [JFIF](#JFIF) | Das JPEG File Interchange Format (.jfif) ist ein Bild, das für einen schnellen Austausch zwischen Plattformen entwickelt wurde. |
| [PNG](#PNG) | Stellt ein Portable Network Graphic (.png) dar, das ein Rasterbild-Dateiformat ist, das verlustfreie Kompression verwendet. |
| [GIF](#GIF) | Stellt eine Graphical Interchange Format-Datei (.gif) dar, die ein stark komprimiertes Bild ist. |
| [APNG](#APNG) | Stellt ein Animated Portable Network Graphic (.apng) dar, das eine Erweiterung des PNG-Formats ist und Animation unterstützt. |
| [BMP](#BMP) | Stellt eine Bitmap Image File (.bmp) dar, die zum Speichern von Bitmap-Digitalbildern verwendet wird. |
| [ICO](#ICO) | Stellt eine Icon-Datei (.ico) dar, die als Symbol für die Darstellung einer Anwendung unter Microsoft Windows verwendet wird. |
| [TGA](#TGA) | Stellt eine Truevision TGA (TARGA)-Datei dar, die zum Speichern von Bitmap-Digitalbildern verwendet wird und von TRUEVISION entwickelt wurde. |
| [JP_2](#JP-2) | Stellt eine JPEG 2000 Core Image File (.jp2) dar, die ein Bildcodierungssystem und einen hochmodernen Bildkompressionsstandard darstellt. |
| [JPF](#JPF) | Stellt eine JPEG 2000 Image File (.jpf) dar. |
| [JPX](#JPX) | Stellt eine JPEG 2000 Image File (.jpx) dar. |
| [JPM](#JPM) | Stellt eine JPEG 2000 Image File (.jpm) dar. |
| [J2C](#J2C) | Stellt einen JPEG 2000 Code InputStream (.j2c) dar. |
| [J2K](#J2K) | Stellt einen JPEG 2000 Code Stream (.j2k) dar, der ein Bild ist, das mittels Wavelet-Kompression anstelle von DCT-Kompression komprimiert wurde. |
| [JPC](#JPC) | Stellt einen JPEG 2000 Code Stream (.jpc) dar. |
| [JLS](#JLS) | Stellt eine JPEG-LS (JLS)-Datei (.jls) dar. |
| [DIB](#DIB) | Stellt eine Device Independent Bitmap-Datei (.dib) dar. |
| [WMF](#WMF) | Stellt ein Windows Metafile (.wmf) dar, das das Microsoft Windows Metafile (WMF) zum Speichern von Vektor- sowie Bitmap-Bilddaten repräsentiert. |
| [WMZ](#WMZ) | Stellt ein Compressed Windows Metafile (.wmz) dar, das das Microsoft Windows Metafile (WMF) in einem GZIP-Archiv komprimiert zum Speichern von Vektor- und Bitmap-Bilddaten repräsentiert. |
| [EMF](#EMF) | Stellt ein Enhanced Windows Metafile (.emf) dar, das grafische Bilder geräteunabhängig repräsentiert. |
| [EMZ](#EMZ) | Stellt ein Windows Compressed Enhanced Metafile (.emz) dar, das grafische Bilder geräteunabhängig durch GZIP komprimiert repräsentiert. |
| [WEBP](#WEBP) | Stellt ein WebP-Bild (.webp) dar, das ein modernes rasterbasiertes Web-Bilddateiformat ist, das auf verlustfreier und verlustbehafteter Kompression basiert. |
| [DNG](#DNG) | Stellt eine Digital Negative Specification (.dng) dar, ein digitales Kamerabildformat, das zur Speicherung von Rohdateien verwendet wird. |
| [CDR](#CDR) | Stellt ein CorelDraw Vector Graphic Drawing (.cdr) dar, eine Vektorzeichnungs-Bilddatei, die nativ mit CorelDRAW erstellt wurde, um digital codierte und komprimierte Bilder zu speichern. |
| [CMX](#CMX) | Stellt ein Corel Exchange (.cmx) dar, eine Zeichenbilddatei, die sowohl Vektorgrafiken als auch Bitmap-Grafiken enthalten kann. |
| [DJVU](#DJVU) | Stellt ein DjVu-Bild (.djvu) dar, das ein Grafikdateiformat ist, das für gescannte Dokumente und Bücher vorgesehen ist, insbesondere für solche, die eine Kombination aus Text, Zeichnungen, Bildern und Fotografien enthalten. |
| [CGM](#CGM) | Stellt ein Computer Graphics Metafile (.cgm) dar, das ein kostenloses, plattformunabhängiges, internationaler Standard-Metadateiformat zum Speichern und Austauschen von Vektorgrafiken (2D), Rastergrafiken und Text ist. |
| [PCL](#PCL) | Stellt ein Printer Command Language-Dokument (.pcl) dar. |
| [PSD](#PSD) | Stellt ein Adobe Photoshop-Dokument (.psd) dar, das das native Dateiformat von Adobe Photoshop ist und für Grafikdesign und -entwicklung verwendet wird. |
| [PSB](#PSB) | Stellt ein Photoshop Large Document Format (.psb) dar, das für Grafikdesign und -entwicklung in Adobe Photoshop verwendet wird. |
| [DCM](#DCM) | Stellt ein DICOM-Bild (.dcm) dar, das ein digitales Bild ist, das medizinische Informationen von Patienten wie MRTs, CT-Scans und Ultraschallbilder speichert. |
| [PS](#PS) | Stellt eine PostScript-Datei (.ps) dar. |
| [EPS](#EPS) | Stellt eine Encapsulated PostScript-Datei (.eps) dar, die ein Encapsulated PostScript-Programmbeschreibt, das das Aussehen einer einzelnen Seite definiert. |
| [ODG](#ODG) | Stellt eine OpenDocument-Grafikdatei (.odg) dar, die von der Draw-Anwendung von Apache OpenOffice verwendet wird, um Zeichnungselemente als Vektorbilder zu speichern. |
| [FODG](#FODG) | Stellt eine Flat XML ODF-Vorlage (.fodg) dar, die von der Draw-Anwendung von Apache OpenOffice verwendet wird, um Zeichnungselemente als Vektorbilder zu speichern. |
| [SVG](#SVG) | Stellt eine Scalable Vector Graphics-Datei (.svg) dar, die eine Scalable Vector Graphics-Datei ist und ein XML-basiertes Textformat zur Beschreibung des Aussehens eines Bildes verwendet. |
| [SVGZ](#SVGZ) | Stellt eine komprimierte Scalable Vector Graphics-Datei (.svgz) dar, die eine Scalable Vector Graphics-Datei ist, die ein XML-basiertes Textformat verwendet, das mit GZIP komprimiert ist, um das Aussehen eines Bildes zu beschreiben. |
| [OTG](#OTG) | Stellt eine OpenDocument-Grafikvorlage (.otg) dar. |
| [HTM](#HTM) | Stellt eine Hypertext Markup Language-Datei (.htm) dar, die die Erweiterung für Webseiten ist, die zur Anzeige in Browsern erstellt wurden. |
| [HTML](#HTML) | Stellt eine Hypertext Markup Language-Datei (.html) dar, die die Erweiterung für Webseiten ist, die zur Anzeige in Browsern erstellt wurden. |
| [MHT](#MHT) | Stellt ein MHTML-Webarchiv (.mht) dar. |
| [NSF](#NSF) | Stellt eine Lotus Notes-Datenbank (.nsf) dar. |
| [MBOX](#MBOX) | Stellt eine E‑Mail-Postfachdatei (.mbox) dar. |
| [MHTML](#MHTML) | Stellt eine MIME HTML-Datei (.mhtml) dar. |
| [XML](#XML) | Stellt eine XML-Datei (.xml) dar. |
| [ONE](#ONE) | Stellt ein OneNote-Dokument (.one) dar, das von der Microsoft OneNote-Anwendung erstellt wurde. |
| [PDF](#PDF) | Stellt eine Portable Document Format-Datei (.pdf) dar, die eine Dokumentart ist, die von Adobe in den 1990er‑Jahren erstellt wurde. |
| [XPS](#XPS) | Stellt eine XML Paper Specification-Datei (.xps) dar, die Seitenlayoutdateien auf Basis von XML Paper Specifications repräsentiert, die von Microsoft erstellt wurden. |
| [OXPS](#OXPS) | Stellt eine OpenXPS-Datei (.oxps) dar. |
| [TEX](#TEX) | Stellt ein LaTeX-Quelltextdokument (.tex) dar, das eine Sprache ist, die sowohl Programmier- als auch Markup‑Funktionen umfasst und zum Satz von Dokumenten verwendet wird. |
| [PPT](#PPT) | Stellt eine PowerPoint-Präsentation (.ppt) dar, die eine PowerPoint-Datei ist, die aus einer Sammlung von Folien besteht, die als Diashow angezeigt werden. |
| [PPTX](#PPTX) | Stellt eine PowerPoint Open XML-Präsentation (.pptx) dar, bei der es sich um Präsentationsdateien handelt, die mit der beliebten Microsoft PowerPoint-Anwendung erstellt wurden. |
| [PPS](#PPS) | Stellt eine PowerPoint-Diashow (.pps) dar, die mit Microsoft PowerPoint für Diashow-Zwecke erstellt wurde. |
| [PPSX](#PPSX) | Stellt PowerPoint Open XML-Diashowdateien (.ppsx) dar, die mit Microsoft PowerPoint 2007 und höher für Diashow-Zwecke erstellt wurden. |
| [ODP](#ODP) | Stellt eine OpenDocument-Präsentation (.odp) dar, ein Präsentationsdateiformat, das von OpenOffice.org im OASISOpen-Standard verwendet wird. |
| [FODP](#FODP) | Stellt eine OpenDocument-Präsentation (.fodp) dar, die OpenDocument Flat XML-Präsentation. |
| [POT](#POT) | Stellt eine PowerPoint-Vorlage (.pot) dar, Microsoft PowerPoint-Vorlagendateien, die von PowerPoint‑Versionen 97‑2003 erstellt wurden. |
| [PPTM](#PPTM) | Stellt eine PowerPoint Open XML-Makro‑aktivierte Präsentation (.pptm) dar, das sind makro‑aktivierte Präsentationsdateien, die mit Microsoft PowerPoint 2007 oder neueren Versionen erstellt wurden. |
| [POTX](#POTX) | Stellt eine PowerPoint Open XML-Präsentationsvorlage (.potx) dar, die Microsoft PowerPoint-Vortragsvorlagen repräsentiert, die mit Microsoft PowerPoint 2007 und höher erstellt wurden. |
| [POTM](#POTM) | Stellt eine PowerPoint Open XML-Makro‑aktivierte Präsentationsvorlage (.potm) dar, das sind Microsoft PowerPoint-Vorlagendateien mit Makrounterstützung. |
| [PPSM](#PPSM) | Stellt eine PowerPoint Open XML-Makro‑aktivierte Folie (.ppsm) dar, ein makro‑aktiviertes Diashow-Dateiformat, das mit Microsoft PowerPoint 2007 oder höher erstellt wurde. |
| [OTP](#OTP) | Stellt eine OpenDocument-Präsentationsvorlage (.otp) dar, die Präsentationsvorlagendateien repräsentiert, die von Anwendungen im OASIS OpenDocument-Standardformat erstellt werden. |
| [XLS](#XLS) | Stellt eine Excel-Tabelle (.xls) dar, das Excel-Binärdateiformat. |
| [EXCEL_2003_XML](#EXCEL-2003-XML) | Stellt ein Excel 2003 XML (SpreadsheetML) (.xml) dar, das Excel-Binärdateiformat repräsentiert. |
| [NUMBERS](#NUMBERS) | Stellt Apple Numbers (.numbers) dar, ein Excel-ähnliches Binärdateiformat. |
| [XLSX](#XLSX) | Stellt eine Microsoft Excel Open XML-Tabelle (.xlsx) dar, ein bekanntes Format für Microsoft Excel-Dokumente, das von Microsoft mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde. |
| [XLSM](#XLSM) | Stellt eine Excel Open XML-Makro‑aktivierte Tabelle (.xlsm) dar, ein Tabellendateityp, der Makros unterstützt. |
| [XLSB](#XLSB) | Stellt eine Excel-Binärtabelle (.xlsb) dar, die das Excel-Binärdateiformat spezifiziert. |
| [CSV](#CSV) | Stellt eine durch Kommas getrennte Werte-Datei (.csv) dar, die Klartextdateien repräsentiert, die Datensätze mit kommagetrennten Werten enthalten. |
| [TSV](#TSV) | Stellt eine durch Tabs getrennte Werte-Datei (.tsv) dar, die Daten im Klartextformat darstellt, die durch Tabulatoren getrennt sind. |
| [ODS](#ODS) | Stellt eine OpenDocument-Tabelle (.ods) dar, das OpenDocument-Tabellendokumentformat, das vom Benutzer bearbeitet werden kann. |
| [FODS](#FODS) | Stellt eine OpenDocument Flat XML-Tabelle (.fods) dar. |
| [OTS](#OTS) | Stellt eine OpenDocument-Tabellenvorlage (.ots) dar. |
| [XLAM](#XLAM) | Stellt ein Microsoft Excel-Add‑In (.xlam) dar. |
| [XLTM](#XLTM) | Stellt eine Microsoft Excel Macro-Enabled Template (.xltm) dar, die von Microsoft Excel als makroaktivierte Vorlagendateien erzeugte Dateien repräsentiert. |
| [XLT](#XLT) | Stellt eine Microsoft Excel Vorlage (.xlt) dar, die Vorlagendateien sind, die mit Microsoft Excel erstellt wurden, einer Tabellenkalkulationsanwendung, die Teil der Microsoft Office‑Suite ist. |
| [XLTX](#XLTX) | Stellt eine Excel Open XML Tabellenkalkulationsvorlage (.xltx) dar, die Microsoft Excel‑Vorlagen basierend auf den Office OpenXML‑Dateiformatspezifikationen repräsentiert. |
| [SXC](#SXC) | Stellt eine StarOffice Calc Tabelle (.sxc) dar. |
| [MPP](#MPP) | Stellt eine Microsoft Project Datei (.mpp) dar, die eine Microsoft Project‑Datendatei ist, die Informationen zum Projektmanagement integriert speichert. |
| [MPT](#MPT) | Stellt eine Microsoft Project Vorlage (.mpt) dar, die grundlegende Informationen und Struktur sowie Dokumenteinstellungen für die Erstellung von .MPP‑Dateien enthält. |
| [MPX](#MPX) | Stellt eine Microsoft Project Exchange‑Datei (.mpx) dar, die ein ASCII‑Dateiformat zum Übertragen von Projektinformationen zwischen Microsoft Project (MSP) und anderen Anwendungen, die das MPX‑Dateiformat unterstützen, wie Primavera Project Planner, Sciforma und Timerline Precision Estimating, ist. |
| [AS](#AS) | Stellt eine ActionScript‑Datei (.as) dar. |
| [AS_3](#AS-3) | Stellt eine ActionScript‑Datei (.as3) dar. |
| [ASM](#ASM) | Stellt eine Assembly‑Language‑Quellcodedatei (.asm) dar. |
| [BAT](#BAT) | Stellt eine DOS‑Batch‑Datei (.bat) dar. |
| [C](#C) | Stellt eine C/C++‑Quellcodedatei (.c) dar. |
| [CC](#CC) | Stellt eine C++‑Quellcodedatei (.cc) dar. |
| [CMAKE](#CMAKE) | Stellt eine CMake‑Datei (.cmake) dar. |
| [CPP](#CPP) | Stellt eine C++‑Quellcodedatei (.cpp) dar. |
| [CS](#CS) | Stellt eine C\#‑Quellcodedatei (.cs) dar, die eine Quellcodedatei für die C\#‑Programmiersprache ist. |
| [VB](#VB) | Stellt eine Visual‑Basic‑Projekt‑Item‑Datei (.vb) dar, die eine Quellcodedatei ist, die in der Visual‑Basic‑Sprache erstellt wurde. |
| [CSS](#CSS) | Stellt eine Cascading Style Sheet (.css)‑Datei dar. |
| [CXX](#CXX) | Stellt eine C++‑Quellcodedatei (.cxx) dar. |
| [DIFF](#DIFF) | Stellt eine Patch‑Datei (.diff) dar. |
| [ERB](#ERB) | Stellt ein Ruby ERB‑Skript (.erb) dar. |
| [GROOVY](#GROOVY) | Stellt eine Groovy‑Quellcodedatei (.groovy) dar. |
| [H](#H) | Stellt eine C/C++/Objective‑C‑Header‑Datei (.h) dar. |
| [HAML](#HAML) | Stellt eine Haml‑Quellcodedatei (.haml) dar. |
| [HH](#HH) | Stellt eine C++‑Header‑Datei (.hh) dar. |
| [JAVA](#JAVA) | Stellt eine Java-Quellcodedatei (.java) dar. |
| [JS](#JS) | Stellt eine JavaScript-Datei (.js) dar. |
| [JSON](#JSON) | Stellt eine JavaScript Object Notation-Datei (.json) dar. |
| [LESS](#LESS) | Stellt eine LESS-Stylesheet-Datei (.less) dar. |
| [LOG](#LOG) | Stellt eine Protokolldatei (.log) dar. |
| [M](#M) | Stellt eine Objective-C-Implementierungsdatei (.m) dar. |
| [MAKE](#MAKE) | Stellt ein Xcode-Makefile-Skript (.make) dar. |
| [MD](#MD) | Stellt eine Markdown-Dokumentationsdatei (.md) dar. |
| [ML](#ML) | Stellt eine ML-Quellcodedatei (.ml) dar. |
| [MM](#MM) | Stellt eine Objective-C++-Quellcodedatei (.mm) dar. |
| [PHP](#PHP) | Stellt eine PHP-Quellcodedatei (.php) dar. |
| [PL](#PL) | Stellt ein Perl-Skript (.pl) dar. |
| [PROPERTIES](#PROPERTIES) | Stellt eine Java-Properties-Datei (.properties) dar. |
| [PY](#PY) | Stellt ein Python-Skript (.py) dar. |
| [RB](#RB) | Stellt eine Ruby-Quellcodedatei (.rb) dar. |
| [RST](#RST) | Stellt eine reStructuredText-Datei (.rst) dar. |
| [SASS](#SASS) | Stellt eine Syntactically Awesome StyleSheets-Datei (.sass) dar. |
| [SCALA](#SCALA) | Stellt eine Scala-Quellcodedatei (.scala) dar. |
| [SCM](#SCM) | Stellt eine Scheme-Quellcodedatei (.scm) dar. |
| [SCRIPT](#SCRIPT) | Stellt eine generische Skriptdatei (.script) dar. |
| [SH](#SH) | Stellt ein Bash-Shell-Skript (.sh) dar. |
| [SML](#SML) | Stellt eine Standard-ML-Quellcodedatei (.sml) dar. |
| [SQL](#SQL) | Stellt eine Structured Query Language-Datendatei (.sql) dar. |
| [VIM](#VIM) | Stellt eine Vim-Einstellungsdatei (.vim) dar. |
| [YAML](#YAML) | Stellt ein YAML-Dokument (.yaml) dar. |
| [DOC](#DOC) | Stellt eine Microsoft Word-Dokumentdatei (.doc) dar. |
| [DOCX](#DOCX) | Stellt eine Microsoft Word Open XML-Dokumentdatei (.docx) dar. |
| [CHM](#CHM) | Stellt eine Microsoft Compiled HTML Help-Datei (.chm) dar. |
| [DOCM](#DOCM) | Stellt ein Word Open XML-Makroaktiviertes Dokument (.docm) dar. |
| [DOT](#DOT) | Stellt eine Word-Dokumentvorlage (.dot) dar. |
| [DOTX](#DOTX) | Stellt eine Word Open XML-Dokumentvorlage (.dotx) dar. |
| [DOTM](#DOTM) | Stellt eine Word Open XML-Makroaktivierte Dokumentvorlage (.dotm) dar. |
| [RTF](#RTF) | Stellt eine Rich Text Format-Datei (.rtf) dar. |
| [TXT](#TXT) | Stellt eine Nur-Text-Datei (.txt) dar. |
| [ODT](#ODT) | Stellt ein OpenDocument-Textdokument (.odt) dar. |
| [OTT](#OTT) | Stellt eine OpenDocument-Dokumentvorlage (.ott) dar. |
| [VCF](#VCF) | Stellt eine vCard-Datei (.vcf) dar, die ein digitales Dateiformat zum Speichern von Kontaktinformationen ist. |
| [AI](#AI) | Stellt eine Adobe Illustrator-Datei (.ai) dar, ein Dateiformat für Adobe Illustrator-Zeichnungen. |
| [PSM1](#PSM1) | Stellt eine PowerShell‑Skriptmoduldatei (.psm1) dar. |
| [PS1](#PS1) | Stellt eine PowerShell‑Skriptdatei (.ps1) dar. |
| [PSD1](#PSD1) | Stellt eine PowerShell‑Skriptmodulmanifestdatei (.psd1) dar. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Ordnet eine Dateierweiterung einem Dateityp zu. |
| [fromFilePath(String filePath)](#fromFilePath-java.lang.String-) | Extrahiert die Dateierweiterung aus einem Dateinamen oder Dateipfad und ordnet sie einem Dateityp zu. |
| [fromMediaType(String mediaType)](#fromMediaType-java.lang.String-) | Ordnet einen Dateimedientyp einem Dateityp zu. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Ermittelt den Dateityp durch Lesen der Dateisignatur. |
| [fromStream(InputStream stream, String password)](#fromStream-java.io.InputStream-java.lang.String-) | Ermittelt den Dateityp durch Lesen der Dateisignatur. |
| [fromStream(InputStream stream, ILogger logger)](#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-) | Ermittelt den Dateityp durch Lesen der Dateisignatur. |
| [fromStream(InputStream stream, String password, ILogger logger)](#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-) | Ermittelt den Dateityp durch Lesen der Dateisignatur. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | Ruft die unterstützten Dateitypen ab. |
| [detectCharset(String filePath)](#detectCharset-java.lang.String-) | Versucht, den Zeichensatz von Textdateien [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) und [CSV](../../com.groupdocs.viewer/filetype\#CSV) anhand des Pfads zu erkennen. |
| [detectCharset(InputStream stream)](#detectCharset-java.io.InputStream-) | Versucht, den Zeichensatz von Textdateien [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) und [CSV](../../com.groupdocs.viewer/filetype\#CSV) anhand des Streams zu erkennen. |
| [getFileFormat()](#getFileFormat--) | Ermittelt den Namen des Dateiformats, z. B. „Microsoft Word Document“. |
| [getExtension()](#getExtension--) | Ermittelt das Dateierweiterungs‑Suffix (einschließlich des Punktes "."), z. B. ".doc". |
| [toString()](#toString--) | Gibt eine Zeichenkettenrepräsentation des aktuellen Objekts zurück. |
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Stellt einen unbekannten Dateityp dar.

### ZIP {#ZIP}
```
public static final FileType ZIP
```


Stellt eine gezippte Datei (.zip) dar, die eine oder mehrere Dateien oder Verzeichnisse enthalten kann. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/compression/zip

### TAR {#TAR}
```
public static final FileType TAR
```


Stellt ein konsolidiertes Unix-Dateiarchiv (.tar) dar, das zum Sammeln einer oder mehrerer Dateien erstellt wurde. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/compression/tar

### XZ {#XZ}
```
public static final FileType XZ
```


Stellt eine XZ-Datei (.xz) dar, die mit einem hochkomprimierenden Algorithmus auf Basis des LZMA-Algorithmus komprimiert wurde. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://fileinfo.com/extension/xz

### TXZ {#TXZ}
```
public static final FileType TXZ
```


Stellt ein konsolidiertes Unix-Dateiarchiv (.txz, .tar.xz) dar, das zum Sammeln einer oder mehrerer Dateien erstellt wurde. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://fileinfo.com/extension/txz

### TARXZ {#TARXZ}
```
public static final FileType TARXZ
```


Stellt ein konsolidiertes Unix-Dateiarchiv (.txz, .tar.xz) dar, das zum Sammeln einer oder mehrerer Dateien erstellt wurde. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://fileinfo.com/extension/txz

### TGZ {#TGZ}
```
public static final FileType TGZ
```


Stellt ein konsolidiertes Unix-Dateiarchiv (.tgz, .tar.gz) dar, das zum Sammeln einer oder mehrerer Dateien erstellt wurde. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://fileinfo.com/extension/tgz

### TARGZ {#TARGZ}
```
public static final FileType TARGZ
```


Stellt ein konsolidiertes Unix-Dateiarchiv (.tgz, .tar.gz) dar, das zum Sammeln einer oder mehrerer Dateien erstellt wurde. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://fileinfo.com/extension/tgz

### BZ_2 {#BZ-2}
```
public static final FileType BZ_2
```


Stellt eine Bzip2-komprimierte Datei (.bz2) dar, die mit der Open-Source-Komprimierungsmethode BZIP2 erzeugt wurde. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/compression/bz2

### RAR {#RAR}
```
public static final FileType RAR
```


Stellt eine Roshal-Archiv (.rar) komprimierte Datei dar, die mit der RAR-Komprimierungsmethode (WINRAR Version 4) erzeugt wurde. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/compression/rar

### GZ {#GZ}
```
public static final FileType GZ
```


Stellt eine Gnu-Zip-Datei (.gz) dar, die mit der gzip-Komprimierungsanwendung erstellt wurde. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/compression/gz

### GZIP {#GZIP}
```
public static final FileType GZIP
```


Stellt eine Gnu-Zip-Datei (.gzip) dar, die als kostenloses Dienstprogramm zur Ersetzung des Compress-Programms in Unix-Systemen eingeführt wurde. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/compression/gz

### SEVEN_ZIP {#SEVEN-ZIP}
```
public static final FileType SEVEN_ZIP
```


Stellt eine 7Zip-Datei (.7z, .7zip) dar, die ein kostenloser Open-Source-Archivierer mit LZMA- und LZMA2-Kompression ist. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://docs.fileformat.com/compression/7z/

### CPIO {#CPIO}
```
public static final FileType CPIO
```


Cpio ist ein allgemeines Dateiarchivierungswerkzeug und das zugehörige Dateiformat. Es ist hauptsächlich auf unixähnlichen Betriebssystemen installiert. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/compression/cpio

### ZSTANDARD {#ZSTANDARD}
```
public static final FileType ZSTANDARD
```


ZST-Datei ist eine komprimierte Datei, die mit dem Zstandard‑Kompressionsalgorithmus (zstd) erzeugt wird. Es handelt sich um eine komprimierte Datei, die durch verlustfreie Kompression des Algorithmus erstellt wird. ZST‑Dateien können verwendet werden, um verschiedene Dateitypen wie Datenbanken, Dateisysteme, Netzwerke und Spiele zu komprimieren. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://docs.fileformat.com/compression/zst/

### TZST {#TZST}
```
public static final FileType TZST
```


TZST-Dateien (.tar.zst, .tzst) sind Zstandard-Archive (ZST), die intern ein Consolidated Unix File Archive (Tar) enthalten und mit einem Unix-basierten Dienstprogramm zum Sammeln von einer oder mehreren Dateien erstellt wurden.

### TAR_ZST {#TAR-ZST}
```
public static final FileType TAR_ZST
```


TZST-Dateien (.tar.zst, .tzst) sind Zstandard-Archive (ZST), die intern ein Consolidated Unix File Archive (Tar) enthalten und mit einem Unix-basierten Dienstprogramm zum Sammeln von einer oder mehreren Dateien erstellt wurden.

### ISO {#ISO}
```
public static final FileType ISO
```


ISO‑Optical‑Disc‑Image ist eine unkomprimierte Archiv‑Disk‑Image‑Datei, die den gesamten Inhalt einer optischen Disc wie CD oder DVD gemäß dem ISO‑9660‑Standard darstellt. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://docs.fileformat.com/compression/iso/

### LHA {#LHA}
```
public static final FileType LHA
```


LHA oder LZH ist ein Freeware-Komprimierungsprogramm und das zugehörige Dateiformat. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://docs.fileformat.com/compression/lzh/

### CAB {#CAB}
```
public static final FileType CAB
```


Cabinet (oder CAB) ist ein Archivdateiformat für Microsoft Windows. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://en.wikipedia.org/wiki/Cabinet_%28file_format%29

### DXF {#DXF}
```
public static final FileType DXF
```


Stellt eine Drawing‑Exchange‑Format‑Datei (.dxf) dar, die eine getaggte Datenrepräsentation einer AutoCAD‑Zeichnungsdatei ist. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/cad/dxf

### DWG {#DWG}
```
public static final FileType DWG
```


Stellt eine AutoCAD‑Zeichnungsdatenbank‑Datei (.dwg) dar, die proprietäre Binärdateien zur Speicherung von 2D‑ und 3D‑Designdaten enthält. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/cad/dwg

### DWT {#DWT}
```
public static final FileType DWT
```


Stellt eine AutoCAD‑Zeichnungsvorlage (.dwt) dar, die als Ausgangsvorlage für das Erstellen von Zeichnungen dient, die als DWG‑Dateien gespeichert werden können. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/cad/dwt

### STL {#STL}
```
public static final FileType STL
```


Stellt eine Stereolithografie-Datei (.stl) dar, die ein austauschbares Dateiformat ist, das 3‑dimensionale Oberflächengeometrie darstellt. Sie wird häufig beim Rapid Prototyping, 3D‑Druck und der computergestützten Fertigung verwendet. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/cad/stl

### IFC {#IFC}
```
public static final FileType IFC
```


Stellt eine Industry Foundation Classes‑Datei (.ifc) dar, ein Dateiformat, das internationale Standards für den Import und Export von Bauobjekten und deren Eigenschaften festlegt. Es ermöglicht Interoperabilität zwischen verschiedenen Softwareanwendungen. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/cad/ifc

### DWF {#DWF}
```
public static final FileType DWF
```


Stellt eine Design Web Format‑Datei (.dwf) dar, ein komprimiertes Dateiformat zum Anzeigen, Überprüfen oder Drucken von 2D/3D‑Zeichnungen. Es enthält Grafiken und Text als Teil der Designdaten und reduziert die Dateigröße durch Kompression. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/cad/dwf

### FBX {#FBX}
```
public static final FileType FBX
```


Stellt eine Autodesk FBX Interchange‑Datei (FilmBoX) (.fbx) dar, ein 3D‑Modellformat. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/cad/fbx

### DWFX {#DWFX}
```
public static final FileType DWFX
```


Stellt eine Design Web Format‑Datei XPS (.dwfx) dar, ein komprimiertes Format zum Anzeigen, Überprüfen oder Drucken von 2D/3D‑Zeichnungen als XPS‑Dokument. Es enthält Grafiken und Text als Teil der Designdaten und reduziert die Dateigröße durch Kompression. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/cad/dwfx

### DGN {#DGN}
```
public static final FileType DGN
```


Stellt eine MicroStation‑Design‑Datei (.dgn) dar, bei der es sich um Zeichnungen handelt, die von CAD‑Anwendungen wie MicroStation und Intergraph Interactive Graphics Design System erstellt und unterstützt werden. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/cad/dgn

### PLT {#PLT}
```
public static final FileType PLT
```


Stellt eine PLT‑(HPGL‑)Datei (.plt) dar, eine vektorbasierte Plotterdatei, die von Autodesk, Inc. eingeführt wurde. Sie enthält Informationen für eine bestimmte CAD‑Datei, und alle Bilder werden mit Linien statt Punkten gedruckt, was Genauigkeit und Präzision in der Produktion gewährleistet. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/cad/plt

### CF2 {#CF2}
```
public static final FileType CF2
```


Stellt eine Common File Format‑Datei (.cf2) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://fileinfo.com/extension/cf2

### OBJ {#OBJ}
```
public static final FileType OBJ
```


Stellt eine Wavefront 3D‑Objekt‑Datei (.obj) dar, eine von Wavefront Technologies eingeführte 3D‑Bilddatei. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/3d/obj/

### HPG {#HPG}
```
public static final FileType HPG
```


Stellt eine PLT‑(HPGL‑)Datei (.hpg) dar. Es ist ein Dateiformat, das für Plotterdateien in der HP Graphics Language (HPGL) verwendet wird. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://fileinfo.com/extension/hpg

### IGS {#IGS}
```
public static final FileType IGS
```


Stellt eine Initial Graphics Exchange Specification (IGES) File (.igs) dar.

### VSD {#VSD}
```
public static final FileType VSD
```


Stellt eine Visio‑Zeichnungsdatei (.vsd) dar, bei der es sich um mit der Microsoft‑Visio‑Anwendung erstellte Zeichnungen handelt, die eine Vielzahl von grafischen Objekten und deren Verbindungen darstellen. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/image/vsd

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Stellt eine Visio‑Zeichnungsdatei (.vsdx) dar, das Microsoft‑Visio‑Dateiformat, das ab Microsoft Office 2013 eingeführt wurde. Es ersetzte das binäre Dateiformat (.VSD), das von früheren Versionen von Microsoft Visio unterstützt wurde. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/image/vsdx

### VSS {#VSS}
```
public static final FileType VSS
```


Stellt eine Visio‑Stencil‑Datei (.vss) dar, bei der es sich um mit Microsoft Visio 2007 und früheren Versionen erstellte Stencil‑Dateien handelt. Stencil‑Dateien stellen Zeichenobjekte bereit, die in einer .VSD‑Visio‑Zeichnung eingebunden werden können. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/image/vss

### VSSX {#VSSX}
```
public static final FileType VSSX
```


Stellt eine Visio-Stencil-Datei (.vssx) dar, die Zeichenstencil-Dateien sind, die mit Microsoft Visio 2013 und höher erstellt wurden. Das VSSX-Dateiformat kann mit Visio 2013 und höher geöffnet werden. Visio-Dateien sind dafür bekannt, eine Vielzahl von Zeichnungselementen wie Formen, Verbinder, Flussdiagramme, Netzwerklayouts, UML-Diagramme usw. darzustellen. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/image/vssx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Stellt eine Visio-Makro‑aktivierte Zeichnung (.vsdm) dar, die Zeichnungsdateien sind, die mit der Microsoft Visio‑Anwendung erstellt wurden und Makros unterstützen. VSDM‑Dateien sind OPC/XML‑Zeichnungen, die VSDX ähneln, aber zudem die Möglichkeit bieten, Makros beim Öffnen der Datei auszuführen. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/image/vsdm

### VST {#VST}
```
public static final FileType VST
```


Stellt eine Visio-Zeichnungsvorlage (.vst) dar, die Vektorbilder sind, die mit Microsoft Visio erstellt wurden. Sie dienen als Vorlagen für die Erstellung weiterer Dateien und enthalten das Standardlayout und die Einstellungen, die für das Erstellen neuer Visio‑Zeichnungen verwendet werden. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/image/vst

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Stellt eine Visio-Zeichnungsvorlage (.vstx) dar, die Zeichenvorlagendateien sind, die mit Microsoft Visio 2013 und höher erstellt wurden. Diese VSTX‑Dateien bieten einen Ausgangspunkt für die Erstellung von Visio‑Zeichnungen, die als .VSDX‑Dateien gespeichert werden, mit Standardlayout und -einstellungen. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Stellt eine Visio-Makro‑aktivierte Zeichnungsvorlage (.vstm) dar, die Vorlagendateien sind, die mit Microsoft Visio erstellt wurden und Makros unterstützen. Aus VSTM‑Vorlagen erstellte Dateien können Makros ausführen, die in Visual Basic for Applications (VBA)-Code entwickelt wurden. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Stellt eine Visio-Makro‑aktivierte Stencil‑Datei (.vssm) dar, die Microsoft Visio Stencil‑Dateien sind, die Makros unterstützen. Wenn eine VSSM‑Datei geöffnet wird, können Makros ausgeführt werden, um die gewünschte Formatierung und Platzierung von Formen in einem Diagramm zu erreichen. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Stellt eine Visio-Stencil‑XML‑Datei (.vsx) dar, die sich auf Stencils bezieht, die aus Zeichnungen und Formen bestehen und zum Erstellen von Diagrammen in Microsoft Visio verwendet werden. VSX‑Dateien werden im XML‑Dateiformat gespeichert und wurden bis Visio 2013 unterstützt. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


Stellt eine Visio‑Vorlagen‑XML‑Datei (.vtx) dar, die eine Microsoft Visio‑Zeichnungsvorlage ist, die auf der Festplatte im XML‑Dateiformat gespeichert wird. Die Vorlage bietet grundlegende Einstellungen für die Erstellung mehrerer Visio‑Dateien mit denselben Einstellungen. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/image/vtx

### VDW {#VDW}
```
public static final FileType VDW
```


Stellt eine Visio-Web‑Zeichnung (.vdw) dar, die die für die Darstellung einer Web‑Zeichnung erforderlichen Streams und Speicher angibt. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/web/vdw

### VDX {#VDX}
```
public static final FileType VDX
```


Stellt eine Visio‑Zeichnungs‑XML‑Datei (.vdx) dar, die jede in Microsoft Visio erstellte Zeichnung oder jedes Diagramm repräsentiert, das im XML‑Format mit der Erweiterung .VDX gespeichert wird. Eine Visio‑Zeichnungs‑XML‑Datei wird in der von Microsoft entwickelten Visio‑Software erstellt. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Stellt eine Open eBook-Datei (.epub) dar, ein eBook-Dateiformat, das ein standardisiertes digitales Publikationsformat für Verlage und Verbraucher bereitstellt. Das Format wird von vielen E-Readern und Softwareanwendungen unterstützt. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/ebook/epub

### MOBI {#MOBI}
```
public static final FileType MOBI
```


Stellt ein Mobipocket-eBook (.mobi) dar, eines der am weitesten verbreiteten eBook-Dateiformate. Das Format ist eine Weiterentwicklung des alten OEB (Open Ebook Format)-Formats und wurde als proprietäres Format für den Mobipocket Reader verwendet. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/ebook/mobi

### AZW_3 {#AZW-3}
```
public static final FileType AZW_3
```


Das Amazon Kindle Format 8 (KF8) eBook ist das digitale Dateiformat, das für Amazon Kindle-Geräte entwickelt wurde. Das Format ist eine Weiterentwicklung älterer AZW-Dateien und wird ausschließlich auf Kindle Fire-Geräten verwendet, wobei es abwärtskompatibel zum Vorgängerformat, d. h. MOBI und AZW, ist. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/ebook/azw3

### MSG {#MSG}
```
public static final FileType MSG
```


Stellt eine Outlook-Mail-Nachricht (.msg) dar, ein Dateiformat, das von Microsoft Outlook und Exchange zum Speichern von E‑Mail‑Nachrichten, Kontakten, Terminen oder anderen Aufgaben verwendet wird. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/email/msg

### EML {#EML}
```
public static final FileType EML
```


Stellt eine E‑Mail‑Nachricht (.eml) dar, die per Outlook und anderen relevanten Anwendungen gespeicherte E‑Mails repräsentiert. Fast alle E‑Mail‑Clients unterstützen dieses Dateiformat, da es dem RFC‑822‑Internetnachrichtenformat‑Standard entspricht. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/email/eml

### EMLX {#EMLX}
```
public static final FileType EMLX
```


Stellt eine Apple‑Mail‑Nachricht (.emlx) dar, die von Apple implementiert und entwickelt wurde. Die Apple‑Mail‑Anwendung verwendet das EMLX‑Dateiformat zum Exportieren von E‑Mails. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/email/emlx

### PST {#PST}
```
public static final FileType PST
```


Stellt eine Outlook-Personal‑Information‑Store‑Datei (.pst) dar, die Outlook-Personal‑Storage‑Files (auch Personal Storage Table genannt) repräsentiert und eine Vielzahl von Benutzerdaten speichert. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/email/pst

### OST {#OST}
```
public static final FileType OST
```


Stellt eine Outlook-Offline‑Data‑File (.ost) dar, die die Postfachdaten eines Benutzers im Offline‑Modus auf einem lokalen Rechner nach Registrierung beim Exchange‑Server mit Microsoft Outlook repräsentiert. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/email/ost

### TIF {#TIF}
```
public static final FileType TIF
```


Stellt eine Tagged Image File (.tif) dar, die Rasterbilder repräsentiert, die für die Verwendung auf einer Vielzahl von Geräten gedacht sind, die diesem Dateiformatstandard entsprechen. Sie kann zweistufige, Graustufen-, Paletten- und Vollfarbbilddaten in mehreren Farbräumen beschreiben. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/tiff

### TIFF {#TIFF}
```
public static final FileType TIFF
```


Stellt ein Tagged Image File Format (.tiff) dar, das Rasterbilder repräsentiert, die für die Verwendung auf einer Vielzahl von Geräten gedacht sind, die diesem Dateiformatstandard entsprechen. Es kann zweistufige, Graustufen-, Paletten- und Vollfarbbilddaten in mehreren Farbräumen beschreiben. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/tiff

### JPG {#JPG}
```
public static final FileType JPG
```


Stellt ein JPEG‑Bild (.jpg) dar, ein Bildformat, das mittels verlustbehafteter Kompression gespeichert wird. Das Ergebnisbild ist dabei ein Kompromiss zwischen Dateigröße und Bildqualität. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/jpeg

### JPEG {#JPEG}
```
public static final FileType JPEG
```


Stellt ein JPEG-Bild (.jpeg) dar, das ein Bildformat ist, das mit verlustbehafteter Kompression gespeichert wird. Das Ausgabebild ist als Ergebnis der Kompression ein Kompromiss zwischen Speichergröße und Bildqualität. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/jpeg

### JFIF {#JFIF}
```
public static final FileType JFIF
```


Das JPEG File Interchange Format (.jfif) ist ein Bild, das für den schnellen Austausch zwischen Plattformen entwickelt wurde. Dieses Format verwendet JPEG‑Kompression. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/jfif

### PNG {#PNG}
```
public static final FileType PNG
```


Stellt ein Portable Network Graphic (.png) dar, ein Raster‑Bilddateiformat, das verlustfreie Kompression verwendet. Dieses Dateiformat wurde als Ersatz für das Graphics Interchange Format (GIF) geschaffen und hat keine urheberrechtlichen Beschränkungen. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/png

### GIF {#GIF}
```
public static final FileType GIF
```


Stellt eine Graphical Interchange Format Datei (.gif) dar, ein stark komprimiertes Bild. Für jedes Bild erlaubt GIF typischerweise bis zu 8 Bit pro Pixel, und bis zu 256 Farben sind im Bild zulässig. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/gif

### APNG {#APNG}
```
public static final FileType APNG
```


Stellt ein Animated Portable Network Graphic (.apng) dar, eine Erweiterung des PNG‑Formats, die Animation unterstützt. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/apng

### BMP {#BMP}
```
public static final FileType BMP
```


Stellt eine Bitmap Image File (.bmp) dar, die zum Speichern von Bitmap‑Digitalbildern verwendet wird. Diese Bilder sind unabhängig vom Grafikadapter und werden auch Device Independent Bitmap (DIB) Dateiformat genannt. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/bmp

### ICO {#ICO}
```
public static final FileType ICO
```


Stellt eine Icon File (.ico) dar, ein Bilddateityp, der als Symbol für die Darstellung einer Anwendung unter Microsoft Windows verwendet wird. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/ico

### TGA {#TGA}
```
public static final FileType TGA
```


Stellt eine Truevision TGA (TARGA) Datei dar, die zum Speichern von Bitmap‑Digitalbildern entwickelt wurde von TRUEVISION. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/tga

### JP_2 {#JP-2}
```
public static final FileType JP_2
```


Stellt eine JPEG 2000 Core Image File (.jp2) dar, ein Bildkodierungssystem und einen hochmodernen Bildkompressionsstandard. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/jp2

### JPF {#JPF}
```
public static final FileType JPF
```


Stellt eine JPEG 2000 Image File (.jpf) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/image/jpf

### JPX {#JPX}
```
public static final FileType JPX
```


Stellt eine JPEG 2000 Image File (.jpx) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/jpx

### JPM {#JPM}
```
public static final FileType JPM
```


Stellt eine JPEG 2000 Image File (.jpm) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/jpm

### J2C {#J2C}
```
public static final FileType J2C
```


Stellt einen JPEG 2000 Code InputStream (.j2c) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/j2c

### J2K {#J2K}
```
public static final FileType J2K
```


Stellt einen JPEG 2000 Code Stream (.j2k) dar, ein Bild, das mit Wavelet‑Kompression statt DCT‑Kompression komprimiert wird. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/j2k

### JPC {#JPC}
```
public static final FileType JPC
```


Stellt einen JPEG 2000 Code Stream (.jpc) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/jpc

### JLS {#JLS}
```
public static final FileType JLS
```


Stellt eine JPEG‑LS (JLS) Datei (.jls) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://fileinfo.com/extension/jls

### DIB {#DIB}
```
public static final FileType DIB
```


Stellt eine Device Independent Bitmap File (.dib) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/dib

### WMF {#WMF}
```
public static final FileType WMF
```


Stellt ein Windows Metafile (.wmf) dar, das Microsoft Windows Metafile (WMF) zum Speichern von Vektor‑ sowie Bitmap‑Bilddaten repräsentiert. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/wmf

### WMZ {#WMZ}
```
public static final FileType WMZ
```


Stellt ein komprimiertes Windows Metafile (.wmz) dar, das ein Microsoft Windows Metafile (WMF) darstellt, das in einem GZIP-Archiv komprimiert ist, um Vektor‑ sowie Bitmap‑Bilddaten zu speichern. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://fileinfo.com/extension/wmz#compressed_windows_metafile

### EMF {#EMF}
```
public static final FileType EMF
```


Stellt ein Enhanced Windows Metafile (.emf) dar, das grafische Bilder geräteunabhängig repräsentiert. EMF‑Metadateien bestehen aus variablen Längendrekorden in chronologischer Reihenfolge, die das gespeicherte Bild nach dem Parsen auf jedem Ausgabegerät rendern können. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/emf

### EMZ {#EMZ}
```
public static final FileType EMZ
```


Stellt ein Windows Compressed Enhanced Metafile (.emz) dar, das grafische Bilder geräteunabhängig durch GZIP komprimiert darstellt. EMF‑Metadateien bestehen aus variablen Längendrekorden in chronologischer Reihenfolge, die das gespeicherte Bild nach dem Parsen auf jedem Ausgabegerät rendern können. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/emz

### WEBP {#WEBP}
```
public static final FileType WEBP
```


Stellt ein WebP‑Bild (.webp) dar, ein modernes rasterbasiertes Web‑Bilddateiformat, das auf verlustfreier und verlustbehafteter Kompression basiert. Es liefert die gleiche Bildqualität bei gleichzeitig erheblicher Reduzierung der Dateigröße. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/webp

### DNG {#DNG}
```
public static final FileType DNG
```


Stellt eine Digital Negative Specification (.dng) dar, ein digitales Kamerabildformat zur Speicherung von Rohdateien. Es wurde von Adobe im September 2004 entwickelt und wird hauptsächlich für die digitale Fotografie verwendet. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/dng

### CDR {#CDR}
```
public static final FileType CDR
```


Stellt ein CorelDraw Vector Graphic Drawing (.cdr) dar, eine Vektorzeichnungs‑Bilddatei, die nativ mit CorelDRAW erstellt wird, um digital codierte und komprimierte Bilder zu speichern. Eine CDR‑Datei enthält Text, Linien, Formen, Bilder, Farben und Effekte zur Vektorrepräsentation des Bildinhalts. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/cdr

### CMX {#CMX}
```
public static final FileType CMX
```


Stellt einen Corel Exchange (.cmx) dar, eine Zeichen‑Bilddatei, die sowohl Vektorgrafiken als auch Bitmap‑Grafiken enthalten kann. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/cmx

### DJVU {#DJVU}
```
public static final FileType DJVU
```


Stellt ein DjVu‑Bild (.djvu) dar, ein Grafikdateiformat für gescannte Dokumente und Bücher, insbesondere solche mit einer Kombination aus Text, Zeichnungen, Bildern und Fotografien. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/djvu

### CGM {#CGM}
```
public static final FileType CGM
```


Stellt ein Computer Graphics Metafile (.cgm) dar, ein kostenloses, plattformunabhängiges, internationaler Standard‑Metadateiformat zum Speichern und Austauschen von Vektorgrafiken (2D), Rastergrafiken und Text. CGM verwendet einen objektorientierten Ansatz und bietet zahlreiche Funktionen für die Bildproduktion. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/page-description-language/cgm

### PCL {#PCL}
```
public static final FileType PCL
```


Stellt ein Printer Command Language‑Dokument (.pcl) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/page-description-language/pcl

### PSD {#PSD}
```
public static final FileType PSD
```


Stellt ein Adobe Photoshop‑Dokument (.psd) dar, das native Dateiformat von Adobe Photoshop für Grafikdesign und -entwicklung. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/psd

### PSB {#PSB}
```
public static final FileType PSB
```


Stellt ein Photoshop Large Document Format (.psb) dar, das für Grafikdesign und -entwicklung in Adobe Photoshop verwendet wird. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/psb

### DCM {#DCM}
```
public static final FileType DCM
```


Stellt ein DICOM‑Bild (.dcm) dar, das ein digitales Bild ist, das medizinische Informationen von Patienten wie MRTs, CT‑Scans und Ultraschallbilder speichert. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/dcm

### PS {#PS}
```
public static final FileType PS
```


Stellt eine PostScript‑Datei (.ps) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/page-description-language/ps

### EPS {#EPS}
```
public static final FileType EPS
```


Stellt eine Encapsulated PostScript‑Datei (.eps) dar, die ein Encapsulated PostScript‑Programm beschreibt, das das Aussehen einer einzelnen Seite definiert. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/page-description-language/eps

### ODG {#ODG}
```
public static final FileType ODG
```


Stellt eine OpenDocument‑Grafikdatei (.odg) dar, die von der Draw‑Anwendung von Apache OpenOffice verwendet wird, um Zeichnungselemente als Vektorbilder zu speichern. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/odg

### FODG {#FODG}
```
public static final FileType FODG
```


Stellt eine Flat XML ODF‑Vorlage (.fodg) dar, die von der Draw‑Anwendung von Apache OpenOffice verwendet wird, um Zeichnungselemente als Vektorbilder zu speichern. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/image/fodg

### SVG {#SVG}
```
public static final FileType SVG
```


Stellt eine Scalable Vector Graphics‑Datei (.svg) dar, die ein XML‑basiertes Textformat zur Beschreibung des Aussehens eines Bildes verwendet. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/page-description-language/svg

### SVGZ {#SVGZ}
```
public static final FileType SVGZ
```


Stellt eine komprimierte Scalable Vector Graphics‑Datei (.svgz) dar, die ein XML‑basiertes Textformat, komprimiert mit GZIP, zur Beschreibung des Aussehens eines Bildes verwendet. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://fileinfo.com/extension/svgz

### OTG {#OTG}
```
public static final FileType OTG
```


Stellt eine OpenDocument‑Grafikvorlage (.otg) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/image/otg

### HTM {#HTM}
```
public static final FileType HTM
```


Stellt eine Hypertext Markup Language‑Datei (.htm) dar, die die Dateierweiterung für Webseiten ist, die zur Anzeige in Browsern erstellt wurden. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/web/html

### HTML {#HTML}
```
public static final FileType HTML
```


Stellt eine Hypertext Markup Language‑Datei (.html) dar, die die Dateierweiterung für Webseiten ist, die zur Anzeige in Browsern erstellt wurden. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


Stellt ein MHTML‑Webarchiv (.mht) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/web/mht

### NSF {#NSF}
```
public static final FileType NSF
```


Stellt eine Lotus Notes‑Datenbank (.nsf) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://fileinfo.com/extension/nsf

### MBOX {#MBOX}
```
public static final FileType MBOX
```


Stellt eine E‑Mail‑Postfachdatei (.mbox) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://fileinfo.com/extension/mbox

### MHTML {#MHTML}
```
public static final FileType MHTML
```


Stellt eine MIME HTML‑Datei (.mhtml) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/web/mhtml

### XML {#XML}
```
public static final FileType XML
```


Stellt eine XML‑Datei (.xml) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/web/xml

### ONE {#ONE}
```
public static final FileType ONE
```


Stellt ein OneNote‑Dokument (.one) dar, das von der Microsoft OneNote‑Anwendung erstellt wurde. OneNote ermöglicht es Ihnen, Informationen zu sammeln, als würden Sie Ihr Notizblock zum Notieren verwenden. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


Stellt eine Portable Document Format‑Datei (.pdf) dar, die in den 1990er‑Jahren von Adobe erstellt wurde. Der Zweck dieses Dateiformats war es, einen Standard für die Darstellung von Dokumenten und anderen Referenzmaterialien einzuführen, der unabhängig von Anwendungssoftware, Hardware und Betriebssystemen ist. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


Stellt eine XML Paper Specification Datei (.xps) dar, die Seitenlayout‑Dateien basierend auf von Microsoft erstellten XML Paper Specifications repräsentiert. Dieses Format wurde von Microsoft als Ersatz für das EMF‑Dateiformat entwickelt und ist dem PDF‑Dateiformat ähnlich, verwendet jedoch XML für Layout-, Erscheinungs‑ und Druckinformationen eines Dokuments. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/page-description-language/xps

### OXPS {#OXPS}
```
public static final FileType OXPS
```


Stellt eine OpenXPS‑Datei (.oxps) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/page-description-language/oxps

### TEX {#TEX}
```
public static final FileType TEX
```


Stellt ein LaTeX‑Quelltextdokument (.tex) dar, eine Sprache, die sowohl Programmier‑ als auch Auszeichnungsfunktionen zur Satz von Dokumenten umfasst. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


Stellt eine PowerPoint‑Präsentation (.ppt) dar, die eine PowerPoint‑Datei ist, die aus einer Sammlung von Folien für die Anzeige als Diashow besteht. Sie gibt das von Microsoft PowerPoint 97‑2003 verwendete Binärdateiformat an. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


Stellt eine PowerPoint Open XML‑Präsentation (.pptx) dar, das Präsentationsdateien sind, die mit der beliebten Microsoft PowerPoint‑Anwendung erstellt wurden. Im Gegensatz zur vorherigen Version des Präsentationsdateiformats PPT, das binär war, basiert das PPTX‑Format auf dem Microsoft PowerPoint Open XML‑Präsentationsdateiformat. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


Stellt eine PowerPoint‑Diashow (.pps) dar, die mit Microsoft PowerPoint für Diashow‑Zwecke erstellt wird. Das Lesen und Erstellen von PPS‑Dateien wird von Microsoft PowerPoint 97‑2003 unterstützt. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


Stellt PowerPoint Open XML‑Diashow‑Dateien (.ppsx) dar, die mit Microsoft PowerPoint 2007 und höher für Diashow‑Zwecke erstellt werden. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


Stellt eine OpenDocument‑Präsentation (.odp) dar, ein Präsentationsdateiformat, das von OpenOffice.org im OASISOpen‑Standard verwendet wird. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/presentation/odp

### FODP {#FODP}
```
public static final FileType FODP
```


Stellt eine OpenDocument‑Präsentation (.fodp) dar, die OpenDocument Flat XML‑Präsentation. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://fileinfo.com/extension/fodp

### POT {#POT}
```
public static final FileType POT
```


Stellt eine PowerPoint‑Vorlage (.pot) dar, Microsoft PowerPoint‑Vorlagendateien, die mit PowerPoint‑Versionen 97‑2003 erstellt wurden. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/presentation/pot

### PPTM {#PPTM}
```
public static final FileType PPTM
```


Stellt eine PowerPoint Open XML‑Makro‑aktivierte Präsentation (.pptm) dar, das sind makro‑aktivierte Präsentationsdateien, die mit Microsoft PowerPoint 2007 oder neueren Versionen erstellt wurden. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/presentation/pptm

### POTX {#POTX}
```
public static final FileType POTX
```


Stellt eine PowerPoint Open XML‑Präsentationsvorlage (.potx) dar, Microsoft PowerPoint‑Vorlagepräsentationen, die mit Microsoft PowerPoint 2007 und höher erstellt wurden. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/presentation/potx

### POTM {#POTM}
```
public static final FileType POTM
```


Stellt eine PowerPoint Open XML‑Makro‑aktivierte Präsentationsvorlage (.potm) dar, Microsoft PowerPoint‑Vorlagendateien mit Makro‑Unterstützung. POTM‑Dateien werden mit PowerPoint 2007 oder höher erstellt und enthalten Standardeinstellungen, die zur Erstellung weiterer Präsentationsdateien verwendet werden können. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/presentation/potm

### PPSM {#PPSM}
```
public static final FileType PPSM
```


Stellt eine PowerPoint Open XML Makro‑aktivierte Folie (.ppsm) dar, die ein makroaktiviertes Diashow‑Dateiformat darstellt, das mit Microsoft PowerPoint 2007 oder höher erstellt wurde. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/presentation/ppsm

### OTP {#OTP}
```
public static final FileType OTP
```


Stellt eine OpenDocument Präsentationsvorlage (.otp) dar, die Präsentationsvorlagendateien repräsentiert, die von Anwendungen im OASIS OpenDocument‑Standardformat erstellt werden. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


Stellt eine Excel‑Tabelle (.xls) dar, die das Excel‑Binärdateiformat repräsentiert. Solche Dateien können von Microsoft Excel sowie anderen ähnlichen Tabellenkalkulationsprogrammen wie OpenOffice Calc oder Apple Numbers erstellt werden. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### EXCEL_2003_XML {#EXCEL-2003-XML}
```
public static final FileType EXCEL_2003_XML
```


Stellt ein Excel 2003 XML (SpreadsheetML) (.xml) dar, das das Excel‑Binärdateiformat repräsentiert. Solche Dateien können von Microsoft Excel sowie anderen ähnlichen Tabellenkalkulationsprogrammen wie OpenOffice Calc oder Apple Numbers erstellt werden. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### NUMBERS {#NUMBERS}
```
public static final FileType NUMBERS
```


Stellt Apple Numbers (.numbers) dar, das ein Excel‑ähnliches Binärdateiformat repräsentiert. Solche Dateien können mit der Apple Numbers‑Anwendung erstellt werden. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://fileinfo.com/extension/numbers

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Stellt ein Microsoft Excel Open XML‑Tabellenblatt (.xlsx) dar, das ein bekanntes Format für Microsoft‑Excel‑Dokumente ist, das von Microsoft mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Stellt ein Excel Open XML Makro‑aktiviertes Tabellenblatt (.xlsm) dar, das ein Tabellendateityp ist, der Makros unterstützt. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Stellt ein Excel‑Binär‑Tabellenblatt (.xlsb) dar, das das Excel‑Binärdateiformat definiert. Es ist eine Sammlung von Datensätzen und Strukturen, die den Inhalt einer Excel‑Arbeitsmappe festlegen. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


Stellt eine Comma‑Separated‑Values‑Datei (.csv) dar, die Klartextdateien repräsentiert, die Datensätze mit kommagetrennten Werten enthalten. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


Stellt eine Tab‑Separated‑Values‑Datei (.tsv) dar, die Daten im Klartextformat mit Tab‑Trennzeichen darstellt. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


Stellt ein OpenDocument‑Tabellenblatt (.ods) dar, das für das OpenDocument‑Tabellendokumentformat steht, das vom Benutzer bearbeitbar ist. Daten werden in ODF‑Dateien in Zeilen und Spalten gespeichert. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/spreadsheet/ods

### FODS {#FODS}
```
public static final FileType FODS
```


Stellt ein OpenDocument Flat XML‑Tabellenblatt (.fods) dar. Es ist ein auf XML basierendes Tabellenblattformat, das von OpenOffice und LibreOffice verwendet wird. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/spreadsheet/fods

### OTS {#OTS}
```
public static final FileType OTS
```


Stellt eine OpenDocument‑Tabellenvorlage (.ots) dar. Es ist ein Vorlagendokumentformat, das von OpenOffice und LibreOffice für Tabellen verwendet wird. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/spreadsheet/ots

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Stellt ein Microsoft Excel Add‑in (.xlam) dar. Es ist ein Dateiformat, das von Microsoft Excel verwendet wird, um Add‑ins mit benutzerdefinierter Funktionalität zu erstellen. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://fileinfo.com/extension/xlam

### XLTM {#XLTM}
```
public static final FileType XLTM
```


Stellt eine Microsoft Excel Makro‑aktivierte Vorlage (.xltm) dar, die Dateien repräsentiert, die von Microsoft Excel als makroaktivierte Vorlagendateien erzeugt werden. XLTM‑Dateien ähneln XLTX in ihrer Struktur, außer dass Letztere keine Vorlagendateien mit Makros unterstützen. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltm

### XLT {#XLT}
```
public static final FileType XLT
```


Stellt eine Microsoft Excel Vorlage (.xlt) dar, die Vorlagendateien sind, die mit Microsoft Excel erstellt wurden, einer Tabellenkalkulationsanwendung, die Teil der Microsoft Office‑Suite ist. Microsoft Office 97‑2003 unterstützte das Erstellen neuer XLT‑Dateien sowie das Öffnen dieser. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlt

### XLTX {#XLTX}
```
public static final FileType XLTX
```


Stellt eine Excel Open‑XML‑Tabellenvorlage (.xltx) dar, die Microsoft Excel‑Vorlagen basierend auf den Office‑OpenXML‑Dateiformatspezifikationen repräsentiert. Sie wird verwendet, um eine Standardvorlagendatei zu erstellen, die zur Erzeugung von XLSX‑Dateien mit denselben in der XLTX‑Datei angegebenen Einstellungen genutzt werden kann. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltx

### SXC {#SXC}
```
public static final FileType SXC
```


Stellt eine StarOffice Calc‑Tabellendatei (.sxc) dar. Es ist ein Tabellendokument, das mit StarOffice Calc, einem Tabellenkalkulationsprogramm, erstellt wurde. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/sxc

### MPP {#MPP}
```
public static final FileType MPP
```


Stellt eine Microsoft Project‑Datei (.mpp) dar, die eine Microsoft Project‑Datendatei ist und Informationen zum Projektmanagement integriert speichert. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/project-management/mpp

### MPT {#MPT}
```
public static final FileType MPT
```


Stellt eine Microsoft Project‑Vorlage (.mpt) dar, die Grundinformationen und -struktur sowie Dokumenteinstellungen für die Erstellung von .MPP‑Dateien enthält. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/project-management/mpt

### MPX {#MPX}
```
public static final FileType MPX
```


Stellt eine Microsoft Project Exchange‑Datei (.mpx) dar, ein ASCII‑Dateiformat zum Austausch von Projektinformationen zwischen Microsoft Project (MSP) und anderen Anwendungen, die das MPX‑Dateiformat unterstützen, wie Primavera Project Planner, Sciforma und Timerline Precision Estimating. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/project-management/mpx

### AS {#AS}
```
public static final FileType AS
```


Stellt eine ActionScript‑Datei (.as) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/programming/as

### AS_3 {#AS-3}
```
public static final FileType AS_3
```


Stellt eine ActionScript‑Datei (.as3) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://datatypes.net/open-as3-files

### ASM {#ASM}
```
public static final FileType ASM
```


Stellt eine Assembler‑Quellcodedatei (.asm) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/cad/asm

### BAT {#BAT}
```
public static final FileType BAT
```


Stellt eine DOS‑Batch‑Datei (.bat) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/executable/bat

### C {#C}
```
public static final FileType C
```


Stellt eine C/C++‑Quellcodedatei (.c) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/programming/c

### CC {#CC}
```
public static final FileType CC
```


Stellt eine C++‑Quellcodedatei (.cc) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/programming/cc

### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Stellt eine CMake‑Datei (.cmake) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/programming/cmake

### CPP {#CPP}
```
public static final FileType CPP
```


Stellt eine C++‑Quellcodedatei (.cpp) dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/programming/cpp

### CS {#CS}
```
public static final FileType CS
```


Stellt eine C\#‑Quellcodedatei (.cs) dar, die eine Quellcodedatei für die Programmiersprache C\# ist. Sie wurde von Microsoft für die Verwendung mit dem .NET Framework eingeführt. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/programming/cs

### VB {#VB}
```
public static final FileType VB
```


Stellt eine Visual‑Basic‑Projektdatei (.vb) dar, die eine Quellcodedatei ist, die in der Visual‑Basic‑Sprache erstellt wurde. Sie wurde von Microsoft für die Entwicklung von .NET‑Anwendungen erstellt. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://wiki.fileformat.com/programming/vb

### CSS {#CSS}
```
public static final FileType CSS
```


Stellt eine Cascading Style Sheet (.css)-Datei dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/web/css

### CXX {#CXX}
```
public static final FileType CXX
```


Stellt eine C++-Quellcodedatei (.cxx) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://docs.fileformat.com/programming/cxx

### DIFF {#DIFF}
```
public static final FileType DIFF
```


Stellt eine Patch-Datei (.diff) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://docs.fileformat.com/programming/diff

### ERB {#ERB}
```
public static final FileType ERB
```


Stellt ein Ruby ERB‑Skript (.erb) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://docs.fileformat.com/programming/erb

### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Stellt eine Groovy‑Quellcodedatei (.groovy) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/programming/groovy

### H {#H}
```
public static final FileType H
```


Stellt eine C/C++/Objective‑C-Header‑Datei (.h) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://docs.fileformat.com/programming/h

### HAML {#HAML}
```
public static final FileType HAML
```


Stellt eine Haml‑Quellcodedatei (.haml) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/programming/haml

### HH {#HH}
```
public static final FileType HH
```


Stellt eine C++‑Header‑Datei (.hh) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://docs.fileformat.com/programming/hh

### JAVA {#JAVA}
```
public static final FileType JAVA
```


Stellt eine Java‑Quellcodedatei (.java) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/programming/java

### JS {#JS}
```
public static final FileType JS
```


Stellt eine JavaScript‑Datei (.js) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://docs.fileformat.com/web/js

### JSON {#JSON}
```
public static final FileType JSON
```


Stellt eine JavaScript Object Notation‑Datei (.json) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://docs.fileformat.com/web/json

### LESS {#LESS}
```
public static final FileType LESS
```


Stellt eine LESS‑Style‑Sheet‑Datei (.less) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/web/less

### LOG {#LOG}
```
public static final FileType LOG
```


Stellt eine Protokolldatei (.log) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://docs.fileformat.com/database/log

### M {#M}
```
public static final FileType M
```


Stellt eine Objective‑C‑Implementierungsdatei (.m) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://fileinfo.com/extension/m

### MAKE {#MAKE}
```
public static final FileType MAKE
```


Stellt ein Xcode‑Makefile‑Skript (.make) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://docs.fileformat.com/programming/make

### MD {#MD}
```
public static final FileType MD
```


Stellt eine Markdown‑Dokumentationsdatei (.md) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://docs.fileformat.com/word-processing/md

### ML {#ML}
```
public static final FileType ML
```


Stellt eine ML‑Quellcodedatei (.ml) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/programming/ml

### MM {#MM}
```
public static final FileType MM
```


Stellt eine Objective‑C++‑Quellcodedatei (.mm) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://docs.fileformat.com/programming/mm

### PHP {#PHP}
```
public static final FileType PHP
```


Stellt eine PHP‑Quellcodedatei (.php) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://wiki.fileformat.com/programming/php

### PL {#PL}
```
public static final FileType PL
```


Stellt ein Perl‑Skript (.pl) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://docs.fileformat.com/programming/pl

### PROPERTIES {#PROPERTIES}
```
public static final FileType PROPERTIES
```


Stellt eine Java‑Properties‑Datei (.properties) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://fileinfo.com/extension/properties

### PY {#PY}
```
public static final FileType PY
```


Stellt ein Python‑Skript (.py) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://docs.fileformat.com/programming/py

### RB {#RB}
```
public static final FileType RB
```


Stellt eine Ruby‑Quellcodedatei (.rb) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://docs.fileformat.com/programming/rb

### RST {#RST}
```
public static final FileType RST
```


Stellt eine reStructuredText‑Datei (.rst) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://docs.fileformat.com/programming/rst

### SASS {#SASS}
```
public static final FileType SASS
```


Stellt eine Syntactically Awesome StyleSheets‑Datei (.sass) dar. Erfahren Sie mehr über dieses Dateiformat [hier][].


[here]: https://docs.fileformat.com/web/sass

### SCALA {#SCALA}
```
public static final FileType SCALA
```


Stellt eine Scala-Quellcodedatei (.scala) dar. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://docs.fileformat.com/programming/scala

### SCM {#SCM}
```
public static final FileType SCM
```


Stellt eine Scheme-Quellcodedatei (.scm) dar. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://docs.fileformat.com/programming/scm

### SCRIPT {#SCRIPT}
```
public static final FileType SCRIPT
```


Stellt eine generische Skriptdatei (.script) dar. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://docs.fileformat.com/programming/script

### SH {#SH}
```
public static final FileType SH
```


Stellt ein Bash-Shellskript (.sh) dar. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://docs.fileformat.com/cs/programming/sh

### SML {#SML}
```
public static final FileType SML
```


Stellt eine Standard-ML-Quellcodedatei (.sml) dar. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://fileinfo.com/extension/sml

### SQL {#SQL}
```
public static final FileType SQL
```


Stellt eine Structured Query Language-Datendatei (.sql) dar. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://wiki.fileformat.com/database/sql

### VIM {#VIM}
```
public static final FileType VIM
```


Stellt eine Vim-Einstellungsdatei (.vim) dar. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://fileinfo.com/extension/vim

### YAML {#YAML}
```
public static final FileType YAML
```


Stellt ein YAML-Dokument (.yaml) dar. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://docs.fileformat.com/programming/yaml

### DOC {#DOC}
```
public static final FileType DOC
```


Stellt ein Microsoft Word-Dokument (.doc) dar. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://wiki.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Stellt ein Microsoft Word Open XML-Dokument (.docx) dar. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://wiki.fileformat.com/word-processing/docx

### CHM {#CHM}
```
public static final FileType CHM
```


Stellt eine Microsoft Compiled HTML Help-Datei (.chm) dar. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://docs.fileformat.com/web/chm

### DOCM {#DOCM}
```
public static final FileType DOCM
```


Stellt ein Word Open XML-Makroaktiviertes Dokument (.docm) dar. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://wiki.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


Stellt eine Word-Dokumentvorlage (.dot) dar. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://wiki.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Stellt eine Word Open XML-Dokumentvorlage (.dotx) dar. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://wiki.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Stellt eine Word Open XML-Makroaktivierte Dokumentvorlage (.dotm) dar. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://wiki.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


Stellt eine Rich Text Format-Datei (.rtf) dar. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://wiki.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


Stellt eine Plain-Text-Datei (.txt) dar. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://wiki.fileformat.com/word-processing/txt

### ODT {#ODT}
```
public static final FileType ODT
```


Stellt ein OpenDocument-Textdokument (.odt) dar. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://wiki.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


Stellt eine OpenDocument-Dokumentvorlage (.ott) dar. Es ist ein Vorlagendokument, das in Übereinstimmung mit dem OpenDocument-Standardformat von OASIS erstellt wurde. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://wiki.fileformat.com/word-processing/ott

### VCF {#VCF}
```
public static final FileType VCF
```


Stellt eine vCard-Datei (.vcf) dar, die ein digitales Dateiformat zum Speichern von Kontaktinformationen ist. Sie wird häufig für den Datenaustausch zwischen gängigen Informationsaustausch-Anwendungen verwendet. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://wiki.fileformat.com/email/vcf

### AI {#AI}
```
public static final FileType AI
```


Stellt eine Adobe Illustrator-Datei (.ai) dar, die ein Dateiformat für Adobe Illustrator-Zeichnungen ist. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://docs.fileformat.com/image/ai

### PSM1 {#PSM1}
```
public static final FileType PSM1
```


Stellt eine PowerShell-Skriptmoduldatei (.psm1) dar. Es ist ein Dateiformat für PowerShell-Modulskripte. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://fileinfo.com/extension/psm1

### PS1 {#PS1}
```
public static final FileType PS1
```


Stellt eine PowerShell-Skriptdatei (.ps1) dar. Es ist ein Dateiformat für Windows PowerShell-Cmdlet-Dateien. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


[here]: https://fileinfo.com/extension/ps1

### PSD1 {#PSD1}
```
public static final FileType PSD1
```


Stellt eine PowerShell-Skriptmodulmanifestdatei (.psd1) dar. Es ist ein Dateiformat für PowerShell-Modulmanifestskripte. Weitere Informationen zu diesem Dateiformat finden Sie [hier][].


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

Diese Methode nimmt eine Dateierweiterung, mit oder ohne den Punkt ".", und gibt den entsprechenden Dateityp zurück, wenn er unterstützt wird. Wenn der Dateityp nicht unterstützt wird, gibt sie den Standard [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN)-Dateityp zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| extension | java.lang.String | Die Dateierweiterung mit oder ohne den Punkt ".". |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromFilePath(String filePath) {#fromFilePath-java.lang.String-}
```
public static FileType fromFilePath(String filePath)
```


Extrahiert die Dateierweiterung aus einem Dateinamen oder Dateipfad und ordnet sie einem Dateityp zu.

Wenn der Dateityp unterstützt wird, gibt die Methode den entsprechenden FileType zurück, andernfalls gibt sie den Standard [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN)-Dateityp zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateiname oder Dateipfad. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromMediaType(String mediaType) {#fromMediaType-java.lang.String-}
```
public static FileType fromMediaType(String mediaType)
```


Ordnet einen Dateimedientyp einem Dateityp zu. Zum Beispiel wird 'application/pdf' auf [PDF](../../com.groupdocs.viewer/filetype\#PDF) abgebildet.

Diese Methode nimmt einen Dateimedientyp als Eingabe und ordnet ihn dem entsprechenden FileType zu. Wenn der Medientyp unterstützt wird, gibt die Methode den entsprechenden Dateityp zurück. Wenn der Medientyp nicht unterstützt wird, gibt sie den Standard [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN)-Dateityp zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mediaType | java.lang.String | Der Dateimedientyp, z.B. 'application/pdf'. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if found, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream stream)
```


Ermittelt den Dateityp durch Lesen der Dateisignatur.

Diese Methode nimmt einen Eingabestream, der eine Datei darstellt, und versucht, den Dateityp zu erkennen, indem sie die Dateisignatur analysiert. Die Dateisignatur ist eine eindeutige Byte‑Sequenz am Anfang der Datei, die ihren Dateityp angibt. Die Methode liest die Dateisignatur aus dem Eingabestream und vergleicht sie mit bekannten Dateisignaturen unterstützter Dateitypen. Wird eine Übereinstimmung gefunden, gibt die Methode den entsprechenden Dateityp zurück. Wird keine Übereinstimmung gefunden, gibt sie den Standard [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN)-Dateityp zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Der Eingabestream, der die Datei darstellt. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password) {#fromStream-java.io.InputStream-java.lang.String-}
```
public static FileType fromStream(InputStream stream, String password)
```


Ermittelt den Dateityp durch Lesen der Dateisignatur.

Diese Methode analysiert die Dateisignatur, eine eindeutige Byte‑Sequenz am Anfang der Datei, um den Dateityp zu bestimmen. Sie liest die Dateisignatur aus dem bereitgestellten Eingabestream und vergleicht sie mit bekannten Dateisignaturen unterstützter Dateitypen. Wird eine Übereinstimmung gefunden, gibt die Methode den entsprechenden Dateityp zurück. Wird keine Übereinstimmung gefunden, gibt sie den Standard [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN)-Dateityp zurück.

Wenn die Datei verschlüsselt ist und ein Passwort zum Öffnen benötigt, sollte das Passwort als Parameter an diese Methode übergeben werden. Das Passwort wird verwendet, um die Datei zu entschlüsseln und ihre Signatur zu analysieren, um den Dateityp zu bestimmen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Der Eingabestream, der die Datei darstellt. |
| password | java.lang.String | Das Passwort zum Öffnen der Datei. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, ILogger logger) {#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, ILogger logger)
```


Ermittelt den Dateityp durch Lesen der Dateisignatur.

Diese Methode analysiert die Dateisignatur, eine eindeutige Byte‑Sequenz am Anfang der Datei, um den Dateityp zu bestimmen. Sie liest die Dateisignatur aus dem bereitgestellten Eingabestream und vergleicht sie mit bekannten Dateisignaturen unterstützter Dateitypen. Wird eine Übereinstimmung gefunden, gibt die Methode den entsprechenden Dateityp zurück. Wird keine Übereinstimmung gefunden, gibt sie den Standard [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN)-Dateityp zurück.

Ein Logger kann bereitgestellt werden, um relevante Informationen oder Fehler während des Dateityp‑Erkennungsprozesses zu protokollieren. Der Logger sollte das ILogger‑Interface implementieren. Wenn kein Logger bereitgestellt wird, erzeugt der Erkennungsprozess keine Protokollausgabe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Der Eingabestream, der die Datei darstellt. |
| Logger | com.groupdocs.foundation.logging.ILogger | Der Logger zum Protokollieren von Informationen oder Fehlern. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password, ILogger logger) {#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, String password, ILogger logger)
```


Ermittelt den Dateityp durch Lesen der Dateisignatur.

Diese Methode analysiert die Dateisignatur, eine eindeutige Byte‑Sequenz am Anfang der Datei, um den Dateityp zu bestimmen. Sie liest die Dateisignatur aus dem bereitgestellten Eingabestream und vergleicht sie mit bekannten Dateisignaturen unterstützter Dateitypen. Wird eine Übereinstimmung gefunden, gibt die Methode den entsprechenden Dateityp zurück. Wird keine Übereinstimmung gefunden, gibt sie den Standard [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN)-Dateityp zurück.

Ein Passwort kann angegeben werden, wenn die Datei verschlüsselt oder geschützt ist. Das Passwort wird verwendet, um die Datei vor der Analyse der Dateisignatur zu öffnen. Wenn die Datei kein Passwort benötigt, kann dieser Parameter auf null gesetzt werden.

Ein Logger kann bereitgestellt werden, um relevante Informationen oder Fehler während des Dateityp‑Erkennungsprozesses zu protokollieren. Der Logger sollte das ILogger‑Interface implementieren. Wenn kein Logger bereitgestellt wird, erzeugt der Erkennungsprozess keine Protokollausgabe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Der Eingabestream, der die Datei darstellt. |
| password | java.lang.String | Das Passwort zum Öffnen der Datei. |
| Logger | com.groupdocs.foundation.logging.ILogger | Der Logger zum Protokollieren von Informationen oder Fehlern. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Ruft die unterstützten Dateitypen ab.

Diese Methode gibt eine Sequenz aller vom System unterstützten Dateitypen zurück. Die Dateitypen repräsentieren verschiedene Dokumentformate, die vom System verarbeitet oder erkannt werden können.

 **Learn more**

 *  Learn more about the supported document formats: [Full list of supported file formats][]


[Full list of supported file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/

**Returns:**
java.util.List<com.groupdocs.viewer.FileType> - eine Sequenz unterstützter Dateitypen.
### detectCharset(String filePath) {#detectCharset-java.lang.String-}
```
public static Charset detectCharset(String filePath)
```


Versucht, den Zeichensatz von Textdateien [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) und [CSV](../../com.groupdocs.viewer/filetype\#CSV) anhand des Pfads zu erkennen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateiname oder Dateipfad. |

**Returns:**
java.nio.charset.Charset - Charset oder null, wenn die Erkennung des Dateicharsets fehlschlägt.

**Example:**

```
Charset charset = FileType.detectCharset("message.txt");
```
### detectCharset(InputStream stream) {#detectCharset-java.io.InputStream-}
```
public static Charset detectCharset(InputStream stream)
```


Versucht, den Zeichensatz von Textdateien [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) und [CSV](../../com.groupdocs.viewer/filetype\#CSV) anhand des Streams zu erkennen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Der Dateistream. |

**Returns:**
java.nio.charset.Charset - Charset oder null, wenn die Erkennung des Dateicharsets fehlschlägt.

**Example:**

```
InputStream stream = new FileInputStream("message.txt");
 Charset charset = FileType.detectCharset(stream);
```
### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Ermittelt den Namen des Dateiformats, z. B. „Microsoft Word Document“.

**Returns:**
java.lang.String - der Name des Dateiformats.
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Ermittelt das Dateierweiterungs‑Suffix (einschließlich des Punktes "."), z. B. ".doc".

**Returns:**
java.lang.String - die Dateierweiterungsendung.
### toString() {#toString--}
```
public String toString()
```


Gibt eine Zeichenkettenrepräsentation des aktuellen Objekts zurück.

**Returns:**
java.lang.String - eine Zeichenkettenrepräsentation des aktuellen Objekts.
