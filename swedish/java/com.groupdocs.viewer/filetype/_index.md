---
title: "FileType"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Representerar filtypen."
type: docs
weight: 14
url: /sv/java/com.groupdocs.viewer/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, com.groupdocs.viewer.caching.Cacheable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>, Cacheable
```

Representerar filtypen. Tillhandahåller metoder för att hämta en lista över alla filtyper som stöds av GroupDocs.Viewer-komponenten.


FileType‑enumet tillhandahåller konstanter som representerar olika filtyper som stöds av GroupDocs.Viewer-komponenten.
Du kan använda metoderna i detta enum för att hämta en lista över alla stödda filtyper eller kontrollera om en specifik filtyp stöds.


Exempel på användning:

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


## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | Representerar en okänd filtyp. |
|
|  | [ZIP](#ZIP) | Representerar en zip‑fil (.zip) som kan innehålla en eller flera filer eller kataloger. |
|
|  | [TAR](#TAR) | Representerar ett samlat Unix‑arkiv (.tar) som skapats för att samla en eller flera filer. |
|
|  | [XZ](#XZ) | Representerar en XZ‑fil (.xz) komprimerad med en högkomprimeringsalgoritm baserad på LZMA‑algoritmen. |
|
|  | [TXZ](#TXZ) | Representerar ett konsoliderat Unix-filarkiv (.txz, .tar.xz) skapat för att samla en eller flera filer. |
|
|  | [TARXZ](#TARXZ) | Representerar ett konsoliderat Unix-filarkiv (.txz, .tar.xz) skapat för att samla en eller flera filer. |
|
|  | [TGZ](#TGZ) | Representerar ett konsoliderat Unix-filarkiv (.tgz, .tar.gz) skapat för att samla en eller flera filer. |
|
|  | [TARGZ](#TARGZ) | Representerar ett konsoliderat Unix-filarkiv (.tgz, .tar.gz) skapat för att samla en eller flera filer. |
|
|  | [BZ_2](#BZ-2) | Representerar en Bzip2-komprimerad fil (.bz2) som genererats med BZIP2‑metoden för öppen källkod. |
|
|  | [RAR](#RAR) | Representerar en Roshal Archive (.rar) komprimerad fil som genererats med RAR‑metoden (WINRAR version 4). |
|
|  | [GZ](#GZ) | Representerar en Gnu Zipped File (.gz) komprimerad fil skapad med gzip‑komprimeringsprogrammet. |
|
|  | [GZIP](#GZIP) | Representerar en Gnu Zipped File (.gzip) komprimerad fil som introducerades som ett gratisverktyg för att ersätta Compress‑programmet som används i Unix‑system. |
|
|  | [SEVEN_ZIP](#SEVEN-ZIP) | Representerar en 7Zip (.7z, .7zip)-fil, som är en gratis öppen källkod‑arkiverare med LZMA‑ och LZMA2‑komprimering. |
|
|  | [CPIO](#CPIO) | Cpio är ett allmänt filarkiveringsverktyg och dess tillhörande filformat. |
|
|  | [ZSTANDARD](#ZSTANDARD) | ZST‑fil är en komprimerad fil som genereras med Zstandard‑algoritmen (zstd). |
|
|  | [TZST](#TZST) | TZST‑filer (.tar.zst, .tzst) är Zstandard‑arkiv (ZST) som internt innehåller ett konsoliderat Unix-filarkiv (Tar), skapat med ett Unix‑baserat verktyg för att samla en eller flera filer. |
|
|  | [TAR_ZST](#TAR-ZST) | TZST‑filer (.tar.zst, .tzst) är Zstandard‑arkiv (ZST) som internt innehåller ett konsoliderat Unix-filarkiv (Tar), skapat med ett Unix‑baserat verktyg för att samla en eller flera filer. |
|
|  | [ISO](#ISO) | ISO‑optisk skivavbild är en okomprimerad arkiv‑diskavbildningsfil som representerar innehållet i hela data på en optisk skiva såsom CD eller DVD, baserad på ISO‑9660‑standarden. |
|
|  | [LHA](#LHA) | LHA eller LZH är ett gratis komprimeringsverktyg och tillhörande filformat. |
|
|  | [CAB](#CAB) | Cabinet (eller CAB) är ett arkivfilformat för Microsoft Windows. |
|
|  | [DXF](#DXF) | Representerar en Drawing Exchange Format‑fil (.dxf), som är en taggad datarapresentation av en AutoCAD‑ritningsfil. |
|
|  | [DWG](#DWG) | Representerar en AutoCAD Drawing Database‑fil (.dwg), som representerar proprietära binära filer som används för att innehålla 2D‑ och 3D‑designdata. |
|
|  | [DWT](#DWT) | Representerar en AutoCAD Drawing Template (.dwt), som är en AutoCAD‑ritningsmallfil som används som utgångspunkt för att skapa ritningar som kan sparas som DWG‑filer. |
|
|  | [STL](#STL) | Representerar en Stereolithography‑fil (.stl), som är ett utbytbart filformat som representerar tredimensionell ytgometri. |
|
|  | [IFC](#IFC) | Representerar en Industry Foundation Classes‑fil (.ifc), som är ett filformat som fastställer internationella standarder för import och export av byggnadsobjekt och deras egenskaper. |
|
|  | [DWF](#DWF) | Representerar en Design Web Format‑fil (.dwf), som är ett komprimerat filformat för visning, granskning eller utskrift av 2D/3D‑ritningar. |
|
|  | [FBX](#FBX) | Representerar en Autodesk FBX Interchange‑fil (FilmBoX) (.fbx), som är ett 3D‑modellformat. |
|
|  | [DWFX](#DWFX) | Representerar en Design Web Format‑fil XPS (.dwfx), som är ett komprimerat format för visning, granskning eller utskrift av 2D/3D‑ritningar som ett XPS‑dokument. |
|
|  | [DGN](#DGN) | Representerar en MicroStation Design‑fil (.dgn), som är ritningar skapade och stödda av CAD‑program som MicroStation och Intergraph Interactive Graphics Design System. |
|
|  | [PLT](#PLT) | Representerar en PLT (HPGL)-fil (.plt), som är en vektorbaserad plotterfil introducerad av Autodesk, Inc. |
|
|  | [CF2](#CF2) | Representerar en Common File Format‑fil (.cf2). |
|
|  | [OBJ](#OBJ) | Representerar en Wavefront 3D Object‑fil (.obj), som är en 3D‑bildfil introducerad av Wavefront Technologies. |
|
|  | [HPG](#HPG) | Representerar en PLT (HPGL)-fil (.hpg). |
|
|  | [IGS](#IGS) | Representerar en Initial Graphics Exchange Specification (IGES)-fil (.igs). |
|
|  | [VSD](#VSD) | Representerar en Visio-ritningsfil (.vsd), som är ritningar skapade med Microsoft Visio‑applikationen för att representera en mängd grafiska objekt och deras samband. |
|
|  | [VSDX](#VSDX) | Representerar en Visio-ritningsfil (.vsdx), som representerar Microsoft Visio‑filformatet som introducerades från Microsoft Office 2013 och framåt. |
|
|  | [VSS](#VSS) | Representerar en Visio‑stencil‑fil (.vss), som är stencil‑filer skapade med Microsoft Visio 2007 och tidigare. |
|
|  | [VSSX](#VSSX) | Representerar en Visio‑stencil‑fil (.vssx), som är ritningsstencil‑filer skapade med Microsoft Visio 2013 och senare. |
|
|  | [VSDM](#VSDM) | Representerar en Visio‑makroaktiverad ritningsfil (.vsdm), som är ritningsfiler skapade med Microsoft Visio‑applikationen som stödjer makron. |
|
|  | [VST](#VST) | Representerar en Visio‑ritningsmall (.vst), som är vektorbildfiler skapade med Microsoft Visio. |
|
|  | [VSTX](#VSTX) | Representerar en Visio‑ritningsmall (.vstx), som är ritningsmallfiler skapade med Microsoft Visio 2013 och senare. |
|
|  | [VSTM](#VSTM) | Representerar en Visio‑makroaktiverad ritningsmall (.vstm), som är mallfiler skapade med Microsoft Visio som stödjer makron. |
|
|  | [VSSM](#VSSM) | Representerar en Visio‑makroaktiverad stencil‑fil (.vssm), som är Microsoft Visio‑stencil‑filer som stödjer makron. |
|
|  | [VSX](#VSX) | Representerar en Visio‑stencil‑XML‑fil (.vsx), som avser stencil‑filer bestående av ritningar och former som används för att skapa diagram i Microsoft Visio. |
|
|  | [VTX](#VTX) | Representerar en Visio‑mall‑XML‑fil (.vtx), som är en Microsoft Visio‑ritningsmall sparad på disk i XML‑filformat. |
|
|  | [VDW](#VDW) | Representerar en Visio‑webbritning (.vdw), som specificerar de strömmar och lagringar som krävs för att rendera en webbritning. |
|
|  | [VDX](#VDX) | Representerar en Visio‑ritnings‑XML‑fil (.vdx), som representerar alla ritningar eller diagram skapade i Microsoft Visio men sparade i XML‑format med .VDX‑ändelsen. |
|
|  | [EPUB](#EPUB) | Representerar en Open eBook‑fil (.epub), som är ett e‑bokfilformat som tillhandahåller ett standardiserat digitalt publiceringsformat för utgivare och konsumenter. |
|
|  | [MOBI](#MOBI) | Representerar en Mobipocket‑eBook (.mobi), som är ett av de mest använda e‑bokfilformaten. |
|
|  | [AZW_3](#AZW-3) | Amazon Kindle Format 8 (KF8)‑eBook är det digitala filformat som utvecklats för Amazon Kindle‑enheter. |
|
|  | [MSG](#MSG) | Representerar ett Outlook‑e‑postmeddelande (.msg), som är ett filformat som används av Microsoft Outlook och Exchange för att lagra e‑postmeddelanden, kontakter, möten eller andra uppgifter. |
|
|  | [EML](#EML) | Representerar ett e‑postmeddelande (.eml), som representerar e‑postmeddelanden sparade med Outlook och andra relevanta program. |
|
|  | [EMLX](#EMLX) | Representerar ett Apple‑e‑postmeddelande (.emlx), som är implementerat och utvecklat av Apple. |
|
|  | [PST](#PST) | Representerar en Outlook‑Personal Information Store‑fil (.pst), som representerar Outlook Personal Storage Files (även kallade Personal Storage Table) som lagrar en mängd användarinformation. |
|
|  | [OST](#OST) | Representerar en Outlook‑Offline‑datafil (.ost), som representerar en användares brevlådedata i offlineläge på en lokal maskin efter registrering mot Exchange Server med Microsoft Outlook. |
|
|  | [TIF](#TIF) | Representerar en Tagged Image File (.tif), som representerar rasterbilder avsedda för användning på en mängd enheter som följer denna filformatstandard. |
|
|  | [TIFF](#TIFF) | Representerar ett Tagged Image File Format (.tiff), som representerar rasterbilder som är avsedda för användning på en mängd olika enheter som följer denna filformatstandard. |
|
|  | [JPG](#JPG) | Representerar en JPEG-bild (.jpg), som är en typ av bildformat som sparas med förlustkomprimering. |
|
|  | [JPEG](#JPEG) | Representerar en JPEG-bild (.jpeg), som är en typ av bildformat som sparas med förlustkomprimering. |
|
|  | [JFIF](#JFIF) | JPEG File Interchange Format (.jfif) är en bild som utvecklades för snabb utbyte mellan plattformar. |
|
|  | [PNG](#PNG) | Representerar ett Portable Network Graphic (.png), som är en typ av rasterbildfilformat som använder förlustfri komprimering. |
|
|  | [GIF](#GIF) | Representerar en Graphical Interchange Format-fil (.gif), som är en typ av starkt komprimerad bild. |
|
|  | [APNG](#APNG) | Representerar en Animated Portable Network Graphic (.apng), som är en utökning av PNG-formatet som stödjer animation. |
|
|  | [BMP](#BMP) | Representerar en Bitmap Image File (.bmp), som används för att lagra bitmapdigitala bilder. |
|
|  | [ICO](#ICO) | Representerar en Icon File (.ico), som är en bildfilstyp som används som ikon för att representera ett program på Microsoft Windows. |
|
|  | [TGA](#TGA) | Representerar en Truevision TGA (TARGA)-fil, som används för att lagra bitmapdigitala bilder utvecklade av TRUEVISION. |
|
|  | [JP_2](#JP-2) | Representerar en JPEG 2000 Core Image File (.jp2), som är ett bildkodningssystem och en toppmodern bildkomprimeringsstandard. |
|
|  | [JPF](#JPF) | Representerar en JPEG 2000 Image File (.jpf). |
|
|  | [JPX](#JPX) | Representerar en JPEG 2000 Image File (.jpx). |
|
|  | [JPM](#JPM) | Representerar en JPEG 2000 Image File (.jpm). |
|
|  | [J2C](#J2C) | Representerar en JPEG 2000 Code InputStream (.j2c). |
|
|  | [J2K](#J2K) | Representerar en JPEG 2000 Code Stream (.j2k), som är en bild komprimerad med wavelet-komprimering istället för DCT-komprimering. |
|
|  | [JPC](#JPC) | Representerar en JPEG 2000 Code Stream (.jpc). |
|
|  | [JLS](#JLS) | Representerar en JPEG-LS (JLS)-fil (.jls). |
|
|  | [DIB](#DIB) | Representerar en Device Independent Bitmap File (.dib). |
|
|  | [WMF](#WMF) | Representerar en Windows Metafile (.wmf), som representerar Microsoft Windows Metafile (WMF) för lagring av både vektor- och bitmapformatbilddata. |
|
|  | [WMZ](#WMZ) | Representerar en Compressed Windows Metafile (.wmz), som representerar Microsoft Windows Metafile (WMF) komprimerad i ett GZIP-arkiv för lagring av både vektor- och bitmapformatbilddata. |
|
|  | [EMF](#EMF) | Representerar en Enhanced Windows Metafile (.emf), som representerar grafiska bilder enhetsoberoende. |
|
|  | [EMZ](#EMZ) | Representerar en Windows Compressed Enhanced Metafile (.emz), som representerar grafiska bilder enhetsoberoende komprimerade med GZIP. |
|
|  | [WEBP](#WEBP) | Representerar en WebP Image (.webp), som är ett modernt rasterwebbbildfilformat baserat på förlustfri och förlustkomprimering. |
|
|  | [DNG](#DNG) | Representerar en Digital Negative Specification (.dng), som är ett digitalt kamerabildformat som används för lagring av råfiler. |
|
|  | [CDR](#CDR) | Representerar en CorelDraw vektorgrafikritning (.cdr), som är en vektorritningsbildfil som ursprungligen skapats med CorelDRAW för att lagra digitalt kodade och komprimerade bilder. |
|
|  | [CMX](#CMX) | Representerar en Corel Exchange (.cmx), som är en ritningsbildfil som kan innehålla vektorgrafik såväl som bitmapgrafik. |
|
|  | [DJVU](#DJVU) | Representerar en DjVu-bild (.djvu), som är ett grafikfilformat avsett för skannade dokument och böcker, särskilt de som innehåller en kombination av text, teckningar, bilder och fotografier. |
|
|  | [CGM](#CGM) | Representerar en Computer Graphics Metafile (.cgm), som är ett fritt, plattformsoberoende, internationellt standardmetafilformat för lagring och utbyte av vektorgrafik (2D), rastergrafik och text. |
|
|  | [PCL](#PCL) | Representerar ett Printer Command Language-dokument (.pcl). |
|
|  | [PSD](#PSD) | Representerar ett Adobe Photoshop-dokument (.psd), som är Adobe Photoshops inhemska filformat som används för grafisk design och utveckling. |
|
|  | [PSB](#PSB) | Representerar ett Photoshop Large Document Format (.psb), som används för grafisk design och utveckling i Adobe Photoshop. |
|
|  | [DCM](#DCM) | Representerar en DICOM-bild (.dcm), som representerar en digital bild som lagrar medicinsk information om patienter såsom MR, CT-skanningar och ultraljudsbilder. |
|
|  | [PS](#PS) | Representerar en PostScript-fil (.ps). |
|
|  | [EPS](#EPS) | Representerar en Encapsulated PostScript-fil (.eps), som beskriver ett Encapsulated PostScript-språkprogram som definierar utseendet på en enda sida. |
|
|  | [ODG](#ODG) | Representerar en OpenDocument Graphic-fil (.odg), som används av Apache OpenOffice Draw-applikationen för att lagra ritningselement som en vektorbild. |
|
|  | [FODG](#FODG) | Representerar en Flat XML ODF-mall (.fodg), som används av Apache OpenOffice Draw-applikationen för att lagra ritningselement som en vektorbild. |
|
|  | [SVG](#SVG) | Representerar en Scalable Vector Graphics-fil (.svg), som är en Scalable Vector Graphics-fil som använder ett XML-baserat textformat för att beskriva en bilds utseende. |
|
|  | [SVGZ](#SVGZ) | Representerar en Compressed Scalable Vector Graphics-fil (.svgz), som är en Scalar Vector Graphics-fil som använder ett XML-baserat textformat, komprimerat med GZIP, för att beskriva en bilds utseende. |
|
|  | [OTG](#OTG) | Representerar en OpenDocument Graphic-mall (.otg). |
|
|  | [HTM](#HTM) | Representerar en Hypertext Markup Language-fil (.htm), som är filändelsen för webbsidor skapade för visning i webbläsare. |
|
|  | [HTML](#HTML) | Representerar en Hypertext Markup Language-fil (.html), som är filändelsen för webbsidor skapade för visning i webbläsare. |
|
|  | [MHT](#MHT) | Representerar ett MHTML-webbarkiv (.mht). |
|
|  | [NSF](#NSF) | Representerar en Lotus Notes-databas (.nsf). |
|
|  | [MBOX](#MBOX) | Representerar en e-postbrevlådefil (.mbox). |
|
|  | [MHTML](#MHTML) | Representerar en MIME HTML-fil (.mhtml). |
|
|  | [XML](#XML) | Representerar en XML-fil (.xml). |
|
|  | [ONE](#ONE) | Representerar ett OneNote-dokument (.one) skapat av Microsoft OneNote-applikationen. |
|
|  | [PDF](#PDF) | Representerar en Portable Document Format-fil (.pdf), som är en dokumenttyp skapad av Adobe på 1990-talet. |
|
|  | [XPS](#XPS) | Representerar en XML Paper Specification-fil (.xps), som representerar sidlayoutfiler baserade på XML Paper Specifications skapade av Microsoft. |
|
|  | [OXPS](#OXPS) | Representerar en OpenXPS-fil (.oxps). |
|
|  | [TEX](#TEX) | Representerar ett LaTeX‑källdokument (.tex), som är ett språk som omfattar programmering samt markup‑funktioner som används för att sätta dokument. |
|
|  | [OFD](#OFD) | Open Fixed‑layout Document (OFD)-formatet som definierats av GB/T 33190-2016 syftar till att ersätta PDF i kinesiska offentliga institutioner. |
|
|  | [PPT](#PPT) | Representerar en PowerPoint‑presentation (.ppt), som representerar en PowerPoint‑fil som består av en samling bilder för visning som ett bildspel. |
|
|  | [PPTX](#PPTX) | Representerar en PowerPoint Open XML‑presentation (.pptx), som är presentationsfiler skapade med den populära Microsoft PowerPoint‑applikationen. |
|
|  | [PPS](#PPS) | Representerar ett PowerPoint‑bildspel (.pps), som skapas med Microsoft PowerPoint för bildspelsändamål. |
|
|  | [PPSX](#PPSX) | Representerar PowerPoint Open XML‑bildspelsfiler (.ppsx), som skapas med Microsoft PowerPoint 2007 och senare för bildspelsändamål. |
|
|  | [ODP](#ODP) | Representerar en OpenDocument‑presentation (.odp), som är ett presentationsfilformat som används av OpenOffice.org i OASISOpen‑standarden. |
|
|  | [FODP](#FODP) | Representerar en OpenDocument‑presentation (.fodp), som är en OpenDocument Flat XML‑presentation. |
|
|  | [POT](#POT) | Representerar en PowerPoint‑mall (.pot), som är Microsoft PowerPoint‑mallfiler skapade av PowerPoint 97‑2003‑versionerna. |
|
|  | [PPTM](#PPTM) | Representerar en PowerPoint Open XML‑makroaktiverad presentation (.pptm), som är makroaktiverade presentationsfiler skapade med Microsoft PowerPoint 2007 eller senare versioner. |
|
|  | [POTX](#POTX) | Representerar en PowerPoint Open XML‑presentationmall (.potx), som är Microsoft PowerPoint‑mallpresentationer skapade med Microsoft PowerPoint 2007 och senare. |
|
|  | [POTM](#POTM) | Representerar en PowerPoint Open XML‑makroaktiverad presentationmall (.potm), som är Microsoft PowerPoint‑mallfiler med stöd för makron. |
|
|  | [PPSM](#PPSM) | Representerar en PowerPoint Open XML‑makroaktiverad bild (.ppsm), som är ett makroaktiverat bildspelsfilformat skapat med Microsoft PowerPoint 2007 eller senare. |
|
|  | [OTP](#OTP) | Representerar en OpenDocument‑presentationmall (.otp), som är presentationsmallfiler skapade av program i OASIS OpenDocument‑standardformatet. |
|
|  | [XLS](#XLS) | Representerar ett Excel‑kalkylblad (.xls), som representerar Excel Binary File Format. |
|
|  | [EXCEL_2003_XML](#EXCEL-2003-XML) | Representerar en Excel 2003 XML (SpreadsheetML) (.xml), som representerar Excel Binary File Format. |
|
|  | [NUMBERS](#NUMBERS) | Representerar Apple Numbers (.numbers), som representerar ett Excel‑liknande binärt filformat. |
|
|  | [XLSX](#XLSX) | Representerar ett Microsoft Excel Open XML‑kalkylblad (.xlsx), som är ett välkänt format för Microsoft Excel‑dokument som introducerades av Microsoft med lanseringen av Microsoft Office 2007. |
|
|  | [XLSM](#XLSM) | Representerar ett Excel Open XML‑makroaktiverat kalkylblad (.xlsm), som är en typ av kalkylbladsfil som stödjer makron. |
|
|  | [XLSB](#XLSB) | Representerar ett Excel binärt kalkylblad (.xlsb), som specificerar Excel Binary File Format. |
|
|  | [CSV](#CSV) | Representerar en kommaseparerad värdefil (.csv), som är enkla textfiler som innehåller dataposter med kommaseparerade värden. |
|
|  | [TSV](#TSV) | Representerar en tabbseparerad värdefil (.tsv), som representerar data separerad med tabbar i enkelt textformat. |
|
|  | [ODS](#ODS) | Representerar ett OpenDocument‑kalkylblad (.ods), som står för OpenDocument Spreadsheet Document‑format som kan redigeras av användaren. |
|
|  | [FODS](#FODS) | Representerar ett OpenDocument Flat XML‑kalkylblad (.fods). |
|
|  | [OTS](#OTS) | Representerar en OpenDocument-kalkylblads-mall (.ots). |
|
|  | [XLAM](#XLAM) | Representerar ett Microsoft Excel-tillägg (.xlam). |
|
|  | [XLTM](#XLTM) | Representerar en Microsoft Excel-makroaktiverad mall (.xltm), som representerar filer som genereras av Microsoft Excel som makroaktiverade mallfiler. |
|
|  | [XLT](#XLT) | Representerar en Microsoft Excel-mall (.xlt), som är mallfiler skapade med Microsoft Excel, ett kalkylprogram som ingår i Microsoft Office-sviten. |
|
|  | [XLTX](#XLTX) | Representerar en Excel Open XML-kalkylblads-mall (.xltx), som representerar Microsoft Excel-mallar baserade på Office OpenXML-filformatsspecifikationerna. |
|
|  | [SXC](#SXC) | Representerar ett StarOffice Calc-kalkylblad (.sxc). |
|
|  | [MPP](#MPP) | Representerar en Microsoft Project-fil (.mpp), som är en Microsoft Project-datfil som lagrar information relaterad till projektledning på ett integrerat sätt. |
|
|  | [MPT](#MPT) | Representerar en Microsoft Project-mall (.mpt), som innehåller grundläggande information och struktur samt dokumentinställningar för att skapa .MPP-filer. |
|
|  | [MPX](#MPX) | Representerar en Microsoft Project Exchange-fil (.mpx), som är ett ASCII-filformat för överföring av projektinformation mellan Microsoft Project (MSP) och andra program som stödjer MPX-filformatet, såsom Primavera Project Planner, Sciforma och Timerline Precision Estimating. |
|
|  | [AS](#AS) | Representerar en ActionScript-fil (.as). |
|
|  | [AS_3](#AS-3) | Representerar en ActionScript-fil (.as3). |
|
|  | [ASM](#ASM) | Representerar en Assembly Language-källkodfil (.asm). |
|
|  | [BAT](#BAT) | Representerar en DOS-batchfil (.bat). |
|
|  | [C](#C) | Representerar en C/C++-källkodfil (.c). |
|
|  | [CC](#CC) | Representerar en C++-källkodfil (.cc). |
|
|  | [CMAKE](#CMAKE) | Representerar en CMake-fil (.cmake). |
|
|  | [CPP](#CPP) | Representerar en C++-källkodfil (.cpp). |
|
|  | [CS](#CS) | Representerar en C#-källkodfil (.cs), som är en källkodfil för programmeringsspråket C#. |
|
|  | [VB](#VB) | Representerar en Visual Basic-projektobjektfil (.vb), som är en källkodfil skapad i Visual Basic-språket. |
|
|  | [CSS](#CSS) | Representerar en Cascading Style Sheet-fil (.css). |
|
|  | [CXX](#CXX) | Representerar en C++-källkodfil (.cxx). |
|
|  | [DIFF](#DIFF) | Representerar en patchfil (.diff). |
|
|  | [ERB](#ERB) | Representerar ett Ruby ERB-skript (.erb). |
|
|  | [GROOVY](#GROOVY) | Representerar en Groovy-källkodfil (.groovy). |
|
|  | [H](#H) | Representerar en C/C++/Objective-C-headerfil (.h). |
|
|  | [HAML](#HAML) | Representerar en Haml‑källkodfil (.haml). |
|
|  | [HH](#HH) | Representerar en C++‑headerfil (.hh). |
|
|  | [JAVA](#JAVA) | Representerar en Java‑källkodfil (.java). |
|
|  | [JS](#JS) | Representerar en JavaScript‑fil (.js). |
|
|  | [JSON](#JSON) | Representerar en JSON‑fil (.json). |
|
|  | [LESS](#LESS) | Representerar en LESS‑stilmallfil (.less). |
|
|  | [LOG](#LOG) | Representerar en loggfil (.log). |
|
|  | [M](#M) | Representerar en Objective‑C‑implementationsfil (.m). |
|
|  | [MAKE](#MAKE) | Representerar ett Xcode‑Makefile‑skript (.make). |
|
|  | [MD](#MD) | Representerar en Markdown‑dokumentationsfil (.md). |
|
|  | [ML](#ML) | Representerar en ML‑källkodfil (.ml). |
|
|  | [MM](#MM) | Representerar en Objective‑C++‑källkodfil (.mm). |
|
|  | [PHP](#PHP) | Representerar en PHP‑källkodfil (.php). |
|
|  | [PL](#PL) | Representerar ett Perl‑skript (.pl). |
|
|  | [PROPERTIES](#PROPERTIES) | Representerar en Java‑egenskapsfil (.properties). |
|
|  | [PY](#PY) | Representerar ett Python‑skript (.py). |
|
|  | [RB](#RB) | Representerar en Ruby‑källkodfil (.rb). |
|
|  | [RST](#RST) | Representerar en reStructuredText‑fil (.rst). |
|
|  | [SASS](#SASS) | Representerar en Syntactically Awesome StyleSheets‑fil (.sass). |
|
|  | [SCALA](#SCALA) | Representerar en Scala‑källkodfil (.scala). |
|
|  | [SCM](#SCM) | Representerar en Scheme‑källkodfil (.scm). |
|
|  | [SCRIPT](#SCRIPT) | Representerar en generisk skriptfil (.script). |
|
|  | [SH](#SH) | Representerar ett Bash‑shell‑skript (.sh). |
|
|  | [SML](#SML) | Representerar en Standard‑ML‑källkodfil (.sml). |
|
|  | [SQL](#SQL) | Representerar en Structured Query Language‑datfil (.sql). |
|
|  | [VIM](#VIM) | Representerar en Vim-inställningsfil (.vim). |
|
|  | [YAML](#YAML) | Representerar ett YAML-dokument (.yaml). |
|
|  | [DOC](#DOC) | Representerar en Microsoft Word-dokumentfil (.doc). |
|
|  | [DOCX](#DOCX) | Representerar en Microsoft Word Open XML-dokumentfil (.docx). |
|
|  | [CHM](#CHM) | Representerar en Microsoft Compiled HTML Help-fil (.chm). |
|
|  | [DOCM](#DOCM) | Representerar en Word Open XML makroaktiverad dokumentfil (.docm). |
|
|  | [DOT](#DOT) | Representerar en Word-dokumentmall (.dot) fil. |
|
|  | [DOTX](#DOTX) | Representerar en Word Open XML-dokumentmall (.dotx) fil. |
|
|  | [DOTM](#DOTM) | Representerar en Word Open XML makroaktiverad dokumentmall (.dotm) fil. |
|
|  | [RTF](#RTF) | Representerar en Rich Text Format-fil (.rtf). |
|
|  | [TXT](#TXT) | Representerar en vanlig textfil (.txt). |
|
|  | [ODT](#ODT) | Representerar ett OpenDocument Text-dokument (.odt). |
|
|  | [OTT](#OTT) | Representerar en OpenDocument-dokumentmall (.ott). |
|
|  | [VCF](#VCF) | Representerar en vCard-fil (.vcf), som är ett digitalt filformat för lagring av kontaktinformation. |
|
|  | [AI](#AI) | Representerar en Adobe Illustrator-fil (.ai), som är ett filformat för Adobe Illustrator-ritningar. |
|
|  | [PSM1](#PSM1) | Representerar en PowerShell-skriptmodulfil (.psm1). |
|
|  | [PS1](#PS1) | Representerar en PowerShell-skriptfil (.ps1). |
|
|  | [PSD1](#PSD1) | Representerar en PowerShell-skriptmodulmanifestfil (.psd1). |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Mappar en filändelse till en filtyp. |
|
|  | [fromFilePath(String filePath)](#fromFilePath-java.lang.String-) | Extraherar filändelsen från ett filnamn eller en filsökväg och mappar den till en filtyp. |
|
|  | [fromMediaType(String mediaType)](#fromMediaType-java.lang.String-) | Mappar en filmediatyp till en filtyp. |
|
|  | [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Detekterar filtypen genom att läsa filsignaturen. |
|
|  | [fromStream(InputStream stream, String password)](#fromStream-java.io.InputStream-java.lang.String-) | Detekterar filtypen genom att läsa filsignaturen. |
|
|  | [fromStream(InputStream stream, ILogger logger)](#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-) | Detekterar filtypen genom att läsa filsignaturen. |
|
|  | [fromStream(InputStream stream, String password, ILogger logger)](#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-) | Detekterar filtypen genom att läsa filsignaturen. |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | Hämtar de stödjade filtyperna. |
|
|  | [detectCharset(String filePath)](#detectCharset-java.lang.String-) | Försöker att identifiera teckenkodning för text [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV) och [CSV](../../com.groupdocs.viewer/filetype#CSV) filer via sökväg. |
|
|  | [detectCharset(InputStream stream)](#detectCharset-java.io.InputStream-) | Försöker att identifiera teckenkodning för text [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV) och [CSV](../../com.groupdocs.viewer/filetype#CSV) fil via ström. |
|
|  | [getFileFormat()](#getFileFormat--) | Hämtar namn på filformatet, t.ex. "Microsoft Word Document". |
|
|  | [getExtension()](#getExtension--) | Hämtar filens filändelse (inklusive punkten "."), t.ex. ".doc". |
|
|  | [toString()](#toString--) | Returnerar en strängrepresentation av det aktuella objektet. |
|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Representerar en okänd filtyp.


### ZIP {#ZIP}
```
public static final FileType ZIP
```


Representerar en zip‑fil (.zip) som kan innehålla en eller flera filer eller kataloger.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/compression/zip).


### TAR {#TAR}
```
public static final FileType TAR
```


Representerar ett samlat Unix‑arkiv (.tar) som skapats för att samla en eller flera filer.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/compression/tar).


### XZ {#XZ}
```
public static final FileType XZ
```


Representerar en XZ‑fil (.xz) komprimerad med en högkomprimeringsalgoritm baserad på LZMA‑algoritmen.
Läs mer om detta filformat [här](../https://fileinfo.com/extension/xz).


### TXZ {#TXZ}
```
public static final FileType TXZ
```


Representerar ett konsoliderat Unix-filarkiv (.txz, .tar.xz) skapat för att samla en eller flera filer.
Läs mer om detta filformat [här](../https://fileinfo.com/extension/txz).


### TARXZ {#TARXZ}
```
public static final FileType TARXZ
```


Representerar ett konsoliderat Unix-filarkiv (.txz, .tar.xz) skapat för att samla en eller flera filer.
Läs mer om detta filformat [här](../https://fileinfo.com/extension/txz).


### TGZ {#TGZ}
```
public static final FileType TGZ
```


Representerar ett konsoliderat Unix-filarkiv (.tgz, .tar.gz) skapat för att samla en eller flera filer.
Läs mer om detta filformat [här](../https://fileinfo.com/extension/tgz).


### TARGZ {#TARGZ}
```
public static final FileType TARGZ
```


Representerar ett konsoliderat Unix-filarkiv (.tgz, .tar.gz) skapat för att samla en eller flera filer.
Läs mer om detta filformat [här](../https://fileinfo.com/extension/tgz).


### BZ_2 {#BZ-2}
```
public static final FileType BZ_2
```


Representerar en Bzip2-komprimerad fil (.bz2) som genererats med BZIP2‑metoden för öppen källkod.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/compression/bz2).


### RAR {#RAR}
```
public static final FileType RAR
```


Representerar en Roshal Archive (.rar) komprimerad fil som genererats med RAR‑metoden (WINRAR version 4).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/compression/rar).


### GZ {#GZ}
```
public static final FileType GZ
```


Representerar en Gnu Zipped File (.gz) komprimerad fil skapad med gzip‑komprimeringsprogrammet.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/compression/gz).


### GZIP {#GZIP}
```
public static final FileType GZIP
```


Representerar en Gnu Zipped File (.gzip) komprimerad fil som introducerades som ett gratisverktyg för att ersätta Compress‑programmet som används i Unix‑system.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/compression/gz).


### SEVEN_ZIP {#SEVEN-ZIP}
```
public static final FileType SEVEN_ZIP
```


Representerar en 7Zip (.7z, .7zip)-fil, som är en gratis öppen källkod‑arkiverare med LZMA‑ och LZMA2‑komprimering.
Läs mer om detta filformat [här](../https://docs.fileformat.com/compression/7z/).


### CPIO {#CPIO}
```
public static final FileType CPIO
```


Cpio är ett allmänt filarkiveringsverktyg och dess tillhörande filformat. Det är främst installerat på Unix-liknande operativsystem. Läs mer om detta filformat [här](../https://wiki.fileformat.com/compression/cpio).


### ZSTANDARD {#ZSTANDARD}
```
public static final FileType ZSTANDARD
```


ZST-fil är en komprimerad fil som genereras med Zstandard (zstd)-komprimeringsalgoritmen. Det är en komprimerad fil som skapas med förlustfri kompression av algoritmen. ZST-filer kan användas för att komprimera olika typer av filer såsom databaser, filsystem, nätverk och spel.
Läs mer om detta filformat [här](../https://docs.fileformat.com/compression/zst/).


### TZST {#TZST}
```
public static final FileType TZST
```


TZST‑filer (.tar.zst, .tzst) är Zstandard‑arkiv (ZST) som internt innehåller ett konsoliderat Unix-filarkiv (Tar), skapat med ett Unix‑baserat verktyg för att samla en eller flera filer.


### TAR_ZST {#TAR-ZST}
```
public static final FileType TAR_ZST
```


TZST‑filer (.tar.zst, .tzst) är Zstandard‑arkiv (ZST) som internt innehåller ett konsoliderat Unix-filarkiv (Tar), skapat med ett Unix‑baserat verktyg för att samla en eller flera filer.


### ISO {#ISO}
```
public static final FileType ISO
```


ISO‑optisk skivavbild är en okomprimerad arkiv‑diskavbildningsfil som representerar innehållet i hela data på en optisk skiva såsom CD eller DVD, baserad på ISO‑9660‑standarden.
Läs mer om detta filformat [här](../https://docs.fileformat.com/compression/iso/).


### LHA {#LHA}
```
public static final FileType LHA
```


LHA eller LZH är ett gratis komprimeringsverktyg och tillhörande filformat.
Läs mer om detta filformat [här](../https://docs.fileformat.com/compression/lzh/).


### CAB {#CAB}
```
public static final FileType CAB
```


Cabinet (eller CAB) är ett arkivfilformat för Microsoft Windows.
Läs mer om detta filformat [här](../https://en.wikipedia.org/wiki/Cabinet_(file_format)).


### DXF {#DXF}
```
public static final FileType DXF
```


Representerar en Drawing Exchange Format‑fil (.dxf), som är en taggad datarapresentation av en AutoCAD‑ritningsfil.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/cad/dxf).


### DWG {#DWG}
```
public static final FileType DWG
```


Representerar en AutoCAD Drawing Database‑fil (.dwg), som representerar proprietära binära filer som används för att innehålla 2D‑ och 3D‑designdata.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/cad/dwg).


### DWT {#DWT}
```
public static final FileType DWT
```


Representerar en AutoCAD Drawing Template (.dwt), som är en AutoCAD‑ritningsmallfil som används som utgångspunkt för att skapa ritningar som kan sparas som DWG‑filer.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/cad/dwt).


### STL {#STL}
```
public static final FileType STL
```


Representerar en Stereolitografi-fil (.stl), vilket är ett utbytbart filformat som representerar tredimensionell ytegeometri. Den används ofta i snabb prototypframställning, 3D-utskrift och datorstödd tillverkning.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/cad/stl).


### IFC {#IFC}
```
public static final FileType IFC
```


Representerar en Industry Foundation Classes-fil (.ifc), vilket är ett filformat som fastställer internationella standarder för import och export av byggnadsobjekt och deras egenskaper. Det möjliggör interoperabilitet mellan olika mjukvaruapplikationer.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/cad/ifc).


### DWF {#DWF}
```
public static final FileType DWF
```


Representerar en Design Web Format-fil (.dwf), vilket är ett komprimerat filformat för visning, granskning eller utskrift av 2D/3D-ritningar. Den innehåller grafik och text som en del av designdata och minskar filstorleken genom kompression.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/cad/dwf).


### FBX {#FBX}
```
public static final FileType FBX
```


Representerar en Autodesk FBX Interchange‑fil (FilmBoX) (.fbx), som är ett 3D‑modellformat.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/cad/fbx).


### DWFX {#DWFX}
```
public static final FileType DWFX
```


Representerar en Design Web Format-fil XPS (.dwfx), som är ett komprimerat format för visning, granskning eller utskrift av 2D/3D-ritningar som ett XPS-dokument. Den innehåller grafik och text som en del av designdata och minskar filstorleken på grund av komprimering.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/cad/dwfx).


### DGN {#DGN}
```
public static final FileType DGN
```


Representerar en MicroStation Design‑fil (.dgn), som är ritningar skapade och stödda av CAD‑program som MicroStation och Intergraph Interactive Graphics Design System.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/cad/dgn).


### PLT {#PLT}
```
public static final FileType PLT
```


Representerar en PLT (HPGL)-fil (.plt), som är en vektorbaserad plotterfil introducerad av Autodesk, Inc. Den innehåller information för en viss CAD-fil, och alla bilder skrivs ut med linjer istället för punkter, vilket säkerställer noggrannhet och precision i produktionen.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/cad/plt).


### CF2 {#CF2}
```
public static final FileType CF2
```


Representerar en Common File Format‑fil (.cf2).
Läs mer om detta filformat [här](../https://fileinfo.com/extension/cf2).


### OBJ {#OBJ}
```
public static final FileType OBJ
```


Representerar en Wavefront 3D Object‑fil (.obj), som är en 3D‑bildfil introducerad av Wavefront Technologies.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/3d/obj/).


### HPG {#HPG}
```
public static final FileType HPG
```


Representerar en PLT (HPGL)-fil (.hpg).
Det är ett filformat som används för plotterfiler i HP Graphics Language (HPGL).
Läs mer om detta filformat [här](../https://fileinfo.com/extension/hpg).


### IGS {#IGS}
```
public static final FileType IGS
```


Representerar en Initial Graphics Exchange Specification (IGES)-fil (.igs).


### VSD {#VSD}
```
public static final FileType VSD
```


Representerar en Visio-ritningsfil (.vsd), som är ritningar skapade med Microsoft Visio‑applikationen för att representera en mängd grafiska objekt och deras samband.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/vsd).


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Representerar en Visio-ritningsfil (.vsdx), som är Microsoft Visio-filformatet som introducerades från Microsoft Office 2013 och framåt. Den ersatte det binära filformatet (.VSD) som stöddes av tidigare versioner av Microsoft Visio.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/vsdx).


### VSS {#VSS}
```
public static final FileType VSS
```


Representerar en Visio-stencilfil (.vss), som är stencil-filer skapade med Microsoft Visio 2007 och tidigare. Stencil-filer tillhandahåller ritobjekt som kan inkluderas i en .VSD Visio-ritning.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/vss).


### VSSX {#VSSX}
```
public static final FileType VSSX
```


Representerar en Visio-stencilfil (.vssx), som är ritstencil-filer skapade med Microsoft Visio 2013 och senare. VSSX-filformatet kan öppnas med Visio 2013 och senare. Visio-filer är kända för att representera en mängd ritningselement såsom former, anslutningar, flödesscheman, nätverkslayout, UML-diagram osv.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/vssx).


### VSDM {#VSDM}
```
public static final FileType VSDM
```


Representerar en Visio-makroaktiverad ritning (.vsdm), som är ritningsfiler skapade med Microsoft Visio-applikationen som stödjer makron. VSDM-filer är OPC/XML-ritningar som liknar VSDX, men ger också möjlighet att köra makron när filen öppnas.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/vsdm).


### VST {#VST}
```
public static final FileType VST
```


Representerar en Visio-ritningsmall (.vst), som är vektorbildfiler skapade med Microsoft Visio. De fungerar som mallar för att skapa ytterligare filer och innehåller standardlayouten och inställningarna som används för att skapa nya Visio-ritningar.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/vst).


### VSTX {#VSTX}
```
public static final FileType VSTX
```


Representerar en Visio-ritningsmall (.vstx), som är ritningsmallfiler skapade med Microsoft Visio 2013 och senare. Dessa VSTX-filer ger en utgångspunkt för att skapa Visio-ritningar sparade som .VSDX-filer, med standardlayout och -inställningar.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/vstx).


### VSTM {#VSTM}
```
public static final FileType VSTM
```


Representerar en Visio-makroaktiverad ritningsmall (.vstm), som är mallfiler skapade med Microsoft Visio som stödjer makron. Filer som skapas från VSTM-mallar kan köra makron utvecklade i Visual Basic for Applications (VBA)-kod.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/vstm).


### VSSM {#VSSM}
```
public static final FileType VSSM
```


Representerar en Visio-makroaktiverad stencilfil (.vssm), som är Microsoft Visio-stencilfiler som stödjer makron. När en VSSM-fil öppnas kan makron köras för att uppnå önskad formatering och placering av former i ett diagram.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/vssm).


### VSX {#VSX}
```
public static final FileType VSX
```


Representerar en Visio stencil-XML-fil (.vsx), som avser stenciler bestående av ritningar och former som används för att skapa diagram i Microsoft Visio. VSX-filer sparas i XML-filformat och stöddes fram till Visio 2013.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/vsx).


### VTX {#VTX}
```
public static final FileType VTX
```


Representerar en Visio mall-XML-fil (.vtx), som är en Microsoft Visio-ritningsmall sparad på disk i XML-filformat. Mallen ger grundinställningar för att skapa flera Visio-filer med samma inställningar.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/vtx).


### VDW {#VDW}
```
public static final FileType VDW
```


Representerar en Visio‑webbritning (.vdw), som specificerar de strömmar och lagringar som krävs för att rendera en webbritning.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/web/vdw).


### VDX {#VDX}
```
public static final FileType VDX
```


Representerar en Visio ritnings-XML-fil (.vdx), som representerar alla ritningar eller diagram skapade i Microsoft Visio men sparade i XML-format med .VDX-förlängningen. En Visio-ritnings-XML-fil skapas i Visio-programvaran utvecklad av Microsoft.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/vdx).


### EPUB {#EPUB}
```
public static final FileType EPUB
```


Representerar en Open eBook-fil (.epub), som är ett e-bokfilformat som tillhandahåller ett standardiserat digitalt publiceringsformat för förlag och konsumenter. Formatet stöds av många e-läsare och mjukvaruapplikationer.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/ebook/epub).


### MOBI {#MOBI}
```
public static final FileType MOBI
```


Representerar en Mobipocket eBook (.mobi), som är ett av de mest använda e-bokfilformaten. Formatet är en förbättring av det gamla OEB (Open Ebook Format)-formatet och användes som ett proprietärt format för Mobipocket Reader.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/ebook/mobi).


### AZW_3 {#AZW-3}
```
public static final FileType AZW_3
```


Amazon Kindle Format 8 (KF8) e-bok är det digitala filformat som utvecklats för Amazon Kindle-enheter. Formatet är en förbättring av äldre AZW-filer och används endast på Kindle Fire-enheter med bakåtkompatibilitet för det föregående filformatet, dvs. MOBI och AZW.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/ebook/azw3).


### MSG {#MSG}
```
public static final FileType MSG
```


Representerar ett Outlook‑e‑postmeddelande (.msg), som är ett filformat som används av Microsoft Outlook och Exchange för att lagra e‑postmeddelanden, kontakter, möten eller andra uppgifter.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/email/msg).


### EML {#EML}
```
public static final FileType EML
```


Representerar ett e‑postmeddelande (.eml), som representerar e‑postmeddelanden sparade med Outlook och andra relevanta program. Nästan alla e‑postklienter stöder detta filformat på grund av dess efterlevnad av RFC-822 Internet Message Format‑standarden.
Läs mer om detta filformat [here](../https://wiki.fileformat.com/email/eml).


### EMLX {#EMLX}
```
public static final FileType EMLX
```


Representerar ett Apple Mail‑meddelande (.emlx), som är implementerat och utvecklat av Apple. Apple Mail‑applikationen använder EMLX‑filformatet för att exportera e‑post.
Läs mer om detta filformat [here](../https://wiki.fileformat.com/email/emlx).


### PST {#PST}
```
public static final FileType PST
```


Representerar en Outlook‑Personal Information Store‑fil (.pst), som representerar Outlook Personal Storage Files (även kallade Personal Storage Table) som lagrar en mängd användarinformation.
Läs mer om detta filformat [here](../https://wiki.fileformat.com/email/pst).


### OST {#OST}
```
public static final FileType OST
```


Representerar en Outlook‑Offline‑datafil (.ost), som representerar en användares brevlådedata i offlineläge på en lokal maskin efter registrering mot Exchange Server med Microsoft Outlook.
Läs mer om detta filformat [here](../https://wiki.fileformat.com/email/ost).


### TIF {#TIF}
```
public static final FileType TIF
```


Representerar en Tagged Image File (.tif), som representerar rasterbilder avsedda för användning på en mängd olika enheter som följer detta filformatstandard. Den kan beskriva tvånivå‑, gråskala‑, palett‑färg‑ och full‑färgsbilddata i flera färgrymder.
Läs mer om detta filformat [here](../https://wiki.fileformat.com/image/tiff).


### TIFF {#TIFF}
```
public static final FileType TIFF
```


Representerar ett Tagged Image File Format (.tiff), som representerar rasterbilder avsedda för användning på en mängd olika enheter som följer detta filformatstandard. Den kan beskriva tvånivå‑, gråskala‑, palett‑färg‑ och full‑färgsbilddata i flera färgrymder.
Läs mer om detta filformat [here](../https://wiki.fileformat.com/image/tiff).


### JPG {#JPG}
```
public static final FileType JPG
```


Representerar en JPEG‑bild (.jpg), som är en typ av bildformat som sparas med förlustkomprimering. Den resulterande bilden är en avvägning mellan lagringsstorlek och bildkvalitet.
Läs mer om detta filformat [here](../https://wiki.fileformat.com/image/jpeg).


### JPEG {#JPEG}
```
public static final FileType JPEG
```


Representerar en JPEG‑bild (.jpeg), som är en typ av bildformat som sparas med förlustkomprimering. Den resulterande bilden är en avvägning mellan lagringsstorlek och bildkvalitet.
Läs mer om detta filformat [here](../https://wiki.fileformat.com/image/jpeg).


### JFIF {#JFIF}
```
public static final FileType JFIF
```


JPEG File Interchange Format (.jfif) är en bild som utvecklades för snabb utbyte mellan plattformar. Detta format använder JPEG‑komprimering. Läs mer om detta filformat [here](../https://wiki.fileformat.com/image/jfif).


### PNG {#PNG}
```
public static final FileType PNG
```


Representerar en Portable Network Graphic (.png), som är en typ av rasterbildfilformat som använder förlustfri komprimering. Detta filformat skapades som en ersättning för Graphics Interchange Format (GIF) och har inga upphovsrättsliga begränsningar.
Läs mer om detta filformat [here](../https://wiki.fileformat.com/image/png).


### GIF {#GIF}
```
public static final FileType GIF
```


Representerar en Graphical Interchange Format‑fil (.gif), som är en typ av starkt komprimerad bild. För varje bild tillåter GIF vanligtvis upp till 8 bitar per pixel, och upp till 256 färger är tillåtna i bilden.
Läs mer om detta filformat [here](../https://wiki.fileformat.com/image/gif).


### APNG {#APNG}
```
public static final FileType APNG
```


Representerar en Animated Portable Network Graphic (.apng), som är en utökning av PNG-formatet som stödjer animation.
Läs mer om detta filformat [here](../https://wiki.fileformat.com/image/apng).


### BMP {#BMP}
```
public static final FileType BMP
```


Representerar en Bitmap Image File (.bmp), som används för att lagra bitmap‑digitala bilder. Dessa bilder är oberoende av grafikadaptern och kallas även device independent bitmap (DIB)‑filformat.
Läs mer om detta filformat [here](../https://wiki.fileformat.com/image/bmp).


### ICO {#ICO}
```
public static final FileType ICO
```


Representerar en Icon File (.ico), som är en bildfilstyp som används som ikon för att representera ett program på Microsoft Windows.
Läs mer om detta filformat [here](../https://wiki.fileformat.com/image/ico).


### TGA {#TGA}
```
public static final FileType TGA
```


Representerar en Truevision TGA (TARGA)-fil, som används för att lagra bitmapdigitala bilder utvecklade av TRUEVISION.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/tga).


### JP_2 {#JP-2}
```
public static final FileType JP_2
```


Representerar en JPEG 2000 Core Image File (.jp2), som är ett bildkodningssystem och en toppmodern bildkomprimeringsstandard.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/jp2).


### JPF {#JPF}
```
public static final FileType JPF
```


Representerar en JPEG 2000 Image File (.jpf).
Läs mer om detta filformat [här](../https://docs.fileformat.com/image/jpf).


### JPX {#JPX}
```
public static final FileType JPX
```


Representerar en JPEG 2000 Image File (.jpx).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/jpx).


### JPM {#JPM}
```
public static final FileType JPM
```


Representerar en JPEG 2000 Image File (.jpm).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/jpm).


### J2C {#J2C}
```
public static final FileType J2C
```


Representerar en JPEG 2000 Code InputStream (.j2c).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/j2c).


### J2K {#J2K}
```
public static final FileType J2K
```


Representerar en JPEG 2000 Code Stream (.j2k), som är en bild komprimerad med wavelet-komprimering istället för DCT-komprimering.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/j2k).


### JPC {#JPC}
```
public static final FileType JPC
```


Representerar en JPEG 2000 Code Stream (.jpc).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/jpc).


### JLS {#JLS}
```
public static final FileType JLS
```


Representerar en JPEG-LS (JLS)-fil (.jls).
Läs mer om detta filformat [här](../https://fileinfo.com/extension/jls).


### DIB {#DIB}
```
public static final FileType DIB
```


Representerar en Device Independent Bitmap File (.dib).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/dib).


### WMF {#WMF}
```
public static final FileType WMF
```


Representerar en Windows Metafile (.wmf), som representerar Microsoft Windows Metafile (WMF) för lagring av både vektor- och bitmapformatbilddata.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/wmf).


### WMZ {#WMZ}
```
public static final FileType WMZ
```


Representerar en Compressed Windows Metafile (.wmz), som representerar Microsoft Windows Metafile (WMF) komprimerad i ett GZIP-arkiv för lagring av både vektor- och bitmapformatbilddata.
Läs mer om detta filformat [här](../https://fileinfo.com/extension/wmz#compressed_windows_metafile).


### EMF {#EMF}
```
public static final FileType EMF
```


Representerar en förbättrad Windows Metafil (.emf), som representerar grafiska bilder enhetsoberoende. Metafiler för EMF består av variabellängda poster i kronologisk ordning som kan återge den lagrade bilden efter parsning på vilken utskriftsenhet som helst.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/emf).


### EMZ {#EMZ}
```
public static final FileType EMZ
```


Representerar en Windows-komprimerad förbättrad Metafil (.emz), som representerar grafiska bilder enhetsoberoende komprimerade med GZIP. Metafiler för EMF består av variabellängda poster i kronologisk ordning som kan återge den lagrade bilden efter parsning på vilken utskriftsenhet som helst.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/emz).


### WEBP {#WEBP}
```
public static final FileType WEBP
```


Representerar en WebP-bild (.webp), som är ett modernt rasterwebbbildformat baserat på förlustfri och förlustkomprimering. Det ger samma bildkvalitet samtidigt som bildstorleken minskas avsevärt.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/webp).


### DNG {#DNG}
```
public static final FileType DNG
```


Representerar en Digital Negative Specification (.dng), som är ett digitalt kamerabildformat för lagring av råfiler. Det utvecklades av Adobe i september 2004 och används främst för digital fotografering.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/dng).


### CDR {#CDR}
```
public static final FileType CDR
```


Representerar en CorelDraw vektorgrafikritning (.cdr), som är en vektorritningsfil som ursprungligen skapats med CorelDRAW för lagring av digitalt kodade och komprimerade bilder. En CDR-ritningsfil innehåller text, linjer, former, bilder, färger och effekter för vektorrepresentation av bildinnehåll.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/cdr).


### CMX {#CMX}
```
public static final FileType CMX
```


Representerar en Corel Exchange (.cmx), som är en ritningsbildfil som kan innehålla vektorgrafik såväl som bitmapgrafik.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/cmx).


### DJVU {#DJVU}
```
public static final FileType DJVU
```


Representerar en DjVu-bild (.djvu), som är ett grafikfilformat avsett för skannade dokument och böcker, särskilt de som innehåller en kombination av text, teckningar, bilder och fotografier.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/djvu).


### CGM {#CGM}
```
public static final FileType CGM
```


Representerar en Computer Graphics Metafile (.cgm), som är ett fritt, plattformsoberoende, internationellt standardmetafilformat för lagring och utbyte av vektorgrafik (2D), rastergrafik och text. CGM använder ett objektorienterat tillvägagångssätt och erbjuder många funktioner för bildproduktion.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/page-description-language/cgm).


### PCL {#PCL}
```
public static final FileType PCL
```


Representerar ett Printer Command Language-dokument (.pcl).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/page-description-language/pcl).


### PSD {#PSD}
```
public static final FileType PSD
```


Representerar ett Adobe Photoshop-dokument (.psd), som är Adobe Photoshops inhemska filformat som används för grafisk design och utveckling.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/psd).


### PSB {#PSB}
```
public static final FileType PSB
```


Representerar ett Photoshop Large Document Format (.psb), som används för grafisk design och utveckling i Adobe Photoshop.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/psb).


### DCM {#DCM}
```
public static final FileType DCM
```


Representerar en DICOM-bild (.dcm), som representerar en digital bild som lagrar medicinsk information om patienter såsom MR, CT-skanningar och ultraljudsbilder.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/dcm).


### PS {#PS}
```
public static final FileType PS
```


Representerar en PostScript-fil (.ps).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/page-description-language/ps).


### EPS {#EPS}
```
public static final FileType EPS
```


Representerar en Encapsulated PostScript-fil (.eps), som beskriver ett Encapsulated PostScript-språkprogram som definierar utseendet på en enda sida.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/page-description-language/eps).


### ODG {#ODG}
```
public static final FileType ODG
```


Representerar en OpenDocument Graphic-fil (.odg), som används av Apache OpenOffice Draw-applikationen för att lagra ritningselement som en vektorbild.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/odg).


### FODG {#FODG}
```
public static final FileType FODG
```


Representerar en Flat XML ODF-mall (.fodg), som används av Apache OpenOffice Draw-applikationen för att lagra ritningselement som en vektorbild.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/image/fodg).


### SVG {#SVG}
```
public static final FileType SVG
```


Representerar en Scalable Vector Graphics-fil (.svg), som är en Scalable Vector Graphics-fil som använder ett XML-baserat textformat för att beskriva en bilds utseende.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/page-description-language/svg).


### SVGZ {#SVGZ}
```
public static final FileType SVGZ
```


Representerar en Compressed Scalable Vector Graphics-fil (.svgz), som är en Scalar Vector Graphics-fil som använder ett XML-baserat textformat, komprimerat med GZIP, för att beskriva en bilds utseende.
Läs mer om detta filformat [här](../https://fileinfo.com/extension/svgz).


### OTG {#OTG}
```
public static final FileType OTG
```


Representerar en OpenDocument Graphic-mall (.otg).
Läs mer om detta filformat [här](../https://docs.fileformat.com/image/otg).


### HTM {#HTM}
```
public static final FileType HTM
```


Representerar en Hypertext Markup Language-fil (.htm), som är filändelsen för webbsidor skapade för visning i webbläsare.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/web/html).


### HTML {#HTML}
```
public static final FileType HTML
```


Representerar en Hypertext Markup Language-fil (.html), som är filändelsen för webbsidor skapade för visning i webbläsare.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/web/html).


### MHT {#MHT}
```
public static final FileType MHT
```


Representerar ett MHTML-webbarkiv (.mht).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/web/mht).


### NSF {#NSF}
```
public static final FileType NSF
```


Representerar en Lotus Notes-databas (.nsf).
Läs mer om detta filformat [här](../https://fileinfo.com/extension/nsf).


### MBOX {#MBOX}
```
public static final FileType MBOX
```


Representerar en e-postbrevlådefil (.mbox).
Läs mer om detta filformat [här](../https://fileinfo.com/extension/mbox).


### MHTML {#MHTML}
```
public static final FileType MHTML
```


Representerar en MIME HTML-fil (.mhtml).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/web/mhtml).


### XML {#XML}
```
public static final FileType XML
```


Representerar en XML-fil (.xml).
Läs mer om detta filformat [här](../https://docs.fileformat.com/web/xml).


### ONE {#ONE}
```
public static final FileType ONE
```


Representerar ett OneNote-dokument (.one) skapat av Microsoft OneNote‑applikationen. OneNote låter dig samla information med applikationen som om du använde ditt anteckningsblock för att ta anteckningar.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/note-taking/one).


### PDF {#PDF}
```
public static final FileType PDF
```


Representerar en Portable Document Format‑fil (.pdf), som är en typ av dokument som skapades av Adobe på 1990‑talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av programvara, hårdvara och operativsystem.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/view/pdf).


### XPS {#XPS}
```
public static final FileType XPS
```


Representerar en XML Paper Specification‑fil (.xps), som representerar sidlayoutfiler baserade på XML Paper Specifications skapade av Microsoft. Detta format utvecklades av Microsoft som en ersättning för EMF‑filformatet och liknar PDF‑filformatet, men använder XML i layout, utseende och utskriftsinformation för ett dokument.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/page-description-language/xps).


### OXPS {#OXPS}
```
public static final FileType OXPS
```


Representerar en OpenXPS-fil (.oxps).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/page-description-language/oxps).


### TEX {#TEX}
```
public static final FileType TEX
```


Representerar ett LaTeX‑källdokument (.tex), som är ett språk som omfattar programmering samt markup‑funktioner som används för att sätta dokument.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/page-description-language/tex).


### OFD {#OFD}
```
public static final FileType OFD
```


Open Fixed‑layout Document (OFD)-formatet som definierats av GB/T 33190-2016 syftar till att ersätta PDF i kinesiska offentliga institutioner.


### PPT {#PPT}
```
public static final FileType PPT
```


Representerar en PowerPoint-presentation (.ppt), som representerar en PowerPoint-fil som består av en samling bilder för visning som ett bildspel. Den specificerar det binära filformatet som används av Microsoft PowerPoint 97-2003.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/presentation/ppt).


### PPTX {#PPTX}
```
public static final FileType PPTX
```


Representerar en PowerPoint Open XML-presentation (.pptx), som är presentationsfiler skapade med det populära Microsoft PowerPoint-programmet. Till skillnad från den tidigare versionen av presentationsfilformatet PPT, som var binärt, är PPTX-formatet baserat på Microsoft PowerPoint Open XML-presentationens filformat.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/presentation/pptx).


### PPS {#PPS}
```
public static final FileType PPS
```


Representerar ett PowerPoint-bildspel (.pps), som skapas med Microsoft PowerPoint för bildspelsändamål. Läsning och skapande av PPS-filer stöds av Microsoft PowerPoint 97-2003.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/presentation/pps).


### PPSX {#PPSX}
```
public static final FileType PPSX
```


Representerar PowerPoint Open XML‑bildspelsfiler (.ppsx), som skapas med Microsoft PowerPoint 2007 och senare för bildspelsändamål.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/presentation/ppsx).


### ODP {#ODP}
```
public static final FileType ODP
```


Representerar en OpenDocument‑presentation (.odp), som är ett presentationsfilformat som används av OpenOffice.org i OASISOpen‑standarden.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/presentation/odp).


### FODP {#FODP}
```
public static final FileType FODP
```


Representerar en OpenDocument‑presentation (.fodp), som är en OpenDocument Flat XML‑presentation.
Läs mer om detta filformat [här](../https://fileinfo.com/extension/fodp).


### POT {#POT}
```
public static final FileType POT
```


Representerar en PowerPoint‑mall (.pot), som är Microsoft PowerPoint‑mallfiler skapade av PowerPoint 97‑2003‑versionerna.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/presentation/pot).


### PPTM {#PPTM}
```
public static final FileType PPTM
```


Representerar en PowerPoint Open XML‑makroaktiverad presentation (.pptm), som är makroaktiverade presentationsfiler skapade med Microsoft PowerPoint 2007 eller senare versioner.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/presentation/pptm).


### POTX {#POTX}
```
public static final FileType POTX
```


Representerar en PowerPoint Open XML‑presentationmall (.potx), som är Microsoft PowerPoint‑mallpresentationer skapade med Microsoft PowerPoint 2007 och senare.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/presentation/potx).


### POTM {#POTM}
```
public static final FileType POTM
```


Representerar en PowerPoint Open XML-makroaktiverad presentationsmall (.potm), som är Microsoft PowerPoint-mallar med stöd för makron. POTM-filer skapas med PowerPoint 2007 eller senare och innehåller standardinställningar som kan användas för att skapa ytterligare presentationsfiler.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/presentation/potm).


### PPSM {#PPSM}
```
public static final FileType PPSM
```


Representerar en PowerPoint Open XML‑makroaktiverad bild (.ppsm), som är ett makroaktiverat bildspelsfilformat skapat med Microsoft PowerPoint 2007 eller senare.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/presentation/ppsm).


### OTP {#OTP}
```
public static final FileType OTP
```


Representerar en OpenDocument‑presentationmall (.otp), som är presentationsmallfiler skapade av program i OASIS OpenDocument‑standardformatet.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/presentation/otp).


### XLS {#XLS}
```
public static final FileType XLS
```


Representerar ett Excel-kalkylblad (.xls), som representerar Excel:s binära filformat. Sådana filer kan skapas av Microsoft Excel samt andra liknande kalkylprogram som OpenOffice Calc eller Apple Numbers.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/spreadsheet/xls).


### EXCEL_2003_XML {#EXCEL-2003-XML}
```
public static final FileType EXCEL_2003_XML
```


Representerar en Excel 2003 XML (SpreadsheetML) (.xml), som representerar Excel:s binära filformat. Sådana filer kan skapas av Microsoft Excel samt andra liknande kalkylprogram som OpenOffice Calc eller Apple Numbers.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/spreadsheet/xls).


### NUMBERS {#NUMBERS}
```
public static final FileType NUMBERS
```


Representerar Apple Numbers (.numbers), som representerar ett Excel-liknande binärt filformat. Sådana filer kan skapas av Apple Numbers‑applikationen.
Läs mer om detta filformat [här](../https://fileinfo.com/extension/numbers).


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Representerar ett Microsoft Excel Open XML‑kalkylblad (.xlsx), som är ett välkänt format för Microsoft Excel‑dokument som introducerades av Microsoft med lanseringen av Microsoft Office 2007.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/spreadsheet/xlsx).


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Representerar ett Excel Open XML‑makroaktiverat kalkylblad (.xlsm), som är en typ av kalkylbladsfil som stödjer makron.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/spreadsheet/xlsm).


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Representerar ett Excel Binary Spreadsheet (.xlsb), som specificerar Excel Binary File Format. Det är en samling av poster och strukturer som specificerar innehållet i en Excel workbook.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/spreadsheet/xlsb).


### CSV {#CSV}
```
public static final FileType CSV
```


Representerar en kommaseparerad värdefil (.csv), som är enkla textfiler som innehåller dataposter med kommaseparerade värden.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/spreadsheet/csv).


### TSV {#TSV}
```
public static final FileType TSV
```


Representerar en tabbseparerad värdefil (.tsv), som representerar data separerad med tabbar i enkelt textformat.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/spreadsheet/tsv).


### ODS {#ODS}
```
public static final FileType ODS
```


Representerar ett OpenDocument Spreadsheet (.ods), som står för OpenDocument Spreadsheet Document-format som är redigerbart av användaren. Data lagras i ODF-filer i rader och kolumner.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/spreadsheet/ods).


### FODS {#FODS}
```
public static final FileType FODS
```


Representerar ett OpenDocument Flat XML‑kalkylblad (.fods).
Det är ett kalkylbladsdokumentformat baserat på XML som används av OpenOffice och LibreOffice.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/spreadsheet/fods).


### OTS {#OTS}
```
public static final FileType OTS
```


Representerar en OpenDocument-kalkylblads-mall (.ots).
Det är ett malldokumentformat som används av OpenOffice och LibreOffice för kalkylblad.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/spreadsheet/ots).


### XLAM {#XLAM}
```
public static final FileType XLAM
```


Representerar ett Microsoft Excel-tillägg (.xlam).
Det är ett filformat som används av Microsoft Excel för att skapa tillägg med anpassad funktionalitet.
Läs mer om detta filformat [här](../https://fileinfo.com/extension/xlam).


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Representerar en Microsoft Excel Macro-Enabled Template (.xltm), som representerar filer som genereras av Microsoft Excel som makroaktiverade mallfiler. XLTM-filer är liknande XLTX i struktur förutom att den senare inte stödjer att skapa mallfiler med makron.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/spreadsheet/xltm).


### XLT {#XLT}
```
public static final FileType XLT
```


Representerar en Microsoft Excel Template (.xlt), som är mallfiler skapade med Microsoft Excel, ett kalkylprogram som ingår i Microsoft Office-paketet. Microsoft Office 97-2003 stödde att skapa nya XLT-filer samt att öppna dem.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/spreadsheet/xlt).


### XLTX {#XLTX}
```
public static final FileType XLTX
```


Representerar en Excel Open XML Spreadsheet Template (.xltx), som representerar Microsoft Excel-mallar baserade på Office OpenXML-filformatsspecifikationerna. Den används för att skapa en standardmallfil som kan användas för att generera XLSX-filer med samma inställningar som specificeras i XLTX-filen.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/spreadsheet/xltx).


### SXC {#SXC}
```
public static final FileType SXC
```


Representerar ett StarOffice Calc-kalkylblad (.sxc).
Det är ett kalkylbladsdokument skapat med StarOffice Calc, ett kalkylprogram.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/spreadsheet/sxc).


### MPP {#MPP}
```
public static final FileType MPP
```


Representerar en Microsoft Project-fil (.mpp), som är en Microsoft Project-datfil som lagrar information relaterad till projektledning på ett integrerat sätt.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/project-management/mpp).


### MPT {#MPT}
```
public static final FileType MPT
```


Representerar en Microsoft Project-mall (.mpt), som innehåller grundläggande information och struktur samt dokumentinställningar för att skapa .MPP-filer.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/project-management/mpt).


### MPX {#MPX}
```
public static final FileType MPX
```


Representerar en Microsoft Project Exchange-fil (.mpx), som är ett ASCII-filformat för överföring av projektinformation mellan Microsoft Project (MSP) och andra program som stödjer MPX-filformatet, såsom Primavera Project Planner, Sciforma och Timerline Precision Estimating.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/project-management/mpx).


### AS {#AS}
```
public static final FileType AS
```


Representerar en ActionScript-fil (.as).
Läs mer om detta filformat [här](../https://docs.fileformat.com/programming/as).


### AS_3 {#AS-3}
```
public static final FileType AS_3
```


Representerar en ActionScript-fil (.as3).
Läs mer om detta filformat [här](../https://datatypes.net/open-as3-files).


### ASM {#ASM}
```
public static final FileType ASM
```


Representerar en Assembly Language-källkodfil (.asm).
Läs mer om detta filformat [här](../https://docs.fileformat.com/cad/asm).


### BAT {#BAT}
```
public static final FileType BAT
```


Representerar en DOS-batchfil (.bat).
Läs mer om detta filformat [här](../https://docs.fileformat.com/executable/bat).


### C {#C}
```
public static final FileType C
```


Representerar en C/C++-källkodfil (.c).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/programming/c).


### CC {#CC}
```
public static final FileType CC
```


Representerar en C++-källkodfil (.cc).
Läs mer om detta filformat [här](../https://docs.fileformat.com/programming/cc).


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Representerar en CMake-fil (.cmake).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/programming/cmake).


### CPP {#CPP}
```
public static final FileType CPP
```


Representerar en C++-källkodfil (.cpp).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/programming/cpp).


### CS {#CS}
```
public static final FileType CS
```


Representerar en C#-källkodfil (.cs), som är en källkodfil för C#-programmeringsspråket. Den introducerades av Microsoft för användning med .NET Framework.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/programming/cs).


### VB {#VB}
```
public static final FileType VB
```


Representerar en Visual Basic-projektfil (.vb), som är en källkodfil skapad i Visual Basic-språket. Den skapades av Microsoft för utveckling av .NET-applikationer.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/programming/vb).


### CSS {#CSS}
```
public static final FileType CSS
```


Representerar en Cascading Style Sheet-fil (.css).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/web/css).


### CXX {#CXX}
```
public static final FileType CXX
```


Representerar en C++-källkodfil (.cxx).
Läs mer om detta filformat [här](../https://docs.fileformat.com/programming/cxx).


### DIFF {#DIFF}
```
public static final FileType DIFF
```


Representerar en patchfil (.diff).
Läs mer om detta filformat [här](../https://docs.fileformat.com/programming/diff).


### ERB {#ERB}
```
public static final FileType ERB
```


Representerar ett Ruby ERB-skript (.erb).
Läs mer om detta filformat [här](../https://docs.fileformat.com/programming/erb).


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Representerar en Groovy-källkodfil (.groovy).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/programming/groovy).


### H {#H}
```
public static final FileType H
```


Representerar en C/C++/Objective-C-headerfil (.h).
Läs mer om detta filformat [här](../https://docs.fileformat.com/programming/h).


### HAML {#HAML}
```
public static final FileType HAML
```


Representerar en Haml‑källkodfil (.haml).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/programming/haml).


### HH {#HH}
```
public static final FileType HH
```


Representerar en C++‑headerfil (.hh).
Läs mer om detta filformat [här](../https://docs.fileformat.com/programming/hh).


### JAVA {#JAVA}
```
public static final FileType JAVA
```


Representerar en Java‑källkodfil (.java).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/programming/java).


### JS {#JS}
```
public static final FileType JS
```


Representerar en JavaScript‑fil (.js).
Läs mer om detta filformat [här](../https://docs.fileformat.com/web/js).


### JSON {#JSON}
```
public static final FileType JSON
```


Representerar en JSON‑fil (.json).
Läs mer om detta filformat [här](../https://docs.fileformat.com/web/json).


### LESS {#LESS}
```
public static final FileType LESS
```


Representerar en LESS‑stilmallfil (.less).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/web/less).


### LOG {#LOG}
```
public static final FileType LOG
```


Representerar en loggfil (.log).
Läs mer om detta filformat [här](../https://docs.fileformat.com/database/log).


### M {#M}
```
public static final FileType M
```


Representerar en Objective‑C‑implementationsfil (.m).
Läs mer om detta filformat [här](../https://fileinfo.com/extension/m).


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Representerar ett Xcode‑Makefile‑skript (.make).
Läs mer om detta filformat [här](../https://docs.fileformat.com/programming/make).


### MD {#MD}
```
public static final FileType MD
```


Representerar en Markdown‑dokumentationsfil (.md).
Läs mer om detta filformat [här](../https://docs.fileformat.com/word-processing/md).


### ML {#ML}
```
public static final FileType ML
```


Representerar en ML‑källkodfil (.ml).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/programming/ml).


### MM {#MM}
```
public static final FileType MM
```


Representerar en Objective‑C++‑källkodfil (.mm).
Läs mer om detta filformat [här](../https://docs.fileformat.com/programming/mm).


### PHP {#PHP}
```
public static final FileType PHP
```


Representerar en PHP‑källkodfil (.php).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/programming/php).


### PL {#PL}
```
public static final FileType PL
```


Representerar ett Perl‑skript (.pl).
Läs mer om detta filformat [här](../https://docs.fileformat.com/programming/pl).


### PROPERTIES {#PROPERTIES}
```
public static final FileType PROPERTIES
```


Representerar en Java‑egenskapsfil (.properties).
Läs mer om detta filformat [här](../https://fileinfo.com/extension/properties).


### PY {#PY}
```
public static final FileType PY
```


Representerar ett Python‑skript (.py).
Läs mer om detta filformat [här](../https://docs.fileformat.com/programming/py).


### RB {#RB}
```
public static final FileType RB
```


Representerar en Ruby‑källkodfil (.rb).
Läs mer om detta filformat [här](../https://docs.fileformat.com/programming/rb).


### RST {#RST}
```
public static final FileType RST
```


Representerar en reStructuredText‑fil (.rst).
Läs mer om detta filformat [här](../https://docs.fileformat.com/programming/rst).


### SASS {#SASS}
```
public static final FileType SASS
```


Representerar en Syntactically Awesome StyleSheets‑fil (.sass).
Läs mer om detta filformat [här](../https://docs.fileformat.com/web/sass).


### SCALA {#SCALA}
```
public static final FileType SCALA
```


Representerar en Scala‑källkodfil (.scala).
Läs mer om detta filformat [här](../https://docs.fileformat.com/programming/scala).


### SCM {#SCM}
```
public static final FileType SCM
```


Representerar en Scheme‑källkodfil (.scm).
Läs mer om detta filformat [här](../https://docs.fileformat.com/programming/scm).


### SCRIPT {#SCRIPT}
```
public static final FileType SCRIPT
```


Representerar en generisk skriptfil (.script).
Läs mer om detta filformat [här](../https://docs.fileformat.com/programming/script).


### SH {#SH}
```
public static final FileType SH
```


Representerar ett Bash‑shell‑skript (.sh).
Läs mer om detta filformat [här](../https://docs.fileformat.com/cs/programming/sh).


### SML {#SML}
```
public static final FileType SML
```


Representerar en Standard‑ML‑källkodfil (.sml).
Läs mer om detta filformat [här](../https://fileinfo.com/extension/sml).


### SQL {#SQL}
```
public static final FileType SQL
```


Representerar en Structured Query Language‑datfil (.sql).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/database/sql).


### VIM {#VIM}
```
public static final FileType VIM
```


Representerar en Vim-inställningsfil (.vim).
Läs mer om detta filformat [här](../https://fileinfo.com/extension/vim).


### YAML {#YAML}
```
public static final FileType YAML
```


Representerar ett YAML-dokument (.yaml).
Läs mer om detta filformat [här](../https://docs.fileformat.com/programming/yaml).


### DOC {#DOC}
```
public static final FileType DOC
```


Representerar en Microsoft Word-dokumentfil (.doc).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/word-processing/doc).


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Representerar en Microsoft Word Open XML-dokumentfil (.docx).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/word-processing/docx).


### CHM {#CHM}
```
public static final FileType CHM
```


Representerar en Microsoft Compiled HTML Help-fil (.chm).
Läs mer om detta filformat [här](../https://docs.fileformat.com/web/chm).


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Representerar en Word Open XML makroaktiverad dokumentfil (.docm).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/word-processing/docm).


### DOT {#DOT}
```
public static final FileType DOT
```


Representerar en Word-dokumentmall (.dot) fil.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/word-processing/dot).


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Representerar en Word Open XML-dokumentmall (.dotx) fil.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/word-processing/dotx).


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Representerar en Word Open XML makroaktiverad dokumentmall (.dotm) fil.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/word-processing/dotm).


### RTF {#RTF}
```
public static final FileType RTF
```


Representerar en Rich Text Format-fil (.rtf).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/word-processing/rtf).


### TXT {#TXT}
```
public static final FileType TXT
```


Representerar en vanlig textfil (.txt).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/word-processing/txt).


### ODT {#ODT}
```
public static final FileType ODT
```


Representerar ett OpenDocument Text-dokument (.odt).
Läs mer om detta filformat [här](../https://wiki.fileformat.com/word-processing/odt).


### OTT {#OTT}
```
public static final FileType OTT
```


Representerar en OpenDocument-dokumentmall (.ott).
Det är ett mall-dokument som genererats i enlighet med OASIS' OpenDocument-standardformat.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/word-processing/ott).


### VCF {#VCF}
```
public static final FileType VCF
```


Representerar en vCard-fil (.vcf), som är ett digitalt filformat för lagring av kontaktinformation.
Det används i stor utsträckning för datautbyte mellan populära informationsutbytesprogram.
Läs mer om detta filformat [här](../https://wiki.fileformat.com/email/vcf).


### AI {#AI}
```
public static final FileType AI
```


Representerar en Adobe Illustrator-fil (.ai), som är ett filformat för Adobe Illustrator-ritningar.
Läs mer om detta filformat [här](../https://docs.fileformat.com/image/ai).


### PSM1 {#PSM1}
```
public static final FileType PSM1
```


Representerar en PowerShell-skriptmodulfil (.psm1).
Det är ett filformat för PowerShell-modulskript.
Läs mer om detta filformat [här](../https://fileinfo.com/extension/psm1).


### PS1 {#PS1}
```
public static final FileType PS1
```


Representerar en PowerShell-skriptfil (.ps1).
Det är ett filformat för Windows PowerShell Cmdlet-filer.
Läs mer om detta filformat [här](../https://fileinfo.com/extension/ps1).


### PSD1 {#PSD1}
```
public static final FileType PSD1
```


Representerar en PowerShell-skriptmodulmanifestfil (.psd1).
Det är ett filformat för PowerShell-modulmanifestskript.
Läs mer om detta filformat [här](../https://fileinfo.com/extension/psd1).


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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


Mappar en filändelse till en filtyp.


Denna metod tar en filändelse, med eller utan punkten ".", och returnerar motsvarande filtyp om den stöds.
Om filtypen inte stöds returnerar den standardfiltypen [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | extension | java.lang.String | Filändelsen med eller utan punkten ".". |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromFilePath(String filePath) {#fromFilePath-java.lang.String-}
```
public static FileType fromFilePath(String filePath)
```


Extraherar filändelsen från ett filnamn eller en filsökväg och mappar den till en filtyp.


Om filtypen stöds returnerar metoden motsvarande
FileType
,
annars returnerar den standardfiltypen [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Filnamnet eller filsökvägen. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromMediaType(String mediaType) {#fromMediaType-java.lang.String-}
```
public static FileType fromMediaType(String mediaType)
```


Mappar en filmediatyp till en filtyp. Till exempel kommer 'application/pdf' att mappas till [PDF](../../com.groupdocs.viewer/filetype#PDF).


Denna metod tar en filmediatyp som indata och mappar den till motsvarande
FileType
. Om mediatypen är
stöds, returnerar metoden den motsvarande filtypen. Om mediatypen inte stöds, returnerar den standardvärdet
[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | mediaType | java.lang.String | Filens mediatyp, t.ex. 'application/pdf'. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if found, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream stream)
```


