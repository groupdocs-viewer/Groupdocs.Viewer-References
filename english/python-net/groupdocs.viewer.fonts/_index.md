---
title: groupdocs.viewer.fonts
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Font loading and substitution configuration."
type: docs
url: /python-net/groupdocs.viewer.fonts/
is_root: false
weight: 40
---


Font loading and substitution configuration.

### Classes
| Class | Description |
| :- | :- |
| [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) | Represents the folder that contains TrueType fonts. |
| [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/) | Provides methods for working with sources to look for TrueType fonts. |
| [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) | Represents 4 possible styles of the font, used in the document: Regular, Bold, Italic, or Bold Italic. |
| [`IFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/) | Represents a common interface for all fonts that can be extracted from all supported families of document formats: PDF, WordProcessing, Spreadsheet, and Presentation. |
| [`PdfFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/) | Encapsulates metadata and binary data of a PDF font loaded into a [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instance, which may be embedded in the document or installed on the operating system where GroupDocs.Viewer runs. |
| [`PresentationFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/) | Represents metainfo and binary data of a font from a Presentation document loaded into a [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instance. The font is used in the document content and may be embedded in the document or installed in the operating system where the viewer runs. |
| [`SpreadsheetFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/) | Encapsulates metainfo and binary data of a font from a spreadsheet document loaded into a [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instance. Spreadsheet documents cannot have embedded fonts, so a font returned by [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) is installed in the operating system where the viewer runs. |
| [`WordProcessingFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/) | Encapsulates metainfo and binary data of a font from a WordProcessing document loaded into a [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instance. |
| [`WordProcessingSubstitutedFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/) | Encapsulates metainfo and binary data of one font from a WordProcessing document, which originally is not used in the loaded [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instance document, but serves as a substitution font for those that cannot be found on the target machine. Substituted fonts exist only for the WordProcessing formats family. |

### Enumerations
| Enum | Description |
| :- | :- |
| [`FontFormat`](/viewer/python-net/groupdocs.viewer.fonts/fontformat/) |  |
| [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) | Represents a marker interface for font sources. |
| [`SearchOption`](/viewer/python-net/groupdocs.viewer.fonts/searchoption/) |  |
