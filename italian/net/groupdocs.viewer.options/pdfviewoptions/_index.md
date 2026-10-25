---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer per .NET API Reference"
description: "Contiene opzioni per il rendering dei documenti in formato PDF. Per ulteriori dettagli vedere la documentazionehttps//docs.groupdocs.com/viewer/net/renderingtopdf/."
type: docs
weight: 420
url: /it/net/groupdocs.viewer.options/pdfviewoptions/
---

## PdfViewOptions class

Contiene opzioni per il rendering dei documenti in formato PDF. Per ulteriori dettagli, vedere la [documentazione](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

```csharp
public class PdfViewOptions : ViewOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | Inizializza un'istanza della classe [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | Inizializza un'istanza della classe [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | Inizializza un'istanza della classe [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | Inizializza un'istanza della classe [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | Inizializza un'istanza della classe [`PdfViewOptions`](../pdfviewoptions). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Le opzioni di visualizzazione dei file di archivio. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Le opzioni di visualizzazione dei disegni CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Imposta il carattere predefinito per un documento. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Le opzioni di visualizzazione dei messaggi email. |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | Imposta l'altezza di un'immagine di output (in pixel). |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | Imposta l'altezza massima di un'immagine di output (in pixel). |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | Imposta la larghezza massima di un'immagine di output (in pixel). |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | Imposta la larghezza di un'immagine di output (in pixel). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Le opzioni di visualizzazione dei file di dati di archiviazione della posta. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Le opzioni di visualizzazione dei file di dati di Microsoft Outlook. |
| [PdfOptimizationOptions](../../groupdocs.viewer.options/pdfviewoptions/pdfoptimizationoptions) { get; set; } | Riduce la dimensione del file PDF di output applicando tecniche di ottimizzazione con diverse opzioni. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Le opzioni di visualizzazione del documento PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Le opzioni di visualizzazione dei file di presentazione. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Le opzioni di visualizzazione dei file di gestione progetti. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Disabilita il rendering dei commenti quando impostato su `true`. Per impostazione predefinita è `false` — tutti i commenti sono visualizzati. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Abilita il rendering delle pagine nascoste. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Abilita il rendering di note e annotazioni per alcuni formati. |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | Imposta le opzioni di sicurezza del documento PDF di output. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Le opzioni di visualizzazione dei file di foglio di calcolo. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Le opzioni di visualizzazione dei file di testo. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Le opzioni di visualizzazione dei file Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | La filigrana di testo da applicare a ogni pagina. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Le opzioni di visualizzazione dei file Web. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Le opzioni di visualizzazione dei file di elaborazione testi. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Applica la rotazione in senso orario a una pagina. |

## Campi

| Nome | Descrizione |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | La rotazione della pagina. |

### Vedi anche

* class [ViewOptions](../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
