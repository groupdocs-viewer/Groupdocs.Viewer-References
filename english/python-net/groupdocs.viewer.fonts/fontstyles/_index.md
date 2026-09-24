---
title: FontStyles class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Represents 4 possible styles of the font, used in the document: Regular, Bold, Italic, or Bold Italic."
type: docs
url: /python-net/groupdocs.viewer.fonts/fontstyles/
is_root: false
weight: 40
---


## FontStyles class

Represents 4 possible styles of the font, used in the document: Regular, Bold, Italic, or Bold Italic.

Immutable struct with convenient API and combining operations.

The FontStyles type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/__init__/#is_bold-is_italic) | Initializes a FontStyles instance from specified bold and italic flags. |

### Methods
| Method | Description |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals/#other) | Indicates whether this FontStyles instance is equal to the specified instance. |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals/#other) | Indicates whether this [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) instance is equal to the specified uncasted object. |
| [equals_font_styles](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals_font_styles/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/get_hash_code/) | Returns a hash-code of this instance. |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/to_string/) | Returns the name of this font style, same as [`FontStyles.name`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/name/). |
| [try_parse](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/try_parse/#style-parsed) | Tries to parse specified raw string as a font style name. |

### Properties
| Property | Description |
| :- | :- |
| [is_bold](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/is_bold/) | The property indicates whether this [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) instance has a bold flag enabled (`True`) or disabled (`False`). |
| [is_italic](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/is_italic/) | The italic flag state of this [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) instance; True if enabled, False if disabled. |
| [name](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/name/) | The name of this font style. |

### Fields
| Field | Description |
| :- | :- |
| [REGULAR](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/) | Regular font style, default value (no bold and italic) |
| [BOLD](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/bold/) | Bold font style (bold only, without italic) |
| [ITALIC](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/italic/) | Italic font style (italic only, without bold) |
| [BOLD_ITALIC](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/bold_italic/) | BoldItalic font style (bold and italic together) |

### See Also
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
