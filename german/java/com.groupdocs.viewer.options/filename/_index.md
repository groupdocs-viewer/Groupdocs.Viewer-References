---
title: "FileName"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt den Namen einer Datei in einem Archiv dar."
type: docs
weight: 15
url: /de/java/com.groupdocs.viewer.options/filename/
---
**Inheritance:**
java.lang.Object
```
public class FileName
```

Stellt den Namen einer Datei in einem Archiv dar.


Die FileName‑Klasse kapselt den Namen einer Datei ohne Pfad‑ oder Verzeichnisinformationen.
Sie bietet Methoden zum Manipulieren und Abrufen von Informationen über den Dateinamen.


Beispielverwendung:

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

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [FileName(String fileName)](#FileName-java.lang.String-) | Initialisiert eine neue Instanz von |
FileName
Klasse.
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [EMPTY](#EMPTY) | Stellt einen leeren Dateinamen dar. |
|
|  | [SOURCE](#SOURCE) | Stellt den Namen der Quelldatei dar. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getText()](#getText--) |  |
|  | [toString()](#toString--) | Gibt eine String-Darstellung des aktuellen Objekts zurück. |
|
### FileName(String fileName) {#FileName-java.lang.String-}
```
public FileName(String fileName)
```


Initialisiert eine neue Instanz von
FileName
Klasse.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileName | java.lang.String | Der Name der Datei. |
|

### EMPTY {#EMPTY}
```
public static final FileName EMPTY
```


Stellt einen leeren Dateinamen dar.


### SOURCE {#SOURCE}
```
public static final FileName SOURCE
```


Stellt den Namen der Quelldatei dar.


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


Gibt eine String-Darstellung des aktuellen Objekts zurück.


**Returns:**
java.lang.String – eine String-Darstellung des aktuellen Objekts.

