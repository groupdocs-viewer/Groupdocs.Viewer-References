---
title: "FileLogger"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "ログメッセージをファイルに書き込みます。"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.viewer.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

ログメッセージをファイルに書き込みます。

FileLogger クラスは、ログメッセージをファイルに書き込む機能を提供します。ILogger インターフェイスを実装しており、アプリケーション内のさまざまなイベントやメッセージを記録するために使用できます。ログメッセージは指定されたファイルに書き込まれます。

使用例:

```

 // Create a new instance of FileLogger with the specified log file path
 FileLogger fileLogger = new FileLogger("/path/to/logfile.txt");

 // Log an informational message
 fileLogger.debug("Debug message");

 // Log an error message
 fileLogger.error("Error message");

 // Check is logging warning messages enabled
 boolean warningEnabled = fileLogger.isWarningEnabled();
 
```

***Note:** The  FileLogger  class provides basic logging functionality. You can extend this class to add custom log levels or additional logging features as per your requirements.*
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [FileLogger(String fileName)](#FileLogger-java.lang.String-) | 提供されたファイル名で指定されたファイルにメッセージを記録するロガーを作成します。 |
| [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | 指定されたログレベルでファイルにメッセージを記録するロガーを作成します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
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
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


提供されたファイル名で指定されたファイルにメッセージを記録するロガーを作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | パスを含む完全なファイル名です。 |

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


指定されたログレベルでファイルにメッセージを記録するロガーを作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | パスを含む完全なファイル名です。 |
| isTraceEnabled | boolean | トレースレベルのロギングが有効かどうかを指定します。 |
| isDebugEnabled | boolean | デバッグレベルのロギングが有効かどうかを指定します。 |
| isWarningEnabled | boolean | 警告レベルのロギングが有効かどうかを指定します。 |
| isErrorEnabled | boolean | エラーレベルのロギングが有効かどうかを指定します。 |

### MESSAGE {#MESSAGE}
```
public static final String MESSAGE
```


### EXCEPTION {#EXCEPTION}
```
public static final String EXCEPTION
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public void trace(String message, Object[] arguments)
```


コンソールにトレースメッセージを書き込みます。トレースログメッセージは、アプリケーションのフローに関する一般的に有用な情報を提供します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String | トレースメッセージです。 |
| 引数 | java.lang.Object[] | メッセージ内で置換される引数です。これらは、渡された順序で \{\} プレースホルダーを置換します。 |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
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
public boolean isTraceEnabled()
```


トレースレベルのロギングが有効かどうかを確認します。

**Returns:**
boolean - トレースレベルが有効な場合は true、そうでない場合は false。
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


デバッグログメッセージをコンソールに書き込みます。デバッグログメッセージは、アプリケーションフロー内のさまざまなプロセスに関する情報を提供します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String | デバッグログメッセージです。 |
| 引数 | java.lang.Object[] | メッセージ内で置換される引数です。渡された順序で \{\} プレースホルダーを置換します。 |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
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
public boolean isDebugEnabled()
```


デバッグレベルのロギングが有効かどうかを確認します。

**Returns:**
boolean - デバッグレベルが有効な場合は true、そうでない場合は false。
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


警告ログメッセージをコンソールに書き込みます。警告ログメッセージは、アプリケーションフローにおける予期しない、かつ回復可能なイベントに関する情報を提供します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String | 警告ログメッセージです。 |
| 引数 | java.lang.Object[] | メッセージ内で置換される引数です。渡された順序で \{\} プレースホルダーを置換します。 |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
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
public boolean isWarningEnabled()
```


警告レベルのロギングが有効かどうかを確認します。

**Returns:**
boolean - 警告レベルが有効な場合は true、そうでない場合は false。
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


エラーログメッセージをコンソールに書き込みます。エラーログメッセージは、アプリケーションフローにおける回復不可能なイベントに関する情報を提供します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String | エラーログメッセージです。 |
| 引数 | java.lang.Object[] | メッセージ内で置換される引数です。渡された順序で \{\} プレースホルダーを置換します。 |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
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
public boolean isErrorEnabled()
```


エラーレベルのロギングが有効かどうかを確認します。

**Returns:**
boolean - エラーレベルのロギングが有効な場合は true、そうでない場合は false。
