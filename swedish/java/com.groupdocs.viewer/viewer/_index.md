---
title: "Viewer"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Representerar huvudklassen som styr dokumentrenderingsprocessen."
type: docs
weight: 12
url: /sv/java/com.groupdocs.viewer/viewer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Viewer implements Closeable
```

Representerar huvudklassen som styr dokumentrenderingsprocessen.


Viewer-klassen är ingångspunkten för att rendera dokument med hjälp av GroupDocs.Viewer-komponenten.
Den tillhandahåller metoder och alternativ för att läsa in dokument från olika källor, anpassa renderingsprocessen och hämta den renderade utdata i olika format.


Exempel på användning:

````

 try (Viewer viewer = new Viewer("source.pdf")) {
     viewer.view(new PngViewOptions("result-page{0}.png"));
 }
 
````


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [Viewer(InputStream fileStream)](#Viewer-java.io.InputStream-) | Initierar en ny instans av Viewer-klassen. |
|
|  | [Viewer(InputStream fileStream, boolean leaveOpen)](#Viewer-java.io.InputStream-boolean-) | Initierar en ny instans av Viewer-klassen. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-) | Initierar en ny instans av Viewer-klassen. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-) | Initierar en ny instans av Viewer-klassen. |
|
|  | [Viewer(InputStream fileStream, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-) | Initierar en ny instans av Viewer-klassen. |
|
|  | [Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-) | Initierar en ny instans av Viewer-klassen. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Initierar en ny instans av Viewer-klassen. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-) | Initierar ny instans av Viewer-klassen. |
|
|  | [Viewer(URL url)](#Viewer-java.net.URL-) | Initierar en ny instans av Viewer-klassen. |
|
|  | [Viewer(URL url, LoadOptions loadOptions)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-) | Initierar en ny instans av Viewer-klassen. |
|
|  | [Viewer(URL url, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-) | Initierar en ny instans av Viewer-klassen. |
|
|  | [Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Initierar en ny instans av Viewer-klassen. |
|
|  | [Viewer(FileReader fileReader, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-) | Initierar en ny instans av Viewer-klassen. |
|
|  | [Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Initierar en ny instans av Viewer-klassen. |
|
|  | [Viewer(String filePath)](#Viewer-java.lang.String-) | Initierar en ny instans av Viewer-klassen. |
|
|  | [Viewer(Path filePath)](#Viewer-java.nio.file.Path-) | Initierar en ny instans av Viewer-klassen. |
|
|  | [Viewer(String filePath, LoadOptions loadOptions)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-) | Initierar en ny instans av Viewer-klassen. |
|
|  | [Viewer(Path filePath, LoadOptions loadOptions)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-) | Initierar en ny instans av Viewer-klassen. |
|
|  | [Viewer(String filePath, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-) | Initierar en ny instans av Viewer-klassen. |
|
|  | [Viewer(Path filePath, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-) | Initierar en ny instans av Viewer-klassen. |
|
|  | [Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Initierar en ny instans av Viewer-klassen. |
|
|  | [Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Initierar en ny instans av Viewer-klassen. |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
| [LOAD_OPTIONS](#LOAD-OPTIONS) |  |
| [SETTINGS](#SETTINGS) |  |
| [FILE_READER](#FILE-READER) |  |
| [OPTIONS](#OPTIONS) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getViewInfo(ViewInfoOptions options)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-) | Returnerar information om vyn och dokumentspecifik information. |
|
|  | [getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-com.groupdocs.viewer.utils.CancellationToken-) | Returnerar information om vyn och dokumentspecifik information. |
|
|  | [getAttachments()](#getAttachments--) | Returnerar bilagor som finns i dokumentet. |
|
|  | [getAttachments(CancellationToken cancellationToken)](#getAttachments-com.groupdocs.viewer.utils.CancellationToken-) | Returnerar bilagor som finns i dokumentet. |
|
|  | [saveAttachment(Attachment attachment, OutputStream destination)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-) | Sparar en bilagefil till destinationsströmmen. |
|
|  | [saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-com.groupdocs.viewer.utils.CancellationToken-) | Sparar en bilagefil till destinationsströmmen. |
|
|  | [view(ViewOptions options)](#view-com.groupdocs.viewer.options.ViewOptions-) | Skapar en vy av alla dokumentsidor. |
|
|  | [view(ViewOptions options, CancellationToken cancellationToken)](#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-) | Skapar en vy av alla dokumentsidor. |
|
|  | [view(ViewOptions options, int pageNumber)](#view-com.groupdocs.viewer.options.ViewOptions-int-) | Skapar en vy av en specifik dokumentsida. |
|
|  | [view(ViewOptions options, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-int...-) | Skapar en vy av specifika dokumentsidor. |
|
|  | [view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-int...-) | Skapar en vy av specifika dokumentsidor. |
|
|  | [getAllFonts()](#getAllFonts--) | Returnerar alla teckensnitt som används i de inlästa dokumenten, inklusive de som är inbäddade i själva dokumentet samt de systemteckensnitt som är installerade i operativsystemet och används i dokumentet. |
|
|  | [search(SearchHighlightOptions options)](#search-com.groupdocs.viewer.options.SearchHighlightOptions-) | Utför en textsökning och markerar träffar (om några hittas) i det inlästa dokumentet enligt de angivna alternativen. |
|
|  | [getFileInfo()](#getFileInfo--) | Returnerar information om filen, såsom filtyp och en flagga som indikerar om filen är krypterad. |
|
|  | [close()](#close--) | Frigör filströmmen och hanterade interna resurser. |
|
### Viewer(InputStream fileStream) {#Viewer-java.io.InputStream-}
```
public Viewer(InputStream fileStream)
```


Initierar en ny instans av Viewer-klassen.


Mer om filtyper som stöds av GroupDocs.Viewer:
[Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Metoden som returnerar en läsbar ström. |
|

### Viewer(InputStream fileStream, boolean leaveOpen) {#Viewer-java.io.InputStream-boolean-}
```
public Viewer(InputStream fileStream, boolean leaveOpen)
```


Initierar en ny instans av Viewer-klassen.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Filströmmen. |
|
|  | leaveOpen | boolean | true för att lämna strömmen öppen efter att Viewer-objektet har frigjorts; annars false. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions)
```


