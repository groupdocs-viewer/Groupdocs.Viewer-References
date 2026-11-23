---
title: "ForRenderingByScaleFactor"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инициализирует экземпляр класса CadOptionsgroupdocs.viewer.options/cadoptions для рендеринга по коэффициенту масштабирования."
type: docs
weight: 20
url: /ru/net/groupdocs.viewer.options/cadoptions/forrenderingbyscalefactor/
---

## CadOptions.ForRenderingByScaleFactor method

Инициализирует экземпляр класса [`CadOptions`](../../cadoptions) для рендеринга по коэффициенту масштабирования.

```csharp
public static CadOptions ForRenderingByScaleFactor(float scaleFactor)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| scaleFactor | Single | Значение больше 1 увеличивает результат вывода; значение от 0 до 1 уменьшает результат вывода. |

### Возвращаемое значение

Новый экземпляр класса [`CadOptions`](../../cadoptions) для рендеринга по коэффициенту масштабирования.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *scaleFactor* меньше или равен нулю. |

### Примечания

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#configure-the-output-image-size).

### См. также

* class [CadOptions](../../cadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
