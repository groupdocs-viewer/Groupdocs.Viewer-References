---
title: "Сохранить вложения"
linkTitle: "Save attachments"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Получайте и сохраняйте вложения из электронных писем, файлов Outlook, архивов и PDF."
type: docs
url: /ru/python-net/guides/how-to-extract-and-save-attachments/
is_root: false
weight: 110
---


Чтобы получить и сохранить вложения, выполните следующие действия:

1. Создайте объект [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/) . Укажите файл, содержащий вложения.
2. Вызовите метод [get_attachments](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) . Он возвращает коллекцию вложений.
3. Пройдитесь по коллекции. Чтобы сохранить вложение, вызовите метод [save_attachment](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) .

Следующий фрагмент кода показывает, как получить и сохранить все вложения из файла MSG:

ПРИМЕЧАНИЕ: предоставленный фрагмент кода подходит для всех семейств форматов, поддерживающих вложения: электронные письма, файлы данных Outlook, архивы и PDF‑документы.

{{< tabs \"example1\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.viewer import Viewer

def extract_and_save_attachments():
    # Загрузить документ с вложениями
    with Viewer("with_attachments.msg") as viewer:
        attachments = viewer.get_attachments()

        print("\nAttachments:")
        for attachment in attachments:
            print(attachment)
            # Сохранить вложение на диск
            viewer.save_attachment(attachment, f"./attachments/{attachment.file_name}")

    print(f"\nAttachments retrieved successfully.")

if __name__ == "__main__":
    extract_and_save_attachments()
```
{{< /tab >}}
{{< tab \"with_attachments.msg\" >}}

`with_attachments.msg` — пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/processing-attachments/with_attachments.msg) чтобы скачать его.

{{< /tab >}}
{{< tab \"extract-and-save-attachments-outputs.zip\" >}}
```text
attachments/attachment-image.png (26 KB)
attachments/attachment-word.doc (220 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/processing-attachments/how-to-extract-and-save-attachments/extract_and_save_attachments/extract-and-save-attachments-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
