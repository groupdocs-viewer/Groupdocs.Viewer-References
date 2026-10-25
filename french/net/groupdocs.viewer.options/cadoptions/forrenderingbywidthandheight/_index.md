---
title: "PourRenduParLargeurEtHauteur"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Initialise une instance de la classe CadOptionsgroupdocs.viewer.options/cadoptions pour le rendu par largeur et hauteur."
type: docs
weight: 40
url: /fr/net/groupdocs.viewer.options/cadoptions/forrenderingbywidthandheight/
---

## CadOptions.ForRenderingByWidthAndHeight method

Initialise une instance de la classe [`CadOptions`](../../cadoptions) pour le rendu par largeur et hauteur.

```csharp
public static CadOptions ForRenderingByWidthAndHeight(int width, int height)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| largeur | Int32 | La largeur du résultat de sortie (en pixels). |
| hauteur | Int32 | La hauteur du résultat de sortie (en pixels). |

### Valeur de retour

Nouvelle instance de la classe [`CadOptions`](../../cadoptions) pour le rendu par largeur et hauteur.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque *largeur* est inférieure ou égale à zéro. |
| ArgumentException | Lancée lorsque *hauteur* est inférieure ou égale à zéro. |

### Remarques

Pour un exemple de code, consultez la [documentation](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#configure-the-output-image-size).

### Voir aussi

* class [CadOptions](../../cadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
