---
title: "com.groupdocs.viewer.fonts"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Das Paket stellt Klassen und Aufzählungen bereit, um während des Rendering‑Vorgangs verwendete Schriftarten zu verwalten."
type: docs
weight: 16
url: /de/java/com.groupdocs.viewer.fonts/
---

Das Paket stellt Klassen und Aufzählungen bereit, um während des Rendering‑Vorgangs verwendete Schriftarten zu verwalten.

Die wichtigsten Klassen und Schnittstellen in diesem Paket sind:

* [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) - Represents a folder that contains TrueType fonts.
* [FontSettings](../../com.groupdocs.viewer.fonts/fontsettings) - Provides methods for working with sources to look for TrueType fonts.
* [FontSource](../../com.groupdocs.viewer.fonts/fontsource) - Marker interface for the font sources.


Weitere Details zur Arbeit mit Schriftarten in GroupDocs.Viewer finden Sie unter
[GroupDocs.Viewer Documentation](../https://docs.groupdocs.com/viewer/java/).



## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [FolderFontSource](../com.groupdocs.viewer.fonts/folderfontsource) | Stellt einen Ordner dar, der TrueType-Schriftarten enthält. |
| [FontFormat](../com.groupdocs.viewer.fonts/fontformat) | Stellt alle Schriftformaten dar, die in der Klasse UsedFontInfo vorhanden sein können. |
| [FontSettings](../com.groupdocs.viewer.fonts/fontsettings) | Stellt Methoden zur Arbeit mit Quellen bereit, um nach TrueType-Schriftarten zu suchen. |
| [FontStyles](../com.groupdocs.viewer.fonts/fontstyles) | Stellt 4 mögliche Schriftstile dar, die im Dokument verwendet werden: Normal, Fett, Kursiv oder Fett Kursiv. |
| [PdfFontInfo](../com.groupdocs.viewer.fonts/pdffontinfo) | Kapselt Metainformationen und Binärdaten einer Schriftart aus einem PDF-Dokument, das in die Viewer-Instanz geladen wurde. |
| [PresentationFontInfo](../com.groupdocs.viewer.fonts/presentationfontinfo) | Kapselt Metadaten und Binärdaten einer in einem Präsentationsdokument verwendeten Schriftart, das in die Viewer-Instanz geladen wurde. |
| [SpreadsheetFontInfo](../com.groupdocs.viewer.fonts/spreadsheetfontinfo) | Kapselt Metainformationen und Binärdaten einer Schriftart aus dem Tabellenkalkulationsdokument, das in die Viewer-Instanz geladen wurde. |
| [WordProcessingFontInfo](../com.groupdocs.viewer.fonts/wordprocessingfontinfo) | Kapselt Metainformationen und Binärdaten einer Schriftart aus dem Textverarbeitungsdokument, das in die Viewer-Instanz geladen wurde. |
| [WordProcessingSubstitutedFontInfo](../com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo) | Kapselt Metadaten und Binärdaten einer ersetzten Schriftart, die in einem Textverarbeitungsdokument über GroupDocs.Viewer verwendet wird. |

## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [FontSource](../com.groupdocs.viewer.fonts/fontsource) | Marker-Schnittstelle für die Schriftquellen. |
| [IFontInfo](../com.groupdocs.viewer.fonts/ifontinfo) | Gemeinsame Schnittstelle für alle Schriftarten, die aus Dokumentformaten extrahiert werden können: PDF, WordProcessing, Spreadsheet und Presentation. |

## Aufzählungen

| Enum | Beschreibung |
| --- | --- |
| [SearchOption](../com.groupdocs.viewer.fonts/searchoption) | Gibt an, ob nur im aktuellen Ordner oder im aktuellen Ordner und allen Unterordnern gesucht werden soll. |
