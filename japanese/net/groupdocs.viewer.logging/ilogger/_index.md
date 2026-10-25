---
title: "ILogger"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "ロギングを実行するために使用されるメソッドを定義します。"
type: docs
weight: 670
url: /ja/net/groupdocs.viewer.logging/ilogger/
---

## ILogger interface

ロギングを実行するために使用されるメソッドを定義します。

```csharp
public interface ILogger
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Error](../../groupdocs.viewer.logging/ilogger/error)(string, Exception) | エラーメッセージを書き込みます。エラーログメッセージは、アプリケーションフローで回復不可能なイベントに関する情報を提供します。 |
| [Trace](../../groupdocs.viewer.logging/ilogger/trace)(string) | トレースメッセージを書き込みます。トレースログメッセージは、アプリケーションフローに関する一般的に有用な情報を提供します。 |
| [Warning](../../groupdocs.viewer.logging/ilogger/warning)(string) | 警告メッセージを書き込みます。警告ログメッセージは、アプリケーションのフローで予期しない回復可能なイベントに関する情報を提供します。 |

### 関連項目

* namespace [GroupDocs.Viewer.Logging](../../groupdocs.viewer.logging)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
