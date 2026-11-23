---
title: "Viewer"
second_title: "GroupDocs.Viewer per .NET API Reference"
description: "Rappresenta la classe principale che controlla il processo di rendering del documento."
type: docs
weight: 50
url: /it/net/groupdocs.viewer/viewer/
---

## Viewer class

Rappresenta la classe principale che controlla il processo di rendering del documento.

```csharp
public class Viewer : IDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Viewer](viewer#constructor)(Func&lt;Stream&gt;) | Inizializza una nuova istanza della classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_4)(Stream) | Inizializza una nuova istanza della classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_12)(string) | Inizializza una nuova istanza della classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_2)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | Inizializza una nuova istanza della classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_1)(Func&lt;Stream&gt;, ViewerSettings) | Inizializza una nuova istanza della classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_5)(Stream, bool) | Inizializza una nuova istanza della classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_6)(Stream, LoadOptions) | Inizializza una nuova istanza della classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_10)(Stream, ViewerSettings) | Inizializza una nuova istanza della classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_13)(string, LoadOptions) | Inizializza una nuova istanza della classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_15)(string, ViewerSettings) | Inizializza una nuova istanza della classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) | Inizializza una nuova istanza della classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_7)(Stream, LoadOptions, bool) | Inizializza una nuova istanza della classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_8)(Stream, LoadOptions, ViewerSettings) | Inizializza una nuova istanza della classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_11)(Stream, ViewerSettings, bool) | Inizializza una nuova istanza della classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_14)(string, LoadOptions, ViewerSettings) | Inizializza una nuova istanza della classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_9)(Stream, LoadOptions, ViewerSettings, bool) | Inizializza una nuova istanza della classe [`Viewer`](../viewer). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../groupdocs.viewer/viewer/dispose)() | Rilascia lo stream del file e le risorse interne gestite. |
| [GetAllFonts](../../groupdocs.viewer/viewer/getallfonts)() | Restituisce tutti i font utilizzati nei documenti caricati, includendo quelli incorporati nel documento stesso e i font di sistema installati nel sistema operativo e usati nel documento. |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments)() | Restituisce gli allegati contenuti nel documento. |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments_1)(CancellationToken) | Restituisce gli allegati contenuti nel documento. |
| [GetFileInfo](../../groupdocs.viewer/viewer/getfileinfo)() | Restituisce informazioni sul file, come il tipo di file e l'indicatore che segnala se il file è crittografato. |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo)(ViewInfoOptions) | Restituisce informazioni sulla visualizzazione e informazioni specifiche del documento. |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo_1)(ViewInfoOptions, CancellationToken) | Restituisce informazioni sulla visualizzazione e informazioni specifiche del documento. |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment)(Attachment, Stream) | Salva il file allegato nello stream di *destinazione*. |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment_1)(Attachment, Stream, CancellationToken) | Salva il file allegato nello stream di *destinazione*. |
| [Search](../../groupdocs.viewer/viewer/search)(SearchHighlightOptions) | Esegue una ricerca di testo e la sua evidenziazione (se trovata) nel documento caricato secondo le opzioni caricate. |
| [View](../../groupdocs.viewer/viewer/view#view)(ViewOptions) | Crea la visualizzazione di tutte le pagine del documento. |
| [View](../../groupdocs.viewer/viewer/view#view_2)(ViewOptions, CancellationToken) | Crea la visualizzazione di tutte le pagine del documento. |
| [View](../../groupdocs.viewer/viewer/view#view_1)(ViewOptions, params int[]) | Crea la visualizzazione di pagine specifiche del documento. |
| [View](../../groupdocs.viewer/viewer/view#view_3)(ViewOptions, CancellationToken, params int[]) | Crea la visualizzazione di pagine specifiche del documento. |

### Vedi anche

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
