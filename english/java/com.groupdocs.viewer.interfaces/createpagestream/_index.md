---
title: CreatePageStream
second_title: GroupDocs.Viewer for Java API Reference
description: Represents interface that instantiates stream used to write output page data.
type: docs
weight: 11
url: /java/com.groupdocs.viewer.interfaces/createpagestream/
---```
public interface CreatePageStream
```

Represents interface that instantiates stream used to write output page data.
## Methods

| Method | Description |
| --- | --- |
| [invoke(int pageNumber)](#invoke-int-) | The method must return OutputStream that will be used to write output page data. |
### invoke(int pageNumber) {#invoke-int-}
```
public abstract OutputStream invoke(int pageNumber)
```


The method must return OutputStream that will be used to write output page data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Number of the page |

**Returns:**
java.io.OutputStream - The stream used to write output page data.
