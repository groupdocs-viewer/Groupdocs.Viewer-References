---
title: "TextOverflowMode"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Définit le mode de dépassement de texte pour le rendu des documents de feuille de calcul en HTML."
type: docs
weight: 550
url: /fr/net/groupdocs.viewer.options/textoverflowmode/
---

## TextOverflowMode enumeration

Définit le mode de dépassement de texte pour le rendu des documents de feuille de calcul en HTML.

```csharp
public enum TextOverflowMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Overlay | `0` | Superposer les cellules suivantes même si elles ne sont pas vides. |
| OverlayIfNextIsEmpty | `1` | Superposer les cellules suivantes uniquement si elles sont vides. Valeur par défaut. |
| AutoFitColumn | `2` | Étendre les colonnes pour ajuster le texte. |
| HideText | `3` | Masquer le texte débordant. |

### Remarques

Pour plus de détails, consultez la [documentation](https://docs.groupdocs.com/viewer/net/specify-rendering-options/#control-cell-text-overflow).

### Voir aussi

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
