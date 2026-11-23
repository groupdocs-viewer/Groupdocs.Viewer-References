---
title: "GetViewInfo"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "ビューおよびドキュメント固有の情報を返します。"
type: docs
weight: 60
url: /ja/net/groupdocs.viewer/viewer/getviewinfo/
---

## GetViewInfo(ViewInfoOptions) {#getviewinfo}

ビューおよびドキュメント固有の情報を返します。

```csharp
public ViewInfo GetViewInfo(ViewInfoOptions options)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| options | ViewInfoOptions | ビュー情報オプションです。 |

### 戻り値

ビューとドキュメント固有の情報です。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | Thrown when *options* is null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | ドキュメントを開くのにパスワードが必要な場合にスローされます。 |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | 指定されたパスワードが正しくない場合にスローされます。 |

### 備考

**Learn more**

* Learn more about document - file type, pages count and other format specific properties: [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

### 関連項目

* class [ViewInfo](../../../groupdocs.viewer.results/viewinfo)
* class [ViewInfoOptions](../../../groupdocs.viewer.options/viewinfooptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## GetViewInfo(ViewInfoOptions, CancellationToken) {#getviewinfo_1}

ビューおよびドキュメント固有の情報を返します。

```csharp
public ViewInfo GetViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| options | ViewInfoOptions | ビュー情報オプションです。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 戻り値

ビューとドキュメント固有の情報です。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | Thrown when *options* is null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | ドキュメントを開くのにパスワードが必要な場合にスローされます。 |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | 指定されたパスワードが正しくない場合にスローされます。 |

### 備考

**Learn more**

* Learn more about document - file type, pages count and other format specific properties: [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

### 関連項目

* class [ViewInfo](../../../groupdocs.viewer.results/viewinfo)
* class [ViewInfoOptions](../../../groupdocs.viewer.options/viewinfooptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
