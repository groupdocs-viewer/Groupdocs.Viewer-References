---
title: "CacheableFactory"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Esta clase ayuda a personalizar ."
type: docs
weight: 10
url: /es/java/com.groupdocs.viewer.caching.extra/cacheablefactory/
---
**Inheritance:**
java.lang.Object
```
public class CacheableFactory
```

Esta clase ayuda a personalizar [Cache](../../com.groupdocs.viewer.caching/cache).


Los modelos personalizados para serialización pueden implementarse sobrescribiendo métodos en esta clase para devolverlos en lugar de los integrados.
Para lograr esto, extienda CacheableFactory y actívelo pasando una nueva instancia de la fábrica personalizada al método [setInstance(CacheableFactory)](../../com.groupdocs.viewer.caching.extra/cacheablefactory#setInstance-CacheableFactory-).


Ejemplo de uso:

````

 CacheableFactory.setInstance(new YourCustomCacheableFactory());
 // Custom cacheable factory is now in use. You can start rendering documents.
 
````


Para más detalles, pautas y ejemplos sobre la personalización de la caché, consulte el
[GroupDocs.Viewer documentation](../https://docs.groupdocs.com/viewer/java/getting-started/).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [CacheableFactory()](#CacheableFactory--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getInstance()](#getInstance--) | Obtiene una instancia de |
CacheableFactory
que puede usarse para crear objetos almacenables en caché.
|
|  | [setInstance(CacheableFactory instance)](#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-) | Establece la instancia de |
CacheableFactory
para ser utilizada.
|
|  | [newViewInfo(FileType fileType, List<Page> pages)](#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--) | Crea una implementación de la interfaz [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) para el tipo de archivo y páginas especificados. |
|
| [newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from)](#newEmailViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.lang.String-java.lang.String-) |  |
|  | [newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Crea una implementación de la interfaz [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) para el tipo de archivo, páginas y recuento de notas especificados. |
|
|  | [newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Crea una implementación de la interfaz [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) para el tipo de archivo, páginas y carpetas especificados. |
|
|  | [newCharacter(char character, double x, double y, double width, double height)](#newCharacter-char-double-double-double-double-) | Crea una implementación de la interfaz [Character](../../com.groupdocs.viewer.results/character) para el carácter, posición y dimensiones especificados. |
|
|  | [newFileInfo(FileType fileType)](#newFileInfo-com.groupdocs.viewer.FileType-) | Crea una implementación de la interfaz [FileInfo](../../com.groupdocs.viewer.results/fileinfo) para el tipo de archivo especificado. |
|
|  | [newLayer(String name, boolean visible)](#newLayer-java.lang.String-boolean-) | Crea una implementación de la interfaz [Layer](../../com.groupdocs.viewer.results/layer) con el nombre y la visibilidad especificados. |
|
|  | [newLayer(String name)](#newLayer-java.lang.String-) | Crea una implementación de la interfaz [Layer](../../com.groupdocs.viewer.results/layer) con el nombre especificado. |
|
|  | [newLayout(String name, double width, double height)](#newLayout-java.lang.String-double-double-) | Crea una implementación de la interfaz [Layout](../../com.groupdocs.viewer.results/layout) con el nombre, el ancho y la altura especificados. |
|
|  | [newLine(String line, double x, double y, double width, double height, List<Word> words)](#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--) | Crea una implementación de la interfaz [Line](../../com.groupdocs.viewer.results/line) con la línea, la posición, las dimensiones y las palabras especificadas. |
|
|  | [newAttachment(String fileName, String filePath)](#newAttachment-java.lang.String-java.lang.String-) | Crea una implementación de la interfaz [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newAttachment(String id, String fileName, String filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-) | Crea una implementación de la interfaz [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newAttachment(String id, String fileName, Path filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-) | Crea una implementación de la interfaz [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newAttachment(String id, String fileName, String filePath, FileType fileType, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-) | Crea una implementación de la interfaz [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Crea una implementación de la interfaz [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) basada en el tipo de archivo especificado, |
lista de páginas y lista de carpetas.
|
|  | [newPage(int number, boolean visible)](#newPage-int-boolean-) | Crea una implementación de la interfaz [Page](../../com.groupdocs.viewer.results/page) que representa una página con el número y la visibilidad especificados. |
|
|  | [newPage(int number, String name, boolean visible)](#newPage-int-java.lang.String-boolean-) | Crea una implementación de la interfaz [Page](../../com.groupdocs.viewer.results/page) que representa una página con el número, el nombre y la visibilidad especificados. |
|
|  | [newPage(int number, String name, boolean visible, int width, int height)](#newPage-int-java.lang.String-boolean-int-int-) | Crea una implementación de la interfaz [Page](../../com.groupdocs.viewer.results/page) que representa una página con el número, el nombre, la visibilidad, el ancho y la altura especificados. |
|
|  | [newPage(int number, boolean visible, int width, int height)](#newPage-int-boolean-int-int-) | Crea una implementación de la interfaz [Page](../../com.groupdocs.viewer.results/page) que representa una página con el número, la visibilidad, el ancho y la altura especificados. |
|
|  | [newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)](#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Crea una implementación de la interfaz [Page](../../com.groupdocs.viewer.results/page) que representa una página con el número, el nombre, la visibilidad, el ancho, la altura y las líneas especificados. |
|
|  | [newPage(int number, boolean visible, int width, int height, List<Line> lines)](#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Crea una implementación de la interfaz [Page](../../com.groupdocs.viewer.results/page) que representa una página con el número, la visibilidad, el ancho, la altura y las líneas especificados. |
|
|  | [newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)](#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-) | Crea una implementación de la interfaz [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) con el tipo de archivo, las páginas y la bandera de impresión permitida especificados. |
|
|  | [newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)](#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--) | Crea una implementación de la interfaz [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) con el tipo de archivo, las páginas, las capas y los diseños especificados. |
|
|  | [newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)](#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-) | Crea una implementación de la interfaz [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) con el tipo de archivo, las páginas, la fecha de inicio y la fecha de finalización especificados. |
|
|  | [<T>newTextElement(T value, double x, double y, double width, double height)](#-T-newTextElement-T-double-double-double-double-) | Crea una implementación de la interfaz [TextElement](../../com.groupdocs.viewer.results/textelement) con el valor, las coordenadas y las dimensiones especificados. |
|
|  | [newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Crea una implementación de la interfaz MboxViewInfo con el tipo de archivo, las páginas y el recuento de notas especificados. |
|
|  | [newWord(String word, double x, double y, double width, double height, List<Character> characters)](#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--) | Crea una implementación de la interfaz [Word](../../com.groupdocs.viewer.results/word) con la palabra, las coordenadas, las dimensiones y los caracteres especificados. |
|
### CacheableFactory() {#CacheableFactory--}
```
public CacheableFactory()
```


### getInstance() {#getInstance--}
```
public static CacheableFactory getInstance()
```


Obtiene una instancia de
CacheableFactory
que puede usarse para crear objetos almacenables en caché.


**Returns:**
[CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) - an instance of  CacheableFactory .

### setInstance(CacheableFactory instance) {#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-}
```
public static void setInstance(CacheableFactory instance)
```


Establece la instancia de
CacheableFactory
para ser usado. Esto permite una implementación personalizada de la fábrica cacheable.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | instance | [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) | La instancia de  CacheableFactory  a establecer. |
|

### newViewInfo(FileType fileType, List<Page> pages) {#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--}
```
public ViewInfo newViewInfo(FileType fileType, List<Page> pages)
```


Crea una implementación de la interfaz [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) para el tipo de archivo y páginas especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | El tipo de archivo. |
|
|  | páginas | java.util.List<com.groupdocs.viewer.results.Page> | La lista de páginas que representan las páginas del documento. |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - a new instance of the [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) implementation.

### newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from) {#newEmailViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.lang.String-java.lang.String-}
```
public ViewInfo newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) |  |
| páginas | java.util.List<com.groupdocs.viewer.results.Page> |  |
| originalMessageDate | java.util.Date |  |
| asunto | java.lang.String |  |
| de | java.lang.String |  |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
### newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public LotusNotesViewInfo newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Crea una implementación de la interfaz [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) para el tipo de archivo, páginas y recuento de notas especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | El tipo de archivo. |
|
|  | páginas | java.util.List<com.groupdocs.viewer.results.Page> | La lista de páginas que representan las páginas del documento. |
|
|  | notesCount | int | El recuento de Lotus Notes en el documento. |
|

**Returns:**
[LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) - a new instance of the [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) implementation.

### newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public ArchiveViewInfo newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Crea una implementación de la interfaz [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) para el tipo de archivo, páginas y carpetas especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | El tipo de archivo. |
|
|  | páginas | java.util.List<com.groupdocs.viewer.results.Page> | La lista de páginas que representan las páginas del documento. |
|
|  | carpetas | java.util.List<java.lang.String> | La lista de carpetas en el archivo. |
|

**Returns:**
[ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) - a new instance of the [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) implementation.

### newCharacter(char character, double x, double y, double width, double height) {#newCharacter-char-double-double-double-double-}
```
public Character newCharacter(char character, double x, double y, double width, double height)
```


Crea una implementación de la interfaz [Character](../../com.groupdocs.viewer.results/character) para el carácter, posición y dimensiones especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | carácter | char | El carácter. |
|
|  | x | double | La coordenada x de la posición del carácter. |
|
|  | y | double | La coordenada y de la posición del carácter. |
|
|  | width | double | El ancho del carácter. |
|
|  | altura | double | La altura del carácter. |
|

**Returns:**
[Character](../../com.groupdocs.viewer.results/character) - a new instance of the [Character](../../com.groupdocs.viewer.results/character) implementation.

### newFileInfo(FileType fileType) {#newFileInfo-com.groupdocs.viewer.FileType-}
```
public FileInfo newFileInfo(FileType fileType)
```


Crea una implementación de la interfaz [FileInfo](../../com.groupdocs.viewer.results/fileinfo) para el tipo de archivo especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | El tipo de archivo. |
|

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - a new instance of the [FileInfo](../../com.groupdocs.viewer.results/fileinfo) implementation.

### newLayer(String name, boolean visible) {#newLayer-java.lang.String-boolean-}
```
public Layer newLayer(String name, boolean visible)
```


Crea una implementación de la interfaz [Layer](../../com.groupdocs.viewer.results/layer) con el nombre y la visibilidad especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | El nombre de la capa. |
|
|  | visible | boolean | La visibilidad de la capa. |
|

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.

### newLayer(String name) {#newLayer-java.lang.String-}
```
public Layer newLayer(String name)
```


Crea una implementación de la interfaz [Layer](../../com.groupdocs.viewer.results/layer) con el nombre especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | El nombre de la capa. |
|

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.

### newLayout(String name, double width, double height) {#newLayout-java.lang.String-double-double-}
```
public Layout newLayout(String name, double width, double height)
```


Crea una implementación de la interfaz [Layout](../../com.groupdocs.viewer.results/layout) con el nombre, el ancho y la altura especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | El nombre del diseño. |
|
|  | width | double | El ancho del diseño. |
|
|  | altura | double | La altura del diseño. |
|

**Returns:**
[Layout](../../com.groupdocs.viewer.results/layout) - a new instance of the [Layout](../../com.groupdocs.viewer.results/layout) implementation.

### newLine(String line, double x, double y, double width, double height, List<Word> words) {#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--}
```
public Line newLine(String line, double x, double y, double width, double height, List<Word> words)
```


Crea una implementación de la interfaz [Line](../../com.groupdocs.viewer.results/line) con la línea, la posición, las dimensiones y las palabras especificadas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | línea | java.lang.String | El contenido de la línea. |
|
|  | x | double | La coordenada X del punto superior izquierdo del rectángulo que contiene la línea. |
|
|  | y | double | La coordenada Y del punto superior izquierdo del rectángulo que contiene la línea. |
|
|  | width | double | El ancho del rectángulo que contiene la línea (en píxeles). |
|
|  | altura | double | La altura del rectángulo que contiene la línea (en píxeles). |
|
|  | palabras | java.util.List<com.groupdocs.viewer.results.Word> | Las palabras contenidas en la línea. |
|

**Returns:**
[Line](../../com.groupdocs.viewer.results/line) - a new instance of the [Line](../../com.groupdocs.viewer.results/line) implementation.

### newAttachment(String fileName, String filePath) {#newAttachment-java.lang.String-java.lang.String-}
```
public Attachment newAttachment(String fileName, String filePath)
```


Crea una implementación de la interfaz [Attachment](../../com.groupdocs.viewer.results/attachment).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileName | java.lang.String | El nombre del adjunto. |
|
|  | filePath | java.lang.String | La ruta relativa del adjunto, por ejemplo, "folder/file.docx". Cuando el archivo se encuentra en la raíz de un archivo comprimido, en un mensaje de correo electrónico o en un archivo de datos, indique el nombre del archivo. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, String filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, long size)
```


Crea una implementación de la interfaz [Attachment](../../com.groupdocs.viewer.results/attachment).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | id | java.lang.String | El ID del adjunto. |
|
|  | fileName | java.lang.String | El nombre del adjunto. |
|
|  | filePath | java.lang.String | La ruta relativa del adjunto, por ejemplo, "folder/file.docx". Cuando el archivo se encuentra en la raíz de un archivo comprimido, en un mensaje de correo electrónico o en un archivo de datos, indique el nombre del archivo. |
|
|  | size | long | El tamaño del adjunto. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, Path filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-}
```
public Attachment newAttachment(String id, String fileName, Path filePath, long size)
```


Crea una implementación de la interfaz [Attachment](../../com.groupdocs.viewer.results/attachment).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | id | java.lang.String | El ID del adjunto. |
|
|  | fileName | java.lang.String | El nombre del adjunto. |
|
|  | filePath | java.nio.file.Path | La ruta relativa o absoluta del adjunto. |
|
|  | size | long | El tamaño del adjunto. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, String filePath, FileType fileType, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, FileType fileType, long size)
```


Crea una implementación de la interfaz [Attachment](../../com.groupdocs.viewer.results/attachment). El adjunto representa un archivo adjunto a un documento o a un mensaje de correo electrónico.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | id | java.lang.String | El ID del adjunto. |
|
|  | fileName | java.lang.String | El nombre del adjunto. |
|
|  | filePath | java.lang.String | La ruta relativa o absoluta del adjunto. Puede ser una ruta de archivo dentro de una carpeta o el propio nombre de archivo si el archivo se encuentra en la raíz de un archivo comprimido, en un mensaje de correo electrónico o en un archivo de datos. |
|
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | El tipo del archivo adjunto. |
|
|  | size | long | El tamaño del adjunto. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public OutlookViewInfo newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Crea una implementación de la interfaz [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) basada en el tipo de archivo especificado,
lista de páginas y lista de carpetas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | El tipo de archivo. |
|
|  | páginas | java.util.List<com.groupdocs.viewer.results.Page> | La lista de páginas. |
|
|  | carpetas | java.util.List<java.lang.String> | La lista de carpetas. |
|

**Returns:**
[OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) - a new instance of the [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) implementation.

### newPage(int number, boolean visible) {#newPage-int-boolean-}
```
public Page newPage(int number, boolean visible)
```


Crea una implementación de la interfaz [Page](../../com.groupdocs.viewer.results/page) que representa una página con el número y la visibilidad especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | number | int | El número de página. |
|
|  | visible | boolean | La bandera de visibilidad. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible) {#newPage-int-java.lang.String-boolean-}
```
public Page newPage(int number, String name, boolean visible)
```


Crea una implementación de la interfaz [Page](../../com.groupdocs.viewer.results/page) que representa una página con el número, el nombre y la visibilidad especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | number | int | El número de página. |
|
|  | nombre | java.lang.String | El nombre de la página. |
|
|  | visible | boolean | La bandera de visibilidad. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible, int width, int height) {#newPage-int-java.lang.String-boolean-int-int-}
```
public Page newPage(int number, String name, boolean visible, int width, int height)
```


Crea una implementación de la interfaz [Page](../../com.groupdocs.viewer.results/page) que representa una página con el número, el nombre, la visibilidad, el ancho y la altura especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | number | int | El número de página. |
|
|  | nombre | java.lang.String | El nombre de la página. |
|
|  | visible | boolean | La bandera de visibilidad. |
|
|  | width | int | El ancho de la página. |
|
|  | altura | int | La altura de la página. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, boolean visible, int width, int height) {#newPage-int-boolean-int-int-}
```
public Page newPage(int number, boolean visible, int width, int height)
```


Crea una implementación de la interfaz [Page](../../com.groupdocs.viewer.results/page) que representa una página con el número, la visibilidad, el ancho y la altura especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | number | int | El número de página. |
|
|  | visible | boolean | La bandera de visibilidad. |
|
|  | width | int | El ancho de la página. |
|
|  | altura | int | La altura de la página. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible, int width, int height, List<Line> lines) {#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)
```


Crea una implementación de la interfaz [Page](../../com.groupdocs.viewer.results/page) que representa una página con el número, el nombre, la visibilidad, el ancho, la altura y las líneas especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | number | int | El número de página. |
|
|  | nombre | java.lang.String | El nombre de la página. |
|
|  | visible | boolean | La bandera de visibilidad. |
|
|  | width | int | El ancho de la página. |
|
|  | altura | int | La altura de la página. |
|
|  | líneas | java.util.List<com.groupdocs.viewer.results.Line> | Las líneas contenidas en la página. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, boolean visible, int width, int height, List<Line> lines) {#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, boolean visible, int width, int height, List<Line> lines)
```


Crea una implementación de la interfaz [Page](../../com.groupdocs.viewer.results/page) que representa una página con el número, la visibilidad, el ancho, la altura y las líneas especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | number | int | El número de página. |
|
|  | visible | boolean | La bandera de visibilidad. |
|
|  | width | int | El ancho de la página. |
|
|  | altura | int | La altura de la página. |
|
|  | líneas | java.util.List<com.groupdocs.viewer.results.Line> | Las líneas contenidas en la página. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed) {#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-}
```
public PdfViewInfo newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)
```


Crea una implementación de la interfaz [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) con el tipo de archivo, las páginas y la bandera de impresión permitida especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | El tipo de archivo. |
|
|  | páginas | java.util.List<com.groupdocs.viewer.results.Page> | La lista de páginas. |
|
|  | printingAllowed | boolean | La bandera que indica si la impresión está permitida. |
|

**Returns:**
[PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) - a new instance of the [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) implementation.

### newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts) {#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--}
```
public CadViewInfo newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```


Crea una implementación de la interfaz [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) con el tipo de archivo, las páginas, las capas y los diseños especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | El tipo de archivo. |
|
|  | páginas | java.util.List<com.groupdocs.viewer.results.Page> | La lista de páginas. |
|
|  | layers | java.util.List<com.groupdocs.viewer.results.Layer> | La lista de capas. |
|
|  | layouts | java.util.List<com.groupdocs.viewer.results.Layout> | La lista de diseños. |
|

**Returns:**
[CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) - a new instance of the [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) implementation.

### newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate) {#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-}
```
public ProjectManagementViewInfo newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)
```


Crea una implementación de la interfaz [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) con el tipo de archivo, las páginas, la fecha de inicio y la fecha de finalización especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | El tipo de archivo. |
|
|  | páginas | java.util.List<com.groupdocs.viewer.results.Page> | La lista de páginas. |
|
|  | startDate | java.util.Date | La fecha de inicio. |
|
|  | endDate | java.util.Date | La fecha de finalización. |
|

**Returns:**
[ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) - a new instance of the [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) implementation.

### <T>newTextElement(T value, double x, double y, double width, double height) {#-T-newTextElement-T-double-double-double-double-}
```
public TextElement<T> <T>newTextElement(T value, double x, double y, double width, double height)
```


Crea una implementación de la interfaz [TextElement](../../com.groupdocs.viewer.results/textelement) con el valor, las coordenadas y las dimensiones especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | T | El valor. |
|
|  | x | double | La coordenada X. |
|
|  | y | double | La coordenada Y. |
|
|  | width | double | El ancho. |
|
|  | altura | double | La altura. |
|

**Returns:**
[TextElement](../../com.groupdocs.viewer.results/textelement) - a new instance of the [TextElement](../../com.groupdocs.viewer.results/textelement) implementation.

### newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public MboxViewInfo newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Crea una implementación de la interfaz MboxViewInfo con el tipo de archivo, las páginas y el recuento de notas especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | El tipo del archivo. |
|
|  | páginas | java.util.List<com.groupdocs.viewer.results.Page> | La lista de páginas a ver. |
|
|  | notesCount | int | El recuento de notas contenido en el archivo de almacenamiento de base de datos Lotus. |
|

**Returns:**
com.groupdocs.viewer.results.MboxViewInfo - una nueva instancia de la implementación de MboxViewInfo.

### newWord(String word, double x, double y, double width, double height, List<Character> characters) {#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--}
```
public Word newWord(String word, double x, double y, double width, double height, List<Character> characters)
```


Crea una implementación de la interfaz [Word](../../com.groupdocs.viewer.results/word) con la palabra, las coordenadas, las dimensiones y los caracteres especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | word | java.lang.String | La palabra. |
|
|  | x | double | La coordenada X del punto superior izquierdo en el diseño de página donde comienza el rectángulo que contiene la palabra. |
|
|  | y | double | La coordenada Y del punto superior izquierdo en el diseño de página donde comienza el rectángulo que contiene la palabra. |
|
|  | width | double | El ancho del rectángulo que contiene la palabra (en píxeles). |
|
|  | altura | double | La altura del rectángulo que contiene la palabra (en píxeles). |
|
|  | caracteres | java.util.List<com.groupdocs.viewer.results.Character> | Los caracteres contenidos por la palabra. |
|

**Returns:**
[Word](../../com.groupdocs.viewer.results/word) - a new instance of the [Word](../../com.groupdocs.viewer.results/word) implementation.

