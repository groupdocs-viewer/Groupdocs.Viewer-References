---
title: "Viewer"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Representa la clase principal que controla el proceso de renderizado del documento."
type: docs
weight: 12
url: /es/java/com.groupdocs.viewer/viewer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Viewer implements Closeable
```

Representa la clase principal que controla el proceso de renderizado del documento.


La clase Viewer es el punto de entrada para renderizar documentos usando el componente GroupDocs.Viewer.
Proporciona métodos y opciones para cargar documentos desde diversas fuentes, personalizar el proceso de renderizado y obtener la salida renderizada en diferentes formatos.


Ejemplo de uso:

````

 try (Viewer viewer = new Viewer("source.pdf")) {
     viewer.view(new PngViewOptions("result-page{0}.png"));
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [Viewer(InputStream fileStream)](#Viewer-java.io.InputStream-) | Inicializa una nueva instancia de la clase Viewer. |
|
|  | [Viewer(InputStream fileStream, boolean leaveOpen)](#Viewer-java.io.InputStream-boolean-) | Inicializa una nueva instancia de la clase Viewer. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-) | Inicializa una nueva instancia de la clase Viewer. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-) | Inicializa una nueva instancia de la clase Viewer. |
|
|  | [Viewer(InputStream fileStream, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-) | Inicializa una nueva instancia de la clase Viewer. |
|
|  | [Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-) | Inicializa una nueva instancia de la clase Viewer. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Inicializa una nueva instancia de la clase Viewer. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-) | Inicializa una nueva instancia de la clase Viewer. |
|
|  | [Viewer(URL url)](#Viewer-java.net.URL-) | Inicializa una nueva instancia de la clase Viewer. |
|
|  | [Viewer(URL url, LoadOptions loadOptions)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-) | Inicializa una nueva instancia de la clase Viewer. |
|
|  | [Viewer(URL url, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-) | Inicializa una nueva instancia de la clase Viewer. |
|
|  | [Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Inicializa una nueva instancia de la clase Viewer. |
|
|  | [Viewer(FileReader fileReader, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-) | Inicializa una nueva instancia de la clase Viewer. |
|
|  | [Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Inicializa una nueva instancia de la clase Viewer. |
|
|  | [Viewer(String filePath)](#Viewer-java.lang.String-) | Inicializa una nueva instancia de la clase Viewer. |
|
|  | [Viewer(Path filePath)](#Viewer-java.nio.file.Path-) | Inicializa una nueva instancia de la clase Viewer. |
|
|  | [Viewer(String filePath, LoadOptions loadOptions)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-) | Inicializa una nueva instancia de la clase Viewer. |
|
|  | [Viewer(Path filePath, LoadOptions loadOptions)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-) | Inicializa una nueva instancia de la clase Viewer. |
|
|  | [Viewer(String filePath, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-) | Inicializa una nueva instancia de la clase Viewer. |
|
|  | [Viewer(Path filePath, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-) | Inicializa una nueva instancia de la clase Viewer. |
|
|  | [Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Inicializa una nueva instancia de la clase Viewer. |
|
|  | [Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Inicializa una nueva instancia de la clase Viewer. |
|
## Campos

| Campo | Descripción |
| --- | --- |
| [LOAD_OPTIONS](#LOAD-OPTIONS) |  |
| [SETTINGS](#SETTINGS) |  |
| [FILE_READER](#FILE-READER) |  |
| [OPTIONS](#OPTIONS) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getViewInfo(ViewInfoOptions options)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-) | Devuelve información sobre la vista y la información específica del documento. |
|
|  | [getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-com.groupdocs.viewer.utils.CancellationToken-) | Devuelve información sobre la vista y la información específica del documento. |
|
|  | [getAttachments()](#getAttachments--) | Devuelve los archivos adjuntos contenidos en el documento. |
|
|  | [getAttachments(CancellationToken cancellationToken)](#getAttachments-com.groupdocs.viewer.utils.CancellationToken-) | Devuelve los archivos adjuntos contenidos en el documento. |
|
|  | [saveAttachment(Attachment attachment, OutputStream destination)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-) | Guarda un archivo adjunto en el flujo de destino. |
|
|  | [saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-com.groupdocs.viewer.utils.CancellationToken-) | Guarda un archivo adjunto en el flujo de destino. |
|
|  | [view(ViewOptions options)](#view-com.groupdocs.viewer.options.ViewOptions-) | Crea una vista de todas las páginas del documento. |
|
|  | [view(ViewOptions options, CancellationToken cancellationToken)](#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-) | Crea una vista de todas las páginas del documento. |
|
|  | [view(ViewOptions options, int pageNumber)](#view-com.groupdocs.viewer.options.ViewOptions-int-) | Crea una vista de una página específica del documento. |
|
|  | [view(ViewOptions options, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-int...-) | Crea una vista de páginas específicas del documento. |
|
|  | [view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-int...-) | Crea una vista de páginas específicas del documento. |
|
|  | [getAllFonts()](#getAllFonts--) | Devuelve todas las fuentes utilizadas en los documentos cargados, incluidas las incrustadas dentro del propio documento y las fuentes del sistema instaladas en el SO y usadas en el documento. |
|
|  | [search(SearchHighlightOptions options)](#search-com.groupdocs.viewer.options.SearchHighlightOptions-) | Realiza una búsqueda de texto y resalta las coincidencias (si se encuentran) en el documento cargado según las opciones proporcionadas. |
|
|  | [getFileInfo()](#getFileInfo--) | Devuelve información sobre el archivo, como el tipo de archivo y una bandera que indica si el archivo está cifrado. |
|
|  | [close()](#close--) | Libera el flujo de archivo y los recursos internos gestionados. |
|
### Viewer(InputStream fileStream) {#Viewer-java.io.InputStream-}
```
public Viewer(InputStream fileStream)
```


Inicializa una nueva instancia de la clase Viewer.


Más información sobre los tipos de archivo compatibles con GroupDocs.Viewer:
[Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | El método que devuelve un flujo legible. |
|

### Viewer(InputStream fileStream, boolean leaveOpen) {#Viewer-java.io.InputStream-boolean-}
```
public Viewer(InputStream fileStream, boolean leaveOpen)
```


Inicializa una nueva instancia de la clase Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | El flujo del archivo. |
|
|  | leaveOpen | boolean | true para dejar el flujo abierto después de que el objeto Viewer se elimine; de lo contrario, false. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions)
```


