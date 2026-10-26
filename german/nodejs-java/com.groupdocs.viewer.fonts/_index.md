---
title: "com.groupdocs.viewer.fonts"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Das Paket stellt Klassen und Aufzählungen bereit, um während des Renderings verwendete Schriftarten zu verwalten."
type: docs
weight: 14
url: /de/nodejs-java/com.groupdocs.viewer.fonts/
---

Das Paket stellt Klassen und Aufzählungen bereit, um während des Renderings verwendete Schriftarten zu verwalten.

Die Hauptklassen und -schnittstellen in diesem Paket sind:

 *  [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) - Represents a folder that contains TrueType fonts.
 *  [FontSettings](../../com.groupdocs.viewer.fonts/fontsettings) - Provides methods for working with sources to look for TrueType fonts.
 *  [FontSource](../../com.groupdocs.viewer.fonts/fontsource) - Marker interface for the font sources.

Weitere Details zur Arbeit mit Schriften in GroupDocs.Viewer finden Sie in der [GroupDocs.Viewer Documentation][].


[GroupDocs.Viewer Documentation]: https://docs.groupdocs.com/viewer/java/


## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [FolderFontSource](../com.groupdocs.viewer.fonts/folderfontsource) | Stellt einen Ordner dar, der TrueType-Schriften enthält. |
| [FontFormat](../com.groupdocs.viewer.fonts/fontformat) | Stellt alle Schriftformate dar, die in der Klasse UsedFontInfo vorhanden sein können. |
| [FontSettings](../com.groupdocs.viewer.fonts/fontsettings) | Stellt Methoden zur Arbeit mit Quellen bereit, um nach TrueType-Schriften zu suchen. |
| [FontStyles](../com.groupdocs.viewer.fonts/fontstyles) | Stellt 4 mögliche Schriftstile dar, die im Dokument verwendet werden: Regular, Bold, Italic oder Bold Italic. |
| [PdfFontInfo](../com.groupdocs.viewer.fonts/pdffontinfo) | Kapselt Metainformationen und Binärdaten einer Schrift aus einem PDF-Dokument, die in die Viewer-Instanz geladen wurden. |
| [PresentationFontInfo](../com.groupdocs.viewer.fonts/presentationfontinfo) | Kapselt Metadaten und Binärdaten einer Schrift, die in einem Präsentations-Dokument verwendet wird und in die Viewer-Instanz geladen wurde. |
| [SpreadsheetFontInfo](../com.groupdocs.viewer.fonts/spreadsheetfontinfo) | Kapselt Metainformationen und Binärdaten einer Schrift aus dem Spreadsheet-Dokument, die in die Viewer-Instanz geladen wurde. |
| [WordProcessingFontInfo](../com.groupdocs.viewer.fonts/wordprocessingfontinfo) | Kapselt Metainformationen und Binärdaten einer Schrift aus dem WordProcessing-Dokument, die in die Viewer-Instanz geladen wurde. |
| [WordProcessingSubstitutedFontInfo](../com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo) | Kapselt Metadaten und Binärdaten einer ersetzten Schrift, die in einem WordProcessing-Dokument über GroupDocs.Viewer verwendet wird. |

## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [FontSource](../com.groupdocs.viewer.fonts/fontsource) | Marker-Schnittstelle für die Schriftquellen. |
| [IFontInfo](../com.groupdocs.viewer.fonts/ifontinfo) | Gemeinsame Schnittstelle für alle Schriften, die aus Dokumentformaten extrahiert werden können: PDF, WordProcessing, Spreadsheet und Presentation. |

## Aufzählungen

| Enum | Beschreibung |
| --- | --- |
| [SearchOption](../com.groupdocs.viewer.fonts/searchoption) | Gibt an, ob im aktuellen Ordner oder im aktuellen Ordner und allen Unterordnern gesucht werden soll. |
