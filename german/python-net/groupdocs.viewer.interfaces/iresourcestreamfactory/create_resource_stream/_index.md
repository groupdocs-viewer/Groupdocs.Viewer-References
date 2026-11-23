---
title: "create_resource_stream Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Erstellt den Stream, der zum Schreiben der HTML-Ressourcendaten der Ausgabe verwendet wird."
type: docs
url: /de/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/
is_root: false
weight: 1010
---


## create_resource_stream {#page_number-resource}

Erstellt den Stream, der zum Schreiben der HTML-Ressourcendaten der Ausgabe verwendet wird.

```python
def create_resource_stream(self, page_number, resource):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page_number | `int` | Die Nummer einer Seite. |
| resource | `Resource` | Die HTML-Ressource wie Schriftart, Stil, Bild oder Grafik. |

**Returns:** io.RawIOBase: Stream used to write output resource data.

### Beispiel

```python
from groupdocs.viewer import Viewer

viewer = Viewer()
factory = viewer.resource_stream_factory

# Erstelle einen Stream für eine CSS-Ressource auf Seite 1
stream = factory.create_resource_stream(pageNumber=1, resource="style.css")
with stream:
    stream.write(b"body { font-family: Arial; }")
```

### Siehe auch
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
