---
title: LotusNotesViewInfo
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Represents view information for Lotus Notes database storage.
type: docs
weight: 19
url: /nodejs-java/com.groupdocs.viewer.results/lotusnotesviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface LotusNotesViewInfo extends ViewInfo
```

Represents view information for Lotus Notes database storage.

The LotusNotesViewInfo interface defines the contract for accessing and manipulating view information for Lotus Notes database storage in the GroupDocs.Viewer component. It provides methods to retrieve information such as notes count, and other properties.

Example usage:

```

 try (Viewer viewer = new Viewer("document.nsf")) {
     final LotusNotesViewInfo viewInfo = (LotusNotesViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is LotusNotesViewInfoImpl.*
## Methods

| Method | Description |
| --- | --- |
| [getNotesCount()](#getNotesCount--) | Retrieves the count of notes in the storage. |
| [setNotesCount(int count)](#setNotesCount-int-) | Sets the count of notes in the storage. |
### getNotesCount() {#getNotesCount--}
```
public abstract int getNotesCount()
```


Retrieves the count of notes in the storage.

**Returns:**
int - the count of notes in the storage.
### setNotesCount(int count) {#setNotesCount-int-}
```
public abstract void setNotesCount(int count)
```


Sets the count of notes in the storage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| count | int | the count of notes in the storage. |

