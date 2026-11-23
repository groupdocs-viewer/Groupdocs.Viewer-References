---
title: "Anhänge speichern"
linkTitle: "Save attachments"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Abrufen und Speichern von Anhängen aus E-Mails, Outlook-Dateien, Archiven und PDFs."
type: docs
url: /de/python-net/guides/how-to-extract-and-save-attachments/
is_root: false
weight: 110
---


Um Anhänge zu erhalten und zu speichern, folgen Sie diesen Schritten:

1. Instanziieren Sie das [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/)‑Objekt. Geben Sie eine Datei an, die Anhänge enthält.
2. Rufen Sie die Methode [get_attachments](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) auf. Sie gibt die Anhangssammlung zurück.
3. Durchlaufen Sie die Sammlung. Um einen Anhang zu speichern, rufen Sie die Methode [save_attachment](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) auf.

Das folgende Code‑Snippet zeigt, wie man alle Anhänge aus der MSG‑Datei abruft und speichert:

HINWEIS: Das bereitgestellte Code‑Snippet ist für alle Formatfamilien geeignet, die Anhänge unterstützen: E-Mails, Outlook‑Datendateien, Archive und PDF‑Dokumente.

{{< tabs \"example1\">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer

def extract_and_save_attachments():
    # Dokument mit Anhängen laden
    with Viewer("with_attachments.msg") as viewer:
        attachments = viewer.get_attachments()

        print("\nAttachments:")
        for attachment in attachments:
            print(attachment)
            # Anhang auf Festplatte speichern
            viewer.save_attachment(attachment, f"./attachments/{attachment.file_name}")

    print(f"\nAttachments retrieved successfully.")

if __name__ == "__main__":
    extract_and_save_attachments()
```
{{< /tab >}}
{{< tab "with_attachments.msg" >}}

`with_attachments.msg` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/processing-attachments/with_attachments.msg), um sie herunterzuladen.

{{< /tab >}}
{{< tab "extract-and-save-attachments-outputs.zip" >}}
```text
attachments/attachment-image.png (26 KB)
attachments/attachment-word.doc (220 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/processing-attachments/how-to-extract-and-save-attachments/extract_and_save_attachments/extract-and-save-attachments-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
