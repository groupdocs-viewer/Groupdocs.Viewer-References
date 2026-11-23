---
title: "TextElement"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Inicializa una nueva instancia de la clase TextElementgroupdocs.viewer.results/textelement1."
type: docs
weight: 10
url: /es/net/groupdocs.viewer.results/textelement-1/textelement/
---

## TextElement() {#constructor}

Inicializa una nueva instancia de la clase [`TextElement`](../../textelement-1).

```csharp
public TextElement()
```

### Ver también

* class [TextElement&lt;T&gt;](../../textelement-1)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## TextElement(T, double, double, double, double) {#constructor_1}

Inicializa una nueva instancia de la clase [`TextElement`](../../textelement-1).

```csharp
public TextElement(T value, double x, double y, double width, double height)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| value | T | El valor del elemento de texto. |
| x | Double | La coordenada X del punto superior izquierdo en el diseño de página donde comienza el rectángulo que contiene el elemento. |
| y | Double | La coordenada Y del punto superior izquierdo en el diseño de página donde comienza el rectángulo que contiene el elemento. |
| width | Double | El ancho del rectángulo que contiene el elemento (en píxeles). |
| height | Double | La altura del rectángulo que contiene el elemento (en píxeles). |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzado cuando *value* es nulo. |
| ArgumentException | Se lanza cuando *width* es menor o igual a cero. |
| ArgumentException | Se lanza cuando *height* es menor o igual a cero. |

### Ver también

* class [TextElement&lt;T&gt;](../../textelement-1)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
