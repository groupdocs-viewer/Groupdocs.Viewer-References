---
title: WordProcessingSubstitutedFontInfo class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Encapsulates metainfo and binary data of one font from a WordProcessing document, which originally is not used in the loaded Viewer instance document, but serves as a substitution font for those that…"
type: docs
url: /python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
is_root: false
weight: 120
---


## WordProcessingSubstitutedFontInfo class

Encapsulates metainfo and binary data of one font from a WordProcessing document, which originally is not used in the loaded [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instance document, but serves as a substitution font for those that cannot be found on the target machine. Substituted fonts exist only for the WordProcessing formats family.

Immutable struct. Its instances are produced and returned by the [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) public API and normally should not be created by the user. For details, see the documentation: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

The WordProcessingSubstitutedFontInfo type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/__init__/) |  |

### Methods
| Method | Description |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css/#output) | Serializes the font info as a @font-face at-rule and writes it to the specified text writer. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/to_string/) | Returns a debug string containing font information in the format "original-name -> substituted-name style, format". |

### Properties
| Property | Description |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content/) | The content of the substituted font as a byte array. It is never None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/family_name/) | The family name of the substituted font, without style. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format/) | The format of this substituted (not original) font. |
| [original_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/original_family_name/) | The family name of the original font, which cannot be found on a target machine, without style. Never is null or empty string. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style/) | The style of the original font — may be Regular, Bold, Italic, or Bold Italic. |

### See Also
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
