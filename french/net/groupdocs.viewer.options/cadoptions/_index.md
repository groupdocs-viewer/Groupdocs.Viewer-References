---
title: CadOptions
second_title: Référence de l'API GroupDocs.Viewer pour .NET
description: Fournit des options pour le rendu des dessins CAO.
type: docs
weight: 290
url: /fr/net/groupdocs.viewer.options/cadoptions/
---
## CadOptions class

Fournit des options pour le rendu des dessins CAO.

```csharp
public class CadOptions
```

## Propriétés

| Nom | La description |
| --- | --- |
| [BackgroundColor](../../groupdocs.viewer.options/cadoptions/backgroundcolor) { get; set; } | Couleur de fond de l'image |
| [Height](../../groupdocs.viewer.options/cadoptions/height) { get; } | La hauteur du résultat de sortie en pixels. |
| [Layers](../../groupdocs.viewer.options/cadoptions/layers) { get; set; } | Les calques de dessin CAO à rendre. |
| [LayoutName](../../groupdocs.viewer.options/cadoptions/layoutname) { get; set; } | Le nom de la mise en page spécifique à rendre. Le nom de la mise en page est sensible à la casse. |
| [Pc3File](../../groupdocs.viewer.options/cadoptions/pc3file) { get; set; } | PC3 - fichier de configuration du traceur |
| [RenderLayouts](../../groupdocs.viewer.options/cadoptions/renderlayouts) { get; set; } | Indique si les mises en page du document CAO doivent être rendues. |
| [ScaleFactor](../../groupdocs.viewer.options/cadoptions/scalefactor) { get; } | Les valeurs supérieures à 1 agrandiront le résultat de sortie ; les valeurs entre 0 et 1 rendront le résultat de sortie plus petit. |
| [Tiles](../../groupdocs.viewer.options/cadoptions/tiles) { get; set; } | Les régions de dessin à rendre. |
| [Width](../../groupdocs.viewer.options/cadoptions/width) { get; } | La largeur du résultat de sortie en pixels. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [ForRenderingByHeight](../../groupdocs.viewer.options/cadoptions/forrenderingbyheight)(int) | Initialise la nouvelle instance de[`CadOptions`](../cadoptions) classe pour le rendu par hauteur. |
| static [ForRenderingByScaleFactor](../../groupdocs.viewer.options/cadoptions/forrenderingbyscalefactor)(float) | Initialise la nouvelle instance de[`CadOptions`](../cadoptions) classe pour le rendu par facteur d'échelle. |
| static [ForRenderingByWidth](../../groupdocs.viewer.options/cadoptions/forrenderingbywidth)(int) | Initialise la nouvelle instance de[`CadOptions`](../cadoptions) classe pour le rendu par largeur. |
| static [ForRenderingByWidthAndHeight](../../groupdocs.viewer.options/cadoptions/forrenderingbywidthandheight)(int, int) | Initialise la nouvelle instance de[`CadOptions`](../cadoptions) classe pour le rendu par largeur et hauteur. |

### Voir également

* espace de noms [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* Assemblée [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->