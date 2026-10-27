---
title: "error メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "コンソールにエラーメッセージを書き込みます。"
type: docs
url: /ja/python-net/groupdocs.viewer.logging/filelogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

コンソールにエラーメッセージを書き込みます。エラーログメッセージは、アプリケーションフローで回復不可能なイベントに関する情報を提供します。

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
* class [`FileLogger`](/viewer/python-net/groupdocs.viewer.logging/filelogger/)
