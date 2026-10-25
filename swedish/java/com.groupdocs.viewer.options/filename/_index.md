---
title: "FileName"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Representerar namnet på en fil i ett arkiv."
type: docs
weight: 15
url: /sv/java/com.groupdocs.viewer.options/filename/
---
**Inheritance:**
java.lang.Object
```
public class FileName
```

Representerar namnet på en fil i ett arkiv.


FileName-klassen kapslar in namnet på en fil utan någon sökväg eller kataloginformation.
Den tillhandahåller metoder för att manipulera och hämta information om filnamnet.


Exempel på användning:

````

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.getArchiveOptions().setFileName(new FileName("my-file-name"));

 final LoadOptions loadOptions = new LoadOptions(FileType.ZIP);
 try (final Viewer viewer = new Viewer(documentPath, loadOptions)) {
     viewer.view(options);
     // Use the viewer object for archive document rendering
 }
 
````


***Note:** The FileName class is used to work with file names and does not handle file operations or manipulation.*

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [FileName(String fileName)](#FileName-java.lang.String-) | Initierar en ny instans av |
FileName
klassen.
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [EMPTY](#EMPTY) | Representerar ett tomt filnamn. |
|
|  | [SOURCE](#SOURCE) | Representerar namnet på källfilen. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getText()](#getText--) |  |
|  | [toString()](#toString--) | Returnerar en strängrepresentation av det aktuella objektet. |
|
### FileName(String fileName) {#FileName-java.lang.String-}
```
public FileName(String fileName)
```


Initierar en ny instans av
FileName
klassen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileName | java.lang.String | Namnet på filen. |
|

### EMPTY {#EMPTY}
```
public static final FileName EMPTY
```


Representerar ett tomt filnamn.


### SOURCE {#SOURCE}
```
public static final FileName SOURCE
```


Representerar namnet på källfilen.


### getText() {#getText--}
```
public String getText()
```




**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Returnerar en strängrepresentation av det aktuella objektet.


**Returns:**
java.lang.String - en strängrepresentation av det aktuella objektet.

