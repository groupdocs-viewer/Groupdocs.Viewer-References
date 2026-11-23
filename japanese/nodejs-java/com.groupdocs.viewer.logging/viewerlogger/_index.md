---
title: "ViewerLogger"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "グローバル ビューア ロガー。"
type: docs
weight: 11
url: /ja/nodejs-java/com.groupdocs.viewer.logging/viewerlogger/
---
**Inheritance:**
java.lang.Object
```
public class ViewerLogger
```

グローバル ビューア ロガー。

ViewerLogger クラスは、統合されたロガーまたはユーザー定義のロガーにメッセージを記録する機能を提供します。ビューアモジュールのグローバルロガーとして機能し、さまざまなイベントやメッセージを記録するために使用できます。

使用例:

```

 // Configure the viewer logger to use the default integrated logger
 ViewerLogger.setLogger(new FileLogger("/path/to/file.log"));

 // Log an debug message
 ViewerLogger.debug("Debug message");

 // Log an error message
 ViewerLogger.error("Error message");
 
```

***Note:** The  ViewerLogger  class can be configured to use a custom logger implementation by calling the [setLogger(ILogger)](../../com.groupdocs.viewer.logging/viewerlogger\#setLogger-ILogger-) method. By default, it uses the integrated logger provided by the viewer module.*
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [ViewerLogger()](#ViewerLogger--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | コンソールにトレースメッセージを書き込みます。 |
| [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | コンソールにトレースログメッセージを書き込みます。 |
| [isTraceEnabled()](#isTraceEnabled--) | トレースレベルのロギングが有効かどうかを確認します。 |
| [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | コンソールにデバッグログメッセージを書き込みます。 |
| [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | コンソールにデバッグログメッセージを書き込みます。 |
| [isDebugEnabled()](#isDebugEnabled--) | デバッグレベルのロギングが有効かどうかを確認します。 |
| [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | コンソールに警告ログメッセージを書き込みます。 |
| [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | コンソールに警告ログメッセージを書き込みます。 |
| [isWarningEnabled()](#isWarningEnabled--) | 警告レベルのロギングが有効かどうかを確認します。 |
| [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | コンソールにエラーログメッセージを書き込みます。 |
| [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | コンソールにエラーログメッセージを書き込みます。 |
| [isErrorEnabled()](#isErrorEnabled--) | エラーレベルのロギングが有効かどうかを確認します。 |
| [getLogger()](#getLogger--) | メッセージのロギングに使用されるロガーインスタンスを取得します。 |
| [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | メッセージのロギングに使用されるロガーインスタンスを設定します。 |
### ViewerLogger() {#ViewerLogger--}
```
public ViewerLogger()
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


コンソールにトレースメッセージを書き込みます。トレースログメッセージは、アプリケーションのフローに関する一般的に有用な情報を提供します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String | トレースメッセージです。 |
| 引数 | java.lang.Object[] | メッセージ内で置換される引数です。これらは、渡された順序で \{\} プレースホルダーを置換します。 |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


トレースログメッセージをコンソールに書き込みます。トレースログメッセージは、アプリケーションのフローに関する一般的に有用な情報を提供します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| スロー可能オブジェクト | java.lang.Throwable | トレースログメッセージに関連付けられた例外です。 |
| メッセージ | java.lang.String | トレースログメッセージです。 |
| 引数 | java.lang.Object[] | メッセージ内で置換される引数です。渡された順序で \{\} プレースホルダーを置換します。 |

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


トレースレベルのロギングが有効かどうかを確認します。

**Returns:**
boolean - トレースレベルが有効な場合は true、そうでない場合は false。
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


デバッグログメッセージをコンソールに書き込みます。デバッグログメッセージは、アプリケーションフロー内のさまざまなプロセスに関する情報を提供します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String | デバッグログメッセージです。 |
| 引数 | java.lang.Object[] | メッセージ内で置換される引数です。渡された順序で \{\} プレースホルダーを置換します。 |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


デバッグログメッセージをコンソールに書き込みます。デバッグログメッセージは、アプリケーションフロー内のさまざまなプロセスに関する情報を提供します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| スロー可能オブジェクト | java.lang.Throwable | デバッグログメッセージに関連付けられた例外です。 |
| メッセージ | java.lang.String | デバッグログメッセージです。 |
| 引数 | java.lang.Object[] | メッセージ内で置換される引数です。渡された順序で \{\} プレースホルダーを置換します。 |

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


デバッグレベルのロギングが有効かどうかを確認します。

**Returns:**
boolean - デバッグレベルが有効な場合は true、そうでない場合は false。
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


警告ログメッセージをコンソールに書き込みます。警告ログメッセージは、アプリケーションフローにおける予期しない、かつ回復可能なイベントに関する情報を提供します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String | 警告ログメッセージです。 |
| 引数 | java.lang.Object[] | メッセージ内で置換される引数です。渡された順序で \{\} プレースホルダーを置換します。 |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


警告ログメッセージをコンソールに書き込みます。警告ログメッセージは、アプリケーションフローにおける予期しない、かつ回復可能なイベントに関する情報を提供します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| スロー可能オブジェクト | java.lang.Throwable | 警告ログメッセージに関連付けられた例外です。 |
| メッセージ | java.lang.String | 警告ログメッセージです。 |
| 引数 | java.lang.Object[] | メッセージ内で置換される引数です。渡された順序で \{\} プレースホルダーを置換します。 |

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


警告レベルのロギングが有効かどうかを確認します。

**Returns:**
boolean - 警告レベルが有効な場合は true、そうでない場合は false。
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


エラーログメッセージをコンソールに書き込みます。エラーログメッセージは、アプリケーションフローにおける回復不可能なイベントに関する情報を提供します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String | エラーログメッセージです。 |
| 引数 | java.lang.Object[] | メッセージ内で置換される引数です。渡された順序で \{\} プレースホルダーを置換します。 |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


エラーログメッセージをコンソールに書き込みます。エラーログメッセージは、アプリケーションフローにおける回復不可能なイベントに関する情報を提供します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| スロー可能オブジェクト | java.lang.Throwable | エラーログメッセージに関連付けられた例外です。 |
| メッセージ | java.lang.String | エラーログメッセージです。 |
| 引数 | java.lang.Object[] | メッセージ内で置換される引数です。渡された順序で \{\} プレースホルダーを置換します。 |

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


メッセージのロギングに使用されるロガーインスタンスを取得します。ロガーインスタンスは、トレース、デバッグ、警告、エラーなど、さまざまなレベルのメッセージを記録するために使用できます。

**Returns:**
com.groupdocs.foundation.logging.ILogger - ロガーインスタンスです。
### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


メッセージのロギングに使用されるロガーインスタンスを設定します。ロガーインスタンスは、トレース、デバッグ、警告、エラーなど、さまざまなレベルのメッセージを記録するために使用できます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ロガー | com.groupdocs.foundation.logging.ILogger | 設定するロガーインスタンスです。 |