Inicializa una nueva instancia de la clase Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | El flujo legible. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Las opciones de carga del documento. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)
```


Inicializa una nueva instancia de la clase Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | El flujo del archivo. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Las opciones de carga del documento. |
|
|  | leaveOpen | boolean | true para dejar el flujo abierto después de que el objeto Viewer se elimine; de lo contrario, false. |
|

### Viewer(InputStream fileStream, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, ViewerSettings settings)
```


Inicializa una nueva instancia de la clase Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | El flujo del archivo. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | La configuración del Viewer. |
|

### Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)
```


Inicializa una nueva instancia de la clase Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | El flujo del archivo. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | La configuración del Viewer. |
|
|  | leaveOpen | boolean | true para dejar el flujo abierto después de que el objeto Viewer se elimine; de lo contrario, false. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)
```


Inicializa una nueva instancia de la clase Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | El flujo del archivo. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Las opciones de carga del documento. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | La configuración del Viewer. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)
```


Inicializa una nueva instancia de la clase Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | El flujo del archivo. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Las opciones de carga del documento. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | La configuración del Viewer. |
|
|  | leaveOpen | boolean | true para dejar el flujo abierto después de que el objeto Viewer se elimine; de lo contrario, false. |
|

### Viewer(URL url) {#Viewer-java.net.URL-}
```
public Viewer(URL url)
```


Inicializa una nueva instancia de la clase Viewer.


Más información sobre los tipos de archivo compatibles con GroupDocs.Viewer: [Formatos de documento compatibles con GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | url | java.net.URL | Una URL a un archivo que debe cargarse en el Viewer. |
|

### Viewer(URL url, LoadOptions loadOptions) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(URL url, LoadOptions loadOptions)
```


Inicializa una nueva instancia de la clase Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | url | java.net.URL | Una URL a un archivo que debe cargarse en el Viewer. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Las opciones de carga del documento. |
|

