---
title: "MboxViewInfo"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Initialisiert eine neue Instanz der Klasse MboxViewInfogroupdocs.viewer.results/mboxviewinfo."
type: docs
weight: 10
url: /de/net/groupdocs.viewer.results/mboxviewinfo/mboxviewinfo/
---

## MboxViewInfo() {#constructor}

Initialisiert eine neue Instanz der Klasse [`MboxViewInfo`](../../mboxviewinfo).

```csharp
public MboxViewInfo()
```

### Siehe auch

* class [MboxViewInfo](../../mboxviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## MboxViewInfo(FileType, List&lt;Page&gt;, int) {#constructor_1}

Initialisiert eine neue Instanz der Klasse [`MboxViewInfo`](../../mboxviewinfo).

```csharp
public MboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| fileType | FileType | Der Typ der Datei. |
| Seiten | List`1 | Die Liste der anzuzeigenden Seiten. |
| notesCount | Int32 | Die Notizanzahl, die in der Lotus-Datenbankdatei enthalten ist. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *fileType* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *pages* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *notesCount* null ist. |

### Siehe auch

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [MboxViewInfo](../../mboxviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
