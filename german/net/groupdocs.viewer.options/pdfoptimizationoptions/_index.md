---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Enthält die PDF-Optimierungsoptionen, die auf die Ausgabedatei angewendet werden. Weitere Details und Codebeispiele finden Sie auf dieser Seite https//docs.groupdocs.com/viewer/net/optimizationpdfoptions/ und deren Unterseiten."
type: docs
weight: 400
url: /de/net/groupdocs.viewer.options/pdfoptimizationoptions/
---

## PdfOptimizationOptions class

Enthält die PDF‑Optimierungsoptionen, die auf die ausgegebene PDF‑Datei angewendet werden. Weitere Details und Code‑Beispiele finden Sie auf dieser [Seite](https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) und deren Unterseiten.

```csharp
public class PdfOptimizationOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | Legt die Standardwerte der Option MaxResolution auf 300 und der Option ImageQuality auf 100 fest. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CompressImages](../../groupdocs.viewer.options/pdfoptimizationoptions/compressimages) { get; set; } | Ermöglicht das Komprimieren von Bildern in der Ausgabedatei im PDF-Format. |
| [ConvertToGrayScale](../../groupdocs.viewer.options/pdfoptimizationoptions/converttograyscale) { get; set; } | Ermöglicht die Umwandlung der Ausgabedatei in ein Graustufen-PDF. |
| [ImageQuality](../../groupdocs.viewer.options/pdfoptimizationoptions/imagequality) { get; set; } | Legt die Bildqualität in der Ausgabedatei (in Prozent) fest. |
| [Lineriaze](../../groupdocs.viewer.options/pdfoptimizationoptions/lineriaze) { get; set; } | Ermöglicht die Optimierung der Ausgabedatei für die Online‑Ansicht in einem Webbrowser. |
| [MaxResolution](../../groupdocs.viewer.options/pdfoptimizationoptions/maxresolution) { get; set; } | Legt die maximale Auflösung in der Ausgabedatei fest. |
| [OptimizeSpreadsheets](../../groupdocs.viewer.options/pdfoptimizationoptions/optimizespreadsheets) { get; set; } | Ermöglicht die Optimierung von Tabellenkalkulationen in PDF-Dateien. |
| [RemoveAnnotations](../../groupdocs.viewer.options/pdfoptimizationoptions/removeannotations) { get; set; } | Ermöglicht das Entfernen von Anmerkungen aus der Ausgabedatei. |
| [RemoveFormFields](../../groupdocs.viewer.options/pdfoptimizationoptions/removeformfields) { get; set; } | Ermöglicht das Entfernen von Formularfeldern aus einer PDF-Datei. |
| [RemoveUnusedObjects](../../groupdocs.viewer.options/pdfoptimizationoptions/removeunusedobjects) { get; set; } | Entfernt ungenutzte (verwaiste) Objekte aus einer PDF-Datei, die im PDF‑Dokument platziert, aber von keinen Ressourcen‑Dictionaries einer Seite referenziert werden und daher überhaupt nicht verwendet werden. Das Aktivieren dieser Eigenschaft (`true`) verringert die Größe des Ausgabedokuments. Standardmäßig ist sie deaktiviert (`false`). |
| [RemoveUnusedStreams](../../groupdocs.viewer.options/pdfoptimizationoptions/removeunusedstreams) { get; set; } | Entfernt ungenutzte (verwaiste) Streams aus einer PDF-Datei, die noch von den Ressourcen‑Dictionaries der Seite referenziert werden, aber tatsächlich nie im Seiteninhalt verwendet werden. Standardmäßig ist dies deaktiviert (`false`), das Aktivieren (`true`) verringert die Größe des Ausgabedokuments. |
| [ResizeImages](../../groupdocs.viewer.options/pdfoptimizationoptions/resizeimages) { get; set; } | Ermöglicht das Festlegen der maximalen Auflösung in der Ausgabedatei. |
| [SubsetFonts](../../groupdocs.viewer.options/pdfoptimizationoptions/subsetfonts) { get; set; } | Erstellt Teilmengen von Schriftarten in der Ausgabedatei. |

### Siehe auch

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
