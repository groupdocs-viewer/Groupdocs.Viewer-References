---
title: "PdfViewInfo"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "PdfViewInfogroupdocs.viewer.results/pdfviewinfo クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.viewer.results/pdfviewinfo/pdfviewinfo/
---

## PdfViewInfo() {#constructor}

[`PdfViewInfo`](../../pdfviewinfo) クラスの新しいインスタンスを初期化します。

```csharp
public PdfViewInfo()
```

### 関連項目

* class [PdfViewInfo](../../pdfviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewInfo(FileType, List&lt;Page&gt;, bool) {#constructor_1}

[`PdfViewInfo`](../../pdfviewinfo) クラスの新しいインスタンスを初期化します。

```csharp
public PdfViewInfo(FileType fileType, List<Page> pages, bool printingAllowed)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fileType | FileType | ファイルのタイプです。 |
| ページ | List`1 | 表示するページの一覧です。 |
| printingAllowed | Boolean | 印刷許可インジケータです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pages* が null のときにスローされます。 |

### 関連項目

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [PdfViewInfo](../../pdfviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
