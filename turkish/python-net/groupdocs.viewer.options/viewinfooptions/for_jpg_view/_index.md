---
title: "for_jpg_view yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "JPG'ye işlenirken görünüm hakkında bilgi almak için bir ViewInfoOptions örneği başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/
is_root: false
weight: 1030
---


## for_jpg_view

JPG'ye render ederken görünüm bilgilerini almak için bir [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) örneği başlatır.

```python
def for_jpg_view(cls):
    ...
```

**Returns:** A new `ViewInfoOptions` instance.

### Örnek

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

JPG'ye render ederken görünüm bilgilerini almak için bir ViewInfoOptions örneği başlatır.

```python
def for_jpg_view(cls, extract_text):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| extract_text | `bool` | Metin çıkarımını etkinleştirir. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Ayrıca Bakınız
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
