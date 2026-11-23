---
title: "طريقة for_jpg_view"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يُهيئ كائن ViewInfoOptions لاسترجاع معلومات العرض عند التحويل إلى JPG."
type: docs
url: /ar/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/
is_root: false
weight: 1030
---


## for_jpg_view

يُهيئ كائن [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) لاسترجاع معلومات العرض عند التحويل إلى JPG.

```python
def for_jpg_view(cls):
    ...
```

**Returns:** A new `ViewInfoOptions` instance.

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

def get_jpg_view_info():
    with Viewer("sample.pdf") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_jpg_view())
        print("Document type:", info.file_type)
        print("Pages count:", len(info.pages))

if __name__ == "__main__":
    get_jpg_view_info()
```

## for_jpg_view {#extract_text}

يُهيئ كائن ViewInfoOptions لاسترجاع معلومات العرض عند التحويل إلى JPG.

```python
def for_jpg_view(cls, extract_text):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| extract_text | `bool` | يُمكّن استخراج النص. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### انظر أيضًا
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
