---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una nueva instancia de Attachment."
type: docs
url: /es/python-net/groupdocs.viewer.results/attachment/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/).

```python
def __init__(self):
    ...
```

## __init__ {#file_name-file_path}

Inicializa una nueva instancia de Attachment.

```python
def __init__(self, file_name, file_path):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_name | `str` | Nombre de archivo del adjunto. |
| file_path | `str` | Ruta relativa del adjunto, p. ej. \"folder/file.docx\" o nombre de archivo cuando el archivo se encuentra en la raíz de un archivo comprimido, en un mensaje de correo electrónico o en un archivo de datos. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `file_path` es None o está vacío. |

## __init__ {#id-file_name-file_path-size}

Inicializa una nueva instancia de la clase Attachment.

```python
def __init__(self, id, file_name, file_path, size):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| id | `str` | Identificador único (en el contexto de un solo archivo) del adjunto. |
| file_name | `str` | Nombre de archivo del adjunto. |
| file_path | `str` | Ruta relativa del adjunto, p. ej. `folder/file.docx` o nombre de archivo cuando el archivo se encuentra en la raíz de un archivo comprimido, en un mensaje de correo electrónico o en un archivo de datos. |
| size | `int` | Tamaño del archivo adjunto en bytes. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `file_path` es nulo o está vacío. |

## __init__ {#id-file_name-file_path-file_type-size}

Inicializa una nueva instancia de la clase Attachment.

```python
def __init__(self, id, file_name, file_path, file_type, size):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| id | `str` | Identificador único (en el contexto de un solo archivo) del adjunto. |
| file_name | `str` | Nombre de archivo del adjunto. |
| file_path | `str` | Ruta relativa del adjunto, p. ej. `folder/file.docx` o nombre de archivo cuando el archivo se encuentra en la raíz de un archivo comprimido, en un mensaje de correo electrónico o en un archivo de datos. |
| file_type | `FileType` | Tipo de archivo adjunto. |
| size | `int` | Tamaño del archivo adjunto en bytes. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `file_type` es nulo. |

### Ver también
* class [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/)
