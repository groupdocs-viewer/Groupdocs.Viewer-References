---
title: "Word"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Inicializa una nueva instancia de la clase Wordgroupdocs.viewer.results/word."
type: docs
weight: 10
url: /es/net/groupdocs.viewer.results/word/word/
---

## Word() {#constructor}

Inicializa una nueva instancia de la clase [`Word`](../../word).

```csharp
public Word()
```

### Ver también

* class [Word](../../word)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Word(string, double, double, double, double, List&lt;Character&gt;) {#constructor_1}

Inicializa una nueva instancia de la clase [`Word`](../../word).

```csharp
public Word(string word, double x, double y, double width, double height, 
    List<Character> characters)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| palabra | String | La palabra. |
| x | Double | La coordenada X del punto superior izquierdo en el diseño de página donde comienza el rectángulo que contiene la palabra. |
| y | Double | La coordenada Y del punto superior izquierdo en el diseño de página donde comienza el rectángulo que contiene la palabra. |
| width | Double | El ancho del rectángulo que contiene la palabra. |
| height | Double | La altura del rectángulo que contiene la palabra. |
| caracteres | List`1 | Los caracteres contenidos por la palabra. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando *word* es nulo o está vacío. |
| ArgumentNullException | Se lanza cuando *characters* es nulo. |

### Ver también

* class [Character](../../character)
* class [Word](../../word)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
