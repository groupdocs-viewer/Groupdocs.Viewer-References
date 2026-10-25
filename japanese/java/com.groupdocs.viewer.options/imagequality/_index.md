---
title: "ImageQuality"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "PDF 文書に含まれる出力 HTML の画像の品質。"
type: docs
weight: 41
url: /ja/java/com.groupdocs.viewer.options/imagequality/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ImageQuality extends Enum<ImageQuality>
```

PDF 文書に含まれる出力 HTML の画像の品質。


ImageQuality 列挙型は、PDF ドキュメントに含まれる出力 HTML の画像品質を表します
GroupDocs.Viewer コンポーネント内です。使用できるさまざまな画像品質レベルを提供します
生成された HTML 出力における画像のレンダリングと圧縮を制御します。


使用例:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 PdfOptions pdfOptions = htmlViewOptions.getPdfOptions();
 pdfOptions.setImageQuality(ImageQuality.HIGH);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [LOW](#LOW) | 許容できる品質と最高のパフォーマンスです。 |
|
|  | [MEDIUM](#MEDIUM) | 品質は向上しますが、パフォーマンスは低下します。 |
|
|  | [HIGH](#HIGH) | 最高の品質ですが、パフォーマンスは遅くなります。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### LOW {#LOW}
```
public static final ImageQuality LOW
```


許容できる品質と最高のパフォーマンスです。
この設定は画像品質よりもレンダリング速度を優先します。


### MEDIUM {#MEDIUM}
```
public static final ImageQuality MEDIUM
```


品質は向上しますが、パフォーマンスは低下します。
この設定は画像品質とレンダリング速度のバランスを提供します。


### HIGH {#HIGH}
```
public static final ImageQuality HIGH
```


最高の品質ですが、パフォーマンスは遅くなります。
この設定はレンダリング速度よりも画像品質を優先します。


### values() {#values--}
```
public static ImageQuality[] values()
```




**Returns:**
com.groupdocs.viewer.options.ImageQuality[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ImageQuality valueOf(String name)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String |  |

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality)
