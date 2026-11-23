---
title: "DisableCharsGrouping"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Désactive le regroupement des symboles pour un positionnement précis des symboles lors du rendu de la page."
type: docs
weight: 20
url: /fr/net/groupdocs.viewer.options/pdfoptions/disablecharsgrouping/
---

## PdfOptions.DisableCharsGrouping property

Désactive le regroupement des symboles pour un positionnement précis des symboles lors du rendu de la page.

```csharp
public bool DisableCharsGrouping { get; set; }
```

### Remarques

Lors de la conversion de fichiers PDF, GroupDocs.Viewer regroupe les caractères individuels en mots pour améliorer les performances de rendu. Si votre document comprend des hiéroglyphes ou des symboles spéciaux, vous pourriez souhaiter interdire le regroupement des caractères afin d’assurer une mise en page plus précise. La valeur par défaut est `false`.

Pour un exemple de code, voir la [documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-character-grouping).

### Voir aussi

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
