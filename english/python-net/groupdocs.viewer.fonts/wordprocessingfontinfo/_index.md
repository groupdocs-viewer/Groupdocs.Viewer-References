---
title: WordProcessingFontInfo class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Encapsulates metainfo and binary data of a font from a WordProcessing document loaded into a Viewer instance."
type: docs
url: /python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/
is_root: false
weight: 110
---


## WordProcessingFontInfo class

Encapsulates metainfo and binary data of a font from a WordProcessing document loaded into a [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instance.

Immutable struct.

Its instances are produced and returned by the [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) public API and normally should not be created by the user.

For details, see the documentation: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

The WordProcessingFontInfo type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/__init__/) |  |

### Methods
| Method | Description |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css/#output) | Serializes the font info as a @font-face at-rule and writes it to the specified text writer. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/to_string/) | Returns a debug info about this font data as the next template: "name style, embedded/system, format". |

### Properties
| Property | Description |
| :- | :- |
| [alt_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/alt_family_name/) | The alternative family name of the font. If missing, then an empty string. |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/charset/) | The character set of this font. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/content/) | The content of this font as a byte array. If only metainfo about this font is available and the binary content is unavailable, the property returns None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/family_name/) | The family name of the font, without style; never None or empty string. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/format/) | The format of this font. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/is_embedded/) | The property indicates whether this font is embedded inside the document, loaded into the [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instance (`True`), or it is a system font (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/style/) | The style of the font — may be Regular, Bold, Italic, or Bold Italic. |

### See Also
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
