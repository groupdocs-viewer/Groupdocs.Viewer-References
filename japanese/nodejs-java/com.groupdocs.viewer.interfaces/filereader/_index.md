---
title: "FileReader"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "ファイルストリームを読み取るためのインターフェイスを宣言します。"
type: docs
weight: 14
url: /ja/nodejs-java/com.groupdocs.viewer.interfaces/filereader/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface FileReader extends Closeable
```

ファイルストリームを読み取るためのインターフェイスを宣言します。

FileReader インターフェイスは、ファイルストリームを読み取るためのメソッドを提供します。これは、ファイルの内容に順次アクセスして読み取るために使用されます。このインターフェイスの実装は、ファイルからデータを読み取るために必要な操作を処理すべきです。

使用例:

```

 FileReader fileReader = new FileReader() {
     @Override
     public InputStream read() {
         // Create document stream
     }

     @Override
     public void close() {
         // Close the stream
     }
 };
 try (Viewer viewer = new Viewer(fileReader, new ViewerSettings())){
     // Process document
 }
 
```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [read()](#read--) | ファイルの読み取り可能なストリームを表す InputStream を返します。 |
| [close()](#close--) | オブジェクトを破棄し、それに関連付けられたすべてのシステムリソースを解放します。 |
### read() {#read--}
```
public abstract InputStream read()
```


ファイルの読み取り可能なストリームを表す InputStream を返します。

**Returns:**
java.io.InputStream - 読み取り可能な InputStream ストリーム。
### close() {#close--}
```
public abstract void close()
```


オブジェクトを破棄し、それに関連付けられたすべてのシステムリソースを解放します。

