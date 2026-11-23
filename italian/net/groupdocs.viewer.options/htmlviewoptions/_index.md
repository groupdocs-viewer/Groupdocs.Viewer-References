---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer per .NET API Reference"
description: "Contiene le opzioni per il rendering dei documenti in formato HTML. Per i dettagli vedere il topic https//docs.groupdocs.com/viewer/net/renderingtohtml/ e i suoi figli."
type: docs
weight: 320
url: /it/net/groupdocs.viewer.options/htmlviewoptions/
---

## HtmlViewOptions class

Contiene opzioni per il rendering dei documenti in formato HTML. Per ulteriori dettagli, vedere l'[argomento](https://docs.groupdocs.com/viewer/net/rendering-to-html/) e le sue sezioni.

```csharp
public class HtmlViewOptions : ViewOptions
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Le opzioni di visualizzazione dei file di archivio. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Le opzioni di visualizzazione dei disegni CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Imposta il carattere predefinito per un documento. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Le opzioni di visualizzazione dei messaggi email. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | Disabilita l'aggiunta di qualsiasi font nel documento HTML. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | L'elenco dei nomi dei font da escludere dal documento HTML. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | Abilita l'ottimizzazione dell'HTML di output per la stampa. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | L'altezza di un'immagine di output (in pixel). La proprietà è disponibile solo quando si converte un'immagine singola in HTML. |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | Altezza massima di un'immagine di output (in pixel). La proprietà è disponibile solo durante la conversione di un'immagine singola in HTML. |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | Larghezza massima di un'immagine di output (in pixel). La proprietà è disponibile solo durante la conversione di un'immagine singola in HTML. |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | La larghezza dell'immagine di output (in pixel). La proprietà è disponibile solo durante la conversione di un'immagine singola in HTML. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Le opzioni di visualizzazione dei file di dati di archiviazione della posta. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | Abilita la minificazione del contenuto HTML e delle risorse HTML. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Le opzioni di visualizzazione dei file di dati di Microsoft Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Le opzioni di visualizzazione del documento PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Le opzioni di visualizzazione dei file di presentazione. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Le opzioni di visualizzazione dei file di gestione progetti. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Disabilita il rendering dei commenti quando impostato su `true`. Per impostazione predefinita è `false` — tutti i commenti sono visualizzati. |
| [RemoveJavaScript](../../groupdocs.viewer.options/htmlviewoptions/removejavascript) { get; set; } | Consente di rimuovere il codice sorgente JavaScript dai collegamenti nei documenti HTML risultanti, durante il rendering dei documenti di input che contengono script. Per impostazione predefinita è abilitato (`true`). |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Abilita il rendering delle pagine nascoste. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Abilita il rendering di note e annotazioni per alcuni formati. |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | Abilita il rendering responsivo. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | Abilita il rendering di un intero documento in un unico file HTML. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Le opzioni di visualizzazione dei file di foglio di calcolo. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Le opzioni di visualizzazione dei file di testo. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Le opzioni di visualizzazione dei file Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | La filigrana di testo da applicare a ogni pagina. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Le opzioni di visualizzazione dei file Web. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Le opzioni di visualizzazione dei file di elaborazione testi. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | Inizializza un'istanza della classe [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | Inizializza un'istanza della classe [`HtmlViewOptions`](../htmlviewoptions) per il rendering in HTML con risorse incorporate. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | Inizializza un'istanza della classe [`HtmlViewOptions`](../htmlviewoptions) per il rendering in HTML con risorse incorporate. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | Inizializza un'istanza della classe [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | Inizializza un'istanza della classe [`HtmlViewOptions`](../htmlviewoptions) per il rendering in HTML con risorse incorporate. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | Inizializza un'istanza della classe [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | Inizializza un'istanza della classe [`HtmlViewOptions`](../htmlviewoptions) per il rendering in HTML con risorse esterne. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | Inizializza un'istanza della classe [`HtmlViewOptions`](../htmlviewoptions) per il rendering in HTML con risorse esterne. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | Inizializza un'istanza della classe [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | Inizializza un'istanza della classe [`HtmlViewOptions`](../htmlviewoptions) per il rendering in HTML con risorse esterne. |
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
