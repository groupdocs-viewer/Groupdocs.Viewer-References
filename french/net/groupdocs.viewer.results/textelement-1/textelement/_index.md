---
title: "TextElement"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Initialise une nouvelle instance de TextElementgroupdocs.viewer.results/textelement1 classe."
type: docs
weight: 10
url: /fr/net/groupdocs.viewer.results/textelement-1/textelement/
---

## TextElement() {#constructor}

Initialise une nouvelle instance de [`TextElement`](../../textelement-1) classe.

```csharp
public TextElement()
```

### Voir aussi

* class [TextElement&lt;T&gt;](../../textelement-1)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## TextElement(T, double, double, double, double) {#constructor_1}

Initialise une nouvelle instance de [`TextElement`](../../textelement-1) classe.

```csharp
public TextElement(T value, double x, double y, double width, double height)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| value | T | La valeur de l'élément texte. |
| x | Double | La coordonnée X du point le plus à gauche et le plus haut de la mise en page où commence le rectangle qui contient l'élément. |
| y | Double | La coordonnée Y du point le plus à gauche et le plus haut de la mise en page où commence le rectangle qui contient l'élément. |
| largeur | Double | La largeur du rectangle qui contient l'élément (en pixels). |
| hauteur | Double | La hauteur du rectangle qui contient l'élément (en pixels). |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancé lorsque *value* est nul. |
| ArgumentException | Lancée lorsque *largeur* est inférieure ou égale à zéro. |
| ArgumentException | Lancée lorsque *hauteur* est inférieure ou égale à zéro. |

### Voir aussi

* class [TextElement&lt;T&gt;](../../textelement-1)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
