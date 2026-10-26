---
title: "ArchiveOptions"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "アーカイブファイルのレンダリングオプションを提供します。"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

アーカイブファイルのレンダリングオプションを提供します。

ArchiveOptions クラスは、ビューアモジュールでアーカイブファイルのレンダリングを構成するために使用できるオプションのセットを表します。ページごとのアイテム数など、レンダリングプロセスのさまざまな側面をカスタマイズできます。

使用例:

```

 // Create an instance of ArchiveOptions
 ArchiveOptions options = new ArchiveOptions();

 // Set the count of items to be shown on each page
 options.setItemsPerPage(16);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, options)) {
     // Use the viewer object for document rendering
 }
 
```

***Note:** The  ArchiveOptions  class provides a range of customization options for rendering archive files. You can configure these options based on your specific requirements to achieve the desired output.*
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [ArchiveOptions()](#ArchiveOptions--) | デフォルト設定で ArchiveOptions クラスの新しいインスタンスを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFolder()](#getFolder--) | レンダリングに使用される、アーカイブ内のフォルダーを取得します。 |
| [setFolder(String value)](#setFolder-java.lang.String-) | レンダリングに使用されるアーカイブ内のフォルダーを設定します。 |
| [getFileName()](#getFileName--) | ヘッダーに表示されるファイル名を取得します。 |
| [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | ヘッダーに表示されるファイル名を設定します。 |
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


デフォルト設定で ArchiveOptions クラスの新しいインスタンスを作成します。

### getFolder() {#getFolder--}
```
public final String getFolder()
```


レンダリングに使用される、アーカイブ内のフォルダーを取得します。

デフォルトでは、GroupDocs.Viewer はアーカイブに含まれるすべてのフォルダーの項目をレンダリングします。特定のフォルダーの項目をレンダリングするには、このプロパティを設定します。コード例については、[ドキュメント][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder

**Returns:**
java.lang.String - レンダリングされるフォルダー。
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


レンダリングに使用されるアーカイブ内のフォルダーを設定します。

デフォルトでは、GroupDocs.Viewer はアーカイブに含まれるすべてのフォルダーの項目をレンダリングします。特定のフォルダーの項目をレンダリングするには、このプロパティを設定します。コード例については、[ドキュメント][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String | レンダリングされるフォルダー。 |

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


ヘッダーに表示されるファイル名を取得します。

デフォルトでは、GroupDocs.Viewer は各ページのヘッダーにアーカイブのファイル名を表示します。この名前を変更または非表示にするには、このプロパティを設定します。詳細情報とコード例については、[ドキュメント][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.
### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


ヘッダーに表示されるファイル名を設定します。

デフォルトでは、GroupDocs.Viewer は各ページのヘッダーにアーカイブのファイル名を表示します。この名前を変更または非表示にするには、このプロパティを設定します。詳細情報とコード例については、[ドキュメント][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileName | [FileName](../../com.groupdocs.viewer.options/filename) | 表示されるファイル名。 |

