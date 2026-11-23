---
title: "Line"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Initialise une nouvelle instance de la classe Linegroupdocs.viewer.results/line."
type: docs
weight: 10
url: /fr/net/groupdocs.viewer.results/line/line/
---

## Line() {#constructor}

Initialise une nouvelle instance de la classe [`Line`](../../line).

```csharp
public Line()
```

### Voir aussi

* class [Line](../../line)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Line(string, double, double, double, double, List&lt;Word&gt;) {#constructor_1}

Initialise une nouvelle instance de la classe [`Line`](../../line).

```csharp
public Line(string line, double x, double y, double width, double height, List<Word> words)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| ligne | String | La ligne. |
| x | Double | La coordonnée X du point le plus haut à gauche de la mise en page où commence le rectangle qui contient la ligne. |
| y | Double | La coordonnée Y du point le plus haut à gauche de la mise en page où commence le rectangle qui contient la ligne. |
| largeur | Double | La largeur du rectangle qui contient la ligne (en pixels). |
| hauteur | Double | La hauteur du rectangle qui contient la ligne (en pixels). |
| mots | List`1 | Les mots contenus par la ligne. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque *line* est nul ou vide. |
| ArgumentNullException | Lancée lorsque *words* est nul. |

### Voir aussi

* class [Word](../../word)
* class [Line](../../line)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
