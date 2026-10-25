---
title: "FileLogger"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "ログメッセージをファイルに書き込みます。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.viewer.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

ログメッセージをファイルに書き込みます。


この
FileLogger
クラスはログメッセージをファイルに書き込む機能を提供します。ILogger インターフェイスを実装しています。
アプリケーション内のさまざまなイベントやメッセージを記録するために使用できます。ログメッセージは指定されたファイルに書き込まれます。


使用例:

````

 // Create a new instance of FileLogger with the specified log file path
 FileLogger fileLogger = new FileLogger("/path/to/logfile.txt");

 // Log an informational message
 fileLogger.debug("Debug message");

 // Log an error message
 fileLogger.error("Error message");

 // Check is logging warning messages enabled
 boolean warningEnabled = fileLogger.isWarningEnabled();
 
````


***Note:** The 
FileLogger
クラスは基本的なロギング機能を提供します。
要件に応じてカスタムログレベルや追加のロギング機能を追加するために、このクラスを拡張できます。*

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [FileLogger(String fileName)](#FileLogger-java.lang.String-) | 指定されたファイル名で指定されたファイルにメッセージを記録するロガーを作成します。 |
|
|  | [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | 指定されたロギングレベルでファイルにメッセージを記録するロガーを作成します。 |
|
## フィールド

| フィールド | 説明 |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
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
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


指定されたファイル名で指定されたファイルにメッセージを記録するロガーを作成します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fileName | java.lang.String | パスを含む完全なファイル名です。 |
|

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


指定されたロギングレベルでファイルにメッセージを記録するロガーを作成します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fileName | java.lang.String | パスを含む完全なファイル名です。 |
|
|  | isTraceEnabled | boolean | トレースレベルのロギングが有効かどうかを指定します。 |
|
|  | isDebugEnabled | boolean | デバッグレベルのロギングが有効かどうかを指定します。 |
|
|  | isWarningEnabled | boolean | 警告レベルのロギングが有効かどうかを指定します。 |
|
|  | isErrorEnabled | boolean | エラーレベルのロギングが有効かどうかを指定します。 |
|

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
public void trace(Throwable throwable, String message, Object[] arguments)
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
public boolean isTraceEnabled()
```


トレースレベルが有効かどうかを確認します。


**Returns:**
boolean -  true  がトレースレベルで有効な場合、  false  がそれ以外の場合。

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
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
public void debug(Throwable throwable, String message, Object[] arguments)
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
public boolean isDebugEnabled()
```


デバッグレベルが有効かどうかを確認します。


**Returns:**
boolean - デバッグレベルが有効な場合は true、そうでない場合は false。

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
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
public void warning(Throwable throwable, String message, Object[] arguments)
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
public boolean isWarningEnabled()
```


警告レベルが有効かどうかを確認します。


**Returns:**
boolean - 警告レベルが有効な場合は true、そうでない場合は false。

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
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
public void error(Throwable throwable, String message, Object[] arguments)
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
public boolean isErrorEnabled()
```


エラーレベルのロギングが有効かどうかを確認します。


**Returns:**
boolean - エラーレベルのロギングが有効な場合は true、そうでない場合は false。

