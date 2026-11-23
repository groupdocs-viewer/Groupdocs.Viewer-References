---
title: "Proteger documento PDF"
linkTitle: "Protect PDF document"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Asegure la salida PDF con contraseñas y permisos al renderizar documentos usando GroupDocs.Viewer."
type: docs
url: /es/python-net/guides/protect-pdf-document/
is_root: false
weight: 90
---


Puede proteger un documento PDF estableciendo los siguientes parámetros:

* permissions
* password to open document
* password to change permissions

Para proteger un documento PDF, siga estos pasos:

1. Cree una instancia de la clase [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Especifique la ruta del documento fuente como parámetro del constructor.
2. Instancie el objeto [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security).
3. Para especificar una contraseña para abrir el documento, establezca la propiedad [DocumentOpenPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties).
4. Para especificar una contraseña para cambiar las restricciones, establezca la propiedad [PermissionsPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties).
5. Para especificar los permisos del documento, establezca la propiedad [Permissions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/permissions).
6. Instancie el objeto [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions). Especifique el formato de la ruta de guardado para el documento renderizado.
7. Inicialice la propiedad [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/#properties) del objeto [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) con el objeto creado en los pasos 2-5.
8. Llame al método [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) del objeto [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). Especifique el objeto [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) como parámetro.

El siguiente fragmento de código muestra cómo proteger el documento PDF de salida:

{{< tabs \"example1\">}}
{{< tab \"Python\">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

def protect_pdf_document():
    # Cargar documento
    with Viewer("sample.docx") as viewer:
        # Especifique la configuración de seguridad.
        security = Security()
        security.document_open_password = "o123"
        security.permissions_password = "p123"
        security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

        # Cree un archivo PDF.
        pdf_options = PdfViewOptions("protect_pdf_document/protected_document.pdf")

        # Aplique la configuración de seguridad
        pdf_options.security = security
        viewer.view(pdf_options)

if __name__ == "__main__":
    protect_pdf_document()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` es el archivo de ejemplo utilizado en este caso. Haga clic en [aquí](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/sample.docx) para descargarlo.

{{< /tab >}}
{{< tab \"protected_document.pdf\" >}}
```text
Binary file (PDF, 238 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/protect_pdf_document/protected_document.pdf)
{{< /tab >}}
{{< /tabs >}}
