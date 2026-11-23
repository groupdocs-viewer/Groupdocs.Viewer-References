---
title: "classe FileType"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Représente un type de fichier et fournit des méthodes pour obtenir la liste de tous les types de fichiers pris en charge par GroupDocs.Viewer."
type: docs
url: /fr/python-net/groupdocs.viewer/filetype/
is_root: false
weight: 10
---


## FileType class

Représente un type de fichier et fournit des méthodes pour obtenir la liste de tous les types de fichiers pris en charge par GroupDocs.Viewer.

Le type FileType expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/) | Initialise une nouvelle instance de [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/). |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/#file_format-extension) | Initialise une nouvelle instance de FileType. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#file_path) | Détecte l'encodage des fichiers texte TXT, TSV et CSV par chemin. |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#stream) | Tente de détecter l'encodage des fichiers texte (TXT, TSV, CSV) à partir d'un flux. |
| [detect_encoding_file](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_file/) |  |
| [detect_encoding_stream](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_stream/) |  |
| [detect_encoding_streams](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_streams/) |  |
| [detect_encoding_string](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_string/) |  |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#other) | Détermine si le [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) actuel est identique au [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) spécifié. |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#obj) | Détermine si le [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) actuel est identique à l'objet spécifié. |
| [equals_file_type](/viewer/python-net/groupdocs.viewer/filetype/equals_file_type/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer/filetype/equals_object/) |  |
| [from_extension](/viewer/python-net/groupdocs.viewer/filetype/from_extension/#extension) | Mappe l'extension de fichier au type de fichier. |
| [from_file_path](/viewer/python-net/groupdocs.viewer/filetype/from_file_path/#file_path) | Extrait l'extension de fichier et la mappe à un type de fichier. |
| [from_media_type](/viewer/python-net/groupdocs.viewer/filetype/from_media_type/#media_type) | Mappe un type de média de fichier à un [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) (par ex., 'application/pdf' est mappé à [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)). |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream) | Détecte le type de fichier en lisant la signature du fichier. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password) | Détecte le type de fichier en lisant la signature du fichier. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-logger) | Détecte le type de fichier en lisant la signature du fichier. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password-logger) | Détecte le type de fichier en lisant la signature du fichier. |
| [from_stream_file](/viewer/python-net/groupdocs.viewer/filetype/from_stream_file/) |  |
| [from_stream_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream_stream/) |  |
| [from_stream_streams](/viewer/python-net/groupdocs.viewer/filetype/from_stream_streams/) |  |
| [from_stream_string](/viewer/python-net/groupdocs.viewer/filetype/from_stream_string/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer/filetype/get_hash_code/) | Renvoie le code de hachage de l'objet [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) actuel. |
| [get_supported_file_types](/viewer/python-net/groupdocs.viewer/filetype/get_supported_file_types/) | Récupère les types de fichiers pris en charge. |
| [to_string](/viewer/python-net/groupdocs.viewer/filetype/to_string/) | Renvoie un str qui représente l'objet actuel. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [extension](/viewer/python-net/groupdocs.viewer/filetype/extension/) | Le suffixe du nom de fichier (y compris le point \".\") par ex. \".doc\". |
| [file_format](/viewer/python-net/groupdocs.viewer/filetype/file_format/) | Le nom du type de fichier, par ex. \"Microsoft Word Document\". |

### Champs
| Champ | Description |
| :- | :- |
| [UNKNOWN](/viewer/python-net/groupdocs.viewer/filetype/unknown/) | Représente un type de fichier inconnu. |
| [ZIP](/viewer/python-net/groupdocs.viewer/filetype/zip/) | Le fichier compressé (.zip) représente des archives pouvant contenir un ou plusieurs fichiers ou répertoires. En savoir plus sur ce format de fichier ici. |
| [TAR](/viewer/python-net/groupdocs.viewer/filetype/tar/) | Consolidated Unix File Archive (.tar) sont des archives créées avec un utilitaire Unix pour regrouper un ou plusieurs fichiers. En savoir plus sur ce format de fichier ici. |
| [XZ](/viewer/python-net/groupdocs.viewer/filetype/xz/) | Le fichier XZ (.xz) est une archive compressée avec un algorithme de compression à haut ratio basé sur l'algorithme LZMA. En savoir plus sur ce format de fichier ici. |
| [TXZ](/viewer/python-net/groupdocs.viewer/filetype/txz/) | Consolidated Unix File Archive (.txz, .tar.xz) sont des archives créées avec un utilitaire Unix pour regrouper un ou plusieurs fichiers. En savoir plus sur ce format de fichier ici. |
| [TARXZ](/viewer/python-net/groupdocs.viewer/filetype/tarxz/) | Consolidated Unix File Archive (.txz, .tar.xz) sont des archives créées avec un utilitaire Unix pour regrouper un ou plusieurs fichiers. En savoir plus sur ce format de fichier ici. |
| [TGZ](/viewer/python-net/groupdocs.viewer/filetype/tgz/) | Consolidated Unix File Archive (.tgz, .tar.gz) sont des archives créées avec un utilitaire Unix pour regrouper un ou plusieurs fichiers. En savoir plus sur ce format de fichier ici. |
| [TARGZ](/viewer/python-net/groupdocs.viewer/filetype/targz/) | Consolidated Unix File Archive (.tgz, .tar.gz) sont des archives créées avec un utilitaire Unix pour regrouper un ou plusieurs fichiers. En savoir plus sur ce format de fichier ici. |
| [BZ2](/viewer/python-net/groupdocs.viewer/filetype/bz2/) | Le fichier compressé Bzip2 (.bz2) est un fichier compressé généré à l'aide de la méthode de compression open source BZIP2, principalement sur les systèmes UNIX ou Linux. En savoir plus sur ce format de fichier ici. |
| [RAR](/viewer/python-net/groupdocs.viewer/filetype/rar/) | Roshal ARchive (.rar) sont des fichiers compressés générés à l'aide de la méthode de compression RAR (WINRAR). En savoir plus sur ce format de fichier ici. |
| [GZ](/viewer/python-net/groupdocs.viewer/filetype/gz/) | Gnu Zipped File (.gz) sont des fichiers compressés créés avec l'application de compression gzip. Ils peuvent contenir plusieurs fichiers compressés et sont couramment utilisés sur les systèmes UNIX et Linux. En savoir plus sur ce format de fichier ici. |
| [GZIP](/viewer/python-net/groupdocs.viewer/filetype/gzip/) | Gnu Zipped File (.gzip) a été introduit comme un utilitaire gratuit pour remplacer le programme Compress utilisé dans les systèmes Unix. Ces fichiers peuvent être ouverts et extraits avec plusieurs applications telles que WinZip, disponible à la fois sur Windows et macOS. En savoir plus sur ce format de fichier ici. |
| [SEVEN_ZIP](/viewer/python-net/groupdocs.viewer/filetype/seven_zip/) | 7Zip (.7z, .7zip) est un archivage gratuit et open source avec compression LZMA et LZMA2. En savoir plus sur ce format de fichier ici. |
| [CPIO](/viewer/python-net/groupdocs.viewer/filetype/cpio/) | Cpio est un utilitaire d'archivage de fichiers général et son format de fichier associé. Il est principalement installé sur les systèmes d'exploitation informatiques de type Unix. En savoir plus sur ce format de fichier ici. |
| [ZSTANDARD](/viewer/python-net/groupdocs.viewer/filetype/zstandard/) | Le fichier ZST est un fichier compressé généré avec l'algorithme de compression Zstandard (zstd). Il s'agit d'un fichier compressé créé avec une compression sans perte par cet algorithme. Les fichiers ZST peuvent être utilisés pour compresser différents types de fichiers tels que les bases de données, les systèmes de fichiers, les réseaux et les jeux. En savoir plus sur ce format de fichier ici. |
| [TZST](/viewer/python-net/groupdocs.viewer/filetype/tzst/) | Les fichiers TZST (.tar.zst, .tzst) sont des archives Zstandard (ZST), qui contiennent en interne une Archive de fichiers Unix consolidée (Tar), créée avec un utilitaire basé sur Unix pour rassembler un ou plusieurs fichiers. |
| [TAR_ZST](/viewer/python-net/groupdocs.viewer/filetype/tar_zst/) | Les fichiers TZST (.tar.zst, .tzst) sont des archives Zstandard (ZST), qui contiennent en interne une Archive de fichiers Unix consolidée (Tar), créée avec un utilitaire basé sur Unix pour rassembler un ou plusieurs fichiers. |
| [ISO](/viewer/python-net/groupdocs.viewer/filetype/iso/) | L'image de disque optique ISO est un fichier d'image disque d'archive non compressé qui représente le contenu complet d'un disque optique tel qu'un CD ou un DVD, basé sur la norme ISO-9660. En savoir plus sur ce format de fichier ici. |
| [LHA](/viewer/python-net/groupdocs.viewer/filetype/lha/) | LHA ou LZH est un utilitaire de compression gratuit et son format de fichier associé. En savoir plus sur ce format de fichier ici. |
| [CAB](/viewer/python-net/groupdocs.viewer/filetype/cab/) | Cabinet (ou CAB) est un format de fichier d'archive pour Microsoft Windows. En savoir plus sur ce format de fichier ici. |
| [DXF](/viewer/python-net/groupdocs.viewer/filetype/dxf/) | Drawing Exchange Format File (.dxf) est une représentation de données balisées d'un fichier de dessin AutoCAD. En savoir plus sur ce format de fichier ici. |
| [DWG](/viewer/python-net/groupdocs.viewer/filetype/dwg/) | AutoCAD Drawing Database File (.dwg) représente des fichiers binaires propriétaires utilisés pour contenir des données de conception 2D et 3D. Comme le DXF, qui sont des fichiers ASCII, le DWG représente le format de fichier binaire pour les dessins CAO (Conception Assistée par Ordinateur). En savoir plus sur ce format de fichier ici. |
| [DWT](/viewer/python-net/groupdocs.viewer/filetype/dwt/) | AutoCAD Drawing Template (.dwt) est un fichier de modèle de dessin AutoCAD utilisé comme point de départ pour créer des dessins qui peuvent être enregistrés au format DWG. En savoir plus sur ce format de fichier ici. |
| [STL](/viewer/python-net/groupdocs.viewer/filetype/stl/) | Stereolithography File (.stl) est un format de fichier interchangeable qui représente la géométrie de surface tridimensionnelle. Ce format de fichier est utilisé dans plusieurs domaines tels que le prototypage rapide, l'impression 3D et la fabrication assistée par ordinateur. En savoir plus sur ce format de fichier ici. |
| [IFC](/viewer/python-net/groupdocs.viewer/filetype/ifc/) | Industry Foundation Classes File (.ifc) est un format de fichier qui établit des normes internationales pour l'importation et l'exportation d'objets de construction et de leurs propriétés. Ce format de fichier assure l'interopérabilité entre différentes applications logicielles. En savoir plus sur ce format de fichier ici. |
| [DWF](/viewer/python-net/groupdocs.viewer/filetype/dwf/) | Design Web Format File (.dwf) représente des dessins 2D/3D au format compressé pour la visualisation, la révision ou l'impression de fichiers de conception. Il contient des graphiques et du texte faisant partie des données de conception et réduit la taille du fichier grâce à son format compressé. En savoir plus sur ce format de fichier ici. |
| [FBX](/viewer/python-net/groupdocs.viewer/filetype/fbx/) | Autodesk FBX Interchange File (FilmBoX) (.fbx) représente un format de modèle 3D. En savoir plus sur ce format de fichier ici. |
| [DWFX](/viewer/python-net/groupdocs.viewer/filetype/dwfx/) | Design Web Format File XPS (.dwfx) représente des dessins 2D/3D sous forme de document XPS au format compressé pour la visualisation, la révision ou l'impression de fichiers de conception. Il contient des graphiques et du texte faisant partie des données de conception et réduit la taille du fichier grâce à son format compressé. En savoir plus sur ce format de fichier ici. |
| [DGN](/viewer/python-net/groupdocs.viewer/filetype/dgn/) | MicroStation Design File (.dgn) sont des dessins créés et pris en charge par des applications CAO telles que MicroStation et Intergraph Interactive Graphics Design System. En savoir plus sur ce format de fichier ici. |
| [PLT](/viewer/python-net/groupdocs.viewer/filetype/plt/) | PLT (HPGL) (.plt) est un fichier traceur vectoriel introduit par Autodesk, Inc. et contient des informations pour un certain fichier CAO. Les détails du traçage nécessitent précision et exactitude en production, et l’utilisation du fichier PLT garantit cela car toutes les images sont imprimées à l’aide de lignes plutôt que de points. En savoir plus sur ce format de fichier ici. |
| [CF2](/viewer/python-net/groupdocs.viewer/filetype/cf2/) | Fichier de format de fichier commun En savoir plus sur ce format de fichier ici. |
| [OBJ](/viewer/python-net/groupdocs.viewer/filetype/obj/) | Wavefront 3D Object File (.obj) est un fichier image 3D introduit par Wavefront Technologies. En savoir plus sur ce format de fichier ici. |
| [HPG](/viewer/python-net/groupdocs.viewer/filetype/hpg/) | PLT (HPGL) (.hpg) |
| [IGS](/viewer/python-net/groupdocs.viewer/filetype/igs/) | Initial Graphics Exchange Specification (IGES) (.igs) |
| [VSD](/viewer/python-net/groupdocs.viewer/filetype/vsd/) | Visio Drawing File (.vsd) sont des dessins créés avec l’application Microsoft Visio pour représenter une variété d’objets graphiques et leurs interconnexions. En savoir plus sur ce format de fichier ici. |
| [VSDX](/viewer/python-net/groupdocs.viewer/filetype/vsdx/) | Visio Drawing (.vsdx) représente le format de fichier Microsoft Visio introduit à partir de Microsoft Office 2013. Il a été développé pour remplacer le format de fichier binaire, .VSD, qui est pris en charge par les versions antérieures de Microsoft Visio. En savoir plus sur ce format de fichier ici. |
| [VSS](/viewer/python-net/groupdocs.viewer/filetype/vss/) | Visio Stencil File(.vss) sont des fichiers gabarit créés avec Microsoft Visio 2007 et antérieurs. Les fichiers gabarit fournissent des objets de dessin qui peuvent être inclus dans un dessin Visio .VSD. En savoir plus sur ce format de fichier ici. |
| [VSSX](/viewer/python-net/groupdocs.viewer/filetype/vssx/) | Visio Stencil File (.vssx) sont des gabarits de dessin créés avec Microsoft Visio 2013 et versions ultérieures. Le format de fichier VSSX peut être ouvert avec Visio 2013 et versions ultérieures. Les fichiers Visio sont connus pour la représentation d’une variété d’éléments de dessin tels que des collections de formes, des connecteurs, des organigrammes, des agencements réseau, des diagrammes UML, En savoir plus sur ce format de fichier ici. |
| [VSDM](/viewer/python-net/groupdocs.viewer/filetype/vsdm/) | Visio Macro-Enabled Drawing (.vsdm) sont des fichiers de dessin créés avec l’application Microsoft Visio qui prend en charge les macros. Les fichiers VSDM sont des dessins OPC/XML similaires aux VSDX, mais offrent également la capacité d’exécuter des macros lorsque le fichier est ouvert. En savoir plus sur ce format de fichier ici. |
| [VST](/viewer/python-net/groupdocs.viewer/filetype/vst/) | Visio Drawing Template (.vst) sont des fichiers image vectoriels créés avec Microsoft Visio et servent de modèle pour créer d’autres fichiers. Ces fichiers modèle sont au format binaire et contiennent la mise en page et les paramètres par défaut utilisés pour la création de nouveaux dessins Visio. En savoir plus sur ce format de fichier ici. |
| [VSTX](/viewer/python-net/groupdocs.viewer/filetype/vstx/) | Visio Drawing Template (.vstx) sont des fichiers modèle de dessin créés avec Microsoft Visio 2013 et versions ultérieures. Ces fichiers VSTX offrent un point de départ pour créer des dessins Visio, enregistrés au format .VSDX, avec une mise en page et des paramètres par défaut. En savoir plus sur ce format de fichier ici. |
| [VSTM](/viewer/python-net/groupdocs.viewer/filetype/vstm/) | Visio Macro-Enabled Drawing Template (.vstm) sont des fichiers modèle créés avec Microsoft Visio qui prennent en charge les macros. Contrairement aux fichiers VSDX, les fichiers créés à partir de modèles VSTM peuvent exécuter des macros développées en code Visual Basic for Applications (VBA). En savoir plus sur ce format de fichier ici. |
| [VSSM](/viewer/python-net/groupdocs.viewer/filetype/vssm/) | Visio Macro-Enabled Stencil File (.vssm) sont des fichiers gabarit Microsoft Visio qui offrent la prise en charge des macros. Un fichier VSSM, lorsqu’il est ouvert, permet d’exécuter les macros afin d’obtenir le formatage et le placement souhaités des formes dans un diagramme. En savoir plus sur ce format de fichier ici. |
| [VSX](/viewer/python-net/groupdocs.viewer/filetype/vsx/) | Visio Stencil XML File (.vsx) fait référence aux gabarits qui comprennent des dessins et des formes utilisés pour créer des diagrammes dans Microsoft Visio. Les fichiers VSX sont enregistrés au format XML et étaient pris en charge jusqu’à Visio 2013. En savoir plus sur ce format de fichier ici. |
| [VTX](/viewer/python-net/groupdocs.viewer/filetype/vtx/) | Visio Template XML File (.vtx) est un modèle de dessin Microsoft Visio enregistré sur le disque au format XML. Ce modèle vise à fournir un fichier avec des paramètres de base pouvant être utilisés pour créer plusieurs fichiers Visio avec les mêmes paramètres. En savoir plus sur ce format de fichier ici. |
| [VDW](/viewer/python-net/groupdocs.viewer/filetype/vdw/) | Visio Web Drawing (.vdw) représente le format de fichier qui spécifie les flux et les stockages nécessaires au rendu d’un dessin Web. En savoir plus sur ce format de fichier ici. |
| [VDX](/viewer/python-net/groupdocs.viewer/filetype/vdx/) | Visio Drawing XML File (.vdx) représente tout dessin ou graphique créé dans Microsoft Visio, mais enregistré au format XML avec l’extension .VDX. Un fichier XML de dessin Visio est créé dans le logiciel Visio, développé par Microsoft. En savoir plus sur ce format de fichier ici. |
| [EPUB](/viewer/python-net/groupdocs.viewer/filetype/epub/) | Le fichier Open eBook (.epub) est un format de fichier e-book qui fournit un format de publication numérique standard pour les éditeurs et les consommateurs. Ce format est désormais si répandu qu'il est pris en charge par de nombreux lecteurs électroniques et applications logicielles. En savoir plus sur ce format de fichier ici. |
| [MOBI](/viewer/python-net/groupdocs.viewer/filetype/mobi/) | Le eBook Mobipocket (.mobi) est l'un des formats de fichier ebook les plus largement utilisés. Ce format est une amélioration du vieux format OEB (Open Ebook Format) et était utilisé comme format propriétaire pour le lecteur Mobipocket. En savoir plus sur ce format de fichier ici. |
| [AZW3](/viewer/python-net/groupdocs.viewer/filetype/azw3/) | Le ebook Amazon Kindle Format 8 (KF8) est le format de fichier numérique développé pour les appareils Amazon Kindle. Ce format est une amélioration des anciens fichiers AZW et est utilisé uniquement sur les appareils Kindle Fire avec une compatibilité descendante avec les formats de fichiers antérieurs, à savoir MOBI et AZW. En savoir plus sur ce format de fichier ici. |
| [MSG](/viewer/python-net/groupdocs.viewer/filetype/msg/) | Le message Outlook Mail (.msg) est un format de fichier utilisé par Microsoft Outlook et Exchange pour stocker les messages électroniques, les contacts, les rendez-vous ou d'autres tâches. En savoir plus sur ce format de fichier ici. |
| [EML](/viewer/python-net/groupdocs.viewer/filetype/eml/) | Le message E‑Mail (.eml) représente les messages électroniques enregistrés à l'aide d'Outlook et d'autres applications pertinentes. Presque tous les clients de messagerie prennent en charge ce format de fichier en raison de sa conformité à la norme RFC‑822 du format de message Internet. En savoir plus sur ce format de fichier ici. |
| [NSF](/viewer/python-net/groupdocs.viewer/filetype/nsf/) | Base de données Lotus Notes (.nsf) En savoir plus sur ce format de fichier ici. |
| [MBOX](/viewer/python-net/groupdocs.viewer/filetype/mbox/) | Fichier de boîte aux lettres e‑mail (.mbox) En savoir plus sur ce format de fichier ici. |
| [EMLX](/viewer/python-net/groupdocs.viewer/filetype/emlx/) | Le message Apple Mail (.emlx) est implémenté et développé par Apple. L'application Apple Mail utilise le format de fichier EMLX pour l'exportation des e‑mails. En savoir plus sur ce format de fichier ici. |
| [PST](/viewer/python-net/groupdocs.viewer/filetype/pst/) | Le fichier Outlook Personal Information Store (.pst) représente les fichiers de stockage personnel Outlook (également appelés Personal Storage Table) qui stockent diverses informations utilisateur. En savoir plus sur ce format de fichier ici. |
| [OST](/viewer/python-net/groupdocs.viewer/filetype/ost/) | Le fichier Outlook Offline Data (.ost) représente les données de boîte aux lettres de l'utilisateur en mode hors ligne sur la machine locale après l'enregistrement auprès du serveur Exchange via Microsoft Outlook. En savoir plus sur ce format de fichier ici. |
| [TIF](/viewer/python-net/groupdocs.viewer/filetype/tif/) | Le fichier Tagged Image (.tif) représente des images matricielles destinées à être utilisées sur une variété d'appareils compatibles avec cette norme de format de fichier. Il peut décrire des données d'image binaire, en niveaux de gris, à palette de couleurs et en couleur pleine dans plusieurs espaces colorimétriques. En savoir plus sur ce format de fichier ici. |
| [TIFF](/viewer/python-net/groupdocs.viewer/filetype/tiff/) | Le format Tagged Image File (.tiff) représente des images matricielles destinées à être utilisées sur une variété d'appareils compatibles avec cette norme de format de fichier. Il peut décrire des données d'image binaire, en niveaux de gris, à palette de couleurs et en couleur pleine dans plusieurs espaces colorimétriques. En savoir plus sur ce format de fichier ici. |
| [JPG](/viewer/python-net/groupdocs.viewer/filetype/jpg/) | L'image JPEG (.jpg) est un type de format d'image enregistré à l'aide d'une compression avec perte. L'image résultante, suite à la compression, représente un compromis entre la taille de stockage et la qualité de l'image. En savoir plus sur ce format de fichier ici. |
| [JPEG](/viewer/python-net/groupdocs.viewer/filetype/jpeg/) | L'image JPEG (.jpeg) est un type de format d'image enregistré à l'aide d'une compression avec perte. L'image résultante, suite à la compression, représente un compromis entre la taille de stockage et la qualité de l'image. En savoir plus sur ce format de fichier ici. |
| [JFIF](/viewer/python-net/groupdocs.viewer/filetype/jfif/) | Le format JPEG File Interchange (.jfif) est une image développée pour un échange rapide entre plateformes. Ce format utilise la compression JPEG. En savoir plus sur ce format de fichier ici. |
| [PNG](/viewer/python-net/groupdocs.viewer/filetype/png/) | Le Portable Network Graphic (.png) est un type de format de fichier image matricielle qui utilise une compression sans perte. Ce format a été créé comme remplacement du Graphics Interchange Format (GIF) et ne comporte aucune limitation de droits d'auteur. En savoir plus sur ce format de fichier ici. |
| [GIF](/viewer/python-net/groupdocs.viewer/filetype/gif/) | Le fichier Graphical Interchange Format (.gif) est un type d'image fortement compressée. Pour chaque image, le GIF permet généralement jusqu'à 8 bits par pixel et jusqu'à 256 couleurs sont autorisées sur l'image. En savoir plus sur ce format de fichier ici. |
| [APNG](/viewer/python-net/groupdocs.viewer/filetype/apng/) | Le Animated Portable Network Graphic (.apng) est une extension du format PNG qui prend en charge l'animation. En savoir plus sur ce format de fichier ici. |
| [BMP](/viewer/python-net/groupdocs.viewer/filetype/bmp/) | Le fichier image bitmap (.bmp) est utilisé pour stocker des images numériques bitmap. Ces images sont indépendantes de l'adaptateur graphique et sont également appelées format de fichier bitmap indépendant du dispositif (DIB). En savoir plus sur ce format de fichier ici. |
| [TGA](/viewer/python-net/groupdocs.viewer/filetype/tga/) | Le Truevision TGA (Truevision Advanced Raster Adapter - TARGA) est utilisé pour stocker des images numériques bitmap développées par TRUEVISION. En savoir plus sur ce format de fichier ici. |
| [ICO](/viewer/python-net/groupdocs.viewer/filetype/ico/) | Le fichier icône (.ico) est un type de fichier image utilisé comme icône pour représenter une application sur Microsoft Windows. En savoir plus sur ce format de fichier ici. |
| [JP2](/viewer/python-net/groupdocs.viewer/filetype/jp2/) | Le fichier image principal JPEG 2000 (.jp2) est un système de codage d'image et une norme de compression d'image de pointe. En savoir plus sur ce format de fichier ici. |
| [JPF](/viewer/python-net/groupdocs.viewer/filetype/jpf/) | Fichier image JPEG 2000 (.jpf) |
| [JPX](/viewer/python-net/groupdocs.viewer/filetype/jpx/) | Fichier image JPEG 2000 (.jpx) |
| [JPM](/viewer/python-net/groupdocs.viewer/filetype/jpm/) | Fichier image JPEG 2000 (.jpm) |
| [J2C](/viewer/python-net/groupdocs.viewer/filetype/j2c/) | Flux de code JPEG 2000 (.j2c) |
| [J2K](/viewer/python-net/groupdocs.viewer/filetype/j2k/) | Le flux de code JPEG 2000 (.j2k) est une image compressée en utilisant la compression par ondelettes au lieu de la compression DCT. En savoir plus sur ce format de fichier ici. |
| [JPC](/viewer/python-net/groupdocs.viewer/filetype/jpc/) | Flux de code JPEG 2000 (.jpc) |
| [JLS](/viewer/python-net/groupdocs.viewer/filetype/jls/) | JPEG-LS (JLS) (.jls) |
| [DIB](/viewer/python-net/groupdocs.viewer/filetype/dib/) | Fichier bitmap indépendant du dispositif (.dib) |
| [WMF](/viewer/python-net/groupdocs.viewer/filetype/wmf/) | Le Windows Metafile (.wmf) représente le Microsoft Windows Metafile (WMF) pour le stockage de données d'images vectorielles ainsi que bitmap. En savoir plus sur ce format de fichier ici. |
| [WMZ](/viewer/python-net/groupdocs.viewer/filetype/wmz/) | Le Windows Metafile compressé (.wmz) représente le Microsoft Windows Metafile (WMF) compressé en archive GZIP - pour le stockage de données d'images vectorielles ainsi que bitmap. En savoir plus sur ce format de fichier ici. |
| [EMF](/viewer/python-net/groupdocs.viewer/filetype/emf/) | Le Enhanced Windows Metafile (.emf) représente des images graphiques de manière indépendante du dispositif. Les métafichiers EMF comprennent des enregistrements de longueur variable dans l'ordre chronologique qui peuvent rendre l'image stockée après analyse sur n'importe quel dispositif de sortie. En savoir plus sur ce format de fichier ici. |
| [EMZ](/viewer/python-net/groupdocs.viewer/filetype/emz/) | Le Enhanced Windows Metafile compressé (.emz) représente des images graphiques de manière indépendante du dispositif, compressées par GZIP. Les métafichiers EMF comprennent des enregistrements de longueur variable dans l'ordre chronologique qui peuvent rendre l'image stockée après analyse sur n'importe quel dispositif de sortie. En savoir plus sur ce format de fichier ici. |
| [WEBP](/viewer/python-net/groupdocs.viewer/filetype/webp/) | L'image WebP (.webp) est un format de fichier d'image raster web moderne basé sur la compression sans perte et avec perte. Elle offre la même qualité d'image tout en réduisant considérablement la taille de l'image. En savoir plus sur ce format de fichier ici. |
| [DNG](/viewer/python-net/groupdocs.viewer/filetype/dng/) | La spécification Digital Negative (.dng) est un format d'image de caméra numérique utilisé pour le stockage de fichiers RAW. Elle a été développée par Adobe en septembre 2004. Elle a été essentiellement développée pour la photographie numérique. En savoir plus sur ce format de fichier ici. |
| [CDR](/viewer/python-net/groupdocs.viewer/filetype/cdr/) | Le dessin graphique vectoriel CorelDraw (.cdr) est un fichier d'image vectorielle créé nativement avec CorelDRAW pour le stockage d'images numériques encodées et compressées. Un tel fichier de dessin contient du texte, des lignes, des formes, des images, des couleurs et des effets pour la représentation vectorielle du contenu de l'image. En savoir plus sur ce format de fichier ici. |
| [CMX](/viewer/python-net/groupdocs.viewer/filetype/cmx/) | Le Corel Exchange (.cmx) est un fichier d'image de dessin qui peut contenir des graphiques vectoriels ainsi que des graphiques bitmap. En savoir plus sur ce format de fichier ici. |
| [DJVU](/viewer/python-net/groupdocs.viewer/filetype/djvu/) | L'image DjVu (.djvu) est un format de fichier graphique destiné aux documents et livres numérisés, en particulier ceux qui contiennent une combinaison de texte, dessins, images et photographies. En savoir plus sur ce format de fichier ici. |
| [CGM](/viewer/python-net/groupdocs.viewer/filetype/cgm/) | Le Metafile de graphisme informatique (.cgm) est un format de métafile gratuit, indépendant de la plateforme, norme internationale pour le stockage et l'échange de graphiques vectoriels (2D), graphiques raster et texte. CGM utilise une approche orientée objet et de nombreuses fonctions pour la production d'images. En savoir plus sur ce format de fichier ici. |
| [PCL](/viewer/python-net/groupdocs.viewer/filetype/pcl/) | Document Printer Command Language (.pcl) |
| [PSD](/viewer/python-net/groupdocs.viewer/filetype/psd/) | Le document Adobe Photoshop (.psd) représente le format de fichier natif d'Adobe Photoshop utilisé pour la conception et le développement graphiques. En savoir plus sur ce format de fichier ici. |
| [PSB](/viewer/python-net/groupdocs.viewer/filetype/psb/) | Le format de document Photoshop Large (.psb) représente le Photoshop Large Document Format utilisé pour la conception et le développement graphiques. En savoir plus sur ce format de fichier ici. |
| [DCM](/viewer/python-net/groupdocs.viewer/filetype/dcm/) | L'image DICOM (.dcm) représente une image numérique qui stocke les informations médicales des patients telles que les IRM, les scanners CT et les images d'échographie. En savoir plus sur ce format de fichier ici. |
| [PS](/viewer/python-net/groupdocs.viewer/filetype/ps/) | Fichier PostScript (.ps) |
| [EPS](/viewer/python-net/groupdocs.viewer/filetype/eps/) | Le fichier Encapsulated PostScript (.eps) décrit un programme de langage Encapsulated PostScript qui définit l'apparence d'une seule page. En savoir plus sur ce format de fichier ici. |
| [ODG](/viewer/python-net/groupdocs.viewer/filetype/odg/) | Le fichier OpenDocument Graphic (.odg) est utilisé par l'application Draw d'Apache OpenOffice pour stocker les éléments de dessin sous forme d'image vectorielle. En savoir plus sur ce format de fichier ici. |
| [FODG](/viewer/python-net/groupdocs.viewer/filetype/fodg/) | Le modèle Flat XML ODF (.fodg) est utilisé par l'application Draw d'Apache OpenOffice pour stocker les éléments de dessin sous forme d'image vectorielle. En savoir plus sur ce format de fichier ici. |
| [SVG](/viewer/python-net/groupdocs.viewer/filetype/svg/) | Le fichier Scalable Vector Graphics (.svg) est un fichier Scalable Vector Graphics qui utilise un format texte basé sur XML pour décrire l'apparence d'une image. En savoir plus sur ce format de fichier ici. |
| [SVGZ](/viewer/python-net/groupdocs.viewer/filetype/svgz/) | Le fichier Scalable Vector Graphics (.svgz) est un fichier Scalable Vector Graphics qui utilise un format texte basé sur XML, compressé par GZIP, pour décrire l'apparence d'une image. En savoir plus sur ce format de fichier ici. |
| [OTG](/viewer/python-net/groupdocs.viewer/filetype/otg/) | Modèle OpenDocument Graphic (.otg) |
| [HTM](/viewer/python-net/groupdocs.viewer/filetype/htm/) | Le fichier Hypertext Markup Language (.htm) est l'extension des pages web créées pour être affichées dans les navigateurs. En savoir plus sur ce format de fichier ici. |
| [HTML](/viewer/python-net/groupdocs.viewer/filetype/html/) | Le fichier Hypertext Markup Language (.html) est l'extension des pages web créées pour être affichées dans les navigateurs. En savoir plus sur ce format de fichier ici. |
| [MHT](/viewer/python-net/groupdocs.viewer/filetype/mht/) | Archive Web MHTML (.mht) |
| [MHTML](/viewer/python-net/groupdocs.viewer/filetype/mhtml/) | Fichier MIME HTML (.mhtml) |
| [XML](/viewer/python-net/groupdocs.viewer/filetype/xml/) | Fichier XML (.xml). GroupDocs.Viewer possède un processeur spécial pour gérer les fichiers XML, voir la documentation. |
| [ONE](/viewer/python-net/groupdocs.viewer/filetype/one/) | Le document OneNote (.one) est créé par l'application Microsoft OneNote. OneNote vous permet de rassembler des informations en utilisant l'application comme si vous utilisiez votre carnet de brouillon pour prendre des notes. En savoir plus sur ce format de fichier ici. |
| [PDF](/viewer/python-net/groupdocs.viewer/filetype/pdf/) | Le fichier Portable Document Format (.pdf) est un type de document créé par Adobe dans les années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et d'autres supports de référence dans un format indépendant des logiciels d'application, du matériel ainsi que du système d'exploitation. En savoir plus sur ce format de fichier ici. |
| [XPS](/viewer/python-net/groupdocs.viewer/filetype/xps/) | Le fichier XML Paper Specification (.xps) représente des fichiers de mise en page basés sur les spécifications XML Paper créées par Microsoft. Ce format a été développé par Microsoft comme remplacement du format de fichier EMF et est similaire au format PDF, mais utilise XML pour la mise en page, l'apparence et les informations d'impression d'un document. En savoir plus sur ce format de fichier ici. |
| [OXPS](/viewer/python-net/groupdocs.viewer/filetype/oxps/) | Fichier OpenXPS (.oxps) |
| [TEX](/viewer/python-net/groupdocs.viewer/filetype/tex/) | Le document source LaTeX (.tex) est un langage qui comprend des fonctionnalités de programmation ainsi que de balisage, utilisé pour la composition de documents. En savoir plus sur ce format de fichier ici. |
| [OFD](/viewer/python-net/groupdocs.viewer/filetype/ofd/) | Le format Open Fixed-layout Document (OFD) défini par GB/T 33190-2016 vise à remplacer le PDF dans les institutions publiques chinoises. |
| [PPT](/viewer/python-net/groupdocs.viewer/filetype/ppt/) | La présentation PowerPoint (.ppt) représente un fichier PowerPoint qui consiste en une collection de diapositives à afficher en diaporama. Elle spécifie le format de fichier binaire utilisé par Microsoft PowerPoint 97-2003. En savoir plus sur ce format de fichier ici. |
| [PPTX](/viewer/python-net/groupdocs.viewer/filetype/pptx/) | Les présentations PowerPoint Open XML (.pptx) sont des fichiers de présentation créés avec l'application Microsoft PowerPoint populaire. Contrairement à la version précédente du format de fichier de présentation PPT qui était binaire, le format PPTX est basé sur le format de fichier de présentation Open XML de Microsoft PowerPoint. En savoir plus sur ce format de fichier ici. |
| [PPS](/viewer/python-net/groupdocs.viewer/filetype/pps/) | Le diaporama PowerPoint (.pps) est créé à l'aide de Microsoft PowerPoint à des fins de présentation. La lecture et la création de fichiers PPS sont prises en charge par Microsoft PowerPoint 97-2003. En savoir plus sur ce format de fichier ici. |
| [PPSX](/viewer/python-net/groupdocs.viewer/filetype/ppsx/) | Les fichiers diaporama PowerPoint Open XML (.ppsx) sont créés avec Microsoft PowerPoint 2007 et versions ultérieures à des fins de présentation. En savoir plus sur ce format de fichier ici. |
| [ODP](/viewer/python-net/groupdocs.viewer/filetype/odp/) | La présentation OpenDocument (.odp) représente le format de fichier de présentation utilisé par OpenOffice.org dans la norme OASISOpen. En savoir plus sur ce format de fichier ici. |
| [FODP](/viewer/python-net/groupdocs.viewer/filetype/fodp/) | La présentation OpenDocument (.fodp) représente la présentation OpenDocument Flat XML. En savoir plus sur ce format de fichier ici. |
| [POT](/viewer/python-net/groupdocs.viewer/filetype/pot/) | Le modèle PowerPoint (.pot) représente les fichiers de modèle Microsoft PowerPoint créés par les versions PowerPoint 97-2003. En savoir plus sur ce format de fichier ici. |
| [PPTM](/viewer/python-net/groupdocs.viewer/filetype/pptm/) | PowerPoint Open XML Macro-Enabled Presentation sont des fichiers de présentation avec macros créés avec Microsoft PowerPoint 2007 ou des versions ultérieures. En savoir plus sur ce format de fichier ici. |
| [POTX](/viewer/python-net/groupdocs.viewer/filetype/potx/) | PowerPoint Open XML Presentation Template (.potx) représente les présentations modèles Microsoft PowerPoint créées avec Microsoft PowerPoint 2007 et versions ultérieures. En savoir plus sur ce format de fichier ici. |
| [POTM](/viewer/python-net/groupdocs.viewer/filetype/potm/) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) sont des fichiers de modèle Microsoft PowerPoint avec prise en charge des macros. Les fichiers POTM sont créés avec PowerPoint 2007 ou ultérieur et contiennent des paramètres par défaut pouvant être utilisés pour créer d’autres fichiers de présentation. En savoir plus sur ce format de fichier ici. |
| [PPSM](/viewer/python-net/groupdocs.viewer/filetype/ppsm/) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) représente le format de fichier diaporama avec macros créé avec Microsoft PowerPoint 2007 ou version ultérieure. En savoir plus sur ce format de fichier ici. |
| [OTP](/viewer/python-net/groupdocs.viewer/filetype/otp/) | OpenDocument Presentation Template (.otp) représente les fichiers de modèle de présentation créés par des applications au format standard OASIS OpenDocument. En savoir plus sur ce format de fichier ici. |
| [XLS](/viewer/python-net/groupdocs.viewer/filetype/xls/) | Excel Spreadsheet (.xls) représente le format de fichier binaire Excel. De tels fichiers peuvent être créés par Microsoft Excel ainsi que par d’autres programmes de tableur similaires tels qu’OpenOffice Calc ou Apple Numbers. En savoir plus sur ce format de fichier ici. |
| [EXCEL_2003XML](/viewer/python-net/groupdocs.viewer/filetype/excel_2003xml/) | Excel 2003 XML (SpreadsheetML) représente le format de fichier binaire Excel. De tels fichiers peuvent être créés par Microsoft Excel ainsi que par d’autres programmes de tableur similaires tels qu’OpenOffice Calc ou Apple Numbers. En savoir plus sur ce format de fichier ici. |
| [NUMBERS](/viewer/python-net/groupdocs.viewer/filetype/numbers/) | Apple Numbers représente un format de fichier binaire similaire à Excel. De tels fichiers peuvent être créés par l’application Apple Numbers. En savoir plus sur ce format de fichier ici. |
| [XLSX](/viewer/python-net/groupdocs.viewer/filetype/xlsx/) | Microsoft Excel Open XML Spreadsheet (.xlsx) est un format bien connu pour les documents Microsoft Excel, introduit par Microsoft avec la sortie de Microsoft Office 2007. En savoir plus sur ce format de fichier ici. |
| [XLSM](/viewer/python-net/groupdocs.viewer/filetype/xlsm/) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) est un type de fichier tableur qui prend en charge les macros. En savoir plus sur ce format de fichier ici. |
| [XLSB](/viewer/python-net/groupdocs.viewer/filetype/xlsb/) | Excel Binary Spreadsheet (.xlsb) spécifie le format de fichier binaire Excel, qui est une collection d’enregistrements et de structures définissant le contenu d’un classeur Excel. En savoir plus sur ce format de fichier ici. |
| [CSV](/viewer/python-net/groupdocs.viewer/filetype/csv/) | Comma Separated Values File (.csv) représente des fichiers texte simples contenant des enregistrements de données avec des valeurs séparées par des virgules. En savoir plus sur ce format de fichier ici. |
| [TSV](/viewer/python-net/groupdocs.viewer/filetype/tsv/) | Tab Separated Values File (.tsv) représente des données séparées par des tabulations dans un format texte simple. En savoir plus sur ce format de fichier ici. |
| [ODS](/viewer/python-net/groupdocs.viewer/filetype/ods/) | OpenDocument Spreadsheet (.ods) désigne le format de document tableur OpenDocument, modifiable par l’utilisateur. Les données sont stockées dans le fichier ODF sous forme de lignes et de colonnes. En savoir plus sur ce format de fichier ici. |
| [FODS](/viewer/python-net/groupdocs.viewer/filetype/fods/) | OpenDocument Flat XML Spreadsheet (.fods) |
| [OTS](/viewer/python-net/groupdocs.viewer/filetype/ots/) | OpenDocument Spreadsheet Template (.ots) |
| [XLAM](/viewer/python-net/groupdocs.viewer/filetype/xlam/) | Microsoft Excel Add-in (.xlam) |
| [XLTM](/viewer/python-net/groupdocs.viewer/filetype/xltm/) | Microsoft Excel Macro-Enabled Template (.xltm) représente les fichiers générés par Microsoft Excel en tant que modèles avec macros. Les fichiers XLTM sont similaires aux XLTX sur le plan de la structure, à la différence que ces derniers ne prennent pas en charge la création de modèles avec macros. En savoir plus sur ce format de fichier ici. |
| [XLT](/viewer/python-net/groupdocs.viewer/filetype/xlt/) | Microsoft Excel Template (.xlt) sont des fichiers modèle créés avec Microsoft Excel, une application de tableur faisant partie de la suite Microsoft Office. Microsoft Office 97-2003 permettait de créer de nouveaux fichiers XLT ainsi que de les ouvrir. En savoir plus sur ce format de fichier ici. |
| [XLTX](/viewer/python-net/groupdocs.viewer/filetype/xltx/) | Excel Open XML Spreadsheet Template (.xltx) représente le modèle Microsoft Excel basé sur les spécifications du format de fichier Office OpenXML. Il est utilisé pour créer un fichier modèle standard pouvant être utilisé pour générer des fichiers XLSX présentant les mêmes paramètres que ceux spécifiés dans le fichier XLTX. En savoir plus sur ce format de fichier ici. |
| [SXC](/viewer/python-net/groupdocs.viewer/filetype/sxc/) | StarOffice Calc Spreadsheet (.sxc) |
| [MPP](/viewer/python-net/groupdocs.viewer/filetype/mpp/) | Le fichier Microsoft Project (.mpp) est un fichier de données Microsoft Project qui stocke les informations liées à la gestion de projet de manière intégrée. En savoir plus sur ce format de fichier ici. |
| [MPT](/viewer/python-net/groupdocs.viewer/filetype/mpt/) | Le modèle Microsoft Project (.mpt) contient des informations de base et une structure ainsi que les paramètres du document pour créer des fichiers .MPP. En savoir plus sur ce format de fichier ici. |
| [MPX](/viewer/python-net/groupdocs.viewer/filetype/mpx/) | Le fichier d’échange Microsoft Project (.mpx) est un format de fichier ASCII pour le transfert d’informations de projet entre Microsoft Project (MSP) et d’autres applications qui prennent en charge le format de fichier MPX telles que Primavera Project Planner, Sciforma et Timerline Precision Estimating. En savoir plus sur ce format de fichier ici. |
| [AS_](/viewer/python-net/groupdocs.viewer/filetype/as_/) | Fichier ActionScript (.as) |
| [AS3](/viewer/python-net/groupdocs.viewer/filetype/as3/) | Fichier ActionScript (.as) |
| [ASM](/viewer/python-net/groupdocs.viewer/filetype/asm/) | Fichier de code source en langage d'assemblage (.asm) |
| [BAT](/viewer/python-net/groupdocs.viewer/filetype/bat/) | Fichier batch DOS (.bat) |
| [C](/viewer/python-net/groupdocs.viewer/filetype/c/) | Fichier de code source C/C++ (.c) |
| [CC](/viewer/python-net/groupdocs.viewer/filetype/cc/) | Fichier de code source C++ (.cc) |
| [CMAKE](/viewer/python-net/groupdocs.viewer/filetype/cmake/) | Fichier CMake (.cmake) |
| [CPP](/viewer/python-net/groupdocs.viewer/filetype/cpp/) | Fichier de code source C++ (.cpp) |
| [CS](/viewer/python-net/groupdocs.viewer/filetype/cs/) | Le fichier de code source C# (.cs) est un fichier de code source pour le langage de programmation C#. Introduit par Microsoft pour une utilisation avec le .NET Framework. En savoir plus sur ce format de fichier ici. |
| [VB](/viewer/python-net/groupdocs.viewer/filetype/vb/) | Le fichier d'élément de projet Visual Basic (.vb) est un fichier de code source créé en langage Visual Basic, développé par Microsoft pour la création d'applications .NET. En savoir plus sur ce format de fichier ici. |
| [CSS](/viewer/python-net/groupdocs.viewer/filetype/css/) | Feuille de style en cascade (.css) |
| [CXX](/viewer/python-net/groupdocs.viewer/filetype/cxx/) | Fichier de code source C++ (.cxx) |
| [DIFF](/viewer/python-net/groupdocs.viewer/filetype/diff/) | Fichier de correctif (.diff) |
| [ERB](/viewer/python-net/groupdocs.viewer/filetype/erb/) | Script Ruby ERB (.erb) |
| [GROOVY](/viewer/python-net/groupdocs.viewer/filetype/groovy/) | Fichier de code source Groovy (.groovy) |
| [H](/viewer/python-net/groupdocs.viewer/filetype/h/) | Fichier d’en-tête C/C++/Objective-C (.h) |
| [HAML](/viewer/python-net/groupdocs.viewer/filetype/haml/) | Fichier de code source Haml (.haml) |
| [HH](/viewer/python-net/groupdocs.viewer/filetype/hh/) | Fichier d’en-tête C++ (.hh) |
| [JAVA](/viewer/python-net/groupdocs.viewer/filetype/java/) | Fichier de code source Java (.java) |
| [JS](/viewer/python-net/groupdocs.viewer/filetype/js/) | Fichier JavaScript (.js) |
| [JSON](/viewer/python-net/groupdocs.viewer/filetype/json/) | Fichier JavaScript Object Notation (.json) |
| [LESS](/viewer/python-net/groupdocs.viewer/filetype/less/) | Feuille de style LESS (.less) |
| [LOG](/viewer/python-net/groupdocs.viewer/filetype/log/) | Fichier journal (.log) |
| [M](/viewer/python-net/groupdocs.viewer/filetype/m/) | Fichier d'implémentation Objective-C (.m) |
| [MAKE](/viewer/python-net/groupdocs.viewer/filetype/make/) | Script Makefile Xcode (.make) |
| [MD](/viewer/python-net/groupdocs.viewer/filetype/md/) | Fichier de documentation Markdown (.md) |
| [ML](/viewer/python-net/groupdocs.viewer/filetype/ml/) | Fichier de code source ML (.ml) |
| [MM](/viewer/python-net/groupdocs.viewer/filetype/mm/) | Fichier source Objective-C++ (.mm) |
| [PHP](/viewer/python-net/groupdocs.viewer/filetype/php/) | Fichier de code source PHP (.php) |
| [PL](/viewer/python-net/groupdocs.viewer/filetype/pl/) | Script Perl (.pl) |
| [PROPERTIES](/viewer/python-net/groupdocs.viewer/filetype/properties/) | Fichier de propriétés Java (.properties) |
| [PY](/viewer/python-net/groupdocs.viewer/filetype/py/) | Script Python (.py) |
| [RB](/viewer/python-net/groupdocs.viewer/filetype/rb/) | Fichier de code source Ruby (.rb) |
| [RST](/viewer/python-net/groupdocs.viewer/filetype/rst/) | Fichier reStructuredText (.rst) |
| [SASS](/viewer/python-net/groupdocs.viewer/filetype/sass/) | Fichier Syntactically Awesome StyleSheets (.sass) |
| [SCALA](/viewer/python-net/groupdocs.viewer/filetype/scala/) | Fichier de code source Scala (.scala) |
| [SCM](/viewer/python-net/groupdocs.viewer/filetype/scm/) | Fichier de code source Scheme (.scm) |
| [SCRIPT](/viewer/python-net/groupdocs.viewer/filetype/script/) | Fichier de script générique (.script) |
| [SH](/viewer/python-net/groupdocs.viewer/filetype/sh/) | Script Bash Shell (.sh) |
| [SML](/viewer/python-net/groupdocs.viewer/filetype/sml/) | Fichier de code source Standard ML (.sml) |
| [SQL](/viewer/python-net/groupdocs.viewer/filetype/sql/) | Fichier de données Structured Query Language (.sql) |
| [VIM](/viewer/python-net/groupdocs.viewer/filetype/vim/) | Fichier de paramètres Vim (.vim) |
| [YAML](/viewer/python-net/groupdocs.viewer/filetype/yaml/) | Document YAML (.yaml) |
| [DOC](/viewer/python-net/groupdocs.viewer/filetype/doc/) | Le document Microsoft Word (.doc) représente les documents générés par Microsoft Word ou d'autres traitements de texte au format binaire. En savoir plus sur ce format de fichier ici. |
| [DOCX](/viewer/python-net/groupdocs.viewer/filetype/docx/) | Le document Microsoft Word Open XML (.docx) est un format bien connu pour les documents Microsoft Word. Introduit à partir de 2007 avec la sortie de Microsoft Office 2007, la structure de ce nouveau format de document est passée du binaire simple à une combinaison de fichiers XML et binaires. En savoir plus sur ce format de fichier ici. |
| [CHM](/viewer/python-net/groupdocs.viewer/filetype/chm/) | Le fichier d'aide Microsoft Compiled HTML (.chm) est un format bien connu pour les documents d'AIDE (documentation d'une application). En savoir plus sur ce format de fichier ici. |
| [DOCM](/viewer/python-net/groupdocs.viewer/filetype/docm/) | Le document Word Open XML avec macros activées (.docm) est un document généré par Microsoft Word 2007 ou version ultérieure, avec la capacité d'exécuter des macros. En savoir plus sur ce format de fichier ici. |
| [DOT](/viewer/python-net/groupdocs.viewer/filetype/dot/) | Les modèles de document Word (.dot) sont des fichiers modèles créés par Microsoft Word pour disposer de paramètres préformatés en vue de la génération de futurs fichiers DOC ou DOCX. En savoir plus sur ce format de fichier ici. |
| [DOTX](/viewer/python-net/groupdocs.viewer/filetype/dotx/) | Les modèles de documents Word Open XML (.dotx) sont des fichiers modèles créés par Microsoft Word pour disposer de paramètres préformatés en vue de la génération de futurs fichiers DOCX. En savoir plus sur ce format de fichier ici. |
| [DOTM](/viewer/python-net/groupdocs.viewer/filetype/dotm/) | Le modèle de document Word Open XML avec macros (.dotm) représente un fichier modèle créé avec Microsoft Word 2007 ou version ultérieure. En savoir plus sur ce format de fichier ici. |
| [RTF](/viewer/python-net/groupdocs.viewer/filetype/rtf/) | Le fichier Rich Text Format (.rtf) représente une méthode d'encodage de texte formaté et de graphiques pour une utilisation dans les applications. En savoir plus sur ce format de fichier ici. |
| [TXT](/viewer/python-net/groupdocs.viewer/filetype/txt/) | Le fichier texte brut (.txt) représente un document texte contenant du texte simple sous forme de lignes. En savoir plus sur ce format de fichier ici. |
| [ODT](/viewer/python-net/groupdocs.viewer/filetype/odt/) | Les documents OpenDocument Text (.odt) sont un type de documents créés avec des applications de traitement de texte basées sur le format de fichier OpenDocument Text. En savoir plus sur ce format de fichier ici. |
| [OTT](/viewer/python-net/groupdocs.viewer/filetype/ott/) | Le modèle de document OpenDocument (.ott) représente des documents modèles générés par des applications conformes au format standard OpenDocument de l'OASIS. En savoir plus sur ce format de fichier ici. |
| [VCF](/viewer/python-net/groupdocs.viewer/filetype/vcf/) | Le fichier vCard (.vcf) est un format de fichier numérique pour stocker des informations de contact. Ce format est largement utilisé pour l'échange de données entre les applications d'échange d'informations populaires. En savoir plus sur ce format de fichier ici. |
| [AI](/viewer/python-net/groupdocs.viewer/filetype/ai/) | Adobe Illustrator (.ai) est un format de fichier pour les dessins Adobe Illustrator. En savoir plus sur ce format de fichier ici. |
| [PSM1](/viewer/python-net/groupdocs.viewer/filetype/psm1/) | Le module de script PowerShell (.psm1) est un format de fichier pour les scripts de modules PowerShell. En savoir plus sur ce format de fichier ici. |
| [PS1](/viewer/python-net/groupdocs.viewer/filetype/ps1/) | Le fichier de script PowerShell (.ps1) est un format de fichier pour les fichiers Cmdlet Windows PowerShell. En savoir plus sur ce format de fichier ici. |
| [PSD1](/viewer/python-net/groupdocs.viewer/filetype/psd1/) | Le manifeste de module de script PowerShell (.psd1) est un format de fichier pour les scripts de manifeste de module PowerShell. En savoir plus sur ce format de fichier ici. |

### Exemple

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

# Spécifiez le type de fichier (par ex., Markdown) lors du chargement du document
load_options = LoadOptions(FileType.MD)

# Convertir le document en PDF
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### Voir aussi
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
