---
title: "Übersicht der Funktionen"
linkTitle: "Features overview"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Rendern Sie Dokumente zu HTML, PDF, PNG oder JPEG; extrahieren Sie Text; listen Sie Anhänge auf; und wenden Sie Drehungen, Neuordnungen und Wasserzeichen mit GroupDocs.Viewer für Python via .NET an."
type: docs
url: /de/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Rendering Documents

Der Begriff *rendering* in GroupDocs.Viewer beschreibt den Vorgang, ein Dokument in ein Dateiformat zu konvertieren, das Seitenbegrenzungen beibehält. Zum Beispiel, wenn eine dreiseitige DOCX‑Datei zu HTML gerendert wird, entsteht das Ergebnis aus drei HTML‑Dateien – eine pro Seite. Siehe den [Developer Guide](), für ausführbare Beispiele.

![Rendering diagram](https://docs.groupdocs.com/viewer/python-net/images/getting-started/features-overview/rendering.png)

### Rendering to HTML

Das Rendern zu HTML ist die beste Wahl, wenn Sie folgendes benötigen:

- Build a web-based application and display document content inside a browser.
- Allow users to interact with the rendered text — select, copy, or search it.
- View document pages separately.
- Zoom in on a document without quality loss.
- Rotate, reorder, or watermark pages.

GroupDocs.Viewer für Python bietet zwei HTML‑Ressourcen‑Verwaltungsmodi:

- **HTML with external resources** — stores page resources (CSS, fonts, images) next to the HTML file so common resources are reused across pages. Reduces overall page size and speeds up loading.
- **HTML with embedded resources** — inlines every resource into the HTML file so each page is self-contained. Larger individual files but easier to distribute.

### Rendering to PNG or JPEG

Das Rendern zu PNG oder JPEG ist die beste Wahl, wenn Sie folgendes benötigen:

- Support any type of application (desktop, web, mobile, CLI).
- Restrict interaction with rendered text — for example, to prevent copying. You can still extract a text layer separately if you want to overlay selectable text on the image.
- View document pages separately.
- Rotate, reorder, or watermark pages.

Ein kurzer Vergleich der beiden Bildformate:

- **PNG** is a lossless raster format that supports full-colour images and transparency. PNG does not expose a quality setting. It is a good choice for line drawings, text, and iconic graphics at small file sizes.
- **JPEG** is a lossy compressed format whose quality can be tuned — lowering the quality removes detail and adds noise, but the file becomes smaller. JPEG is optimal for photographs and any image with a large colour range, and is a common web choice thanks to its compression ratio.

### Rendering to PDF

GroupDocs.Viewer rendert ein Dokument in eine einzelne PDF‑Datei. Das Rendern zu PDF ist die beste Wahl, wenn Sie folgendes benötigen:

- Print documents.
- Send documents via email.
- Distribute all pages as a single file rather than a collection of per-page files.

## Retrieving Document Information

GroupDocs.Viewer für Python stellt grundlegende Informationen über ein Quelldokument bereit – Dateityp, Seitenzahl, Text mit Koordinaten und mehr – ohne zu rendern. Siehe [Get Document Info]().

Formatspezifische Informationen sind ebenfalls verfügbar:

- **Archive** — list of folders contained in the archive.
- **CAD** — list of layers and layouts in a CAD document.
- **Email** — list of folders contained in an Outlook data file.
- **PDF** — a flag that indicates whether document printing is allowed.
- **Project Management** — project start and end dates.

### Text extraction

Sie können wählen, Dokumenttext beim Rendern zu PNG oder JPEG zu extrahieren. Der Text wird zusammen mit Wort‑Koordinaten zurückgegeben, was hilfreich ist, wenn man eine auswählbare Textebene über ein Seitenbild legt.

## Processing Attachments

In GroupDocs.Viewer umfasst *attachments* E‑Mail‑Anhänge, in PDFs eingebettete Dateien und einzelne Elemente in komprimierten Archiven.

Mit GroupDocs.Viewer können Sie auflisten und speichern:

- Email attachments.
- Files embedded in PDF documents.
- Email messages contained in Outlook and Lotus Notes data files.
- Individual files inside archive containers.

Siehe [Processing Attachments]() für ein ausführbares Beispiel.

## Output Transformation

GroupDocs.Viewer for Python liefert ein Set von Optionen, um jede gerenderte Seite zu transformieren:

- **Rotate pages** — change page orientation when rendering to HTML, JPG, PNG, or PDF.
- **Add a text watermark** — stamp a text watermark on every rendered page.
- **Reorder pages** — render pages in any order you prefer, including when rendering to PDF.

## Caching Results

GroupDocs.Viewer for Python unterstützt Caching, um wiederholte Renderings zu beschleunigen und die Gesamtauslastung der Anwendung zu reduzieren.

Standardmäßig wird der Cache auf der lokalen Festplatte gespeichert. Die Viewer-API stellt außerdem Cache-Schnittstellen bereit, die für Drittanbieterspeicher implementiert werden können — FTP, Amazon S3, Dropbox, Google Drive, Microsoft Azure, Redis oder jedes andere Backend.
