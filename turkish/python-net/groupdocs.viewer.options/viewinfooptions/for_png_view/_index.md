---
title: "for_png_view yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "PNG'ye render ederken görünüm bilgilerini almak için bir ViewInfoOptions sınıfının örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/
is_root: false
weight: 1060
---


## for_png_view

PNG'ye render ederken görünüm bilgilerini almak için bir [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) sınıfının örneğini başlatır.

```python
def for_png_view(cls):
    ...
```

**Returns:** ViewInfoOptions: New instance of the `ViewInfoOptions` class.

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# PNG formatı için görünüm bilgisi seçenekleri oluştur
view_info_options_png = ViewInfoOptions.for_png_view()

# Bir belge yükleyin ve PNG için görünüm bilgilerini alın
with Viewer("sample.xml") as viewer:
    result_png = viewer.get_view_info(view_info_options_png)
```

## for_png_view {#extract_text}

PNG'ye render ederken görünüm bilgilerini almak için bir ViewInfoOptions sınıfının örneğini başlatır.

```python
def for_png_view(cls, extract_text):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| extract_text | `bool` | Metin çıkarımını etkinleştirir. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Örnek

```python
from groupdocs.viewer.options import ViewInfoOptions

# Metin çıkarımı etkinleştirilmiş PNG formatı için görünüm bilgisi seçenekleri oluştur
options = ViewInfoOptions.for_png_view(extractText=True)
```

### Ayrıca Bakınız
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
