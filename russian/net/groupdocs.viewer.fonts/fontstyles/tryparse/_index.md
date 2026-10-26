---
title: "TryParse"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Пытается разобрать указанную необработанную строку как имя стиля шрифта"
type: docs
weight: 120
url: /ru/net/groupdocs.viewer.fonts/fontstyles/tryparse/
---

## FontStyles.TryParse method

Пытается разобрать указанную необработанную строку как имя стиля шрифта

```csharp
public static bool TryParse(string style, out FontStyles parsed)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| стиль | String | Строка, которую следует разобрать как стиль шрифта |
| parsed | FontStyles& | Разобранный стиль шрифта при успехе или [`Regular`](../regular) при неудаче |

### Возвращаемое значение

`true`, если строка была успешно разобрана как корректный стиль шрифта; `false` в противном случае

### См. также

* struct [FontStyles](../../fontstyles)
* namespace [GroupDocs.Viewer.Fonts](../../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
