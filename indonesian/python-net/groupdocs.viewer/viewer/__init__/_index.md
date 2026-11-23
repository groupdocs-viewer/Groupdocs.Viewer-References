---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi instance baru dari kelas Viewer."
type: docs
url: /id/python-net/groupdocs.viewer/viewer/__init__/
is_root: false
weight: 10
---


## __init__ {#get_file_stream}

Menginisialisasi instance baru dari kelas [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Pelajari lebih lanjut

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Metode yang mengembalikan aliran yang dapat dibaca. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Dilempar ketika `get_file_stream` bernilai None. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options}

Menginisialisasi instance baru dari [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

```python
def __init__(self, get_file_stream, get_load_options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Metode yang mengembalikan aliran yang dapat dibaca. |
| get_load_options | `Func[LoadOptions]` | Metode yang mengembalikan opsi pemuatan dokumen. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Dilempar ketika `get_load_options` bernilai None. |
| `Remarks` | - Selengkapnya tentang tipe file yang didukung oleh GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats - Selengkapnya tentang fitur GroupDocs.Viewer untuk .NET: https://docs.groupdocs.com/display/viewernet/Developer+Guide - Selengkapnya tentang memuat dokumen terenkripsi dan melihat file dari penyimpanan pihak ketiga dengan GroupDocs.Viewer untuk .NET: https://docs.groupdocs.com/display/viewernet/Loading |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#get_file_stream-settings}

Menginisialisasi [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) baru.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream, settings):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Metode yang mengembalikan aliran yang dapat dibaca. |
| settings | `ViewerSettings` | Pengaturan Viewer. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `settings` bernilai None. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options-settings}

Menginisialisasi instance Viewer baru.

Informasi lebih lanjut:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, get_file_stream, get_load_options, settings):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Callable yang mengembalikan aliran yang dapat dibaca. |
| get_load_options | `Func[LoadOptions]` | Callable yang mengembalikan opsi pemuatan dokumen. |
| settings | `ViewerSettings` | Pengaturan Viewer. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `settings` bernilai None. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#stream}

Menginisialisasi instance baru dari kelas [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | `io.RawIOBase` | Aliran file. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Dilempar ketika `stream` bernilai None. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-leave_open}

Menginisialisasi instance Viewer baru.

Pelajari lebih lanjut:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, leave_open):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | `io.RawIOBase` | Aliran file. |
| leave_open | `bool` | True untuk membiarkan aliran tetap terbuka setelah objek Viewer dibuang; jika tidak, False. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `stream` bernilai None. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML — the hello‑world example."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#stream-load_options}

Menginisialisasi instance baru dari [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Pelajari lebih lanjut:

- More about file types supported by GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats>
- More about GroupDocs.Viewer for .NET features: <https://docs.groupdocs.com/display/viewernet/Developer+Guide>
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: <https://docs.groupdocs.com/display/viewernet/Loading>

```python
def __init__(self, stream, load_options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | `io.RawIOBase` | Aliran file. |
| load_options | `LoadOptions` | Opsi pemuatan dokumen. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `load_options` bernilai None. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-leave_open}

Menginisialisasi instance Viewer baru.

```python
def __init__(self, stream, load_options, leave_open):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | `io.RawIOBase` | Aliran file. |
| load_options | `LoadOptions` | Opsi pemuatan dokumen. |
| leave_open | `bool` | True untuk membiarkan aliran tetap terbuka setelah objek Viewer dibuang; jika tidak, False. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `load_options` bernilai None. |
| `Remarks` | - Informasi lebih lanjut tentang tipe file yang didukung oleh GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats> - Informasi lebih lanjut tentang fitur GroupDocs.Viewer untuk .NET: <https://docs.groupdocs.com/display/viewernet/Developer+Guide> - Informasi lebih lanjut tentang memuat dokumen terenkripsi dan melihat file dari penyimpanan pihak ketiga dengan GroupDocs.Viewer untuk .NET: <https://docs.groupdocs.com/display/viewernet/Loading> |

### Contoh

```python
import io
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream, loadOptions=None, leaveOpen=False)
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings}

Menginisialisasi instance Viewer baru.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, settings):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | `io.RawIOBase` | Aliran file. |
| settings | `ViewerSettings` | Pengaturan Viewer. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `settings` bernilai None. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings-leave_open}

Menginisialisasi instance Viewer baru.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

```python
def __init__(self, stream, settings, leave_open):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | `io.RawIOBase` | Aliran file. |
| settings | `ViewerSettings` | Pengaturan Viewer. |
| leave_open | `bool` | True untuk membiarkan aliran tetap terbuka setelah objek Viewer dibuang; jika tidak, False. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `settings` bernilai None. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-settings}

Menginisialisasi instance Viewer baru.

Konstruktor memerlukan aliran file (`io.RawIOBase`) dan secara opsional menerima opsi pemuatan dokumen serta pengaturan Viewer.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | `io.RawIOBase` | Aliran file. |
| load_options | `LoadOptions` | Opsi pemuatan dokumen. |
| settings | `ViewerSettings` | Pengaturan Viewer. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `stream`, `load_options`, atau `settings` bernilai None. |

### Contoh

```python
from groupdocs.viewer import Viewer

# Buka file sebagai aliran biner dan buat Viewer
with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream)
    # Gunakan viewer, mis., render ke HTML
    # ...
```

## __init__ {#stream-load_options-settings-leave_open}

Menginisialisasi instance baru dari [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Pelajari lebih lanjut:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings, leave_open):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | `io.RawIOBase` | Aliran file. |
| load_options | `LoadOptions` | Opsi pemuatan dokumen. |
| settings | `ViewerSettings` | Pengaturan Viewer. |
| leave_open | `bool` | True untuk membiarkan aliran tetap terbuka setelah objek Viewer dibuang; jika tidak, False. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `settings` bernilai None. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path}

Menginisialisasi instance baru dari kelas [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur ke file yang akan dirender. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `file_path` bernilai `None` atau kosong. |

### Contoh

```python
from groupdocs.viewer import Viewer

# Inisialisasi viewer dengan jalur dokumen
with Viewer("./sample.docx") as viewer:
    # viewer siap merender dokumen
    pass
```

## __init__ {#file_path-settings}

Menginisialisasi instance baru dari kelas [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Pelajari lebih lanjut:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur ke file yang akan dirender. |
| settings | `ViewerSettings` | Pengaturan Viewer. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `settings` bernilai null. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options}

Menginisialisasi instance baru dari [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: Document formats supported by GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: Developer Guide (https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: How to load and view document with GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur ke file yang akan dirender. |
| load_options | `LoadOptions` | Opsi yang digunakan untuk membuka file. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `load_options` bernilai None. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options-settings}

Menginisialisasi instance Viewer baru.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur ke file yang akan dirender. |
| load_options | `LoadOptions` | Opsi yang digunakan untuk membuka file. |
| settings | `ViewerSettings` | Pengaturan Viewer. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `settings` bernilai None. |

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
