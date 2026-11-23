---
title: "FileType-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Representerar en filtyp och tillhandahåller metoder för att hämta listan över alla filtyper som stöds av GroupDocs.Viewer."
type: docs
url: /sv/python-net/groupdocs.viewer/filetype/
is_root: false
weight: 10
---


## FileType class

Representerar en filtyp och tillhandahåller metoder för att hämta listan över alla filtyper som stöds av GroupDocs.Viewer.

FileType-typen exponerar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/) | Initierar en ny instans av [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/). |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/#file_format-extension) | Initierar en ny FileType-instans. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#file_path) | Detekterar kodningen för textfiler TXT, TSV och CSV via sökväg. |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#stream) | Försöker detektera kodningen för textfiler (TXT, TSV, CSV) från en ström. |
| [detect_encoding_file](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_file/) |  |
| [detect_encoding_stream](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_stream/) |  |
| [detect_encoding_streams](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_streams/) |  |
| [detect_encoding_string](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_string/) |  |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#other) | Bestämmer om den aktuella [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) är densamma som den angivna [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/). |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#obj) | Bestämmer om den aktuella [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) är densamma som det angivna objektet. |
| [equals_file_type](/viewer/python-net/groupdocs.viewer/filetype/equals_file_type/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer/filetype/equals_object/) |  |
| [from_extension](/viewer/python-net/groupdocs.viewer/filetype/from_extension/#extension) | Mappar filändelse till filtyp. |
| [from_file_path](/viewer/python-net/groupdocs.viewer/filetype/from_file_path/#file_path) | Extraherar filändelse och mappar den till en filtyp. |
| [from_media_type](/viewer/python-net/groupdocs.viewer/filetype/from_media_type/#media_type) | Mappar en filmediatyp till en [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) (t.ex. 'application/pdf' mappar till [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)). |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream) | Detekterar filtyp genom att läsa filens signatur. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password) | Detekterar filtyp genom att läsa filens signatur. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-logger) | Detekterar filtyp genom att läsa filens signatur. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password-logger) | Detekterar filtypen genom att läsa filens signatur. |
| [from_stream_file](/viewer/python-net/groupdocs.viewer/filetype/from_stream_file/) |  |
| [from_stream_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream_stream/) |  |
| [from_stream_streams](/viewer/python-net/groupdocs.viewer/filetype/from_stream_streams/) |  |
| [from_stream_string](/viewer/python-net/groupdocs.viewer/filetype/from_stream_string/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer/filetype/get_hash_code/) | Returnerar hashkoden för det aktuella [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) objektet. |
| [get_supported_file_types](/viewer/python-net/groupdocs.viewer/filetype/get_supported_file_types/) | Hämtar stödjade filtyper. |
| [to_string](/viewer/python-net/groupdocs.viewer/filetype/to_string/) | Returnerar en str som representerar det aktuella objektet. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [extension](/viewer/python-net/groupdocs.viewer/filetype/extension/) | Filnamnsuffixen (inklusive punkten ".") t.ex. ".doc". |
| [file_format](/viewer/python-net/groupdocs.viewer/filetype/file_format/) | Filtypens namn t.ex. "Microsoft Word Document". |

### Fält
| Fält | Beskrivning |
| :- | :- |
| [UNKNOWN](/viewer/python-net/groupdocs.viewer/filetype/unknown/) | Representerar okänd filtyp. |
| [ZIP](/viewer/python-net/groupdocs.viewer/filetype/zip/) | Zippad fil (.zip) representerar arkiv som kan innehålla en eller flera filer eller kataloger. Läs mer om detta filformat här. |
| [TAR](/viewer/python-net/groupdocs.viewer/filetype/tar/) | Konsoliderat Unix-filarkiv (.tar) är arkiv skapade med ett Unix-baserat verktyg för att samla en eller flera filer. Läs mer om detta filformat här. |
| [XZ](/viewer/python-net/groupdocs.viewer/filetype/xz/) | XZ-fil (.xz) är ett arkiv komprimerat med en högkomprimeringsalgoritm baserad på LZMA-algoritmen. Läs mer om detta filformat här. |
| [TXZ](/viewer/python-net/groupdocs.viewer/filetype/txz/) | Konsoliderat Unix-filarkiv (.txz, .tar.xz) är arkiv skapade med ett Unix-baserat verktyg för att samla en eller flera filer. Läs mer om detta filformat här. |
| [TARXZ](/viewer/python-net/groupdocs.viewer/filetype/tarxz/) | Konsoliderat Unix-filarkiv (.txz, .tar.xz) är arkiv skapade med ett Unix-baserat verktyg för att samla en eller flera filer. Läs mer om detta filformat här. |
| [TGZ](/viewer/python-net/groupdocs.viewer/filetype/tgz/) | Konsoliderat Unix-filarkiv (.tgz, .tar.gz) är arkiv skapade med ett Unix-baserat verktyg för att samla en eller flera filer. Läs mer om detta filformat här. |
| [TARGZ](/viewer/python-net/groupdocs.viewer/filetype/targz/) | Konsoliderat Unix-filarkiv (.tgz, .tar.gz) är arkiv skapade med ett Unix-baserat verktyg för att samla en eller flera filer. Läs mer om detta filformat här. |
| [BZ2](/viewer/python-net/groupdocs.viewer/filetype/bz2/) | Bzip2-komprimerad fil (.bz2) är komprimerade filer som genererats med BZIP2 öppen källkodskomprimeringsmetod, främst på UNIX- eller Linux-system. Läs mer om detta filformat här. |
| [RAR](/viewer/python-net/groupdocs.viewer/filetype/rar/) | Roshal ARchive (.rar) är komprimerade filer som genereras med komprimeringsmetoden RAR (WINRAR). Läs mer om detta filformat här. |
| [GZ](/viewer/python-net/groupdocs.viewer/filetype/gz/) | Gnu Zipped File (.gz) är komprimerade filer som skapats med gzip-komprimeringsprogrammet. Den kan innehålla flera komprimerade filer och används vanligtvis på UNIX- och Linux-system. Läs mer om detta filformat här. |
| [GZIP](/viewer/python-net/groupdocs.viewer/filetype/gzip/) | Gnu Zipped File (.gzip) introducerades som ett gratisverktyg för att ersätta Compress-programmet som används i Unix-system. Sådana filer kan öppnas och extraheras med flera program, såsom WinZip som finns tillgängligt både för Windows och macOS. Läs mer om detta filformat här. |
| [SEVEN_ZIP](/viewer/python-net/groupdocs.viewer/filetype/seven_zip/) | 7Zip (.7z, .7zip) är en gratis öppen källkodsarkiverare med LZMA- och LZMA2-komprimering. Läs mer om detta filformat här. |
| [CPIO](/viewer/python-net/groupdocs.viewer/filetype/cpio/) | Cpio är ett allmänt filarkiveringsverktyg och dess tillhörande filformat. Det installeras främst på Unix-liknande operativsystem. Läs mer om detta filformat här. |
| [ZSTANDARD](/viewer/python-net/groupdocs.viewer/filetype/zstandard/) | ZST-fil är en komprimerad fil som genereras med komprimeringsalgoritmen Zstandard (zstd). Det är en komprimerad fil som skapas med förlustfri komprimering av algoritmen. ZST-filer kan användas för att komprimera olika typer av filer såsom databaser, filsystem, nätverk och spel. Läs mer om detta filformat här. |
| [TZST](/viewer/python-net/groupdocs.viewer/filetype/tzst/) | TZST-filer (.tar.zst, .tzst) är Zstandard-arkiv (ZST) som internt innehåller ett konsoliderat Unix-filarkiv (Tar), skapat med ett Unix-baserat verktyg för att samla en eller flera filer. |
| [TAR_ZST](/viewer/python-net/groupdocs.viewer/filetype/tar_zst/) | TZST-filer (.tar.zst, .tzst) är Zstandard-arkiv (ZST) som internt innehåller ett konsoliderat Unix-filarkiv (Tar), skapat med ett Unix-baserat verktyg för att samla en eller flera filer. |
| [ISO](/viewer/python-net/groupdocs.viewer/filetype/iso/) | ISO-optisk skivavbild är en okomprimerad arkivskivavbildningsfil som representerar innehållet av hela data på en optisk skiva såsom CD eller DVD, baserad på ISO-9660-standarden. Läs mer om detta filformat här. |
| [LHA](/viewer/python-net/groupdocs.viewer/filetype/lha/) | LHA eller LZH är ett gratis komprimeringsverktyg och tillhörande filformat. Läs mer om detta filformat här. |
| [CAB](/viewer/python-net/groupdocs.viewer/filetype/cab/) | Cabinet (eller CAB) är ett arkivfilformat för Microsoft Windows. Läs mer om detta filformat här. |
| [DXF](/viewer/python-net/groupdocs.viewer/filetype/dxf/) | Drawing Exchange Format File (.dxf) är en taggad datarapresentation av en AutoCAD-ritningsfil. Läs mer om detta filformat här. |
| [DWG](/viewer/python-net/groupdocs.viewer/filetype/dwg/) | AutoCAD Drawing Database File (.dwg) representerar proprietära binära filer som används för att innehålla 2D- och 3D-designdata. Till skillnad från DXF, som är ASCII-filer, representerar DWG det binära filformatet för CAD (Computer Aided Design)-ritningar. Läs mer om detta filformat här. |
| [DWT](/viewer/python-net/groupdocs.viewer/filetype/dwt/) | AutoCAD Drawing Template (.dwt) är en AutoCAD-ritningsmallfil som används som utgångspunkt för att skapa ritningar som kan sparas som DWG-filer. Läs mer om detta filformat här. |
| [STL](/viewer/python-net/groupdocs.viewer/filetype/stl/) | Stereolithography File (.stl) är ett utbytbart filformat som representerar tredimensionell ytgometri. Filformatet används inom flera områden såsom snabb prototypframtagning, 3D-utskrift och datorstödd tillverkning. Läs mer om detta filformat här. |
| [IFC](/viewer/python-net/groupdocs.viewer/filetype/ifc/) | Industry Foundation Classes File (.ifc) är ett filformat som fastställer internationella standarder för import och export av byggnadsobjekt och deras egenskaper. Detta filformat möjliggör interoperabilitet mellan olika programvaruapplikationer. Läs mer om detta filformat här. |
| [DWF](/viewer/python-net/groupdocs.viewer/filetype/dwf/) | Design Web Format-fil (.dwf) representerar 2D/3D-ritning i komprimerat format för visning, granskning eller utskrift av designfiler. Den innehåller grafik och text som en del av designdata och minskar filens storlek på grund av dess komprimerade format. Läs mer om detta filformat här. |
| [FBX](/viewer/python-net/groupdocs.viewer/filetype/fbx/) | Autodesk FBX Interchange File (FilmBoX) (.fbx) representerar 3D-modellformat. Läs mer om detta filformat här. |
| [DWFX](/viewer/python-net/groupdocs.viewer/filetype/dwfx/) | Design Web Format File XPS (.dwfx) representerar 2D/3D-ritning som XPS-dokument i komprimerat format för visning, granskning eller utskrift av designfiler. Den innehåller grafik och text som en del av designdata och minskar filens storlek på grund av dess komprimerade format. Läs mer om detta filformat här. |
| [DGN](/viewer/python-net/groupdocs.viewer/filetype/dgn/) | MicroStation Design File (.dgn) är ritningar som skapats av och stöds av CAD-program såsom MicroStation och Intergraph Interactive Graphics Design System. Läs mer om detta filformat här. |
| [PLT](/viewer/python-net/groupdocs.viewer/filetype/plt/) | PLT (HPGL) (.plt) är en vektorbaserad plotterfil introducerad av Autodesk, Inc. och innehåller information för en viss CAD-fil. Plottdetaljer kräver noggrannhet och precision i produktionen, och användning av PLT-filen garanterar detta eftersom alla bilder skrivs ut med linjer istället för punkter. Läs mer om detta filformat här. |
| [CF2](/viewer/python-net/groupdocs.viewer/filetype/cf2/) | Common File Format File Läs mer om detta filformat här. |
| [OBJ](/viewer/python-net/groupdocs.viewer/filetype/obj/) | Wavefront 3D Object File (.obj) är en 3D-bildfil introducerad av Wavefront Technologies. Läs mer om detta filformat här. |
| [HPG](/viewer/python-net/groupdocs.viewer/filetype/hpg/) | PLT (HPGL) (.hpg) |
| [IGS](/viewer/python-net/groupdocs.viewer/filetype/igs/) | Initial Graphics Exchange Specification (IGES) (.igs) |
| [VSD](/viewer/python-net/groupdocs.viewer/filetype/vsd/) | Visio Drawing File (.vsd) är ritningar skapade med Microsoft Visio-applikationen för att representera en mängd grafiska objekt och deras sammankoppling. Läs mer om detta filformat här. |
| [VSDX](/viewer/python-net/groupdocs.viewer/filetype/vsdx/) | Visio Drawing (.vsdx) representerar Microsoft Visio-filformatet som introducerades från Microsoft Office 2013 och framåt. Det utvecklades för att ersätta det binära filformatet .VSD, som stöds av tidigare versioner av Microsoft Visio. Läs mer om detta filformat här. |
| [VSS](/viewer/python-net/groupdocs.viewer/filetype/vss/) | Visio Stencil File(.vss) är stencil-filer skapade med Microsoft Visio 2007 och tidigare. Stencil-filer tillhandahåller ritobjekt som kan inkluderas i en .VSD Visio-ritning. Läs mer om detta filformat här. |
| [VSSX](/viewer/python-net/groupdocs.viewer/filetype/vssx/) | Visio Stencil File (.vssx) är ritstencilar skapade med Microsoft Visio 2013 och senare. VSSX-filformatet kan öppnas med Visio 2013 och senare. Visio-filer är kända för att representera en mängd ritningselement såsom samlingar av former, anslutningar, flödesscheman, nätverkslayouter, UML-diagram. Läs mer om detta filformat här. |
| [VSDM](/viewer/python-net/groupdocs.viewer/filetype/vsdm/) | Visio Macro-Enabled Drawing (.vsdm) är ritningsfiler skapade med Microsoft Visio-applikationen som stöder makron. VSDM-filer är OPC/XML-ritningar som liknar VSDX, men ger också möjlighet att köra makron när filen öppnas. Läs mer om detta filformat här. |
| [VST](/viewer/python-net/groupdocs.viewer/filetype/vst/) | Visio Drawing Template (.vst) är vektorbildfiler skapade med Microsoft Visio och fungerar som mall för att skapa ytterligare filer. Dessa mallfiler är i binärt filformat och innehåller standardlayouten och inställningarna som används för att skapa nya Visio-ritningar. Läs mer om detta filformat här. |
| [VSTX](/viewer/python-net/groupdocs.viewer/filetype/vstx/) | Visio Drawing Template (.vstx) är ritmallfiler som skapats med Microsoft Visio 2013 och senare. Dessa VSTX-filer ger en utgångspunkt för att skapa Visio-ritningar, sparade som .VSDX-filer, med standardlayout och -inställningar. Läs mer om detta filformat här. |
| [VSTM](/viewer/python-net/groupdocs.viewer/filetype/vstm/) | Visio Macro-Enabled Drawing Template (.vstm) är mallfiler som skapats med Microsoft Visio och som stöder makron. Till skillnad från VSDX-filer kan filer som skapas från VSTM-mallar köra makron som utvecklats i Visual Basic for Applications (VBA)-kod. Läs mer om detta filformat här. |
| [VSSM](/viewer/python-net/groupdocs.viewer/filetype/vssm/) | Visio Macro-Enabled Stencil File (.vssm) är Microsoft Visio Stencil-filer som ger stöd för makron. En VSSM-fil som öppnas gör det möjligt att köra makron för att uppnå önskad formatering och placering av former i ett diagram. Läs mer om detta filformat här. |
| [VSX](/viewer/python-net/groupdocs.viewer/filetype/vsx/) | Visio Stencil XML File (.vsx) avser stenciler som består av ritningar och former som används för att skapa diagram i Microsoft Visio. VSX-filer sparas i XML-filformat och stöddes fram till Visio 2013. Läs mer om detta filformat här. |
| [VTX](/viewer/python-net/groupdocs.viewer/filetype/vtx/) | Visio Template XML File (.vtx) är en Microsoft Visio-ritmall som sparas på disk i XML-filformat. Mallen är avsedd att tillhandahålla en fil med grundinställningar som kan användas för att skapa flera Visio-filer med samma inställningar. Läs mer om detta filformat här. |
| [VDW](/viewer/python-net/groupdocs.viewer/filetype/vdw/) | Visio Web Drawing (.vdw) representerar ett filformat som specificerar de strömmar och lagringar som krävs för att rendera en webbritning. Läs mer om detta filformat här. |
| [VDX](/viewer/python-net/groupdocs.viewer/filetype/vdx/) | Visio Drawing XML File (.vdx) representerar alla ritningar eller diagram som skapats i Microsoft Visio, men som sparas i XML-format med .VDX-filändelse. En Visio-ritnings‑XML‑fil skapas i Visio‑programvaran, som utvecklats av Microsoft. Läs mer om detta filformat här. |
| [EPUB](/viewer/python-net/groupdocs.viewer/filetype/epub/) | Open eBook File (.epub) är ett e‑bokfilformat som tillhandahåller ett standardiserat digitalt publiceringsformat för utgivare och läsare. Formatet har blivit så vanligt att det stöds av många e‑läsare och programvaror. Läs mer om detta filformat här. |
| [MOBI](/viewer/python-net/groupdocs.viewer/filetype/mobi/) | Mobipocket eBook (.mobi) är ett av de mest använda e‑bokfilformaten. Formatet är en förbättring av det gamla OEB (Open Ebook Format)-formatet och användes som proprietärt format för Mobipocket Reader. Läs mer om detta filformat här. |
| [AZW3](/viewer/python-net/groupdocs.viewer/filetype/azw3/) | Amazon Kindle Format 8 (KF8) e‑bok är det digitala filformat som utvecklats för Amazon Kindle‑enheter. Formatet är en förbättring av äldre AZW‑filer och används på Kindle Fire‑enheter med bakåtkompatibilitet för de äldre filformaten, dvs. MOBI och AZW. Läs mer om detta filformat här. |
| [MSG](/viewer/python-net/groupdocs.viewer/filetype/msg/) | Outlook Mail Message (.msg) är ett filformat som används av Microsoft Outlook och Exchange för att lagra e‑postmeddelanden, kontakter, möten eller andra uppgifter. Läs mer om detta filformat här. |
| [EML](/viewer/python-net/groupdocs.viewer/filetype/eml/) | E‑Mail Message (.eml) representerar e‑postmeddelanden som sparats med Outlook och andra relevanta program. Nästan alla e‑postklienter stödjer detta filformat på grund av dess överensstämmelse med RFC‑822 Internet Message Format‑standarden. Läs mer om detta filformat här. |
| [NSF](/viewer/python-net/groupdocs.viewer/filetype/nsf/) | Lotus Notes Database (.nsf) Läs mer om detta filformat här. |
| [MBOX](/viewer/python-net/groupdocs.viewer/filetype/mbox/) | Email Mailbox File (.mbox) Läs mer om detta filformat här. |
| [EMLX](/viewer/python-net/groupdocs.viewer/filetype/emlx/) | Apple Mail-meddelande (.emlx) är implementerat och utvecklat av Apple. Apple Mail‑applikationen använder EMLX‑filformatet för att exportera e‑postmeddelanden. Läs mer om detta filformat här. |
| [PST](/viewer/python-net/groupdocs.viewer/filetype/pst/) | Outlook Personal Information Store‑fil (.pst) representerar Outlook Personal Storage Files (även kallade Personal Storage Table) som lagrar olika användarinformation. Läs mer om detta filformat här. |
| [OST](/viewer/python-net/groupdocs.viewer/filetype/ost/) | Outlook Offline Data‑fil (.ost) representerar användarens brevlådedata i offline‑läge på den lokala maskinen efter registrering med Exchange Server via Microsoft Outlook. Läs mer om detta filformat här. |
| [TIF](/viewer/python-net/groupdocs.viewer/filetype/tif/) | Tagged Image File (.tif) representerar rasterbilder som är avsedda för användning på en mängd olika enheter som följer detta filformatstandard. Den kan beskriva tvånivå-, gråskala-, palett‑färg‑ och fullfärgsbilddata i flera färgrymder. Läs mer om detta filformat här. |
| [TIFF](/viewer/python-net/groupdocs.viewer/filetype/tiff/) | Tagged Image File Format (.tiff) representerar rasterbilder som är avsedda för användning på en mängd olika enheter som följer detta filformatstandard. Den kan beskriva tvånivå-, gråskala-, palett‑färg‑ och fullfärgsbilddata i flera färgrymder. Läs mer om detta filformat här. |
| [JPG](/viewer/python-net/groupdocs.viewer/filetype/jpg/) | JPEG‑bild (.jpg) är en typ av bildformat som sparas med förlustkomprimering. Den resulterande bilden är en avvägning mellan lagringsstorlek och bildkvalitet. Läs mer om detta filformat här. |
| [JPEG](/viewer/python-net/groupdocs.viewer/filetype/jpeg/) | JPEG‑bild (.jpeg) är en typ av bildformat som sparas med förlustkomprimering. Den resulterande bilden är en avvägning mellan lagringsstorlek och bildkvalitet. Läs mer om detta filformat här. |
| [JFIF](/viewer/python-net/groupdocs.viewer/filetype/jfif/) | JPEG File Interchange Format (.jfif) är en bild som utvecklades för snabb överföring mellan plattformar. Detta format använder JPEG‑komprimering. Läs mer om detta filformat här. |
| [PNG](/viewer/python-net/groupdocs.viewer/filetype/png/) | Portable Network Graphic (.png) är en typ av rasterbildfilformat som använder förlustfri komprimering. Detta filformat skapades som en ersättning för Graphics Interchange Format (GIF) och har inga upphovsrättsliga begränsningar. Läs mer om detta filformat här. |
| [GIF](/viewer/python-net/groupdocs.viewer/filetype/gif/) | Graphical Interchange Format‑fil (.gif) är en typ av starkt komprimerad bild. För varje bild tillåter GIF vanligtvis upp till 8 bitar per pixel och upp till 256 färger över bilden. Läs mer om detta filformat här. |
| [APNG](/viewer/python-net/groupdocs.viewer/filetype/apng/) | Animated Portable Network Graphic (.apng) är en utökning av PNG‑formatet som stödjer animation. Läs mer om detta filformat här. |
| [BMP](/viewer/python-net/groupdocs.viewer/filetype/bmp/) | Bitmap Image File (.bmp) används för att lagra bitmap‑digitala bilder. Dessa bilder är oberoende av grafikadapter och kallas även device independent bitmap (DIB)‑filformat. Läs mer om detta filformat här. |
| [TGA](/viewer/python-net/groupdocs.viewer/filetype/tga/) | Truevision TGA (Truevision Advanced Raster Adapter – TARGA) används för att lagra bitmap‑digitala bilder utvecklade av TRUEVISION. Läs mer om detta filformat här. |
| [ICO](/viewer/python-net/groupdocs.viewer/filetype/ico/) | Icon‑fil (.ico) är bildfiltyper som används som ikon för att representera ett program på Microsoft Windows. Läs mer om detta filformat här. |
| [JP2](/viewer/python-net/groupdocs.viewer/filetype/jp2/) | JPEG 2000 Core Image File (.jp2) är ett bildkodningssystem och en toppmodern bildkomprimeringsstandard. Läs mer om detta filformat här. |
| [JPF](/viewer/python-net/groupdocs.viewer/filetype/jpf/) | JPEG 2000 Image File (.jpf) |
| [JPX](/viewer/python-net/groupdocs.viewer/filetype/jpx/) | JPEG 2000 Image File (.jpx) |
| [JPM](/viewer/python-net/groupdocs.viewer/filetype/jpm/) | JPEG 2000-bildfil (.jpm) |
| [J2C](/viewer/python-net/groupdocs.viewer/filetype/j2c/) | JPEG 2000-kodström (.j2c) |
| [J2K](/viewer/python-net/groupdocs.viewer/filetype/j2k/) | JPEG 2000 Code Stream (.j2k) är en bild som komprimeras med wavelet‑komprimering istället för DCT‑komprimering. Läs mer om detta filformat här. |
| [JPC](/viewer/python-net/groupdocs.viewer/filetype/jpc/) | JPEG 2000-kodström (.jpc) |
| [JLS](/viewer/python-net/groupdocs.viewer/filetype/jls/) | JPEG-LS (JLS) (.jls) |
| [DIB](/viewer/python-net/groupdocs.viewer/filetype/dib/) | Enhetsoberoende bitmapfil (.dib) |
| [WMF](/viewer/python-net/groupdocs.viewer/filetype/wmf/) | Windows Metafile (.wmf) representerar Microsoft Windows Metafile (WMF) för lagring av både vektor‑ och bitmapformatbilder. Läs mer om detta filformat här. |
| [WMZ](/viewer/python-net/groupdocs.viewer/filetype/wmz/) | Compressed Windows Metafile (.wmz) representerar Microsoft Windows Metafile (WMF) komprimerad i GZIP‑arkiv – för lagring av både vektor‑ och bitmapformatbilder. Läs mer om detta filformat här. |
| [EMF](/viewer/python-net/groupdocs.viewer/filetype/emf/) | Enhanced Windows Metafile (.emf) representerar grafiska bilder enhetsoberoende. EMF‑metafiler består av variabelängdliga poster i kronologisk ordning som kan återge den lagrade bilden efter tolkning på vilken utskriftsenhet som helst. Läs mer om detta filformat här. |
| [EMZ](/viewer/python-net/groupdocs.viewer/filetype/emz/) | Enhanced Windows Metafile compressed (.emz) representerar grafiska bilder enhetsoberoende komprimerade med GZIP. EMF‑metafiler består av variabelängdliga poster i kronologisk ordning som kan återge den lagrade bilden efter tolkning på vilken utskriftsenhet som helst. Läs mer om detta filformat här. |
| [WEBP](/viewer/python-net/groupdocs.viewer/filetype/webp/) | WebP Image (.webp) är ett modernt rasterwebb‑bildfilformat som är baserat på förlustfri och förlustkomprimering. Det ger samma bildkvalitet samtidigt som det avsevärt minskar bildstorleken. Läs mer om detta filformat här. |
| [DNG](/viewer/python-net/groupdocs.viewer/filetype/dng/) | Digital Negative Specification (.dng) är ett digitalt kamerabildformat som används för lagring av råfiler. Det utvecklades av Adobe i september 2004. Det utvecklades i princip för digital fotografering. Läs mer om detta filformat här. |
| [CDR](/viewer/python-net/groupdocs.viewer/filetype/cdr/) | CorelDraw Vector Graphic Drawing (.cdr) är en vektorritningsbildfil som ursprungligen skapas med CorelDRAW för lagring av digitala bilder som kodas och komprimeras. En sådan ritningsfil innehåller text, linjer, former, bilder, färger och effekter för vektorrepräsentation av bildinnehåll. Läs mer om detta filformat här. |
| [CMX](/viewer/python-net/groupdocs.viewer/filetype/cmx/) | Corel Exchange (.cmx) är en ritningsbildfil som kan innehålla både vektorgrafik och bitmapgrafik. Läs mer om detta filformat här. |
| [DJVU](/viewer/python-net/groupdocs.viewer/filetype/djvu/) | DjVu Image (.djvu) är ett grafikfilformat avsett för skannade dokument och böcker, särskilt de som innehåller en kombination av text, teckningar, bilder och fotografier. Läs mer om detta filformat här. |
| [CGM](/viewer/python-net/groupdocs.viewer/filetype/cgm/) | Computer Graphics Metafile (.cgm) är ett fritt, plattformsoberoende, internationellt standardmetafilformat för lagring och utbyte av vektorgrafik (2D), rastergrafik och text. CGM använder ett objektorienterat tillvägagångssätt och många funktionsmöjligheter för bildproduktion. Läs mer om detta filformat här. |
| [PCL](/viewer/python-net/groupdocs.viewer/filetype/pcl/) | Printer Command Language-dokument (.pcl) |
| [PSD](/viewer/python-net/groupdocs.viewer/filetype/psd/) | Adobe Photoshop Document (.psd) representerar Adobe Photoshops inhemska filformat som används för grafisk design och utveckling. Läs mer om detta filformat här. |
| [PSB](/viewer/python-net/groupdocs.viewer/filetype/psb/) | Photoshop Large Document Format (.psb) representerar Photoshop Large Document Format som används för grafisk design och utveckling. Läs mer om detta filformat här. |
| [DCM](/viewer/python-net/groupdocs.viewer/filetype/dcm/) | DICOM-bild (.dcm) representerar en digital bild som lagrar medicinsk information om patienter såsom MR, CT-skanningar och ultraljudsbilder. Läs mer om detta filformat här. |
| [PS](/viewer/python-net/groupdocs.viewer/filetype/ps/) | PostScript-fil (.ps) |
| [EPS](/viewer/python-net/groupdocs.viewer/filetype/eps/) | Encapsulated PostScript-fil (.eps) beskriver ett Encapsulated PostScript-språkprogram som beskriver utseendet på en enskild sida. Läs mer om detta filformat här. |
| [ODG](/viewer/python-net/groupdocs.viewer/filetype/odg/) | OpenDocument-grafikfil (.odg) används av Apache OpenOffice Draw för att lagra ritningskomponenter som en vektorbild. Läs mer om detta filformat här. |
| [FODG](/viewer/python-net/groupdocs.viewer/filetype/fodg/) | Flat XML ODF-mall (.fodg) används av Apache OpenOffice Draw för att lagra ritningskomponenter som en vektorbild. Läs mer om detta filformat här. |
| [SVG](/viewer/python-net/groupdocs.viewer/filetype/svg/) | Scalable Vector Graphics-fil (.svg) är en skalär vektorgrafikfil som använder ett XML-baserat textformat för att beskriva en bilds utseende. Läs mer om detta filformat här. |
| [SVGZ](/viewer/python-net/groupdocs.viewer/filetype/svgz/) | Scalable Vector Graphics-fil (.svgz) är en skalär vektorgrafikfil som använder ett XML-baserat textformat, komprimerat med GZIP, för att beskriva en bilds utseende. Läs mer om detta filformat här. |
| [OTG](/viewer/python-net/groupdocs.viewer/filetype/otg/) | OpenDocument-grafikmall (.otg) |
| [HTM](/viewer/python-net/groupdocs.viewer/filetype/htm/) | Hypertext Markup Language-fil (.htm) är filändelsen för webbsidor som skapats för visning i webbläsare. Läs mer om detta filformat här. |
| [HTML](/viewer/python-net/groupdocs.viewer/filetype/html/) | Hypertext Markup Language-fil (.html) är filändelsen för webbsidor som skapats för visning i webbläsare. Läs mer om detta filformat här. |
| [MHT](/viewer/python-net/groupdocs.viewer/filetype/mht/) | MHTML-webbarkiv (.mht) |
| [MHTML](/viewer/python-net/groupdocs.viewer/filetype/mhtml/) | MIME HTML-fil (.mhtml) |
| [XML](/viewer/python-net/groupdocs.viewer/filetype/xml/) | XML-fil (.xml). GroupDocs.Viewer har en speciell processor för att hantera XML-filer, se dokumentationen. |
| [ONE](/viewer/python-net/groupdocs.viewer/filetype/one/) | OneNote-dokument (.one) skapas av Microsoft OneNote-applikationen. OneNote låter dig samla information med applikationen som om du använde ditt anteckningsblock för att ta anteckningar. Läs mer om detta filformat här. |
| [PDF](/viewer/python-net/groupdocs.viewer/filetype/pdf/) | Portable Document Format-fil (.pdf) är en typ av dokument som skapades av Adobe på 1990-talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av programvara, hårdvara samt operativsystem. Läs mer om detta filformat här. |
| [XPS](/viewer/python-net/groupdocs.viewer/filetype/xps/) | XML Paper Specification-fil (.xps) representerar sidlayoutfiler som är baserade på XML Paper Specifications skapade av Microsoft. Detta format utvecklades av Microsoft som en ersättning för EMF-filformatet och liknar PDF-filformatet, men använder XML för layout, utseende och utskriftsinformation i ett dokument. Läs mer om detta filformat här. |
| [OXPS](/viewer/python-net/groupdocs.viewer/filetype/oxps/) | OpenXPS-fil (.oxps) |
| [TEX](/viewer/python-net/groupdocs.viewer/filetype/tex/) | LaTeX-källdokument (.tex) är ett språk som omfattar både programmerings- och markup-funktioner, och används för att sätta dokument. Läs mer om detta filformat här. |
| [OFD](/viewer/python-net/groupdocs.viewer/filetype/ofd/) | Open Fixed-layout Document (OFD)-formatet definierat av GB/T 33190-2016 syftar till att ersätta PDF i kinesiska offentliga institutioner |
| [PPT](/viewer/python-net/groupdocs.viewer/filetype/ppt/) | PowerPoint-presentation (.ppt) representerar en PowerPoint-fil som består av en samling bilder för visning som bildspel. Den specificerar det binära filformatet som används av Microsoft PowerPoint 97-2003. Läs mer om detta filformat här. |
| [PPTX](/viewer/python-net/groupdocs.viewer/filetype/pptx/) | PowerPoint Open XML Presentation (.pptx) är presentationsfiler som skapats med det populära Microsoft PowerPoint-programmet. Till skillnad från den tidigare versionen av presentationsfilformatet PPT som var binärt, är PPTX-formatet baserat på Microsoft PowerPoints öppna XML‑presentationsfilformat. Läs mer om detta filformat här. |
| [PPS](/viewer/python-net/groupdocs.viewer/filetype/pps/) | PowerPoint Slide Show (.pps) skapas med Microsoft PowerPoint för bildspelsändamål. Läsning och skapande av PPS‑filer stöds av Microsoft PowerPoint 97-2003. Läs mer om detta filformat här. |
| [PPSX](/viewer/python-net/groupdocs.viewer/filetype/ppsx/) | PowerPoint Open XML Slide Show (.ppsx)-filer skapas med Microsoft PowerPoint 2007 och senare för bildspelsändamål. Läs mer om detta filformat här. |
| [ODP](/viewer/python-net/groupdocs.viewer/filetype/odp/) | OpenDocument Presentation (.odp) representerar presentationsfilformatet som används av OpenOffice.org i OASIS Open‑standarden. Läs mer om detta filformat här. |
| [FODP](/viewer/python-net/groupdocs.viewer/filetype/fodp/) | OpenDocument Presentation (.fodp) representerar OpenDocument Flat XML Presentation. Läs mer om detta filformat här. |
| [POT](/viewer/python-net/groupdocs.viewer/filetype/pot/) | PowerPoint Template (.pot) representerar Microsoft PowerPoint‑mallfiler som skapats av PowerPoint 97-2003‑versionerna. Läs mer om detta filformat här. |
| [PPTM](/viewer/python-net/groupdocs.viewer/filetype/pptm/) | PowerPoint Open XML Macro-Enabled Presentation är makroaktiverade presentationsfiler som skapats med Microsoft PowerPoint 2007 eller senare versioner. Läs mer om detta filformat här. |
| [POTX](/viewer/python-net/groupdocs.viewer/filetype/potx/) | PowerPoint Open XML Presentation Template (.potx) representerar Microsoft PowerPoint‑mallpresentationer som skapats med Microsoft PowerPoint 2007 och senare. Läs mer om detta filformat här. |
| [POTM](/viewer/python-net/groupdocs.viewer/filetype/potm/) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) är Microsoft PowerPoint‑mallfiler med stöd för makron. POTM‑filer skapas med PowerPoint 2007 eller senare och innehåller standardinställningar som kan användas för att skapa ytterligare presentationsfiler. Läs mer om detta filformat här. |
| [PPSM](/viewer/python-net/groupdocs.viewer/filetype/ppsm/) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) representerar makroaktiverat bildspelsfilformat skapat med Microsoft PowerPoint 2007 eller senare. Läs mer om detta filformat här. |
| [OTP](/viewer/python-net/groupdocs.viewer/filetype/otp/) | OpenDocument Presentation Template (.otp) representerar presentationsmallfiler som skapats av program i OASIS OpenDocument‑standardformatet. Läs mer om detta filformat här. |
| [XLS](/viewer/python-net/groupdocs.viewer/filetype/xls/) | Excel Spreadsheet (.xls) representerar Excel Binary File Format. Sådana filer kan skapas av Microsoft Excel såväl som andra liknande kalkylprogram som OpenOffice Calc eller Apple Numbers. Läs mer om detta filformat här. |
| [EXCEL_2003XML](/viewer/python-net/groupdocs.viewer/filetype/excel_2003xml/) | Excel 2003 XML (SpreadsheetML) representerar Excel Binary File Format. Sådana filer kan skapas av Microsoft Excel såväl som andra liknande kalkylprogram som OpenOffice Calc eller Apple Numbers. Läs mer om detta filformat här. |
| [NUMBERS](/viewer/python-net/groupdocs.viewer/filetype/numbers/) | Apple Numbers representerar ett Excel‑likt binärt filformat. Sådana filer kan skapas av Apple Numbers‑applikationen. Läs mer om detta filformat här. |
| [XLSX](/viewer/python-net/groupdocs.viewer/filetype/xlsx/) | Microsoft Excel Open XML Spreadsheet (.xlsx) är ett välkänt format för Microsoft Excel‑dokument som introducerades av Microsoft med lanseringen av Microsoft Office 2007. Läs mer om detta filformat här. |
| [XLSM](/viewer/python-net/groupdocs.viewer/filetype/xlsm/) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) är en typ av kalkylfiler som stödjer makron. Läs mer om detta filformat här. |
| [XLSB](/viewer/python-net/groupdocs.viewer/filetype/xlsb/) | Excel Binary Spreadsheet (.xlsb) specificerar Excel Binary File Format, som är en samling av poster och strukturer som specificerar innehållet i en Excel-arbetsbok. Läs mer om detta filformat här. |
| [CSV](/viewer/python-net/groupdocs.viewer/filetype/csv/) | Comma Separated Values File (.csv) representerar textfiler som innehåller dataposter med kommaseparerade värden. Läs mer om detta filformat här. |
| [TSV](/viewer/python-net/groupdocs.viewer/filetype/tsv/) | Tab Separated Values File (.tsv) representerar data separerad med tabbar i ett vanligt textformat. Läs mer om detta filformat här. |
| [ODS](/viewer/python-net/groupdocs.viewer/filetype/ods/) | OpenDocument Spreadsheet (.ods) står för OpenDocument Spreadsheet-dokumentformat som kan redigeras av användaren. Data lagras i ODF-filen i rader och kolumner. Läs mer om detta filformat här. |
| [FODS](/viewer/python-net/groupdocs.viewer/filetype/fods/) | OpenDocument Flat XML Spreadsheet (.fods) |
| [OTS](/viewer/python-net/groupdocs.viewer/filetype/ots/) | OpenDocument Spreadsheet Template (.ots) |
| [XLAM](/viewer/python-net/groupdocs.viewer/filetype/xlam/) | Microsoft Excel Add-in (.xlam) |
| [XLTM](/viewer/python-net/groupdocs.viewer/filetype/xltm/) | Microsoft Excel Macro-Enabled Template (.xltm) representerar filer som genereras av Microsoft Excel som makroaktiverade mallfiler. XLTM-filer är liknande XLTX i struktur förutom att den senare inte stödjer att skapa mallfiler med makron. Läs mer om detta filformat här. |
| [XLT](/viewer/python-net/groupdocs.viewer/filetype/xlt/) | Microsoft Excel Template (.xlt) är mallfiler skapade med Microsoft Excel, som är ett kalkylprogram som ingår i Microsoft Office-paketet. Microsoft Office 97-2003 stödde att skapa nya XLT-filer samt att öppna dem. Läs mer om detta filformat här. |
| [XLTX](/viewer/python-net/groupdocs.viewer/filetype/xltx/) | Excel Open XML Spreadsheet Template (.xltx) representerar Microsoft Excel-mallar som är baserade på Office OpenXML-filformatsspecifikationerna. Den används för att skapa en standardmallfil som kan användas för att generera XLSX-filer som har samma inställningar som specificerade i XLTX-filen. Läs mer om detta filformat här. |
| [SXC](/viewer/python-net/groupdocs.viewer/filetype/sxc/) | StarOffice Calc Spreadsheet (.sxc) |
| [MPP](/viewer/python-net/groupdocs.viewer/filetype/mpp/) | Microsoft Project File (.mpp) är en Microsoft Project-datafil som lagrar information relaterad till projektledning på ett integrerat sätt. Läs mer om detta filformat här. |
| [MPT](/viewer/python-net/groupdocs.viewer/filetype/mpt/) | Microsoft Project Template (.mpt) innehåller grundläggande information och struktur samt dokumentinställningar för att skapa .MPP-filer. Läs mer om detta filformat här. |
| [MPX](/viewer/python-net/groupdocs.viewer/filetype/mpx/) | Microsoft Project Exchange file (.mpx) är ett ASCII-filformat för överföring av projektinformation mellan Microsoft Project (MSP) och andra program som stödjer MPX-filformatet, såsom Primavera Project Planner, Sciforma och Timerline Precision Estimating. Läs mer om detta filformat här. |
| [AS_](/viewer/python-net/groupdocs.viewer/filetype/as_/) | ActionScript File (.as) |
| [AS3](/viewer/python-net/groupdocs.viewer/filetype/as3/) | ActionScript File (.as) |
| [ASM](/viewer/python-net/groupdocs.viewer/filetype/asm/) | Assembly Language Source Code File (.asm) |
| [BAT](/viewer/python-net/groupdocs.viewer/filetype/bat/) | DOS Batch File (.bat) |
| [C](/viewer/python-net/groupdocs.viewer/filetype/c/) | C/C++ Source Code File (.c) |
| [CC](/viewer/python-net/groupdocs.viewer/filetype/cc/) | C++ Source Code File (.cc) |
| [CMAKE](/viewer/python-net/groupdocs.viewer/filetype/cmake/) | CMake File (.cmake) |
| [CPP](/viewer/python-net/groupdocs.viewer/filetype/cpp/) | C++ Source Code File (.cpp) |
| [CS](/viewer/python-net/groupdocs.viewer/filetype/cs/) | C# Source Code File (.cs) är en källkodfil för C#-programmeringsspråket. Introducerad av Microsoft för användning med .NET Framework. Läs mer om detta filformat här. |
| [VB](/viewer/python-net/groupdocs.viewer/filetype/vb/) | Visual Basic Project Item File (.vb) är en källkodfil skapad i Visual Basic-språket som utvecklats av Microsoft för utveckling av .NET-applikationer. Läs mer om detta filformat här. |
| [CSS](/viewer/python-net/groupdocs.viewer/filetype/css/) | Cascading Style Sheet (.css) |
| [CXX](/viewer/python-net/groupdocs.viewer/filetype/cxx/) | C++ Source Code File (.cxx) |
| [DIFF](/viewer/python-net/groupdocs.viewer/filetype/diff/) | Patchfil (.diff) |
| [ERB](/viewer/python-net/groupdocs.viewer/filetype/erb/) | Ruby ERB‑skript (.erb) |
| [GROOVY](/viewer/python-net/groupdocs.viewer/filetype/groovy/) | Groovy‑källkodfil (.groovy) |
| [H](/viewer/python-net/groupdocs.viewer/filetype/h/) | C/C++/Objective-C‑headerfil (.h) |
| [HAML](/viewer/python-net/groupdocs.viewer/filetype/haml/) | Haml‑källkodfil (.haml) |
| [HH](/viewer/python-net/groupdocs.viewer/filetype/hh/) | C++‑headerfil (.hh) |
| [JAVA](/viewer/python-net/groupdocs.viewer/filetype/java/) | Java‑källkodfil (.java) |
| [JS](/viewer/python-net/groupdocs.viewer/filetype/js/) | JavaScript‑fil (.js) |
| [JSON](/viewer/python-net/groupdocs.viewer/filetype/json/) | JavaScript Object Notation‑fil (.json) |
| [LESS](/viewer/python-net/groupdocs.viewer/filetype/less/) | LESS‑stilmall (.less) |
| [LOG](/viewer/python-net/groupdocs.viewer/filetype/log/) | Loggfil (.log) |
| [M](/viewer/python-net/groupdocs.viewer/filetype/m/) | Objective-C‑implementeringsfil (.m) |
| [MAKE](/viewer/python-net/groupdocs.viewer/filetype/make/) | Xcode Makefile‑skript (.make) |
| [MD](/viewer/python-net/groupdocs.viewer/filetype/md/) | Markdown‑dokumentationsfil (.md) |
| [ML](/viewer/python-net/groupdocs.viewer/filetype/ml/) | ML‑källkodfil (.ml) |
| [MM](/viewer/python-net/groupdocs.viewer/filetype/mm/) | Objective-C++‑källkodfil (.mm) |
| [PHP](/viewer/python-net/groupdocs.viewer/filetype/php/) | PHP‑källkodfil (.php) |
| [PL](/viewer/python-net/groupdocs.viewer/filetype/pl/) | Perl‑skript (.pl) |
| [PROPERTIES](/viewer/python-net/groupdocs.viewer/filetype/properties/) | Java‑egenskapsfil (.properties) |
| [PY](/viewer/python-net/groupdocs.viewer/filetype/py/) | Python‑skript (.py) |
| [RB](/viewer/python-net/groupdocs.viewer/filetype/rb/) | Ruby‑källkod (.rb) |
| [RST](/viewer/python-net/groupdocs.viewer/filetype/rst/) | reStructuredText‑fil (.rst) |
| [SASS](/viewer/python-net/groupdocs.viewer/filetype/sass/) | Syntactically Awesome StyleSheets‑fil (.sass) |
| [SCALA](/viewer/python-net/groupdocs.viewer/filetype/scala/) | Scala‑källkodfil (.scala) |
| [SCM](/viewer/python-net/groupdocs.viewer/filetype/scm/) | Scheme‑källkodfil (.scm) |
| [SCRIPT](/viewer/python-net/groupdocs.viewer/filetype/script/) | Generisk skriptfil (.script) |
| [SH](/viewer/python-net/groupdocs.viewer/filetype/sh/) | Bash-skalsskript (.sh) |
| [SML](/viewer/python-net/groupdocs.viewer/filetype/sml/) | Standard ML‑källkodfil (.sml) |
| [SQL](/viewer/python-net/groupdocs.viewer/filetype/sql/) | Structured Query Language‑datafil (.sql) |
| [VIM](/viewer/python-net/groupdocs.viewer/filetype/vim/) | Vim‑inställningsfil (.vim) |
| [YAML](/viewer/python-net/groupdocs.viewer/filetype/yaml/) | YAML‑dokument (.yaml) |
| [DOC](/viewer/python-net/groupdocs.viewer/filetype/doc/) | Microsoft Word‑dokument (.doc) representerar dokument som genereras av Microsoft Word eller andra ordbehandlingsdokument i binärt filformat. Läs mer om detta filformat här. |
| [DOCX](/viewer/python-net/groupdocs.viewer/filetype/docx/) | Microsoft Word Open XML‑dokument (.docx) är ett välkänt format för Microsoft Word‑dokument. Introducerades 2007 med utgivningen av Microsoft Office 2007, strukturen för detta nya dokumentformat ändrades från ren binär till en kombination av XML‑ och binära filer. Läs mer om detta filformat här. |
| [CHM](/viewer/python-net/groupdocs.viewer/filetype/chm/) | Microsoft Compiled HTML Help‑fil (.chm) är ett välkänt format för HELP (dokumentation till någon applikation) dokument. Läs mer om detta filformat här. |
| [DOCM](/viewer/python-net/groupdocs.viewer/filetype/docm/) | Word Open XML‑makroaktiverat dokument (.docm) är ett Microsoft Word 2007 eller senare genererat dokument med möjlighet att köra makron. Läs mer om detta filformat här. |
| [DOT](/viewer/python-net/groupdocs.viewer/filetype/dot/) | Word‑dokumentmall (.dot) är mallfiler som skapats av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOC‑ eller DOCX‑filer. Läs mer om detta filformat här. |
| [DOTX](/viewer/python-net/groupdocs.viewer/filetype/dotx/) | Word Open XML‑dokumentmall (.dotx) är mallfiler som skapats av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOCX‑filer. Läs mer om detta filformat här. |
| [DOTM](/viewer/python-net/groupdocs.viewer/filetype/dotm/) | Word Open XML‑makroaktiverad dokumentmall (.dotm) representerar mallfil skapad med Microsoft Word 2007 eller senare. Läs mer om detta filformat här. |
| [RTF](/viewer/python-net/groupdocs.viewer/filetype/rtf/) | Rich Text Format‑fil (.rtf) representerar en metod för att koda formaterad text och grafik för användning i applikationer. Läs mer om detta filformat här. |
| [TXT](/viewer/python-net/groupdocs.viewer/filetype/txt/) | Vanlig textfil (.txt) representerar ett textdokument som innehåller vanlig text i form av rader. Läs mer om detta filformat här. |
| [ODT](/viewer/python-net/groupdocs.viewer/filetype/odt/) | OpenDocument Text‑dokument (.odt) är en typ av dokument som skapats med ordbehandlingsprogram som är baserade på OpenDocument Text‑filformatet. Läs mer om detta filformat här. |
| [OTT](/viewer/python-net/groupdocs.viewer/filetype/ott/) | OpenDocument‑dokumentmall (.ott) representerar mall‑dokument som genererats av program i enlighet med OASIS' OpenDocument‑standardformat. Läs mer om detta filformat här. |
| [VCF](/viewer/python-net/groupdocs.viewer/filetype/vcf/) | vCard‑fil (.vcf) är ett digitalt filformat för lagring av kontaktinformation. Formatet används i stor utsträckning för datautbyte bland populära informationsutbytesprogram. Läs mer om detta filformat här. |
| [AI](/viewer/python-net/groupdocs.viewer/filetype/ai/) | Adobe Illustrator (.ai) är ett filformat för Adobe Illustrator‑ritningar. Läs mer om detta filformat här. |
| [PSM1](/viewer/python-net/groupdocs.viewer/filetype/psm1/) | PowerShell‑skriptmodul (.psm1) är ett filformat för PowerShell‑modulskript. Läs mer om detta filformat här. |
| [PS1](/viewer/python-net/groupdocs.viewer/filetype/ps1/) | PowerShell‑skriptfil (.ps1) är ett filformat för Windows PowerShell Cmdlet‑filer. Läs mer om detta filformat här. |
| [PSD1](/viewer/python-net/groupdocs.viewer/filetype/psd1/) | PowerShell‑skriptmodulmanifest (.psd1) är ett filformat för PowerShell‑modulmanifest‑skript. Läs mer om detta filformat här. |

### Exempel

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

# Ange filtypen (t.ex. Markdown) när du laddar dokumentet
load_options = LoadOptions(FileType.MD)

# Rendera dokumentet till PDF
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### Se även
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
