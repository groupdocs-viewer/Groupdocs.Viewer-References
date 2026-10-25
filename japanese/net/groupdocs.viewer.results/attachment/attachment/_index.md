---
title: "添付ファイル"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "Attachmentgroupdocs.viewer.results/attachment クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.viewer.results/attachment/attachment/
---

## Attachment() {#constructor}

[`Attachment`](../../attachment) クラスの新しいインスタンスを初期化します。

```csharp
public Attachment()
```

### 関連項目

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string) {#constructor_1}

[`Attachment`](../../attachment) クラスの新しいインスタンスを初期化します。

```csharp
public Attachment(string fileName, string filePath)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fileName | String | 添付ファイル名。 |
| filePath | String | 添付ファイルの相対パス（例: folder/file.docx、またはアーカイブのルート、メールメッセージ、データファイルにある場合はファイル名）。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *fileName* が null または空のときにスローされます。 |
| ArgumentException | *filePath* が null または空のときにスローされます。 |

### 関連項目

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string, string, long) {#constructor_3}

[`Attachment`](../../attachment) クラスの新しいインスタンスを初期化します。

```csharp
public Attachment(string id, string fileName, string filePath, long size)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| id | String | 単一ファイルのコンテキストにおける添付ファイルの一意の識別子です。 |
| fileName | String | 添付ファイル名。 |
| filePath | String | 添付ファイルの相対パス（例: folder/file.docx、またはアーカイブのルート、メールメッセージ、データファイルにある場合はファイル名）。 |
| サイズ | Int64 | 添付ファイルのサイズ（バイト単位）。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *id* が null または空の場合にスローされます。 |
| ArgumentException | *fileName* が null または空のときにスローされます。 |
| ArgumentException | *filePath* が null または空のときにスローされます。 |

### 関連項目

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string, string, FileType, long) {#constructor_2}

[`Attachment`](../../attachment) クラスの新しいインスタンスを初期化します。

```csharp
public Attachment(string id, string fileName, string filePath, FileType fileType, long size)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| id | String | 単一ファイルのコンテキストにおける添付ファイルの一意の識別子です。 |
| fileName | String | 添付ファイル名。 |
| filePath | String | 添付ファイルの相対パス（例: folder/file.docx、またはアーカイブのルート、メールメッセージ、データファイルにある場合はファイル名）。 |
| fileType | FileType | 添付ファイルの種類。 |
| サイズ | Int64 | 添付ファイルのサイズ（バイト単位）。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *id* が null または空の場合にスローされます。 |
| ArgumentException | *fileName* が null または空のときにスローされます。 |
| ArgumentException | *filePath* が null または空のときにスローされます。 |
| ArgumentNullException | *fileType* が null のときにスローされます。 |

### 関連項目

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
