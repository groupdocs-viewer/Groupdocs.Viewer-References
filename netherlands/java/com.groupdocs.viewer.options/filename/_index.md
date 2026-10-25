---
title: "FileName"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Stelt de naam van een bestand in een archief voor."
type: docs
weight: 15
url: /nl/java/com.groupdocs.viewer.options/filename/
---
**Inheritance:**
java.lang.Object
```
public class FileName
```

Stelt de naam van een bestand in een archief voor.


De FileName‑klasse omvat de naam van een bestand zonder pad‑ of directory‑informatie.
Het biedt methoden om de bestandsnaam te manipuleren en informatie erover op te halen.


Voorbeeldgebruik:

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

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [FileName(String fileName)](#FileName-java.lang.String-) | Initialiseert een nieuw exemplaar van de |
FileName
klasse.
|
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [EMPTY](#EMPTY) | Vertegenwoordigt een lege bestandsnaam. |
|
|  | [SOURCE](#SOURCE) | Vertegenwoordigt de naam van het bronbestand. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getText()](#getText--) |  |
|  | [toString()](#toString--) | Retourneert een stringrepresentatie van het huidige object. |
|
### FileName(String fileName) {#FileName-java.lang.String-}
```
public FileName(String fileName)
```


Initialiseert een nieuw exemplaar van de
FileName
klasse.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileName | java.lang.String | De naam van het bestand. |
|

### EMPTY {#EMPTY}
```
public static final FileName EMPTY
```


Vertegenwoordigt een lege bestandsnaam.


### SOURCE {#SOURCE}
```
public static final FileName SOURCE
```


Vertegenwoordigt de naam van het bronbestand.


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


Retourneert een stringrepresentatie van het huidige object.


**Returns:**
java.lang.String - een stringrepresentatie van het huidige object.