Detekterar filtypen genom att läsa filsignaturen.


Denna metod tar ett inmatningsflöde som representerar en fil och försöker upptäcka dess filtyp genom att analysera filsignaturen. Det
Filsignaturen är en unik sekvens av byte i början av filen som indikerar dess filtyp. Metoden
läser filsignaturen från inmatningsflödet och matchar den mot kända filsignaturer för stödda filtyper.
Om en matchning hittas, returnerar metoden den motsvarande filtypen. Om ingen matchning hittas, returnerar den standardvärdet
[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | stream | java.io.InputStream | Inmatningsflödet som representerar filen. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, String password) {#fromStream-java.io.InputStream-java.lang.String-}
```
public static FileType fromStream(InputStream stream, String password)
```


Detekterar filtypen genom att läsa filsignaturen.


Denna metod analyserar filsignaturen, som är en unik sekvens av byte i början av filen, för att bestämma
filtypen. Den läser filsignaturen från det angivna inmatningsflödet och matchar den mot kända filsignaturer
för stödda filtyper. Om en matchning hittas, returnerar metoden den motsvarande filtypen. Om ingen matchning hittas, den
returnerar standard [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) filtyp.


Om filen är krypterad och kräver ett lösenord för att öppnas, bör lösenordet anges som en parameter till detta
metod. Lösenordet kommer att användas för att dekryptera filen och analysera dess signatur för att bestämma filtypen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | stream | java.io.InputStream | Inmatningsflödet som representerar filen. |
|
|  | password | java.lang.String | Lösenordet för att öppna filen. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, ILogger logger) {#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, ILogger logger)
```


Detekterar filtypen genom att läsa filsignaturen.


Denna metod analyserar filsignaturen, som är en unik sekvens av byte i början av filen, för att bestämma
filtypen. Den läser filsignaturen från det angivna inmatningsflödet och matchar den mot kända filsignaturer
för stödda filtyper. Om en matchning hittas, returnerar metoden den motsvarande filtypen. Om ingen matchning hittas, den
returnerar standard [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) filtyp.


En logger kan tillhandahållas för att logga relevant information eller fel under filtypdetekteringsprocessen. Loggern
bör implementera ILogger-gränssnittet. Om ingen logger tillhandahålls, kommer detekteringsprocessen inte att producera någon
loggutdata.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | stream | java.io.InputStream | Inmatningsflödet som representerar filen. |
|
|  | logger | com.groupdocs.foundation.logging.ILogger | Loggern för att logga information eller fel. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, String password, ILogger logger) {#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, String password, ILogger logger)
```


Detekterar filtypen genom att läsa filsignaturen.


Denna metod analyserar filsignaturen, som är en unik sekvens av byte i början av filen, för att bestämma
filtypen. Den läser filsignaturen från det angivna inmatningsflödet och matchar den mot kända filsignaturer
för stödda filtyper. Om en matchning hittas, returnerar metoden den motsvarande filtypen. Om ingen matchning hittas, den
returnerar standard [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) filtyp.


Ett lösenord kan tillhandahållas om filen är krypterad eller skyddad. Lösenordet kommer att användas för att öppna filen innan
analys av filsignaturen. Om filen inte kräver ett lösenord, kan denna parameter sättas till null.


En logger kan tillhandahållas för att logga relevant information eller fel under filtypdetekteringsprocessen. Loggern
bör implementera ILogger-gränssnittet. Om ingen logger tillhandahålls, kommer detekteringsprocessen inte att producera någon
loggutdata.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | stream | java.io.InputStream | Inmatningsflödet som representerar filen. |
|
|  | password | java.lang.String | Lösenordet för att öppna filen. |
|
|  | logger | com.groupdocs.foundation.logging.ILogger | Loggern för att logga information eller fel. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Hämtar de stödjade filtyperna.


Denna metod returnerar en sekvens av alla stödda filtyper i systemet. Filtyperna representerar olika
dokumentformat som kan bearbetas eller kännas igen av systemet.
***Learn more**
* Learn more about the supported document formats: [Full list of supported file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/)*


**Returns:**
java.util.List<com.groupdocs.viewer.FileType> - en sekvens av stödda filtyper.

### detectCharset(String filePath) {#detectCharset-java.lang.String-}
```
public static Charset detectCharset(String filePath)
```


Försöker att identifiera teckenkodning för text [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV) och [CSV](../../com.groupdocs.viewer/filetype#CSV) filer via sökväg.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Filnamnet eller filsökvägen. |
|

**Returns:**
java.nio.charset.Charset - teckenkodning eller null när det misslyckas att upptäcka en fils teckenkodning.

**Example:**


Charset charset = FileType.detectCharset("message.txt");
     

### detectCharset(InputStream stream) {#detectCharset-java.io.InputStream-}
```
public static Charset detectCharset(InputStream stream)
```


Försöker att identifiera teckenkodning för text [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV) och [CSV](../../com.groupdocs.viewer/filetype#CSV) fil via ström.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | stream | java.io.InputStream | Filströmmen. |
|

**Returns:**
java.nio.charset.Charset - teckenkodning eller null när det misslyckas att upptäcka en fils teckenkodning.

**Example:**


InputStream stream = new FileInputStream("message.txt");
Charset charset = FileType.detectCharset(stream);
     

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Hämtar namn på filformatet, t.ex. "Microsoft Word Document".


**Returns:**
java.lang.String - namnet på dokumentformatet.

### getExtension() {#getExtension--}
```
public final String getExtension()
```


Hämtar filens filändelse (inklusive punkten "."), t.ex. ".doc".


**Returns:**
java.lang.String - filens filändelse.

### toString() {#toString--}
```
public String toString()
```


Returnerar en strängrepresentation av det aktuella objektet.


**Returns:**
java.lang.String - en strängrepresentation av det aktuella objektet.

