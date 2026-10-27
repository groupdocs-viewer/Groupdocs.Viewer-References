---
title: "Aperçu des fonctionnalités"
linkTitle: "Features overview"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Rendez les documents en HTML, PDF, PNG ou JPEG ; extrayez le texte ; listez les pièces jointes ; et appliquez des rotations, des réordonnancements et des filigranes avec GroupDocs.Viewer pour Python via .NET."
type: docs
url: /fr/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Rendering Documents

Le terme *rendering* dans GroupDocs.Viewer décrit le processus de conversion d'un document en un format de fichier qui préserve les limites de page. Par exemple, lorsqu'un fichier DOCX de trois pages est rendu en HTML, le résultat est de trois fichiers HTML — un par page. Consultez le [Guide du développeur]() pour des exemples exécutables.

![Rendering diagram](https://docs.groupdocs.com/viewer/python-net/images/getting-started/features-overview/rendering.png)

### Rendering to HTML

Le rendu en HTML est le meilleur choix lorsque vous devez :

- Build a web-based application and display document content inside a browser.
- Allow users to interact with the rendered text — select, copy, or search it.
- View document pages separately.
- Zoom in on a document without quality loss.
- Rotate, reorder, or watermark pages.

GroupDocs.Viewer pour Python propose deux modes de gestion des ressources HTML :

- **HTML with external resources** — stores page resources (CSS, fonts, images) next to the HTML file so common resources are reused across pages. Reduces overall page size and speeds up loading.
- **HTML with embedded resources** — inlines every resource into the HTML file so each page is self-contained. Larger individual files but easier to distribute.

### Rendering to PNG or JPEG

Le rendu en PNG ou JPEG est le meilleur choix lorsque vous devez :

- Support any type of application (desktop, web, mobile, CLI).
- Restrict interaction with rendered text — for example, to prevent copying. You can still extract a text layer separately if you want to overlay selectable text on the image.
- View document pages separately.
- Rotate, reorder, or watermark pages.

Une comparaison rapide des deux formats d'image :

- **PNG** is a lossless raster format that supports full-colour images and transparency. PNG does not expose a quality setting. It is a good choice for line drawings, text, and iconic graphics at small file sizes.
- **JPEG** is a lossy compressed format whose quality can be tuned — lowering the quality removes detail and adds noise, but the file becomes smaller. JPEG is optimal for photographs and any image with a large colour range, and is a common web choice thanks to its compression ratio.

### Rendering to PDF

GroupDocs.Viewer rend un document dans un seul fichier PDF. Le rendu en PDF est le meilleur choix lorsque vous devez :

- Print documents.
- Send documents via email.
- Distribute all pages as a single file rather than a collection of per-page files.

## Retrieving Document Information

GroupDocs.Viewer pour Python expose des informations de base sur un document source — type de fichier, nombre de pages, texte avec coordonnées, et plus — sans rendu. Consultez [Obtenir les informations du document]().

Des informations spécifiques au format sont également disponibles :

- **Archive** — list of folders contained in the archive.
- **CAD** — list of layers and layouts in a CAD document.
- **Email** — list of folders contained in an Outlook data file.
- **PDF** — a flag that indicates whether document printing is allowed.
- **Project Management** — project start and end dates.

### Text extraction

Vous pouvez choisir d'extraire le texte du document lors du rendu en PNG ou JPEG. Le texte est renvoyé avec les coordonnées mot à mot, ce qui est utile lors du superposition d'une couche de texte sélectionnable sur l'image d'une page.

## Processing Attachments

Dans GroupDocs.Viewer, les *attachments* couvrent les pièces jointes d'e‑mail, les fichiers intégrés dans les PDF et les éléments individuels à l'intérieur des archives compressées.

Avec GroupDocs.Viewer, vous pouvez lister et enregistrer :

- Email attachments.
- Files embedded in PDF documents.
- Email messages contained in Outlook and Lotus Notes data files.
- Individual files inside archive containers.

Voir [Traitement des pièces jointes]() pour un exemple exécutable.

## Output Transformation

GroupDocs.Viewer pour Python fournit un ensemble d'options pour transformer chaque page rendue :

- **Rotate pages** — change page orientation when rendering to HTML, JPG, PNG, or PDF.
- **Add a text watermark** — stamp a text watermark on every rendered page.
- **Reorder pages** — render pages in any order you prefer, including when rendering to PDF.

## Caching Results

GroupDocs.Viewer pour Python prend en charge la mise en cache pour accélérer les rendus répétés et réduire la charge globale de l'application.

Par défaut, le cache est stocké sur le disque local. L'API du visualiseur expose également des interfaces de cache qui peuvent être implémentées pour un stockage tiers — FTP, Amazon S3, Dropbox, Google Drive, Microsoft Azure, Redis, ou tout autre backend.
