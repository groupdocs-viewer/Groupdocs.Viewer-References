---
title: "LoadOptions"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Fournit des options qui sont utilisées pour ouvrir un fichier."
type: docs
weight: 18
url: /fr/java/com.groupdocs.viewer.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Fournit des options qui sont utilisées pour ouvrir un fichier.


La classe LoadOptions encapsule divers paramètres et réglages qui peuvent être utilisés
pour spécifier comment un fichier doit être ouvert et chargé dans le composant GroupDocs.Viewer.
Pour plus de détails, consultez cette [page](../https://docs.groupdocs.com/viewer/java/loading/) et ses sous‑pages.


Exemple d'utilisation :

````

 LoadOptions options = new LoadOptions();
 options.setPassword("myPassword");
 options.setFileType(PDF);
 options.setCharset(Charset.forName("UTF-8"));

 try (Viewer viewer = new Viewer(pdfFileInputStream, options)) {
     // Use the viewer object for further operations
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Initialise une nouvelle instance de |
LoadOptions
classe.
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.viewer.FileType-) | Initialise une nouvelle instance de |
LoadOptions
classe.
|
## Champs

| Champ | Description |
| --- | --- |
| [DEFAULT_URL_CONNECT_TIMEOUT](#DEFAULT-URL-CONNECT-TIMEOUT) |  |
| [DEFAULT_URL_READ_TIMEOUT](#DEFAULT-URL-READ-TIMEOUT) |  |
| [_tryRepair](#-tryRepair) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isTryRepair()](#isTryRepair--) | Lorsqu'elle est activée, GroupDocs.Viewer tente de réparer les corruptions structurelles des documents PDF. |
|
|  | [setTryRepair(boolean tryRepair)](#setTryRepair-boolean-) | Lorsqu'elle est activée, GroupDocs.Viewer tente de réparer les corruptions structurelles des documents PDF. |
|
|  | [getFileType()](#getFileType--) | Obtient le type du fichier à ouvrir. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.viewer.FileType-) | Définit le type du fichier à ouvrir. |
|
|  | [getPassword()](#getPassword--) | Obtient le mot de passe pour ouvrir un fichier chiffré. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Définit le mot de passe pour ouvrir un fichier chiffré. |
|
|  | [getCharset()](#getCharset--) | Le jeu de caractères utilisé lors de l'ouverture de fichiers texte ou de messages électroniques tels que |
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
et [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
|
|  | [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | Le jeu de caractères utilisé lors de l'ouverture de fichiers texte ou de messages électroniques tels que |
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
et [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
|
|  | [isDetectCharset()](#isDetectCharset--) | Cette option active la détection du jeu de caractères pour les fichiers [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) et [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV). |
|
|  | [setDetectCharset(boolean detectCharset)](#setDetectCharset-boolean-) | Cette option active la détection du jeu de caractères pour les fichiers [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) et [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV). |
|
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Obtient le délai d'attente pour le chargement des ressources externes. |
|
|  | [setResourceLoadingTimeout(int resourceLoadingTimeout)](#setResourceLoadingTimeout-int-) | Définit le délai d'attente pour le chargement des ressources externes, comme les graphiques. |
|
|  | [getUrlConnectTimeout()](#getUrlConnectTimeout--) | Obtient le délai d'attente de connexion pour créer un [Viewer](../../com.groupdocs.viewer/viewer) en utilisant java.net.URL afin de charger un document. |
|
|  | [setUrlConnectTimeout(int urlConnectTimeout)](#setUrlConnectTimeout-int-) | Définit le délai d'attente de connexion pour créer un [Viewer](../../com.groupdocs.viewer/viewer) en utilisant java.net.URL afin de charger un document. |
|
|  | [getUrlReadTimeout()](#getUrlReadTimeout--) | Obtient le délai d'attente de lecture pour créer un [Viewer](../../com.groupdocs.viewer/viewer) en utilisant java.net.URL afin de charger un document. |
|
|  | [setUrlReadTimeout(int urlReadTimeout)](#setUrlReadTimeout-int-) | Définit le délai d'attente de lecture pour créer un [Viewer](../../com.groupdocs.viewer/viewer) en utilisant java.net.URL afin de charger un document. |
|
|  | [getArchiveSecurityOptions()](#getArchiveSecurityOptions--) | Obtient les options de sécurité pour contrôler le processus d'extraction des archives. |
|
|  | [setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)](#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-) | Définit les options de sécurité pour contrôler le processus d'extraction des archives. |
|
|  | [isSkipExternalResources()](#isSkipExternalResources--) | Lorsqu'elle est définie sur `true`, toutes les ressources externes comme les images ne seront pas chargées sauf #getWhitelistedResources().getWhitelistedResources(). |
|
|  | [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) | Lorsqu'elle est définie sur `true`, toutes les ressources externes comme les images ne seront pas chargées sauf #getWhitelistedResources().getWhitelistedResources(). |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | La liste des fragments d'URL correspondant aux ressources externes qui doivent être chargées lorsque #isSkipExternalResources().isSkipExternalResources() est définie sur `true`. |
|
|  | [setWhitelistedResources(List<String> whitelistedResources)](#setWhitelistedResources-java.util.List-java.lang.String--) | Définit la liste des fragments d'URL correspondant aux ressources externes qui doivent être chargées lorsque #isSkipExternalResources().isSkipExternalResources() est réglé sur `true`. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initialise une nouvelle instance de
LoadOptions
classe.


Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.viewer.FileType-}
```
public LoadOptions(FileType fileType)
```


Initialise une nouvelle instance de
LoadOptions
classe.


Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Le type du fichier à ouvrir. |
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


Lorsqu'il est activé, GroupDocs.Viewer tente de réparer la corruption structurelle des documents PDF. La valeur par défaut est false.


Cette fonctionnalité résout les problèmes suivants dans un document PDF :

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).


**Returns:**
boolean
### setTryRepair(boolean tryRepair) {#setTryRepair-boolean-}
```
public void setTryRepair(boolean tryRepair)
```


Lorsqu'il est activé, GroupDocs.Viewer tente de réparer la corruption structurelle des documents PDF. La valeur par défaut est false.


Cette fonctionnalité résout les problèmes suivants dans un document PDF :

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tryRepair | boolean |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Obtient le type du fichier à ouvrir.


Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.

### setFileType(FileType value) {#setFileType-com.groupdocs.viewer.FileType-}
```
public final void setFileType(FileType value)
```


Définit le type du fichier à ouvrir.


Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.viewer/filetype) | Le type de fichier. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Obtient le mot de passe pour ouvrir un fichier chiffré.


Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/load-password-protected-document/).


**Returns:**
java.lang.String - le mot de passe pour ouvrir le fichier.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Définit le mot de passe pour ouvrir un fichier chiffré.


Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/load-password-protected-document/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le mot de passe pour ouvrir le fichier. |
|

### getCharset() {#getCharset--}
```
public final Charset getCharset()
```


Le jeu de caractères utilisé lors de l'ouverture de fichiers texte ou de messages électroniques tels que
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
et [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
La valeur par défaut est java.nio.charset.StandardCharsets#UTF_8.UTF_8. Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/).

**Learn more**

* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files)
* [Render email messages as HTML, PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-email-messages/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setCharset(StandardCharsets.US_ASCII); // Définir le jeu de caractères

try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
java.nio.charset.Charset
### setCharset(Charset value) {#setCharset-java.nio.charset.Charset-}
```
public final void setCharset(Charset value)
```


Le jeu de caractères utilisé lors de l'ouverture de fichiers texte ou de messages électroniques tels que
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
et [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
La valeur par défaut est java.nio.charset.StandardCharsets#UTF_8.UTF_8. Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/).

**Learn more**

* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files)
* [Render email messages as HTML, PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-email-messages/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setCharset(StandardCharsets.US_ASCII); // Définir le jeu de caractères

try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.nio.charset.Charset |  |

### isDetectCharset() {#isDetectCharset--}
```
public boolean isDetectCharset()
```


Cette option active la détection du jeu de caractères des fichiers [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) et [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV). Dans le cas où le jeu de caractères ne peut pas être détecté, le [getCharset()](../../com.groupdocs.viewer.options/loadoptions#getCharset--) par défaut est utilisé.

**Learn more about rendering text and tab/comma delimited files**

* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)


Si le codage ne peut pas être détecté, la valeur par défaut est utilisée. Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/).

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setDetectCharset(true); // Activer la détection du codage

try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setDetectCharset(boolean detectCharset) {#setDetectCharset-boolean-}
```
public void setDetectCharset(boolean detectCharset)
```


Cette option active la détection du jeu de caractères des fichiers [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) et [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV). Dans le cas où le jeu de caractères ne peut pas être détecté, le [getCharset()](../../com.groupdocs.viewer.options/loadoptions#getCharset--) par défaut est utilisé.

**Learn more about rendering text and tab/comma delimited files**

* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)


Si le codage ne peut pas être détecté, la valeur par défaut est utilisée. Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/).

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setDetectCharset(true); // Activer la détection du codage

try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| detectCharset | boolean |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public int getResourceLoadingTimeout()
```


Obtient le délai d'attente pour le chargement des ressources externes.


**Note:** The default value is 10 seconds.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)


La valeur par défaut est de 30 secondes. Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents).

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setResourceLoadingTimeout(5000); // Définir le délai d'attente du chargement des ressources à 5 secondes

try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
int
### setResourceLoadingTimeout(int resourceLoadingTimeout) {#setResourceLoadingTimeout-int-}
```
public void setResourceLoadingTimeout(int resourceLoadingTimeout)
```


Définit le délai d'attente pour le chargement des ressources externes, comme les graphiques.


***Note:** The default value is 30 seconds.*


Cette option est prise en charge pour les documents de traitement de texte contenant des ressources externes.
La valeur par défaut est de 30 secondes. Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | resourceLoadingTimeout | int | Le délai d'attente de chargement, millisecondes. |
|

### getUrlConnectTimeout() {#getUrlConnectTimeout--}
```
public int getUrlConnectTimeout()
```


Obtient le délai d'attente de connexion pour créer un [Viewer](../../com.groupdocs.viewer/viewer) en utilisant java.net.URL afin de charger un document.


***Note:** The default value is 5 seconds.*


**Returns:**
int - le délai d'attente de connexion.

### setUrlConnectTimeout(int urlConnectTimeout) {#setUrlConnectTimeout-int-}
```
public void setUrlConnectTimeout(int urlConnectTimeout)
```


Définit le délai d'attente de connexion pour créer un [Viewer](../../com.groupdocs.viewer/viewer) en utilisant java.net.URL afin de charger un document.


***Note:** The default value is 5 seconds.*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | urlConnectTimeout | int | Le délai d'attente de connexion. |
|

### getUrlReadTimeout() {#getUrlReadTimeout--}
```
public int getUrlReadTimeout()
```


Obtient le délai d'attente de lecture pour créer un [Viewer](../../com.groupdocs.viewer/viewer) en utilisant java.net.URL afin de charger un document.


***Note:** The default value is 30 seconds.*


**Returns:**
int - le délai d'attente de lecture.

### setUrlReadTimeout(int urlReadTimeout) {#setUrlReadTimeout-int-}
```
public void setUrlReadTimeout(int urlReadTimeout)
```


Définit le délai d'attente de lecture pour créer un [Viewer](../../com.groupdocs.viewer/viewer) en utilisant java.net.URL afin de charger un document.


***Note:** The default value is 30 seconds.*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | urlReadTimeout | int | Le délai d'attente de lecture. |
|

### getArchiveSecurityOptions() {#getArchiveSecurityOptions--}
```
public ArchiveSecurityOptions getArchiveSecurityOptions()
```


Obtient les options de sécurité pour contrôler le processus d'extraction des archives.


***Note:** Not each archive type supports all options.*


**Returns:**
com.groupdocs.viewer.options.ArchiveSecurityOptions - l'objet d'options pour configurer le processus d'extraction des archives.

### setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions) {#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-}
```
public void setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)
```


Définit les options de sécurité pour contrôler le processus d'extraction des archives.


***Note:** Not each archive type supports all options.*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | archiveSecurityOptions | com.groupdocs.viewer.options.ArchiveSecurityOptions | L'objet d'options pour configurer le processus d'extraction des archives. |
|

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


Lorsqu'elle est définie sur `true`, toutes les ressources externes comme les images ne seront pas chargées sauf #getWhitelistedResources().getWhitelistedResources().

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Ignorer le chargement des ressources externes

try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```


Lorsqu'elle est définie sur `true`, toutes les ressources externes comme les images ne seront pas chargées sauf #getWhitelistedResources().getWhitelistedResources().

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Ignorer le chargement des ressources externes

try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | skipExternalResources | boolean | Le drapeau pour activer ou désactiver le chargement des ressources externes. |
|

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


La liste des fragments d'URL correspondant aux ressources externes qui doivent être chargées lorsque #isSkipExternalResources().isSkipExternalResources() est définie sur `true`.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Ignorer le chargement des ressources externes
loadOptions.getWhitelistedResources().add("avatars.githubusercontent.com"); // Activer le chargement des ressources externes qui contiennent le fragment 'avatars.githubusercontent.com' dans l'URL de la ressource.
try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whitelistedResources) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whitelistedResources)
```


Définit la liste des fragments d'URL correspondant aux ressources externes qui doivent être chargées lorsque #isSkipExternalResources().isSkipExternalResources() est réglé sur `true`.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Ignorer le chargement des ressources externes
loadOptions.setWhitelistedResources(Arrays.asList("avatars.githubusercontent.com")); // Activer le chargement des ressources externes qui contiennent le fragment 'avatars.githubusercontent.com' dans l'URL de la ressource.
try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | whitelistedResources | java.util.List<java.lang.String> | La liste des fragments d'URL correspondant aux ressources externes qui doivent être chargées. |
|

