---
title: "GetAttachments"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Возвращает вложения, содержащиеся в документе."
type: docs
weight: 40
url: /ru/net/groupdocs.viewer/viewer/getattachments/
---

## GetAttachments() {#getattachments}

Возвращает вложения, содержащиеся в документе.

```csharp
public IList<Attachment> GetAttachments()
```

### Возвращаемое значение

Вложения, содержащиеся в документе.

### Исключения

| исключение | условие |
| --- | --- |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Выбрасывается, когда для открытия документа требуется пароль. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Выбрасывается, когда указанный пароль неверен. |

### Примечания

**Learn more**

* Learn more about getting document attachments in C#: [How to get list of document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* Learn more about saving document attachments in C#: [How to save document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### См. также

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## GetAttachments(CancellationToken) {#getattachments_1}

Возвращает вложения, содержащиеся в документе.

```csharp
public IList<Attachment> GetAttachments(CancellationToken cancellationToken)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| cancellationToken | CancellationToken | Токен отмены. |

### Возвращаемое значение

Вложения, содержащиеся в документе.

### Исключения

| исключение | условие |
| --- | --- |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Выбрасывается, когда для открытия документа требуется пароль. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Выбрасывается, когда указанный пароль неверен. |

### Примечания

**Learn more**

* Learn more about getting document attachments in C#: [How to get list of document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* Learn more about saving document attachments in C#: [How to save document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### См. также

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
