---
title: EmailOptions class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Contains options for rendering email messages."
type: docs
url: /python-net/groupdocs.viewer.options/emailoptions/
is_root: false
weight: 40
---


## EmailOptions class

Contains options for rendering email messages.

GroupDocs.Viewer supports the EmailOptions class that allows you to specify different options for rendering email messages. To access these options, use the EmailOptions property on one of the following view option classes, depending on the desired output format:

- [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
- [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
- [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
- [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)

The EmailOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/emailoptions/__init__/) | Initializes an instance of the [`EmailOptions`](/viewer/python-net/groupdocs.viewer.options/emailoptions/) class. |

### Properties
| Property | Description |
| :- | :- |
| [date_time_format](/viewer/python-net/groupdocs.viewer.options/emailoptions/date_time_format/) | The time format (can include TimeZone). If not set, the current system format is used. |
| [field_text_map](/viewer/python-net/groupdocs.viewer.options/emailoptions/field_text_map/) | The mapping between email message [`Field`](/viewer/python-net/groupdocs.viewer.options/field/) and field text representation. |
| [page_size](/viewer/python-net/groupdocs.viewer.options/emailoptions/page_size/) | The size of the output page. |
| [time_zone_offset](/viewer/python-net/groupdocs.viewer.options/emailoptions/time_zone_offset/) | The message time zone offset. |

### See Also
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
