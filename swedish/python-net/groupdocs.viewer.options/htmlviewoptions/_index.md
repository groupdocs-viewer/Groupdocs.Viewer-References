---
title: "HtmlViewOptions-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Alternativen för att rendera dokument till HTML-format."
type: docs
url: /sv/python-net/groupdocs.viewer.options/htmlviewoptions/
is_root: false
weight: 70
---


## HtmlViewOptions class

Alternativen för att rendera dokument till HTML-format.

HtmlViewOptions-typen visar följande medlemmar:

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [for_embedded_resources](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/#create_page_stream) | Initierar en HtmlViewOptions-instans för att rendera HTML med inbäddade resurser. |
| [for_embedded_resources](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/#create_page_stream-release_page_stream) | Initierar en instans av klassen [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) för att rendera till HTML med inbäddade resurser. |
| [for_embedded_resources](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/#page_stream_factory) | Initierar en HtmlViewOptions-instans för att rendera till HTML med inbäddade resurser. |
| [for_embedded_resources](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/) | Initierar en instans av klassen [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) med inbäddade resurser. |
| [for_embedded_resources](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/#file_path_format) | Initierar en HtmlViewOptions-instans för inbäddade resurser. |
| [for_embedded_resources_create_page_stream](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources_create_page_stream/) |  |
| [for_embedded_resources_file](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources_file/) |  |
| [for_embedded_resources_ipage_stream_factory](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources_ipage_stream_factory/) |  |
| [for_embedded_resources_string](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources_string/) |  |
| [for_external_resources](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/#create_page_stream-create_resource_stream-create_resource_url) | Initierar en instans av klassen [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) för att rendera till HTML med externa resurser. |
| [for_external_resources](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/#create_page_stream-create_resource_stream-create_resource_url-release_page_stream-release_resource_stream) | Initierar en instans av HtmlViewOptions-klassen för att rendera till HTML med externa resurser. |
| [for_external_resources](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/#page_stream_factory-resource_stream_factory) | Initierar en HtmlViewOptions-instans för att rendera till HTML med externa resurser. |
| [for_external_resources](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/) | Initierar en HtmlViewOptions-instans konfigurerad för att generera HTML-filer med externa resurser. |
| [for_external_resources](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/#file_path_format-resource_file_path_format-resource_url_format) | Initierar en instans av klassen [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/). |
| [for_external_resources_create_page_stream](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources_create_page_stream/) |  |
| [for_external_resources_file](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources_file/) |  |
| [for_external_resources_ipage_stream_factory](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources_ipage_stream_factory/) |  |
| [for_external_resources_string](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources_string/) |  |
| [rotate_page](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page/) | Tillämpar medurs rotation på en sida. (ärvd från [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [rotate_page_int32](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page_int32/) | (ärvd från [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [exclude_fonts](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/exclude_fonts/) | Egenskapen inaktiverar att lägga till några typsnitt i HTML-dokumentet. |
| [fonts_to_exclude](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/fonts_to_exclude/) | Listan med typsnittsnamn som ska uteslutas från HTML-dokumentet. |
| [for_printing](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/for_printing/) | Egenskapen möjliggör optimering av den genererade HTML för utskrift. |
| [image_height](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/image_height/) | Höjden på en utdata bild (i pixlar). Denna egenskap är endast tillgänglig när en enskild bild konverteras till HTML. |
| [image_max_height](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/image_max_height/) | Den maximala höjden på en utdata bild i pixlar. Denna egenskap är endast tillgänglig när en enda bild konverteras till HTML. |
| [image_max_width](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/image_max_width/) | Den maximala bredden på en utdata bild (i pixlar). Denna egenskap är endast tillgänglig när en enda bild konverteras till HTML. |
| [image_width](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/image_width/) | Bredden på utdata bilden (i pixlar). |
| [minify](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/minify/) | Egenskapen möjliggör minifiering av HTML-innehåll och HTML-resurser. |
| [remove_java_script](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/remove_java_script/) | Egenskapen bestämmer om JavaScript-källkod tas bort från länkar i de genererade HTML-dokumenten när inmatningsdokument som innehåller skript renderas. Aktiverad som standard (`True`). |
| [render_responsive](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/render_responsive/) | Egenskapen möjliggör responsiv rendering. |
| [render_to_single_page](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/render_to_single_page/) | Egenskapen möjliggör rendering av ett helt dokument till en enda HTML-fil. |
| [archive_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/archive_options/) | Visningsalternativen för arkivfiler. (ärvd från [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [cad_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/cad_options/) | Visningsalternativen för CAD-ritningar. (ärvd från [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [default_font_name](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/default_font_name/) | Standardteckensnittet för ett dokument som används vid rendering när ett nödvändigt teckensnitt saknas. (ärvd från [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [email_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/email_options/) | Visningsalternativen för e‑postmeddelanden. (ärvd från [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [mail_storage_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/mail_storage_options/) | Visningsalternativen för e‑postlagringsdatafiler. (ärvd från [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [outlook_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/outlook_options/) | Visningsalternativen för Microsoft Outlook-datafiler. (ärvd från [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [page_rotations](/viewer/python-net/groupdocs.viewer.options/viewoptions/page_rotations/) | Sidrotationen. (ärvd från [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [pdf_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/pdf_options/) | Visningsalternativen för PDF-dokument. (ärvd från [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [presentation_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/presentation_options/) | Visningsalternativen för presentationsfiler. (ärvd från [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [project_management_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/project_management_options/) | Visningsalternativen för projektledningsfiler. (ärvd från [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [remove_comments](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/) | Egenskapen inaktiverar rendering av kommentarer när den är satt till True. Som standard är den False, så alla kommentarer visas. (ärvd från [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_comments](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_comments/) | Egenskapen möjliggör att aktivera eller inaktivera rendering av kommentarer. (ärvd från [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_hidden_pages](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_hidden_pages/) | Egenskapen möjliggör rendering av dolda sidor. (ärvd från [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_notes](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/) | Egenskapen möjliggör rendering av anteckningar och annotationer för vissa format. (ärvd från [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [spreadsheet_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/spreadsheet_options/) | Visningsalternativen för kalkylbladsfiler. (ärvd från [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [text_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/text_options/) | Textalternativen för rendering av textfiler. (ärvd från [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [visio_rendering_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/visio_rendering_options/) | Visio‑filernas visningsalternativ. (ärvd från [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [watermark](/viewer/python-net/groupdocs.viewer.options/viewoptions/watermark/) | Textvattenstämpeln som ska tillämpas på varje sida. (ärvd från [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [web_document_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/web_document_options/) | Visningsalternativen för webb‑filer. (ärvd från [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [word_processing_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/word_processing_options/) | Visningsalternativen för ordbehandlingsfiler. (ärvd från [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Guides
Uppgiftsguider som använder `HtmlViewOptions`:

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)
* [Load document from local disk](/viewer/python-net/guides/load-document-from-local-disk/)
* [Load document from stream](/viewer/python-net/guides/load-document-from-stream/)
* [Load document from URL](/viewer/python-net/guides/load-document-from-url/)
* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)

### Se även
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
