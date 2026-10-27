---
title: "Bijlagen opslaan"
linkTitle: "Save attachments"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Ophalen en opslaan van bijlagen uit e‑mail, Outlook‑bestanden, archieven en PDF‑bestanden."
type: docs
url: /nl/python-net/guides/how-to-extract-and-save-attachments/
is_root: false
weight: 110
---


Om bijlagen op te halen en op te slaan, volg deze stappen:

1. Maak een instantie van het [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/) object. Geef een bestand op dat bijlagen bevat.
2. Roep de [get_attachments](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) methode aan. Deze retourneert de collectie van bijlagen.
3. Doorloop de collectie. Om een bijlage op te slaan, roep de [save_attachment](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) methode aan.

De volgende codefragment toont hoe alle bijlagen uit het MSG‑bestand kunnen worden opgehaald en opgeslagen:

OPMERKING: het meegeleverde codefragment is geschikt voor alle bestandsformaten die bijlagen ondersteunen: e‑mail, Outlook‑databestanden, archieven en PDF‑documenten.

{{< tabs \"example1\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.viewer import Viewer

def extract_and_save_attachments():
    # Document laden met bijlagen
    with Viewer("with_attachments.msg") as viewer:
        attachments = viewer.get_attachments()

        print("\nAttachments:")
        for attachment in attachments:
            print(attachment)
            # Bijlage opslaan op schijf
            viewer.save_attachment(attachment, f"./attachments/{attachment.file_name}")

    print(f"\nAttachments retrieved successfully.")

if __name__ == "__main__":
    extract_and_save_attachments()
```
{{< /tab >}}
{{< tab \"with_attachments.msg\" >}}

`with_attachments.msg` is het voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/processing-attachments/with_attachments.msg) om het te downloaden.

{{< /tab >}}
{{< tab \"extract-and-save-attachments-outputs.zip\" >}}
```text
attachments/attachment-image.png (26 KB)
attachments/attachment-word.doc (220 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/processing-attachments/how-to-extract-and-save-attachments/extract_and_save_attachments/extract-and-save-attachments-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
