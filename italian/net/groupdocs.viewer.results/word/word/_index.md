---
title: Word
second_title: Riferimento API GroupDocs.Viewer per .NET
description: Inizializza una nuova istanza diWordgroupdocs.viewer.results/word classe.
type: docs
weight: 10
url: /it/net/groupdocs.viewer.results/word/word/
---
## Word() {#constructor}

Inizializza una nuova istanza di[`Word`](../../word) classe.

```csharp
public Word()
```

### Guarda anche

* class [Word](../../word)
* spazio dei nomi [GroupDocs.Viewer.Results](../../word)
* assemblea [GroupDocs.Viewer](../../../)

---

## Word(string, double, double, double, double, List&lt;Character&gt;) {#constructor_1}

Inizializza una nuova istanza di[`Word`](../../word) classe.

```csharp
public Word(string word, double x, double y, double width, double height, 
    List<Character> characters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| word | String | La parola. |
| x | Double | La coordinata X del punto più alto a sinistra del layout di pagina in cui inizia il rettangolo che contiene la parola. |
| y | Double | La coordinata Y del punto in alto a sinistra del layout di pagina in cui inizia il rettangolo che contiene la parola. |
| width | Double | La larghezza del rettangolo che contiene la parola. |
| height | Double | L'altezza del rettangolo che contiene la parola. |
| characters | List`1 | caratteri contenuti dalla parola. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Lanciato quando*word* è nullo o vuoto. |
| ArgumentNullException | Lanciato quando*characters* è zero. |

### Guarda anche

* class [Character](../../character)
* class [Word](../../word)
* spazio dei nomi [GroupDocs.Viewer.Results](../../word)
* assemblea [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
