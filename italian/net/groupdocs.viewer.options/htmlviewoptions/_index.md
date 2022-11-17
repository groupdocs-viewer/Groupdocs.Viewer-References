---
title: HtmlViewOptions
second_title: Riferimento API GroupDocs.Viewer per .NET
description: Fornisce opzioni per il rendering dei documenti in formato HTML.
type: docs
weight: 330
url: /it/net/groupdocs.viewer.options/htmlviewoptions/
---
## HtmlViewOptions class

Fornisce opzioni per il rendering dei documenti in formato HTML.

```csharp
public class HtmlViewOptions : ViewOptions
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Le opzioni di visualizzazione dei file di archivio. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Le opzioni di visualizzazione del disegno CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Carattere predefinito da utilizzare quando non è possibile trovare un determinato carattere utilizzato nel documento. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Le opzioni di visualizzazione dei messaggi e-mail. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | Quando abilitato impedisce l'aggiunta di caratteri nel documento HTML. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | L'elenco dei nomi dei caratteri, da escludere dal documento HTML. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | Indica se ottimizzare l'HTML di output per la stampa. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | L'altezza di un'immagine di output in pixel. (Quando si converte una singola immagine solo in HTML) |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | Altezza massima di un'immagine di output in pixel. (Quando si converte solo una singola immagine in HTML) |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | Larghezza massima di un'immagine di output in pixel. (Quando si converte solo una singola immagine in HTML) |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | La larghezza dell'immagine di output in pixel. (Quando si converte una singola immagine solo in HTML) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Opzioni di visualizzazione dei file di dati di archiviazione della posta. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | Abilita la minimizzazione del contenuto HTML e delle risorse HTML. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | I file di dati di MS Outlook visualizzano le opzioni. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Le opzioni di visualizzazione dei documenti PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Le opzioni di visualizzazione dei documenti di elaborazione della presentazione. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | I file di gestione del progetto visualizzano le opzioni. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Abilita il rendering dei commenti. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Abilita il rendering di pagine nascoste. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Abilita il rendering delle note. |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | Abilita il rendering reattivo; Le pagine Web reattive vengono visualizzate bene su dispositivi con dimensioni dello schermo diverse. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | Abilita il rendering del contenuto HTML su una singola pagina |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | I file del foglio di calcolo visualizzano le opzioni. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Opzioni di suddivisione dei file di testo in pagine. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | I file di Visio elaborano le opzioni di visualizzazione dei documenti. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | La filigrana di testo applicata a ciascuna pagina. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Queste opzioni di rendering consentono di personalizzare l'aspetto dell'output HTML/PDF/PNG/JPEG durante il rendering di documenti Web. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Queste opzioni di rendering consentono di personalizzare l'aspetto dell'output HTML/PDF/PNG/JPEG durante il rendering di documenti Word. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | Inizializza la nuova istanza di[`HtmlViewOptions`](../htmlviewoptions) classe. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | Inizializza la nuova istanza di[`HtmlViewOptions`](../htmlviewoptions) classe per il rendering in HTML con risorse incorporate. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | Inizializza la nuova istanza di[`HtmlViewOptions`](../htmlviewoptions) classe per il rendering in HTML con risorse incorporate. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | Inizializza la nuova istanza di[`HtmlViewOptions`](../htmlviewoptions) classe. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | Inizializza la nuova istanza di[`HtmlViewOptions`](../htmlviewoptions) classe per il rendering in HTML con risorse incorporate. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | Inizializza la nuova istanza di[`HtmlViewOptions`](../htmlviewoptions) classe. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | Inizializza la nuova istanza di[`HtmlViewOptions`](../htmlviewoptions) classe per il rendering in HTML con risorse esterne. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | Inizializza la nuova istanza di[`HtmlViewOptions`](../htmlviewoptions) classe per il rendering in HTML con risorse esterne. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | Inizializza la nuova istanza di[`HtmlViewOptions`](../htmlviewoptions) classe. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | Inizializza la nuova istanza di[`HtmlViewOptions`](../htmlviewoptions) classe per il rendering in HTML con risorse esterne. |
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
