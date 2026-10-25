---
title: "FontsToExclude"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "La liste des noms de polices à exclure du document HTML."
type: docs
weight: 40
url: /fr/net/groupdocs.viewer.options/htmlviewoptions/fontstoexclude/
---

## HtmlViewOptions.FontsToExclude property

La liste des noms de polices à exclure du document HTML.

```csharp
public List<string> FontsToExclude { get; set; }
```

### Remarques

Les polices ajoutées au document HTML améliorent la stabilité de la vue de sortie, tout en augmentant la taille du résultat du rendu. Cette option vous permet d’équilibrer stabilité et taille de la sortie. Incluez les noms de polices qui sont populaires et installés sur la plupart des systèmes.

Veuillez noter que cette propriété n’est active que lorsque l’option [`ExcludeFonts`](../excludefonts) est désactivée.

Pour plus de détails et un exemple de code, consultez la [documentation](https://docs.groupdocs.com/viewer/net/exclude-fonts/).

### Voir aussi

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
