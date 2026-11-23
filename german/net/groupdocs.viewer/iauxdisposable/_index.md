---
title: "IAuxDisposable"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Erweitert das standardmäßige IDisposable-Interface und ermöglicht das Abrufen des aktuellen Zustands eines Objekts sowie das Abonnieren des Entsorgungsereignisses."
type: docs
weight: 20
url: /de/net/groupdocs.viewer/iauxdisposable/
---

## IAuxDisposable interface

Erweitert das standardmäßige IDisposable-Interface, ermöglicht das Abrufen des aktuellen Zustands eines Objekts und das Abonnieren des Entsorgungsereignisses

```csharp
public interface IAuxDisposable : IDisposable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [IsDisposed](../../groupdocs.viewer/iauxdisposable/isdisposed) { get; } | Gibt an, ob eine Ressource bereits entsorgt ist (`true`) oder nicht (`false`). |

## Ereignisse

| Name | Beschreibung |
| --- | --- |
| event [Disposed](../../groupdocs.viewer/iauxdisposable/disposed) | Tritt auf, wenn das Objekt entsorgt wird, unmittelbar nachdem das Entsorgen der Ressourcen erfolgreich abgeschlossen ist. |

### Siehe auch

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
