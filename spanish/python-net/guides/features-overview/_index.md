---
title: "Resumen de características"
linkTitle: "Features overview"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Renderice documentos a HTML, PDF, PNG o JPEG; extraiga texto; enumere adjuntos; y aplique rotaciones, reordenamientos y marcas de agua con GroupDocs.Viewer para Python a través de .NET."
type: docs
url: /es/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Rendering Documents

El término *rendering* en GroupDocs.Viewer describe el proceso de convertir un documento a un formato de archivo que preserva los límites de página. Por ejemplo, cuando un archivo DOCX de tres páginas se renderiza a HTML, el resultado son tres archivos HTML — uno por página. Consulte la [Developer Guide]() para ejemplos ejecutables.

![Rendering diagram](https://docs.groupdocs.com/viewer/python-net/images/getting-started/features-overview/rendering.png)

### Rendering to HTML

Renderizar a HTML es la mejor opción cuando necesita:

- Build a web-based application and display document content inside a browser.
- Allow users to interact with the rendered text — select, copy, or search it.
- View document pages separately.
- Zoom in on a document without quality loss.
- Rotate, reorder, or watermark pages.

GroupDocs.Viewer para Python ofrece dos modos de gestión de recursos HTML:

- **HTML with external resources** — stores page resources (CSS, fonts, images) next to the HTML file so common resources are reused across pages. Reduces overall page size and speeds up loading.
- **HTML with embedded resources** — inlines every resource into the HTML file so each page is self-contained. Larger individual files but easier to distribute.

### Rendering to PNG or JPEG

Renderizar a PNG o JPEG es la mejor opción cuando necesita:

- Support any type of application (desktop, web, mobile, CLI).
- Restrict interaction with rendered text — for example, to prevent copying. You can still extract a text layer separately if you want to overlay selectable text on the image.
- View document pages separately.
- Rotate, reorder, or watermark pages.

Una comparación rápida de los dos formatos de imagen:

- **PNG** is a lossless raster format that supports full-colour images and transparency. PNG does not expose a quality setting. It is a good choice for line drawings, text, and iconic graphics at small file sizes.
- **JPEG** is a lossy compressed format whose quality can be tuned — lowering the quality removes detail and adds noise, but the file becomes smaller. JPEG is optimal for photographs and any image with a large colour range, and is a common web choice thanks to its compression ratio.

### Rendering to PDF

GroupDocs.Viewer renderiza un documento en un único archivo PDF. Renderizar a PDF es la mejor opción cuando necesita:

- Print documents.
- Send documents via email.
- Distribute all pages as a single file rather than a collection of per-page files.

## Retrieving Document Information

GroupDocs.Viewer para Python expone información básica sobre un documento fuente — tipo de archivo, número de páginas, texto con coordenadas y más — sin renderizar. Consulte [Get Document Info]().

La información específica de formato también está disponible:

- **Archive** — list of folders contained in the archive.
- **CAD** — list of layers and layouts in a CAD document.
- **Email** — list of folders contained in an Outlook data file.
- **PDF** — a flag that indicates whether document printing is allowed.
- **Project Management** — project start and end dates.

### Text extraction

Puede optar por extraer el texto del documento al renderizar a PNG o JPEG. El texto se devuelve junto con coordenadas por palabra, lo que es útil al superponer una capa de texto seleccionable sobre la imagen de la página.

## Processing Attachments

En GroupDocs.Viewer, *attachments* abarca los adjuntos de correo electrónico, archivos incrustados en PDFs y elementos individuales dentro de archivos comprimidos.

Con GroupDocs.Viewer puede enumerar y guardar:

- Email attachments.
- Files embedded in PDF documents.
- Email messages contained in Outlook and Lotus Notes data files.
- Individual files inside archive containers.

Consulte [Processing Attachments]() para un ejemplo ejecutable.

## Output Transformation

GroupDocs.Viewer para Python incluye un conjunto de opciones para transformar cada página renderizada:

- **Rotate pages** — change page orientation when rendering to HTML, JPG, PNG, or PDF.
- **Add a text watermark** — stamp a text watermark on every rendered page.
- **Reorder pages** — render pages in any order you prefer, including when rendering to PDF.

## Caching Results

GroupDocs.Viewer para Python admite el almacenamiento en caché para acelerar renderizados repetidos y reducir la carga total de la aplicación.

Por defecto, la caché se almacena en el disco local. La API del visor también expone interfaces de caché que pueden implementarse para almacenamiento de terceros — FTP, Amazon S3, Dropbox, Google Drive, Microsoft Azure, Redis o cualquier otro backend.
