---
title: "Carica documento dallo stream"
linkTitle: "Load from stream"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Carica i documenti direttamente da un oggetto simile a un file — handle di file aperto, BytesIO o qualsiasi stream — con GroupDocs.Viewer per Python via .NET."
type: docs
url: /it/python-net/guides/load-document-from-stream/
is_root: false
weight: 60
---


Puoi caricare un documento da uno stream senza salvarlo come file su disco. Puoi utilizzare questa funzionalità per caricare un documento da diverse fonti come un URL, FTP e così via.

Per caricare un documento da uno stream, segui questi passaggi:

1. Implementa un metodo per ottenere lo stream del documento.
2. Chiama il costruttore della classe [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Specifica il metodo implementato nel passaggio precedente.

Il seguente frammento di codice mostra come caricare un documento da uno stream:

{{< tabs \"example1\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_stream():
    # Apri lo stream del documento
    stream = open("sample.docx", "rb")

    # Renderizza un documento dallo stream.
    with Viewer(stream) as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    load_document_from_stream()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-stream/sample.docx) per scaricarlo.

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

Vedi anche [Load document from URL]() per un esempio concreto di download di un documento in uno stream `BytesIO` e della sua renderizzazione senza mai scriverlo su disco.
