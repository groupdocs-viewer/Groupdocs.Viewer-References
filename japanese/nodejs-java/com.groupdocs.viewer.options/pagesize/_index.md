---
title: "PageSize"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "ページのサイズです。"
type: docs
weight: 42
url: /ja/nodejs-java/com.groupdocs.viewer.options/pagesize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PageSize extends Enum<PageSize>
```

ページのサイズです。

PageSize 列挙型は、GroupDocs.Viewer コンポーネントで使用できるさまざまなページサイズを表します。さまざまな文書レンダリングシナリオでページの寸法を指定するために使用できる事前定義されたページサイズのセットを提供します。

使用例:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = htmlViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## フィールド

| フィールド | 説明 |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | デフォルトの、未指定のページサイズ。 |
| [LETTER](#LETTER) | Letter ページのサイズ（ポイント）は 792 x 612 です。 |
| [LEDGER](#LEDGER) | A0 ページのサイズ（ポイント）は 3371 x 2384 です。 |
| [A0](#A0) | A1 ページのサイズ（ポイント）は 2384 x 1685 です。 |
| [A1](#A1) | A2 ページのサイズ（ポイント）は 1684 x 1190 です。 |
| [A2](#A2) | A3 ページのサイズ（ポイント）は 1190 x 842 です。 |
| [A3](#A3) | A3 ページのサイズ（ポイント）は 1190 x 842 です。 |
| [A4](#A4) | A4 ページのサイズ（ポイント）は 842 x 595 です。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final PageSize UNSPECIFIED
```


デフォルトの、未指定のページサイズです。このサイズは、特定のページサイズが指定されていない場合に使用されます。

### LETTER {#LETTER}
```
public static final PageSize LETTER
```


Letter ページのサイズ（ポイント）は 792 x 612 です。このページサイズは北米での手紙や文書に一般的に使用されます。

### LEDGER {#LEDGER}
```
public static final PageSize LEDGER
```


A0 ページのサイズ（ポイント）は 3371 x 2384 です。この大きなページサイズは ISO 216 国際規格の一部です。

### A0 {#A0}
```
public static final PageSize A0
```


A1 ページのサイズ（ポイント）は 2384 x 1685 です。このページサイズは ISO 216 国際規格の一部です。

### A1 {#A1}
```
public static final PageSize A1
```


A2 ページのサイズ（ポイント）は 1684 x 1190 です。このページサイズは ISO 216 国際規格の一部です。

### A2 {#A2}
```
public static final PageSize A2
```


A3 ページのサイズ（ポイント）は 1190 x 842 です。このページサイズは ISO 216 国際規格の一部です。

### A3 {#A3}
```
public static final PageSize A3
```


A3 ページのサイズ（ポイント）は 1190 x 842 です。このページサイズは ISO 216 国際規格の一部です。

### A4 {#A4}
```
public static final PageSize A4
```


A4 ページのサイズ（ポイント）は 842 x 595 です。このページサイズは ISO 216 国際規格の一部です。

### values() {#values--}
```
public static PageSize[] values()
```




**Returns:**
com.groupdocs.viewer.options.PageSize[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PageSize valueOf(String name)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String |  |

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize)
