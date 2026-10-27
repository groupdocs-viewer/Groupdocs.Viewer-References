---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ワードプロセッシング文書のレンダリング用オプションを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/
is_root: false
weight: 10
---


## __init__

ワードプロセッシング文書のレンダリング用オプションを初期化します。

```python
def __init__(self):
    ...
```

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("document.docx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # トラッキングされた変更のレンダリングを有効にします。
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### 参照
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
