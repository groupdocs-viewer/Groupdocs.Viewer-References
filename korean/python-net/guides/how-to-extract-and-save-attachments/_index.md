---
title: "첨부 파일 저장"
linkTitle: "Save attachments"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "이메일, Outlook 파일, 아카이브 및 PDF에서 첨부 파일을 검색하고 저장합니다."
type: docs
url: /ko/python-net/guides/how-to-extract-and-save-attachments/
is_root: false
weight: 110
---


첨부 파일을 가져오고 저장하려면 다음 단계를 따르세요:

1. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/) 객체를 인스턴스화합니다. 첨부 파일이 포함된 파일을 지정합니다.
2. [get_attachments](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) 메서드를 호출합니다. 이 메서드는 첨부 파일 컬렉션을 반환합니다.
3. 컬렉션을 반복합니다. 첨부 파일을 저장하려면 [save_attachment](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) 메서드를 호출합니다.

다음 코드 스니펫은 MSG 파일에서 모든 첨부 파일을 가져오고 저장하는 방법을 보여줍니다:

참고: 제공된 코드 스니펫은 첨부 파일을 지원하는 모든 형식군(이메일, Outlook 데이터 파일, 아카이브 및 PDF 문서)에 적용됩니다.

{{< tabs \"example1\">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer

def extract_and_save_attachments():
    # 첨부 파일이 있는 문서 로드
    with Viewer("with_attachments.msg") as viewer:
        attachments = viewer.get_attachments()

        print("\nAttachments:")
        for attachment in attachments:
            print(attachment)
            # 첨부 파일을 디스크에 저장
            viewer.save_attachment(attachment, f"./attachments/{attachment.file_name}")

    print(f"\nAttachments retrieved successfully.")

if __name__ == "__main__":
    extract_and_save_attachments()
```
{{< /tab >}}
{{< tab "with_attachments.msg" >}}

`with_attachments.msg`는 이 예제에서 사용되는 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/processing-attachments/with_attachments.msg)를 클릭하십시오.

{{< /tab >}}
{{< tab "extract-and-save-attachments-outputs.zip" >}}
```text
attachments/attachment-image.png (26 KB)
attachments/attachment-word.doc (220 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/processing-attachments/how-to-extract-and-save-attachments/extract_and_save_attachments/extract-and-save-attachments-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
