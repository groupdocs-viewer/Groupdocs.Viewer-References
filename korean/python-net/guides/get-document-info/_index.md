---
title: "문서 정보 가져오기"
linkTitle: "Get Document Info"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "Viewer.get_view_info 및 Viewer.get_file_info 메서드를 사용하여 .NET을 통해 Python용 GroupDocs.Viewer에서 문서를 검사합니다 — 파일 유형, 페이지 수, 첨부 파일 및 형식별 메타데이터 —."
type: docs
url: /ko/python-net/guides/get-document-info/
is_root: false
weight: 40
---


`GroupDocs.Viewer`는 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 클래스에 두 개의 검사 메서드를 제공합니다:

- `get_file_info()` — returns a [`FileInfo`](/viewer/python-net/groupdocs.viewer.results/fileinfo/) result with the detected file type and name. Cheap; no rendering required.
- `get_view_info(options)` — returns a [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) result that includes the page count, per-page dimensions, and format-specific metadata. Takes a [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) created with one of the `for_html_view()` / `for_png_view()` / `for_jpg_view()` / `for_pdf_view()` factory methods.

여러 형식군에 대해, `get_view_info`는 추가 속성을 노출하는 [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)의 **format-specific subclass**를 반환합니다:

| 형식군 | 결과 유형 | 추가 속성 |
|---|---|---|
| PDF | [`PdfViewInfo`](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/) | `printing_allowed` |
| Archive (ZIP / RAR / 7Z) | [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/) | `folders` |
| CAD (DWG / DXF / DGN) | [`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/) | `layers`, `layouts` |
| Outlook (PST / OST) | [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/) | `folders` |
| Project (MPP / MPT) | [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/) | `start_date`, `end_date` |

[`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) 결과를 적절한 하위 클래스로 캐스팅하여 추가 속성에 접근합니다.

## Example 1: Get File Type and Pages Count

다음 코드 스니펫은 지원되는 모든 문서에 대해 파일 형식과 페이지 수를 가져오는 방법을 보여줍니다:

