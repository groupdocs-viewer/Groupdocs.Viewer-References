---
title: forEmbeddedResources
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: 
type: docs

url: /nodejs-java/groupdocs.viewer/htmlviewoptions/forembeddedresources/
---

## forEmbeddedResources([CreatePageStream](../../createpagestream) createPageStream)  function
Initializes new instance of  HtmlViewOptions class for rendering into HTML with embedded resources.

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../createpagestream) | The function that instantiates stream used to write output page data. |

### Result
HtmlViewOptions


---


## forEmbeddedResources([CreatePageStream](../../createpagestream) createPageStream, [ReleasePageStream](../../releasepagestream) releasePageStream)  function
Initializes new instance of  HtmlViewOptions class for rendering into HTML with embedded resources.

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../createpagestream) | The function that instantiates stream used to write output page data. |
| releasePageStream | [ReleasePageStream](../../releasepagestream) | The function that releases stream created by function assigned to delegate that passed to createPageStream parameter. |

### Result
HtmlViewOptions


---


## forEmbeddedResources([PageStreamFactory](../../pagestreamfactory) pageStreamFactory)  function

 Initializes new instance of  HtmlViewOptions class for rendering into HTML with embedded resources.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../pagestreamfactory) | The factory which implements functions for creating and releasing output page stream. |

### Result
HtmlViewOptions

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code pageStreamFactory} is null. |


---


## forEmbeddedResources()  function

 Initializes new instance of  HtmlViewOptions class.
 

### Result
HtmlViewOptions


---


## forEmbeddedResources(String filePathFormat)  function

 Initializes new instance of  HtmlViewOptions class.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePathFormat | String | The file path format e&#46;g&#46; 'page_{0}.html'. |

### Result
HtmlViewOptions

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code filePathFormat} is null or empty. |


---


## forEmbeddedResources(Path filePathFormat)  function

 Initializes new instance of  HtmlViewOptions class.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePathFormat | Path | The file path format e&#46;g&#46; 'page_{0}.html'. |

### Result
HtmlViewOptions

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code filePathFormat} is null or empty. |


---


## forEmbeddedResources([CreatePageStream](../../createpagestream) createPageStream)  function
Initializes new instance of  HtmlViewOptions class for rendering into HTML with embedded resources.

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../createpagestream) | The function that instantiates stream used to write output page data. |

### Result
HtmlViewOptions


---


## forEmbeddedResources([CreatePageStream](../../createpagestream) createPageStream, [ReleasePageStream](../../releasepagestream) releasePageStream)  function
Initializes new instance of  HtmlViewOptions class for rendering into HTML with embedded resources.

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../createpagestream) | The function that instantiates stream used to write output page data. |
| releasePageStream | [ReleasePageStream](../../releasepagestream) | The function that releases stream created by function assigned to delegate that passed to createPageStream parameter. |

### Result
HtmlViewOptions


---


## forEmbeddedResources([PageStreamFactory](../../pagestreamfactory) pageStreamFactory)  function

 Initializes new instance of  HtmlViewOptions class for rendering into HTML with embedded resources.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../pagestreamfactory) | The factory which implements functions for creating and releasing output page stream. |

### Result
HtmlViewOptions

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code pageStreamFactory} is null. |


---


## forEmbeddedResources()  function

 Initializes new instance of  HtmlViewOptions class.
 

### Result
HtmlViewOptions


---


## forEmbeddedResources(String filePathFormat)  function

 Initializes new instance of  HtmlViewOptions class.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePathFormat | String | The file path format e&#46;g&#46; 'page_{0}.html'. |

### Result
HtmlViewOptions

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code filePathFormat} is null or empty. |


---


## forEmbeddedResources(Path filePathFormat)  function

 Initializes new instance of  HtmlViewOptions class.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePathFormat | Path | The file path format e&#46;g&#46; 'page_{0}.html'. |

### Result
HtmlViewOptions

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code filePathFormat} is null or empty. |


---


