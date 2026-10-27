---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Attachment-Instanz."
type: docs
url: /de/python-net/groupdocs.viewer.results/attachment/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/) Instanz.

```python
def __init__(self):
    ...
```

## __init__ {#file_name-file_path}

Initialisiert eine neue Attachment-Instanz.

```python
def __init__(self, file_name, file_path):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_name | `str` | Dateiname des Anhangs. |
| file_path | `str` | Relativer Pfad des Anhangs, z. B. "folder/file.docx" oder Dateiname, wenn die Datei im Stammverzeichnis eines Archivs, in einer E‑Mail‑Nachricht oder einer Datendatei liegt. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `file_path` None oder leer ist. |

## __init__ {#id-file_name-file_path-size}

Initialisiert eine neue Instanz der Klasse Attachment.

```python
def __init__(self, id, file_name, file_path, size):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| id | `str` | Eindeutiger (im Kontext einer einzelnen Datei) Bezeichner des Anhangs. |
| file_name | `str` | Dateiname des Anhangs. |
| file_path | `str` | Relativer Pfad des Anhangs, z. B. `folder/file.docx` oder Dateiname, wenn die Datei im Stammverzeichnis eines Archivs, in einer E‑Mail‑Nachricht oder einer Datendatei liegt. |
| size | `int` | Dateigröße des Anhangs in Bytes. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `file_path` null oder leer ist. |

## __init__ {#id-file_name-file_path-file_type-size}

Initialisiert eine neue Instanz der Klasse Attachment.

```python
def __init__(self, id, file_name, file_path, file_type, size):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| id | `str` | Eindeutiger (im Kontext einer einzelnen Datei) Bezeichner des Anhangs. |
| file_name | `str` | Dateiname des Anhangs. |
| file_path | `str` | Relativer Pfad des Anhangs, z. B. `folder/file.docx` oder Dateiname, wenn die Datei im Stammverzeichnis eines Archivs, in einer E‑Mail‑Nachricht oder einer Datendatei liegt. |
| file_type | `FileType` | Dateityp des Anhangs. |
| size | `int` | Dateigröße des Anhangs in Bytes. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `file_type` null ist. |

### Siehe auch
* class [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/)
