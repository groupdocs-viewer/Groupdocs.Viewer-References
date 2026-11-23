---
title: "WrapImagesInSvg"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Active l'encapsulation de chaque image dans la sortie HTML dans une balise SVG pour améliorer la qualité de sortie."
type: docs
weight: 110
url: /fr/net/groupdocs.viewer.options/pdfoptions/wrapimagesinsvg/
---

## PdfOptions.WrapImagesInSvg property

Active l'encapsulation de chaque image dans la sortie HTML dans une balise SVG pour améliorer la qualité de sortie.

```csharp
public bool WrapImagesInSvg { get; set; }
```

### Remarques

Par défaut, lors du rendu de fichiers PDF et de mise en page en HTML, toutes les images sont rendues sous forme d'une seule image PNG. L'image PNG rendue est utilisée comme arrière-plan du document HTML de sortie.

Cette option est disponible lors du rendu des [formats de fichiers PDF et de mise en page](https://docs.groupdocs.com/viewer/net/supported-document-formats/#pdf-and-page-layout-file-formats) en HTML avec des ressources intégrées et externes. Elle permet d'encapsuler chaque image du document HTML de sortie dans une balise SVG. La valeur par défaut est `false`.

Pour un exemple de code, consultez la [documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#enclose-images-in-svg-when-rendering-pdf-and-page-layout-files).

### Voir aussi

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
