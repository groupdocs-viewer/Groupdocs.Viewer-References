---
title: "ForRenderingByScaleFactor"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Initialise une instance de la classe CadOptionsgroupdocs.viewer.options/cadoptions pour le rendu par facteur d'échelle."
type: docs
weight: 20
url: /fr/net/groupdocs.viewer.options/cadoptions/forrenderingbyscalefactor/
---

## CadOptions.ForRenderingByScaleFactor method

Initialise une instance de la classe [`CadOptions`](../../cadoptions) pour le rendu par facteur d'échelle.

```csharp
public static CadOptions ForRenderingByScaleFactor(float scaleFactor)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| scaleFactor | Simple | Une valeur supérieure à 1 agrandit le résultat de sortie ; une valeur comprise entre 0 et 1 réduit le résultat de sortie. |

### Valeur de retour

Nouvelle instance de la classe [`CadOptions`](../../cadoptions) pour le rendu par facteur d'échelle.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque *scaleFactor* est inférieur ou égal à zéro. |

### Remarques

Pour un exemple de code, consultez la [documentation](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#configure-the-output-image-size).

### Voir aussi

* class [CadOptions](../../cadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
