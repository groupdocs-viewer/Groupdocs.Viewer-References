---
title: "MaxItemsInFolder"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Le nombre maximal de messages ou d'éléments pouvant être rendus à partir d'un dossier."
type: docs
weight: 40
url: /fr/net/groupdocs.viewer.options/outlookoptions/maxitemsinfolder/
---

## OutlookOptions.MaxItemsInFolder property

Le nombre maximal de messages ou d'éléments pouvant être rendus à partir d'un dossier.

```csharp
public int MaxItemsInFolder { get; set; }
```

### Remarques

Les fichiers de données Outlook peuvent être volumineux et la récupération de tous les messages peut prendre un temps considérable. Cette propriété limite le nombre maximal de messages ou d'éléments rendus. La valeur par défaut est `50`. Pour rendre tous les messages, définissez la valeur à `0`.

Pour un exemple de code, consultez la [documentation](https://docs.groupdocs.com/viewer/net/render-outlook-data-files/#limit-the-number-of-folder-items-to-render).

### Voir aussi

* class [OutlookOptions](../../outlookoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
