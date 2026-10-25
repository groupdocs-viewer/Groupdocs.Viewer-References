---
title: "PdfOptions"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Contient des options pour le rendu de documents PDF. Pour plus de détails, consultez la documentationhttps//docs.groupdocs.com/viewer/net/renderpdfdocuments/."
type: docs
weight: 410
url: /fr/net/groupdocs.viewer.options/pdfoptions/
---

## PdfOptions class

Contient des options pour le rendu vers des documents PDF. Pour plus de détails, consultez la [documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/).

```csharp
public class PdfOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfOptions](pdfoptions)() | Initialise une nouvelle instance de la classe [`PdfOptions`](../pdfoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [DisableCharsGrouping](../../groupdocs.viewer.options/pdfoptions/disablecharsgrouping) { get; set; } | Désactive le regroupement des symboles pour un positionnement précis des symboles lors du rendu de la page. |
| [DisableCopyProtection](../../groupdocs.viewer.options/pdfoptions/disablecopyprotection) { get; set; } | Désactive la protection contre la copie de contenu lors du rendu en HTML. |
| [DisableFontLicenseVerifications](../../groupdocs.viewer.options/pdfoptions/disablefontlicenseverifications) { get; set; } | Désactive toutes les restrictions de licence pour toutes les polices dans le document XPS/OXPS actuel. |
| [EnableFontHinting](../../groupdocs.viewer.options/pdfoptions/enablefonthinting) { get; set; } | Active le hinting des polices. |
| [EnableLayeredRendering](../../groupdocs.viewer.options/pdfoptions/enablelayeredrendering) { get; set; } | Active le rendu du texte et des graphiques dans l'ordre Z du document PDF original lors du rendu en HTML. |
| [FixedLayout](../../groupdocs.viewer.options/pdfoptions/fixedlayout) { get; set; } | Active le rendu des documents PDF et EPUB en HTML avec une mise en page fixe. |
| [ImageQuality](../../groupdocs.viewer.options/pdfoptions/imagequality) { get; set; } | Définit la qualité d'image de sortie pour les ressources d'image lors du rendu en HTML. La qualité par défaut est `Low`. |
| [RenderOriginalPageSize](../../groupdocs.viewer.options/pdfoptions/renderoriginalpagesize) { get; set; } | Définit la taille de page de sortie identique à celle du document PDF source. |
| [RenderTextAsImage](../../groupdocs.viewer.options/pdfoptions/rendertextasimage) { get; set; } | Active le rendu du texte des fichiers PDF sous forme d'image dans la sortie HTML. |
| [WrapImagesInSvg](../../groupdocs.viewer.options/pdfoptions/wrapimagesinsvg) { get; set; } | Active l'encapsulation de chaque image dans la sortie HTML dans une balise SVG pour améliorer la qualité de sortie. |

### Voir aussi

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
