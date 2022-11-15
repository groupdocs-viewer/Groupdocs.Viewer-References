---
title: Viewer
second_title: Riferimento API GroupDocs.Viewer per .NET
description: Rappresenta la classe principale che controlla il processo di rendering del documento.
type: docs
weight: 800
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
| [Viewer](viewer#constructor)(Func&lt;Stream&gt;) | Inizializza la nuova istanza di[`Viewer`](../viewer) classe. |
| [Viewer](viewer#constructor_4)(Stream) | Inizializza la nuova istanza di[`Viewer`](../viewer) classe. |
| [Viewer](viewer#constructor_12)(string) | Inizializza la nuova istanza di[`Viewer`](../viewer) classe. |
| [Viewer](viewer#constructor_2)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | Inizializza la nuova istanza di[`Viewer`](../viewer) classe. |
| [Viewer](viewer#constructor_1)(Func&lt;Stream&gt;, ViewerSettings) | Inizializza la nuova istanza di[`Viewer`](../viewer) classe. |
| [Viewer](viewer#constructor_5)(Stream, bool) | Inizializza la nuova istanza di[`Viewer`](../viewer) classe. |
| [Viewer](viewer#constructor_6)(Stream, LoadOptions) | Inizializza la nuova istanza di[`Viewer`](../viewer) classe. |
| [Viewer](viewer#constructor_10)(Stream, ViewerSettings) | Inizializza la nuova istanza di[`Viewer`](../viewer) classe. |
| [Viewer](viewer#constructor_13)(string, LoadOptions) | Inizializza la nuova istanza di[`Viewer`](../viewer) classe. |
| [Viewer](viewer#constructor_15)(string, ViewerSettings) | Inizializza la nuova istanza di[`Viewer`](../viewer) classe. |
| [Viewer](viewer#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) | Inizializza la nuova istanza di[`Viewer`](../viewer) classe. |
| [Viewer](viewer#constructor_7)(Stream, LoadOptions, bool) | Inizializza la nuova istanza di[`Viewer`](../viewer) classe. |
| [Viewer](viewer#constructor_8)(Stream, LoadOptions, ViewerSettings) | Inizializza la nuova istanza di[`Viewer`](../viewer) classe. |
| [Viewer](viewer#constructor_11)(Stream, ViewerSettings, bool) | Inizializza la nuova istanza di[`Viewer`](../viewer) classe. |
| [Viewer](viewer#constructor_14)(string, LoadOptions, ViewerSettings) | Inizializza la nuova istanza di[`Viewer`](../viewer) classe. |
| [Viewer](viewer#constructor_9)(Stream, LoadOptions, ViewerSettings, bool) | Inizializza la nuova istanza di[`Viewer`](../viewer) classe. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../groupdocs.viewer/viewer/dispose)() | Rilascia il flusso di file e le risorse interne gestite. |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments)() | Restituisce gli allegati contenuti nel documento. |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments_1)(CancellationToken) | Restituisce gli allegati contenuti nel documento. |
| [GetFileInfo](../../groupdocs.viewer/viewer/getfileinfo)() | Restituisce informazioni sul file come il tipo di file e il flag che indica se il file è crittografato. |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo)(ViewInfoOptions) | Restituisce informazioni sulla vista e informazioni specifiche del documento. |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo_1)(ViewInfoOptions, CancellationToken) | Restituisce informazioni sulla vista e informazioni specifiche del documento. |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment)(Attachment, Stream) | Salva il file allegato in*destination* flusso. |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment_1)(Attachment, Stream, CancellationToken) | Salva il file allegato in*destination* flusso. |
| [View](../../groupdocs.viewer/viewer/view#view)(ViewOptions) | Crea la visualizzazione di tutte le pagine del documento. |
| [View](../../groupdocs.viewer/viewer/view#view_2)(ViewOptions, CancellationToken) | Crea la visualizzazione di tutte le pagine del documento. |
| [View](../../groupdocs.viewer/viewer/view#view_1)(ViewOptions, params int[]) | Crea la visualizzazione di pagine di documenti specifici. |
| [View](../../groupdocs.viewer/viewer/view#view_3)(ViewOptions, CancellationToken, params int[]) | Crea la visualizzazione di pagine di documenti specifici. |

### Guarda anche

* spazio dei nomi [GroupDocs.Viewer](../../groupdocs.viewer)
* assemblea [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->