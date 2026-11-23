---
title: "Salva gli allegati"
linkTitle: "Save attachments"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Recupera e salva gli allegati da email, file Outlook, archivi e PDF."
type: docs
url: /it/python-net/guides/how-to-extract-and-save-attachments/
is_root: false
weight: 110
---


Per ottenere e salvare gli allegati, segui questi passaggi:

1. Istanzia l'oggetto [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/). Specifica un file che contiene allegati.
2. Chiama il metodo [get_attachments](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods). Restituisce la collezione di allegati.
3. Itera attraverso la collezione. Per salvare un allegato, chiama il metodo [save_attachment](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods).

Il seguente frammento di codice mostra come ottenere e salvare tutti gli allegati dal file MSG:

NOTA: il frammento di codice fornito è adatto a tutte le famiglie di formati che supportano gli allegati: email, file dati Outlook, archivi e documenti PDF.

{{< tabs \"example1\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.viewer import Viewer

def extract_and_save_attachments():
    # Carica documento con allegati
    with Viewer("with_attachments.msg") as viewer:
        attachments = viewer.get_attachments()

        print("\nAttachments:")
        for attachment in attachments:
            print(attachment)
            # Salva allegato su disco
            viewer.save_attachment(attachment, f"./attachments/{attachment.file_name}")

    print(f"\nAttachments retrieved successfully.")

if __name__ == "__main__":
    extract_and_save_attachments()
```
{{< /tab >}}
{{< tab \"with_attachments.msg\" >}}

`with_attachments.msg` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/processing-attachments/with_attachments.msg) per scaricarlo.

{{< /tab >}}
{{< tab \"extract-and-save-attachments-outputs.zip\" >}}
```text
attachments/attachment-image.png (26 KB)
attachments/attachment-word.doc (220 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/processing-attachments/how-to-extract-and-save-attachments/extract_and_save_attachments/extract-and-save-attachments-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
