---
title: "FileLogger"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "ファイルにログメッセージを書き込みます。"
type: docs
weight: 660
url: /ja/net/groupdocs.viewer.logging/filelogger/
---

## FileLogger class

ファイルにログメッセージを書き込みます。

```csharp
public class FileLogger : ILogger
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [FileLogger](filelogger)(string) | ファイルへのロガーを作成します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Error](../../groupdocs.viewer.logging/filelogger/error)(string, Exception) | コンソールにエラーメッセージを書き込みます。エラーログメッセージは、アプリケーションフローで回復不可能なイベントに関する情報を提供します。 |
| [Trace](../../groupdocs.viewer.logging/filelogger/trace)(string) | コンソールにトレースメッセージを書き込みます。トレースログメッセージは、アプリケーションフローに関する一般的に有用な情報を提供します。 |
| [Warning](../../groupdocs.viewer.logging/filelogger/warning)(string) | コンソールに警告メッセージを書き込みます。警告ログメッセージは、アプリケーションフローで予期しない回復可能なイベントに関する情報を提供します。 |

### 関連項目

* interface [ILogger](../ilogger)
* namespace [GroupDocs.Viewer.Logging](../../groupdocs.viewer.logging)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
