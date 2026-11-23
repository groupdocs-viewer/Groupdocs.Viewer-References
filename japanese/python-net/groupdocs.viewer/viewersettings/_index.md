---
title: "ViewerSettings クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "Viewer の動作をカスタマイズするための設定を定義します。"
type: docs
url: /ja/python-net/groupdocs.viewer/viewersettings/
is_root: false
weight: 110
---


## ViewerSettings class

[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) の動作をカスタマイズする設定を定義します。

ViewerSettings 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache-logger) | 新しい ViewerSettings インスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache) | 新しい ViewerSettings インスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#logger) | 新しい ViewerSettings インスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [cache](/viewer/python-net/groupdocs.viewer/viewersettings/cache/) | レンダリング結果を保存するために使用されるキャッシュ実装です。 |
| [logger](/viewer/python-net/groupdocs.viewer/viewersettings/logger/) | ロギング（エラー、警告、トレース）に使用されるロガー実装です。 |

### 例

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources(
        "example/page_{0}.html"
    )
    viewer.view(html_options)
```

### 参照
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
