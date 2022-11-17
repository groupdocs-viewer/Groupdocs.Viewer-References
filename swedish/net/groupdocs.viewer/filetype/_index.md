---
title: FileType
second_title: GroupDocs.Viewer för .NET API-referens
description: Representerar filtyp. Ger metoder för att få en lista över alla filtyper som stöds avGroupDocs.Viewer .
type: docs
weight: 70
url: /sv/net/groupdocs.viewer/filetype/
---
## FileType class

Representerar filtyp. Ger metoder för att få en lista över alla filtyper som stöds av**GroupDocs.Viewer** .

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Extension](../../groupdocs.viewer/filetype/extension) { get; } | Filnamnssuffix (inklusive perioden ".") t.ex. ".doc". |
| [FileFormat](../../groupdocs.viewer/filetype/fileformat) { get; } | Filtypsnamn t.ex. "Microsoft Word Document". |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromExtension](../../groupdocs.viewer/filetype/fromextension)(string) | Mappar filtillägget till filtyp. |
| static [FromFilePath](../../groupdocs.viewer/filetype/fromfilepath)(string) | Extraherar filtillägget och mappar det till filtyp. |
| static [FromMediaType](../../groupdocs.viewer/filetype/frommediatype)(string) | Mappar filmediatyp till filtyp, t.ex. "applikation/pdf" kommer att mappas till[`PDF`](./pdf) . |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream)(Stream) | Upptäcker filtyp genom att läsa filsignaturen. |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_1)(Stream, ILogger) | Upptäcker filtyp genom att läsa filsignaturen. |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_2)(Stream, string) | Upptäcker filtyp genom att läsa filsignaturen. |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_3)(Stream, string, ILogger) | Upptäcker filtyp genom att läsa filsignaturen. |
| [Equals](../../groupdocs.viewer/filetype/equals#equals)(FileType) | Bestämmer om strömmen[`FileType`](../filetype)är samma som specificerats[`FileType`](../filetype) objekt. |
| override [Equals](../../groupdocs.viewer/filetype/equals#equals_1)(object) | Bestämmer om strömmen[`FileType`](../filetype) är samma som specificerat objekt. |
| override [GetHashCode](../../groupdocs.viewer/filetype/gethashcode)() | Returnerar hashkoden för den aktuella[`FileType`](../filetype) objekt. |
| override [ToString](../../groupdocs.viewer/filetype/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |
| static [GetSupportedFileTypes](../../groupdocs.viewer/filetype/getsupportedfiletypes)() | Hämtar filtyper som stöds |
| [operator ==](../../groupdocs.viewer/filetype/op_equality) | Bestämmer om två[`FileType`](../filetype) objekten är desamma. |
| [operator !=](../../groupdocs.viewer/filetype/op_inequality) | Bestämmer om två[`FileType`](../filetype) objekt är inte samma sak. |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [AI](../../groupdocs.viewer/filetype/ai) | Adobe Illustrator (.ai) är ett filformat för Adobe Illustrator-ritningar. Läs mer om detta filformat[här](https://fileinfo.com/extension/ai#adobe_illustrator_file) . |
| static readonly [APNG](../../groupdocs.viewer/filetype/apng) | Animated Portable Network Graphic (.apng) är en förlängning av PNG-format som stöder animering. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/apng) . |
| static readonly [AS](../../groupdocs.viewer/filetype/as) | ActionScript-fil (.as) |
| static readonly [AS3](../../groupdocs.viewer/filetype/as3) | ActionScript-fil (.as) |
| static readonly [ASM](../../groupdocs.viewer/filetype/asm) | Assembly Language Källkodsfil (.asm) |
| static readonly [BAT](../../groupdocs.viewer/filetype/bat) | DOS-batchfil (.bat) |
| static readonly [BMP](../../groupdocs.viewer/filetype/bmp) | Bitmappsbildfil (.bmp) används för att lagra digitala bitmappsbilder. Dessa bilder är oberoende av grafikkort och kallas även enhetsoberoende bitmapps (DIB) filformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/bmp) . |
| static readonly [BZ2](../../groupdocs.viewer/filetype/bz2) | Bzip2 Compressed File (.bz2) är komprimerade filer som genereras med BZIP2 open source-komprimeringsmetoden, mestadels på UNIX- eller Linux-system. Läs mer om detta filformat[här](https://wiki.fileformat.com/compression/bz2) . |
| static readonly [C](../../groupdocs.viewer/filetype/c) | C/C++ källkodsfil (.c) |
| static readonly [CC](../../groupdocs.viewer/filetype/cc) | C++ källkodsfil (.cc) |
| static readonly [CDR](../../groupdocs.viewer/filetype/cdr) | CorelDraw Vector Graphic Drawing (.cdr) är en vektorritningsbildfil som skapas med CorelDRAW för att lagra digitala bilder kodade och komprimerade. En sådan ritfil innehåller text, linjer, former, bilder, färger och effekter för vektorrepresentation av bildinnehåll. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/cdr) . |
| static readonly [CF2](../../groupdocs.viewer/filetype/cf2) | Vanligt filformat File Läs mer om detta filformat[här](https://fileinfo.com/extension/cf2) . |
| static readonly [CGM](../../groupdocs.viewer/filetype/cgm) | Computer Graphics Metafile (.cgm) är ett gratis, plattformsoberoende, internationellt standardmetafilformat för lagring och utbyte av vektorgrafik (2D), rastergrafik och text. CGM använder ett objektorienterat tillvägagångssätt och många funktioner för bildproduktion. Läs mer om detta filformat[här](https://wiki.fileformat.com/page-description-language/cgm) . |
| static readonly [CHM](../../groupdocs.viewer/filetype/chm) | Microsoft Compiled HTML Help File (.chm) är ett välkänt format för HELP-dokument (dokumentation till vissa program). Läs mer om detta filformat[här](https://docs.fileformat.com/web/chm/) . |
| static readonly [CMAKE](../../groupdocs.viewer/filetype/cmake) | CMake-fil (.cmake) |
| static readonly [CMX](../../groupdocs.viewer/filetype/cmx) | Corel Exchange (.cmx) är en ritbildsfil som kan innehålla såväl vektorgrafik som bitmappsgrafik. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/cmx) . |
| static readonly [CPP](../../groupdocs.viewer/filetype/cpp) | C++ källkodsfil (.cpp) |
| static readonly [CS](../../groupdocs.viewer/filetype/cs) | C# källkodsfil (.cs) är en källkodsfil för programmeringsspråket C#. Introducerad av Microsoft för användning med .NET Framework. Läs mer om detta filformat[här](https://wiki.fileformat.com/programming/cs) . |
| static readonly [CSS](../../groupdocs.viewer/filetype/css) | Cascading Style Sheet (.css) |
| static readonly [CSV](../../groupdocs.viewer/filetype/csv) | Comma Separated Values File (.csv) representerar vanliga textfiler som innehåller dataposter med kommaseparerade värden. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [CXX](../../groupdocs.viewer/filetype/cxx) | C++ källkodsfil (.cxx) |
| static readonly [DCM](../../groupdocs.viewer/filetype/dcm) | DICOM-bild (.dcm) representerar en digital bild som lagrar medicinsk information om patienter som MRI, datortomografi och ultraljudsbilder. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/dcm) . |
| static readonly [DGN](../../groupdocs.viewer/filetype/dgn) | MicroStation Design File (.dgn) är ritningar skapade av och stöds av CAD-applikationer som MicroStation och Intergraph Interactive Graphics Design System. Läs mer om detta filformat[här](https://wiki.fileformat.com/cad/dgn) . |
| static readonly [DIB](../../groupdocs.viewer/filetype/dib) | Enhetsoberoende bitmappsfil (.dib) |
| static readonly [DIFF](../../groupdocs.viewer/filetype/diff) | Patch-fil (.diff) |
| static readonly [DJVU](../../groupdocs.viewer/filetype/djvu) | DjVu Image (.djvu) är ett grafikfilformat avsett för skannade dokument och böcker, särskilt de som innehåller en kombination av text, teckningar, bilder och fotografier. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/djvu) . |
| static readonly [DNG](../../groupdocs.viewer/filetype/dng) | Digital Negative Specification (.dng) är ett digitalkamerabildformat som används för lagring av råfiler. Den har utvecklats av Adobe i september 2004. Den utvecklades i princip för digital fotografering. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/dng) . |
| static readonly [DOC](../../groupdocs.viewer/filetype/doc) | Microsoft Word-dokument (.doc) representerar dokument som genererats av Microsoft Word eller andra ordbehandlingsdokument i binärt filformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [DOCM](../../groupdocs.viewer/filetype/docm) | Word Open XML Macro-Enabled Document (.docm) är ett Microsoft Word 2007 eller högre genererat dokument med förmågan att köra makron. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [DOCX](../../groupdocs.viewer/filetype/docx) | Microsoft Word Open XML Document (.docx) är ett välkänt format för Microsoft Word-dokument. Introducerad från 2007 med lanseringen av Microsoft Office 2007, ändrades strukturen för detta nya dokumentformat från vanligt binärt till en kombination av XML och binära filer. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [DOT](../../groupdocs.viewer/filetype/dot) | Word-dokumentmall (.dot) är mallfiler skapade av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOC- eller DOCX-filer. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [DOTM](../../groupdocs.viewer/filetype/dotm) | Word Open XML Macro-Enabled Document Template (.dotm) representerar mallfil skapad med Microsoft Word 2007 eller högre. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [DOTX](../../groupdocs.viewer/filetype/dotx) | Word Open XML Document Template (.dotx) är mallfiler skapade av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOCX-filer. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [DWF](../../groupdocs.viewer/filetype/dwf) | Design Web Format File (.dwf) representerar 2D/3D-ritning i komprimerat format för att visa, granska eller skriva ut designfiler. Den innehåller grafik och text som en del av designdata och minskar storleken på filen på grund av dess komprimerade format. Läs mer om detta filformat[här](https://wiki.fileformat.com/cad/dwf) . |
| static readonly [DWG](../../groupdocs.viewer/filetype/dwg) | AutoCAD Drawing Database File (.dwg) representerar proprietära binära filer som används för att innehålla 2D- och 3D-designdata. Liksom DXF, som är ASCII-filer, representerar DWG det binära filformatet för CAD-ritningar (Computer Aided Design). Läs mer om detta filformat[här](https://wiki.fileformat.com/cad/dwg) . |
| static readonly [DWT](../../groupdocs.viewer/filetype/dwt) | AutoCAD Drawing Template (.dwt) är en AutoCAD ritmallsfil som används som start för att skapa ritningar som kan sparas som DWG-filer. Läs mer om detta filformat[här](https://wiki.fileformat.com/cad/dwt) . |
| static readonly [DXF](../../groupdocs.viewer/filetype/dxf) | Drawing Exchange Format File (.dxf) är en taggad datarepresentation av AutoCAD-ritningsfil. Läs mer om detta filformat[här](https://wiki.fileformat.com/cad/dxf) . |
| static readonly [EMF](../../groupdocs.viewer/filetype/emf) | Enhanced Windows Metafile (.emf) representerar grafiska bilder enhetsoberoende. Metafiler av EMF består av poster med variabel längd i kronologisk ordning som kan återge den lagrade bilden efter analys på valfri utenhet. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/emf) . |
| static readonly [EML](../../groupdocs.viewer/filetype/eml) | E-postmeddelande (.eml) representerar e-postmeddelanden som sparats med Outlook och andra relevanta applikationer. Nästan alla e-postklienter stöder detta filformat för dess överensstämmelse med RFC-822 Internet Message Format Standard. Läs mer om detta filformat[här](https://wiki.fileformat.com/email/eml) . |
| static readonly [EMLX](../../groupdocs.viewer/filetype/emlx) | Apple Mail Message (.emlx) är implementerat och utvecklat av Apple. Apple Mail-applikationen använder filformatet EMLX för att exportera e-postmeddelanden. Läs mer om detta filformat[här](https://wiki.fileformat.com/email/emlx) . |
| static readonly [EMZ](../../groupdocs.viewer/filetype/emz) | Enhanced Windows Metafile komprimerad (.emz) representerar grafiska bilder enhetsoberoende komprimerade av GZIP. Metafiler av EMF består av poster med variabel längd i kronologisk ordning som kan återge den lagrade bilden efter analys på valfri utenhet. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/emz) . |
| static readonly [EPS](../../groupdocs.viewer/filetype/eps) | Encapsulated PostScript File (.eps) beskriver ett Encapsulated PostScript-språkprogram som beskriver utseendet på en enskild sida. Läs mer om detta filformat[här](https://wiki.fileformat.com/page-description-language/eps) . |
| static readonly [EPUB](../../groupdocs.viewer/filetype/epub) | Open eBook File (.epub) är ett e-boksfilformat som tillhandahåller ett standardformat för digitala publikationer för förlag och konsumenter. Formatet har varit så vanligt vid det här laget att det stöds av många e-läsare och program. Läs mer om detta filformat[här](https://wiki.fileformat.com/ebook/epub) . |
| static readonly [ERB](../../groupdocs.viewer/filetype/erb) | Ruby ERB Script (.erb) |
| static readonly [Excel2003XML](../../groupdocs.viewer/filetype/excel2003xml) | Excel 2003 XML (SpreadsheetML) representerar Excel Binary File Format. Sådana filer kan skapas av Microsoft Excel såväl som andra liknande kalkylprogram som OpenOffice Calc eller Apple Numbers. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [FODG](../../groupdocs.viewer/filetype/fodg) | Platt XML ODF-mall (.fodg) används av Apache OpenOffices Draw-applikation för att lagra ritelement som en vektorbild. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/fodg) . |
| static readonly [FODP](../../groupdocs.viewer/filetype/fodp) | OpenDocument Presentation (.fodp) representerar OpenDocument Flat XML Presentation. Läs mer om detta filformat[här](https://fileinfo.com/extension/fodp) . |
| static readonly [FODS](../../groupdocs.viewer/filetype/fods) | OpenDocument Flat XML-kalkylblad (.fods) |
| static readonly [GIF](../../groupdocs.viewer/filetype/gif) | Graphical Interchange Format File (.gif) är en typ av mycket komprimerad bild. För varje bild tillåter GIF vanligtvis upp till 8 bitar per pixel och upp till 256 färger är tillåtna över hela bilden. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/gif) . |
| static readonly [GROOVY](../../groupdocs.viewer/filetype/groovy) | Groovy källkodsfil (.groovy) |
| static readonly [GZ](../../groupdocs.viewer/filetype/gz) | Gnu Zipped File (.gz) är komprimerade filer skapade med gzip-komprimeringsprogrammet. Den kan innehålla flera komprimerade filer och används ofta på UNIX- och Linux-system. Läs mer om detta filformat[här](https://wiki.fileformat.com/compression/gz) . |
| static readonly [GZIP](../../groupdocs.viewer/filetype/gzip) | Gnu Zipped File (.gzip) introducerades som ett gratis verktyg för att ersätta Compress-programmet som används i Unix-system. Sådana filer kan öppnas och extraheras med ett flertal applikationer som WinZip som är tillgängligt på både Windows och MacOS. Läs mer om detta filformat[här](https://wiki.fileformat.com/compression/gz) . |
| static readonly [H](../../groupdocs.viewer/filetype/h) | C/C++/Objective-C Header File (.h) |
| static readonly [HAML](../../groupdocs.viewer/filetype/haml) | Haml källkodsfil (.haml) |
| static readonly [HH](../../groupdocs.viewer/filetype/hh) | C++ Header File (.hh) |
| static readonly [HPG](../../groupdocs.viewer/filetype/hpg) | PLT (HPGL) (.hpg) |
| static readonly [HTM](../../groupdocs.viewer/filetype/htm) | Hypertext Markup Language File (.htm) är tillägget för webbsidor som skapats för visning i webbläsare. Läs mer om detta filformat[här](https://wiki.fileformat.com/web/html) . |
| static readonly [HTML](../../groupdocs.viewer/filetype/html) | Hypertext Markup Language File (.html) är tillägget för webbsidor som skapats för visning i webbläsare. Läs mer om detta filformat[här](https://wiki.fileformat.com/web/html) . |
| static readonly [ICO](../../groupdocs.viewer/filetype/ico) | Icon File (.ico) är bildfiltyper som används som ikon för representation av ett program på Microsoft Windows. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/ico) . |
| static readonly [IFC](../../groupdocs.viewer/filetype/ifc) | Industry Foundation Classes File (.ifc) är ett filformat som fastställer internationella standarder för att importera och exportera byggnadsobjekt och deras egenskaper. Detta filformat ger interoperabilitet mellan olika programvaror. Läs mer om detta filformat[här](https://wiki.fileformat.com/cad/ifc) . |
| static readonly [IGS](../../groupdocs.viewer/filetype/igs) | Initial Graphics Exchange Specification (IGES) (.igs) |
| static readonly [J2C](../../groupdocs.viewer/filetype/j2c) | JPEG 2000 Code Stream (.j2c) |
| static readonly [J2K](../../groupdocs.viewer/filetype/j2k) | JPEG 2000 Code Stream (.j2k) är en bild som komprimeras med hjälp av wavelet-komprimering istället för DCT-komprimering. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/j2k) . |
| static readonly [JAVA](../../groupdocs.viewer/filetype/java) | Java-källkodsfil (.java) |
| static readonly [JP2](../../groupdocs.viewer/filetype/jp2) | JPEG 2000 Core Image File (.jp2) är ett bildkodningssystem och en toppmodern bildkomprimeringsstandard. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/jp2) . |
| static readonly [JPC](../../groupdocs.viewer/filetype/jpc) | JPEG 2000 Code Stream (.jpc) |
| static readonly [JPEG](../../groupdocs.viewer/filetype/jpeg) | JPEG-bild (.jpeg) är en typ av bildformat som sparas med metoden för förlustkomprimering. Utdatabilden, som ett resultat av komprimering, är en kompromiss mellan lagringsstorlek och bildkvalitet. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [JPF](../../groupdocs.viewer/filetype/jpf) | JPEG 2000-bildfil (.jpf) |
| static readonly [JPG](../../groupdocs.viewer/filetype/jpg) | JPEG-bild (.jpg) är en typ av bildformat som sparas med metoden för förlustkomprimering. Utdatabilden, som ett resultat av komprimering, är en kompromiss mellan lagringsstorlek och bildkvalitet. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [JPM](../../groupdocs.viewer/filetype/jpm) | JPEG 2000-bildfil (.jpm) |
| static readonly [JPX](../../groupdocs.viewer/filetype/jpx) | JPEG 2000-bildfil (.jpx) |
| static readonly [JS](../../groupdocs.viewer/filetype/js) | JavaScript-fil (.js) |
| static readonly [JSON](../../groupdocs.viewer/filetype/json) | JavaScript-objektnotationsfil (.json) |
| static readonly [LESS](../../groupdocs.viewer/filetype/less) | LESS Style Sheet (.less) |
| static readonly [LOG](../../groupdocs.viewer/filetype/log) | Loggfil (.log) |
| static readonly [M](../../groupdocs.viewer/filetype/m) | Objective-C Implementation File (.m) |
| static readonly [MAKE](../../groupdocs.viewer/filetype/make) | Xcode Makefile Script (.make) |
| static readonly [MBOX](../../groupdocs.viewer/filetype/mbox) | Email Mailbox File (.mbox) Läs mer om detta filformat[här](https://fileinfo.com/extension/mbox) . |
| static readonly [MD](../../groupdocs.viewer/filetype/md) | Markdown Documentation File (.md) |
| static readonly [MHT](../../groupdocs.viewer/filetype/mht) | MHTML Web Archive (.mht) |
| static readonly [MHTML](../../groupdocs.viewer/filetype/mhtml) | MIME HTML-fil (.mhtml) |
| static readonly [ML](../../groupdocs.viewer/filetype/ml) | ML källkodsfil (.ml) |
| static readonly [MM](../../groupdocs.viewer/filetype/mm) | Objective-C++ källfil (.mm) |
| static readonly [MOBI](../../groupdocs.viewer/filetype/mobi) | Mobipocket eBook (.mobi) är ett av de mest använda e-boksfilformaten. Formatet är en förbättring av det gamla OEB-formatet (Open Ebook Format) och användes som proprietärt format för Mobipocket Reader. Läs mer om detta filformat[här](https://wiki.fileformat.com/ebook/mobi) . |
| static readonly [MPP](../../groupdocs.viewer/filetype/mpp) | Microsoft Project File (.mpp) är Microsoft Project-datafil som lagrar information relaterad till projektledning på ett integrerat sätt. Läs mer om detta filformat[här](https://wiki.fileformat.com/project-management/mpp) . |
| static readonly [MPT](../../groupdocs.viewer/filetype/mpt) | Microsoft Project Template (.mpt) innehåller grundläggande information och struktur tillsammans med dokumentinställningar för att skapa .MPP-filer. Läs mer om detta filformat[här](https://wiki.fileformat.com/project-management/mpt) . |
| static readonly [MPX](../../groupdocs.viewer/filetype/mpx) | Microsoft Project Exchange-fil (.mpx) är ett ASCII-filformat för överföring av projektinformation mellan Microsoft Project (MSP) och andra applikationer som stöder MPX-filformatet som Primavera Project Planner, Sciforma och Timerline Precision Estimating. Läs mer om detta filformat[här](https://wiki.fileformat.com/project-management/mpx) . |
| static readonly [MSG](../../groupdocs.viewer/filetype/msg) | Outlook Mail Message (.msg) är ett filformat som används av Microsoft Outlook och Exchange för att lagra e-postmeddelanden, kontakter, möten eller andra uppgifter. Läs mer om detta filformat[här](https://wiki.fileformat.com/email/msg) . |
| static readonly [NSF](../../groupdocs.viewer/filetype/nsf) | Lotus Notes Database (.nsf) Läs mer om detta filformat[här](https://fileinfo.com/extension/nsf) . |
| static readonly [NUMBERS](../../groupdocs.viewer/filetype/numbers) | Apple-nummer representerar Excel som binärt filformat. Sådana filer kan skapas av Apples nummerapplikation. Läs mer om detta filformat[här](https://fileinfo.com/extension/numbers) . |
| static readonly [OBJ](../../groupdocs.viewer/filetype/obj) | Wavefront 3D Object File (.obj) är en 3D-bildfil introducerad av Wavefront Technologies Läs mer om detta filformat[här](https://wiki.fileformat.com/3d/obj/) . |
| static readonly [ODG](../../groupdocs.viewer/filetype/odg) | OpenDocument Graphic File (.odg) används av Apache OpenOffices Draw-applikation för att lagra ritelement som en vektorbild. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/odg) . |
| static readonly [ODP](../../groupdocs.viewer/filetype/odp) | OpenDocument Presentation (.odp) representerar presentationsfilformat som används av OpenOffice.org i OASISOpen-standarden. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [ODS](../../groupdocs.viewer/filetype/ods) | OpenDocument Spreadsheet (.ods) står för OpenDocument Spreadsheet Document-format som kan redigeras av användaren. Data lagras i ODF-filen i rader och kolumner. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [ODT](../../groupdocs.viewer/filetype/odt) | OpenDocument Text Document (.odt) är typ av dokument skapade med ordbehandlingsprogram som är baserade på OpenDocument Text File-format. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [ONE](../../groupdocs.viewer/filetype/one) | OneNote-dokument (.one) skapas av Microsoft OneNote-applikationen. OneNote låter dig samla in information med applikationen som om du använder din kladdplatta för att göra anteckningar. Läs mer om detta filformat[här](https://wiki.fileformat.com/note-taking/one) . |
| static readonly [OST](../../groupdocs.viewer/filetype/ost) | Outlook Offline Data File (.ost) representerar användarens postlådedata i offlineläge på lokal dator vid registrering med Exchange Server med Microsoft Outlook. Läs mer om detta filformat[här](https://wiki.fileformat.com/email/ost) . |
| static readonly [OTG](../../groupdocs.viewer/filetype/otg) | OpenDocument grafisk mall (.otg) |
| static readonly [OTP](../../groupdocs.viewer/filetype/otp) | OpenDocument Presentation Template (.otp) representerar presentationsmallfiler skapade av applikationer i OASIS OpenDocument standardformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [OTS](../../groupdocs.viewer/filetype/ots) | OpenDocument Spreadsheet Mall (.ots) |
| static readonly [OTT](../../groupdocs.viewer/filetype/ott) | OpenDocument Document Template (.ott) representerar malldokument som genereras av applikationer i enlighet med OASIS OpenDocument-standardformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [OXPS](../../groupdocs.viewer/filetype/oxps) | Öppna XPS-fil (.oxps) |
| static readonly [PCL](../../groupdocs.viewer/filetype/pcl) | Skrivarkommandospråkdokument (.pcl) |
| static readonly [PDF](../../groupdocs.viewer/filetype/pdf) | Portable Document Format File (.pdf) är en typ av dokument som skapades av Adobe redan på 1990-talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av applikationsprogramvara, hårdvara samt operativsystem. Läs mer om detta filformat[här](https://wiki.fileformat.com/view/pdf) . |
| static readonly [PHP](../../groupdocs.viewer/filetype/php) | PHP-källkodsfil (.php) |
| static readonly [PL](../../groupdocs.viewer/filetype/pl) | Perl Script (.pl) |
| static readonly [PLT](../../groupdocs.viewer/filetype/plt) | PLT (HPGL) (.plt) är en vektorbaserad plotterfil introducerad av Autodesk, Inc. och innehåller information för en viss CAD-fil. Plottdetaljer kräver noggrannhet och precision i produktionen, och användning av PLT-fil garanterar detta eftersom alla bilder skrivs ut med linjer istället för prickar. Läs mer om detta filformat[här](https://wiki.fileformat.com/cad/plt) . |
| static readonly [PNG](../../groupdocs.viewer/filetype/png) | Portable Network Graphic (.png) är en typ av rasterbildsfilformat som använder förlustfri komprimering. Det här filformatet skapades som en ersättning för Graphics Interchange Format (GIF) och har inga upphovsrättsliga begränsningar. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/png) . |
| static readonly [POT](../../groupdocs.viewer/filetype/pot) | PowerPoint-mall (.pot) representerar Microsoft PowerPoint-mallfiler skapade av PowerPoint 97-2003-versioner. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [POTM](../../groupdocs.viewer/filetype/potm) | PowerPoint Open XML Makro-aktiverad presentationsmall (.potm) är Microsoft PowerPoint-mallfiler med stöd för makron. POTM-filer skapas med PowerPoint 2007 eller högre och innehåller standardinställningar som kan användas för att skapa ytterligare presentationsfiler. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [POTX](../../groupdocs.viewer/filetype/potx) | PowerPoint Open XML-presentationsmall (.potx) representerar Microsoft PowerPoint-mallpresentationer som skapats med Microsoft PowerPoint 2007 och senare. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [PPS](../../groupdocs.viewer/filetype/pps) | PowerPoint-bildspel (.pps) skapas med Microsoft PowerPoint för bildspel. PPS-filläsning och skapande stöds av Microsoft PowerPoint 97-2003. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [PPSM](../../groupdocs.viewer/filetype/ppsm) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) representerar Macro-enabled Slide Show-filformat skapat med Microsoft PowerPoint 2007 eller högre. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [PPSX](../../groupdocs.viewer/filetype/ppsx) | PowerPoint Open XML Slide Show-filer (.ppsx) skapas med Microsoft PowerPoint 2007 och senare för Slide Show-ändamål. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [PPT](../../groupdocs.viewer/filetype/ppt) | PowerPoint-presentation (.ppt) representerar en PowerPoint-fil som består av en samling bilder för visning som bildspel. Den anger det binära filformatet som används av Microsoft PowerPoint 97-2003. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [PPTM](../../groupdocs.viewer/filetype/pptm) | PowerPoint Open XML Macro-Enabled Presentation är makroaktiverade presentationsfiler som skapas med Microsoft PowerPoint 2007 eller senare versioner. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [PPTX](../../groupdocs.viewer/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) är presentationsfiler skapade med populära Microsoft PowerPoint-applikationer. Till skillnad från den tidigare versionen av presentationsfilformatet PPT som var binärt, är PPTX-formatet baserat på Microsoft PowerPoints öppna XML-presentationsfilformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [PROPERTIES](../../groupdocs.viewer/filetype/properties) | Java Properties File (.properties) |
| static readonly [PS](../../groupdocs.viewer/filetype/ps) | PostScript-fil (.ps) |
| static readonly [PS1](../../groupdocs.viewer/filetype/ps1) | PowerShell-skriptfil (.ps1) ett filformat för Windows PowerShell Cmdlet-filer. Läs mer om detta filformat[här](https://fileinfo.com/extension/ps1) . |
| static readonly [PSB](../../groupdocs.viewer/filetype/psb) | Photoshop Large Document Format (.psb) representerar Photoshop Large Document Format som används för grafisk design och utveckling. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/psb) . |
| static readonly [PSD](../../groupdocs.viewer/filetype/psd) | Adobe Photoshop Document (.psd) representerar Adobe Photoshops ursprungliga filformat som används för grafisk design och utveckling. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/psd) . |
| static readonly [PSD1](../../groupdocs.viewer/filetype/psd1) | PowerShell-skriptmodulmanifest (.psd1) ett filformat för PowerShell-modulmanifestskript. Läs mer om detta filformat[här](https://fileinfo.com/extension/psd1) . |
| static readonly [PSM1](../../groupdocs.viewer/filetype/psm1) | PowerShell-skriptmodul (.psm1) ett filformat för PowerShell-modulskript. Läs mer om detta filformat[här](https://fileinfo.com/extension/psm1) . |
| static readonly [PST](../../groupdocs.viewer/filetype/pst) | Outlook Personal Information Store File (.pst) representerar Outlook Personal Storage Files (även kallad Personal Storage Table) som lagrar olika användarinformation. Läs mer om detta filformat[här](https://wiki.fileformat.com/email/pst) . |
| static readonly [PY](../../groupdocs.viewer/filetype/py) | Python Script (.py) |
| static readonly [RAR](../../groupdocs.viewer/filetype/rar) | Roshal ARchive (.rar) är komprimerade filer som genereras med komprimeringsmetoden RAR (WINRAR). Läs mer om detta filformat[här](https://wiki.fileformat.com/compression/rar) . |
| static readonly [RB](../../groupdocs.viewer/filetype/rb) | Ruby källkod (.rb) |
| static readonly [RST](../../groupdocs.viewer/filetype/rst) | reStructuredText File (.rst) |
| static readonly [RTF](../../groupdocs.viewer/filetype/rtf) | Rich Text Format File (.rtf) representerar en metod för att koda formaterad text och grafik för användning i applikationer. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [SASS](../../groupdocs.viewer/filetype/sass) | Syntactically Awesome StyleSheets-fil (.sass) |
| static readonly [SCALA](../../groupdocs.viewer/filetype/scala) | Scala källkodsfil (.scala) |
| static readonly [SCM](../../groupdocs.viewer/filetype/scm) | Schemekällkodsfil (.scm) |
| static readonly [SCRIPT](../../groupdocs.viewer/filetype/script) | Generisk skriptfil (.script) |
| static readonly [SevenZip](../../groupdocs.viewer/filetype/sevenzip) | 7Zip (.7z, .7zip) är gratis arkivering med öppen källkod med LZMA- och LZMA2-komprimering. Läs mer om detta filformat[här](https://docs.fileformat.com/compression/7z/) . |
| static readonly [SH](../../groupdocs.viewer/filetype/sh) | Bash Shell Script (.sh) |
| static readonly [SML](../../groupdocs.viewer/filetype/sml) | Standard ML källkodsfil (.sml) |
| static readonly [SQL](../../groupdocs.viewer/filetype/sql) | Structured Query Language Data File (.sql) |
| static readonly [STL](../../groupdocs.viewer/filetype/stl) | Stereolithography File (.stl) är ett utbytbart filformat som representerar 3-dimensionell ytgeometri. Filformatet finner sin användning inom flera områden som snabb prototypframställning, 3D-utskrift och datorstödd tillverkning. Läs mer om detta filformat[här](https://wiki.fileformat.com/cad/stl) . |
| static readonly [SVG](../../groupdocs.viewer/filetype/svg) | Scalable Vector Graphics File (.svg) är en Scalar Vector Graphics-fil som använder XML-baserat textformat för att beskriva utseendet på en bild. Läs mer om detta filformat[här](https://wiki.fileformat.com/page-description-language/svg) . |
| static readonly [SVGZ](../../groupdocs.viewer/filetype/svgz) | Scalable Vector Graphics File (.svgz) är en Scalar Vector Graphics-fil som använder XML-baserat textformat, komprimerat av GZIP för att beskriva utseendet på en bild. Läs mer om detta filformat[här](https://fileinfo.com/extension/svgz) . |
| static readonly [SXC](../../groupdocs.viewer/filetype/sxc) | StarOffice Calc-kalkylblad (.sxc) |
| static readonly [TAR](../../groupdocs.viewer/filetype/tar) | Consolidated Unix File Archive (.tar) är arkiv skapade med Unix-baserat verktyg för att samla in en eller flera filer. Läs mer om detta filformat[här](https://wiki.fileformat.com/compression/tar) . |
| static readonly [TARGZ](../../groupdocs.viewer/filetype/targz) | Consolidated Unix File Archive (.tgz, .tar.gz) är arkiv skapade med Unix-baserat verktyg för att samla in en eller flera filer. Läs mer om detta filformat[här](https://fileinfo.com/extension/tgz) . |
| static readonly [TARXZ](../../groupdocs.viewer/filetype/tarxz) | Consolidated Unix File Archive (.txz, .tar.xz) är arkiv skapade med Unix-baserat verktyg för att samla in en eller flera filer. Läs mer om detta filformat[här](https://fileinfo.com/extension/txz) . |
| static readonly [TEX](../../groupdocs.viewer/filetype/tex) | LaTeX källdokument (.tex) är ett språk som består av både programmering och uppmärkningsfunktioner, som används för att sätta in dokument. Läs mer om detta filformat[här](https://wiki.fileformat.com/page-description-language/tex) . |
| static readonly [TGA](../../groupdocs.viewer/filetype/tga) | Truevision TGA (Truevision Advanced Raster Adapter - TARGA) används för att lagra digitala bitmappsbilder utvecklade av TRUEVISION. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/tga) . |
| static readonly [TGZ](../../groupdocs.viewer/filetype/tgz) | Consolidated Unix File Archive (.tgz, .tar.gz) är arkiv skapade med Unix-baserat verktyg för att samla in en eller flera filer. Läs mer om detta filformat[här](https://fileinfo.com/extension/tgz) . |
| static readonly [TIF](../../groupdocs.viewer/filetype/tif) | Taggad bildfil (.tif) representerar rasterbilder som är avsedda för användning på en mängd olika enheter som överensstämmer med denna filformatstandard. Den kan beskriva bilevel-, gråskala-, palett-färg- och fullfärgsbilddata i flera färgrymder. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TIFF](../../groupdocs.viewer/filetype/tiff) | Tagged Image File Format (.tiff) representerar rasterbilder som är avsedda för användning på en mängd olika enheter som överensstämmer med denna filformatstandard. Den kan beskriva bilevel-, gråskala-, palett-färg- och fullfärgsbilddata i flera färgrymder. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TSV](../../groupdocs.viewer/filetype/tsv) | Tab Separated Values File (.tsv) representerar data separerade med flikar i vanligt textformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [TXT](../../groupdocs.viewer/filetype/txt) | Vanlig textfil (.txt) representerar ett textdokument som innehåller ren text i form av rader. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [TXZ](../../groupdocs.viewer/filetype/txz) | Consolidated Unix File Archive (.txz, .tar.xz) är arkiv skapade med Unix-baserat verktyg för att samla in en eller flera filer. Läs mer om detta filformat[här](https://fileinfo.com/extension/txz) . |
| static readonly [Unknown](../../groupdocs.viewer/filetype/unknown) | Representerar okänd filtyp. |
| static readonly [VB](../../groupdocs.viewer/filetype/vb) | Visual Basic Project Item File (.vb) är en källkodsfil skapad i Visual Basic-språket som skapades av Microsoft för utveckling av .NET-applikationer. Läs mer om detta filformat[här](https://wiki.fileformat.com/programming/vb) . |
| static readonly [VCF](../../groupdocs.viewer/filetype/vcf) | vCard-fil (.vcf) är ett digitalt filformat för att lagra kontaktinformation. Formatet används ofta för datautbyte bland populära program för informationsutbyte. Läs mer om detta filformat[här](https://wiki.fileformat.com/email/vcf) . |
| static readonly [VDW](../../groupdocs.viewer/filetype/vdw) | Visio Web Drawing (.vdw) representerar filformat som anger de strömmar och lagringar som krävs för att rendera en webbritning. Läs mer om detta filformat[här](https://wiki.fileformat.com/web/vdw) . |
| static readonly [VDX](../../groupdocs.viewer/filetype/vdx) | Visio Drawing XML-fil (.vdx) representerar alla ritningar eller diagram som skapats i Microsoft Visio, men som sparats i XML-format har filtillägget .VDX. En Visio-ritnings-XML-fil skapas i Visio-programvaran, som är utvecklad av Microsoft. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vdx) . |
| static readonly [VIM](../../groupdocs.viewer/filetype/vim) | Vim-inställningsfil (.vim) |
| static readonly [VSD](../../groupdocs.viewer/filetype/vsd) | Visio Drawing File (.vsd) är ritningar skapade med Microsoft Visio-applikationen för att representera olika grafiska objekt och sammankopplingen mellan dessa. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vsd) . |
| static readonly [VSDM](../../groupdocs.viewer/filetype/vsdm) | Visio Macro-Enabled Drawing (.vsdm) är ritfiler som skapats med Microsoft Visio-programmet som stöder makron. VSDM-filer är OPC/XML-ritningar som liknar VSDX, men som också ger möjlighet att köra makron när filen öppnas. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vsdm) . |
| static readonly [VSDX](../../groupdocs.viewer/filetype/vsdx) | Visio Drawing (.vsdx) representerar Microsoft Visio-filformat som introducerats från Microsoft Office 2013 och framåt. Det utvecklades för att ersätta det binära filformatet .VSD, som stöds av tidigare versioner av Microsoft Visio. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vsdx) . |
| static readonly [VSS](../../groupdocs.viewer/filetype/vss) | Visio Stencil File(.vss) är stencilfiler skapade med Microsoft Visio 2007 och tidigare. Stencilfiler tillhandahåller ritobjekt som kan inkluderas i en .VSD Visio-ritning. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vss) . |
| static readonly [VSSM](../../groupdocs.viewer/filetype/vssm) | Visio Macro-Enabled Stencil File (.vssm) är Microsoft Visio Stencil-filer som stöder ger stöd för makron. En VSSM-fil när den öppnas gör det möjligt att köra makron för att uppnå önskad formatering och placering av former i ett diagram. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vssm) . |
| static readonly [VSSX](../../groupdocs.viewer/filetype/vssx) | Visio Stencil File (.vssx) är ritstenciler skapade med Microsoft Visio 2013 och senare. VSSX-filformatet kan öppnas med Visio 2013 och högre. Visio-filer är kända för representation av en mängd olika ritningselement som samling av former, kopplingar, flödesscheman, nätverkslayout, UML-diagram, Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vssx) . |
| static readonly [VST](../../groupdocs.viewer/filetype/vst) | Visio Drawing Template (.vst) är vektorbildfiler skapade med Microsoft Visio och fungerar som mall för att skapa ytterligare filer. Dessa mallfiler är i binärt filformat och innehåller standardlayout och inställningar som används för att skapa nya Visio-ritningar. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vst) . |
| static readonly [VSTM](../../groupdocs.viewer/filetype/vstm) | Visio Macro-Enabled Drawing Template (.vstm) är mallfiler skapade med Microsoft Visio som stöder makron. Till skillnad från VSDX-filer kan filer skapade från VSTM-mallar köra makron som är utvecklade i Visual Basic for Applications (VBA)-kod. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vstm) . |
| static readonly [VSTX](../../groupdocs.viewer/filetype/vstx) | Visio Drawing Template (.vstx) är ritmallsfiler skapade med Microsoft Visio 2013 och senare. Dessa VSTX-filer ger en startpunkt för att skapa Visio-ritningar, sparade som .VSDX-filer, med standardlayout och inställningar. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vstx) . |
| static readonly [VSX](../../groupdocs.viewer/filetype/vsx) | Visio Stencil XML File (.vsx) hänvisar till schabloner som består av ritningar och former som används för att skapa diagram i Microsoft Visio. VSX-filer sparas i XML-filformat och stöddes till Visio 2013. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vsx) . |
| static readonly [VTX](../../groupdocs.viewer/filetype/vtx) | Visio Template XML File (.vtx) är en Microsoft Visio ritmall som sparas på skiva i XML-filformat. Mallen syftar till att tillhandahålla en fil med grundläggande inställningar som kan användas för att skapa flera Visio-filer med samma inställningar. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vtx) . |
| static readonly [WEBP](../../groupdocs.viewer/filetype/webp) | WebP Image (.webp) är ett modernt rasterwebbbildsfilformat som är baserat på förlustfri och förlustfri komprimering. Det ger samma bildkvalitet samtidigt som det minskar bildstorleken avsevärt. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/webp) . |
| static readonly [WMF](../../groupdocs.viewer/filetype/wmf) | Windows Metafile (.wmf) representerar Microsoft Windows Metafile (WMF) för lagring av vektor- och bitmappsbilddata. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/wmf) . |
| static readonly [WMZ](../../groupdocs.viewer/filetype/wmz) | Komprimerad Windows Metafile (.wmz) representerar Microsoft Windows Metafile (WMF) komprimerad i GZIP archvive - för att lagra vektor- och bitmappsbilddata. Läs mer om detta filformat[här](https://fileinfo.com/extension/wmz#compressed_windows_metafile) . |
| static readonly [XLAM](../../groupdocs.viewer/filetype/xlam) | Microsoft Excel-tillägg (.xlam) |
| static readonly [XLS](../../groupdocs.viewer/filetype/xls) | Excel-kalkylblad (.xls) representerar det binära filformatet för Excel. Sådana filer kan skapas av Microsoft Excel såväl som andra liknande kalkylprogram som OpenOffice Calc eller Apple Numbers. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [XLSB](../../groupdocs.viewer/filetype/xlsb) | Excel binära kalkylblad (.xlsb) anger det binära filformatet för Excel, som är en samling poster och strukturer som anger innehåll i Excel-arbetsboken. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [XLSM](../../groupdocs.viewer/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) är en typ av kalkylbladsfiler som stöder makron. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [XLSX](../../groupdocs.viewer/filetype/xlsx) | Microsoft Excel Open XML-kalkylblad (.xlsx) är ett välkänt format för Microsoft Excel-dokument som introducerades av Microsoft i och med lanseringen av Microsoft Office 2007. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [XLT](../../groupdocs.viewer/filetype/xlt) | Microsoft Excel-mall (.xlt) är mallfiler skapade med Microsoft Excel som är ett kalkylprogram som ingår i Microsoft Office-paketet. Microsoft Office 97-2003 stödde att skapa nya XLT-filer samt att öppna dessa. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [XLTM](../../groupdocs.viewer/filetype/xltm) | Microsoft Excel Macro-Enabled Mall (.xltm) representerar filer som genereras av Microsoft Excel som makro-aktiverade mallfiler. XLTM-filer liknar XLTX i annan struktur än att de senare inte stöder att skapa mallfiler med makron. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [XLTX](../../groupdocs.viewer/filetype/xltx) | Excel Open XML-kalkylbladsmall (.xltx) representerar Microsoft Excel-mall som är baserad på Office OpenXML-filformatspecifikationerna. Den används för att skapa en standardmallfil som kan användas för att generera XLSX-filer som uppvisar samma inställningar som anges i XLTX-filen. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xltx) . |
| static readonly [XML](../../groupdocs.viewer/filetype/xml) | XML-fil (.xml) |
| static readonly [XPS](../../groupdocs.viewer/filetype/xps) | XML Paper Specification File (.xps) representerar sidlayoutfiler som är baserade på XML Paper Specifications skapade av Microsoft. Det här formatet utvecklades av Microsoft som en ersättning för EMF-filformatet och liknar PDF-filformatet, men använder XML i layout, utseende och utskriftsinformation för ett dokument. Läs mer om detta filformat[här](https://wiki.fileformat.com/page-description-language/xps) . |
| static readonly [XZ](../../groupdocs.viewer/filetype/xz) | XZ-fil (.xz) är arkivkomprimerad en komprimeringsalgoritm med hög kvot baserad på LZMA-algoritmen. Läs mer om detta filformat[här](https://fileinfo.com/extension/xz) . |
| static readonly [YAML](../../groupdocs.viewer/filetype/yaml) | YAML-dokument (.yaml) |
| static readonly [ZIP](../../groupdocs.viewer/filetype/zip) | Zippad fil (.zip) representerar arkiv som kan innehålla en eller flera filer eller kataloger. Läs mer om detta filformat[här](https://wiki.fileformat.com/compression/zip) . |

### Se även

* namnutrymme [GroupDocs.Viewer](../../groupdocs.viewer)
* hopsättning [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
