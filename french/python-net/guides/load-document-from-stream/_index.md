---
title: "Charger le document depuis un flux"
linkTitle: "Load from stream"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Chargez des documents directement depuis un objet de type fichier — poignée de fichier ouverte, BytesIO ou tout flux — avec GroupDocs.Viewer pour Python via .NET."
type: docs
url: /fr/python-net/guides/load-document-from-stream/
is_root: false
weight: 60
---


Vous pouvez charger un document depuis un flux sans l’enregistrer comme fichier sur le disque. Vous pouvez utiliser cette fonctionnalité pour charger un document depuis différentes sources telles qu’une URL, FTP, etc.

Pour charger un document depuis un flux, suivez ces étapes :

1. Implémentez une méthode pour obtenir le flux du document.
2. Appelez le constructeur de classe [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Spécifiez la méthode implémentée à l’étape précédente.

Le fragment de code suivant montre comment charger un document depuis un flux :

{{< tabs \"example1\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_stream():
    # Ouvrir le flux du document
    stream = open("sample.docx", "rb")

    # Rendre un document depuis le flux.
    with Viewer(stream) as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    load_document_from_stream()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` est le fichier d’exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-stream/sample.docx) pour le télécharger.

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

Voir aussi [Load document from URL]() pour un exemple concret de téléchargement d’un document dans un flux `BytesIO` et de son rendu sans jamais l’écrire sur le disque.
