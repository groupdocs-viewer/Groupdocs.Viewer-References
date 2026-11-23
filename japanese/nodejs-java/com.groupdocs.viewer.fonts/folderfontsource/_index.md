---
title: "FolderFontSource"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "TrueType フォントを含むフォルダーを表します。"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.viewer.fonts/folderfontsource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.fonts.FontSource](../../com.groupdocs.viewer.fonts/fontsource), com.aspose.ms.System.IEquatable
```
public final class FolderFontSource implements FontSource, System.IEquatable<FolderFontSource>
```

TrueType フォントを含むフォルダーを表します。

FolderFontSource クラスは、TrueType フォントを含むフォルダーの場所を指定するために使用されます。これにより、GroupDocs.Viewer API が指定されたフォルダーに保存されたフォントにアクセスし、ドキュメントのレンダリングに利用できます。

使用例:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [FolderFontSource(String folderPath, SearchOption searchOption)](#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-) | FolderFontSource クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isEqualTo(FolderFontSource left, FolderFontSource right)](#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | 二つの FolderFontSource オブジェクトが同じかどうかを判断します。 |
| [isNotEqualTo(FolderFontSource left, FolderFontSource right)](#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | 二つの FolderFontSource オブジェクトが異なるかどうかを判断します。 |
| [getFolderPath()](#getFolderPath--) | TrueType フォントを含むフォルダーへのパスを取得します。 |
| [getSearchOption()](#getSearchOption--) | 現在のフォルダーのみ、または現在のフォルダーとすべてのサブフォルダーを検索するかを指定する検索オプションを取得します。 |
| [isRecursive()](#isRecursive--) | フォントが再帰的に検索されるかどうかを確認します。 |
| [equals(FolderFontSource other)](#equals-com.groupdocs.viewer.fonts.FolderFontSource-) | 現在の FolderFontSource が指定された FolderFontSource オブジェクトと同じかどうかを判断します。 |
| [equals(Object o)](#equals-java.lang.Object-) | 現在の FolderFontSource が指定されたオブジェクトと同じかどうかを判断します。 |
| [hashCode()](#hashCode--) | 現在の FolderFontSource オブジェクトのハッシュコードを返します。 |
| [toString()](#toString--) | 現在のオブジェクトを表す文字列を返します。 |
### FolderFontSource(String folderPath, SearchOption searchOption) {#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-}
```
public FolderFontSource(String folderPath, SearchOption searchOption)
```


FolderFontSource クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| folderPath | java.lang.String | TrueType フォントを含むフォルダーへのパス。 |
| searchOption | [SearchOption](../../com.groupdocs.viewer.fonts/searchoption) | 現在のフォルダーのみ、または現在のフォルダーとすべてのサブフォルダーを検索するかを指定します。 |

### isEqualTo(FolderFontSource left, FolderFontSource right) {#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isEqualTo(FolderFontSource left, FolderFontSource right)
```


二つの FolderFontSource オブジェクトが同じかどうかを判断します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | 左側の FolderFontSource オブジェクト。 |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | 右側の FolderFontSource オブジェクト。 |

**Returns:**
boolean - 両方の FolderFontSource オブジェクトが同じ場合は true、そうでない場合は false。
### isNotEqualTo(FolderFontSource left, FolderFontSource right) {#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isNotEqualTo(FolderFontSource left, FolderFontSource right)
```


二つの FolderFontSource オブジェクトが異なるかどうかを判断します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | 左側の FolderFontSource オブジェクト。 |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | 右側の FolderFontSource オブジェクト。 |

**Returns:**
boolean - 両方の FolderFontSource オブジェクトが異なる場合は true、そうでない場合は false。
### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


TrueType フォントを含むフォルダーへのパスを取得します。

**Returns:**
java.lang.String - TrueType フォントを含むフォルダーへのパスです。
### getSearchOption() {#getSearchOption--}
```
public SearchOption getSearchOption()
```


現在のフォルダーのみ、または現在のフォルダーとすべてのサブフォルダーを検索するかを指定する検索オプションを取得します。

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption) - the search option.
### isRecursive() {#isRecursive--}
```
public boolean isRecursive()
```


フォントが再帰的に検索されるかどうかを確認します。

**Returns:**
boolean - フォントを再帰的に検索する場合は true、そうでない場合は false。
### equals(FolderFontSource other) {#equals-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public boolean equals(FolderFontSource other)
```


現在の FolderFontSource が指定された FolderFontSource オブジェクトと同じかどうかを判断します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | 現在の  FolderFontSource  オブジェクトと比較するオブジェクトです。 |

**Returns:**
boolean - 両方の  FolderFontSource  オブジェクトが同じ場合は true、そうでない場合は false。
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


現在の FolderFontSource が指定されたオブジェクトと同じかどうかを判断します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| o | java.lang.Object | 現在の  FolderFontSource  オブジェクトと比較するオブジェクトです。 |

**Returns:**
boolean -  obj パラメータが  FolderFontSource  型であり、現在の  FolderFontSource  オブジェクトと同じ場合は true、そうでない場合は false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


現在の FolderFontSource オブジェクトのハッシュコードを返します。

**Returns:**
int - 現在の  FolderFontSource  オブジェクトのハッシュコードです。
### toString() {#toString--}
```
public String toString()
```


現在のオブジェクトを表す文字列を返します。

**Returns:**
java.lang.String - 現在のオブジェクトを表す文字列。
