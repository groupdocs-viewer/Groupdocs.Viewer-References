---
title: ViewInfoOptions
second_title: Riferimento API GroupDocs.Viewer per .NET
description: Fornisce le opzioni utilizzate per recuperare informazioni sulla vista.
type: docs
weight: 570
url: /it/net/groupdocs.viewer.options/viewinfooptions/
---
## ViewInfoOptions class

Fornisce le opzioni utilizzate per recuperare informazioni sulla vista.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Le opzioni di visualizzazione dei file di archivio. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Le opzioni di visualizzazione del disegno CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Carattere predefinito da utilizzare quando non è possibile trovare un determinato carattere utilizzato nel documento. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Le opzioni di visualizzazione dei messaggi e-mail. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | Indica che l'estrazione del testo è abilitata. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | Altezza immagine (solo per il rendering in PNG/JPG) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Opzioni di visualizzazione dei file di dati di archiviazione della posta. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | Altezza massima dell'immagine di output (solo per il rendering in PNG/JPG) |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | Larghezza massima dell'immagine di output (solo per il rendering in PNG/JPG) |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | I file di dati di MS Outlook visualizzano le opzioni. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Le opzioni di visualizzazione dei documenti PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Le opzioni di visualizzazione dei documenti di elaborazione della presentazione. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | I file di gestione del progetto visualizzano le opzioni. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Abilita il rendering dei commenti. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Abilita il rendering di pagine nascoste. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Abilita il rendering delle note. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | I file del foglio di calcolo visualizzano le opzioni. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Opzioni di suddivisione dei file di testo in pagine. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | I file di Visio elaborano le opzioni di visualizzazione dei documenti. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Queste opzioni di rendering consentono di personalizzare l'aspetto dell'output HTML/PDF/PNG/JPEG durante il rendering di documenti Web. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | Larghezza immagine (solo per il rendering in PNG/JPG) |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Queste opzioni di rendering consentono di personalizzare l'aspetto dell'output HTML/PDF/PNG/JPEG durante il rendering di documenti Word. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | Inizializza la nuova istanza di[`ViewInfoOptions`](../viewinfooptions) classe per recuperare informazioni sulla visualizzazione durante il rendering in HTML. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | Inizializza la nuova istanza di[`ViewInfoOptions`](../viewinfooptions) classe per recuperare informazioni sulla visualizzazione durante il rendering in HTML. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | Inizializza la nuova istanza di[`ViewInfoOptions`](../viewinfooptions) classe per recuperare informazioni sulla visualizzazione durante il rendering in JPG. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | Inizializza la nuova istanza di[`ViewInfoOptions`](../viewinfooptions) classe per recuperare informazioni sulla visualizzazione durante il rendering in JPG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | Inizializza la nuova istanza di[`ViewInfoOptions`](../viewinfooptions)classe per recuperare informazioni sulla visualizzazione durante il rendering in PNG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | Inizializza la nuova istanza di[`ViewInfoOptions`](../viewinfooptions)classe per recuperare informazioni sulla visualizzazione durante il rendering in PNG. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | Inizializza la nuova istanza di[`ViewInfoOptions`](../viewinfooptions) classe basata su[`HtmlViewOptions`](../htmlviewoptions) oggetto. |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | Inizializza la nuova istanza di[`ViewInfoOptions`](../viewinfooptions) classe basata su[`JpgViewOptions`](../jpgviewoptions) oggetto. |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | Inizializza la nuova istanza di[`ViewInfoOptions`](../viewinfooptions) classe basata su[`PngViewOptions`](../pngviewoptions) oggetto. |

### Guarda anche

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* spazio dei nomi [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assemblea [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