Initierar en ny instans av Viewer-klassen.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Den läsbara strömmen. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Dokumentets laddningsalternativ. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)
```


Initierar en ny instans av Viewer-klassen.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Filströmmen. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Dokumentets laddningsalternativ. |
|
|  | leaveOpen | boolean | true för att lämna strömmen öppen efter att Viewer-objektet har frigjorts; annars false. |
|

### Viewer(InputStream fileStream, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, ViewerSettings settings)
```


Initierar en ny instans av Viewer-klassen.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Filströmmen. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer-inställningarna. |
|

### Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)
```


Initierar en ny instans av Viewer-klassen.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Filströmmen. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer-inställningarna. |
|
|  | leaveOpen | boolean | true för att lämna strömmen öppen efter att Viewer-objektet har frigjorts; annars false. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)
```


Initierar en ny instans av Viewer-klassen.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Filströmmen. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Dokumentets laddningsalternativ. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer-inställningarna. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)
```


Initierar ny instans av Viewer-klassen.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Filströmmen. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Dokumentets laddningsalternativ. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer-inställningarna. |
|
|  | leaveOpen | boolean | true för att lämna strömmen öppen efter att Viewer-objektet har frigjorts; annars false. |
|

### Viewer(URL url) {#Viewer-java.net.URL-}
```
public Viewer(URL url)
```


Initierar en ny instans av Viewer-klassen.


Mer om filtyper som stöds av GroupDocs.Viewer: [Dokumentformat som stöds av GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | url | java.net.URL | En URL till en fil som ska laddas in i Viewer. |
|

### Viewer(URL url, LoadOptions loadOptions) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(URL url, LoadOptions loadOptions)
```


Initierar en ny instans av Viewer-klassen.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | url | java.net.URL | En URL till en fil som ska laddas in i Viewer. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Dokumentets laddningsalternativ. |
|

