---
title: "FileCache"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "ローカルのディスク上キャッシュを表します。"
type: docs
weight: 11
url: /ja/nodejs-java/com.groupdocs.viewer.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.caching.Cache](../../com.groupdocs.viewer.caching/cache)
```
public class FileCache implements Cache
```

ローカルのディスク上キャッシュを表します。

FileCache クラスは GroupDocs.Viewer コンポーネント内のローカルディスクキャッシュを表します。ディスク上にキャッシュデータを保存および取得する機能を提供し、効率的なドキュメントレンダリングを実現します。

使用例:

```

 FileCache fileCache = new FileCache(cachePath, cacheSubFolder);

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setCache(fileCache);

 try (Viewer viewer = new Viewer(documentPath, viewerSettings)) {
     // Use the viewer object for document rendering
 }
 
```

FileCache を使用するには、このクラスのインスタンスを作成し、ViewerSettings オブジェクトに渡す必要があります。その後、Viewer オブジェクトはドキュメントのレンダリング中にキャッシュ目的で FileCache を使用します。

***Note:** The FileCache is just one of the cache implementations provided by GroupDocs.Viewer. You can also implement your own custom cache by implementing the Cache interface.*
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [FileCache(String cachePath)](#FileCache-java.lang.String-) | FileCache クラスの新しいインスタンスを作成します。 |
| [FileCache(Path cachePath)](#FileCache-java.nio.file.Path-) | FileCache クラスの新しいインスタンスを作成します。 |
| [FileCache(String cachePath, String cacheSubFolder)](#FileCache-java.lang.String-java.lang.String-) | FileCache クラスの新しいインスタンスを作成します。 |
| [FileCache(Path cachePath, String cacheSubFolder)](#FileCache-java.nio.file.Path-java.lang.String-) | FileCache クラスの新しいインスタンスを作成します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [CACHE_PATH](#CACHE-PATH) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCachePath()](#getCachePath--) | キャッシュフォルダーへの相対パスまたは絶対パスを取得します。 |
| [getCacheSubFolder()](#getCacheSubFolder--) | キャッシュパスに追加するサブフォルダーです。 |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | データをローカルディスクにシリアライズします。 |
| [<T>get(String key, Class<T> clazz)](#-T-get-java.lang.String-java.lang.Class-T--) | このキーに関連付けられたデータが存在すればデシリアライズします。 |
| [getKeys(String filter)](#getKeys-java.lang.String-) | ファイル名にフィルターが含まれるすべてのファイル名を返します。 |
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


FileCache クラスの新しいインスタンスを作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cachePath | java.lang.String | ドキュメントキャッシュが保存される相対パスまたは絶対パスです。 |

### FileCache(Path cachePath) {#FileCache-java.nio.file.Path-}
```
public FileCache(Path cachePath)
```


FileCache クラスの新しいインスタンスを作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cachePath | java.nio.file.Path | ドキュメントキャッシュが保存される相対パスまたは絶対パスです。 |

### FileCache(String cachePath, String cacheSubFolder) {#FileCache-java.lang.String-java.lang.String-}
```
public FileCache(String cachePath, String cacheSubFolder)
```


FileCache クラスの新しいインスタンスを作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cachePath | java.lang.String | ドキュメントキャッシュが保存される相対パスまたは絶対パスです。 |
| cacheSubFolder | java.lang.String | cachePath に追加するサブフォルダーです。 |

### FileCache(Path cachePath, String cacheSubFolder) {#FileCache-java.nio.file.Path-java.lang.String-}
```
public FileCache(Path cachePath, String cacheSubFolder)
```


FileCache クラスの新しいインスタンスを作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cachePath | java.nio.file.Path | ドキュメントキャッシュが保存される相対パスまたは絶対パスです。 |
| cacheSubFolder | java.lang.String | cachePath に追加するサブフォルダーです。 |

### CACHE_PATH {#CACHE-PATH}
```
public static final String CACHE_PATH
```


### getCachePath() {#getCachePath--}
```
public final String getCachePath()
```


キャッシュフォルダーへの相対パスまたは絶対パスを取得します。

**Returns:**
java.lang.String - キャッシュフォルダーへのパス。
### getCacheSubFolder() {#getCacheSubFolder--}
```
public final String getCacheSubFolder()
```


キャッシュパスに追加するサブフォルダーです。

**Returns:**
java.lang.String - 追加するサブフォルダー。
### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public final void set(String key, Object value)
```


データをローカルディスクにシリアライズします。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| key | java.lang.String | キャッシュエントリの一意の識別子です。 |
| value | java.lang.Object | シリアライズするオブジェクトです。 |

### <T>get(String key, Class<T> clazz) {#-T-get-java.lang.String-java.lang.Class-T--}
```
public final T <T>get(String key, Class<T> clazz)
```


このキーに関連付けられたデータが存在すればデシリアライズします。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| key | java.lang.String | 要求されたエントリを識別するキーです。 |
| clazz | java.lang.Class<T> | 期待される値のクラスです。 |

**Returns:**
T - 見つかった値または null。
### getKeys(String filter) {#getKeys-java.lang.String-}
```
public final List<String> getKeys(String filter)
```


ファイル名にフィルターが含まれるすべてのファイル名を返します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filter | java.lang.String | 使用するフィルターです。 |

**Returns:**
java.util.List<java.lang.String> - ファイル名にフィルターが含まれるファイル名。
