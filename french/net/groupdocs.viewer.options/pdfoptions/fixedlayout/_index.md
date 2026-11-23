---
title: "FixedLayout"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Active le rendu des documents PDF et EPUB en HTML avec une mise en page fixe."
type: docs
weight: 70
url: /fr/net/groupdocs.viewer.options/pdfoptions/fixedlayout/
---

## PdfOptions.FixedLayout property

Active le rendu des documents PDF et EPUB en HTML avec une mise en page fixe.

```csharp
public bool FixedLayout { get; set; }
```

### Remarques

Les documents PDF et EPUB sont initialement rendus en HTML avec une mise en page fixe afin de conserver l’apparence du document source. Cette mise en page fixe signifie que tous les éléments HTML ont des positions précises à l’intérieur d’un conteneur de taille définie. Redimensionner la fenêtre du navigateur n’affecte pas la position et la taille des éléments du document.

Cette option n’est disponible que lors du rendu en HTML. La valeur par défaut est `true`. Pour rendre avec une mise en page fluide, définissez cette propriété sur `false`.

Lors du rendu avec une mise en page fluide, les images sont ignorées. Utilisez la mise en page fluide lors du rendu de documents PDF contenant du texte.

Pour un exemple de code, voir la [documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#create-html-with-fluid-layout).

### Voir aussi

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
