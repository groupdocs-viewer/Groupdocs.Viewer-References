---
title: "view yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Tüm belge sayfalarının görünümünü oluşturur."
type: docs
url: /tr/python-net/groupdocs.viewer/viewer/view/
is_root: false
weight: 1130
---


## view {#options}

Tüm belge sayfalarının görünümünü oluşturur.

Daha fazla bilgi edinin

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | `ViewOptions` | Görünüm seçenekleri. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `options` None olduğunda. |
| `PasswordRequiredException` | Belgeyi açmak için bir şifre gerektiğinde. |
| `IncorrectPasswordException` | Belirtilen şifre yanlış olduğunda. |
| `GroupDocsViewerException` | Ek bulunamadığında. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-page_numbers}

Belirli belge sayfalarının görünümünü oluşturur.

Daha fazla bilgi edinin

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, page_numbers):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | `ViewOptions` | Görünüm seçenekleri. |
| page_numbers | `list[int]` | Görüntülenecek sayfa numaraları. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `page_numbers` boş olduğunda. |
| `PasswordRequiredException` | Belgeyi açmak için parola gerektiğinde. |
| `IncorrectPasswordException` | belirtilen şifre yanlış olduğunda. |
| `GroupDocsViewerException` | ek dosya bulunamadığında. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-cancellation_token-page_numbers}

Belirli belge sayfalarının görünümünü oluşturur.

Daha fazla bilgi edinin:

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, cancellation_token, page_numbers):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | `ViewOptions` | Görünüm seçenekleri. |
| cancellation_token | `CancellationToken` | İşlemi iptal etmek için iptal belirteci. |
| page_numbers | `list[int]` | Görüntülenecek sayfa numaraları. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `page_numbers` boş olduğunda. |
| `PasswordRequiredException` | Belgeyi açmak için şifre gerektiğinde. |
| `IncorrectPasswordException` | Belirtilen şifre yanlış olduğunda. |
| `GroupDocsViewerException` | Ek dosya bulunamadığında. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Ayrıca Bakınız
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
