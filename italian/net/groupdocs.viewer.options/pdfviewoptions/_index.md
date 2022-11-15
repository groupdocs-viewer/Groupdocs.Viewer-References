---
title: PdfViewOptions
second_title: Riferimento API GroupDocs.Viewer per .NET
description: Fornisce opzioni per il rendering dei documenti in formato PDF.
type: docs
weight: 420
url: /it/net/groupdocs.viewer.options/pdfviewoptions/
---
## PdfViewOptions class

Fornisce opzioni per il rendering dei documenti in formato PDF.

```csharp
public class PdfViewOptions : ViewOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | Inizializza la nuova istanza di[`PdfViewOptions`](../pdfviewoptions) classe. |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | Inizializza la nuova istanza di[`PdfViewOptions`](../pdfviewoptions) classe. |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | Inizializza la nuova istanza di[`PdfViewOptions`](../pdfviewoptions) classe. |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | Inizializza la nuova istanza di[`PdfViewOptions`](../pdfviewoptions) classe. |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | Inizializza la nuova istanza di[`PdfViewOptions`](../pdfviewoptions) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Le opzioni di visualizzazione dei file di archivio. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Le opzioni di visualizzazione del disegno CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Carattere predefinito da utilizzare quando non è possibile trovare un determinato carattere utilizzato nel documento. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Le opzioni di visualizzazione dei messaggi e-mail. |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | L'altezza di un'immagine di output in pixel. (Quando si converte una singola immagine solo in HTML) |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | Altezza massima di un'immagine di output in pixel. (Quando si converte solo una singola immagine in HTML) |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | Larghezza massima di un'immagine di output in pixel. (Quando si converte solo una singola immagine in HTML) |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | La larghezza dell'immagine di output in pixel. (Quando si converte una singola immagine solo in HTML) |
| [JpgQuality](../../groupdocs.viewer.options/pdfviewoptions/jpgquality) { get; set; } | La qualità delle immagini JPG contenute nel documento PDF di output; I valori validi sono compresi tra 1 e 100; Il valore predefinito è 90. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Opzioni di visualizzazione dei file di dati di archiviazione della posta. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | I file di dati di MS Outlook visualizzano le opzioni. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Le opzioni di visualizzazione dei documenti PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Le opzioni di visualizzazione dei documenti di elaborazione della presentazione. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | I file di gestione del progetto visualizzano le opzioni. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Abilita il rendering dei commenti. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Abilita il rendering di pagine nascoste. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Abilita il rendering delle note. |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | Le opzioni di protezione del documento PDF di output. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | I file del foglio di calcolo visualizzano le opzioni. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Opzioni di suddivisione dei file di testo in pagine. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | I file di Visio elaborano le opzioni di visualizzazione dei documenti. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | La filigrana di testo applicata a ciascuna pagina. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Queste opzioni di rendering consentono di personalizzare l'aspetto dell'output HTML/PDF/PNG/JPEG durante il rendering di documenti Web. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Queste opzioni di rendering consentono di personalizzare l'aspetto dell'output HTML/PDF/PNG/JPEG durante il rendering di documenti Word. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Applica la rotazione in senso orario alla pagina. |

## Campi

| Nome | Descrizione |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Le rotazioni della pagina. |

### Guarda anche

* class [ViewOptions](../viewoptions)
* spazio dei nomi [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assemblea [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->