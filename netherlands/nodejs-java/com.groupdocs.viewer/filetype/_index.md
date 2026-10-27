---
title: "FileType"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Stelt het bestandstype voor."
type: docs
weight: 14
url: /nl/nodejs-java/com.groupdocs.viewer/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, com.groupdocs.viewer.caching.Cacheable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>, Cacheable
```

Stelt het bestandstype voor. Biedt methoden om een lijst van alle bestandstypen die door de GroupDocs.Viewer-component worden ondersteund te verkrijgen.

De FileType-enum biedt constanten die verschillende bestandstypen vertegenwoordigen die door de GroupDocs.Viewer-component worden ondersteund. Je kunt de methoden in deze enum gebruiken om een lijst van alle ondersteunde bestandstypen te verkrijgen of om te controleren of een specifiek bestandstype wordt ondersteund.

Voorbeeldgebruik:

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
## Velden

| Veld | Beschrijving |
| --- | --- |
| [UNKNOWN](#UNKNOWN) | Stelt een onbekend bestandstype voor. |
| [ZIP](#ZIP) | Stelt een zip-bestand (.zip) voor dat een of meer bestanden of mappen kan bevatten. |
| [TAR](#TAR) | Stelt een geconsolideerd Unix-bestandsarchief (.tar) voor dat is aangemaakt om één of meer bestanden te verzamelen. |
| [XZ](#XZ) | Stelt een XZ-bestand (.xz) voor dat gecomprimeerd is met een hoogcompressie-algoritme gebaseerd op het LZMA-algoritme. |
| [TXZ](#TXZ) | Stelt een geconsolideerd Unix-bestandsarchief (.txz, .tar.xz) voor dat is aangemaakt om één of meer bestanden te verzamelen. |
| [TARXZ](#TARXZ) | Stelt een geconsolideerd Unix-bestandsarchief (.txz, .tar.xz) voor dat is aangemaakt om één of meer bestanden te verzamelen. |
| [TGZ](#TGZ) | Stelt een geconsolideerd Unix-bestandsarchief (.tgz, .tar.gz) voor dat is aangemaakt om één of meer bestanden te verzamelen. |
| [TARGZ](#TARGZ) | Stelt een geconsolideerd Unix-bestandsarchief (.tgz, .tar.gz) voor dat is aangemaakt om één of meer bestanden te verzamelen. |
| [BZ_2](#BZ-2) | Stelt een Bzip2-gecomprimeerd bestand (.bz2) voor dat is gegenereerd met de open-source compressiemethode BZIP2. |
| [RAR](#RAR) | Stelt een Roshal-archief (.rar) voor dat gecomprimeerd is met de RAR (WINRAR versie 4) compressiemethode. |
| [GZ](#GZ) | Stelt een Gnu-gecomprimeerd bestand (.gz) voor dat is aangemaakt met de gzip-compressietoepassing. |
| [GZIP](#GZIP) | Stelt een Gnu Zipped File (.gzip) gecomprimeerd bestand voor dat is geïntroduceerd als een gratis hulpprogramma ter vervanging van het Compress-programma dat in Unix-systemen werd gebruikt. |
| [SEVEN_ZIP](#SEVEN-ZIP) | Stelt een 7Zip (.7z, .7zip) bestand voor, dat een gratis open-source archiver is met LZMA- en LZMA2-compressie. |
| [CPIO](#CPIO) | Cpio is een algemene bestandsarchiveringsutility en het bijbehorende bestandsformaat. |
| [ZSTANDARD](#ZSTANDARD) | ZST-bestand is een gecomprimeerd bestand dat wordt gegenereerd met het Zstandard (zstd) compressie-algoritme. |
| [TZST](#TZST) | TZST-bestanden (.tar.zst, .tzst) zijn Zstandard-archieven (ZST), die intern een Consolidated Unix File Archive (Tar) bevatten, gemaakt met een Unix-gebaseerde utility voor het verzamelen van één of meer bestanden. |
| [TAR_ZST](#TAR-ZST) | TZST-bestanden (.tar.zst, .tzst) zijn Zstandard-archieven (ZST), die intern een Consolidated Unix File Archive (Tar) bevatten, gemaakt met een Unix-gebaseerde utility voor het verzamelen van één of meer bestanden. |
| [ISO](#ISO) | ISO-optische schijf‑image is een ongecomprimeerd archief‑schijf‑imagebestand dat de inhoud van alle gegevens op een optische schijf zoals een CD of DVD weergeeft, gebaseerd op de ISO‑9660‑standaard. |
| [LHA](#LHA) | LHA of LZH is een freeware compressie‑utility en bijbehorend bestandsformaat. |
| [CAB](#CAB) | Cabinet (of CAB) is een archief‑bestandformaat voor Microsoft Windows. |
| [DXF](#DXF) | Stelt een Drawing Exchange Format‑bestand (.dxf) voor, dat een getagde gegevensrepresentatie van een AutoCAD-tekenbestand is. |
| [DWG](#DWG) | Stelt een AutoCAD Drawing Database‑bestand (.dwg) voor, dat propriëtaire binaire bestanden vertegenwoordigt die worden gebruikt voor het bevatten van 2D‑ en 3D‑ontwerpgegevens. |
| [DWT](#DWT) | Stelt een AutoCAD Drawing Template‑bestand (.dwt) voor, dat een AutoCAD‑teken sjabloonbestand is dat wordt gebruikt als startpunt voor het maken van tekeningen die als DWG‑bestanden kunnen worden opgeslagen. |
| [STL](#STL) | Stelt een Stereolithography‑bestand (.stl) voor, dat een uitwisselbaar bestandsformaat is dat 3‑dimensionale oppervlakgeometrie weergeeft. |
| [IFC](#IFC) | Stelt een Industry Foundation Classes‑bestand (.ifc) voor, dat een bestandsformaat is dat internationale normen vaststelt voor het importeren en exporteren van bouwobjecten en hun eigenschappen. |
| [DWF](#DWF) | Stelt een Design Web Format‑bestand (.dwf) voor, dat een gecomprimeerd bestandsformaat is voor het bekijken, beoordelen of afdrukken van 2D/3D‑tekeningen. |
| [FBX](#FBX) | Stelt een Autodesk FBX Interchange‑bestand (FilmBoX) (.fbx) voor, dat een 3D‑modelformaat is. |
| [DWFX](#DWFX) | Stelt een Design Web Format‑bestand XPS (.dwfx) voor, dat een gecomprimeerd formaat is voor het bekijken, beoordelen of afdrukken van 2D/3D‑tekeningen als een XPS‑document. |
| [DGN](#DGN) | Stelt een MicroStation Design‑bestand (.dgn) voor, dat tekeningen zijn die zijn gemaakt en ondersteund door CAD‑toepassingen zoals MicroStation en Intergraph Interactive Graphics Design System. |
| [PLT](#PLT) | Stelt een PLT (HPGL)‑bestand (.plt) voor, dat een vector‑gebaseerd plotter‑bestand is geïntroduceerd door Autodesk, Inc. |
| [CF2](#CF2) | Stelt een Common File Format‑bestand (.cf2) voor. |
| [OBJ](#OBJ) | Stelt een Wavefront 3D Object‑bestand (.obj) voor, dat een 3D‑afbeeldingsbestand is geïntroduceerd door Wavefront Technologies. |
| [HPG](#HPG) | Stelt een PLT (HPGL)‑bestand (.hpg) voor. |
| [IGS](#IGS) | Stelt een Initial Graphics Exchange Specification (IGES)‑bestand (.igs) voor. |
| [VSD](#VSD) | Stelt een Visio Drawing‑bestand (.vsd) voor, dat tekeningen zijn die zijn gemaakt met de Microsoft Visio‑applicatie om een verscheidenheid aan grafische objecten en hun onderlinge verbindingen weer te geven. |
| [VSDX](#VSDX) | Stelt een Visio Drawing‑bestand (.vsdx) voor, dat het Microsoft Visio‑bestandsformaat vertegenwoordigt dat is geïntroduceerd vanaf Microsoft Office 2013 en later. |
| [VSS](#VSS) | Stelt een Visio Stencil‑bestand (.vss) voor, dat stencil‑bestanden zijn die zijn gemaakt met Microsoft Visio 2007 en eerder. |
| [VSSX](#VSSX) | Stelt een Visio Stencil File (.vssx) voor, die tekensjablonen zijn die zijn gemaakt met Microsoft Visio 2013 en hoger. |
| [VSDM](#VSDM) | Stelt een Visio Macro-Enabled Drawing (.vsdm) voor, die tekenbestanden zijn die zijn gemaakt met de Microsoft Visio-toepassing en macro's ondersteunen. |
| [VST](#VST) | Stelt een Visio Drawing Template (.vst) voor, die vectorafbeeldingsbestanden zijn die zijn gemaakt met Microsoft Visio. |
| [VSTX](#VSTX) | Stelt een Visio Drawing Template (.vstx) voor, die tekensjabloonbestanden zijn die zijn gemaakt met Microsoft Visio 2013 en hoger. |
| [VSTM](#VSTM) | Stelt een Visio Macro-Enabled Drawing Template (.vstm) voor, die sjabloonbestanden zijn die zijn gemaakt met Microsoft Visio en macro's ondersteunen. |
| [VSSM](#VSSM) | Stelt een Visio Macro-Enabled Stencil File (.vssm) voor, die Microsoft Visio Stencil-bestanden zijn die macro's ondersteunen. |
| [VSX](#VSX) | Stelt een Visio Stencil XML File (.vsx) voor, die verwijst naar sjablonen bestaande uit tekeningen en vormen die worden gebruikt voor het maken van diagrammen in Microsoft Visio. |
| [VTX](#VTX) | Stelt een Visio Template XML File (.vtx) voor, die een Microsoft Visio-tekenjabloon is dat op schijf is opgeslagen in XML-bestandsformaat. |
| [VDW](#VDW) | Stelt een Visio Web Drawing (.vdw) voor, die de streams en opslaglocaties specificeert die nodig zijn voor het renderen van een webtekening. |
| [VDX](#VDX) | Stelt een Visio Drawing XML File (.vdx) voor, die elke tekening of grafiek die in Microsoft Visio is gemaakt representeert, maar opgeslagen is in XML-formaat met de .VDX-extensie. |
| [EPUB](#EPUB) | Stelt een Open eBook File (.epub) voor, die een e-boekbestandsformaat is dat een standaard digitaal publicatieformaat biedt voor uitgevers en consumenten. |
| [MOBI](#MOBI) | Stelt een Mobipocket eBook (.mobi) voor, die een van de meest gebruikte e-boekbestandsformaten is. |
| [AZW_3](#AZW-3) | Amazon Kindle Format 8 (KF8) e-boek is het digitale bestandsformaat dat is ontwikkeld voor Amazon Kindle-apparaten. |
| [MSG](#MSG) | Stelt een Outlook Mail Message (.msg) voor, die een bestandsformaat is dat door Microsoft Outlook en Exchange wordt gebruikt om e-mailberichten, contactpersonen, afspraken of andere taken op te slaan. |
| [EML](#EML) | Stelt een E-Mail Message (.eml) voor, die e-mailberichten representeert die zijn opgeslagen met Outlook en andere relevante toepassingen. |
| [EMLX](#EMLX) | Stelt een Apple Mail Message (.emlx) voor, die is geïmplementeerd en ontwikkeld door Apple. |
| [PST](#PST) | Stelt een Outlook Personal Information Store File (.pst) voor, die Outlook Personal Storage Files (ook wel Personal Storage Table genoemd) representeert die een verscheidenheid aan gebruikersinformatie opslaan. |
| [OST](#OST) | Stelt een Outlook Offline Data File (.ost) voor, die de mailboxgegevens van een gebruiker in offline-modus op een lokale machine representeert na registratie bij Exchange Server met Microsoft Outlook. |
| [TIF](#TIF) | Stelt een Tagged Image File (.tif) voor, die rasterafbeeldingen representeert die bedoeld zijn voor gebruik op diverse apparaten die aan deze bestandsformaatstandaard voldoen. |
| [TIFF](#TIFF) | Stelt een Tagged Image File Format (.tiff) voor, die rasterafbeeldingen representeert die bedoeld zijn voor gebruik op diverse apparaten die aan deze bestandsformaatstandaard voldoen. |
| [JPG](#JPG) | Stelt een JPEG Image (.jpg) voor, die een type afbeeldingsformaat is dat wordt opgeslagen met behulp van verliesgevende compressie. |
| [JPEG](#JPEG) | Stelt een JPEG Image (.jpeg) voor, die een type afbeeldingsformaat is dat wordt opgeslagen met behulp van verliesgevende compressie. |
| [JFIF](#JFIF) | JPEG File Interchange Format (.jfif) is een afbeelding die is ontwikkeld voor snelle uitwisseling tussen platformen. |
| [PNG](#PNG) | Stelt een Portable Network Graphic (.png) voor, die een type rasterafbeeldingsbestand is dat verliesloze compressie gebruikt. |
| [GIF](#GIF) | Stelt een Graphical Interchange Format File (.gif) voor, die een type sterk gecomprimeerde afbeelding is. |
| [APNG](#APNG) | Stelt een Animated Portable Network Graphic (.apng) voor, een uitbreiding van het PNG-formaat die animatie ondersteunt. |
| [BMP](#BMP) | Duidt een Bitmap Image File (.bmp) aan, die wordt gebruikt om bitmap digitale afbeeldingen op te slaan. |
| [ICO](#ICO) | Stelt een Icon File (.ico) voor, een afbeeldingsbestandtype dat wordt gebruikt als pictogram voor de weergave van een applicatie op Microsoft Windows. |
| [TGA](#TGA) | Stelt een Truevision TGA (TARGA)-bestand voor, dat wordt gebruikt om bitmap digitale afbeeldingen op te slaan die zijn ontwikkeld door TRUEVISION. |
| [JP_2](#JP-2) | Stelt een JPEG 2000 Core Image File (.jp2) voor, een beeldcodering systeem en geavanceerde beeldcompressiestandaard. |
| [JPF](#JPF) | Stelt een JPEG 2000 Image File (.jpf) voor. |
| [JPX](#JPX) | Stelt een JPEG 2000 Image File (.jpx) voor. |
| [JPM](#JPM) | Stelt een JPEG 2000 Image File (.jpm) voor. |
| [J2C](#J2C) | Stelt een JPEG 2000 Code InputStream (.j2c) voor. |
| [J2K](#J2K) | Stelt een JPEG 2000 Code Stream (.j2k) voor, een afbeelding die gecomprimeerd is met waveletcompressie in plaats van DCT-compressie. |
| [JPC](#JPC) | Stelt een JPEG 2000 Code Stream (.jpc) voor. |
| [JLS](#JLS) | Stelt een JPEG-LS (JLS)-bestand (.jls) voor. |
| [DIB](#DIB) | Stelt een Device Independent Bitmap File (.dib) voor. |
| [WMF](#WMF) | Stelt een Windows Metafile (.wmf) voor, dat Microsoft Windows Metafile (WMF) vertegenwoordigt voor het opslaan van zowel vector- als bitmapformaat beeldgegevens. |
| [WMZ](#WMZ) | Stelt een Compressed Windows Metafile (.wmz) voor, dat Microsoft Windows Metafile (WMF) vertegenwoordigt, gecomprimeerd in een GZIP-archief voor het opslaan van zowel vector- als bitmapformaat beeldgegevens. |
| [EMF](#EMF) | Stelt een Enhanced Windows Metafile (.emf) voor, dat grafische afbeeldingen apparaatonafhankelijk weergeeft. |
| [EMZ](#EMZ) | Stelt een Windows Compressed Enhanced Metafile (.emz) voor, dat grafische afbeeldingen apparaatonafhankelijk weergeeft en gecomprimeerd is met GZIP. |
| [WEBP](#WEBP) | Stelt een WebP Image (.webp) voor, een modern raster webafbeeldingsformaat gebaseerd op verliesvrije en verliesgevende compressie. |
| [DNG](#DNG) | Stelt een Digital Negative Specification (.dng) voor, een digitaal camerabeeldformaat dat wordt gebruikt voor de opslag van raw-bestanden. |
| [CDR](#CDR) | Stelt een CorelDraw Vector Graphic Drawing (.cdr) voor, een vectortekeningsbestand dat native is gemaakt met CorelDRAW voor het opslaan van digitaal gecodeerde en gecomprimeerde afbeeldingen. |
| [CMX](#CMX) | Stelt een Corel Exchange (.cmx) voor, een tekeningsbestand dat zowel vectorafbeeldingen als bitmapafbeeldingen kan bevatten. |
| [DJVU](#DJVU) | Stelt een DjVu Image (.djvu) voor, een grafisch bestandsformaat bedoeld voor gescande documenten en boeken, vooral die met een combinatie van tekst, tekeningen, afbeeldingen en foto’s. |
| [CGM](#CGM) | Stelt een Computer Graphics Metafile (.cgm) voor, een gratis, platformonafhankelijk, internationaal standaard metafile-formaat voor het opslaan en uitwisselen van vectorafbeeldingen (2D), rasterafbeeldingen en tekst. |
| [PCL](#PCL) | Stelt een Printer Command Language Document (.pcl) voor. |
| [PSD](#PSD) | Stelt een Adobe Photoshop Document (.psd) voor, het native bestandsformaat van Adobe Photoshop dat wordt gebruikt voor grafisch ontwerp en ontwikkeling. |
| [PSB](#PSB) | Vertegenwoordigt een Photoshop Large Document Format (.psb), dat wordt gebruikt voor grafisch ontwerp en ontwikkeling in Adobe Photoshop. |
| [DCM](#DCM) | Vertegenwoordigt een DICOM-afbeelding (.dcm), die een digitale afbeelding is die medische informatie van patiënten opslaat, zoals MRI's, CT-scans en echobeelden. |
| [PS](#PS) | Vertegenwoordigt een PostScript-bestand (.ps). |
| [EPS](#EPS) | Vertegenwoordigt een Encapsulated PostScript-bestand (.eps), dat een Encapsulated PostScript-taalprogramma beschrijft dat de weergave van een enkele pagina definieert. |
| [ODG](#ODG) | Vertegenwoordigt een OpenDocument Graphic-bestand (.odg), dat wordt gebruikt door de Draw-toepassing van Apache OpenOffice om tekenelementen op te slaan als een vectorafbeelding. |
| [FODG](#FODG) | Vertegenwoordigt een Flat XML ODF-sjabloon (.fodg), dat wordt gebruikt door de Draw-toepassing van Apache OpenOffice om tekenelementen op te slaan als een vectorafbeelding. |
| [SVG](#SVG) | Vertegenwoordigt een Scalable Vector Graphics-bestand (.svg), dat een Scalar Vector Graphics-bestand is dat een XML-gebaseerd tekstformaat gebruikt om het uiterlijk van een afbeelding te beschrijven. |
| [SVGZ](#SVGZ) | Vertegenwoordigt een gecomprimeerd Scalable Vector Graphics-bestand (.svgz), dat een Scalar Vector Graphics-bestand is dat een XML-gebaseerd tekstformaat gebruikt, gecomprimeerd met GZIP, om het uiterlijk van een afbeelding te beschrijven. |
| [OTG](#OTG) | Vertegenwoordigt een OpenDocument Graphic-sjabloon (.otg). |
| [HTM](#HTM) | Vertegenwoordigt een Hypertext Markup Language-bestand (.htm), dat de extensie is voor webpagina's die zijn gemaakt voor weergave in browsers. |
| [HTML](#HTML) | Vertegenwoordigt een Hypertext Markup Language-bestand (.html), dat de extensie is voor webpagina's die zijn gemaakt voor weergave in browsers. |
| [MHT](#MHT) | Vertegenwoordigt een MHTML-webarchief (.mht). |
| [NSF](#NSF) | Vertegenwoordigt een Lotus Notes-database (.nsf). |
| [MBOX](#MBOX) | Vertegenwoordigt een e-mailmailboxbestand (.mbox). |
| [MHTML](#MHTML) | Vertegenwoordigt een MIME HTML-bestand (.mhtml). |
| [XML](#XML) | Vertegenwoordigt een XML-bestand (.xml). |
| [ONE](#ONE) | Vertegenwoordigt een OneNote-document (.one) gemaakt door de Microsoft OneNote-toepassing. |
| [PDF](#PDF) | Vertegenwoordigt een Portable Document Format-bestand (.pdf), dat een type document is dat in de jaren 1990 door Adobe werd gemaakt. |
| [XPS](#XPS) | Vertegenwoordigt een XML Paper Specification-bestand (.xps), dat paginalay-outbestanden vertegenwoordigt die gebaseerd zijn op XML Paper Specifications en zijn gemaakt door Microsoft. |
| [OXPS](#OXPS) | Vertegenwoordigt een OpenXPS-bestand (.oxps). |
| [TEX](#TEX) | Vertegenwoordigt een LaTeX-brondocument (.tex), dat een taal is die zowel programmeer- als opmaakfuncties omvat die worden gebruikt om documenten op te maken. |
| [PPT](#PPT) | Vertegenwoordigt een PowerPoint-presentatie (.ppt), die een PowerPoint-bestand vertegenwoordigt dat bestaat uit een verzameling dia's voor weergave als diavoorstelling. |
| [PPTX](#PPTX) | Vertegenwoordigt een PowerPoint Open XML-presentatie (.pptx), die presentatiesbestanden zijn die zijn gemaakt met de populaire Microsoft PowerPoint-toepassing. |
| [PPS](#PPS) | Vertegenwoordigt een PowerPoint-diavoorstelling (.pps), die zijn gemaakt met Microsoft PowerPoint voor diavoorstellingsdoeleinden. |
| [PPSX](#PPSX) | Vertegenwoordigt PowerPoint Open XML-diavoorstellingsbestanden (.ppsx), die zijn gemaakt met Microsoft PowerPoint 2007 en hoger voor diavoorstellingsdoeleinden. |
| [ODP](#ODP) | Stelt een OpenDocument-presentatie (.odp) voor, die een presentatiebestandsformaat vertegenwoordigt dat wordt gebruikt door OpenOffice.org in de OASISOpen-standaard. |
| [FODP](#FODP) | Stelt een OpenDocument-presentatie (.fodp) voor, die een OpenDocument Flat XML-presentatie vertegenwoordigt. |
| [POT](#POT) | Stelt een PowerPoint-sjabloon (.pot) voor, die Microsoft PowerPoint-sjabloonbestanden vertegenwoordigt die zijn gemaakt door PowerPoint‑versies 97‑2003. |
| [PPTM](#PPTM) | Stelt een PowerPoint Open XML macro‑ingeschakelde presentatie (.pptm) voor, die macro‑ingeschakelde presentatiesbestanden vertegenwoordigt die zijn gemaakt met Microsoft PowerPoint 2007 of hogere versies. |
| [POTX](#POTX) | Stelt een PowerPoint Open XML presentatiesjabloon (.potx) voor, die Microsoft PowerPoint-sjabloonpresentaties vertegenwoordigt die zijn gemaakt met Microsoft PowerPoint 2007 en hoger. |
| [POTM](#POTM) | Stelt een PowerPoint Open XML macro‑ingeschakelde presentatiesjabloon (.potm) voor, die Microsoft PowerPoint-sjabloonbestanden met macro‑ondersteuning vertegenwoordigt. |
| [PPSM](#PPSM) | Stelt een PowerPoint Open XML macro‑ingeschakelde dia (.ppsm) voor, die een macro‑ingeschakeld diavoorstellingbestand vertegenwoordigt dat is gemaakt met Microsoft PowerPoint 2007 of hoger. |
| [OTP](#OTP) | Stelt een OpenDocument-presentatiesjabloon (.otp) voor, die presentatiesjabloonbestanden vertegenwoordigt die zijn gemaakt door applicaties in het OASIS OpenDocument-standaardformaat. |
| [XLS](#XLS) | Stelt een Excel-werkblad (.xls) voor, dat het Excel Binary File Format vertegenwoordigt. |
| [EXCEL_2003_XML](#EXCEL-2003-XML) | Stelt een Excel 2003 XML (SpreadsheetML) (.xml) voor, dat het Excel Binary File Format vertegenwoordigt. |
| [NUMBERS](#NUMBERS) | Stelt Apple Numbers (.numbers) voor, dat een Excel‑achtig binair bestandsformaat vertegenwoordigt. |
| [XLSX](#XLSX) | Stelt een Microsoft Excel Open XML-werkblad (.xlsx) voor, een bekend formaat voor Microsoft Excel‑documenten dat werd geïntroduceerd door Microsoft met de release van Microsoft Office 2007. |
| [XLSM](#XLSM) | Stelt een Excel Open XML macro‑ingeschakeld werkblad (.xlsm) voor, een type werkbladbestand dat macro's ondersteunt. |
| [XLSB](#XLSB) | Stelt een Excel binair werkblad (.xlsb) voor, dat het Excel Binary File Format specificeert. |
| [CSV](#CSV) | Stelt een komma‑gescheiden waarden‑bestand (.csv) voor, dat platte‑tekstbestanden vertegenwoordigt die gegevensrecords bevatten met komma‑gescheiden waarden. |
| [TSV](#TSV) | Stelt een tab‑gescheiden waarden‑bestand (.tsv) voor, dat gegevens vertegenwoordigt die in platte‑tekstformaat met tabs zijn gescheiden. |
| [ODS](#ODS) | Stelt een OpenDocument-werkblad (.ods) voor, dat staat voor het OpenDocument-werkbladdocumentformaat dat door de gebruiker bewerkbaar is. |
| [FODS](#FODS) | Stelt een OpenDocument Flat XML-werkblad (.fods) voor. |
| [OTS](#OTS) | Stelt een OpenDocument-werkbladsjabloon (.ots) voor. |
| [XLAM](#XLAM) | Stelt een Microsoft Excel-add‑in (.xlam) voor. |
| [XLTM](#XLTM) | Stelt een Microsoft Excel macro‑ingeschakelde sjabloon (.xltm) voor, die bestanden vertegenwoordigt die door Microsoft Excel worden gegenereerd als macro‑ingeschakelde sjabloonbestanden. |
| [XLT](#XLT) | Stelt een Microsoft Excel-sjabloon (.xlt) voor, die sjabloonbestanden vertegenwoordigt die zijn gemaakt met Microsoft Excel, een spreadsheet‑applicatie die deel uitmaakt van de Microsoft Office‑suite. |
| [XLTX](#XLTX) | Stelt een Excel Open XML-werkbladsjabloon (.xltx) voor, die Microsoft Excel-sjablonen vertegenwoordigt op basis van de Office OpenXML‑bestandsformaat‑specificaties. |
| [SXC](#SXC) | Stelt een StarOffice Calc-werkblad (.sxc) voor. |
| [MPP](#MPP) | Stelt een Microsoft Project‑bestand (.mpp) voor, dat een Microsoft Project‑databestand is dat informatie met betrekking tot projectbeheer op geïntegreerde wijze opslaat. |
| [MPT](#MPT) | Stelt een Microsoft Project-sjabloon (.mpt) voor, dat basisinformatie en structuur bevat, samen met documentinstellingen voor het maken van .MPP-bestanden. |
| [MPX](#MPX) | Stelt een Microsoft Project Exchange-bestand (.mpx) voor, dat een ASCII-bestandsformaat is voor het overdragen van projectinformatie tussen Microsoft Project (MSP) en andere toepassingen die het MPX-bestandsformaat ondersteunen, zoals Primavera Project Planner, Sciforma en Timerline Precision Estimating. |
| [AS](#AS) | Stelt een ActionScript-bestand (.as) voor. |
| [AS_3](#AS-3) | Stelt een ActionScript-bestand (.as3) voor. |
| [ASM](#ASM) | Stelt een Assembly Language-broncodebestand (.asm) voor. |
| [BAT](#BAT) | Stelt een DOS-batchbestand (.bat) voor. |
| [C](#C) | Stelt een C/C++-broncodebestand (.c) voor. |
| [CC](#CC) | Stelt een C++-broncodebestand (.cc) voor. |
| [CMAKE](#CMAKE) | Stelt een CMake-bestand (.cmake) voor. |
| [CPP](#CPP) | Stelt een C++-broncodebestand (.cpp) voor. |
| [CS](#CS) | Stelt een C\#-broncodebestand (.cs) voor, dat een broncodebestand is voor de C\# programmeertaal. |
| [VB](#VB) | Stelt een Visual Basic Project Item-bestand (.vb) voor, dat een broncodebestand is dat is gemaakt in de Visual Basic-taal. |
| [CSS](#CSS) | Stelt een Cascading Style Sheet-bestand (.css) voor. |
| [CXX](#CXX) | Stelt een C++-broncodebestand (.cxx) voor. |
| [DIFF](#DIFF) | Stelt een patchbestand (.diff) voor. |
| [ERB](#ERB) | Stelt een Ruby ERB-script (.erb) voor. |
| [GROOVY](#GROOVY) | Stelt een Groovy-broncodebestand (.groovy) voor. |
| [H](#H) | Stelt een C/C++/Objective-C-headerbestand (.h) voor. |
| [HAML](#HAML) | Stelt een Haml-broncodebestand (.haml) voor. |
| [HH](#HH) | Stelt een C++-headerbestand (.hh) voor. |
| [JAVA](#JAVA) | Stelt een Java-broncodebestand (.java) voor. |
| [JS](#JS) | Stelt een JavaScript-bestand (.js) voor. |
| [JSON](#JSON) | Stelt een JavaScript Object Notation-bestand (.json) voor. |
| [LESS](#LESS) | Stelt een LESS-stylesheet (.less) bestand voor. |
| [LOG](#LOG) | Stelt een logbestand (.log) voor. |
| [M](#M) | Stelt een Objective-C-implementatiebestand (.m) voor. |
| [MAKE](#MAKE) | Stelt een Xcode-Makefile‑script (.make) voor. |
| [MD](#MD) | Stelt een Markdown‑documentatiebestand (.md) voor. |
| [ML](#ML) | Stelt een ML‑broncodebestand (.ml) voor. |
| [MM](#MM) | Stelt een Objective-C++‑bronbestand (.mm) voor. |
| [PHP](#PHP) | Stelt een PHP‑broncodebestand (.php) voor. |
| [PL](#PL) | Stelt een Perl‑script (.pl) voor. |
| [PROPERTIES](#PROPERTIES) | Stelt een Java‑eigenschappenbestand (.properties) voor. |
| [PY](#PY) | Stelt een Python‑script (.py) voor. |
| [RB](#RB) | Stelt een Ruby‑broncodebestand (.rb) voor. |
| [RST](#RST) | Stelt een reStructuredText‑bestand (.rst) voor. |
| [SASS](#SASS) | Stelt een Syntactically Awesome StyleSheets‑bestand (.sass) voor. |
| [SCALA](#SCALA) | Stelt een Scala‑broncodebestand (.scala) voor. |
| [SCM](#SCM) | Stelt een Scheme‑broncodebestand (.scm) voor. |
| [SCRIPT](#SCRIPT) | Stelt een generiek scriptbestand (.script) voor. |
| [SH](#SH) | Stelt een Bash‑shellscript (.sh) voor. |
| [SML](#SML) | Stelt een Standard ML‑broncodebestand (.sml) voor. |
| [SQL](#SQL) | Stelt een Structured Query Language‑databestand (.sql) voor. |
| [VIM](#VIM) | Stelt een Vim‑instellingenbestand (.vim) voor. |
| [YAML](#YAML) | Stelt een YAML‑document (.yaml) voor. |
| [DOC](#DOC) | Stelt een Microsoft Word‑document (.doc) voor. |
| [DOCX](#DOCX) | Stelt een Microsoft Word Open XML‑document (.docx) voor. |
| [CHM](#CHM) | Stelt een Microsoft gecompileerd HTML‑helpbestand (.chm) voor. |
| [DOCM](#DOCM) | Stelt een Word Open XML‑macro‑ingeschakeld document (.docm) voor. |
| [DOT](#DOT) | Stelt een Word‑documenttemplate (.dot) voor. |
| [DOTX](#DOTX) | Stelt een Word Open XML Document Template (.dotx) bestand voor. |
| [DOTM](#DOTM) | Stelt een Word Open XML Macro-Enabled Document Template (.dotm) bestand voor. |
| [RTF](#RTF) | Stelt een Rich Text Format-bestand (.rtf) voor. |
| [TXT](#TXT) | Stelt een platte tekstbestand (.txt) voor. |
| [ODT](#ODT) | Stelt een OpenDocument Tekstdocument (.odt) voor. |
| [OTT](#OTT) | Stelt een OpenDocument Document Template (.ott) voor. |
| [VCF](#VCF) | Stelt een vCard-bestand (.vcf) voor, dat een digitaal bestandsformaat is voor het opslaan van contactinformatie. |
| [AI](#AI) | Stelt een Adobe Illustrator-bestand (.ai) voor, dat een bestandsformaat is voor Adobe Illustrator-tekeningen. |
| [PSM1](#PSM1) | Stelt een PowerShell scriptmodulebestand (.psm1) voor. |
| [PS1](#PS1) | Stelt een PowerShell scriptbestand (.ps1) voor. |
| [PSD1](#PSD1) | Stelt een PowerShell scriptmodule-manifestbestand (.psd1) voor. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Koppelt een bestandsextensie aan een bestandstype. |
| [fromFilePath(String filePath)](#fromFilePath-java.lang.String-) | Haalt de bestandsextensie uit een bestandsnaam of bestandspad en koppelt deze aan een bestandstype. |
| [fromMediaType(String mediaType)](#fromMediaType-java.lang.String-) | Koppelt een bestandsmediatype aan een bestandstype. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Detecteert het bestandstype door de bestandssignatuur te lezen. |
| [fromStream(InputStream stream, String password)](#fromStream-java.io.InputStream-java.lang.String-) | Detecteert het bestandstype door de bestandssignatuur te lezen. |
| [fromStream(InputStream stream, ILogger logger)](#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-) | Detecteert het bestandstype door de bestandssignatuur te lezen. |
| [fromStream(InputStream stream, String password, ILogger logger)](#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-) | Detecteert het bestandstype door de bestandssignatuur te lezen. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | Haalt de ondersteunde bestandstypen op. |
| [detectCharset(String filePath)](#detectCharset-java.lang.String-) | Probeert de tekenset van tekstbestanden [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) en [CSV](../../com.groupdocs.viewer/filetype\#CSV) te detecteren op basis van het pad. |
| [detectCharset(InputStream stream)](#detectCharset-java.io.InputStream-) | Probeert de tekenset van tekstbestanden [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) en [CSV](../../com.groupdocs.viewer/filetype\#CSV) te detecteren op basis van de stream. |
| [getFileFormat()](#getFileFormat--) | Haalt de naam van het bestandsformaat op, bijv. "Microsoft Word Document". |
| [getExtension()](#getExtension--) | Haalt het bestandsextensie-achtervoegsel op (inclusief de punt "."), bijv. ".doc". |
| [toString()](#toString--) | Retourneert een tekenreeksrepresentatie van het huidige object. |
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Stelt een onbekend bestandstype voor.

### ZIP {#ZIP}
```
public static final FileType ZIP
```


Stelt een gecomprimeerd bestand (.zip) voor dat een of meer bestanden of mappen kan bevatten. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/compression/zip

### TAR {#TAR}
```
public static final FileType TAR
```


Stelt een samengevoegd Unix-bestandsarchief (.tar) voor dat is gemaakt om een of meer bestanden te verzamelen. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/compression/tar

### XZ {#XZ}
```
public static final FileType XZ
```


Stelt een XZ-bestand (.xz) voor dat gecomprimeerd is met een hoogcompressie-algoritme gebaseerd op het LZMA-algoritme. Meer informatie over dit bestandsformaat [hier][].


[here]: https://fileinfo.com/extension/xz

### TXZ {#TXZ}
```
public static final FileType TXZ
```


Stelt een samengevoegd Unix-bestandsarchief (.txz, .tar.xz) voor dat is gemaakt om een of meer bestanden te verzamelen. Meer informatie over dit bestandsformaat [hier][].


[here]: https://fileinfo.com/extension/txz

### TARXZ {#TARXZ}
```
public static final FileType TARXZ
```


Stelt een samengevoegd Unix-bestandsarchief (.txz, .tar.xz) voor dat is gemaakt om een of meer bestanden te verzamelen. Meer informatie over dit bestandsformaat [hier][].


[here]: https://fileinfo.com/extension/txz

### TGZ {#TGZ}
```
public static final FileType TGZ
```


Stelt een samengevoegd Unix-bestandsarchief (.tgz, .tar.gz) voor dat is gemaakt om een of meer bestanden te verzamelen. Meer informatie over dit bestandsformaat [hier][].


[here]: https://fileinfo.com/extension/tgz

### TARGZ {#TARGZ}
```
public static final FileType TARGZ
```


Stelt een samengevoegd Unix-bestandsarchief (.tgz, .tar.gz) voor dat is gemaakt om een of meer bestanden te verzamelen. Meer informatie over dit bestandsformaat [hier][].


[here]: https://fileinfo.com/extension/tgz

### BZ_2 {#BZ-2}
```
public static final FileType BZ_2
```


Stelt een Bzip2-gecomprimeerd bestand (.bz2) voor dat is gegenereerd met de BZIP2 open‑source compressiemethode. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/compression/bz2

### RAR {#RAR}
```
public static final FileType RAR
```


Stelt een Roshal‑archief (.rar) gecomprimeerd bestand voor dat is gegenereerd met de RAR (WINRAR versie 4) compressiemethode. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/compression/rar

### GZ {#GZ}
```
public static final FileType GZ
```


Stelt een Gnu‑gecomprimeerd bestand (.gz) voor dat is aangemaakt met de gzip-compressietoepassing. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/compression/gz

### GZIP {#GZIP}
```
public static final FileType GZIP
```


Stelt een Gnu‑gecomprimeerd bestand (.gzip) voor dat is geïntroduceerd als een gratis hulpprogramma ter vervanging van het Compress‑programma dat in Unix‑systemen werd gebruikt. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/compression/gz

### SEVEN_ZIP {#SEVEN-ZIP}
```
public static final FileType SEVEN_ZIP
```


Stelt een 7Zip‑bestand (.7z, .7zip) voor, een gratis open‑source archiver met LZMA‑ en LZMA2‑compressie. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/compression/7z/

### CPIO {#CPIO}
```
public static final FileType CPIO
```


Cpio is een algemene bestandsarchiveringsutility en het bijbehorende bestandsformaat. Het wordt voornamelijk geïnstalleerd op Unix‑achtige besturingssystemen. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/compression/cpio

### ZSTANDARD {#ZSTANDARD}
```
public static final FileType ZSTANDARD
```


Een ZST‑bestand is een gecomprimeerd bestand dat wordt gegenereerd met het Zstandard (zstd) compressie‑algoritme. Het is een gecomprimeerd bestand dat met verliesloze compressie door het algoritme wordt gemaakt. ZST‑bestanden kunnen worden gebruikt om verschillende soorten bestanden te comprimeren, zoals databases, bestandssystemen, netwerken en games. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/compression/zst/

### TZST {#TZST}
```
public static final FileType TZST
```


TZST-bestanden (.tar.zst, .tzst) zijn Zstandard-archieven (ZST), die intern een Consolidated Unix File Archive (Tar) bevatten, gemaakt met een Unix-gebaseerde utility voor het verzamelen van één of meer bestanden.

### TAR_ZST {#TAR-ZST}
```
public static final FileType TAR_ZST
```


TZST-bestanden (.tar.zst, .tzst) zijn Zstandard-archieven (ZST), die intern een Consolidated Unix File Archive (Tar) bevatten, gemaakt met een Unix-gebaseerde utility voor het verzamelen van één of meer bestanden.

### ISO {#ISO}
```
public static final FileType ISO
```


Een ISO‑optische schijf‑image is een ongecomprimeerd archief‑schijf‑imagebestand dat de inhoud van een volledige data op een optische schijf zoals een CD of DVD weergeeft, gebaseerd op de ISO‑9660‑standaard. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/compression/iso/

### LHA {#LHA}
```
public static final FileType LHA
```


LHA of LZH is een freeware compressie‑utility en het bijbehorende bestandsformaat. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/compression/lzh/

### CAB {#CAB}
```
public static final FileType CAB
```


Cabinet (of CAB) is een archief‑bestandformaat voor Microsoft Windows. Meer informatie over dit bestandsformaat [hier][].


[here]: https://en.wikipedia.org/wiki/Cabinet_%28file_format%29

### DXF {#DXF}
```
public static final FileType DXF
```


Stelt een Drawing Exchange Format‑bestand (.dxf) voor, een getagde gegevensrepresentatie van een AutoCAD‑tekenbestand. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/cad/dxf

### DWG {#DWG}
```
public static final FileType DWG
```


Stelt een AutoCAD Drawing Database‑bestand (.dwg) voor, een propriëtair binair bestand dat wordt gebruikt voor het bevatten van 2D‑ en 3D‑ontwerpgegevens. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/cad/dwg

### DWT {#DWT}
```
public static final FileType DWT
```


Stelt een AutoCAD Drawing Template‑bestand (.dwt) voor, een AutoCAD‑tekeningssjabloon dat wordt gebruikt als startpunt voor het maken van tekeningen die als DWG‑bestanden kunnen worden opgeslagen. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/cad/dwt

### STL {#STL}
```
public static final FileType STL
```


Stelt een Stereolithography‑bestand (.stl) voor, een uitwisselbaar bestandsformaat dat 3‑dimensionale oppervlakte‑geometrie weergeeft. Het wordt veel gebruikt bij rapid prototyping, 3D‑printen en computer‑aided manufacturing. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/cad/stl

### IFC {#IFC}
```
public static final FileType IFC
```


Stelt een Industry Foundation Classes‑bestand (.ifc) voor, een bestandsformaat dat internationale normen vastlegt voor het importeren en exporteren van bouwobjecten en hun eigenschappen. Het maakt interoperabiliteit tussen verschillende softwaretoepassingen mogelijk. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/cad/ifc

### DWF {#DWF}
```
public static final FileType DWF
```


Stelt een Design Web Format‑bestand (.dwf) voor, een gecomprimeerd bestandsformaat voor het bekijken, beoordelen of afdrukken van 2D/3D‑tekeningen. Het bevat grafische elementen en tekst als onderdeel van de ontwerpgegevens en verkleint de bestandsgrootte door compressie. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/cad/dwf

### FBX {#FBX}
```
public static final FileType FBX
```


Stelt een Autodesk FBX Interchange‑bestand (FilmBoX) (.fbx) voor, een 3D‑modelformaat. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/cad/fbx

### DWFX {#DWFX}
```
public static final FileType DWFX
```


Stelt een Design Web Format‑bestand XPS (.dwfx) voor, een gecomprimeerd formaat voor het bekijken, beoordelen of afdrukken van 2D/3D‑tekeningen als een XPS‑document. Het bevat grafische elementen en tekst als onderdeel van de ontwerpgegevens en verkleint de bestandsgrootte door compressie. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/cad/dwfx

### DGN {#DGN}
```
public static final FileType DGN
```


Stelt een MicroStation Design‑bestand (.dgn) voor, tekeningen die zijn gemaakt en ondersteund door CAD‑toepassingen zoals MicroStation en Intergraph Interactive Graphics Design System. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/cad/dgn

### PLT {#PLT}
```
public static final FileType PLT
```


Stelt een PLT (HPGL) bestand (.plt) voor, dat een vectorgebaseerd plotterbestand is geïntroduceerd door Autodesk, Inc. Het bevat informatie voor een bepaald CAD‑bestand, en alle afbeeldingen worden afgedrukt met lijnen in plaats van punten, waardoor nauwkeurigheid en precisie in de productie worden gegarandeerd. Leer meer over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/cad/plt

### CF2 {#CF2}
```
public static final FileType CF2
```


Stelt een Common File Format‑bestand (.cf2) voor. Leer meer over dit bestandsformaat [hier][].


[here]: https://fileinfo.com/extension/cf2

### OBJ {#OBJ}
```
public static final FileType OBJ
```


Stelt een Wavefront 3D Object‑bestand (.obj) voor, dat een 3D‑afbeeldingsbestand is geïntroduceerd door Wavefront Technologies. Leer meer over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/3d/obj/

### HPG {#HPG}
```
public static final FileType HPG
```


Stelt een PLT (HPGL) bestand (.hpg) voor. Het is een bestandsformaat dat wordt gebruikt voor plotterbestanden in de HP Graphics Language (HPGL). Leer meer over dit bestandsformaat [hier][].


[here]: https://fileinfo.com/extension/hpg

### IGS {#IGS}
```
public static final FileType IGS
```


Stelt een Initial Graphics Exchange Specification (IGES)‑bestand (.igs) voor.

### VSD {#VSD}
```
public static final FileType VSD
```


Stelt een Visio-tekenbestand (.vsd) voor, dat tekeningen zijn gemaakt met de Microsoft Visio‑applicatie om een verscheidenheid aan grafische objecten en hun onderlinge verbindingen weer te geven. Leer meer over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/image/vsd

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Stelt een Visio-tekenbestand (.vsdx) voor, dat het Microsoft Visio‑bestandsformaat vertegenwoordigt dat vanaf Microsoft Office 2013 is geïntroduceerd. Het verving het binaire bestandsformaat (.VSD) dat werd ondersteund door eerdere versies van Microsoft Visio. Leer meer over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/image/vsdx

### VSS {#VSS}
```
public static final FileType VSS
```


Stelt een Visio‑stencilbestand (.vss) voor, dat stencil‑bestanden zijn gemaakt met Microsoft Visio 2007 en eerder. Stencil‑bestanden bieden tekenobjecten die kunnen worden opgenomen in een .VSD Visio‑tekening. Leer meer over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/image/vss

### VSSX {#VSSX}
```
public static final FileType VSSX
```


Stelt een Visio‑stencilbestand (.vssx) voor, dat teken‑stencils zijn gemaakt met Microsoft Visio 2013 en hoger. Het VSSX‑bestandsformaat kan worden geopend met Visio 2013 en hoger. Visio‑bestanden staan bekend om het vertegenwoordigen van diverse tekenelementen zoals vormen, connectoren, stroomdiagrammen, netwerklay-outs, UML‑diagrammen, enz. Leer meer over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/image/vssx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Stelt een Visio macro‑ingeschakelde tekening (.vsdm) voor, dat tekenbestanden zijn gemaakt met de Microsoft Visio‑applicatie die macro's ondersteunen. VSDM‑bestanden zijn OPC/XML‑tekeningen die vergelijkbaar zijn met VSDX, maar ook de mogelijkheid bieden om macro's uit te voeren wanneer het bestand wordt geopend. Leer meer over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/image/vsdm

### VST {#VST}
```
public static final FileType VST
```


Stelt een Visio-teken‑sjabloon (.vst) voor, dat vectorafbeeldingsbestanden zijn gemaakt met Microsoft Visio. Ze fungeren als sjablonen voor het maken van verdere bestanden en bevatten de standaardlay-out en instellingen die worden gebruikt voor het maken van nieuwe Visio‑tekeningen. Leer meer over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/image/vst

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Stelt een Visio-teken‑sjabloon (.vstx) voor, dat teken‑sjabloonbestanden zijn gemaakt met Microsoft Visio 2013 en hoger. Deze VSTX‑bestanden bieden een startpunt voor het maken van Visio‑tekeningen die worden opgeslagen als .VSDX‑bestanden, met standaardlay-out en instellingen. Leer meer over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Stelt een Visio macro‑ingeschakelde teken‑sjabloon (.vstm) voor, dat sjabloonbestanden zijn gemaakt met Microsoft Visio die macro's ondersteunen. Bestanden die zijn gemaakt vanuit VSTM‑sjablonen kunnen macro's uitvoeren die zijn ontwikkeld in Visual Basic for Applications (VBA)-code. Leer meer over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Stelt een Visio macro‑ingeschakeld stencil‑bestand (.vssm) voor, dat Microsoft Visio‑stencilbestanden zijn die macro's ondersteunen. Wanneer een VSSM‑bestand wordt geopend, kunnen macro's worden uitgevoerd om de gewenste opmaak en plaatsing van vormen in een diagram te realiseren. Leer meer over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Stelt een Visio stencil‑XML‑bestand (.vsx) voor, dat verwijst naar stencils bestaande uit tekeningen en vormen die worden gebruikt voor het maken van diagrammen in Microsoft Visio. VSX‑bestanden worden opgeslagen in XML‑bestandsformaat en werden ondersteund tot Visio 2013. Leer meer over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


Stelt een Visio‑sjabloon‑XML‑bestand (.vtx) voor, dat een Microsoft Visio‑teken‑sjabloon is dat op schijf wordt opgeslagen in XML‑bestandsformaat. Het sjabloon biedt basisinstellingen voor het maken van meerdere Visio‑bestanden met dezelfde instellingen. Leer meer over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/image/vtx

### VDW {#VDW}
```
public static final FileType VDW
```


Stelt een Visio‑webtekening (.vdw) voor, die de streams en opslaglocaties specificeert die nodig zijn voor het renderen van een webtekening. Leer meer over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/web/vdw

### VDX {#VDX}
```
public static final FileType VDX
```


Stelt een Visio-tekening XML-bestand (.vdx) voor, dat elke tekening of diagram vertegenwoordigt die is gemaakt in Microsoft Visio maar is opgeslagen in XML-indeling met de .VDX-extensie. Een Visio-tekening XML-bestand wordt aangemaakt in de Visio-software die door Microsoft is ontwikkeld. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Stelt een Open eBook-bestand (.epub) voor, dat een e‑bookbestandsformaat is dat een standaard digitaal publicatieformaat biedt voor uitgevers en consumenten. Het formaat wordt ondersteund door veel e‑readers en softwaretoepassingen. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/ebook/epub

### MOBI {#MOBI}
```
public static final FileType MOBI
```


Stelt een Mobipocket eBook (.mobi) voor, dat een van de meest gebruikte e‑bookbestandsformaten is. Het formaat is een verbetering van het oude OEB (Open Ebook Format) en werd gebruikt als een propriëtair formaat voor Mobipocket Reader. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/ebook/mobi

### AZW_3 {#AZW-3}
```
public static final FileType AZW_3
```


Amazon Kindle Format 8 (KF8) e‑book is het digitale bestandsformaat dat is ontwikkeld voor Amazon Kindle‑apparaten. Het formaat is een verbetering ten opzichte van oudere AZW‑bestanden en wordt alleen op Kindle Fire‑apparaten gebruikt met achterwaartse compatibiliteit voor het voorouderformaat, d.w.z. MOBI en AZW. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/ebook/azw3

### MSG {#MSG}
```
public static final FileType MSG
```


Stelt een Outlook‑mailbericht (.msg) voor, dat een bestandsformaat is dat door Microsoft Outlook en Exchange wordt gebruikt om e‑mailberichten, contactpersonen, afspraken of andere taken op te slaan. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/email/msg

### EML {#EML}
```
public static final FileType EML
```


Stelt een e‑mailbericht (.eml) voor, dat e‑mailberichten vertegenwoordigt die zijn opgeslagen met Outlook en andere relevante toepassingen. Bijna alle e‑mailclients ondersteunen dit bestandsformaat vanwege de naleving van de RFC‑822 Internet Message Format‑standaard. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/email/eml

### EMLX {#EMLX}
```
public static final FileType EMLX
```


Stelt een Apple‑mailbericht (.emlx) voor, dat is geïmplementeerd en ontwikkeld door Apple. De Apple Mail‑applicatie gebruikt het EMLX‑bestandsformaat voor het exporteren van e‑mails. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/email/emlx

### PST {#PST}
```
public static final FileType PST
```


Stelt een Outlook Personal Information Store‑bestand (.pst) voor, dat Outlook Personal Storage‑bestanden (ook wel Personal Storage Table genoemd) vertegenwoordigt die een verscheidenheid aan gebruikersinformatie opslaan. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/email/pst

### OST {#OST}
```
public static final FileType OST
```


Stelt een Outlook Offline Data‑bestand (.ost) voor, dat de mailboxgegevens van een gebruiker in offline‑modus op een lokale machine weergeeft na registratie bij Exchange Server met Microsoft Outlook. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/email/ost

### TIF {#TIF}
```
public static final FileType TIF
```


Stelt een Tagged Image File (.tif) voor, dat rasterafbeeldingen vertegenwoordigt die bedoeld zijn voor gebruik op diverse apparaten die aan deze bestandsformaatstandaard voldoen. Het kan bilevel-, grijswaarden-, paletkleur- en full‑color‑beeldgegevens beschrijven in verschillende kleurenruimten. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/tiff

### TIFF {#TIFF}
```
public static final FileType TIFF
```


Stelt een Tagged Image File Format (.tiff) voor, dat rasterafbeeldingen vertegenwoordigt die bedoeld zijn voor gebruik op diverse apparaten die aan deze bestandsformaatstandaard voldoen. Het kan bilevel-, grijswaarden-, paletkleur- en full‑color‑beeldgegevens beschrijven in verschillende kleurenruimten. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/tiff

### JPG {#JPG}
```
public static final FileType JPG
```


Stelt een JPEG‑afbeelding (.jpg) voor, dat een type afbeeldingsformaat is dat wordt opgeslagen met behulp van verliesgevende compressie. De resulterende afbeelding is een afweging tussen opslaggrootte en beeldkwaliteit. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/jpeg

### JPEG {#JPEG}
```
public static final FileType JPEG
```


Stelt een JPEG‑afbeelding (.jpeg) voor, dat een type afbeeldingsformaat is dat wordt opgeslagen met behulp van verliesgevende compressie. De resulterende afbeelding is een afweging tussen opslaggrootte en beeldkwaliteit. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/jpeg

### JFIF {#JFIF}
```
public static final FileType JFIF
```


JPEG File Interchange Format (.jfif) is een afbeelding die is ontwikkeld voor snelle uitwisseling tussen platformen. Dit formaat gebruikt JPEG‑compressie. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/jfif

### PNG {#PNG}
```
public static final FileType PNG
```


Stelt een Portable Network Graphic (.png) voor, dat een type rasterafbeeldingsbestand is dat verliesloze compressie gebruikt. Dit bestandsformaat werd gecreëerd als vervanging voor het Graphics Interchange Format (GIF) en heeft geen auteursrechtenbeperkingen. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/png

### GIF {#GIF}
```
public static final FileType GIF
```


Stelt een Graphical Interchange Format-bestand (.gif) voor, dat een type sterk gecomprimeerde afbeelding is. Voor elke afbeelding ondersteunt GIF doorgaans tot 8 bits per pixel, en tot 256 kleuren zijn toegestaan over de afbeelding. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/gif

### APNG {#APNG}
```
public static final FileType APNG
```


Stelt een Animated Portable Network Graphic (.apng) voor, een extensie van het PNG-formaat die animatie ondersteunt. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/apng

### BMP {#BMP}
```
public static final FileType BMP
```


Stelt een Bitmap Image File (.bmp) voor, dat wordt gebruikt om bitmap digitale afbeeldingen op te slaan. Deze afbeeldingen zijn onafhankelijk van de grafische adapter en worden ook wel device independent bitmap (DIB) bestandsformaat genoemd. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/bmp

### ICO {#ICO}
```
public static final FileType ICO
```


Stelt een Icon File (.ico) voor, een type afbeeldingsbestand dat wordt gebruikt als pictogram voor de weergave van een toepassing op Microsoft Windows. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/ico

### TGA {#TGA}
```
public static final FileType TGA
```


Stelt een Truevision TGA (TARGA)-bestand voor, dat wordt gebruikt om bitmap digitale afbeeldingen op te slaan die zijn ontwikkeld door TRUEVISION. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/tga

### JP_2 {#JP-2}
```
public static final FileType JP_2
```


Stelt een JPEG 2000 Core Image File (.jp2) voor, een beeldcodering systeem en geavanceerde beeldcompressiestandaard. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/jp2

### JPF {#JPF}
```
public static final FileType JPF
```


Stelt een JPEG 2000 Image File (.jpf) voor. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/image/jpf

### JPX {#JPX}
```
public static final FileType JPX
```


Stelt een JPEG 2000 Image File (.jpx) voor. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/jpx

### JPM {#JPM}
```
public static final FileType JPM
```


Stelt een JPEG 2000 Image File (.jpm) voor. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/jpm

### J2C {#J2C}
```
public static final FileType J2C
```


Stelt een JPEG 2000 Code InputStream (.j2c) voor. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/j2c

### J2K {#J2K}
```
public static final FileType J2K
```


Stelt een JPEG 2000 Code Stream (.j2k) voor, een afbeelding die gecomprimeerd is met waveletcompressie in plaats van DCT-compressie. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/j2k

### JPC {#JPC}
```
public static final FileType JPC
```


Stelt een JPEG 2000 Code Stream (.jpc) voor. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/jpc

### JLS {#JLS}
```
public static final FileType JLS
```


Stelt een JPEG-LS (JLS)-bestand (.jls) voor. Meer informatie over dit bestandsformaat [here][].


[here]: https://fileinfo.com/extension/jls

### DIB {#DIB}
```
public static final FileType DIB
```


Stelt een Device Independent Bitmap File (.dib) voor. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/dib

### WMF {#WMF}
```
public static final FileType WMF
```


Stelt een Windows Metafile (.wmf) voor, dat Microsoft Windows Metafile (WMF) weergeeft voor het opslaan van zowel vector- als bitmapformaat afbeeldingsgegevens. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/wmf

### WMZ {#WMZ}
```
public static final FileType WMZ
```


Stelt een Compressed Windows Metafile (.wmz) voor, dat Microsoft Windows Metafile (WMF) gecomprimeerd in een GZIP-archief weergeeft voor het opslaan van zowel vector- als bitmapformaat afbeeldingsgegevens. Meer informatie over dit bestandsformaat [here][].


[here]: https://fileinfo.com/extension/wmz#compressed_windows_metafile

### EMF {#EMF}
```
public static final FileType EMF
```


Stelt een Enhanced Windows Metafile (.emf) voor, dat grafische afbeeldingen apparaat-onafhankelijk weergeeft. Metabestanden van EMF bestaan uit variabele lengte records in chronologische volgorde die de opgeslagen afbeelding kunnen renderen na parsing op elk uitvoerapparaat. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/emf

### EMZ {#EMZ}
```
public static final FileType EMZ
```


Stelt een Windows Compressed Enhanced Metafile (.emz) voor, dat grafische afbeeldingen apparaat-onafhankelijk comprimeert met GZIP. Metabestanden van EMF bestaan uit variabele lengte records in chronologische volgorde die de opgeslagen afbeelding kunnen renderen na parsing op elk uitvoerapparaat. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/emz

### WEBP {#WEBP}
```
public static final FileType WEBP
```


Stelt een WebP Image (.webp) voor, een modern raster webafbeeldingsformaat gebaseerd op verliesloze en verliesgevende compressie. Het levert dezelfde beeldkwaliteit terwijl het de bestandsgrootte aanzienlijk verkleint. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/webp

### DNG {#DNG}
```
public static final FileType DNG
```


Stelt een Digital Negative Specification (.dng) voor, een digitaal camera-afbeeldingsformaat dat wordt gebruikt voor de opslag van raw-bestanden. Het werd ontwikkeld door Adobe in september 2004 en wordt voornamelijk gebruikt voor digitale fotografie. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/dng

### CDR {#CDR}
```
public static final FileType CDR
```


Stelt een CorelDraw Vector Graphic Drawing (.cdr) voor, een vector-tekeningsafbeeldingsbestand dat native is aangemaakt met CorelDRAW voor het opslaan van digitaal gecodeerde en gecomprimeerde afbeeldingen. Een CDR-tekeningsbestand bevat tekst, lijnen, vormen, afbeeldingen, kleuren en effecten voor vectorrepresentatie van de inhoud van de afbeelding. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/cdr

### CMX {#CMX}
```
public static final FileType CMX
```


Stelt een Corel Exchange (.cmx) voor, een tekeningsafbeeldingsbestand dat zowel vectorafbeeldingen als bitmapafbeeldingen kan bevatten. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/cmx

### DJVU {#DJVU}
```
public static final FileType DJVU
```


Stelt een DjVu-afbeelding (.djvu) voor, die een grafisch bestandsformaat is bedoeld voor gescande documenten en boeken, vooral die met een combinatie van tekst, tekeningen, afbeeldingen en foto’s. Leer meer over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/djvu

### CGM {#CGM}
```
public static final FileType CGM
```


Stelt een Computer Graphics Metafile (.cgm) voor, dat een gratis, platformonafhankelijk, internationaal standaard metafileformaat is voor het opslaan en uitwisselen van vectorafbeeldingen (2D), rasterafbeeldingen en tekst. CGM gebruikt een objectgeoriënteerde benadering en biedt veel functies voor beeldproductie. Leer meer over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/page-description-language/cgm

### PCL {#PCL}
```
public static final FileType PCL
```


Stelt een Printer Command Language-document (.pcl) voor. Leer meer over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/page-description-language/pcl

### PSD {#PSD}
```
public static final FileType PSD
```


Stelt een Adobe Photoshop-document (.psd) voor, dat het native bestandsformaat van Adobe Photoshop is dat wordt gebruikt voor grafisch ontwerp en ontwikkeling. Leer meer over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/psd

### PSB {#PSB}
```
public static final FileType PSB
```


Stelt een Photoshop Large Document Format (.psb) voor, dat wordt gebruikt voor grafisch ontwerp en ontwikkeling in Adobe Photoshop. Leer meer over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/psb

### DCM {#DCM}
```
public static final FileType DCM
```


Stelt een DICOM-afbeelding (.dcm) voor, die een digitale afbeelding is die medische informatie van patiënten opslaat, zoals MRI's, CT-scans en echografiebeelden. Leer meer over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/dcm

### PS {#PS}
```
public static final FileType PS
```


Stelt een PostScript-bestand (.ps) voor. Leer meer over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/page-description-language/ps

### EPS {#EPS}
```
public static final FileType EPS
```


Stelt een Encapsulated PostScript-bestand (.eps) voor, dat een Encapsulated PostScript-taalprogramma beschrijft dat het uiterlijk van een enkele pagina definieert. Leer meer over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/page-description-language/eps

### ODG {#ODG}
```
public static final FileType ODG
```


Stelt een OpenDocument Graphic-bestand (.odg) voor, dat wordt gebruikt door de Draw-toepassing van Apache OpenOffice om tekenelementen op te slaan als een vectorafbeelding. Leer meer over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/odg

### FODG {#FODG}
```
public static final FileType FODG
```


Stelt een Flat XML ODF-sjabloon (.fodg) voor, dat wordt gebruikt door de Draw-toepassing van Apache OpenOffice om tekenelementen op te slaan als een vectorafbeelding. Leer meer over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/image/fodg

### SVG {#SVG}
```
public static final FileType SVG
```


Stelt een Scalable Vector Graphics-bestand (.svg) voor, dat een Scalable Vector Graphics-bestand is dat een op XML gebaseerde tekstindeling gebruikt om het uiterlijk van een afbeelding te beschrijven. Leer meer over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/page-description-language/svg

### SVGZ {#SVGZ}
```
public static final FileType SVGZ
```


Stelt een gecomprimeerd Scalable Vector Graphics-bestand (.svgz) voor, dat een Scalable Vector Graphics-bestand is dat een op XML gebaseerde tekstindeling gebruikt, gecomprimeerd met GZIP, om het uiterlijk van een afbeelding te beschrijven. Leer meer over dit bestandsformaat [here][].


[here]: https://fileinfo.com/extension/svgz

### OTG {#OTG}
```
public static final FileType OTG
```


Stelt een OpenDocument Graphic-sjabloon (.otg) voor. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/image/otg

### HTM {#HTM}
```
public static final FileType HTM
```


Stelt een Hypertext Markup Language-bestand (.htm) voor, dat de extensie is voor webpagina’s die zijn gemaakt voor weergave in browsers. Leer meer over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/web/html

### HTML {#HTML}
```
public static final FileType HTML
```


Stelt een Hypertext Markup Language-bestand (.html) voor, dat de extensie is voor webpagina’s die zijn gemaakt voor weergave in browsers. Leer meer over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


Stelt een MHTML-webarchief (.mht) voor. Leer meer over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/web/mht

### NSF {#NSF}
```
public static final FileType NSF
```


Stelt een Lotus Notes-database (.nsf) voor. Leer meer over dit bestandsformaat [here][].


[here]: https://fileinfo.com/extension/nsf

### MBOX {#MBOX}
```
public static final FileType MBOX
```


Stelt een e-mailmailboxbestand (.mbox) voor. Leer meer over dit bestandsformaat [here][].


[here]: https://fileinfo.com/extension/mbox

### MHTML {#MHTML}
```
public static final FileType MHTML
```


Stelt een MIME HTML-bestand (.mhtml) voor. Leer meer over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/web/mhtml

### XML {#XML}
```
public static final FileType XML
```


Stelt een XML-bestand (.xml) voor. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/web/xml

### ONE {#ONE}
```
public static final FileType ONE
```


Stelt een OneNote-document (.one) voor, gemaakt door de Microsoft OneNote-toepassing. OneNote stelt je in staat informatie te verzamelen met de toepassing alsof je je kladblok gebruikt om notities te maken. Leer meer over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


Stelt een Portable Document Format-bestand (.pdf) voor, dat een type document is dat in de jaren 90 door Adobe werd gecreëerd. Het doel van dit bestandsformaat was een standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van toepassingssoftware, hardware en besturingssystemen. Leer meer over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


Stelt een XML Paper Specification-bestand (.xps) voor, dat paginalay-outbestanden vertegenwoordigt op basis van XML Paper Specifications gemaakt door Microsoft. Dit formaat is ontwikkeld door Microsoft als vervanging voor het EMF-bestandsformaat en is vergelijkbaar met het PDF-bestandsformaat, maar gebruikt XML in de lay-out, weergave en afdrukinformatie van een document. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/page-description-language/xps

### OXPS {#OXPS}
```
public static final FileType OXPS
```


Stelt een OpenXPS-bestand (.oxps) voor. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/page-description-language/oxps

### TEX {#TEX}
```
public static final FileType TEX
```


Stelt een LaTeX-brondocument (.tex) voor, een taal die zowel programmeer- als opmaakfuncties bevat die worden gebruikt om documenten op te maken. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


Stelt een PowerPoint-presentatie (.ppt) voor, een PowerPoint-bestand dat bestaat uit een verzameling dia's voor weergave als diavoorstelling. Het specificeert het binaire bestandsformaat dat wordt gebruikt door Microsoft PowerPoint 97-2003. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


Stelt een PowerPoint Open XML-presentatie (.pptx) voor, presentatiebestanden die zijn gemaakt met de populaire Microsoft PowerPoint-toepassing. In tegenstelling tot de vorige versie van het presentatiebestandsformaat PPT, dat binair was, is het PPTX-formaat gebaseerd op het Microsoft PowerPoint Open XML-presentatiebestandsformaat. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


Stelt een PowerPoint-diavoorstelling (.pps) voor, die wordt gemaakt met Microsoft PowerPoint voor diavoorstellingsdoeleinden. Het lezen en maken van PPS-bestanden wordt ondersteund door Microsoft PowerPoint 97-2003. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


Stelt PowerPoint Open XML-diavoorstelling (.ppsx)-bestanden voor, die worden gemaakt met Microsoft PowerPoint 2007 en hoger voor diavoorstellingsdoeleinden. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


Stelt een OpenDocument-presentatie (.odp) voor, een presentatiebestandsformaat dat wordt gebruikt door OpenOffice.org volgens de OASIS Open-standaard. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/presentation/odp

### FODP {#FODP}
```
public static final FileType FODP
```


Stelt een OpenDocument-presentatie (.fodp) voor, die OpenDocument Flat XML Presentation vertegenwoordigt. Meer informatie over dit bestandsformaat [here][].


[here]: https://fileinfo.com/extension/fodp

### POT {#POT}
```
public static final FileType POT
```


Stelt een PowerPoint-sjabloon (.pot) voor, Microsoft PowerPoint-sjabloonbestanden die zijn gemaakt met PowerPoint 97-2003-versies. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/presentation/pot

### PPTM {#PPTM}
```
public static final FileType PPTM
```


Stelt een PowerPoint Open XML-macro-ingeschakelde presentatie (.pptm) voor, macro-ingeschakelde presentatiebestanden die zijn gemaakt met Microsoft PowerPoint 2007 of hogere versies. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/presentation/pptm

### POTX {#POTX}
```
public static final FileType POTX
```


Stelt een PowerPoint Open XML-presentatiesjabloon (.potx) voor, Microsoft PowerPoint-sjabloonpresentaties die zijn gemaakt met Microsoft PowerPoint 2007 en hoger. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/presentation/potx

### POTM {#POTM}
```
public static final FileType POTM
```


Stelt een PowerPoint Open XML-macro-ingeschakelde presentatiesjabloon (.potm) voor, Microsoft PowerPoint-sjabloonbestanden met ondersteuning voor macro's. POTM-bestanden worden gemaakt met PowerPoint 2007 of hoger en bevatten standaardinstellingen die kunnen worden gebruikt om verdere presentatiebestanden te maken. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/presentation/potm

### PPSM {#PPSM}
```
public static final FileType PPSM
```


Stelt een PowerPoint Open XML-macro-ingeschakelde dia (.ppsm) voor, een macro-ingeschakeld diavoorstellingsbestand gemaakt met Microsoft PowerPoint 2007 of hoger. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/presentation/ppsm

### OTP {#OTP}
```
public static final FileType OTP
```


Stelt een OpenDocument-presentatiesjabloon (.otp) voor, presentatie-sjabloonbestanden die zijn gemaakt door toepassingen volgens het OASIS OpenDocument-standaardformaat. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


Stelt een Excel-werkblad (.xls) voor, het Excel-binaire bestandsformaat. Dergelijke bestanden kunnen worden gemaakt met Microsoft Excel evenals andere vergelijkbare spreadsheetprogramma's zoals OpenOffice Calc of Apple Numbers. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### EXCEL_2003_XML {#EXCEL-2003-XML}
```
public static final FileType EXCEL_2003_XML
```


Stelt een Excel 2003 XML (SpreadsheetML) (.xml) voor, dat het Excel-binaire bestandsformaat vertegenwoordigt. Dergelijke bestanden kunnen worden gemaakt met Microsoft Excel evenals andere vergelijkbare spreadsheetprogramma's zoals OpenOffice Calc of Apple Numbers. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### NUMBERS {#NUMBERS}
```
public static final FileType NUMBERS
```


Geeft Apple Numbers (.numbers) weer, wat een Excel-achtig binair bestandsformaat is. Dergelijke bestanden kunnen worden aangemaakt met de Apple Numbers-toepassing. Meer informatie over dit bestandsformaat [here][].


[here]: https://fileinfo.com/extension/numbers

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Geeft een Microsoft Excel Open XML-spreadsheet (.xlsx) weer, een bekend formaat voor Microsoft Excel-documenten dat door Microsoft werd geïntroduceerd met de release van Microsoft Office 2007. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Geeft een Excel Open XML-macro-ondersteunde spreadsheet (.xlsm) weer, een type spreadsheetbestand dat macro's ondersteunt. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Geeft een Excel Binary-spreadsheet (.xlsb) weer, die het Excel Binary-bestandsformaat specificeert. Het is een verzameling records en structuren die de inhoud van een Excel-werkmap definiëren. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


Geeft een Comma Separated Values-bestand (.csv) weer, dat platte-tekstbestanden zijn met gegevensrecords gescheiden door komma's. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


Geeft een Tab Separated Values-bestand (.tsv) weer, dat gegevens bevat die met tabs gescheiden zijn in een platte-tekstformaat. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


Geeft een OpenDocument-spreadsheet (.ods) weer, wat staat voor het OpenDocument Spreadsheet Document-formaat dat door de gebruiker bewerkbaar is. Gegevens worden opgeslagen in ODF-bestanden in rijen en kolommen. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ods

### FODS {#FODS}
```
public static final FileType FODS
```


Geeft een OpenDocument Flat XML-spreadsheet (.fods) weer. Het is een spreadsheetdocumentformaat gebaseerd op XML dat wordt gebruikt door OpenOffice en LibreOffice. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/fods

### OTS {#OTS}
```
public static final FileType OTS
```


Geeft een OpenDocument Spreadsheet-sjabloon (.ots) weer. Het is een sjabloondocumentformaat dat door OpenOffice en LibreOffice voor spreadsheets wordt gebruikt. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ots

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Geeft een Microsoft Excel-add-in (.xlam) weer. Het is een bestandsformaat dat door Microsoft Excel wordt gebruikt om add-ins met aangepaste functionaliteit te maken. Meer informatie over dit bestandsformaat [here][].


[here]: https://fileinfo.com/extension/xlam

### XLTM {#XLTM}
```
public static final FileType XLTM
```


Geeft een Microsoft Excel macro-ondersteunde sjabloon (.xltm) weer, dat bestanden vertegenwoordigt die door Microsoft Excel worden gegenereerd als macro-ondersteunde sjabloonbestanden. XLTM-bestanden lijken qua structuur op XLTX, behalve dat laatstgenoemde geen sjabloonbestanden met macro's ondersteunt. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltm

### XLT {#XLT}
```
public static final FileType XLT
```


Geeft een Microsoft Excel-sjabloon (.xlt) weer, dit zijn sjabloonbestanden die met Microsoft Excel zijn gemaakt, een spreadsheettoepassing die deel uitmaakt van de Microsoft Office-suite. Microsoft Office 97-2003 ondersteunde het maken van nieuwe XLT-bestanden en het openen ervan. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlt

### XLTX {#XLTX}
```
public static final FileType XLTX
```


Geeft een Excel Open XML-spreadsheet-sjabloon (.xltx) weer, dat Microsoft Excel-sjablonen vertegenwoordigt op basis van de Office OpenXML-bestandsformaatspecificaties. Het wordt gebruikt om een standaard sjabloonbestand te maken dat kan worden gebruikt om XLSX-bestanden te genereren met dezelfde instellingen als gespecificeerd in het XLTX-bestand. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltx

### SXC {#SXC}
```
public static final FileType SXC
```


Geeft een StarOffice Calc-spreadsheet (.sxc) weer. Het is een spreadsheetdocument dat is gemaakt met StarOffice Calc, een spreadsheetprogramma. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/spreadsheet/sxc

### MPP {#MPP}
```
public static final FileType MPP
```


Geeft een Microsoft Project-bestand (.mpp) weer, een Microsoft Project-gegevensbestand dat informatie over projectbeheer op een geïntegreerde manier opslaat. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/project-management/mpp

### MPT {#MPT}
```
public static final FileType MPT
```


Geeft een Microsoft Project-sjabloon (.mpt) weer, dat basisinformatie en -structuur bevat, samen met documentinstellingen voor het maken van .MPP-bestanden. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/project-management/mpt

### MPX {#MPX}
```
public static final FileType MPX
```


Geeft een Microsoft Project Exchange-bestand (.mpx) weer, een ASCII-bestandsformaat voor het overbrengen van projectinformatie tussen Microsoft Project (MSP) en andere toepassingen die het MPX-bestandsformaat ondersteunen, zoals Primavera Project Planner, Sciforma en Timerline Precision Estimating. Meer informatie over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/project-management/mpx

### AS {#AS}
```
public static final FileType AS
```


Geeft een ActionScript-bestand (.as) weer. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/programming/as

### AS_3 {#AS-3}
```
public static final FileType AS_3
```


Geeft een ActionScript-bestand (.as3) weer. Meer informatie over dit bestandsformaat [here][].


[here]: https://datatypes.net/open-as3-files

### ASM {#ASM}
```
public static final FileType ASM
```


Stelt een Assembly Language broncodebestand (.asm) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/cad/asm

### BAT {#BAT}
```
public static final FileType BAT
```


Stelt een DOS-batchbestand (.bat) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/executable/bat

### C {#C}
```
public static final FileType C
```


Stelt een C/C++ broncodebestand (.c) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/programming/c

### CC {#CC}
```
public static final FileType CC
```


Stelt een C++ broncodebestand (.cc) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/programming/cc

### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Stelt een CMake-bestand (.cmake) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/programming/cmake

### CPP {#CPP}
```
public static final FileType CPP
```


Stelt een C++ broncodebestand (.cpp) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/programming/cpp

### CS {#CS}
```
public static final FileType CS
```


Stelt een C\# broncodebestand (.cs) voor, dat een broncodebestand is voor de C\# programmeertaal. Het werd geïntroduceerd door Microsoft voor gebruik met het .NET Framework. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/programming/cs

### VB {#VB}
```
public static final FileType VB
```


Stelt een Visual Basic-projectitembestand (.vb) voor, dat een broncodebestand is dat is gemaakt in de Visual Basic-taal. Het werd gemaakt door Microsoft voor de ontwikkeling van .NET-toepassingen. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/programming/vb

### CSS {#CSS}
```
public static final FileType CSS
```


Stelt een Cascading Style Sheet (.css) bestand voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/web/css

### CXX {#CXX}
```
public static final FileType CXX
```


Stelt een C++ broncodebestand (.cxx) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/programming/cxx

### DIFF {#DIFF}
```
public static final FileType DIFF
```


Stelt een patchbestand (.diff) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/programming/diff

### ERB {#ERB}
```
public static final FileType ERB
```


Stelt een Ruby ERB-script (.erb) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/programming/erb

### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Stelt een Groovy broncodebestand (.groovy) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/programming/groovy

### H {#H}
```
public static final FileType H
```


Stelt een C/C++/Objective-C headerbestand (.h) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/programming/h

### HAML {#HAML}
```
public static final FileType HAML
```


Stelt een Haml broncodebestand (.haml) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/programming/haml

### HH {#HH}
```
public static final FileType HH
```


Stelt een C++ headerbestand (.hh) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/programming/hh

### JAVA {#JAVA}
```
public static final FileType JAVA
```


Stelt een Java broncodebestand (.java) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/programming/java

### JS {#JS}
```
public static final FileType JS
```


Stelt een JavaScript-bestand (.js) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/web/js

### JSON {#JSON}
```
public static final FileType JSON
```


Stelt een JavaScript Object Notation-bestand (.json) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/web/json

### LESS {#LESS}
```
public static final FileType LESS
```


Stelt een LESS-stylesheet (.less) bestand voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/web/less

### LOG {#LOG}
```
public static final FileType LOG
```


Stelt een logbestand (.log) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/database/log

### M {#M}
```
public static final FileType M
```


Stelt een Objective-C-implementatiebestand (.m) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://fileinfo.com/extension/m

### MAKE {#MAKE}
```
public static final FileType MAKE
```


Stelt een Xcode Makefile-script (.make) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/programming/make

### MD {#MD}
```
public static final FileType MD
```


Stelt een Markdown-documentatiebestand (.md) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/word-processing/md

### ML {#ML}
```
public static final FileType ML
```


Stelt een ML broncodebestand (.ml) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/programming/ml

### MM {#MM}
```
public static final FileType MM
```


Stelt een Objective-C++ bronbestand (.mm) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/programming/mm

### PHP {#PHP}
```
public static final FileType PHP
```


Stelt een PHP broncodebestand (.php) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/programming/php

### PL {#PL}
```
public static final FileType PL
```


Stelt een Perl‑script (.pl) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/programming/pl

### PROPERTIES {#PROPERTIES}
```
public static final FileType PROPERTIES
```


Stelt een Java‑eigenschappenbestand (.properties) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://fileinfo.com/extension/properties

### PY {#PY}
```
public static final FileType PY
```


Stelt een Python‑script (.py) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/programming/py

### RB {#RB}
```
public static final FileType RB
```


Stelt een Ruby‑broncodebestand (.rb) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/programming/rb

### RST {#RST}
```
public static final FileType RST
```


Stelt een reStructuredText‑bestand (.rst) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/programming/rst

### SASS {#SASS}
```
public static final FileType SASS
```


Stelt een Syntactically Awesome StyleSheets‑bestand (.sass) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/web/sass

### SCALA {#SCALA}
```
public static final FileType SCALA
```


Stelt een Scala‑broncodebestand (.scala) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/programming/scala

### SCM {#SCM}
```
public static final FileType SCM
```


Stelt een Scheme‑broncodebestand (.scm) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/programming/scm

### SCRIPT {#SCRIPT}
```
public static final FileType SCRIPT
```


Stelt een Algemeen script‑bestand (.script) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/programming/script

### SH {#SH}
```
public static final FileType SH
```


Stelt een Bash‑shellscript (.sh) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/cs/programming/sh

### SML {#SML}
```
public static final FileType SML
```


Stelt een Standard ML‑broncodebestand (.sml) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://fileinfo.com/extension/sml

### SQL {#SQL}
```
public static final FileType SQL
```


Stelt een Structured Query Language‑databestand (.sql) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/database/sql

### VIM {#VIM}
```
public static final FileType VIM
```


Stelt een Vim‑instellingenbestand (.vim) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://fileinfo.com/extension/vim

### YAML {#YAML}
```
public static final FileType YAML
```


Stelt een YAML‑document (.yaml) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/programming/yaml

### DOC {#DOC}
```
public static final FileType DOC
```


Stelt een Microsoft Word‑document (.doc) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Stelt een Microsoft Word Open XML‑document (.docx) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/word-processing/docx

### CHM {#CHM}
```
public static final FileType CHM
```


Stelt een Microsoft Compiled HTML‑helpbestand (.chm) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/web/chm

### DOCM {#DOCM}
```
public static final FileType DOCM
```


Stelt een Word Open XML‑macro‑ingeschakeld document (.docm) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


Stelt een Word‑documentsjabloon (.dot) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Stelt een Word Open XML‑documentsjabloon (.dotx) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Stelt een Word Open XML‑macro‑ingeschakeld documentsjabloon (.dotm) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


Stelt een Rich Text Format‑bestand (.rtf) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


Stelt een Platte‑tekstbestand (.txt) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/word-processing/txt

### ODT {#ODT}
```
public static final FileType ODT
```


Stelt een OpenDocument-tekstdocument (.odt) voor. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


Stelt een OpenDocument-sjabloondocument (.ott) voor. Het is een sjabloondocument dat is gegenereerd in overeenstemming met de OpenDocument-standaard van OASIS. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/word-processing/ott

### VCF {#VCF}
```
public static final FileType VCF
```


Stelt een vCard‑bestand (.vcf) voor, een digitaal bestandsformaat voor het opslaan van contactinformatie. Het wordt veel gebruikt voor gegevensuitwisseling tussen populaire uitwisselingsapplicaties. Meer informatie over dit bestandsformaat [hier][].


[here]: https://wiki.fileformat.com/email/vcf

### AI {#AI}
```
public static final FileType AI
```


Stelt een Adobe Illustrator‑bestand (.ai) voor, een bestandsformaat voor Adobe Illustrator‑tekeningen. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/image/ai

### PSM1 {#PSM1}
```
public static final FileType PSM1
```


Stelt een PowerShell‑scriptmodule‑bestand (.psm1) voor. Het is een bestandsformaat voor PowerShell‑modulescripts. Meer informatie over dit bestandsformaat [hier][].


[here]: https://fileinfo.com/extension/psm1

### PS1 {#PS1}
```
public static final FileType PS1
```


Stelt een PowerShell‑scriptbestand (.ps1) voor. Het is een bestandsformaat voor Windows PowerShell‑cmdlet‑bestanden. Meer informatie over dit bestandsformaat [hier][].


[here]: https://fileinfo.com/extension/ps1

### PSD1 {#PSD1}
```
public static final FileType PSD1
```


Stelt een PowerShell‑scriptmodule‑manifestbestand (.psd1) voor. Het is een bestandsformaat voor PowerShell‑module‑manifestscripts. Meer informatie over dit bestandsformaat [hier][].


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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


Koppelt een bestandsextensie aan een bestandstype.

Deze methode neemt een bestandsextensie, met of zonder de punt ".", en retourneert het overeenkomstige bestandstype als het wordt ondersteund. Als het bestandstype niet wordt ondersteund, retourneert het het standaard [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) bestandstype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| extension | java.lang.String | De bestandsextensie met of zonder de punt ".". |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromFilePath(String filePath) {#fromFilePath-java.lang.String-}
```
public static FileType fromFilePath(String filePath)
```


Haalt de bestandsextensie uit een bestandsnaam of bestandspad en koppelt deze aan een bestandstype.

Als het bestandstype wordt ondersteund, retourneert de methode het overeenkomstige  FileType , anders retourneert het het standaard [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) bestandstype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | De bestandsnaam of het bestandspad. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromMediaType(String mediaType) {#fromMediaType-java.lang.String-}
```
public static FileType fromMediaType(String mediaType)
```


Koppelt een mediatype van een bestand aan een bestandstype. Bijvoorbeeld, 'application/pdf' wordt gekoppeld aan [PDF](../../com.groupdocs.viewer/filetype\#PDF).

Deze methode neemt een mediatype van een bestand als invoer en koppelt het aan het overeenkomstige  FileType . Als het mediatype wordt ondersteund, retourneert de methode het overeenkomstige bestandstype. Als het mediatype niet wordt ondersteund, retourneert het het standaard [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) bestandstype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mediaType | java.lang.String | Het mediatype van het bestand, bijv. 'application/pdf'. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if found, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream stream)
```


