---
title: "ArchiveOptions"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Tillhandahåller alternativ för rendering av arkivfiler."
type: docs
weight: 10
url: /sv/java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

Tillhandahåller alternativ för rendering av arkivfiler.


Den
ArchiveOptions
klassen representerar en uppsättning alternativ som kan användas för att konfigurera rendering av arkivfiler i visningsmodulen.
Den låter dig anpassa olika aspekter av renderingsprocessen, såsom antalet objekt per sida och så vidare.


Exempel på användning:

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
klassen tillhandahåller ett antal anpassningsalternativ för rendering av arkivfiler.
Du kan konfigurera dessa alternativ baserat på dina specifika krav för att uppnå önskat resultat.*

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [ArchiveOptions()](#ArchiveOptions--) | Skapar en ny instans av klassen ArchiveOptions med standardinställningar. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFolder()](#getFolder--) | Hämtar mappen i arkivet som kommer att användas för rendering. |
|
|  | [setFolder(String value)](#setFolder-java.lang.String-) | Ställer in mappen i arkivet som kommer att användas för rendering. |
|
|  | [getFileName()](#getFileName--) | Hämtar filnamnet som ska visas i rubriken. |
|
|  | [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | Ställer in filnamnet som ska visas i rubriken. |
|
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


Skapar en ny instans av klassen ArchiveOptions med standardinställningar.


### getFolder() {#getFolder--}
```
public final String getFolder()
```


Hämtar mappen i arkivet som kommer att användas för rendering.


Som standard renderar GroupDocs.Viewer objekt från alla mappar som finns i arkivet. För att rendera objekt från en specifik mapp, ställ in den här egenskapen.
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder).


**Returns:**
java.lang.String – mappen som ska renderas.

### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Ställer in mappen i arkivet som kommer att användas för rendering.


Som standard renderar GroupDocs.Viewer objekt från alla mappar som finns i arkivet. För att rendera objekt från en specifik mapp, ställ in den här egenskapen.
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | Mappen som ska renderas. |
|

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


Hämtar filnamnet som ska visas i rubriken.


Som standard visar GroupDocs.Viewer arkivfilens namn i rubriken på varje sida. För att ändra eller dölja detta namn, ställ in denna egenskap.
För mer information och kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name).


**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.

### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


Ställer in filnamnet som ska visas i rubriken.


Som standard visar GroupDocs.Viewer arkivfilens namn i rubriken på varje sida. För att ändra eller dölja detta namn, ställ in denna egenskap.
För mer information och kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileName | [FileName](../../com.groupdocs.viewer.options/filename) | Filnamnet som ska visas. |
|

