---
title: "Cargar documento desde un flujo"
linkTitle: "Load from stream"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Cargar documentos directamente desde un objeto similar a un archivo — controlador de archivo abierto, BytesIO o cualquier flujo — con GroupDocs.Viewer para Python a través de .NET."
type: docs
url: /es/python-net/guides/load-document-from-stream/
is_root: false
weight: 60
---


Puede cargar un documento desde un flujo sin guardarlo como un archivo en el disco. Puede usar esta función para cargar un documento desde diferentes fuentes como una URL, FTP, etc.

Para cargar un documento desde un flujo, siga estos pasos:

1. Implemente un método para obtener el flujo del documento.
2. Llame al constructor de la clase [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Especifique el método implementado en el paso anterior.

El siguiente fragmento de código muestra cómo cargar un documento desde un flujo:

{{< tabs \"example1\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_stream():
    # Abrir flujo del documento
    stream = open("sample.docx", "rb")

    # Renderizar un documento desde el flujo.
    with Viewer(stream) as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    load_document_from_stream()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` es el archivo de ejemplo utilizado en este caso. Haga clic [aquí](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-stream/sample.docx) para descargarlo.

{{< /tab >}}
{{< tab \"load-document-from-stream-outputs.zip\" >}}
```text
page_1.html (317 KB)
page_2.html (149 KB)
page_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/loading-documents/load-document-from-stream/load_document_from_stream/load-document-from-stream-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

Consulte también [Load document from URL]() para un ejemplo concreto de descarga de un documento en un flujo `BytesIO` y su renderizado sin nunca escribirlo en disco.
