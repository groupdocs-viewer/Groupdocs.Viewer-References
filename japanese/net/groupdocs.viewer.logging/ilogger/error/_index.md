---
title: "エラー"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "エラーメッセージを書き込みます。エラーログメッセージは、アプリケーションフローで回復不可能なイベントに関する情報を提供します。"
type: docs
weight: 10
url: /ja/net/groupdocs.viewer.logging/ilogger/error/
---

## ILogger.Error method

エラーメッセージを書き込みます。エラーログメッセージは、アプリケーションフローで回復不可能なイベントに関する情報を提供します。

```csharp
public void Error(string message, Exception exception)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| メッセージ | String | エラーメッセージ。 |
| 例外 | 例外 | 例外。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *message* が null のときにスローされます。 |
| ArgumentNullException | *exception* が null のときにスローされます。 |

### 関連項目

* interface [ILogger](../../ilogger)
* namespace [GroupDocs.Viewer.Logging](../../../groupdocs.viewer.logging)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
