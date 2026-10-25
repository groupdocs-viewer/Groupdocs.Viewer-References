---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer per .NET API Reference"
description: "Contiene opzioni per il rendering dei documenti Word. Per ulteriori dettagli vedere la documentazione https://docs.groupdocs.com/viewer/net/renderworddocuments/."
type: docs
weight: 630
url: /it/net/groupdocs.viewer.options/wordprocessingoptions/
---

## WordProcessingOptions class

Contiene opzioni per il rendering dei documenti Word. Per ulteriori dettagli, vedere la [documentazione](https://docs.groupdocs.com/viewer/net/render-word-documents/).

```csharp
public class WordProcessingOptions : ICloneable, IEquatable<WordProcessingOptions>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [WordProcessingOptions](wordprocessingoptions)() | Contiene opzioni per il rendering dei documenti di elaborazione testi. Per ulteriori dettagli, vedere la [documentazione](https://docs.groupdocs.com/viewer/net/render-word-documents/). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/wordprocessingoptions/bottommargin) { get; set; } | Imposta il margine inferiore di una pagina. |
| [EnableOpenTypeFeatures](../../groupdocs.viewer.options/wordprocessingoptions/enableopentypefeatures) { get; set; } | Questa opzione abilita il kerning e altre funzionalità OpenType durante il rendering di script arabi, ebraici, indiani basati su latino o basati su cirillico. |
| [HorizontalResolution](../../groupdocs.viewer.options/wordprocessingoptions/horizontalresolution) { get; set; } | Ottiene o imposta la risoluzione orizzontale per le immagini generate in punti per pollice. Questa opzione è utilizzata solo durante il rendering di documenti WordProcessing in formati PNG o JPEG. |
| [LeftMargin](../../groupdocs.viewer.options/wordprocessingoptions/leftmargin) { get; set; } | Imposta il margine sinistro di una pagina. |
| [PageNumberLocation](../../groupdocs.viewer.options/wordprocessingoptions/pagenumberlocation) { get; set; } | Consente di applicare forzatamente la numerazione delle pagine per il documento WordProcessing caricato. Per impostazione predefinita è NotApply — il documento rimane intatto. |
| [PageSize](../../groupdocs.viewer.options/wordprocessingoptions/pagesize) { get; set; } | La dimensione della pagina di output. Il valore predefinito è Unspecified, il che significa che viene utilizzata una dimensione di pagina impostata nelle impostazioni della pagina (Page Setup). Quando si esegue il rendering di file HTM e HTML, la dimensione di pagina predefinita è impostata a Letter 792 x 612 punti. Di conseguenza, parte del contenuto potrebbe non adattarsi al riquadro della pagina. Imposta una dimensione di pagina più grande, ad esempio A3, per adattare il contenuto. |
| [RenderTrackedChanges](../../groupdocs.viewer.options/wordprocessingoptions/rendertrackedchanges) { get; set; } | Abilita il rendering delle modifiche tracciate (revisioni). |
| [RightMargin](../../groupdocs.viewer.options/wordprocessingoptions/rightmargin) { get; set; } | Imposta il margine destro di una pagina. |
| [TopMargin](../../groupdocs.viewer.options/wordprocessingoptions/topmargin) { get; set; } | Imposta il margine superiore di una pagina. |
| [UnlinkTableOfContents](../../groupdocs.viewer.options/wordprocessingoptions/unlinktableofcontents) { get; set; } | Durante il rendering in HTML o PDF, è possibile impostare questa opzione su `true` per disabilitare la navigazione dall'indice. Per il rendering HTML, i tag `a` con collegamenti relativi saranno sostituiti da tag `span`, rimuovendo la funzionalità ma mantenendo l'aspetto visivo. Per il rendering PDF, l'indice verrà renderizzato come testo semplice senza collegamenti alle sezioni del documento. |
| [UpdateFields](../../groupdocs.viewer.options/wordprocessingoptions/updatefields) { get; set; } | Ottiene o imposta un valore che determina se i campi di determinati tipi devono essere aggiornati prima di salvare il documento WordProcessing di input nei formati di output HTML, PDF, PNG o JPEG. Il valore predefinito per questa proprietà è `true` — i campi saranno aggiornati prima del salvataggio. |
| [VerticalResolution](../../groupdocs.viewer.options/wordprocessingoptions/verticalresolution) { get; set; } | Ottiene o imposta la risoluzione verticale per le immagini generate in punti per pollice. Questa opzione è utilizzata solo durante il rendering di documenti WordProcessing in formati PNG o JPEG. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.viewer.options/wordprocessingoptions/clone)() | Crea e restituisce una copia profonda completa di queste opzioni |
| [Equals](../../groupdocs.viewer.options/wordprocessingoptions/equals#equals)(WordProcessingOptions) | Determina se l'istanza specificata di [`WordProcessingOptions`](../wordprocessingoptions) è uguale a questa |

### Vedi anche

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
