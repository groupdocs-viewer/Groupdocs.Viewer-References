---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer per .NET API Reference"
description: "Contiene opzioni per il rendering dei documenti in formato PNG. Per i dettagli, vedere questa paginahttps//docs.groupdocs.com/viewer/net/renderingtopngorjpeg/ e le relative sezioni."
type: docs
weight: 440
url: /it/net/groupdocs.viewer.options/pngviewoptions/
---

## PngViewOptions class

Contiene opzioni per il rendering dei documenti in formato PNG. Per ulteriori dettagli, vedere questa [pagina](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/) e le relative sezioni.

```csharp
public class PngViewOptions : ViewOptions, IMaxSizeOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PngViewOptions](pngviewoptions#constructor)() | Inizializza un'istanza della classe [`PngViewOptions`](../pngviewoptions). |
| [PngViewOptions](pngviewoptions#constructor_1)(CreatePageStream) | Inizializza un'istanza della classe [`PngViewOptions`](../pngviewoptions). |
| [PngViewOptions](pngviewoptions#constructor_3)(IPageStreamFactory) | Inizializza un'istanza della classe [`PngViewOptions`](../pngviewoptions). |
| [PngViewOptions](pngviewoptions#constructor_4)(string) | Inizializza un'istanza della classe [`PngViewOptions`](../pngviewoptions). |
| [PngViewOptions](pngviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | Inizializza un'istanza della classe [`PngViewOptions`](../pngviewoptions). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Le opzioni di visualizzazione dei file di archivio. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Le opzioni di visualizzazione dei disegni CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Imposta il carattere predefinito per un documento. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Le opzioni di visualizzazione dei messaggi email. |
| [ExtractText](../../groupdocs.viewer.options/pngviewoptions/extracttext) { get; set; } | Abilita l'estrazione del testo. |
| [Height](../../groupdocs.viewer.options/pngviewoptions/height) { get; set; } | Imposta l'altezza di un'immagine di output (in pixel). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Le opzioni di visualizzazione dei file di dati di archiviazione della posta. |
| [MaxHeight](../../groupdocs.viewer.options/pngviewoptions/maxheight) { get; set; } | Imposta l'altezza massima di un'immagine di output (in pixel). |
| [MaxWidth](../../groupdocs.viewer.options/pngviewoptions/maxwidth) { get; set; } | Imposta la larghezza massima di un'immagine di output (in pixel). |
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
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | La filigrana di testo da applicare a ogni pagina. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Le opzioni di visualizzazione dei file Web. |
| [Width](../../groupdocs.viewer.options/pngviewoptions/width) { get; set; } | La larghezza dell'immagine di output (in pixel). |
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
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
