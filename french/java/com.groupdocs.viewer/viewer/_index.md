---
title: "Viewer"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Représente la classe principale qui contrôle le processus de rendu du document."
type: docs
weight: 12
url: /fr/java/com.groupdocs.viewer/viewer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Viewer implements Closeable
```

Représente la classe principale qui contrôle le processus de rendu du document.


La classe Viewer est le point d'entrée pour le rendu de documents utilisant le composant GroupDocs.Viewer.
Elle fournit des méthodes et des options pour charger des documents depuis diverses sources, personnaliser le processus de rendu et récupérer la sortie rendue dans différents formats.


Exemple d'utilisation :

````

 try (Viewer viewer = new Viewer("source.pdf")) {
     viewer.view(new PngViewOptions("result-page{0}.png"));
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [Viewer(InputStream fileStream)](#Viewer-java.io.InputStream-) | Initialise une nouvelle instance de la classe Viewer. |
|
|  | [Viewer(InputStream fileStream, boolean leaveOpen)](#Viewer-java.io.InputStream-boolean-) | Initialise une nouvelle instance de la classe Viewer. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-) | Initialise une nouvelle instance de la classe Viewer. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-) | Initialise une nouvelle instance de la classe Viewer. |
|
|  | [Viewer(InputStream fileStream, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-) | Initialise une nouvelle instance de la classe Viewer. |
|
|  | [Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-) | Initialise une nouvelle instance de la classe Viewer. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Initialise une nouvelle instance de la classe Viewer. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-) | Initialise une nouvelle instance de la classe Viewer. |
|
|  | [Viewer(URL url)](#Viewer-java.net.URL-) | Initialise une nouvelle instance de la classe Viewer. |
|
|  | [Viewer(URL url, LoadOptions loadOptions)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-) | Initialise une nouvelle instance de la classe Viewer. |
|
|  | [Viewer(URL url, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-) | Initialise une nouvelle instance de la classe Viewer. |
|
|  | [Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Initialise une nouvelle instance de la classe Viewer. |
|
|  | [Viewer(FileReader fileReader, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-) | Initialise une nouvelle instance de la classe Viewer. |
|
|  | [Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Initialise une nouvelle instance de la classe Viewer. |
|
|  | [Viewer(String filePath)](#Viewer-java.lang.String-) | Initialise une nouvelle instance de la classe Viewer. |
|
|  | [Viewer(Path filePath)](#Viewer-java.nio.file.Path-) | Initialise une nouvelle instance de la classe Viewer. |
|
|  | [Viewer(String filePath, LoadOptions loadOptions)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-) | Initialise une nouvelle instance de la classe Viewer. |
|
|  | [Viewer(Path filePath, LoadOptions loadOptions)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-) | Initialise une nouvelle instance de la classe Viewer. |
|
|  | [Viewer(String filePath, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-) | Initialise une nouvelle instance de la classe Viewer. |
|
|  | [Viewer(Path filePath, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-) | Initialise une nouvelle instance de la classe Viewer. |
|
|  | [Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Initialise une nouvelle instance de la classe Viewer. |
|
|  | [Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Initialise une nouvelle instance de la classe Viewer. |
|
## Champs

| Champ | Description |
| --- | --- |
| [LOAD_OPTIONS](#LOAD-OPTIONS) |  |
| [SETTINGS](#SETTINGS) |  |
| [FILE_READER](#FILE-READER) |  |
| [OPTIONS](#OPTIONS) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getViewInfo(ViewInfoOptions options)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-) | Renvoie des informations sur la vue et des informations spécifiques au document. |
|
|  | [getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-com.groupdocs.viewer.utils.CancellationToken-) | Renvoie des informations sur la vue et des informations spécifiques au document. |
|
|  | [getAttachments()](#getAttachments--) | Renvoie les pièces jointes contenues dans le document. |
|
|  | [getAttachments(CancellationToken cancellationToken)](#getAttachments-com.groupdocs.viewer.utils.CancellationToken-) | Renvoie les pièces jointes contenues dans le document. |
|
|  | [saveAttachment(Attachment attachment, OutputStream destination)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-) | Enregistre un fichier de pièce jointe dans le flux de destination. |
|
|  | [saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-com.groupdocs.viewer.utils.CancellationToken-) | Enregistre un fichier de pièce jointe dans le flux de destination. |
|
|  | [view(ViewOptions options)](#view-com.groupdocs.viewer.options.ViewOptions-) | Crée une vue de toutes les pages du document. |
|
|  | [view(ViewOptions options, CancellationToken cancellationToken)](#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-) | Crée une vue de toutes les pages du document. |
|
|  | [view(ViewOptions options, int pageNumber)](#view-com.groupdocs.viewer.options.ViewOptions-int-) | Crée une vue d’une page spécifique du document. |
|
|  | [view(ViewOptions options, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-int...-) | Crée une vue de pages spécifiques du document. |
|
|  | [view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-int...-) | Crée une vue de pages spécifiques du document. |
|
|  | [getAllFonts()](#getAllFonts--) | Renvoie toutes les polices utilisées dans les documents chargés, y compris celles intégrées dans le document lui‑même et les polices système installées dans le système d’exploitation et utilisées dans le document. |
|
|  | [search(SearchHighlightOptions options)](#search-com.groupdocs.viewer.options.SearchHighlightOptions-) | Effectue une recherche de texte et met en évidence les correspondances (si trouvées) dans le document chargé selon les options fournies. |
|
|  | [getFileInfo()](#getFileInfo--) | Renvoie des informations sur le fichier, telles que le type de fichier et un indicateur qui indique si le fichier est chiffré. |
|
|  | [close()](#close--) | Libère le flux de fichier et les ressources internes gérées. |
|
### Viewer(InputStream fileStream) {#Viewer-java.io.InputStream-}
```
public Viewer(InputStream fileStream)
```


Initialise une nouvelle instance de la classe Viewer.


Plus d’informations sur les types de fichiers pris en charge par GroupDocs.Viewer :
[Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | La méthode qui renvoie un flux lisible. |
|

### Viewer(InputStream fileStream, boolean leaveOpen) {#Viewer-java.io.InputStream-boolean-}
```
public Viewer(InputStream fileStream, boolean leaveOpen)
```


Initialise une nouvelle instance de la classe Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Le flux de fichier. |
|
|  | leaveOpen | boolean | true pour laisser le flux ouvert après la libération de l’objet Viewer ; sinon, false. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions)
```


