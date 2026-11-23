---
title: "CadViewInfo"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Initialisiert eine neue Instanz der Klasse CadViewInfogroupdocs.viewer.results/cadviewinfo."
type: docs
weight: 10
url: /de/net/groupdocs.viewer.results/cadviewinfo/cadviewinfo/
---

## CadViewInfo constructor

Initialisiert eine neue Instanz der Klasse [`CadViewInfo`](../../cadviewinfo).

```csharp
public CadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| fileType | FileType | Der Typ der Datei. |
| Seiten | List`1 | Die Liste der anzuzeigenden Seiten. |
| layers | List`1 | Die Liste der in der CAD-Zeichnung enthaltenen Ebenen. |
| layouts | List`1 | Die Liste der in der CAD-Zeichnung enthaltenen Ebenen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *fileType* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *pages* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *layers* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *layouts* null ist. |

### Siehe auch

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [Layer](../../layer)
* class [Layout](../../layout)
* class [CadViewInfo](../../cadviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
