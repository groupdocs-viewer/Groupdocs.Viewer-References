---
title: "RemoveComments"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Désactive le rendu des commentaires lorsqu'elle est définie sur `true`. Par défaut, c'est `false` et tous les commentaires sont affichés."
type: docs
weight: 100
url: /fr/net/groupdocs.viewer.options/baseviewoptions/removecomments/
---

## BaseViewOptions.RemoveComments property

Désactive le rendu des commentaires lorsqu'il est réglé sur `true`. Par défaut, il est `false` — tous les commentaires sont affichés.

```csharp
public bool RemoveComments { get; set; }
```

### Remarques

Certains formats de document comme PDF et WordProcessing peuvent contenir des commentaires. Par défaut, GroupDocs.Viewer les rend. Avec cette option définie sur `true`, les commentaires peuvent être exclus du document résultant.

Cette option remplace la propriété obsolète 'RenderComments'.

### Voir aussi

* class [BaseViewOptions](../../baseviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
