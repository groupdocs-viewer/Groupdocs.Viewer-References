---
title: "ビューア"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "Viewergroupdocs.viewer/viewer クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.viewer/viewer/viewer/
---

## Viewer(Func&lt;Stream&gt;) {#constructor}

[`Viewer`](../../viewer) クラスの新しいインスタンスを初期化します。

```csharp
public Viewer(Func<Stream> getFileStream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| getFileStream | Func`1 | 読み取り可能なストリームを返すメソッドです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *getFileStream* が null のときにスローされます。 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 関連項目

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

[`Viewer`](../../viewer) クラスの新しいインスタンスを初期化します。

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| getFileStream | Func`1 | 読み取り可能なストリームを返すメソッドです。 |
| getLoadOptions | Func`1 | ドキュメントのロードオプションを返すメソッドです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *getFileStream* が null のときにスローされます。 |
| ArgumentNullException | *getLoadOptions* が null のときにスローされます。 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 関連項目

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

[`Viewer`](../../viewer) クラスの新しいインスタンスを初期化します。

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| getFileStream | Func`1 | 読み取り可能なストリームを返すメソッドです。 |
| settings | ViewerSettings | Viewer の設定です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *getFileStream* が null のときにスローされます。 |
| ArgumentNullException | *settings* が null のときにスローされます。 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 関連項目

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

[`Viewer`](../../viewer) クラスの新しいインスタンスを初期化します。

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| getFileStream | Func`1 | 読み取り可能なストリームを返すメソッドです。 |
| getLoadOptions | Func`1 | ドキュメントのロードオプションを返すメソッドです。 |
| settings | ViewerSettings | Viewer の設定です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *getFileStream* が null のときにスローされます。 |
| ArgumentNullException | *getLoadOptions* が null のときにスローされます。 |
| ArgumentNullException | *settings* が null のときにスローされます。 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 関連項目

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

[`Viewer`](../../viewer) クラスの新しいインスタンスを初期化します。

```csharp
public Viewer(Stream stream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ファイルストリームです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *stream* が null のときにスローされます。 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 関連項目

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

[`Viewer`](../../viewer) クラスの新しいインスタンスを初期化します。

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ファイルストリームです。 |
| leaveOpen | Boolean | Viewer オブジェクトが破棄された後もストリームを開いたままにする場合は true、そうでない場合は false。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *stream* が null のときにスローされます。 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 関連項目

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

[`Viewer`](../../viewer) クラスの新しいインスタンスを初期化します。

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ファイルストリームです。 |
| loadOptions | LoadOptions | ドキュメントのロードオプションです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *stream* が null のときにスローされます。 |
| ArgumentNullException | *loadOptions* が null のときにスローされます。 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 関連項目

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

[`Viewer`](../../viewer) クラスの新しいインスタンスを初期化します。

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ファイルストリームです。 |
| loadOptions | LoadOptions | ドキュメントのロードオプションです。 |
| leaveOpen | Boolean | Viewer オブジェクトが破棄された後もストリームを開いたままにする場合は true、そうでない場合は false。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *stream* が null のときにスローされます。 |
| ArgumentNullException | *loadOptions* が null のときにスローされます。 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 関連項目

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

[`Viewer`](../../viewer) クラスの新しいインスタンスを初期化します。

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ファイルストリームです。 |
| settings | ViewerSettings | Viewer の設定です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *stream* が null のときにスローされます。 |
| ArgumentNullException | *settings* が null のときにスローされます。 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 関連項目

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

[`Viewer`](../../viewer) クラスの新しいインスタンスを初期化します。

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ファイルストリームです。 |
| settings | ViewerSettings | Viewer の設定です。 |
| leaveOpen | Boolean | Viewer オブジェクトが破棄された後もストリームを開いたままにする場合は true、そうでない場合は false。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *stream* が null のときにスローされます。 |
| ArgumentNullException | *settings* が null のときにスローされます。 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 関連項目

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

[`Viewer`](../../viewer) クラスの新しいインスタンスを初期化します。

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ファイルストリームです。 |
| loadOptions | LoadOptions | ドキュメントのロードオプションです。 |
| settings | ViewerSettings | Viewer の設定です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *stream* が null のときにスローされます。 |
| ArgumentNullException | *loadOptions* が null のときにスローされます。 |
| ArgumentNullException | *settings* が null のときにスローされます。 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 関連項目

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

[`Viewer`](../../viewer) クラスの新しいインスタンスを初期化します。

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ファイルストリームです。 |
| loadOptions | LoadOptions | ドキュメントのロードオプションです。 |
| settings | ViewerSettings | Viewer の設定です。 |
| leaveOpen | Boolean | Viewer オブジェクトが破棄された後もストリームを開いたままにする場合は true、そうでない場合は false。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *stream* が null のときにスローされます。 |
| ArgumentNullException | *loadOptions* が null のときにスローされます。 |
| ArgumentNullException | *settings* が null のときにスローされます。 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 関連項目

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

[`Viewer`](../../viewer) クラスの新しいインスタンスを初期化します。

```csharp
public Viewer(string filePath)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | レンダリングするファイルへのパスです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *filePath* が null または空のときにスローされます。 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 関連項目

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

[`Viewer`](../../viewer) クラスの新しいインスタンスを初期化します。

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | レンダリングするファイルへのパスです。 |
| settings | ViewerSettings | Viewer の設定です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *filePath* が null または空のときにスローされます。 |
| ArgumentNullException | *settings* が null のときにスローされます。 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 関連項目

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

[`Viewer`](../../viewer) クラスの新しいインスタンスを初期化します。

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | レンダリングするファイルへのパスです。 |
| loadOptions | LoadOptions | ファイルを開く際に使用されるオプションです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *filePath* が null または空のときにスローされます。 |
| ArgumentNullException | *loadOptions* が null のときにスローされます。 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 関連項目

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

[`Viewer`](../../viewer) クラスの新しいインスタンスを初期化します。

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | レンダリングするファイルへのパスです。 |
| loadOptions | LoadOptions | ファイルを開く際に使用されるオプションです。 |
| settings | ViewerSettings | Viewer の設定です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *filePath* が null または空のときにスローされます。 |
| ArgumentNullException | *loadOptions* が null のときにスローされます。 |
| ArgumentNullException | *settings* が null のときにスローされます。 |

### 備考

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 関連項目

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
