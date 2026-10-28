---
title: "for_html_view yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "HTML'ye render ederken görünüm bilgilerini almak için bir ViewInfoOptions örneği başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/
is_root: false
weight: 1010
---


## for_html_view

HTML'ye render ederken görünüm bilgilerini almak için bir ViewInfoOptions örneği başlatır.

```python
def for_html_view(cls):
    ...
```

**Returns:** ViewInfoOptions: A new ViewInfoOptions instance.

### Örnek

```python
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import ViewInfoOptions

    # HTML formatı (tek sayfa) için görünüm bilgisi seçenekleri oluştur.
    options = ViewInfoOptions.for_html_view(True)

    # Bir belge yükleyin ve görünüm bilgilerini alın
    with Viewer("sample.xml") as viewer:
        info = viewer.get_view_info(options)
    ```

## for_html_view {#render_single_page}

HTML'ye render ederken görünüm bilgilerini almak için bir ViewInfoOptions örneği başlatır.

```python
def for_html_view(cls, render_single_page):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| render_single_page | `bool` | HTML içeriğinin tek sayfaya işlenmesini etkinleştirir. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# Tek sayfalı HTML için görünüm bilgilerini al
options = ViewInfoOptions.for_html_view(True)

with Viewer("sample.xml") as viewer:
    info = viewer.get_view_info(options)
    print("Document type:", info.file_type)
    print("Pages count:", len(info.pages))
```

### Ayrıca Bakınız
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
