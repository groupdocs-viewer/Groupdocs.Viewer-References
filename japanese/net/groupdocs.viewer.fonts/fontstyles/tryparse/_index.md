---
title: "TryParse"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "指定された生文字列をフォントスタイル名として解析しようとします"
type: docs
weight: 120
url: /ja/net/groupdocs.viewer.fonts/fontstyles/tryparse/
---

## FontStyles.TryParse method

指定された生文字列をフォントスタイル名として解析しようとします

```csharp
public static bool TryParse(string style, out FontStyles parsed)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| スタイル | String | フォントスタイルとして解析すべき文字列 |
| parsed | FontStyles& | 成功した場合は解析されたフォントスタイル、失敗した場合は [`Regular`](../regular) |

### 戻り値

`true` は文字列が正しいフォントスタイルとして正常に解析された場合、`false` はそれ以外の場合

### 関連項目

* struct [FontStyles](../../fontstyles)
* namespace [GroupDocs.Viewer.Fonts](../../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
