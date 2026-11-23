---
title: "PdfViewInfo"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "PDF ドキュメントのビュー情報を表します。"
type: docs
weight: 22
url: /ja/nodejs-java/com.groupdocs.viewer.results/pdfviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface PdfViewInfo extends ViewInfo
```

PDF ドキュメントのビュー情報を表します。

PdfViewInfo インターフェイスは、GroupDocs.Viewer コンポーネント内の PDF ドキュメントに対するビュー情報へのアクセスと操作のための契約を定義します。印刷の許可などの情報を取得するメソッドやその他のプロパティを提供します。

使用例:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     final PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is PdfViewInfoImpl.*
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isPrintingAllowed()](#isPrintingAllowed--) | ドキュメントの印刷が許可されているかを確認します。 |
| [setPrintingAllowed(boolean allowPrinting)](#setPrintingAllowed-boolean-) | ドキュメントの印刷が許可されているかどうかを設定します。 |
### isPrintingAllowed() {#isPrintingAllowed--}
```
public abstract boolean isPrintingAllowed()
```


ドキュメントの印刷が許可されているかを確認します。

**Returns:**
boolean - 印刷が許可されている場合は true、そうでない場合は false。
### setPrintingAllowed(boolean allowPrinting) {#setPrintingAllowed-boolean-}
```
public abstract void setPrintingAllowed(boolean allowPrinting)
```


ドキュメントの印刷が許可されているかどうかを設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| allowPrinting | boolean | true は印刷を許可し、false はそれ以外の場合です。 |

