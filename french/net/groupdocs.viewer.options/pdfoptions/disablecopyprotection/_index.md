---
title: "DisableCopyProtection"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Désactive la protection contre la copie de contenu lors du rendu en HTML."
type: docs
weight: 30
url: /fr/net/groupdocs.viewer.options/pdfoptions/disablecopyprotection/
---

## PdfOptions.DisableCopyProtection property

Désactive la protection contre la copie de contenu lors du rendu en HTML.

```csharp
public bool DisableCopyProtection { get; set; }
```

### Remarques

Lors du rendu de fichiers PDF protégés contre la copie de texte et d’images en HTML, GroupDocs.Viewer ajoute un attribut HTML « inert » à la balise BODY du HTML. La valeur par défaut de cette option est `false`, indiquant que l’attribut HTML « intent » n’est ajouté que si le document PDF est protégé.

Pour un exemple de code, voir la [documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).

### Voir aussi

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
