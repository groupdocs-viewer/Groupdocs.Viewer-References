---
title: "ArchiveOptions"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt Optionen zum Rendern von Archivdateien bereit."
type: docs
weight: 10
url: /de/java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

Stellt Optionen zum Rendern von Archivdateien bereit.


Die
ArchiveOptions
Die Klasse repräsentiert einen Satz von Optionen, die verwendet werden können, um das Rendern von Archivdateien im Viewer‑Modul zu konfigurieren.
Sie ermöglicht es Ihnen, verschiedene Aspekte des Renderprozesses anzupassen, wie z. B. die Anzahl der Elemente pro Seite und so weiter.


Beispielverwendung:

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
Die Klasse bietet eine Reihe von Anpassungsoptionen für das Rendern von Archivdateien.
Sie können diese Optionen basierend auf Ihren spezifischen Anforderungen konfigurieren, um das gewünschte Ergebnis zu erzielen.*

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [ArchiveOptions()](#ArchiveOptions--) | Erstellt eine neue Instanz der Klasse ArchiveOptions mit den Standardeinstellungen. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFolder()](#getFolder--) | Ruft den Ordner im Archiv ab, der für das Rendern verwendet wird. |
|
|  | [setFolder(String value)](#setFolder-java.lang.String-) | Legt den Ordner im Archiv fest, der für das Rendern verwendet wird. |
|
|  | [getFileName()](#getFileName--) | Ruft den Dateinamen ab, der in der Kopfzeile angezeigt wird. |
|
|  | [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | Legt den Dateinamen fest, der in der Kopfzeile angezeigt wird. |
|
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


Erstellt eine neue Instanz der Klasse ArchiveOptions mit den Standardeinstellungen.


### getFolder() {#getFolder--}
```
public final String getFolder()
```


Ruft den Ordner im Archiv ab, der für das Rendern verwendet wird.


Standardmäßig rendert GroupDocs.Viewer Elemente aus allen im Archiv enthaltenen Ordnern. Um Elemente aus einem bestimmten Ordner zu rendern, setzen Sie diese Eigenschaft.
Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder).


**Returns:**
java.lang.String – der zu rendernde Ordner.

### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Legt den Ordner im Archiv fest, der für das Rendern verwendet wird.


Standardmäßig rendert GroupDocs.Viewer Elemente aus allen im Archiv enthaltenen Ordnern. Um Elemente aus einem bestimmten Ordner zu rendern, setzen Sie diese Eigenschaft.
Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Der zu rendernde Ordner. |
|

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


Ruft den Dateinamen ab, der in der Kopfzeile angezeigt wird.


Standardmäßig zeigt GroupDocs.Viewer den Archivdateinamen in der Kopfzeile jeder Seite an. Um diesen Namen zu ändern oder zu verbergen, setzen Sie diese Eigenschaft.
Für weitere Informationen und ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name).


**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.

### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


Legt den Dateinamen fest, der in der Kopfzeile angezeigt wird.


Standardmäßig zeigt GroupDocs.Viewer den Archivdateinamen in der Kopfzeile jeder Seite an. Um diesen Namen zu ändern oder zu verbergen, setzen Sie diese Eigenschaft.
Für weitere Informationen und ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileName | [FileName](../../com.groupdocs.viewer.options/filename) | Der anzuzeigende Dateiname. |
|

