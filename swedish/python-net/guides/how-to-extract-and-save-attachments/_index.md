---
title: "Spara bilagor"
linkTitle: "Save attachments"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Hämta och spara bilagor från e-post, Outlook-filer, arkiv och PDF-filer."
type: docs
url: /sv/python-net/guides/how-to-extract-and-save-attachments/
is_root: false
weight: 110
---


För att hämta och spara bilagor, följ dessa steg:

1. Instansiera [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/)‑objektet. Ange en fil som innehåller bilagor.
2. Anropa metoden [get_attachments](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods). Den returnerar bilagssamlingen.
3. Iterera genom samlingen. För att spara en bilaga, anropa metoden [save_attachment](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods).

Följande kodsnutt visar hur du hämtar och sparar alla bilagor från MSG-filen:

OBS: den medföljande kodsnutten fungerar för alla formatfamiljer som stöder bilagor: e-post, Outlook‑datafiler, arkiv och PDF‑dokument.

{{< tabs \"example1\">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer

def extract_and_save_attachments():
    # Läs in dokument med bilagor
    with Viewer("with_attachments.msg") as viewer:
        attachments = viewer.get_attachments()

        print("\nAttachments:")
        for attachment in attachments:
            print(attachment)
            # Spara bilaga till disk
            viewer.save_attachment(attachment, f"./attachments/{attachment.file_name}")

    print(f"\nAttachments retrieved successfully.")

if __name__ == "__main__":
    extract_and_save_attachments()
```
{{< /tab >}}
{{< tab "with_attachments.msg" >}}

`with_attachments.msg` är exempel filen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/processing-attachments/with_attachments.msg) för att ladda ner den.

{{< /tab >}}
{{< tab "extract-and-save-attachments-outputs.zip" >}}
```text
attachments/attachment-image.png (26 KB)
attachments/attachment-word.doc (220 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/processing-attachments/how-to-extract-and-save-attachments/extract_and_save_attachments/extract-and-save-attachments-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
