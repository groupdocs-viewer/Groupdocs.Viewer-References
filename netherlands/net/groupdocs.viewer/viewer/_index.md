---
title: "Viewer"
second_title: "GroupDocs.Viewer for .NET API-referentie"
description: "Stelt de hoofdklasse voor die het documentrenderingsproces beheert."
type: docs
weight: 50
url: /nl/net/groupdocs.viewer/viewer/
---

## Viewer class

Stelt de hoofdklasse voor die het documentrenderingsproces beheert.

```csharp
public class Viewer : IDisposable
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Viewer](viewer#constructor)(Func&lt;Stream&gt;) | Initialiseert een nieuwe instantie van [`Viewer`](../viewer) klasse. |
| [Viewer](viewer#constructor_4)(Stream) | Initialiseert een nieuwe instantie van [`Viewer`](../viewer) klasse. |
| [Viewer](viewer#constructor_12)(string) | Initialiseert een nieuwe instantie van [`Viewer`](../viewer) klasse. |
| [Viewer](viewer#constructor_2)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | Initialiseert een nieuwe instantie van [`Viewer`](../viewer) klasse. |
| [Viewer](viewer#constructor_1)(Func&lt;Stream&gt;, ViewerSettings) | Initialiseert een nieuwe instantie van [`Viewer`](../viewer) klasse. |
| [Viewer](viewer#constructor_5)(Stream, bool) | Initialiseert een nieuwe instantie van [`Viewer`](../viewer) klasse. |
| [Viewer](viewer#constructor_6)(Stream, LoadOptions) | Initialiseert een nieuwe instantie van [`Viewer`](../viewer) klasse. |
| [Viewer](viewer#constructor_10)(Stream, ViewerSettings) | Initialiseert een nieuwe instantie van [`Viewer`](../viewer) klasse. |
| [Viewer](viewer#constructor_13)(string, LoadOptions) | Initialiseert een nieuwe instantie van [`Viewer`](../viewer) klasse. |
| [Viewer](viewer#constructor_15)(string, ViewerSettings) | Initialiseert een nieuwe instantie van [`Viewer`](../viewer) klasse. |
| [Viewer](viewer#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) | Initialiseert een nieuwe instantie van [`Viewer`](../viewer) klasse. |
| [Viewer](viewer#constructor_7)(Stream, LoadOptions, bool) | Initialiseert een nieuwe instantie van [`Viewer`](../viewer) klasse. |
| [Viewer](viewer#constructor_8)(Stream, LoadOptions, ViewerSettings) | Initialiseert een nieuwe instantie van [`Viewer`](../viewer) klasse. |
| [Viewer](viewer#constructor_11)(Stream, ViewerSettings, bool) | Initialiseert een nieuwe instantie van [`Viewer`](../viewer) klasse. |
| [Viewer](viewer#constructor_14)(string, LoadOptions, ViewerSettings) | Initialiseert een nieuwe instantie van [`Viewer`](../viewer) klasse. |
| [Viewer](viewer#constructor_9)(Stream, LoadOptions, ViewerSettings, bool) | Initialiseert een nieuwe instantie van [`Viewer`](../viewer) klasse. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Dispose](../../groupdocs.viewer/viewer/dispose)() | Vrijgeeft de bestandsstroom en beheerde interne bronnen. |
| [GetAllFonts](../../groupdocs.viewer/viewer/getallfonts)() | Geeft alle lettertypen terug die in de geladen documenten worden gebruikt, inclusief de lettertypen die in het document zelf zijn ingebed en de systeemlettertypen die in het OS zijn geïnstalleerd en in het document worden gebruikt. |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments)() | Geeft bijlagen terug die in het document zijn opgenomen. |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments_1)(CancellationToken) | Geeft bijlagen terug die in het document zijn opgenomen. |
| [GetFileInfo](../../groupdocs.viewer/viewer/getfileinfo)() | Geeft informatie terug over het bestand, zoals bestandstype en een vlag die aangeeft of het bestand versleuteld is. |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo)(ViewInfoOptions) | Geeft informatie terug over de weergave en document‑specifieke informatie. |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo_1)(ViewInfoOptions, CancellationToken) | Geeft informatie terug over de weergave en document‑specifieke informatie. |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment)(Attachment, Stream) | Slaat bijlagebestand op naar *destination* stream. |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment_1)(Attachment, Stream, CancellationToken) | Slaat bijlagebestand op naar *destination* stream. |
| [Search](../../groupdocs.viewer/viewer/search)(SearchHighlightOptions) | Voert een tekstzoekopdracht uit en markeert (indien gevonden) in het geladen document volgens de geladen opties. |
| [View](../../groupdocs.viewer/viewer/view#view)(ViewOptions) | Maakt een weergave van alle documentpagina's. |
| [View](../../groupdocs.viewer/viewer/view#view_2)(ViewOptions, CancellationToken) | Maakt een weergave van alle documentpagina's. |
| [View](../../groupdocs.viewer/viewer/view#view_1)(ViewOptions, params int[]) | Maakt een weergave van specifieke documentpagina's. |
| [View](../../groupdocs.viewer/viewer/view#view_3)(ViewOptions, CancellationToken, params int[]) | Maakt een weergave van specifieke documentpagina's. |

### Zie ook

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
