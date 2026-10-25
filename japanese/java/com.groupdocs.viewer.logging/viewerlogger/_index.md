---
title: "ViewerLogger"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "グローバルビューアロガー。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.viewer.logging/viewerlogger/
---
**Inheritance:**
java.lang.Object
```
public class ViewerLogger
```

グローバルビューアロガー。


この
ViewerLogger
クラスは、統合ロガーまたはユーザー定義ロガーにメッセージを記録する機能を提供します。
ビューアモジュールのグローバルロガーとして機能し、さまざまなイベントやメッセージを記録するために使用できます。


使用例:

````

 // Configure the viewer logger to use the default integrated logger
 ViewerLogger.setLogger(new FileLogger("/path/to/file.log"));

 // Log an debug message
 ViewerLogger.debug("Debug message");

 // Log an error message
 ViewerLogger.error("Error message");
 
````


***Note:** The 
ViewerLogger
クラスは、[setLogger(ILogger)](../../com.groupdocs.viewer.logging/viewerlogger#setLogger-ILogger-) メソッドを呼び出すことで、カスタムロガー実装を使用するように構成できます。
デフォルトでは、ビューアモジュールが提供する統合ロガーを使用します。*

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ViewerLogger()](#ViewerLogger--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | コンソールにトレースメッセージを書き込みます。 |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | コンソールにトレースログメッセージを書き込みます。 |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | トレースレベルが有効かどうかを確認します。 |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | コンソールにデバッグログメッセージを書き込みます。 |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | コンソールにデバッグログメッセージを書き込みます。 |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | デバッグレベルが有効かどうかを確認します。 |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | コンソールに警告ログメッセージを書き込みます。 |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | コンソールに警告ログメッセージを書き込みます。 |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | 警告レベルが有効かどうかを確認します。 |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | コンソールにエラーログメッセージを書き込みます。 |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | コンソールにエラーログメッセージを書き込みます。 |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | エラーレベルのロギングが有効かどうかを確認します。 |
|
|  | [getLogger()](#getLogger--) | メッセージの記録に使用されるロガーインスタンスを取得します。 |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | メッセージの記録に使用されるロガーインスタンスを設定します。 |
|
### ViewerLogger() {#ViewerLogger--}
```
public ViewerLogger()
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


コンソールにトレースメッセージを書き込みます。
トレースログメッセージは、アプリケーションのフローに関する一般的に有用な情報を提供します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | メッセージ | java.lang.String | トレースメッセージです。 |
|
|  | 引数 | java.lang.Object[] | メッセージ内で置換される引数です。{} プレースホルダーは渡された順序で置換されます。 |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


コンソールにトレースログメッセージを書き込みます。
トレースログメッセージは、アプリケーションのフローに関する一般的に有用な情報を提供します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | トレースログメッセージに関連付けられた例外です。 |
|
|  | メッセージ | java.lang.String | トレースログメッセージです。 |
|
|  | 引数 | java.lang.Object[] | メッセージ内で置換される引数です。{} プレースホルダーは渡された順序で置換されます。 |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


トレースレベルが有効かどうかを確認します。


**Returns:**
boolean -  true  がトレースレベルで有効な場合、  false  がそれ以外の場合。

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


コンソールにデバッグログメッセージを書き込みます。
デバッグログメッセージは、アプリケーションフロー内のさまざまなプロセスに関する情報を提供します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | メッセージ | java.lang.String | デバッグログメッセージです。 |
|
|  | 引数 | java.lang.Object[] | メッセージ内で置換される引数です。{} プレースホルダーは渡された順序で置換されます。 |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


コンソールにデバッグログメッセージを書き込みます。
デバッグログメッセージは、アプリケーションフロー内のさまざまなプロセスに関する情報を提供します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | デバッグログメッセージに関連付けられた例外です。 |
|
|  | メッセージ | java.lang.String | デバッグログメッセージです。 |
|
|  | 引数 | java.lang.Object[] | メッセージ内で置換される引数です。{} プレースホルダーは渡された順序で置換されます。 |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


デバッグレベルが有効かどうかを確認します。


**Returns:**
boolean - デバッグレベルが有効な場合は true、そうでない場合は false。

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


コンソールに警告ログメッセージを書き込みます。
警告ログメッセージは、アプリケーションのフローで予期しない回復可能なイベントに関する情報を提供します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | メッセージ | java.lang.String | 警告ログメッセージです。 |
|
|  | 引数 | java.lang.Object[] | メッセージ内で置換される引数です。{} プレースホルダーは渡された順序で置換されます。 |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


コンソールに警告ログメッセージを書き込みます。
警告ログメッセージは、アプリケーションのフローで予期しない回復可能なイベントに関する情報を提供します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | 警告ログメッセージに関連付けられた例外です。 |
|
|  | メッセージ | java.lang.String | 警告ログメッセージです。 |
|
|  | 引数 | java.lang.Object[] | メッセージ内で置換される引数です。{} プレースホルダーは渡された順序で置換されます。 |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


警告レベルが有効かどうかを確認します。


**Returns:**
boolean - 警告レベルが有効な場合は true、そうでない場合は false。

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


コンソールにエラーログメッセージを書き込みます。
エラーログメッセージは、アプリケーションのフローで回復不可能なイベントに関する情報を提供します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | メッセージ | java.lang.String | エラーログメッセージです。 |
|
|  | 引数 | java.lang.Object[] | メッセージ内で置換される引数です。{} プレースホルダーは渡された順序で置換されます。 |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


コンソールにエラーログメッセージを書き込みます。
エラーログメッセージは、アプリケーションのフローで回復不可能なイベントに関する情報を提供します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | エラーログメッセージに関連付けられた例外です。 |
|
|  | メッセージ | java.lang.String | エラーログメッセージです。 |
|
|  | 引数 | java.lang.Object[] | メッセージ内で置換される引数です。{} プレースホルダーは渡された順序で置換されます。 |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


エラーレベルのロギングが有効かどうかを確認します。


**Returns:**
boolean - エラーレベルのロギングが有効な場合は true、そうでない場合は false。

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


メッセージの記録に使用されるロガーインスタンスを取得します。
ロガーインスタンスは、trace、debug、warning、error などのさまざまなレベルのメッセージを記録するために使用できます。


**Returns:**
com.groupdocs.foundation.logging.ILogger - ロガーインスタンスです。

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


メッセージの記録に使用されるロガーインスタンスを設定します。
ロガーインスタンスは、trace、debug、warning、error などのさまざまなレベルのメッセージを記録するために使用できます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | ロガー | com.groupdocs.foundation.logging.ILogger | 設定するロガーインスタンスです。 |
|

