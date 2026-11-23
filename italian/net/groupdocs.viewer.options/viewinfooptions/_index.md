---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer per .NET API Reference"
description: "Contiene opzioni per recuperare informazioni sulla visualizzazione."
type: docs
weight: 580
url: /it/net/groupdocs.viewer.options/viewinfooptions/
---

## ViewInfoOptions class

Contiene opzioni per recuperare informazioni sulla visualizzazione.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Le opzioni di visualizzazione dei file di archivio. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Le opzioni di visualizzazione dei disegni CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Imposta il carattere predefinito per un documento. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Le opzioni di visualizzazione dei messaggi email. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | Abilita l'estrazione del testo. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | L'altezza dell'immagine di output (in pixel, solo per il rendering in PNG/JPG). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Le opzioni di visualizzazione dei file di dati di archiviazione della posta. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | Imposta l'altezza massima di un'immagine di output (in pixel, solo per il rendering in PNG/JPG). |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | Imposta la larghezza massima di un'immagine di output (in pixel, solo per il rendering in PNG/JPG). |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Le opzioni di visualizzazione dei file di dati di Microsoft Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Le opzioni di visualizzazione del documento PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Le opzioni di visualizzazione dei file di presentazione. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Le opzioni di visualizzazione dei file di gestione progetti. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Disabilita il rendering dei commenti quando impostato su `true`. Per impostazione predefinita è `false` — tutti i commenti sono visualizzati. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Abilita il rendering delle pagine nascoste. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Abilita il rendering di note e annotazioni per alcuni formati. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Le opzioni di visualizzazione dei file di foglio di calcolo. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Le opzioni di visualizzazione dei file di testo. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Le opzioni di visualizzazione dei file Visio. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Le opzioni di visualizzazione dei file Web. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | La larghezza dell'immagine di output (in pixel, solo per il rendering in PNG/JPG). |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Le opzioni di visualizzazione dei file di elaborazione testi. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | Inizializza un'istanza della classe [`ViewInfoOptions`](../viewinfooptions) per recuperare informazioni sulla visualizzazione durante il rendering in HTML. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | Inizializza un'istanza della classe [`ViewInfoOptions`](../viewinfooptions) per recuperare informazioni sulla visualizzazione durante il rendering in HTML. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | Inizializza un'istanza della classe [`ViewInfoOptions`](../viewinfooptions) per recuperare informazioni sulla visualizzazione durante il rendering in JPG. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | Inizializza un'istanza della classe [`ViewInfoOptions`](../viewinfooptions) per recuperare informazioni sulla visualizzazione durante il rendering in JPG. |
| static [ForPdfView](../../groupdocs.viewer.options/viewinfooptions/forpdfview)() | Inizializza un'istanza della classe [`ViewInfoOptions`](../viewinfooptions) per recuperare informazioni sulla visualizzazione durante il rendering in PDF. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | Inizializza un'istanza della classe [`ViewInfoOptions`](../viewinfooptions) per recuperare informazioni sulla visualizzazione durante il rendering in PNG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | Inizializza un'istanza della classe [`ViewInfoOptions`](../viewinfooptions) per recuperare informazioni sulla visualizzazione durante il rendering in PNG. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | Inizializza un'istanza della classe [`ViewInfoOptions`](../viewinfooptions) basata sull'oggetto [`HtmlViewOptions`](../htmlviewoptions). |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | Inizializza un'istanza della classe [`ViewInfoOptions`](../viewinfooptions) basata sull'oggetto [`JpgViewOptions`](../jpgviewoptions). |
| static [FromPdfViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompdfviewoptions)(PdfViewOptions) | Inizializza un'istanza della classe [`ViewInfoOptions`](../viewinfooptions) basata sull'oggetto [`PdfViewOptions`](../pdfviewoptions). |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | Inizializza un'istanza della classe [`ViewInfoOptions`](../viewinfooptions) basata sull'oggetto [`PngViewOptions`](../pngviewoptions). |

### Vedi anche

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
