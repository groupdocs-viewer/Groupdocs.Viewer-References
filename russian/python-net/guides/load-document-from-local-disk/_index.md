---
title: "Загрузить документ с локального диска"
linkTitle: "Load from local disk"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Загрузите документы с вашего локального диска, используя путь к файлу, с помощью GroupDocs.Viewer для Python через .NET."
type: docs
url: /ru/python-net/guides/load-document-from-local-disk/
is_root: false
weight: 50
---


Вы можете загрузить документ с локального диска, используя путь к файлу. GroupDocs.Viewer открывает файл в режиме только для чтения.

Следующий фрагмент кода показывает, как загрузить документ, используя строку локального пути:

{{< tabs \"example1\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_local_disk():
    # Загрузить документ с локального диска
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_embedded_resources("load_document_from_local_disk/document_from_local_disk_{0}.html")
        viewer.view(html_options)

if __name__ == "__main__":
    load_document_from_local_disk()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` — это пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-local-disk/sample.docx), чтобы скачать его.

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
