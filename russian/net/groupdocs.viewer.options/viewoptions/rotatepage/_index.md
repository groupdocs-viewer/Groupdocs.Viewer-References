---
title: "RotatePage"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Применяет вращение по часовой стрелке к странице."
type: docs
weight: 30
url: /ru/net/groupdocs.viewer.options/viewoptions/rotatepage/
---

## ViewOptions.RotatePage method

Применяет вращение по часовой стрелке к странице.

```csharp
public void RotatePage(int pageNumber, Rotation rotation)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Номер страницы должен быть строго больше 0. |
| rotation | Rotation | Значение вращения. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Выбрасывается, когда *pageNumber* меньше или равен нулю. |
| ArgumentException | Выбрасывается, когда вращение для страницы с номером *pageNumber* уже было добавлено. |

### Примечания

Для получения подробностей см. [документацию](https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/).

### См. также

* enum [Rotation](../../rotation)
* class [ViewOptions](../../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
