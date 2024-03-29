---
title: SaveAttachment
second_title: Справочник по API GroupDocs.Viewer для .NET
description: Сохраняет вложенный файл вdestination поток.
type: docs
weight: 60
url: /ru/net/groupdocs.viewer/viewer/saveattachment/
---
## SaveAttachment(Attachment, Stream, CancellationToken) {#saveattachment_1}

Сохраняет вложенный файл в*destination* поток.

```csharp
public void SaveAttachment(Attachment attachment, Stream destination, 
    CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| attachment | Attachment | Вложение. |
| destination | Stream | Доступный для записи поток. |
| cancellationToken | CancellationToken | Токен отмены. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*attachment* нулевой. |
| ArgumentNullException | Брошен, когда*destination* нулевой. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Генерируется, когда для открытия документа требуется пароль. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Генерируется, когда указанный пароль неверен. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Брошен, когда вложение не может быть найдено. |

### Примечания

**Узнать больше**

* Узнайте больше о получении вложений документов в C#: [Как получить список вложенных документов с помощью GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* Узнайте больше о сохранении вложений документов в C#: [Как сохранить вложения к документам с помощью GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### Смотрите также

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

---

## SaveAttachment(Attachment, Stream) {#saveattachment}

Сохраняет вложенный файл в*destination* поток.

```csharp
public void SaveAttachment(Attachment attachment, Stream destination)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| attachment | Attachment | Вложение. |
| destination | Stream | Доступный для записи поток. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*attachment* нулевой. |
| ArgumentNullException | Брошен, когда*destination* нулевой. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Генерируется, когда для открытия документа требуется пароль. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Генерируется, когда указанный пароль неверен. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Брошен, когда вложение не может быть найдено. |

### Примечания

**Узнать больше**

* Узнайте больше о получении вложений документов в C#: [Как получить список вложенных документов с помощью GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* Узнайте больше о сохранении вложений документов в C#: [Как сохранить вложения к документам с помощью GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### Смотрите также

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
