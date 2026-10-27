---
title: "error メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "エラーメッセージを書き込みます。"
type: docs
url: /ja/python-net/groupdocs.viewer.logging/ilogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

エラーメッセージを書き込みます。

エラーログ メッセージは、アプリケーションのフローにおける回復不可能なイベントに関する情報を提供します。

```python
def error(self, message, exception):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| message | `str` | エラーメッセージです。 |
| exception | `Exception` | 例外です。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `exception` が None のとき。 |

### 参照
* class [`ILogger`](/viewer/python-net/groupdocs.viewer.logging/ilogger/)
