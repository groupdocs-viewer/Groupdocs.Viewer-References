---
title: "Rotation"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "ページの回転角度（時計回り）を度数で含みます。"
type: docs
weight: 45
url: /ja/java/com.groupdocs.viewer.options/rotation/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Rotation extends Enum<Rotation>
```

ページの回転角度（時計回り）を含みます。


Rotation 列挙型は、GroupDocs.Viewer コンポーネント内のページに対するさまざまな回転角度を表します。
事前定義された回転オプションのセットを提供し、回転角度を指定するために使用できます。
さまざまなドキュメント閲覧または変換シナリオでページをレンダリングするために使用されます。


使用例:

````

 PdfViewOptions pdfViewOptions = new PdfViewOptions();

 pdfViewOptions.rotatePage(1, Rotation.ON_90_DEGREE);
 pdfViewOptions.rotatePage(2, Rotation.ON_180_DEGREE);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [ON_90_DEGREE](#ON-90-DEGREE) | 90 度のページ回転です。 |
|
|  | [ON_180_DEGREE](#ON-180-DEGREE) | 180 度のページ回転です。 |
|
|  | [ON_270_DEGREE](#ON-270-DEGREE) | 270 度のページ回転です。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### ON_90_DEGREE {#ON-90-DEGREE}
```
public static final Rotation ON_90_DEGREE
```


90 度のページ回転です。
この回転は、ページの時計回り 90 度回転を表します。


### ON_180_DEGREE {#ON-180-DEGREE}
```
public static final Rotation ON_180_DEGREE
```


180 度のページ回転です。
この回転は、ページの時計回り 180 度回転を表します。


### ON_270_DEGREE {#ON-270-DEGREE}
```
public static final Rotation ON_270_DEGREE
```


270 度のページ回転です。
この回転は、ページの時計回り 270 度回転を表します。


### values() {#values--}
```
public static Rotation[] values()
```




**Returns:**
com.groupdocs.viewer.options.Rotation[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Rotation valueOf(String name)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String |  |

**Returns:**
[Rotation](../../com.groupdocs.viewer.options/rotation)
