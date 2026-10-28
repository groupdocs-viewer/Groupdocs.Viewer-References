---
title: "remove_comments özelliği"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Bu özellik True olarak ayarlandığında yorumların render edilmesini devre dışı bırakır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/
is_root: false
weight: 2100
---


## remove_comments property

Bu özellik True olarak ayarlandığında yorumların render edilmesini devre dışı bırakır. Varsayılan olarak False'tur, bu yüzden tüm yorumlar gösterilir.

PDF ve WordProcessing gibi bazı belge formatları yorum içerebilir. Varsayılan olarak GroupDocs.Viewer bunları render eder. Bu seçenek True olarak ayarlandığında yorumlar sonuç belgeden çıkarılabilir.

Bu seçenek, eski `RenderComments` özelliğini değiştirir.

### Definition:
```python
@property
def remove_comments(self):
    ...
@remove_comments.setter
def remove_comments(self, value):
    ...
```

### Ayrıca Bakınız
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
