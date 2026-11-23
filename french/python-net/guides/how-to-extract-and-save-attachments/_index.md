---
title: "Enregistrer les pièces jointes"
linkTitle: "Save attachments"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Récupérer et enregistrer les pièces jointes provenant des e‑mails, des fichiers Outlook, des archives et des PDF."
type: docs
url: /fr/python-net/guides/how-to-extract-and-save-attachments/
is_root: false
weight: 110
---


Pour récupérer et enregistrer les pièces jointes, suivez ces étapes :

1. Instanciez l’objet [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/). Spécifiez un fichier contenant des pièces jointes.
2. Appelez la méthode [get_attachments](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods). Elle renvoie la collection de pièces jointes.
3. Parcourez la collection. Pour enregistrer une pièce jointe, appelez la méthode [save_attachment](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods).

Le fragment de code suivant montre comment récupérer et enregistrer toutes les pièces jointes du fichier MSG :

NOTE : le fragment de code fourni convient à toutes les familles de formats qui prennent en charge les pièces jointes : e‑mails, fichiers de données Outlook, archives et documents PDF.

{{< tabs \"example1\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.viewer import Viewer

def extract_and_save_attachments():
    # Charger le document avec les pièces jointes
    with Viewer("with_attachments.msg") as viewer:
        attachments = viewer.get_attachments()

        print("\nAttachments:")
        for attachment in attachments:
            print(attachment)
            # Enregistrer la pièce jointe sur le disque
            viewer.save_attachment(attachment, f"./attachments/{attachment.file_name}")

    print(f"\nAttachments retrieved successfully.")

if __name__ == "__main__":
    extract_and_save_attachments()
```
{{< /tab >}}
{{< tab \"with_attachments.msg\" >}}

`with_attachments.msg` est le fichier d’exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/processing-attachments/with_attachments.msg) pour le télécharger.

{{< /tab >}}
{{< tab \"extract-and-save-attachments-outputs.zip\" >}}
```text
attachments/attachment-image.png (26 KB)
attachments/attachment-word.doc (220 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/processing-attachments/how-to-extract-and-save-attachments/extract_and_save_attachments/extract-and-save-attachments-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
