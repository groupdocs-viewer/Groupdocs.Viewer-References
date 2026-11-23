---
title: "RenderNotes"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Active le rendu des notes et des annotations pour certains formats."
type: docs
weight: 120
url: /fr/net/groupdocs.viewer.options/baseviewoptions/rendernotes/
---

## BaseViewOptions.RenderNotes property

Active le rendu des notes et des annotations pour certains formats.

```csharp
public bool RenderNotes { get; set; }
```

### Remarques

Certains formats, tels que les présentations ou les fichiers Microsoft Project, peuvent contenir des notes. De plus, les fichiers PDF peuvent comporter des annotations contextuelles (infobulles), qui sont masquées par défaut et ne sont visibles dans un lecteur PDF que lorsque le curseur de la souris les survole. Par défaut, GroupDocs.Viewer ne rend pas ces notes et annotations (`false`). Pour ce faire, définissez cette propriété sur `true`.

Pour un exemple de code, consultez la [documentation](https://docs.groupdocs.com/viewer/net/render-presentations/#render-speaker-notes).

### Voir aussi

* class [BaseViewOptions](../../baseviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
