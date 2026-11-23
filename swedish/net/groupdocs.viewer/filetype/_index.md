---
title: "FileType"
second_title: "GroupDocs.Viewer för .NET API-referens"
description: "Representerar filtyp. Tillhandahåller metoder för att hämta en lista över alla filtyper som stöds av GroupDocs.Viewer."
type: docs
weight: 10
url: /sv/net/groupdocs.viewer/filetype/
---

## FileType class

Representerar filtyp. Tillhandahåller metoder för att hämta en lista över alla filtyper som stöds av **GroupDocs.Viewer**.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [FileType](filetype#constructor)() | Initierar en ny instans av klassen [`FileType`](../filetype). |
| [FileType](filetype#constructor_1)(string, string) | Initierar en ny instans av klassen [`FileType`](../filetype). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Extension](../../groupdocs.viewer/filetype/extension) { get; set; } | Filnamnsuffix (inklusive perioden ".") t.ex. ".doc". |
| [FileFormat](../../groupdocs.viewer/filetype/fileformat) { get; set; } | Filtypnamn t.ex. "Microsoft Word Document". |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromExtension](../../groupdocs.viewer/filetype/fromextension)(string) | Mappar filändelse till filtyp. |
| static [FromFilePath](../../groupdocs.viewer/filetype/fromfilepath)(string) | Extraherar filändelse och mappar den till filtyp. |
| static [FromMediaType](../../groupdocs.viewer/filetype/frommediatype)(string) | Mappar filmediatyp till filtyp, t.ex. 'application/pdf' kommer att mappas till [`PDF`](./pdf). |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream)(Stream) | Detekterar filtyp genom att läsa filsignaturen. |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_1)(Stream, ILogger) | Detekterar filtyp genom att läsa filsignaturen. |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_2)(Stream, string) | Detekterar filtyp genom att läsa filsignaturen. |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_3)(Stream, string, ILogger) | Detekterar filtyp genom att läsa filsignaturen. |
| [Equals](../../groupdocs.viewer/filetype/equals#equals)(FileType) | Bestämmer om den aktuella [`FileType`](../filetype) är densamma som det angivna [`FileType`](../filetype)-objektet. |
| override [Equals](../../groupdocs.viewer/filetype/equals#equals_1)(object) | Bestämmer om den aktuella [`FileType`](../filetype) är densamma som det angivna objektet. |
| override [GetHashCode](../../groupdocs.viewer/filetype/gethashcode)() | Returnerar hashkoden för det aktuella [`FileType`](../filetype)-objektet. |
| override [ToString](../../groupdocs.viewer/filetype/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |
| static [DetectEncoding](../../groupdocs.viewer/filetype/detectencoding#detectencoding)(Stream) | Försöker att detektera textkodning för [`TXT`](./txt), [`TSV`](./tsv) och [`CSV`](./csv)-filer via ström. |
| static [DetectEncoding](../../groupdocs.viewer/filetype/detectencoding#detectencoding_1)(string) | Försöker att detektera textkodning för [`TXT`](./txt), [`TSV`](./tsv) och [`CSV`](./csv)-filer via sökväg. |
| static [GetSupportedFileTypes](../../groupdocs.viewer/filetype/getsupportedfiletypes)() | Hämtar stödda filtyper |
| [operator ==](../../groupdocs.viewer/filetype/op_equality) | Bestämmer om två [`FileType`](../filetype)-objekt är desamma. |
| [operator !=](../../groupdocs.viewer/filetype/op_inequality) | Bestämmer om två [`FileType`](../filetype)-objekt inte är desamma. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [APNG](../../groupdocs.viewer/filetype/apng) | Animated Portable Network Graphic (.apng) är en utökning av PNG-formatet som stödjer animation. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/apng). |
| static readonly [AS](../../groupdocs.viewer/filetype/as) | ActionScript-fil (.as) |
| static readonly [AS3](../../groupdocs.viewer/filetype/as3) | ActionScript-fil (.as) |
| static readonly [ASM](../../groupdocs.viewer/filetype/asm) | Assembly Language-källkodfil (.asm) |
| static readonly [AZW3](../../groupdocs.viewer/filetype/azw3) | Amazon Kindle Format 8 (KF8) e-bok är det digitala filformat som utvecklats för Amazon Kindle-enheter. Formatet är en förbättring av äldre AZW-filer och används endast på Kindle Fire-enheter med bakåtkompatibilitet för det föregående filformatet, dvs. MOBI och AZW. Läs mer om detta filformat [här](https://wiki.fileformat.com/ebook/azw3). |
| static readonly [BAT](../../groupdocs.viewer/filetype/bat) | DOS-batchfil (.bat) |
| static readonly [BMP](../../groupdocs.viewer/filetype/bmp) | Bitmap-bildfil (.bmp) används för att lagra bitmap-digitala bilder. Dessa bilder är oberoende av grafikadapter och kallas också en device independent bitmap (DIB)-filformat. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/bmp). |
| static readonly [BZ2](../../groupdocs.viewer/filetype/bz2) | Bzip2-komprimerad fil (.bz2) är komprimerade filer som genereras med BZIP2-metoden för öppen källkod, främst på UNIX- eller Linux-system. Läs mer om detta filformat [här](https://wiki.fileformat.com/compression/bz2). |
| static readonly [C](../../groupdocs.viewer/filetype/c) | C/C++-källkodfil (.c) |
| static readonly [Cab](../../groupdocs.viewer/filetype/cab) | Cabinet (eller CAB) är ett arkivfilformat för Microsoft Windows. Läs mer om detta filformat [här](https://en.wikipedia.org/wiki/Cabinet_(file_format)). |
| static readonly [CC](../../groupdocs.viewer/filetype/cc) | C++-källkodfil (.cc) |
| static readonly [CDR](../../groupdocs.viewer/filetype/cdr) | CorelDraw-vektorgrafikritning (.cdr) är en vektorritningsfil som ursprungligen skapas med CorelDRAW för lagring av digitala bilder som kodas och komprimeras. En sådan ritningsfil innehåller text, linjer, former, bilder, färger och effekter för vektorrepräsentation av bildinnehåll. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/cdr). |
| static readonly [CF2](../../groupdocs.viewer/filetype/cf2) | Common File Format-fil. Läs mer om detta filformat [här](https://fileinfo.com/extension/cf2). |
| static readonly [CGM](../../groupdocs.viewer/filetype/cgm) | Computer Graphics Metafile (.cgm) är ett fritt, plattformsoberoende, internationellt standardmetafilformat för lagring och utbyte av vektorgrafik (2D), rastergrafik och text. CGM använder ett objektorienterat tillvägagångssätt och många funktionsmöjligheter för bildproduktion. Läs mer om detta filformat [här](https://wiki.fileformat.com/page-description-language/cgm). |
| static readonly [CHM](../../groupdocs.viewer/filetype/chm) | Microsoft Compiled HTML Help-fil (.chm) är ett välkänt format för HELP- (dokumentation till någon applikation) dokument. Läs mer om detta filformat [här](https://docs.fileformat.com/web/chm/). |
| static readonly [CMAKE](../../groupdocs.viewer/filetype/cmake) | CMake-fil (.cmake) |
| static readonly [CMX](../../groupdocs.viewer/filetype/cmx) | Corel Exchange (.cmx) är en ritningsfil som kan innehålla både vektorgrafik och bitmapgrafik. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/cmx). |
| static readonly [CPIO](../../groupdocs.viewer/filetype/cpio) | Cpio är ett allmänt filarkiveringsverktyg och dess tillhörande filformat. Det är främst installerat på Unix-liknande operativsystem. Läs mer om detta filformat [här](https://wiki.fileformat.com/compression/cpio). |
| static readonly [CPP](../../groupdocs.viewer/filetype/cpp) | C++-källkodfil (.cpp) |
| static readonly [CS](../../groupdocs.viewer/filetype/cs) | C#-källkodfil (.cs) är en källkodfil för programmeringsspråket C#. Introducerad av Microsoft för användning med .NET-ramverket. Läs mer om detta filformat [här](https://wiki.fileformat.com/programming/cs). |
| static readonly [CSS](../../groupdocs.viewer/filetype/css) | Cascading Style Sheet (.css) |
| static readonly [CSV](../../groupdocs.viewer/filetype/csv) | Comma Separated Values-fil (.csv) representerar enkla textfiler som innehåller datarader med kommaseparerade värden. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/csv). |
| static readonly [CXX](../../groupdocs.viewer/filetype/cxx) | C++-källkodfil (.cxx) |
| static readonly [DCM](../../groupdocs.viewer/filetype/dcm) | DICOM-bild (.dcm) representerar en digital bild som lagrar medicinsk information om patienter såsom MR, CT-skanningar och ultraljudsbilder. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/dcm). |
| static readonly [DGN](../../groupdocs.viewer/filetype/dgn) | MicroStation-designfil (.dgn) är ritningar som skapas av och stöds av CAD-program såsom MicroStation och Intergraph Interactive Graphics Design System. Läs mer om detta filformat [här](https://wiki.fileformat.com/cad/dgn). |
| static readonly [DIB](../../groupdocs.viewer/filetype/dib) | Device Independent Bitmap-fil (.dib) |
| static readonly [DIFF](../../groupdocs.viewer/filetype/diff) | Patchfil (.diff) |
| static readonly [DJVU](../../groupdocs.viewer/filetype/djvu) | DjVu-bild (.djvu) är ett grafikfilformat avsett för skannade dokument och böcker, särskilt de som innehåller en kombination av text, teckningar, bilder och fotografier. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/djvu). |
| static readonly [DNG](../../groupdocs.viewer/filetype/dng) | Digital Negative Specification (.dng) är ett bildformat för digitalkameror som används för lagring av råfiler. Det utvecklades av Adobe i september 2004. Det skapades i princip för digital fotografering. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/dng). |
| static readonly [DOC](../../groupdocs.viewer/filetype/doc) | Microsoft Word-dokument (.doc) representerar dokument som genereras av Microsoft Word eller andra ordbehandlingsprogram i binärt filformat. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [DOCM](../../groupdocs.viewer/filetype/docm) | Word Open XML-makroaktiverat dokument (.docm) är ett dokument som genereras av Microsoft Word 2007 eller senare med möjlighet att köra makron. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [DOCX](../../groupdocs.viewer/filetype/docx) | Microsoft Word Open XML-dokument (.docx) är ett välkänt format för Microsoft Word-dokument. Introducerat från 2007 med lanseringen av Microsoft Office 2007 förändrades strukturen för detta nya dokumentformat från rent binärt till en kombination av XML- och binära filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [DOT](../../groupdocs.viewer/filetype/dot) | Word-dokumentmall (.dot) är mallfiler som skapas av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOC- eller DOCX-filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [DOTM](../../groupdocs.viewer/filetype/dotm) | Word Open XML-makroaktiverad dokumentmall (.dotm) representerar en mallfil skapad med Microsoft Word 2007 eller senare. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [DOTX](../../groupdocs.viewer/filetype/dotx) | Word Open XML-dokumentmall (.dotx) är mallfiler som skapas av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOCX-filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [DWF](../../groupdocs.viewer/filetype/dwf) | Design Web Format-fil (.dwf) representerar 2D/3D-ritningar i komprimerat format för visning, granskning eller utskrift av designfiler. Den innehåller grafik och text som en del av designdata och minskar filens storlek på grund av sitt komprimerade format. Läs mer om detta filformat [här](https://wiki.fileformat.com/cad/dwf). |
| static readonly [DWFX](../../groupdocs.viewer/filetype/dwfx) | Design Web Format-fil XPS (.dwfx) representerar 2D/3D-ritningar som XPS-dokument i komprimerat format för visning, granskning eller utskrift av designfiler. Den innehåller grafik och text som en del av designdata och minskar filens storlek på grund av dess komprimerade format. Läs mer om detta filformat [här](https://wiki.fileformat.com/cad/dwfx). |
| static readonly [DWG](../../groupdocs.viewer/filetype/dwg) | AutoCAD Drawing Database File (.dwg) representerar proprietära binära filer som används för att innehålla 2D- och 3D-designdata. Till skillnad från DXF, som är ASCII-filer, representerar DWG det binära filformatet för CAD (Computer Aided Design)-ritningar. Läs mer om detta filformat [här](https://wiki.fileformat.com/cad/dwg). |
| static readonly [DWT](../../groupdocs.viewer/filetype/dwt) | AutoCAD Drawing Template (.dwt) är en AutoCAD-ritningsmallfil som används som start för att skapa ritningar som kan sparas som DWG-filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/cad/dwt). |
| static readonly [DXF](../../groupdocs.viewer/filetype/dxf) | Drawing Exchange Format File (.dxf) är en taggad datarapresentation av en AutoCAD-ritningsfil. Läs mer om detta filformat [här](https://wiki.fileformat.com/cad/dxf). |
| static readonly [EMF](../../groupdocs.viewer/filetype/emf) | Enhanced Windows Metafile (.emf) representerar grafiska bilder enhetsoberoende. EMF-metafiler består av variabelt långa poster i kronologisk ordning som kan återge den lagrade bilden efter parsning på vilken utskriftsenhet som helst. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/emf). |
| static readonly [EML](../../groupdocs.viewer/filetype/eml) | E‑Mail Message (.eml) representerar e‑postmeddelanden som sparats med Outlook och andra relevanta program. Nästan alla e‑postklienter stödjer detta filformat på grund av dess överensstämmelse med RFC‑822 Internet Message Format Standard. Läs mer om detta filformat [här](https://wiki.fileformat.com/email/eml). |
| static readonly [EMLX](../../groupdocs.viewer/filetype/emlx) | Apple Mail Message (.emlx) är implementerad och utvecklad av Apple. Apple Mail‑applikationen använder EMLX‑filformatet för att exportera e‑postmeddelanden. Läs mer om detta filformat [här](https://wiki.fileformat.com/email/emlx). |
| static readonly [EMZ](../../groupdocs.viewer/filetype/emz) | Enhanced Windows Metafile compressed (.emz) representerar grafiska bilder enhetsoberoende komprimerade med GZIP. EMF-metafiler består av variabelt långa poster i kronologisk ordning som kan återge den lagrade bilden efter parsning på vilken utskriftsenhet som helst. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/emz). |
| static readonly [EPS](../../groupdocs.viewer/filetype/eps) | Encapsulated PostScript File (.eps) beskriver ett Encapsulated PostScript-språkprogram som beskriver utseendet på en enskild sida. Läs mer om detta filformat [här](https://wiki.fileformat.com/page-description-language/eps). |
| static readonly [EPUB](../../groupdocs.viewer/filetype/epub) | Open eBook File (.epub) är ett e‑bokfilformat som tillhandahåller ett standardiserat digitalt publiceringsformat för förlag och konsumenter. Formatet har blivit så vanligt att det stöds av många e‑läsare och programvaror. Läs mer om detta filformat [här](https://wiki.fileformat.com/ebook/epub). |
| static readonly [ERB](../../groupdocs.viewer/filetype/erb) | Ruby ERB Script (.erb) |
| static readonly [Excel2003XML](../../groupdocs.viewer/filetype/excel2003xml) | Excel 2003 XML (SpreadsheetML) representerar Excel Binary File Format. Sådana filer kan skapas av Microsoft Excel såväl som andra liknande kalkylprogram som OpenOffice Calc eller Apple Numbers. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [FBX](../../groupdocs.viewer/filetype/fbx) | Autodesk FBX Interchange File (FilmBoX) (.fbx) representerar 3D-modellformat. Läs mer om detta filformat [här](https://wiki.fileformat.com/cad/fbx). |
| static readonly [FODG](../../groupdocs.viewer/filetype/fodg) | Flat XML ODF Template (.fodg) används av Apache OpenOffices Draw‑program för att lagra ritningselement som en vektorbild. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/fodg). |
| static readonly [FODP](../../groupdocs.viewer/filetype/fodp) | OpenDocument Presentation (.fodp) representerar OpenDocument Flat XML Presentation. Läs mer om detta filformat [här](https://fileinfo.com/extension/fodp). |
| static readonly [FODS](../../groupdocs.viewer/filetype/fods) | OpenDocument Flat XML‑kalkylblad (.fods) |
| static readonly [GIF](../../groupdocs.viewer/filetype/gif) | Graphical Interchange Format File (.gif) är en typ av starkt komprimerad bild. För varje bild tillåter GIF vanligtvis upp till 8 bitar per pixel och upp till 256 färger är tillåtna i hela bilden. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/gif). |
| static readonly [GROOVY](../../groupdocs.viewer/filetype/groovy) | Groovy källkodfil (.groovy) |
| static readonly [GZ](../../groupdocs.viewer/filetype/gz) | Gnu Zipped File (.gz) är komprimerade filer skapade med gzip‑komprimeringsprogram. Den kan innehålla flera komprimerade filer och används ofta på UNIX‑ och Linux‑system. Läs mer om detta filformat [här](https://wiki.fileformat.com/compression/gz). |
| static readonly [GZIP](../../groupdocs.viewer/filetype/gzip) | Gnu Zipped File (.gzip) introducerades som ett fritt verktyg för att ersätta Compress‑programmet som användes i Unix‑system. Sådana filer kan öppnas och extraheras med flera program såsom WinZip, som finns tillgängligt både på Windows och macOS. Läs mer om detta filformat [här](https://wiki.fileformat.com/compression/gz). |
| static readonly [H](../../groupdocs.viewer/filetype/h) | C/C++/Objective‑C huvudfil (.h) |
| static readonly [HAML](../../groupdocs.viewer/filetype/haml) | Haml källkodfil (.haml) |
| static readonly [HH](../../groupdocs.viewer/filetype/hh) | C++ huvudfil (.hh) |
| static readonly [HPG](../../groupdocs.viewer/filetype/hpg) | PLT (HPGL) (.hpg) |
| static readonly [HTM](../../groupdocs.viewer/filetype/htm) | Hypertext Markup Language‑fil (.htm) är filändelsen för webbsidor som skapats för visning i webbläsare. Läs mer om detta filformat [här](https://wiki.fileformat.com/web/html). |
| static readonly [HTML](../../groupdocs.viewer/filetype/html) | Hypertext Markup Language‑fil (.html) är filändelsen för webbsidor som skapats för visning i webbläsare. Läs mer om detta filformat [här](https://wiki.fileformat.com/web/html). |
| static readonly [ICO](../../groupdocs.viewer/filetype/ico) | Icon File (.ico) är bildfiltyper som används som ikon för att representera ett program på Microsoft Windows. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/ico). |
| static readonly [IFC](../../groupdocs.viewer/filetype/ifc) | Industry Foundation Classes‑fil (.ifc) är ett filformat som fastställer internationella standarder för import och export av byggnadsobjekt och deras egenskaper. Detta filformat möjliggör interoperabilitet mellan olika programvaror. Läs mer om detta filformat [här](https://wiki.fileformat.com/cad/ifc). |
| static readonly [IGS](../../groupdocs.viewer/filetype/igs) | Initial Graphics Exchange‑specifikation (IGES) (.igs) |
| static readonly [Iso](../../groupdocs.viewer/filetype/iso) | ISO‑optisk skivavbild är en okomprimerad arkivskivavbildningsfil som representerar innehållet av hela data på en optisk skiva såsom CD eller DVD, baserad på ISO‑9660‑standarden. Läs mer om detta filformat [här](https://docs.fileformat.com/compression/iso/). |
| static readonly [J2C](../../groupdocs.viewer/filetype/j2c) | JPEG 2000 kodström (.j2c) |
| static readonly [J2K](../../groupdocs.viewer/filetype/j2k) | JPEG 2000 kodström (.j2k) är en bild som komprimeras med vågforms‑komprimering istället för DCT‑komprimering. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/j2k). |
| static readonly [JAVA](../../groupdocs.viewer/filetype/java) | Java källkodfil (.java) |
| static readonly [JFIF](../../groupdocs.viewer/filetype/jfif) | JPEG File Interchange Format (.jfif) är en bild som utvecklades för snabb utbyte mellan plattformar. Detta format använder JPEG-komprimering. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/jfif). |
| static readonly [JLS](../../groupdocs.viewer/filetype/jls) | JPEG-LS (JLS) (.jls) |
| static readonly [JP2](../../groupdocs.viewer/filetype/jp2) | JPEG 2000 Core Image File (.jp2) är ett bildkodningssystem och en toppmodern bildkomprimeringsstandard. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/jp2). |
| static readonly [JPC](../../groupdocs.viewer/filetype/jpc) | JPEG 2000 Code Stream (.jpc) |
| static readonly [JPEG](../../groupdocs.viewer/filetype/jpeg) | JPEG Image (.jpeg) är en typ av bildformat som sparas med en förlustkomprimeringsmetod. Den resulterande bilden, som ett resultat av komprimeringen, är en avvägning mellan lagringsstorlek och bildkvalitet. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/jpeg). |
| static readonly [JPF](../../groupdocs.viewer/filetype/jpf) | JPEG 2000 Image File (.jpf) |
| static readonly [JPG](../../groupdocs.viewer/filetype/jpg) | JPEG Image (.jpg) är en typ av bildformat som sparas med en förlustkomprimeringsmetod. Den resulterande bilden, som ett resultat av komprimeringen, är en avvägning mellan lagringsstorlek och bildkvalitet. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/jpeg). |
| static readonly [JPM](../../groupdocs.viewer/filetype/jpm) | JPEG 2000 Image File (.jpm) |
| static readonly [JPX](../../groupdocs.viewer/filetype/jpx) | JPEG 2000 Image File (.jpx) |
| static readonly [JS](../../groupdocs.viewer/filetype/js) | JavaScript File (.js) |
| static readonly [JSON](../../groupdocs.viewer/filetype/json) | JavaScript Object Notation File (.json) |
| static readonly [LESS](../../groupdocs.viewer/filetype/less) | LESS Style Sheet (.less) |
| static readonly [Lha](../../groupdocs.viewer/filetype/lha) | LHA eller LZH är ett gratis komprimeringsverktyg och tillhörande filformat. Läs mer om detta filformat [här](https://docs.fileformat.com/compression/lzh/). |
| static readonly [LOG](../../groupdocs.viewer/filetype/log) | Log File (.log) |
| static readonly [M](../../groupdocs.viewer/filetype/m) | Objective-C Implementation File (.m) |
| static readonly [MAKE](../../groupdocs.viewer/filetype/make) | Xcode Makefile Script (.make) |
| static readonly [MBOX](../../groupdocs.viewer/filetype/mbox) | Email Mailbox File (.mbox) Läs mer om detta filformat [här](https://fileinfo.com/extension/mbox). |
| static readonly [MD](../../groupdocs.viewer/filetype/md) | Markdown Documentation File (.md) |
| static readonly [MHT](../../groupdocs.viewer/filetype/mht) | MHTML Web Archive (.mht) |
| static readonly [MHTML](../../groupdocs.viewer/filetype/mhtml) | MIME HTML File (.mhtml) |
| static readonly [ML](../../groupdocs.viewer/filetype/ml) | ML Source Code File (.ml) |
| static readonly [MM](../../groupdocs.viewer/filetype/mm) | Objective-C++ Source File (.mm) |
| static readonly [MOBI](../../groupdocs.viewer/filetype/mobi) | Mobipocket eBook (.mobi) är ett av de mest använda e-bokfilformaten. Formatet är en förbättring av det gamla OEB (Open Ebook Format)-formatet och användes som proprietärt format för Mobipocket Reader. Läs mer om detta filformat [här](https://wiki.fileformat.com/ebook/mobi). |
| static readonly [MPP](../../groupdocs.viewer/filetype/mpp) | Microsoft Project File (.mpp) är en Microsoft Project-datafil som lagrar information relaterad till projektledning på ett integrerat sätt. Läs mer om detta filformat [här](https://wiki.fileformat.com/project-management/mpp). |
| static readonly [MPT](../../groupdocs.viewer/filetype/mpt) | Microsoft Project Template (.mpt) innehåller grundläggande information och struktur samt dokumentinställningar för att skapa .MPP-filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/project-management/mpt). |
| static readonly [MPX](../../groupdocs.viewer/filetype/mpx) | Microsoft Project Exchange‑fil (.mpx) är ett ASCII‑filformat för överföring av projektinformation mellan Microsoft Project (MSP) och andra program som stöder MPX‑filformatet, såsom Primavera Project Planner, Sciforma och Timerline Precision Estimating. Läs mer om detta filformat [här](https://wiki.fileformat.com/project-management/mpx). |
| static readonly [MSG](../../groupdocs.viewer/filetype/msg) | Outlook‑e‑postmeddelande (.msg) är ett filformat som används av Microsoft Outlook och Exchange för att lagra e‑postmeddelanden, kontakter, möten eller andra uppgifter. Läs mer om detta filformat [här](https://wiki.fileformat.com/email/msg). |
| static readonly [NSF](../../groupdocs.viewer/filetype/nsf) | Lotus Notes‑databas (.nsf) Läs mer om detta filformat [här](https://fileinfo.com/extension/nsf). |
| static readonly [NUMBERS](../../groupdocs.viewer/filetype/numbers) | Apple Numbers representerar ett Excel‑likt binärt filformat. Sådana filer kan skapas av Apple Numbers‑applikationen. Läs mer om detta filformat [här](https://fileinfo.com/extension/numbers). |
| static readonly [OBJ](../../groupdocs.viewer/filetype/obj) | Wavefront 3D‑objektfil (.obj) är en 3D‑bildfil som introducerades av Wavefront Technologies. Läs mer om detta filformat [här](https://wiki.fileformat.com/3d/obj/). |
| static readonly [ODG](../../groupdocs.viewer/filetype/odg) | OpenDocument‑grafikfil (.odg) används av Apache OpenOffice Draw‑applikationen för att lagra ritningselement som en vektorbild. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/odg). |
| static readonly [ODP](../../groupdocs.viewer/filetype/odp) | OpenDocument‑presentation (.odp) representerar presentationsfilformatet som används av OpenOffice.org i OASIS‑standard. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/odp). |
| static readonly [ODS](../../groupdocs.viewer/filetype/ods) | OpenDocument‑kalkylblad (.ods) står för OpenDocument Spreadsheet‑dokumentformat som kan redigeras av användaren. Data lagras i ODF‑filen i rader och kolumner. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [ODT](../../groupdocs.viewer/filetype/odt) | OpenDocument‑textdokument (.odt) är en typ av dokument som skapas med ordbehandlingsprogram baserade på OpenDocument Text‑filformatet. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [OFD](../../groupdocs.viewer/filetype/ofd) | Open Fixed‑layout‑dokument (OFD)-formatet, definierat av GB/T 33190-2016, syftar till att ersätta PDF i kinesiska offentliga institutioner. |
| static readonly [OST](../../groupdocs.viewer/filetype/ost) | Outlook Offline Data File (.ost) representerar användarens brevlådedata i offline‑läge på den lokala maskinen efter registrering med Exchange Server via Microsoft Outlook. Läs mer om detta filformat [här](https://wiki.fileformat.com/email/ost). |
| static readonly [OTG](../../groupdocs.viewer/filetype/otg) | OpenDocument‑grafikmall (.otg) |
| static readonly [OTP](../../groupdocs.viewer/filetype/otp) | OpenDocument‑presentationmall (.otp) representerar presentationsmallar som skapas av program i OASIS OpenDocument‑standardformatet. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/otp). |
| static readonly [OTS](../../groupdocs.viewer/filetype/ots) | OpenDocument‑kalkylblads‑mall (.ots) |
| static readonly [OTT](../../groupdocs.viewer/filetype/ott) | OpenDocument‑dokumentmall (.ott) representerar mall‑dokument som genereras av program i enlighet med OASIS OpenDocument‑standardformatet. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [OXPS](../../groupdocs.viewer/filetype/oxps) | OpenXPS‑fil (.oxps) |
| static readonly [PCL](../../groupdocs.viewer/filetype/pcl) | Printer Command Language‑dokument (.pcl) |
| static readonly [PDF](../../groupdocs.viewer/filetype/pdf) | Portable Document Format File (.pdf) är en typ av dokument som skapades av Adobe på 1990-talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av programvara, hårdvara samt operativsystem. Läs mer om detta filformat [här](https://wiki.fileformat.com/view/pdf). |
| static readonly [PHP](../../groupdocs.viewer/filetype/php) | PHP Källkodfil (.php) |
| static readonly [PL](../../groupdocs.viewer/filetype/pl) | Perl-skript (.pl) |
| static readonly [PLT](../../groupdocs.viewer/filetype/plt) | PLT (HPGL) (.plt) är en vektorbaserad plotterfil som introducerades av Autodesk, Inc. och innehåller information för en viss CAD-fil. Plottdetaljer kräver noggrannhet och precision i produktionen, och användning av PLT-filen garanterar detta eftersom alla bilder skrivs ut med linjer istället för punkter. Läs mer om detta filformat [här](https://wiki.fileformat.com/cad/plt). |
| static readonly [PNG](../../groupdocs.viewer/filetype/png) | Portable Network Graphic (.png) är en typ av rasterbildfilformat som använder förlustfri kompression. Detta filformat skapades som en ersättning för Graphics Interchange Format (GIF) och har inga upphovsrättsliga begränsningar. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/png). |
| static readonly [POT](../../groupdocs.viewer/filetype/pot) | PowerPoint-mallen (.pot) representerar Microsoft PowerPoint-mallfiler som skapades av PowerPoint‑versionerna 97‑2003. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/pot). |
| static readonly [POTM](../../groupdocs.viewer/filetype/potm) | PowerPoint Open XML Makro‑aktiverad presentationsmall (.potm) är Microsoft PowerPoint‑mallfiler med stöd för makron. POTM‑filer skapas med PowerPoint 2007 eller senare och innehåller standardinställningar som kan användas för att skapa ytterligare presentationsfiler. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/potm). |
| static readonly [POTX](../../groupdocs.viewer/filetype/potx) | PowerPoint Open XML presentationsmall (.potx) representerar Microsoft PowerPoint‑mallpresentationer som skapas med Microsoft PowerPoint 2007 och senare. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/potx). |
| static readonly [PPS](../../groupdocs.viewer/filetype/pps) | PowerPoint‑bildspel (.pps) skapas med Microsoft PowerPoint för bildspelsändamål. PPS‑filens läsning och skapande stöds av Microsoft PowerPoint 97‑2003. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/pps). |
| static readonly [PPSM](../../groupdocs.viewer/filetype/ppsm) | PowerPoint Open XML Makro‑aktiverad bildspel (.ppsm) representerar makro‑aktiverat bildspelsfilformat skapat med Microsoft PowerPoint 2007 eller senare. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [PPSX](../../groupdocs.viewer/filetype/ppsx) | PowerPoint Open XML bildspel (.ppsx)‑filer skapas med Microsoft PowerPoint 2007 och senare för bildspelsändamål. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [PPT](../../groupdocs.viewer/filetype/ppt) | PowerPoint‑presentation (.ppt) representerar en PowerPoint‑fil som består av en samling bilder för visning som bildspel. Den specificerar det binära filformatet som används av Microsoft PowerPoint 97‑2003. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [PPTM](../../groupdocs.viewer/filetype/pptm) | PowerPoint Open XML Makro‑aktiverad presentation är makro‑aktiverade presentationsfiler som skapas med Microsoft PowerPoint 2007 eller senare versioner. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [PPTX](../../groupdocs.viewer/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) är presentationsfiler som skapats med det populära Microsoft PowerPoint-programmet. Till skillnad från den tidigare versionen av presentationsfilformatet PPT som var binärt, är PPTX-formatet baserat på Microsoft PowerPoints öppna XML‑presentationsfilformat. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/pptx). |
| static readonly [PROPERTIES](../../groupdocs.viewer/filetype/properties) | Java‑egenskapsfil (.properties) |
| static readonly [PS](../../groupdocs.viewer/filetype/ps) | PostScript‑fil (.ps) |
| static readonly [PS1](../../groupdocs.viewer/filetype/ps1) | PowerShell‑skriptfil (.ps1) är ett filformat för Windows PowerShell‑Cmdlet‑filer. Läs mer om detta filformat [här](https://fileinfo.com/extension/ps1). |
| static readonly [PSD1](../../groupdocs.viewer/filetype/psd1) | PowerShell‑skriptmodulmanifest (.psd1) är ett filformat för PowerShell‑modulmanifest‑skript. Läs mer om detta filformat [här](https://fileinfo.com/extension/psd1). |
| static readonly [PSM1](../../groupdocs.viewer/filetype/psm1) | PowerShell‑skriptmodul (.psm1) är ett filformat för PowerShell‑modul‑skript. Läs mer om detta filformat [här](https://fileinfo.com/extension/psm1). |
| static readonly [PST](../../groupdocs.viewer/filetype/pst) | Outlook Personal Information Store‑fil (.pst) representerar Outlook Personal Storage‑filer (även kallade Personal Storage Table) som lagrar en mängd användarinformation. Läs mer om detta filformat [här](https://wiki.fileformat.com/email/pst). |
| static readonly [PY](../../groupdocs.viewer/filetype/py) | Python‑skript (.py) |
| static readonly [RAR](../../groupdocs.viewer/filetype/rar) | Roshal ARchive (.rar) är komprimerade filer som genererats med RAR‑komprimeringsmetoden (WINRAR). Läs mer om detta filformat [här](https://wiki.fileformat.com/compression/rar). |
| static readonly [RB](../../groupdocs.viewer/filetype/rb) | Ruby‑källkod (.rb) |
| static readonly [RST](../../groupdocs.viewer/filetype/rst) | reStructuredText‑fil (.rst) |
| static readonly [RTF](../../groupdocs.viewer/filetype/rtf) | Rich Text Format‑fil (.rtf) representerar en metod för att koda formaterad text och grafik för användning i applikationer. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [SASS](../../groupdocs.viewer/filetype/sass) | Syntactically Awesome StyleSheets‑fil (.sass) |
| static readonly [SCALA](../../groupdocs.viewer/filetype/scala) | Scala‑källkodfil (.scala) |
| static readonly [SCM](../../groupdocs.viewer/filetype/scm) | Scheme‑källkodfil (.scm) |
| static readonly [SCRIPT](../../groupdocs.viewer/filetype/script) | Generisk skriptfil (.script) |
| static readonly [SevenZip](../../groupdocs.viewer/filetype/sevenzip) | 7Zip (.7z, .7zip) är en fri öppen källkodsarkiverare med LZMA‑ och LZMA2‑komprimering. Läs mer om detta filformat [här](https://docs.fileformat.com/compression/7z/). |
| static readonly [SH](../../groupdocs.viewer/filetype/sh) | Bash‑skalskript (.sh) |
| static readonly [SML](../../groupdocs.viewer/filetype/sml) | Standard ML‑källkodfil (.sml) |
| static readonly [SQL](../../groupdocs.viewer/filetype/sql) | Structured Query Language‑datafil (.sql) |
| static readonly [STL](../../groupdocs.viewer/filetype/stl) | Stereolithography‑fil (.stl) är ett utbytbart filformat som representerar tredimensionell ytgometri. Filformatet används inom flera områden såsom snabb prototypframtagning, 3D‑utskrift och datorstödd tillverkning. Läs mer om detta filformat [här](https://wiki.fileformat.com/cad/stl). |
| static readonly [SVG](../../groupdocs.viewer/filetype/svg) | Scalable Vector Graphics‑fil (.svg) är en Scalable Vector Graphics‑fil som använder ett XML‑baserat textformat för att beskriva en bilds utseende. Läs mer om detta filformat [här](https://wiki.fileformat.com/page-description-language/svg). |
| static readonly [SVGZ](../../groupdocs.viewer/filetype/svgz) | Scalable Vector Graphics‑fil (.svgz) är en Scalable Vector Graphics‑fil som använder ett XML‑baserat textformat, komprimerat med GZIP, för att beskriva en bilds utseende. Läs mer om detta filformat [här](https://fileinfo.com/extension/svgz). |
| static readonly [SXC](../../groupdocs.viewer/filetype/sxc) | StarOffice Calc‑kalkylblad (.sxc) |
| static readonly [TAR](../../groupdocs.viewer/filetype/tar) | Consolidated Unix File‑arkiv (.tar) är arkiv som skapats med ett Unix‑baserat verktyg för att samla en eller flera filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/compression/tar). |
| static readonly [TARGZ](../../groupdocs.viewer/filetype/targz) | Konsoliderat Unix-filarkiv (.tgz, .tar.gz) är arkiv som skapats med ett Unix-baserat verktyg för att samla en eller flera filer. Läs mer om detta filformat [här](https://fileinfo.com/extension/tgz). |
| static readonly [TARXZ](../../groupdocs.viewer/filetype/tarxz) | Konsoliderat Unix-filarkiv (.txz, .tar.xz) är arkiv som skapats med ett Unix-baserat verktyg för att samla en eller flera filer. Läs mer om detta filformat [här](https://fileinfo.com/extension/txz). |
| static readonly [TarZst](../../groupdocs.viewer/filetype/tarzst) | TZST-filer (.tar.zst, .tzst) är Zstandard-arkiv (ZST), som internt innehåller ett konsoliderat Unix-filarkiv (Tar), skapat med ett Unix-baserat verktyg för att samla en eller flera filer. |
| static readonly [TEX](../../groupdocs.viewer/filetype/tex) | LaTeX-källdokument (.tex) är ett språk som omfattar både programmerings- och markup-funktioner, och används för att sätta dokument. Läs mer om detta filformat [här](https://wiki.fileformat.com/page-description-language/tex). |
| static readonly [TGA](../../groupdocs.viewer/filetype/tga) | Truevision TGA (Truevision Advanced Raster Adapter - TARGA) används för att lagra bitmapdigitala bilder utvecklade av TRUEVISION. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/tga). |
| static readonly [TGZ](../../groupdocs.viewer/filetype/tgz) | Konsoliderat Unix-filarkiv (.tgz, .tar.gz) är arkiv som skapats med ett Unix-baserat verktyg för att samla en eller flera filer. Läs mer om detta filformat [här](https://fileinfo.com/extension/tgz). |
| static readonly [TIF](../../groupdocs.viewer/filetype/tif) | Tagged Image File (.tif) representerar rasterbilder som är avsedda för användning på en mängd olika enheter som följer denna filformatstandard. Den kan beskriva tvånivå-, gråskala-, palettfärg- och fullfärgsbilddata i flera färgrymder. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/tiff). |
| static readonly [TIFF](../../groupdocs.viewer/filetype/tiff) | Tagged Image File Format (.tiff) representerar rasterbilder som är avsedda för användning på en mängd olika enheter som följer denna filformatstandard. Den kan beskriva tvånivå-, gråskala-, palettfärg- och fullfärgsbilddata i flera färgrymder. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/tiff). |
| static readonly [TSV](../../groupdocs.viewer/filetype/tsv) | Tabbseparerade värden-fil (.tsv) representerar data separerade med tabbar i ett vanligt textformat. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/tsv). |
| static readonly [TXT](../../groupdocs.viewer/filetype/txt) | Vanlig textfil (.txt) representerar ett textdokument som innehåller ren text i form av rader. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/txt). |
| static readonly [TXZ](../../groupdocs.viewer/filetype/txz) | Konsoliderat Unix-filarkiv (.txz, .tar.xz) är arkiv som skapats med ett Unix-baserat verktyg för att samla en eller flera filer. Läs mer om detta filformat [här](https://fileinfo.com/extension/txz). |
| static readonly [Tzst](../../groupdocs.viewer/filetype/tzst) | TZST-filer (.tar.zst, .tzst) är Zstandard-arkiv (ZST), som internt innehåller ett konsoliderat Unix-filarkiv (Tar), skapat med ett Unix-baserat verktyg för att samla en eller flera filer. |
| static readonly [Unknown](../../groupdocs.viewer/filetype/unknown) | Representerar okänd filtyp. |
| static readonly [VB](../../groupdocs.viewer/filetype/vb) | Visual Basic Project Item File (.vb) är en källkodfil skapad i Visual Basic-språket som utvecklats av Microsoft för utveckling av .NET-applikationer. Läs mer om detta filformat [här](https://wiki.fileformat.com/programming/vb). |
| static readonly [VCF](../../groupdocs.viewer/filetype/vcf) | vCard-fil (.vcf) är ett digitalt filformat för lagring av kontaktinformation. Formatet används i stor utsträckning för datautbyte mellan populära informationsutbytesprogram. Läs mer om detta filformat [här](https://wiki.fileformat.com/email/vcf). |
| static readonly [VDW](../../groupdocs.viewer/filetype/vdw) | Visio Web Drawing (.vdw) representerar ett filformat som specificerar de strömmar och lagringar som krävs för att rendera en webbteckning. Läs mer om detta filformat [här](https://wiki.fileformat.com/web/vdw). |
| static readonly [VDX](../../groupdocs.viewer/filetype/vdx) | Visio Drawing XML File (.vdx) representerar alla teckningar eller diagram som skapats i Microsoft Visio, men sparats i XML-format med .VDX‑ändelse. En Visio‑teckning i XML‑format skapas i Visio‑programvaran, som utvecklats av Microsoft. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vdx). |
| static readonly [VIM](../../groupdocs.viewer/filetype/vim) | Vim-inställningsfil (.vim) |
| static readonly [VSD](../../groupdocs.viewer/filetype/vsd) | Visio Drawing File (.vsd) är ritningar som skapats med Microsoft Visio‑applikationen för att representera en mängd grafiska objekt och deras sammankoppling. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vsd). |
| static readonly [VSDM](../../groupdocs.viewer/filetype/vsdm) | Visio Macro-Enabled Drawing (.vsdm) är ritningsfiler som skapats med Microsoft Visio‑applikationen och som stödjer makron. VSDM‑filer är OPC/XML‑ritningar som liknar VSDX, men som också ger möjlighet att köra makron när filen öppnas. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vsdm). |
| static readonly [VSDX](../../groupdocs.viewer/filetype/vsdx) | Visio Drawing (.vsdx) representerar Microsoft Visio‑filformatet som introducerades från Microsoft Office 2013 och framåt. Det utvecklades för att ersätta det binära filformatet .VSD, som stöddes av tidigare versioner av Microsoft Visio. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vsdx). |
| static readonly [VSS](../../groupdocs.viewer/filetype/vss) | Visio Stencil File(.vss) är stencelfiler som skapats med Microsoft Visio 2007 och tidigare. Stencelfiler tillhandahåller ritningsobjekt som kan inkluderas i en .VSD Visio‑ritning. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vss). |
| static readonly [VSSM](../../groupdocs.viewer/filetype/vssm) | Visio Macro-Enabled Stencil File (.vssm) är Microsoft Visio‑stencelfiler som ger stöd för makron. En VSSM‑fil låter, när den öppnas, köra makron för att uppnå önskad formatering och placering av former i ett diagram. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vssm). |
| static readonly [VSSX](../../groupdocs.viewer/filetype/vssx) | Visio Stencil File (.vssx) är ritningsstenciler som skapats med Microsoft Visio 2013 och senare. VSSX‑filformatet kan öppnas med Visio 2013 och senare. Visio‑filer är kända för att representera en mängd ritningselement såsom samlingar av former, anslutningar, flödesscheman, nätverkslayouter, UML‑diagram. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vssx). |
| static readonly [VST](../../groupdocs.viewer/filetype/vst) | Visio Drawing Template (.vst) är vektorbildfiler som skapats med Microsoft Visio och fungerar som mall för att skapa ytterligare filer. Dessa mallfiler är i binärt filformat och innehåller standardlayouten och -inställningarna som används för att skapa nya Visio‑ritningar. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vst). |
| static readonly [VSTM](../../groupdocs.viewer/filetype/vstm) | Visio Macro-Enabled Drawing Template (.vstm) är mallfiler som skapats med Microsoft Visio och som stödjer makron. Till skillnad från VSDX‑filer kan filer som skapas från VSTM‑mallar köra makron som utvecklats i Visual Basic for Applications (VBA)-kod. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vstm). |
| static readonly [VSTX](../../groupdocs.viewer/filetype/vstx) | Visio Drawing Template (.vstx) är ritningsmallfiler som skapats med Microsoft Visio 2013 och senare. Dessa VSTX‑filer ger en startpunkt för att skapa Visio‑ritningar, sparade som .VSDX‑filer, med standardlayout och -inställningar. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vstx). |
| static readonly [VSX](../../groupdocs.viewer/filetype/vsx) | Visio Stencil XML File (.vsx) avser stenciler som består av ritningar och former som används för att skapa diagram i Microsoft Visio. VSX‑filer sparas i XML‑filformat och stöddes fram till Visio 2013. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vsx). |
| static readonly [VTX](../../groupdocs.viewer/filetype/vtx) | Visio Template XML File (.vtx) är en Microsoft Visio-ritmall som sparas på disk i XML-filformat. Mallen är avsedd att tillhandahålla en fil med grundinställningar som kan användas för att skapa flera Visio-filer med samma inställningar. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vtx). |
| static readonly [WEBP](../../groupdocs.viewer/filetype/webp) | WebP Image (.webp) är ett modernt rasterwebbbildfilformat som baseras på förlustfri och förlustkomprimering. Det ger samma bildkvalitet samtidigt som bildstorleken minskas avsevärt. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/webp). |
| static readonly [WMF](../../groupdocs.viewer/filetype/wmf) | Windows Metafile (.wmf) representerar Microsoft Windows Metafile (WMF) för lagring av både vektor- och bitmapformatbilder. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/wmf). |
| static readonly [WMZ](../../groupdocs.viewer/filetype/wmz) | Compressed Windows Metafile (.wmz) representerar Microsoft Windows Metafile (WMF) komprimerad i GZIP-arkiv – för lagring av både vektor- och bitmapformatbilder. Läs mer om detta filformat [här](https://fileinfo.com/extension/wmz#compressed_windows_metafile). |
| static readonly [XLAM](../../groupdocs.viewer/filetype/xlam) | Microsoft Excel-tillägg (.xlam) |
| static readonly [XLS](../../groupdocs.viewer/filetype/xls) | Excel Spreadsheet (.xls) representerar Excel Binary File Format. Sådana filer kan skapas av Microsoft Excel såväl som andra liknande kalkylprogram som OpenOffice Calc eller Apple Numbers. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [XLSB](../../groupdocs.viewer/filetype/xlsb) | Excel Binary Spreadsheet (.xlsb) specificerar Excel Binary File Format, som är en samling poster och strukturer som specificerar innehållet i en Excel-arbetsbok. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [XLSM](../../groupdocs.viewer/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) är en typ av kalkylbladsfiler som stödjer makron. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [XLSX](../../groupdocs.viewer/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) är ett välkänt format för Microsoft Excel-dokument som introducerades av Microsoft med lanseringen av Microsoft Office 2007. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [XLT](../../groupdocs.viewer/filetype/xlt) | Microsoft Excel Template (.xlt) är mallfiler som skapats med Microsoft Excel, ett kalkylprogram som ingår i Microsoft Office-paketet. Microsoft Office 97-2003 stödde att skapa nya XLT-filer samt att öppna dem. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [XLTM](../../groupdocs.viewer/filetype/xltm) | Microsoft Excel Macro-Enabled Template (.xltm) representerar filer som genereras av Microsoft Excel som makroaktiverade mallfiler. XLTM-filer liknar XLTX i struktur förutom att den senare inte stödjer att skapa mallfiler med makron. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [XLTX](../../groupdocs.viewer/filetype/xltx) | Excel Open XML Spreadsheet Template (.xltx) representerar Microsoft Excel Template som är baserade på Office OpenXML-filformatspecifikationerna. Den används för att skapa en standardmallfil som kan användas för att generera XLSX-filer som har samma inställningar som specificeras i XLTX-filen. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/xltx). |
| static readonly [XML](../../groupdocs.viewer/filetype/xml) | XML‑fil (.xml). GroupDocs.Viewer har en speciell processor för att hantera XML‑filer, se [dokumentation](https://docs.groupdocs.com/viewer/net/render-xml-documents/). |
| static readonly [XPS](../../groupdocs.viewer/filetype/xps) | XML Paper Specification‑fil (.xps) representerar sidlayoutfiler som är baserade på XML Paper Specifications skapade av Microsoft. Detta format utvecklades av Microsoft som en ersättning för EMF‑filformatet och är likt PDF‑filformatet, men använder XML i layout, utseende och utskriftsinformation för ett dokument. Läs mer om detta filformat [här](https://wiki.fileformat.com/page-description-language/xps). |
| static readonly [XZ](../../groupdocs.viewer/filetype/xz) | XZ‑fil (.xz) är ett arkiv komprimerat med en högkomprimeringsalgoritm baserad på LZMA‑algoritmen. Läs mer om detta filformat [här](https://fileinfo.com/extension/xz). |
| static readonly [YAML](../../groupdocs.viewer/filetype/yaml) | YAML‑dokument (.yaml) |
| static readonly [ZIP](../../groupdocs.viewer/filetype/zip) | Komprimerad fil (.zip) representerar arkiv som kan innehålla en eller flera filer eller kataloger. Läs mer om detta filformat [här](https://wiki.fileformat.com/compression/zip). |
| static readonly [Zstandard](../../groupdocs.viewer/filetype/zstandard) | ZST‑fil är en komprimerad fil som genereras med Zstandard‑algoritmen (zstd). Det är en komprimerad fil som skapas med förlustfri kompression av algoritmen. ZST‑filer kan användas för att komprimera olika typer av filer såsom databaser, filsystem, nätverk och spel. Läs mer om detta filformat [här](https://docs.fileformat.com/compression/zst/). |

### Se även

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
