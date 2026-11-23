---
title: "Защитить PDF‑документ"
linkTitle: "Protect PDF document"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Обеспечьте безопасность PDF‑вывода с помощью паролей и разрешений при рендеринге документов с использованием GroupDocs.Viewer."
type: docs
url: /ru/python-net/guides/protect-pdf-document/
is_root: false
weight: 90
---


Вы можете защитить PDF‑документ, задав следующие параметры:

* permissions
* password to open document
* password to change permissions

Чтобы защитить PDF‑документ, выполните следующие шаги:

1. Создайте экземпляр класса [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Укажите путь к исходному документу в качестве параметра конструктора.
2. Создайте объект [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security).
3. Чтобы указать пароль для открытия документа, задайте свойство [DocumentOpenPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties).
4. Чтобы указать пароль для изменения ограничений, задайте свойство [PermissionsPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties).
5. Чтобы указать разрешения документа, задайте свойство [Permissions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/permissions).
6. Создайте объект [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions). Укажите формат пути сохранения для отрендеренного документа.
7. Инициализируйте свойство [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/#properties) объекта [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) объектом, созданным на шагах 2‑5.
8. Вызовите метод [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) объекта [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Укажите объект [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) в качестве параметра.

Следующий фрагмент кода показывает, как защитить результирующий PDF‑документ:

{{< tabs \"example1\">}}
{{< tab \"Python\">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

def protect_pdf_document():
    # Загрузить документ
    with Viewer("sample.docx") as viewer:
        # Укажите параметры безопасности.
        security = Security()
        security.document_open_password = "o123"
        security.permissions_password = "p123"
        security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

        # Создайте PDF‑файл.
        pdf_options = PdfViewOptions("protect_pdf_document/protected_document.pdf")

        # Примените параметры безопасности
        pdf_options.security = security
        viewer.view(pdf_options)

if __name__ == "__main__":
    protect_pdf_document()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` — это пример файла, используемый в данном примере. Нажмите [здесь](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/sample.docx) чтобы скачать его.

{{< /tab >}}
{{< tab \"protected_document.pdf\" >}}
```text
Binary file (PDF, 238 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/protect_pdf_document/protected_document.pdf)
{{< /tab >}}
{{< /tabs >}}
