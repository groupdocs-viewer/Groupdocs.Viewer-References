---
title: "طريقة try_parse"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يحاول تحليل السلسلة الخام المحددة كاسم لنمط الخط."
type: docs
url: /ar/python-net/groupdocs.viewer.fonts/fontstyles/try_parse/
is_root: false
weight: 1060
---


## try_parse {#style-parsed}

يحاول تحليل السلسلة الخام المحددة كاسم لنمط الخط.

```python
def try_parse(cls, style, parsed):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| style | `str` | سلسلة يجب تحليلها كنمط خط. |
| parsed | `FontStyles` | نمط الخط المُحلل عند النجاح أو `FontStyles.Regular` عند الفشل. |

**Returns:** bool: True if string was successfully parsed as a correct font style; False otherwise.

### انظر أيضًا
* class [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/)
