---
title: PdfOptions
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: 
type: docs

url: /nodejs-java/groupdocs.viewer/pdfoptions/
---

## PdfOptions class

 Provides options for rendering PDF documents.
 
| [PdfOptions](pdfoptions)() | Initializes new instance of PdfOptions class. |

## Functions

| Name | Description |
| --- | --- |
| [getImageQuality](getimagequality)() | Specifies output image quality for image resources when rendering into HTML. The default value is Low. |
| [isDisableCharsGrouping](isdisablecharsgrouping)() | If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML. May be useful to make text unselectable or HTML text is not rendered properly. When this option is set to true, the text is rendered as an image in the output HTML. Enable this option to make text unselectable or to fix characters rendering and make HTML look like PDF. The default value is false. This option is supported when rendering into HTML. /** Disables chars grouping to keep maximum precision during chars positioning when rendering the page. |
| [isEnableFontHinting](isenablefonthinting)() | Enables font hinting. The font hinting adjusts the display of an outline font. Supported only for TTF fonts when these fonts are used in source document. This option is supported when rendering into PNG or JPG formats. |
| [isEnableLayeredRendering](isenablelayeredrendering)() | Enables rendering of text and graphics according to z-order in original PDF document when rendering into HTML. By default text and graphics are rendered into HTML as a single layer. |
| [isRenderOriginalPageSize](isrenderoriginalpagesize)() | When this option enabled the output pages will have the same size in pixels as page size in a source PDF document. By default GroupDocs.Viewer calculates output image page size for better rendering quality. |
| [isRenderTextAsImage](isrendertextasimage)() | If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML. May be useful to make text unselectable or HTML text is not rendered properly. When this option is set to true, the text is rendered as an image in the output HTML. Enable this option to make text unselectable or to fix characters rendering and make HTML look like PDF. The default value is false. This option is supported when rendering into HTML. |
| [setDisableCharsGrouping](setdisablecharsgrouping)(boolean) | Disables chars grouping to keep maximum precision during chars positioning when rendering the page. |
| [setEnableFontHinting](setenablefonthinting)(boolean) | Enables font hinting. The font hinting adjusts the display of an outline font. Supported only for TTF fonts when these fonts are used in source document. This option is supported when rendering into PNG or JPG formats. |
| [setEnableLayeredRendering](setenablelayeredrendering)(boolean) | Enables rendering of text and graphics according to z-order in original PDF document when rendering into HTML. By default text and graphics are rendered into HTML as a single layer. |
| [setImageQuality](setimagequality)([ImageQuality](../imagequality)) | Specifies output image quality for image resources when rendering into HTML. The default value is Low. |
| [setRenderOriginalPageSize](setrenderoriginalpagesize)(boolean) | When this option enabled the output pages will have the same size in pixels as page size in a source PDF document. By default GroupDocs.Viewer calculates output image page size for better rendering quality. |
| [setRenderTextAsImage](setrendertextasimage)(boolean) | If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML. May be useful to make text unselectable or HTML text is not rendered properly. When this option is set to true, the text is rendered as an image in the output HTML. Enable this option to make text unselectable or to fix characters rendering and make HTML look like PDF. The default value is false. This option is supported when rendering into HTML. |
