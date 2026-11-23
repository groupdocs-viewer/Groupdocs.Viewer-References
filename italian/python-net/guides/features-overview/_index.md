---
title: "Panoramica delle funzionalità"
linkTitle: "Features overview"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Renderizza documenti in HTML, PDF, PNG o JPEG; estrai testo; elenca gli allegati; e applica rotazioni, riordini e filigrane con GroupDocs.Viewer per Python via .NET."
type: docs
url: /it/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Rendering Documents

Il termine *rendering* in GroupDocs.Viewer descrive il processo di conversione di un documento in un formato file che preserva i limiti di pagina. Ad esempio, quando un file DOCX a tre pagine viene renderizzato in HTML, il risultato sono tre file HTML — uno per pagina. Vedi la [Guida per sviluppatori]() per esempi eseguibili.

![Rendering diagram](https://docs.groupdocs.com/viewer/python-net/images/getting-started/features-overview/rendering.png)

### Rendering to HTML

Renderizzare in HTML è la scelta migliore quando devi:

- Build a web-based application and display document content inside a browser.
- Allow users to interact with the rendered text — select, copy, or search it.
- View document pages separately.
- Zoom in on a document without quality loss.
- Rotate, reorder, or watermark pages.

GroupDocs.Viewer per Python offre due modalità di gestione delle risorse HTML:

- **HTML with external resources** — stores page resources (CSS, fonts, images) next to the HTML file so common resources are reused across pages. Reduces overall page size and speeds up loading.
- **HTML with embedded resources** — inlines every resource into the HTML file so each page is self-contained. Larger individual files but easier to distribute.

### Rendering to PNG or JPEG

Renderizzare in PNG o JPEG è la scelta migliore quando devi:

- Support any type of application (desktop, web, mobile, CLI).
- Restrict interaction with rendered text — for example, to prevent copying. You can still extract a text layer separately if you want to overlay selectable text on the image.
- View document pages separately.
- Rotate, reorder, or watermark pages.

Un confronto rapido dei due formati immagine:

- **PNG** is a lossless raster format that supports full-colour images and transparency. PNG does not expose a quality setting. It is a good choice for line drawings, text, and iconic graphics at small file sizes.
- **JPEG** is a lossy compressed format whose quality can be tuned — lowering the quality removes detail and adds noise, but the file becomes smaller. JPEG is optimal for photographs and any image with a large colour range, and is a common web choice thanks to its compression ratio.

### Rendering to PDF

GroupDocs.Viewer renderizza un documento in un unico file PDF. Renderizzare in PDF è la scelta migliore quando devi:

- Print documents.
- Send documents via email.
- Distribute all pages as a single file rather than a collection of per-page files.

## Retrieving Document Information

GroupDocs.Viewer per Python espone informazioni di base su un documento sorgente — tipo di file, numero di pagine, testo con coordinate e altro — senza renderizzare. Vedi [Ottieni informazioni sul documento]().

Sono disponibili anche informazioni specifiche per formato:

- **Archive** — list of folders contained in the archive.
- **CAD** — list of layers and layouts in a CAD document.
- **Email** — list of folders contained in an Outlook data file.
- **PDF** — a flag that indicates whether document printing is allowed.
- **Project Management** — project start and end dates.

### Text extraction

Puoi scegliere di estrarre il testo del documento quando renderizzi in PNG o JPEG. Il testo viene restituito insieme alle coordinate per parola, il che è utile quando si sovrappone uno strato di testo selezionabile su un'immagine di pagina.

## Processing Attachments

In GroupDocs.Viewer, *attachments* comprende gli allegati email, i file incorporati nei PDF e gli elementi individuali all'interno di archivi compressi.

Con GroupDocs.Viewer puoi elencare e salvare:

- Email attachments.
- Files embedded in PDF documents.
- Email messages contained in Outlook and Lotus Notes data files.
- Individual files inside archive containers.

Vedi [Elaborazione degli allegati]() per un esempio eseguibile.

## Output Transformation

GroupDocs.Viewer per Python fornisce un insieme di opzioni per trasformare ogni pagina renderizzata:

- **Rotate pages** — change page orientation when rendering to HTML, JPG, PNG, or PDF.
- **Add a text watermark** — stamp a text watermark on every rendered page.
- **Reorder pages** — render pages in any order you prefer, including when rendering to PDF.

## Caching Results

GroupDocs.Viewer per Python supporta la cache per accelerare le renderizzazioni ripetute e ridurre il carico complessivo sull'applicazione.

Per impostazione predefinita, la cache è memorizzata sul disco locale. L'API del visualizzatore espone anche interfacce di cache che possono essere implementate per archiviazione di terze parti — FTP, Amazon S3, Dropbox, Google Drive, Microsoft Azure, Redis o qualsiasi altro backend.