Initialise une nouvelle instance de la classe Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Le flux lisible. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Les options de chargement du document. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)
```


Initialise une nouvelle instance de la classe Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Le flux de fichier. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Les options de chargement du document. |
|
|  | leaveOpen | boolean | true pour laisser le flux ouvert après la libération de l’objet Viewer ; sinon, false. |
|

### Viewer(InputStream fileStream, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, ViewerSettings settings)
```


Initialise une nouvelle instance de la classe Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Le flux de fichier. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Les paramètres du Viewer. |
|

### Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)
```


Initialise une nouvelle instance de la classe Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Le flux de fichier. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Les paramètres du Viewer. |
|
|  | leaveOpen | boolean | true pour laisser le flux ouvert après la libération de l’objet Viewer ; sinon, false. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)
```


Initialise une nouvelle instance de la classe Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Le flux de fichier. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Les options de chargement du document. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Les paramètres du Viewer. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)
```


Initialise une nouvelle instance de la classe Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Le flux de fichier. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Les options de chargement du document. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Les paramètres du Viewer. |
|
|  | leaveOpen | boolean | true pour laisser le flux ouvert après la libération de l’objet Viewer ; sinon, false. |
|

### Viewer(URL url) {#Viewer-java.net.URL-}
```
public Viewer(URL url)
```


Initialise une nouvelle instance de la classe Viewer.


Plus d’informations sur les types de fichiers pris en charge par GroupDocs.Viewer : [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | url | java.net.URL | Une URL vers un fichier qui doit être chargé dans le Viewer. |
|

### Viewer(URL url, LoadOptions loadOptions) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(URL url, LoadOptions loadOptions)
```


