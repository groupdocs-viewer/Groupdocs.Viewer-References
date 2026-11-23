---
title: "Ekleri kaydedin"
linkTitle: "Save attachments"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "E-postalardan, Outlook dosyalarından, arşivlerden ve PDF'lerden ekleri alıp kaydedin."
type: docs
url: /tr/python-net/guides/how-to-extract-and-save-attachments/
is_root: false
weight: 110
---


Ekleri almak ve kaydetmek için şu adımları izleyin:

1. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/) nesnesini oluşturun. Ekleri içeren bir dosya belirtin.
2. [get_attachments](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) metodunu çağırın. Bu, ek koleksiyonunu döndürür.
3. Koleksiyon üzerinde yineleme yapın. Bir eki kaydetmek için [save_attachment](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) metodunu çağırın.

Aşağıdaki kod parçacığı, MSG dosyasından tüm ekleri nasıl alıp kaydedeceğinizi gösterir:

NOT: Sağlanan kod parçacığı, ekleri destekleyen tüm format ailelerine uygundur: e-postalar, Outlook veri dosyaları, arşivler ve PDF belgeleri.

{{< tabs \"example1\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.viewer import Viewer

def extract_and_save_attachments():
    # Ekli belgeyi yükle
    with Viewer("with_attachments.msg") as viewer:
        attachments = viewer.get_attachments()

        print("\nAttachments:")
        for attachment in attachments:
            print(attachment)
            # Ek'i diske kaydet
            viewer.save_attachment(attachment, f"./attachments/{attachment.file_name}")

    print(f"\nAttachments retrieved successfully.")

if __name__ == "__main__":
    extract_and_save_attachments()
```
{{< /tab >}}
{{< tab \"with_attachments.msg\" >}}

`with_attachments.msg` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/processing-attachments/with_attachments.msg) tıklayın.

{{< /tab >}}
{{< tab \"extract-and-save-attachments-outputs.zip\" >}}
```text
attachments/attachment-image.png (26 KB)
attachments/attachment-word.doc (220 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/processing-attachments/how-to-extract-and-save-attachments/extract_and_save_attachments/extract-and-save-attachments-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
