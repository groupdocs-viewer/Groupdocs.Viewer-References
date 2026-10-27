---
title: "Ottieni informazioni sul documento"
linkTitle: "Get Document Info"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Ispeziona un documento — tipo di file, numero di pagine, allegati e metadati specifici del formato — con i metodi Viewer.get_view_info e Viewer.get_file_info in GroupDocs.Viewer per Python tramite .NET."
type: docs
url: /it/python-net/guides/get-document-info/
is_root: false
weight: 40
---


`GroupDocs.Viewer` espone due metodi di ispezione sulla classe [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/):

- `get_file_info()` — returns a [`FileInfo`](/viewer/python-net/groupdocs.viewer.results/fileinfo/) result with the detected file type and name. Cheap; no rendering required.
- `get_view_info(options)` — returns a [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) result that includes the page count, per-page dimensions, and format-specific metadata. Takes a [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) created with one of the `for_html_view()` / `for_png_view()` / `for_jpg_view()` / `for_pdf_view()` factory methods.

Per diverse famiglie di formati, `get_view_info` restituisce una **sottoclasse specifica del formato** di [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) che espone proprietà aggiuntive:

| Famiglia di formato | Tipo di risultato | Proprietà aggiuntive |
|---|---|---|
| PDF | [`PdfViewInfo`](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/) | `printing_allowed` |
| Archive (ZIP / RAR / 7Z) | [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/) | `folders` |
| CAD (DWG / DXF / DGN) | [`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/) | `layers`, `layouts` |
| Outlook (PST / OST) | [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/) | `folders` |
| Project (MPP / MPT) | [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/) | `start_date`, `end_date` |

Esegui il cast del risultato [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) alla sottoclasse appropriata per accedere alle proprietà aggiuntive.

## Example 1: Get File Type and Pages Count

Il seguente frammento di codice mostra come ottenere il tipo di file e il conteggio delle pagine per qualsiasi documento supportato:

{{< tabs \"example1\">}}
{{< tab "get_file_type_and_pages_count.py" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

def get_file_type_and_pages_count():
    # Carica documento PDF
    with Viewer("sample.pdf") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())

        print("Document type:", info.file_type)
        print("Pages count:", len(info.pages))

if __name__ == "__main__":
    get_file_type_and_pages_count()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/sample.pdf) per scaricarlo.

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

Per i documenti PDF, il [`PdfViewInfo`](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/) restituito riporta anche se la stampa è consentita:

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

`sample.pdf` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/sample.pdf) per scaricarlo.

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

Per gli archivi (ZIP / RAR / 7Z), `ArchiveViewInfo.folders` restituisce l'elenco delle cartelle di livello superiore:

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

`documents.zip` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/documents.zip) per scaricarlo.

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

Per i disegni CAD (DWG / DXF / DGN), [`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/) espone i `layers` e i `layouts` del disegno:

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

`sample.dwg` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/sample.dwg) per scaricarlo.

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

Per i file dati di Outlook (PST / OST), `OutlookViewInfo.folders` espone l'elenco delle cartelle della casella di posta:

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

`sample.pst` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/sample.pst) per scaricarlo.

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

Per i file Microsoft Project (MPP / MPT), [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/) espone le `start_date` e `end_date` del progetto:

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

`sample.mpp` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/get-document-info/sample.mpp) per scaricarlo.

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

## Vedi anche

- [Rendering archives]() — render the contents of a ZIP, RAR, or 7Z archive.
- [Rendering CAD drawings]() — apply CAD-specific options (layouts, tiles, background color).
- [Rendering Outlook data files]() — filter messages by folder.
- [Rendering PDF documents]() — PDF-specific options.
- [Rendering Microsoft Project files]() — date range and time-unit options.
