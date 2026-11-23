---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "MaxResolution オプションのデフォルト値を 300、ImageQuality オプションのデフォルト値を 100 に初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/
is_root: false
weight: 10
---


## __init__

MaxResolution オプションのデフォルト値を 300、ImageQuality オプションのデフォルト値を 100 に初期化します。

詳細とコードサンプルについては、https://docs.groupdocs.com/viewer/net/optimization-pdf-options/ とその子ページをご覧ください。

```python
def __init__(self):
    ...
```

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

with Viewer("sample.docx") as viewer:
    view_options = PdfViewOptions("optimized.pdf")
    view_options.pdf_optimization_options = PdfOptimizationOptions()
    viewer.view(view_options)
```

### 参照
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
