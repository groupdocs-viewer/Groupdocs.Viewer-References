---
title: "RenderOriginalPageSize"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Définit la taille de la page de sortie identique à celle de la page du document PDF source."
type: docs
weight: 90
url: /fr/net/groupdocs.viewer.options/pdfoptions/renderoriginalpagesize/
---

## PdfOptions.RenderOriginalPageSize property

Définit la taille de page de sortie identique à celle du document PDF source.

```csharp
public bool RenderOriginalPageSize { get; set; }
```

### Remarques

Par défaut, GroupDocs.Viewer calcule la taille de la page d'image de sortie pour une meilleure qualité de rendu. Activez cette option pour garantir que les pages de sortie ont la même taille que la taille de la page du document PDF source (en pixels). La valeur par défaut est `false`.

Cette option est disponible pour le rendu aux formats PNG ou JPG.

Pour un exemple de code, consultez la [documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#preserve-the-size-of-document-pages).

### Voir aussi

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
