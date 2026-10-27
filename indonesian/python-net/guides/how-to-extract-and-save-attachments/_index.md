---
title: "Simpan lampiran"
linkTitle: "Save attachments"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Ambil dan simpan lampiran dari email, file Outlook, arsip, dan PDF."
type: docs
url: /id/python-net/guides/how-to-extract-and-save-attachments/
is_root: false
weight: 110
---


Untuk mengambil dan menyimpan lampiran, ikuti langkah-langkah berikut:

1. Buat instance objek [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/). Tentukan file yang berisi lampiran.
2. Panggil metode [get_attachments](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods). Metode ini mengembalikan koleksi lampiran.
3. Iterasi melalui koleksi. Untuk menyimpan sebuah lampiran, panggil metode [save_attachment](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods).

Potongan kode berikut menunjukkan cara mengambil dan menyimpan semua lampiran dari file MSG:

CATATAN: potongan kode yang disediakan cocok untuk semua keluarga format yang mendukung lampiran: email, file data Outlook, arsip, dan dokumen PDF.

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer

def extract_and_save_attachments():
    # Muat dokumen dengan lampiran
    with Viewer("with_attachments.msg") as viewer:
        attachments = viewer.get_attachments()

        print("\nAttachments:")
        for attachment in attachments:
            print(attachment)
            # Simpan lampiran ke disk
            viewer.save_attachment(attachment, f"./attachments/{attachment.file_name}")

    print(f"\nAttachments retrieved successfully.")

if __name__ == "__main__":
    extract_and_save_attachments()
```
{{< /tab >}}
{{< tab "with_attachments.msg" >}}

`with_attachments.msg` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/processing-attachments/with_attachments.msg) untuk mengunduhnya.

{{< /tab >}}
{{< tab "extract-and-save-attachments-outputs.zip" >}}
```text
attachments/attachment-image.png (26 KB)
attachments/attachment-word.doc (220 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/processing-attachments/how-to-extract-and-save-attachments/extract_and_save_attachments/extract-and-save-attachments-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
