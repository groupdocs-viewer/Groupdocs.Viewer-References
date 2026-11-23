---
title: "Belge Bilgilerini Al"
linkTitle: "Get Document Info"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Viewer.get_view_info ve Viewer.get_file_info yöntemlerini kullanarak, .NET üzerinden Python için GroupDocs.Viewer içinde bir belgeyi — dosya türü, sayfa sayısı, ekler ve format‑özel meta verileri — inceleyin."
type: docs
url: /tr/python-net/guides/get-document-info/
is_root: false
weight: 40
---


`GroupDocs.Viewer` iki inceleme yöntemini [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) sınıfında sunar:

- `get_file_info()` — returns a [`FileInfo`](/viewer/python-net/groupdocs.viewer.results/fileinfo/) result with the detected file type and name. Cheap; no rendering required.
- `get_view_info(options)` — returns a [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) result that includes the page count, per-page dimensions, and format-specific metadata. Takes a [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) created with one of the `for_html_view()` / `for_png_view()` / `for_jpg_view()` / `for_pdf_view()` factory methods.

Birçok format ailesi için, `get_view_info` ek özellikler sunan [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) **format‑özel alt sınıf** döndürür:

| Format ailesi | Sonuç türü | Ek özellikler |
|---|---|---|
| PDF | [`PdfViewInfo`](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/) | `printing_allowed` |
| Archive (ZIP / RAR / 7Z) | [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/) | `folders` |
| CAD (DWG / DXF / DGN) | [`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/) | `layers`, `layouts` |
| Outlook (PST / OST) | [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/) | `folders` |
| Project (MPP / MPT) | [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/) | `start_date`, `end_date` |

`[`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)` sonucunu, ek özelliklere erişmek için uygun alt sınıfa dönüştürün.

## Example 1: Get File Type and Pages Count

Aşağıdaki kod parçacığı, desteklenen herhangi bir belge için dosya türünü ve sayfa sayısını nasıl alacağınızı gösterir:

{{< tabs \"example1\">}}
{{< tab "get_file_type_and_pages_count.py" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

def get_file_type_and_pages_count():
    # PDF belgesini yükle
    with Viewer("sample.pdf") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())

        print("Document type:", info.file_type)
        print("Pages count:", len(info.pages))

if __name__ == "__main__":
    get_file_type_and_pages_count()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab "get-file-type-and-pages-count.txt" >}}
```text
Document type: Portable Document Format File (.pdf)
Pages count: 2
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/get-document-info/get_file_type_and_pages_count/get-file-type-and-pages-count.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Get PDF-Specific Information

PDF belgeleri için, döndürülen [`PdfViewInfo`](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/) ayrıca yazdırmanın izinli olup olmadığını rapor eder:

{{< tabs "example2">}}
{{< tab "get_pdf_info.py" >}}
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
{{< tab "sample.pdf" >}}

`sample.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/sample.pdf) tıklayın.

{{< /tab >}}
{{< tab "get-pdf-info.txt" >}}
```text
File type: Portable Document Format File (.pdf)
Pages count: 2
Printing allowed: True
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/get-document-info/get_pdf_info/get-pdf-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Get Archive Folder Structure

Arşivler (ZIP / RAR / 7Z) için, `ArchiveViewInfo.folders` üst düzey klasör listesini döndürür:

{{< tabs "example3">}}
{{< tab "get_archive_info.py" >}}
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
{{< tab "documents.zip" >}}

`documents.zip` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/documents.zip) tıklayın.

{{< /tab >}}
{{< tab "get-archive-info.txt" >}}
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

CAD çizimleri (DWG / DXF / DGN) için, [`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/) çizimin `layers` ve `layouts` öğelerini ortaya çıkarır:

{{< tabs "example4">}}
{{< tab "get_cad_info.py" >}}
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
{{< tab "sample.dwg" >}}

`sample.dwg` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/sample.dwg) tıklayın.

{{< /tab >}}
{{< tab "get-cad-info.txt" >}}
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

Outlook veri dosyaları (PST / OST) için, `OutlookViewInfo.folders` posta kutusu klasör listesini ortaya çıkarır:

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

`sample.pst` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/sample.pst) tıklayın.

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

Microsoft Project dosyaları (MPP / MPT) için, [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/) projenin `start_date` ve `end_date` değerlerini ortaya çıkarır:

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

`sample.mpp` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/sample.mpp) tıklayın.

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

## Ayrıca bakınız

- [Rendering archives]() — render the contents of a ZIP, RAR, or 7Z archive.
- [Rendering CAD drawings]() — apply CAD-specific options (layouts, tiles, background color).
- [Rendering Outlook data files]() — filter messages by folder.
- [Rendering PDF documents]() — PDF-specific options.
- [Rendering Microsoft Project files]() — date range and time-unit options.
