---
title: "metode from_html_view_options"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi sebuah instance kelas ViewInfoOptions berdasarkan objek HtmlViewOptions."
type: docs
url: /id/python-net/groupdocs.viewer.options/viewinfooptions/from_html_view_options/
is_root: false
weight: 1080
---


## from_html_view_options {#options}

Menginisialisasi sebuah instance kelas ViewInfoOptions berdasarkan objek HtmlViewOptions.

```python
def from_html_view_options(cls, options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | `HtmlViewOptions` | Opsi tampilan HTML. |

**Returns:** A new ViewInfoOptions instance.

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `options` adalah None. |

### Contoh

```python
from groupdocs.viewer.options import ViewInfoOptions, HtmlViewOptions

html_opts = HtmlViewOptions()
view_info_opts = ViewInfoOptions.from_html_view_options(html_opts)
```

### Lihat Juga
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
