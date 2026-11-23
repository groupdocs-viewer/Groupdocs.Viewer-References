---
title: "Resolution"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "画像の解像度を出力ドキュメントに設定するオプションを提供します。"
type: docs
weight: 44
url: /ja/nodejs-java/com.groupdocs.viewer.options/resolution/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Resolution extends Enum<Resolution>
```

画像の解像度を設定するオプションを提供します：出力ドキュメント。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [DPI_330](#DPI-330) | 高精細 (HD) ディスプレイ向けの高品質です。 |
| [DPI_220](#DPI-220) | ほとんどのプリンターと画面で優れた品質です。 |
| [DPI_150](#DPI-150) | ウェブページやプロジェクターに適しています。 |
| [DPI_96](#DPI-96) | ウェブページやプロジェクターに適しています。 |
| [DPI_72](#DPI-72) | デフォルトの圧縮レベルです。 |
| [DOCUMENT_RESOLUTION](#DOCUMENT-RESOLUTION) | デフォルトの圧縮レベル - ドキュメントと同様です。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getValue()](#getValue--) | 品質 DPI。 |
| [getSlidesPicturesResolution()](#getSlidesPicturesResolution--) | オプションの Resolution クラスから Aspose.Slides の画像解像度を取得します。 |
### DPI_330 {#DPI-330}
```
public static final Resolution DPI_330
```


高精細 (HD) ディスプレイ向けの高品質です。

### DPI_220 {#DPI-220}
```
public static final Resolution DPI_220
```


ほとんどのプリンターと画面で優れた品質です。

### DPI_150 {#DPI-150}
```
public static final Resolution DPI_150
```


ウェブページやプロジェクターに適しています。

### DPI_96 {#DPI-96}
```
public static final Resolution DPI_96
```


ウェブページやプロジェクターに適しています。

### DPI_72 {#DPI-72}
```
public static final Resolution DPI_72
```


デフォルトの圧縮レベルです。

### DOCUMENT_RESOLUTION {#DOCUMENT-RESOLUTION}
```
public static final Resolution DOCUMENT_RESOLUTION
```


デフォルトの圧縮レベル - ドキュメントと同様です。

### values() {#values--}
```
public static Resolution[] values()
```




**Returns:**
com.groupdocs.viewer.options.Resolution[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Resolution valueOf(String name)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String |  |

**Returns:**
com.groupdocs.viewer.options.Resolution
### getValue() {#getValue--}
```
public int getValue()
```


品質 DPI。

**Returns:**
int
### getSlidesPicturesResolution() {#getSlidesPicturesResolution--}
```
public int getSlidesPicturesResolution()
```


オプションの Resolution クラスから Aspose.Slides の画像解像度を取得します。

**Returns:**
int
