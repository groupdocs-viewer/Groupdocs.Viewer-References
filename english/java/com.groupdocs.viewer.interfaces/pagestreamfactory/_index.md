---
title: PageStreamFactory
second_title: GroupDocs.Viewer for Java API Reference
description: Defines the methods that are required for instantiating and releasing an output page stream.
type: docs
weight: 16
url: /java/com.groupdocs.viewer.interfaces/pagestreamfactory/
---```
public interface PageStreamFactory
```

Defines the methods that are required for instantiating and releasing an output page stream.

The  PageStreamFactory  interface declares methods that are used to create and release an output page stream. Implementations of this interface should provide the necessary functionality to create a page stream for writing output page data, as well as release any resources associated with the page stream.

Example usage:

```

 final PageStreamFactory pageStreamFactory = new PageStreamFactory() {
     public OutputStream createPageStream(int pageNumber) {
         // Custom implementation to create and return an output page stream for the specified page number
     }

     @Override
     public void closePageStream(int pageNumber, OutputStream pageStream) {
         // Custom implementation to release any resources associated with the output page stream
     }
 };

 PngViewOptions pngViewOptions = new PngViewOptions(pageStreamFactory);
 // Use pngViewOptions in Viewer
 
```
## Methods

| Method | Description |
| --- | --- |
| [createPageStream(int pageNumber)](#createPageStream-int-) | Creates the stream used to write output page data. |
| [closePageStream(int pageNumber, OutputStream pageStream)](#closePageStream-int-java.io.OutputStream-) | Releases the stream created by \#createPageStream(int).createPageStream(int) method. |
### createPageStream(int pageNumber) {#createPageStream-int-}
```
public abstract OutputStream createPageStream(int pageNumber)
```


Creates the stream used to write output page data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of the page. |

**Returns:**
java.io.OutputStream - the OutputStream used to write output page data.
### closePageStream(int pageNumber, OutputStream pageStream) {#closePageStream-int-java.io.OutputStream-}
```
public abstract void closePageStream(int pageNumber, OutputStream pageStream)
```


Releases the stream created by \#createPageStream(int).createPageStream(int) method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of the page. |
| pageStream | java.io.OutputStream | The OutputStream created by \#createPageStream(int).createPageStream(int) method. |

