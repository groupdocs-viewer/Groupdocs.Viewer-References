---
title: "TextElement"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инициализирует новый экземпляр класса TextElementgroupdocs.viewer.results/textelement1."
type: docs
weight: 10
url: /ru/net/groupdocs.viewer.results/textelement-1/textelement/
---

## TextElement() {#constructor}

Инициализирует новый экземпляр класса [`TextElement`](../../textelement-1).

```csharp
public TextElement()
```

### См. также

* class [TextElement&lt;T&gt;](../../textelement-1)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## TextElement(T, double, double, double, double) {#constructor_1}

Инициализирует новый экземпляр класса [`TextElement`](../../textelement-1).

```csharp
public TextElement(T value, double x, double y, double width, double height)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| value | T | Значение текстового элемента. |
| x | Double | Координата X самой левой верхней точки на макете страницы, где начинается прямоугольник, содержащий элемент. |
| y | Double | Координата Y самой левой верхней точки на макете страницы, где начинается прямоугольник, содержащий элемент. |
| width | Double | Ширина прямоугольника, содержащего элемент (в пикселях). |
| height | Double | Высота прямоугольника, содержащего элемент (в пикселях). |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *value* равно null. |
| ArgumentException | Выбрасывается, когда *width* меньше или равен нулю. |
| ArgumentException | Выбрасывается, когда *height* меньше или равен нулю. |

### См. также

* class [TextElement&lt;T&gt;](../../textelement-1)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
