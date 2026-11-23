---
title: "Viewer-klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Stelt de hoofdklasse voor die het documentrenderingsproces beheert."
type: docs
url: /nl/python-net/groupdocs.viewer/viewer/
is_root: false
weight: 100
---


## Viewer class

Stelt de hoofdklasse voor die het documentrenderingsproces beheert.

Het Viewer-type maakt de volgende leden beschikbaar:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream) | Initialiseert een nieuwe instantie van de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)-klasse. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options) | Initialiseert een nieuwe instantie van [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-settings) | Initialiseert een nieuwe [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)-instantie. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options-settings) | Initialiseert een nieuwe Viewer-instantie. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream) | Initialiseert een nieuwe instantie van de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)-klasse. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-leave_open) | Initialiseert een nieuwe Viewer-instantie. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options) | Initialiseert een nieuwe instantie van [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-leave_open) | Initialiseert een nieuwe Viewer-instantie. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings) | Initialiseert een nieuwe Viewer-instantie. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings-leave_open) | Initialiseert een nieuwe Viewer-instantie. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings) | Initialiseert een nieuwe Viewer-instantie. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings-leave_open) | Initialiseert een nieuwe instantie van [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path) | Initialiseert een nieuwe instantie van de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)-klasse. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-settings) | Initialiseert een nieuwe instantie van [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)-klasse. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options) | Initialiseert een nieuwe instantie van [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options-settings) | Initialiseert een nieuwe Viewer-instantie. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [dispose](/viewer/python-net/groupdocs.viewer/viewer/dispose/) | Vrijgeeft bestandsstroom en beheerde interne bronnen. |
| [get_all_fonts](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) | Retourneert alle lettertypen die in het geladen document worden gebruikt, inclusief ingesloten lettertypen en systeemlettertypen die op het besturingssysteem zijn geïnstalleerd. |
| [get_attachments](/viewer/python-net/groupdocs.viewer/viewer/get_attachments/) | Retourneert bijlagen die in het document zijn opgenomen. |
| [get_file_info](/viewer/python-net/groupdocs.viewer/viewer/get_file_info/) | Retourneert informatie over het bestand, zoals het bestandstype en een vlag die aangeeft of het bestand versleuteld is. |
| [get_view_info](/viewer/python-net/groupdocs.viewer/viewer/get_view_info/#options) | Retourneert weergave- en documentspecifieke informatie. |
| [get_view_info_view_info_options](/viewer/python-net/groupdocs.viewer/viewer/get_view_info_view_info_options/) |  |
| [save_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment/#attachment-destination) | Slaat bijlagebestand op naar `destination`-stream. |
| [save_attachment_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_attachment/) |  |
| [save_attachment_stream](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_stream/) |  |
| [save_attachment_streams](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_streams/) |  |
| [search](/viewer/python-net/groupdocs.viewer/viewer/search/#options) | Voert een tekstzoekopdracht uit en markeert de gevonden tekst in het geladen document volgens de opgegeven opties. |
| [search_search_highlight_options](/viewer/python-net/groupdocs.viewer/viewer/search_search_highlight_options/) |  |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options) | Maakt een weergave van alle documentpagina's. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-page_numbers) | Maakt een weergave van specifieke documentpagina's. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-cancellation_token-page_numbers) | Maakt een weergave van specifieke documentpagina's. |
| [view_view_options](/viewer/python-net/groupdocs.viewer/viewer/view_view_options/) |  |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, PngViewOptions

# Render DOCX naar HTML
with Viewer("./sample.docx") as viewer:
    html_opts = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(html_opts)

# Render PDF naar PNG
with Viewer("document.pdf") as viewer:
    png_opts = PngViewOptions("page_{0}.png")
    viewer.view(png_opts)
```

### Guides
Taakgidsen die `Viewer` gebruiken:

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)
* [Get Document Information](/viewer/python-net/guides/get-document-info/)
* [Load document from local disk](/viewer/python-net/guides/load-document-from-local-disk/)
* [Load document from stream](/viewer/python-net/guides/load-document-from-stream/)
* [Load document from URL](/viewer/python-net/guides/load-document-from-url/)
* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)
* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)
* [Reorder pages](/viewer/python-net/guides/reorder-pages/)
* [Save attachments](/viewer/python-net/guides/how-to-extract-and-save-attachments/)

### Zie ook
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
