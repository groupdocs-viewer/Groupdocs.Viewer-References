---
title: View
second_title: Справочник по API GroupDocs.Viewer для .NET
description: Создает представление всех страниц документа.
type: docs
weight: 70
url: /ru/net/groupdocs.viewer/viewer/view/
---
## View(ViewOptions) {#view}

Создает представление всех страниц документа.

```csharp
public void View(ViewOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | ViewOptions | Варианты просмотра. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*options* нулевой. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Генерируется, когда для открытия документа требуется пароль. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Генерируется, когда указанный пароль неверен. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Брошен, когда вложение не может быть найдено. |

### Примечания

**Учить больше**

* Подробнее о различных параметрах просмотра в этом руководстве: [Как настроить вывод просмотра документов с помощью GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Смотрите также

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

Создает представление всех страниц документа.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | ViewOptions | Варианты просмотра. |
| cancellationToken | CancellationToken | Токен отмены для отправки запроса на отмену текущего процесса просмотра. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*options* нулевой. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Генерируется, когда для открытия документа требуется пароль. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Генерируется, когда указанный пароль неверен. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Брошен, когда вложение не может быть найдено. |

### Примечания

**Учить больше**

* Подробнее о различных параметрах просмотра в этом руководстве: [Как настроить вывод просмотра документов с помощью GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Смотрите также

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

Создает представление определенных страниц документа.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | ViewOptions | Варианты просмотра. |
| pageNumbers | Int32[] | Номера страниц для просмотра. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*options* нулевой. |
| ArgumentNullException | Брошен, когда*pageNumbers* нулевой. |
| ArgumentException | Брошен, когда*pageNumbers* пустой. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Генерируется, когда для открытия документа требуется пароль. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Генерируется, когда указанный пароль неверен. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Брошен, когда вложение не может быть найдено. |

### Примечания

**Учить больше**

* Подробнее о различных параметрах просмотра в этом руководстве: [Как настроить вывод просмотра документов с помощью GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Смотрите также

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

Создает представление определенных страниц документа.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | ViewOptions | Варианты просмотра. |
| pageNumbers | CancellationToken | Номера страниц для просмотра. |
| cancellationToken | Int32[] | Токен отмены для отмены обработки. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*options* нулевой. |
| ArgumentNullException | Брошен, когда*pageNumbers* нулевой. |
| ArgumentException | Брошен, когда*pageNumbers* пустой. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Генерируется, когда для открытия документа требуется пароль. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Генерируется, когда указанный пароль неверен. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Брошен, когда вложение не может быть найдено. |

### Примечания

**Учить больше**

* Подробнее о различных параметрах просмотра в этом руководстве: [Как настроить вывод просмотра документов с помощью GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Смотрите также

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
