---
title: "FileNotFoundException"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "この例外は、ファイルまたはディレクトリが見つからない場合にスローされます。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.viewer.exception/filenotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.viewer.exception.GroupDocsViewerException](../../com.groupdocs.viewer.exception/groupdocsviewerexception)
```
public class FileNotFoundException extends GroupDocsViewerException
```

この例外は、ファイルまたはディレクトリが見つからないときにスローされます。指定されたファイルまたはディレクトリが存在しないか、アクセスできないことを示します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [FileNotFoundException(String message)](#FileNotFoundException-java.lang.String-) | 指定されたメッセージで FileNotFoundException クラスのインスタンスを作成します。 |
|
|  | [FileNotFoundException(Path path)](#FileNotFoundException-java.nio.file.Path-) | 指定されたファイルパスで FileNotFoundException クラスの新しいインスタンスを初期化します。 |
|
|  | [FileNotFoundException(String messageTemplate, Object[] params)](#FileNotFoundException-java.lang.String-java.lang.Object...-) | 指定されたエラーメッセージで FileNotFoundException クラスの新しいインスタンスを作成します。 |
|
|  | [FileNotFoundException(Throwable cause)](#FileNotFoundException-java.lang.Throwable-) | FileNotFoundException クラスの新しいインスタンスを生成します。 |
|
|  | [FileNotFoundException(String message, Throwable throwable)](#FileNotFoundException-java.lang.String-java.lang.Throwable-) | 指定されたエラーメッセージで FileNotFoundException クラスの新しいインスタンスを初期化します。 |
|
### FileNotFoundException(String message) {#FileNotFoundException-java.lang.String-}
```
public FileNotFoundException(String message)
```


指定されたメッセージで FileNotFoundException クラスのインスタンスを作成します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | メッセージ | java.lang.String | エラーを説明するメッセージ。 |
|

### FileNotFoundException(Path path) {#FileNotFoundException-java.nio.file.Path-}
```
public FileNotFoundException(Path path)
```


指定されたファイルパスで FileNotFoundException クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | パス | java.nio.file.Path | 存在しないファイルのパス。 |
|

### FileNotFoundException(String messageTemplate, Object[] params) {#FileNotFoundException-java.lang.String-java.lang.Object...-}
```
public FileNotFoundException(String messageTemplate, Object[] params)
```


指定されたエラーメッセージで FileNotFoundException クラスの新しいインスタンスを作成します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | messageTemplate | java.lang.String | エラーを説明するメッセージ。 |
|
|  | パラメータ | java.lang.Object[] | エラーメッセージに設定されるパラメータ。 |
|

### FileNotFoundException(Throwable cause) {#FileNotFoundException-java.lang.Throwable-}
```
public FileNotFoundException(Throwable cause)
```


FileNotFoundException クラスの新しいインスタンスを生成します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 原因 | java.lang.Throwable | 例外の原因。 |
|

### FileNotFoundException(String message, Throwable throwable) {#FileNotFoundException-java.lang.String-java.lang.Throwable-}
```
public FileNotFoundException(String message, Throwable throwable)
```


指定されたエラーメッセージで FileNotFoundException クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | メッセージ | java.lang.String | エラーを説明するメッセージ。 |
|
|  | throwable | java.lang.Throwable | 例外を引き起こしたスロー可能オブジェクト。 |
|