Initialise une nouvelle instance de la classe Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | url | java.net.URL | Une URL vers un fichier qui doit être chargé dans le Viewer. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Les options de chargement du document. |
|

### Viewer(URL url, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, ViewerSettings settings)
```


Initialise une nouvelle instance de la classe Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | url | java.net.URL | Une URL vers un fichier qui doit être chargé dans le Viewer. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Les paramètres du Viewer. |
|

### Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)
```


Initialise une nouvelle instance de la classe Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | url | java.net.URL | Une URL vers un fichier qui doit être chargé dans le Viewer. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Les options de chargement du document. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Les paramètres du Viewer. |
|

### Viewer(FileReader fileReader, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, ViewerSettings settings)
```


Initialise une nouvelle instance de la classe Viewer.


Ce constructeur vous permet de créer un objet Viewer pour afficher un document à partir d’un [FileReader](../../com.groupdocs.viewer.interfaces/filereader) avec les [ViewerSettings](../../com.groupdocs.viewer/viewersettings) spécifiés.
***Learn more**
* To learn about the file types supported by GroupDocs.Viewer, visit: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* To explore the features of GroupDocs.Viewer for Java, refer to: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | Le [FileReader](../../com.groupdocs.viewer.interfaces/filereader) contenant le document à charger dans le Viewer. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Les [ViewerSettings](../../com.groupdocs.viewer/viewersettings) à appliquer au Viewer. |
|

### Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)
```


Initialise une nouvelle instance de la classe Viewer.


Fournit des fonctionnalités pour charger et afficher des documents à l'aide de GroupDocs.Viewer.


**Note:** Ensure that the file reader, load options, and settings are properly configured for accurate document processing.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | Le lecteur de fichier. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Les options de chargement. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Les paramètres du Viewer. |
|

### Viewer(String filePath) {#Viewer-java.lang.String-}
```
public Viewer(String filePath)
```


Initialise une nouvelle instance de la classe Viewer.
***Learn more:**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier à rendre. |
|

### Viewer(Path filePath) {#Viewer-java.nio.file.Path-}
```
public Viewer(Path filePath)
```


Initialise une nouvelle instance de la classe Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Le chemin du fichier à rendre. |
|

### Viewer(String filePath, LoadOptions loadOptions) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(String filePath, LoadOptions loadOptions)
```


Initialise une nouvelle instance de la classe Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier à rendre. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Les options de chargement du document. |
|

### Viewer(Path filePath, LoadOptions loadOptions) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(Path filePath, LoadOptions loadOptions)
```


Initialise une nouvelle instance de la classe Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view a document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Le chemin du fichier à rendre. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Les options de chargement du document. |
|

### Viewer(String filePath, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, ViewerSettings settings)
```


Initialise une nouvelle instance de la classe Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier à rendre. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Les paramètres du Viewer. |
|

### Viewer(Path filePath, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, ViewerSettings settings)
```


Initialise une nouvelle instance de la classe Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Le chemin du fichier à rendre. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Les paramètres du Viewer. |
|

### Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Initialise une nouvelle instance de la classe Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier à rendre. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Les options de chargement du document. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Les paramètres du Viewer. |
|

### Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Initialise une nouvelle instance de la classe Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Le chemin du fichier à rendre. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Les options de chargement du document. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Les paramètres du Viewer. |
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


Renvoie des informations sur la vue et des informations spécifiques au document.
***Learn more:**
* Learn more about the document - file type, page count, and other format specific properties: [How to get file information using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+file+information)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | Les options d'informations d'affichage. |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about the view and document specific information.

### getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken) {#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-com.groupdocs.viewer.utils.CancellationToken-}
```
public final ViewInfo getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)
```


Renvoie des informations sur la vue et des informations spécifiques au document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | Les options d'informations d'affichage. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Jeton d'annulation pour annuler l'opération. |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about the view and document specific information.

### getAttachments() {#getAttachments--}
```
public final List<Attachment> getAttachments()
```


Renvoie les pièces jointes contenues dans le document.
***Learn more:**
* Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+attachments)
* Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Save+attachments)*


**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - pièces jointes contenues dans le document.

