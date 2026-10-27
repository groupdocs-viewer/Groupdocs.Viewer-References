---
title: "保护 PDF 文档"
linkTitle: "Protect PDF document"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "在使用 GroupDocs.Viewer 渲染文档时，通过密码和权限保护 PDF 输出。"
type: docs
url: /zh/python-net/guides/protect-pdf-document/
is_root: false
weight: 90
---


You can protect a PDF document by setting the following parameters:

* permissions
* password to open document
* password to change permissions

To protect a PDF document, follow these steps:

1. Create an instance of the [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) class. Specify the source document path as a constructor parameter.
2. Instantiate the [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security) object.
3. To specify a password to open the document, set the [DocumentOpenPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties) property.
4. To specify a password to change restrictions, set the [PermissionsPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties) property.
5. To specify the document permissions, set the [Permissions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/permissions) property.
6. Instantiate the [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) object. Specify the saving path format for the rendered document.
7. Initialize the [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/#properties) property of the [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) object with the object created in steps 2-5.
8. Call the [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) method of the [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) object. Specify the [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) object as the parameter.

The following code snippet shows how to protect the output PDF document:

{{< tabs "example1">}}
{{< tab "Python">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

def protect_pdf_document():
    # 加载文档
    with Viewer("sample.docx") as viewer:
        # Specify the security settings.
        security = Security()
        security.document_open_password = "o123"
        security.permissions_password = "p123"
        security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

        # Create a PDF file.
        pdf_options = PdfViewOptions("protect_pdf_document/protected_document.pdf")

        # Apply the security settings
        pdf_options.security = security
        viewer.view(pdf_options)

if __name__ == "__main__":
    protect_pdf_document()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` 是本示例中使用的示例文件。点击 [此处](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/sample.docx) 下载。

{{< /tab >}}
{{< tab "protected_document.pdf" >}}
```text
Binary file (PDF, 238 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/protect_pdf_document/protected_document.pdf)
{{< /tab >}}
{{< /tabs >}}
