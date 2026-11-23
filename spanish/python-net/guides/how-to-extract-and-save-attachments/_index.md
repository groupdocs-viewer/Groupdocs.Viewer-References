---
title: "Guardar adjuntos"
linkTitle: "Save attachments"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Recuperar y guardar archivos adjuntos de correos electrónicos, archivos de Outlook, archivos comprimidos y PDFs."
type: docs
url: /es/python-net/guides/how-to-extract-and-save-attachments/
is_root: false
weight: 110
---


Para obtener y guardar los archivos adjuntos, siga estos pasos:

1. Instanciar el objeto [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/). Especifique un archivo que contenga adjuntos.
2. Llamar al método [get_attachments](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods). Devuelve la colección de adjuntos.
3. Recorrer la colección. Para guardar un adjunto, llame al método [save_attachment](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods).

El siguiente fragmento de código muestra cómo obtener y guardar todos los adjuntos del archivo MSG:

NOTA: el fragmento de código proporcionado se adapta a todas las familias de formatos que admiten adjuntos: correos electrónicos, archivos de datos de Outlook, archivos comprimidos y documentos PDF.

{{< tabs \"example1\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.viewer import Viewer

def extract_and_save_attachments():
    # Cargar documento con adjuntos
    with Viewer("with_attachments.msg") as viewer:
        attachments = viewer.get_attachments()

        print("\nAttachments:")
        for attachment in attachments:
            print(attachment)
            # Guardar adjunto en disco
            viewer.save_attachment(attachment, f"./attachments/{attachment.file_name}")

    print(f"\nAttachments retrieved successfully.")

if __name__ == "__main__":
    extract_and_save_attachments()
```
{{< /tab >}}
{{< tab \"with_attachments.msg\" >}}

`with_attachments.msg` es el archivo de ejemplo utilizado en este caso. Haga clic [aquí](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/processing-attachments/with_attachments.msg) para descargarlo.

{{< /tab >}}
{{< tab \"extract-and-save-attachments-outputs.zip\" >}}
```text
attachments/attachment-image.png (26 KB)
attachments/attachment-word.doc (220 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/processing-attachments/how-to-extract-and-save-attachments/extract_and_save_attachments/extract-and-save-attachments-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