### getAttachments(CancellationToken cancellationToken) {#getAttachments-com.groupdocs.viewer.utils.CancellationToken-}
```
public final List<Attachment> getAttachments(CancellationToken cancellationToken)
```


Renvoie les pièces jointes contenues dans le document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Jeton d'annulation pour annuler l'opération. |
|

**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - pièces jointes contenues dans le document.

### saveAttachment(Attachment attachment, OutputStream destination) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-}
```
public void saveAttachment(Attachment attachment, OutputStream destination)
```


Enregistre un fichier de pièce jointe dans le flux de destination.
***Learn more:**
* Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+attachments)
* Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Save+attachments)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | La pièce jointe. |
|
|  | destination | java.io.OutputStream | Le flux d'écriture. |
|

### saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-com.groupdocs.viewer.utils.CancellationToken-}
```
public void saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken)
```


Enregistre un fichier de pièce jointe dans le flux de destination.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | La pièce jointe. |
|
|  | destination | java.io.OutputStream | Le flux d'écriture. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Jeton d'annulation pour annuler l'opération. |
|

### view(ViewOptions options) {#view-com.groupdocs.viewer.options.ViewOptions-}
```
public final void view(ViewOptions options)
```


Crée une vue de toutes les pages du document.
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Les options d'affichage. |
|

### view(ViewOptions options, CancellationToken cancellationToken) {#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-}
```
public final void view(ViewOptions options, CancellationToken cancellationToken)
```


Crée une vue de toutes les pages du document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Les options d'affichage. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Jeton d'annulation pour annuler le processus de rendu. |
|

### view(ViewOptions options, int pageNumber) {#view-com.groupdocs.viewer.options.ViewOptions-int-}
```
public final void view(ViewOptions options, int pageNumber)
```


Crée une vue d’une page spécifique du document.
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Les options d'affichage. |
|
|  | pageNumber | int | Le numéro de page à afficher. |
|

### view(ViewOptions options, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-int...-}
```
public final void view(ViewOptions options, int[] pageNumbers)
```


Crée une vue de pages spécifiques du document.
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Les options d'affichage. |
|
|  | pageNumbers | int[] | Les numéros de page à afficher. |
|

### view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-int...-}
```
public final void view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers)
```


Crée une vue de pages spécifiques du document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Les options d'affichage. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Jeton d'annulation pour annuler le processus de rendu. |
|
|  | pageNumbers | int[] | Les numéros de page à afficher. |
|

### getAllFonts() {#getAllFonts--}
```
public IFontInfo[] getAllFonts()
```


Renvoie toutes les polices utilisées dans les documents chargés, y compris celles intégrées dans le document lui‑même et les polices système installées dans le système d’exploitation et utilisées dans le document.

Pour plus de détails, voir le
[documentation](../https://docs.groupdocs.com/viewer/net/getting-used-fonts/).


**Returns:**
com.groupdocs.viewer.fonts.IFontInfo[] - Liste non nulle de toutes les polices utilisées dans le document chargé dans cette instance [Viewer](../../com.groupdocs.viewer/viewer).

### search(SearchHighlightOptions options) {#search-com.groupdocs.viewer.options.SearchHighlightOptions-}
```
public void search(SearchHighlightOptions options)
```


Effectue une recherche de texte et met en évidence les correspondances (si trouvées) dans le document chargé selon les options fournies.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | options | com.groupdocs.viewer.options.SearchHighlightOptions | Options de recherche et de mise en surbrillance, incluant une phrase texte à rechercher. Ne peut pas être nul. |
|

### getFileInfo() {#getFileInfo--}
```
public FileInfo getFileInfo()
```


Renvoie des informations sur le fichier, telles que le type de fichier et un indicateur qui indique si le fichier est chiffré.
***Learn more:**
* Learn more about how to check if a file is encrypted: [How to check if a file is encrypted](../https://docs.groupdocs.com/viewer/net/how-to-check-if-file-is-encrypted/)*


**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - the file information.

### close() {#close--}
```
public final void close()
```


Libère le flux de fichier et les ressources internes gérées.