### Viewer(URL url, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, ViewerSettings settings)
```


Inicializa una nueva instancia de la clase Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | url | java.net.URL | Una URL a un archivo que debe cargarse en el Viewer. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | La configuración del Viewer. |
|

### Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)
```


Inicializa una nueva instancia de la clase Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | url | java.net.URL | Una URL a un archivo que debe cargarse en el Viewer. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Las opciones de carga del documento. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | La configuración del Viewer. |
|

### Viewer(FileReader fileReader, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, ViewerSettings settings)
```


Inicializa una nueva instancia de la clase Viewer.


Este constructor le permite crear un objeto Viewer para ver un documento desde un [FileReader](../../com.groupdocs.viewer.interfaces/filereader) con los [ViewerSettings](../../com.groupdocs.viewer/viewersettings) especificados.
***Learn more**
* To learn about the file types supported by GroupDocs.Viewer, visit: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* To explore the features of GroupDocs.Viewer for Java, refer to: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | El [FileReader](../../com.groupdocs.viewer.interfaces/filereader) que contiene el documento que se cargará en el Viewer. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Los [ViewerSettings](../../com.groupdocs.viewer/viewersettings) que se aplicarán al Viewer. |
|

### Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)
```


Inicializa una nueva instancia de la clase Viewer.


Proporciona funcionalidad para cargar y ver documentos usando GroupDocs.Viewer.


**Note:** Ensure that the file reader, load options, and settings are properly configured for accurate document processing.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | El lector de archivos. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Las opciones de carga. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | La configuración del Viewer. |
|

### Viewer(String filePath) {#Viewer-java.lang.String-}
```
public Viewer(String filePath)
```


Inicializa una nueva instancia de la clase Viewer.
***Learn more:**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta al archivo que se renderizará. |
|

### Viewer(Path filePath) {#Viewer-java.nio.file.Path-}
```
public Viewer(Path filePath)
```


Inicializa una nueva instancia de la clase Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | La ruta al archivo que se renderizará. |
|

### Viewer(String filePath, LoadOptions loadOptions) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(String filePath, LoadOptions loadOptions)
```


Inicializa una nueva instancia de la clase Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta al archivo que se renderizará. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Las opciones de carga del documento. |
|

### Viewer(Path filePath, LoadOptions loadOptions) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(Path filePath, LoadOptions loadOptions)
```


Inicializa una nueva instancia de la clase Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view a document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | La ruta al archivo que se renderizará. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Las opciones de carga del documento. |
|

### Viewer(String filePath, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, ViewerSettings settings)
```


Inicializa una nueva instancia de la clase Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta al archivo que se renderizará. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | La configuración del Viewer. |
|

### Viewer(Path filePath, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, ViewerSettings settings)
```


Inicializa una nueva instancia de la clase Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | La ruta al archivo que se renderizará. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | La configuración del Viewer. |
|

### Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Inicializa una nueva instancia de la clase Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta al archivo que se renderizará. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Las opciones de carga del documento. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | La configuración del Viewer. |
|

### Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Inicializa una nueva instancia de la clase Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | La ruta al archivo que se renderizará. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Las opciones de carga del documento. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | La configuración del Viewer. |
|

### LOAD_OPTIONS {#LOAD-OPTIONS}
```
public static final String LOAD_OPTIONS
```


### SETTINGS {#SETTINGS}
```
public static final String SETTINGS
```


### FILE_READER {#FILE-READER}
```
public static final String FILE_READER
```


### OPTIONS {#OPTIONS}
```
public static final String OPTIONS
```


### getViewInfo(ViewInfoOptions options) {#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-}
```
public final ViewInfo getViewInfo(ViewInfoOptions options)
```


Devuelve información sobre la vista y la información específica del documento.
***Learn more:**
* Learn more about the document - file type, page count, and other format specific properties: [How to get file information using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+file+information)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | Las opciones de información de vista. |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about the view and document specific information.

### getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken) {#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-com.groupdocs.viewer.utils.CancellationToken-}
```
public final ViewInfo getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)
```


Devuelve información sobre la vista y la información específica del documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | Las opciones de información de vista. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Token de cancelación para abortar la operación. |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about the view and document specific information.

### getAttachments() {#getAttachments--}
```
public final List<Attachment> getAttachments()
```


