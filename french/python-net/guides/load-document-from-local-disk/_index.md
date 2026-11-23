---
title: "Charger le document depuis le disque local"
linkTitle: "Load from local disk"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Chargez des documents depuis votre disque local en utilisant un chemin de fichier avec GroupDocs.Viewer pour Python via .NET."
type: docs
url: /fr/python-net/guides/load-document-from-local-disk/
is_root: false
weight: 50
---


Vous pouvez charger un document depuis un disque local en utilisant le chemin d'un fichier. GroupDocs.Viewer ouvre le fichier en mode lecture seule.

L'extrait de code suivant montre comment charger un document en utilisant la chaîne de chemin local :

{{< tabs \"example1\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_local_disk():
    # Charger le document depuis le disque local
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_embedded_resources("load_document_from_local_disk/document_from_local_disk_{0}.html")
        viewer.view(html_options)

if __name__ == "__main__":
    load_document_from_local_disk()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-local-disk/sample.docx) pour le télécharger.

{{< /tab >}}
{{< tab "load-document-from-local-disk-outputs.zip" >}}
```text
load_document_from_local_disk/document_from_local_disk_1.html (317 KB)
load_document_from_local_disk/document_from_local_disk_2.html (149 KB)
load_document_from_local_disk/document_from_local_disk_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/loading-documents/load-document-from-local-disk/load_document_from_local_disk/load-document-from-local-disk-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
