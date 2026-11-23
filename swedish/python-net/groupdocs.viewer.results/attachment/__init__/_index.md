---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en ny Attachment-instans."
type: docs
url: /sv/python-net/groupdocs.viewer.results/attachment/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/) instans.

```python
def __init__(self):
    ...
```

## __init__ {#file_name-file_path}

Initierar en ny Attachment-instans.

```python
def __init__(self, file_name, file_path):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_name | `str` | Bilagans filnamn. |
| file_path | `str` | Relativ sökväg för bilagan, t.ex. "folder/file.docx" eller filnamn när filen ligger i rotkatalogen i ett arkiv, i e‑mailmeddelande eller datafil. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `file_path` är None eller tom. |

## __init__ {#id-file_name-file_path-size}

Initierar en ny instans av Attachment-klassen.

```python
def __init__(self, id, file_name, file_path, size):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| id | `str` | Unik (i kontext av en enda fil) identifierare för bilagan. |
| file_name | `str` | Bilagans filnamn. |
| file_path | `str` | Relativ sökväg för bilagan, t.ex. `folder/file.docx` eller filnamn när filen ligger i rotkatalogen i ett arkiv, i e‑mailmeddelande eller datafil. |
| size | `int` | Bilagans filstorlek i byte. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `file_path` är null eller tom. |

## __init__ {#id-file_name-file_path-file_type-size}

Initierar en ny instans av Attachment-klassen.

```python
def __init__(self, id, file_name, file_path, file_type, size):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| id | `str` | Unik (i kontext av en enda fil) identifierare för bilagan. |
| file_name | `str` | Bilagans filnamn. |
| file_path | `str` | Relativ sökväg för bilagan, t.ex. `folder/file.docx` eller filnamn när filen ligger i rotkatalogen i ett arkiv, i e‑mailmeddelande eller datafil. |
| file_type | `FileType` | Bilagans filtyp. |
| size | `int` | Bilagans filstorlek i byte. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `file_type` är null. |

### Se även
* class [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/)
