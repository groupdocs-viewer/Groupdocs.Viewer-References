---
title: "FileType"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Représente le type de fichier."
type: docs
weight: 14
url: /fr/java/com.groupdocs.viewer/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, com.groupdocs.viewer.caching.Cacheable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>, Cacheable
```

Représente le type de fichier. Fournit des méthodes pour obtenir une liste de tous les types de fichiers pris en charge par le composant GroupDocs.Viewer.


L'énumération FileType fournit des constantes représentant différents types de fichiers pris en charge par le composant GroupDocs.Viewer.
Vous pouvez utiliser les méthodes de cette énumération pour obtenir une liste de tous les types de fichiers pris en charge ou vérifier si un type de fichier spécifique est supporté.


Exemple d'utilisation :

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


## Champs

| Champ | Description |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | Représente un type de fichier inconnu. |
|
|  | [ZIP](#ZIP) | Représente un fichier compressé (.zip) pouvant contenir un ou plusieurs fichiers ou répertoires. |
|
|  | [TAR](#TAR) | Représente une archive Unix consolidée (.tar) créée pour regrouper un ou plusieurs fichiers. |
|
|  | [XZ](#XZ) | Représente un fichier XZ (.xz) compressé à l'aide d'un algorithme de compression à haut ratio basé sur l'algorithme LZMA. |
|
|  | [TXZ](#TXZ) | Représente une archive Unix consolidée (.txz, .tar.xz) créée pour regrouper un ou plusieurs fichiers. |
|
|  | [TARXZ](#TARXZ) | Représente une archive Unix consolidée (.txz, .tar.xz) créée pour regrouper un ou plusieurs fichiers. |
|
|  | [TGZ](#TGZ) | Représente une archive Unix consolidée (.tgz, .tar.gz) créée pour regrouper un ou plusieurs fichiers. |
|
|  | [TARGZ](#TARGZ) | Représente une archive Unix consolidée (.tgz, .tar.gz) créée pour regrouper un ou plusieurs fichiers. |
|
|  | [BZ_2](#BZ-2) | Représente un fichier compressé Bzip2 (.bz2) généré à l'aide de la méthode de compression open‑source BZIP2. |
|
|  | [RAR](#RAR) | Représente un fichier compressé Roshal Archive (.rar) généré à l'aide de la méthode de compression RAR (version WINRAR 4). |
|
|  | [GZ](#GZ) | Représente un fichier Gnu Zipped (.gz) compressé créé avec l'application de compression gzip. |
|
|  | [GZIP](#GZIP) | Représente un fichier Gnu Zipped (.gzip) compressé introduit comme utilitaire gratuit pour remplacer le programme Compress utilisé dans les systèmes Unix. |
|
|  | [SEVEN_ZIP](#SEVEN-ZIP) | Représente un fichier 7Zip (.7z, .7zip), qui est un archivage gratuit open‑source avec compression LZMA et LZMA2. |
|
|  | [CPIO](#CPIO) | Cpio est un utilitaire d'archivage de fichiers général et son format de fichier associé. |
|
|  | [ZSTANDARD](#ZSTANDARD) | Le fichier ZST est un fichier compressé généré avec l'algorithme de compression Zstandard (zstd). |
|
|  | [TZST](#TZST) | Les fichiers TZST (.tar.zst, .tzst) sont des archives Zstandard (ZST), qui contiennent en interne une archive Unix consolidée (Tar), créée avec un utilitaire Unix pour regrouper un ou plusieurs fichiers. |
|
|  | [TAR_ZST](#TAR-ZST) | Les fichiers TZST (.tar.zst, .tzst) sont des archives Zstandard (ZST), qui contiennent en interne une archive Unix consolidée (Tar), créée avec un utilitaire Unix pour regrouper un ou plusieurs fichiers. |
|
|  | [ISO](#ISO) | L'image de disque optique ISO est un fichier image de disque d'archive non compressé qui représente le contenu complet d'un disque optique tel qu'un CD ou un DVD, basé sur la norme ISO‑9660. |
|
|  | [LHA](#LHA) | LHA ou LZH est un utilitaire de compression gratuit et le format de fichier associé. |
|
|  | [CAB](#CAB) | Cabinet (ou CAB) est un format de fichier d'archive pour Microsoft Windows. |
|
|  | [DXF](#DXF) | Représente un fichier Drawing Exchange Format (.dxf), qui est une représentation de données balisées d'un fichier de dessin AutoCAD. |
|
|  | [DWG](#DWG) | Représente un fichier de base de données de dessin AutoCAD (.dwg), qui représente des fichiers binaires propriétaires utilisés pour contenir des données de conception 2D et 3D. |
|
|  | [DWT](#DWT) | Représente un modèle de dessin AutoCAD (.dwt), qui est un fichier modèle de dessin AutoCAD utilisé comme point de départ pour créer des dessins pouvant être enregistrés au format DWG. |
|
|  | [STL](#STL) | Représente un fichier Stéréolithographie (.stl), qui est un format de fichier interchangeable représentant la géométrie de surface tridimensionnelle. |
|
|  | [IFC](#IFC) | Représente un fichier Industry Foundation Classes (.ifc), qui est un format de fichier établissant des normes internationales pour l'importation et l'exportation d'objets de bâtiment et de leurs propriétés. |
|
|  | [DWF](#DWF) | Représente un fichier Design Web Format (.dwf), qui est un format de fichier compressé pour visualiser, réviser ou imprimer des dessins 2D/3D. |
|
|  | [FBX](#FBX) | Représente un fichier Autodesk FBX Interchange (FilmBoX) (.fbx), qui est un format de modèle 3D. |
|
|  | [DWFX](#DWFX) | Représente un fichier Design Web Format XPS (.dwfx), qui est un format compressé pour visualiser, réviser ou imprimer des dessins 2D/3D sous forme de document XPS. |
|
|  | [DGN](#DGN) | Représente un fichier de conception MicroStation (.dgn), qui sont des dessins créés et pris en charge par des applications CAO telles que MicroStation et Intergraph Interactive Graphics Design System. |
|
|  | [PLT](#PLT) | Représente un fichier PLT (HPGL) (.plt), qui est un fichier traceur vectoriel introduit par Autodesk, Inc. |
|
|  | [CF2](#CF2) | Représente un fichier Common File Format (.cf2). |
|
|  | [OBJ](#OBJ) | Représente un fichier Wavefront 3D Object (.obj), qui est un fichier image 3D introduit par Wavefront Technologies. |
|
|  | [HPG](#HPG) | Représente un fichier PLT (HPGL) (.hpg). |
|
|  | [IGS](#IGS) | Représente un fichier Initial Graphics Exchange Specification (IGES) (.igs). |
|
|  | [VSD](#VSD) | Représente un fichier de dessin Visio (.vsd), qui sont des dessins créés avec l'application Microsoft Visio pour représenter une variété d'objets graphiques et leurs interconnexions. |
|
|  | [VSDX](#VSDX) | Représente un fichier de dessin Visio (.vsdx), qui représente le format de fichier Microsoft Visio introduit à partir de Microsoft Office 2013. |
|
|  | [VSS](#VSS) | Représente un fichier de pochoir Visio (.vss), qui sont des fichiers de pochoir créés avec Microsoft Visio 2007 et antérieurs. |
|
|  | [VSSX](#VSSX) | Représente un fichier de pochoir Visio (.vssx), qui sont des pochoirs de dessin créés avec Microsoft Visio 2013 et versions ultérieures. |
|
|  | [VSDM](#VSDM) | Représente un dessin Visio activé par macro (.vsdm), qui sont des fichiers de dessin créés avec l'application Microsoft Visio et qui prennent en charge les macros. |
|
|  | [VST](#VST) | Représente un modèle de dessin Visio (.vst), qui sont des fichiers d'image vectorielle créés avec Microsoft Visio. |
|
|  | [VSTX](#VSTX) | Représente un modèle de dessin Visio (.vstx), qui sont des fichiers de modèle de dessin créés avec Microsoft Visio 2013 et versions ultérieures. |
|
|  | [VSTM](#VSTM) | Représente un modèle de dessin Visio activé par macro (.vstm), qui sont des fichiers de modèle créés avec Microsoft Visio et qui prennent en charge les macros. |
|
|  | [VSSM](#VSSM) | Représente un fichier de pochoir Visio activé par macro (.vssm), qui sont des fichiers de pochoir Microsoft Visio prenant en charge les macros. |
|
|  | [VSX](#VSX) | Représente un fichier XML de pochoir Visio (.vsx), qui désigne des pochoirs composés de dessins et de formes utilisés pour créer des diagrammes dans Microsoft Visio. |
|
|  | [VTX](#VTX) | Représente un fichier XML de modèle Visio (.vtx), qui est un modèle de dessin Microsoft Visio enregistré sur le disque au format XML. |
|
|  | [VDW](#VDW) | Représente un dessin Web Visio (.vdw), qui spécifie les flux et les stockages requis pour le rendu d'un dessin web. |
|
|  | [VDX](#VDX) | Représente un fichier XML de dessin Visio (.vdx), qui représente tout dessin ou diagramme créé dans Microsoft Visio mais enregistré au format XML avec l'extension .VDX. |
|
|  | [EPUB](#EPUB) | Représente un fichier Open eBook (.epub), qui est un format de fichier e-book offrant un format de publication numérique standard pour les éditeurs et les consommateurs. |
|
|  | [MOBI](#MOBI) | Représente un eBook Mobipocket (.mobi), qui est l'un des formats de fichier ebook les plus largement utilisés. |
|
|  | [AZW_3](#AZW-3) | Le ebook Amazon Kindle Format 8 (KF8) est le format de fichier numérique développé pour les appareils Amazon Kindle. |
|
|  | [MSG](#MSG) | Représente un message Outlook Mail (.msg), qui est un format de fichier utilisé par Microsoft Outlook et Exchange pour stocker des messages électroniques, des contacts, des rendez-vous ou d'autres tâches. |
|
|  | [EML](#EML) | Représente un message E‑Mail (.eml), qui représente des messages électroniques enregistrés à l'aide d'Outlook et d'autres applications pertinentes. |
|
|  | [EMLX](#EMLX) | Représente un message Apple Mail (.emlx), qui est implémenté et développé par Apple. |
|
|  | [PST](#PST) | Représente un fichier Outlook Personal Information Store (.pst), qui représente les fichiers de stockage personnel Outlook (également appelés Personal Storage Table) qui stockent une variété d'informations utilisateur. |
|
|  | [OST](#OST) | Représente un fichier Outlook Offline Data (.ost), qui représente les données de boîte aux lettres d'un utilisateur en mode hors ligne sur une machine locale après enregistrement auprès du serveur Exchange via Microsoft Outlook. |
|
|  | [TIF](#TIF) | Représente un fichier Tagged Image (.tif), qui représente des images raster destinées à être utilisées sur une variété d'appareils conformes à cette norme de format de fichier. |
|
|  | [TIFF](#TIFF) | Représente un format Tagged Image File (.tiff), qui représente des images raster destinées à être utilisées sur une variété d'appareils conformes à cette norme de format de fichier. |
|
|  | [JPG](#JPG) | Représente une image JPEG (.jpg), qui est un type de format d'image enregistré en utilisant la méthode de compression avec perte. |
|
|  | [JPEG](#JPEG) | Représente une image JPEG (.jpeg), qui est un type de format d'image enregistré en utilisant la méthode de compression avec perte. |
|
|  | [JFIF](#JFIF) | Le format d'échange de fichiers JPEG (.jfif) est une image qui a été développée pour un échange rapide entre les plateformes. |
|
|  | [PNG](#PNG) | Représente un graphique réseau portable (.png), qui est un type de format de fichier image raster qui utilise une compression sans perte. |
|
|  | [GIF](#GIF) | Représente un fichier Graphical Interchange Format (.gif), qui est un type d'image fortement compressée. |
|
|  | [APNG](#APNG) | Représente un graphique réseau portable animé (.apng), qui est une extension du format PNG qui prend en charge l'animation. |
|
|  | [BMP](#BMP) | Représente un fichier image bitmap (.bmp), qui est utilisé pour stocker des images numériques bitmap. |
|
|  | [ICO](#ICO) | Représente un fichier icône (.ico), qui est un type de fichier image utilisé comme icône pour la représentation d'une application sur Microsoft Windows. |
|
|  | [TGA](#TGA) | Représente un fichier Truevision TGA (TARGA), qui est utilisé pour stocker des images numériques bitmap développées par TRUEVISION. |
|
|  | [JP_2](#JP-2) | Représente un fichier d'image principal JPEG 2000 (.jp2), qui est un système de codage d'image et une norme de compression d'image à la pointe de la technologie. |
|
|  | [JPF](#JPF) | Représente un fichier image JPEG 2000 (.jpf). |
|
|  | [JPX](#JPX) | Représente un fichier image JPEG 2000 (.jpx). |
|
|  | [JPM](#JPM) | Représente un fichier image JPEG 2000 (.jpm). |
|
|  | [J2C](#J2C) | Représente un flux d'entrée de code JPEG 2000 (.j2c). |
|
|  | [J2K](#J2K) | Représente un flux de code JPEG 2000 (.j2k), qui est une image compressée en utilisant la compression par ondelettes au lieu de la compression DCT. |
|
|  | [JPC](#JPC) | Représente un flux de code JPEG 2000 (.jpc). |
|
|  | [JLS](#JLS) | Représente un fichier JPEG-LS (JLS) (.jls). |
|
|  | [DIB](#DIB) | Représente un fichier bitmap indépendant du dispositif (.dib). |
|
|  | [WMF](#WMF) | Représente un fichier Windows Metafile (.wmf), qui représente le Windows Metafile (WMF) de Microsoft pour le stockage de données d'image vectorielles ainsi que bitmap. |
|
|  | [WMZ](#WMZ) | Représente un Windows Metafile compressé (.wmz), qui représente le Windows Metafile (WMF) de Microsoft compressé dans une archive GZIP pour le stockage de données d'image vectorielles ainsi que bitmap. |
|
|  | [EMF](#EMF) | Représente un Enhanced Windows Metafile (.emf), qui représente des images graphiques de manière indépendante du dispositif. |
|
|  | [EMZ](#EMZ) | Représente un Windows Compressed Enhanced Metafile (.emz), qui représente des images graphiques indépendantes du dispositif compressées par GZIP. |
|
|  | [WEBP](#WEBP) | Représente une image WebP (.webp), qui est un format de fichier image raster web moderne basé sur la compression sans perte et avec perte. |
|
|  | [DNG](#DNG) | Représente une spécification Digital Negative (.dng), qui est un format d'image de caméra numérique utilisé pour le stockage de fichiers RAW. |
|
|  | [CDR](#CDR) | Représente un dessin vectoriel CorelDraw (.cdr), qui est un fichier d'image de dessin vectoriel créé nativement avec CorelDRAW pour le stockage d'images numériquement codées et compressées. |
|
|  | [CMX](#CMX) | Représente un Corel Exchange (.cmx), qui est un fichier d'image de dessin pouvant contenir des graphiques vectoriels ainsi que des graphiques bitmap. |
|
|  | [DJVU](#DJVU) | Représente une image DjVu (.djvu), qui est un format de fichier graphique destiné aux documents numérisés et aux livres, en particulier ceux contenant une combinaison de texte, de dessins, d'images et de photographies. |
|
|  | [CGM](#CGM) | Représente un Computer Graphics Metafile (.cgm), qui est un format de métafichier gratuit, indépendant de la plateforme, norme internationale pour le stockage et l'échange de graphiques vectoriels (2D), de graphiques raster et de texte. |
|
|  | [PCL](#PCL) | Représente un document Printer Command Language (.pcl). |
|
|  | [PSD](#PSD) | Représente un Adobe Photoshop Document (.psd), qui est le format de fichier natif d'Adobe Photoshop utilisé pour la conception et le développement graphiques. |
|
|  | [PSB](#PSB) | Représente un Photoshop Large Document Format (.psb), qui est utilisé pour la conception et le développement graphiques dans Adobe Photoshop. |
|
|  | [DCM](#DCM) | Représente une image DICOM (.dcm), qui représente une image numérique stockant les informations médicales des patients telles que les IRM, les scanners CT et les images d'échographie. |
|
|  | [PS](#PS) | Représente un fichier PostScript (.ps). |
|
|  | [EPS](#EPS) | Représente un fichier Encapsulated PostScript (.eps), qui décrit un programme de langage Encapsulated PostScript définissant l'apparence d'une seule page. |
|
|  | [ODG](#ODG) | Représente un fichier OpenDocument Graphic (.odg), qui est utilisé par l'application Draw d'Apache OpenOffice pour stocker les éléments de dessin sous forme d'image vectorielle. |
|
|  | [FODG](#FODG) | Représente un modèle Flat XML ODF (.fodg), qui est utilisé par l'application Draw d'Apache OpenOffice pour stocker les éléments de dessin sous forme d'image vectorielle. |
|
|  | [SVG](#SVG) | Représente un fichier Scalable Vector Graphics (.svg), qui est un fichier Scalable Vector Graphics utilisant un format texte basé sur XML pour décrire l'apparence d'une image. |
|
|  | [SVGZ](#SVGZ) | Représente un fichier Compressed Scalable Vector Graphics (.svgz), qui est un fichier Scalable Vector Graphics utilisant un format texte basé sur XML, compressé par GZIP, pour décrire l'apparence d'une image. |
|
|  | [OTG](#OTG) | Représente un modèle OpenDocument Graphic (.otg). |
|
|  | [HTM](#HTM) | Représente un fichier Hypertext Markup Language (.htm), qui est l'extension des pages web créées pour être affichées dans les navigateurs. |
|
|  | [HTML](#HTML) | Représente un fichier Hypertext Markup Language (.html), qui est l'extension des pages web créées pour être affichées dans les navigateurs. |
|
|  | [MHT](#MHT) | Représente une archive Web MHTML (.mht). |
|
|  | [NSF](#NSF) | Représente une base de données Lotus Notes (.nsf). |
|
|  | [MBOX](#MBOX) | Représente un fichier de boîte aux lettres Email (.mbox). |
|
|  | [MHTML](#MHTML) | Représente un fichier MIME HTML (.mhtml). |
|
|  | [XML](#XML) | Représente un fichier XML (.xml). |
|
|  | [ONE](#ONE) | Représente un document OneNote (.one) créé par l'application Microsoft OneNote. |
|
|  | [PDF](#PDF) | Représente un fichier Portable Document Format (.pdf), qui est un type de document créé par Adobe dans les années 1990. |
|
|  | [XPS](#XPS) | Représente un fichier XML Paper Specification (.xps), qui représente des fichiers de mise en page basés sur les spécifications XML Paper créés par Microsoft. |
|
|  | [OXPS](#OXPS) | Représente un fichier OpenXPS (.oxps). |
|
|  | [TEX](#TEX) | Représente un document source LaTeX (.tex), qui est un langage comprenant la programmation ainsi que des fonctionnalités de balisage utilisées pour la composition de documents. |
|
|  | [OFD](#OFD) | Le format Open Fixed-layout Document (OFD) défini par GB/T 33190-2016 vise à remplacer le PDF dans les institutions publiques chinoises. |
|
|  | [PPT](#PPT) | Représente une présentation PowerPoint (.ppt), qui est un fichier PowerPoint composé d’une collection de diapositives destinées à être affichées sous forme de diaporama. |
|
|  | [PPTX](#PPTX) | Représente une présentation PowerPoint Open XML (.pptx), qui sont des fichiers de présentation créés avec l’application Microsoft PowerPoint populaire. |
|
|  | [PPS](#PPS) | Représente un diaporama PowerPoint (.pps), qui est créé à l’aide de Microsoft PowerPoint à des fins de diaporama. |
|
|  | [PPSX](#PPSX) | Représente des fichiers de diaporama PowerPoint Open XML (.ppsx), qui sont créés avec Microsoft PowerPoint 2007 et versions ultérieures à des fins de diaporama. |
|
|  | [ODP](#ODP) | Représente une présentation OpenDocument (.odp), qui est un format de fichier de présentation utilisé par OpenOffice.org dans la norme OASIS Open. |
|
|  | [FODP](#FODP) | Représente une présentation OpenDocument (.fodp), qui correspond à une présentation OpenDocument Flat XML. |
|
|  | [POT](#POT) | Représente un modèle PowerPoint (.pot), qui correspond aux fichiers de modèle Microsoft PowerPoint créés par les versions PowerPoint 97-2003. |
|
|  | [PPTM](#PPTM) | Représente une présentation PowerPoint Open XML avec macros activées (.pptm), qui sont des fichiers de présentation avec macros créés avec Microsoft PowerPoint 2007 ou versions supérieures. |
|
|  | [POTX](#POTX) | Représente un modèle de présentation PowerPoint Open XML (.potx), qui correspond aux modèles de présentation Microsoft PowerPoint créés avec Microsoft PowerPoint 2007 et versions ultérieures. |
|
|  | [POTM](#POTM) | Représente un modèle de présentation PowerPoint Open XML avec macros activées (.potm), qui sont des fichiers de modèle Microsoft PowerPoint prenant en charge les macros. |
|
|  | [PPSM](#PPSM) | Représente une diapositive PowerPoint Open XML avec macros activées (.ppsm), qui correspond à un format de fichier de diaporama avec macros créé avec Microsoft PowerPoint 2007 ou supérieur. |
|
|  | [OTP](#OTP) | Représente un modèle de présentation OpenDocument (.otp), qui correspond aux fichiers de modèle de présentation créés par des applications au format standard OASIS OpenDocument. |
|
|  | [XLS](#XLS) | Représente une feuille de calcul Excel (.xls), qui correspond au format de fichier binaire Excel. |
|
|  | [EXCEL_2003_XML](#EXCEL-2003-XML) | Représente un XML Excel 2003 (SpreadsheetML) (.xml), qui correspond au format de fichier binaire Excel. |
|
|  | [NUMBERS](#NUMBERS) | Représente Apple Numbers (.numbers), qui correspond à un format de fichier binaire similaire à Excel. |
|
|  | [XLSX](#XLSX) | Représente une feuille de calcul Microsoft Excel Open XML (.xlsx), qui est un format bien connu pour les documents Microsoft Excel introduit par Microsoft avec la sortie de Microsoft Office 2007. |
|
|  | [XLSM](#XLSM) | Représente une feuille de calcul Excel Open XML avec macros activées (.xlsm), qui est un type de fichier de feuille de calcul prenant en charge les macros. |
|
|  | [XLSB](#XLSB) | Représente une feuille de calcul binaire Excel (.xlsb), qui spécifie le format de fichier binaire Excel. |
|
|  | [CSV](#CSV) | Représente un fichier de valeurs séparées par des virgules (.csv), qui correspond à des fichiers texte simples contenant des enregistrements de données avec des valeurs séparées par des virgules. |
|
|  | [TSV](#TSV) | Représente un fichier de valeurs séparées par des tabulations (.tsv), qui correspond à des données séparées par des tabulations dans un format texte simple. |
|
|  | [ODS](#ODS) | Représente une feuille de calcul OpenDocument (.ods), qui désigne le format de document de feuille de calcul OpenDocument modifiable par l'utilisateur. |
|
|  | [FODS](#FODS) | Représente une feuille de calcul OpenDocument Flat XML (.fods). |
|
|  | [OTS](#OTS) | Représente un modèle de feuille de calcul OpenDocument (.ots). |
|
|  | [XLAM](#XLAM) | Représente un module complémentaire Microsoft Excel (.xlam). |
|
|  | [XLTM](#XLTM) | Représente un modèle Microsoft Excel activé par macro (.xltm), qui représente les fichiers générés par Microsoft Excel en tant que fichiers de modèle activés par macro. |
|
|  | [XLT](#XLT) | Représente un modèle Microsoft Excel (.xlt), qui sont des fichiers de modèle créés avec Microsoft Excel, une application de feuille de calcul faisant partie de la suite Microsoft Office. |
|
|  | [XLTX](#XLTX) | Représente un modèle de feuille de calcul Excel Open XML (.xltx), qui représente les modèles Microsoft Excel basés sur les spécifications du format de fichier Office OpenXML. |
|
|  | [SXC](#SXC) | Représente une feuille de calcul StarOffice Calc (.sxc). |
|
|  | [MPP](#MPP) | Représente un fichier Microsoft Project (.mpp), qui est un fichier de données Microsoft Project stockant les informations liées à la gestion de projet de manière intégrée. |
|
|  | [MPT](#MPT) | Représente un modèle Microsoft Project (.mpt), qui contient des informations de base et une structure ainsi que les paramètres de document pour créer des fichiers .MPP. |
|
|  | [MPX](#MPX) | Représente un fichier d'échange Microsoft Project (.mpx), qui est un format de fichier ASCII permettant le transfert d'informations de projet entre Microsoft Project (MSP) et d'autres applications prenant en charge le format de fichier MPX, telles que Primavera Project Planner, Sciforma et Timerline Precision Estimating. |
|
|  | [AS](#AS) | Représente un fichier ActionScript (.as). |
|
|  | [AS_3](#AS-3) | Représente un fichier ActionScript (.as3). |
|
|  | [ASM](#ASM) | Représente un fichier source en langage d'assemblage (.asm). |
|
|  | [BAT](#BAT) | Représente un fichier batch DOS (.bat). |
|
|  | [C](#C) | Représente un fichier source C/C++ (.c). |
|
|  | [CC](#CC) | Représente un fichier source C++ (.cc). |
|
|  | [CMAKE](#CMAKE) | Représente un fichier CMake (.cmake). |
|
|  | [CPP](#CPP) | Représente un fichier source C++ (.cpp). |
|
|  | [CS](#CS) | Représente un fichier source C# (.cs), qui est un fichier source pour le langage de programmation C#. |
|
|  | [VB](#VB) | Représente un fichier d'élément de projet Visual Basic (.vb), qui est un fichier source créé en langage Visual Basic. |
|
|  | [CSS](#CSS) | Représente un fichier de feuille de style en cascade (.css). |
|
|  | [CXX](#CXX) | Représente un fichier source C++ (.cxx). |
|
|  | [DIFF](#DIFF) | Représente un fichier de correctif (.diff). |
|
|  | [ERB](#ERB) | Représente un script Ruby ERB (.erb). |
|
|  | [GROOVY](#GROOVY) | Représente un fichier source Groovy (.groovy). |
|
|  | [H](#H) | Représente un fichier d'en-tête C/C++/Objective-C (.h). |
|
|  | [HAML](#HAML) | Représente un fichier source Haml (.haml). |
|
|  | [HH](#HH) | Représente un fichier d'en-tête C++ (.hh). |
|
|  | [JAVA](#JAVA) | Représente un fichier de code source Java (.java). |
|
|  | [JS](#JS) | Représente un fichier JavaScript (.js). |
|
|  | [JSON](#JSON) | Représente un fichier JavaScript Object Notation (.json). |
|
|  | [LESS](#LESS) | Représente un fichier de feuille de style LESS (.less). |
|
|  | [LOG](#LOG) | Représente un fichier journal (.log). |
|
|  | [M](#M) | Représente un fichier d'implémentation Objective-C (.m). |
|
|  | [MAKE](#MAKE) | Représente un script Makefile Xcode (.make). |
|
|  | [MD](#MD) | Représente un fichier de documentation Markdown (.md). |
|
|  | [ML](#ML) | Représente un fichier de code source ML (.ml). |
|
|  | [MM](#MM) | Représente un fichier source Objective-C++ (.mm). |
|
|  | [PHP](#PHP) | Représente un fichier de code source PHP (.php). |
|
|  | [PL](#PL) | Représente un script Perl (.pl). |
|
|  | [PROPERTIES](#PROPERTIES) | Représente un fichier de propriétés Java (.properties). |
|
|  | [PY](#PY) | Représente un script Python (.py). |
|
|  | [RB](#RB) | Représente un fichier de code source Ruby (.rb). |
|
|  | [RST](#RST) | Représente un fichier reStructuredText (.rst). |
|
|  | [SASS](#SASS) | Représente un fichier Syntactically Awesome StyleSheets (.sass). |
|
|  | [SCALA](#SCALA) | Représente un fichier de code source Scala (.scala). |
|
|  | [SCM](#SCM) | Représente un fichier de code source Scheme (.scm). |
|
|  | [SCRIPT](#SCRIPT) | Représente un fichier de script générique (.script). |
|
|  | [SH](#SH) | Représente un script Bash Shell (.sh). |
|
|  | [SML](#SML) | Représente un fichier de code source Standard ML (.sml). |
|
|  | [SQL](#SQL) | Représente un fichier de données Structured Query Language (.sql). |
|
|  | [VIM](#VIM) | Représente un fichier de paramètres Vim (.vim). |
|
|  | [YAML](#YAML) | Représente un document YAML (.yaml). |
|
|  | [DOC](#DOC) | Représente un fichier Microsoft Word Document (.doc). |
|
|  | [DOCX](#DOCX) | Représente un fichier Microsoft Word Open XML Document (.docx). |
|
|  | [CHM](#CHM) | Représente un fichier Microsoft Compiled HTML Help (.chm). |
|
|  | [DOCM](#DOCM) | Représente un fichier Word Open XML Macro-Enabled Document (.docm). |
|
|  | [DOT](#DOT) | Représente un fichier Word Document Template (.dot). |
|
|  | [DOTX](#DOTX) | Représente un fichier Word Open XML Document Template (.dotx). |
|
|  | [DOTM](#DOTM) | Représente un fichier Word Open XML Macro-Enabled Document Template (.dotm). |
|
|  | [RTF](#RTF) | Représente un fichier Rich Text Format (.rtf). |
|
|  | [TXT](#TXT) | Représente un fichier texte brut (.txt). |
|
|  | [ODT](#ODT) | Représente un document texte OpenDocument (.odt). |
|
|  | [OTT](#OTT) | Représente un modèle de document OpenDocument (.ott). |
|
|  | [VCF](#VCF) | Représente un fichier vCard (.vcf), qui est un format de fichier numérique pour stocker des informations de contact. |
|
|  | [AI](#AI) | Représente un fichier Adobe Illustrator (.ai), qui est un format de fichier pour les dessins Adobe Illustrator. |
|
|  | [PSM1](#PSM1) | Représente un fichier module de script PowerShell (.psm1). |
|
|  | [PS1](#PS1) | Représente un fichier script PowerShell (.ps1). |
|
|  | [PSD1](#PSD1) | Représente un fichier manifeste de module de script PowerShell (.psd1). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Mappe une extension de fichier à un type de fichier. |
|
|  | [fromFilePath(String filePath)](#fromFilePath-java.lang.String-) | Extrait l'extension du fichier d'un nom de fichier ou d'un chemin d'accès et la mappe à un type de fichier. |
|
|  | [fromMediaType(String mediaType)](#fromMediaType-java.lang.String-) | Mappe un type de média de fichier à un type de fichier. |
|
|  | [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Détecte le type de fichier en lisant la signature du fichier. |
|
|  | [fromStream(InputStream stream, String password)](#fromStream-java.io.InputStream-java.lang.String-) | Détecte le type de fichier en lisant la signature du fichier. |
|
|  | [fromStream(InputStream stream, ILogger logger)](#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-) | Détecte le type de fichier en lisant la signature du fichier. |
|
|  | [fromStream(InputStream stream, String password, ILogger logger)](#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-) | Détecte le type de fichier en lisant la signature du fichier. |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | Récupère les types de fichiers pris en charge. |
|
|  | [detectCharset(String filePath)](#detectCharset-java.lang.String-) | Tente de détecter le jeu de caractères des fichiers texte [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV), et [CSV](../../com.groupdocs.viewer/filetype#CSV) par chemin. |
|
|  | [detectCharset(InputStream stream)](#detectCharset-java.io.InputStream-) | Tente de détecter le jeu de caractères du fichier texte [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV), et [CSV](../../com.groupdocs.viewer/filetype#CSV) par flux. |
|
|  | [getFileFormat()](#getFileFormat--) | Obtient le nom du format de fichier, par ex., "Microsoft Word Document". |
|
|  | [getExtension()](#getExtension--) | Obtient le suffixe d'extension de fichier (y compris le point "."), par ex., ".doc". |
|
|  | [toString()](#toString--) | Renvoie une représentation sous forme de chaîne de l'objet actuel. |
|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Représente un type de fichier inconnu.


### ZIP {#ZIP}
```
public static final FileType ZIP
```


Représente un fichier compressé (.zip) pouvant contenir un ou plusieurs fichiers ou répertoires.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/compression/zip).


### TAR {#TAR}
```
public static final FileType TAR
```


Représente une archive Unix consolidée (.tar) créée pour regrouper un ou plusieurs fichiers.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/compression/tar).


### XZ {#XZ}
```
public static final FileType XZ
```


Représente un fichier XZ (.xz) compressé à l'aide d'un algorithme de compression à haut ratio basé sur l'algorithme LZMA.
En savoir plus sur ce format de fichier [ici](../https://fileinfo.com/extension/xz).


### TXZ {#TXZ}
```
public static final FileType TXZ
```


Représente une archive Unix consolidée (.txz, .tar.xz) créée pour regrouper un ou plusieurs fichiers.
En savoir plus sur ce format de fichier [ici](../https://fileinfo.com/extension/txz).


### TARXZ {#TARXZ}
```
public static final FileType TARXZ
```


Représente une archive Unix consolidée (.txz, .tar.xz) créée pour regrouper un ou plusieurs fichiers.
En savoir plus sur ce format de fichier [ici](../https://fileinfo.com/extension/txz).


### TGZ {#TGZ}
```
public static final FileType TGZ
```


Représente une archive Unix consolidée (.tgz, .tar.gz) créée pour regrouper un ou plusieurs fichiers.
En savoir plus sur ce format de fichier [ici](../https://fileinfo.com/extension/tgz).


### TARGZ {#TARGZ}
```
public static final FileType TARGZ
```


Représente une archive Unix consolidée (.tgz, .tar.gz) créée pour regrouper un ou plusieurs fichiers.
En savoir plus sur ce format de fichier [ici](../https://fileinfo.com/extension/tgz).


### BZ_2 {#BZ-2}
```
public static final FileType BZ_2
```


Représente un fichier compressé Bzip2 (.bz2) généré à l'aide de la méthode de compression open‑source BZIP2.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/compression/bz2).


### RAR {#RAR}
```
public static final FileType RAR
```


Représente un fichier compressé Roshal Archive (.rar) généré à l'aide de la méthode de compression RAR (version WINRAR 4).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/compression/rar).


### GZ {#GZ}
```
public static final FileType GZ
```


Représente un fichier Gnu Zipped (.gz) compressé créé avec l'application de compression gzip.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/compression/gz).


### GZIP {#GZIP}
```
public static final FileType GZIP
```


Représente un fichier Gnu Zipped (.gzip) compressé introduit comme utilitaire gratuit pour remplacer le programme Compress utilisé dans les systèmes Unix.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/compression/gz).


### SEVEN_ZIP {#SEVEN-ZIP}
```
public static final FileType SEVEN_ZIP
```


Représente un fichier 7Zip (.7z, .7zip), qui est un archivage gratuit open‑source avec compression LZMA et LZMA2.
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/compression/7z/).


### CPIO {#CPIO}
```
public static final FileType CPIO
```


Cpio est un utilitaire d'archivage de fichiers général et son format de fichier associé. Il est principalement installé sur les systèmes d'exploitation informatiques de type Unix. En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/compression/cpio).


### ZSTANDARD {#ZSTANDARD}
```
public static final FileType ZSTANDARD
```


Le fichier ZST est un fichier compressé généré avec l'algorithme de compression Zstandard (zstd). C'est un fichier compressé créé avec une compression sans perte par cet algorithme. Les fichiers ZST peuvent être utilisés pour compresser différents types de fichiers tels que les bases de données, les systèmes de fichiers, les réseaux et les jeux.
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/compression/zst/).


### TZST {#TZST}
```
public static final FileType TZST
```


Les fichiers TZST (.tar.zst, .tzst) sont des archives Zstandard (ZST), qui contiennent en interne une archive Unix consolidée (Tar), créée avec un utilitaire Unix pour regrouper un ou plusieurs fichiers.


### TAR_ZST {#TAR-ZST}
```
public static final FileType TAR_ZST
```


Les fichiers TZST (.tar.zst, .tzst) sont des archives Zstandard (ZST), qui contiennent en interne une archive Unix consolidée (Tar), créée avec un utilitaire Unix pour regrouper un ou plusieurs fichiers.


### ISO {#ISO}
```
public static final FileType ISO
```


L'image de disque optique ISO est un fichier image de disque d'archive non compressé qui représente le contenu complet d'un disque optique tel qu'un CD ou un DVD, basé sur la norme ISO‑9660.
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/compression/iso/).


### LHA {#LHA}
```
public static final FileType LHA
```


LHA ou LZH est un utilitaire de compression gratuit et le format de fichier associé.
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/compression/lzh/).


### CAB {#CAB}
```
public static final FileType CAB
```


Cabinet (ou CAB) est un format de fichier d'archive pour Microsoft Windows.
En savoir plus sur ce format de fichier [ici](../https://en.wikipedia.org/wiki/Cabinet_(file_format)).


### DXF {#DXF}
```
public static final FileType DXF
```


Représente un fichier Drawing Exchange Format (.dxf), qui est une représentation de données balisées d'un fichier de dessin AutoCAD.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/cad/dxf).


### DWG {#DWG}
```
public static final FileType DWG
```


Représente un fichier de base de données de dessin AutoCAD (.dwg), qui représente des fichiers binaires propriétaires utilisés pour contenir des données de conception 2D et 3D.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/cad/dwg).


### DWT {#DWT}
```
public static final FileType DWT
```


Représente un modèle de dessin AutoCAD (.dwt), qui est un fichier modèle de dessin AutoCAD utilisé comme point de départ pour créer des dessins pouvant être enregistrés au format DWG.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/cad/dwt).


### STL {#STL}
```
public static final FileType STL
```


Représente un fichier de stéréolithographie (.stl), qui est un format de fichier interchangeable représentant la géométrie de surface tridimensionnelle. Il est couramment utilisé en prototypage rapide, impression 3D et fabrication assistée par ordinateur.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/cad/stl).


### IFC {#IFC}
```
public static final FileType IFC
```


Représente un fichier Industry Foundation Classes (.ifc), qui est un format de fichier établissant des normes internationales pour l'importation et l'exportation d'objets de construction et leurs propriétés. Il permet l'interopérabilité entre différentes applications logicielles.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/cad/ifc).


### DWF {#DWF}
```
public static final FileType DWF
```


Représente un fichier Design Web Format (.dwf), qui est un format de fichier compressé pour visualiser, examiner ou imprimer des dessins 2D/3D. Il contient des graphiques et du texte faisant partie des données de conception et réduit la taille du fichier grâce à la compression.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/cad/dwf).


### FBX {#FBX}
```
public static final FileType FBX
```


Représente un fichier Autodesk FBX Interchange (FilmBoX) (.fbx), qui est un format de modèle 3D.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/cad/fbx).


### DWFX {#DWFX}
```
public static final FileType DWFX
```


Représente un fichier Design Web Format XPS (.dwfx), qui est un format compressé pour visualiser, examiner ou imprimer des dessins 2D/3D sous forme de document XPS. Il contient des graphiques et du texte faisant partie des données de conception et réduit la taille du fichier grâce à la compression.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/cad/dwfx).


### DGN {#DGN}
```
public static final FileType DGN
```


Représente un fichier de conception MicroStation (.dgn), qui sont des dessins créés et pris en charge par des applications CAO telles que MicroStation et Intergraph Interactive Graphics Design System.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/cad/dgn).


### PLT {#PLT}
```
public static final FileType PLT
```


Représente un fichier PLT (HPGL) (.plt), qui est un fichier traceur vectoriel introduit par Autodesk, Inc. Il contient des informations pour un certain fichier CAD, et toutes les images sont imprimées en utilisant des lignes plutôt que des points, garantissant précision et exactitude en production.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/cad/plt).


### CF2 {#CF2}
```
public static final FileType CF2
```


Représente un fichier Common File Format (.cf2).
En savoir plus sur ce format de fichier [ici](../https://fileinfo.com/extension/cf2).


### OBJ {#OBJ}
```
public static final FileType OBJ
```


Représente un fichier Wavefront 3D Object (.obj), qui est un fichier image 3D introduit par Wavefront Technologies.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/3d/obj/).


### HPG {#HPG}
```
public static final FileType HPG
```


Représente un fichier PLT (HPGL) (.hpg).
Il s'agit d'un format de fichier utilisé pour les fichiers traceur dans le HP Graphics Language (HPGL).
En savoir plus sur ce format de fichier [ici](../https://fileinfo.com/extension/hpg).


### IGS {#IGS}
```
public static final FileType IGS
```


Représente un fichier Initial Graphics Exchange Specification (IGES) (.igs).


### VSD {#VSD}
```
public static final FileType VSD
```


Représente un fichier de dessin Visio (.vsd), qui sont des dessins créés avec l'application Microsoft Visio pour représenter une variété d'objets graphiques et leurs interconnexions.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vsd).


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Représente un fichier de dessin Visio (.vsdx), qui représente le format de fichier Microsoft Visio introduit à partir de Microsoft Office 2013. Il a remplacé le format de fichier binaire (.VSD) pris en charge par les versions antérieures de Microsoft Visio.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vsdx).


### VSS {#VSS}
```
public static final FileType VSS
```


Représente un fichier de pochoir Visio (.vss), qui sont des fichiers de pochoir créés avec Microsoft Visio 2007 et antérieur. Les fichiers de pochoir fournissent des objets de dessin qui peuvent être inclus dans un dessin Visio .VSD.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vss).


### VSSX {#VSSX}
```
public static final FileType VSSX
```


Représente un fichier de pochoir Visio (.vssx), qui sont des pochoirs de dessin créés avec Microsoft Visio 2013 et versions ultérieures. Le format de fichier VSSX peut être ouvert avec Visio 2013 et versions ultérieures. Les fichiers Visio sont connus pour représenter une variété d'éléments de dessin tels que des formes, des connecteurs, des organigrammes, des mises en page réseau, des diagrammes UML, etc.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vssx).


### VSDM {#VSDM}
```
public static final FileType VSDM
```


Représente un dessin Visio avec macros activées (.vsdm), qui sont des fichiers de dessin créés avec l'application Microsoft Visio qui prend en charge les macros. Les fichiers VSDM sont des dessins OPC/XML similaires aux VSDX, mais offrent également la capacité d'exécuter des macros lorsque le fichier est ouvert.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vsdm).


### VST {#VST}
```
public static final FileType VST
```


Représente un modèle de dessin Visio (.vst), qui sont des fichiers image vectorielle créés avec Microsoft Visio. Ils servent de modèles pour créer d'autres fichiers et contiennent la mise en page et les paramètres par défaut utilisés pour créer de nouveaux dessins Visio.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vst).


### VSTX {#VSTX}
```
public static final FileType VSTX
```


Représente un modèle de dessin Visio (.vstx), qui sont des fichiers modèle de dessin créés avec Microsoft Visio 2013 et versions ultérieures. Ces fichiers VSTX offrent un point de départ pour créer des dessins Visio enregistrés au format .VSDX, avec la mise en page et les paramètres par défaut.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vstx).


### VSTM {#VSTM}
```
public static final FileType VSTM
```


Représente un modèle de dessin Visio avec macros activées (.vstm), qui sont des fichiers modèle créés avec Microsoft Visio qui prennent en charge les macros. Les fichiers créés à partir de modèles VSTM peuvent exécuter des macros développées en code Visual Basic for Applications (VBA).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vstm).


### VSSM {#VSSM}
```
public static final FileType VSSM
```


Représente un fichier de gabarit Visio avec macros (.vssm), qui sont des fichiers de gabarits Microsoft Visio prenant en charge les macros. Lorsqu'un fichier VSSM est ouvert, des macros peuvent être exécutées pour obtenir le formatage et le placement souhaités des formes dans un diagramme.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vssm).


### VSX {#VSX}
```
public static final FileType VSX
```


Représente un fichier XML de gabarit Visio (.vsx), qui désigne des gabarits composés de dessins et de formes utilisés pour créer des diagrammes dans Microsoft Visio. Les fichiers VSX sont enregistrés au format XML et étaient pris en charge jusqu'à Visio 2013.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vsx).


### VTX {#VTX}
```
public static final FileType VTX
```


Représente un fichier XML de modèle Visio (.vtx), qui est un modèle de dessin Microsoft Visio enregistré sur le disque au format XML. Le modèle fournit des paramètres de base pour créer plusieurs fichiers Visio avec les mêmes paramètres.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vtx).


### VDW {#VDW}
```
public static final FileType VDW
```


Représente un dessin Web Visio (.vdw), qui spécifie les flux et les stockages requis pour le rendu d'un dessin web.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/web/vdw).


### VDX {#VDX}
```
public static final FileType VDX
```


Représente un fichier XML de dessin Visio (.vdx), qui représente tout dessin ou diagramme créé dans Microsoft Visio mais enregistré au format XML avec l'extension .VDX. Un fichier XML de dessin Visio est créé dans le logiciel Visio développé par Microsoft.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/vdx).


### EPUB {#EPUB}
```
public static final FileType EPUB
```


Représente un fichier Open eBook (.epub), qui est un format de fichier e-book offrant un format de publication numérique standard pour les éditeurs et les lecteurs. Le format est pris en charge par de nombreux lecteurs électroniques et applications logicielles.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/ebook/epub).


### MOBI {#MOBI}
```
public static final FileType MOBI
```


Représente un eBook Mobipocket (.mobi), qui est l'un des formats de fichier ebook les plus largement utilisés. Le format est une amélioration du vieux format OEB (Open Ebook Format) et était utilisé comme format propriétaire pour le lecteur Mobipocket.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/ebook/mobi).


### AZW_3 {#AZW-3}
```
public static final FileType AZW_3
```


Le ebook Amazon Kindle Format 8 (KF8) est le format de fichier numérique développé pour les appareils Amazon Kindle. Le format est une amélioration des anciens fichiers AZW et est utilisé uniquement sur les appareils Kindle Fire avec une compatibilité descendante avec le format de fichier ancêtre, c’est‑à‑dire MOBI et AZW.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/ebook/azw3).


### MSG {#MSG}
```
public static final FileType MSG
```


Représente un message Outlook Mail (.msg), qui est un format de fichier utilisé par Microsoft Outlook et Exchange pour stocker des messages électroniques, des contacts, des rendez-vous ou d'autres tâches.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/email/msg).


### EML {#EML}
```
public static final FileType EML
```


Représente un message électronique (.eml), qui représente les messages électroniques enregistrés à l'aide d'Outlook et d'autres applications pertinentes. Presque tous les clients de messagerie prennent en charge ce format de fichier en raison de sa conformité à la norme RFC‑822 du format de message Internet.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/email/eml).


### EMLX {#EMLX}
```
public static final FileType EMLX
```


Représente un message Apple Mail (.emlx), qui est implémenté et développé par Apple. L'application Apple Mail utilise le format de fichier EMLX pour l'exportation des courriels.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/email/emlx).


### PST {#PST}
```
public static final FileType PST
```


Représente un fichier Outlook Personal Information Store (.pst), qui représente les fichiers de stockage personnel Outlook (également appelés Personal Storage Table) qui stockent une variété d'informations utilisateur.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/email/pst).


### OST {#OST}
```
public static final FileType OST
```


Représente un fichier Outlook Offline Data (.ost), qui représente les données de boîte aux lettres d'un utilisateur en mode hors ligne sur une machine locale après enregistrement auprès du serveur Exchange via Microsoft Outlook.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/email/ost).


### TIF {#TIF}
```
public static final FileType TIF
```


Représente un fichier d'image balisée (.tif), qui représente des images matricielles destinées à être utilisées sur une variété d'appareils conformes à cette norme de format de fichier. Il est capable de décrire des données d'image binaire, en niveaux de gris, à palette de couleurs et en couleur pleine dans plusieurs espaces colorimétriques.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/tiff).


### TIFF {#TIFF}
```
public static final FileType TIFF
```


Représente un format de fichier d'image balisée (.tiff), qui représente des images matricielles destinées à être utilisées sur une variété d'appareils conformes à cette norme de format de fichier. Il est capable de décrire des données d'image binaire, en niveaux de gris, à palette de couleurs et en couleur pleine dans plusieurs espaces colorimétriques.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/tiff).


### JPG {#JPG}
```
public static final FileType JPG
```


Représente une image JPEG (.jpg), qui est un type de format d'image enregistré en utilisant la méthode de compression avec perte. L'image résultante, en raison de la compression, constitue un compromis entre la taille de stockage et la qualité de l'image.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/jpeg).


### JPEG {#JPEG}
```
public static final FileType JPEG
```


Représente une image JPEG (.jpeg), qui est un type de format d'image enregistré en utilisant la méthode de compression avec perte. L'image résultante, en raison de la compression, constitue un compromis entre la taille de stockage et la qualité de l'image.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/jpeg).


### JFIF {#JFIF}
```
public static final FileType JFIF
```


Le format d'échange de fichiers JPEG (.jfif) est une image qui a été développée pour un échange rapide entre plateformes. Ce format utilise la compression JPEG. En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/jfif).


### PNG {#PNG}
```
public static final FileType PNG
```


Représente un graphique réseau portable (.png), qui est un type de format de fichier image raster utilisant une compression sans perte. Ce format de fichier a été créé en remplacement du Graphics Interchange Format (GIF) et ne comporte aucune limitation de droits d'auteur.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/png).


### GIF {#GIF}
```
public static final FileType GIF
```


Représente un fichier Graphical Interchange Format (.gif), qui est un type d'image fortement compressée. Pour chaque image, le GIF autorise généralement jusqu'à 8 bits par pixel, et jusqu'à 256 couleurs sont permises dans l'image.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/gif).


### APNG {#APNG}
```
public static final FileType APNG
```


Représente un graphique réseau portable animé (.apng), qui est une extension du format PNG qui prend en charge l'animation.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/apng).


### BMP {#BMP}
```
public static final FileType BMP
```


Représente un fichier image bitmap (.bmp), qui est utilisé pour stocker des images numériques bitmap. Ces images sont indépendantes de l'adaptateur graphique et sont également appelées format de fichier bitmap indépendant du dispositif (DIB).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/bmp).


### ICO {#ICO}
```
public static final FileType ICO
```


Représente un fichier icône (.ico), qui est un type de fichier image utilisé comme icône pour la représentation d'une application sur Microsoft Windows.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/ico).


### TGA {#TGA}
```
public static final FileType TGA
```


Représente un fichier Truevision TGA (TARGA), qui est utilisé pour stocker des images numériques bitmap développées par TRUEVISION.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/tga).


### JP_2 {#JP-2}
```
public static final FileType JP_2
```


Représente un fichier d'image principal JPEG 2000 (.jp2), qui est un système de codage d'image et une norme de compression d'image à la pointe de la technologie.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/jp2).


### JPF {#JPF}
```
public static final FileType JPF
```


Représente un fichier image JPEG 2000 (.jpf).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/image/jpf).


### JPX {#JPX}
```
public static final FileType JPX
```


Représente un fichier image JPEG 2000 (.jpx).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/jpx).


### JPM {#JPM}
```
public static final FileType JPM
```


Représente un fichier image JPEG 2000 (.jpm).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/jpm).


### J2C {#J2C}
```
public static final FileType J2C
```


Représente un flux d'entrée de code JPEG 2000 (.j2c).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/j2c).


### J2K {#J2K}
```
public static final FileType J2K
```


Représente un flux de code JPEG 2000 (.j2k), qui est une image compressée en utilisant la compression par ondelettes au lieu de la compression DCT.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/j2k).


### JPC {#JPC}
```
public static final FileType JPC
```


Représente un flux de code JPEG 2000 (.jpc).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/jpc).


### JLS {#JLS}
```
public static final FileType JLS
```


Représente un fichier JPEG-LS (JLS) (.jls).
En savoir plus sur ce format de fichier [ici](../https://fileinfo.com/extension/jls).


### DIB {#DIB}
```
public static final FileType DIB
```


Représente un fichier bitmap indépendant du dispositif (.dib).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/dib).


### WMF {#WMF}
```
public static final FileType WMF
```


Représente un fichier Windows Metafile (.wmf), qui représente le Windows Metafile (WMF) de Microsoft pour le stockage de données d'image vectorielles ainsi que bitmap.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/wmf).


### WMZ {#WMZ}
```
public static final FileType WMZ
```


Représente un Windows Metafile compressé (.wmz), qui représente le Windows Metafile (WMF) de Microsoft compressé dans une archive GZIP pour le stockage de données d'image vectorielles ainsi que bitmap.
En savoir plus sur ce format de fichier [ici](../https://fileinfo.com/extension/wmz#compressed_windows_metafile).


### EMF {#EMF}
```
public static final FileType EMF
```


Représente un Enhanced Windows Metafile (.emf), qui représente des images graphiques de manière indépendante du dispositif. Les métafichiers EMF comprennent des enregistrements de longueur variable dans l'ordre chronologique qui peuvent rendre l'image stockée après analyse sur n'importe quel dispositif de sortie.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/emf).


### EMZ {#EMZ}
```
public static final FileType EMZ
```


Représente un Windows Compressed Enhanced Metafile (.emz), qui représente des images graphiques compressées de manière indépendante du dispositif par GZIP. Les métafichiers EMF comprennent des enregistrements de longueur variable dans l'ordre chronologique qui peuvent rendre l'image stockée après analyse sur n'importe quel dispositif de sortie.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/emz).


### WEBP {#WEBP}
```
public static final FileType WEBP
```


Représente une image WebP (.webp), qui est un format de fichier d'image raster web moderne basé sur la compression sans perte et avec perte. Il offre la même qualité d'image tout en réduisant considérablement la taille de l'image.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/webp).


### DNG {#DNG}
```
public static final FileType DNG
```


Représente une spécification Digital Negative (.dng), qui est un format d'image de caméra numérique utilisé pour le stockage de fichiers RAW. Il a été développé par Adobe en septembre 2004 et est principalement utilisé pour la photographie numérique.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/dng).


### CDR {#CDR}
```
public static final FileType CDR
```


Représente un dessin vectoriel CorelDraw (.cdr), qui est un fichier d'image de dessin vectoriel créé nativement avec CorelDRAW pour stocker des images codées numériquement et compressées. Un fichier de dessin CDR contient du texte, des lignes, des formes, des images, des couleurs et des effets pour la représentation vectorielle du contenu de l'image.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/cdr).


### CMX {#CMX}
```
public static final FileType CMX
```


Représente un Corel Exchange (.cmx), qui est un fichier d'image de dessin pouvant contenir des graphiques vectoriels ainsi que des graphiques bitmap.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/cmx).


### DJVU {#DJVU}
```
public static final FileType DJVU
```


Représente une image DjVu (.djvu), qui est un format de fichier graphique destiné aux documents numérisés et aux livres, en particulier ceux contenant une combinaison de texte, de dessins, d'images et de photographies.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/djvu).


### CGM {#CGM}
```
public static final FileType CGM
```


Représente un Computer Graphics Metafile (.cgm), qui est un format de métas fichier gratuit, indépendant de la plateforme, norme internationale pour le stockage et l'échange de graphiques vectoriels (2D), de graphiques raster et de texte. CGM utilise une approche orientée objet et fournit de nombreuses fonctions pour la production d'images.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/page-description-language/cgm).


### PCL {#PCL}
```
public static final FileType PCL
```


Représente un document Printer Command Language (.pcl).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/page-description-language/pcl).


### PSD {#PSD}
```
public static final FileType PSD
```


Représente un Adobe Photoshop Document (.psd), qui est le format de fichier natif d'Adobe Photoshop utilisé pour la conception et le développement graphiques.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/psd).


### PSB {#PSB}
```
public static final FileType PSB
```


Représente un Photoshop Large Document Format (.psb), qui est utilisé pour la conception et le développement graphiques dans Adobe Photoshop.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/psb).


### DCM {#DCM}
```
public static final FileType DCM
```


Représente une image DICOM (.dcm), qui représente une image numérique stockant les informations médicales des patients telles que les IRM, les scanners CT et les images d'échographie.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/dcm).


### PS {#PS}
```
public static final FileType PS
```


Représente un fichier PostScript (.ps).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/page-description-language/ps).


### EPS {#EPS}
```
public static final FileType EPS
```


Représente un fichier Encapsulated PostScript (.eps), qui décrit un programme de langage Encapsulated PostScript définissant l'apparence d'une seule page.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/page-description-language/eps).


### ODG {#ODG}
```
public static final FileType ODG
```


Représente un fichier OpenDocument Graphic (.odg), qui est utilisé par l'application Draw d'Apache OpenOffice pour stocker les éléments de dessin sous forme d'image vectorielle.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/odg).


### FODG {#FODG}
```
public static final FileType FODG
```


Représente un modèle Flat XML ODF (.fodg), qui est utilisé par l'application Draw d'Apache OpenOffice pour stocker les éléments de dessin sous forme d'image vectorielle.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/image/fodg).


### SVG {#SVG}
```
public static final FileType SVG
```


Représente un fichier Scalable Vector Graphics (.svg), qui est un fichier Scalable Vector Graphics utilisant un format texte basé sur XML pour décrire l'apparence d'une image.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/page-description-language/svg).


### SVGZ {#SVGZ}
```
public static final FileType SVGZ
```


Représente un fichier Compressed Scalable Vector Graphics (.svgz), qui est un fichier Scalable Vector Graphics utilisant un format texte basé sur XML, compressé par GZIP, pour décrire l'apparence d'une image.
En savoir plus sur ce format de fichier [ici](../https://fileinfo.com/extension/svgz).


### OTG {#OTG}
```
public static final FileType OTG
```


Représente un modèle OpenDocument Graphic (.otg).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/image/otg).


### HTM {#HTM}
```
public static final FileType HTM
```


Représente un fichier Hypertext Markup Language (.htm), qui est l'extension des pages web créées pour être affichées dans les navigateurs.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/web/html).


### HTML {#HTML}
```
public static final FileType HTML
```


Représente un fichier Hypertext Markup Language (.html), qui est l'extension des pages web créées pour être affichées dans les navigateurs.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/web/html).


### MHT {#MHT}
```
public static final FileType MHT
```


Représente une archive Web MHTML (.mht).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/web/mht).


### NSF {#NSF}
```
public static final FileType NSF
```


Représente une base de données Lotus Notes (.nsf).
En savoir plus sur ce format de fichier [ici](../https://fileinfo.com/extension/nsf).


### MBOX {#MBOX}
```
public static final FileType MBOX
```


Représente un fichier de boîte aux lettres Email (.mbox).
En savoir plus sur ce format de fichier [ici](../https://fileinfo.com/extension/mbox).


### MHTML {#MHTML}
```
public static final FileType MHTML
```


Représente un fichier MIME HTML (.mhtml).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/web/mhtml).


### XML {#XML}
```
public static final FileType XML
```


Représente un fichier XML (.xml).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/web/xml).


### ONE {#ONE}
```
public static final FileType ONE
```


Représente un document OneNote (.one) créé par l'application Microsoft OneNote. OneNote vous permet de rassembler des informations en utilisant l'application comme si vous utilisiez votre bloc-notes pour prendre des notes.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/note-taking/one).


### PDF {#PDF}
```
public static final FileType PDF
```


Représente un fichier Portable Document Format (.pdf), qui est un type de document créé par Adobe dans les années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et d'autres matériels de référence dans un format indépendant du logiciel applicatif, du matériel et des systèmes d'exploitation.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/view/pdf).


### XPS {#XPS}
```
public static final FileType XPS
```


Représente un fichier XML Paper Specification (.xps), qui représente des fichiers de mise en page basés sur les spécifications XML Paper créées par Microsoft. Ce format a été développé par Microsoft comme remplacement du format de fichier EMF et est similaire au format PDF, mais utilise XML dans la mise en page, l'apparence et les informations d'impression d'un document.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/page-description-language/xps).


### OXPS {#OXPS}
```
public static final FileType OXPS
```


Représente un fichier OpenXPS (.oxps).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/page-description-language/oxps).


### TEX {#TEX}
```
public static final FileType TEX
```


Représente un document source LaTeX (.tex), qui est un langage comprenant la programmation ainsi que des fonctionnalités de balisage utilisées pour la composition de documents.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/page-description-language/tex).


### OFD {#OFD}
```
public static final FileType OFD
```


Le format Open Fixed-layout Document (OFD) défini par GB/T 33190-2016 vise à remplacer le PDF dans les institutions publiques chinoises.


### PPT {#PPT}
```
public static final FileType PPT
```


Représente une présentation PowerPoint (.ppt), qui représente un fichier PowerPoint composé d'une collection de diapositives affichées sous forme de diaporama. Il spécifie le format de fichier binaire utilisé par Microsoft PowerPoint 97-2003.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/presentation/ppt).


### PPTX {#PPTX}
```
public static final FileType PPTX
```


Représente une présentation PowerPoint Open XML (.pptx), qui sont des fichiers de présentation créés avec l'application populaire Microsoft PowerPoint. Contrairement à la version précédente du format de fichier de présentation PPT, qui était binaire, le format PPTX est basé sur le format de fichier de présentation Microsoft PowerPoint Open XML.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/presentation/pptx).


### PPS {#PPS}
```
public static final FileType PPS
```


Représente un diaporama PowerPoint (.pps), qui est créé à l'aide de Microsoft PowerPoint à des fins de présentation. La lecture et la création de fichiers PPS sont prises en charge par Microsoft PowerPoint 97-2003.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/presentation/pps).


### PPSX {#PPSX}
```
public static final FileType PPSX
```


Représente des fichiers de diaporama PowerPoint Open XML (.ppsx), qui sont créés avec Microsoft PowerPoint 2007 et versions ultérieures à des fins de diaporama.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/presentation/ppsx).


### ODP {#ODP}
```
public static final FileType ODP
```


Représente une présentation OpenDocument (.odp), qui est un format de fichier de présentation utilisé par OpenOffice.org dans la norme OASIS Open.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/presentation/odp).


### FODP {#FODP}
```
public static final FileType FODP
```


Représente une présentation OpenDocument (.fodp), qui correspond à une présentation OpenDocument Flat XML.
En savoir plus sur ce format de fichier [ici](../https://fileinfo.com/extension/fodp).


### POT {#POT}
```
public static final FileType POT
```


Représente un modèle PowerPoint (.pot), qui correspond aux fichiers de modèle Microsoft PowerPoint créés par les versions PowerPoint 97-2003.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/presentation/pot).


### PPTM {#PPTM}
```
public static final FileType PPTM
```


Représente une présentation PowerPoint Open XML avec macros activées (.pptm), qui sont des fichiers de présentation avec macros créés avec Microsoft PowerPoint 2007 ou versions supérieures.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/presentation/pptm).


### POTX {#POTX}
```
public static final FileType POTX
```


Représente un modèle de présentation PowerPoint Open XML (.potx), qui correspond aux modèles de présentation Microsoft PowerPoint créés avec Microsoft PowerPoint 2007 et versions ultérieures.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/presentation/potx).


### POTM {#POTM}
```
public static final FileType POTM
```


Représente un modèle de présentation PowerPoint Open XML avec macros activées (.potm), qui sont des fichiers de modèle Microsoft PowerPoint avec prise en charge des macros. Les fichiers POTM sont créés avec PowerPoint 2007 ou une version ultérieure et contiennent des paramètres par défaut pouvant être utilisés pour créer d'autres fichiers de présentation.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/presentation/potm).


### PPSM {#PPSM}
```
public static final FileType PPSM
```


Représente une diapositive PowerPoint Open XML avec macros activées (.ppsm), qui correspond à un format de fichier de diaporama avec macros créé avec Microsoft PowerPoint 2007 ou supérieur.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/presentation/ppsm).


### OTP {#OTP}
```
public static final FileType OTP
```


Représente un modèle de présentation OpenDocument (.otp), qui correspond aux fichiers de modèle de présentation créés par des applications au format standard OASIS OpenDocument.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/presentation/otp).


### XLS {#XLS}
```
public static final FileType XLS
```


Représente une feuille de calcul Excel (.xls), qui correspond au format de fichier binaire Excel. Ces fichiers peuvent être créés par Microsoft Excel ainsi que par d'autres programmes de tableur similaires tels qu'OpenOffice Calc ou Apple Numbers.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/xls).


### EXCEL_2003_XML {#EXCEL-2003-XML}
```
public static final FileType EXCEL_2003_XML
```


Représente un XML Excel 2003 (SpreadsheetML) (.xml), qui correspond au format de fichier binaire Excel. Ces fichiers peuvent être créés par Microsoft Excel ainsi que par d'autres programmes de tableur similaires tels qu'OpenOffice Calc ou Apple Numbers.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/xls).


### NUMBERS {#NUMBERS}
```
public static final FileType NUMBERS
```


Représente Apple Numbers (.numbers), qui correspond à un format de fichier binaire similaire à Excel. Ces fichiers peuvent être créés par l'application Apple Numbers.
En savoir plus sur ce format de fichier [ici](../https://fileinfo.com/extension/numbers).


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Représente une feuille de calcul Microsoft Excel Open XML (.xlsx), qui est un format bien connu pour les documents Microsoft Excel introduit par Microsoft avec la sortie de Microsoft Office 2007.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/xlsx).


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Représente une feuille de calcul Excel Open XML avec macros activées (.xlsm), qui est un type de fichier de feuille de calcul prenant en charge les macros.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/xlsm).


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Représente une feuille de calcul binaire Excel (.xlsb), qui spécifie le format de fichier binaire Excel. Il s'agit d'une collection d'enregistrements et de structures qui définissent le contenu du classeur Excel.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/xlsb).


### CSV {#CSV}
```
public static final FileType CSV
```


Représente un fichier de valeurs séparées par des virgules (.csv), qui correspond à des fichiers texte simples contenant des enregistrements de données avec des valeurs séparées par des virgules.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/csv).


### TSV {#TSV}
```
public static final FileType TSV
```


Représente un fichier de valeurs séparées par des tabulations (.tsv), qui correspond à des données séparées par des tabulations dans un format texte simple.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/tsv).


### ODS {#ODS}
```
public static final FileType ODS
```


Représente une feuille de calcul OpenDocument (.ods), qui désigne le format de document de feuille de calcul OpenDocument modifiable par l'utilisateur. Les données sont stockées dans les fichiers ODF sous forme de lignes et de colonnes.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/ods).


### FODS {#FODS}
```
public static final FileType FODS
```


Représente une feuille de calcul OpenDocument Flat XML (.fods).
Il s'agit d'un format de document de feuille de calcul basé sur XML utilisé par OpenOffice et LibreOffice.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/fods).


### OTS {#OTS}
```
public static final FileType OTS
```


Représente un modèle de feuille de calcul OpenDocument (.ots).
Il s'agit d'un format de document modèle utilisé par OpenOffice et LibreOffice pour les feuilles de calcul.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/ots).


### XLAM {#XLAM}
```
public static final FileType XLAM
```


Représente un module complémentaire Microsoft Excel (.xlam).
Il s'agit d'un format de fichier utilisé par Microsoft Excel pour créer des modules complémentaires avec des fonctionnalités personnalisées.
En savoir plus sur ce format de fichier [ici](../https://fileinfo.com/extension/xlam).


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Représente un modèle Excel avec macros activées (.xltm), qui correspond aux fichiers générés par Microsoft Excel en tant que modèles avec macros. Les fichiers XLTM sont similaires aux XLTX sur le plan de la structure, à l'exception que ces derniers ne prennent pas en charge la création de modèles avec macros.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/xltm).


### XLT {#XLT}
```
public static final FileType XLT
```


Représente un modèle Microsoft Excel (.xlt), qui sont des fichiers modèle créés avec Microsoft Excel, une application de feuille de calcul faisant partie de la suite Microsoft Office. Microsoft Office 97-2003 permettait de créer de nouveaux fichiers XLT ainsi que de les ouvrir.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/xlt).


### XLTX {#XLTX}
```
public static final FileType XLTX
```


Représente un modèle de feuille de calcul Excel Open XML (.xltx), qui représente des modèles Microsoft Excel basés sur les spécifications du format de fichier Office OpenXML. Il est utilisé pour créer un fichier modèle standard qui peut être utilisé pour générer des fichiers XLSX avec les mêmes paramètres spécifiés dans le fichier XLTX.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/xltx).


### SXC {#SXC}
```
public static final FileType SXC
```


Représente une feuille de calcul StarOffice Calc (.sxc).
Il s'agit d'un document de feuille de calcul créé avec StarOffice Calc, un programme de feuille de calcul.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/spreadsheet/sxc).


### MPP {#MPP}
```
public static final FileType MPP
```


Représente un fichier Microsoft Project (.mpp), qui est un fichier de données Microsoft Project stockant les informations liées à la gestion de projet de manière intégrée.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/project-management/mpp).


### MPT {#MPT}
```
public static final FileType MPT
```


Représente un modèle Microsoft Project (.mpt), qui contient des informations de base et une structure ainsi que les paramètres de document pour créer des fichiers .MPP.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/project-management/mpt).


### MPX {#MPX}
```
public static final FileType MPX
```


Représente un fichier d'échange Microsoft Project (.mpx), qui est un format de fichier ASCII permettant le transfert d'informations de projet entre Microsoft Project (MSP) et d'autres applications prenant en charge le format de fichier MPX, telles que Primavera Project Planner, Sciforma et Timerline Precision Estimating.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/project-management/mpx).


### AS {#AS}
```
public static final FileType AS
```


Représente un fichier ActionScript (.as).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/programming/as).


### AS_3 {#AS-3}
```
public static final FileType AS_3
```


Représente un fichier ActionScript (.as3).
En savoir plus sur ce format de fichier [ici](../https://datatypes.net/open-as3-files).


### ASM {#ASM}
```
public static final FileType ASM
```


Représente un fichier source en langage d'assemblage (.asm).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/cad/asm).


### BAT {#BAT}
```
public static final FileType BAT
```


Représente un fichier batch DOS (.bat).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/executable/bat).


### C {#C}
```
public static final FileType C
```


Représente un fichier source C/C++ (.c).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/programming/c).


### CC {#CC}
```
public static final FileType CC
```


Représente un fichier source C++ (.cc).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/programming/cc).


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Représente un fichier CMake (.cmake).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/programming/cmake).


### CPP {#CPP}
```
public static final FileType CPP
```


Représente un fichier source C++ (.cpp).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/programming/cpp).


### CS {#CS}
```
public static final FileType CS
```


Représente un fichier source C# (.cs), qui est un fichier de code source pour le langage de programmation C#. Il a été introduit par Microsoft pour une utilisation avec le .NET Framework.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/programming/cs).


### VB {#VB}
```
public static final FileType VB
```


Représente un fichier d'élément de projet Visual Basic (.vb), qui est un fichier de code source créé dans le langage Visual Basic. Il a été créé par Microsoft pour le développement d'applications .NET.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/programming/vb).


### CSS {#CSS}
```
public static final FileType CSS
```


Représente un fichier de feuille de style en cascade (.css).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/web/css).


### CXX {#CXX}
```
public static final FileType CXX
```


Représente un fichier source C++ (.cxx).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/programming/cxx).


### DIFF {#DIFF}
```
public static final FileType DIFF
```


Représente un fichier de correctif (.diff).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/programming/diff).


### ERB {#ERB}
```
public static final FileType ERB
```


Représente un script Ruby ERB (.erb).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/programming/erb).


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Représente un fichier source Groovy (.groovy).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/programming/groovy).


### H {#H}
```
public static final FileType H
```


Représente un fichier d'en-tête C/C++/Objective-C (.h).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/programming/h).


### HAML {#HAML}
```
public static final FileType HAML
```


Représente un fichier source Haml (.haml).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/programming/haml).


### HH {#HH}
```
public static final FileType HH
```


Représente un fichier d'en-tête C++ (.hh).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/programming/hh).


### JAVA {#JAVA}
```
public static final FileType JAVA
```


Représente un fichier de code source Java (.java).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/programming/java).


### JS {#JS}
```
public static final FileType JS
```


Représente un fichier JavaScript (.js).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/web/js).


### JSON {#JSON}
```
public static final FileType JSON
```


Représente un fichier JavaScript Object Notation (.json).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/web/json).


### LESS {#LESS}
```
public static final FileType LESS
```


Représente un fichier de feuille de style LESS (.less).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/web/less).


### LOG {#LOG}
```
public static final FileType LOG
```


Représente un fichier journal (.log).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/database/log).


### M {#M}
```
public static final FileType M
```


Représente un fichier d'implémentation Objective-C (.m).
En savoir plus sur ce format de fichier [ici](../https://fileinfo.com/extension/m).


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Représente un script Makefile Xcode (.make).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/programming/make).


### MD {#MD}
```
public static final FileType MD
```


Représente un fichier de documentation Markdown (.md).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/word-processing/md).


### ML {#ML}
```
public static final FileType ML
```


Représente un fichier de code source ML (.ml).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/programming/ml).


### MM {#MM}
```
public static final FileType MM
```


Représente un fichier source Objective-C++ (.mm).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/programming/mm).


### PHP {#PHP}
```
public static final FileType PHP
```


Représente un fichier de code source PHP (.php).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/programming/php).


### PL {#PL}
```
public static final FileType PL
```


Représente un script Perl (.pl).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/programming/pl).


### PROPERTIES {#PROPERTIES}
```
public static final FileType PROPERTIES
```


Représente un fichier de propriétés Java (.properties).
En savoir plus sur ce format de fichier [ici](../https://fileinfo.com/extension/properties).


### PY {#PY}
```
public static final FileType PY
```


Représente un script Python (.py).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/programming/py).


### RB {#RB}
```
public static final FileType RB
```


Représente un fichier de code source Ruby (.rb).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/programming/rb).


### RST {#RST}
```
public static final FileType RST
```


Représente un fichier reStructuredText (.rst).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/programming/rst).


### SASS {#SASS}
```
public static final FileType SASS
```


Représente un fichier Syntactically Awesome StyleSheets (.sass).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/web/sass).


### SCALA {#SCALA}
```
public static final FileType SCALA
```


Représente un fichier de code source Scala (.scala).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/programming/scala).


### SCM {#SCM}
```
public static final FileType SCM
```


Représente un fichier de code source Scheme (.scm).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/programming/scm).


### SCRIPT {#SCRIPT}
```
public static final FileType SCRIPT
```


Représente un fichier de script générique (.script).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/programming/script).


### SH {#SH}
```
public static final FileType SH
```


Représente un script Bash Shell (.sh).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/cs/programming/sh).


### SML {#SML}
```
public static final FileType SML
```


Représente un fichier de code source Standard ML (.sml).
En savoir plus sur ce format de fichier [ici](../https://fileinfo.com/extension/sml).


### SQL {#SQL}
```
public static final FileType SQL
```


Représente un fichier de données Structured Query Language (.sql).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/database/sql).


### VIM {#VIM}
```
public static final FileType VIM
```


Représente un fichier de paramètres Vim (.vim).
En savoir plus sur ce format de fichier [ici](../https://fileinfo.com/extension/vim).


### YAML {#YAML}
```
public static final FileType YAML
```


Représente un document YAML (.yaml).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/programming/yaml).


### DOC {#DOC}
```
public static final FileType DOC
```


Représente un fichier Microsoft Word Document (.doc).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/word-processing/doc).


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Représente un fichier Microsoft Word Open XML Document (.docx).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/word-processing/docx).


### CHM {#CHM}
```
public static final FileType CHM
```


Représente un fichier Microsoft Compiled HTML Help (.chm).
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/web/chm).


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Représente un fichier Word Open XML Macro-Enabled Document (.docm).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/word-processing/docm).


### DOT {#DOT}
```
public static final FileType DOT
```


Représente un fichier Word Document Template (.dot).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/word-processing/dot).


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Représente un fichier Word Open XML Document Template (.dotx).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/word-processing/dotx).


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Représente un fichier Word Open XML Macro-Enabled Document Template (.dotm).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/word-processing/dotm).


### RTF {#RTF}
```
public static final FileType RTF
```


Représente un fichier Rich Text Format (.rtf).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/word-processing/rtf).


### TXT {#TXT}
```
public static final FileType TXT
```


Représente un fichier texte brut (.txt).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/word-processing/txt).


### ODT {#ODT}
```
public static final FileType ODT
```


Représente un document texte OpenDocument (.odt).
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/word-processing/odt).


### OTT {#OTT}
```
public static final FileType OTT
```


Représente un modèle de document OpenDocument (.ott).
Il s'agit d'un document modèle généré conformément au format standard OpenDocument d'OASIS.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/word-processing/ott).


### VCF {#VCF}
```
public static final FileType VCF
```


Représente un fichier vCard (.vcf), qui est un format de fichier numérique pour stocker des informations de contact.
Il est largement utilisé pour l'échange de données entre les applications d'échange d'informations populaires.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/email/vcf).


### AI {#AI}
```
public static final FileType AI
```


Représente un fichier Adobe Illustrator (.ai), qui est un format de fichier pour les dessins Adobe Illustrator.
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/image/ai).


### PSM1 {#PSM1}
```
public static final FileType PSM1
```


Représente un fichier module de script PowerShell (.psm1).
Il s'agit d'un format de fichier pour les scripts de module PowerShell.
En savoir plus sur ce format de fichier [ici](../https://fileinfo.com/extension/psm1).


### PS1 {#PS1}
```
public static final FileType PS1
```


Représente un fichier script PowerShell (.ps1).
Il s'agit d'un format de fichier pour les fichiers Cmdlet de Windows PowerShell.
En savoir plus sur ce format de fichier [ici](../https://fileinfo.com/extension/ps1).


### PSD1 {#PSD1}
```
public static final FileType PSD1
```


Représente un fichier manifeste de module de script PowerShell (.psd1).
Il s'agit d'un format de fichier pour les scripts de manifeste de module PowerShell.
En savoir plus sur ce format de fichier [ici](../https://fileinfo.com/extension/psd1).


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
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


Mappe une extension de fichier à un type de fichier.


Cette méthode accepte une extension de fichier, avec ou sans le point ".", et renvoie le type de fichier correspondant s'il est pris en charge.
Si le type de fichier n'est pas pris en charge, il renvoie le type de fichier par défaut [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | extension | java.lang.String | L'extension de fichier avec ou sans le point ".". |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromFilePath(String filePath) {#fromFilePath-java.lang.String-}
```
public static FileType fromFilePath(String filePath)
```


Extrait l'extension du fichier d'un nom de fichier ou d'un chemin d'accès et la mappe à un type de fichier.


Si le type de fichier est pris en charge, la méthode renvoie le correspondant
FileType
,
sinon, il renvoie le type de fichier par défaut [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le nom du fichier ou le chemin du fichier. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromMediaType(String mediaType) {#fromMediaType-java.lang.String-}
```
public static FileType fromMediaType(String mediaType)
```


Mappe un type de média de fichier à un type de fichier. Par exemple, 'application/pdf' sera mappé à [PDF](../../com.groupdocs.viewer/filetype#PDF).


Cette méthode prend un type de média de fichier en entrée et le mappe au correspondant
FileType
. Si le type de média est
pris en charge, la méthode renvoie le type de fichier correspondant. Si le type de média n'est pas pris en charge, il renvoie le défaut
[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | mediaType | java.lang.String | Le type de média du fichier, par ex., 'application/pdf'. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if found, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream stream)
```


