---
title: JpgViewOptions
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: 
type: docs

url: /nodejs-java/groupdocs.viewer/jpgviewoptions/jpgviewoptions/
---

## JpgViewOptions([CreatePageStream](../../createpagestream) createPageStream) function
Initializes new instance of  JpgViewOptions class.

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../createpagestream) | The method that instantiates stream used to write output page data. |

### Result
JpgViewOptions


---


## JpgViewOptions([CreatePageStream](../../createpagestream) createPageStream, [ReleasePageStream](../../releasepagestream) releasePageStream) function
Initializes new instance of  JpgViewOptions class.

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../createpagestream) | The method that instantiates stream used to write output page data. |
| releasePageStream | [ReleasePageStream](../../releasepagestream) | The method that releases stream created by method assigned to delegate that passed to createPageStream parameter. |

### Result
JpgViewOptions


---


## JpgViewOptions([PageStreamFactory](../../pagestreamfactory) pageStreamFactory) function

 Initializes new instance of  JpgViewOptions class.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../pagestreamfactory) | The factory which implements methods for creating and releasing output page stream. |

### Result
JpgViewOptions

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code pageStreamFactory} is null. |


---


## JpgViewOptions() function

 Initializes new instance of  JpgViewOptions class.
 
 
 
 This constructor initializes new instance of  JpgViewOptions
 with "p_{0}.jpg" as file path format for the output files.
 The output files will be placed into current working directory of the
 application.
 
 

### Result
JpgViewOptions


---


## JpgViewOptions(String filePathFormat) function

 Initializes new instance of  JpgViewOptions class.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePathFormat | String | The file path format e&#46;g&#46; 'page_{0}.jpg'. |

### Result
JpgViewOptions

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code filePathFormat} is null or empty. |


---


## JpgViewOptions(Path filePathFormat) function

 Initializes new instance of  JpgViewOptions class.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePathFormat | Path | The file path format e&#46;g&#46; 'page_{0}.jpg'. |

### Result
JpgViewOptions

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code filePathFormat} is null or empty. |


---


