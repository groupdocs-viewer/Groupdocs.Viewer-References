---
title: "ViewerSettings"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "Viewer コンポーネントの動作をカスタマイズするための設定を定義します。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.viewer/viewersettings/
---
**Inheritance:**
java.lang.Object
```
public class ViewerSettings
```

Viewer コンポーネントの動作をカスタマイズするための設定を定義します。


ViewerSettings クラスは、ドキュメントのレンダリング処理中に GroupDocs.Viewer コンポーネントの動作をカスタマイズするためのオプションとプロパティを提供します。
このクラスを使用して、ロガーやカスタムキャッシュ実装など、さまざまな設定を指定できます。


使用例:

````

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setLogger(new ConsoleLogger(false, true));

 try (Viewer viewer = new Viewer("source.pdf", viewerSettings)) {
     // Document processing
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [ViewerSettings(Cache cache, ILogger logger)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-) | 新しいインスタンスを初期化します |
ViewerSettings
クラス。
|
|  | [ViewerSettings(ILogger logger)](#ViewerSettings-com.groupdocs.foundation.logging.ILogger-) | 新しいインスタンスを初期化します |
ViewerSettings
クラス。
|
|  | [ViewerSettings(Cache cache)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-) | 新しいインスタンスを初期化します |
ViewerSettings
クラス。
|
|  | [ViewerSettings()](#ViewerSettings--) | 新しいインスタンスを初期化します |
ViewerSettings
クラス。
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getLogger()](#getLogger--) | ロギングに使用されるロガー実装（エラー、警告、トレース）を取得します。 |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | ロギングに使用されるロガー実装（エラー、警告、トレース）を設定します。 |
|
|  | [getCache()](#getCache--) | レンダリング結果の保存に使用されるキャッシュ実装を取得します。 |
|
|  | [setCache(Cache cache)](#setCache-com.groupdocs.viewer.caching.Cache-) | レンダリング結果の保存に使用されるキャッシュ実装を設定します。 |
|
### ViewerSettings(Cache cache, ILogger logger) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(Cache cache, ILogger logger)
```


新しいインスタンスを初期化します
ViewerSettings
クラス。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | キャッシュ。 |
|
|  | ロガー | com.groupdocs.foundation.logging.ILogger | ロガー。 |
|

### ViewerSettings(ILogger logger) {#ViewerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(ILogger logger)
```


新しいインスタンスを初期化します
ViewerSettings
クラス。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | ロガー | com.groupdocs.foundation.logging.ILogger | ロガー。 |
|

### ViewerSettings(Cache cache) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-}
```
public ViewerSettings(Cache cache)
```


新しいインスタンスを初期化します
ViewerSettings
クラス。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | キャッシュ。 |
|

### ViewerSettings() {#ViewerSettings--}
```
public ViewerSettings()
```


新しいインスタンスを初期化します
ViewerSettings
クラス。


### getLogger() {#getLogger--}
```
public ILogger getLogger()
```


ロギングに使用されるロガー実装（エラー、警告、トレース）を取得します。


**Returns:**
com.groupdocs.foundation.logging.ILogger - ロガー実装です。

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public void setLogger(ILogger logger)
```


ロギングに使用されるロガー実装（エラー、警告、トレース）を設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | ロガー | com.groupdocs.foundation.logging.ILogger | 設定するロガー実装。 |
|

### getCache() {#getCache--}
```
public final Cache getCache()
```


レンダリング結果の保存に使用されるキャッシュ実装を取得します。


**Returns:**
[Cache](../../com.groupdocs.viewer.caching/cache) - the cache implementation.

### setCache(Cache cache) {#setCache-com.groupdocs.viewer.caching.Cache-}
```
public void setCache(Cache cache)
```


レンダリング結果の保存に使用されるキャッシュ実装を設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | キャッシュ実装。 |
|

