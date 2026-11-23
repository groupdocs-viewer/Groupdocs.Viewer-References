---
title: "FolderFontSource"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "FolderFontSourcegroupdocs.viewer.fonts/folderfontsource クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.viewer.fonts/folderfontsource/folderfontsource/
---

## FolderFontSource constructor

[`FolderFontSource`](../../folderfontsource) クラスの新しいインスタンスを初期化します。

```csharp
public FolderFontSource(string folderPath, SearchOption searchOption)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| folderPath | String | TrueType フォントを含むフォルダーへのパスです。 |
| searchOption | SearchOption | 現在のフォルダー、または現在のフォルダーとすべてのサブフォルダーを検索するかどうかを指定します。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *folderPath* が null のときにスローされます。 |
| DirectoryNotFoundException | *folderPath* に指定されたパスが見つからない場合にスローされます。 |

### 関連項目

* enum [SearchOption](../../searchoption)
* class [FolderFontSource](../../folderfontsource)
* namespace [GroupDocs.Viewer.Fonts](../../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
