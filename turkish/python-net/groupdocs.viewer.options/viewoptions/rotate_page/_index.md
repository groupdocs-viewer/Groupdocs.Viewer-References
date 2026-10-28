---
title: "rotate_page yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Bir sayfaya saat yönünde döndürme uygular."
type: docs
url: /tr/python-net/groupdocs.viewer.options/viewoptions/rotate_page/
is_root: false
weight: 1010
---


## rotate_page {#page_number-rotation}

Bir sayfaya saat yönünde döndürme uygular.

Ayrıntılar için belgeleri https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/ adresinde inceleyin.

```python
def rotate_page(self, page_number, rotation):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| page_number | `int` | Sayfa numarası, 0'dan kesinlikle büyük olmalıdır. |
| rotation | `Rotation` | Dönüş değeri. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | Sayfa numarası `page_number` olan sayfa için dönüş zaten eklenmişse. |

### Ayrıca Bakınız
* class [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)
