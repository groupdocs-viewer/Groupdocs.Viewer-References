---
title: "FileType klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Stelt een bestandstype voor en biedt methoden om de lijst van alle bestandstypen die door GroupDocs.Viewer worden ondersteund op te halen."
type: docs
url: /nl/python-net/groupdocs.viewer/filetype/
is_root: false
weight: 10
---


## FileType class

Stelt een bestandstype voor en biedt methoden om de lijst van alle bestandstypen die door GroupDocs.Viewer worden ondersteund op te halen.

Het FileType-type biedt de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/) | Initialiseert een nieuw exemplaar van [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/). |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/#file_format-extension) | Initialiseert een nieuw FileType-exemplaar. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#file_path) | Detecteert de codering van tekst‑TXT, TSV‑ en CSV‑bestanden op basis van pad. |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#stream) | Probeert de codering van tekstbestanden (TXT, TSV, CSV) uit een stream te detecteren. |
| [detect_encoding_file](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_file/) |  |
| [detect_encoding_stream](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_stream/) |  |
| [detect_encoding_streams](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_streams/) |  |
| [detect_encoding_string](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_string/) |  |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#other) | Bepaalt of de huidige [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) hetzelfde is als de opgegeven [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/). |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#obj) | Bepaalt of de huidige [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) hetzelfde is als het opgegeven object. |
| [equals_file_type](/viewer/python-net/groupdocs.viewer/filetype/equals_file_type/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer/filetype/equals_object/) |  |
| [from_extension](/viewer/python-net/groupdocs.viewer/filetype/from_extension/#extension) | Koppelt bestandsextensie aan bestandstype. |
| [from_file_path](/viewer/python-net/groupdocs.viewer/filetype/from_file_path/#file_path) | Haalt de bestandsextensie op en koppelt deze aan een bestandstype. |
| [from_media_type](/viewer/python-net/groupdocs.viewer/filetype/from_media_type/#media_type) | Koppelt een bestandsmediatype aan een [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) (bijv. 'application/pdf' koppelt aan [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)). |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream) | Detecteert bestandstype door de bestandssignatuur te lezen. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password) | Detecteert bestandstype door de bestandssignatuur te lezen. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-logger) | Detecteert bestandstype door de bestandssignatuur te lezen. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password-logger) | Detecteert het bestandstype door de bestandssignatuur te lezen. |
| [from_stream_file](/viewer/python-net/groupdocs.viewer/filetype/from_stream_file/) |  |
| [from_stream_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream_stream/) |  |
| [from_stream_streams](/viewer/python-net/groupdocs.viewer/filetype/from_stream_streams/) |  |
| [from_stream_string](/viewer/python-net/groupdocs.viewer/filetype/from_stream_string/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer/filetype/get_hash_code/) | Retourneert de hashcode voor het huidige [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) object. |
| [get_supported_file_types](/viewer/python-net/groupdocs.viewer/filetype/get_supported_file_types/) | Haalt ondersteunde bestandstypen op. |
| [to_string](/viewer/python-net/groupdocs.viewer/filetype/to_string/) | Retourneert een str die het huidige object vertegenwoordigt. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [extension](/viewer/python-net/groupdocs.viewer/filetype/extension/) | Het bestandsnaamsuffix (inclusief de punt "."), bijv. ".doc". |
| [file_format](/viewer/python-net/groupdocs.viewer/filetype/file_format/) | De bestandstypenaam, bijv. "Microsoft Word Document". |

### Velden
| Veld | Beschrijving |
| :- | :- |
| [UNKNOWN](/viewer/python-net/groupdocs.viewer/filetype/unknown/) | Stelt een onbekend bestandstype voor. |
| [ZIP](/viewer/python-net/groupdocs.viewer/filetype/zip/) | Een Zip‑bestand (.zip) vertegenwoordigt archieven die één of meer bestanden of mappen kunnen bevatten. Meer informatie over dit bestandsformaat vind je hier. |
| [TAR](/viewer/python-net/groupdocs.viewer/filetype/tar/) | Een Consolidated Unix File Archive (.tar) is een archief dat is gemaakt met een Unix‑gebaseerd hulpprogramma om één of meer bestanden te verzamelen. Meer informatie over dit bestandsformaat vind je hier. |
| [XZ](/viewer/python-net/groupdocs.viewer/filetype/xz/) | Een XZ‑bestand (.xz) is een archief gecomprimeerd met een hoogcompressie‑algoritme gebaseerd op het LZMA‑algoritme. Meer informatie over dit bestandsformaat vind je hier. |
| [TXZ](/viewer/python-net/groupdocs.viewer/filetype/txz/) | Een Consolidated Unix File Archive (.txz, .tar.xz) is een archief dat is gemaakt met een Unix‑gebaseerd hulpprogramma om één of meer bestanden te verzamelen. Meer informatie over dit bestandsformaat vind je hier. |
| [TARXZ](/viewer/python-net/groupdocs.viewer/filetype/tarxz/) | Een Consolidated Unix File Archive (.txz, .tar.xz) is een archief dat is gemaakt met een Unix‑gebaseerd hulpprogramma om één of meer bestanden te verzamelen. Meer informatie over dit bestandsformaat vind je hier. |
| [TGZ](/viewer/python-net/groupdocs.viewer/filetype/tgz/) | Een Consolidated Unix File Archive (.tgz, .tar.gz) is een archief dat is gemaakt met een Unix‑gebaseerd hulpprogramma om één of meer bestanden te verzamelen. Meer informatie over dit bestandsformaat vind je hier. |
| [TARGZ](/viewer/python-net/groupdocs.viewer/filetype/targz/) | Een Consolidated Unix File Archive (.tgz, .tar.gz) is een archief dat is gemaakt met een Unix‑gebaseerd hulpprogramma om één of meer bestanden te verzamelen. Meer informatie over dit bestandsformaat vind je hier. |
| [BZ2](/viewer/python-net/groupdocs.viewer/filetype/bz2/) | Een Bzip2‑gecomprimeerd bestand (.bz2) is een gecomprimeerd bestand dat is gegenereerd met de BZIP2 open‑source compressiemethode, meestal op UNIX‑ of Linux‑systemen. Meer informatie over dit bestandsformaat vind je hier. |
| [RAR](/viewer/python-net/groupdocs.viewer/filetype/rar/) | Roshal ARchive (.rar) zijn gecomprimeerde bestanden die zijn gegenereerd met de RAR (WINRAR) compressiemethode. Leer meer over dit bestandsformaat hier. |
| [GZ](/viewer/python-net/groupdocs.viewer/filetype/gz/) | Gnu Zipped File (.gz) zijn gecomprimeerde bestanden die zijn gemaakt met de gzip-compressietoepassing. Het kan meerdere gecomprimeerde bestanden bevatten en wordt vaak gebruikt op UNIX- en Linux-systemen. Leer meer over dit bestandsformaat hier. |
| [GZIP](/viewer/python-net/groupdocs.viewer/filetype/gzip/) | Gnu Zipped File (.gzip) werd geïntroduceerd als een gratis hulpprogramma ter vervanging van het Compress-programma dat in Unix-systemen werd gebruikt. Dergelijke bestanden kunnen worden geopend en uitgepakt met verschillende toepassingen, zoals WinZip, dat beschikbaar is voor zowel Windows als macOS. Leer meer over dit bestandsformaat hier. |
| [SEVEN_ZIP](/viewer/python-net/groupdocs.viewer/filetype/seven_zip/) | 7Zip (.7z, .7zip) is een gratis open‑source archiver met LZMA‑ en LZMA2‑compressie. Leer meer over dit bestandsformaat hier. |
| [CPIO](/viewer/python-net/groupdocs.viewer/filetype/cpio/) | Cpio is een algemene bestandsarchiverings‑utility en het bijbehorende bestandsformaat. Het wordt voornamelijk geïnstalleerd op Unix‑achtige besturingssystemen. Leer meer over dit bestandsformaat hier. |
| [ZSTANDARD](/viewer/python-net/groupdocs.viewer/filetype/zstandard/) | ZST‑bestand is een gecomprimeerd bestand dat wordt gegenereerd met het Zstandard (zstd) compressie‑algoritme. Het is een gecomprimeerd bestand dat met verliesloze compressie door het algoritme wordt gemaakt. ZST‑bestanden kunnen worden gebruikt om verschillende soorten bestanden te comprimeren, zoals databases, bestandssystemen, netwerken en games. Leer meer over dit bestandsformaat hier. |
| [TZST](/viewer/python-net/groupdocs.viewer/filetype/tzst/) | TZST‑bestanden (.tar.zst, .tzst) zijn Zstandard‑archieven (ZST), die intern een Consolidated Unix File Archive (Tar) bevatten, gemaakt met een Unix‑gebaseerde utility voor het verzamelen van één of meer bestanden. |
| [TAR_ZST](/viewer/python-net/groupdocs.viewer/filetype/tar_zst/) | TZST‑bestanden (.tar.zst, .tzst) zijn Zstandard‑archieven (ZST), die intern een Consolidated Unix File Archive (Tar) bevatten, gemaakt met een Unix‑gebaseerde utility voor het verzamelen van één of meer bestanden. |
| [ISO](/viewer/python-net/groupdocs.viewer/filetype/iso/) | ISO‑optische schijf‑image is een ongecomprimeerd archief‑schijf‑image‑bestand dat de inhoud van alle gegevens op een optische schijf zoals een CD of DVD weergeeft, gebaseerd op de ISO‑9660‑standaard. Leer meer over dit bestandsformaat hier. |
| [LHA](/viewer/python-net/groupdocs.viewer/filetype/lha/) | LHA of LZH is een freeware compressie‑utility en het bijbehorende bestandsformaat. Leer meer over dit bestandsformaat hier. |
| [CAB](/viewer/python-net/groupdocs.viewer/filetype/cab/) | Cabinet (of CAB) is een archief‑bestandformaat voor Microsoft Windows. Leer meer over dit bestandsformaat hier. |
| [DXF](/viewer/python-net/groupdocs.viewer/filetype/dxf/) | Drawing Exchange Format File (.dxf) is een getagde gegevensrepresentatie van een AutoCAD‑tekenbestand. Leer meer over dit bestandsformaat hier. |
| [DWG](/viewer/python-net/groupdocs.viewer/filetype/dwg/) | AutoCAD Drawing Database File (.dwg) vertegenwoordigt propriëtaire binaire bestanden die worden gebruikt voor het bevatten van 2D‑ en 3D‑ontwerpgegevens. Net als DXF, dat ASCII‑bestanden zijn, vertegenwoordigt DWG het binaire bestandsformaat voor CAD‑ (Computer‑Aided‑Design) tekeningen. Leer meer over dit bestandsformaat hier. |
| [DWT](/viewer/python-net/groupdocs.viewer/filetype/dwt/) | AutoCAD Drawing Template (.dwt) is een AutoCAD‑tekeningssjabloonbestand dat wordt gebruikt als startpunt voor het maken van tekeningen die kunnen worden opgeslagen als DWG‑bestanden. Leer meer over dit bestandsformaat hier. |
| [STL](/viewer/python-net/groupdocs.viewer/filetype/stl/) | Stereolithography File (.stl) is een uitwisselbaar bestandsformaat dat 3‑dimensionale oppervlakgeometrie weergeeft. Het bestandsformaat wordt gebruikt in verschillende vakgebieden, zoals rapid prototyping, 3D‑printen en computer‑aided manufacturing. Leer meer over dit bestandsformaat hier. |
| [IFC](/viewer/python-net/groupdocs.viewer/filetype/ifc/) | Industry Foundation Classes File (.ifc) is een bestandsformaat dat internationale normen vastlegt voor het importeren en exporteren van bouwobjecten en hun eigenschappen. Dit bestandsformaat biedt interoperabiliteit tussen verschillende softwaretoepassingen. Leer meer over dit bestandsformaat hier. |
| [DWF](/viewer/python-net/groupdocs.viewer/filetype/dwf/) | Design Web Format File (.dwf) vertegenwoordigt 2D/3D‑tekeningen in een gecomprimeerd formaat voor het bekijken, beoordelen of afdrukken van ontwerpbestanden. Het bevat grafische elementen en tekst als onderdeel van ontwerpgegevens en verkleint de bestandsgrootte dankzij het gecomprimeerde formaat. Leer meer over dit bestandsformaat hier. |
| [FBX](/viewer/python-net/groupdocs.viewer/filetype/fbx/) | Autodesk FBX Interchange File (FilmBoX) (.fbx) vertegenwoordigt een 3D‑modelformaat. Leer meer over dit bestandsformaat hier. |
| [DWFX](/viewer/python-net/groupdocs.viewer/filetype/dwfx/) | Design Web Format File XPS (.dwfx) vertegenwoordigt 2D/3D‑tekeningen als XPS‑document in een gecomprimeerd formaat voor het bekijken, beoordelen of afdrukken van ontwerpbestanden. Het bevat grafische elementen en tekst als onderdeel van ontwerpgegevens en verkleint de bestandsgrootte dankzij het gecomprimeerde formaat. Leer meer over dit bestandsformaat hier. |
| [DGN](/viewer/python-net/groupdocs.viewer/filetype/dgn/) | MicroStation Design File (.dgn) zijn tekeningen die zijn gemaakt door en ondersteund worden door CAD‑toepassingen zoals MicroStation en Intergraph Interactive Graphics Design System. Leer meer over dit bestandsformaat hier. |
| [PLT](/viewer/python-net/groupdocs.viewer/filetype/plt/) | PLT (HPGL) (.plt) is een vectorgebaseerd plotterbestand geïntroduceerd door Autodesk, Inc. en bevat informatie voor een bepaald CAD‑bestand. Plotdetails vereisen nauwkeurigheid en precisie in de productie, en het gebruik van PLT‑bestand garandeert dit omdat alle afbeeldingen worden afgedrukt met lijnen in plaats van stippen. Leer meer over dit bestandsformaat hier. |
| [CF2](/viewer/python-net/groupdocs.viewer/filetype/cf2/) | Gemeenschappelijk bestandsformaat bestand Leer meer over dit bestandsformaat hier. |
| [OBJ](/viewer/python-net/groupdocs.viewer/filetype/obj/) | Wavefront 3D Object File (.obj) is een 3D‑afbeeldingsbestand geïntroduceerd door Wavefront Technologies. Leer meer over dit bestandsformaat hier. |
| [HPG](/viewer/python-net/groupdocs.viewer/filetype/hpg/) | PLT (HPGL) (.hpg) |
| [IGS](/viewer/python-net/groupdocs.viewer/filetype/igs/) | Initial Graphics Exchange Specification (IGES) (.igs) |
| [VSD](/viewer/python-net/groupdocs.viewer/filetype/vsd/) | Visio Drawing File (.vsd) zijn tekeningen gemaakt met de Microsoft Visio‑applicatie om een verscheidenheid aan grafische objecten en de onderlinge verbindingen weer te geven. Leer meer over dit bestandsformaat hier. |
| [VSDX](/viewer/python-net/groupdocs.viewer/filetype/vsdx/) | Visio Drawing (.vsdx) vertegenwoordigt het Microsoft Visio‑bestandsformaat dat vanaf Microsoft Office 2013 is geïntroduceerd. Het is ontwikkeld om het binaire bestandsformaat .VSD te vervangen, dat wordt ondersteund door eerdere versies van Microsoft Visio. Leer meer over dit bestandsformaat hier. |
| [VSS](/viewer/python-net/groupdocs.viewer/filetype/vss/) | Visio Stencil File(.vss) zijn stencil‑bestanden gemaakt met Microsoft Visio 2007 en eerder. Stencil‑bestanden bieden tekenobjecten die kunnen worden opgenomen in een .VSD Visio‑tekening. Leer meer over dit bestandsformaat hier. |
| [VSSX](/viewer/python-net/groupdocs.viewer/filetype/vssx/) | Visio Stencil File (.vssx) zijn tekensjablonen gemaakt met Microsoft Visio 2013 en hoger. Het VSSX‑bestandsformaat kan worden geopend met Visio 2013 en hoger. Visio‑bestanden staan bekend om de weergave van een verscheidenheid aan tekenelementen zoals een verzameling vormen, connectoren, stroomdiagrammen, netwerkindelingen, UML‑diagrammen. Leer meer over dit bestandsformaat hier. |
| [VSDM](/viewer/python-net/groupdocs.viewer/filetype/vsdm/) | Visio Macro-Enabled Drawing (.vsdm) zijn tekenbestanden gemaakt met de Microsoft Visio‑applicatie die macro's ondersteunt. VSDM‑bestanden zijn OPC/XML‑tekeningen die vergelijkbaar zijn met VSDX, maar ook de mogelijkheid bieden om macro's uit te voeren wanneer het bestand wordt geopend. Leer meer over dit bestandsformaat hier. |
| [VST](/viewer/python-net/groupdocs.viewer/filetype/vst/) | Visio Drawing Template (.vst) zijn vector‑afbeeldingsbestanden gemaakt met Microsoft Visio en fungeren als sjabloon voor het maken van verdere bestanden. Deze sjabloonbestanden hebben een binair bestandsformaat en bevatten de standaardlay-out en instellingen die worden gebruikt voor het creëren van nieuwe Visio‑tekeningen. Leer meer over dit bestandsformaat hier. |
| [VSTX](/viewer/python-net/groupdocs.viewer/filetype/vstx/) | Visio Drawing Template (.vstx) zijn tekensjabloonbestanden gemaakt met Microsoft Visio 2013 en hoger. Deze VSTX‑bestanden bieden een startpunt voor het maken van Visio‑tekeningen, opgeslagen als .VSDX‑bestanden, met een standaardlay-out en instellingen. Leer meer over dit bestandsformaat hier. |
| [VSTM](/viewer/python-net/groupdocs.viewer/filetype/vstm/) | Visio Macro-Enabled Drawing Template (.vstm) zijn sjabloonbestanden gemaakt met Microsoft Visio die macro's ondersteunen. In tegenstelling tot VSDX‑bestanden kunnen bestanden die zijn gemaakt vanuit VSTM‑sjablonen macro's uitvoeren die zijn ontwikkeld in Visual Basic for Applications (VBA)-code. Leer meer over dit bestandsformaat hier. |
| [VSSM](/viewer/python-net/groupdocs.viewer/filetype/vssm/) | Visio Macro-Enabled Stencil File (.vssm) zijn Microsoft Visio Stencil‑bestanden die ondersteuning voor macro's bieden. Een VSSM‑bestand maakt bij openen het uitvoeren van macro's mogelijk om de gewenste opmaak en plaatsing van vormen in een diagram te bereiken. Leer meer over dit bestandsformaat hier. |
| [VSX](/viewer/python-net/groupdocs.viewer/filetype/vsx/) | Visio Stencil XML File (.vsx) verwijst naar stencils die bestaan uit tekeningen en vormen die worden gebruikt voor het maken van diagrammen in Microsoft Visio. VSX‑bestanden worden opgeslagen in XML‑bestandsformaat en werden ondersteund tot Visio 2013. Leer meer over dit bestandsformaat hier. |
| [VTX](/viewer/python-net/groupdocs.viewer/filetype/vtx/) | Visio Template XML File (.vtx) is een Microsoft Visio‑tekeningssjabloon dat op schijf wordt opgeslagen in XML‑bestandsformaat. Het sjabloon is bedoeld om een bestand met basisinstellingen te bieden dat kan worden gebruikt om meerdere Visio‑bestanden met dezelfde instellingen te maken. Leer meer over dit bestandsformaat hier. |
| [VDW](/viewer/python-net/groupdocs.viewer/filetype/vdw/) | Visio Web Drawing (.vdw) vertegenwoordigt een bestandsformaat dat de streams en opslaglocaties specificeert die nodig zijn voor het weergeven van een webtekening. Leer meer over dit bestandsformaat hier. |
| [VDX](/viewer/python-net/groupdocs.viewer/filetype/vdx/) | Visio Drawing XML File (.vdx) vertegenwoordigt elke tekening of grafiek die is gemaakt in Microsoft Visio, maar opgeslagen in XML‑formaat met .VDX‑extensie. Een Visio‑tekenings‑XML‑bestand wordt aangemaakt in Visio‑software, die door Microsoft is ontwikkeld. Leer meer over dit bestandsformaat hier. |
| [EPUB](/viewer/python-net/groupdocs.viewer/filetype/epub/) | Open eBook File (.epub) is een e‑book bestandsformaat dat een standaard digitaal publicatieformaat biedt voor uitgevers en consumenten. Het formaat is inmiddels zo gangbaar dat het wordt ondersteund door veel e‑readers en softwaretoepassingen. Meer informatie over dit bestandsformaat hier. |
| [MOBI](/viewer/python-net/groupdocs.viewer/filetype/mobi/) | Mobipocket eBook (.mobi) is een van de meest gebruikte ebook bestandsformaten. Het formaat is een verbetering ten opzichte van het oude OEB (Open Ebook Format) formaat en werd gebruikt als propriëtair formaat voor de Mobipocket Reader. Meer informatie over dit bestandsformaat hier. |
| [AZW3](/viewer/python-net/groupdocs.viewer/filetype/azw3/) | Amazon Kindle Format 8 (KF8) ebook is het digitale bestandsformaat dat is ontwikkeld voor Amazon Kindle-apparaten. Het formaat is een verbetering ten opzichte van oudere AZW‑bestanden en wordt alleen op Kindle Fire‑apparaten gebruikt met achterwaartse compatibiliteit voor het oorspronkelijke bestandsformaat, d.w.z. MOBI en AZW. Meer informatie over dit bestandsformaat hier. |
| [MSG](/viewer/python-net/groupdocs.viewer/filetype/msg/) | Outlook Mail Message (.msg) is een bestandsformaat dat wordt gebruikt door Microsoft Outlook en Exchange om e‑mailberichten, contactpersonen, afspraken of andere taken op te slaan. Meer informatie over dit bestandsformaat hier. |
| [EML](/viewer/python-net/groupdocs.viewer/filetype/eml/) | E‑Mail Message (.eml) vertegenwoordigt e‑mailberichten die zijn opgeslagen met Outlook en andere relevante toepassingen. Bijna alle e‑mailclients ondersteunen dit bestandsformaat vanwege de naleving van de RFC‑822 Internet Message Format‑standaard. Meer informatie over dit bestandsformaat hier. |
| [NSF](/viewer/python-net/groupdocs.viewer/filetype/nsf/) | Lotus Notes Database (.nsf) Meer informatie over dit bestandsformaat hier. |
| [MBOX](/viewer/python-net/groupdocs.viewer/filetype/mbox/) | Email Mailbox File (.mbox) Meer informatie over dit bestandsformaat hier. |
| [EMLX](/viewer/python-net/groupdocs.viewer/filetype/emlx/) | Apple Mail Message (.emlx) is geïmplementeerd en ontwikkeld door Apple. De Apple Mail‑applicatie gebruikt het EMLX‑bestandsformaat voor het exporteren van e‑mails. Meer informatie over dit bestandsformaat hier. |
| [PST](/viewer/python-net/groupdocs.viewer/filetype/pst/) | Outlook Personal Information Store File (.pst) vertegenwoordigt Outlook Personal Storage Files (ook wel Personal Storage Table genoemd) die een verscheidenheid aan gebruikersinformatie opslaan. Meer informatie over dit bestandsformaat hier. |
| [OST](/viewer/python-net/groupdocs.viewer/filetype/ost/) | Outlook Offline Data File (.ost) vertegenwoordigt de mailboxgegevens van een gebruiker in offline‑modus op de lokale machine na registratie bij Exchange Server met Microsoft Outlook. Meer informatie over dit bestandsformaat hier. |
| [TIF](/viewer/python-net/groupdocs.viewer/filetype/tif/) | Tagged Image File (.tif) vertegenwoordigt rasterafbeeldingen die bedoeld zijn voor gebruik op verschillende apparaten die voldoen aan deze bestandsformaatstandaard. Het kan bilevel-, grijswaarden-, palet‑kleur‑ en full‑color‑beeldgegevens beschrijven in verschillende kleurruimtes. Meer informatie over dit bestandsformaat hier. |
| [TIFF](/viewer/python-net/groupdocs.viewer/filetype/tiff/) | Tagged Image File Format (.tiff) vertegenwoordigt rasterafbeeldingen die bedoeld zijn voor gebruik op verschillende apparaten die voldoen aan deze bestandsformaatstandaard. Het kan bilevel-, grijswaarden-, palet‑kleur‑ en full‑color‑beeldgegevens beschrijven in verschillende kleurruimtes. Meer informatie over dit bestandsformaat hier. |
| [JPG](/viewer/python-net/groupdocs.viewer/filetype/jpg/) | JPEG Image (.jpg) is een type afbeeldingsformaat dat wordt opgeslagen met behulp van verliesgevende compressie. De resulterende afbeelding is een afweging tussen opslaggrootte en beeldkwaliteit. Meer informatie over dit bestandsformaat hier. |
| [JPEG](/viewer/python-net/groupdocs.viewer/filetype/jpeg/) | JPEG Image (.jpeg) is een type afbeeldingsformaat dat wordt opgeslagen met behulp van verliesgevende compressie. De resulterende afbeelding is een afweging tussen opslaggrootte en beeldkwaliteit. Meer informatie over dit bestandsformaat hier. |
| [JFIF](/viewer/python-net/groupdocs.viewer/filetype/jfif/) | JPEG File Interchange Format (.jfif) is een afbeelding die is ontwikkeld voor snelle uitwisseling tussen platformen. Dit formaat maakt gebruik van JPEG‑compressie. Meer informatie over dit bestandsformaat hier. |
| [PNG](/viewer/python-net/groupdocs.viewer/filetype/png/) | Portable Network Graphic (.png) is een type rasterafbeeldingsformaat dat verliesloze compressie gebruikt. Dit bestandsformaat is gemaakt als vervanging van Graphics Interchange Format (GIF) en heeft geen auteursrechtelijke beperkingen. Meer informatie over dit bestandsformaat hier. |
| [GIF](/viewer/python-net/groupdocs.viewer/filetype/gif/) | Graphical Interchange Format File (.gif) is een type sterk gecomprimeerde afbeelding. Voor elke afbeelding staat GIF doorgaans tot 8 bits per pixel toe en tot 256 kleuren zijn toegestaan over de afbeelding heen. Meer informatie over dit bestandsformaat hier. |
| [APNG](/viewer/python-net/groupdocs.viewer/filetype/apng/) | Animated Portable Network Graphic (.apng) is een uitbreiding van het PNG‑formaat die animatie ondersteunt. Meer informatie over dit bestandsformaat hier. |
| [BMP](/viewer/python-net/groupdocs.viewer/filetype/bmp/) | Bitmap Image File (.bmp) wordt gebruikt om bitmap digitale afbeeldingen op te slaan. Deze afbeeldingen zijn onafhankelijk van de grafische adapter en worden ook wel device independent bitmap (DIB) bestandsformaat genoemd. Leer meer over dit bestandsformaat hier. |
| [TGA](/viewer/python-net/groupdocs.viewer/filetype/tga/) | Truevision TGA (Truevision Advanced Raster Adapter - TARGA) wordt gebruikt om bitmap digitale afbeeldingen op te slaan die ontwikkeld zijn door TRUEVISION. Leer meer over dit bestandsformaat hier. |
| [ICO](/viewer/python-net/groupdocs.viewer/filetype/ico/) | Icon File (.ico) zijn beeldbestandstypen die worden gebruikt als pictogram voor de weergave van een applicatie op Microsoft Windows. Leer meer over dit bestandsformaat hier. |
| [JP2](/viewer/python-net/groupdocs.viewer/filetype/jp2/) | JPEG 2000 Core Image File (.jp2) is een beeldcoderingssysteem en een geavanceerde beeldcompressiestandaard. Leer meer over dit bestandsformaat hier. |
| [JPF](/viewer/python-net/groupdocs.viewer/filetype/jpf/) | JPEG 2000 Afbeeldingsbestand (.jpf) |
| [JPX](/viewer/python-net/groupdocs.viewer/filetype/jpx/) | JPEG 2000 Afbeeldingsbestand (.jpx) |
| [JPM](/viewer/python-net/groupdocs.viewer/filetype/jpm/) | JPEG 2000 Afbeeldingsbestand (.jpm) |
| [J2C](/viewer/python-net/groupdocs.viewer/filetype/j2c/) | JPEG 2000 Code-stroom (.j2c) |
| [J2K](/viewer/python-net/groupdocs.viewer/filetype/j2k/) | JPEG 2000 Code-stroom (.j2k) is een afbeelding die gecomprimeerd is met waveletcompressie in plaats van DCT-compressie. Leer meer over dit bestandsformaat hier. |
| [JPC](/viewer/python-net/groupdocs.viewer/filetype/jpc/) | JPEG 2000 Code-stroom (.jpc) |
| [JLS](/viewer/python-net/groupdocs.viewer/filetype/jls/) | JPEG-LS (JLS) (.jls) |
| [DIB](/viewer/python-net/groupdocs.viewer/filetype/dib/) | Device Independent Bitmap Bestand (.dib) |
| [WMF](/viewer/python-net/groupdocs.viewer/filetype/wmf/) | Windows Metafile (.wmf) vertegenwoordigt Microsoft Windows Metafile (WMF) voor het opslaan van zowel vector- als bitmapformaat afbeeldingsgegevens. Leer meer over dit bestandsformaat hier. |
| [WMZ](/viewer/python-net/groupdocs.viewer/filetype/wmz/) | Compressed Windows Metafile (.wmz) vertegenwoordigt Microsoft Windows Metafile (WMF) gecomprimeerd in GZIP-archief - voor het opslaan van zowel vector- als bitmapformaat afbeeldingsgegevens. Leer meer over dit bestandsformaat hier. |
| [EMF](/viewer/python-net/groupdocs.viewer/filetype/emf/) | Enhanced Windows Metafile (.emf) vertegenwoordigt grafische afbeeldingen apparaat-onafhankelijk. Metabestanden van EMF bestaan uit variabele lengte records in chronologische volgorde die de opgeslagen afbeelding kunnen renderen na parsing op elk uitvoerapparaat. Leer meer over dit bestandsformaat hier. |
| [EMZ](/viewer/python-net/groupdocs.viewer/filetype/emz/) | Enhanced Windows Metafile compressed (.emz) vertegenwoordigt grafische afbeeldingen apparaat-onafhankelijk gecomprimeerd door GZIP. Metabestanden van EMF bestaan uit variabele lengte records in chronologische volgorde die de opgeslagen afbeelding kunnen renderen na parsing op elk uitvoerapparaat. Leer meer over dit bestandsformaat hier. |
| [WEBP](/viewer/python-net/groupdocs.viewer/filetype/webp/) | WebP Image (.webp) is een modern raster webafbeeldingsbestandformaat dat gebaseerd is op verliesloze en verliesgevende compressie. Het biedt dezelfde beeldkwaliteit terwijl het de bestandsgrootte aanzienlijk verkleint. Leer meer over dit bestandsformaat hier. |
| [DNG](/viewer/python-net/groupdocs.viewer/filetype/dng/) | Digital Negative Specification (.dng) is een digitaal camerabeeldformaat dat wordt gebruikt voor de opslag van raw-bestanden. Het is ontwikkeld door Adobe in september 2004. Het is in principe ontwikkeld voor digitale fotografie. Leer meer over dit bestandsformaat hier. |
| [CDR](/viewer/python-net/groupdocs.viewer/filetype/cdr/) | CorelDraw Vector Graphic Drawing (.cdr) is een vector-tekeningsbestand dat native wordt aangemaakt met CorelDRAW voor het opslaan van digitale beelden die gecodeerd en gecomprimeerd zijn. Zo'n tekeningsbestand bevat tekst, lijnen, vormen, afbeeldingen, kleuren en effecten voor vectorrepresentatie van de beeldinhoud. Leer meer over dit bestandsformaat hier. |
| [CMX](/viewer/python-net/groupdocs.viewer/filetype/cmx/) | Corel Exchange (.cmx) is een tekeningsbestand dat zowel vectorafbeeldingen als bitmapafbeeldingen kan bevatten. Leer meer over dit bestandsformaat hier. |
| [DJVU](/viewer/python-net/groupdocs.viewer/filetype/djvu/) | DjVu Image (.djvu) is een grafisch bestandsformaat bedoeld voor gescande documenten en boeken, met name die welke een combinatie van tekst, tekeningen, afbeeldingen en foto’s bevatten. Leer meer over dit bestandsformaat hier. |
| [CGM](/viewer/python-net/groupdocs.viewer/filetype/cgm/) | Computer Graphics Metafile (.cgm) is een gratis, platformonafhankelijk, internationaal standaard metafileformaat voor het opslaan en uitwisselen van vectorgraphics (2D), rastergraphics en tekst. CGM maakt gebruik van een objectgeoriënteerde benadering en vele functievoorzieningen voor beeldproductie. Leer meer over dit bestandsformaat hier. |
| [PCL](/viewer/python-net/groupdocs.viewer/filetype/pcl/) | Printer Command Language-document (.pcl) |
| [PSD](/viewer/python-net/groupdocs.viewer/filetype/psd/) | Adobe Photoshop Document (.psd) vertegenwoordigt het native bestandsformaat van Adobe Photoshop dat wordt gebruikt voor grafisch ontwerp en ontwikkeling. Leer meer over dit bestandsformaat hier. |
| [PSB](/viewer/python-net/groupdocs.viewer/filetype/psb/) | Photoshop Large Document Format (.psb) vertegenwoordigt het Photoshop Large Document Format dat wordt gebruikt voor grafisch ontwerp en ontwikkeling. Leer meer over dit bestandsformaat hier. |
| [DCM](/viewer/python-net/groupdocs.viewer/filetype/dcm/) | DICOM-afbeelding (.dcm) vertegenwoordigt een digitale afbeelding die medische informatie van patiënten opslaat, zoals MRI's, CT-scans en echobeelden. Meer informatie over dit bestandsformaat vindt u hier. |
| [PS](/viewer/python-net/groupdocs.viewer/filetype/ps/) | PostScript-bestand (.ps) |
| [EPS](/viewer/python-net/groupdocs.viewer/filetype/eps/) | Encapsulated PostScript-bestand (.eps) beschrijft een Encapsulated PostScript-taalprogramma dat het uiterlijk van een enkele pagina beschrijft. Meer informatie over dit bestandsformaat vindt u hier. |
| [ODG](/viewer/python-net/groupdocs.viewer/filetype/odg/) | OpenDocument grafisch bestand (.odg) wordt gebruikt door de Draw-toepassing van Apache OpenOffice om tekenelementen op te slaan als een vectorafbeelding. Meer informatie over dit bestandsformaat vindt u hier. |
| [FODG](/viewer/python-net/groupdocs.viewer/filetype/fodg/) | Flat XML ODF-sjabloon (.fodg) wordt gebruikt door de Draw-toepassing van Apache OpenOffice om tekenelementen op te slaan als een vectorafbeelding. Meer informatie over dit bestandsformaat vindt u hier. |
| [SVG](/viewer/python-net/groupdocs.viewer/filetype/svg/) | Scalable Vector Graphics-bestand (.svg) is een Scalar Vector Graphics‑bestand dat een op XML gebaseerd tekstformaat gebruikt om het uiterlijk van een afbeelding te beschrijven. Meer informatie over dit bestandsformaat vindt u hier. |
| [SVGZ](/viewer/python-net/groupdocs.viewer/filetype/svgz/) | Scalable Vector Graphics-bestand (.svgz) is een Scalar Vector Graphics‑bestand dat een op XML gebaseerd tekstformaat gebruikt, gecomprimeerd met GZIP, om het uiterlijk van een afbeelding te beschrijven. Meer informatie over dit bestandsformaat vindt u hier. |
| [OTG](/viewer/python-net/groupdocs.viewer/filetype/otg/) | OpenDocument grafisch sjabloon (.otg) |
| [HTM](/viewer/python-net/groupdocs.viewer/filetype/htm/) | Hypertext Markup Language-bestand (.htm) is de extensie voor webpagina's die zijn gemaakt voor weergave in browsers. Meer informatie over dit bestandsformaat vindt u hier. |
| [HTML](/viewer/python-net/groupdocs.viewer/filetype/html/) | Hypertext Markup Language-bestand (.html) is de extensie voor webpagina's die zijn gemaakt voor weergave in browsers. Meer informatie over dit bestandsformaat vindt u hier. |
| [MHT](/viewer/python-net/groupdocs.viewer/filetype/mht/) | MHTML-webarchief (.mht) |
| [MHTML](/viewer/python-net/groupdocs.viewer/filetype/mhtml/) | MIME HTML-bestand (.mhtml) |
| [XML](/viewer/python-net/groupdocs.viewer/filetype/xml/) | XML-bestand (.xml). GroupDocs.Viewer heeft een speciale processor voor het verwerken van XML‑bestanden, zie de documentatie. |
| [ONE](/viewer/python-net/groupdocs.viewer/filetype/one/) | OneNote-document (.one) wordt gemaakt door de Microsoft OneNote-toepassing. OneNote stelt u in staat informatie te verzamelen met de toepassing alsof u uw kladblok gebruikt om aantekeningen te maken. Meer informatie over dit bestandsformaat vindt u hier. |
| [PDF](/viewer/python-net/groupdocs.viewer/filetype/pdf/) | Portable Document Format-bestand (.pdf) is een type document dat in de jaren 1990 door Adobe is gemaakt. Het doel van dit bestandsformaat was een standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van toepassingssoftware, hardware en besturingssysteem. Meer informatie over dit bestandsformaat vindt u hier. |
| [XPS](/viewer/python-net/groupdocs.viewer/filetype/xps/) | XML Paper Specification-bestand (.xps) vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications gemaakt door Microsoft. Dit formaat is ontwikkeld door Microsoft als vervanging van het EMF‑bestandsformaat en is vergelijkbaar met het PDF‑formaat, maar gebruikt XML voor lay-out, uiterlijk en afdrukinformatie van een document. Meer informatie over dit bestandsformaat vindt u hier. |
| [OXPS](/viewer/python-net/groupdocs.viewer/filetype/oxps/) | OpenXPS-bestand (.oxps) |
| [TEX](/viewer/python-net/groupdocs.viewer/filetype/tex/) | LaTeX-brondocument (.tex) is een taal die bestaat uit programmeer- en opmaakfuncties, gebruikt om documenten op te maken. Meer informatie over dit bestandsformaat vindt u hier. |
| [OFD](/viewer/python-net/groupdocs.viewer/filetype/ofd/) | Open Fixed‑layout Document (OFD)-formaat, gedefinieerd door GB/T 33190-2016, heeft als doel PDF te vervangen in Chinese openbare instellingen. |
| [PPT](/viewer/python-net/groupdocs.viewer/filetype/ppt/) | PowerPoint-presentatie (.ppt) vertegenwoordigt een PowerPoint‑bestand dat bestaat uit een verzameling dia's voor weergave als diavoorstelling. Het specificeert het binaire bestandsformaat dat wordt gebruikt door Microsoft PowerPoint 97-2003. Meer informatie over dit bestandsformaat vindt u hier. |
| [PPTX](/viewer/python-net/groupdocs.viewer/filetype/pptx/) | PowerPoint Open XML-presentatie (.pptx) zijn presentatiebestanden die zijn gemaakt met de populaire Microsoft PowerPoint-toepassing. In tegenstelling tot de vorige versie van het presentatiebestandsformaat PPT, dat binair was, is het PPTX‑formaat gebaseerd op het Microsoft PowerPoint Open XML-presentatiebestandsformaat. Meer informatie over dit bestandsformaat vindt u hier. |
| [PPS](/viewer/python-net/groupdocs.viewer/filetype/pps/) | PowerPoint-diavoorstelling (.pps) wordt gemaakt met Microsoft PowerPoint voor diavoorstellingsdoeleinden. Het lezen en maken van PPS‑bestanden wordt ondersteund door Microsoft PowerPoint 97-2003. Meer informatie over dit bestandsformaat vindt u hier. |
| [PPSX](/viewer/python-net/groupdocs.viewer/filetype/ppsx/) | PowerPoint Open XML-diavoorstelling (.ppsx) bestanden worden gemaakt met Microsoft PowerPoint 2007 en hoger voor diavoorstellingsdoeleinden. Meer informatie over dit bestandsformaat vindt u hier. |
| [ODP](/viewer/python-net/groupdocs.viewer/filetype/odp/) | OpenDocument-presentatie (.odp) vertegenwoordigt het presentatiebestandsformaat dat wordt gebruikt door OpenOffice.org in de OASISOpen-standaard. Meer informatie over dit bestandsformaat vindt u hier. |
| [FODP](/viewer/python-net/groupdocs.viewer/filetype/fodp/) | OpenDocument-presentatie (.fodp) vertegenwoordigt OpenDocument Flat XML-presentatie. Meer informatie over dit bestandsformaat vindt u hier. |
| [POT](/viewer/python-net/groupdocs.viewer/filetype/pot/) | PowerPoint-sjabloon (.pot) vertegenwoordigt Microsoft PowerPoint-sjabloonbestanden die zijn gemaakt met PowerPoint‑versies 97‑2003. Meer informatie over dit bestandsformaat vindt u hier. |
| [PPTM](/viewer/python-net/groupdocs.viewer/filetype/pptm/) | PowerPoint Open XML Macro‑Enabled Presentatie zijn macro‑ingeschakelde presentaties die zijn gemaakt met Microsoft PowerPoint 2007 of hogere versies. Meer informatie over dit bestandsformaat vindt u hier. |
| [POTX](/viewer/python-net/groupdocs.viewer/filetype/potx/) | PowerPoint Open XML Presentatie‑sjabloon (.potx) vertegenwoordigt Microsoft PowerPoint‑sjabloonpresentaties die zijn gemaakt met Microsoft PowerPoint 2007 en hoger. Meer informatie over dit bestandsformaat vindt u hier. |
| [POTM](/viewer/python-net/groupdocs.viewer/filetype/potm/) | PowerPoint Open XML Macro‑Enabled Presentatie‑sjabloon (.potm) zijn Microsoft PowerPoint‑sjabloonbestanden met ondersteuning voor macro's. POTM‑bestanden worden gemaakt met PowerPoint 2007 of hoger en bevatten standaardinstellingen die kunnen worden gebruikt om verdere presentaties te maken. Meer informatie over dit bestandsformaat vindt u hier. |
| [PPSM](/viewer/python-net/groupdocs.viewer/filetype/ppsm/) | PowerPoint Open XML Macro‑Enabled Dia (.ppsm) vertegenwoordigt een macro‑ingeschakelde diavoorstelling die is gemaakt met Microsoft PowerPoint 2007 of hoger. Meer informatie over dit bestandsformaat vindt u hier. |
| [OTP](/viewer/python-net/groupdocs.viewer/filetype/otp/) | OpenDocument Presentatie‑sjabloon (.otp) vertegenwoordigt presentatiesjabloonbestanden die zijn gemaakt door toepassingen volgens de OASIS OpenDocument‑standaard. Meer informatie over dit bestandsformaat vindt u hier. |
| [XLS](/viewer/python-net/groupdocs.viewer/filetype/xls/) | Excel-werkblad (.xls) vertegenwoordigt het Excel Binary File Format. Dergelijke bestanden kunnen worden gemaakt met Microsoft Excel evenals andere vergelijkbare spreadsheet‑programma's zoals OpenOffice Calc of Apple Numbers. Meer informatie over dit bestandsformaat vindt u hier. |
| [EXCEL_2003XML](/viewer/python-net/groupdocs.viewer/filetype/excel_2003xml/) | Excel 2003 XML (SpreadsheetML) vertegenwoordigt het Excel Binary File Format. Dergelijke bestanden kunnen worden gemaakt met Microsoft Excel evenals andere vergelijkbare spreadsheet‑programma's zoals OpenOffice Calc of Apple Numbers. Meer informatie over dit bestandsformaat vindt u hier. |
| [NUMBERS](/viewer/python-net/groupdocs.viewer/filetype/numbers/) | Apple Numbers vertegenwoordigt een Excel‑achtig binair bestandsformaat. Dergelijke bestanden kunnen worden gemaakt met de Apple Numbers‑applicatie. Meer informatie over dit bestandsformaat vindt u hier. |
| [XLSX](/viewer/python-net/groupdocs.viewer/filetype/xlsx/) | Microsoft Excel Open XML Spreadsheet (.xlsx) is een bekend formaat voor Microsoft Excel‑documenten dat door Microsoft werd geïntroduceerd met de release van Microsoft Office 2007. Meer informatie over dit bestandsformaat vindt u hier. |
| [XLSM](/viewer/python-net/groupdocs.viewer/filetype/xlsm/) | Excel Open XML Macro‑Enabled Spreadsheet (.xlsm) is een type spreadsheet‑bestanden dat macro's ondersteunt. Meer informatie over dit bestandsformaat vindt u hier. |
| [XLSB](/viewer/python-net/groupdocs.viewer/filetype/xlsb/) | Excel Binary Spreadsheet (.xlsb) specificeert het Excel Binary File Format, een verzameling records en structuren die de inhoud van een Excel‑werkmap definiëren. Meer informatie over dit bestandsformaat vindt u hier. |
| [CSV](/viewer/python-net/groupdocs.viewer/filetype/csv/) | Comma Separated Values‑bestand (.csv) vertegenwoordigt platte tekstbestanden die gegevensrecords met door komma's gescheiden waarden bevatten. Meer informatie over dit bestandsformaat vindt u hier. |
| [TSV](/viewer/python-net/groupdocs.viewer/filetype/tsv/) | Tab Separated Values‑bestand (.tsv) vertegenwoordigt gegevens die met tabs zijn gescheiden in een platte-tekstformaat. Meer informatie over dit bestandsformaat vindt u hier. |
| [ODS](/viewer/python-net/groupdocs.viewer/filetype/ods/) | OpenDocument Spreadsheet (.ods) staat voor het OpenDocument Spreadsheet‑documentformaat dat door de gebruiker bewerkbaar is. Gegevens worden in het ODF‑bestand opgeslagen in rijen en kolommen. Meer informatie over dit bestandsformaat vindt u hier. |
| [FODS](/viewer/python-net/groupdocs.viewer/filetype/fods/) | OpenDocument Flat XML Spreadsheet (.fods) |
| [OTS](/viewer/python-net/groupdocs.viewer/filetype/ots/) | OpenDocument Spreadsheet Template (.ots) |
| [XLAM](/viewer/python-net/groupdocs.viewer/filetype/xlam/) | Microsoft Excel Add-in (.xlam) |
| [XLTM](/viewer/python-net/groupdocs.viewer/filetype/xltm/) | Microsoft Excel Macro‑Enabled Sjabloon (.xltm) vertegenwoordigt bestanden die door Microsoft Excel worden gegenereerd als macro‑ingeschakelde sjabloonbestanden. XLTM‑bestanden lijken op XLTX in structuur, behalve dat laatstgenoemde geen sjabloonbestanden met macro's kan maken. Meer informatie over dit bestandsformaat vindt u hier. |
| [XLT](/viewer/python-net/groupdocs.viewer/filetype/xlt/) | Microsoft Excel Sjabloon (.xlt) zijn sjabloonbestanden die zijn gemaakt met Microsoft Excel, een spreadsheet‑applicatie die deel uitmaakt van de Microsoft Office‑suite. Microsoft Office 97‑2003 ondersteunde het maken van nieuwe XLT‑bestanden en het openen ervan. Meer informatie over dit bestandsformaat vindt u hier. |
| [XLTX](/viewer/python-net/groupdocs.viewer/filetype/xltx/) | Excel Open XML Spreadsheet‑sjabloon (.xltx) vertegenwoordigt Microsoft Excel‑sjabloon dat is gebaseerd op de Office OpenXML‑bestandsformaatspecificaties. Het wordt gebruikt om een standaard‑sjabloonbestand te maken dat kan worden gebruikt om XLSX‑bestanden te genereren met dezelfde instellingen als gespecificeerd in het XLTX‑bestand. Meer informatie over dit bestandsformaat vindt u hier. |
| [SXC](/viewer/python-net/groupdocs.viewer/filetype/sxc/) | StarOffice Calc Spreadsheet (.sxc) |
| [MPP](/viewer/python-net/groupdocs.viewer/filetype/mpp/) | Microsoft Project-bestand (.mpp) is een Microsoft Project-gegevensbestand dat informatie met betrekking tot projectbeheer op een geïntegreerde manier opslaat. Leer meer over dit bestandsformaat hier. |
| [MPT](/viewer/python-net/groupdocs.viewer/filetype/mpt/) | Microsoft Project-sjabloon (.mpt) bevat basisinformatie en -structuur samen met documentinstellingen voor het maken van .MPP-bestanden. Leer meer over dit bestandsformaat hier. |
| [MPX](/viewer/python-net/groupdocs.viewer/filetype/mpx/) | Microsoft Project Exchange-bestand (.mpx) is een ASCII-bestandsformaat voor het overbrengen van projectinformatie tussen Microsoft Project (MSP) en andere toepassingen die het MPX-bestandsformaat ondersteunen, zoals Primavera Project Planner, Sciforma en Timerline Precision Estimating. Leer meer over dit bestandsformaat hier. |
| [AS_](/viewer/python-net/groupdocs.viewer/filetype/as_/) | ActionScript-bestand (.as) |
| [AS3](/viewer/python-net/groupdocs.viewer/filetype/as3/) | ActionScript-bestand (.as) |
| [ASM](/viewer/python-net/groupdocs.viewer/filetype/asm/) | Assembly Language-broncodebestand (.asm) |
| [BAT](/viewer/python-net/groupdocs.viewer/filetype/bat/) | DOS-batchbestand (.bat) |
| [C](/viewer/python-net/groupdocs.viewer/filetype/c/) | C/C++-broncodebestand (.c) |
| [CC](/viewer/python-net/groupdocs.viewer/filetype/cc/) | C++-broncodebestand (.cc) |
| [CMAKE](/viewer/python-net/groupdocs.viewer/filetype/cmake/) | CMake-bestand (.cmake) |
| [CPP](/viewer/python-net/groupdocs.viewer/filetype/cpp/) | C++-broncodebestand (.cpp) |
| [CS](/viewer/python-net/groupdocs.viewer/filetype/cs/) | C#-broncodebestand (.cs) is een broncodebestand voor de programmeertaal C#. Geïntroduceerd door Microsoft voor gebruik met het .NET Framework. Leer meer over dit bestandsformaat hier. |
| [VB](/viewer/python-net/groupdocs.viewer/filetype/vb/) | Visual Basic Project Item-bestand (.vb) is een broncodebestand gemaakt in de Visual Basic-taal dat door Microsoft is gecreëerd voor de ontwikkeling van .NET-toepassingen. Leer meer over dit bestandsformaat hier. |
| [CSS](/viewer/python-net/groupdocs.viewer/filetype/css/) | Cascading Style Sheet (.css) |
| [CXX](/viewer/python-net/groupdocs.viewer/filetype/cxx/) | C++-broncodebestand (.cxx) |
| [DIFF](/viewer/python-net/groupdocs.viewer/filetype/diff/) | Patchbestand (.diff) |
| [ERB](/viewer/python-net/groupdocs.viewer/filetype/erb/) | Ruby ERB-script (.erb) |
| [GROOVY](/viewer/python-net/groupdocs.viewer/filetype/groovy/) | Groovy-broncodebestand (.groovy) |
| [H](/viewer/python-net/groupdocs.viewer/filetype/h/) | C/C++/Objective-C-headerbestand (.h) |
| [HAML](/viewer/python-net/groupdocs.viewer/filetype/haml/) | Haml-broncodebestand (.haml) |
| [HH](/viewer/python-net/groupdocs.viewer/filetype/hh/) | C++-headerbestand (.hh) |
| [JAVA](/viewer/python-net/groupdocs.viewer/filetype/java/) | Java-broncodebestand (.java) |
| [JS](/viewer/python-net/groupdocs.viewer/filetype/js/) | JavaScript-bestand (.js) |
| [JSON](/viewer/python-net/groupdocs.viewer/filetype/json/) | JavaScript Object Notation-bestand (.json) |
| [LESS](/viewer/python-net/groupdocs.viewer/filetype/less/) | LESS-stylesheet (.less) |
| [LOG](/viewer/python-net/groupdocs.viewer/filetype/log/) | Logbestand (.log) |
| [M](/viewer/python-net/groupdocs.viewer/filetype/m/) | Objective-C-implementatiebestand (.m) |
| [MAKE](/viewer/python-net/groupdocs.viewer/filetype/make/) | Xcode Makefile-script (.make) |
| [MD](/viewer/python-net/groupdocs.viewer/filetype/md/) | Markdown-documentatiebestand (.md) |
| [ML](/viewer/python-net/groupdocs.viewer/filetype/ml/) | ML-broncodebestand (.ml) |
| [MM](/viewer/python-net/groupdocs.viewer/filetype/mm/) | Objective-C++-bronbestand (.mm) |
| [PHP](/viewer/python-net/groupdocs.viewer/filetype/php/) | PHP-broncodebestand (.php) |
| [PL](/viewer/python-net/groupdocs.viewer/filetype/pl/) | Perl-script (.pl) |
| [PROPERTIES](/viewer/python-net/groupdocs.viewer/filetype/properties/) | Java-eigenschappenbestand (.properties) |
| [PY](/viewer/python-net/groupdocs.viewer/filetype/py/) | Python-script (.py) |
| [RB](/viewer/python-net/groupdocs.viewer/filetype/rb/) | Ruby-broncodebestand (.rb) |
| [RST](/viewer/python-net/groupdocs.viewer/filetype/rst/) | reStructuredText-bestand (.rst) |
| [SASS](/viewer/python-net/groupdocs.viewer/filetype/sass/) | Syntactically Awesome StyleSheets-bestand (.sass) |
| [SCALA](/viewer/python-net/groupdocs.viewer/filetype/scala/) | Scala-broncodebestand (.scala) |
| [SCM](/viewer/python-net/groupdocs.viewer/filetype/scm/) | Scheme-broncodebestand (.scm) |
| [SCRIPT](/viewer/python-net/groupdocs.viewer/filetype/script/) | Generiek scriptbestand (.script) |
| [SH](/viewer/python-net/groupdocs.viewer/filetype/sh/) | Bash-shellscript (.sh) |
| [SML](/viewer/python-net/groupdocs.viewer/filetype/sml/) | Standard ML-broncodebestand (.sml) |
| [SQL](/viewer/python-net/groupdocs.viewer/filetype/sql/) | Structured Query Language-gegevensbestand (.sql) |
| [VIM](/viewer/python-net/groupdocs.viewer/filetype/vim/) | Vim-instellingsbestand (.vim) |
| [YAML](/viewer/python-net/groupdocs.viewer/filetype/yaml/) | YAML-document (.yaml) |
| [DOC](/viewer/python-net/groupdocs.viewer/filetype/doc/) | Microsoft Word-document (.doc) vertegenwoordigt documenten die zijn gegenereerd door Microsoft Word of andere tekstverwerkingsdocumenten in binair bestandsformaat. Leer meer over dit bestandsformaat hier. |
| [DOCX](/viewer/python-net/groupdocs.viewer/filetype/docx/) | Microsoft Word Open XML-document (.docx) is een bekend formaat voor Microsoft Word-documenten. Geïntroduceerd in 2007 met de release van Microsoft Office 2007, werd de structuur van dit nieuwe documentformaat gewijzigd van puur binair naar een combinatie van XML- en binaire bestanden. Leer meer over dit bestandsformaat hier. |
| [CHM](/viewer/python-net/groupdocs.viewer/filetype/chm/) | Microsoft Compiled HTML Help-bestand (.chm) is een bekend formaat voor HELP (documentatie voor een applicatie) documenten. Leer meer over dit bestandsformaat hier. |
| [DOCM](/viewer/python-net/groupdocs.viewer/filetype/docm/) | Word Open XML Macro-Enabled-document (.docm) is een door Microsoft Word 2007 of hoger gegenereerd document met de mogelijkheid om macro's uit te voeren. Leer meer over dit bestandsformaat hier. |
| [DOT](/viewer/python-net/groupdocs.viewer/filetype/dot/) | Word Document-sjabloon (.dot) zijn sjabloonbestanden die door Microsoft Word zijn gemaakt om vooraf geformatteerde instellingen te hebben voor het genereren van verdere DOC- of DOCX-bestanden. Leer meer over dit bestandsformaat hier. |
| [DOTX](/viewer/python-net/groupdocs.viewer/filetype/dotx/) | Word Open XML Document Template (.dotx) zijn sjabloonbestanden die door Microsoft Word zijn gemaakt om vooraf geformatteerde instellingen te hebben voor het genereren van verdere DOCX-bestanden. Meer informatie over dit bestandsformaat vindt u hier. |
| [DOTM](/viewer/python-net/groupdocs.viewer/filetype/dotm/) | Word Open XML Macro-Enabled Document Template (.dotm) vertegenwoordigt een sjabloonbestand dat is gemaakt met Microsoft Word 2007 of hoger. Meer informatie over dit bestandsformaat vindt u hier. |
| [RTF](/viewer/python-net/groupdocs.viewer/filetype/rtf/) | Rich Text Format File (.rtf) vertegenwoordigt een methode om opgemaakte tekst en afbeeldingen te coderen voor gebruik binnen toepassingen. Meer informatie over dit bestandsformaat vindt u hier. |
| [TXT](/viewer/python-net/groupdocs.viewer/filetype/txt/) | Plain Text File (.txt) vertegenwoordigt een tekstdocument dat platte tekst bevat in de vorm van regels. Meer informatie over dit bestandsformaat vindt u hier. |
| [ODT](/viewer/python-net/groupdocs.viewer/filetype/odt/) | OpenDocument Text Document (.odt) is een type documenten dat wordt gemaakt met tekstverwerkingsprogramma's die gebaseerd zijn op het OpenDocument Text-bestandformaat. Meer informatie over dit bestandsformaat vindt u hier. |
| [OTT](/viewer/python-net/groupdocs.viewer/filetype/ott/) | OpenDocument Document Template (.ott) vertegenwoordigt sjabloondocumenten die door toepassingen worden gegenereerd in overeenstemming met de OASIS OpenDocument-standaard. Meer informatie over dit bestandsformaat vindt u hier. |
| [VCF](/viewer/python-net/groupdocs.viewer/filetype/vcf/) | vCard File (.vcf) is een digitaal bestandsformaat voor het opslaan van contactinformatie. Het formaat wordt veel gebruikt voor gegevensuitwisseling tussen populaire informatie-uitwisselingsapplicaties. Meer informatie over dit bestandsformaat vindt u hier. |
| [AI](/viewer/python-net/groupdocs.viewer/filetype/ai/) | Adobe Illustrator (.ai) is een bestandsformaat voor Adobe Illustrator-tekeningen. Meer informatie over dit bestandsformaat vindt u hier. |
| [PSM1](/viewer/python-net/groupdocs.viewer/filetype/psm1/) | PowerShell script module (.psm1) is een bestandsformaat voor PowerShell-modulescripts. Meer informatie over dit bestandsformaat vindt u hier. |
| [PS1](/viewer/python-net/groupdocs.viewer/filetype/ps1/) | PowerShell script file (.ps1) is een bestandsformaat voor Windows PowerShell-Cmdlet-bestanden. Meer informatie over dit bestandsformaat vindt u hier. |
| [PSD1](/viewer/python-net/groupdocs.viewer/filetype/psd1/) | PowerShell script module manifest (.psd1) is een bestandsformaat voor PowerShell-module-manifest-scripts. Meer informatie over dit bestandsformaat vindt u hier. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

# Geef het bestandstype op (bijv. Markdown) bij het laden van het document
load_options = LoadOptions(FileType.MD)

# Render het document naar PDF
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### Zie ook
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
