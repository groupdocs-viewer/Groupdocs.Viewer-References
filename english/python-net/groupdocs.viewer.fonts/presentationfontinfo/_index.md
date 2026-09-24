---
title: PresentationFontInfo class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Represents metainfo and binary data of a font from a Presentation document loaded into a Viewer instance."
type: docs
url: /python-net/groupdocs.viewer.fonts/presentationfontinfo/
is_root: false
weight: 80
---


## PresentationFontInfo class

Represents metainfo and binary data of a font from a Presentation document loaded into a [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instance. The font is used in the document content and may be embedded in the document or installed in the operating system where the viewer runs.

The PresentationFontInfo type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/__init__/) |  |

### Methods
| Method | Description |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css/#output) | Serializes this font info as a @font-face at-rule and writes it to the specified text writer. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css_text_writer/) |  |

### Properties
| Property | Description |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/content/) | The content of this font as a byte array. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/family_name/) | The family name of the font, without style; never None or empty string. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/format/) | The format of this font. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/is_embedded/) | The property indicates whether the font is embedded inside the document and loaded into the [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instance (`True`), or is a system font (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/style/) | The style of the font — may be Regular, Bold, Italic, or Bold Italic. |

### See Also
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
