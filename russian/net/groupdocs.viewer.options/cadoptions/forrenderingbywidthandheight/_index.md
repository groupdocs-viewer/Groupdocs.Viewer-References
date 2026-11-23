---
title: "ForRenderingByWidthAndHeight"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инициализирует экземпляр класса CadOptionsgroupdocs.viewer.options/cadoptions для рендеринга по ширине и высоте."
type: docs
weight: 40
url: /ru/net/groupdocs.viewer.options/cadoptions/forrenderingbywidthandheight/
---

## CadOptions.ForRenderingByWidthAndHeight method

Инициализирует экземпляр класса [`CadOptions`](../../cadoptions) для рендеринга по ширине и высоте.

```csharp
public static CadOptions ForRenderingByWidthAndHeight(int width, int height)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| width | Int32 | Ширина результата вывода (в пикселях). |
| height | Int32 | Высота выходного результата (в пикселях). |

### Возвращаемое значение

Новый экземпляр класса [`CadOptions`](../../cadoptions) для рендеринга по ширине и высоте.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *width* меньше или равен нулю. |
| ArgumentException | Выбрасывается, когда *height* меньше или равен нулю. |

### Примечания

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#configure-the-output-image-size).

### См. также

* class [CadOptions](../../cadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
