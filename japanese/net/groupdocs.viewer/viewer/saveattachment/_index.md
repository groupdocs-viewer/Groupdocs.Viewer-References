---
title: "SaveAttachment"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "添付ファイルを宛先ストリームに保存します。"
type: docs
weight: 70
url: /ja/net/groupdocs.viewer/viewer/saveattachment/
---

## SaveAttachment(Attachment, Stream, CancellationToken) {#saveattachment_1}

*destination* ストリームに添付ファイルを保存します。

```csharp
public void SaveAttachment(Attachment attachment, Stream destination, 
    CancellationToken cancellationToken)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 添付ファイル | 添付ファイル | 添付ファイルです。 |
| 宛先 | ストリーム | 書き込み可能なストリームです。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | Thrown when *attachment* is null. |
| ArgumentNullException | Thrown when *destination* is null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | ドキュメントを開くのにパスワードが必要な場合にスローされます。 |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | 指定されたパスワードが正しくない場合にスローされます。 |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | 添付ファイルが見つからない場合にスローされます。 |

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

## SaveAttachment(Attachment, Stream) {#saveattachment}

*destination* ストリームに添付ファイルを保存します。

```csharp
public void SaveAttachment(Attachment attachment, Stream destination)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 添付ファイル | 添付ファイル | 添付ファイルです。 |
| 宛先 | ストリーム | 書き込み可能なストリームです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | Thrown when *attachment* is null. |
| ArgumentNullException | Thrown when *destination* is null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | ドキュメントを開くのにパスワードが必要な場合にスローされます。 |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | 指定されたパスワードが正しくない場合にスローされます。 |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | 添付ファイルが見つからない場合にスローされます。 |

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
