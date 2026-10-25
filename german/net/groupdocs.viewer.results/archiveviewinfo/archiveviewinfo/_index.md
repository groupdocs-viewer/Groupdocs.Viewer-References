---
title: "ArchiveViewInfo"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Initialisiert eine neue Instanz der Klasse ArchiveViewInfogroupdocs.viewer.results/archiveviewinfo."
type: docs
weight: 10
url: /de/net/groupdocs.viewer.results/archiveviewinfo/archiveviewinfo/
---

## ArchiveViewInfo() {#constructor}

Initialisiert eine neue Instanz der Klasse [`ArchiveViewInfo`](../../archiveviewinfo).

```csharp
public ArchiveViewInfo()
```

### Siehe auch

* class [ArchiveViewInfo](../../archiveviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## ArchiveViewInfo(FileType, List&lt;Page&gt;, List&lt;string&gt;) {#constructor_1}

Initialisiert eine neue Instanz der Klasse [`ArchiveViewInfo`](../../archiveviewinfo).

```csharp
public ArchiveViewInfo(FileType fileType, List<Page> pages, List<string> folders)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| fileType | FileType | Der Typ der Datei. |
| Seiten | List`1 | Die Liste der anzuzeigenden Seiten. |
| Ordner | List`1 | Die Liste der im Archiv enthaltenen Ordner. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *fileType* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *pages* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *folders* null ist. |

### Siehe auch

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [ArchiveViewInfo](../../archiveviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
