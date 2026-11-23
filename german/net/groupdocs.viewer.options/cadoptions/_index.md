---
title: "CadOptions"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Enthält Optionen zum Rendern von CAD‑Zeichnungen. Weitere Informationen und Code‑Beispiele finden Sie unter Render CAD drawings and models as HTML PDF and image fileshttps//docs.groupdocs.com/viewer/net/rendercaddrawingsandmodels/ und Specify rendering options for CAD fileshttps//docs.groupdocs.com/viewer/net/specifycadrenderingoptions/."
type: docs
weight: 280
url: /de/net/groupdocs.viewer.options/cadoptions/
---

## CadOptions class

Enthält Optionen zum Rendern von CAD-Zeichnungen. Weitere Informationen und Code‑Beispiele finden Sie unter [Render CAD drawings and models as HTML, PDF, and image files](https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) und [Specify rendering options for CAD files](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/).

```csharp
public class CadOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BackgroundColor](../../groupdocs.viewer.options/cadoptions/backgroundcolor) { get; set; } | Bildhintergrundfarbe. |
| [EnablePerformanceConversionMode](../../groupdocs.viewer.options/cadoptions/enableperformanceconversionmode) { get; set; } | Das Setzen dieses Flags auf `true` aktiviert einen speziellen, leistungsorientierten Konvertierungsmodus für alle Formate der CAD‑Familie — in diesem Modus ist die Konvertierungsgeschwindigkeit deutlich höher, jedoch ist die Qualität der resultierenden Dokumente signifikant schlechter. Standardmäßig ist er deaktiviert (`false`) — die Qualität der resultierenden Dokumente ist dann bestmöglich, jedoch zulasten der Leistung. |
| [Height](../../groupdocs.viewer.options/cadoptions/height) { get; } | Die Höhe des Ausgabeergebnisses (in Pixeln). |
| [Layers](../../groupdocs.viewer.options/cadoptions/layers) { get; set; } | Die zu rendernden CAD‑Zeichnungsebenen. |
| [LayoutName](../../groupdocs.viewer.options/cadoptions/layoutname) { get; set; } | Der Name des zu rendernden Layouts. Der Layout‑Name ist groß-/kleinschreibungssensitiv. |
| [Pc3File](../../groupdocs.viewer.options/cadoptions/pc3file) { get; set; } | PC3 – Plotter‑Konfigurationsdatei |
| [RenderLayouts](../../groupdocs.viewer.options/cadoptions/renderlayouts) { get; set; } | Flag, ob Layouts aus dem CAD‑Dokument gerendert werden sollen. |
| [ScaleFactor](../../groupdocs.viewer.options/cadoptions/scalefactor) { get; } | Ein Wert größer als 1 vergrößert das Ausgabeergebnis; ein Wert zwischen 0 und 1 verkleinert das Ausgabeergebnis. |
| [Tiles](../../groupdocs.viewer.options/cadoptions/tiles) { get; set; } | Die zu rendernden Zeichenbereiche. |
| [Width](../../groupdocs.viewer.options/cadoptions/width) { get; } | Die Breite des Ausgabeergebnisses (in Pixeln). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [ForRenderingByHeight](../../groupdocs.viewer.options/cadoptions/forrenderingbyheight)(int) | Initialisiert eine Instanz der [`CadOptions`](../cadoptions)-Klasse zum Rendern nach Höhe. |
| static [ForRenderingByScaleFactor](../../groupdocs.viewer.options/cadoptions/forrenderingbyscalefactor)(float) | Initialisiert eine Instanz der [`CadOptions`](../cadoptions)-Klasse zum Rendern nach Skalierungsfaktor. |
| static [ForRenderingByWidth](../../groupdocs.viewer.options/cadoptions/forrenderingbywidth)(int) | Initialisiert eine Instanz der [`CadOptions`](../cadoptions)-Klasse zum Rendern nach Breite. |
| static [ForRenderingByWidthAndHeight](../../groupdocs.viewer.options/cadoptions/forrenderingbywidthandheight)(int, int) | Initialisiert eine Instanz der [`CadOptions`](../cadoptions)-Klasse für die Darstellung nach Breite und Höhe. |

### Siehe auch

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