Devuelve los archivos adjuntos contenidos en el documento.
***Learn more:**
* Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+attachments)
* Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Save+attachments)*


**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - archivos adjuntos contenidos en el documento.

### getAttachments(CancellationToken cancellationToken) {#getAttachments-com.groupdocs.viewer.utils.CancellationToken-}
```
public final List<Attachment> getAttachments(CancellationToken cancellationToken)
```


Devuelve los archivos adjuntos contenidos en el documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Token de cancelación para abortar la operación. |
|

**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - archivos adjuntos contenidos en el documento.

### saveAttachment(Attachment attachment, OutputStream destination) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-}
```
public void saveAttachment(Attachment attachment, OutputStream destination)
```


Guarda un archivo adjunto en el flujo de destino.
***Learn more:**
* Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+attachments)
* Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Save+attachments)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | El adjunto. |
|
|  | destino | java.io.OutputStream | El flujo de escritura. |
|

### saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-com.groupdocs.viewer.utils.CancellationToken-}
```
public void saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken)
```


Guarda un archivo adjunto en el flujo de destino.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | El adjunto. |
|
|  | destino | java.io.OutputStream | El flujo de escritura. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Token de cancelación para abortar la operación. |
|

### view(ViewOptions options) {#view-com.groupdocs.viewer.options.ViewOptions-}
```
public final void view(ViewOptions options)
```


Crea una vista de todas las páginas del documento.
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Las opciones de vista. |
|

### view(ViewOptions options, CancellationToken cancellationToken) {#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-}
```
public final void view(ViewOptions options, CancellationToken cancellationToken)
```


Crea una vista de todas las páginas del documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Las opciones de vista. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Token de cancelación para abortar el proceso de renderizado. |
|

### view(ViewOptions options, int pageNumber) {#view-com.groupdocs.viewer.options.ViewOptions-int-}
```
public final void view(ViewOptions options, int pageNumber)
```


Crea una vista de una página específica del documento.
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Las opciones de vista. |
|
|  | pageNumber | int | El número de página a visualizar. |
|

### view(ViewOptions options, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-int...-}
```
public final void view(ViewOptions options, int[] pageNumbers)
```


Crea una vista de páginas específicas del documento.
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Las opciones de vista. |
|
|  | pageNumbers | int[] | Los números de página a visualizar. |
|

### view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-int...-}
```
public final void view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers)
```


Crea una vista de páginas específicas del documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Las opciones de vista. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Token de cancelación para abortar el proceso de renderizado. |
|
|  | pageNumbers | int[] | Los números de página a visualizar. |
|

### getAllFonts() {#getAllFonts--}
```
public IFontInfo[] getAllFonts()
```


Devuelve todas las fuentes utilizadas en los documentos cargados, incluidas las incrustadas dentro del propio documento y las fuentes del sistema instaladas en el SO y usadas en el documento.

Para obtener más detalles, vea el
[documentation](../https://docs.groupdocs.com/viewer/net/getting-used-fonts/).


**Returns:**
com.groupdocs.viewer.fonts.IFontInfo[] - Lista no nula de todas las fuentes usadas en el documento cargado en esta instancia de [Viewer](../../com.groupdocs.viewer/viewer).

### search(SearchHighlightOptions options) {#search-com.groupdocs.viewer.options.SearchHighlightOptions-}
```
public void search(SearchHighlightOptions options)
```


Realiza una búsqueda de texto y resalta las coincidencias (si se encuentran) en el documento cargado según las opciones proporcionadas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | opciones | com.groupdocs.viewer.options.SearchHighlightOptions | Opciones de búsqueda y resaltado, incluyendo una frase de texto para buscar. No puede ser null. |
|

### getFileInfo() {#getFileInfo--}
```
public FileInfo getFileInfo()
```


Devuelve información sobre el archivo, como el tipo de archivo y una bandera que indica si el archivo está cifrado.
***Learn more:**
* Learn more about how to check if a file is encrypted: [How to check if a file is encrypted](../https://docs.groupdocs.com/viewer/net/how-to-check-if-file-is-encrypted/)*


**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - the file information.

### close() {#close--}
```
public final void close()
```


Libera el flujo de archivo y los recursos internos gestionados.


