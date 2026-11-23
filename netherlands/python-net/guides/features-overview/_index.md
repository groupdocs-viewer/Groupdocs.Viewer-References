---
title: "Overzicht van functies"
linkTitle: "Features overview"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Render documenten naar HTML, PDF, PNG of JPEG; extraheer tekst; lijst bijlagen op; en pas rotaties, hersorteringen en watermerken toe met GroupDocs.Viewer voor Python via .NET."
type: docs
url: /nl/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Rendering Documents

De term *rendering* in GroupDocs.Viewer beschrijft het proces van het converteren van een document naar een bestandsformaat dat paginagrenzen behoudt. Bijvoorbeeld, wanneer een drie‑pagina’s DOCX‑bestand wordt gerenderd naar HTML, is het resultaat drie HTML‑bestanden — één per pagina. Zie de [Developer Guide]() voor uitvoerbare voorbeelden.

![Rendering diagram](https://docs.groupdocs.com/viewer/python-net/images/getting-started/features-overview/rendering.png)

### Rendering to HTML

Renderen naar HTML is de beste keuze wanneer u moet:

- Build a web-based application and display document content inside a browser.
- Allow users to interact with the rendered text — select, copy, or search it.
- View document pages separately.
- Zoom in on a document without quality loss.
- Rotate, reorder, or watermark pages.

GroupDocs.Viewer voor Python biedt twee HTML‑resource‑beheermodi:

- **HTML with external resources** — stores page resources (CSS, fonts, images) next to the HTML file so common resources are reused across pages. Reduces overall page size and speeds up loading.
- **HTML with embedded resources** — inlines every resource into the HTML file so each page is self-contained. Larger individual files but easier to distribute.

### Rendering to PNG or JPEG

Renderen naar PNG of JPEG is de beste keuze wanneer u moet:

- Support any type of application (desktop, web, mobile, CLI).
- Restrict interaction with rendered text — for example, to prevent copying. You can still extract a text layer separately if you want to overlay selectable text on the image.
- View document pages separately.
- Rotate, reorder, or watermark pages.

Een snelle vergelijking van de twee afbeeldingsformaten:

- **PNG** is a lossless raster format that supports full-colour images and transparency. PNG does not expose a quality setting. It is a good choice for line drawings, text, and iconic graphics at small file sizes.
- **JPEG** is a lossy compressed format whose quality can be tuned — lowering the quality removes detail and adds noise, but the file becomes smaller. JPEG is optimal for photographs and any image with a large colour range, and is a common web choice thanks to its compression ratio.

### Rendering to PDF

GroupDocs.Viewer rendert een document naar één enkel PDF‑bestand. Renderen naar PDF is de beste keuze wanneer u moet:

- Print documents.
- Send documents via email.
- Distribute all pages as a single file rather than a collection of per-page files.

## Retrieving Document Information

GroupDocs.Viewer voor Python geeft basisinformatie over een brondocument weer — bestandstype, paginatelling, tekst met coördinaten en meer — zonder te renderen. Zie [Get Document Info]().

Formaat‑specifieke informatie is ook beschikbaar:

- **Archive** — list of folders contained in the archive.
- **CAD** — list of layers and layouts in a CAD document.
- **Email** — list of folders contained in an Outlook data file.
- **PDF** — a flag that indicates whether document printing is allowed.
- **Project Management** — project start and end dates.

### Text extraction

U kunt ervoor kiezen om documenttekst te extraheren bij het renderen naar PNG of JPEG. De tekst wordt teruggegeven samen met woord‑per‑woord coördinaten, wat handig is bij het overleggen van een selecteerbare tekstlaag op een pagina‑afbeelding.

## Processing Attachments

In GroupDocs.Viewer omvat *attachments* e‑mailbijlagen, bestanden ingebed in PDF’s en individuele items in gecomprimeerde archieven.

Met GroupDocs.Viewer kunt u het volgende opsommen en opslaan:

- Email attachments.
- Files embedded in PDF documents.
- Email messages contained in Outlook and Lotus Notes data files.
- Individual files inside archive containers.

Zie [Processing Attachments]() voor een uitvoerbaar voorbeeld.

## Output Transformation

GroupDocs.Viewer voor Python levert een reeks opties om elke gerenderde pagina te transformeren:

- **Rotate pages** — change page orientation when rendering to HTML, JPG, PNG, or PDF.
- **Add a text watermark** — stamp a text watermark on every rendered page.
- **Reorder pages** — render pages in any order you prefer, including when rendering to PDF.

## Caching Results

GroupDocs.Viewer voor Python ondersteunt caching om herhaalde renderingen te versnellen en de algehele belasting van de applicatie te verminderen.

Standaard wordt de cache opgeslagen op de lokale schijf. De viewer‑API biedt ook cache‑interfaces die geïmplementeerd kunnen worden voor opslag van derden — FTP, Amazon S3, Dropbox, Google Drive, Microsoft Azure, Redis, of een andere backend.
