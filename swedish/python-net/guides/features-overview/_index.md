---
title: "Översikt över funktioner"
linkTitle: "Features overview"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Rendera dokument till HTML, PDF, PNG eller JPEG; extrahera text; lista bilagor; och tillämpa rotationer, omordningar och vattenstämplar med GroupDocs.Viewer för Python via .NET."
type: docs
url: /sv/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Rendering Documents

Termen *rendering* i GroupDocs.Viewer beskriver processen att konvertera ett dokument till ett filformat som bevarar sidgränser. Till exempel, när en tre‑sidig DOCX‑fil renderas till HTML blir resultatet tre HTML‑filer — en per sida. Se [Developer Guide]() för körbara exempel.

![Rendering diagram](https://docs.groupdocs.com/viewer/python-net/images/getting-started/features-overview/rendering.png)

### Rendering to HTML

Rendering till HTML är det bästa valet när du behöver:

- Build a web-based application and display document content inside a browser.
- Allow users to interact with the rendered text — select, copy, or search it.
- View document pages separately.
- Zoom in on a document without quality loss.
- Rotate, reorder, or watermark pages.

GroupDocs.Viewer för Python erbjuder två HTML‑resurshanteringslägen:

- **HTML with external resources** — stores page resources (CSS, fonts, images) next to the HTML file so common resources are reused across pages. Reduces overall page size and speeds up loading.
- **HTML with embedded resources** — inlines every resource into the HTML file so each page is self-contained. Larger individual files but easier to distribute.

### Rendering to PNG or JPEG

Rendering till PNG eller JPEG är det bästa valet när du behöver:

- Support any type of application (desktop, web, mobile, CLI).
- Restrict interaction with rendered text — for example, to prevent copying. You can still extract a text layer separately if you want to overlay selectable text on the image.
- View document pages separately.
- Rotate, reorder, or watermark pages.

En snabb jämförelse av de två bildformaten:

- **PNG** is a lossless raster format that supports full-colour images and transparency. PNG does not expose a quality setting. It is a good choice for line drawings, text, and iconic graphics at small file sizes.
- **JPEG** is a lossy compressed format whose quality can be tuned — lowering the quality removes detail and adds noise, but the file becomes smaller. JPEG is optimal for photographs and any image with a large colour range, and is a common web choice thanks to its compression ratio.

### Rendering to PDF

GroupDocs.Viewer renderar ett dokument till en enda PDF‑fil. Rendering till PDF är det bästa valet när du behöver:

- Print documents.
- Send documents via email.
- Distribute all pages as a single file rather than a collection of per-page files.

## Retrieving Document Information

GroupDocs.Viewer for Python visar grundläggande information om ett källdokument — filtyp, sidantal, text med koordinater och mer — utan rendering. Se [Hämta dokumentinformation]().

Format‑specifik information är också tillgänglig:

- **Archive** — list of folders contained in the archive.
- **CAD** — list of layers and layouts in a CAD document.
- **Email** — list of folders contained in an Outlook data file.
- **PDF** — a flag that indicates whether document printing is allowed.
- **Project Management** — project start and end dates.

### Text extraction

Du kan välja att extrahera dokumenttext vid rendering till PNG eller JPEG. Texten returneras tillsammans med per‑ord‑koordinater, vilket är användbart när du lägger ett markerbart textlager över en sidbild.

## Processing Attachments

I GroupDocs.Viewer omfattar *attachments* e‑postbilagor, filer inbäddade i PDF‑filer och enskilda objekt i komprimerade arkiv.

Med GroupDocs.Viewer kan du lista och spara:

- Email attachments.
- Files embedded in PDF documents.
- Email messages contained in Outlook and Lotus Notes data files.
- Individual files inside archive containers.

Se [Bearbeta bilagor]() för ett körbart exempel.

## Output Transformation

GroupDocs.Viewer for Python levererar en uppsättning alternativ för att transformera varje renderad sida:

- **Rotate pages** — change page orientation when rendering to HTML, JPG, PNG, or PDF.
- **Add a text watermark** — stamp a text watermark on every rendered page.
- **Reorder pages** — render pages in any order you prefer, including when rendering to PDF.

## Caching Results

GroupDocs.Viewer for Python stödjer cachning för att påskynda återkommande renderingar och minska den totala belastningen på applikationen.

Som standard lagras cachen på den lokala disken. Viewer‑API:et exponerar också cache‑gränssnitt som kan implementeras för tredjepartslagring — FTP, Amazon S3, Dropbox, Google Drive, Microsoft Azure, Redis eller någon annan backend.
