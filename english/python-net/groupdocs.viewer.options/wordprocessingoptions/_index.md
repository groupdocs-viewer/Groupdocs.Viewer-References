---
title: WordProcessingOptions class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Contains options for rendering Word documents."
type: docs
url: /python-net/groupdocs.viewer.options/wordprocessingoptions/
is_root: false
weight: 380
---


## WordProcessingOptions class

Contains options for rendering Word documents.

For details, see the documentation at https://docs.groupdocs.com/viewer/net/render-word-documents/.

The WordProcessingOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/) | Initializes options for rendering word processing documents. |

### Methods
| Method | Description |
| :- | :- |
| [clone](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/clone/) | Creates and returns a full deep copy of these options. |
| [equals](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals/#options) | Determines whether the specified [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/) instance is equal to this instance. |
| [equals_word_processing_options](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals_word_processing_options/) |  |

### Properties
| Property | Description |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/bottom_margin/) | The bottom margin of a page. |
| [enable_open_type_features](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/enable_open_type_features/) | The option enables kerning and other OpenType features when rendering Arabic, Hebrew, Indian Latin-based, or Cyrillic-based scripts. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/) | The horizontal resolution for generated images in dots per inch. This option is used when rendering WordProcessing documents to PNG or JPEG formats only. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/left_margin/) | The left margin of a page. |
| [page_number_location](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_number_location/) | The page numbering location for the loaded WordProcessing document, which can forcibly apply page numbering; by default it is `WordsPageNumberLocation.not_apply`, leaving the document intact. |
| [page_size](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/) | The size of the output page. |
| [render_tracked_changes](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/render_tracked_changes/) | The property enables rendering of tracked changes (revisions). |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/right_margin/) | The right margin of a page. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/top_margin/) | The top margin of a page in points. |
| [unlink_table_of_contents](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/unlink_table_of_contents/) | The option disables navigation from the table of contents when set to True for HTML or PDF rendering. |
| [update_fields](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/update_fields/) | The property determines whether fields of certain types are updated before saving the WordProcessing document to HTML, PDF, PNG, or JPEG formats. The default is True, meaning fields are updated. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/vertical_resolution/) | The vertical resolution for generated images in dots per inch, used when rendering WordProcessing documents to PNG or JPEG formats only. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("with_tracked_changes.docx") as viewer:
    view_options = PdfViewOptions("output/word_with_tracked_changes.pdf")
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### See Also
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
