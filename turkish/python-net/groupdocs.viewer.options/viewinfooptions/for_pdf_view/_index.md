---
title: "for_pdf_view yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "PDF'ye render ederken görünüm bilgilerini almak için bir ViewInfoOptions örneği başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/viewinfooptions/for_pdf_view/
is_root: false
weight: 1050
---


## for_pdf_view

PDF'ye render ederken görünüm bilgilerini almak için bir ViewInfoOptions örneği başlatır.

```python
def for_pdf_view(cls):
    ...
```

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Örnek

```python
    from groupdocs.viewer.options import ViewInfoOptions

    # PDF formatı için görünüm bilgisi seçenekleri oluştur
    view_info_options_pdf = ViewInfoOptions.for_pdf_view()
    ```

### Ayrıca Bakınız
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
