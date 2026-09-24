---
title: IFontInfo class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Represents a common interface for all fonts that can be extracted from all supported families of document formats: PDF, WordProcessing, Spreadsheet, and Presentation."
type: docs
url: /python-net/groupdocs.viewer.fonts/ifontinfo/
is_root: false
weight: 50
---


## IFontInfo class

Represents a common interface for all fonts that can be extracted from all supported families of document formats: PDF, WordProcessing, Spreadsheet, and Presentation.

The IFontInfo type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css/#output) | Serializes this font info as a @font-face at-rule and writes it to the specified text writer. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css_text_writer/) |  |

### Properties
| Property | Description |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/content/) | The binary content of the font as a byte array, if available, or None if not. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/family_name/) | The family name of the font as a string. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/format/) | The format of this font as an enum — TrueType, TrueType Collection, OpenType, Embedded OpenType, or `FontFormat.unknown`. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/style/) | The style of the font as an enum (Regular, Bold, Italic, or Bold Italic); some document formats may support only [`FontStyles.regular`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/). |

### See Also
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
