---
title: "PresentationOptions"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Contient des options pour le rendu des présentations. Pour plus de détails, voir la documentationhttps//docs.groupdocs.com/viewer/net/renderpresentations/."
type: docs
weight: 460
url: /fr/net/groupdocs.viewer.options/presentationoptions/
---

## PresentationOptions class

Contient des options pour le rendu des présentations. Pour plus de détails, consultez la [documentation](https://docs.groupdocs.com/viewer/net/render-presentations/).

```csharp
public class PresentationOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PresentationOptions](presentationoptions)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [RenderHeaderFooterPlaceholders](../../groupdocs.viewer.options/presentationoptions/renderheaderfooterplaceholders) { get; set; } | Active le rendu des espaces réservés dans l'en-tête et le pied de page d'une diapositive. Désactivé par défaut (`false`). Cette option s'applique aux 4 modes de rendu des présentations : HTML, PDF, PNG et JPEG. Elle n'est pas applicable lors du rendu de la présentation en balisage HTML/CSS pur en utilisant [`RenderToPureHtml`](./rendertopurehtml). |
| [RenderToPureHtml](../../groupdocs.viewer.options/presentationoptions/rendertopurehtml) { get; set; } | Active un nouveau mode de rendu HTML pour les documents de présentation — dans ce mode, les fichiers de présentation sont rendus en **pure HTML/CSS markup**, sans images SVG. Par défaut, il est désactivé (`false`) — le rendu HTML basé sur SVG existant est utilisé. |
| [Resolution](../../groupdocs.viewer.options/presentationoptions/resolution) { get; set; } | Résolution des images de la présentation (pour le rendu en HTML/PDF uniquement). |

### Voir aussi

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