### Viewer(URL url, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, ViewerSettings settings)
```


Initierar en ny instans av Viewer-klassen.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | url | java.net.URL | En URL till en fil som ska laddas in i Viewer. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer-inställningarna. |
|

### Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)
```


Initierar en ny instans av Viewer-klassen.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | url | java.net.URL | En URL till en fil som ska laddas in i Viewer. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Dokumentets laddningsalternativ. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer-inställningarna. |
|

### Viewer(FileReader fileReader, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, ViewerSettings settings)
```


Initierar en ny instans av Viewer-klassen.


Denna konstruktor låter dig skapa ett Viewer-objekt för att visa ett dokument från en [FileReader](../../com.groupdocs.viewer.interfaces/filereader) med de angivna [ViewerSettings](../../com.groupdocs.viewer/viewersettings).
***Learn more**
* To learn about the file types supported by GroupDocs.Viewer, visit: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* To explore the features of GroupDocs.Viewer for Java, refer to: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | Den [FileReader](../../com.groupdocs.viewer.interfaces/filereader) som innehåller dokumentet som ska laddas in i Viewer. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | De [ViewerSettings](../../com.groupdocs.viewer/viewersettings) som ska tillämpas på Viewer. |
|

### Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)
```


Initierar en ny instans av Viewer-klassen.


Tillhandahåller funktionalitet för att ladda och visa dokument med hjälp av GroupDocs.Viewer.


**Note:** Ensure that the file reader, load options, and settings are properly configured for accurate document processing.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | Fil-läsaren. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Laddningsalternativen. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer-inställningarna. |
|

### Viewer(String filePath) {#Viewer-java.lang.String-}
```
public Viewer(String filePath)
```


Initierar en ny instans av Viewer-klassen.
***Learn more:**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Sökvägen till filen som ska renderas. |
|

### Viewer(Path filePath) {#Viewer-java.nio.file.Path-}
```
public Viewer(Path filePath)
```


Initierar en ny instans av Viewer-klassen.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Sökvägen till filen som ska renderas. |
|

### Viewer(String filePath, LoadOptions loadOptions) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(String filePath, LoadOptions loadOptions)
```


Initierar en ny instans av Viewer-klassen.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Sökvägen till filen som ska renderas. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Dokumentets laddningsalternativ. |
|

### Viewer(Path filePath, LoadOptions loadOptions) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(Path filePath, LoadOptions loadOptions)
```


Initierar en ny instans av Viewer-klassen.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view a document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Sökvägen till filen som ska renderas. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Dokumentets laddningsalternativ. |
|

### Viewer(String filePath, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, ViewerSettings settings)
```


Initierar en ny instans av Viewer-klassen.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Sökvägen till filen som ska renderas. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer-inställningarna. |
|

### Viewer(Path filePath, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, ViewerSettings settings)
```


Initierar en ny instans av Viewer-klassen.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Sökvägen till filen som ska renderas. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer-inställningarna. |
|

### Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Initierar en ny instans av Viewer-klassen.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Sökvägen till filen som ska renderas. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Dokumentets laddningsalternativ. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer-inställningarna. |
|

### Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Initierar en ny instans av Viewer-klassen.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Sökvägen till filen som ska renderas. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Dokumentets laddningsalternativ. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer-inställningarna. |
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


Returnerar information om vyn och dokumentspecifik information.
***Learn more:**
* Learn more about the document - file type, page count, and other format specific properties: [How to get file information using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+file+information)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | Visningsinformationsalternativen. |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about the view and document specific information.

### getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken) {#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-com.groupdocs.viewer.utils.CancellationToken-}
```
public final ViewInfo getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)
```


Returnerar information om vyn och dokumentspecifik information.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | Visningsinformationsalternativen. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Avbrotts-token för att avbryta operationen. |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about the view and document specific information.

### getAttachments() {#getAttachments--}
```
public final List<Attachment> getAttachments()
```


Returnerar bilagor som finns i dokumentet.
***Learn more:**
* Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+attachments)
* Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Save+attachments)*


**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - bilagor som finns i dokumentet.

