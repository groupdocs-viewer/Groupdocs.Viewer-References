---
title: Viewer
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: 
type: docs

url: /nodejs-java/groupdocs.viewer/viewer/viewer/
---

## createViewerFromStream (ReadStream fileStream, Function callback) function

 Initializes new instance of  Viewer class.
 
 More about file types supported by GroupDocs.Viewer: Document formats supported by GroupDocs.Viewer

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fileStream | ReadStream | The method that returns readable stream. |
| callback | Function | callback(error, item) - Callback to be called when the class is created, item is the new instance of the Viewer |

### Result
Viewer

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code fileStream} is null. |


---


## createViewerFromStream (ReadStream fileStream, boolean leaveOpen, Function callback) function

 Initializes new instance of  Viewer class.
 
 Learn more
   
     
         More about file types supported by GroupDocs.Viewer:
       Document formats supported by GroupDocs.Viewer
     
     
         More about GroupDocs.Viewer for Java features:
      Developer Guide
     
     
         More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java:
      How to load and view document with GroupDocs.Viewer
     
   
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fileStream | ReadStream | The file stream. |
| leaveOpen | boolean | true to leave the stream open after the Viewer object is disposed; otherwise, false |
| callback | Function | callback(error, item) - Callback to be called when the class is created, item is the new instance of the Viewer |

### Result
Viewer


---


## createViewerFromStream (ReadStream fileStream, [LoadOptions](../../loadoptions) loadOptions, Function callback) function

 Initializes new instance of  Viewer class.
 

 Learn more
   
     
         More about file types supported by GroupDocs.Viewer:
       Document formats supported by GroupDocs.Viewer
     
     
         More about GroupDocs.Viewer for Java features:
      Developer Guide
     
     
         More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java:
      How to load and view document with GroupDocs.Viewer
     
   
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fileStream | ReadStream | The readable stream. |
| loadOptions | [LoadOptions](../../loadoptions) | The document load options. |
| callback | Function | callback(error, item) - Callback to be called when the class is created, item is the new instance of the Viewer |

### Result
Viewer

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code loadOptions} is null. |


---


## createViewerFromStream (ReadStream fileStream, [LoadOptions](../../loadoptions) loadOptions, boolean leaveOpen, Function callback) function

 Initializes new instance of  Viewer class.
 
 Learn more
   
     
         More about file types supported by GroupDocs.Viewer:
       Document formats supported by GroupDocs.Viewer
     
     
         More about GroupDocs.Viewer for Java features:
      Developer Guide
     
     
         More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java:
      How to load and view document with GroupDocs.Viewer
     
   
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fileStream | ReadStream | The file stream. |
| loadOptions | [LoadOptions](../loadoptions) | The document load options. |
| leaveOpen | boolean | true to leave the stream open after the Viewer object is disposed; otherwise, false |
| callback | Function | callback(error, item) - Callback to be called when the class is created, item is the new instance of the Viewer |

### Result
Viewer


---


## createViewerFromStream (ReadStream inputStream, [ViewerSettings](../../viewersettings) settings, Function callback) function

 Initializes new instance of  Viewer class.
 
 Learn more
   
     
         More about file types supported by GroupDocs.Viewer:
       Document formats supported by GroupDocs.Viewer
     
     
         More about GroupDocs.Viewer for Java features:
      Developer Guide
     
     
         More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java:
      How to load and view document with GroupDocs.Viewer
     
   
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| inputStream | ReadStream | The file stream |
| settings | [ViewerSettings](../../viewersettings) | The Viewer settings. |
| callback | Function | callback(error, item) - Callback to be called when the class is created, item is the new instance of the Viewer |

### Result
Viewer

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code settings} is null. |


---


## createViewerFromStream (ReadStream inputStream, [ViewerSettings](../../viewersettings) settings, boolean leaveOpen, Function callback) function
Initializes new instance of  class.

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| inputStream | ReadStream | The file stream. |
| settings | [ViewerSettings](../viewersettings) | The Viewer settings. |
| leaveOpen | boolean | true to leave the stream open after the Viewer object is disposed; otherwise, false |
| callback | Function | callback(error, item) - Callback to be called when the class is created, item is the new instance of the Viewer |

### Result
Viewer


---


## createViewerFromStream (ReadStream inputStream, [LoadOptions](../../loadoptions) loadOptions, [ViewerSettings](../../viewersettings) settings, Function callback) function

 Initializes new instance of  Viewer class.
 
 Learn more
   
     
         More about file types supported by GroupDocs.Viewer:
       Document formats supported by GroupDocs.Viewer
     
     
         More about GroupDocs.Viewer for Java features:
      Developer Guide
     
     
         More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java:
      How to load and view document with GroupDocs.Viewer
     
   
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| inputStream | ReadStream | The file stream |
| loadOptions | [LoadOptions](../loadoptions) | The document load options. |
| settings | [ViewerSettings](../../viewersettings) | The Viewer settings. |
| callback | Function | callback(error, item) - Callback to be called when the class is created, item is the new instance of the Viewer |

