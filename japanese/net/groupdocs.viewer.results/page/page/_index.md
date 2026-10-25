---
title: "Page"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "Pagegroupdocs.viewer.results/page クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.viewer.results/page/page/
---

## Page() {#constructor}

[`Page`](../../page) クラスの新しいインスタンスを初期化します。

```csharp
public Page()
```

### 関連項目

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool) {#constructor_1}

[`Page`](../../page) クラスの新しいインスタンスを初期化します。

```csharp
public Page(int number, bool visible)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 数値 | Int32 | ページ番号。 |
| 表示 | Boolean | ページの表示状態インジケータ。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *number* が 0 以下の場合にスローされます。 |

### 関連項目

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool) {#constructor_4}

[`Page`](../../page) クラスの新しいインスタンスを初期化します。

```csharp
public Page(int number, string name, bool visible)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 数値 | Int32 | ページ番号。 |
| 名前 | String | ワークシートまたはページの名前。 |
| 表示 | Boolean | ページの表示状態インジケータ。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *number* が 0 以下の場合にスローされます。 |

### 関連項目

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int) {#constructor_2}

[`Page`](../../page) クラスの新しいインスタンスを初期化します。

```csharp
public Page(int number, bool visible, int width, int height)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 数値 | Int32 | ページ番号。 |
| 表示 | Boolean | ページの表示状態インジケータ。 |
| width | Int32 | JPG または PNG として表示する場合のページの幅（ピクセル単位）。 |
| height | Int32 | JPG または PNG として表示する場合のページの高さ（ピクセル単位）。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *number* が 0 以下の場合にスローされます。 |
| ArgumentException | *width* が 0 以下の場合にスローされます。 |
| ArgumentException | *height* が 0 以下の場合にスローされます。 |

### 関連項目

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int) {#constructor_5}

[`Page`](../../page) クラスの新しいインスタンスを初期化します。

```csharp
public Page(int number, string name, bool visible, int width, int height)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 数値 | Int32 | ページ番号。 |
| 名前 | String | ワークシートまたはページの名前。 |
| 表示 | Boolean | ページの表示状態インジケータ。 |
| width | Int32 | JPG または PNG として表示する場合のページの幅（ピクセル単位）。 |
| height | Int32 | JPG または PNG として表示する場合のページの高さ（ピクセル単位）。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *number* が 0 以下の場合にスローされます。 |
| ArgumentException | *width* が 0 以下の場合にスローされます。 |
| ArgumentException | *height* が 0 以下の場合にスローされます。 |

### 関連項目

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int, List&lt;Line&gt;) {#constructor_3}

[`Page`](../../page) クラスの新しいインスタンスを初期化します。

```csharp
public Page(int number, bool visible, int width, int height, List<Line> lines)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 数値 | Int32 | ページ番号。 |
| 表示 | Boolean | ページの表示状態インジケータ。 |
| width | Int32 | JPG または PNG として表示する場合のページの幅（ピクセル単位）。 |
| height | Int32 | JPG または PNG として表示する場合のページの高さ（ピクセル単位）。 |
| 行 | List`1 | テキスト抽出が有効な状態で JPG または PNG として表示する場合のページに含まれる行。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *number* が 0 以下の場合にスローされます。 |
| ArgumentException | *width* が 0 以下の場合にスローされます。 |
| ArgumentException | *height* が 0 以下の場合にスローされます。 |
| ArgumentNullException | *lines* が null の場合にスローされます。 |

### 関連項目

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int, List&lt;Line&gt;) {#constructor_6}

[`Page`](../../page) クラスの新しいインスタンスを初期化します。

```csharp
public Page(int number, string name, bool visible, int width, int height, List<Line> lines)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 数値 | Int32 | ページ番号。 |
| 名前 | String | ワークシートまたはページの名前。 |
| 表示 | Boolean | ページの表示状態インジケータ。 |
| width | Int32 | JPG または PNG として表示する場合のページの幅（ピクセル単位）。 |
| height | Int32 | JPG または PNG として表示する場合のページの高さ（ピクセル単位）。 |
| 行 | List`1 | テキスト抽出が有効な状態で JPG または PNG として表示する場合のページに含まれる行。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *number* が 0 以下の場合にスローされます。 |
| ArgumentException | *width* が 0 以下の場合にスローされます。 |
| ArgumentException | *height* が 0 以下の場合にスローされます。 |
| ArgumentNullException | *lines* が null の場合にスローされます。 |

### 関連項目

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
