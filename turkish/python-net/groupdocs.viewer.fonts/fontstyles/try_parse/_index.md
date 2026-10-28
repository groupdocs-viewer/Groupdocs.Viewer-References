---
title: "try_parse yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Belirtilen ham dizeyi bir yazı tipi stil adı olarak ayrıştırmayı dener."
type: docs
url: /tr/python-net/groupdocs.viewer.fonts/fontstyles/try_parse/
is_root: false
weight: 1060
---


## try_parse {#style-parsed}

Belirtilen ham dizeyi bir yazı tipi stil adı olarak ayrıştırmayı dener.

```python
def try_parse(cls, style, parsed):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| style | `str` | Yazı tipi stili olarak ayrıştırılması gereken dize. |
| parsed | `FontStyles` | Başarı durumunda ayrıştırılmış yazı tipi stili, başarısızlıkta `FontStyles.Regular`. |

**Returns:** bool: True if string was successfully parsed as a correct font style; False otherwise.

### Ayrıca Bakınız
* class [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/)
