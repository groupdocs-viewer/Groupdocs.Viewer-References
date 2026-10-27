---
title: "保存附件"
linkTitle: "Save attachments"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "检索并保存来自电子邮件、Outlook 文件、存档和 PDF 的附件。"
type: docs
url: /zh/python-net/guides/how-to-extract-and-save-attachments/
is_root: false
weight: 110
---


获取并保存附件，请按照以下步骤操作：

1. 实例化 [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/) 对象。指定包含附件的文件。
2. 调用 [get_attachments](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) 方法。它返回附件集合。
3. 遍历集合。要保存附件，请调用 [save_attachment](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) 方法。

以下代码片段展示了如何从 MSG 文件获取并保存所有附件：

注意：提供的代码片段适用于所有支持附件的格式族：电子邮件、Outlook 数据文件、存档和 PDF 文档。

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer

def extract_and_save_attachments():
    # 加载带有附件的文档
    with Viewer("with_attachments.msg") as viewer:
        attachments = viewer.get_attachments()

        print("\nAttachments:")
        for attachment in attachments:
            print(attachment)
            # 将附件保存到磁盘
            viewer.save_attachment(attachment, f"./attachments/{attachment.file_name}")

    print(f"\nAttachments retrieved successfully.")

if __name__ == "__main__":
    extract_and_save_attachments()
```
{{< /tab >}}
{{< tab "with_attachments.msg" >}}

`with_attachments.msg` 是本示例中使用的示例文件。点击 [here](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/processing-attachments/with_attachments.msg) 下载。

{{< /tab >}}
{{< tab "extract-and-save-attachments-outputs.zip" >}}
```text
attachments/attachment-image.png (26 KB)
attachments/attachment-word.doc (220 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/processing-attachments/how-to-extract-and-save-attachments/extract_and_save_attachments/extract-and-save-attachments-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
