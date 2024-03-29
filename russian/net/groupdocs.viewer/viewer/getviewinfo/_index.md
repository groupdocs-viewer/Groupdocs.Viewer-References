---
title: GetViewInfo
second_title: Справочник по API GroupDocs.Viewer для .NET
description: Возвращает информацию о представлении и конкретной информации о документе.
type: docs
weight: 50
url: /ru/net/groupdocs.viewer/viewer/getviewinfo/
---
## GetViewInfo(ViewInfoOptions) {#getviewinfo}

Возвращает информацию о представлении и конкретной информации о документе.

```csharp
public ViewInfo GetViewInfo(ViewInfoOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | ViewInfoOptions | Параметры просмотра информации. |

### Возвращаемое значение

Информация о просмотре и документировании конкретной информации.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*options* нулевой. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Генерируется, когда для открытия документа требуется пароль. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Генерируется, когда указанный пароль неверен. |

### Примечания

**Узнать больше**

* Узнайте больше о документе — типе файла, количестве страниц и других свойствах формата: [Как получить информацию о файле с помощью GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

### Смотрите также

* class [ViewInfo](../../../groupdocs.viewer.results/viewinfo)
* class [ViewInfoOptions](../../../groupdocs.viewer.options/viewinfooptions)
* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

---

## GetViewInfo(ViewInfoOptions, CancellationToken) {#getviewinfo_1}

Возвращает информацию о представлении и конкретной информации о документе.

```csharp
public ViewInfo GetViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | ViewInfoOptions | Параметры просмотра информации. |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

Информация о просмотре и документировании конкретной информации.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*options* нулевой. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Генерируется, когда для открытия документа требуется пароль. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Генерируется, когда указанный пароль неверен. |

### Примечания

**Узнать больше**

* Узнайте больше о документе — типе файла, количестве страниц и других свойствах формата: [Как получить информацию о файле с помощью GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

### Смотрите также

* class [ViewInfo](../../../groupdocs.viewer.results/viewinfo)
* class [ViewInfoOptions](../../../groupdocs.viewer.options/viewinfooptions)
* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
