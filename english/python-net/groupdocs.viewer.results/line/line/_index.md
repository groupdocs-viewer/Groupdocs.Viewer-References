---
title: Line
second_title: GroupDocs.Viewer for Python via .NET API Reference
description: Initializes new instance of Linegroupdocs.viewer.results/line class.
type: docs
weight: 10
url: /python-net/groupdocs.viewer.results/line/line/
---
## Line() {#constructor}

Initializes new instance of [`Line`](../../line) class.

```csharp
public Line()
```

### See Also

* class [Line](../../line)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Line(string, double, double, double, double, List&lt;Word&gt;) {#constructor_1}

Initializes new instance of [`Line`](../../line) class.

```csharp
public Line(string line, double x, double y, double width, double height, List<Word> words)
```

| Parameter | Type | Description |
| --- | --- | --- |
| line | String | The line. |
| x | Double | The X coordinate of the highest left point on the page layout where the rectangle that contains line begins. |
| y | Double | The Y coordinate of the highest left point on the page layout where the rectangle that contains line begins. |
| width | Double | The width of the rectangle which contains the line (in pixels). |
| height | Double | The height of the rectangle which contains the line (in pixels). |
| words | List`1 | The words contained by the line. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when *line* is null or empty. |
| ArgumentNullException | Thrown when *words* is null. |

### See Also

* class [Word](../../word)
* class [Line](../../line)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.viewer.dll -->