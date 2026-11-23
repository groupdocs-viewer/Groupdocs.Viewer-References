---
title: "ドキュメント情報を取得する"
linkTitle: "Get Document Info"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "Viewer.get_view_info と Viewer.get_file_info メソッドを使用して、.NET 経由の Python 用 GroupDocs.Viewer でドキュメントを検査します — ファイルタイプ、ページ数、添付ファイル、フォーマット固有のメタデータ —。"
type: docs
url: /ja/python-net/guides/get-document-info/
is_root: false
weight: 40
---


`GroupDocs.Viewer` は [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) クラスに対して 2 つの検査メソッドを公開します：

- `get_file_info()` — returns a [`FileInfo`](/viewer/python-net/groupdocs.viewer.results/fileinfo/) result with the detected file type and name. Cheap; no rendering required.
- `get_view_info(options)` — returns a [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) result that includes the page count, per-page dimensions, and format-specific metadata. Takes a [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) created with one of the `for_html_view()` / `for_png_view()` / `for_jpg_view()` / `for_pdf_view()` factory methods.

いくつかのフォーマットファミリーについて、`get_view_info` は追加プロパティを公開する [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) の **format-specific subclass** を返します：

| フォーマットファミリー | 結果タイプ | 追加プロパティ |
|---|---|---|
| PDF | [`PdfViewInfo`](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/) | `printing_allowed` |
| Archive (ZIP / RAR / 7Z) | [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/) | `folders` |
| CAD (DWG / DXF / DGN) | [`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/) | `layers`, `layouts` |
| Outlook (PST / OST) | [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/) | `folders` |
| Project (MPP / MPT) | [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/) | `start_date`, `end_date` |

[`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) の結果を適切なサブクラスにキャストして、追加プロパティにアクセスします。

## Example 1: Get File Type and Pages Count

次のコードスニペットは、サポートされている任意のドキュメントのファイルタイプとページ数を取得する方法を示しています。

{{< tabs "example1">}}
{{< tab \"get_file_type_and_pages_count.py\" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

def get_file_type_and_pages_count():
    # PDF ドキュメントを読み込む
    with Viewer("sample.pdf") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())

        print("Document type:", info.file_type)
        print("Pages count:", len(info.pages))

if __name__ == "__main__":
    get_file_type_and_pages_count()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` はこの例で使用されているサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/sample.pdf) をクリックしてください。

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

PDF ドキュメントの場合、返される [`PdfViewInfo`](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/) は印刷が許可されているかどうかも報告します。

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

`sample.pdf` はこの例で使用されているサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/sample.pdf) をクリックしてください。

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

アーカイブ (ZIP / RAR / 7Z) の場合、`ArchiveViewInfo.folders` はトップレベルのフォルダーリストを返します。

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

`documents.zip` はこの例で使用されているサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/documents.zip) をクリックしてください。

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

CAD 図面 (DWG / DXF / DGN) の場合、[`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/) は図面の `layers` と `layouts` を提供します。

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

`sample.dwg` はこの例で使用されているサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/sample.dwg) をクリックしてください。

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

Outlook データ ファイル (PST / OST) の場合、`OutlookViewInfo.folders` はメールボックス フォルダー リストを公開します:

{{< tabs \"example5\">}}
{{< tab \"get_outlook_info.py\" >}}
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
{{< tab \"sample.pst\" >}}

`sample.pst` はこの例で使用されているサンプル ファイルです。ダウンロードするには [こちら](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/sample.pst) をクリックしてください。

{{< /tab >}}
{{< tab \"get-outlook-info.txt\" >}}
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

Microsoft Project ファイル (MPP / MPT) の場合、[`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/) はプロジェクトの `start_date` と `end_date` を公開します:

{{< tabs \"example6\">}}
{{< tab \"get_project_info.py\" >}}
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
{{< tab \"sample.mpp\" >}}

`sample.mpp` はこの例で使用されているサンプル ファイルです。ダウンロードするには [こちら](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/sample.mpp) をクリックしてください。

{{< /tab >}}
{{< tab \"get-project-info.txt\" >}}
```text
File type: Microsoft Project File (.mpp)
Pages count: 1
Start date: 2008-06-01 00:00:00+00:00
End date: 2008-09-03 00:00:00+00:00
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/get-document-info/get_project_info/get-project-info.txt)
{{< /tab >}}
{{< /tabs >}}

## 参照

- [Rendering archives]() — render the contents of a ZIP, RAR, or 7Z archive.
- [Rendering CAD drawings]() — apply CAD-specific options (layouts, tiles, background color).
- [Rendering Outlook data files]() — filter messages by folder.
- [Rendering PDF documents]() — PDF-specific options.
- [Rendering Microsoft Project files]() — date range and time-unit options.
