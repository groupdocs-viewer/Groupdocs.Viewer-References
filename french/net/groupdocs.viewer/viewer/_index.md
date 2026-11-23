---
title: "Visionneuse"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Représente la classe principale qui contrôle le processus de rendu du document."
type: docs
weight: 50
url: /fr/net/groupdocs.viewer/viewer/
---

## Viewer class

Représente la classe principale qui contrôle le processus de rendu du document.

```csharp
public class Viewer : IDisposable
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Viewer](viewer#constructor)(Func&lt;Stream&gt;) | Initialise une nouvelle instance de la classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_4)(Stream) | Initialise une nouvelle instance de la classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_12)(string) | Initialise une nouvelle instance de la classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_2)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | Initialise une nouvelle instance de la classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_1)(Func&lt;Stream&gt;, ViewerSettings) | Initialise une nouvelle instance de la classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_5)(Stream, bool) | Initialise une nouvelle instance de la classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_6)(Stream, LoadOptions) | Initialise une nouvelle instance de la classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_10)(Stream, ViewerSettings) | Initialise une nouvelle instance de la classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_13)(string, LoadOptions) | Initialise une nouvelle instance de la classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_15)(string, ViewerSettings) | Initialise une nouvelle instance de la classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) | Initialise une nouvelle instance de la classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_7)(Stream, LoadOptions, bool) | Initialise une nouvelle instance de la classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_8)(Stream, LoadOptions, ViewerSettings) | Initialise une nouvelle instance de la classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_11)(Stream, ViewerSettings, bool) | Initialise une nouvelle instance de la classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_14)(string, LoadOptions, ViewerSettings) | Initialise une nouvelle instance de la classe [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_9)(Stream, LoadOptions, ViewerSettings, bool) | Initialise une nouvelle instance de la classe [`Viewer`](../viewer). |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../groupdocs.viewer/viewer/dispose)() | Libère le flux de fichier et les ressources internes gérées. |
| [GetAllFonts](../../groupdocs.viewer/viewer/getallfonts)() | Renvoie toutes les polices utilisées dans les documents chargés, y compris celles qui sont intégrées dans le document lui‑même et les polices système installées dans le système d'exploitation et utilisées dans le document. |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments)() | Renvoie les pièces jointes contenues dans le document. |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments_1)(CancellationToken) | Renvoie les pièces jointes contenues dans le document. |
| [GetFileInfo](../../groupdocs.viewer/viewer/getfileinfo)() | Renvoie des informations sur le fichier, telles que le type de fichier et le drapeau indiquant si le fichier est chiffré. |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo)(ViewInfoOptions) | Renvoie des informations sur la vue et des informations spécifiques au document. |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo_1)(ViewInfoOptions, CancellationToken) | Renvoie des informations sur la vue et des informations spécifiques au document. |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment)(Attachment, Stream) | Enregistre le fichier de pièce jointe dans le flux *destination*. |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment_1)(Attachment, Stream, CancellationToken) | Enregistre le fichier de pièce jointe dans le flux *destination*. |
| [Search](../../groupdocs.viewer/viewer/search)(SearchHighlightOptions) | Effectue une recherche de texte et son surlignage (si trouvé) dans le document chargé selon les options chargées. |
| [View](../../groupdocs.viewer/viewer/view#view)(ViewOptions) | Crée une vue de toutes les pages du document. |
| [View](../../groupdocs.viewer/viewer/view#view_2)(ViewOptions, CancellationToken) | Crée une vue de toutes les pages du document. |
| [View](../../groupdocs.viewer/viewer/view#view_1)(ViewOptions, params int[]) | Crée une vue de pages spécifiques du document. |
| [View](../../groupdocs.viewer/viewer/view#view_3)(ViewOptions, CancellationToken, params int[]) | Crée une vue de pages spécifiques du document. |

### Voir aussi

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
