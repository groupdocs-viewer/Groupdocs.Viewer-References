---
title: "GetViewInfo"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Возвращает информацию о представлении и специфическую информацию о документе."
type: docs
weight: 60
url: /ru/net/groupdocs.viewer/viewer/getviewinfo/
---

## GetViewInfo(ViewInfoOptions) {#getviewinfo}

Возвращает информацию о представлении и специфическую информацию о документе.

```csharp
public ViewInfo GetViewInfo(ViewInfoOptions options)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| параметры | ViewInfoOptions | Параметры информации представления. |

### Возвращаемое значение

Информация о представлении и специфической информации документа.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *options* равен null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Выбрасывается, когда для открытия документа требуется пароль. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Выбрасывается, когда указанный пароль неверен. |

### Примечания

**Learn more**

* Learn more about document - file type, pages count and other format specific properties: [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

### См. также

* class [ViewInfo](../../../groupdocs.viewer.results/viewinfo)
* class [ViewInfoOptions](../../../groupdocs.viewer.options/viewinfooptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## GetViewInfo(ViewInfoOptions, CancellationToken) {#getviewinfo_1}

Возвращает информацию о представлении и специфическую информацию о документе.

```csharp
public ViewInfo GetViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| параметры | ViewInfoOptions | Параметры информации представления. |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

Информация о представлении и специфической информации документа.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *options* равен null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Выбрасывается, когда для открытия документа требуется пароль. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Выбрасывается, когда указанный пароль неверен. |

### Примечания

**Learn more**

* Learn more about document - file type, pages count and other format specific properties: [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

### См. также

* class [ViewInfo](../../../groupdocs.viewer.results/viewinfo)
* class [ViewInfoOptions](../../../groupdocs.viewer.options/viewinfooptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
