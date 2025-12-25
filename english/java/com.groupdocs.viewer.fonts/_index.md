---
title: com.groupdocs.viewer.fonts
second_title: GroupDocs.Viewer for Java API Reference
description: The package provides classes and enumerations to manage fonts used during the rendering process.
type: docs
weight: 16
url: /java/com.groupdocs.viewer.fonts/
---

The package provides classes and enumerations to manage fonts used during the rendering process.

The main classes and interfaces in this package are:

 *  [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) - Represents a folder that contains TrueType fonts.
 *  [FontSettings](../../com.groupdocs.viewer.fonts/fontsettings) - Provides methods for working with sources to look for TrueType fonts.
 *  [FontSource](../../com.groupdocs.viewer.fonts/fontsource) - Marker interface for the font sources.

For more details on working with fonts in GroupDocs.Viewer, please refer to the [GroupDocs.Viewer Documentation][].


[GroupDocs.Viewer Documentation]: https://docs.groupdocs.com/viewer/java/


## Classes

| Class | Description |
| --- | --- |
| [FolderFontSource](../com.groupdocs.viewer.fonts/folderfontsource) | Represents a folder that contains TrueType fonts. |
| [FontFormat](../com.groupdocs.viewer.fonts/fontformat) | Represents all font formats, which may be present in the UsedFontInfo class. |
| [FontSettings](../com.groupdocs.viewer.fonts/fontsettings) | Provides methods for working with sources to look for TrueType fonts. |
| [FontStyles](../com.groupdocs.viewer.fonts/fontstyles) | Represents 4 possible styles of the font, used in the document: Regular, Bold, Italic, or Bold Italic. |
| [PdfFontInfo](../com.groupdocs.viewer.fonts/pdffontinfo) | Encapsulates meta-information and binary data of one font from a PDF document, loaded into the Viewer instance. |
| [PresentationFontInfo](../com.groupdocs.viewer.fonts/presentationfontinfo) | Encapsulates metadata and binary data of a font used in a Presentation document, loaded into the Viewer instance. |
| [SpreadsheetFontInfo](../com.groupdocs.viewer.fonts/spreadsheetfontinfo) | Encapsulates metainfo and binary data of one font from the Spreadsheet document, loaded into the Viewer instance. |
| [WordProcessingFontInfo](../com.groupdocs.viewer.fonts/wordprocessingfontinfo) | Encapsulates metainfo and binary data of one font from the WordProcessing document, loaded into the Viewer instance. |
| [WordProcessingSubstitutedFontInfo](../com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo) | Encapsulates metadata and binary data of one substituted font used in a WordProcessing document via GroupDocs.Viewer. |

## Interfaces

| Interface | Description |
| --- | --- |
| [FontSource](../com.groupdocs.viewer.fonts/fontsource) | Marker interface for the font sources. |
| [IFontInfo](../com.groupdocs.viewer.fonts/ifontinfo) | Common interface for all fonts that can be extracted from document formats: PDF, WordProcessing, Spreadsheet, and Presentation. |

## Enumerations

| Enum | Description |
| --- | --- |
| [SearchOption](../com.groupdocs.viewer.fonts/searchoption) | Specifies whether to search the current folder, or the current folder and all subfolders. |
