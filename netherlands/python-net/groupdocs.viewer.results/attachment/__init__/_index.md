---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een nieuw Attachment‑exemplaar."
type: docs
url: /nl/python-net/groupdocs.viewer.results/attachment/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/) exemplaar.

```python
def __init__(self):
    ...
```

## __init__ {#file_name-file_path}

Initialiseert een nieuw Attachment‑exemplaar.

```python
def __init__(self, file_name, file_path):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_name | `str` | Bestandsnaam van de bijlage. |
| file_path | `str` | Relatief pad van de bijlage bijv. "folder/file.docx" of bestandsnaam wanneer het bestand zich in de hoofdmap van een archief bevindt, in een e‑mailbericht of gegevensbestand. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `file_path` None of leeg is. |

## __init__ {#id-file_name-file_path-size}

Initialiseert een nieuw exemplaar van de Attachment‑klasse.

```python
def __init__(self, id, file_name, file_path, size):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| id | `str` | Unieke (in de context van één bestand) identifier van de attachment. |
| file_name | `str` | Bestandsnaam van de bijlage. |
| file_path | `str` | Relatief pad van de bijlage bijv. `folder/file.docx` of bestandsnaam wanneer het bestand zich in de hoofdmap van een archief bevindt, in een e‑mailbericht of gegevensbestand. |
| size | `int` | Grootte van bijlagebestand in bytes. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `file_path` null of leeg is. |

## __init__ {#id-file_name-file_path-file_type-size}

Initialiseert een nieuw exemplaar van de Attachment‑klasse.

```python
def __init__(self, id, file_name, file_path, file_type, size):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| id | `str` | Unieke (in de context van één bestand) identifier van de attachment. |
| file_name | `str` | Bestandsnaam van de bijlage. |
| file_path | `str` | Relatief pad van de bijlage bijv. `folder/file.docx` of bestandsnaam wanneer het bestand zich in de hoofdmap van een archief bevindt, in een e‑mailbericht of gegevensbestand. |
| file_type | `FileType` | Type van bijlagebestand. |
| size | `int` | Grootte van bijlagebestand in bytes. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `file_type` null is. |

### Zie ook
* class [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/)
