---
title: "GetAttachments"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "ドキュメントに含まれる添付ファイルを返します。"
type: docs
weight: 40
url: /ja/net/groupdocs.viewer/viewer/getattachments/
---

## GetAttachments() {#getattachments}

ドキュメントに含まれる添付ファイルを返します。

```csharp
public IList<Attachment> GetAttachments()
```

### 戻り値

ドキュメントに含まれる添付ファイルです。

### 例外

| 例外 | 条件 |
| --- | --- |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | ドキュメントを開くのにパスワードが必要な場合にスローされます。 |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | 指定されたパスワードが正しくない場合にスローされます。 |

### 備考

**Learn more**

* Learn more about getting document attachments in C#: [How to get list of document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* Learn more about saving document attachments in C#: [How to save document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### 関連項目

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## GetAttachments(CancellationToken) {#getattachments_1}

ドキュメントに含まれる添付ファイルを返します。

```csharp
public IList<Attachment> GetAttachments(CancellationToken cancellationToken)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 戻り値

ドキュメントに含まれる添付ファイルです。

### 例外

| 例外 | 条件 |
| --- | --- |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | ドキュメントを開くのにパスワードが必要な場合にスローされます。 |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | 指定されたパスワードが正しくない場合にスローされます。 |

### 備考

**Learn more**

* Learn more about getting document attachments in C#: [How to get list of document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* Learn more about saving document attachments in C#: [How to save document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### 関連項目

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
