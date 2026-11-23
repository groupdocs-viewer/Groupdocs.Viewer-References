---
title: "Permissions"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Définit les autorisations du document PDF."
type: docs
weight: 430
url: /fr/net/groupdocs.viewer.options/permissions/
---

## Permissions enumeration

Définit les autorisations du document PDF.

```csharp
[Flags]
public enum Permissions
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| AllowAll | `0` | Autoriser l'impression, la modification et l'extraction de données. |
| DenyPrinting | `1` | Interdire l'impression. |
| DenyModification | `2` | Interdire la modification du contenu, le remplissage des formulaires, l'ajout ou la modification d'annotations. |
| DenyDataExtraction | `4` | Interdire l'extraction de texte et de graphiques. |
| DenyAll | `7` | Interdire l'impression, la modification du contenu et l'extraction de données. |

### Voir aussi

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
