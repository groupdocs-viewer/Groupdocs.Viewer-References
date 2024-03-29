---
title: SaveAttachment
second_title: GroupDocs.Viewer for .NET API 参考
description: 将附件文件保存到destination流.
type: docs
weight: 60
url: /zh/net/groupdocs.viewer/viewer/saveattachment/
---
## SaveAttachment(Attachment, Stream, CancellationToken) {#saveattachment_1}

将附件文件保存到*destination*流.

```csharp
public void SaveAttachment(Attachment attachment, Stream destination, 
    CancellationToken cancellationToken)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| attachment | Attachment | 附件。 |
| destination | Stream | 可写流。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*attachment*一片空白。 |
| ArgumentNullException | 抛出时*destination*一片空白。 |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | 当打开文档需要密码时抛出。 |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | 当指定的密码不正确时抛出。 |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | 找不到附件时抛出。 |

### 评论

**了解更多**

* 了解有关在 C# 中获取文档附件的更多信息： [如何使用 GroupDocs.Viewer 获取文档附件列表](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* 了解有关在 C# 中保存文档附件的更多信息： [如何使用 GroupDocs.Viewer 保存文档附件](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### 也可以看看

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* 命名空间 [GroupDocs.Viewer](../../viewer)
* 部件 [GroupDocs.Viewer](../../../)

---

## SaveAttachment(Attachment, Stream) {#saveattachment}

将附件文件保存到*destination*流.

```csharp
public void SaveAttachment(Attachment attachment, Stream destination)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| attachment | Attachment | 附件。 |
| destination | Stream | 可写流。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*attachment*一片空白。 |
| ArgumentNullException | 抛出时*destination*一片空白。 |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | 当打开文档需要密码时抛出。 |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | 当指定的密码不正确时抛出。 |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | 找不到附件时抛出。 |

### 评论

**了解更多**

* 了解有关在 C# 中获取文档附件的更多信息： [如何使用 GroupDocs.Viewer 获取文档附件列表](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* 了解有关在 C# 中保存文档附件的更多信息： [如何使用 GroupDocs.Viewer 保存文档附件](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### 也可以看看

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* 命名空间 [GroupDocs.Viewer](../../viewer)
* 部件 [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
