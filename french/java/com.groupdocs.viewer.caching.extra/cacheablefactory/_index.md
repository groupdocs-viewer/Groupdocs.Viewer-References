---
title: "CacheableFactory"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Cette classe aide à personnaliser."
type: docs
weight: 10
url: /fr/java/com.groupdocs.viewer.caching.extra/cacheablefactory/
---
**Inheritance:**
java.lang.Object
```
public class CacheableFactory
```

Cette classe aide à personnaliser [Cache](../../com.groupdocs.viewer.caching/cache).


Des modèles personnalisés pour la sérialisation peuvent être implémentés en surchargeant les méthodes de cette classe afin de les renvoyer à la place de ceux intégrés.
Pour ce faire, étendez CacheableFactory et activez‑le en passant une nouvelle instance de la fabrique personnalisée à la méthode [setInstance(CacheableFactory)](../../com.groupdocs.viewer.caching.extra/cacheablefactory#setInstance-CacheableFactory-) .


Exemple d'utilisation :

````

 CacheableFactory.setInstance(new YourCustomCacheableFactory());
 // Custom cacheable factory is now in use. You can start rendering documents.
 
````


Pour plus de détails, de directives et d'exemples sur la personnalisation du cache, veuillez vous référer à la
[GroupDocs.Viewer documentation](../https://docs.groupdocs.com/viewer/java/getting-started/).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CacheableFactory()](#CacheableFactory--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getInstance()](#getInstance--) | Obtient une instance de |
CacheableFactory
qui peut être utilisée pour créer des objets cacheables.
|
|  | [setInstance(CacheableFactory instance)](#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-) | Définit l'instance de |
CacheableFactory
à utiliser.
|
|  | [newViewInfo(FileType fileType, List<Page> pages)](#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--) | Crée une implémentation de l'interface [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) pour le type de fichier et les pages spécifiés. |
|
| [newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from)](#newEmailViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.lang.String-java.lang.String-) |  |
|  | [newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Crée une implémentation de l'interface [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) pour le type de fichier, les pages et le nombre de notes spécifiés. |
|
|  | [newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Crée une implémentation de l'interface [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) pour le type de fichier, les pages et les dossiers spécifiés. |
|
|  | [newCharacter(char character, double x, double y, double width, double height)](#newCharacter-char-double-double-double-double-) | Crée une implémentation de l'interface [Character](../../com.groupdocs.viewer.results/character) pour le caractère, la position et les dimensions spécifiés. |
|
|  | [newFileInfo(FileType fileType)](#newFileInfo-com.groupdocs.viewer.FileType-) | Crée une implémentation de l'interface [FileInfo](../../com.groupdocs.viewer.results/fileinfo) pour le type de fichier spécifié. |
|
|  | [newLayer(String name, boolean visible)](#newLayer-java.lang.String-boolean-) | Crée une implémentation de l'interface [Layer](../../com.groupdocs.viewer.results/layer) avec le nom et la visibilité spécifiés. |
|
|  | [newLayer(String name)](#newLayer-java.lang.String-) | Crée une implémentation de l'interface [Layer](../../com.groupdocs.viewer.results/layer) avec le nom spécifié. |
|
|  | [newLayout(String name, double width, double height)](#newLayout-java.lang.String-double-double-) | Crée une implémentation de l'interface [Layout](../../com.groupdocs.viewer.results/layout) avec le nom, la largeur et la hauteur spécifiés. |
|
|  | [newLine(String line, double x, double y, double width, double height, List<Word> words)](#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--) | Crée une implémentation de l'interface [Line](../../com.groupdocs.viewer.results/line) avec la ligne, la position, les dimensions et les mots spécifiés. |
|
|  | [newAttachment(String fileName, String filePath)](#newAttachment-java.lang.String-java.lang.String-) | Crée une implémentation de l'interface [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newAttachment(String id, String fileName, String filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-) | Crée une implémentation de l'interface [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newAttachment(String id, String fileName, Path filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-) | Crée une implémentation de l'interface [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newAttachment(String id, String fileName, String filePath, FileType fileType, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-) | Crée une implémentation de l'interface [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Crée une implémentation de l'interface [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) basée sur le type de fichier spécifié, |
liste de pages et liste de dossiers.
|
|  | [newPage(int number, boolean visible)](#newPage-int-boolean-) | Crée une implémentation de l'interface [Page](../../com.groupdocs.viewer.results/page) représentant une page avec le numéro et la visibilité spécifiés. |
|
|  | [newPage(int number, String name, boolean visible)](#newPage-int-java.lang.String-boolean-) | Crée une implémentation de l'interface [Page](../../com.groupdocs.viewer.results/page) représentant une page avec le numéro, le nom et la visibilité spécifiés. |
|
|  | [newPage(int number, String name, boolean visible, int width, int height)](#newPage-int-java.lang.String-boolean-int-int-) | Crée une implémentation de l'interface [Page](../../com.groupdocs.viewer.results/page) représentant une page avec le numéro, le nom, la visibilité, la largeur et la hauteur spécifiés. |
|
|  | [newPage(int number, boolean visible, int width, int height)](#newPage-int-boolean-int-int-) | Crée une implémentation de l'interface [Page](../../com.groupdocs.viewer.results/page) représentant une page avec le numéro, la visibilité, la largeur et la hauteur spécifiés. |
|
|  | [newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)](#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Crée une implémentation de l'interface [Page](../../com.groupdocs.viewer.results/page) représentant une page avec le numéro, le nom, la visibilité, la largeur, la hauteur et les lignes spécifiés. |
|
|  | [newPage(int number, boolean visible, int width, int height, List<Line> lines)](#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Crée une implémentation de l'interface [Page](../../com.groupdocs.viewer.results/page) représentant une page avec le numéro, la visibilité, la largeur, la hauteur et les lignes spécifiés. |
|
|  | [newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)](#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-) | Crée une implémentation de l'interface [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) avec le type de fichier, les pages et le drapeau d'autorisation d'impression spécifiés. |
|
|  | [newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)](#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--) | Crée une implémentation de l'interface [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) avec le type de fichier, les pages, les calques et les mises en page spécifiés. |
|
|  | [newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)](#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-) | Crée une implémentation de l'interface [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) avec le type de fichier, les pages, la date de début et la date de fin spécifiés. |
|
|  | [<T>newTextElement(T value, double x, double y, double width, double height)](#-T-newTextElement-T-double-double-double-double-) | Crée une implémentation de l'interface [TextElement](../../com.groupdocs.viewer.results/textelement) avec la valeur, les coordonnées et les dimensions spécifiées. |
|
|  | [newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Crée une implémentation de l'interface MboxViewInfo avec le type de fichier, les pages et le nombre de notes spécifiés. |
|
|  | [newWord(String word, double x, double y, double width, double height, List<Character> characters)](#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--) | Crée une implémentation de l'interface [Word](../../com.groupdocs.viewer.results/word) avec le mot, les coordonnées, les dimensions et les caractères spécifiés. |
|
### CacheableFactory() {#CacheableFactory--}
```
public CacheableFactory()
```


### getInstance() {#getInstance--}
```
public static CacheableFactory getInstance()
```


Obtient une instance de
CacheableFactory
qui peut être utilisée pour créer des objets cacheables.


**Returns:**
[CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) - an instance of  CacheableFactory .

### setInstance(CacheableFactory instance) {#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-}
```
public static void setInstance(CacheableFactory instance)
```


Définit l'instance de
CacheableFactory
à utiliser. Cela permet une implémentation personnalisée de la fabrique mise en cache.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | instance | [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) | L'instance de  CacheableFactory  à définir. |
|

### newViewInfo(FileType fileType, List<Page> pages) {#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--}
```
public ViewInfo newViewInfo(FileType fileType, List<Page> pages)
```


Crée une implémentation de l'interface [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) pour le type de fichier et les pages spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Le type de fichier. |
|
|  | pages | java.util.List<com.groupdocs.viewer.results.Page> | La liste des pages représentant les pages du document. |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - a new instance of the [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) implementation.

### newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from) {#newEmailViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.lang.String-java.lang.String-}
```
public ViewInfo newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) |  |
| pages | java.util.List<com.groupdocs.viewer.results.Page> |  |
| originalMessageDate | java.util.Date |  |
| sujet | java.lang.String |  |
| de | java.lang.String |  |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
### newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public LotusNotesViewInfo newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Crée une implémentation de l'interface [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) pour le type de fichier, les pages et le nombre de notes spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Le type de fichier. |
|
|  | pages | java.util.List<com.groupdocs.viewer.results.Page> | La liste des pages représentant les pages du document. |
|
|  | notesCount | int | Le nombre de Lotus Notes dans le document. |
|

**Returns:**
[LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) - a new instance of the [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) implementation.

### newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public ArchiveViewInfo newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Crée une implémentation de l'interface [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) pour le type de fichier, les pages et les dossiers spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Le type de fichier. |
|
|  | pages | java.util.List<com.groupdocs.viewer.results.Page> | La liste des pages représentant les pages du document. |
|
|  | dossiers | java.util.List<java.lang.String> | La liste des dossiers dans l'archive. |
|

**Returns:**
[ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) - a new instance of the [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) implementation.

### newCharacter(char character, double x, double y, double width, double height) {#newCharacter-char-double-double-double-double-}
```
public Character newCharacter(char character, double x, double y, double width, double height)
```


Crée une implémentation de l'interface [Character](../../com.groupdocs.viewer.results/character) pour le caractère, la position et les dimensions spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | caractère | char | Le caractère. |
|
|  | x | double | La coordonnée x de la position du caractère. |
|
|  | y | double | La coordonnée y de la position du caractère. |
|
|  | width | double | La largeur du caractère. |
|
|  | hauteur | double | La hauteur du caractère. |
|

**Returns:**
[Character](../../com.groupdocs.viewer.results/character) - a new instance of the [Character](../../com.groupdocs.viewer.results/character) implementation.

### newFileInfo(FileType fileType) {#newFileInfo-com.groupdocs.viewer.FileType-}
```
public FileInfo newFileInfo(FileType fileType)
```


Crée une implémentation de l'interface [FileInfo](../../com.groupdocs.viewer.results/fileinfo) pour le type de fichier spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Le type de fichier. |
|

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - a new instance of the [FileInfo](../../com.groupdocs.viewer.results/fileinfo) implementation.

### newLayer(String name, boolean visible) {#newLayer-java.lang.String-boolean-}
```
public Layer newLayer(String name, boolean visible)
```


Crée une implémentation de l'interface [Layer](../../com.groupdocs.viewer.results/layer) avec le nom et la visibilité spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nom | java.lang.String | Le nom du calque. |
|
|  | visible | boolean | La visibilité du calque. |
|

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.

### newLayer(String name) {#newLayer-java.lang.String-}
```
public Layer newLayer(String name)
```


Crée une implémentation de l'interface [Layer](../../com.groupdocs.viewer.results/layer) avec le nom spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nom | java.lang.String | Le nom du calque. |
|

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.

### newLayout(String name, double width, double height) {#newLayout-java.lang.String-double-double-}
```
public Layout newLayout(String name, double width, double height)
```


Crée une implémentation de l'interface [Layout](../../com.groupdocs.viewer.results/layout) avec le nom, la largeur et la hauteur spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nom | java.lang.String | Le nom de la mise en page. |
|
|  | width | double | La largeur de la mise en page. |
|
|  | hauteur | double | La hauteur de la mise en page. |
|

**Returns:**
[Layout](../../com.groupdocs.viewer.results/layout) - a new instance of the [Layout](../../com.groupdocs.viewer.results/layout) implementation.

### newLine(String line, double x, double y, double width, double height, List<Word> words) {#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--}
```
public Line newLine(String line, double x, double y, double width, double height, List<Word> words)
```


Crée une implémentation de l'interface [Line](../../com.groupdocs.viewer.results/line) avec la ligne, la position, les dimensions et les mots spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | ligne | java.lang.String | Le contenu de la ligne. |
|
|  | x | double | La coordonnée X du point supérieur gauche du rectangle qui contient la ligne. |
|
|  | y | double | La coordonnée Y du point supérieur gauche du rectangle qui contient la ligne. |
|
|  | width | double | La largeur du rectangle qui contient la ligne (en pixels). |
|
|  | hauteur | double | La hauteur du rectangle qui contient la ligne (en pixels). |
|
|  | mots | java.util.List<com.groupdocs.viewer.results.Word> | Les mots contenus dans la ligne. |
|

**Returns:**
[Line](../../com.groupdocs.viewer.results/line) - a new instance of the [Line](../../com.groupdocs.viewer.results/line) implementation.

### newAttachment(String fileName, String filePath) {#newAttachment-java.lang.String-java.lang.String-}
```
public Attachment newAttachment(String fileName, String filePath)
```


Crée une implémentation de l'interface [Attachment](../../com.groupdocs.viewer.results/attachment).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileName | java.lang.String | Le nom de la pièce jointe. |
|
|  | filePath | java.lang.String | Le chemin relatif de la pièce jointe, par exemple "folder/file.docx". Lorsque le fichier se trouve à la racine d'une archive, dans un message électronique ou dans un fichier de données, indiquez le nom du fichier. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, String filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, long size)
```


Crée une implémentation de l'interface [Attachment](../../com.groupdocs.viewer.results/attachment).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | id | java.lang.String | L'ID de la pièce jointe. |
|
|  | fileName | java.lang.String | Le nom de la pièce jointe. |
|
|  | filePath | java.lang.String | Le chemin relatif de la pièce jointe, par exemple "folder/file.docx". Lorsque le fichier se trouve à la racine d'une archive, dans un message électronique ou dans un fichier de données, indiquez le nom du fichier. |
|
|  | size | long | La taille de la pièce jointe. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, Path filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-}
```
public Attachment newAttachment(String id, String fileName, Path filePath, long size)
```


Crée une implémentation de l'interface [Attachment](../../com.groupdocs.viewer.results/attachment).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | id | java.lang.String | L'ID de la pièce jointe. |
|
|  | fileName | java.lang.String | Le nom de la pièce jointe. |
|
|  | filePath | java.nio.file.Path | Le chemin relatif ou absolu de la pièce jointe. |
|
|  | size | long | La taille de la pièce jointe. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, String filePath, FileType fileType, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, FileType fileType, long size)
```


Crée une implémentation de l'interface [Attachment](../../com.groupdocs.viewer.results/attachment). La pièce jointe représente un fichier attaché à un document ou à un message électronique.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | id | java.lang.String | L'ID de la pièce jointe. |
|
|  | fileName | java.lang.String | Le nom de la pièce jointe. |
|
|  | filePath | java.lang.String | Le chemin relatif ou absolu de la pièce jointe. Il peut s'agir d'un chemin de fichier dans un dossier ou du nom du fichier lui‑même si le fichier se trouve à la racine d'une archive, dans un message électronique ou dans un fichier de données. |
|
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Le type du fichier de la pièce jointe. |
|
|  | size | long | La taille de la pièce jointe. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public OutlookViewInfo newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Crée une implémentation de l'interface [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) basée sur le type de fichier spécifié,
liste de pages et liste de dossiers.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Le type de fichier. |
|
|  | pages | java.util.List<com.groupdocs.viewer.results.Page> | La liste des pages. |
|
|  | dossiers | java.util.List<java.lang.String> | La liste des dossiers. |
|

**Returns:**
[OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) - a new instance of the [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) implementation.

### newPage(int number, boolean visible) {#newPage-int-boolean-}
```
public Page newPage(int number, boolean visible)
```


Crée une implémentation de l'interface [Page](../../com.groupdocs.viewer.results/page) représentant une page avec le numéro et la visibilité spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nombre | int | Le numéro de page. |
|
|  | visible | boolean | Le drapeau de visibilité. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible) {#newPage-int-java.lang.String-boolean-}
```
public Page newPage(int number, String name, boolean visible)
```


Crée une implémentation de l'interface [Page](../../com.groupdocs.viewer.results/page) représentant une page avec le numéro, le nom et la visibilité spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nombre | int | Le numéro de page. |
|
|  | nom | java.lang.String | Le nom de la page. |
|
|  | visible | boolean | Le drapeau de visibilité. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible, int width, int height) {#newPage-int-java.lang.String-boolean-int-int-}
```
public Page newPage(int number, String name, boolean visible, int width, int height)
```


Crée une implémentation de l'interface [Page](../../com.groupdocs.viewer.results/page) représentant une page avec le numéro, le nom, la visibilité, la largeur et la hauteur spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nombre | int | Le numéro de page. |
|
|  | nom | java.lang.String | Le nom de la page. |
|
|  | visible | boolean | Le drapeau de visibilité. |
|
|  | width | int | La largeur de la page. |
|
|  | hauteur | int | La hauteur de la page. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, boolean visible, int width, int height) {#newPage-int-boolean-int-int-}
```
public Page newPage(int number, boolean visible, int width, int height)
```


Crée une implémentation de l'interface [Page](../../com.groupdocs.viewer.results/page) représentant une page avec le numéro, la visibilité, la largeur et la hauteur spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nombre | int | Le numéro de page. |
|
|  | visible | boolean | Le drapeau de visibilité. |
|
|  | width | int | La largeur de la page. |
|
|  | hauteur | int | La hauteur de la page. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible, int width, int height, List<Line> lines) {#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)
```


Crée une implémentation de l'interface [Page](../../com.groupdocs.viewer.results/page) représentant une page avec le numéro, le nom, la visibilité, la largeur, la hauteur et les lignes spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nombre | int | Le numéro de page. |
|
|  | nom | java.lang.String | Le nom de la page. |
|
|  | visible | boolean | Le drapeau de visibilité. |
|
|  | width | int | La largeur de la page. |
|
|  | hauteur | int | La hauteur de la page. |
|
|  | lignes | java.util.List<com.groupdocs.viewer.results.Line> | Les lignes contenues dans la page. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, boolean visible, int width, int height, List<Line> lines) {#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, boolean visible, int width, int height, List<Line> lines)
```


Crée une implémentation de l'interface [Page](../../com.groupdocs.viewer.results/page) représentant une page avec le numéro, la visibilité, la largeur, la hauteur et les lignes spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nombre | int | Le numéro de page. |
|
|  | visible | boolean | Le drapeau de visibilité. |
|
|  | width | int | La largeur de la page. |
|
|  | hauteur | int | La hauteur de la page. |
|
|  | lignes | java.util.List<com.groupdocs.viewer.results.Line> | Les lignes contenues dans la page. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed) {#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-}
```
public PdfViewInfo newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)
```


Crée une implémentation de l'interface [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) avec le type de fichier, les pages et le drapeau d'autorisation d'impression spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Le type de fichier. |
|
|  | pages | java.util.List<com.groupdocs.viewer.results.Page> | La liste des pages. |
|
|  | printingAllowed | boolean | Le drapeau indiquant si l'impression est autorisée. |
|

**Returns:**
[PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) - a new instance of the [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) implementation.

### newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts) {#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--}
```
public CadViewInfo newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```


Crée une implémentation de l'interface [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) avec le type de fichier, les pages, les calques et les mises en page spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Le type de fichier. |
|
|  | pages | java.util.List<com.groupdocs.viewer.results.Page> | La liste des pages. |
|
|  | layers | java.util.List<com.groupdocs.viewer.results.Layer> | La liste des couches. |
|
|  | layouts | java.util.List<com.groupdocs.viewer.results.Layout> | La liste des mises en page. |
|

**Returns:**
[CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) - a new instance of the [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) implementation.

### newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate) {#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-}
```
public ProjectManagementViewInfo newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)
```


Crée une implémentation de l'interface [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) avec le type de fichier, les pages, la date de début et la date de fin spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Le type de fichier. |
|
|  | pages | java.util.List<com.groupdocs.viewer.results.Page> | La liste des pages. |
|
|  | startDate | java.util.Date | La date de début. |
|
|  | endDate | java.util.Date | La date de fin. |
|

**Returns:**
[ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) - a new instance of the [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) implementation.

### <T>newTextElement(T value, double x, double y, double width, double height) {#-T-newTextElement-T-double-double-double-double-}
```
public TextElement<T> <T>newTextElement(T value, double x, double y, double width, double height)
```


Crée une implémentation de l'interface [TextElement](../../com.groupdocs.viewer.results/textelement) avec la valeur, les coordonnées et les dimensions spécifiées.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | T | La valeur. |
|
|  | x | double | La coordonnée X. |
|
|  | y | double | La coordonnée Y. |
|
|  | width | double | La largeur. |
|
|  | hauteur | double | La hauteur. |
|

**Returns:**
[TextElement](../../com.groupdocs.viewer.results/textelement) - a new instance of the [TextElement](../../com.groupdocs.viewer.results/textelement) implementation.

### newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public MboxViewInfo newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Crée une implémentation de l'interface MboxViewInfo avec le type de fichier, les pages et le nombre de notes spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Le type du fichier. |
|
|  | pages | java.util.List<com.groupdocs.viewer.results.Page> | La liste des pages à afficher. |
|
|  | notesCount | int | Le nombre de notes contenues dans le fichier de stockage de base de données Lotus. |
|

**Returns:**
com.groupdocs.viewer.results.MboxViewInfo - une nouvelle instance de l'implémentation de MboxViewInfo.

### newWord(String word, double x, double y, double width, double height, List<Character> characters) {#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--}
```
public Word newWord(String word, double x, double y, double width, double height, List<Character> characters)
```


Crée une implémentation de l'interface [Word](../../com.groupdocs.viewer.results/word) avec le mot, les coordonnées, les dimensions et les caractères spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | word | java.lang.String | Le mot. |
|
|  | x | double | La coordonnée X du point le plus haut à gauche de la mise en page où commence le rectangle contenant le mot. |
|
|  | y | double | La coordonnée Y du point le plus haut à gauche de la mise en page où commence le rectangle contenant le mot. |
|
|  | width | double | La largeur du rectangle qui contient le mot (en pixels). |
|
|  | hauteur | double | La hauteur du rectangle qui contient le mot (en pixels). |
|
|  | caractères | java.util.List<com.groupdocs.viewer.results.Character> | Les caractères contenus par le mot. |
|

**Returns:**
[Word](../../com.groupdocs.viewer.results/word) - a new instance of the [Word](../../com.groupdocs.viewer.results/word) implementation.

