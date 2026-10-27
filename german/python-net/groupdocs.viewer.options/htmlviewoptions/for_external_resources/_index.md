---
title: "Methode for_external_resources"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine Instanz der HtmlViewOptions-Klasse zum Rendern in HTML mit externen Ressourcen."
type: docs
url: /de/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/
is_root: false
weight: 1060
---


## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url}

Initialisiert eine Instanz der [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) Klasse zum Rendern in HTML mit externen Ressourcen.

Siehe das Codebeispiel in der Dokumentation.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Die Methode, die den Stream erstellt, der zum Schreiben der Ausgabeseitendaten verwendet wird. |
| create_resource_stream | `CreateResourceStream` | Die Methode, die den von der Methode `create_page_stream` erstellten Stream freigibt. |
| create_resource_url | `CreateResourceUrl` | Die Methode, die eine URL für die HTML-Ressource erstellt. |

**Returns:** New instance of the `HtmlViewOptions` class for rendering into HTML with external resources.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `create_resource_url` None ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("sample.docx") as viewer:
    options = HtmlViewOptions.for_external_resources(
        "page_{0}.html",
        "page_{0}/resource_{0}_{1}",
        "page_{0}/resource_{0}_{1}"
    )
    viewer.view(options)
```

## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url-release_page_stream-release_resource_stream}

Initialisiert eine Instanz der HtmlViewOptions-Klasse zum Rendern in HTML mit externen Ressourcen.

Für weitere Anwendungsbeispiele siehe die GroupDocs Viewer-Dokumentation.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url, release_page_stream, release_resource_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Die Methode, die einen Stream erzeugt, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| create_resource_stream | `CreateResourceStream` | Die Methode, die einen Stream erstellt, der zum Schreiben der Ausgabedaten der HTML-Ressource verwendet wird. |
| create_resource_url | `CreateResourceUrl` | Die Methode, die eine URL für eine HTML-Ressource erstellt. |
| release_page_stream | `ReleasePageStream` | Die Methode, die den von dem an `create_page_stream` übergebenen Delegaten erstellten Stream freigibt. |
| release_resource_stream | `ReleaseResourceStream` | Die Methode, die den von dem an `create_resource_stream` übergebenen Delegaten erstellten Stream freigibt. |

**Returns:** HtmlViewOptions: New instance of the HtmlViewOptions class for rendering into HTML with external resources.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `release_resource_stream` None ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_excel_to_html_external():
    # Excel‑Tabellendokument laden
    with Viewer("invoice.xlsx") as viewer:
        # Konvertieren Sie die Tabelle in HTML mit externen Ressourcen.
        # {0} und {1} werden jeweils durch die aktuelle Seitennummer bzw. den Ressourcennamen ersetzt.
        view_options = HtmlViewOptions.for_external_resources(
            "render_excel_to_html_external/pdf_page_{0}.html",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}"
        )
        viewer.view(view_options)

if __name__ == "__main__":
    render_excel_to_html_external()
```

## for_external_resources {#page_stream_factory-resource_stream_factory}

Initialisiert eine HtmlViewOptions-Instanz zum Rendern in HTML mit externen Ressourcen.

Weitere Details finden Sie in der Online‑Dokumentation.

```python
def for_external_resources(cls, page_stream_factory, resource_stream_factory):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Die Fabrik, die Methoden zum Erstellen und Freigeben des Ausgabeseiten‑Streams implementiert. |
| resource_stream_factory | `IResourceStreamFactory` | Die Fabrik, die die für das Erstellen von Ressourcen‑URLs, das Instanziieren und das Freigeben von Ausgabestreams für HTML‑Ressourcen erforderlichen Methoden implementiert. |

**Returns:** HtmlViewOptions: A new HtmlViewOptions instance configured for external resources.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Falls `resource_stream_factory` None ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Erstellen Sie für jede Seite eine HTML‑Datei und speichern Sie externe Ressourcen separat.
    # {0} und {1} werden jeweils durch die aktuelle Seitennummer bzw. den Ressourcennamen ersetzt.
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

## for_external_resources

Initialisiert eine HtmlViewOptions-Instanz, die konfiguriert ist, HTML-Dateien mit externen Ressourcen zu erzeugen.

Die Instanz verwendet die bereitgestellten Formatzeichenketten:
- `html_file_path_format` – file path format for the output HTML files (e.g., `"page_{0}.html"`).
- `resources_path_format` – folder path format for external resource files (e.g., `"page_{0}/resource_{0}_{1}"`).
- `resources_url_format` – URL format for HTML resources (e.g., `"page_{0}/resource_{0}_{1}"`).

Die Ausgabedateien werden im aktuellen Arbeitsverzeichnis der Anwendung abgelegt.

```python
def for_external_resources(cls):
    ...
```

**Returns:** HtmlViewOptions: Configured options for rendering HTML with external resources.

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html_external():
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html_external()
```

## for_external_resources {#file_path_format-resource_file_path_format-resource_url_format}

Initialisiert eine Instanz der [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) Klasse.

Siehe das Codebeispiel in der Dokumentation.

```python
def for_external_resources(cls, file_path_format, resource_file_path_format, resource_url_format):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path_format | `str` | Das Dateipfadformat, z. B. `'page_{0}.html'`. |
| resource_file_path_format | `str` | Das Ressourcen‑Dateipfadformat, z. B. `'page_{0}/resource_{1}'`. |
| resource_url_format | `str` | Das Ressourcen‑URL‑Format, z. B. `'page_{0}/resource_{1}'`. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Falls `resource_url_format` None oder leer ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Laden Sie ein Dokument und rendern Sie jede Seite in eine HTML‑Datei mit externen Ressourcen.
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

### Siehe auch
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
