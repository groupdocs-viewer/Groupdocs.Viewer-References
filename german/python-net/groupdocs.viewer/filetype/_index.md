---
title: "FileType Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Stellt einen Dateityp dar und bietet Methoden, um die Liste aller von GroupDocs.Viewer unterstützten Dateitypen zu erhalten."
type: docs
url: /de/python-net/groupdocs.viewer/filetype/
is_root: false
weight: 10
---


## FileType class

Stellt einen Dateityp dar und bietet Methoden, um die Liste aller von GroupDocs.Viewer unterstützten Dateitypen zu erhalten.

Der Typ FileType stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/) | Initialisiert eine neue Instanz von [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/). |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/#file_format-extension) | Initialisiert eine neue FileType-Instanz. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#file_path) | Ermittelt die Kodierung von Text‑TXT-, TSV‑ und CSV‑Dateien anhand des Pfads. |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#stream) | Versucht, die Kodierung von Textdateien (TXT, TSV, CSV) aus einem Stream zu ermitteln. |
| [detect_encoding_file](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_file/) |  |
| [detect_encoding_stream](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_stream/) |  |
| [detect_encoding_streams](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_streams/) |  |
| [detect_encoding_string](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_string/) |  |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#other) | Bestimmt, ob der aktuelle [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) derselbe ist wie der angegebene [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/). |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#obj) | Bestimmt, ob der aktuelle [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) derselbe ist wie das angegebene Objekt. |
| [equals_file_type](/viewer/python-net/groupdocs.viewer/filetype/equals_file_type/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer/filetype/equals_object/) |  |
| [from_extension](/viewer/python-net/groupdocs.viewer/filetype/from_extension/#extension) | Ordnet Dateierweiterungen Dateitypen zu. |
| [from_file_path](/viewer/python-net/groupdocs.viewer/filetype/from_file_path/#file_path) | Extrahiert die Dateierweiterung und ordnet sie einem Dateityp zu. |
| [from_media_type](/viewer/python-net/groupdocs.viewer/filetype/from_media_type/#media_type) | Ordnet einen Dateimedientyp einem [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) zu (z. B. wird 'application/pdf' dem [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/) zugeordnet). |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream) | Erkennt den Dateityp durch Lesen der Dateisignatur. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password) | Erkennt den Dateityp durch Lesen der Dateisignatur. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-logger) | Erkennt den Dateityp durch Lesen der Dateisignatur. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password-logger) | Erkennt den Dateityp durch Lesen der Dateisignatur. |
| [from_stream_file](/viewer/python-net/groupdocs.viewer/filetype/from_stream_file/) |  |
| [from_stream_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream_stream/) |  |
| [from_stream_streams](/viewer/python-net/groupdocs.viewer/filetype/from_stream_streams/) |  |
| [from_stream_string](/viewer/python-net/groupdocs.viewer/filetype/from_stream_string/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer/filetype/get_hash_code/) | Gibt den Hashcode für das aktuelle [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)‑Objekt zurück. |
| [get_supported_file_types](/viewer/python-net/groupdocs.viewer/filetype/get_supported_file_types/) | Ruft unterstützte Dateitypen ab. |
| [to_string](/viewer/python-net/groupdocs.viewer/filetype/to_string/) | Gibt einen String zurück, der das aktuelle Objekt darstellt. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [extension](/viewer/python-net/groupdocs.viewer/filetype/extension/) | Der Dateinamensuffix (einschließlich des Punktes "."), z. B. ".doc". |
| [file_format](/viewer/python-net/groupdocs.viewer/filetype/file_format/) | Der Dateitypname, z. B. "Microsoft Word Document". |

### Felder
| Feld | Beschreibung |
| :- | :- |
| [UNKNOWN](/viewer/python-net/groupdocs.viewer/filetype/unknown/) | Stellt einen unbekannten Dateityp dar. |
| [ZIP](/viewer/python-net/groupdocs.viewer/filetype/zip/) | Zipped File (.zip) steht für Archive, die eine oder mehrere Dateien oder Verzeichnisse enthalten können. Weitere Informationen zu diesem Dateiformat finden Sie hier. |
| [TAR](/viewer/python-net/groupdocs.viewer/filetype/tar/) | Consolidated Unix File Archive (.tar) sind Archive, die mit einem Unix‑basierten Dienstprogramm zum Sammeln einer oder mehrerer Dateien erstellt wurden. Weitere Informationen zu diesem Dateiformat finden Sie hier. |
| [XZ](/viewer/python-net/groupdocs.viewer/filetype/xz/) | XZ-Datei (.xz) ist ein komprimiertes Archiv, das einen hochgradigen Kompressionsalgorithmus auf Basis des LZMA-Algorithmus verwendet. Erfahren Sie hier mehr über dieses Dateiformat. |
| [TXZ](/viewer/python-net/groupdocs.viewer/filetype/txz/) | Consolidated Unix File Archive (.txz, .tar.xz) sind Archive, die mit einem Unix‑basierten Dienstprogramm zum Sammeln einer oder mehrerer Dateien erstellt wurden. Erfahren Sie hier mehr über dieses Dateiformat. |
| [TARXZ](/viewer/python-net/groupdocs.viewer/filetype/tarxz/) | Consolidated Unix File Archive (.txz, .tar.xz) sind Archive, die mit einem Unix‑basierten Dienstprogramm zum Sammeln einer oder mehrerer Dateien erstellt wurden. Erfahren Sie hier mehr über dieses Dateiformat. |
| [TGZ](/viewer/python-net/groupdocs.viewer/filetype/tgz/) | Consolidated Unix File Archive (.tgz, .tar.gz) sind Archive, die mit einem Unix‑basierten Dienstprogramm zum Sammeln einer oder mehrerer Dateien erstellt wurden. Erfahren Sie hier mehr über dieses Dateiformat. |
| [TARGZ](/viewer/python-net/groupdocs.viewer/filetype/targz/) | Consolidated Unix File Archive (.tgz, .tar.gz) sind Archive, die mit einem Unix‑basierten Dienstprogramm zum Sammeln einer oder mehrerer Dateien erstellt wurden. Erfahren Sie hier mehr über dieses Dateiformat. |
| [BZ2](/viewer/python-net/groupdocs.viewer/filetype/bz2/) | Bzip2-komprimierte Datei (.bz2) sind komprimierte Dateien, die mit der Open‑Source‑Kompressionsmethode BZIP2 erzeugt werden, meist auf UNIX‑ oder Linux‑Systemen. Erfahren Sie hier mehr über dieses Dateiformat. |
| [RAR](/viewer/python-net/groupdocs.viewer/filetype/rar/) | Roshal ARchive (.rar) sind komprimierte Dateien, die mit der RAR‑Kompressionsmethode (WINRAR) erzeugt werden. Erfahren Sie hier mehr über dieses Dateiformat. |
| [GZ](/viewer/python-net/groupdocs.viewer/filetype/gz/) | Gnu Zipped File (.gz) sind komprimierte Dateien, die mit der gzip‑Kompressionsanwendung erstellt werden. Sie können mehrere komprimierte Dateien enthalten und werden häufig auf UNIX‑ und Linux‑Systemen verwendet. Erfahren Sie hier mehr über dieses Dateiformat. |
| [GZIP](/viewer/python-net/groupdocs.viewer/filetype/gzip/) | Gnu Zipped File (.gzip) wurde als kostenloses Dienstprogramm eingeführt, um das in Unix‑Systemen verwendete Compress‑Programm zu ersetzen. Solche Dateien können mit verschiedenen Anwendungen wie WinZip, das sowohl für Windows als auch für macOS verfügbar ist, geöffnet und extrahiert werden. Erfahren Sie hier mehr über dieses Dateiformat. |
| [SEVEN_ZIP](/viewer/python-net/groupdocs.viewer/filetype/seven_zip/) | 7Zip (.7z, .7zip) ist ein kostenloser Open‑Source‑Archivierer mit LZMA‑ und LZMA2‑Kompression. Erfahren Sie hier mehr über dieses Dateiformat. |
| [CPIO](/viewer/python-net/groupdocs.viewer/filetype/cpio/) | Cpio ist ein allgemeines Dateiarchivierungs‑Dienstprogramm und das zugehörige Dateiformat. Es ist hauptsächlich auf unix‑ähnlichen Betriebssystemen installiert. Erfahren Sie hier mehr über dieses Dateiformat. |
| [ZSTANDARD](/viewer/python-net/groupdocs.viewer/filetype/zstandard/) | ZST-Datei ist eine komprimierte Datei, die mit dem Zstandard‑ (zstd‑) Kompressionsalgorithmus erzeugt wird. Sie wird durch verlustfreie Kompression des Algorithmus erstellt. ZST‑Dateien können verwendet werden, um verschiedene Dateitypen wie Datenbanken, Dateisysteme, Netzwerke und Spiele zu komprimieren. Erfahren Sie hier mehr über dieses Dateiformat. |
| [TZST](/viewer/python-net/groupdocs.viewer/filetype/tzst/) | TZST-Dateien (.tar.zst, .tzst) sind Zstandard‑Archive (ZST), die intern ein Consolidated Unix File Archive (Tar) enthalten und mit einem Unix‑basierten Dienstprogramm zum Sammeln einer oder mehrerer Dateien erstellt wurden. |
| [TAR_ZST](/viewer/python-net/groupdocs.viewer/filetype/tar_zst/) | TZST-Dateien (.tar.zst, .tzst) sind Zstandard‑Archive (ZST), die intern ein Consolidated Unix File Archive (Tar) enthalten und mit einem Unix‑basierten Dienstprogramm zum Sammeln einer oder mehrerer Dateien erstellt wurden. |
| [ISO](/viewer/python-net/groupdocs.viewer/filetype/iso/) | ISO‑Optik‑Disc‑Image ist eine unkomprimierte Archiv‑Disk‑Image‑Datei, die den gesamten Inhalt einer optischen Disc wie CD oder DVD gemäß dem ISO‑9660‑Standard darstellt. Erfahren Sie hier mehr über dieses Dateiformat. |
| [LHA](/viewer/python-net/groupdocs.viewer/filetype/lha/) | LHA oder LZH ist ein kostenloses Kompressions‑Dienstprogramm und das zugehörige Dateiformat. Erfahren Sie hier mehr über dieses Dateiformat. |
| [CAB](/viewer/python-net/groupdocs.viewer/filetype/cab/) | Cabinet (oder CAB) ist ein Archivdateiformat für Microsoft Windows. Erfahren Sie hier mehr über dieses Dateiformat. |
| [DXF](/viewer/python-net/groupdocs.viewer/filetype/dxf/) | Drawing Exchange Format File (.dxf) ist eine getaggte Datenrepräsentation einer AutoCAD‑Zeichnungsdatei. Erfahren Sie hier mehr über dieses Dateiformat. |
| [DWG](/viewer/python-net/groupdocs.viewer/filetype/dwg/) | AutoCAD Drawing Database File (.dwg) stellt proprietäre Binärdateien dar, die zur Speicherung von 2D‑ und 3D‑Designdaten verwendet werden. Wie DXF, das ASCII‑Dateien sind, repräsentiert DWG das binäre Dateiformat für CAD‑(Computer‑Aided‑Design‑)Zeichnungen. Erfahren Sie hier mehr über dieses Dateiformat. |
| [DWT](/viewer/python-net/groupdocs.viewer/filetype/dwt/) | AutoCAD-Zeichnungsvorlage (.dwt) ist eine AutoCAD-Zeichnungsvorlagendatei, die als Ausgangspunkt für das Erstellen von Zeichnungen verwendet wird, die als DWG-Dateien gespeichert werden können. Erfahren Sie hier mehr über dieses Dateiformat. |
| [STL](/viewer/python-net/groupdocs.viewer/filetype/stl/) | Stereolithographie-Datei (.stl) ist ein austauschbares Dateiformat, das dreidimensionale Oberflächengeometrie darstellt. Das Dateiformat wird in verschiedenen Bereichen wie Rapid Prototyping, 3D-Druck und computergestützter Fertigung verwendet. Erfahren Sie hier mehr über dieses Dateiformat. |
| [IFC](/viewer/python-net/groupdocs.viewer/filetype/ifc/) | Industry Foundation Classes-Datei (.ifc) ist ein Dateiformat, das internationale Standards für den Import und Export von Bauobjekten und deren Eigenschaften festlegt. Dieses Dateiformat ermöglicht Interoperabilität zwischen verschiedenen Softwareanwendungen. Erfahren Sie hier mehr über dieses Dateiformat. |
| [DWF](/viewer/python-net/groupdocs.viewer/filetype/dwf/) | Design Web Format-Datei (.dwf) stellt 2D/3D-Zeichnungen in komprimiertem Format zum Anzeigen, Überprüfen oder Drucken von Design-Dateien dar. Sie enthält Grafiken und Text als Teil der Designdaten und reduziert die Dateigröße dank ihres komprimierten Formats. Erfahren Sie hier mehr über dieses Dateiformat. |
| [FBX](/viewer/python-net/groupdocs.viewer/filetype/fbx/) | Autodesk FBX Interchange File (FilmBoX) (.fbx) stellt ein 3D-Modellformat dar. Erfahren Sie hier mehr über dieses Dateiformat. |
| [DWFX](/viewer/python-net/groupdocs.viewer/filetype/dwfx/) | Design Web Format File XPS (.dwfx) stellt 2D/3D-Zeichnungen als XPS-Dokument in komprimiertem Format zum Anzeigen, Überprüfen oder Drucken von Design-Dateien dar. Es enthält Grafiken und Text als Teil der Designdaten und reduziert die Dateigröße dank seines komprimierten Formats. Erfahren Sie hier mehr über dieses Dateiformat. |
| [DGN](/viewer/python-net/groupdocs.viewer/filetype/dgn/) | MicroStation Design File (.dgn) sind Zeichnungen, die von CAD-Anwendungen wie MicroStation und Intergraph Interactive Graphics Design System erstellt und unterstützt werden. Erfahren Sie hier mehr über dieses Dateiformat. |
| [PLT](/viewer/python-net/groupdocs.viewer/filetype/plt/) | PLT (HPGL) (.plt) ist eine vektorbasierte Plotterdatei, die von Autodesk, Inc. eingeführt wurde und Informationen für eine bestimmte CAD-Datei enthält. Plotdetails erfordern Genauigkeit und Präzision in der Produktion, und die Verwendung von PLT-Dateien garantiert dies, da alle Bilder mit Linien statt Punkten gedruckt werden. Erfahren Sie hier mehr über dieses Dateiformat. |
| [CF2](/viewer/python-net/groupdocs.viewer/filetype/cf2/) | Common File Format-Datei Erfahren Sie hier mehr über dieses Dateiformat. |
| [OBJ](/viewer/python-net/groupdocs.viewer/filetype/obj/) | Wavefront 3D Object File (.obj) ist eine 3D-Bilddatei, die von Wavefront Technologies eingeführt wurde. Erfahren Sie hier mehr über dieses Dateiformat. |
| [HPG](/viewer/python-net/groupdocs.viewer/filetype/hpg/) | PLT (HPGL) (.hpg) |
| [IGS](/viewer/python-net/groupdocs.viewer/filetype/igs/) | Initial Graphics Exchange Specification (IGES) (.igs) |
| [VSD](/viewer/python-net/groupdocs.viewer/filetype/vsd/) | Visio Drawing File (.vsd) sind Zeichnungen, die mit der Microsoft Visio-Anwendung erstellt werden, um eine Vielzahl von grafischen Objekten und deren Verknüpfungen darzustellen. Erfahren Sie hier mehr über dieses Dateiformat. |
| [VSDX](/viewer/python-net/groupdocs.viewer/filetype/vsdx/) | Visio Drawing (.vsdx) stellt das Microsoft Visio-Dateiformat dar, das ab Microsoft Office 2013 eingeführt wurde. Es wurde entwickelt, um das binäre Dateiformat .VSD zu ersetzen, das von früheren Versionen von Microsoft Visio unterstützt wird. Erfahren Sie hier mehr über dieses Dateiformat. |
| [VSS](/viewer/python-net/groupdocs.viewer/filetype/vss/) | Visio Stencil File(.vss) sind Stencil-Dateien, die mit Microsoft Visio 2007 und früher erstellt wurden. Stencil-Dateien stellen Zeichenobjekte bereit, die in einer .VSD Visio-Zeichnung eingebunden werden können. Erfahren Sie hier mehr über dieses Dateiformat. |
| [VSSX](/viewer/python-net/groupdocs.viewer/filetype/vssx/) | Visio-Stencil-Datei (.vssx) sind Zeichenstempel, die mit Microsoft Visio 2013 und höher erstellt wurden. Das VSSX-Dateiformat kann mit Visio 2013 und höher geöffnet werden. Visio-Dateien sind bekannt für die Darstellung einer Vielzahl von Zeichnungselementen wie Sammlungen von Formen, Verbindern, Flussdiagrammen, Netzwerklayouts, UML-Diagrammen, Erfahren Sie mehr über dieses Dateiformat hier. |
| [VSDM](/viewer/python-net/groupdocs.viewer/filetype/vsdm/) | Visio-Makro‑aktivierte Zeichnung (.vsdm) sind Zeichnungsdateien, die mit der Microsoft Visio‑Anwendung erstellt wurden und Makros unterstützen. VSDM‑Dateien sind OPC/XML‑Zeichnungen, die VSDX ähneln, aber zudem die Möglichkeit bieten, Makros beim Öffnen der Datei auszuführen. Erfahren Sie mehr über dieses Dateiformat hier. |
| [VST](/viewer/python-net/groupdocs.viewer/filetype/vst/) | Visio-Zeichnungsvorlage (.vst) sind Vektorbilder, die mit Microsoft Visio erstellt werden und als Vorlage für die Erstellung weiterer Dateien dienen. Diese Vorlagendateien liegen im Binärformat vor und enthalten das Standardlayout sowie die Einstellungen, die für die Erstellung neuer Visio‑Zeichnungen verwendet werden. Erfahren Sie mehr über dieses Dateiformat hier. |
| [VSTX](/viewer/python-net/groupdocs.viewer/filetype/vstx/) | Visio-Zeichnungsvorlage (.vstx) sind Zeichnungsvorlagendateien, die mit Microsoft Visio 2013 und höher erstellt wurden. Diese VSTX‑Dateien bieten einen Ausgangspunkt für die Erstellung von Visio‑Zeichnungen, die als .VSDX‑Dateien gespeichert werden, mit Standardlayout und -einstellungen. Erfahren Sie mehr über dieses Dateiformat hier. |
| [VSTM](/viewer/python-net/groupdocs.viewer/filetype/vstm/) | Visio-Makro‑aktivierte Zeichnungsvorlage (.vstm) sind Vorlagendateien, die mit Microsoft Visio erstellt wurden und Makros unterstützen. Im Gegensatz zu VSDX‑Dateien können aus VSTM‑Vorlagen erstellte Dateien Makros ausführen, die in Visual Basic for Applications (VBA)-Code entwickelt wurden. Erfahren Sie mehr über dieses Dateiformat hier. |
| [VSSM](/viewer/python-net/groupdocs.viewer/filetype/vssm/) | Visio-Makro‑aktivierte Stencil‑Datei (.vssm) sind Microsoft Visio‑Stencil‑Dateien, die Makros unterstützen. Wird eine VSSM‑Datei geöffnet, können die Makros ausgeführt werden, um die gewünschte Formatierung und Platzierung von Formen in einem Diagramm zu erreichen. Erfahren Sie mehr über dieses Dateiformat hier. |
| [VSX](/viewer/python-net/groupdocs.viewer/filetype/vsx/) | Visio-Stencil‑XML‑Datei (.vsx) bezieht sich auf Stencils, die aus Zeichnungen und Formen bestehen und zum Erstellen von Diagrammen in Microsoft Visio verwendet werden. VSX‑Dateien werden im XML‑Dateiformat gespeichert und wurden bis Visio 2013 unterstützt. Erfahren Sie mehr über dieses Dateiformat hier. |
| [VTX](/viewer/python-net/groupdocs.viewer/filetype/vtx/) | Visio‑Vorlagen‑XML‑Datei (.vtx) ist eine Microsoft Visio‑Zeichnungsvorlage, die im XML‑Dateiformat auf dem Datenträger gespeichert wird. Die Vorlage soll eine Datei mit Basiseinstellungen bereitstellen, die zur Erstellung mehrerer Visio‑Dateien mit denselben Einstellungen verwendet werden kann. Erfahren Sie mehr über dieses Dateiformat hier. |
| [VDW](/viewer/python-net/groupdocs.viewer/filetype/vdw/) | Visio-Web‑Zeichnung (.vdw) stellt ein Dateiformat dar, das die für die Darstellung einer Web‑Zeichnung erforderlichen Streams und Speicherbereiche spezifiziert. Erfahren Sie mehr über dieses Dateiformat hier. |
| [VDX](/viewer/python-net/groupdocs.viewer/filetype/vdx/) | Visio‑Zeichnungs‑XML‑Datei (.vdx) steht für jede in Microsoft Visio erstellte Zeichnung oder Grafik, die im XML‑Format mit der Erweiterung .VDX gespeichert wird. Eine Visio‑Zeichnungs‑XML‑Datei wird in der Visio‑Software erstellt, die von Microsoft entwickelt wurde. Erfahren Sie mehr über dieses Dateiformat hier. |
| [EPUB](/viewer/python-net/groupdocs.viewer/filetype/epub/) | Open eBook File (.epub) ist ein eBook-Dateiformat, das ein standardisiertes digitales Publikationsformat für Verlage und Verbraucher bereitstellt. Das Format ist inzwischen so verbreitet, dass es von vielen E-Readern und Softwareanwendungen unterstützt wird. Erfahren Sie hier mehr über dieses Dateiformat. |
| [MOBI](/viewer/python-net/groupdocs.viewer/filetype/mobi/) | Mobipocket eBook (.mobi) ist eines der am weitesten verbreiteten eBook-Dateiformate. Das Format ist eine Weiterentwicklung des alten OEB (Open Ebook Format)-Formats und wurde als proprietäres Format für den Mobipocket Reader verwendet. Erfahren Sie hier mehr über dieses Dateiformat. |
| [AZW3](/viewer/python-net/groupdocs.viewer/filetype/azw3/) | Amazon Kindle Format 8 (KF8) eBook ist das digitale Dateiformat, das für Amazon Kindle‑Geräte entwickelt wurde. Das Format ist eine Weiterentwicklung älterer AZW‑Dateien und wird auf Kindle‑Fire‑Geräten ausschließlich mit Rückwärtskompatibilität zum Vorgängerformat, d. h. MOBI und AZW, verwendet. Erfahren Sie hier mehr über dieses Dateiformat. |
| [MSG](/viewer/python-net/groupdocs.viewer/filetype/msg/) | Outlook Mail Message (.msg) ist ein Dateiformat, das von Microsoft Outlook und Exchange zum Speichern von E‑Mail‑Nachrichten, Kontakten, Terminen oder anderen Aufgaben verwendet wird. Erfahren Sie hier mehr über dieses Dateiformat. |
| [EML](/viewer/python-net/groupdocs.viewer/filetype/eml/) | E‑Mail Message (.eml) steht für mit Outlook und anderen relevanten Anwendungen gespeicherte E‑Mail‑Nachrichten. Fast alle E‑Mail‑Clients unterstützen dieses Dateiformat, da es dem RFC‑822‑Internet‑Message‑Format‑Standard entspricht. Erfahren Sie hier mehr über dieses Dateiformat. |
| [NSF](/viewer/python-net/groupdocs.viewer/filetype/nsf/) | Lotus Notes Database (.nsf) Erfahren Sie hier mehr über dieses Dateiformat. |
| [MBOX](/viewer/python-net/groupdocs.viewer/filetype/mbox/) | Email Mailbox File (.mbox) Erfahren Sie hier mehr über dieses Dateiformat. |
| [EMLX](/viewer/python-net/groupdocs.viewer/filetype/emlx/) | Apple Mail Message (.emlx) wird von Apple implementiert und entwickelt. Die Apple‑Mail‑Anwendung verwendet das EMLX‑Dateiformat zum Exportieren von E‑Mails. Erfahren Sie hier mehr über dieses Dateiformat. |
| [PST](/viewer/python-net/groupdocs.viewer/filetype/pst/) | Outlook Personal Information Store File (.pst) steht für Outlook Personal Storage Files (auch Personal Storage Table genannt), die eine Vielzahl von Benutzerdaten speichern. Erfahren Sie hier mehr über dieses Dateiformat. |
| [OST](/viewer/python-net/groupdocs.viewer/filetype/ost/) | Outlook Offline Data File (.ost) stellt die Mailbox‑Daten eines Benutzers im Offline‑Modus auf dem lokalen Rechner dar, nachdem er sich mit dem Exchange‑Server über Microsoft Outlook registriert hat. Erfahren Sie hier mehr über dieses Dateiformat. |
| [TIF](/viewer/python-net/groupdocs.viewer/filetype/tif/) | Tagged Image File (.tif) steht für Rasterbilder, die auf einer Vielzahl von Geräten verwendet werden können, die diesem Dateiformatstandard entsprechen. Es kann bilevel‑, Graustufen‑, Paletten‑ und Vollfarbbilddaten in mehreren Farbräumen beschreiben. Erfahren Sie hier mehr über dieses Dateiformat. |
| [TIFF](/viewer/python-net/groupdocs.viewer/filetype/tiff/) | Tagged Image File Format (.tiff) steht für Rasterbilder, die auf einer Vielzahl von Geräten verwendet werden können, die diesem Dateiformatstandard entsprechen. Es kann bilevel‑, Graustufen‑, Paletten‑ und Vollfarbbilddaten in mehreren Farbräumen beschreiben. Erfahren Sie hier mehr über dieses Dateiformat. |
| [JPG](/viewer/python-net/groupdocs.viewer/filetype/jpg/) | JPEG Image (.jpg) ist ein Bildformat, das mit verlustbehafteter Kompression gespeichert wird. Das resultierende Bild stellt einen Kompromiss zwischen Dateigröße und Bildqualität dar. Erfahren Sie hier mehr über dieses Dateiformat. |
| [JPEG](/viewer/python-net/groupdocs.viewer/filetype/jpeg/) | JPEG-Bild (.jpeg) ist ein Bildformat, das mit verlustbehafteter Kompression gespeichert wird. Das Ausgabebild ist als Ergebnis der Kompression ein Kompromiss zwischen Speichergröße und Bildqualität. Erfahren Sie hier mehr über dieses Dateiformat. |
| [JFIF](/viewer/python-net/groupdocs.viewer/filetype/jfif/) | JPEG File Interchange Format (.jfif) ist ein Bildformat, das für den schnellen Austausch zwischen Plattformen entwickelt wurde. Dieses Format verwendet JPEG‑Kompression. Erfahren Sie hier mehr über dieses Dateiformat. |
| [PNG](/viewer/python-net/groupdocs.viewer/filetype/png/) | Portable Network Graphic (.png) ist ein Raster‑Bilddateiformat, das verlustfreie Kompression verwendet. Dieses Dateiformat wurde als Ersatz des Graphics Interchange Format (GIF) geschaffen und hat keine urheberrechtlichen Beschränkungen. Erfahren Sie hier mehr über dieses Dateiformat. |
| [GIF](/viewer/python-net/groupdocs.viewer/filetype/gif/) | Graphical Interchange Format File (.gif) ist ein stark komprimiertes Bildformat. Für jedes Bild erlaubt GIF typischerweise bis zu 8 Bit pro Pixel und bis zu 256 Farben im Bild. Erfahren Sie hier mehr über dieses Dateiformat. |
| [APNG](/viewer/python-net/groupdocs.viewer/filetype/apng/) | Animated Portable Network Graphic (.apng) ist eine Erweiterung des PNG‑Formats, die Animation unterstützt. Erfahren Sie hier mehr über dieses Dateiformat. |
| [BMP](/viewer/python-net/groupdocs.viewer/filetype/bmp/) | Bitmap Image File (.bmp) wird verwendet, um digitale Bitmap‑Bilder zu speichern. Diese Bilder sind unabhängig vom Grafikadapter und werden auch Device Independent Bitmap (DIB) Dateiformat genannt. Erfahren Sie hier mehr über dieses Dateiformat. |
| [TGA](/viewer/python-net/groupdocs.viewer/filetype/tga/) | Truevision TGA (Truevision Advanced Raster Adapter – TARGA) wird verwendet, um von TRUEVISION entwickelte digitale Bitmap‑Bilder zu speichern. Erfahren Sie hier mehr über dieses Dateiformat. |
| [ICO](/viewer/python-net/groupdocs.viewer/filetype/ico/) | Icon File (.ico) ist ein Bilddateityp, der als Symbol zur Darstellung einer Anwendung unter Microsoft Windows verwendet wird. Erfahren Sie hier mehr über dieses Dateiformat. |
| [JP2](/viewer/python-net/groupdocs.viewer/filetype/jp2/) | JPEG 2000 Core Image File (.jp2) ist ein Bildkodierungssystem und ein hochmodernes Bildkompressionsstandard. Erfahren Sie hier mehr über dieses Dateiformat. |
| [JPF](/viewer/python-net/groupdocs.viewer/filetype/jpf/) | JPEG 2000 Bilddatei (.jpf) |
| [JPX](/viewer/python-net/groupdocs.viewer/filetype/jpx/) | JPEG 2000 Bilddatei (.jpx) |
| [JPM](/viewer/python-net/groupdocs.viewer/filetype/jpm/) | JPEG 2000 Bilddatei (.jpm) |
| [J2C](/viewer/python-net/groupdocs.viewer/filetype/j2c/) | JPEG 2000 Code‑Stream (.j2c) |
| [J2K](/viewer/python-net/groupdocs.viewer/filetype/j2k/) | JPEG 2000 Code‑Stream (.j2k) ist ein Bild, das mit Wavelet‑Kompression anstelle von DCT‑Kompression komprimiert wird. Erfahren Sie hier mehr über dieses Dateiformat. |
| [JPC](/viewer/python-net/groupdocs.viewer/filetype/jpc/) | JPEG 2000 Code‑Stream (.jpc) |
| [JLS](/viewer/python-net/groupdocs.viewer/filetype/jls/) | JPEG-LS (JLS) (.jls) |
| [DIB](/viewer/python-net/groupdocs.viewer/filetype/dib/) | Geräteunabhängige Bitmap-Datei (.dib) |
| [WMF](/viewer/python-net/groupdocs.viewer/filetype/wmf/) | Windows Metafile (.wmf) stellt das Microsoft Windows Metafile (WMF) zum Speichern von Vektor‑ sowie Bitmap‑Bilddaten dar. Erfahren Sie hier mehr über dieses Dateiformat. |
| [WMZ](/viewer/python-net/groupdocs.viewer/filetype/wmz/) | Compressed Windows Metafile (.wmz) stellt das Microsoft Windows Metafile (WMF) dar, das in einem GZIP‑Archiv komprimiert ist – zum Speichern von Vektor‑ sowie Bitmap‑Bilddaten. Erfahren Sie hier mehr über dieses Dateiformat. |
| [EMF](/viewer/python-net/groupdocs.viewer/filetype/emf/) | Enhanced Windows Metafile (.emf) stellt grafische Bilder geräteunabhängig dar. EMF‑Metadateien bestehen aus variablen Längerecords in chronologischer Reihenfolge, die das gespeicherte Bild nach dem Parsen auf jedem Ausgabegerät rendern können. Erfahren Sie hier mehr über dieses Dateiformat. |
| [EMZ](/viewer/python-net/groupdocs.viewer/filetype/emz/) | Enhanced Windows Metafile compressed (.emz) stellt grafische Bilder geräteunabhängig dar, die mit GZIP komprimiert wurden. EMF‑Metadateien bestehen aus variablen Längerecords in chronologischer Reihenfolge, die das gespeicherte Bild nach dem Parsen auf jedem Ausgabegerät rendern können. Erfahren Sie hier mehr über dieses Dateiformat. |
| [WEBP](/viewer/python-net/groupdocs.viewer/filetype/webp/) | WebP-Bild (.webp) ist ein modernes Raster-Webbilddateiformat, das auf verlustfreier und verlustbehafteter Kompression basiert. Es bietet dieselbe Bildqualität bei gleichzeitig erheblicher Reduzierung der Dateigröße. Erfahren Sie hier mehr über dieses Dateiformat. |
| [DNG](/viewer/python-net/groupdocs.viewer/filetype/dng/) | Digital Negative Specification (.dng) ist ein digitales Kamerabildformat, das zur Speicherung von Rohdateien verwendet wird. Es wurde von Adobe im September 2004 entwickelt. Es wurde im Wesentlichen für die digitale Fotografie entwickelt. Erfahren Sie hier mehr über dieses Dateiformat. |
| [CDR](/viewer/python-net/groupdocs.viewer/filetype/cdr/) | CorelDraw Vector Graphic Drawing (.cdr) ist eine Vektorgrafik‑Datei, die nativ mit CorelDRAW erstellt wird, um digitale Bilder zu speichern, die kodiert und komprimiert sind. Eine solche Zeichnungsdatei enthält Text, Linien, Formen, Bilder, Farben und Effekte für die Vektor‑Darstellung von Bildinhalten. Erfahren Sie hier mehr über dieses Dateiformat. |
| [CMX](/viewer/python-net/groupdocs.viewer/filetype/cmx/) | Corel Exchange (.cmx) ist eine Zeichenbilddatei, die sowohl Vektorgrafiken als auch Bitmap‑Grafiken enthalten kann. Erfahren Sie hier mehr über dieses Dateiformat. |
| [DJVU](/viewer/python-net/groupdocs.viewer/filetype/djvu/) | DjVu Image (.djvu) ist ein Grafikdateiformat, das für gescannte Dokumente und Bücher gedacht ist, insbesondere für solche, die eine Kombination aus Text, Zeichnungen, Bildern und Fotografien enthalten. Erfahren Sie hier mehr über dieses Dateiformat. |
| [CGM](/viewer/python-net/groupdocs.viewer/filetype/cgm/) | Computer Graphics Metafile (.cgm) ist ein kostenloses, plattformunabhängiges, internationaler Standard‑Metadateiformat zum Speichern und Austauschen von Vektorgrafiken (2D), Rastergrafiken und Text. CGM verwendet einen objektorientierten Ansatz und zahlreiche Funktionsbereitstellungen für die Bildproduktion. Erfahren Sie hier mehr über dieses Dateiformat. |
| [PCL](/viewer/python-net/groupdocs.viewer/filetype/pcl/) | Printer Command Language Dokument (.pcl) |
| [PSD](/viewer/python-net/groupdocs.viewer/filetype/psd/) | Adobe Photoshop Document (.psd) stellt das native Dateiformat von Adobe Photoshop dar, das für Grafikdesign und -entwicklung verwendet wird. Erfahren Sie hier mehr über dieses Dateiformat. |
| [PSB](/viewer/python-net/groupdocs.viewer/filetype/psb/) | Photoshop Large Document Format (.psb) stellt das Photoshop Large Document Format dar, das für Grafikdesign und -entwicklung verwendet wird. Erfahren Sie hier mehr über dieses Dateiformat. |
| [DCM](/viewer/python-net/groupdocs.viewer/filetype/dcm/) | DICOM Image (.dcm) stellt ein digitales Bild dar, das medizinische Informationen von Patienten wie MRTs, CT‑Scans und Ultraschallbilder speichert. Erfahren Sie hier mehr über dieses Dateiformat. |
| [PS](/viewer/python-net/groupdocs.viewer/filetype/ps/) | PostScript Datei (.ps) |
| [EPS](/viewer/python-net/groupdocs.viewer/filetype/eps/) | Encapsulated PostScript File (.eps) beschreibt ein Encapsulated‑PostScript‑Programm, das das Aussehen einer einzelnen Seite definiert. Erfahren Sie hier mehr über dieses Dateiformat. |
| [ODG](/viewer/python-net/groupdocs.viewer/filetype/odg/) | OpenDocument Graphic File (.odg) wird von der Draw‑Anwendung von Apache OpenOffice verwendet, um Zeichnungselemente als Vektorbilder zu speichern. Erfahren Sie hier mehr über dieses Dateiformat. |
| [FODG](/viewer/python-net/groupdocs.viewer/filetype/fodg/) | Flat XML ODF Template (.fodg) wird von der Draw‑Anwendung von Apache OpenOffice verwendet, um Zeichnungselemente als Vektorbilder zu speichern. Erfahren Sie hier mehr über dieses Dateiformat. |
| [SVG](/viewer/python-net/groupdocs.viewer/filetype/svg/) | Scalable Vector Graphics File (.svg) ist eine Scalable Vector Graphics‑Datei, die ein XML‑basiertes Textformat verwendet, um das Aussehen eines Bildes zu beschreiben. Erfahren Sie hier mehr über dieses Dateiformat. |
| [SVGZ](/viewer/python-net/groupdocs.viewer/filetype/svgz/) | Scalable Vector Graphics File (.svgz) ist eine Scalable Vector Graphics‑Datei, die ein XML‑basiertes Textformat verwendet und zur Beschreibung des Bildaussehens mit GZIP komprimiert ist. Erfahren Sie hier mehr über dieses Dateiformat. |
| [OTG](/viewer/python-net/groupdocs.viewer/filetype/otg/) | OpenDocument Graphic Template (.otg) |
| [HTM](/viewer/python-net/groupdocs.viewer/filetype/htm/) | Hypertext Markup Language Datei (.htm) ist die Erweiterung für Webseiten, die zur Anzeige in Browsern erstellt wurden. Erfahren Sie hier mehr über dieses Dateiformat. |
| [HTML](/viewer/python-net/groupdocs.viewer/filetype/html/) | Hypertext Markup Language Datei (.html) ist die Erweiterung für Webseiten, die zur Anzeige in Browsern erstellt wurden. Erfahren Sie hier mehr über dieses Dateiformat. |
| [MHT](/viewer/python-net/groupdocs.viewer/filetype/mht/) | MHTML-Webarchiv (.mht) |
| [MHTML](/viewer/python-net/groupdocs.viewer/filetype/mhtml/) | MIME HTML Datei (.mhtml) |
| [XML](/viewer/python-net/groupdocs.viewer/filetype/xml/) | XML Datei (.xml). GroupDocs.Viewer verfügt über einen speziellen Prozessor zur Verarbeitung von XML-Dateien, siehe Dokumentation. |
| [ONE](/viewer/python-net/groupdocs.viewer/filetype/one/) | OneNote-Dokument (.one) wird von der Microsoft OneNote‑Anwendung erstellt. OneNote ermöglicht es Ihnen, Informationen zu sammeln, als würden Sie Ihr Notizblock zum Notieren verwenden. Erfahren Sie hier mehr über dieses Dateiformat. |
| [PDF](/viewer/python-net/groupdocs.viewer/filetype/pdf/) | Portable Document Format Datei (.pdf) ist ein Dokumenttyp, der von Adobe in den 1990er‑Jahren erstellt wurde. Der Zweck dieses Dateiformats war es, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einem Format einzuführen, das unabhängig von Anwendungssoftware, Hardware sowie Betriebssystem ist. Erfahren Sie hier mehr über dieses Dateiformat. |
| [XPS](/viewer/python-net/groupdocs.viewer/filetype/xps/) | XML Paper Specification Datei (.xps) stellt Seitenlayout‑Dateien dar, die auf von Microsoft erstellten XML Paper Specifications basieren. Dieses Format wurde von Microsoft als Ersatz für das EMF‑Dateiformat entwickelt und ist dem PDF‑Dateiformat ähnlich, verwendet jedoch XML für Layout, Aussehen und Druckinformationen eines Dokuments. Erfahren Sie hier mehr über dieses Dateiformat. |
| [OXPS](/viewer/python-net/groupdocs.viewer/filetype/oxps/) | OpenXPS Datei (.oxps) |
| [TEX](/viewer/python-net/groupdocs.viewer/filetype/tex/) | LaTeX-Quellendokument (.tex) ist eine Sprache, die Programmier‑ und Auszeichnungsfunktionen kombiniert und zum Satz von Dokumenten verwendet wird. Erfahren Sie hier mehr über dieses Dateiformat. |
| [OFD](/viewer/python-net/groupdocs.viewer/filetype/ofd/) | Das Open Fixed‑layout Document (OFD) Format, definiert durch GB/T 33190‑2016, zielt darauf ab, PDF in chinesischen öffentlichen Institutionen zu ersetzen. |
| [PPT](/viewer/python-net/groupdocs.viewer/filetype/ppt/) | PowerPoint‑Präsentation (.ppt) stellt eine PowerPoint‑Datei dar, die aus einer Sammlung von Folien für die Anzeige als Diashow besteht. Sie definiert das binäre Dateiformat, das von Microsoft PowerPoint 97‑2003 verwendet wird. Erfahren Sie hier mehr über dieses Dateiformat. |
| [PPTX](/viewer/python-net/groupdocs.viewer/filetype/pptx/) | PowerPoint Open XML Präsentation (.pptx) sind Präsentationsdateien, die mit der beliebten Microsoft PowerPoint‑Anwendung erstellt werden. Im Gegensatz zur vorherigen, binären PPT‑Version basiert das PPTX‑Format auf dem offenen XML‑Präsentationsdateiformat von Microsoft PowerPoint. Erfahren Sie hier mehr über dieses Dateiformat. |
| [PPS](/viewer/python-net/groupdocs.viewer/filetype/pps/) | PowerPoint‑Diashow (.pps) wird mit Microsoft PowerPoint für Diashow‑Zwecke erstellt. Das Lesen und Erstellen von PPS‑Dateien wird von Microsoft PowerPoint 97‑2003 unterstützt. Erfahren Sie hier mehr über dieses Dateiformat. |
| [PPSX](/viewer/python-net/groupdocs.viewer/filetype/ppsx/) | PowerPoint Open XML Diashow (.ppsx) Dateien werden mit Microsoft PowerPoint 2007 und höher für Diashow‑Zwecke erstellt. Erfahren Sie hier mehr über dieses Dateiformat. |
| [ODP](/viewer/python-net/groupdocs.viewer/filetype/odp/) | OpenDocument‑Präsentation (.odp) stellt das von OpenOffice.org im OASIS‑Open‑Standard verwendete Präsentationsdateiformat dar. Erfahren Sie hier mehr über dieses Dateiformat. |
| [FODP](/viewer/python-net/groupdocs.viewer/filetype/fodp/) | OpenDocument‑Präsentation (.fodp) stellt die OpenDocument Flat XML Präsentation dar. Erfahren Sie hier mehr über dieses Dateiformat. |
| [POT](/viewer/python-net/groupdocs.viewer/filetype/pot/) | PowerPoint-Vorlage (.pot) stellt Microsoft PowerPoint-Vorlagendateien dar, die von PowerPoint‑Versionen 97‑2003 erstellt wurden. Erfahren Sie hier mehr über dieses Dateiformat. |
| [PPTM](/viewer/python-net/groupdocs.viewer/filetype/pptm/) | PowerPoint Open XML Makro‑aktivierte Präsentation sind makroaktivierte Präsentationsdateien, die mit Microsoft PowerPoint 2007 oder neueren Versionen erstellt werden. Erfahren Sie hier mehr über dieses Dateiformat. |
| [POTX](/viewer/python-net/groupdocs.viewer/filetype/potx/) | PowerPoint Open XML Präsentationsvorlage (.potx) stellt Microsoft PowerPoint‑Vortragsvorlagen dar, die mit Microsoft PowerPoint 2007 und neueren Versionen erstellt werden. Erfahren Sie hier mehr über dieses Dateiformat. |
| [POTM](/viewer/python-net/groupdocs.viewer/filetype/potm/) | PowerPoint Open XML Makro‑aktivierte Präsentationsvorlage (.potm) sind Microsoft PowerPoint‑Vorlagendateien mit Makrounterstützung. POTM‑Dateien werden mit PowerPoint 2007 oder höher erstellt und enthalten Standardeinstellungen, die zur Erstellung weiterer Präsentationsdateien verwendet werden können. Erfahren Sie hier mehr über dieses Dateiformat. |
| [PPSM](/viewer/python-net/groupdocs.viewer/filetype/ppsm/) | PowerPoint Open XML Makro‑aktivierte Folie (.ppsm) stellt ein makroaktiviertes Diashow‑Dateiformat dar, das mit Microsoft PowerPoint 2007 oder höher erstellt wurde. Erfahren Sie hier mehr über dieses Dateiformat. |
| [OTP](/viewer/python-net/groupdocs.viewer/filetype/otp/) | OpenDocument Präsentationsvorlage (.otp) stellt Präsentationsvorlagendateien dar, die von Anwendungen im OASIS OpenDocument‑Standardformat erstellt werden. Erfahren Sie hier mehr über dieses Dateiformat. |
| [XLS](/viewer/python-net/groupdocs.viewer/filetype/xls/) | Excel‑Tabellendokument (.xls) stellt das Excel‑Binärdateiformat dar. Solche Dateien können mit Microsoft Excel sowie anderen ähnlichen Tabellenkalkulationsprogrammen wie OpenOffice Calc oder Apple Numbers erstellt werden. Erfahren Sie hier mehr über dieses Dateiformat. |
| [EXCEL_2003XML](/viewer/python-net/groupdocs.viewer/filetype/excel_2003xml/) | Excel 2003 XML (SpreadsheetML) stellt das Excel‑Binärdateiformat dar. Solche Dateien können mit Microsoft Excel sowie anderen ähnlichen Tabellenkalkulationsprogrammen wie OpenOffice Calc oder Apple Numbers erstellt werden. Erfahren Sie hier mehr über dieses Dateiformat. |
| [NUMBERS](/viewer/python-net/groupdocs.viewer/filetype/numbers/) | Apple Numbers stellt ein Excel‑ähnliches Binärdateiformat dar. Solche Dateien können mit der Apple Numbers‑Anwendung erstellt werden. Erfahren Sie hier mehr über dieses Dateiformat. |
| [XLSX](/viewer/python-net/groupdocs.viewer/filetype/xlsx/) | Microsoft Excel Open XML Tabellenkalkulation (.xlsx) ist ein bekanntes Format für Microsoft Excel‑Dokumente, das von Microsoft mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde. Erfahren Sie hier mehr über dieses Dateiformat. |
| [XLSM](/viewer/python-net/groupdocs.viewer/filetype/xlsm/) | Excel Open XML Makro‑aktivierte Tabellenkalkulation (.xlsm) ist ein Typ von Tabellenkalkulationsdateien, die Makros unterstützen. Erfahren Sie hier mehr über dieses Dateiformat. |
| [XLSB](/viewer/python-net/groupdocs.viewer/filetype/xlsb/) | Excel Binäre Tabellenkalkulation (.xlsb) definiert das Excel‑Binärdateiformat, das eine Sammlung von Datensätzen und Strukturen enthält, die den Inhalt von Excel‑Arbeitsmappen festlegen. Erfahren Sie hier mehr über dieses Dateiformat. |
| [CSV](/viewer/python-net/groupdocs.viewer/filetype/csv/) | Kommagetrennte Werte‑Datei (.csv) stellt Textdateien dar, die Datensätze mit durch Kommas getrennten Werten enthalten. Erfahren Sie hier mehr über dieses Dateiformat. |
| [TSV](/viewer/python-net/groupdocs.viewer/filetype/tsv/) | Tabulatorgetrennte Werte‑Datei (.tsv) stellt Daten dar, die in einem Klartextformat durch Tabulatoren getrennt sind. Erfahren Sie hier mehr über dieses Dateiformat. |
| [ODS](/viewer/python-net/groupdocs.viewer/filetype/ods/) | OpenDocument Tabellenkalkulation (.ods) steht für das OpenDocument‑Tabellenkalkulationsformat, das vom Benutzer bearbeitet werden kann. Daten werden in der ODF‑Datei in Zeilen und Spalten gespeichert. Erfahren Sie hier mehr über dieses Dateiformat. |
| [FODS](/viewer/python-net/groupdocs.viewer/filetype/fods/) | OpenDocument Flat XML Tabellenkalkulation (.fods) |
| [OTS](/viewer/python-net/groupdocs.viewer/filetype/ots/) | OpenDocument Tabellenkalkulationsvorlage (.ots) |
| [XLAM](/viewer/python-net/groupdocs.viewer/filetype/xlam/) | Microsoft Excel Add‑In (.xlam) |
| [XLTM](/viewer/python-net/groupdocs.viewer/filetype/xltm/) | Microsoft Excel Makro‑aktivierte Vorlage (.xltm) stellt Dateien dar, die von Microsoft Excel als makroaktivierte Vorlagendateien erzeugt werden. XLTM‑Dateien sind in ihrer Struktur XLTX‑Dateien ähnlich, abgesehen davon, dass Letztere keine Vorlagendateien mit Makros unterstützen. Erfahren Sie hier mehr über dieses Dateiformat. |
| [XLT](/viewer/python-net/groupdocs.viewer/filetype/xlt/) | Microsoft Excel Vorlage (.xlt) sind Vorlagendateien, die mit Microsoft Excel erstellt werden, einer Tabellenkalkulationsanwendung, die Teil der Microsoft Office‑Suite ist. Microsoft Office 97‑2003 unterstützte das Erstellen neuer XLT‑Dateien sowie das Öffnen dieser. Erfahren Sie hier mehr über dieses Dateiformat. |
| [XLTX](/viewer/python-net/groupdocs.viewer/filetype/xltx/) | Excel Open‑XML‑Tabellenvorlage (.xltx) stellt eine Microsoft Excel‑Vorlage dar, die auf den Office‑OpenXML‑Dateiformatspezifikationen basiert. Sie wird verwendet, um eine Standardvorlagendatei zu erstellen, die zur Erzeugung von XLSX‑Dateien genutzt werden kann, die dieselben Einstellungen wie in der XLTX‑Datei aufweisen. Erfahren Sie hier mehr über dieses Dateiformat. |
| [SXC](/viewer/python-net/groupdocs.viewer/filetype/sxc/) | StarOffice Calc Tabellenkalkulation (.sxc) |
| [MPP](/viewer/python-net/groupdocs.viewer/filetype/mpp/) | Microsoft Project‑Datei (.mpp) ist eine Microsoft Project‑Datendatei, die Informationen zum Projektmanagement integriert speichert. Erfahren Sie hier mehr über dieses Dateiformat. |
| [MPT](/viewer/python-net/groupdocs.viewer/filetype/mpt/) | Microsoft Project‑Vorlage (.mpt) enthält grundlegende Informationen und Strukturen sowie Dokumenteinstellungen für die Erstellung von .MPP‑Dateien. Erfahren Sie hier mehr über dieses Dateiformat. |
| [MPX](/viewer/python-net/groupdocs.viewer/filetype/mpx/) | Microsoft Project Exchange‑Datei (.mpx) ist ein ASCII‑Dateiformat zum Austausch von Projektinformationen zwischen Microsoft Project (MSP) und anderen Anwendungen, die das MPX‑Dateiformat unterstützen, wie Primavera Project Planner, Sciforma und Timerline Precision Estimating. Erfahren Sie hier mehr über dieses Dateiformat. |
| [AS_](/viewer/python-net/groupdocs.viewer/filetype/as_/) | ActionScript‑Datei (.as) |
| [AS3](/viewer/python-net/groupdocs.viewer/filetype/as3/) | ActionScript‑Datei (.as) |
| [ASM](/viewer/python-net/groupdocs.viewer/filetype/asm/) | Assembler‑Quellcode‑Datei (.asm) |
| [BAT](/viewer/python-net/groupdocs.viewer/filetype/bat/) | DOS‑Batchdatei (.bat) |
| [C](/viewer/python-net/groupdocs.viewer/filetype/c/) | C/C++‑Quellcode‑Datei (.c) |
| [CC](/viewer/python-net/groupdocs.viewer/filetype/cc/) | C++‑Quellcode‑Datei (.cc) |
| [CMAKE](/viewer/python-net/groupdocs.viewer/filetype/cmake/) | CMake‑Datei (.cmake) |
| [CPP](/viewer/python-net/groupdocs.viewer/filetype/cpp/) | C++‑Quellcode‑Datei (.cpp) |
| [CS](/viewer/python-net/groupdocs.viewer/filetype/cs/) | C#‑Quellcode‑Datei (.cs) ist eine Quellcodedatei für die Programmiersprache C#. Sie wurde von Microsoft für die Verwendung mit dem .NET‑Framework eingeführt. Erfahren Sie hier mehr über dieses Dateiformat. |
| [VB](/viewer/python-net/groupdocs.viewer/filetype/vb/) | Visual‑Basic‑Projekt‑Item‑Datei (.vb) ist eine Quellcodedatei, die in der Programmiersprache Visual Basic erstellt wurde und von Microsoft für die Entwicklung von .NET‑Anwendungen bereitgestellt wird. Erfahren Sie hier mehr über dieses Dateiformat. |
| [CSS](/viewer/python-net/groupdocs.viewer/filetype/css/) | Cascading Style Sheet (.css) |
| [CXX](/viewer/python-net/groupdocs.viewer/filetype/cxx/) | C++‑Quellcode‑Datei (.cxx) |
| [DIFF](/viewer/python-net/groupdocs.viewer/filetype/diff/) | Patch‑Datei (.diff) |
| [ERB](/viewer/python-net/groupdocs.viewer/filetype/erb/) | Ruby‑ERB‑Skript (.erb) |
| [GROOVY](/viewer/python-net/groupdocs.viewer/filetype/groovy/) | Groovy‑Quellcode‑Datei (.groovy) |
| [H](/viewer/python-net/groupdocs.viewer/filetype/h/) | C/C++/Objective‑C‑Header‑Datei (.h) |
| [HAML](/viewer/python-net/groupdocs.viewer/filetype/haml/) | Haml‑Quellcode‑Datei (.haml) |
| [HH](/viewer/python-net/groupdocs.viewer/filetype/hh/) | C++‑Header‑Datei (.hh) |
| [JAVA](/viewer/python-net/groupdocs.viewer/filetype/java/) | Java‑Quellcode‑Datei (.java) |
| [JS](/viewer/python-net/groupdocs.viewer/filetype/js/) | JavaScript-Datei (.js) |
| [JSON](/viewer/python-net/groupdocs.viewer/filetype/json/) | JavaScript Object Notation-Datei (.json) |
| [LESS](/viewer/python-net/groupdocs.viewer/filetype/less/) | LESS-Stylesheet (.less) |
| [LOG](/viewer/python-net/groupdocs.viewer/filetype/log/) | Logdatei (.log) |
| [M](/viewer/python-net/groupdocs.viewer/filetype/m/) | Objective-C-Implementierungsdatei (.m) |
| [MAKE](/viewer/python-net/groupdocs.viewer/filetype/make/) | Xcode-Makefile-Skript (.make) |
| [MD](/viewer/python-net/groupdocs.viewer/filetype/md/) | Markdown-Dokumentationsdatei (.md) |
| [ML](/viewer/python-net/groupdocs.viewer/filetype/ml/) | ML-Quellcode-Datei (.ml) |
| [MM](/viewer/python-net/groupdocs.viewer/filetype/mm/) | Objective-C++-Quelldatei (.mm) |
| [PHP](/viewer/python-net/groupdocs.viewer/filetype/php/) | PHP-Quellcode-Datei (.php) |
| [PL](/viewer/python-net/groupdocs.viewer/filetype/pl/) | Perl-Skript (.pl) |
| [PROPERTIES](/viewer/python-net/groupdocs.viewer/filetype/properties/) | Java-Properties-Datei (.properties) |
| [PY](/viewer/python-net/groupdocs.viewer/filetype/py/) | Python-Skript (.py) |
| [RB](/viewer/python-net/groupdocs.viewer/filetype/rb/) | Ruby-Quellcode (.rb) |
| [RST](/viewer/python-net/groupdocs.viewer/filetype/rst/) | reStructuredText-Datei (.rst) |
| [SASS](/viewer/python-net/groupdocs.viewer/filetype/sass/) | Syntactically Awesome StyleSheets-Datei (.sass) |
| [SCALA](/viewer/python-net/groupdocs.viewer/filetype/scala/) | Scala-Quellcode-Datei (.scala) |
| [SCM](/viewer/python-net/groupdocs.viewer/filetype/scm/) | Scheme-Quellcode-Datei (.scm) |
| [SCRIPT](/viewer/python-net/groupdocs.viewer/filetype/script/) | Generische Skriptdatei (.script) |
| [SH](/viewer/python-net/groupdocs.viewer/filetype/sh/) | Bash-Shell-Skript (.sh) |
| [SML](/viewer/python-net/groupdocs.viewer/filetype/sml/) | Standard-ML-Quellcode-Datei (.sml) |
| [SQL](/viewer/python-net/groupdocs.viewer/filetype/sql/) | Structured Query Language-Datendatei (.sql) |
| [VIM](/viewer/python-net/groupdocs.viewer/filetype/vim/) | Vim-Einstellungsdatei (.vim) |
| [YAML](/viewer/python-net/groupdocs.viewer/filetype/yaml/) | YAML-Dokument (.yaml) |
| [DOC](/viewer/python-net/groupdocs.viewer/filetype/doc/) | Microsoft Word-Dokument (.doc) stellt Dokumente dar, die von Microsoft Word oder anderen Textverarbeitungsprogrammen im Binärdateiformat erzeugt werden. Erfahren Sie hier mehr über dieses Dateiformat. |
| [DOCX](/viewer/python-net/groupdocs.viewer/filetype/docx/) | Microsoft Word Open XML Document (.docx) ist ein bekanntes Format für Microsoft Word‑Dokumente. Eingeführt ab 2007 mit der Veröffentlichung von Microsoft Office 2007, wurde die Struktur dieses neuen Dokumentformats von reinem Binärformat zu einer Kombination aus XML‑ und Binärdateien geändert. Erfahren Sie hier mehr über dieses Dateiformat. |
| [CHM](/viewer/python-net/groupdocs.viewer/filetype/chm/) | Microsoft Compiled HTML Help File (.chm) ist ein bekanntes Format für HELP‑ (Dokumentation zu einer Anwendung) Dokumente. Erfahren Sie hier mehr über dieses Dateiformat. |
| [DOCM](/viewer/python-net/groupdocs.viewer/filetype/docm/) | Word Open XML Macro-Enabled Document (.docm) ist ein mit Microsoft Word 2007 oder höher erstelltes Dokument mit der Möglichkeit, Makros auszuführen. Erfahren Sie hier mehr über dieses Dateiformat. |
| [DOT](/viewer/python-net/groupdocs.viewer/filetype/dot/) | Word Document Template (.dot) sind Vorlagendateien, die von Microsoft Word erstellt werden, um vordefinierte Einstellungen für die Erstellung weiterer DOC‑ oder DOCX‑Dateien zu besitzen. Erfahren Sie hier mehr über dieses Dateiformat. |
| [DOTX](/viewer/python-net/groupdocs.viewer/filetype/dotx/) | Word Open XML Document Template (.dotx) sind Vorlagendateien, die von Microsoft Word erstellt werden, um vordefinierte Einstellungen für die Erstellung weiterer DOCX‑Dateien zu besitzen. Erfahren Sie hier mehr über dieses Dateiformat. |
| [DOTM](/viewer/python-net/groupdocs.viewer/filetype/dotm/) | Word Open XML Macro-Enabled Document Template (.dotm) stellt eine Vorlagendatei dar, die mit Microsoft Word 2007 oder höher erstellt wurde. Erfahren Sie hier mehr über dieses Dateiformat. |
| [RTF](/viewer/python-net/groupdocs.viewer/filetype/rtf/) | Rich Text Format File (.rtf) stellt eine Methode zur Kodierung von formatiertem Text und Grafiken für die Verwendung in Anwendungen dar. Erfahren Sie hier mehr über dieses Dateiformat. |
| [TXT](/viewer/python-net/groupdocs.viewer/filetype/txt/) | Plain Text File (.txt) stellt ein Textdokument dar, das reinen Text in Form von Zeilen enthält. Erfahren Sie hier mehr über dieses Dateiformat. |
| [ODT](/viewer/python-net/groupdocs.viewer/filetype/odt/) | OpenDocument Text Document (.odt) ist eine Art von Dokumenten, die mit Textverarbeitungsprogrammen erstellt werden und auf dem OpenDocument‑Textdateiformat basieren. Erfahren Sie hier mehr über dieses Dateiformat. |
| [OTT](/viewer/python-net/groupdocs.viewer/filetype/ott/) | OpenDocument Document Template (.ott) stellt Vorlagendokumente dar, die von Anwendungen erzeugt werden und dem OASIS‑OpenDocument‑Standardformat entsprechen. Erfahren Sie hier mehr über dieses Dateiformat. |
| [VCF](/viewer/python-net/groupdocs.viewer/filetype/vcf/) | vCard File (.vcf) ist ein digitales Dateiformat zur Speicherung von Kontaktinformationen. Das Format wird häufig für den Datenaustausch zwischen gängigen Informationsaustausch‑Anwendungen verwendet. Erfahren Sie hier mehr über dieses Dateiformat. |
| [AI](/viewer/python-net/groupdocs.viewer/filetype/ai/) | Adobe Illustrator (.ai) ist ein Dateiformat für Adobe‑Illustrator‑Zeichnungen. Erfahren Sie hier mehr über dieses Dateiformat. |
| [PSM1](/viewer/python-net/groupdocs.viewer/filetype/psm1/) | PowerShell script module (.psm1) ist ein Dateiformat für PowerShell‑Modul‑Skripte. Erfahren Sie hier mehr über dieses Dateiformat. |
| [PS1](/viewer/python-net/groupdocs.viewer/filetype/ps1/) | PowerShell script file (.ps1) ist ein Dateiformat für Windows PowerShell‑Cmdlet‑Dateien. Erfahren Sie hier mehr über dieses Dateiformat. |
| [PSD1](/viewer/python-net/groupdocs.viewer/filetype/psd1/) | PowerShell script module manifest (.psd1) ist ein Dateiformat für PowerShell‑Modul‑Manifest‑Skripte. Erfahren Sie hier mehr über dieses Dateiformat. |

### Beispiel

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

# Geben Sie beim Laden des Dokuments den Dateityp an (z. B. Markdown).
load_options = LoadOptions(FileType.MD)

# Rendern Sie das Dokument zu PDF.
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### Siehe auch
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
