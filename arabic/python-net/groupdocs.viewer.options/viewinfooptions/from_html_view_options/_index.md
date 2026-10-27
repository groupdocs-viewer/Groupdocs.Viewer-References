---
title: "طريقة from_html_view_options"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يُهيئ كائنًا من فئة ViewInfoOptions بناءً على كائن HtmlViewOptions."
type: docs
url: /ar/python-net/groupdocs.viewer.options/viewinfooptions/from_html_view_options/
is_root: false
weight: 1080
---


## from_html_view_options {#options}

يُهيئ كائنًا من فئة ViewInfoOptions بناءً على كائن HtmlViewOptions.

```python
def from_html_view_options(cls, options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | `HtmlViewOptions` | خيارات عرض HTML. |

**Returns:** A new ViewInfoOptions instance.

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `options` هو None. |

### مثال

```python
from groupdocs.viewer.options import ViewInfoOptions, HtmlViewOptions

html_opts = HtmlViewOptions()
view_info_opts = ViewInfoOptions.from_html_view_options(html_opts)
```

### انظر أيضًا
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
