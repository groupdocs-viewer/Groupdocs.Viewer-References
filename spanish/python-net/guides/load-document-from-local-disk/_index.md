---
title: "Cargar documento desde el disco local"
linkTitle: "Load from local disk"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Cargar documentos desde su disco local usando una ruta de archivo con GroupDocs.Viewer para Python a través de .NET."
type: docs
url: /es/python-net/guides/load-document-from-local-disk/
is_root: false
weight: 50
---


Puede cargar un documento desde un disco local usando la ruta a un archivo. GroupDocs.Viewer abre el archivo en modo de solo lectura.

El siguiente fragmento de código muestra cómo cargar un documento usando la cadena de ruta local:

{{< tabs \"example1\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_local_disk():
    # Cargar documento desde el disco local
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_embedded_resources("load_document_from_local_disk/document_from_local_disk_{0}.html")
        viewer.view(html_options)

if __name__ == "__main__":
    load_document_from_local_disk()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` es el archivo de ejemplo usado en este caso. Haga clic [aquí](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-local-disk/sample.docx) para descargarlo.

{{< /tab >}}
{{< tab \"load-document-from-local-disk-outputs.zip\" >}}
```text
load_document_from_local_disk/document_from_local_disk_1.html (317 KB)
load_document_from_local_disk/document_from_local_disk_2.html (149 KB)
load_document_from_local_disk/document_from_local_disk_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/loading-documents/load-document-from-local-disk/load_document_from_local_disk/load-document-from-local-disk-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
