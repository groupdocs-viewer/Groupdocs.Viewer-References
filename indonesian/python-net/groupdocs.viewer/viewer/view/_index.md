---
title: "metode view"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Membuat tampilan semua halaman dokumen."
type: docs
url: /id/python-net/groupdocs.viewer/viewer/view/
is_root: false
weight: 1130
---


## view {#options}

Membuat tampilan semua halaman dokumen.

Pelajari lebih lanjut

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | `ViewOptions` | Opsi tampilan. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `options` bernilai None. |
| `PasswordRequiredException` | Ketika kata sandi diperlukan untuk membuka dokumen. |
| `IncorrectPasswordException` | Ketika kata sandi yang ditentukan tidak benar. |
| `GroupDocsViewerException` | Ketika lampiran tidak dapat ditemukan. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-page_numbers}

Membuat tampilan halaman dokumen tertentu.

Pelajari lebih lanjut

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, page_numbers):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | `ViewOptions` | Opsi tampilan. |
| page_numbers | `list[int]` | Nomor halaman untuk ditampilkan. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | ketika `page_numbers` kosong. |
| `PasswordRequiredException` | ketika kata sandi diperlukan untuk membuka dokumen. |
| `IncorrectPasswordException` | ketika kata sandi yang ditentukan tidak benar. |
| `GroupDocsViewerException` | ketika lampiran tidak dapat ditemukan. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-cancellation_token-page_numbers}

Membuat tampilan halaman dokumen tertentu.

Pelajari lebih lanjut:

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, cancellation_token, page_numbers):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | `ViewOptions` | Opsi tampilan. |
| cancellation_token | `CancellationToken` | Token pembatalan untuk membatalkan pemrosesan. |
| page_numbers | `list[int]` | Nomor halaman untuk ditampilkan. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `page_numbers` kosong. |
| `PasswordRequiredException` | Ketika kata sandi diperlukan untuk membuka dokumen. |
| `IncorrectPasswordException` | Ketika kata sandi yang ditentukan tidak benar. |
| `GroupDocsViewerException` | Ketika lampiran tidak dapat ditemukan. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Lihat Juga
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
