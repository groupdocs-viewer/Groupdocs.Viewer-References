---
title: "ビュー"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "すべてのドキュメントページのビューを作成します。"
type: docs
weight: 90
url: /ja/net/groupdocs.viewer/viewer/view/
---

## View(ViewOptions) {#view}

すべてのドキュメントページのビューを作成します。

```csharp
public void View(ViewOptions options)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| options | ViewOptions | ビューオプションです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | Thrown when *options* is null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | ドキュメントを開くのにパスワードが必要な場合にスローされます。 |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | 指定されたパスワードが正しくない場合にスローされます。 |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | 添付ファイルが見つからない場合にスローされます。 |

### 備考

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### 関連項目

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

すべてのドキュメントページのビューを作成します。

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| options | ViewOptions | ビューオプションです。 |
| cancellationToken | CancellationToken | 現在のビュー処理をキャンセルするリクエストを送信するためのキャンセルトークンです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | Thrown when *options* is null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | ドキュメントを開くのにパスワードが必要な場合にスローされます。 |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | 指定されたパスワードが正しくない場合にスローされます。 |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | 添付ファイルが見つからない場合にスローされます。 |

### 備考

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### 関連項目

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

特定のドキュメントページのビューを作成します。

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| options | ViewOptions | ビューオプションです。 |
| ページ番号 | Int32[] | 表示するページ番号です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | Thrown when *options* is null. |
| ArgumentNullException | Thrown when *pageNumbers* is null. |
| ArgumentException | Thrown when *pageNumbers* is empty. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | ドキュメントを開くのにパスワードが必要な場合にスローされます。 |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | 指定されたパスワードが正しくない場合にスローされます。 |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | 添付ファイルが見つからない場合にスローされます。 |

### 備考

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### 関連項目

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

特定のドキュメントページのビューを作成します。

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| options | ViewOptions | ビューオプションです。 |
| ページ番号 | CancellationToken | 表示するページ番号です。 |
| cancellationToken | Int32[] | 処理をキャンセルするためのキャンセルトークンです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | Thrown when *options* is null. |
| ArgumentNullException | Thrown when *pageNumbers* is null. |
| ArgumentException | Thrown when *pageNumbers* is empty. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | ドキュメントを開くのにパスワードが必要な場合にスローされます。 |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | 指定されたパスワードが正しくない場合にスローされます。 |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | 添付ファイルが見つからない場合にスローされます。 |

### 備考

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### 関連項目

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
