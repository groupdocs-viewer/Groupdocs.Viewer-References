---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Yeni bir Attachment örneği başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.results/attachment/__init__/
is_root: false
weight: 10
---


## __init__

Yeni bir [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/) örneği başlatır.

```python
def __init__(self):
    ...
```

## __init__ {#file_name-file_path}

Yeni bir Attachment örneği başlatır.

```python
def __init__(self, file_name, file_path):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_name | `str` | Ek dosya adı. |
| file_path | `str` | Ek dosyanın göreli yolu, örn. "folder/file.docx" veya dosya arşivin kökünde, e‑mail mesajında veya veri dosyasında bulunduğunda dosya adı. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `file_path` None veya boş ise. |

## __init__ {#id-file_name-file_path-size}

Attachment sınıfının yeni bir örneğini başlatır.

```python
def __init__(self, id, file_name, file_path, size):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| id | `str` | Tek dosya bağlamında benzersiz ek tanımlayıcısı. |
| file_name | `str` | Ek dosya adı. |
| file_path | `str` | Ek dosyanın göreli yolu, örn. `folder/file.docx` veya dosya arşivin kökünde, e‑mail mesajında veya veri dosyasında bulunduğunda dosya adı. |
| size | `int` | Ek dosya boyutu bayt cinsinden. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `file_path` null veya boş ise. |

## __init__ {#id-file_name-file_path-file_type-size}

Attachment sınıfının yeni bir örneğini başlatır.

```python
def __init__(self, id, file_name, file_path, file_type, size):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| id | `str` | Tek dosya bağlamında benzersiz ek tanımlayıcısı. |
| file_name | `str` | Ek dosya adı. |
| file_path | `str` | Ek dosyanın göreli yolu, örn. `folder/file.docx` veya dosya arşivin kökünde, e‑mail mesajında veya veri dosyasında bulunduğunda dosya adı. |
| file_type | `FileType` | Ek dosya türü. |
| size | `int` | Ek dosya boyutu bayt cinsinden. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `file_type` null olduğunda. |

### Ayrıca Bakınız
* class [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/)
