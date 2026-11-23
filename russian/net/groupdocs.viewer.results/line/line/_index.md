---
title: "Line"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инициализирует новый экземпляр класса Linegroupdocs.viewer.results/line."
type: docs
weight: 10
url: /ru/net/groupdocs.viewer.results/line/line/
---

## Line() {#constructor}

Инициализирует новый экземпляр класса [`Line`](../../line).

```csharp
public Line()
```

### См. также

* class [Line](../../line)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Line(string, double, double, double, double, List&lt;Word&gt;) {#constructor_1}

Инициализирует новый экземпляр класса [`Line`](../../line).

```csharp
public Line(string line, double x, double y, double width, double height, List<Word> words)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| строка | String | Эта строка. |
| x | Double | Координата X самой верхней левой точки в макете страницы, где начинается прямоугольник, содержащий line. |
| y | Double | Координата Y самой верхней левой точки в макете страницы, где начинается прямоугольник, содержащий line. |
| width | Double | Ширина прямоугольника, содержащего line (в пикселях). |
| height | Double | Высота прямоугольника, содержащего line (в пикселях). |
| слова | List`1 | Слова, содержащиеся в строке. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *line* равно null или пустой. |
| ArgumentNullException | Выбрасывается, когда *words* равно null. |

### См. также

* class [Word](../../word)
* class [Line](../../line)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
