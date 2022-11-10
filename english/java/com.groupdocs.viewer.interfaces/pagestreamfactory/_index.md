---
title: PageStreamFactory
second_title: GroupDocs.Viewer for Java API Reference
description: Defines the methods that are required for instantiating and releasing output page stream.
type: docs
weight: 16
url: /java/com.groupdocs.viewer.interfaces/pagestreamfactory/
---```
public interface PageStreamFactory
```

Defines the methods that are required for instantiating and releasing output page stream.
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
| pageNumber | int | The number of a page. |

**Returns:**
java.io.OutputStream - OutputStream used to write output page data.
### closePageStream(int pageNumber, OutputStream pageStream) {#closePageStream-int-java.io.OutputStream-}
```
public abstract void closePageStream(int pageNumber, OutputStream pageStream)
```


Releases the stream created by \#createPageStream(int).createPageStream(int) method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of a page. |
| pageStream | java.io.OutputStream | OutputStream created by \#createPageStream(int).createPageStream(int) method. |

