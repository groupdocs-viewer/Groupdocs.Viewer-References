---
title: SpreadsheetFontInfo class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Encapsulates metainfo and binary data of a font from a spreadsheet document loaded into a Viewer instance."
type: docs
url: /python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/
is_root: false
weight: 100
---


## SpreadsheetFontInfo class

Encapsulates metainfo and binary data of a font from a spreadsheet document loaded into a [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instance. Spreadsheet documents cannot have embedded fonts, so a font returned by [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) is installed in the operating system where the viewer runs.

The SpreadsheetFontInfo type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/__init__/) |  |

### Methods
| Method | Description |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css/#output) | Serializes the font info as a @font-face at-rule and writes it to the specified text writer. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css_text_writer/) |  |

### Properties
| Property | Description |
| :- | :- |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/charset/) | The character set of this font. |
| [color](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/color/) | The color of this font. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/content/) | The content of this font as a byte array. If only metainfo about this font is available and its binary content is unavailable, the property returns None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/family_name/) | The family name of the font, without style, never is null or empty string. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/format/) | The format of this font. |
| [is_strikeout](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_strikeout/) | The font has a single strikeout. |
| [is_underline](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_underline/) | The font has an underline. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/style/) | The style of this font — may be Regular, Bold, Italic, or Bold Italic. |

### See Also
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
