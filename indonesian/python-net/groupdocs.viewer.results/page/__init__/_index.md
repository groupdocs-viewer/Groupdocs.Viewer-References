---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi instance baru dari Page."
type: docs
url: /id/python-net/groupdocs.viewer.results/page/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi instance baru dari [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self):
    ...
```

## __init__ {#number-visible}

Menginisialisasi instance baru [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| number | `int` | Nomor halaman. |
| visible | `bool` | Indikator visibilitas halaman. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `number` kurang dari atau sama dengan nol. |

## __init__ {#number-name-visible}

Menginisialisasi instance Page baru.

```python
def __init__(self, number, name, visible):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| number | `int` | Nomor halaman. |
| name | `str` | Nama lembar kerja atau halaman. |
| visible | `bool` | Indikator visibilitas halaman. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `number` kurang atau sama dengan nol. |

## __init__ {#number-visible-width-height}

Menginisialisasi instance baru [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible, width, height):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| number | `int` | Nomor halaman. |
| visible | `bool` | Indikator visibilitas halaman. |
| width | `int` | Lebar halaman dalam piksel saat dilihat sebagai JPG atau PNG. |
| height | `int` | Tinggi halaman dalam piksel saat dilihat sebagai JPG atau PNG. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `height` kurang atau sama dengan nol. |

## __init__ {#number-name-visible-width-height}

Menginisialisasi instance baru dari [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| number | `int` | Nomor halaman. |
| name | `str` | Nama lembar kerja atau halaman. |
| visible | `bool` | Indikator visibilitas halaman. |
| width | `int` | Lebar halaman dalam piksel saat dilihat sebagai JPG atau PNG. |
| height | `int` | Tinggi halaman dalam piksel saat dilihat sebagai JPG atau PNG. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `height` kurang atau sama dengan nol. |

## __init__ {#number-visible-width-height-lines}

Menginisialisasi instance baru dari [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible, width, height, lines):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| number | `int` | Nomor halaman. |
| visible | `bool` | Indikator visibilitas halaman. |
| width | `int` | Lebar halaman dalam piksel saat dilihat sebagai JPG atau PNG. |
| height | `int` | Tinggi halaman dalam piksel saat dilihat sebagai JPG atau PNG. |
| lines | `List[Line]` | Baris-baris yang terdapat pada halaman saat dilihat sebagai JPG atau PNG dengan Ekstraksi Teks diaktifkan. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `lines` bernilai None. |

## __init__ {#number-name-visible-width-height-lines}

Menginisialisasi instance baru dari [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height, lines):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| number | `int` | Nomor halaman. |
| name | `str` | Nama lembar kerja atau halaman. |
| visible | `bool` | Indikator visibilitas halaman. |
| width | `int` | Lebar halaman dalam piksel saat dilihat sebagai JPG atau PNG. |
| height | `int` | Tinggi halaman dalam piksel saat dilihat sebagai JPG atau PNG. |
| lines | `List[Line]` | Baris-baris yang terdapat pada halaman saat dilihat sebagai JPG atau PNG dengan Ekstraksi Teks diaktifkan. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `lines` bernilai None. |

### Lihat Juga
* class [`Page`](/viewer/python-net/groupdocs.viewer.results/page/)
