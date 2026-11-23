---
title: "添付ファイルを保存する"
linkTitle: "Save attachments"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "メール、Outlook ファイル、アーカイブ、PDF から添付ファイルを取得して保存します。"
type: docs
url: /ja/python-net/guides/how-to-extract-and-save-attachments/
is_root: false
weight: 110
---


添付ファイルを取得して保存するには、次の手順に従ってください：

1. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/) オブジェクトをインスタンス化します。添付ファイルを含むファイルを指定します。
2. [get_attachments](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) メソッドを呼び出します。添付ファイルのコレクションが返されます。
3. コレクションを反復処理します。添付ファイルを保存するには、[save_attachment](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) メソッドを呼び出します。

以下のコードスニペットは、MSG ファイルからすべての添付ファイルを取得して保存する方法を示しています：

注: 提供されたコードスニペットは、添付ファイルをサポートするすべてのフォーマット（メール、Outlook データファイル、アーカイブ、PDF ドキュメント）に適用できます。

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer

def extract_and_save_attachments():
    # 添付ファイル付きドキュメントを読み込む
    with Viewer("with_attachments.msg") as viewer:
        attachments = viewer.get_attachments()

        print("\nAttachments:")
        for attachment in attachments:
            print(attachment)
            # 添付ファイルをディスクに保存する
            viewer.save_attachment(attachment, f"./attachments/{attachment.file_name}")

    print(f"\nAttachments retrieved successfully.")

if __name__ == "__main__":
    extract_and_save_attachments()
```
{{< /tab >}}
{{< tab "with_attachments.msg" >}}

`with_attachments.msg` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/processing-attachments/with_attachments.msg) をクリックしてください。

{{< /tab >}}
{{< tab "extract-and-save-attachments-outputs.zip" >}}
```text
attachments/attachment-image.png (26 KB)
attachments/attachment-word.doc (220 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/processing-attachments/how-to-extract-and-save-attachments/extract_and_save_attachments/extract-and-save-attachments-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
