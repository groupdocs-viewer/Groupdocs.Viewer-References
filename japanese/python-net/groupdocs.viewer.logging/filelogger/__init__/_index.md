---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ファイルにメッセージを書き込むロガーを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.logging/filelogger/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

ファイルにメッセージを書き込むロガーを初期化します。

```python
def __init__(self, file_name):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_name | `str` | パス付きの完全なファイル名。 |

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
* class [`FileLogger`](/viewer/python-net/groupdocs.viewer.logging/filelogger/)
