---
title: "CadOptions"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Contient des options pour le rendu des dessins CAD. Pour plus d'informations et des exemples de code, consultez le rendu des dessins CAD et des modèles en fichiers HTML, PDF et imagehttps//docs.groupdocs.com/viewer/net/rendercaddrawingsandmodels/ et spécifiez les options de rendu pour les fichiers CADhttps//docs.groupdocs.com/viewer/net/specifycadrenderingoptions/."
type: docs
weight: 280
url: /fr/net/groupdocs.viewer.options/cadoptions/
---

## CadOptions class

Contient des options pour le rendu des dessins CAD. Pour plus d'informations et des exemples de code, consultez le [Render CAD drawings and models as HTML, PDF, and image files](https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) et le [Specify rendering options for CAD files](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/).

```csharp
public class CadOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [BackgroundColor](../../groupdocs.viewer.options/cadoptions/backgroundcolor) { get; set; } | Couleur d'arrière-plan de l'image. |
| [EnablePerformanceConversionMode](../../groupdocs.viewer.options/cadoptions/enableperformanceconversionmode) { get; set; } | Activer ce drapeau à `true` active un mode de conversion spécial axé sur les performances pour tous les formats de la famille CAD — dans ce mode, la vitesse de conversion est beaucoup plus rapide, mais la qualité des documents résultants est nettement pire. Par défaut, il est désactivé (`false`) — la qualité des documents résultants est la meilleure possible au détriment des performances. |
| [Height](../../groupdocs.viewer.options/cadoptions/height) { get; } | La hauteur du résultat de sortie (en pixels). |
| [Layers](../../groupdocs.viewer.options/cadoptions/layers) { get; set; } | Les calques du dessin CAD à rendre. |
| [LayoutName](../../groupdocs.viewer.options/cadoptions/layoutname) { get; set; } | Le nom de la mise en page spécifique à rendre. Le nom de la mise en page est sensible à la casse. |
| [Pc3File](../../groupdocs.viewer.options/cadoptions/pc3file) { get; set; } | PC3 - fichier de configuration du traceur |
| [RenderLayouts](../../groupdocs.viewer.options/cadoptions/renderlayouts) { get; set; } | Indique si les mises en page du document CAD doivent être rendues. |
| [ScaleFactor](../../groupdocs.viewer.options/cadoptions/scalefactor) { get; } | Une valeur supérieure à 1 agrandit le résultat de sortie ; une valeur comprise entre 0 et 1 réduit le résultat de sortie. |
| [Tiles](../../groupdocs.viewer.options/cadoptions/tiles) { get; set; } | Les régions de dessin à rendre. |
| [Width](../../groupdocs.viewer.options/cadoptions/width) { get; } | La largeur du résultat de sortie (en pixels). |

## Méthodes

| Nom | Description |
| --- | --- |
| static [ForRenderingByHeight](../../groupdocs.viewer.options/cadoptions/forrenderingbyheight)(int) | Initialise une instance de la classe [`CadOptions`](../cadoptions) pour le rendu par hauteur. |
| static [ForRenderingByScaleFactor](../../groupdocs.viewer.options/cadoptions/forrenderingbyscalefactor)(float) | Initialise une instance de la classe [`CadOptions`](../cadoptions) pour le rendu par facteur d'échelle. |
| static [ForRenderingByWidth](../../groupdocs.viewer.options/cadoptions/forrenderingbywidth)(int) | Initialise une instance de la classe [`CadOptions`](../cadoptions) pour le rendu par largeur. |
| static [ForRenderingByWidthAndHeight](../../groupdocs.viewer.options/cadoptions/forrenderingbywidthandheight)(int, int) | Initialise une instance de la classe [`CadOptions`](../cadoptions) pour le rendu par largeur et hauteur. |

### Voir aussi

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
