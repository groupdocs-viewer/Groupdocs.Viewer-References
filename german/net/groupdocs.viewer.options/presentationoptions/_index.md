---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Enthält Optionen zum Rendern von Präsentationen. Weitere Details siehe die Dokumentation https://docs.groupdocs.com/viewer/net/renderpresentations/."
type: docs
weight: 460
url: /de/net/groupdocs.viewer.options/presentationoptions/
---

## PresentationOptions class

Enthält Optionen zum Rendern von Präsentationen. Weitere Details finden Sie in der [Dokumentation](https://docs.groupdocs.com/viewer/net/render-presentations/).

```csharp
public class PresentationOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PresentationOptions](presentationoptions)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [RenderHeaderFooterPlaceholders](../../groupdocs.viewer.options/presentationoptions/renderheaderfooterplaceholders) { get; set; } | Aktiviert das Rendern von Platzhaltern in Kopf- und Fußzeile einer Folie. Standardmäßig deaktiviert (`false`). Diese Option gilt für alle 4 Rendermodi von Präsentationen: HTML, PDF, PNG und JPEG. Sie ist nicht anwendbar, wenn die Präsentation in reines HTML/CSS-Markup mit [`RenderToPureHtml`](./rendertopurehtml) gerendert wird. |
| [RenderToPureHtml](../../groupdocs.viewer.options/presentationoptions/rendertopurehtml) { get; set; } | Aktiviert einen neuen HTML-Rendermodus für die Präsentationsdokumente — in diesem Modus werden die Präsentationsdateien zu **pure HTML/CSS markup** gerendert, ohne SVG‑Bilder. Standardmäßig ist er deaktiviert (`false`) — der vorhandene SVG‑basierte HTML‑Renderer wird verwendet. |
| [Resolution](../../groupdocs.viewer.options/presentationoptions/resolution) { get; set; } | Auflösung der Präsentationsbilder (nur für das Rendern zu HTML/PDF). |

### Siehe auch

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
