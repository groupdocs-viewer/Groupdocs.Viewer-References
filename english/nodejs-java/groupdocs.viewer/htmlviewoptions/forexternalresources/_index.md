---
title: forExternalResources
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: 
type: docs

url: /nodejs-java/groupdocs.viewer/htmlviewoptions/forexternalresources/
---

## forExternalResources([CreatePageStream](../../createpagestream) createPageStream, [CreateResourceStream](../../createresourcestream) createResourceStream, [CreateResourceUrl](../../createresourceurl) createResourceUrl)  function
Initializes new instance of  HtmlViewOptions class for rendering into HTML with external resources.

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../createpagestream) | The function that instantiates stream used to write output page data. |
| createResourceStream | [CreateResourceStream](../createresourcestream) | The function that releases stream created by createPageStream function. |
| createResourceUrl | [CreateResourceUrl](../../createresourceurl) | The function that creates URL for HTML resource. |

### Result
HtmlViewOptions


---


## forExternalResources([CreatePageStream](../../createpagestream) createPageStream, [CreateResourceStream](../../createresourcestream) createResourceStream, [CreateResourceUrl](../../createresourceurl) createResourceUrl, [ReleasePageStream](../../releasepagestream) releasePageStream, [ReleaseResourceStream](../../releaseresourcestream) releaseResourceStream)  function
Initializes new instance of  HtmlViewOptions class for rendering into HTML with external resources.

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../createpagestream) | The function that instantiates stream used to write output page data. |
| createResourceStream | [CreateResourceStream](../createresourcestream) | The function that instantiates stream used to write output HTML resource data. |
| createResourceUrl | [CreateResourceUrl](../createresourceurl) | The function that creates URL for HTML resource. |
| releasePageStream | [ReleasePageStream](../releasepagestream) | The function that releases stream created by function assigned to delegate that passed to createPageStream parameter. |
| releaseResourceStream | [ReleaseResourceStream](../../releaseresourcestream) | The function that releases stream created by function assigned to delegate that passed to createResourceStream parameter. |

### Result
HtmlViewOptions


---


## forExternalResources([PageStreamFactory](../../pagestreamfactory) pageStreamFactory, [ResourceStreamFactory](../../resourcestreamfactory) resourceStreamFactory)  function

 Initializes new instance of  HtmlViewOptions class for rendering into HTML with external resources.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../pagestreamfactory) | The factory which implements functions for creating and releasing output page stream. |
| resourceStreamFactory | [ResourceStreamFactory](../../resourcestreamfactory) | The factory which implements functions that are required for creating resource URL, instantiating and releasing output HTML resource stream. |

### Result
HtmlViewOptions

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code resourceStreamFactory} is null. |


---


## forExternalResources()  function

 Initializes new instance of  HtmlViewOptions class.
 
 This constructor initializes new instance of  HtmlViewOptions
 
 - with "p_{0}.html" as file path format for the output HTML files;
 - with "p_{0}_{1}" as file path format for the output HTML-resource files;
 - with "p_{0}_{1}" as URL format for HTML-resources;
 
 The output files will be placed into current working directory of the application.
 

### Result
HtmlViewOptions


---


## forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)  function

 Initializes new instance of  HtmlViewOptions class.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePathFormat | String | The file path format e&#46;g&#46; 'page_{0}.html'. |
| resourceFilePathFormat | String | The resource file path format e&#46;g&#46; 'page_{0}/resource_{1}'. |
| resourceUrlFormat | String | The resource URL format e&#46;g&#46; 'page_{0}/resource_{1}'. |

### Result
HtmlViewOptions

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code resourceUrlFormat} is null or empty. |


---


## forExternalResources([CreatePageStream](../../createpagestream) createPageStream, [CreateResourceStream](../../createresourcestream) createResourceStream, [CreateResourceUrl](../../createresourceurl) createResourceUrl)  function
Initializes new instance of  HtmlViewOptions class for rendering into HTML with external resources.

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../createpagestream) | The function that instantiates stream used to write output page data. |
| createResourceStream | [CreateResourceStream](../createresourcestream) | The function that releases stream created by createPageStream function. |
| createResourceUrl | [CreateResourceUrl](../../createresourceurl) | The function that creates URL for HTML resource. |

### Result
HtmlViewOptions


---


## forExternalResources([CreatePageStream](../../createpagestream) createPageStream, [CreateResourceStream](../../createresourcestream) createResourceStream, [CreateResourceUrl](../../createresourceurl) createResourceUrl, [ReleasePageStream](../../releasepagestream) releasePageStream, [ReleaseResourceStream](../../releaseresourcestream) releaseResourceStream)  function
Initializes new instance of  HtmlViewOptions class for rendering into HTML with external resources.

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../createpagestream) | The function that instantiates stream used to write output page data. |
| createResourceStream | [CreateResourceStream](../createresourcestream) | The function that instantiates stream used to write output HTML resource data. |
| createResourceUrl | [CreateResourceUrl](../createresourceurl) | The function that creates URL for HTML resource. |
| releasePageStream | [ReleasePageStream](../releasepagestream) | The function that releases stream created by function assigned to delegate that passed to createPageStream parameter. |
| releaseResourceStream | [ReleaseResourceStream](../../releaseresourcestream) | The function that releases stream created by function assigned to delegate that passed to createResourceStream parameter. |

### Result
HtmlViewOptions


---


## forExternalResources([PageStreamFactory](../../pagestreamfactory) pageStreamFactory, [ResourceStreamFactory](../../resourcestreamfactory) resourceStreamFactory)  function

 Initializes new instance of  HtmlViewOptions class for rendering into HTML with external resources.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../pagestreamfactory) | The factory which implements functions for creating and releasing output page stream. |
| resourceStreamFactory | [ResourceStreamFactory](../../resourcestreamfactory) | The factory which implements functions that are required for creating resource URL, instantiating and releasing output HTML resource stream. |

### Result
HtmlViewOptions

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code resourceStreamFactory} is null. |


---


## forExternalResources()  function

 Initializes new instance of  HtmlViewOptions class.
 
 This constructor initializes new instance of  HtmlViewOptions
 
 - with "p_{0}.html" as file path format for the output HTML files;
 - with "p_{0}_{1}" as file path format for the output HTML-resource files;
 - with "p_{0}_{1}" as URL format for HTML-resources;
 
 The output files will be placed into current working directory of the application.
 

### Result
HtmlViewOptions


---


## forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)  function

 Initializes new instance of  HtmlViewOptions class.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePathFormat | String | The file path format e&#46;g&#46; 'page_{0}.html'. |
| resourceFilePathFormat | String | The resource file path format e&#46;g&#46; 'page_{0}/resource_{1}'. |
| resourceUrlFormat | String | The resource URL format e&#46;g&#46; 'page_{0}/resource_{1}'. |

### Result
HtmlViewOptions

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code resourceUrlFormat} is null or empty. |


---


