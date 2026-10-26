---
title: "View"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Создаёт представление всех страниц документа."
type: docs
weight: 90
url: /ru/net/groupdocs.viewer/viewer/view/
---

## View(ViewOptions) {#view}

Создаёт представление всех страниц документа.

```csharp
public void View(ViewOptions options)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| параметры | ViewOptions | Параметры представления. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *options* равен null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Выбрасывается, когда для открытия документа требуется пароль. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Выбрасывается, когда указанный пароль неверен. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Выбрасывается, когда вложение не найдено. |

### Примечания

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### См. также

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

Создаёт представление всех страниц документа.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| параметры | ViewOptions | Параметры представления. |
| cancellationToken | CancellationToken | Токен отмены для отправки запроса на отмену текущего процесса представления. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *options* равен null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Выбрасывается, когда для открытия документа требуется пароль. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Выбрасывается, когда указанный пароль неверен. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Выбрасывается, когда вложение не найдено. |

### Примечания

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### См. также

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

Создаёт представление определённых страниц документа.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| параметры | ViewOptions | Параметры представления. |
| pageNumbers | Int32[] | Номера страниц для просмотра. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *options* равен null. |
| ArgumentNullException | Выбрасывается, когда *pageNumbers* равно null. |
| ArgumentException | Выбрасывается, когда *pageNumbers* пусто. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Выбрасывается, когда для открытия документа требуется пароль. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Выбрасывается, когда указанный пароль неверен. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Выбрасывается, когда вложение не найдено. |

### Примечания

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### См. также

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

Создаёт представление определённых страниц документа.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| параметры | ViewOptions | Параметры представления. |
| pageNumbers | CancellationToken | Номера страниц для просмотра. |
| cancellationToken | Int32[] | Токен отмены для прерывания обработки. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *options* равен null. |
| ArgumentNullException | Выбрасывается, когда *pageNumbers* равно null. |
| ArgumentException | Выбрасывается, когда *pageNumbers* пусто. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Выбрасывается, когда для открытия документа требуется пароль. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Выбрасывается, когда указанный пароль неверен. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Выбрасывается, когда вложение не найдено. |

### Примечания

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### См. также

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
