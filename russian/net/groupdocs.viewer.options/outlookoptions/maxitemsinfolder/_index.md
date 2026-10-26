---
title: "MaxItemsInFolder"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Максимальное количество сообщений или элементов, которые могут быть отрисованы из одной папки."
type: docs
weight: 40
url: /ru/net/groupdocs.viewer.options/outlookoptions/maxitemsinfolder/
---

## OutlookOptions.MaxItemsInFolder property

Максимальное количество сообщений или элементов, которые могут быть отрендерены из одной папки.

```csharp
public int MaxItemsInFolder { get; set; }
```

### Примечания

Файлы данных Outlook могут быть большими, и получение всех сообщений может занять значительное время. Это свойство ограничивает максимальное количество отрисовываемых сообщений или элементов. Значение по умолчанию — `50`. Чтобы отрисовать все сообщения, установите значение `0`.

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/render-outlook-data-files/#limit-the-number-of-folder-items-to-render).

### См. также

* class [OutlookOptions](../../outlookoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
