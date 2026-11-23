---
title: "Classe FileType"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rappresenta un tipo di file e fornisce metodi per ottenere l'elenco di tutti i tipi di file supportati da GroupDocs.Viewer."
type: docs
url: /it/python-net/groupdocs.viewer/filetype/
is_root: false
weight: 10
---


## FileType class

Rappresenta un tipo di file e fornisce metodi per ottenere l'elenco di tutti i tipi di file supportati da GroupDocs.Viewer.

Il tipo FileType espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/) | Inizializza una nuova istanza di [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/). |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/#file_format-extension) | Inizializza una nuova istanza di FileType. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#file_path) | Rileva la codifica dei file di testo TXT, TSV e CSV tramite percorso. |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#stream) | Tenta di rilevare la codifica dei file di testo (TXT, TSV, CSV) da uno stream. |
| [detect_encoding_file](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_file/) |  |
| [detect_encoding_stream](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_stream/) |  |
| [detect_encoding_streams](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_streams/) |  |
| [detect_encoding_string](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_string/) |  |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#other) | Determina se l'attuale [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) è lo stesso del [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) specificato. |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#obj) | Determina se l'attuale [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) è lo stesso dell'oggetto specificato. |
| [equals_file_type](/viewer/python-net/groupdocs.viewer/filetype/equals_file_type/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer/filetype/equals_object/) |  |
| [from_extension](/viewer/python-net/groupdocs.viewer/filetype/from_extension/#extension) | Mappa l'estensione del file al tipo di file. |
| [from_file_path](/viewer/python-net/groupdocs.viewer/filetype/from_file_path/#file_path) | Estrae l'estensione del file e la mappa a un tipo di file. |
| [from_media_type](/viewer/python-net/groupdocs.viewer/filetype/from_media_type/#media_type) | Mappa un tipo di media del file a un [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) (ad esempio, 'application/pdf' viene mappato a [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)). |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream) | Rileva il tipo di file leggendo la firma del file. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password) | Rileva il tipo di file leggendo la firma del file. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-logger) | Rileva il tipo di file leggendo la firma del file. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password-logger) | Rileva il tipo di file leggendo la firma del file. |
| [from_stream_file](/viewer/python-net/groupdocs.viewer/filetype/from_stream_file/) |  |
| [from_stream_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream_stream/) |  |
| [from_stream_streams](/viewer/python-net/groupdocs.viewer/filetype/from_stream_streams/) |  |
| [from_stream_string](/viewer/python-net/groupdocs.viewer/filetype/from_stream_string/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer/filetype/get_hash_code/) | Restituisce il codice hash per l'oggetto [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) corrente. |
| [get_supported_file_types](/viewer/python-net/groupdocs.viewer/filetype/get_supported_file_types/) | Recupera i tipi di file supportati. |
| [to_string](/viewer/python-net/groupdocs.viewer/filetype/to_string/) | Restituisce una stringa che rappresenta l'oggetto corrente. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [extension](/viewer/python-net/groupdocs.viewer/filetype/extension/) | Il suffisso del nome file (incluso il punto ".") es. ".doc". |
| [file_format](/viewer/python-net/groupdocs.viewer/filetype/file_format/) | Il nome del tipo di file es. "Microsoft Word Document". |

### Campi
| Campo | Descrizione |
| :- | :- |
| [UNKNOWN](/viewer/python-net/groupdocs.viewer/filetype/unknown/) | Rappresenta un tipo di file sconosciuto. |
| [ZIP](/viewer/python-net/groupdocs.viewer/filetype/zip/) | Il file Zippato (.zip) rappresenta archivi che possono contenere uno o più file o directory. Scopri di più su questo formato di file qui. |
| [TAR](/viewer/python-net/groupdocs.viewer/filetype/tar/) | L'archivio Unix consolidato (.tar) è un archivio creato con utility basate su Unix per raccogliere uno o più file. Scopri di più su questo formato di file qui. |
| [XZ](/viewer/python-net/groupdocs.viewer/filetype/xz/) | Il file XZ (.xz) è un archivio compresso con un algoritmo di compressione ad alto rapporto basato sull'algoritmo LZMA. Scopri di più su questo formato di file qui. |
| [TXZ](/viewer/python-net/groupdocs.viewer/filetype/txz/) | L'archivio Unix consolidato (.txz, .tar.xz) è un archivio creato con utility basate su Unix per raccogliere uno o più file. Scopri di più su questo formato di file qui. |
| [TARXZ](/viewer/python-net/groupdocs.viewer/filetype/tarxz/) | L'archivio Unix consolidato (.txz, .tar.xz) è un archivio creato con utility basate su Unix per raccogliere uno o più file. Scopri di più su questo formato di file qui. |
| [TGZ](/viewer/python-net/groupdocs.viewer/filetype/tgz/) | L'archivio Unix consolidato (.tgz, .tar.gz) è un archivio creato con utility basate su Unix per raccogliere uno o più file. Scopri di più su questo formato di file qui. |
| [TARGZ](/viewer/python-net/groupdocs.viewer/filetype/targz/) | L'archivio Unix consolidato (.tgz, .tar.gz) è un archivio creato con utility basate su Unix per raccogliere uno o più file. Scopri di più su questo formato di file qui. |
| [BZ2](/viewer/python-net/groupdocs.viewer/filetype/bz2/) | Il file compresso Bzip2 (.bz2) è un file compresso generato usando il metodo di compressione open source BZIP2, principalmente su sistemi UNIX o Linux. Scopri di più su questo formato di file qui. |
| [RAR](/viewer/python-net/groupdocs.viewer/filetype/rar/) | Roshal ARchive (.rar) sono file compressi generati utilizzando il metodo di compressione RAR (WINRAR). Scopri di più su questo formato di file qui. |
| [GZ](/viewer/python-net/groupdocs.viewer/filetype/gz/) | Gnu Zipped File (.gz) sono file compressi creati con l'applicazione di compressione gzip. Può contenere più file compressi ed è comunemente usato su sistemi UNIX e Linux. Scopri di più su questo formato di file qui. |
| [GZIP](/viewer/python-net/groupdocs.viewer/filetype/gzip/) | Gnu Zipped File (.gzip) è stato introdotto come utility gratuito per sostituire il programma Compress usato nei sistemi Unix. Tali file possono essere aperti ed estratti con diverse applicazioni, come WinZip, disponibile sia per Windows che per macOS. Scopri di più su questo formato di file qui. |
| [SEVEN_ZIP](/viewer/python-net/groupdocs.viewer/filetype/seven_zip/) | 7Zip (.7z, .7zip) è un archiviatore open source gratuito con compressione LZMA e LZMA2. Scopri di più su questo formato di file qui. |
| [CPIO](/viewer/python-net/groupdocs.viewer/filetype/cpio/) | Cpio è un'utilità di archiviazione di file generica e il relativo formato di file. È principalmente installato sui sistemi operativi Unix-like. Scopri di più su questo formato di file qui. |
| [ZSTANDARD](/viewer/python-net/groupdocs.viewer/filetype/zstandard/) | Il file ZST è un file compresso generato con l'algoritmo di compressione Zstandard (zstd). È un file compresso creato con compressione senza perdita di dati dall'algoritmo. I file ZST possono essere usati per comprimere diversi tipi di file, come database, file system, reti e giochi. Scopri di più su questo formato di file qui. |
| [TZST](/viewer/python-net/groupdocs.viewer/filetype/tzst/) | I file TZST (.tar.zst, .tzst) sono archivi Zstandard (ZST), che contengono internamente un Consolidated Unix File Archive (Tar), creati con un'utilità basata su Unix per raccogliere uno o più file. |
| [TAR_ZST](/viewer/python-net/groupdocs.viewer/filetype/tar_zst/) | I file TZST (.tar.zst, .tzst) sono archivi Zstandard (ZST), che contengono internamente un Consolidated Unix File Archive (Tar), creati con un'utilità basata su Unix per raccogliere uno o più file. |
| [ISO](/viewer/python-net/groupdocs.viewer/filetype/iso/) | L'immagine ISO di disco ottico è un file immagine di disco archivio non compresso che rappresenta il contenuto di tutti i dati su un disco ottico come CD o DVD, basato sullo standard ISO-9660. Scopri di più su questo formato di file qui. |
| [LHA](/viewer/python-net/groupdocs.viewer/filetype/lha/) | LHA o LZH è un'utilità di compressione freeware e il relativo formato di file. Scopri di più su questo formato di file qui. |
| [CAB](/viewer/python-net/groupdocs.viewer/filetype/cab/) | Cabinet (o CAB) è un formato di file archivio per Microsoft Windows. Scopri di più su questo formato di file qui. |
| [DXF](/viewer/python-net/groupdocs.viewer/filetype/dxf/) | Il file Drawing Exchange Format (.dxf) è una rappresentazione di dati etichettati di un file di disegno AutoCAD. Scopri di più su questo formato di file qui. |
| [DWG](/viewer/python-net/groupdocs.viewer/filetype/dwg/) | Il file AutoCAD Drawing Database (.dwg) rappresenta file binari proprietari usati per contenere dati di progettazione 2D e 3D. Come DXF, che sono file ASCII, DWG rappresenta il formato di file binario per i disegni CAD (Computer Aided Design). Scopri di più su questo formato di file qui. |
| [DWT](/viewer/python-net/groupdocs.viewer/filetype/dwt/) | Il modello di disegno AutoCAD (.dwt) è un file modello di disegno AutoCAD usato come punto di partenza per creare disegni che possono essere salvati come file DWG. Scopri di più su questo formato di file qui. |
| [STL](/viewer/python-net/groupdocs.viewer/filetype/stl/) | Il file Stereolithography (.stl) è un formato di file intercambiabile che rappresenta la geometria di superficie tridimensionale. Questo formato di file è utilizzato in diversi settori, come la prototipazione rapida, la stampa 3D e la produzione assistita da computer. Scopri di più su questo formato di file qui. |
| [IFC](/viewer/python-net/groupdocs.viewer/filetype/ifc/) | Il file Industry Foundation Classes (.ifc) è un formato di file che stabilisce standard internazionali per importare ed esportare oggetti edilizi e le loro proprietà. Questo formato di file fornisce interoperabilità tra diverse applicazioni software. Scopri di più su questo formato di file qui. |
| [DWF](/viewer/python-net/groupdocs.viewer/filetype/dwf/) | Il file Design Web Format (.dwf) rappresenta disegni 2D/3D in formato compresso per visualizzare, revisionare o stampare i file di progetto. Contiene grafica e testo come parte dei dati di progetto e riduce le dimensioni del file grazie al suo formato compresso. Scopri di più su questo formato di file qui. |
| [FBX](/viewer/python-net/groupdocs.viewer/filetype/fbx/) | Il file Autodesk FBX Interchange (FilmBoX) (.fbx) rappresenta un formato di modello 3D. Scopri di più su questo formato di file qui. |
| [DWFX](/viewer/python-net/groupdocs.viewer/filetype/dwfx/) | Il file Design Web Format XPS (.dwfx) rappresenta disegni 2D/3D come documento XPS in formato compresso per visualizzare, revisionare o stampare i file di progetto. Contiene grafica e testo come parte dei dati di progetto e riduce le dimensioni del file grazie al suo formato compresso. Scopri di più su questo formato di file qui. |
| [DGN](/viewer/python-net/groupdocs.viewer/filetype/dgn/) | Il file MicroStation Design (.dgn) sono disegni creati e supportati da applicazioni CAD come MicroStation e Intergraph Interactive Graphics Design System. Scopri di più su questo formato di file qui. |
| [PLT](/viewer/python-net/groupdocs.viewer/filetype/plt/) | PLT (HPGL) (.plt) è un file plotter basato su vettori introdotto da Autodesk, Inc. e contiene informazioni per un determinato file CAD. I dettagli della stampa richiedono accuratezza e precisione nella produzione, e l'uso del file PLT garantisce ciò poiché tutte le immagini vengono stampate usando linee invece di punti. Scopri di più su questo formato di file qui. |
| [CF2](/viewer/python-net/groupdocs.viewer/filetype/cf2/) | Formato di file comune Scopri di più su questo formato di file qui. |
| [OBJ](/viewer/python-net/groupdocs.viewer/filetype/obj/) | Wavefront 3D Object File (.obj) è un file immagine 3D introdotto da Wavefront Technologies. Scopri di più su questo formato di file qui. |
| [HPG](/viewer/python-net/groupdocs.viewer/filetype/hpg/) | PLT (HPGL) (.hpg) |
| [IGS](/viewer/python-net/groupdocs.viewer/filetype/igs/) | Initial Graphics Exchange Specification (IGES) (.igs) |
| [VSD](/viewer/python-net/groupdocs.viewer/filetype/vsd/) | Visio Drawing File (.vsd) sono disegni creati con l'applicazione Microsoft Visio per rappresentare una varietà di oggetti grafici e le loro interconnessioni. Scopri di più su questo formato di file qui. |
| [VSDX](/viewer/python-net/groupdocs.viewer/filetype/vsdx/) | Visio Drawing (.vsdx) rappresenta il formato di file Microsoft Visio introdotto a partire da Microsoft Office 2013. È stato sviluppato per sostituire il formato di file binario, .VSD, supportato dalle versioni precedenti di Microsoft Visio. Scopri di più su questo formato di file qui. |
| [VSS](/viewer/python-net/groupdocs.viewer/filetype/vss/) | Visio Stencil File(.vss) sono file stencil creati con Microsoft Visio 2007 e versioni precedenti. I file stencil forniscono oggetti di disegno che possono essere inclusi in un disegno Visio .VSD. Scopri di più su questo formato di file qui. |
| [VSSX](/viewer/python-net/groupdocs.viewer/filetype/vssx/) | Visio Stencil File (.vssx) sono stencil di disegno creati con Microsoft Visio 2013 e versioni successive. Il formato di file VSSX può essere aperto con Visio 2013 e versioni successive. I file Visio sono noti per la rappresentazione di una varietà di elementi di disegno come collezioni di forme, connettori, diagrammi di flusso, layout di rete, diagrammi UML. Scopri di più su questo formato di file qui. |
| [VSDM](/viewer/python-net/groupdocs.viewer/filetype/vsdm/) | Visio Macro-Enabled Drawing (.vsdm) sono file di disegno creati con l'applicazione Microsoft Visio che supporta macro. I file VSDM sono disegni OPC/XML simili a VSDX, ma offrono anche la possibilità di eseguire macro quando il file viene aperto. Scopri di più su questo formato di file qui. |
| [VST](/viewer/python-net/groupdocs.viewer/filetype/vst/) | Visio Drawing Template (.vst) sono file immagine vettoriali creati con Microsoft Visio e fungono da modello per creare altri file. Questi file modello sono in formato binario e contengono il layout predefinito e le impostazioni utilizzate per la creazione di nuovi disegni Visio. Scopri di più su questo formato di file qui. |
| [VSTX](/viewer/python-net/groupdocs.viewer/filetype/vstx/) | Visio Drawing Template (.vstx) sono file modello di disegno creati con Microsoft Visio 2013 e versioni successive. Questi file VSTX forniscono un punto di partenza per creare disegni Visio, salvati come file .VSDX, con layout e impostazioni predefinite. Scopri di più su questo formato di file qui. |
| [VSTM](/viewer/python-net/groupdocs.viewer/filetype/vstm/) | Visio Macro-Enabled Drawing Template (.vstm) sono file modello creati con Microsoft Visio che supportano macro. A differenza dei file VSDX, i file creati da modelli VSTM possono eseguire macro sviluppate in codice Visual Basic for Applications (VBA). Scopri di più su questo formato di file qui. |
| [VSSM](/viewer/python-net/groupdocs.viewer/filetype/vssm/) | Visio Macro-Enabled Stencil File (.vssm) sono file stencil di Microsoft Visio che supportano macro. Un file VSSM, quando aperto, consente di eseguire le macro per ottenere la formattazione e il posizionamento desiderati delle forme in un diagramma. Scopri di più su questo formato di file qui. |
| [VSX](/viewer/python-net/groupdocs.viewer/filetype/vsx/) | Visio Stencil XML File (.vsx) si riferisce a stencil composti da disegni e forme utilizzati per creare diagrammi in Microsoft Visio. I file VSX sono salvati in formato XML e sono stati supportati fino a Visio 2013. Scopri di più su questo formato di file qui. |
| [VTX](/viewer/python-net/groupdocs.viewer/filetype/vtx/) | Visio Template XML File (.vtx) è un modello di disegno Microsoft Visio salvato su disco in formato XML. Il modello è pensato per fornire un file con impostazioni di base che può essere usato per creare più file Visio con le stesse impostazioni. Scopri di più su questo formato di file qui. |
| [VDW](/viewer/python-net/groupdocs.viewer/filetype/vdw/) | Visio Web Drawing (.vdw) rappresenta il formato di file che specifica i flussi e le memorie necessarie per il rendering di un disegno Web. Scopri di più su questo formato di file qui. |
| [VDX](/viewer/python-net/groupdocs.viewer/filetype/vdx/) | Visio Drawing XML File (.vdx) rappresenta qualsiasi disegno o grafico creato in Microsoft Visio, ma salvato in formato XML con estensione .VDX. Un file Visio Drawing XML è creato nel software Visio, sviluppato da Microsoft. Scopri di più su questo formato di file qui. |
| [EPUB](/viewer/python-net/groupdocs.viewer/filetype/epub/) | Il file Open eBook (.epub) è un formato di file e-book che fornisce un formato di pubblicazione digitale standard per editori e consumatori. Il formato è ormai così comune che è supportato da molti e-reader e applicazioni software. Scopri di più su questo formato di file qui. |
| [MOBI](/viewer/python-net/groupdocs.viewer/filetype/mobi/) | Il Mobipocket eBook (.mobi) è uno dei formati di file e-book più ampiamente utilizzati. Il formato è un miglioramento del vecchio formato OEB (Open Ebook Format) ed è stato usato come formato proprietario per Mobipocket Reader. Scopri di più su questo formato di file qui. |
| [AZW3](/viewer/python-net/groupdocs.viewer/filetype/azw3/) | L'ebook Amazon Kindle Format 8 (KF8) è il formato di file digitale sviluppato per i dispositivi Amazon Kindle. Il formato è un miglioramento dei file AZW più vecchi ed è usato sui dispositivi Kindle Fire solo con compatibilità retroattiva per i formati di file precedenti, cioè MOBI e AZW. Scopri di più su questo formato di file qui. |
| [MSG](/viewer/python-net/groupdocs.viewer/filetype/msg/) | Il messaggio di posta Outlook (.msg) è un formato di file utilizzato da Microsoft Outlook e Exchange per archiviare messaggi email, contatti, appuntamenti o altre attività. Scopri di più su questo formato di file qui. |
| [EML](/viewer/python-net/groupdocs.viewer/filetype/eml/) | Il messaggio di posta elettronica (.eml) rappresenta i messaggi email salvati con Outlook e altre applicazioni pertinenti. Quasi tutti i client di posta supportano questo formato di file per la sua conformità allo standard RFC-822 Internet Message Format. Scopri di più su questo formato di file qui. |
| [NSF](/viewer/python-net/groupdocs.viewer/filetype/nsf/) | Database Lotus Notes (.nsf) Scopri di più su questo formato di file qui. |
| [MBOX](/viewer/python-net/groupdocs.viewer/filetype/mbox/) | File casella di posta elettronica (.mbox) Scopri di più su questo formato di file qui. |
| [EMLX](/viewer/python-net/groupdocs.viewer/filetype/emlx/) | Il messaggio di posta Apple Mail (.emlx) è implementato e sviluppato da Apple. L'applicazione Apple Mail utilizza il formato di file EMLX per esportare le email. Scopri di più su questo formato di file qui. |
| [PST](/viewer/python-net/groupdocs.viewer/filetype/pst/) | Il file Outlook Personal Information Store (.pst) rappresenta i file di archiviazione personale di Outlook (chiamati anche Personal Storage Table) che memorizzano una varietà di informazioni dell'utente. Scopri di più su questo formato di file qui. |
| [OST](/viewer/python-net/groupdocs.viewer/filetype/ost/) | Il file Outlook Offline Data (.ost) rappresenta i dati della casella di posta dell'utente in modalità offline sul computer locale dopo la registrazione al server Exchange tramite Microsoft Outlook. Scopri di più su questo formato di file qui. |
| [TIF](/viewer/python-net/groupdocs.viewer/filetype/tif/) | Il Tagged Image File (.tif) rappresenta immagini raster destinate all'uso su una varietà di dispositivi che rispettano lo standard di questo formato di file. È in grado di descrivere dati immagine bi-livello, in scala di grigi, a palette di colori e a colori completi in diversi spazi colore. Scopri di più su questo formato di file qui. |
| [TIFF](/viewer/python-net/groupdocs.viewer/filetype/tiff/) | Il Tagged Image File Format (.tiff) rappresenta immagini raster destinate all'uso su una varietà di dispositivi che rispettano lo standard di questo formato di file. È in grado di descrivere dati immagine bi-livello, in scala di grigi, a palette di colori e a colori completi in diversi spazi colore. Scopri di più su questo formato di file qui. |
| [JPG](/viewer/python-net/groupdocs.viewer/filetype/jpg/) | L'immagine JPEG (.jpg) è un tipo di formato immagine salvato mediante compressione con perdita. L'immagine risultante, a seguito della compressione, è un compromesso tra dimensione di archiviazione e qualità dell'immagine. Scopri di più su questo formato di file qui. |
| [JPEG](/viewer/python-net/groupdocs.viewer/filetype/jpeg/) | L'immagine JPEG (.jpeg) è un tipo di formato immagine salvato mediante compressione con perdita. L'immagine risultante, a seguito della compressione, è un compromesso tra dimensione di archiviazione e qualità dell'immagine. Scopri di più su questo formato di file qui. |
| [JFIF](/viewer/python-net/groupdocs.viewer/filetype/jfif/) | Il JPEG File Interchange Format (.jfif) è un'immagine sviluppata per lo scambio rapido tra piattaforme. Questo formato utilizza la compressione JPEG. Scopri di più su questo formato di file qui. |
| [PNG](/viewer/python-net/groupdocs.viewer/filetype/png/) | Il Portable Network Graphic (.png) è un tipo di formato di file immagine raster che utilizza compressione senza perdita. Questo formato è stato creato come sostituto del Graphics Interchange Format (GIF) e non ha limitazioni di copyright. Scopri di più su questo formato di file qui. |
| [GIF](/viewer/python-net/groupdocs.viewer/filetype/gif/) | Il file Graphical Interchange Format (.gif) è un tipo di immagine altamente compressa. Per ogni immagine GIF tipicamente consente fino a 8 bit per pixel e fino a 256 colori sono consentiti nell'immagine. Scopri di più su questo formato di file qui. |
| [APNG](/viewer/python-net/groupdocs.viewer/filetype/apng/) | Il Animated Portable Network Graphic (.apng) è un'estensione del formato PNG che supporta l'animazione. Scopri di più su questo formato di file qui. |
| [BMP](/viewer/python-net/groupdocs.viewer/filetype/bmp/) | Il file immagine bitmap (.bmp) è usato per memorizzare immagini digitali bitmap. Queste immagini sono indipendenti dall'adattatore grafico e sono anche chiamate formato file bitmap indipendente dal dispositivo (DIB). Scopri di più su questo formato file qui. |
| [TGA](/viewer/python-net/groupdocs.viewer/filetype/tga/) | Truevision TGA (Truevision Advanced Raster Adapter - TARGA) è usato per memorizzare immagini digitali bitmap sviluppate da TRUEVISION. Scopri di più su questo formato file qui. |
| [ICO](/viewer/python-net/groupdocs.viewer/filetype/ico/) | Il file icona (.ico) è un tipo di file immagine usato come icona per la rappresentazione di un'applicazione su Microsoft Windows. Scopri di più su questo formato file qui. |
| [JP2](/viewer/python-net/groupdocs.viewer/filetype/jp2/) | Il file immagine principale JPEG 2000 (.jp2) è un sistema di codifica delle immagini e uno standard di compressione d'immagine all'avanguardia. Scopri di più su questo formato file qui. |
| [JPF](/viewer/python-net/groupdocs.viewer/filetype/jpf/) | File immagine JPEG 2000 (.jpf) |
| [JPX](/viewer/python-net/groupdocs.viewer/filetype/jpx/) | File immagine JPEG 2000 (.jpx) |
| [JPM](/viewer/python-net/groupdocs.viewer/filetype/jpm/) | File immagine JPEG 2000 (.jpm) |
| [J2C](/viewer/python-net/groupdocs.viewer/filetype/j2c/) | Flusso di codice JPEG 2000 (.j2c) |
| [J2K](/viewer/python-net/groupdocs.viewer/filetype/j2k/) | Il flusso di codice JPEG 2000 (.j2k) è un'immagine compressa usando la compressione wavelet invece della compressione DCT. Scopri di più su questo formato file qui. |
| [JPC](/viewer/python-net/groupdocs.viewer/filetype/jpc/) | Flusso di codice JPEG 2000 (.jpc) |
| [JLS](/viewer/python-net/groupdocs.viewer/filetype/jls/) | JPEG-LS (JLS) (.jls) |
| [DIB](/viewer/python-net/groupdocs.viewer/filetype/dib/) | File bitmap indipendente dal dispositivo (.dib) |
| [WMF](/viewer/python-net/groupdocs.viewer/filetype/wmf/) | Windows Metafile (.wmf) rappresenta il Microsoft Windows Metafile (WMF) per la memorizzazione di dati di immagini in formato vettoriale e bitmap. Scopri di più su questo formato file qui. |
| [WMZ](/viewer/python-net/groupdocs.viewer/filetype/wmz/) | Compressed Windows Metafile (.wmz) rappresenta il Microsoft Windows Metafile (WMF) compresso in archivio GZIP - per la memorizzazione di dati di immagini in formato vettoriale e bitmap. Scopri di più su questo formato file qui. |
| [EMF](/viewer/python-net/groupdocs.viewer/filetype/emf/) | Enhanced Windows Metafile (.emf) rappresenta immagini grafiche indipendenti dal dispositivo. I metafile EMF comprendono record di lunghezza variabile in ordine cronologico che possono rendere l'immagine memorizzata dopo l'analisi su qualsiasi dispositivo di output. Scopri di più su questo formato file qui. |
| [EMZ](/viewer/python-net/groupdocs.viewer/filetype/emz/) | Enhanced Windows Metafile compresso (.emz) rappresenta immagini grafiche indipendenti dal dispositivo compresse con GZIP. I metafile EMF comprendono record di lunghezza variabile in ordine cronologico che possono rendere l'immagine memorizzata dopo l'analisi su qualsiasi dispositivo di output. Scopri di più su questo formato file qui. |
| [WEBP](/viewer/python-net/groupdocs.viewer/filetype/webp/) | WebP Image (.webp) è un moderno formato di file immagine raster per il web basato su compressione senza perdita e con perdita. Fornisce la stessa qualità dell'immagine riducendo notevolmente le dimensioni del file. Scopri di più su questo formato file qui. |
| [DNG](/viewer/python-net/groupdocs.viewer/filetype/dng/) | Digital Negative Specification (.dng) è un formato di immagine per fotocamere digitali usato per la memorizzazione di file raw. È stato sviluppato da Adobe a settembre 2004. È stato fondamentalmente sviluppato per la fotografia digitale. Scopri di più su questo formato file qui. |
| [CDR](/viewer/python-net/groupdocs.viewer/filetype/cdr/) | CorelDraw Vector Graphic Drawing (.cdr) è un file immagine di disegno vettoriale creato nativamente con CorelDRAW per la memorizzazione di immagini digitali codificate e compresse. Tale file di disegno contiene testo, linee, forme, immagini, colori ed effetti per la rappresentazione vettoriale del contenuto dell'immagine. Scopri di più su questo formato file qui. |
| [CMX](/viewer/python-net/groupdocs.viewer/filetype/cmx/) | Corel Exchange (.cmx) è un file immagine di disegno che può contenere grafica vettoriale così come grafica bitmap. Scopri di più su questo formato file qui. |
| [DJVU](/viewer/python-net/groupdocs.viewer/filetype/djvu/) | DjVu Image (.djvu) è un formato di file grafico destinato a documenti e libri scansionati, soprattutto quelli che contengono una combinazione di testo, disegni, immagini e fotografie. Scopri di più su questo formato file qui. |
| [CGM](/viewer/python-net/groupdocs.viewer/filetype/cgm/) | Computer Graphics Metafile (.cgm) è un formato metafile gratuito, indipendente dalla piattaforma, standard internazionale per la memorizzazione e lo scambio di grafica vettoriale (2D), grafica raster e testo. CGM utilizza un approccio orientato agli oggetti e molte funzioni per la produzione di immagini. Scopri di più su questo formato file qui. |
| [PCL](/viewer/python-net/groupdocs.viewer/filetype/pcl/) | Documento Printer Command Language (.pcl) |
| [PSD](/viewer/python-net/groupdocs.viewer/filetype/psd/) | Adobe Photoshop Document (.psd) rappresenta il formato file nativo di Adobe Photoshop usato per la progettazione e lo sviluppo grafico. Scopri di più su questo formato file qui. |
| [PSB](/viewer/python-net/groupdocs.viewer/filetype/psb/) | Photoshop Large Document Format (.psb) rappresenta il formato documento grande di Photoshop usato per la progettazione e lo sviluppo grafico. Scopri di più su questo formato file qui. |
| [DCM](/viewer/python-net/groupdocs.viewer/filetype/dcm/) | L'immagine DICOM (.dcm) rappresenta un'immagine digitale che memorizza informazioni mediche dei pazienti, come risonanze magnetiche, scansioni TC e immagini ecografiche. Scopri di più su questo formato di file qui. |
| [PS](/viewer/python-net/groupdocs.viewer/filetype/ps/) | File PostScript (.ps) |
| [EPS](/viewer/python-net/groupdocs.viewer/filetype/eps/) | Il file Encapsulated PostScript (.eps) descrive un programma di linguaggio Encapsulated PostScript che definisce l'aspetto di una singola pagina. Scopri di più su questo formato di file qui. |
| [ODG](/viewer/python-net/groupdocs.viewer/filetype/odg/) | Il file OpenDocument Graphic (.odg) è usato dall'applicazione Draw di Apache OpenOffice per memorizzare gli elementi di disegno come immagine vettoriale. Scopri di più su questo formato di file qui. |
| [FODG](/viewer/python-net/groupdocs.viewer/filetype/fodg/) | Il modello Flat XML ODF (.fodg) è usato dall'applicazione Draw di Apache OpenOffice per memorizzare gli elementi di disegno come immagine vettoriale. Scopri di più su questo formato di file qui. |
| [SVG](/viewer/python-net/groupdocs.viewer/filetype/svg/) | Il file Scalable Vector Graphics (.svg) è un file Scalar Vector Graphics che utilizza un formato di testo basato su XML per descrivere l'aspetto di un'immagine. Scopri di più su questo formato di file qui. |
| [SVGZ](/viewer/python-net/groupdocs.viewer/filetype/svgz/) | Il file Scalable Vector Graphics (.svgz) è un file Scalar Vector Graphics che utilizza un formato di testo basato su XML, compresso con GZIP, per descrivere l'aspetto di un'immagine. Scopri di più su questo formato di file qui. |
| [OTG](/viewer/python-net/groupdocs.viewer/filetype/otg/) | Modello OpenDocument Graphic (.otg) |
| [HTM](/viewer/python-net/groupdocs.viewer/filetype/htm/) | Il file Hypertext Markup Language (.htm) è l'estensione per pagine web create per la visualizzazione nei browser. Scopri di più su questo formato di file qui. |
| [HTML](/viewer/python-net/groupdocs.viewer/filetype/html/) | Il file Hypertext Markup Language (.html) è l'estensione per pagine web create per la visualizzazione nei browser. Scopri di più su questo formato di file qui. |
| [MHT](/viewer/python-net/groupdocs.viewer/filetype/mht/) | Archivio Web MHTML (.mht) |
| [MHTML](/viewer/python-net/groupdocs.viewer/filetype/mhtml/) | File MIME HTML (.mhtml) |
| [XML](/viewer/python-net/groupdocs.viewer/filetype/xml/) | File XML (.xml). GroupDocs.Viewer dispone di un processore speciale per la gestione dei file XML, consulta la documentazione. |
| [ONE](/viewer/python-net/groupdocs.viewer/filetype/one/) | Il documento OneNote (.one) è creato dall'applicazione Microsoft OneNote. OneNote ti consente di raccogliere informazioni usando l'applicazione come se stessi usando il tuo blocco per prendere appunti. Scopri di più su questo formato di file qui. |
| [PDF](/viewer/python-net/groupdocs.viewer/filetype/pdf/) | Il file Portable Document Format (.pdf) è un tipo di documento creato da Adobe negli anni '90. Lo scopo di questo formato di file era introdurre uno standard per la rappresentazione di documenti e altri materiali di riferimento in un formato indipendente dal software applicativo, dall'hardware e dal sistema operativo. Scopri di più su questo formato di file qui. |
| [XPS](/viewer/python-net/groupdocs.viewer/filetype/xps/) | Il file XML Paper Specification (.xps) rappresenta file di layout di pagina basati sulle XML Paper Specifications create da Microsoft. Questo formato è stato sviluppato da Microsoft come sostituto del formato EMF ed è simile al formato PDF, ma utilizza XML per il layout, l'aspetto e le informazioni di stampa di un documento. Scopri di più su questo formato di file qui. |
| [OXPS](/viewer/python-net/groupdocs.viewer/filetype/oxps/) | File OpenXPS (.oxps) |
| [TEX](/viewer/python-net/groupdocs.viewer/filetype/tex/) | Il documento sorgente LaTeX (.tex) è un linguaggio che comprende funzionalità di programmazione e di markup, usato per impaginare documenti. Scopri di più su questo formato di file qui. |
| [OFD](/viewer/python-net/groupdocs.viewer/filetype/ofd/) | Il formato Open Fixed-layout Document (OFD) definito da GB/T 33190-2016 mira a sostituire il PDF nelle istituzioni pubbliche cinesi. |
| [PPT](/viewer/python-net/groupdocs.viewer/filetype/ppt/) | La presentazione PowerPoint (.ppt) rappresenta un file PowerPoint che consiste in una raccolta di diapositive da visualizzare come presentazione. Specifica il Binary File Format usato da Microsoft PowerPoint 97-2003. Scopri di più su questo formato di file qui. |
| [PPTX](/viewer/python-net/groupdocs.viewer/filetype/pptx/) | Le presentazioni PowerPoint Open XML (.pptx) sono file di presentazione creati con la popolare applicazione Microsoft PowerPoint. A differenza della versione precedente del formato PPT, che era binario, il formato PPTX si basa sul formato di presentazione Open XML di Microsoft PowerPoint. Scopri di più su questo formato di file qui. |
| [PPS](/viewer/python-net/groupdocs.viewer/filetype/pps/) | Le presentazioni PowerPoint Slide Show (.pps) sono create con Microsoft PowerPoint per scopi di presentazione. La lettura e la creazione di file PPS è supportata da Microsoft PowerPoint 97-2003. Scopri di più su questo formato di file qui. |
| [PPSX](/viewer/python-net/groupdocs.viewer/filetype/ppsx/) | I file PowerPoint Open XML Slide Show (.ppsx) sono creati con Microsoft PowerPoint 2007 e versioni successive per scopi di presentazione. Scopri di più su questo formato di file qui. |
| [ODP](/viewer/python-net/groupdocs.viewer/filetype/odp/) | La presentazione OpenDocument (.odp) rappresenta il formato di file di presentazione usato da OpenOffice.org nello standard OASISOpen. Scopri di più su questo formato di file qui. |
| [FODP](/viewer/python-net/groupdocs.viewer/filetype/fodp/) | La presentazione OpenDocument (.fodp) rappresenta l'OpenDocument Flat XML Presentation. Scopri di più su questo formato di file qui. |
| [POT](/viewer/python-net/groupdocs.viewer/filetype/pot/) | Il modello PowerPoint (.pot) rappresenta i file modello di Microsoft PowerPoint creati dalle versioni PowerPoint 97-2003. Scopri di più su questo formato di file qui. |
| [PPTM](/viewer/python-net/groupdocs.viewer/filetype/pptm/) | PowerPoint Open XML Macro-Enabled Presentation sono file di presentazione con macro creati con Microsoft PowerPoint 2007 o versioni successive. Scopri di più su questo formato di file qui. |
| [POTX](/viewer/python-net/groupdocs.viewer/filetype/potx/) | PowerPoint Open XML Presentation Template (.potx) rappresenta le presentazioni modello di Microsoft PowerPoint create con Microsoft PowerPoint 2007 e versioni successive. Scopri di più su questo formato di file qui. |
| [POTM](/viewer/python-net/groupdocs.viewer/filetype/potm/) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) sono file modello di Microsoft PowerPoint con supporto per le macro. I file POTM sono creati con PowerPoint 2007 o versioni successive e contengono impostazioni predefinite che possono essere usate per creare ulteriori file di presentazione. Scopri di più su questo formato di file qui. |
| [PPSM](/viewer/python-net/groupdocs.viewer/filetype/ppsm/) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) rappresenta il formato di file di presentazione con macro creato con Microsoft PowerPoint 2007 o versioni successive. Scopri di più su questo formato di file qui. |
| [OTP](/viewer/python-net/groupdocs.viewer/filetype/otp/) | OpenDocument Presentation Template (.otp) rappresenta i file modello di presentazione creati da applicazioni nel formato standard OASIS OpenDocument. Scopri di più su questo formato di file qui. |
| [XLS](/viewer/python-net/groupdocs.viewer/filetype/xls/) | Excel Spreadsheet (.xls) rappresenta il formato di file binario di Excel. Tali file possono essere creati da Microsoft Excel così come da altri programmi di fogli di calcolo simili, come OpenOffice Calc o Apple Numbers. Scopri di più su questo formato di file qui. |
| [EXCEL_2003XML](/viewer/python-net/groupdocs.viewer/filetype/excel_2003xml/) | Excel 2003 XML (SpreadsheetML) rappresenta il formato di file binario di Excel. Tali file possono essere creati da Microsoft Excel così come da altri programmi di fogli di calcolo simili, come OpenOffice Calc o Apple Numbers. Scopri di più su questo formato di file qui. |
| [NUMBERS](/viewer/python-net/groupdocs.viewer/filetype/numbers/) | Apple Numbers rappresenta un formato di file binario simile a Excel. Tali file possono essere creati dall'applicazione Apple Numbers. Scopri di più su questo formato di file qui. |
| [XLSX](/viewer/python-net/groupdocs.viewer/filetype/xlsx/) | Microsoft Excel Open XML Spreadsheet (.xlsx) è un formato noto per i documenti Microsoft Excel, introdotto da Microsoft con il rilascio di Microsoft Office 2007. Scopri di più su questo formato di file qui. |
| [XLSM](/viewer/python-net/groupdocs.viewer/filetype/xlsm/) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) è un tipo di file di foglio di calcolo che supporta le macro. Scopri di più su questo formato di file qui. |
| [XLSB](/viewer/python-net/groupdocs.viewer/filetype/xlsb/) | Excel Binary Spreadsheet (.xlsb) specifica il formato di file binario di Excel, che è una raccolta di record e strutture che definiscono il contenuto della cartella di lavoro di Excel. Scopri di più su questo formato di file qui. |
| [CSV](/viewer/python-net/groupdocs.viewer/filetype/csv/) | Comma Separated Values File (.csv) rappresenta file di testo semplice che contengono record di dati con valori separati da virgola. Scopri di più su questo formato di file qui. |
| [TSV](/viewer/python-net/groupdocs.viewer/filetype/tsv/) | Tab Separated Values File (.tsv) rappresenta dati separati da tabulazioni in formato di testo semplice. Scopri di più su questo formato di file qui. |
| [ODS](/viewer/python-net/groupdocs.viewer/filetype/ods/) | OpenDocument Spreadsheet (.ods) indica il formato di documento foglio di calcolo OpenDocument, modificabile dall'utente. I dati sono memorizzati all'interno del file ODF in righe e colonne. Scopri di più su questo formato di file qui. |
| [FODS](/viewer/python-net/groupdocs.viewer/filetype/fods/) | OpenDocument Flat XML Spreadsheet (.fods) |
| [OTS](/viewer/python-net/groupdocs.viewer/filetype/ots/) | OpenDocument Spreadsheet Template (.ots) |
| [XLAM](/viewer/python-net/groupdocs.viewer/filetype/xlam/) | Microsoft Excel Add-in (.xlam) |
| [XLTM](/viewer/python-net/groupdocs.viewer/filetype/xltm/) | Microsoft Excel Macro-Enabled Template (.xltm) rappresenta i file generati da Microsoft Excel come modelli con macro. I file XLTM sono simili a XLTX nella struttura, tranne per il fatto che quest'ultimo non supporta la creazione di modelli con macro. Scopri di più su questo formato di file qui. |
| [XLT](/viewer/python-net/groupdocs.viewer/filetype/xlt/) | Microsoft Excel Template (.xlt) sono file modello creati con Microsoft Excel, un'applicazione di foglio di calcolo inclusa nella suite Microsoft Office. Microsoft Office 97-2003 supportava la creazione di nuovi file XLT così come l'apertura di questi. Scopri di più su questo formato di file qui. |
| [XLTX](/viewer/python-net/groupdocs.viewer/filetype/xltx/) | Excel Open XML Spreadsheet Template (.xltx) rappresenta il modello di Microsoft Excel basato sulle specifiche del formato file Office OpenXML. Viene utilizzato per creare un file modello standard che può essere impiegato per generare file XLSX con le stesse impostazioni specificate nel file XLTX. Scopri di più su questo formato di file qui. |
| [SXC](/viewer/python-net/groupdocs.viewer/filetype/sxc/) | StarOffice Calc Spreadsheet (.sxc) |
| [MPP](/viewer/python-net/groupdocs.viewer/filetype/mpp/) | Il file Microsoft Project (.mpp) è un file di dati di Microsoft Project che memorizza informazioni relative alla gestione del progetto in modo integrato. Scopri di più su questo formato di file qui. |
| [MPT](/viewer/python-net/groupdocs.viewer/filetype/mpt/) | Il modello Microsoft Project (.mpt) contiene informazioni di base e struttura insieme alle impostazioni del documento per creare file .MPP. Scopri di più su questo formato di file qui. |
| [MPX](/viewer/python-net/groupdocs.viewer/filetype/mpx/) | Il file Microsoft Project Exchange (.mpx) è un formato di file ASCII per il trasferimento di informazioni di progetto tra Microsoft Project (MSP) e altre applicazioni che supportano il formato MPX, come Primavera Project Planner, Sciforma e Timerline Precision Estimating. Scopri di più su questo formato di file qui. |
| [AS_](/viewer/python-net/groupdocs.viewer/filetype/as_/) | File ActionScript (.as) |
| [AS3](/viewer/python-net/groupdocs.viewer/filetype/as3/) | File ActionScript (.as) |
| [ASM](/viewer/python-net/groupdocs.viewer/filetype/asm/) | File di codice sorgente Assembly Language (.asm) |
| [BAT](/viewer/python-net/groupdocs.viewer/filetype/bat/) | File batch DOS (.bat) |
| [C](/viewer/python-net/groupdocs.viewer/filetype/c/) | File di codice sorgente C/C++ (.c) |
| [CC](/viewer/python-net/groupdocs.viewer/filetype/cc/) | File di codice sorgente C++ (.cc) |
| [CMAKE](/viewer/python-net/groupdocs.viewer/filetype/cmake/) | File CMake (.cmake) |
| [CPP](/viewer/python-net/groupdocs.viewer/filetype/cpp/) | File di codice sorgente C++ (.cpp) |
| [CS](/viewer/python-net/groupdocs.viewer/filetype/cs/) | Il file di codice sorgente C# (.cs) è un file di codice sorgente per il linguaggio di programmazione C#. Introdotto da Microsoft per l'uso con il .NET Framework. Scopri di più su questo formato di file qui. |
| [VB](/viewer/python-net/groupdocs.viewer/filetype/vb/) | Il file di elemento progetto Visual Basic (.vb) è un file di codice sorgente creato in linguaggio Visual Basic da Microsoft per lo sviluppo di applicazioni .NET. Scopri di più su questo formato di file qui. |
| [CSS](/viewer/python-net/groupdocs.viewer/filetype/css/) | Foglio di stile a cascata (.css) |
| [CXX](/viewer/python-net/groupdocs.viewer/filetype/cxx/) | File di codice sorgente C++ (.cxx) |
| [DIFF](/viewer/python-net/groupdocs.viewer/filetype/diff/) | File di patch (.diff) |
| [ERB](/viewer/python-net/groupdocs.viewer/filetype/erb/) | Script Ruby ERB (.erb) |
| [GROOVY](/viewer/python-net/groupdocs.viewer/filetype/groovy/) | File di codice sorgente Groovy (.groovy) |
| [H](/viewer/python-net/groupdocs.viewer/filetype/h/) | File di intestazione C/C++/Objective-C (.h) |
| [HAML](/viewer/python-net/groupdocs.viewer/filetype/haml/) | File di codice sorgente Haml (.haml) |
| [HH](/viewer/python-net/groupdocs.viewer/filetype/hh/) | File di intestazione C++ (.hh) |
| [JAVA](/viewer/python-net/groupdocs.viewer/filetype/java/) | File di codice sorgente Java (.java) |
| [JS](/viewer/python-net/groupdocs.viewer/filetype/js/) | File JavaScript (.js) |
| [JSON](/viewer/python-net/groupdocs.viewer/filetype/json/) | File JavaScript Object Notation (.json) |
| [LESS](/viewer/python-net/groupdocs.viewer/filetype/less/) | Foglio di stile LESS (.less) |
| [LOG](/viewer/python-net/groupdocs.viewer/filetype/log/) | File di registro (.log) |
| [M](/viewer/python-net/groupdocs.viewer/filetype/m/) | File di implementazione Objective-C (.m) |
| [MAKE](/viewer/python-net/groupdocs.viewer/filetype/make/) | Script Makefile di Xcode (.make) |
| [MD](/viewer/python-net/groupdocs.viewer/filetype/md/) | File di documentazione Markdown (.md) |
| [ML](/viewer/python-net/groupdocs.viewer/filetype/ml/) | File di codice sorgente ML (.ml) |
| [MM](/viewer/python-net/groupdocs.viewer/filetype/mm/) | File sorgente Objective-C++ (.mm) |
| [PHP](/viewer/python-net/groupdocs.viewer/filetype/php/) | File di codice sorgente PHP (.php) |
| [PL](/viewer/python-net/groupdocs.viewer/filetype/pl/) | Script Perl (.pl) |
| [PROPERTIES](/viewer/python-net/groupdocs.viewer/filetype/properties/) | File di proprietà Java (.properties) |
| [PY](/viewer/python-net/groupdocs.viewer/filetype/py/) | Script Python (.py) |
| [RB](/viewer/python-net/groupdocs.viewer/filetype/rb/) | File di codice sorgente Ruby (.rb) |
| [RST](/viewer/python-net/groupdocs.viewer/filetype/rst/) | File reStructuredText (.rst) |
| [SASS](/viewer/python-net/groupdocs.viewer/filetype/sass/) | File Syntactically Awesome StyleSheets (.sass) |
| [SCALA](/viewer/python-net/groupdocs.viewer/filetype/scala/) | File di codice sorgente Scala (.scala) |
| [SCM](/viewer/python-net/groupdocs.viewer/filetype/scm/) | File di codice sorgente Scheme (.scm) |
| [SCRIPT](/viewer/python-net/groupdocs.viewer/filetype/script/) | File script generico (.script) |
| [SH](/viewer/python-net/groupdocs.viewer/filetype/sh/) | Script Bash Shell (.sh) |
| [SML](/viewer/python-net/groupdocs.viewer/filetype/sml/) | File di codice sorgente Standard ML (.sml) |
| [SQL](/viewer/python-net/groupdocs.viewer/filetype/sql/) | File dati Structured Query Language (.sql) |
| [VIM](/viewer/python-net/groupdocs.viewer/filetype/vim/) | File di impostazioni Vim (.vim) |
| [YAML](/viewer/python-net/groupdocs.viewer/filetype/yaml/) | Documento YAML (.yaml) |
| [DOC](/viewer/python-net/groupdocs.viewer/filetype/doc/) | Il documento Microsoft Word (.doc) rappresenta i documenti generati da Microsoft Word o da altri programmi di elaborazione testi in formato binario. Scopri di più su questo formato di file qui. |
| [DOCX](/viewer/python-net/groupdocs.viewer/filetype/docx/) | Il documento Microsoft Word Open XML (.docx) è un formato noto per i documenti Microsoft Word. Introdotto dal 2007 con il rilascio di Microsoft Office 2007, la struttura di questo nuovo formato di documento è stata modificata da puro binario a una combinazione di file XML e binari. Scopri di più su questo formato di file qui. |
| [CHM](/viewer/python-net/groupdocs.viewer/filetype/chm/) | Il file Microsoft Compiled HTML Help (.chm) è un formato noto per i documenti HELP (documentazione per qualche applicazione). Scopri di più su questo formato di file qui. |
| [DOCM](/viewer/python-net/groupdocs.viewer/filetype/docm/) | Il documento Word Open XML abilitato alle macro (.docm) è un documento generato da Microsoft Word 2007 o versioni successive con la possibilità di eseguire macro. Scopri di più su questo formato di file qui. |
| [DOT](/viewer/python-net/groupdocs.viewer/filetype/dot/) | I modelli di documento Word (.dot) sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOC o DOCX. Scopri di più su questo formato di file qui. |
| [DOTX](/viewer/python-net/groupdocs.viewer/filetype/dotx/) | Word Open XML Document Template (.dotx) sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOCX. Scopri di più su questo formato di file qui. |
| [DOTM](/viewer/python-net/groupdocs.viewer/filetype/dotm/) | Word Open XML Macro-Enabled Document Template (.dotm) rappresenta un file modello creato con Microsoft Word 2007 o versioni successive. Scopri di più su questo formato di file qui. |
| [RTF](/viewer/python-net/groupdocs.viewer/filetype/rtf/) | Rich Text Format File (.rtf) rappresenta un metodo di codifica di testo formattato e grafica per l'uso all'interno delle applicazioni. Scopri di più su questo formato di file qui. |
| [TXT](/viewer/python-net/groupdocs.viewer/filetype/txt/) | Plain Text File (.txt) rappresenta un documento di testo che contiene testo semplice sotto forma di righe. Scopri di più su questo formato di file qui. |
| [ODT](/viewer/python-net/groupdocs.viewer/filetype/odt/) | OpenDocument Text Document (.odt) è un tipo di documento creato con applicazioni di elaborazione testi basate sul formato OpenDocument Text File. Scopri di più su questo formato di file qui. |
| [OTT](/viewer/python-net/groupdocs.viewer/filetype/ott/) | OpenDocument Document Template (.ott) rappresenta documenti modello generati da applicazioni conformi al formato standard OpenDocument di OASIS. Scopri di più su questo formato di file qui. |
| [VCF](/viewer/python-net/groupdocs.viewer/filetype/vcf/) | vCard File (.vcf) è un formato di file digitale per la memorizzazione di informazioni di contatto. Il formato è ampiamente utilizzato per lo scambio di dati tra le popolari applicazioni di scambio informazioni. Scopri di più su questo formato di file qui. |
| [AI](/viewer/python-net/groupdocs.viewer/filetype/ai/) | Adobe Illustrator (.ai) è un formato di file per disegni Adobe Illustrator. Scopri di più su questo formato di file qui. |
| [PSM1](/viewer/python-net/groupdocs.viewer/filetype/psm1/) | PowerShell script module (.psm1) è un formato di file per script di modulo PowerShell. Scopri di più su questo formato di file qui. |
| [PS1](/viewer/python-net/groupdocs.viewer/filetype/ps1/) | PowerShell script file (.ps1) è un formato di file per file Cmdlet di Windows PowerShell. Scopri di più su questo formato di file qui. |
| [PSD1](/viewer/python-net/groupdocs.viewer/filetype/psd1/) | PowerShell script module manifest (.psd1) è un formato di file per script di manifest di modulo PowerShell. Scopri di più su questo formato di file qui. |

### Esempio

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

# Specifica il tipo di file (ad es., Markdown) durante il caricamento del documento
load_options = LoadOptions(FileType.MD)

# Renderizza il documento in PDF
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### Vedi anche
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
