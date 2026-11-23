---
title: "Загрузить документ из потока"
linkTitle: "Load from stream"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Загружайте документы напрямую из объектоподобного файла — открытого файлового дескриптора, BytesIO или любого потока — с помощью GroupDocs.Viewer для Python через .NET."
type: docs
url: /ru/python-net/guides/load-document-from-stream/
is_root: false
weight: 60
---


Вы можете загрузить документ из потока, не сохраняя его как файл на диске. Эта возможность позволяет загружать документ из разных источников, таких как URL, FTP и т.д.

Чтобы загрузить документ из потока, выполните следующие шаги:

1. Реализуйте метод для получения потока документа.
2. Вызовите конструктор класса [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) . Укажите метод, реализованный на предыдущем шаге.

Следующий фрагмент кода показывает, как загрузить документ из потока:

{{< tabs \"example1\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_stream():
    # Открыть поток документа
    stream = open("sample.docx", "rb")

    # Отобразить документ из потока.
    with Viewer(stream) as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    load_document_from_stream()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` — пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-stream/sample.docx) чтобы скачать его.

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

См. также [Load document from URL](), где приведён конкретный пример загрузки документа в поток `BytesIO` и его отображения без записи на диск.
