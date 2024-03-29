---
title: Line
second_title: Référence de l'API GroupDocs.Viewer pour .NET
description: Initialise la nouvelle instance deLinegroupdocs.viewer.results/line classe.
type: docs
weight: 10
url: /fr/net/groupdocs.viewer.results/line/line/
---
## Line() {#constructor}

Initialise la nouvelle instance de[`Line`](../../line) classe.

```csharp
public Line()
```

### Voir également

* class [Line](../../line)
* espace de noms [GroupDocs.Viewer.Results](../../line)
* Assemblée [GroupDocs.Viewer](../../../)

---

## Line(string, double, double, double, double, List&lt;Word&gt;) {#constructor_1}

Initialise la nouvelle instance de[`Line`](../../line) classe.

```csharp
public Line(string line, double x, double y, double width, double height, List<Word> words)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| line | String | La ligne. |
| x | Double | Coordonnée X du point le plus haut à gauche de la mise en page où commence le rectangle contenant la ligne. |
| y | Double | Coordonnée Y du point le plus haut à gauche de la mise en page où commence le rectangle contenant la ligne. |
| width | Double | La largeur du rectangle qui contient la ligne (en pixels). |
| height | Double | La hauteur du rectangle qui contient la ligne (en pixels). |
| words | List`1 | Les mots contenus par la ligne. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Jeté quand*line* est nul ou vide. |
| ArgumentNullException | Jeté quand*words* est nul. |

### Voir également

* class [Word](../../word)
* class [Line](../../line)
* espace de noms [GroupDocs.Viewer.Results](../../line)
* Assemblée [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
