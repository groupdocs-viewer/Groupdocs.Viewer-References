---
title: "ArchiveOptions"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Biedt opties voor het renderen van archiefbestanden."
type: docs
weight: 10
url: /nl/nodejs-java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

Biedt opties voor het renderen van archiefbestanden.

De ArchiveOptions class vertegenwoordigt een reeks opties die kunnen worden gebruikt om het renderen van archiefbestanden in de viewermodule te configureren. Het stelt u in staat verschillende aspecten van het renderproces aan te passen, zoals het aantal items per pagina en dergelijke.

Voorbeeldgebruik:

```

 // Create an instance of ArchiveOptions
 ArchiveOptions options = new ArchiveOptions();

 // Set the count of items to be shown on each page
 options.setItemsPerPage(16);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, options)) {
     // Use the viewer object for document rendering
 }
 
```

***Note:** The  ArchiveOptions  class provides a range of customization options for rendering archive files. You can configure these options based on your specific requirements to achieve the desired output.*
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ArchiveOptions()](#ArchiveOptions--) | Maakt een nieuw exemplaar van de ArchiveOptions class met standaardinstellingen. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFolder()](#getFolder--) | Haalt de map binnen het archief op die zal worden gebruikt voor het renderen. |
| [setFolder(String value)](#setFolder-java.lang.String-) | Stelt de map in het archief in die zal worden gebruikt voor het renderen. |
| [getFileName()](#getFileName--) | Haalt de bestandsnaam op die in de koptekst moet worden weergegeven. |
| [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | Stelt de bestandsnaam in die in de koptekst moet worden weergegeven. |
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


Maakt een nieuw exemplaar van de ArchiveOptions class met standaardinstellingen.

### getFolder() {#getFolder--}
```
public final String getFolder()
```


Haalt de map binnen het archief op die zal worden gebruikt voor het renderen.

Standaard rendert GroupDocs.Viewer items uit alle mappen die in het archief zijn opgenomen. Om items uit een specifieke map te renderen, stelt u deze eigenschap in. Voor een codevoorbeeld, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder

**Returns:**
java.lang.String - de map die moet worden gerenderd.
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Stelt de map in het archief in die zal worden gebruikt voor het renderen.

Standaard rendert GroupDocs.Viewer items uit alle mappen die in het archief zijn opgenomen. Om items uit een specifieke map te renderen, stelt u deze eigenschap in. Voor een codevoorbeeld, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String | De map die moet worden gerenderd. |

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


Haalt de bestandsnaam op die in de koptekst moet worden weergegeven.

Standaard toont GroupDocs.Viewer de archiefbestandsnaam in de koptekst van elke pagina. Om deze naam te wijzigen of te verbergen, stelt u deze eigenschap in. Voor meer informatie en een codevoorbeeld, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.
### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


Stelt de bestandsnaam in die in de koptekst moet worden weergegeven.

Standaard toont GroupDocs.Viewer de archiefbestandsnaam in de koptekst van elke pagina. Om deze naam te wijzigen of te verbergen, stelt u deze eigenschap in. Voor meer informatie en een codevoorbeeld, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | [FileName](../../com.groupdocs.viewer.options/filename) | De bestandsnaam die moet worden weergegeven. |

