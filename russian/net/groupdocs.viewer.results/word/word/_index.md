---
title: "Word"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инициализирует новый экземпляр класса Wordgroupdocs.viewer.results/word."
type: docs
weight: 10
url: /ru/net/groupdocs.viewer.results/word/word/
---

## Word() {#constructor}

Инициализирует новый экземпляр класса [`Word`](../../word).

```csharp
public Word()
```

### См. также

* class [Word](../../word)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Word(string, double, double, double, double, List&lt;Character&gt;) {#constructor_1}

Инициализирует новый экземпляр класса [`Word`](../../word).

```csharp
public Word(string word, double x, double y, double width, double height, 
    List<Character> characters)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| слово | String | Слово. |
| x | Double | Координата X самой верхней левой точки на макете страницы, где начинается прямоугольник, содержащий слово. |
| y | Double | Координата Y самой верхней левой точки на макете страницы, где начинается прямоугольник, содержащий слово. |
| width | Double | Ширина прямоугольника, содержащего слово. |
| height | Double | Высота прямоугольника, содержащего слово. |
| символы | List`1 | Символы, содержащиеся в слове. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *word* равно null или пусто. |
| ArgumentNullException | Выбрасывается, когда *characters* равно null. |

### См. также

* class [Character](../../character)
* class [Word](../../word)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
