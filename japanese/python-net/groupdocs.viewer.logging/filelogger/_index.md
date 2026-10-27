---
title: "FileLogger クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ファイルにログメッセージを書き込みます。"
type: docs
url: /ja/python-net/groupdocs.viewer.logging/filelogger/
is_root: false
weight: 20
---


## FileLogger class

ファイルにログメッセージを書き込みます。

FileLogger 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.logging/filelogger/__init__/#file_name) | ファイルにメッセージを書き込むロガーを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [error](/viewer/python-net/groupdocs.viewer.logging/filelogger/error/#message-exception) | コンソールにエラーメッセージを書き込みます。エラーログメッセージは、アプリケーションフローで回復不可能なイベントに関する情報を提供します。 |
| [error_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/error_file/) |  |
| [error_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/error_string/) |  |
| [trace](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace/#message) | ログにトレースメッセージを書き込みます。トレースログメッセージは、アプリケーションフローに関する一般的に有用な情報を提供します。 |
| [trace_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace_file/) |  |
| [trace_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace_string/) |  |
| [warning](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning/#message) | コンソールに警告メッセージを書き込みます。 |
| [warning_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning_file/) |  |
| [warning_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning_string/) |  |

### 例

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import FileLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=FileLogger("./log.txt"))
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources(
        "write_logs_to_file/page_{0}.html"
    )
    viewer.view(html_options)
```

### 参照
* module [`groupdocs.viewer.logging`](/viewer/python-net/groupdocs.viewer.logging/)
