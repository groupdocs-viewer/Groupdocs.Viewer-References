---
title: PresentationOptions
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Provides options for rendering presentations options.
type: docs
weight: 26
url: /nodejs-java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

Provides options for rendering presentations options.

For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/
## Constructors

| Constructor | Description |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [isRenderToPureHtml()](#isRenderToPureHtml--) | Enables a new HTML rendering mode for Presentation documents. |
| [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Enables a new HTML rendering mode for Presentation documents. |
| [getResolution()](#getResolution--) | Resolution for images inside presentation (for to HTML/PDF rendering only). |
| [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | Resolution for images inside presentation (for to HTML/PDF rendering only). |
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Enables a new HTML rendering mode for Presentation documents.

In this mode, the Presentation files are rendered to pure HTML/CSS markup, without SVG images. By default, this feature is disabled (false). Existing SVG-based HTML renderer is used if this option is not enabled.

**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Enables a new HTML rendering mode for Presentation documents.

In this mode, the Presentation files are rendered to pure HTML/CSS markup, without SVG images. By default, this feature is disabled (false). Existing SVG-based HTML renderer is used if this option is not enabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Resolution for images inside presentation (for to HTML/PDF rendering only).

For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


Resolution for images inside presentation (for to HTML/PDF rendering only).

For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

