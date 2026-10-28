---
title: "Перестановка страниц"
linkTitle: "Reorder pages"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Переставляйте страницы PDF во время рендеринга с помощью GroupDocs.Viewer для Python через .NET. Управляйте последовательностью страниц в выводе."
type: docs
url: /ru/python-net/guides/reorder-pages/
is_root: false
weight: 100
---


GroupDocs.Viewer сохраняет порядок страниц в исходном документе. Вместо этого вы можете изменить порядок страниц в выходном PDF‑документе.

Чтобы переупорядочить страницы, выполните следующие действия:

1. Создайте объект [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer).
2. Создайте объект [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions).
3. Вызовите метод [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) объекта [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Укажите новый порядок страниц в последних параметрах.

Следующий фрагмент кода показывает, как переупорядочить страницы:

{{< tabs \"example1\">}}
{{< tab \"Python\">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def reorder_pages():
    # Загрузить документ
    with Viewer("sample.docx") as viewer:
        # Создайте параметры просмотра.
        viewOptions = PdfViewOptions("reorder_pages/reordered_pages.pdf")

        # Передайте номера страниц в том порядке, в котором вы хотите их отобразить.
        viewer.view(viewOptions, [2, 1])

if __name__ == "__main__":
    reorder_pages()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` — пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/sample.docx) чтобы скачать его.

{{< /tab >}}
{{< tab \"reordered_pages.pdf\" >}}
```text
Binary file (PDF, 176 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/reorder_pages/reordered_pages.pdf)
{{< /tab >}}
{{< /tabs >}}
