---
title: "ArchiveOptions"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Biedt opties voor het renderen van archiefbestanden."
type: docs
weight: 10
url: /nl/java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

Biedt opties voor het renderen van archiefbestanden.


De
ArchiveOptions
klasse vertegenwoordigt een reeks opties die kunnen worden gebruikt om de weergave van archiefbestanden in de viewer-module te configureren.
Het stelt u in staat verschillende aspecten van het weergaveproces aan te passen, zoals het aantal items per pagina en dergelijke.


Voorbeeldgebruik:

````

 // Create an instance of ArchiveOptions
 ArchiveOptions options = new ArchiveOptions();

 // Set the count of items to be shown on each page
 options.setItemsPerPage(16);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, options)) {
     // Use the viewer object for document rendering
 }
 
````


***Note:** The 
ArchiveOptions
klasse biedt een reeks aanpassingsopties voor het weergeven van archiefbestanden.
U kunt deze opties configureren op basis van uw specifieke eisen om de gewenste output te bereiken.*

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [ArchiveOptions()](#ArchiveOptions--) | Maakt een nieuw exemplaar van de ArchiveOptions-klasse met standaardinstellingen. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFolder()](#getFolder--) | Haalt de map binnen het archief op die zal worden gebruikt voor weergave. |
|
|  | [setFolder(String value)](#setFolder-java.lang.String-) | Stelt de map binnen het archief in die zal worden gebruikt voor weergave. |
|
|  | [getFileName()](#getFileName--) | Haalt de bestandsnaam op die in de header wordt weergegeven. |
|
|  | [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | Stelt de bestandsnaam in die in de header wordt weergegeven. |
|
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


Maakt een nieuw exemplaar van de ArchiveOptions-klasse met standaardinstellingen.


### getFolder() {#getFolder--}
```
public final String getFolder()
```


Haalt de map binnen het archief op die zal worden gebruikt voor weergave.


Standaard rendert GroupDocs.Viewer items uit alle mappen die in het archief zitten. Om items uit een specifieke map weer te geven, stelt u deze eigenschap in.
Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder).


**Returns:**
java.lang.String - de map die moet worden weergegeven.

### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Stelt de map binnen het archief in die zal worden gebruikt voor weergave.


Standaard rendert GroupDocs.Viewer items uit alle mappen die in het archief zitten. Om items uit een specifieke map weer te geven, stelt u deze eigenschap in.
Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | De map die moet worden weergegeven. |
|

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


Haalt de bestandsnaam op die in de header wordt weergegeven.


Standaard toont GroupDocs.Viewer de archiefbestandsnaam in de koptekst van elke pagina. Om deze naam te wijzigen of te verbergen, stelt u deze eigenschap in.
Voor meer informatie en een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name).


**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.

### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


Stelt de bestandsnaam in die in de header wordt weergegeven.


Standaard toont GroupDocs.Viewer de archiefbestandsnaam in de koptekst van elke pagina. Om deze naam te wijzigen of te verbergen, stelt u deze eigenschap in.
Voor meer informatie en een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileName | [FileName](../../com.groupdocs.viewer.options/filename) | De bestandsnaam die moet worden weergegeven. |
|

