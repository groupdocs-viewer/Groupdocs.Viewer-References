---
title: Save attachments
linkTitle: "Save attachments"
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Retrieve and save attachments from emails, Outlook files, archives, and PDFs."
type: docs
url: /python-net/guides/how-to-extract-and-save-attachments/
is_root: false
weight: 110
---


To get and save attachments, follow these steps:

1. Instantiate the [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/) object. Specify a file that contains attachments.
2. Call the [get_attachments](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) method. It returns the attachment collection.
3. Iterate through the collection. To save an attachment, call the [save_attachment](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) method.

The following code snippet shows how to get and save all attachments from the MSG file:

NOTE: provided code snippet suits all format families that support attachments: emails, Outlook data files, archives, and PDF documents.

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer

def extract_and_save_attachments():
    # Load document with attachments
    with Viewer("with_attachments.msg") as viewer:
        attachments = viewer.get_attachments()

        print("\nAttachments:")
        for attachment in attachments:
            print(attachment)
            # Save attachment to disk
            viewer.save_attachment(attachment, f"./attachments/{attachment.file_name}")

    print(f"\nAttachments retrieved successfully.")

if __name__ == "__main__":
    extract_and_save_attachments()
```
{{< /tab >}}
{{< tab "with_attachments.msg" >}}

`with_attachments.msg` is the sample file used in this example. Click [here](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/processing-attachments/with_attachments.msg) to download it.

{{< /tab >}}
{{< tab "extract-and-save-attachments-outputs.zip" >}}  
```text
attachments/attachment-image.png (26 KB)
attachments/attachment-word.doc (220 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/processing-attachments/how-to-extract-and-save-attachments/extract_and_save_attachments/extract-and-save-attachments-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
