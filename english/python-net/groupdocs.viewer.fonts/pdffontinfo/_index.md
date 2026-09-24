---
title: PdfFontInfo class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Encapsulates metadata and binary data of a PDF font loaded into a Viewer instance, which may be embedded in the document or installed on the operating system where GroupDocs.Viewer runs."
type: docs
url: /python-net/groupdocs.viewer.fonts/pdffontinfo/
is_root: false
weight: 70
---


## PdfFontInfo class

Encapsulates metadata and binary data of a PDF font loaded into a [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instance, which may be embedded in the document or installed on the operating system where GroupDocs.Viewer runs.

The PdfFontInfo type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/__init__/) |  |

### Methods
| Method | Description |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css/#output) | Serializes this font info as a @font-face at-rule and writes it to the specified text writer. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css_text_writer/) |  |

### Properties
| Property | Description |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/content/) | The content of this font as a byte array, or None if only metadata is available and the binary content is unavailable. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/family_name/) | The family name of the font, without style; never None or empty string. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/format/) | The format of this font. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_embedded/) | The property indicates whether the font is embedded inside the PDF document and loaded into the Viewer instance (`True`), or not. |
| [is_installed](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_installed/) | The property indicates whether this font is present (installed) in the operating system where the GroupDocs.Viewer is running. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/style/) | The style of the font; may be Regular, Bold, Italic, or Bold Italic. |

### See Also
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
