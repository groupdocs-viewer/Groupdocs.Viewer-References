---
title: "PdfViewInfo"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "PDFドキュメントのビュー情報を表します。"
type: docs
weight: 24
url: /ja/java/com.groupdocs.viewer.results/pdfviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface PdfViewInfo extends ViewInfo
```

PDFドキュメントのビュー情報を表します。


PdfViewInfoインターフェイスは、ビュー情報へのアクセスと操作のための契約を定義します。
GroupDocs.ViewerコンポーネントのPDFドキュメント用です。情報を取得するメソッドを提供します。
印刷の許可やその他のプロパティなど。


使用例:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     final PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is PdfViewInfoImpl.*

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isPrintingAllowed()](#isPrintingAllowed--) | ドキュメントの印刷が許可されているかを確認します。 |
|
|  | [setPrintingAllowed(boolean allowPrinting)](#setPrintingAllowed-boolean-) | ドキュメントの印刷が許可されているかを設定します。 |
|
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


ドキュメントの印刷が許可されているかを設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | allowPrinting | boolean | true は印刷を許可し、false はそれ以外です。 |
|

