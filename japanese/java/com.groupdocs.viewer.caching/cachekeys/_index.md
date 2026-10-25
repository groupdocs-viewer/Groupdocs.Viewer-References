---
title: "CacheKeys"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "キャッシュエントリの一意識別子を取得するメソッドを提供します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.viewer.caching/cachekeys/
---
**Inheritance:**
java.lang.Object
```
public class CacheKeys
```

キャッシュエントリの一意識別子を取得するメソッドを提供します。


このクラスは、ドキュメントパス、レンダリングオプション、リソース名など、さまざまなパラメータに基づいてキャッシュキーを生成できるようにします。
これらのキャッシュキーは、効率的なドキュメントレンダリングのためにキャッシュデータを保存および取得するために使用できます。


使用例:

````

 // Generate a cache key for a file
 String fileKey = CacheKeys.getFileKey("filename.pdf");

 // Generate a cache key for a page
 String pageKey = CacheKeys.getPageKey(pageNumber, FileType.HTML.getExtension());

 // Generate a cache key for a resource
 Resource resource = new Resource("styles.css", false);
 String pageKey = CacheKeys.getResourceKey(pageNumber, resource);
 
````


## フィールド

| フィールド | 説明 |
| --- | --- |
| [PAGE_NUMBER](#PAGE-NUMBER) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getAttachmentsKey()](#getAttachmentsKey--) | コレクションの [Attachment](../../com.groupdocs.viewer.results/attachment) オブジェクトを表すキャッシュエントリの一意識別子を返します。 |
|
|  | [getAttachmentKey(String attachmentId)](#getAttachmentKey-java.lang.String-) | 添付ファイルを表すキャッシュエントリの一意識別子を取得します。 |
|
|  | [getViewInfoKey()](#getViewInfoKey--) | [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) オブジェクトを表すキャッシュエントリの一意識別子を取得します。 |
|
|  | [getFileInfoKey()](#getFileInfoKey--) | [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) オブジェクトを表すキャッシュエントリの一意識別子を取得します。 |
|
|  | [getFileKey(String extension)](#getFileKey-java.lang.String-) | ファイルを表すキャッシュエントリの一意識別子を取得します。 |
|
|  | [getPageKey(int pageNumber, String extension)](#getPageKey-int-java.lang.String-) | ページファイルを表すキャッシュエントリの一意識別子を取得します。 |
|
|  | [getResourceKey(int pageNumber, Resource resource)](#getResourceKey-int-com.groupdocs.viewer.results.Resource-) | [Resource](../../com.groupdocs.viewer.results/resource) オブジェクトを表すキャッシュエントリの一意識別子を返します。 |
|
|  | [getResourceFilter(int pageNumber)](#getResourceFilter-int-) | [Resource](../../com.groupdocs.viewer.results/resource) オブジェクトを表すキャッシュエントリを検索するためのフィルタ文字列を返します。 |
|
### PAGE_NUMBER {#PAGE-NUMBER}
```
public static final String PAGE_NUMBER
```


### getAttachmentsKey() {#getAttachmentsKey--}
```
public static String getAttachmentsKey()
```


コレクションの [Attachment](../../com.groupdocs.viewer.results/attachment) オブジェクトを表すキャッシュエントリの一意識別子を返します。


**Returns:**
java.lang.String - 添付ファイルキャッシュエントリの一意識別子です。

### getAttachmentKey(String attachmentId) {#getAttachmentKey-java.lang.String-}
```
public static String getAttachmentKey(String attachmentId)
```


添付ファイルを表すキャッシュエントリの一意識別子を取得します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | attachmentId | java.lang.String | 添付ファイルの一意識別子（単一ファイルのコンテキスト内）。 |
|

**Returns:**
java.lang.String - 添付ファイルキャッシュエントリの一意識別子です。

### getViewInfoKey() {#getViewInfoKey--}
```
public static String getViewInfoKey()
```


[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) オブジェクトを表すキャッシュエントリの一意識別子を取得します。


**Returns:**
java.lang.String - キャッシュエントリの一意識別子です。

### getFileInfoKey() {#getFileInfoKey--}
```
public static String getFileInfoKey()
```


[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) オブジェクトを表すキャッシュエントリの一意識別子を取得します。


**Returns:**
java.lang.String - [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) オブジェクトを表すキャッシュエントリの一意識別子です。

### getFileKey(String extension) {#getFileKey-java.lang.String-}
```
public static String getFileKey(String extension)
```


ファイルを表すキャッシュエントリの一意識別子を取得します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | extension | java.lang.String | ファイル名のサフィックス（ピリオド「.」を含む）例:".doc"。 |
|

**Returns:**
java.lang.String - ファイルを表すキャッシュエントリの一意識別子です。

### getPageKey(int pageNumber, String extension) {#getPageKey-int-java.lang.String-}
```
public static String getPageKey(int pageNumber, String extension)
```


ページファイルを表すキャッシュエントリの一意識別子を取得します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | pageNumber | int | ページ番号です。 |
|
|  | extension | java.lang.String | ファイル名のサフィックス（ピリオド「.」を含む）例:".doc"。 |
|

**Returns:**
java.lang.String - ページファイルを表すキャッシュエントリの一意識別子です。

### getResourceKey(int pageNumber, Resource resource) {#getResourceKey-int-com.groupdocs.viewer.results.Resource-}
```
public static String getResourceKey(int pageNumber, Resource resource)
```


[Resource](../../com.groupdocs.viewer.results/resource) オブジェクトを表すキャッシュエントリの一意識別子を返します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | pageNumber | int | ページ番号です。 |
|
|  | resource | [Resource](../../com.groupdocs.viewer.results/resource) | HTML リソースです。 |
|

**Returns:**
java.lang.String - キャッシュエントリの一意識別子です。

### getResourceFilter(int pageNumber) {#getResourceFilter-int-}
```
public static String getResourceFilter(int pageNumber)
```


[Resource](../../com.groupdocs.viewer.results/resource) オブジェクトを表すキャッシュエントリを検索するためのフィルタ文字列を返します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | pageNumber | int | ページ番号です。 |
|

**Returns:**
java.lang.String - キャッシュエントリを検索するフィルタ文字列です。

