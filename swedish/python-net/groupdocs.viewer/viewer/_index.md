---
title: "Viewer‑klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Representerar huvudklassen som styr dokumentrenderingsprocessen."
type: docs
url: /sv/python-net/groupdocs.viewer/viewer/
is_root: false
weight: 100
---


## Viewer class

Representerar huvudklassen som styr dokumentrenderingsprocessen.

Viewer-typen exponerar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream) | Initierar en ny instans av [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) klass. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options) | Initierar en ny instans av [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-settings) | Initierar en ny [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instans. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options-settings) | Initierar en ny Viewer-instans. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream) | Initierar en ny instans av [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) klassen. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-leave_open) | Initierar en ny Viewer-instans. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options) | Initierar en ny instans av [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-leave_open) | Initierar en ny Viewer-instans. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings) | Initierar en ny Viewer-instans. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings-leave_open) | Initierar en ny Viewer-instans. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings) | Initierar en ny Viewer-instans. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings-leave_open) | Initierar en ny instans av [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path) | Initierar en ny instans av [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) klass. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-settings) | Initierar en ny instans av [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) klass. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options) | Initierar en ny instans av [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options-settings) | Initierar en ny Viewer-instans. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [dispose](/viewer/python-net/groupdocs.viewer/viewer/dispose/) | Frigör filström och hanterade interna resurser. |
| [get_all_fonts](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) | Returnerar alla teckensnitt som används i det inlästa dokumentet, inklusive inbäddade teckensnitt och systemteckensnitt installerade på OS. |
| [get_attachments](/viewer/python-net/groupdocs.viewer/viewer/get_attachments/) | Returnerar bilagor som finns i dokumentet. |
| [get_file_info](/viewer/python-net/groupdocs.viewer/viewer/get_file_info/) | Returnerar information om filen, såsom filtyp och en flagga som indikerar om filen är krypterad. |
| [get_view_info](/viewer/python-net/groupdocs.viewer/viewer/get_view_info/#options) | Returnerar vy- och dokumentspecifik information. |
| [get_view_info_view_info_options](/viewer/python-net/groupdocs.viewer/viewer/get_view_info_view_info_options/) |  |
| [save_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment/#attachment-destination) | Sparar bilagefil till `destination`-ström. |
| [save_attachment_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_attachment/) |  |
| [save_attachment_stream](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_stream/) |  |
| [save_attachment_streams](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_streams/) |  |
| [search](/viewer/python-net/groupdocs.viewer/viewer/search/#options) | Utför en textsökning och markerar den hittade texten i det inlästa dokumentet enligt de angivna alternativen. |
| [search_search_highlight_options](/viewer/python-net/groupdocs.viewer/viewer/search_search_highlight_options/) |  |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options) | Skapar vy av alla dokumentsidor. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-page_numbers) | Skapar vy av specifika dokumentsidor. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-cancellation_token-page_numbers) | Skapar vy av specifika dokumentsidor. |
| [view_view_options](/viewer/python-net/groupdocs.viewer/viewer/view_view_options/) |  |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, PngViewOptions

# Rendera DOCX till HTML
with Viewer("./sample.docx") as viewer:
    html_opts = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(html_opts)

# Rendera PDF till PNG
with Viewer("document.pdf") as viewer:
    png_opts = PngViewOptions("page_{0}.png")
    viewer.view(png_opts)
```

### Guides
Uppgiftsguider som använder `Viewer`:

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)
* [Get Document Information](/viewer/python-net/guides/get-document-info/)
* [Load document from local disk](/viewer/python-net/guides/load-document-from-local-disk/)
* [Load document from stream](/viewer/python-net/guides/load-document-from-stream/)
* [Load document from URL](/viewer/python-net/guides/load-document-from-url/)
* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)
* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)
* [Reorder pages](/viewer/python-net/guides/reorder-pages/)
* [Save attachments](/viewer/python-net/guides/how-to-extract-and-save-attachments/)

### Se även
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
