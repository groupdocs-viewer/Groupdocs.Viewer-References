---
title: "Word"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Initialise une nouvelle instance de la classe Wordgroupdocs.viewer.results/word."
type: docs
weight: 10
url: /fr/net/groupdocs.viewer.results/word/word/
---

## Word() {#constructor}

Initialise une nouvelle instance de la classe [`Word`](../../word).

```csharp
public Word()
```

### Voir aussi

* class [Word](../../word)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Word(string, double, double, double, double, List&lt;Character&gt;) {#constructor_1}

Initialise une nouvelle instance de la classe [`Word`](../../word).

```csharp
public Word(string word, double x, double y, double width, double height, 
    List<Character> characters)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| mot | String | Le mot. |
| x | Double | La coordonnée X du point le plus haut à gauche de la mise en page où commence le rectangle contenant le mot. |
| y | Double | La coordonnée Y du point le plus haut à gauche de la mise en page où commence le rectangle contenant le mot. |
| largeur | Double | La largeur du rectangle qui contient le mot. |
| hauteur | Double | La hauteur du rectangle qui contient le mot. |
| caractères | List`1 | Les caractères contenus par le mot. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancé lorsque *word* est nul ou vide. |
| ArgumentNullException | Lancé lorsque *characters* est nul. |

### Voir aussi

* class [Character](../../character)
* class [Word](../../word)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