### Result
Viewer

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code settings} is null. |


---


## createViewerFromStream (ReadStream inputStream, [LoadOptions](../../loadoptions) loadOptions, [ViewerSettings](../../viewersettings) settings, boolean leaveOpen, Function callback) function

 Initializes new instance of  Viewer class.
 
 Learn more
   
     
         More about file types supported by GroupDocs.Viewer:
       Document formats supported by GroupDocs.Viewer
     
     
         More about GroupDocs.Viewer for Java features:
      Developer Guide
     
     
         More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java:
      How to load and view document with GroupDocs.Viewer
     
   
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| inputStream | ReadStream | The file stream. |
| loadOptions | [LoadOptions](../loadoptions) | The document load options. |
| settings | [ViewerSettings](../viewersettings) | The Viewer settings. |
| leaveOpen | boolean | true to leave the stream open after the Viewer object is disposed; otherwise, false |
| callback | Function | callback(error, item) - Callback to be called when the class is created, item is the new instance of the Viewer |

### Result
Viewer


---


## Viewer(URL url) function

 Initializes new instance of  Viewer class.
 
 More about file types supported by GroupDocs.Viewer: Document formats supported by GroupDocs.Viewer

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| url | URL | A url to a file that should be loaded into Viewer. |

### Result
Viewer

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code url} is null. |


---


## Viewer(URL url, [LoadOptions](../../loadoptions) loadOptions) function

 Initializes new instance of  Viewer class.
 

 Learn more
   
     
         More about file types supported by GroupDocs.Viewer:
       Document formats supported by GroupDocs.Viewer
     
     
         More about GroupDocs.Viewer for Java features:
      Developer Guide
     
     
         More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java:
      How to load and view document with GroupDocs.Viewer
     
   
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| url | URL | A url to a file that should be loaded into Viewer. |
| loadOptions | [LoadOptions](../../loadoptions) | The document load options. |

### Result
Viewer

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code loadOptions} is null. |


---


## Viewer(URL url, [ViewerSettings](../../viewersettings) settings) function

 Initializes new instance of  Viewer class.
 
 Learn more
   
     
         More about file types supported by GroupDocs.Viewer:
       Document formats supported by GroupDocs.Viewer
     
     
         More about GroupDocs.Viewer for Java features:
      Developer Guide
     
     
         More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java:
      How to load and view document with GroupDocs.Viewer
     
   
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| url | URL | A url to a file that should be loaded into Viewer. |
| settings | [ViewerSettings](../../viewersettings) | The Viewer settings. |

### Result
Viewer

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code settings} is null. |


---


## Viewer(URL url, [LoadOptions](../../loadoptions) loadOptions, [ViewerSettings](../../viewersettings) settings) function

 Initializes new instance of  Viewer class.
 
 Learn more
   
     
         More about file types supported by GroupDocs.Viewer:
       Document formats supported by GroupDocs.Viewer
     
     
         More about GroupDocs.Viewer for Java features:
      Developer Guide
     
     
         More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java:
      How to load and view document with GroupDocs.Viewer
     
   
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| url | URL | A url to a file that should be loaded into Viewer. |
| loadOptions | [LoadOptions](../loadoptions) | The document load options. |
| settings | [ViewerSettings](../../viewersettings) | The Viewer settings. |

### Result
Viewer

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code settings} is null. |


---


## Viewer([FileReader](../../filereader) fileReader, [ViewerSettings](../../viewersettings) settings) function

 Initializes new instance of  Viewer class.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fileReader | [FileReader](../filereader) | The file reader |
| settings | [ViewerSettings](../../viewersettings) | The Viewer settings. |

### Result
Viewer

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code settings} is null. |


---


## Viewer([FileReader](../../filereader) fileReader, [LoadOptions](../../loadoptions) loadOptions, [ViewerSettings](../../viewersettings) settings) function

 Initializes new instance of  Viewer class.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fileReader | [FileReader](../filereader) | The file reader. |
| loadOptions | [LoadOptions](../loadoptions) | The load options. |
| settings | [ViewerSettings](../../viewersettings) | The Viewer settings. |

### Result
Viewer

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code settings} is null. |


---


