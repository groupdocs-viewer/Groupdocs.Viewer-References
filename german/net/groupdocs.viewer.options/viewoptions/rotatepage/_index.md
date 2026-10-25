---
title: "RotatePage"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Wendet die Drehung im Uhrzeigersinn auf eine Seite an."
type: docs
weight: 30
url: /de/net/groupdocs.viewer.options/viewoptions/rotatepage/
---

## ViewOptions.RotatePage method

Wendet die Drehung im Uhrzeigersinn auf eine Seite an.

```csharp
public void RotatePage(int pageNumber, Rotation rotation)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| pageNumber | Int32 | Die Seitennummer muss strikt größer als 0 sein. |
| rotation | Rotation | Der Rotationswert. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | Wird ausgelöst, wenn *pageNumber* kleiner oder gleich null ist. |
| ArgumentException | Wird ausgelöst, wenn die Rotation für die Seite mit der Nummer *pageNumber* bereits hinzugefügt wurde. |

### Bemerkungen

Weitere Details finden Sie in der [Dokumentation](https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/).

### Siehe auch

* enum [Rotation](../../rotation)
* class [ViewOptions](../../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
