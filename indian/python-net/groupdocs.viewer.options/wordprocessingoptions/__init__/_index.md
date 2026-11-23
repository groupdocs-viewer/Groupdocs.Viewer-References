---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "वर्ड प्रोसेसिंग दस्तावेज़ों को रेंडर करने के विकल्पों को प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/
is_root: false
weight: 10
---


## __init__

वर्ड प्रोसेसिंग दस्तावेज़ों को रेंडर करने के विकल्पों को प्रारंभ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("document.docx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # ट्रैक किए गए बदलावों का रेंडरिंग सक्षम करें।
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### साथ में देखें
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