### getAttachments(CancellationToken cancellationToken) {#getAttachments-com.groupdocs.viewer.utils.CancellationToken-}
```
public final List<Attachment> getAttachments(CancellationToken cancellationToken)
```


Returnerar bilagor som finns i dokumentet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Avbrotts-token för att avbryta operationen. |
|

**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - bilagor som finns i dokumentet.

### saveAttachment(Attachment attachment, OutputStream destination) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-}
```
public void saveAttachment(Attachment attachment, OutputStream destination)
```


Sparar en bilagefil till destinationsströmmen.
***Learn more:**
* Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+attachments)
* Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Save+attachments)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | Bilagan. |
|
|  | destination | java.io.OutputStream | Den skrivbara strömmen. |
|

### saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-com.groupdocs.viewer.utils.CancellationToken-}
```
public void saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken)
```


Sparar en bilagefil till destinationsströmmen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | Bilagan. |
|
|  | destination | java.io.OutputStream | Den skrivbara strömmen. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Avbrotts-token för att avbryta operationen. |
|

### view(ViewOptions options) {#view-com.groupdocs.viewer.options.ViewOptions-}
```
public final void view(ViewOptions options)
```


Skapar en vy av alla dokumentsidor.
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Visningsalternativen. |
|

### view(ViewOptions options, CancellationToken cancellationToken) {#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-}
```
public final void view(ViewOptions options, CancellationToken cancellationToken)
```


Skapar en vy av alla dokumentsidor.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Visningsalternativen. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Avbokningstoken för att avbryta renderingsprocessen. |
|

### view(ViewOptions options, int pageNumber) {#view-com.groupdocs.viewer.options.ViewOptions-int-}
```
public final void view(ViewOptions options, int pageNumber)
```


Skapar en vy av en specifik dokumentsida.
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Visningsalternativen. |
|
|  | pageNumber | int | Sidnumret att visa. |
|

### view(ViewOptions options, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-int...-}
```
public final void view(ViewOptions options, int[] pageNumbers)
```


Skapar en vy av specifika dokumentsidor.
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Visningsalternativen. |
|
|  | pageNumbers | int[] | Sidnumren att visa. |
|

### view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-int...-}
```
public final void view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers)
```


Skapar en vy av specifika dokumentsidor.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Visningsalternativen. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Avbokningstoken för att avbryta renderingsprocessen. |
|
|  | pageNumbers | int[] | Sidnumren att visa. |
|

### getAllFonts() {#getAllFonts--}
```
public IFontInfo[] getAllFonts()
```


Returnerar alla teckensnitt som används i de inlästa dokumenten, inklusive de som är inbäddade i själva dokumentet samt de systemteckensnitt som är installerade i operativsystemet och används i dokumentet.

För detaljer, se
[documentation](../https://docs.groupdocs.com/viewer/net/getting-used-fonts/).


**Returns:**
com.groupdocs.viewer.fonts.IFontInfo[] - Icke-null lista över alla teckensnitt som används i dokumentet som laddas in i denna [Viewer](../../com.groupdocs.viewer/viewer) instans.

### search(SearchHighlightOptions options) {#search-com.groupdocs.viewer.options.SearchHighlightOptions-}
```
public void search(SearchHighlightOptions options)
```


Utför en textsökning och markerar träffar (om några hittas) i det inlästa dokumentet enligt de angivna alternativen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | options | com.groupdocs.viewer.options.SearchHighlightOptions | Sök- och markeringsalternativ, inklusive en textfras att söka efter. Får inte vara null. |
|

### getFileInfo() {#getFileInfo--}
```
public FileInfo getFileInfo()
```


Returnerar information om filen, såsom filtyp och en flagga som indikerar om filen är krypterad.
***Learn more:**
* Learn more about how to check if a file is encrypted: [How to check if a file is encrypted](../https://docs.groupdocs.com/viewer/net/how-to-check-if-file-is-encrypted/)*


**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - the file information.

### close() {#close--}
```
public final void close()
```


Frigör filströmmen och hanterade interna resurser.


