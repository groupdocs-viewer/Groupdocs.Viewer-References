---
title: "FolderFontSource"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "TrueType フォントを含むフォルダーを表します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.viewer.fonts/folderfontsource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.fonts.FontSource](../../com.groupdocs.viewer.fonts/fontsource), com.aspose.ms.System.IEquatable
```
public final class FolderFontSource implements FontSource, System.IEquatable<FolderFontSource>
```

TrueType フォントを含むフォルダーを表します。


FolderFontSource クラスは、TrueType フォントが含まれるフォルダーの場所を指定するために使用されます。
これにより、GroupDocs.Viewer API が、ドキュメントのレンダリング目的で指定されたフォルダーに保存されているフォントにアクセスできるようになります。


使用例:

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [FolderFontSource(String folderPath, SearchOption searchOption)](#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-) | 新しいインスタンスを初期化します |
FolderFontSource
クラス。
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isEqualTo(FolderFontSource left, FolderFontSource right)](#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | 二つが |
FolderFontSource
オブジェクトは同じです。
|
|  | [isNotEqualTo(FolderFontSource left, FolderFontSource right)](#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | 二つが |
FolderFontSource
オブジェクトは同じではありません。
|
|  | [getFolderPath()](#getFolderPath--) | TrueType フォントが含まれるフォルダーへのパスを取得します。 |
|
|  | [getSearchOption()](#getSearchOption--) | 現在のフォルダーだけを検索するか、現在のフォルダーとすべてのサブフォルダーも検索するかを指定する検索オプションを取得します。 |
|
|  | [isRecursive()](#isRecursive--) | フォントが再帰的に検索されるかどうかをチェックします。 |
|
|  | [equals(FolderFontSource other)](#equals-com.groupdocs.viewer.fonts.FolderFontSource-) | 現在の |
FolderFontSource
が指定された
FolderFontSource
オブジェクト。
|
|  | [equals(Object o)](#equals-java.lang.Object-) | 現在の |
FolderFontSource
指定されたオブジェクトと同じです。
|
|  | [hashCode()](#hashCode--) | 現在の |
FolderFontSource
オブジェクト。
|
|  | [toString()](#toString--) | 現在のオブジェクトを表す文字列を返します。 |
|
### FolderFontSource(String folderPath, SearchOption searchOption) {#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-}
```
public FolderFontSource(String folderPath, SearchOption searchOption)
```


新しいインスタンスを初期化します
FolderFontSource
クラス。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | folderPath | java.lang.String | TrueType フォントが含まれるフォルダーへのパス。 |
|
|  | searchOption | [SearchOption](../../com.groupdocs.viewer.fonts/searchoption) | 現在のフォルダーを検索するか、現在のフォルダーとすべてのサブフォルダーを検索するかを指定します。 |
|

### isEqualTo(FolderFontSource left, FolderFontSource right) {#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isEqualTo(FolderFontSource left, FolderFontSource right)
```


二つが
FolderFontSource
オブジェクトは同じです。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | 左側の  FolderFontSource  オブジェクトです。 |
|
|  | right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | 右側の  FolderFontSource  オブジェクトです。 |
|

**Returns:**
boolean -  true  両方の  FolderFontSource  オブジェクトが同じ場合; それ以外の場合は  false .

### isNotEqualTo(FolderFontSource left, FolderFontSource right) {#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isNotEqualTo(FolderFontSource left, FolderFontSource right)
```


二つが
FolderFontSource
オブジェクトは同じではありません。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | 左側の  FolderFontSource  オブジェクトです。 |
|
|  | right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | 右側の  FolderFontSource  オブジェクトです。 |
|

**Returns:**
boolean -  true  両方の  FolderFontSource  オブジェクトが同じでない場合; それ以外の場合は  false .

### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


TrueType フォントが含まれるフォルダーへのパスを取得します。


**Returns:**
java.lang.String - TrueType フォントを含むフォルダーへのパスです。

### getSearchOption() {#getSearchOption--}
```
public SearchOption getSearchOption()
```


現在のフォルダーだけを検索するか、現在のフォルダーとすべてのサブフォルダーも検索するかを指定する検索オプションを取得します。


**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption) - the search option.

### isRecursive() {#isRecursive--}
```
public boolean isRecursive()
```


フォントが再帰的に検索されるかどうかをチェックします。


**Returns:**
boolean -  true  フォントが再帰的に検索される場合; それ以外の場合は  false .

### equals(FolderFontSource other) {#equals-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public boolean equals(FolderFontSource other)
```


現在の
FolderFontSource
が指定された
FolderFontSource
オブジェクト。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | 現在の  FolderFontSource  オブジェクトと比較するオブジェクトです。 |
|

**Returns:**
boolean -  true  両方の  FolderFontSource  オブジェクトが同じ場合; それ以外の場合は  false

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


現在の
FolderFontSource
指定されたオブジェクトと同じです。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | o | java.lang.Object | 現在の  FolderFontSource  オブジェクトと比較するオブジェクトです。 |
|

**Returns:**
boolean -  true  obj パラメータが FolderFontSource 型で、現在の  FolderFontSource  オブジェクトと同じ場合; それ以外の場合は  false

### hashCode() {#hashCode--}
```
public int hashCode()
```


現在の
FolderFontSource
オブジェクト。


**Returns:**
int - 現在の  FolderFontSource  オブジェクトのハッシュコードです。

### toString() {#toString--}
```
public String toString()
```


現在のオブジェクトを表す文字列を返します。


**Returns:**
java.lang.String - 現在のオブジェクトを表す文字列。

