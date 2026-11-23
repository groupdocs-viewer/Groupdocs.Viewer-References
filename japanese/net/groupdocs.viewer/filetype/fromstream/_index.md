---
title: "FromStream"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "ファイルシグネチャを読み取ってファイルタイプを検出します。"
type: docs
weight: 2000
url: /ja/net/groupdocs.viewer/filetype/fromstream/
---

## FromStream(Stream) {#fromstream}

ファイルシグネチャを読み取ってファイルタイプを検出します。

```csharp
public static FileType FromStream(Stream stream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ファイルストリームです。 |

### 関連項目

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, string) {#fromstream_2}

ファイルシグネチャを読み取ってファイルタイプを検出します。

```csharp
public static FileType FromStream(Stream stream, string password)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ファイルストリームです。 |
| パスワード | String | ファイルを開くためのパスワードです。 |

### 関連項目

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, ILogger) {#fromstream_1}

ファイルシグネチャを読み取ってファイルタイプを検出します。

```csharp
public static FileType FromStream(Stream stream, ILogger logger)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ファイルストリームです。 |
| ロガー | ILogger | ロガーです。 |

### 戻り値

検出に成功した場合はファイルタイプを返し、そうでない場合はデフォルトの [`Unknown`](../unknown) ファイルタイプを返します。

### 関連項目

* interface [ILogger](../../../groupdocs.viewer.logging/ilogger)
* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, string, ILogger) {#fromstream_3}

ファイルシグネチャを読み取ってファイルタイプを検出します。

```csharp
public static FileType FromStream(Stream stream, string password, ILogger logger)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ファイルストリームです。 |
| パスワード | String | ファイルを開くためのパスワードです。 |
| ロガー | ILogger | ロガーです。 |

### 戻り値

検出に成功した場合はファイルタイプを返し、そうでない場合はデフォルトの [`Unknown`](../unknown) ファイルタイプを返します。

### 関連項目

* interface [ILogger](../../../groupdocs.viewer.logging/ilogger)
* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
