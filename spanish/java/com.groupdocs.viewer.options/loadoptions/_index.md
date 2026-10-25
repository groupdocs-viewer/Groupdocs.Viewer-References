---
title: "LoadOptions"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Proporciona opciones que se utilizan para abrir un archivo."
type: docs
weight: 18
url: /es/java/com.groupdocs.viewer.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Proporciona opciones que se utilizan para abrir un archivo.


La clase LoadOptions encapsula varios ajustes y parámetros que pueden ser utilizados
para especificar cómo se debe abrir y cargar un archivo en el componente GroupDocs.Viewer.
Para más detalles, vea esta [página](../https://docs.groupdocs.com/viewer/java/loading/) y sus hijos.


Ejemplo de uso:

````

 LoadOptions options = new LoadOptions();
 options.setPassword("myPassword");
 options.setFileType(PDF);
 options.setCharset(Charset.forName("UTF-8"));

 try (Viewer viewer = new Viewer(pdfFileInputStream, options)) {
     // Use the viewer object for further operations
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Inicializa una nueva instancia de la |
LoadOptions
clase.
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.viewer.FileType-) | Inicializa una nueva instancia de la |
LoadOptions
clase.
|
## Campos

| Campo | Descripción |
| --- | --- |
| [DEFAULT_URL_CONNECT_TIMEOUT](#DEFAULT-URL-CONNECT-TIMEOUT) |  |
| [DEFAULT_URL_READ_TIMEOUT](#DEFAULT-URL-READ-TIMEOUT) |  |
| [_tryRepair](#-tryRepair) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isTryRepair()](#isTryRepair--) | Cuando está habilitado, GroupDocs.Viewer intenta reparar la corrupción estructural en documentos PDF. |
|
|  | [setTryRepair(boolean tryRepair)](#setTryRepair-boolean-) | Cuando está habilitado, GroupDocs.Viewer intenta reparar la corrupción estructural en documentos PDF. |
|
|  | [getFileType()](#getFileType--) | Obtiene el tipo de archivo a abrir. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.viewer.FileType-) | Establece el tipo de archivo a abrir. |
|
|  | [getPassword()](#getPassword--) | Obtiene la contraseña para abrir un archivo encriptado. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Establece la contraseña para abrir un archivo encriptado. |
|
|  | [getCharset()](#getCharset--) | El conjunto de caracteres utilizado al abrir archivos basados en texto o mensajes de correo electrónico como |
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
y [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
|
|  | [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | El conjunto de caracteres utilizado al abrir archivos basados en texto o mensajes de correo electrónico como |
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
y [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
|
|  | [isDetectCharset()](#isDetectCharset--) | Esta opción habilita la detección del conjunto de caracteres de archivos [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) y [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV). |
|
|  | [setDetectCharset(boolean detectCharset)](#setDetectCharset-boolean-) | Esta opción habilita la detección del conjunto de caracteres de archivos [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) y [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV). |
|
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Obtiene el tiempo de espera para cargar recursos externos. |
|
|  | [setResourceLoadingTimeout(int resourceLoadingTimeout)](#setResourceLoadingTimeout-int-) | Establece el tiempo de espera para cargar recursos externos, como gráficos. |
|
|  | [getUrlConnectTimeout()](#getUrlConnectTimeout--) | Obtiene el tiempo de espera de conexión para crear un [Viewer](../../com.groupdocs.viewer/viewer) usando java.net.URL para cargar un documento. |
|
|  | [setUrlConnectTimeout(int urlConnectTimeout)](#setUrlConnectTimeout-int-) | Establece el tiempo de espera de conexión para crear un [Viewer](../../com.groupdocs.viewer/viewer) usando java.net.URL para cargar un documento. |
|
|  | [getUrlReadTimeout()](#getUrlReadTimeout--) | Obtiene el tiempo de espera de lectura para crear un [Viewer](../../com.groupdocs.viewer/viewer) usando java.net.URL para cargar un documento. |
|
|  | [setUrlReadTimeout(int urlReadTimeout)](#setUrlReadTimeout-int-) | Establece el tiempo de espera de lectura para crear un [Viewer](../../com.groupdocs.viewer/viewer) usando java.net.URL para cargar un documento. |
|
|  | [getArchiveSecurityOptions()](#getArchiveSecurityOptions--) | Obtiene las opciones de seguridad para controlar el proceso de extracción de archivos. |
|
|  | [setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)](#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-) | Establece las opciones de seguridad para controlar el proceso de extracción de archivos. |
|
|  | [isSkipExternalResources()](#isSkipExternalResources--) | Cuando se establece en true, todos los recursos externos como imágenes no se cargarán excepto #getWhitelistedResources().getWhitelistedResources(). |
|
|  | [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) | Cuando se establece en true, todos los recursos externos como imágenes no se cargarán excepto #getWhitelistedResources().getWhitelistedResources(). |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | La lista de fragmentos de URL correspondientes a recursos externos que deben cargarse cuando #isSkipExternalResources().isSkipExternalResources() está establecida en `true`. |
|
|  | [setWhitelistedResources(List<String> whitelistedResources)](#setWhitelistedResources-java.util.List-java.lang.String--) | Establece la lista de fragmentos de URL correspondientes a recursos externos que deben cargarse cuando #isSkipExternalResources().isSkipExternalResources() está configurado a `true`. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Inicializa una nueva instancia de la
LoadOptions
clase.


Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.viewer.FileType-}
```
public LoadOptions(FileType fileType)
```


Inicializa una nueva instancia de la
LoadOptions
clase.


Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | El tipo de archivo a abrir. |
|

### DEFAULT_URL_CONNECT_TIMEOUT {#DEFAULT-URL-CONNECT-TIMEOUT}
```
public static final int DEFAULT_URL_CONNECT_TIMEOUT
```


### DEFAULT_URL_READ_TIMEOUT {#DEFAULT-URL-READ-TIMEOUT}
```
public static final int DEFAULT_URL_READ_TIMEOUT
```


### _tryRepair {#-tryRepair}
```
public boolean _tryRepair
```


### isTryRepair() {#isTryRepair--}
```
public boolean isTryRepair()
```


Cuando está habilitado, GroupDocs.Viewer intenta reparar la corrupción estructural en documentos PDF. El valor predeterminado es false.


Esta función aborda los siguientes problemas en un documento PDF:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).


**Returns:**
boolean
### setTryRepair(boolean tryRepair) {#setTryRepair-boolean-}
```
public void setTryRepair(boolean tryRepair)
```


Cuando está habilitado, GroupDocs.Viewer intenta reparar la corrupción estructural en documentos PDF. El valor predeterminado es false.


Esta función aborda los siguientes problemas en un documento PDF:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tryRepair | boolean |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Obtiene el tipo de archivo a abrir.


Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.

### setFileType(FileType value) {#setFileType-com.groupdocs.viewer.FileType-}
```
public final void setFileType(FileType value)
```


Establece el tipo de archivo a abrir.


Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.viewer/filetype) | El tipo de archivo. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Obtiene la contraseña para abrir un archivo encriptado.


Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/load-password-protected-document/).


**Returns:**
java.lang.String - la contraseña para abrir el archivo.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Establece la contraseña para abrir un archivo encriptado.


Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/load-password-protected-document/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | La contraseña para abrir el archivo. |
|

### getCharset() {#getCharset--}
```
public final Charset getCharset()
```


El conjunto de caracteres utilizado al abrir archivos basados en texto o mensajes de correo electrónico como
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
y [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
El valor predeterminado es java.nio.charset.StandardCharsets#UTF_8.UTF_8. Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/).

**Learn more**

* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files)
* [Render email messages as HTML, PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-email-messages/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setCharset(StandardCharsets.US_ASCII); // Establecer el conjunto de caracteres

try (Viewer viewer = new Viewer(\"message.txt\", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
java.nio.charset.Charset
### setCharset(Charset value) {#setCharset-java.nio.charset.Charset-}
```
public final void setCharset(Charset value)
```


El conjunto de caracteres utilizado al abrir archivos basados en texto o mensajes de correo electrónico como
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
y [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
El valor predeterminado es java.nio.charset.StandardCharsets#UTF_8.UTF_8. Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/).

**Learn more**

* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files)
* [Render email messages as HTML, PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-email-messages/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setCharset(StandardCharsets.US_ASCII); // Establecer el conjunto de caracteres

try (Viewer viewer = new Viewer(\"message.txt\", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.nio.charset.Charset |  |

### isDetectCharset() {#isDetectCharset--}
```
public boolean isDetectCharset()
```


Esta opción habilita la detección del juego de caracteres de los archivos [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) y [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV). En caso de que el juego de caracteres no pueda detectarse, se utiliza el [getCharset()](../../com.groupdocs.viewer.options/loadoptions#getCharset--) predeterminado.

**Learn more about rendering text and tab/comma delimited files**

* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)


Si la codificación no puede detectarse, se utiliza la predeterminada. Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/).

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setDetectCharset(true); // Habilitar detección de codificación

try (Viewer viewer = new Viewer(\"employees.csv\", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setDetectCharset(boolean detectCharset) {#setDetectCharset-boolean-}
```
public void setDetectCharset(boolean detectCharset)
```


Esta opción habilita la detección del juego de caracteres de los archivos [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) y [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV). En caso de que el juego de caracteres no pueda detectarse, se utiliza el [getCharset()](../../com.groupdocs.viewer.options/loadoptions#getCharset--) predeterminado.

**Learn more about rendering text and tab/comma delimited files**

* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)


Si la codificación no puede detectarse, se utiliza la predeterminada. Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/).

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setDetectCharset(true); // Habilitar detección de codificación

try (Viewer viewer = new Viewer(\"employees.csv\", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| detectCharset | boolean |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public int getResourceLoadingTimeout()
```


Obtiene el tiempo de espera para cargar recursos externos.


**Note:** The default value is 10 seconds.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)


El valor predeterminado es 30 segundos. Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents).

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setResourceLoadingTimeout(5000); // Establecer el tiempo de espera de carga de recursos a 5 segundos

try (Viewer viewer = new Viewer(\"business-flyer.docx\", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
int
### setResourceLoadingTimeout(int resourceLoadingTimeout) {#setResourceLoadingTimeout-int-}
```
public void setResourceLoadingTimeout(int resourceLoadingTimeout)
```


Establece el tiempo de espera para cargar recursos externos, como gráficos.


***Note:** The default value is 30 seconds.*


Esta opción es compatible con documentos de procesamiento de texto que contienen recursos externos.
El valor predeterminado es 30 segundos. Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | resourceLoadingTimeout | int | El tiempo de espera de carga, milisegundos. |
|

### getUrlConnectTimeout() {#getUrlConnectTimeout--}
```
public int getUrlConnectTimeout()
```


Obtiene el tiempo de espera de conexión para crear un [Viewer](../../com.groupdocs.viewer/viewer) usando java.net.URL para cargar un documento.


***Note:** The default value is 5 seconds.*


**Returns:**
int - el tiempo de espera de la conexión.

### setUrlConnectTimeout(int urlConnectTimeout) {#setUrlConnectTimeout-int-}
```
public void setUrlConnectTimeout(int urlConnectTimeout)
```


Establece el tiempo de espera de conexión para crear un [Viewer](../../com.groupdocs.viewer/viewer) usando java.net.URL para cargar un documento.


***Note:** The default value is 5 seconds.*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | urlConnectTimeout | int | El tiempo de espera de la conexión. |
|

### getUrlReadTimeout() {#getUrlReadTimeout--}
```
public int getUrlReadTimeout()
```


Obtiene el tiempo de espera de lectura para crear un [Viewer](../../com.groupdocs.viewer/viewer) usando java.net.URL para cargar un documento.


***Note:** The default value is 30 seconds.*


**Returns:**
int - el tiempo de espera de lectura.

### setUrlReadTimeout(int urlReadTimeout) {#setUrlReadTimeout-int-}
```
public void setUrlReadTimeout(int urlReadTimeout)
```


Establece el tiempo de espera de lectura para crear un [Viewer](../../com.groupdocs.viewer/viewer) usando java.net.URL para cargar un documento.


***Note:** The default value is 30 seconds.*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | urlReadTimeout | int | El tiempo de espera de lectura. |
|

### getArchiveSecurityOptions() {#getArchiveSecurityOptions--}
```
public ArchiveSecurityOptions getArchiveSecurityOptions()
```


Obtiene las opciones de seguridad para controlar el proceso de extracción de archivos.


***Note:** Not each archive type supports all options.*


**Returns:**
com.groupdocs.viewer.options.ArchiveSecurityOptions - el objeto de opciones para configurar el proceso de extracción de archivos.

### setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions) {#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-}
```
public void setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)
```


Establece las opciones de seguridad para controlar el proceso de extracción de archivos.


***Note:** Not each archive type supports all options.*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | archiveSecurityOptions | com.groupdocs.viewer.options.ArchiveSecurityOptions | El objeto de opciones para configurar el proceso de extracción de archivos. |
|

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


Cuando se establece en true, todos los recursos externos como imágenes no se cargarán excepto #getWhitelistedResources().getWhitelistedResources().

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Omitir la carga de recursos externos

try (Viewer viewer = new Viewer(\"business-flyer.docx\", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```


Cuando se establece en true, todos los recursos externos como imágenes no se cargarán excepto #getWhitelistedResources().getWhitelistedResources().

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Omitir la carga de recursos externos

try (Viewer viewer = new Viewer(\"business-flyer.docx\", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | skipExternalResources | boolean | La bandera para habilitar o deshabilitar la carga de recursos externos. |
|

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


La lista de fragmentos de URL correspondientes a recursos externos que deben cargarse cuando #isSkipExternalResources().isSkipExternalResources() está establecida en `true`.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Omitir la carga de recursos externos
loadOptions.getWhitelistedResources().add("avatars.githubusercontent.com"); // Habilitar la carga de recursos externos que tengan el fragmento 'avatars.githubusercontent.com' en la URL del recurso.
try (Viewer viewer = new Viewer(\"business-flyer.docx\", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whitelistedResources) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whitelistedResources)
```


Establece la lista de fragmentos de URL correspondientes a recursos externos que deben cargarse cuando #isSkipExternalResources().isSkipExternalResources() está configurado a `true`.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Omitir la carga de recursos externos
loadOptions.setWhitelistedResources(Arrays.asList("avatars.githubusercontent.com")); // Habilitar la carga de recursos externos que tengan el fragmento 'avatars.githubusercontent.com' en la URL del recurso.
try (Viewer viewer = new Viewer(\"business-flyer.docx\", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | whitelistedResources | java.util.List<java.lang.String> | La lista de fragmentos de URL correspondientes a recursos externos que deben cargarse. |
|