Detecteert het bestandstype door de bestandssignatuur te lezen.

Deze methode neemt een invoerstroom die een bestand vertegenwoordigt en probeert het bestandstype te detecteren door de bestandssignatuur te analyseren. De bestandssignatuur is een unieke reeks bytes aan het begin van het bestand die het bestandstype aangeeft. De methode leest de bestandssignatuur uit de invoerstroom en vergelijkt deze met bekende bestandssignaturen van ondersteunde bestandstypen. Als er een overeenkomst wordt gevonden, retourneert de methode het overeenkomstige bestandstype. Als er geen overeenkomst wordt gevonden, retourneert het het standaard [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) bestandstype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De invoerstroom die het bestand vertegenwoordigt. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password) {#fromStream-java.io.InputStream-java.lang.String-}
```
public static FileType fromStream(InputStream stream, String password)
```


Detecteert het bestandstype door de bestandssignatuur te lezen.

Deze methode analyseert de bestandssignatuur, een unieke reeks bytes aan het begin van het bestand, om het bestandstype te bepalen. Ze leest de bestandssignatuur uit de opgegeven invoerstroom en vergelijkt deze met bekende bestandssignaturen van ondersteunde bestandstypen. Als er een overeenkomst wordt gevonden, retourneert de methode het overeenkomstige bestandstype. Als er geen overeenkomst wordt gevonden, retourneert ze het standaard [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) bestandstype.

Als het bestand versleuteld is en een wachtwoord vereist om te openen, moet het wachtwoord als parameter aan deze methode worden doorgegeven. Het wachtwoord wordt gebruikt om het bestand te ontsleutelen en de signatuur te analyseren om het bestandstype te bepalen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De invoerstroom die het bestand vertegenwoordigt. |
| password | java.lang.String | Het wachtwoord om het bestand te openen. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, ILogger logger) {#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, ILogger logger)
```


Detecteert het bestandstype door de bestandssignatuur te lezen.

Deze methode analyseert de bestandssignatuur, een unieke reeks bytes aan het begin van het bestand, om het bestandstype te bepalen. Ze leest de bestandssignatuur uit de opgegeven invoerstroom en vergelijkt deze met bekende bestandssignaturen van ondersteunde bestandstypen. Als er een overeenkomst wordt gevonden, retourneert de methode het overeenkomstige bestandstype. Als er geen overeenkomst wordt gevonden, retourneert ze het standaard [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) bestandstype.

Er kan een logger worden opgegeven om relevante informatie of fouten tijdens het detectieproces van het bestandstype te loggen. De logger moet de ILogger‑interface implementeren. Als er geen logger wordt opgegeven, zal het detectieproces geen logoutput produceren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De invoerstroom die het bestand vertegenwoordigt. |
| logger | com.groupdocs.foundation.logging.ILogger | De logger voor het loggen van informatie of fouten. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password, ILogger logger) {#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, String password, ILogger logger)
```


Detecteert het bestandstype door de bestandssignatuur te lezen.

Deze methode analyseert de bestandssignatuur, een unieke reeks bytes aan het begin van het bestand, om het bestandstype te bepalen. Ze leest de bestandssignatuur uit de opgegeven invoerstroom en vergelijkt deze met bekende bestandssignaturen van ondersteunde bestandstypen. Als er een overeenkomst wordt gevonden, retourneert de methode het overeenkomstige bestandstype. Als er geen overeenkomst wordt gevonden, retourneert ze het standaard [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) bestandstype.

Een wachtwoord kan worden opgegeven als het bestand versleuteld of beschermd is. Het wachtwoord wordt gebruikt om het bestand te openen voordat de bestandssignatuur wordt geanalyseerd. Als het bestand geen wachtwoord vereist, kan deze parameter op null worden gezet.

Er kan een logger worden opgegeven om relevante informatie of fouten tijdens het detectieproces van het bestandstype te loggen. De logger moet de ILogger‑interface implementeren. Als er geen logger wordt opgegeven, zal het detectieproces geen logoutput produceren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De invoerstroom die het bestand vertegenwoordigt. |
| password | java.lang.String | Het wachtwoord om het bestand te openen. |
| logger | com.groupdocs.foundation.logging.ILogger | De logger voor het loggen van informatie of fouten. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Haalt de ondersteunde bestandstypen op.

Deze methode retourneert een reeks van alle door het systeem ondersteunde bestandstypen. De bestandstypen vertegenwoordigen verschillende documentformaten die door het systeem kunnen worden verwerkt of herkend.

 **Learn more**

 *  Learn more about the supported document formats: [Full list of supported file formats][]


[Full list of supported file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/

**Returns:**
java.util.List<com.groupdocs.viewer.FileType> - een reeks van ondersteunde bestandstypen.
### detectCharset(String filePath) {#detectCharset-java.lang.String-}
```
public static Charset detectCharset(String filePath)
```


Probeert de tekenset van tekstbestanden [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) en [CSV](../../com.groupdocs.viewer/filetype\#CSV) te detecteren op basis van het pad.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | De bestandsnaam of het bestandspad. |

**Returns:**
java.nio.charset.Charset - Charset of null wanneer het niet lukt een bestandscodering te detecteren.

**Example:**

```
Charset charset = FileType.detectCharset("message.txt");
```
### detectCharset(InputStream stream) {#detectCharset-java.io.InputStream-}
```
public static Charset detectCharset(InputStream stream)
```


Probeert de tekenset van tekstbestanden [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) en [CSV](../../com.groupdocs.viewer/filetype\#CSV) te detecteren op basis van de stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | De bestandsstroom. |

**Returns:**
java.nio.charset.Charset - Charset of null wanneer het niet lukt een bestandscodering te detecteren.

**Example:**

```
InputStream stream = new FileInputStream("message.txt");
 Charset charset = FileType.detectCharset(stream);
```
### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Haalt de naam van het bestandsformaat op, bijv. "Microsoft Word Document".

**Returns:**
java.lang.String - de naam van het bestandsformaat.
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Haalt het bestandsextensie-achtervoegsel op (inclusief de punt "."), bijv. ".doc".

**Returns:**
java.lang.String - het bestandsextensie‑achtervoegsel.
### toString() {#toString--}
```
public String toString()
```


Retourneert een tekenreeksrepresentatie van het huidige object.

**Returns:**
java.lang.String - een tekenreeksrepresentatie van het huidige object.
