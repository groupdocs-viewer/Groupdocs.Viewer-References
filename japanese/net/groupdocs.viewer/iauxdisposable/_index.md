---
title: "IAuxDisposable"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "標準の IDisposable インターフェイスを拡張し、オブジェクトの現在の状態を取得し、破棄イベントを購読できるようにします。"
type: docs
weight: 20
url: /ja/net/groupdocs.viewer/iauxdisposable/
---

## IAuxDisposable interface

標準の IDisposable インターフェイスを拡張し、オブジェクトの現在の状態を取得し、破棄イベントを購読できるようにします。

```csharp
public interface IAuxDisposable : IDisposable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsDisposed](../../groupdocs.viewer/iauxdisposable/isdisposed) { get; } | リソースが既に破棄されているかどうかを示します（`true` または `false`）。 |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [Disposed](../../groupdocs.viewer/iauxdisposable/disposed) | オブジェクトが破棄されたときに発生し、リソースの破棄が正常に完了した直後です |

### 関連項目

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
