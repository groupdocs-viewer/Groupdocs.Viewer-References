---
title: "FileType"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Rappresenta il tipo di file."
type: docs
weight: 14
url: /it/nodejs-java/com.groupdocs.viewer/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, com.groupdocs.viewer.caching.Cacheable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>, Cacheable
```

Rappresenta il tipo di file. Fornisce metodi per ottenere un elenco di tutti i tipi di file supportati dal componente GroupDocs.Viewer.

L'enumerazione FileType fornisce costanti che rappresentano diversi tipi di file supportati dal componente GroupDocs.Viewer. È possibile utilizzare i metodi di questa enumerazione per ottenere un elenco di tutti i tipi di file supportati o verificare se un tipo di file specifico è supportato.

Esempio di utilizzo:

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
## Campi

| Campo | Descrizione |
| --- | --- |
| [UNKNOWN](#UNKNOWN) | Rappresenta un tipo di file sconosciuto. |
| [ZIP](#ZIP) | Rappresenta un file compresso (.zip) che può contenere uno o più file o directory. |
| [TAR](#TAR) | Rappresenta un archivio Unix consolidato (.tar) creato per raccogliere uno o più file. |
| [XZ](#XZ) | Rappresenta un file XZ (.xz) compresso utilizzando un algoritmo di compressione ad alto rapporto basato sull'algoritmo LZMA. |
| [TXZ](#TXZ) | Rappresenta un archivio Unix consolidato (.txz, .tar.xz) creato per raccogliere uno o più file. |
| [TARXZ](#TARXZ) | Rappresenta un archivio Unix consolidato (.txz, .tar.xz) creato per raccogliere uno o più file. |
| [TGZ](#TGZ) | Rappresenta un archivio Unix consolidato (.tgz, .tar.gz) creato per raccogliere uno o più file. |
| [TARGZ](#TARGZ) | Rappresenta un archivio Unix consolidato (.tgz, .tar.gz) creato per raccogliere uno o più file. |
| [BZ_2](#BZ-2) | Rappresenta un file compresso Bzip2 (.bz2) generato utilizzando il metodo di compressione open-source BZIP2. |
| [RAR](#RAR) | Rappresenta un file compresso Roshal Archive (.rar) generato utilizzando il metodo di compressione RAR (WINRAR versione 4). |
| [GZ](#GZ) | Rappresenta un file compresso Gnu Zipped (.gz) creato con l'applicazione di compressione gzip. |
| [GZIP](#GZIP) | Rappresenta un file Gnu Zipped (.gzip) compresso, introdotto come utility gratuito per sostituire il programma Compress utilizzato nei sistemi Unix. |
| [SEVEN_ZIP](#SEVEN-ZIP) | Rappresenta un file 7Zip (.7z, .7zip), che è un archiviatore gratuito open-source con compressione LZMA e LZMA2. |
| [CPIO](#CPIO) | Cpio è un'utilità generale di archiviazione di file e il relativo formato di file. |
| [ZSTANDARD](#ZSTANDARD) | Il file ZST è un file compresso generato con l'algoritmo di compressione Zstandard (zstd). |
| [TZST](#TZST) | I file TZST (.tar.zst, .tzst) sono archivi Zstandard (ZST), che contengono internamente un archivio Unix consolidato (Tar), creato con un'utilità basata su Unix per raccogliere uno o più file. |
| [TAR_ZST](#TAR-ZST) | I file TZST (.tar.zst, .tzst) sono archivi Zstandard (ZST), che contengono internamente un archivio Unix consolidato (Tar), creato con un'utilità basata su Unix per raccogliere uno o più file. |
| [ISO](#ISO) | L'immagine di disco ottico ISO è un file immagine di disco archivio non compresso che rappresenta il contenuto di tutti i dati su un disco ottico come CD o DVD, basato sullo standard ISO-9660. |
| [LHA](#LHA) | LHA o LZH è un'utilità di compressione freeware e il relativo formato di file. |
| [CAB](#CAB) | Cabinet (o CAB) è un formato di file archivio per Microsoft Windows. |
| [DXF](#DXF) | Rappresenta un file Drawing Exchange Format (.dxf), che è una rappresentazione di dati taggati di un file di disegno AutoCAD. |
| [DWG](#DWG) | Rappresenta un file AutoCAD Drawing Database (.dwg), che rappresenta file binari proprietari utilizzati per contenere dati di progettazione 2D e 3D. |
| [DWT](#DWT) | Rappresenta un modello di disegno AutoCAD (.dwt), che è un file modello di disegno AutoCAD usato come punto di partenza per creare disegni che possono essere salvati come file DWG. |
| [STL](#STL) | Rappresenta un file Stereolithography (.stl), che è un formato di file intercambiabile che rappresenta la geometria di superficie tridimensionale. |
| [IFC](#IFC) | Rappresenta un file Industry Foundation Classes (.ifc), che è un formato di file che stabilisce standard internazionali per l'importazione e l'esportazione di oggetti edilizi e delle loro proprietà. |
| [DWF](#DWF) | Rappresenta un file Design Web Format (.dwf), che è un formato di file compresso per visualizzare, revisionare o stampare disegni 2D/3D. |
| [FBX](#FBX) | Rappresenta un file Autodesk FBX Interchange (FilmBoX) (.fbx), che è un formato di modello 3D. |
| [DWFX](#DWFX) | Rappresenta un file Design Web Format XPS (.dwfx), che è un formato compresso per visualizzare, revisionare o stampare disegni 2D/3D come documento XPS. |
| [DGN](#DGN) | Rappresenta un file MicroStation Design (.dgn), che sono disegni creati e supportati da applicazioni CAD come MicroStation e Intergraph Interactive Graphics Design System. |
| [PLT](#PLT) | Rappresenta un file PLT (HPGL) (.plt), che è un file plotter basato su vettori introdotto da Autodesk, Inc. |
| [CF2](#CF2) | Rappresenta un file Common File Format (.cf2). |
| [OBJ](#OBJ) | Rappresenta un file Wavefront 3D Object (.obj), che è un file immagine 3D introdotto da Wavefront Technologies. |
| [HPG](#HPG) | Rappresenta un file PLT (HPGL) (.hpg). |
| [IGS](#IGS) | Rappresenta un file Initial Graphics Exchange Specification (IGES) (.igs). |
| [VSD](#VSD) | Rappresenta un file Visio Drawing (.vsd), che sono disegni creati con l'applicazione Microsoft Visio per rappresentare una varietà di oggetti grafici e le loro interconnessioni. |
| [VSDX](#VSDX) | Rappresenta un file Visio Drawing (.vsdx), che rappresenta il formato di file Microsoft Visio introdotto a partire da Microsoft Office 2013. |
| [VSS](#VSS) | Rappresenta un file Visio Stencil (.vss), che sono file stencil creati con Microsoft Visio 2007 e versioni precedenti. |
| [VSSX](#VSSX) | Rappresenta un file stencil Visio (.vssx), che sono stencil di disegno creati con Microsoft Visio 2013 e versioni successive. |
| [VSDM](#VSDM) | Rappresenta un disegno Visio con macro abilitati (.vsdm), che sono file di disegno creati con l'applicazione Microsoft Visio che supporta le macro. |
| [VST](#VST) | Rappresenta un modello di disegno Visio (.vst), che sono file di immagine vettoriale creati con Microsoft Visio. |
| [VSTX](#VSTX) | Rappresenta un modello di disegno Visio (.vstx), che sono file modello di disegno creati con Microsoft Visio 2013 e versioni successive. |
| [VSTM](#VSTM) | Rappresenta un modello di disegno Visio con macro abilitati (.vstm), che sono file modello creati con Microsoft Visio che supportano le macro. |
| [VSSM](#VSSM) | Rappresenta un file stencil Visio con macro abilitati (.vssm), che sono file stencil Microsoft Visio che supportano le macro. |
| [VSX](#VSX) | Rappresenta un file stencil XML Visio (.vsx), che si riferisce a stencil composti da disegni e forme utilizzati per creare diagrammi in Microsoft Visio. |
| [VTX](#VTX) | Rappresenta un file modello XML Visio (.vtx), che è un modello di disegno Microsoft Visio salvato su disco in formato file XML. |
| [VDW](#VDW) | Rappresenta un disegno web Visio (.vdw), che specifica i flussi e gli archivi necessari per il rendering di un disegno web. |
| [VDX](#VDX) | Rappresenta un file XML di disegno Visio (.vdx), che rappresenta qualsiasi disegno o grafico creato in Microsoft Visio ma salvato in formato XML con estensione .VDX. |
| [EPUB](#EPUB) | Rappresenta un file Open eBook (.epub), che è un formato di file e-book che fornisce un formato di pubblicazione digitale standard per editori e consumatori. |
| [MOBI](#MOBI) | Rappresenta un eBook Mobipocket (.mobi), che è uno dei formati di file ebook più ampiamente utilizzati. |
| [AZW_3](#AZW-3) | Il formato ebook Amazon Kindle 8 (KF8) è il formato di file digitale sviluppato per i dispositivi Amazon Kindle. |
| [MSG](#MSG) | Rappresenta un messaggio di posta Outlook (.msg), che è un formato di file utilizzato da Microsoft Outlook e Exchange per archiviare messaggi email, contatti, appuntamenti o altre attività. |
| [EML](#EML) | Rappresenta un messaggio e-mail (.eml), che rappresenta i messaggi email salvati utilizzando Outlook e altre applicazioni pertinenti. |
| [EMLX](#EMLX) | Rappresenta un messaggio di posta Apple (.emlx), che è implementato e sviluppato da Apple. |
| [PST](#PST) | Rappresenta un file Outlook Personal Information Store (.pst), che rappresenta i file di archiviazione personale di Outlook (chiamati anche Personal Storage Table) che memorizzano una varietà di informazioni dell'utente. |
| [OST](#OST) | Rappresenta un file dati offline Outlook (.ost), che rappresenta i dati della casella di posta di un utente in modalità offline su una macchina locale dopo la registrazione al server Exchange tramite Microsoft Outlook. |
| [TIF](#TIF) | Rappresenta un file Tagged Image (.tif), che rappresenta immagini raster destinate all'uso su una varietà di dispositivi che rispettano questo standard di formato file. |
| [TIFF](#TIFF) | Rappresenta un formato Tagged Image File (.tiff), che rappresenta immagini raster destinate all'uso su una varietà di dispositivi che rispettano questo standard di formato file. |
| [JPG](#JPG) | Rappresenta un'immagine JPEG (.jpg), che è un tipo di formato immagine salvato mediante compressione con perdita. |
| [JPEG](#JPEG) | Rappresenta un'immagine JPEG (.jpeg), che è un tipo di formato immagine salvato mediante compressione con perdita. |
| [JFIF](#JFIF) | Il JPEG File Interchange Format (.jfif) è un'immagine sviluppata per lo scambio rapido tra piattaforme. |
| [PNG](#PNG) | Rappresenta un Portable Network Graphic (.png), che è un tipo di formato file di immagine raster che utilizza compressione senza perdita. |
| [GIF](#GIF) | Rappresenta un file Graphical Interchange Format (.gif), che è un tipo di immagine altamente compressa. |
| [APNG](#APNG) | Rappresenta un Animated Portable Network Graphic (.apng), che è un'estensione del formato PNG che supporta l'animazione. |
| [BMP](#BMP) | Rappresenta un file Bitmap Image (.bmp), che è usato per memorizzare immagini digitali bitmap. |
| [ICO](#ICO) | Rappresenta un file Icon (.ico), che è un tipo di file immagine usato come icona per la rappresentazione di un'applicazione su Microsoft Windows. |
| [TGA](#TGA) | Rappresenta un file Truevision TGA (TARGA), che è usato per memorizzare immagini digitali bitmap sviluppate da TRUEVISION. |
| [JP_2](#JP-2) | Rappresenta un file JPEG 2000 Core Image (.jp2), che è un sistema di codifica delle immagini e uno standard di compressione delle immagini all'avanguardia. |
| [JPF](#JPF) | Rappresenta un file JPEG 2000 Image (.jpf). |
| [JPX](#JPX) | Rappresenta un file JPEG 2000 Image (.jpx). |
| [JPM](#JPM) | Rappresenta un file JPEG 2000 Image (.jpm). |
| [J2C](#J2C) | Rappresenta un JPEG 2000 Code InputStream (.j2c). |
| [J2K](#J2K) | Rappresenta un JPEG 2000 Code Stream (.j2k), che è un'immagine compressa usando la compressione wavelet invece della compressione DCT. |
| [JPC](#JPC) | Rappresenta un JPEG 2000 Code Stream (.jpc). |
| [JLS](#JLS) | Rappresenta un file JPEG-LS (JLS) (.jls). |
| [DIB](#DIB) | Rappresenta un file Device Independent Bitmap (.dib). |
| [WMF](#WMF) | Rappresenta un Windows Metafile (.wmf), che rappresenta il Microsoft Windows Metafile (WMF) per la memorizzazione di dati immagine in formato vettoriale e bitmap. |
| [WMZ](#WMZ) | Rappresenta un Compressed Windows Metafile (.wmz), che rappresenta il Microsoft Windows Metafile (WMF) compresso in archivio GZIP per la memorizzazione di dati immagine in formato vettoriale e bitmap. |
| [EMF](#EMF) | Rappresenta un Enhanced Windows Metafile (.emf), che rappresenta immagini grafiche indipendenti dal dispositivo. |
| [EMZ](#EMZ) | Rappresenta un Windows Compressed Enhanced Metafile (.emz), che rappresenta immagini grafiche indipendenti dal dispositivo compresse da GZIP. |
| [WEBP](#WEBP) | Rappresenta un'immagine WebP (.webp), che è un moderno formato di file immagine raster per il web basato su compressione senza perdita e con perdita. |
| [DNG](#DNG) | Rappresenta una Digital Negative Specification (.dng), che è un formato di immagine per fotocamere digitali usato per la memorizzazione di file raw. |
| [CDR](#CDR) | Rappresenta un CorelDraw Vector Graphic Drawing (.cdr), che è un file immagine di disegno vettoriale creato nativamente con CorelDRAW per la memorizzazione di immagini codificate e compresse digitalmente. |
| [CMX](#CMX) | Rappresenta un Corel Exchange (.cmx), che è un file immagine di disegno che può contenere grafica vettoriale così come grafica bitmap. |
| [DJVU](#DJVU) | Rappresenta un'immagine DjVu (.djvu), che è un formato di file grafico destinato a documenti e libri scansionati, specialmente quelli contenenti una combinazione di testo, disegni, immagini e fotografie. |
| [CGM](#CGM) | Rappresenta un Computer Graphics Metafile (.cgm), che è un formato metafile gratuito, indipendente dalla piattaforma, standard internazionale per la memorizzazione e lo scambio di grafica vettoriale (2D), grafica raster e testo. |
| [PCL](#PCL) | Rappresenta un documento Printer Command Language (.pcl). |
| [PSD](#PSD) | Rappresenta un Adobe Photoshop Document (.psd), che è il formato file nativo di Adobe Photoshop usato per la progettazione e lo sviluppo grafico. |
| [PSB](#PSB) | Rappresenta un Photoshop Large Document Format (.psb), che è usato per la progettazione e lo sviluppo grafico in Adobe Photoshop. |
| [DCM](#DCM) | Rappresenta un'immagine DICOM (.dcm), che rappresenta un'immagine digitale che memorizza informazioni mediche dei pazienti come MRIs, CT scans e ultrasound images. |
| [PS](#PS) | Rappresenta un file PostScript (.ps). |
| [EPS](#EPS) | Rappresenta un file Encapsulated PostScript (.eps), che descrive un programma di linguaggio Encapsulated PostScript che definisce l'aspetto di una singola pagina. |
| [ODG](#ODG) | Rappresenta un file OpenDocument Graphic (.odg), che è usato dall'applicazione Draw di Apache OpenOffice per memorizzare gli elementi di disegno come immagine vettoriale. |
| [FODG](#FODG) | Rappresenta un modello Flat XML ODF (.fodg), che è usato dall'applicazione Draw di Apache OpenOffice per memorizzare gli elementi di disegno come immagine vettoriale. |
| [SVG](#SVG) | Rappresenta un file Scalable Vector Graphics (.svg), che è un file Scalar Vector Graphics che utilizza un formato di testo basato su XML per descrivere l'aspetto di un'immagine. |
| [SVGZ](#SVGZ) | Rappresenta un file Compressed Scalable Vector Graphics (.svgz), che è un file Scalar Vector Graphics che utilizza un formato di testo basato su XML, compresso con GZIP, per descrivere l'aspetto di un'immagine. |
| [OTG](#OTG) | Rappresenta un modello OpenDocument Graphic (.otg). |
| [HTM](#HTM) | Rappresenta un file Hypertext Markup Language (.htm), che è l'estensione per le pagine web create per la visualizzazione nei browser. |
| [HTML](#HTML) | Rappresenta un file Hypertext Markup Language (.html), che è l'estensione per le pagine web create per la visualizzazione nei browser. |
| [MHT](#MHT) | Rappresenta un archivio web MHTML (.mht). |
| [NSF](#NSF) | Rappresenta un database Lotus Notes (.nsf). |
| [MBOX](#MBOX) | Rappresenta un file casella di posta elettronica (.mbox). |
| [MHTML](#MHTML) | Rappresenta un file MIME HTML (.mhtml). |
| [XML](#XML) | Rappresenta un file XML (.xml). |
| [ONE](#ONE) | Rappresenta un documento OneNote (.one) creato dall'applicazione Microsoft OneNote. |
| [PDF](#PDF) | Rappresenta un file Portable Document Format (.pdf), che è un tipo di documento creato da Adobe negli anni '90. |
| [XPS](#XPS) | Rappresenta un file XML Paper Specification (.xps), che rappresenta file di layout di pagina basati su XML Paper Specifications creati da Microsoft. |
| [OXPS](#OXPS) | Rappresenta un file OpenXPS (.oxps). |
| [TEX](#TEX) | Rappresenta un documento sorgente LaTeX (.tex), che è un linguaggio che comprende funzionalità di programmazione e di markup utilizzate per la composizione tipografica dei documenti. |
| [PPT](#PPT) | Rappresenta una presentazione PowerPoint (.ppt), che rappresenta un file PowerPoint composto da una raccolta di diapositive da visualizzare come presentazione. |
| [PPTX](#PPTX) | Rappresenta una presentazione PowerPoint Open XML (.pptx), che sono file di presentazione creati con la popolare applicazione Microsoft PowerPoint. |
| [PPS](#PPS) | Rappresenta uno slide show PowerPoint (.pps), che è creato usando Microsoft PowerPoint per scopi di presentazione. |
| [PPSX](#PPSX) | Rappresenta dei file PowerPoint Open XML Slide Show (.ppsx), che sono creati usando Microsoft PowerPoint 2007 e versioni successive per scopi di presentazione. |
| [ODP](#ODP) | Rappresenta una presentazione OpenDocument (.odp), che rappresenta un formato di file di presentazione usato da OpenOffice.org nello standard OASISOpen. |
| [FODP](#FODP) | Rappresenta una presentazione OpenDocument (.fodp), che rappresenta la presentazione OpenDocument Flat XML. |
| [POT](#POT) | Rappresenta un modello PowerPoint (.pot), che rappresenta i file modello di Microsoft PowerPoint creati dalle versioni PowerPoint 97-2003. |
| [PPTM](#PPTM) | Rappresenta una presentazione PowerPoint Open XML con macro abilitata (.pptm), che sono file di presentazione con macro creati con Microsoft PowerPoint 2007 o versioni successive. |
| [POTX](#POTX) | Rappresenta un modello di presentazione PowerPoint Open XML (.potx), che rappresenta le presentazioni modello di Microsoft PowerPoint create con Microsoft PowerPoint 2007 e versioni successive. |
| [POTM](#POTM) | Rappresenta un modello di presentazione PowerPoint Open XML con macro abilitata (.potm), che sono file modello di Microsoft PowerPoint con supporto per macro. |
| [PPSM](#PPSM) | Rappresenta una diapositiva PowerPoint Open XML con macro abilitata (.ppsm), che rappresenta un formato di file di presentazione con macro creato con Microsoft PowerPoint 2007 o versioni successive. |
| [OTP](#OTP) | Rappresenta un modello di presentazione OpenDocument (.otp), che rappresenta i file modello di presentazione creati dalle applicazioni nel formato standard OASIS OpenDocument. |
| [XLS](#XLS) | Rappresenta un foglio di calcolo Excel (.xls), che rappresenta il formato di file binario di Excel. |
| [EXCEL_2003_XML](#EXCEL-2003-XML) | Rappresenta un XML Excel 2003 (SpreadsheetML) (.xml), che rappresenta il formato di file binario di Excel. |
| [NUMBERS](#NUMBERS) | Rappresenta Apple Numbers (.numbers), che rappresenta un formato di file binario simile a Excel. |
| [XLSX](#XLSX) | Rappresenta un foglio di calcolo Microsoft Excel Open XML (.xlsx), che è un formato noto per i documenti Microsoft Excel introdotto da Microsoft con il rilascio di Microsoft Office 2007. |
| [XLSM](#XLSM) | Rappresenta un foglio di calcolo Excel Open XML con macro abilitata (.xlsm), che è un tipo di file di foglio di calcolo che supporta le macro. |
| [XLSB](#XLSB) | Rappresenta un foglio di calcolo binario Excel (.xlsb), che specifica il formato di file binario di Excel. |
| [CSV](#CSV) | Rappresenta un file di valori separati da virgola (.csv), che rappresenta file di testo semplice contenenti record di dati con valori separati da virgola. |
| [TSV](#TSV) | Rappresenta un file di valori separati da tabulazione (.tsv), che rappresenta dati separati da tabulazioni in formato di testo semplice. |
| [ODS](#ODS) | Rappresenta un foglio di calcolo OpenDocument (.ods), che indica il formato di documento foglio di calcolo OpenDocument modificabile dall'utente. |
| [FODS](#FODS) | Rappresenta un foglio di calcolo OpenDocument Flat XML (.fods). |
| [OTS](#OTS) | Rappresenta un modello di foglio di calcolo OpenDocument (.ots). |
| [XLAM](#XLAM) | Rappresenta un componente aggiuntivo Microsoft Excel (.xlam). |
| [XLTM](#XLTM) | Rappresenta un modello Microsoft Excel con macro abilitata (.xltm), che rappresenta i file generati da Microsoft Excel come file modello con macro. |
| [XLT](#XLT) | Rappresenta un modello Microsoft Excel (.xlt), che sono file modello creati con Microsoft Excel, un'applicazione di foglio di calcolo inclusa nella suite Microsoft Office. |
| [XLTX](#XLTX) | Rappresenta un modello di foglio di calcolo Excel Open XML (.xltx), che rappresenta i modelli Microsoft Excel basati sulle specifiche del formato file Office OpenXML. |
| [SXC](#SXC) | Rappresenta un foglio di calcolo StarOffice Calc (.sxc). |
| [MPP](#MPP) | Rappresenta un file Microsoft Project (.mpp), che è un file di dati Microsoft Project che memorizza informazioni relative alla gestione dei progetti in modo integrato. |
| [MPT](#MPT) | Rappresenta un modello di Microsoft Project (.mpt), che contiene informazioni di base e struttura insieme alle impostazioni del documento per la creazione di file .MPP. |
| [MPX](#MPX) | Rappresenta un file Microsoft Project Exchange (.mpx), che è un formato di file ASCII per il trasferimento di informazioni di progetto tra Microsoft Project (MSP) e altre applicazioni che supportano il formato file MPX, come Primavera Project Planner, Sciforma e Timerline Precision Estimating. |
| [AS](#AS) | Rappresenta un file ActionScript (.as). |
| [AS_3](#AS-3) | Rappresenta un file ActionScript (.as3). |
| [ASM](#ASM) | Rappresenta un file di codice sorgente Assembly (.asm). |
| [BAT](#BAT) | Rappresenta un file batch DOS (.bat). |
| [C](#C) | Rappresenta un file di codice sorgente C/C++ (.c). |
| [CC](#CC) | Rappresenta un file di codice sorgente C++ (.cc). |
| [CMAKE](#CMAKE) | Rappresenta un file CMake (.cmake). |
| [CPP](#CPP) | Rappresenta un file di codice sorgente C++ (.cpp). |
| [CS](#CS) | Rappresenta un file di codice sorgente C\# (.cs), che è un file di codice sorgente per il linguaggio di programmazione C\#. |
| [VB](#VB) | Rappresenta un file di progetto Visual Basic (.vb), che è un file di codice sorgente creato nel linguaggio Visual Basic. |
| [CSS](#CSS) | Rappresenta un file Cascading Style Sheet (.css). |
| [CXX](#CXX) | Rappresenta un file di codice sorgente C++ (.cxx). |
| [DIFF](#DIFF) | Rappresenta un file patch (.diff). |
| [ERB](#ERB) | Rappresenta uno script Ruby ERB (.erb). |
| [GROOVY](#GROOVY) | Rappresenta un file di codice sorgente Groovy (.groovy). |
| [H](#H) | Rappresenta un file header C/C++/Objective-C (.h). |
| [HAML](#HAML) | Rappresenta un file di codice sorgente Haml (.haml). |
| [HH](#HH) | Rappresenta un file header C++ (.hh). |
| [JAVA](#JAVA) | Rappresenta un file di codice sorgente Java (.java). |
| [JS](#JS) | Rappresenta un file JavaScript (.js). |
| [JSON](#JSON) | Rappresenta un file JavaScript Object Notation (.json). |
| [LESS](#LESS) | Rappresenta un file LESS Style Sheet (.less). |
| [LOG](#LOG) | Rappresenta un file di log (.log). |
| [M](#M) | Rappresenta un file di implementazione Objective-C (.m). |
| [MAKE](#MAKE) | Rappresenta uno script Makefile Xcode (.make). |
| [MD](#MD) | Rappresenta un file di documentazione Markdown (.md). |
| [ML](#ML) | Rappresenta un file di codice sorgente ML (.ml). |
| [MM](#MM) | Rappresenta un file di codice sorgente Objective-C++ (.mm). |
| [PHP](#PHP) | Rappresenta un file di codice sorgente PHP (.php). |
| [PL](#PL) | Rappresenta uno script Perl (.pl). |
| [PROPERTIES](#PROPERTIES) | Rappresenta un file di proprietà Java (.properties). |
| [PY](#PY) | Rappresenta uno script Python (.py). |
| [RB](#RB) | Rappresenta un file di codice sorgente Ruby (.rb). |
| [RST](#RST) | Rappresenta un file reStructuredText (.rst). |
| [SASS](#SASS) | Rappresenta un file Syntactically Awesome StyleSheets (.sass). |
| [SCALA](#SCALA) | Rappresenta un file di codice sorgente Scala (.scala). |
| [SCM](#SCM) | Rappresenta un file di codice sorgente Scheme (.scm). |
| [SCRIPT](#SCRIPT) | Rappresenta un file di script generico (.script). |
| [SH](#SH) | Rappresenta uno script Bash Shell (.sh). |
| [SML](#SML) | Rappresenta un file di codice sorgente Standard ML (.sml). |
| [SQL](#SQL) | Rappresenta un file dati Structured Query Language (.sql). |
| [VIM](#VIM) | Rappresenta un file di impostazioni Vim (.vim). |
| [YAML](#YAML) | Rappresenta un documento YAML (.yaml). |
| [DOC](#DOC) | Rappresenta un file documento Microsoft Word (.doc). |
| [DOCX](#DOCX) | Rappresenta un file documento Microsoft Word Open XML (.docx). |
| [CHM](#CHM) | Rappresenta un file Microsoft Compiled HTML Help (.chm). |
| [DOCM](#DOCM) | Rappresenta un file documento Word Open XML Macro-Enabled (.docm). |
| [DOT](#DOT) | Rappresenta un file modello di documento Word (.dot). |
| [DOTX](#DOTX) | Rappresenta un file modello di documento Word Open XML (.dotx). |
| [DOTM](#DOTM) | Rappresenta un file modello di documento Word Open XML con macro abilitata (.dotm). |
| [RTF](#RTF) | Rappresenta un file Rich Text Format (.rtf). |
| [TXT](#TXT) | Rappresenta un file di testo semplice (.txt). |
| [ODT](#ODT) | Rappresenta un documento di testo OpenDocument (.odt). |
| [OTT](#OTT) | Rappresenta un modello di documento OpenDocument (.ott). |
| [VCF](#VCF) | Rappresenta un file vCard (.vcf), che è un formato di file digitale per memorizzare le informazioni di contatto. |
| [AI](#AI) | Rappresenta un file Adobe Illustrator (.ai), che è un formato di file per disegni Adobe Illustrator. |
| [PSM1](#PSM1) | Rappresenta un file modulo script PowerShell (.psm1). |
| [PS1](#PS1) | Rappresenta un file script PowerShell (.ps1). |
| [PSD1](#PSD1) | Rappresenta un file manifesto del modulo script PowerShell (.psd1). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Mappa un'estensione di file a un tipo di file. |
| [fromFilePath(String filePath)](#fromFilePath-java.lang.String-) | Estrae l'estensione del file da un nome file o da un percorso file e la mappa a un tipo di file. |
| [fromMediaType(String mediaType)](#fromMediaType-java.lang.String-) | Mappa un tipo di media del file a un tipo di file. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Rileva il tipo di file leggendo la firma del file. |
| [fromStream(InputStream stream, String password)](#fromStream-java.io.InputStream-java.lang.String-) | Rileva il tipo di file leggendo la firma del file. |
| [fromStream(InputStream stream, ILogger logger)](#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-) | Rileva il tipo di file leggendo la firma del file. |
| [fromStream(InputStream stream, String password, ILogger logger)](#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-) | Rileva il tipo di file leggendo la firma del file. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | Recupera i tipi di file supportati. |
| [detectCharset(String filePath)](#detectCharset-java.lang.String-) | Tenta di rilevare la codifica dei file di testo [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) e [CSV](../../com.groupdocs.viewer/filetype\#CSV) per percorso. |
| [detectCharset(InputStream stream)](#detectCharset-java.io.InputStream-) | Tenta di rilevare la codifica dei file di testo [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) e [CSV](../../com.groupdocs.viewer/filetype\#CSV) per flusso. |
| [getFileFormat()](#getFileFormat--) | Ottiene il nome del formato file, ad esempio "Microsoft Word Document". |
| [getExtension()](#getExtension--) | Ottiene il suffisso dell'estensione del file (incluso il punto "."), ad esempio ".doc". |
| [toString()](#toString--) | Restituisce una rappresentazione stringa dell'oggetto corrente. |
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Rappresenta un tipo di file sconosciuto.

### ZIP {#ZIP}
```
public static final FileType ZIP
```


Rappresenta un file compresso (.zip) che può contenere uno o più file o directory. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/compression/zip

### TAR {#TAR}
```
public static final FileType TAR
```


Rappresenta un archivio Unix consolidato (.tar) creato per raccogliere uno o più file. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/compression/tar

### XZ {#XZ}
```
public static final FileType XZ
```


Rappresenta un file XZ (.xz) compresso usando un algoritmo di compressione ad alto rapporto basato sull'algoritmo LZMA. Scopri di più su questo formato di file [qui][].


[here]: https://fileinfo.com/extension/xz

### TXZ {#TXZ}
```
public static final FileType TXZ
```


Rappresenta un archivio Unix consolidato (.txz, .tar.xz) creato per raccogliere uno o più file. Scopri di più su questo formato di file [qui][].


[here]: https://fileinfo.com/extension/txz

### TARXZ {#TARXZ}
```
public static final FileType TARXZ
```


Rappresenta un archivio Unix consolidato (.txz, .tar.xz) creato per raccogliere uno o più file. Scopri di più su questo formato di file [qui][].


[here]: https://fileinfo.com/extension/txz

### TGZ {#TGZ}
```
public static final FileType TGZ
```


Rappresenta un archivio Unix consolidato (.tgz, .tar.gz) creato per raccogliere uno o più file. Scopri di più su questo formato di file [qui][].


[here]: https://fileinfo.com/extension/tgz

### TARGZ {#TARGZ}
```
public static final FileType TARGZ
```


Rappresenta un archivio Unix consolidato (.tgz, .tar.gz) creato per raccogliere uno o più file. Scopri di più su questo formato di file [qui][].


[here]: https://fileinfo.com/extension/tgz

### BZ_2 {#BZ-2}
```
public static final FileType BZ_2
```


Rappresenta un file compresso Bzip2 (.bz2) generato utilizzando il metodo di compressione open-source BZIP2. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/compression/bz2

### RAR {#RAR}
```
public static final FileType RAR
```


Rappresenta un file compresso Roshal Archive (.rar) generato utilizzando il metodo di compressione RAR (WINRAR versione 4). Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/compression/rar

### GZ {#GZ}
```
public static final FileType GZ
```


Rappresenta un file compresso Gnu Zipped File (.gz) creato con l'applicazione di compressione gzip. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/compression/gz

### GZIP {#GZIP}
```
public static final FileType GZIP
```


Rappresenta un file compresso Gnu Zipped File (.gzip) introdotto come utility gratuita per sostituire il programma Compress utilizzato nei sistemi Unix. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/compression/gz

### SEVEN_ZIP {#SEVEN-ZIP}
```
public static final FileType SEVEN_ZIP
```


Rappresenta un file 7Zip (.7z, .7zip), che è un archiviatore open-source gratuito con compressione LZMA e LZMA2. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/compression/7z/

### CPIO {#CPIO}
```
public static final FileType CPIO
```


Cpio è un'utilità di archiviazione di file generica e il relativo formato di file. È principalmente installata sui sistemi operativi computer di tipo Unix. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/compression/cpio

### ZSTANDARD {#ZSTANDARD}
```
public static final FileType ZSTANDARD
```


Il file ZST è un file compresso generato con l'algoritmo di compressione Zstandard (zstd). È un file compresso creato con compressione senza perdita dell'algoritmo. I file ZST possono essere usati per comprimere diversi tipi di file come database, file system, reti e giochi. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/compression/zst/

### TZST {#TZST}
```
public static final FileType TZST
```


I file TZST (.tar.zst, .tzst) sono archivi Zstandard (ZST), che contengono internamente un archivio Unix consolidato (Tar), creato con un'utilità basata su Unix per raccogliere uno o più file.

### TAR_ZST {#TAR-ZST}
```
public static final FileType TAR_ZST
```


I file TZST (.tar.zst, .tzst) sono archivi Zstandard (ZST), che contengono internamente un archivio Unix consolidato (Tar), creato con un'utilità basata su Unix per raccogliere uno o più file.

### ISO {#ISO}
```
public static final FileType ISO
```


L'immagine disco ottico ISO è un file immagine di archivio non compresso che rappresenta il contenuto di tutti i dati su un disco ottico come CD o DVD, basato sullo standard ISO-9660. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/compression/iso/

### LHA {#LHA}
```
public static final FileType LHA
```


LHA o LZH è un'utilità di compressione freeware e il relativo formato di file. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/compression/lzh/

### CAB {#CAB}
```
public static final FileType CAB
```


Cabinet (o CAB) è un formato di file archivio per Microsoft Windows. Scopri di più su questo formato di file [here][].


[here]: https://en.wikipedia.org/wiki/Cabinet_%28file_format%29

### DXF {#DXF}
```
public static final FileType DXF
```


Rappresenta un file Drawing Exchange Format (.dxf), che è una rappresentazione di dati etichettati di un file di disegno AutoCAD. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/cad/dxf

### DWG {#DWG}
```
public static final FileType DWG
```


Rappresenta un file AutoCAD Drawing Database (.dwg), che rappresenta file binari proprietari utilizzati per contenere dati di progettazione 2D e 3D. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/cad/dwg

### DWT {#DWT}
```
public static final FileType DWT
```


Rappresenta un modello di disegno AutoCAD (.dwt), che è un file modello di disegno AutoCAD usato come punto di partenza per creare disegni che possono essere salvati come file DWG. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/cad/dwt

### STL {#STL}
```
public static final FileType STL
```


Rappresenta un file Stereolithography (.stl), che è un formato di file intercambiabile che rappresenta la geometria di superficie tridimensionale. È comunemente usato nella prototipazione rapida, stampa 3D e nella produzione assistita da computer. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/cad/stl

### IFC {#IFC}
```
public static final FileType IFC
```


Rappresenta un file Industry Foundation Classes (.ifc), che è un formato di file che stabilisce standard internazionali per l'importazione ed esportazione di oggetti edilizi e le loro proprietà. Consente l'interoperabilità tra diverse applicazioni software. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/cad/ifc

### DWF {#DWF}
```
public static final FileType DWF
```


Rappresenta un file Design Web Format (.dwf), che è un formato di file compresso per visualizzare, revisionare o stampare disegni 2D/3D. Contiene grafica e testo come parte dei dati di progetto e riduce la dimensione del file grazie alla compressione. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/cad/dwf

### FBX {#FBX}
```
public static final FileType FBX
```


Rappresenta un file Autodesk FBX Interchange (FilmBoX) (.fbx), che è un formato di modello 3D. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/cad/fbx

### DWFX {#DWFX}
```
public static final FileType DWFX
```


Rappresenta un file Design Web Format XPS (.dwfx), che è un formato compresso per visualizzare, revisionare o stampare disegni 2D/3D come documento XPS. Contiene grafica e testo come parte dei dati di progetto e riduce la dimensione del file grazie alla compressione. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/cad/dwfx

### DGN {#DGN}
```
public static final FileType DGN
```


Rappresenta un file MicroStation Design (.dgn), che sono disegni creati e supportati da applicazioni CAD come MicroStation e Intergraph Interactive Graphics Design System. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/cad/dgn

### PLT {#PLT}
```
public static final FileType PLT
```


Rappresenta un file PLT (HPGL) (.plt), che è un file plotter basato su vettori introdotto da Autodesk, Inc. Contiene informazioni per un determinato file CAD e tutte le immagini vengono stampate usando linee invece di punti, garantendo accuratezza e precisione nella produzione. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/cad/plt

### CF2 {#CF2}
```
public static final FileType CF2
```


Rappresenta un file Common File Format (.cf2). Scopri di più su questo formato di file [here][].


[here]: https://fileinfo.com/extension/cf2

### OBJ {#OBJ}
```
public static final FileType OBJ
```


Rappresenta un file Wavefront 3D Object (.obj), che è un file immagine 3D introdotto da Wavefront Technologies. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/3d/obj/

### HPG {#HPG}
```
public static final FileType HPG
```


Rappresenta un file PLT (HPGL) (.hpg). È un formato di file utilizzato per i file plotter nel linguaggio HP Graphics (HPGL). Scopri di più su questo formato di file [here][].


[here]: https://fileinfo.com/extension/hpg

### IGS {#IGS}
```
public static final FileType IGS
```


Rappresenta un file Initial Graphics Exchange Specification (IGES) (.igs).

### VSD {#VSD}
```
public static final FileType VSD
```


Rappresenta un file Visio Drawing (.vsd), che sono disegni creati con l'applicazione Microsoft Visio per rappresentare una varietà di oggetti grafici e le loro interconnessioni. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/image/vsd

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Rappresenta un file Visio Drawing (.vsdx), che rappresenta il formato di file Microsoft Visio introdotto a partire da Microsoft Office 2013. Ha sostituito il formato di file binario (.VSD) supportato dalle versioni precedenti di Microsoft Visio. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/image/vsdx

### VSS {#VSS}
```
public static final FileType VSS
```


Rappresenta un file Visio Stencil (.vss), che sono file stencil creati con Microsoft Visio 2007 e versioni precedenti. I file stencil forniscono oggetti di disegno che possono essere inclusi in un disegno Visio .VSD. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/image/vss

### VSSX {#VSSX}
```
public static final FileType VSSX
```


Rappresenta un file Visio Stencil (.vssx), che sono stencil di disegno creati con Microsoft Visio 2013 e versioni successive. Il formato di file VSSX può essere aperto con Visio 2013 e versioni successive. I file Visio sono noti per rappresentare una varietà di elementi di disegno come forme, connettori, diagrammi di flusso, layout di rete, diagrammi UML, ecc. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/image/vssx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Rappresenta un disegno Visio con macro abilitata (.vsdm), che sono file di disegno creati con l'applicazione Microsoft Visio che supportano macro. I file VSDM sono disegni OPC/XML simili a VSDX, ma offrono anche la possibilità di eseguire macro quando il file viene aperto. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/image/vsdm

### VST {#VST}
```
public static final FileType VST
```


Rappresenta un modello di disegno Visio (.vst), che sono file immagine vettoriali creati con Microsoft Visio. Funzionano come modelli per creare ulteriori file e contengono il layout predefinito e le impostazioni utilizzate per creare nuovi disegni Visio. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/image/vst

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Rappresenta un modello di disegno Visio (.vstx), che sono file modello di disegno creati con Microsoft Visio 2013 e versioni successive. Questi file VSTX forniscono un punto di partenza per creare disegni Visio salvati come file .VSDX, con layout e impostazioni predefinite. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Rappresenta un modello di disegno Visio con macro abilitata (.vstm), che sono file modello creati con Microsoft Visio che supportano macro. I file creati da modelli VSTM possono eseguire macro sviluppate in codice Visual Basic for Applications (VBA). Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Rappresenta un file Visio Stencil con macro abilitata (.vssm), che sono file Stencil di Microsoft Visio che supportano macro. Quando un file VSSM viene aperto, è possibile eseguire macro per ottenere la formattazione e il posizionamento desiderati delle forme in un diagramma. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Rappresenta un file Visio Stencil XML (.vsx), che si riferisce a stencil composti da disegni e forme utilizzati per creare diagrammi in Microsoft Visio. I file VSX sono salvati in formato XML e sono stati supportati fino a Visio 2013. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


Rappresenta un file Visio Template XML (.vtx), che è un modello di disegno Microsoft Visio salvato su disco in formato XML. Il modello fornisce impostazioni di base per creare più file Visio con le stesse impostazioni. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/image/vtx

### VDW {#VDW}
```
public static final FileType VDW
```


Rappresenta un disegno Web Visio (.vdw), che specifica i flussi e gli archivi necessari per il rendering di un disegno web. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/web/vdw

### VDX {#VDX}
```
public static final FileType VDX
```


Rappresenta un file XML di disegno Visio (.vdx), che rappresenta qualsiasi disegno o diagramma creato in Microsoft Visio ma salvato in formato XML con estensione .VDX. Un file XML di disegno Visio viene creato nel software Visio sviluppato da Microsoft. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Rappresenta un file Open eBook (.epub), che è un formato di file e‑book che fornisce un formato di pubblicazione digitale standard per editori e consumatori. Il formato è supportato da molti e‑reader e applicazioni software. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/ebook/epub

### MOBI {#MOBI}
```
public static final FileType MOBI
```


Rappresenta un eBook Mobipocket (.mobi), che è uno dei formati di file ebook più diffusi. Il formato è un miglioramento del vecchio formato OEB (Open Ebook Format) ed è stato usato come formato proprietario per Mobipocket Reader. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/ebook/mobi

### AZW_3 {#AZW-3}
```
public static final FileType AZW_3
```


L'ebook Amazon Kindle Format 8 (KF8) è il formato di file digitale sviluppato per i dispositivi Amazon Kindle. Il formato è un miglioramento dei vecchi file AZW ed è usato sui dispositivi Kindle Fire solo con compatibilità retroattiva per i formati di file precedenti, cioè MOBI e AZW. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/ebook/azw3

### MSG {#MSG}
```
public static final FileType MSG
```


Rappresenta un messaggio di posta Outlook (.msg), che è un formato di file utilizzato da Microsoft Outlook e Exchange per archiviare messaggi email, contatti, appuntamenti o altre attività. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/email/msg

### EML {#EML}
```
public static final FileType EML
```


Rappresenta un messaggio di posta elettronica (.eml), che rappresenta messaggi email salvati usando Outlook e altre applicazioni pertinenti. Quasi tutti i client di posta supportano questo formato di file grazie alla sua conformità allo standard RFC-822 Internet Message Format. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/email/eml

### EMLX {#EMLX}
```
public static final FileType EMLX
```


Rappresenta un messaggio di posta Apple Mail (.emlx), che è implementato e sviluppato da Apple. L'applicazione Apple Mail utilizza il formato di file EMLX per esportare le email. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/email/emlx

### PST {#PST}
```
public static final FileType PST
```


Rappresenta un file Outlook Personal Information Store (.pst), che rappresenta i file di archiviazione personale di Outlook (chiamati anche Personal Storage Table) che memorizzano una varietà di informazioni dell'utente. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/email/pst

### OST {#OST}
```
public static final FileType OST
```


Rappresenta un file Outlook Offline Data (.ost), che rappresenta i dati della casella di posta di un utente in modalità offline su una macchina locale dopo la registrazione al server Exchange tramite Microsoft Outlook. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/email/ost

### TIF {#TIF}
```
public static final FileType TIF
```


Rappresenta un file Tagged Image (.tif), che rappresenta immagini raster destinate all'uso su una varietà di dispositivi che rispettano questo standard di formato file. È in grado di descrivere dati immagine bi‑livello, in scala di grigi, a palette di colori e a colori completi in diversi spazi colore. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/tiff

### TIFF {#TIFF}
```
public static final FileType TIFF
```


Rappresenta un file Tagged Image Format (.tiff), che rappresenta immagini raster destinate all'uso su una varietà di dispositivi che rispettano questo standard di formato file. È in grado di descrivere dati immagine bi‑livello, in scala di grigi, a palette di colori e a colori completi in diversi spazi colore. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/tiff

### JPG {#JPG}
```
public static final FileType JPG
```


Rappresenta un'immagine JPEG (.jpg), che è un tipo di formato immagine salvato mediante compressione con perdita. L'immagine risultante, a seguito della compressione, è un compromesso tra dimensione di archiviazione e qualità dell'immagine. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/jpeg

### JPEG {#JPEG}
```
public static final FileType JPEG
```


Rappresenta un'immagine JPEG (.jpeg), che è un tipo di formato immagine salvato mediante compressione con perdita. L'immagine risultante, a seguito della compressione, è un compromesso tra dimensione di archiviazione e qualità dell'immagine. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/jpeg

### JFIF {#JFIF}
```
public static final FileType JFIF
```


Il JPEG File Interchange Format (.jfif) è un'immagine sviluppata per lo scambio rapido tra piattaforme. Questo formato utilizza la compressione JPEG. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/jfif

### PNG {#PNG}
```
public static final FileType PNG
```


Rappresenta un Portable Network Graphic (.png), che è un tipo di formato di file immagine raster che utilizza compressione senza perdita. Questo formato di file è stato creato come sostituto del Graphics Interchange Format (GIF) e non ha limitazioni di copyright. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/png

### GIF {#GIF}
```
public static final FileType GIF
```


Rappresenta un Graphical Interchange Format File (.gif), che è un tipo di immagine altamente compressa. Per ogni immagine, GIF consente tipicamente fino a 8 bit per pixel e fino a 256 colori sono consentiti nell'intera immagine. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/gif

### APNG {#APNG}
```
public static final FileType APNG
```


Rappresenta un Animated Portable Network Graphic (.apng), che è un'estensione del formato PNG che supporta l'animazione. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/apng

### BMP {#BMP}
```
public static final FileType BMP
```


Rappresenta un Bitmap Image File (.bmp), che è usato per memorizzare immagini bitmap digitali. Queste immagini sono indipendenti dall'adattatore grafico e sono anche chiamate formato file device independent bitmap (DIB). Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/bmp

### ICO {#ICO}
```
public static final FileType ICO
```


Rappresenta un Icon File (.ico), che è un tipo di file immagine usato come icona per la rappresentazione di un'applicazione su Microsoft Windows. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/ico

### TGA {#TGA}
```
public static final FileType TGA
```


Rappresenta un file Truevision TGA (TARGA), che è usato per memorizzare immagini bitmap digitali sviluppate da TRUEVISION. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/tga

### JP_2 {#JP-2}
```
public static final FileType JP_2
```


Rappresenta un JPEG 2000 Core Image File (.jp2), che è un sistema di codifica delle immagini e uno standard di compressione delle immagini all'avanguardia. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/jp2

### JPF {#JPF}
```
public static final FileType JPF
```


Rappresenta un JPEG 2000 Image File (.jpf). Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/image/jpf

### JPX {#JPX}
```
public static final FileType JPX
```


Rappresenta un JPEG 2000 Image File (.jpx). Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/jpx

### JPM {#JPM}
```
public static final FileType JPM
```


Rappresenta un JPEG 2000 Image File (.jpm). Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/jpm

### J2C {#J2C}
```
public static final FileType J2C
```


Rappresenta un JPEG 2000 Code InputStream (.j2c). Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/j2c

### J2K {#J2K}
```
public static final FileType J2K
```


Rappresenta un JPEG 2000 Code Stream (.j2k), che è un'immagine compressa usando la compressione wavelet invece della compressione DCT. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/j2k

### JPC {#JPC}
```
public static final FileType JPC
```


Rappresenta un JPEG 2000 Code Stream (.jpc). Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/jpc

### JLS {#JLS}
```
public static final FileType JLS
```


Rappresenta un file JPEG-LS (JLS) (.jls). Scopri di più su questo formato di file [qui][].


[here]: https://fileinfo.com/extension/jls

### DIB {#DIB}
```
public static final FileType DIB
```


Rappresenta un Device Independent Bitmap File (.dib). Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/dib

### WMF {#WMF}
```
public static final FileType WMF
```


Rappresenta un Windows Metafile (.wmf), che rappresenta il Microsoft Windows Metafile (WMF) per la memorizzazione di dati immagine vettoriali e bitmap. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/wmf

### WMZ {#WMZ}
```
public static final FileType WMZ
```


Rappresenta un Compressed Windows Metafile (.wmz), che rappresenta il Microsoft Windows Metafile (WMF) compresso in archivio GZIP per la memorizzazione di dati immagine vettoriali e bitmap. Scopri di più su questo formato di file [qui][].


[here]: https://fileinfo.com/extension/wmz#compressed_windows_metafile

### EMF {#EMF}
```
public static final FileType EMF
```


Rappresenta un Enhanced Windows Metafile (.emf), che rappresenta immagini grafiche in modo indipendente dal dispositivo. I metafile EMF comprendono record di lunghezza variabile in ordine cronologico che possono rendere l'immagine memorizzata dopo l'analisi su qualsiasi dispositivo di output. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/emf

### EMZ {#EMZ}
```
public static final FileType EMZ
```


Rappresenta un Windows Compressed Enhanced Metafile (.emz), che rappresenta immagini grafiche in modo indipendente dal dispositivo, compresse con GZIP. I metafile EMF comprendono record di lunghezza variabile in ordine cronologico che possono rendere l'immagine memorizzata dopo l'analisi su qualsiasi dispositivo di output. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/emz

### WEBP {#WEBP}
```
public static final FileType WEBP
```


Rappresenta un WebP Image (.webp), che è un moderno formato di file immagine raster per il web basato su compressione lossless e lossy. Fornisce la stessa qualità dell'immagine riducendo notevolmente le dimensioni del file. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/webp

### DNG {#DNG}
```
public static final FileType DNG
```


Rappresenta una Digital Negative Specification (.dng), che è un formato di immagine per fotocamere digitali usato per la memorizzazione di file raw. È stato sviluppato da Adobe nel settembre 2004 ed è principalmente utilizzato per la fotografia digitale. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/dng

### CDR {#CDR}
```
public static final FileType CDR
```


Rappresenta un CorelDraw Vector Graphic Drawing (.cdr), che è un file immagine vettoriale creato nativamente con CorelDRAW per la memorizzazione di immagini codificate e compresse digitalmente. Un file di disegno CDR contiene testo, linee, forme, immagini, colori ed effetti per la rappresentazione vettoriale del contenuto dell'immagine. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/cdr

### CMX {#CMX}
```
public static final FileType CMX
```


Rappresenta un Corel Exchange (.cmx), che è un file immagine di disegno che può contenere grafica vettoriale così come grafica bitmap. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/image/cmx

### DJVU {#DJVU}
```
public static final FileType DJVU
```


Rappresenta un'immagine DjVu (.djvu), che è un formato di file grafico destinato a documenti e libri scansionati, in particolare a quelli contenenti una combinazione di testo, disegni, immagini e fotografie. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/image/djvu

### CGM {#CGM}
```
public static final FileType CGM
```


Rappresenta un Metafoglio di Grafica Computerizzata (.cgm), che è un formato metafile gratuito, indipendente dalla piattaforma, standard internazionale per l'archiviazione e lo scambio di grafica vettoriale (2D), grafica raster e testo. CGM utilizza un approccio orientato agli oggetti e fornisce molte funzioni per la produzione di immagini. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/page-description-language/cgm

### PCL {#PCL}
```
public static final FileType PCL
```


Rappresenta un documento Printer Command Language (.pcl). Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/page-description-language/pcl

### PSD {#PSD}
```
public static final FileType PSD
```


Rappresenta un documento Adobe Photoshop (.psd), che è il formato di file nativo di Adobe Photoshop utilizzato per la progettazione e lo sviluppo grafico. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/image/psd

### PSB {#PSB}
```
public static final FileType PSB
```


Rappresenta un formato Photoshop Large Document (.psb), che è utilizzato per la progettazione e lo sviluppo grafico in Adobe Photoshop. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/image/psb

### DCM {#DCM}
```
public static final FileType DCM
```


Rappresenta un'immagine DICOM (.dcm), che è un'immagine digitale che memorizza informazioni mediche dei pazienti come risonanze magnetiche, scansioni TC e immagini ecografiche. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/image/dcm

### PS {#PS}
```
public static final FileType PS
```


Rappresenta un file PostScript (.ps). Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/page-description-language/ps

### EPS {#EPS}
```
public static final FileType EPS
```


Rappresenta un file Encapsulated PostScript (.eps), che descrive un programma di linguaggio Encapsulated PostScript che definisce l'aspetto di una singola pagina. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/page-description-language/eps

### ODG {#ODG}
```
public static final FileType ODG
```


Rappresenta un file OpenDocument Graphic (.odg), che è utilizzato dall'applicazione Draw di Apache OpenOffice per memorizzare gli elementi di disegno come immagine vettoriale. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/image/odg

### FODG {#FODG}
```
public static final FileType FODG
```


Rappresenta un modello Flat XML ODF (.fodg), che è utilizzato dall'applicazione Draw di Apache OpenOffice per memorizzare gli elementi di disegno come immagine vettoriale. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/image/fodg

### SVG {#SVG}
```
public static final FileType SVG
```


Rappresenta un file Scalable Vector Graphics (.svg), che è un file Scalable Vector Graphics che utilizza un formato di testo basato su XML per descrivere l'aspetto di un'immagine. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/page-description-language/svg

### SVGZ {#SVGZ}
```
public static final FileType SVGZ
```


Rappresenta un file Compressed Scalable Vector Graphics (.svgz), che è un file Scalable Vector Graphics che utilizza un formato di testo basato su XML, compresso con GZIP, per descrivere l'aspetto di un'immagine. Scopri di più su questo formato di file [here][].


[here]: https://fileinfo.com/extension/svgz

### OTG {#OTG}
```
public static final FileType OTG
```


Rappresenta un modello OpenDocument Graphic (.otg). Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/image/otg

### HTM {#HTM}
```
public static final FileType HTM
```


Rappresenta un file Hypertext Markup Language (.htm), che è l'estensione per le pagine web create per la visualizzazione nei browser. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/web/html

### HTML {#HTML}
```
public static final FileType HTML
```


Rappresenta un file Hypertext Markup Language (.html), che è l'estensione per le pagine web create per la visualizzazione nei browser. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


Rappresenta un archivio web MHTML (.mht). Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/web/mht

### NSF {#NSF}
```
public static final FileType NSF
```


Rappresenta un database Lotus Notes (.nsf). Scopri di più su questo formato di file [here][].


[here]: https://fileinfo.com/extension/nsf

### MBOX {#MBOX}
```
public static final FileType MBOX
```


Rappresenta un file casella di posta elettronica (.mbox). Scopri di più su questo formato di file [here][].


[here]: https://fileinfo.com/extension/mbox

### MHTML {#MHTML}
```
public static final FileType MHTML
```


Rappresenta un file MIME HTML (.mhtml). Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/web/mhtml

### XML {#XML}
```
public static final FileType XML
```


Rappresenta un file XML (.xml). Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/web/xml

### ONE {#ONE}
```
public static final FileType ONE
```


Rappresenta un documento OneNote (.one) creato dall'applicazione Microsoft OneNote. OneNote ti consente di raccogliere informazioni usando l'applicazione come se stessi usando il tuo blocco per prendere appunti. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


Rappresenta un file Portable Document Format (.pdf), che è un tipo di documento creato da Adobe negli anni '90. Lo scopo di questo formato di file era introdurre uno standard per la rappresentazione di documenti e altri materiali di riferimento in un formato indipendente dal software applicativo, dall'hardware e dai sistemi operativi. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


Rappresenta un file XML Paper Specification (.xps), che rappresenta file di layout di pagina basati su XML Paper Specifications creati da Microsoft. Questo formato è stato sviluppato da Microsoft come sostituto del formato file EMF ed è simile al formato file PDF, ma utilizza XML per il layout, l'aspetto e le informazioni di stampa di un documento. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/page-description-language/xps

### OXPS {#OXPS}
```
public static final FileType OXPS
```


Rappresenta un file OpenXPS (.oxps). Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/page-description-language/oxps

### TEX {#TEX}
```
public static final FileType TEX
```


Rappresenta un documento sorgente LaTeX (.tex), che è un linguaggio che comprende funzionalità di programmazione e di markup utilizzate per impaginare documenti. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


Rappresenta una presentazione PowerPoint (.ppt), che rappresenta un file PowerPoint costituito da una raccolta di diapositive da visualizzare come presentazione. Specifica il Binary File Format utilizzato da Microsoft PowerPoint 97-2003. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


Rappresenta una presentazione PowerPoint Open XML (.pptx), che sono file di presentazione creati con la popolare applicazione Microsoft PowerPoint. A differenza della versione precedente del formato file di presentazione PPT, che era binario, il formato PPTX si basa sul formato file di presentazione Microsoft PowerPoint Open XML. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


Rappresenta una presentazione PowerPoint Slide Show (.pps), che è creata utilizzando Microsoft PowerPoint per scopi di presentazione. La lettura e la creazione di file PPS sono supportate da Microsoft PowerPoint 97-2003. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


Rappresenta file PowerPoint Open XML Slide Show (.ppsx), che sono creati con Microsoft PowerPoint 2007 e versioni successive per scopi di presentazione. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


Rappresenta una presentazione OpenDocument (.odp), che rappresenta un formato di file di presentazione utilizzato da OpenOffice.org nello standard OASIS Open. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/presentation/odp

### FODP {#FODP}
```
public static final FileType FODP
```


Rappresenta una presentazione OpenDocument (.fodp), che rappresenta una presentazione OpenDocument Flat XML. Scopri di più su questo formato di file [here][].


[here]: https://fileinfo.com/extension/fodp

### POT {#POT}
```
public static final FileType POT
```


Rappresenta un modello PowerPoint (.pot), che rappresenta i file modello di Microsoft PowerPoint creati dalle versioni PowerPoint 97-2003. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/presentation/pot

### PPTM {#PPTM}
```
public static final FileType PPTM
```


Rappresenta una presentazione PowerPoint Open XML abilitata alle macro (.pptm), che sono file di presentazione con macro creati con Microsoft PowerPoint 2007 o versioni successive. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/presentation/pptm

### POTX {#POTX}
```
public static final FileType POTX
```


Rappresenta un modello di presentazione PowerPoint Open XML (.potx), che rappresenta modelli di presentazione Microsoft PowerPoint creati con Microsoft PowerPoint 2007 e versioni successive. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/presentation/potx

### POTM {#POTM}
```
public static final FileType POTM
```


Rappresenta un modello di presentazione PowerPoint Open XML abilitato alle macro (.potm), che sono file modello di Microsoft PowerPoint con supporto per le macro. I file POTM sono creati con PowerPoint 2007 o versioni successive e contengono impostazioni predefinite che possono essere usate per creare ulteriori file di presentazione. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/presentation/potm

### PPSM {#PPSM}
```
public static final FileType PPSM
```


Rappresenta una diapositiva PowerPoint Open XML abilitata alle macro (.ppsm), che rappresenta un formato di file di presentazione con macro creato con Microsoft PowerPoint 2007 o versioni successive. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/presentation/ppsm

### OTP {#OTP}
```
public static final FileType OTP
```


Rappresenta un modello di presentazione OpenDocument (.otp), che rappresenta file modello di presentazione creati da applicazioni nel formato standard OASIS OpenDocument. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


Rappresenta un foglio di calcolo Excel (.xls), che rappresenta il formato Excel Binary File Format. Tali file possono essere creati da Microsoft Excel così come da altri programmi di fogli di calcolo simili come OpenOffice Calc o Apple Numbers. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### EXCEL_2003_XML {#EXCEL-2003-XML}
```
public static final FileType EXCEL_2003_XML
```


Rappresenta un file Excel 2003 XML (SpreadsheetML) (.xml), che rappresenta il formato Excel Binary File Format. Tali file possono essere creati da Microsoft Excel così come da altri programmi di fogli di calcolo simili come OpenOffice Calc o Apple Numbers. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### NUMBERS {#NUMBERS}
```
public static final FileType NUMBERS
```


Rappresenta Apple Numbers (.numbers), che rappresenta un formato di file binario simile a Excel. Tali file possono essere creati dall'applicazione Apple Numbers. Scopri di più su questo formato di file [here][].


[here]: https://fileinfo.com/extension/numbers

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Rappresenta un foglio di calcolo Microsoft Excel Open XML (.xlsx), che è un formato noto per i documenti Microsoft Excel introdotto da Microsoft con il rilascio di Microsoft Office 2007. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Rappresenta un foglio di calcolo Excel Open XML con macro abilitati (.xlsm), che è un tipo di file di foglio di calcolo che supporta le macro. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Rappresenta un foglio di calcolo Excel Binary (.xlsb), che specifica il formato di file binario di Excel. È una raccolta di record e strutture che definiscono il contenuto della cartella di lavoro Excel. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


Rappresenta un file di valori separati da virgola (.csv), che rappresenta file di testo semplice contenenti record di dati con valori separati da virgola. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


Rappresenta un file di valori separati da tabulazione (.tsv), che rappresenta dati separati da tabulazioni in formato di testo semplice. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


Rappresenta un foglio di calcolo OpenDocument (.ods), che sta per formato di documento foglio di calcolo OpenDocument modificabile dall'utente. I dati sono memorizzati nei file ODF in righe e colonne. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ods

### FODS {#FODS}
```
public static final FileType FODS
```


Rappresenta un foglio di calcolo OpenDocument Flat XML (.fods). È un formato di documento foglio di calcolo basato su XML utilizzato da OpenOffice e LibreOffice. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/spreadsheet/fods

### OTS {#OTS}
```
public static final FileType OTS
```


Rappresenta un modello di foglio di calcolo OpenDocument (.ots). È un formato di documento modello utilizzato da OpenOffice e LibreOffice per i fogli di calcolo. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ots

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Rappresenta un componente aggiuntivo Microsoft Excel (.xlam). È un formato di file utilizzato da Microsoft Excel per creare componenti aggiuntivi con funzionalità personalizzate. Scopri di più su questo formato di file [here][].


[here]: https://fileinfo.com/extension/xlam

### XLTM {#XLTM}
```
public static final FileType XLTM
```


Rappresenta un modello Microsoft Excel con macro abilitate (.xltm), che rappresenta file generati da Microsoft Excel come modelli con macro. I file XLTM sono simili a XLTX nella struttura, tranne per il fatto che quest'ultimo non supporta la creazione di modelli con macro. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltm

### XLT {#XLT}
```
public static final FileType XLT
```


Rappresenta un modello Microsoft Excel (.xlt), che sono file modello creati con Microsoft Excel, un'applicazione di foglio di calcolo inclusa nella suite Microsoft Office. Microsoft Office 97-2003 supportava la creazione di nuovi file XLT e la loro apertura. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlt

### XLTX {#XLTX}
```
public static final FileType XLTX
```


Rappresenta un modello di foglio di calcolo Excel Open XML (.xltx), che rappresenta modelli Microsoft Excel basati sulle specifiche del formato di file Office OpenXML. Viene utilizzato per creare un file modello standard che può essere impiegato per generare file XLSX con le stesse impostazioni specificate nel file XLTX. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltx

### SXC {#SXC}
```
public static final FileType SXC
```


Rappresenta un foglio di calcolo StarOffice Calc (.sxc). È un documento di foglio di calcolo creato con StarOffice Calc, un programma di foglio di calcolo. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/spreadsheet/sxc

### MPP {#MPP}
```
public static final FileType MPP
```


Rappresenta un file Microsoft Project (.mpp), che è un file di dati Microsoft Project che memorizza informazioni relative alla gestione dei progetti in modo integrato. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/project-management/mpp

### MPT {#MPT}
```
public static final FileType MPT
```


Rappresenta un modello Microsoft Project (.mpt), che contiene informazioni di base e struttura insieme alle impostazioni del documento per creare file .MPP. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/project-management/mpt

### MPX {#MPX}
```
public static final FileType MPX
```


Rappresenta un file Microsoft Project Exchange (.mpx), che è un formato di file ASCII per il trasferimento di informazioni di progetto tra Microsoft Project (MSP) e altre applicazioni che supportano il formato MPX, come Primavera Project Planner, Sciforma e Timerline Precision Estimating. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/project-management/mpx

### AS {#AS}
```
public static final FileType AS
```


Rappresenta un file ActionScript (.as). Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/programming/as

### AS_3 {#AS-3}
```
public static final FileType AS_3
```


Rappresenta un file ActionScript (.as3). Scopri di più su questo formato di file [here][].


[here]: https://datatypes.net/open-as3-files

### ASM {#ASM}
```
public static final FileType ASM
```


Rappresenta un file di codice sorgente in linguaggio Assembly (.asm). Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/cad/asm

### BAT {#BAT}
```
public static final FileType BAT
```


Rappresenta un file batch DOS (.bat). Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/executable/bat

### C {#C}
```
public static final FileType C
```


Rappresenta un file di codice sorgente C/C++ (.c). Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/programming/c

### CC {#CC}
```
public static final FileType CC
```


Rappresenta un file di codice sorgente C++ (.cc). Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/programming/cc

### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Rappresenta un file CMake (.cmake). Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/programming/cmake

### CPP {#CPP}
```
public static final FileType CPP
```


Rappresenta un file di codice sorgente C++ (.cpp). Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/programming/cpp

### CS {#CS}
```
public static final FileType CS
```


Rappresenta un file di codice sorgente C\# (.cs), che è un file di codice sorgente per il linguaggio di programmazione C\#. È stato introdotto da Microsoft per l'uso con il .NET Framework. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/programming/cs

### VB {#VB}
```
public static final FileType VB
```


Rappresenta un file di elemento progetto Visual Basic (.vb), che è un file di codice sorgente creato nel linguaggio Visual Basic. È stato creato da Microsoft per lo sviluppo di applicazioni .NET. Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/programming/vb

### CSS {#CSS}
```
public static final FileType CSS
```


Rappresenta un file Cascading Style Sheet (.css). Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/web/css

### CXX {#CXX}
```
public static final FileType CXX
```


Rappresenta un file di codice sorgente C++ (.cxx). Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/programming/cxx

### DIFF {#DIFF}
```
public static final FileType DIFF
```


Rappresenta un file patch (.diff). Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/programming/diff

### ERB {#ERB}
```
public static final FileType ERB
```


Rappresenta uno script Ruby ERB (.erb). Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/programming/erb

### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Rappresenta un file di codice sorgente Groovy (.groovy). Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/programming/groovy

### H {#H}
```
public static final FileType H
```


Rappresenta un file header C/C++/Objective-C (.h). Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/programming/h

### HAML {#HAML}
```
public static final FileType HAML
```


Rappresenta un file di codice sorgente Haml (.haml). Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/programming/haml

### HH {#HH}
```
public static final FileType HH
```


Rappresenta un file header C++ (.hh). Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/programming/hh

### JAVA {#JAVA}
```
public static final FileType JAVA
```


Rappresenta un file di codice sorgente Java (.java). Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/programming/java

### JS {#JS}
```
public static final FileType JS
```


Rappresenta un file JavaScript (.js). Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/web/js

### JSON {#JSON}
```
public static final FileType JSON
```


Rappresenta un file JavaScript Object Notation (.json). Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/web/json

### LESS {#LESS}
```
public static final FileType LESS
```


Rappresenta un file LESS Style Sheet (.less). Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/web/less

### LOG {#LOG}
```
public static final FileType LOG
```


Rappresenta un file di log (.log). Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/database/log

### M {#M}
```
public static final FileType M
```


Rappresenta un file di implementazione Objective-C (.m). Scopri di più su questo formato di file [here][].


[here]: https://fileinfo.com/extension/m

### MAKE {#MAKE}
```
public static final FileType MAKE
```


Rappresenta uno script Xcode Makefile (.make). Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/programming/make

### MD {#MD}
```
public static final FileType MD
```


Rappresenta un file di documentazione Markdown (.md). Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/word-processing/md

### ML {#ML}
```
public static final FileType ML
```


Rappresenta un file di codice sorgente ML (.ml). Scopri di più su questo formato di file [here][].


[here]: https://wiki.fileformat.com/programming/ml

### MM {#MM}
```
public static final FileType MM
```


Rappresenta un file Objective-C++ (.mm). Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/programming/mm

### PHP {#PHP}
```
public static final FileType PHP
```


Rappresenta un file di codice sorgente PHP (.php). Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/programming/php

### PL {#PL}
```
public static final FileType PL
```


Rappresenta uno script Perl (.pl). Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/programming/pl

### PROPERTIES {#PROPERTIES}
```
public static final FileType PROPERTIES
```


Rappresenta un file di proprietà Java (.properties). Scopri di più su questo formato di file [qui][].


[here]: https://fileinfo.com/extension/properties

### PY {#PY}
```
public static final FileType PY
```


Rappresenta uno script Python (.py). Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/programming/py

### RB {#RB}
```
public static final FileType RB
```


Rappresenta un file di codice sorgente Ruby (.rb). Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/programming/rb

### RST {#RST}
```
public static final FileType RST
```


Rappresenta un file reStructuredText (.rst). Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/programming/rst

### SASS {#SASS}
```
public static final FileType SASS
```


Rappresenta un file Syntactically Awesome StyleSheets (.sass). Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/web/sass

### SCALA {#SCALA}
```
public static final FileType SCALA
```


Rappresenta un file di codice sorgente Scala (.scala). Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/programming/scala

### SCM {#SCM}
```
public static final FileType SCM
```


Rappresenta un file di codice sorgente Scheme (.scm). Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/programming/scm

### SCRIPT {#SCRIPT}
```
public static final FileType SCRIPT
```


Rappresenta un file script generico (.script). Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/programming/script

### SH {#SH}
```
public static final FileType SH
```


Rappresenta uno script Bash Shell (.sh). Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/cs/programming/sh

### SML {#SML}
```
public static final FileType SML
```


Rappresenta un file di codice sorgente Standard ML (.sml). Scopri di più su questo formato di file [qui][].


[here]: https://fileinfo.com/extension/sml

### SQL {#SQL}
```
public static final FileType SQL
```


Rappresenta un file di dati Structured Query Language (.sql). Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/database/sql

### VIM {#VIM}
```
public static final FileType VIM
```


Rappresenta un file di impostazioni Vim (.vim). Scopri di più su questo formato di file [qui][].


[here]: https://fileinfo.com/extension/vim

### YAML {#YAML}
```
public static final FileType YAML
```


Rappresenta un documento YAML (.yaml). Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/programming/yaml

### DOC {#DOC}
```
public static final FileType DOC
```


Rappresenta un documento Microsoft Word (.doc). Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Rappresenta un documento Microsoft Word Open XML (.docx). Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/word-processing/docx

### CHM {#CHM}
```
public static final FileType CHM
```


Rappresenta un file Microsoft Compiled HTML Help (.chm). Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/web/chm

### DOCM {#DOCM}
```
public static final FileType DOCM
```


Rappresenta un documento Word Open XML abilitato alle macro (.docm). Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


Rappresenta un modello di documento Word (.dot). Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Rappresenta un modello di documento Word Open XML (.dotx). Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Rappresenta un modello di documento Word Open XML abilitato alle macro (.dotm). Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


Rappresenta un file Rich Text Format (.rtf). Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


Rappresenta un file di testo semplice (.txt). Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/word-processing/txt

### ODT {#ODT}
```
public static final FileType ODT
```


Rappresenta un documento di testo OpenDocument (.odt). Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


Rappresenta un modello di documento OpenDocument (.ott). È un documento modello generato in conformità con lo standard OpenDocument di OASIS. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/word-processing/ott

### VCF {#VCF}
```
public static final FileType VCF
```


Rappresenta un file vCard (.vcf), che è un formato di file digitale per la memorizzazione delle informazioni di contatto. È ampiamente utilizzato per lo scambio di dati tra le popolari applicazioni di scambio di informazioni. Scopri di più su questo formato di file [qui][].


[here]: https://wiki.fileformat.com/email/vcf

### AI {#AI}
```
public static final FileType AI
```


Rappresenta un file Adobe Illustrator (.ai), che è un formato di file per i disegni di Adobe Illustrator. Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/image/ai

### PSM1 {#PSM1}
```
public static final FileType PSM1
```


Rappresenta un file di modulo script PowerShell (.psm1). È un formato di file per script di moduli PowerShell. Scopri di più su questo formato di file [qui][].


[here]: https://fileinfo.com/extension/psm1

### PS1 {#PS1}
```
public static final FileType PS1
```


Rappresenta un file script PowerShell (.ps1). È un formato di file per file Cmdlet di Windows PowerShell. Scopri di più su questo formato di file [qui][].


[here]: https://fileinfo.com/extension/ps1

### PSD1 {#PSD1}
```
public static final FileType PSD1
```


Rappresenta un file manifesto di modulo script PowerShell (.psd1). È un formato di file per script di manifesto di moduli PowerShell. Scopri di più su questo formato di file [qui][].


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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


Mappa un'estensione di file a un tipo di file.

Questo metodo accetta un'estensione di file, con o senza il punto ".", e restituisce il tipo di file corrispondente se è supportato. Se il tipo di file non è supportato, restituisce il tipo di file predefinito [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| extension | java.lang.String | L'estensione del file con o senza il punto ".". |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromFilePath(String filePath) {#fromFilePath-java.lang.String-}
```
public static FileType fromFilePath(String filePath)
```


Estrae l'estensione del file da un nome file o da un percorso file e la mappa a un tipo di file.

Se il tipo di file è supportato, il metodo restituisce il corrispondente  FileType , altrimenti restituisce il tipo di file predefinito [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il nome del file o il percorso del file. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromMediaType(String mediaType) {#fromMediaType-java.lang.String-}
```
public static FileType fromMediaType(String mediaType)
```


Mappa un tipo di media di file a un tipo di file. Per esempio, 'application/pdf' verrà mappato a [PDF](../../com.groupdocs.viewer/filetype\#PDF).

Questo metodo accetta un tipo di media di file come input e lo mappa al corrispondente  FileType . Se il tipo di media è supportato, il metodo restituisce il tipo di file corrispondente. Se il tipo di media non è supportato, restituisce il tipo di file predefinito [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mediaType | java.lang.String | Il tipo di media del file, ad es., 'application/pdf'. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if found, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream stream)
```


