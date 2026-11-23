---
title: "PDF 문서 보호"
linkTitle: "Protect PDF document"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "GroupDocs.Viewer를 사용하여 문서를 렌더링할 때 비밀번호와 권한으로 PDF 출력을 보호합니다."
type: docs
url: /ko/python-net/guides/protect-pdf-document/
is_root: false
weight: 90
---


다음 매개변수를 설정하여 PDF 문서를 보호할 수 있습니다:

* permissions
* password to open document
* password to change permissions

PDF 문서를 보호하려면 다음 단계를 따르세요:

1. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) 클래스의 인스턴스를 생성합니다. 생성자 매개변수로 원본 문서 경로를 지정합니다.
2. [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security) 객체를 인스턴스화합니다.
3. 문서를 열기 위한 비밀번호를 지정하려면 [DocumentOpenPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties) 속성을 설정합니다.
4. 제한을 변경하기 위한 비밀번호를 지정하려면 [PermissionsPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties) 속성을 설정합니다.
5. 문서 권한을 지정하려면 [Permissions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/permissions) 속성을 설정합니다.
6. [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) 객체를 인스턴스화합니다. 렌더링된 문서의 저장 경로 형식을 지정합니다.
7. [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) 객체의 [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/#properties) 속성을 2-5 단계에서 만든 객체로 초기화합니다.
8. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) 객체의 [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) 메서드를 호출합니다. 매개변수로 [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) 객체를 지정합니다.

다음 코드 스니펫은 출력 PDF 문서를 보호하는 방법을 보여줍니다:

{{< tabs \"example1\">}}
{{< tab \"Python\">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

def protect_pdf_document():
    # 문서 로드
    with Viewer("sample.docx") as viewer:
        # 보안 설정을 지정합니다.
        security = Security()
        security.document_open_password = "o123"
        security.permissions_password = "p123"
        security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

        # PDF 파일을 생성합니다.
        pdf_options = PdfViewOptions("protect_pdf_document/protected_document.pdf")

        # 보안 설정을 적용합니다
        pdf_options.security = security
        viewer.view(pdf_options)

if __name__ == "__main__":
    protect_pdf_document()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [here](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/sample.docx)를 클릭하세요.

{{< /tab >}}
{{< tab \"protected_document.pdf\" >}}
```text
Binary file (PDF, 238 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/protect_pdf_document/protected_document.pdf)
{{< /tab >}}
{{< /tabs >}}
