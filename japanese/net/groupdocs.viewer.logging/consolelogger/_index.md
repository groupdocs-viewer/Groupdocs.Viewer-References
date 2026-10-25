---
title: "ConsoleLogger"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "コンソールにログメッセージを書き込みます。"
type: docs
weight: 650
url: /ja/net/groupdocs.viewer.logging/consolelogger/
---

## ConsoleLogger class

コンソールにログメッセージを書き込みます。

```csharp
public class ConsoleLogger : ILogger
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ConsoleLogger](consolelogger)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Error](../../groupdocs.viewer.logging/consolelogger/error)(string, Exception) | コンソールにエラーメッセージを書き込みます。エラーログメッセージは、アプリケーションフローで回復不可能なイベントに関する情報を提供します。 |
| [Trace](../../groupdocs.viewer.logging/consolelogger/trace)(string) | コンソールにトレースメッセージを書き込みます。トレースログメッセージは、アプリケーションフローに関する一般的に有用な情報を提供します。 |
| [Warning](../../groupdocs.viewer.logging/consolelogger/warning)(string) | コンソールに警告メッセージを書き込みます。警告ログメッセージは、アプリケーションフローで予期しない回復可能なイベントに関する情報を提供します。 |

### 関連項目

* interface [ILogger](../ilogger)
* namespace [GroupDocs.Viewer.Logging](../../groupdocs.viewer.logging)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