## Viewer(String filePath) function

 Initializes new instance of  Viewer class.
 
 Note: 
 Learn more
   
     
         More about file types supported by GroupDocs.Viewer:
       Document formats supported by GroupDocs.Viewer
     
     
         More about GroupDocs.Viewer for Java features:
      Developer Guide
     
   
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePath | String | The path to the file to render. |

### Result
Viewer

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code filePath} is null or empty. |


---


## Viewer(Path filePath) function

 Initializes new instance of  Viewer class.
 
 Note: 
 Learn more
   
     
         More about file types supported by GroupDocs.Viewer:
       Document formats supported by GroupDocs.Viewer
     
     
         More about GroupDocs.Viewer for Java features:
      Developer Guide
     
   
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePath | Path | The path to the file to render. |

### Result
Viewer

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code filePath} is null or empty. |


---


## Viewer(String filePath, [LoadOptions](../../loadoptions) loadOptions) function

 Initializes new instance of  Viewer class.
 
 Note: 
 Learn more
   
     
         More about file types supported by GroupDocs.Viewer:
       Document formats supported by GroupDocs.Viewer
     
     
         More about GroupDocs.Viewer for Java features:
      Developer Guide
     
     
         More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java:
      How to load and view document with GroupDocs.Viewer
     
   
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePath | String | The path to the file to render. |
| loadOptions | [LoadOptions](../../loadoptions) | The document load options. |

### Result
Viewer

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code loadOptions} is null. |


---


## Viewer(Path filePath, [LoadOptions](../../loadoptions) loadOptions) function

 Initializes new instance of  Viewer class.
 
 Note: 
 Learn more
   
     
         More about file types supported by GroupDocs.Viewer:
       Document formats supported by GroupDocs.Viewer
     
     
         More about GroupDocs.Viewer for Java features:
      Developer Guide
     
     
         More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java:
      How to load and view document with GroupDocs.Viewer
     
   
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePath | Path | The path to the file to render. |
| loadOptions | [LoadOptions](../../loadoptions) | The document load options. |

### Result
Viewer

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code loadOptions} is null. |


---


## Viewer(String filePath, [ViewerSettings](../../viewersettings) settings) function

 Initializes new instance of  Viewer class.
 
 Note: 
 Learn more
   
     
         More about file types supported by GroupDocs.Viewer:
       Document formats supported by GroupDocs.Viewer
     
     
         More about GroupDocs.Viewer for Java features:
      Developer Guide
     
   
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePath | String | The path to the file to render. |
| settings | [ViewerSettings](../../viewersettings) | The Viewer settings. |

### Result
Viewer

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code settings} is null. |


---


## Viewer(Path filePath, [ViewerSettings](../../viewersettings) settings) function

 Initializes new instance of  Viewer class.
 
 Note: 
 Learn more
   
     
         More about file types supported by GroupDocs.Viewer:
       Document formats supported by GroupDocs.Viewer
     
     
         More about GroupDocs.Viewer for Java features:
      Developer Guide
     
   
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePath | Path | The path to the file to render. |
| settings | [ViewerSettings](../../viewersettings) | The Viewer settings. |

### Result
Viewer

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code settings} is null. |


---


## Viewer(String filePath, [LoadOptions](../../loadoptions) loadOptions, [ViewerSettings](../../viewersettings) settings) function

 Initializes new instance of  Viewer class.
 
 Note: 
 Learn more
   
     
         More about file types supported by GroupDocs.Viewer:
       Document formats supported by GroupDocs.Viewer
     
     
         More about GroupDocs.Viewer for Java features:
      Developer Guide
     
     
         More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java:
      How to load and view document with GroupDocs.Viewer
     
   
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePath | String | The path to the file to render. |
| loadOptions | [LoadOptions](../loadoptions) | The document load options. |
| settings | [ViewerSettings](../../viewersettings) | The Viewer settings. |

### Result
Viewer

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code settings} is null. |


---


## Viewer(Path filePath, [LoadOptions](../../loadoptions) loadOptions, [ViewerSettings](../../viewersettings) settings) function

 Initializes new instance of  Viewer class.
 
 Note: 
 Learn more
   
     
         More about file types supported by GroupDocs.Viewer:
       Document formats supported by GroupDocs.Viewer
     
     
         More about GroupDocs.Viewer for Java features:
      Developer Guide
     
     
         More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java:
      How to load and view document with GroupDocs.Viewer
     
   
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| filePath | Path | The path to the file to render. |
| loadOptions | [LoadOptions](../loadoptions) | The document load options. |
| settings | [ViewerSettings](../../viewersettings) | The Viewer settings. |

### Result
Viewer

### Error

| Error | Condition |
| --- | --- |
 | IllegalArgumentException | Thrown when {@code settings} is null. |


---


