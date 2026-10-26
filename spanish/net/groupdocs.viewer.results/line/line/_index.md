---
title: "Line"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Inicializa una nueva instancia de la clase Linegroupdocs.viewer.results/line."
type: docs
weight: 10
url: /es/net/groupdocs.viewer.results/line/line/
---

## Line() {#constructor}

Inicializa una nueva instancia de la clase [`Line`](../../line).

```csharp
public Line()
```

### Ver también

* class [Line](../../line)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Line(string, double, double, double, double, List&lt;Word&gt;) {#constructor_1}

Inicializa una nueva instancia de la clase [`Line`](../../line).

```csharp
public Line(string line, double x, double y, double width, double height, List<Word> words)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| línea | String | La línea. |
| x | Double | La coordenada X del punto superior izquierdo en el diseño de página donde comienza el rectángulo que contiene la línea. |
| y | Double | La coordenada Y del punto superior izquierdo en el diseño de página donde comienza el rectángulo que contiene la línea. |
| width | Double | El ancho del rectángulo que contiene la línea (en píxeles). |
| height | Double | La altura del rectángulo que contiene la línea (en píxeles). |
| palabras | List`1 | Las palabras contenidas por la línea. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Lanzado cuando *line* es nulo o está vacío. |
| ArgumentNullException | Lanzado cuando *words* es nulo. |

### Ver también

* class [Word](../../word)
* class [Line](../../line)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
