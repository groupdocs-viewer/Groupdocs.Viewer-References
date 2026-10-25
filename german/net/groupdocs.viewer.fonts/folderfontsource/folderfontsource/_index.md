---
title: "FolderFontSource"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Initialisiert eine neue Instanz der Klasse FolderFontSourcegroupdocs.viewer.fonts/folderfontsource."
type: docs
weight: 10
url: /de/net/groupdocs.viewer.fonts/folderfontsource/folderfontsource/
---

## FolderFontSource constructor

Initialisiert eine neue Instanz der Klasse [`FolderFontSource`](../../folderfontsource).

```csharp
public FolderFontSource(string folderPath, SearchOption searchOption)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| folderPath | String | Pfad zu dem Ordner, der TrueType-Schriftarten enthält. |
| searchOption | SearchOption | Gibt an, ob das aktuelle Verzeichnis oder das aktuelle Verzeichnis und alle Unterverzeichnisse durchsucht werden sollen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *folderPath* null ist. |
| DirectoryNotFoundException | Wird ausgelöst, wenn der in *folderPath* angegebene Pfad nicht gefunden werden kann. |

### Siehe auch

* enum [SearchOption](../../searchoption)
* class [FolderFontSource](../../folderfontsource)
* namespace [GroupDocs.Viewer.Fonts](../../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