{{< tabs \"example1\">}}
{{< tab \"get_file_type_and_pages_count.py\" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

def get_file_type_and_pages_count():
    # PDF 문서를 로드합니다
    with Viewer("sample.pdf") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())

        print("Document type:", info.file_type)
        print("Pages count:", len(info.pages))

if __name__ == "__main__":
    get_file_type_and_pages_count()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [여기](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/sample.pdf)를 클릭하십시오.

{{< /tab >}}
{{< tab \"get-file-type-and-pages-count.txt\" >}}
```text
Document type: Portable Document Format File (.pdf)
Pages count: 2
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/get-document-info/get_file_type_and_pages_count/get-file-type-and-pages-count.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Get PDF-Specific Information

PDF 문서의 경우, 반환된 [`PdfViewInfo`](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/)는 인쇄가 허용되는지 여부도 보고합니다:

{{< tabs \"example2\">}}
{{< tab \"get_pdf_info.py\" >}}
```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import PdfViewInfo

def get_pdf_info():
    with Viewer("sample.pdf") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        pdf_info = cast(PdfViewInfo, info)

        print("File type:", pdf_info.file_type)
        print("Pages count:", len(pdf_info.pages))
        print("Printing allowed:", pdf_info.printing_allowed)

if __name__ == "__main__":
    get_pdf_info()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [여기](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/sample.pdf)를 클릭하십시오.

{{< /tab >}}
{{< tab \"get-pdf-info.txt\" >}}
```text
File type: Portable Document Format File (.pdf)
Pages count: 2
Printing allowed: True
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/get-document-info/get_pdf_info/get-pdf-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Get Archive Folder Structure

아카이브(ZIP / RAR / 7Z)의 경우, `ArchiveViewInfo.folders`는 최상위 폴더 목록을 반환합니다:

{{< tabs \"example3\">}}
{{< tab \"get_archive_info.py\" >}}
```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import ArchiveViewInfo

def get_archive_info():
    with Viewer("documents.zip") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        archive_info = cast(ArchiveViewInfo, info)

        print("File type:", archive_info.file_type)
        print("Pages count:", len(archive_info.pages))
        print("Folders:")
        for folder in archive_info.folders:
            print(f"  {folder}")

if __name__ == "__main__":
    get_archive_info()
```
{{< /tab >}}
{{< tab \"documents.zip\" >}}

`documents.zip`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [여기](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/documents.zip)를 클릭하십시오.

{{< /tab >}}
{{< tab \"get-archive-info.txt\" >}}
```text
File type: Zipped File (.zip)
Pages count: 1
Folders:
  /first_folder/
  /second_folder/
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/get-document-info/get_archive_info/get-archive-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 4: Get CAD Layers and Layouts

CAD 도면(DWG / DXF / DGN)의 경우, [`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/)는 도면의 `layers`와 `layouts`를 노출합니다:

{{< tabs \"example4\">}}
{{< tab \"get_cad_info.py\" >}}
```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import CadViewInfo

def get_cad_info():
    with Viewer("sample.dwg") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        cad_info = cast(CadViewInfo, info)

        print("File type:", cad_info.file_type)
        print("Pages count:", len(cad_info.pages))
        print("Layers:")
        for layer in cad_info.layers:
            print(f"  {layer.name} (visible={layer.visible})")
        print("Layouts:")
        for layout in cad_info.layouts:
            print(f"  {layout.name} ({layout.width}x{layout.height})")

if __name__ == "__main__":
    get_cad_info()
```
{{< /tab >}}
{{< tab \"sample.dwg\" >}}

`sample.dwg`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [여기](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/sample.dwg)를 클릭하십시오.

{{< /tab >}}
{{< tab \"get-cad-info.txt\" >}}
```text
File type: AutoCAD Drawing Database File (.dwg)
Pages count: 1
Layers:
  0 (visible=True)
  CIRCLE (visible=True)
  TRIANGLE (visible=True)
  QUADRANT (visible=True)
Layouts:
  Model (26x23)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/get-document-info/get_cad_info/get-cad-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 5: Get Outlook Data File Folders

Outlook 데이터 파일(PST / OST)의 경우, `OutlookViewInfo.folders`가 메일함 폴더 목록을 노출합니다:

{{< tabs "example5">}}
{{< tab "get_outlook_info.py" >}}
```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import OutlookViewInfo

def get_outlook_info():
    with Viewer("sample.pst") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        outlook_info = cast(OutlookViewInfo, info)

        print("File type:", outlook_info.file_type)
        print("Pages count:", len(outlook_info.pages))
        print("Folders:")
        for folder in outlook_info.folders:
            print(f"  {folder}")

if __name__ == "__main__":
    get_outlook_info()
```
{{< /tab >}}
{{< tab "sample.pst" >}}

`sample.pst`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [여기](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/sample.pst)를 클릭하십시오.

{{< /tab >}}
{{< tab "get-outlook-info.txt" >}}
```text
File type: Outlook Personal Information Store File (.pst)
Pages count: 1
Folders:
  Inbox
  Deleted Items
  Outbox
  Sent Items
  Calendar
  Contacts
  Drafts
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/get-document-info/get_outlook_info/get-outlook-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 6: Get Microsoft Project Dates

Microsoft Project 파일(MPP / MPT)의 경우, [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/)가 프로젝트의 `start_date`와 `end_date`를 노출합니다:

{{< tabs "example6">}}
{{< tab "get_project_info.py" >}}
```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import ProjectManagementViewInfo

def get_project_info():
    with Viewer("sample.mpp") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        project_info = cast(ProjectManagementViewInfo, info)

        print("File type:", project_info.file_type)
        print("Pages count:", len(project_info.pages))
        print("Start date:", project_info.start_date)
        print("End date:", project_info.end_date)

if __name__ == "__main__":
    get_project_info()
```
{{< /tab >}}
{{< tab "sample.mpp" >}}

`sample.mpp`는 이 예제에서 사용된 샘플 파일입니다. 다운로드하려면 [여기](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/sample.mpp)를 클릭하십시오.

{{< /tab >}}
{{< tab "get-project-info.txt" >}}
```text
File type: Microsoft Project File (.mpp)
Pages count: 1
Start date: 2008-06-01 00:00:00+00:00
End date: 2008-09-03 00:00:00+00:00
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/get-document-info/get_project_info/get-project-info.txt)
{{< /tab >}}
{{< /tabs >}}

## 또한 보기

- [Rendering archives]() — render the contents of a ZIP, RAR, or 7Z archive.
- [Rendering CAD drawings]() — apply CAD-specific options (layouts, tiles, background color).
- [Rendering Outlook data files]() — filter messages by folder.
- [Rendering PDF documents]() — PDF-specific options.
- [Rendering Microsoft Project files]() — date range and time-unit options.
