---
title: "DetectEncoding"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "パスに基づいて TXT（groupdocs.viewer/filetype/txt）、TSV（groupdocs.viewer/filetype/tsv）、CSV（groupdocs.viewer/filetype/csv）ファイルのエンコーディングを検出しようとします。"
type: docs
weight: 2060
url: /ja/net/groupdocs.viewer/filetype/detectencoding/
---

## DetectEncoding(string) {#detectencoding_1}

パスによってテキスト[`TXT`](../txt)、[`TSV`](../tsv)、および[`CSV`](../csv)ファイルのエンコーディングを検出しようとします。

```csharp
public static Encoding DetectEncoding(string filePath)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | ファイル名またはファイルパスです。 |

### 戻り値

ファイルのエンコーディング検出に失敗した場合はエンコーディングまたは null が返されます。

### 例

この例はテキストファイルのエンコーディングを検出する方法を示しています。

```csharp
Encoding encoding = FileType.DetectEncoding("message.txt");
```

### 関連項目

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## DetectEncoding(Stream) {#detectencoding}

ストリームによってテキスト[`TXT`](../txt)、[`TSV`](../tsv)、および[`CSV`](../csv)ファイルのエンコーディングを検出しようとします。

```csharp
public static Encoding DetectEncoding(Stream stream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ファイルストリームです。 |

### 戻り値

ファイルのエンコーディング検出に失敗した場合はエンコーディングまたは null が返されます。

### 例

この例はテキストファイルのエンコーディングを検出する方法を示しています。

```csharp
Stream stream = File.OpenRead("message.txt");
Encoding encoding = FileType.DetectEncoding(stream);
```

### 関連項目

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
