---
title: "kelas OutlookOptions"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Berisi opsi untuk merender file data Outlook."
type: docs
url: /id/python-net/groupdocs.viewer.options/outlookoptions/
is_root: false
weight: 130
---


## OutlookOptions class

Berisi opsi untuk merender file data Outlook.

Untuk detail, lihat dokumentasi GroupDocs.

Tipe OutlookOptions menampilkan anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/outlookoptions/__init__/) |  |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [address_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/address_filter/) | Alamat email yang digunakan untuk menyaring pesan berdasarkan pengirim atau penerima. |
| [folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/folder/) | Nama folder (misalnya Inbox, Sent Item, atau Deleted Items) yang akan dirender. |
| [max_items_in_folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/) | Jumlah maksimum pesan atau item yang dapat dirender dari satu folder. |
| [text_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/text_filter/) | Kata kunci yang digunakan untuk menyaring pesan. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_outlook():
    with Viewer("sample.pst") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "outlook.html"
        )
        # Batasi jumlah item yang dirender per folder.
        view_options.outlook_options.max_items_in_folder = 30
        viewer.view(view_options)
```

### Lihat Juga
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
