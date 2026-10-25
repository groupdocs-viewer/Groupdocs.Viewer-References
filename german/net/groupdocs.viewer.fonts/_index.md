---
title: "GroupDocs.Viewer.Fonts"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Der Namespace stellt Klassen und Aufzählungen bereit, um Schriftarten zu verwalten, die während des Rendering-Prozesses verwendet werden."
type: docs
weight: 50
url: /de/net/groupdocs.viewer.fonts/
---

Der Namespace stellt Klassen und Aufzählungen bereit, um Schriftarten zu verwalten, die während des Rendering-Prozesses verwendet werden.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [FolderFontSource](./folderfontsource) | Stellt den Ordner dar, der TrueType-Schriften enthält. |
| [FontSettings](./fontsettings) | Stellt Methoden zum Arbeiten mit Quellen bereit, um nach TrueType-Schriften zu suchen. |
## Structures

| Struktur | Beschreibung |
| --- | --- |
| [FontStyles](./fontstyles) | Stellt 4 mögliche Schriftstile dar, die im Dokument verwendet werden: Regular, Bold, Italic oder Bold Italic |
| [PdfFontInfo](./pdffontinfo) | Kapselt Metainformationen und Binärdaten einer Schrift aus dem PDF-Dokument, die in die [`Viewer`](../groupdocs.viewer/viewer)-Instanz geladen wurde. Diese Schrift wird im Dokumentinhalt verwendet und ist entweder im Dokument selbst eingebettet oder im Betriebssystem installiert, in dem GroupDocs.Viewer ausgeführt wird. |
| [PresentationFontInfo](./presentationfontinfo) | Kapselt Metainformationen und Binärdaten einer Schrift aus dem Präsentationsdokument, die in die [`Viewer`](../groupdocs.viewer/viewer)-Instanz geladen wurde. Diese Schrift wird im Dokumentinhalt verwendet und ist entweder im Dokument selbst eingebettet oder im Betriebssystem installiert, in dem GroupDocs.Viewer ausgeführt wird. |
| [SpreadsheetFontInfo](./spreadsheetfontinfo) | Kapselt Metainformationen und Binärdaten einer Schrift aus dem Tabellenkalkulationsdokument, die in die [`Viewer`](../groupdocs.viewer/viewer)-Instanz geladen wurde. Tabellenkalkulationsdokumente können keine eingebetteten Schriften enthalten, daher wird diese spezielle Schrift, falls sie von der [`GetAllFonts`](../groupdocs.viewer/viewer/getallfonts)-Methode zurückgegeben wurde, im Betriebssystem installiert, in dem GroupDocs.Viewer ausgeführt wird. |
| [WordProcessingFontInfo](./wordprocessingfontinfo) | Kapselt Metainformationen und Binärdaten einer Schrift aus dem WordProcessing-Dokument, die in die [`Viewer`](../groupdocs.viewer/viewer)-Instanz geladen wurde. Diese Schrift wird im Dokumentinhalt verwendet und ist entweder im Dokument selbst eingebettet oder im Betriebssystem installiert, in dem GroupDocs.Viewer ausgeführt wird. |
| [WordProcessingSubstitutedFontInfo](./wordprocessingsubstitutedfontinfo) | Kapselt Metainformationen und Binärdaten einer Schrift aus einem WordProcessing-Dokument, die ursprünglich nicht im in die [`Viewer`](../groupdocs.viewer/viewer)-Instanz geladenen Dokument verwendet wird, sondern als Ersatzschrift für solche dient, die auf dem Zielrechner nicht gefunden werden können. Ersetzte Schriften existieren nur für die WordProcessing-Formatfamilie. |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IFontInfo](./ifontinfo) | Gemeinsame Schnittstelle für alle Schriften, die aus allen unterstützten Familien von Dokumentformaten extrahiert werden können: PDF, WordProcessing, Spreadsheet und Presentation. |
| [IFontSource](./ifontsource) | Marker-Schnittstelle für die Schriftquellen. |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [FontFormat](./fontformat) | Stellt alle Schriftformate dar, die in den Erben von [`IFontInfo`](../groupdocs.viewer.fonts/ifontinfo) vorhanden sein können. |
| [SearchOption](./searchoption) | Gibt an, ob im aktuellen Ordner oder im aktuellen Ordner und allen Unterordnern gesucht werden soll. |

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