Rileva il tipo di file leggendo la firma del file.

Questo metodo accetta un flusso di input che rappresenta un file e tenta di rilevare il suo tipo di file analizzando la firma del file. La firma del file è una sequenza unica di byte all'inizio del file che indica il suo tipo di file. Il metodo legge la firma del file dal flusso di input e la confronta con le firme di file note dei tipi di file supportati. Se viene trovata una corrispondenza, il metodo restituisce il tipo di file corrispondente. Se non viene trovata alcuna corrispondenza, restituisce il tipo di file predefinito [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Il flusso di input che rappresenta il file. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password) {#fromStream-java.io.InputStream-java.lang.String-}
```
public static FileType fromStream(InputStream stream, String password)
```


Rileva il tipo di file leggendo la firma del file.

Questo metodo analizza la firma del file, che è una sequenza unica di byte all'inizio del file, per determinare il tipo di file. Legge la firma del file dal flusso di input fornito e la confronta con le firme di file note dei tipi di file supportati. Se viene trovata una corrispondenza, il metodo restituisce il tipo di file corrispondente. Se non viene trovata alcuna corrispondenza, restituisce il tipo di file predefinito [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

Se il file è crittografato e richiede una password per aprirlo, la password deve essere fornita come parametro a questo metodo. La password verrà utilizzata per decrittare il file e analizzare la sua firma per determinare il tipo di file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Il flusso di input che rappresenta il file. |
| password | java.lang.String | La password per aprire il file. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, ILogger logger) {#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, ILogger logger)
```


Rileva il tipo di file leggendo la firma del file.

Questo metodo analizza la firma del file, che è una sequenza unica di byte all'inizio del file, per determinare il tipo di file. Legge la firma del file dal flusso di input fornito e la confronta con le firme di file note dei tipi di file supportati. Se viene trovata una corrispondenza, il metodo restituisce il tipo di file corrispondente. Se non viene trovata alcuna corrispondenza, restituisce il tipo di file predefinito [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

È possibile fornire un logger per registrare qualsiasi informazione o errore rilevante durante il processo di rilevamento del tipo di file. Il logger dovrebbe implementare l'interfaccia **ILogger**. Se non viene fornito alcun logger, il processo di rilevamento non produrrà alcun output di log.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Il flusso di input che rappresenta il file. |
| logger | com.groupdocs.foundation.logging.ILogger | Il logger per registrare informazioni o errori. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password, ILogger logger) {#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, String password, ILogger logger)
```


Rileva il tipo di file leggendo la firma del file.

Questo metodo analizza la firma del file, che è una sequenza unica di byte all'inizio del file, per determinare il tipo di file. Legge la firma del file dal flusso di input fornito e la confronta con le firme di file note dei tipi di file supportati. Se viene trovata una corrispondenza, il metodo restituisce il tipo di file corrispondente. Se non viene trovata alcuna corrispondenza, restituisce il tipo di file predefinito [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

È possibile fornire una password se il file è crittografato o protetto. La password verrà utilizzata per aprire il file prima di analizzare la firma del file. Se il file non richiede una password, questo parametro può essere impostato a null.

È possibile fornire un logger per registrare qualsiasi informazione o errore rilevante durante il processo di rilevamento del tipo di file. Il logger dovrebbe implementare l'interfaccia **ILogger**. Se non viene fornito alcun logger, il processo di rilevamento non produrrà alcun output di log.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Il flusso di input che rappresenta il file. |
| password | java.lang.String | La password per aprire il file. |
| logger | com.groupdocs.foundation.logging.ILogger | Il logger per registrare informazioni o errori. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Recupera i tipi di file supportati.

Questo metodo restituisce una sequenza di tutti i tipi di file supportati dal sistema. I tipi di file rappresentano vari formati di documento che possono essere elaborati o riconosciuti dal sistema.

 **Learn more**

 *  Learn more about the supported document formats: [Full list of supported file formats][]


[Full list of supported file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/

**Returns:**
java.util.List<com.groupdocs.viewer.FileType> - una sequenza di tipi di file supportati.
### detectCharset(String filePath) {#detectCharset-java.lang.String-}
```
public static Charset detectCharset(String filePath)
```


Tenta di rilevare la codifica dei file di testo [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) e [CSV](../../com.groupdocs.viewer/filetype\#CSV) per percorso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il nome del file o il percorso del file. |

**Returns:**
java.nio.charset.Charset - Charset o null quando non riesce a rilevare il charset del file.

**Example:**

```
Charset charset = FileType.detectCharset("message.txt");
```
### detectCharset(InputStream stream) {#detectCharset-java.io.InputStream-}
```
public static Charset detectCharset(InputStream stream)
```


Tenta di rilevare la codifica dei file di testo [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) e [CSV](../../com.groupdocs.viewer/filetype\#CSV) per flusso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Il flusso del file. |

**Returns:**
java.nio.charset.Charset - Charset o null quando non riesce a rilevare il charset del file.

**Example:**

```
InputStream stream = new FileInputStream("message.txt");
 Charset charset = FileType.detectCharset(stream);
```
### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Ottiene il nome del formato file, ad esempio "Microsoft Word Document".

**Returns:**
java.lang.String - il nome del formato del file.
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Ottiene il suffisso dell'estensione del file (incluso il punto "."), ad esempio ".doc".

**Returns:**
java.lang.String - il suffisso dell'estensione del file.
### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione stringa dell'oggetto corrente.

**Returns:**
java.lang.String - una rappresentazione stringa dell'oggetto corrente.
