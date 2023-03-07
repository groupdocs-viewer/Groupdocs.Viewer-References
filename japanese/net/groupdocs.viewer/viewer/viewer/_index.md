---
title: Viewer
second_title: GroupDocs.Viewer for .NET API リファレンス
description: の新しいインスタンスを初期化しますViewergroupdocs.viewer/viewerclass.
type: docs
weight: 10
url: /ja/net/groupdocs.viewer/viewer/viewer/
---
## Viewer(Func&lt;Stream&gt;) {#constructor}

の新しいインスタンスを初期化します[`Viewer`](../../viewer)class.

```csharp
public Viewer(Func<Stream> getFileStream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| getFileStream | Func`1 | 読み取り可能なストリームを返すメソッド。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*getFileStream*無効である。 |

### 備考

**もっと詳しく知る**

* GroupDocs.Viewer でサポートされているファイル タイプの詳細: [GroupDocs.Viewer でサポートされているドキュメント形式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET 機能の詳細: [開発者ガイド](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 関連項目

* class [Viewer](../../viewer)
* 名前空間 [GroupDocs.Viewer](../../viewer)
* 組み立て [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

の新しいインスタンスを初期化します[`Viewer`](../../viewer)class.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| getFileStream | Func`1 | 読み取り可能なストリームを返すメソッド。 |
| getLoadOptions | Func`1 | ドキュメント読み込みオプションを返すメソッド。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*getFileStream*無効である。 |
| ArgumentNullException | スローされるタイミング*getLoadOptions*無効である。 |

### 備考

**もっと詳しく知る**

* GroupDocs.Viewer でサポートされているファイル タイプの詳細: [GroupDocs.Viewer でサポートされているドキュメント形式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET 機能の詳細: [開発者ガイド](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* GroupDocs.Viewer for .NET を使用して暗号化されたドキュメントを読み込み、サードパーティのストレージからファイルを表示する方法の詳細: [GroupDocs.Viewer でドキュメントを読み込んで表示する方法](https://docs.groupdocs.com/display/viewernet/Loading)

### 関連項目

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* 名前空間 [GroupDocs.Viewer](../../viewer)
* 組み立て [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

の新しいインスタンスを初期化します[`Viewer`](../../viewer)class.

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| getFileStream | Func`1 | 読み取り可能なストリームを返すメソッド。 |
| settings | ViewerSettings | ビューアの設定。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*getFileStream*無効である。 |
| ArgumentNullException | スローされるタイミング*settings*無効である。 |

### 備考

**もっと詳しく知る**

* GroupDocs.Viewer でサポートされているファイル タイプの詳細: [GroupDocs.Viewer でサポートされているドキュメント形式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET 機能の詳細: [開発者ガイド](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 関連項目

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 名前空間 [GroupDocs.Viewer](../../viewer)
* 組み立て [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

の新しいインスタンスを初期化します[`Viewer`](../../viewer)class.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| getFileStream | Func`1 | 読み取り可能なストリームを返すメソッド。 |
| getLoadOptions | Func`1 | ドキュメント読み込みオプションを返すメソッド。 |
| settings | ViewerSettings | ビューアの設定。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*getFileStream*無効である。 |
| ArgumentNullException | スローされるタイミング*getLoadOptions*無効である。 |
| ArgumentNullException | スローされるタイミング*settings*無効である。 |

### 備考

**もっと詳しく知る**

* GroupDocs.Viewer でサポートされているファイル タイプの詳細: [GroupDocs.Viewer でサポートされているドキュメント形式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET 機能の詳細: [開発者ガイド](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* GroupDocs.Viewer for .NET を使用して暗号化されたドキュメントを読み込み、サードパーティのストレージからファイルを表示する方法の詳細: [GroupDocs.Viewer でドキュメントを読み込んで表示する方法](https://docs.groupdocs.com/display/viewernet/Loading)

### 関連項目

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 名前空間 [GroupDocs.Viewer](../../viewer)
* 組み立て [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

の新しいインスタンスを初期化します[`Viewer`](../../viewer)class.

```csharp
public Viewer(Stream stream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | ファイル ストリーム。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*stream*無効である。 |

### 備考

**もっと詳しく知る**

* GroupDocs.Viewer でサポートされているファイル タイプの詳細: [GroupDocs.Viewer でサポートされているドキュメント形式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET 機能の詳細: [開発者ガイド](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 関連項目

* class [Viewer](../../viewer)
* 名前空間 [GroupDocs.Viewer](../../viewer)
* 組み立て [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

の新しいインスタンスを初期化します[`Viewer`](../../viewer)class.

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | ファイル ストリーム。 |
| leaveOpen | Boolean | 真実 Viewer オブジェクトが破棄された後、ストリームを開いたままにします。さもないと、間違い. |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*stream*無効である。 |

### 備考

**もっと詳しく知る**

* GroupDocs.Viewer でサポートされているファイル タイプの詳細: [GroupDocs.Viewer でサポートされているドキュメント形式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET 機能の詳細: [開発者ガイド](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 関連項目

* class [Viewer](../../viewer)
* 名前空間 [GroupDocs.Viewer](../../viewer)
* 組み立て [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

の新しいインスタンスを初期化します[`Viewer`](../../viewer)class.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | ファイル ストリーム。 |
| loadOptions | LoadOptions | ドキュメントの読み込みオプション。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*stream*無効である。 |
| ArgumentNullException | スローされるタイミング*loadOptions*無効である。 |

### 備考

**もっと詳しく知る**

* GroupDocs.Viewer でサポートされているファイル タイプの詳細: [GroupDocs.Viewer でサポートされているドキュメント形式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET 機能の詳細: [開発者ガイド](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* GroupDocs.Viewer for .NET を使用して暗号化されたドキュメントを読み込み、サードパーティのストレージからファイルを表示する方法の詳細: [GroupDocs.Viewer でドキュメントを読み込んで表示する方法](https://docs.groupdocs.com/display/viewernet/Loading)

### 関連項目

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* 名前空間 [GroupDocs.Viewer](../../viewer)
* 組み立て [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

の新しいインスタンスを初期化します[`Viewer`](../../viewer)class.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | ファイル ストリーム。 |
| loadOptions | LoadOptions | ドキュメントの読み込みオプション。 |
| leaveOpen | Boolean | 真実 Viewer オブジェクトが破棄された後、ストリームを開いたままにします。さもないと、間違い. |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*stream*無効である。 |
| ArgumentNullException | スローされるタイミング*loadOptions*無効である。 |

### 備考

**もっと詳しく知る**

* GroupDocs.Viewer でサポートされているファイル タイプの詳細: [GroupDocs.Viewer でサポートされているドキュメント形式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET 機能の詳細: [開発者ガイド](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* GroupDocs.Viewer for .NET を使用して暗号化されたドキュメントを読み込み、サードパーティのストレージからファイルを表示する方法の詳細: [GroupDocs.Viewer でドキュメントを読み込んで表示する方法](https://docs.groupdocs.com/display/viewernet/Loading)

### 関連項目

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* 名前空間 [GroupDocs.Viewer](../../viewer)
* 組み立て [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

の新しいインスタンスを初期化します[`Viewer`](../../viewer)class.

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | ファイル ストリーム。 |
| settings | ViewerSettings | ビューアの設定。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*stream*無効である。 |
| ArgumentNullException | スローされるタイミング*settings*無効である。 |

### 備考

**もっと詳しく知る**

* GroupDocs.Viewer でサポートされているファイル タイプの詳細: [GroupDocs.Viewer でサポートされているドキュメント形式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET 機能の詳細: [開発者ガイド](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 関連項目

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 名前空間 [GroupDocs.Viewer](../../viewer)
* 組み立て [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

の新しいインスタンスを初期化します[`Viewer`](../../viewer)class.

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | ファイル ストリーム。 |
| settings | ViewerSettings | ビューアの設定。 |
| leaveOpen | Boolean | 真実 Viewer オブジェクトが破棄された後、ストリームを開いたままにします。さもないと、間違い. |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*stream*無効である。 |
| ArgumentNullException | スローされるタイミング*settings*無効である。 |

### 備考

**もっと詳しく知る**

* GroupDocs.Viewer でサポートされているファイル タイプの詳細: [GroupDocs.Viewer でサポートされているドキュメント形式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET 機能の詳細: [開発者ガイド](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 関連項目

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 名前空間 [GroupDocs.Viewer](../../viewer)
* 組み立て [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

の新しいインスタンスを初期化します[`Viewer`](../../viewer)class.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | ファイル ストリーム。 |
| loadOptions | LoadOptions | ドキュメントの読み込みオプション。 |
| settings | ViewerSettings | ビューアの設定。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*stream*無効である。 |
| ArgumentNullException | スローされるタイミング*loadOptions*無効である。 |
| ArgumentNullException | スローされるタイミング*settings*無効である。 |

### 備考

**もっと詳しく知る**

* GroupDocs.Viewer でサポートされているファイル タイプの詳細: [GroupDocs.Viewer でサポートされているドキュメント形式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET 機能の詳細: [開発者ガイド](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* GroupDocs.Viewer for .NET を使用して暗号化されたドキュメントを読み込み、サードパーティのストレージからファイルを表示する方法の詳細: [GroupDocs.Viewer でドキュメントを読み込んで表示する方法](https://docs.groupdocs.com/display/viewernet/Loading)

### 関連項目

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 名前空間 [GroupDocs.Viewer](../../viewer)
* 組み立て [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

の新しいインスタンスを初期化します[`Viewer`](../../viewer)class.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | ファイル ストリーム。 |
| loadOptions | LoadOptions | ドキュメントの読み込みオプション。 |
| settings | ViewerSettings | ビューアの設定。 |
| leaveOpen | Boolean | 真実 Viewer オブジェクトが破棄された後、ストリームを開いたままにします。さもないと、間違い. |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*stream*無効である。 |
| ArgumentNullException | スローされるタイミング*loadOptions*無効である。 |
| ArgumentNullException | スローされるタイミング*settings*無効である。 |

### 備考

**もっと詳しく知る**

* GroupDocs.Viewer でサポートされているファイル タイプの詳細: [GroupDocs.Viewer でサポートされているドキュメント形式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET 機能の詳細: [開発者ガイド](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* GroupDocs.Viewer for .NET を使用して暗号化されたドキュメントを読み込み、サードパーティのストレージからファイルを表示する方法の詳細: [GroupDocs.Viewer でドキュメントを読み込んで表示する方法](https://docs.groupdocs.com/display/viewernet/Loading)

### 関連項目

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 名前空間 [GroupDocs.Viewer](../../viewer)
* 組み立て [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

の新しいインスタンスを初期化します[`Viewer`](../../viewer)class.

```csharp
public Viewer(string filePath)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | レンダリングするファイルへのパス。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | スローされるタイミング*filePath*null または空です。 |

### 備考

**もっと詳しく知る**

* GroupDocs.Viewer でサポートされているファイル タイプの詳細: [GroupDocs.Viewer でサポートされているドキュメント形式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET 機能の詳細: [開発者ガイド](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 関連項目

* class [Viewer](../../viewer)
* 名前空間 [GroupDocs.Viewer](../../viewer)
* 組み立て [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

の新しいインスタンスを初期化します[`Viewer`](../../viewer)class.

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | レンダリングするファイルへのパス。 |
| settings | ViewerSettings | ビューアの設定。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | スローされるタイミング*filePath*null または空です。 |
| ArgumentNullException | スローされるタイミング*settings*無効である。 |

### 備考

**もっと詳しく知る**

* GroupDocs.Viewer でサポートされているファイル タイプの詳細: [GroupDocs.Viewer でサポートされているドキュメント形式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET 機能の詳細: [開発者ガイド](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 関連項目

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 名前空間 [GroupDocs.Viewer](../../viewer)
* 組み立て [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

の新しいインスタンスを初期化します[`Viewer`](../../viewer)class.

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | レンダリングするファイルへのパス。 |
| loadOptions | LoadOptions | ファイルを開くために使用されたオプション。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | スローされるタイミング*filePath*null または空です。 |
| ArgumentNullException | スローされるタイミング*loadOptions*無効である。 |

### 備考

**もっと詳しく知る**

* GroupDocs.Viewer でサポートされているファイル タイプの詳細: [GroupDocs.Viewer でサポートされているドキュメント形式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET 機能の詳細: [開発者ガイド](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* GroupDocs.Viewer for .NET を使用して暗号化されたドキュメントを読み込み、サードパーティのストレージからファイルを表示する方法の詳細: [GroupDocs.Viewer でドキュメントを読み込んで表示する方法](https://docs.groupdocs.com/display/viewernet/Loading)

### 関連項目

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* 名前空間 [GroupDocs.Viewer](../../viewer)
* 組み立て [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

の新しいインスタンスを初期化します[`Viewer`](../../viewer)class.

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | レンダリングするファイルへのパス。 |
| loadOptions | LoadOptions | ファイルを開くために使用されたオプション。 |
| settings | ViewerSettings | ビューアの設定。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | スローされるタイミング*filePath*null または空です。 |
| ArgumentNullException | スローされるタイミング*loadOptions*無効である。 |
| ArgumentNullException | スローされるタイミング*settings*無効である。 |

### 備考

**もっと詳しく知る**

* GroupDocs.Viewer でサポートされているファイル タイプの詳細: [GroupDocs.Viewer でサポートされているドキュメント形式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* GroupDocs.Viewer for .NET 機能の詳細: [開発者ガイド](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* GroupDocs.Viewer for .NET を使用して暗号化されたドキュメントを読み込み、サードパーティのストレージからファイルを表示する方法の詳細: [GroupDocs.Viewer でドキュメントを読み込んで表示する方法](https://docs.groupdocs.com/display/viewernet/Loading)

### 関連項目

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 名前空間 [GroupDocs.Viewer](../../viewer)
* 組み立て [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