Détecte le type de fichier en lisant la signature du fichier.


Cette méthode prend un flux d'entrée représentant un fichier et tente de détecter son type de fichier en analysant la signature du fichier. Le
La signature du fichier est une séquence unique d'octets au début du fichier qui indique son type de fichier. La méthode
lit la signature du fichier depuis le flux d'entrée et la compare aux signatures de fichiers connues des types de fichiers pris en charge.
Si une correspondance est trouvée, la méthode renvoie le type de fichier correspondant. Si aucune correspondance n'est trouvée, elle renvoie le défaut
[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | stream | java.io.InputStream | Le flux d'entrée représentant le fichier. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, String password) {#fromStream-java.io.InputStream-java.lang.String-}
```
public static FileType fromStream(InputStream stream, String password)
```


Détecte le type de fichier en lisant la signature du fichier.


Cette méthode analyse la signature du fichier, qui est une séquence unique d'octets au début du fichier, afin de déterminer
le type de fichier. Elle lit la signature du fichier depuis le flux d'entrée fourni et la compare aux signatures de fichiers connues
des types de fichiers pris en charge. Si une correspondance est trouvée, la méthode renvoie le type de fichier correspondant. Si aucune correspondance n'est trouvée, elle
renvoie le type de fichier par défaut [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN).


Si le fichier est chiffré et nécessite un mot de passe pour l'ouvrir, le mot de passe doit être fourni en tant que paramètre à cette
méthode. Le mot de passe sera utilisé pour déchiffrer le fichier et analyser sa signature afin de déterminer le type de fichier.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | stream | java.io.InputStream | Le flux d'entrée représentant le fichier. |
|
|  | mot de passe | java.lang.String | Le mot de passe pour ouvrir le fichier. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, ILogger logger) {#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, ILogger logger)
```


Détecte le type de fichier en lisant la signature du fichier.


Cette méthode analyse la signature du fichier, qui est une séquence unique d'octets au début du fichier, afin de déterminer
le type de fichier. Elle lit la signature du fichier depuis le flux d'entrée fourni et la compare aux signatures de fichiers connues
des types de fichiers pris en charge. Si une correspondance est trouvée, la méthode renvoie le type de fichier correspondant. Si aucune correspondance n'est trouvée, elle
renvoie le type de fichier par défaut [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN).


Un journaliseur peut être fourni pour consigner toute information pertinente ou toute erreur pendant le processus de détection du type de fichier. Le journaliseur
doit implémenter l'interface ILogger. Si aucun journaliseur n'est fourni, le processus de détection ne produira aucun
sortie de journal.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | stream | java.io.InputStream | Le flux d'entrée représentant le fichier. |
|
|  | logger | com.groupdocs.foundation.logging.ILogger | Le journaliseur pour consigner les informations ou les erreurs. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, String password, ILogger logger) {#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, String password, ILogger logger)
```


Détecte le type de fichier en lisant la signature du fichier.


Cette méthode analyse la signature du fichier, qui est une séquence unique d'octets au début du fichier, afin de déterminer
le type de fichier. Elle lit la signature du fichier depuis le flux d'entrée fourni et la compare aux signatures de fichiers connues
des types de fichiers pris en charge. Si une correspondance est trouvée, la méthode renvoie le type de fichier correspondant. Si aucune correspondance n'est trouvée, elle
renvoie le type de fichier par défaut [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN).


Un mot de passe peut être fourni si le fichier est chiffré ou protégé. Le mot de passe sera utilisé pour ouvrir le fichier avant
d'analyser la signature du fichier. Si le fichier ne nécessite pas de mot de passe, ce paramètre peut être mis à null.


Un journaliseur peut être fourni pour consigner toute information pertinente ou toute erreur pendant le processus de détection du type de fichier. Le journaliseur
doit implémenter l'interface ILogger. Si aucun journaliseur n'est fourni, le processus de détection ne produira aucun
sortie de journal.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | stream | java.io.InputStream | Le flux d'entrée représentant le fichier. |
|
|  | mot de passe | java.lang.String | Le mot de passe pour ouvrir le fichier. |
|
|  | logger | com.groupdocs.foundation.logging.ILogger | Le journaliseur pour consigner les informations ou les erreurs. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Récupère les types de fichiers pris en charge.


Cette méthode renvoie une séquence de tous les types de fichiers pris en charge par le système. Les types de fichiers représentent divers
formats de documents qui peuvent être traités ou reconnus par le système.
***Learn more**
* Learn more about the supported document formats: [Full list of supported file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/)*


**Returns:**
java.util.List<com.groupdocs.viewer.FileType> - une séquence de types de fichiers pris en charge.

### detectCharset(String filePath) {#detectCharset-java.lang.String-}
```
public static Charset detectCharset(String filePath)
```


Tente de détecter le jeu de caractères des fichiers texte [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV), et [CSV](../../com.groupdocs.viewer/filetype#CSV) par chemin.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le nom du fichier ou le chemin du fichier. |
|

**Returns:**
java.nio.charset.Charset - Jeu de caractères ou null lorsqu'il échoue à détecter le jeu de caractères d'un fichier.

**Example:**


Charset charset = FileType.detectCharset(\"message.txt\");
     

### detectCharset(InputStream stream) {#detectCharset-java.io.InputStream-}
```
public static Charset detectCharset(InputStream stream)
```


Tente de détecter le jeu de caractères du fichier texte [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV), et [CSV](../../com.groupdocs.viewer/filetype#CSV) par flux.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | stream | java.io.InputStream | Le flux de fichier. |
|

**Returns:**
java.nio.charset.Charset - Jeu de caractères ou null lorsqu'il échoue à détecter le jeu de caractères d'un fichier.

**Example:**


InputStream stream = new FileInputStream(\"message.txt\");
Charset charset = FileType.detectCharset(stream);
     

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Obtient le nom du format de fichier, par ex., "Microsoft Word Document".


**Returns:**
java.lang.String - le nom du format de fichier.

### getExtension() {#getExtension--}
```
public final String getExtension()
```


Obtient le suffixe d'extension de fichier (y compris le point "."), par ex., ".doc".


**Returns:**
java.lang.String - le suffixe d'extension de fichier.

### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne de l'objet actuel.


**Returns:**
java.lang.String - une représentation sous forme de chaîne de l'objet actuel.

