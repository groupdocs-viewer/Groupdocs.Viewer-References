---
title: "ArchiveOptions"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Bietet Optionen zum Rendern von Archivdateien."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

Bietet Optionen zum Rendern von Archivdateien.

Die ArchiveOptions-Klasse stellt eine Menge von Optionen dar, die verwendet werden können, um das Rendern von Archivdateien im Viewer-Modul zu konfigurieren. Sie ermöglicht die Anpassung verschiedener Aspekte des Rendering-Prozesses, wie z. B. die Anzahl der Elemente pro Seite und ähnliches.

Beispielhafte Verwendung:

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
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ArchiveOptions()](#ArchiveOptions--) | Erstellt eine neue Instanz der ArchiveOptions-Klasse mit den Standardeinstellungen. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFolder()](#getFolder--) | Gibt den Ordner im Archiv zurück, der für das Rendering verwendet wird. |
| [setFolder(String value)](#setFolder-java.lang.String-) | Legt den Ordner im Archiv fest, der für die Darstellung verwendet wird. |
| [getFileName()](#getFileName--) | Ermittelt den Dateinamen, der in der Kopfzeile angezeigt wird. |
| [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | Legt den Dateinamen fest, der in der Kopfzeile angezeigt wird. |
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


Erstellt eine neue Instanz der ArchiveOptions-Klasse mit den Standardeinstellungen.

### getFolder() {#getFolder--}
```
public final String getFolder()
```


Gibt den Ordner im Archiv zurück, der für das Rendering verwendet wird.

Standardmäßig rendert GroupDocs.Viewer Elemente aus allen im Archiv enthaltenen Ordnern. Um Elemente aus einem bestimmten Ordner zu rendern, setzen Sie diese Eigenschaft. Für ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder

**Returns:**
java.lang.String – der zu rendernde Ordner.
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Legt den Ordner im Archiv fest, der für die Darstellung verwendet wird.

Standardmäßig rendert GroupDocs.Viewer Elemente aus allen im Archiv enthaltenen Ordnern. Um Elemente aus einem bestimmten Ordner zu rendern, setzen Sie diese Eigenschaft. Für ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String | Der zu rendernde Ordner. |

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


Ermittelt den Dateinamen, der in der Kopfzeile angezeigt wird.

Standardmäßig zeigt GroupDocs.Viewer den Archivdateinamen in der Kopfzeile jeder Seite an. Um diesen Namen zu ändern oder zu verbergen, setzen Sie diese Eigenschaft. Für weitere Informationen und ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.
### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


Legt den Dateinamen fest, der in der Kopfzeile angezeigt wird.

Standardmäßig zeigt GroupDocs.Viewer den Archivdateinamen in der Kopfzeile jeder Seite an. Um diesen Namen zu ändern oder zu verbergen, setzen Sie diese Eigenschaft. Für weitere Informationen und ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | [FileName](../../com.groupdocs.viewer.options/filename) | Der anzuzeigende Dateiname. |

